# Style Transfer using Generative Adversarial Network (GAN)
To build a Generative adversarial model(modified U-Net) which can generate artificial MRI images of different contrast levels from existing MRI scans. Our goal in this capstone is to convert T1 type MRI images into T2 type MRI images. This way we can create a revolutionary impact in the healthcare sector.

## Table of Contents
* [General Info](#general-information)
* [Technologies Used](#technologies-used)
* [Conclusions](#conclusions)
* [Acknowledgements](#acknowledgements)

<!-- You can include any other section that is pertinent to your problem -->

## General Information
Misdiagnosis in medical field is a very serious issue having adverse implications on the patient. With skilled radiologists overwhelmed by volume of work, there is critical need for Artifical Intelligence to assist them in taking the right decisions.

Magnetic Resonance Imaging (MRI) is a key imaging technology which offers superb soft tissue contrast with different contrast mechanisms such as T1 weighted and T2 weighted. A radiologist often needs multi contrast images to arrive at the right decision but is often cost prohibitive.

But to have access to different imaging is difficult and expensive. With the help of deep learning, we can use style transfer to generate artificial MRI images of different contrast levels from existing MRI scans. This will help to provide a better diagnosis with the help of an additional image.

Using CycleGAN to translate the style of one MRI image to another, which will help in a better understanding of the scanned image. Using GANs you will create T2 weighted images from T1 weighted MRI image and vice-versa.

**T1 v T2 images**

- On T1 images FAT is white
- On T2 images both FAT and WATER are white

The two basic types of MRI images are T1-weighted and T2-weighted images, often referred to as T1 and T2 images.

The timing of radiofrequency pulse sequences used to make T1 images results in images which highlight fat tissue within the body.The timing of radiofrequency pulse sequences used to make T2 images results in images which highlight fat AND water within the body.

|Type    | T1 Highlight Style | T2 Highlight Style|
|---     |---                 |---                |
|Water   | Dark Very          | Bright            |
|Fat     | Very Bright	      | Dark              |
|Bone    | Dark               | Dark              |
|Muscle  | Intermediate       | Dark              |
|Tumours | Intermediate       | Bright            |

<!-- You don't have to answer all the questions - just the ones relevant to your project. -->

## Conclusions
- We can see that a Cycle GAN architecture is effective in translating the style of T1 weighted MRI images to T2 weighted MRI image inputs, and vice versa.
- This can be very useful in more effective diagnosis, without the need of a second MRI scan. This not only saves time for the doctors, but would also reduce the financial burden on the patients.

<!-- You don't have to answer all the questions - just the ones relevant to your project. -->


## Technologies Used
- python     - version 3.9.0
- numpy      - version 1.24.4
- matplotlib - version 3.3.2
- tensorflow - version 2.9.1
- skimage    - version 0.21.0
- imageio    - version 2.35.1
- PIL        - version 10.4.0
- sys        - version 3.8.10 (default, Jan 17 2025, 14:40:23) 
- GCC        - version 9.4.0

<!-- As the libraries versions keep on changing, it is recommended to mention the version of library used in this project -->

## Acknowledgements
- This project was part of Upgrad's Exploratory Data Analysis Project.
- References if any...
  - [Tensorflow Documentation](https://www.tensorflow.org/versions/r2.9/api_docs/python/tf)
  - [Matplotlib Documentation](https://matplotlib.org/stable/api/index.html)


## Contact
Created by [@tritammohanty] - feel free to contact me!