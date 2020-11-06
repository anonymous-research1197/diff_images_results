# Explaining Universal Adversarial Perturbations From the Frequency Perspective

## Reviewer 3
The jupyter notebook `results.ipynb` in folder `Reviewer 3` reproduces and visualizes the results of Table 3 of the main paper. To download the [model weights](https://srv-store1.gofile.io/download/IMrhtD/checkpoint.pth.tar) for the hiding (H) and reveal (R) network, execute the following: 
```
cd Reviewer\ 3; wget https://srv-store1.gofile.io/download/IMrhtD/checkpoint.pth.tar
```

## Reviewer 6
The jupyter notebook `UAP_magnitude_check.ipynb` in folder `Reviewer 6` contains the perturbations and image from Figure 7 of the main paper. The perturbations are displayed in the amplified representation and the adversarial examples with the untouched UAPs are shown. Additionally, perturbation magnitudes are displayed.  

## Dependencies
```
torch
torchvision
numpy
matplotlib
tabulate
imageio
```