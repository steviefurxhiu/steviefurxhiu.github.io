---
layout: post
title: On Scientific Misconduct
categories:
- General
feature_image: "https://0.gravatar.com/userimage/244506044/7491748ddcfec0168d99b19ad7d506ea?size=256"
---

Previously, I discussed about the scientific method, introducing it together with a very brief history of science. 
This method for conducting research, which laid a more concise and absolute protocol on how to conduct science, requires factchecking for achieving its final approval status. 
This process often occurs after such discoveries manage to get published in journals. 
To speed and contribute to scientific progress, one would “blindly believe” everything that appears in scientific journals is true. 
Unfortunately, it occasionally occurs that claims of great scientific progresses hide erratic concepts, sometimes done so on purpose. 
This current blog’s topic will address such cases of scientific misconduct with two examples close to my field of research. 
After introducing and examining the stories, I will draw some conclusions and differences between the two cases. 
Finally, I will discuss on how to avoid early excitement about scientific results and why factchecking is important.  

#### Why do we cheat when doing science?

There can be many reasons to why someone would cheat when doing science. 
If we consider that a general distribution holds for the scientists’ population, most of its bulk would be comprised of normal individuals. 
We generally consider the most of these individuals to not cheat by nature, thereby greatly reducing the population of the rest of the scientists. 
The rest would be comprised of lovely people who generally would love to help and contribute for the goodness of science, whereas its opposite, 
“evil people” would be more interested in their personal gains thus contributing negatively to science. 

<img src="https://imgur.com/Gb4kQFu.jpg" alt="Alt text" width="800">     

Reasons for cheating would vary ranging from personal fame to economic, but importantly the fraudsters would definitively know how and where to cheat. 
Below I will discuss two stories where fraudulent (or misunderstood) science was published. 
The first example is an old story of how a scientist at Bells Lab tried to fake discovering a way to make molecular transistors, 
the backbone of computers using materials that were though to not work. The second story is more recent and is about two professors 
from Korea university who claimed finding the room temperature superconductors.  

#### Two cases: The Schön scandal and LK99 room temperature superconductor

The Schön scandal, which occurred between 2000 and 2001, left the most wounds in the scientific community and it involved a scientist at Bell Labs. 
Jan Hendrick Schön started his career as a postdoc right after completing his PhD and was offered the opportunity of the century for a scientist 
in his field at one of the world’s most famous physics institutions. Though Bell Labs did not belong to academia some of the then breakthroughs 
in solid state and condensed matter physics were pioneered there and the institution had an almost “godlike” reputation in science. 
Our protagonist, Hendrick, started succeeding at a high pace and claimed big breakthroughs in the field of microelectronics, 
such as single molecule transistors and superconductivity in organic materials, which could not be replicated by his peers at the same and other institutions. 
These big claims, which steadily increased in number and were still difficult to replicate and the increased scepticism led to an independent 
investigation on his publications by his colleagues after getting access to his raw data. Proof of fraud and data manipulation had been observed 
by the investigative committee which led to him being fired from Bells Lab and his PhD degree being retracted. 
This incident left many open questions about the responsibility of collaborators and if journals should investigate such accounts of fraud.

Another case of scientific fraud which is more recent but did not leave as bigger scars as the previous story was the erroneous report of LK-99 as room temperature superconductor. 
It all started with a team of researchers from Korea University publishing a paper intitled “The First Room-Temperature Ambient-Pressure Superconductor” in July 2023. 
In the field of superconductor science, a room temperature superconductor is thought of as the “holy grail” of its research field, thereby reports of superconductivity 
in ambient conditions are usually approached with high scepticism. In this case, an initial positivism was fuelled by many scientists were able to replicate the material 
due to its straightforward synthesis method but by mid-August the community consensus was that LK-99 was not a superconductor at all and the drops in resistance observed 
in the original paper came from copper impurities in its crystalline structure. Though, it is difficult to attribute this story to fraud due to the nature of the report 
itself aligning more to the narrative of not having understood its own data properly. This begs the question if indeed misunderstood data related to big scientific 
discoveries should be published at all.

#### Moral of the stories and how to detect fraud

Though, the two stories are different in their development there are some commonalities. In both cases scientists claimed important discoveries, 
which were later debunked as false. One of the most important factors was the ability to reproduce this data. 
For the LK-99 story this was easily done as the researchers provided crystallographic data like XRD which allowed many groups around the world 
to synthesize the same compound (see image below). 

<img src="https://imgur.com/DuI2rJT.jpg" alt="Alt text" width="800">     

Unfortunately, for the Schön story, this was not the case as his results could not be reproduced by his colleagues and external researchers. 
In fact, the ability for others to reproduce the reported data is one of the most important factors when publishing in a scientific journal. 
Not being able to reproduce others’ data should already hint to some scepticism regarding the reported analysis. 
Though it is important to note that sometimes multiple trials are needed for reproducing an experiment.

In the case the data is falsified this might be more difficult to detect. 
Regarding Hendrick Schön, a committee of experts in these fields was selected to consult his works and find cases of fraud. 
They were able to perform the so-called “second derivative test” for determining if the observed data was observed (see below). 

<img src="https://imgur.com/UqiicVK.jpg" alt="Alt text" width="800">   

The second derivative tests consist in conducting the derivative of an exponential distribution until getting a constant value distribution (e.g. for quadratic distribution => d^2/dx^2 (x^2) = 2). 
In the case of Hendrick, the committee noticed an earie similarity in his data points at 50 K on the first derivative of the plotting data vs temperature. 
Upon conducting another derivative, the scientists noticed that the data had a constant distribution up to the high decimal points and the noise at 50 K had the same shape 
for all his data sets. This fact could not have occurred through sheer causality, even for redundant data which is produced by instrumental noise. 
Being caught Hendrick admitted to data manipulation and fabrication and as a result (also involved in other falsified publications) 
did not accept the prestigious William L. McMillan Award from the University of Illinois which he was supposed to be awarded. 
Furthermore, his PhD degree was also retracted from his Alma Matter, the University of Konstanz, and to this day he got more than 
20% of his publications marked as an erratum (non-valid papers).  

The importance of reproducing other’s result is crucial for the advancement of science. 
There are many programs which allow generating datasets from images found in publications. 
One famous program called [WebPlotDigitizer](https://automeris.io/) allows for generating a csv file based on data pixel’s colours. 
I hope this short blog conveys the idea that cheating in science is counterproductive for both the cheater and 
the community in general and doing so can ruin its own reputation and stain a research field. 
Most importantly, delivering “justice” can also be effective in science and as seen in these cases excessive claims 
which are not backed up and are not reproducible are usually dismissed in the long run. 

In my upcoming blogs I will diverge more to other topics such as scientific concepts and techniques, some of which I am currently using for my own research.
Below you can find the references of the paper regarding LK-99 and the misconduct review on Hendrick Schön. 
I have also suggested some videos on Youtube and further reading for those interested in 

References

Lee, Sukbae, Ji-Hoon Kim, and Young-Wan Kwon. "The first room-temperature ambient-pressure superconductor." arXiv preprint arXiv:2307.12008 (2023)
Beasley, Malcolm R. "Report of the Investigation Committee on the possibility of Scientific Misconduct in the work of Hendrik Schon and Coauthors." Lucent Technol. 25 (2002): 1

Below I would like to reccomend further materials for exploring this topic:

- Book: "Corrupt Cultures, Cheating in Science and Society" by Roy Yorke Calne
- Youtube Video: https://www.youtube.com/watch?v=nfDoml-Db64
- [The man who almost faked his way to a Nobel Prize](https://www.youtube.com/watch?v=nfDoml-Db64)



