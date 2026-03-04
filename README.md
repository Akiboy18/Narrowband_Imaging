# Narrowband Imaging

**This project performs **false-color imaging** using narrowband astronomical data from the **Hubble Space Telescope (HST)** and **James Webb Space Telescope (JWST)**.
FITS files downloaded from the **MAST Portal** are processed and combined into RGB composites, highlighting specific emission wavelengths to visualize celestial structures.**

---

# Overview

This project transforms raw **narrowband FITS data** from space telescopes into **scientifically meaningful false-color images**.

Astronomical detectors record light in individual wavelength filters rather than RGB. By assigning these wavelengths to red, green, and blue channels, we can create images that reveal **nebulae structures, ionized gas regions, and star-forming areas** that are otherwise invisible.

The workflow demonstrates how professional astronomical imagery is produced from raw telescope data.

---

# Demo / Screenshot

![Narrowband Composite](NGC_2070/Tarantula%Nebula%090W.jpg)

---

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
git clone https://github.com/yourusername/narrowband-imaging.git

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

# Repository Structure

```
Narrowband_Imaging
│
├── images
│   └── final_composite.png
│
├── data
│   └── fits_files
│
└── README.md
```

---

# References

MAST Portal
https://mast.stsci.edu

FITS Liberator
https://noirlab.edu/public/products/fitsliberator/

NASA Hubble Archive
https://hla.stsci.edu

# Run the app
npm start
