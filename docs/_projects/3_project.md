---
layout: post
title: Voyager Cryptor
description: Image transformation with ECC encryption
---

This is a project for VandyHacks VIII, which is about the encryption and decryption of images using the Elliptic Curve Cryptography (ECC) encryption. We are a group of 4, and <a href="https://github.com/AllenJWZhu/VandyHacks2021" target="_blank">here is the repo</a> of this amazing project.

## Inspiration
Inspired by the historic journey of the Voyager spacecraft mission in the year 1977, we are launching a Golden Record with a similar, yet unique "time capsule" into space. We have always been wondering about the existence of advanced space-faring civilizations dispersed throughout interstellar space and had a beautiful fantasy of possibly communicating with them... Do you want to be a designer of the next Voyager Golden Record and send a piece of information that would be unique to you to interstellar space? If so, welcome to the journey!

## What it does
We accept a user input image. The image is then transformed using our hardest-ever yet beautiful algorithm (ECC algorithm) and encoded into a Golden Record which is the only unique disk in the world. Even the same picture would be rendered into two different disks if a different person conducts the encryption, and each picture would have a unique private key associated with it. Of course, with our beautiful algorithm, we are able to translate the message engraving on the disk and transform it back into the original image. Come with your lovely picture and get your disk like a voyager!

## How to use it
Using an IDE, you need to first enable the python flask. Run the app.py file, in the command line, you should see a localhost address. Proceed to that address by right-clicking and selecting the link and following the instruction as mentioned.

## Tech stack
Python (Numpy, PIL, Flask...), HTML/CSS/JavaScript.

## Accomplishments that we're proud of
Everything! We started by getting pretty vague decryption after going through our ECC algorithm. We modified its clarity and largely improved the run time of each encryption/decryption process. We attended almost every workshop and were immersed in the awesomeness of the Wond’ry 24/7.We slept only 3 hours for two days and are still alive :)


## What's next
-  Further optimize the run time of our ECC algorithm and try to achieve a better balance between encryption efficiency and time consumption.

- Improve the robustness of the functions and interfaces on the website

- Allow user input of multiple images to encrypt/decrypt at the same time

- Open up new realms of application (Bitcoin mining, Encrypted chat room, …)


## Citation
- Amara, Moncef, and Amar Siad. “Elliptic Curve Cryptography and Its Applications.” *International Workshop on Systems, Signal Processing, and Their Applications*, WOSSPA, 2011, https://doi.org/10.1109/wosspa.2011.5931464.
- Singh, Laiphrakpam Dolendro, and Khumanthem Manglem Singh. “Image Encryption Using Elliptic Curve Cryptography.” *Procedia Computer Science*, vol. 54, 2015, pp. 472–481., https://doi.org/10.1016/j.procs.2015.06.054.


<hr>

<div>

  <a href="#top">Back to top</a>

  <p style="text-align:center; display: flex; justify-content: space-between">
    <a href="../2_project">Prev: Cloud Office Platform - Back</a>
    <a href="../4_project">Next: MINT Lab Continual Learning</a>
  </p>

</div>
