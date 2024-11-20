---
layout: post
title: Transient Absorption Spectroscopy
categories:
- General
feature_image: "https://0.gravatar.com/userimage/244506044/7491748ddcfec0168d99b19ad7d506ea?size=256"
---

Transient absorption (TA) spectroscopy is an optical pump-probe spectroscopy method that allows the time dependent study of photogenerated species 
of excited molecules, materials, and devices. Its discovery paved the way for the field of ultrafast chemistry (femtochemistry) and granted the 1967 Nobel Prize in Chemistry 
to Manfred Eigen (Max Planck Institute), Ronald Weyforth Norrish (Cambridge), and George Porter (Cambridge). 
According to Science’s report from 1967 [1]: “[…] in recognition of important new developments in the study of very fast chemical reactions. 
The procedure followed, in every case, is to shift systems from equilibrium by an energy pulse of as short duration as possible and then to follow 
the subsequent change as the systems return to an equilibrium state.” At the time of this technique’s early days, scientists were using energy beams to perturbate 
samples in equilibrium ad observing changes in the system and determining its origins.  

### TA principle

In the case of TA spectroscopy, the sample is excited with light from the near-IR up to UV/VIS regime (~0.4 eV to ~4.0 eV). 
Importantly the spectroscopic technique presents two light beams, one called probe, a polychromatic light or sometimes referred to as white light 
(has a range of nm) which roughly corresponds to the steady state absorption, and pump (or photoexcitation), which has a determinate wavelength/energy. 
These beams can be measured with a time delay in between, thus generating a 2D array of data of the change in absorption in the probe wavelength/energy 
and time delay (see below).  

<img src="https://imgur.com/yHrjice.jpg" alt="Alt text" width="900">  

This change in absorption (ΔA), which corresponds to the difference of the sample after (t > 0) and before (t = 0) photoexcitation derives from the measured 
transmittance generated from the computer. According to the Beer-Lambert law absorption (A) is equal to the inverse logarithm of transmission (or transmitted 
light per incident light). The setup only measures the transmitted light before and after photoexcitation (see below). Maybe add more text.

<img src="https://imgur.com/7NGuf2p.jpg" alt="Alt text" width="900">  

As mentioned before the instrument generates a 2D array of the change in absorption (ΔA) per pump delay time and probe wavelength. 
Usually this is plotted as a 2D heatmap, where the changes in ΔA can be seen in these arrays. Though this already conveys some information regarding the experiment, 
there exists a clearer way to represent the changes in ΔA by taking slices of the spectrum at horizontal or vertical.

<img src="https://imgur.com/vVk8D4M.jpg" alt="Alt text" width="900">  

In the figure above I have plotted the TA spectrum of monolayer molybdenum disulfide (MoS2) as a 2D heatmap (left image). 
To better represent the shape of the spectrum, I have plotted the intervals from 0 – 2 ps in linear scale and from 2 to ca 3000 ps in logarithmic scale. 
Here I have picked two points in the spectrum A (black) and B (red) and at these points the spectrum has been sliced horizontally and vertically (dotted lines) 
which we can either refer by “time slice” and “probe slice”. Results are plotted in the right figure.  

A time slice corresponds to a horizontal slice of the spectrum (in this case), where we plot ΔA per Probe wavelength at selected times (upper right). 
This allows for observing how the shape of the TA spectrum changes with probe wavelength per selected time intervals. It is usually conducted to show 
the evolution and shifts in wavelength of the TA.   
A probe slice corresponds instead to a vertical slice of the spectrum (in this case), where we plot ΔA per Pump delay at selected probe wavelengths (upper right). 
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

<img src="https://imgur.com/RF45BWO.jpg" alt="Alt text" width="900">  

-Ground State Bleach (GSB or photobleaching) is a negative ΔA signal (ΔA < 0) originating from the so-called Pauli blocking. 
After photoexcitation (or pump) the population of charge carriers at the ground state (S0) cannot be further excited (by probe) at higher lying energy 
levels due such higher levels being fully occupied. This in turn decreases the absorbance signal because carriers cannot get photoexcited. 
Usually, GSB occurs around the region where the sample presents a peak from the steady state absorption measurement.  

-Stimulated Emission (SE) is also a negative ΔA signal (ΔA < 0), normally of lesser magnitude than GSB, which originates from carriers at higher lying levels 
(e.g. S1) relaxating to the S0. SE can occur in the region in which a sample e.g. emit light during a fluorescence measurement (with same photoexcitation as 
pump in TA experiment).   

-Excited State Absorption (ESA) is instead a positive ΔA signal (ΔA > 0) originating from carriers lying at excited levels e.g. S1 being further excited at 
even higher bands e.g. S2 (or more e.g. Sn). Unlike GSB and SE, which can be observed from other experiments, ESA can only be observed from TA measurements 
(or very similar methods).  

#### TA measurement setup

<img src="https://imgur.com/ikWGl1x.jpg" alt="Alt text" width="900">  

#### Types of TA measurements

With this simplistic overview of the TA measurement and setup and its effects, it is important to clarify that there can be different types of setups to 
accommodate for the different processes that wish to be investigated:

-Femtosecond TA (fs or 10^-15 s): used for probing ultrafast dynamics such as electron excitation, energy transfer, and coherent vibrational motion. 
Photophysical and photochemical processes investigated: Excited-state relaxation, charge transfer, formation of excitons or polarons, studying systems 
like semiconductors, organic photovoltaics, light-harvesting complexes, and photocatalysts.

-Picosecond TA (ps or 10^-12 s): used for probing intermediate timescales between ultrafast electronic processes and slower vibrational or structural dynamics. 
Processes such as: intersystem crossing, vibrational cooling, or delayed fluorescence.

-Nanosecond TA (ns or 10^-9 s) capturing slower processes such as: phosphorescence, exciton recombination, triplet-triplet annihilation, 
charge separation and recombination in donor-acceptor systems.  
Suitable for biological samples or systems with long-lived excited states.

### Different types of measurements


Talk on what can you measure with TA quantitatively and qualitatively (ta shape CM etc etc)

### How to conduct a good TA experiment and data analysis

#### Beam allignment

Talk about beam alignment fine tuning probe at high focus etc etc 

#### Chirp correction (for fs-TA)

Talk on how to make a good TA measurement proper beam alignment etc etc check with fine tuning
Chirp correction 

<img src="https://imgur.com/xaYEoSd.jpg" alt="Alt text" width="900">   

#### Coherent artifact


#### Hyperspectral fitting

Also talk about glotaran pyglotaran and how to make other examples of global analysis

#### Reference

[1] Eyring, Henry, and Edward M. Eyring. "Nobel Prizes: Four Named for International Award. 2. Chemistry." Science 158.3802 (1967): 746-748.  
[]





