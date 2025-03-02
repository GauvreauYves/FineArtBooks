# Rêveries – Fine Art Photography Book

This page contains the digital reference edition of *Rêveries*, a fine art photography book.

━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━

## About This Project
From capture to print, I ensure that every photon counts...
<p align="center">■ ■ ■</p>

## About This Project
From capture to print, I ensure that every photon counts...


## 50K-Foot Overview
This is a high-level summary of my workflow, covering exposure, RAW development, printing, and archival longevity. Links are provided for further exploration.

<hr style="border: 1px solid black;">

## About This Project
From capture to print, I ensure that every photon counts. Light takes form, evokes deep emotion, and is preserved in a book crafted with care.  

This project was born from the stability of carbon pigment inks—lasting over 400 years. You don’t place something designed to endure in a disposable container. Hence, a book, its covers, and its archival box, made of noble and archival materials—A companion, an accomplice, a messenger of time itself.

<hr style="border: 1px solid black;">

## Exposure
ETTR (Expose To The Right) maximizes captured photons and optimizes the signal-to-noise ratio (SNR).  
[Learn more about ETTR](https://en.wikipedia.org/wiki/Exposing_to_the_right) |  
[RawDigger – Calibrating exposure for dynamic range](https://www.rawdigger.com/howtouse/calibrate-exposure-meter-to-improve-dynamic-range)

<hr style="border: 1px solid black;">

## RAW Development & Conversion
Scene-referred development preserves raw sensor data without artificial adjustments. A 3D LUT from a ColorChecker ensures color accuracy (ΔE00 < 2).  
[Scene-referred vs. Display-referred](https://ninedegreesbelow.com/photography/display-referred-scene-referred.html) |  
[Darktable – Scene-referred workflow](https://docs.darktable.org/usermanual/3.6/en/overview/workflow/edit-scene-referred/)

<hr style="border: 1px solid black;">

## Post-Processing
A billion photos are taken every day. You want to stand out? Be creative.

<hr style="border: 1px solid black;">

# Printing

Printing follows industry standards—except I am both the printer and the client.  
[ICC White Papers](https://www.color.org/whitepapers.xalter)

### ICC Profiling & Paper Selection

I create ICC profiles using an i1 Pro 2 spectrophotometer.  
[i1 Pro 2 – X-Rite](https://www.xrite.com/categories/calibration-profiling/i1photo-pro-2)

I dismiss papers containing Optical Brightening Agents (OBAs). While they enhance brightness under certain lighting conditions, OBAs degrade over time, causing color shifts. For short-term displays, they can work. For archival prints, I avoid them.  

I use ColorThink Pro and GamutVision to analyze gamut, black & white points, and other critical characteristics.  
[ColorThink Pro](https://www.chromix.com/colorthink/#overview) |  
[GamutVision](http://www.gamutvision.com/modules.php?name=Download)

With my i1 Pro, I create ICC profiles for each paper using i1Profiler. I also use ArgyllCMS for device link profiles, mapping colors from my image masters to the paper’s gamut while preserving color appearance.  
[ArgyllCMS](https://www.argyllcms.com/)

<hr style="border: 1px solid black;">

## Black & White Printing

Most printers are RGB-based. Even in B&W modes, they often use color inks. Printer manufacturers optimize for their own papers, leaving third-party papers without ICC profiles for B&W.  

I create B&W-specific ICC profiles with ABWProfileMaker, optimizing the printer’s B&W mode for neutral grayscale.  
[ABW Profile Maker (GitHub)](https://github.com/doug3236/ABWProfilePatches)  

For even finer control, QuadTone RIP enables precise multi-ink B&W printing.  
[QuadTone RIP](http://www.quadtonerip.com/)

A perfectly neutral and linear grayscale print is the foundation. Giving it soul is up to you.

<hr style="border: 1px solid black;">

## Print Longevity – Epson SureColor P700 & Carbon-Based Inks

I chose the Epson SureColor P700 for its carbon-based pigment inks and their extraordinary longevity.

For true archival permanence, see Table 2 in the Wilhelm Imaging Research report, detailing the P700's lifespan. B&W prints exceed 400 years; color prints last over 200 under proper conditions.  
[Wilhelm Imaging Research – Epson SureColor P700 & P900](https://www.wilhelm-research.com/epson/WIR_Epson_SureColor_P700_and_P900_Printers_2021_07_23.pdf)

By eliminating OBAs and using calibrated carbon-based inks, my prints are built to endure.
