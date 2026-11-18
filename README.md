# rtauargus: protecting linked tables calling tau-Argus
Tutorial presented at uRos2026: https://r-project.ro/conference2026.html

Nadège Ferrer-Pradines & Julien Desclodure

## Content
This repo contains:
- a Quarto markdown .qmd with all commented examples
- a html presentation with its dependencies

## Warning
As of November 2026, you will **only be able to follow this tutorial with a Windows operating system**, as tau-Argus is not compiled to Linux to date.
Follow the instructions for TauArgus installation:
- [TauArgus4.2.3](https://github.com/sdcTools/tauargus/releases/tag/v4.2.3) : unzip the downloaded zip archive into a folder where you have read, write, and execute permissions; install the software in a directory path that does not contain spaces (for example, use C:\TauArgus instead of C:\Program Files\TauArgus) to prevent runtime errors.

Please make sure you have installed R and RStudio then install rtauargus with the following R command:

```
install.packages("remotes")
remotes::install_github(
  "InseeFrLab/rtauargus",
  build_vignettes = FALSE,
  upgrade = "never"
)
```
