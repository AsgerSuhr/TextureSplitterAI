# About

Texture Splitter AI is a Generative Adversarial Network (GAN), discovered
by Ian Goodfellow in 2014. It's able to generate textures from a single input
image. It's able to do this because it has looked on thousands of images of
normal maps, height maps, diffuse maps and so on. From what it has seen in the
past it's able to generate a prediction of textures from any kind of input image.

## Roadmap

+ <del> 5 AI's for generating textures <del>
+ <del> Make it accept any image size <del>
+ <del> fix memory issues on large images <del>
+ <del> UV support <del>
+ <del> seamless AI stitching of image patches <del>
+ <del> remove secondary window and implement completely into Blenders UI <del>
+ fix Linux installation
+ When training GANs train on 512x512 images and split them into four,
feed them to the generator and stitch them together afterwards. Then give them to the discriminator,
hopefully this will teach the generator to create better edges for stitching images together again.
Maybe even random sized tiles that are fed to the generator.
+ implement Super Resolution GAN to remove need of stitching, and improve perfomance (idea)
