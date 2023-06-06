# Image Colorization using GAN

Image colorization is a computer-assisted technology to colorize grayscale images. 
With the rapid development of information technology and increasing image data, the study of image colorization has also become particularly important. 
By training the GAN on a large dataset of grayscale images and their corresponding color images, the generator network can learn to generate realistic and accurate colorizations of grayscale images. This technique has been used in various applications, such as restoring old black-and-white photos and enhancing medical images.

The GAN algorithm is a deep learning technique that involves training two neural networks, a generator network and a discriminator network, to work together to generate new data that is similar to a given dataset.
The GAN architecture is designed to learn the underlying distribution of the input images and generate new images that are similar to the input images.
The generator network generates a new color image by sampling from the learned distribution, and the discriminator network tries to distinguish between the generated color image and the real color image.

### GAN architecture :

![image](https://github.com/DynamVraj/Image_Colorization/assets/99869914/e273c938-38b2-4cd0-b09f-7f325e7e691f)

### Steps :
1. Collect a dataset of grayscale images and their corresponding colored images.
2. Train a cGAN using the dataset. The generator should take a grayscale image as input and output a colored image. The discriminator should distinguish between the generated image and the real colored image.
3. Once the cGAN is trained, you can use the generator to colorize a grayscale image. Simply feed the grayscale image into the generator, and it will output a colored image.
4. Post-process the colored image to improve the quality. This may involve techniques such as color correction, contrast adjustment, and noise reduction.
5. The generator takes as input a grayscale image and produces a colored image, while the discriminator tries to distinguish between the generated image and the real colored image. The generator is trained to fool the discriminator by producing realistic-looking colored images that are visually similar to the real colored images.

### Output :

![image](https://github.com/DynamVraj/Image_Colorization/assets/99869914/f908b09a-6b0d-4d52-a24a-eef58ac8a213)

