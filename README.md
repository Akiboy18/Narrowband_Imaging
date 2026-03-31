# Narrowband Imaging

**This project performs **false-color imaging** using narrowband astronomical data from the **Hubble Space Telescope (HST)** and **James Webb Space Telescope (JWST)**.
FITS files downloaded from the **MAST Portal** are processed and combined into RGB composites, highlighting specific emission wavelengths to visualize celestial structures.**

---

# Overview

This project transforms raw **narrowband FITS data** from space telescopes into **scientifically meaningful false-color images**.

Astronomical detectors record light in individual wavelength filters rather than RGB. By assigning these wavelengths to red, green, and blue channels, we can create images that reveal **nebulae structures, ionized gas regions, and star-forming areas** that are otherwise invisible.

The workflow demonstrates how professional astronomical imagery is produced from raw telescope data.

---
# JWST Filter Images

<p align="center">
<img src="Tarantula_Nebula_090W.jpg" width="700">
</p>
<p align="center"><em>Tarantula Nebula – JWST Filter F090W</em></p>

<p align="center">
<img src="Tarantula_Nebula_187N.jpg" width="700">
</p>
<p align="center"><em>Tarantula Nebula – JWST Filter F187N</em></p>

<p align="center">
<img src="NGC_2070/NGC2070.jpg" width="700">
</p>
<p align="center"><em>Tarantula Nebula – Final Output</em></p>

# Features

* **MAST Data Retrieval**
  Raw **FITS files** were obtained from the **MAST (Mikulski Archive for Space Telescopes)** portal.

* **Narrowband Processing**
  Individual wavelength filters were extracted and stretched to enhance faint astronomical structures.

* **False-Color RGB Composition**
  Multiple narrowband filters were mapped to **RGB channels** to create visually informative composite images.

* **Astronomical Data Handling**
  Demonstrates the workflow used in astrophotography and research imaging.

---

# Tech Stack

## Data Sources

* Hubble Space Telescope (HST)
* James Webb Space Telescope (JWST)
* MAST Portal (Mikulski Archive for Space Telescopes)

## Tools & Software

* FITS Liberator – FITS file visualization and stretching
* Adobe Photoshop – RGB channel combination and color grading
* GIMP – Image processing and adjustments

## Data Format

* FITS (Flexible Image Transport System)

---

# Installation

```bash
# Clone this repository
git clone https://github.com/Akiboy18/Narrowband_Imaging.git

# Navigate into the repository
cd narrowband-imaging
```

This project mainly demonstrates a **data processing workflow** rather than executable software.

To reproduce the results:

1. Download **FITS files** from the **MAST Portal**
2. Open them using **FITS Liberator**
3. Stretch intensity levels for each filter
4. Export images
5. Combine them in **Photoshop/GIMP as RGB channels**

---

# Workflow

1. Download narrowband **FITS images** from MAST.
2. Open FITS files using **FITS Liberator**.
3. Apply intensity stretching to enhance faint structures.
4. Export each filter as a grayscale image.
5. Assign filters to **Red, Green, Blue channels**.
6. Combine and adjust colors in **Photoshop or GIMP**.
7. Produce final **false-color narrowband composite**.

---

# Filter to RGB Mapping Example

| Filter | Wavelength | Assigned Color | Purpose                   |
| ------ | ---------- | -------------- | ------------------------- |
| Hα     | 656.3 nm   | Red            | Hydrogen emission regions |
| OIII   | 500.7 nm   | Green          | Ionized oxygen gas        |
| SII    | 672.4 nm   | Blue           | Shocked gas structures    |

---



---

# References

* MAST Portal
https://mast.stsci.edu

* FITS Liberator
https://noirlab.edu/public/products/fitsliberator/

* NASA Hubble Archive
https://hla.stsci.edu

* Rodrigo, C., Cruz, P., Aguilar, J.F., et al. 2024
  https://ui.adsabs.harvard.edu/abs/2024A%26A...689A..93R/abstract

* Rodrigo, C., Solano, E., Bayo, A., 2012
  *The SVO Filter Profile Service*
  https://ui.adsabs.harvard.edu/abs/2012ivoa.rept.1015R/abstract

* Rodrigo, C., Solano, E., 2020
  *The SVO Filter Profile Service*
  https://ui.adsabs.harvard.edu/abs/2020sea..confE.182R/abstract


# Acknowledgement

This research has made use of the **SVO Filter Profile Service "Carlos Rodrigo"**, funded by **MCIN/AEI/10.13039/501100011033/** through grant **PID2023-146210NB-I00**.

If you use the SVO Filter Profile Service in your research, please acknowledge it using the statement above.

---


