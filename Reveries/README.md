
## Rêveries 

This page contains the digital reference edition of *Rêveries*, a fine art photography book, and an overview of my workflow.

[Click here to download the PDF](https://github.com/GauvreauYves/FineArtBooks/raw/main/Reveries/pdf/ReveriesBilingueFinal_v2.0.pdf)


## The 35,000-Foot Overview
This is a high-level summary of my workflow, covering exposure, RAW development, printing, and archival details. Links are provided for further exploration.



## About This Project

From capture to print to your eyes, I do my utmost to ensure that every photon counts, that my prints reveal scenes where light comes alive and awakens deep emotion. This project draws on all my knowledge and expertise. Art, technique, and craftsmanship converge in perfect synergy, in the pursuit of excellence and permanence.

This project was born out of the incredible stability of carbon pigment inks. Just imagine: over 400 years of permanence. That was all it took to unite everything around this phenomenal characteristic. Hence, the idea of a book, its covers, and its archival box, made of noble and archival materials, hand-crafted with great care: a companion, an accomplice, a messenger of time itself.




## Exposure
ETTR (Expose To The Right) The short story, it maximizes the signal-to-noise ratio (SNR), a measure of quality of an image, and it also maximizes the dynamic range.  
[Learn more about ETTR](https://en.wikipedia.org/wiki/Exposing_to_the_right)  
[RawDigger – Calibrating exposure for dynamic range](https://www.rawdigger.com/howtouse/calibrate-exposure-meter-to-improve-dynamic-range)



## RAW Development & Conversion
Scene-referred development preserves the integrity and authenticity of captured raw sensor data. A correction LUT made from a ColorChecker shot in situ  ensures color and luminance accuracy to an even greater level (ΔE00 < 2). I use mostly DCRaw_emu in combination with PureRaw4 from DXO, 3DLut Creator, and of course Photoshop / Lightroom. Recently, I created a custom DCP profile from my cameras Spectral Sensitivity Function (SSF) that I use from Lightroom. This method also benefit from the correction Lut strategy. The actual workflow is a bit complex, as I use quite a few programs, but the results are worth it. It's a bit kind of Ansel Adams idea of exposing to obtain blacks with a 0.1d (density) above base + fog. If you tried to approach this before, you know what I mean...

[Scene-referred vs. Display-referred](https://ninedegreesbelow.com/photography/display-referred-scene-referred.html)   
[Darktable – Scene-referred workflow](https://docs.darktable.org/usermanual/3.6/en/overview/workflow/edit-scene-referred/)

[Lightroom](https://www.adobe.com/ca/products/photoshop-lightroom-classic.html)<BR> 
[Photoshop](https://www.adobe.com/ca/products/photoshop.html)<BR> 
[3DLut Creator](https://3dlutcreator.com/)<BR> 
[PureRaw](https://www.dxo.com/dxo-pureraw/)<BR> 
[LibRaw](https://www.libraw.org/)<BR> 
[Argyllcms](https://www.argyllcms.com/)<BR> 
[DCamProf](https://github.com/Beep6581/dcamprof)<BR> 
[Camera SSF](https://github.com/COLOR-Lab-Eilat/Spectral-sensitivity-estimation)



## Post-Processing
A billion+ photos are taken every day. If you want to stand out, be creative, and please make your image unique.


# Printing

Just as my RAW development process is meticulously calibrated, my printing process is equally refined. My printing follows industry best practices. I started by finding the best possible printer, inks and paper for this project. 


##  Paper Selection & ICC Profiling

I use an i1 Pro 2 spectrophotometer for all my color management work.  
[i1 Pro 2 – X-Rite](https://www.xrite.com/categories/calibration-profiling/i1photo-pro-2)  

To analyze gamut, black & white points, and other critical ICC profile characteristics, I use ColorThink Pro and GamutVision:  
[ColorThink Pro](https://www.chromix.com/colorthink/#overview)  
[GamutVision](http://www.gamutvision.com/modules.php?name=Download)<BR> 
[ICC White Papers](https://www.color.org/whitepapers.xalter) 

When evaluating paper, I consider several key factors:
- **Gamut**: I choose my printer with 10 or more inks, the more you have, the wider the gamut will be. With 10 inks you generally have a printer that can "print" or render colors outside the sRGB and Adobe RGB gamut. In other words it can print color your screen can't show you accurately. 
- **DMax**: For matte papers, achieving the deepest black possible is crucial, while glossy papers generally perform well in this regard.  
- **Paper whiteness**: I favor warmer papers (positive B* in CIELab) over cooler ones (negative B*) and L* as high as possible.  
- **Optical Brightening Agents (OBAs)**: I avoid them due to their long-term instability. While OBAs enhance brightness under UV light, they degrade over time, leading to color shifts. For short-term displays, they can be beneficial, but for archival purposes, I steer clear, as UV exposure also affects the permanence of most materials. 
- **Texture**: This is a non-objective characteristic of the paper, so you are on your own...

For profiling, I create custom ICC profiles for each paper using i1Profiler. I also use ArgyllCMS to create device link profiles, mapping colors from my image masters to the paper’s gamut while preserving color appearance and luminance.  

This is called "Image Dependent Gamut Mapping" , and it's probably one of the most refined and elegant approach to bringing my master image colors (ProPhoto RGB) into the printer’s (ink, paper) gamut, without creating a mess.

### **Why Image Dependent Gamut Mapping?**  

I do a lot of flowers photography and they often, if not always exhibit extreme saturation levels that exceed the gamut of most display and print colorspaces. Default gamut mapping methods can sometimes cause unwanted compression, loss of color relationships, or shifts in hue. To ensure my prints represent my original image without unnecessary distortions, I use **Image Dependent Gamut Mapping**.  

This method selectively maps colors to the printer's gamut while preserving their relative appearance as naturally as possible. By automating this process with a batch workflow, I maintain full control while keeping efficiency high and ensuring optimal results in every print.


[Image Dependent Gamut Mapping](https://argyllcms.com/doc/Scenarios.html#LP3)<br>
[Image Dependent Gamut Mapping (papers)](https://www.google.ca/search?q=%22image+dependent+gamut+mapping%22&rlz=1C2CHZN_enCA979CA979&sca_esv=d0d3ba676e08ed7a&sxsrf=AHTn8zp9IQt8upU5d-r_GmzLF-i5vH80SA%3A1741013460696&ei=1MHFZ66dKqbcptQPovrgYA&ved=0ahUKEwiu1_7GlO6LAxUmrokEHSI9GAwQ4dUDCBA&uact=5&oq=%22image+dependent+gamut+mapping%22&gs_lp=Egxnd3Mtd2l6LXNlcnAiHyJpbWFnZSBkZXBlbmRlbnQgZ2FtdXQgbWFwcGluZyIyBxAjGCcYrgJIzHtQAFindnABeAGQAQCYAaQBoAHDGKoBBTE4LjE0uAEDyAEA-AEBmAIgoAKrGcICChAjGIAEGCcYigXCAgQQIxgnwgIQEAAYgAQYsQMYQxiDARiKBcICBRAAGIAEwgIREC4YgAQYsQMY0QMYgwEYxwHCAgsQLhiABBjRAxjHAcICCxAAGIAEGJECGIoFwgIOEAAYgAQYsQMYgwEYigXCAggQABiABBixA8ICCxAAGIAEGLEDGIMBwgINEAAYgAQYsQMYQxiKBcICChAAGIAEGEMYigXCAgYQABgWGB7CAggQABgWGAoYHsICCxAAGIAEGIYDGIoFwgIFECEYoAGYAwCSBwUxMi4yMKAH8qMB&sclient=gws-wiz-serp)

With all this being said, I've chosen to use Hahnemühle Photo Rag 188 gsm, a little brother of the world renouned Photo Rag 308 gsm paper. An ISO-9706-1994 compliant paper.

[ISO 9706](https://cdn.standards.iteh.ai/samples/17562/34a23f9c75e44bc0a5b582d3f3608d35/ISO-9706-1994.pdf)


## Black & White Printing

Most printers are RGB-based. Even with B&W modes, it's recommended using RGB images (R=G=B), for best results. Printer manufacturers optimize this mode for their own papers, leaving third-party papers without ICC profiles for B&W.  

I create B&W-specific ICC profiles with ABWProfileMaker, optimizing the printer’s B&W mode for a quasi-perfect linear grayscale.  
[ABW Profile Maker (GitHub)](https://github.com/doug3236/ABWProfilePatches)  

For even finer control of the neutrality, QuadTone RIP allows individual ink control for B&W printing only.  
[QuadTone RIP](http://www.quadtonerip.com/)

A perfectly neutral and linear grayscale print is just the foundation. Giving it a soul, well this is up to you now.



## Print Longevity – Epson SureColor P700

I chose the Epson SureColor P700 for its carbon-based pigment black inks and their extraordinary longevity.

For performance data using the Epson ABW mode with the P700, see Table 2 in the Wilhelm Imaging Research report. B&W prints can last over 400 years under proper conditions. A book completely shields the prints from light, especially when stored in a box. 

[Wilhelm Imaging Research – Epson SureColor P700 & P900](https://www.wilhelm-research.com/epson/WIR_Epson_SureColor_P700_and_P900_Printers_2021_07_23.pdf)



## Final Thoughts  

A print isn’t just ink on paper; it’s the culmination of a process, an intention, and an experience.

My pursuit of excellence in printing is never-ending, but the goal is not just technical accuracy. The print must *live* and *breathe*, otherwise, it's just a piece of paper with black dots on it.

## Materials and archival practices

[Details here](MATERIALS.md)

## License & Usage

This work is licensed under a **Creative Commons Attribution-NonCommercial-ShareAlike (CC BY-NC-SA) License**.  
This means you are free to share and adapt this work for non-commercial purposes, as long as you credit the original author and distribute any modified versions under the same license.

These digital editions are low-resolution references only and do not represent the quality of the physical fine art prints I'm using for the books.

[Read the full license details here](https://creativecommons.org/licenses/by-nc-sa/4.0/)


[Back to the main library](../README.md)
