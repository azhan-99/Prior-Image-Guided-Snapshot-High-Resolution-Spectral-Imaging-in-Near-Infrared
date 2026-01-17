# Prior Image Guided Snapshot High Resolution Spectral Imaging in Near-Infrared
Prior Image Guided Snapshot High-Resolution  Spectral Imaging in Near Infrared (TIP2025)


[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](https://opensource.org/licenses/MIT)
[![Python](https://img.shields.io/badge/Python-3.8%2B-blue)](https://www.python.org/)
[![Paper](https://img.shields.io/badge/Paper-Arxiv-red)](https://arxiv.org/)

## 📖 Introduction

Here involves the brief introduction of your project. This project implements a simulation pipeline for [Specific Optical Phenomenon] and reconstructs images using deep learning.

## 🔬 System Overview (Optical Setup)

We have designed a custom optical setup including a laser source, collimator, and a coded aperture.

<table>
  <tr>
    <td align="center">
      <img src="./assets/optical_schematic.png" width="400"/>
      <br />
      <figcaption><b>Fig 1. Schematic of the Optical Path</b></figcaption>
    </td>
    <td align="center">
      <img src="./assets/setup_photo.png" width="400"/>
      <br />
      <figcaption><b>Fig 2. Experimental Setup</b></figcaption>
    </td>
  </tr>
</table>

### Light Transport Model

The image formation process is modeled as:

$$I = \mathcal{P}(O * K) + \eta$$

Where $I$ is the captured intensity, $O$ is the object, $K$ is the Point Spread Function (PSF), and $\eta$ is the noise term.

## 🚀 Getting Started

### Prerequisites

```bash
pip install -r requirements.txt
