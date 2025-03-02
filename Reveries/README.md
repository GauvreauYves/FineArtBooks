# Rêveries – Fine Art Photography Book

This page contains the digital reference edition of *Rêveries*, a fine art photography book.

## About This Project
From capture to print, I do my utmost to ensure that every photon counts, that my prints reveal scenes where light takes form and evokes deep emotion. This project draws on all my knowledge and expertise. Art, technique, and craftsmanship come together in a quest where time itself becomes raw material.  

This project was born out of the incredible stability of carbon pigment inks.  
Just imagine: over 400 years of permanence. That alone was enough to align everything around this fundamental characteristic. You don’t put something that can last centuries in a biodegradable bag that decomposes in months. Hence, the idea of a book, its covers, and its archival box, made of noble and archival materials, handcrafted with great care, a companion, an accomplice, a messenger of time itself.  

---

## Exposure
ETTR (Expose To The Right) helps capture the maximum number of photons and optimize the signal-to-noise ratio (SNR).  
[Wikipedia – Learn more about ETTR](https://en.wikipedia.org/wiki/Exposing_to_the_right)  
[RawDigger – Calibrating exposure to improve dynamic range](https://www.rawdigger.com/howtouse/calibrate-exposure-meter-to-improve-dynamic-range)  

---

## RAW Development & Conversion
Scene-referred development ensures a faithful conversion of the raw sensor data.  
A 3D LUT derived from the capture of a ColorChecker in situ guarantees precise color and luminance correction (ΔE00 < 2).  

[Nine Degrees Below – Scene-referred vs. Display-referred](https://ninedegreesbelow.com/photography/display-referred-scene-referred.html)  
[Darktable – Scene-referred workflow](https://docs.darktable.org/usermanual/3.6/en/overview/workflow/edit-scene-referred/)  

---

## Post-Processing
A billion photos are taken every day. You want to stand out? Be creative, and especially make your image unique.  

---

# Printing

Just as my development process is meticulously calibrated, my printing process is equally refined.  

My approach to printing aligns with industry standards, with one key difference: I am both the printer and the client.  

[Color Management Standards – ICC White Papers](https://www.color.org/whitepapers.xalter)  

### ICC Profiling & Paper Selection

- Custom ICC Profiles:  
  I create my own ICC profiles using an i1 Pro 2 spectrophotometer.  
  [i1 Pro 2 – X-Rite](https://www.xrite.com/categories/calibration-profiling/i1photo-pro-2)  

- Paper Selection – No OBAs:  
  I dismiss papers containing Optical Brightening Agents (OBAs).  
  OBAs artificially enhance brightness by absorbing ultraviolet light and re-emitting it in the blue spectrum. However, this effect degrades over time, leading to unpredictable color shifts. For archival-quality prints, OBAs are not an option. But it could be an excellent choice in the short term... 

- Gamut & Print Quality Analysis:  
  I use ColorThink Pro and GamutVision to analyze gamut, black & white points, and other critical characteristics before finalizing my paper choice.  
  [ColorThink Pro](https://www.chromix.com/colorthink/#overview)  
  [GamutVision](http://www.gamutvision.com/modules.php?name=Download)  

- Profiling Software:  
  Using my i1 Pro, I create custom ICC profiles for every paper with i1Profiler.  
  I also use ArgyllCMS for advanced profiling tasks, such as creating device link profiles to map individually my masters colors to the paper’s gamut as intelligently as possible, without crushing them. (Image Dependant Gamut Mapping)  
  [ArgyllCMS](https://www.argyllcms.com/)  

---

### Black & White Printing – A Unique Challenge

Most printers are essentially RGB-based. Even in dedicated B&W print modes, the printer still uses color inks for toning adjustments.  

- Challenge:  
  Printer manufacturers optimize their B&W modes for their own branded papers, meaning third-party papers often lack ICC profiles for B&W printing printing mode.  

- Solution:  
  I create B&W-specific ICC profiles using ABWProfileMaker, ensuring that the printer’s B&W mode is fully optimized for linear grayscale reproduction.  
  [ABW Profile Maker (GitHub)](https://github.com/doug3236/ABWProfilePatches)  

This method provides full control over tonal linearity, resulting in archival-quality grayscale prints.  

For those seeking even further refinement:  

- QuadTone RIP enables precise control over multi-ink B&W printing.  
  [QuadTone RIP](http://www.quadtonerip.com/)  

A perfectly neutral and linear grayscale print is the foundation. Giving it soul is up to you.  

---

## Print Longevity – Epson SureColor P700 & Carbon-Based Inks  

One of the primary reasons I chose the Epson SureColor P700 is its use of carbon-based pigment inks, offering extraordinary longevity.  

For true archival permanence, see the second table in the Wilhelm Imaging Research report.  
B&W prints can last over 400 years, while color prints exceed 200 years under proper conditions.  

[Wilhelm Imaging Research – Epson SureColor P700 & P900 Permanence Report](https://www.wilhelm-research.com/epson/WIR_Epson_SureColor_P700_and_P900_Printers_2021_07_23.pdf)  

By eliminating OBAs and using custom-calibrated carbon-based pigment inks, I ensure my prints are not just visually striking—but built to endure.  
