## ***« Rêveries »*** – Fine Art Photography Book

This page contains the digital reference edition of *Rêveries*, a fine art photography book, and an overview of my workflow.

## 35,000-Foot Overview
This is a high-level summary of my workflow, covering exposure, RAW development, printing, and archival longevity. Links are provided for further exploration.



## About This Project
From capture to print to your eyes, I do my utmost to ensure that every photon counts, that my prints reveal scenes where light comes alive and awakens deep emotion. This project draws on all my knowledge and expertise. Art, technique and craftsmanship come together in a quest where time itself becomes raw material.
Yes, this project was born of the incredible stability of carbon pigment inks. Just imagine: over 400 years of permanence. That's all it took to unite everything around this phenomenal characteristic.
In my opinion, you don't put something that can last for centuries in a bag that will degrade in a few months. Hence, the idea of a book, its covers and its box, made of noble and archival materials, hand-crafted with great care: a companion, an accomplice, a messenger of time itself.



## Exposure
ETTR (Expose To The Right) maximizes the signal-to-noise ratio (SNR), the measure of quality of the image.  
[Learn more about ETTR](https://en.wikipedia.org/wiki/Exposing_to_the_right) |  
[RawDigger – Calibrating exposure for dynamic range](https://www.rawdigger.com/howtouse/calibrate-exposure-meter-to-improve-dynamic-range)



## RAW Development & Conversion
Scene-referred development preserves the integrity of raw sensor data. A [3D LUT](https://3dlutcreator.com/) from a ColorChecker ensures color and luminance accuracy (ΔE00 < 2).  
[Scene-referred vs. Display-referred](https://ninedegreesbelow.com/photography/display-referred-scene-referred.html) |  
[Darktable – Scene-referred workflow](https://docs.darktable.org/usermanual/3.6/en/overview/workflow/edit-scene-referred/)



## Post-Processing
A billion+ photos are taken every day. If you want to stand out, be creative, and please make your image unique.


# Printing

Just as my development process is meticulously calibrated, my printing process is equally refined. My printing follows industry best practices. I started by finding the best possible printer, inks and paper for this project. 

[ICC White Papers](https://www.color.org/whitepapers.xalter)

## ICC Profiling & Paper Selection

I'm using an i1 Pro 2 spectrophotometer for all my color management work.  
[i1 Pro 2 – X-Rite](https://www.xrite.com/categories/calibration-profiling/i1photo-pro-2)

I avoid papers with Optical Brightening Agents (OBAs) due to their long-term instability. While they enhance brightness under certain lighting conditions, OBAs degrade over time, causing color shifts. For short-term displays, they can work fine. For archival prints, I avoid them.  

I use ColorThink Pro and GamutVision to analyze gamut, black & white points, and other critical characteristics.  
[ColorThink Pro](https://www.chromix.com/colorthink/#overview)  
[GamutVision](http://www.gamutvision.com/modules.php?name=Download)

With my i1 Pro, I create ICC profiles for each paper I'm using, with i1Profiler. I also use ArgyllCMS for device link profiles, mapping colors from my image masters to the paper’s gamut while preserving color appearance. This is called [Image Dependent Gammut Mapping](https://argyllcms.com/doc/Scenarios.html#LP3) 



## Black & White Printing

Most printers are RGB-based. Even in B&W modes, they often use color inks. Printer manufacturers optimize for their own papers, leaving third-party papers without ICC profiles for B&W.  

I create B&W-specific ICC profiles with ABWProfileMaker, optimizing the printer’s B&W mode for quasi perfect linear grayscale.  
[ABW Profile Maker (GitHub)](https://github.com/doug3236/ABWProfilePatches)  

For even finer control, QuadTone RIP allows individual ink control for B&W printing only. 
[QuadTone RIP](http://www.quadtonerip.com/)

A perfectly neutral and linear grayscale print is the foundation. Giving it a soul is up to you know.



## Print Longevity – Epson SureColor P700 & Carbon-Based Inks

I chose the Epson SureColor P700 for its carbon-based pigment inks and their extraordinary longevity.

For specific performance data on using the Epson ABW mode on the P700, see Table 2 in the Wilhelm Imaging Research report. B&W prints exceed 400 years, under proper conditions, a book fully shields the prints from light—especially when stored in a box.  
[Wilhelm Imaging Research – Epson SureColor P700 & P900](https://www.wilhelm-research.com/epson/WIR_Epson_SureColor_P700_and_P900_Printers_2021_07_23.pdf)


My prints are created using a calibrated process with carbon-based pigment inks and [ISO 9706-compliant](https://cdn.standards.iteh.ai/samples/17562/34a23f9c75e44bc0a5b582d3f3608d35/ISO-9706-1994.pdf), museum-quality paper—ensuring the highest age resistance. They are made to last.

## Final Thoughts  

A print isn’t just ink on paper; it’s the culmination of a process, an intention, and an experience.

The pursuit of perfection in printing is never-ending, but the goal is not just technical accuracy. The print must *live* and *breathe*.
