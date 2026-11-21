---
layout: default
title: Thesis
---

<div class="page-header-row">
  <div>
    <span class="tag">PhD Dissertation &middot; 2020</span>
    <h1>Observations of Helical Plasma Dynamics Using Complementary X-Ray Diagnostics in the MST</h1>
    <p class="page-subtitle">
      Department of Physics, University of Wisconsin&ndash;Madison &middot; Advisor: Daniel J. Den Hartog
    </p>
  </div>
  <div class="hero-actions">
    <a href="{{ '/assets/documents/PhD%20Thesis%20-%20VanMeter%20-%202020.pdf' | relative_url }}" class="btn btn-primary" target="_blank" rel="noopener noreferrer">
      Access Full Thesis (PDF) &nearr;
    </a>
    <a href="https://github.com/pdvanmeter/meSXR" class="btn btn-outline" target="_blank" rel="noopener noreferrer">
      meSXR Python Code &nearr;
    </a>
  </div>
</div>

---

## Overview

High-temperature magnetically confined fusion plasmas emit substantial soft and hard X-ray radiation. While this radiation represents an energy loss channel, a plasma's X-ray emission spectrum encodes rich information about its electron temperature (<em>T<sub>e</sub></em>), impurity composition (<em>n<sub>Z</sub></em> and <em>Z</em><sub>eff</sub>), fast non-thermal electron populations, and internal magnetic topology.

This dissertation details the calibration, installation, forward modeling, and Bayesian Integrated Data Analysis (IDA) of a novel **Multi-Energy Soft X-Ray (ME-SXR)** diagnostic based on the DECTRIS PILATUS3 100K hybrid photon-counting detector on the **Madison Symmetric Torus (MST)** reversed-field pinch (RFP). Together with a complementary suite of X-ray diagnostics—a two-color diode-based soft X-ray tomography array, the NICKAL2 Ross filter spectrometer, and a fast avalanche-photodiode hard X-ray (FXR) camera—this system was used to investigate the structure and evolution of self-organized **quasi-single helicity (QSH)** helical plasma equilibria.

---

## Summary of Key Findings

### 1. Diagnostic Development & Bayesian Integrated Data Analysis

<div class="card-grid">
  <div class="card">
    <h3>Per-Pixel Multi-Energy Calibration</h3>
    <p>
      Calibrated the ~100k-pixel PILATUS3 detector across low-energy (1.6&ndash;6 keV) and medium-energy (4&ndash;14 keV) ranges by scanning individual pixel trimbit thresholds against X-ray fluorescence targets. Demonstrated an effective threshold resolution of &Delta;<em>E</em> &lt; 100 eV (&sigma;<sub><em>E</em></sub> = 300 eV) in high-gain mode and &Delta;<em>E</em> &lt; 200 eV (&sigma;<sub><em>E</em></sub> = 550 eV) in medium-gain mode, and validated an analytical charge-sharing model across both regimes.
    </p>
  </div>

  <div class="card">
    <h3>Collisional-Radiative Forward Model</h3>
    <p>
      Built a comprehensive Python forward model combining <em>in-situ</em> spatial calibration, filter and detector response functions, and ADAS collisional-radiative atomic physics. Demonstrated that charge-exchange with neutral hydrogen significantly shifts aluminum ionization balance (Al<sup>+11</sup> and Al<sup>+12</sup> line emission at ~2 keV) in MST plasmas, and validated the synthetic predictions against simultaneous SXR tomography measurements.
    </p>
  </div>

  <div class="card">
    <h3>Simultaneous Profile Inference via IDA</h3>
    <p>
      Developed methods to identify mid-<em>Z</em> impurity emission lines (such as Ar<sup>+16</sup> at 3.05 &plusmn; 0.02 keV) and integrated the ME-SXR forward model with Thomson scattering, SXR tomography, and Ross spectrometer data inside a Bayesian MCMC framework to simultaneously reconstruct self-consistent <em>T<sub>e</sub></em>, impurity density (<em>n</em><sub>Al</sub>, <em>n</em><sub>C</sub>), and <em>Z</em><sub>eff</sub> radial profiles.
    </p>
  </div>
</div>

### 2. Helical Plasma Dynamics & Enhanced Confinement (QSH)

<div class="card-grid">
  <div class="card">
    <h3>First Time-Resolved 2D Helical <em>T<sub>e</sub></em> Profiles</h3>
    <p>
      Produced the first time-resolved 2D electron temperature and density reconstructions in a helical MST plasma by combining SXR tomography and far-infrared (FIR) interferometry within a forward-modeling framework mapped onto 3D helical equilibria (SHEq). Observed peak temperatures <em>T<sub>e</sub></em> &gt; 700 eV and steep temperature gradients |&nabla;<em>T<sub>e</sub></em>| &ge; 3 keV m<sup>&minus;1</sup>, providing direct evidence of an internal thermal transport barrier.
    </p>
  </div>

  <div class="card">
    <h3>Discovery of the QSH &ldquo;Quiet Flattop Phase&rdquo;</h3>
    <p>
      Demonstrated that the saturated QSH flattop divides into two distinct regimes: an initial self-organized <strong>quiet phase</strong> where secondary tearing modes are nearly absent and a broad hot thermal structure forms, followed by a <strong>dynamic phase</strong> where low-amplitude secondary tearing resumes and the hot region contracts into a narrower helical core. Runaway electrons (<em>E<sub>r</sub></em> &approx; 15&ndash;18 keV) are well-confined during the quiet phase and rapidly lost at the transition.
    </p>
  </div>

  <div class="card">
    <h3>Predator-Prey Dynamics &amp; High-Frequency Fluctuations</h3>
    <p>
      Observed a 180&deg; out-of-phase predator-prey oscillation between the dominant <em>n</em> = 5 tearing mode and secondary (<em>n</em> = 6, 7, 8) modes, with the soft X-ray emissivity gradient oscillating in phase with the dominant mode—confirming predictions of shear-suppression transport barrier theory. Also identified localized 400&ndash;1000 kHz magnetic fluctuations aligned with the helical structure, suggestive of gradient-driven microtearing turbulence.
    </p>
  </div>
</div>

---

## Full Document

You can read or download the complete dissertation PDF below:

<p>
  <a href="{{ '/assets/documents/PhD%20Thesis%20-%20VanMeter%20-%202020.pdf' | relative_url }}" class="btn btn-primary" target="_blank" rel="noopener noreferrer">
    Download PhD Dissertation (PDF, 402 pages) &nearr;
  </a>
</p>
