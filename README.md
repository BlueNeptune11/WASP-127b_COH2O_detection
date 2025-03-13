# WASP-127b CO detection
- __Authors__: Nathan Besch, Neil Gibson
- __Date__: June - July 2024

To investigate the double detection feature in the $K_p-v_{sys}$ cross-correlation map of WASP-127b's CRIRES+ data, we reproduced the work of Nortmann et al (2024). We modelled an atmosphere possessing H2O and CO with petitREADTRANS using the planetary system parameters and cross correlated that model with the atmospheric signal. The latter was obtained using the Sysrem pipeline to remove telluric and stellar signals. Although we were not able to obtain a similarly strong double detection feature, we found CO at approximately $v_{sys}=$ 6 km.s $^{-1}$.

![Kp vsys map for H2O and CO](results/COH2O_v2.png)

_Example: $K_p - v_{sys}$ cross-correlation map with detection significance derived from this analysis._

## List of notebooks
| Notebook | View | Download |
|----------|:----:|:--------:|
| WASP-127b Atmosphere Modelling             | [![NB viewer][nbviewer]][jci_nbviewer]  | [![Download][download]][jci_download]  |
| Juice / Clipper ground track intersections (figures)                 | [![NB viewer][nbviewer]][jcif_nbviewer] | [![Download][download]][jcif_download] |

[nbviewer]: https://juigitlab.esac.esa.int/notebooks/planetary-coverage/-/raw/main/imgs/nbviewer.svg
[download]: https://juigitlab.esac.esa.int/notebooks/planetary-coverage/-/raw/main/imgs/download.svg

[atm_nbviewer]: https://nbviewer.jupyter.org/urls/juigitlab.esac.esa.int/notebooks/misc/intersections-overlaps/-/raw/main/juice_clipper_intersections/juice_clipper_intersections_compute.ipynb
[atm_download]: https://juigitlab.esac.esa.int/notebooks/misc/intersections-overlaps/-/raw/main/juice_clipper_intersections/juice_clipper_intersections_compute.ipynb?inline=false

[cc_nbviewer]: https://nbviewer.jupyter.org/urls/juigitlab.esac.esa.int/notebooks/misc/intersections-overlaps/-/raw/main/juice_clipper_intersections/juice_clipper_intersections_figures.ipynb
[cc_download]: https://juigitlab.esac.esa.int/notebooks/misc/intersections-overlaps/-/raw/main/juice_clipper_intersections/juice_clipper_intersections_figures.ipynb?inline=false