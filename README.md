<h1>Cycle GAN implementation and experimentation with pytorch</h1>



CycleGAN models can take unpaired sets of images and transform images from one domain to another as shown in the images below. 

|Original|Generated|
|--------|---------|
|![48c641285b](https://user-images.githubusercontent.com/67492097/235572323-7c69b5fe-184f-4a5d-a17b-b8c379132a40.jpg)|![monet_1](https://user-images.githubusercontent.com/67492097/235571872-5f3461f7-30bd-46fe-8910-46fcad2af18c.png)

The image on the left is a landscape photo and the image on the right is the model's generated monet style painting based off of the photo.
<br>
In this project I implement the CycleGAN machine learning model in pytorch and run experiments on it using 2 large data sets.
- Zebra to Horse
- Monet to Photo

If you have any questions feel free to reach out to me at samgfales@gmail.com.
<br>
<br>
<br>

Code heavily based on implementation at https://github.com/aladdinpersson/Machine-Learning-Collection/tree/master/ML/Pytorch/GANs/CycleGAN
<br>
Video tutorial at https://www.youtube.com/watch?v=4LktBHGCNfw&t=3s
<br>
Monet dataset found at https://www.kaggle.com/c/gan-getting-started/data
<br>
Horse to Zebra dataset found at https://www.kaggle.com/datasets/suyashdamle/cyclegan
<br>
Original paper found at https://arxiv.org/pdf/1703.10593.pdf






