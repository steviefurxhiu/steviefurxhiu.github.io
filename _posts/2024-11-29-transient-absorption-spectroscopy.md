---
layout: post
title: Transient Absorption Spectroscopy
categories:
- Methods
feature_image: "https://0.gravatar.com/userimage/244506044/7491748ddcfec0168d99b19ad7d506ea?size=256"
---

Transient absorption (TA) spectroscopy is an optical pump-probe spectroscopy method that allows the time dependent study of photogenerated species 
of excited molecules, materials, and devices. Its discovery paved the way for the field of ultrafast chemistry (femtochemistry) and granted the 1967 Nobel Prize in Chemistry 
to Manfred Eigen (Max Planck Institute), Ronald Weyforth Norrish (Cambridge), and George Porter (Cambridge). 
According to Science’s report from 1967 [1]: “[…] in recognition of important new developments in the study of very fast chemical reactions. 
The procedure followed, in every case, is to shift systems from equilibrium by an energy pulse of as short duration as possible and then to follow 
the subsequent change as the systems return to an equilibrium state.” At the time of this technique’s early days, scientists were using energy beams to perturbate 
samples in equilibrium ad observing changes in the system and determining its origins.  

### TA Principle    

In the case of TA spectroscopy, the sample is excited with light from the near-IR up to UV/VIS regime (~0.4 eV to ~4.0 eV). 
Importantly the spectroscopic technique presents two light beams, one called probe, a polychromatic light or sometimes referred to as white light 
(has a range of wavelengths) which roughly corresponds to the steady state absorption, and pump (or photoexcitation), which has a determinate wavelength/energy. 
These beams can be measured with a time delay in between, thus generating a 2D array of data of the change in absorption in the probe wavelength/energy 
and time delay (see below).   

<img src="https://imgur.com/yHrjice.jpg" alt="Alt text" width="650">    

This change in absorption (ΔA), which corresponds to the difference of the sample after (t > 0) and before (t = 0) photoexcitation derives from the measured 
transmittance generated from the computer. According to the Beer-Lambert law absorption (A) is equal to the inverse logarithm of transmission (or transmitted 
light per incident light). In this method, two different absorptions arise, one after photoexcitation (A Pump ON) and one before (A Pump OFF). 
This process is measured by the setup, in which the transmitted light intensity is measured before and after photoexcitation (see below for formula derivation).   

<img src="https://imgur.com/7NGuf2p.jpg" alt="Alt text" width="900">     

As mentioned before the instrument generates a 2D array of the change in absorption (ΔA) per pump delay time and probe wavelength. 
Usually this is plotted as a 2D heatmap, where the changes in ΔA can be seen in these arrays. 
Though this already conveys some information regarding the experiment, 
there exists a clearer way to represent the changes in ΔA by taking either horizontal or vertical slices of the spectrum.    

<img src="https://imgur.com/vVk8D4M.jpg" alt="Alt text" width="900">     

In the figure above I have plotted the TA spectrum of monolayer molybdenum disulfide as a 2D heatmap (left image). 
To better represent the shape of the spectrum, I have plotted the intervals from 0 – 2 ps in linear scale and from 2 to ca 3000 ps in logarithmic scale (y-axis). 
Here I have picked two points in the spectrum A (black) and B (red) and at these points the spectrum has been sliced horizontally and vertically (dotted lines) 
which we can either refer by “time slice” and “probe slice”. Results are plotted in the right figure.     

- A time slice corresponds to a horizontal slice of the spectrum (in this case), where we plot ΔA per Probe wavelength at selected times (upper right). 
This allows for observing how the shape of the TA spectrum changes with probe wavelength per selected time intervals. It is usually conducted to show 
the evolution and shifts in wavelength of the TA.   

- A probe slice corresponds instead to a vertical slice of the spectrum (in this case), where we plot ΔA per Pump delay at selected probe wavelengths (upper right). 
This allows for observing how the ΔA at a selected probe wavelength changes with time.  
It is usually referred to as decay plot in the TA jargon and it is usually plotted to observe the time evolution upon photoexcitation (pump at t=0) 
of a particular ΔA signal, namely, how charge carrier (electrons, holes, excitons etc) population change with time. In my example above I chose two 
points at negative and positive ΔA, respectively referred to as Ground State Bleach (ΔA < 0) and Photo-induced absorption (ΔA > 0).    

Later on, I will explain the meaning of these terms and how they are originated, but in short with a probe slice or decay at a selected wavelength 
we can observe the cay of these signals. It is also important to note that through fitting with exponential decays we can also get information on 
the rate of decay of these signals, but this will be discussed later on in more detail.    

Previously, I compared the probe signal to the steady state absorption. Physically, this phenomenon refers to the rate of transfer of energy upon 
excitation of a sample and can generate a plot of absorbance per energy wavelength. The same can also be said for the pump, but unlike the probe which 
has a range of wavelengths the pump has a set photoexcitation wavelength. In the TA experiment, we can imagine thus measuring the absorption (probe) 
of a sample after the sample has already been photoexcited (pumped), which would in turn yield a different absorption image. 
This experimental method yields different effects which in turn can give rise to positive or negative ΔA. 
The image below schematically depicts the origin of these effects by employing band diagrams.    

<img src="https://imgur.com/f2vnAex.jpg" alt="Alt text" width="900">    

- Ground State Bleach (GSB or photobleaching) is a negative ΔA signal (ΔA < 0) originating from the so-called Pauli blocking. 
After photoexcitation (or pump) the population of charge carriers at the ground state (S0) cannot be further excited (by probe) at higher lying energy 
levels due such higher levels being fully occupied. This in turn decreases the absorbance signal because carriers cannot get photoexcited. 
Usually, GSB occurs around the region where the sample presents a peak from the steady state absorption measurement.     

- Stimulated Emission (SE) is also a negative ΔA signal (ΔA < 0), normally of lesser magnitude than GSB, which originates from carriers at higher lying levels 
(e.g. S1) relaxating to the S0. SE can occur in the region in which a sample e.g. emit light during a fluorescence measurement (with same photoexcitation as 
pump in TA experiment).      

- Excited State Absorption (ESA) is instead a positive ΔA signal (ΔA > 0) originating from carriers lying at excited levels e.g. S1 being further excited at 
even higher bands e.g. S2 (or more e.g. Sn). Unlike GSB and SE, which can be observed from other experiments, ESA can only be observed from TA measurements 
(or very similar methods).     

#### Different Types of Measurements      

With this simplistic overview of the TA measurement and setup and its effects, it is important to clarify that there can be different types of setups to 
accommodate for the different processes that wish to be investigated:   

- Femtosecond TA (fs or 10^-15 s): used for probing ultrafast dynamics such as electron excitation, energy transfer, and coherent vibrational motion. 
Photophysical and photochemical processes investigated: Excited-state relaxation, charge transfer, formation of excitons or polarons, studying systems 
like semiconductors, organic photovoltaics, light-harvesting complexes, and photocatalysts.    

- Picosecond TA (ps or 10^-12 s): used for probing intermediate timescales between ultrafast electronic processes and slower vibrational or structural dynamics. 
Processes such as: intersystem crossing, vibrational cooling, or delayed fluorescence.   

- Nanosecond TA (ns or 10^-9 s) capturing slower processes such as: phosphorescence, exciton recombination, triplet-triplet annihilation, 
charge separation and recombination in donor-acceptor systems.  
Suitable for biological samples or systems with long-lived excited states.   

#### TA Setup   

<img src="https://imgur.com/ikWGl1x.jpg" alt="Alt text" width="800">    

1. Laser Source:
- Lasing Medium: Ytterbium-doped Potassium Gadolinium Tungstate (e.g. Yb:KGW) generates a fundamental beam at 1030 nm.
2. Beam Splitting:
- Beam Splitter: Splits the laser into:
- - Pump Beam: About 10% directed to an Optical Parametric Amplifier (OPA).
- - Probe Beam: The remaining 90% used for white-light continuum generation.
3. Optical Parametric Amplifier (OPA):
- Purpose: Converts the 1030 nm wavelength to a tunable excitation wavelength across visible and near-IR.
- Process:
- - Pumping: Crystals in the OPA are excited by the laser output, interacting with the white-light continuum.
- - Wavelength Selection: Adjusts laser and crystal angles to match group velocities for energy transfer.
- - Tuning: Can operate in:
- - - Visible: 475 to 750 nm for the signal.
- - - Near-IR: 1100 to 1600 nm for the signal.
- - Selection: Uses polarizers or filters to select desired wavelengths.
4. Pump Pulse Delivery:
- Chopper: Blocks alternating pump shots for pump-on and pump-off differentiation.
- Mirrors: Guide the pump pulses to the sample, with a polarizer to minimize scatter.
5. Probe Beam Preparation:
- White Light Generation: From the probe beam.
- Delay Stage: Adjusts probe's path length for timing control up to 3 ns.
6. Sample Interaction:
- Angle: Both beams interact with the sample at an 8° angle.
- Excitation: Pump pulse excites the sample.
- Probing: Probe pulse, after a delay, interacts with the sample post-excitation.
7. Detection:
- Discarding Pump: The pump pulse is removed post-sample interaction.
- Polarizer: Before the detector, blocks scattered light ensuring only the probe signal is measured.

This setup is critical for ultrafast spectroscopy, allowing for the study of how light at different wavelengths affects materials or biological samples over very short timescales.

### Chirp correction and coherent artifacts (for fs-TA)    

<img src="https://imgur.com/ia7xzhh.jpg" alt="Alt text" width="900">     

I have plotted above a TA spectrum before and after conducting chrip correction. The TA spectrum also presents some small positive signals at 700 nm, 800 nm and 900 nm, which are also short lived if compared to the other signals. This signals are generally referred to coherent artifacts and together with chirp correction are important characteristics observed in fs-TA experiments:    

- Chirp corresponds to the change of a signal with time and occurs due to difference in wavelength of light signal. It is also referred to as group velocity dispersion (GVD), which causes the various wavelengths to arrive at slightly different times at the sample or detector. The result is a "chirped" pulse, where shorter (blue) wavelengths arrive earlier to the detector than longer (red) wavelengths. In the image above the spectrum presents a clear difference between before and after pump, thus chirp correction is done using mathematical models for correcting time zero.   

- Coherent artifact in transient absorption spectroscopy refers to an ultrafast, non-resonant signal that arises due to the coherent interaction of pump and probe pulses with the sample, rather than from the population dynamics of the excited states in the system. These artifacts are typically observed at or near time-zero, where the pump and probe pulses temporally overlap. 
   
### Hyperspectral fitting   

Sometimes TA data can be too difficult to understand straightforwardly since its signal can be composed of many overlaying species. The TA setup also does not allow for
separating signals as it measures the changes in absorption along the whole probe region, which can overlay and convey superimposed signals (e.g. GB may be hidden by ESA of another species).  
For this reason, scientists have developed hyperspectral fitting methods, which allows the derivation of additional information based on existing
mathematical fitting models. To my knowledge, the most famous and easy program, which requires no programming knowledge is 
[Glotaran](https://glotaran.org/demonstration.html). Glotaran stands for global and target analysis, meaning either fitting multiple time-resolved spectra
simultaneously by assuming that the data can be described by a common set of kinetic components or decay rates, or targetting more specific spectro-temporal 
contributions to known physical or chemical species and their transitions [2]. 
Besides this program, there are many similar models and methods such as e.g. [Pyglotaran](https://github.com/glotaran/pyglotaran) and 
[KiMoPack](https://pypi.org/project/KiMoPack/) which may require some programming knowledge but allow for more easy manipulation of parameters [3][4].    

Hyperspectral fitting methods can also be created from scratch. In most of these methods, a distribution function (e.g. Gaussian or Lorentzian) can be used to 
describe an absorption transition and in turn the difference between of after and before photoexcitation would correspond to the TA spectrum. From the changes of the
distribution parameters like amplitude, width and peak position, we can obtain information on the photophysical processes occurring in the material.   
Nowadays with the advent of AI, there is a stronger effort to implement LLM (Large Language Models) for better predicting and deriving information on time dependent measurements.    

### Conclusions    

This blog aimed to introduce TA spectroscopy with a rudimentary basis of its pronciples and measurement possibilities, though, the field itself is quite big and there are many 
articles published every year claiming new exciting breakthroughs. TA is one kind of pump-probe spectroscopy and there are many more which depending on the energy range (e.g. in THz spectroscopy around 0.001–0.01 eV) allow for studying different systems.      
In my next blog I will discuss Prof. Richard Feynman's famous lecture "There's Plenty of Room at the Bottom" and how his vision of the nano sciences looks today.

#### References  

[1] Eyring, Henry, and Edward M. Eyring. "Nobel Prizes: Four Named for International Award. 2. Chemistry." Science 158.3802 (1967): 746-748.  
[2] Snellenburg JJ, Laptenok S, Seger R, Mullen KM, van Stokkum IHM. Glotaran: a java-based graphical user interface for the R package    TIMP.JournalofStatisticalSoftware2012;49(3):1–22,ISSN1548-7660. http://www.jstatsoft.org/v49/i03.   
[3] van Stokkum, Ivo HM, et al. "Pyglotaran: a lego-like Python framework for global and target analysis of time-resolved spectra." Photochemical & Photobiological Sciences 22.10 (2023): 2413-2431  
[4] Müller, Carolin, et al. "KiMoPack: A python Package for Kinetic Modeling of the Chemical Mechanism." The Journal of Physical Chemistry A 126.25 (2022): 4087-4099





