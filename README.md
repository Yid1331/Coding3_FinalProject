# Coding3_FinalProject
Name: Xiaoyi Dong
Student ID: 21035114

## 01 Project Overview
The project name is Time Tunnel, which aims to use the relevant knowledge and tools of machine learning (image generation of the **StylGAN2** model and the application of **interactML**) to carry out a creative work.

During my study of machine learning, I found that the images generated by the StyleGAN2 will go through a process from abstract to concrete. This is very similar to the physical representation of memory in my mind. So I want to use **StyleGAN2** to generate representative items representing different stages of life. Then put these “memory fragments” into the time tunnel to bring people's memories.

After that, I used **interactML** to train the position of the lens, so that the "memory fragments" can be flickered in the time tunnel, and the lights in the time tunnel will also change color with the change of the lens position.

[Video Link](https://www.youtube.com/watch?v=AfnSIu_WJmI)

![Screenshot_6](https://user-images.githubusercontent.com/81423727/174595155-685156a5-6cd0-4780-9bed-f3beb8985496.png)


## 02 Design and Development Processes

### 1.Select, download, process datasets
I chose five different stages in person's life, the representative objects of childhood, adolescence, youth, middle age, and old age, namely Ferrari Lego toys, books, briefcases, wedding dresses, and clocks. After that, I used [Jeff Heaton](https://www.youtube.com/watch?v=9sBQqlTtQ2k)'s method to download 5 sets of 512 * 512 px images representing items on the flickr website, each set of 200 images. After that, the obviously incorrect pictures are deleted, and the following 5 sets of data sets are formed.

![dataset](https://user-images.githubusercontent.com/81423727/174593552-774e7a0e-3c0f-4277-9be6-f525ae2175c1.jpg)

### 2.Train Dataseet
I chose the [StyleGAN2](https://colab.research.google.com/drive/1_fenx2FKJAHEPmg-ceBdxEY2TsesnTq-) model to train my datasets.Each set of data was trained for about three hours.After training, I set six generated images, and generate this process as a video to achieve the effect of image transformation.

![Screenshot_7](https://user-images.githubusercontent.com/81423727/174599050-fbc09697-6f05-46c7-b9ca-21fd5a796fe0.png)

#### Training Process (Take the briefcase as an example)

![case](https://user-images.githubusercontent.com/81423727/174598742-3ee5ba42-4507-46bd-a85a-d7899bc6e80b.jpg)

https://user-images.githubusercontent.com/81423727/174599300-371d5f1f-3628-43e2-ba06-22d7fa505d2a.mp4

https://user-images.githubusercontent.com/81423727/174599346-13b20528-ef49-40a5-aa9b-288efed7287b.mp4

https://user-images.githubusercontent.com/81423727/174599399-ae82b4dc-d14a-4b04-9239-6bc18f73e786.mp4

https://user-images.githubusercontent.com/81423727/174599433-6f3da7e6-487a-4ea9-8f55-a4b94d1b29a3.mp4

https://user-images.githubusercontent.com/81423727/174599473-8929881e-3f70-421b-915a-c4e358f56f1e.mp4


### 3.Modeling

After that I used C4D to model the tunnel.

![Screenshot_8](https://user-images.githubusercontent.com/81423727/174600749-7bce1e32-bbeb-4341-b76d-d5a5279f0ca0.png)

