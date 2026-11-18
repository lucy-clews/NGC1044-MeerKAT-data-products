> Clews et al. (2026),
> *"A MeerKAT spectropolarimetric investigation of the tailed FRI radio galaxy NGC 1044"*

## Overview

Repository containing NGC1044 MeerKAT spectropolarimetric data products from Clews et al. (2026), including:

- Total intensity (Stokes I) images
- Spectral index maps
- Spectral ageing maps
- Faraday rotation measure synthesis products

---

## Full Intensity Maps

### S-band

| Product | Resolutions |
|----------|------------|
| Stokes I images | 7″, 12″, 20″ |
| Primary-beam corrected Stokes I images | 7″, 12″, 20″ |

Example files:

- `S_12arc-StokesI-MFS-image.fits`
- `S_12arc-StokesI-MFS-image-pb.fits`

### L-band

| Product | Resolutions |
|----------|------------|
| Stokes I images | 7″, 12″, 20″ |
| Primary-beam corrected Stokes I images | 7″, 12″, 20″ |

Example files:

- `L_12arc-StokesI-MFS-image.fits`
- `L_12arc-StokesI-MFS-image-pb.fits`

---

## Spectral Products

### Spectral Index Maps

Maps derived from combined L-band and S-band imaging.

Available resolutions:

- 7″
- 12″
- 20″

Example:

- `NGC1044_SpectralIndex_12arc.fits`

### JP Spectral Ageing Model

Products:

| File Type | Description |
|------------|-------------|
| Spectral age map | Best-fitting JP model age |
| Error map | Uncertainty on fitted age |

Example files:

- `NGC1044_SpectralAgeing_12arc_JP_B7_94e-10.fits`
- `NGC1044_SpecAgeErrorMap_JP_12arc_B7_94e-10.fits`

### KP Spectral Ageing Model

Products:

| File Type | Description |
|------------|-------------|
| Spectral age map | Best-fitting KP model age |
| Error map | Uncertainty on fitted age |

Example files:

- `NGC1044_SpectralAgeing_12arc_KP_B7_94e-10.fits`
- `NGC1044_SpecAgeErrorMap_KP_12arc_B7_94e-10.fits`

---
## Fractional Polarisation

`NGC1044_fractional_polarisation.fits`
---
## Faraday Rotation Measure Products

| File | Description |
|--------|-------------|
| `NGC1044_RMsynth_peakRM.fits` | Peak Faraday rotation measure (RM) map |
| `NGC1044_RMSynth_FDF_maxPI.fits` | Maximum polarized intensity within the Faraday dispersion function |
| `NGC1044_RMSynth_peak_fit_dPhiPeakPIfit_rm2.fits` | Uncertainty in RM derived from peak fitting |
| `NGC1044_peak_fitFDFcorMAD.fits` | Estimated noise map derived from the Faraday depth spectrum using the MADFM method |

---

## Data products not included in this repository

The following products are not included in this repository due to file-size limitations but are available from the author upon request:

- Measurement sets
- Stokes I, Q, U image cubes
- RMSF cube
- Dirty Faraday depth cube
- Clean Faraday depth cube

---

## Citation

If you use these data products, please cite:

Clews et al. (2026), *A MeerKAT spectropolarimetric investigation of the tailed FRI radio galaxy NGC 1044*.

---

## Contact

For questions regarding the products contained in this repository, please contact Lucy Clews (lucyclews10@hotmail.co.uk) .
