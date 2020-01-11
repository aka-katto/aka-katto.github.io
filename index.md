
# aka_katto's resume!

# About Me 

*(aka_katto vaguely means 'red cat')*

Hello dandere2x lurker and or future prospective employment recruiter, welcome to my page! This page briefly serves as a less formal resume, where I can talk more personally about my projects (as on my resume it's rather brief), and include pictures showcasing my works.

Online I go by the handle of aka_katto for online persona reasons, but in real life, I go by Tyler!

# Project Showcase

## Project: Dandere2x

### Overview
----

Dandere2x is the first video compression algorithm for SRCNN (super-resolution convolutional neural network) image upscalers.  Dandere2x makes use of visual redundancies found in animation to reduce the time needed for a GPU to upscale an image, as it greatly reduces the number of pixels needed to be processed.

[Github](https://github.com/aka-katto/dandere2x)


### Screenshots: GUI:

![GUI for Dandere2x](https://camo.githubusercontent.com/7d9b611d93b2cff858880b6a58e3bc2df2e21301/68747470733a2f2f692e696d6775722e636f6d2f505765374e7a562e706e67)
Image: An older screenshot of what the user sees when using the dandere2x GUI.
### Screenshot(s):  How Dandere2x Uses Visual Redundancy to Save Time
![A demonstration gif](https://camo.githubusercontent.com/3727a7c484c3288edef3b352e5cd113e3737cb43/68747470733a2f2f692e696d6775722e636f6d2f4f6f376b366a6c2e676966)
GIF: An example of a scene with a lot of visual redundancies.

![enter image description here](https://camo.githubusercontent.com/b16861b1b31a151af0a66241855d503072750ab6/68747470733a2f2f692e696d6775722e636f6d2f3173316268644c2e706e67)
Image: A visual intuition of how Dandere2x takes advantage of visual redundancy to speed up upscaling time. 

### Fun Statistics (as of 01/07/20)
----

**Most Viewed Dandere2x Video**: [68,728 views](https://www.youtube.com/watch?v=sfD_D9KVfzE)


**Subreddit subscribers:** [241 Readers](https://www.reddit.com/r/Dandere2x/)


**GitHub stars:** [171 Stars](https://github.com/aka-katto/dandere2x)

### Dandere2x in Media

---
1) [Jeden Anime in 4K sehen! (theoretisch)](https://www.youtube.com/watch?v=GnBjfTihYRk "Jeden Anime in 4K sehen! (theoretisch)") 


A fan-made german video explaining how dandere2x works and how it is used to process videos using waifu2x faster.


2) [Dandere2X - 图文实战教学 - 基于Waifu2x的动漫风格视频Upscale工具的基础应用](https://www.bilibili.com/read/cv2975001/)

A fan-made tutorial of how to use an older version of dandere2x in Chinese. 

### Technological Accomplishments
---

This is a non-exhaustive list of programming features I either developed or deployed in my project

#### 1) Multi-language project (C++ and Python)

Early on in Dandere2x development, java was deemed too slow for the costly computations needed. Eventually, the cost-intensive functions were ported to C++, whose outputs are read by python for the less computationally demanding tasks. 

#### 2) Threading / Parallelism

Dandere2x uses extensive use of key modular components to run in parallel to minimize the experienced run time for the user. Each threaded class is programmed in such a way, if *killed* by the user, it can be resumed in a later dandere2x session, allowing for dandere2x sessions to be suspended and resumed. 

#### 3) GUI Driven User Operation

To appeal to a more general audience, Dandere2x comes included with a GUI executable for ease of use, although users and tinkerers can still run dandere2x through a YAML driven operation.

#### 4) Dandere2x Specific Tools

In this section, I'll briefly articulate the tools I developed myself for dandere2x.

- Adding scalar quantities to images to replicate the compress the fade to black/fade to white scenes in a video.
- Using the quality loss from discrete cosine transformations to determine the acceptable loss of an image block within a video.
- Using PSNR as a means of approximating if two images are related to each other, to prevent dandere2x from compressing two frames that are too unrelated to one another.
- Suspending / Resuming the FFmpeg subprocess to control how many frames extracted from a video may appear on a disk at a given time.

## Project: Fun Grade 

### Overview:

Fun Grade was a website I wrote while I was a TA in community college, and was developed (roughly) over two weekends. The application was heavily modified from the [notto](https://github.com/renatoliveira/notto) Django application to fit the needs of being an online lab-grading tool.

###  Screenshot: Lab Submission Page

![A typical picture of a lab submission a user would see.](https://i.imgur.com/iXsJ7hS.png)
### Full Demonstration

To keep this page small, a full demonstration can be found in this IMGUR album.

[Album](https://imgur.com/a/xR4adJA)
