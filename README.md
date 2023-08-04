# ArtifyGAN - Animated Face Image Generation using GANs

## Project Goals

The primary goal of this project is to develop an efficient and realistic animated facial image generation system using Generative Adversarial Networks (GANs), addressing the inefficiencies prevalent in current technologies. The project aims to leverage GAN architecture to generate high-quality animations from single or limited reference images, capturing fine details that current systems often miss. Training the model on a comprehensive dataset will enable it to accurately represent a wide array of facial styles, thereby improving the realism and versatility of the resulting animations.

## Dataset Used for Training

- CelebA dataset: https://mmlab.ie.cuhk.edu.hk/projects/CelebA.html<br>
  Consists of more than 200K celebrity images and various ttributes such as gender, presence of glasses, and facial landmarks, which facilitates training the model to capture facial expressions and features

- COCO dataset: https://cocodataset.org/ <br>
  Consists of a diverse range of real-world images, enabling the model to understand and identify objects within their contextual settings

- Cartoon Dataset: https://safebooru.org/index.php?page=post&s=list <br>
  Consists of collection of cartoon images sourced from the safebooru website, allowing the model to capture the unique style and features of cartoon images


## ArtifyGAN Architecture
Inspired from CartonnGAN, developeed and implemented the below architecture for generating animated face images for gicen input image
![image](https://github.com/27saniya/ArtifyGAN/assets/101293878/0936f2ef-8d19-49a5-8ff3-4111591d6d82)

## Results:
- Qualitative Results

![image](https://github.com/27saniya/ArtifyGAN/assets/101293878/9fa0afe5-eb82-4376-84b1-4cb5f185d6ad)

- Quantitative Results<br>

FID score: 
  ![image](https://github.com/27saniya/ArtifyGAN/assets/101293878/9f732c93-77a5-4bf3-b775-0b3ef9259c59)

Conclusion <br>
- ArtifyGAN is less complex as compared to other existing models for
generating animated images
- Designing the model from scratch allowed to define the architecture and
modify hyperparameters to better suit our specific dataset and target style
- Although
ArtifyGAN was trained on a smaller dataset and for less training
time as compared to other pre trained models, it is still producing high
quality animated results






  

