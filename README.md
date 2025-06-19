# 📘 XRF2D

A GUI for data processing and visualize WDXRF data. 

## 🧪 Description

The GUI can process data, plot boxplot and mapping. \
Allows thickness calculation from surface density and the S/Mo ratio. \
Enables visualization of data via Mapping/Boxplot. \
Allows setting thresholds on plot parameters (mapping). \

## 📂 Project Structure

# Installation:
## From PyPI (recommanded):

Make sure that Python (> 3.8) is already installed on your computer.

```bash
pip install XRF2D
```

# Quick start

Launch the application from the Windows search bar:

```
XRF2D
```

Once the GUI opens, select a directory containing files.

## How it works 

### Functions

Currently supports only MoS₂ data processing. The sequence of functions is as follows:
1. Calculate thickness using surface density and Mo atomic percentage
2. Plot mapping (only if the number of points > 4)
3. Plot boxplot

More detail can be found there ==> [WDXRF - Mode d’emploi.pptx](https://github.com/user-attachments/files/20815001/WDXRF.-.Mode.d.emploi.pptx)


