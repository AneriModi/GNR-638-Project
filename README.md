## GNR 638 Course Project: Neural Super Sampling

We run this script under [TensorFlow](https://www.tensorflow.org) 2.0.

- In this project we attempt to upscale an image by a factor of 4 times
- This repo consists of two approches: **SRGAN** and **Improved SRGAN (ESRGAN)**

## SRGAN Architecture

<div align="center">
	<img src="img/srgan.jpg" width="80%" height="10%"/>
</div>
</a>

### Results:

<a>
<div align="center">
	<img src="img/zebra_srgan.png" width="80%" height="10%"/>
</div>
</a>



<a>
<div align="center">
	<img src="img/mountain_srgan.png" width="80%" height="10%"/>
</div>
</a>



## ESRGAN Architecture

<a href="https://miro.medium.com/max/855/1*eFtiKIAtigow1OQGrhkWSA.png">
<div align="center">
	<img src="img/esrgan.png" width="80%" height="10%"/>
</div>
</a>

### Results:
<a>
<div align="center">
	<img src="img/mountain_esrgan.png" width="80%" height="10%"/>
</div>
</a>

### Improvement over SRGAN:
<a>
<div align="center">
	<img src="img/sragan_vs_esragan.png" width="80%" height="10%"/>
</div>
</a>



# RUN
- Upload your Low resolution image in `SRGAN/test/input` and high resolution output will be generated in `SRGAN/test/output` (similar procedure goes for ESRGAN)
- Start training: `python train.py`
- For testing: `python test.py`
- `model.py` consists of the SRGAN model code

# References:
SRGAN:	https://arxiv.org/abs/1609.04802 \
ESRGAN:	https://arxiv.org/abs/1809.00219

# Contributors:
- Aneri	(190100015)
- Bhargav(190100102)
- Shwetambari(190100102)

								        Made with 💙
