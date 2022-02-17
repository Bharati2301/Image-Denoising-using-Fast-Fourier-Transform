# Image-Denoising-using-Fast-Fourier-Transform
<p align="center">
  <img src="https://miro.medium.com/max/1400/1*RVsX901R3uAFhGD_qTWoSA.gif" width="350" height="250"/>
</p>

## FOURIER SERIES AND FOURIER TRANSFORM
* Fourier series helps us define any periodic function as the sum of the sine and cosine functions. Also, it helps us to get the amplitude and phase spectrum. Fourier Series provides the decomposition of the periodic function on a base of the harmonic functions.
* Fourier transform (FT) can be explained in exactly the same way as the Fourier Series. The only difference is usage. We generally use the Fourier Transform for Non-Periodic function.

<p align="center">
  <img src="https://user-images.githubusercontent.com/71218441/154472300-458b6057-26a5-40eb-a27f-4b1fb20cb536.JPG" width="600" height="350"/>
</p>

* Using the DFT specifically, we can compose the above signal to a series of sinusoids and each of them will have a different frequency. 
<p align="center">
  <img src="https://user-images.githubusercontent.com/71218441/154472327-a17f0c21-6220-4283-a027-d02becfd3eec.JPG" width="600" height="350"/>
</p>

## PROCESS
* Initially the image is converted into a frequency domain function, using Fourier Transform, after its converted, we can observe the low n high frequency points in the image distinctly, our main task is to reduce the high frequency points to low frequency points to reduce the noise in the image, after performing the necessary steps to do this, the image is again transformed to its original form from the frequency domain by using Inverse Fourier Transform.

<p align="center">
  <img src="https://user-images.githubusercontent.com/71218441/154472313-362faab8-19f4-496c-84f2-7460824cbf09.JPG" width="600" height="350"/>
</p>

