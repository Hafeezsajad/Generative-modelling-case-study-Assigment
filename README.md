GAN Assignment – 2D Curves & Pathology Image Generation
This project is part of a course assignment where I worked with Generative Adversarial Networks (GANs). It has two main parts.

Part 1 – GAN on 2D Data
I trained a basic GAN to generate sine wave samples.

Then I tried it on a more complex curve: y = sin(2x) + 0.3cos(5x) + noise.

I also modified the GAN to see if changes in architecture help.

Plotted real vs generated samples and the loss curves.

Used MSE to see how close the outputs were to the real curve.

Part 2 – DCGAN on PathMNIST
I used a DCGAN to generate synthetic images similar to medical images from the PathMNIST dataset.

The generator learned to produce 3-channel (RGB) images.

I added label smoothing and some random noise to improve training.

At different training stages, I plotted generated samples to see progress.

I compared real and fake images visually and also used FID and SSIM scores for evaluation.

✅ Extra Stuff I Tried
Label smoothing

Noise injection

FID and SSIM to evaluate the results

💻 How to Run
Install dependencies:

arduino
Copy
Edit
pip install medmnist clean-fid scikit-image
Run the Python scripts or notebooks for each part.

Outputs (images, model weights) will be saved automatically.

 Output Examples
You can see real vs. fake images and loss plots in the results section or output folders.

