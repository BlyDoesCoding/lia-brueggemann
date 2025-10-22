---
title: 'Raylib'
slug: 'raylib'
tags: ['Coding', 'C', 'GPU', 'library']
summary: # This is what will be displayed as summary for the post (the theme will automatically generate one from the content you write in the post if left empty)
description: # This is what will be displayed as meta data (the theme will automatically grab it from summary if left empty)
date: '2025-10-21T12:10:50+02:00'
expiryDate: '' # You want your post to vanish after a certain date? Write it down here! Must be in the same format of `date`
translationKey: raylib # If you have a translated post for this one, set the same translationKey to have the translation displayed
draft: false # Set wether this post is a draft
layout: 'single'
Params:
  imageAttribution: 'Photo by <a href="https://unsplash.com/@flotography_91?utm_source=unsplash&utm_medium=referral&utm_content=creditCopyText">FotoFlo</a> on <a href="https://unsplash.com/photos/an-aerial-view-of-a-body-of-water-Mpw7y01WrtY?utm_source=unsplash&utm_medium=referral&utm_content=creditCopyText">Unsplash</a>' # Set an attribution to the author of the picture you're using for the post
# Refer to [Front matter | Hugo](https://gohugo.io/content-management/front-matter/)
---

## Games and libraries
I have recently been wanting to do more in terms of game dev. At the moment I'm also trying to get more into C; thus, I decided to dive into said endeavor with C. A game usually needs 3 components.

    * getting input from the player
    * processing said inputs
    * displaying fancy images to the player

I started with searching for a good solution to graphics. We have plenty of ways to do so, just to name a few:

    * Vulkan
    * OpenGL
    * Metal
    * DirectX

**DirectX** is Xbox and Windows exclusive, so I didn't go with that. **Metal** is a weird Apple thing that I don't even really own any devices supporting it. So that leaves me with **OpenGL** and **Vulkan**, which are both cross-platform. **OpenGL** being the older and way easier one, I decided to go with that. After some testing around together with **GLFW** as a window library, I found myself running into issues. The learning curve was easier than anything I would have had with **Vulkan** but still a very long and steep one. After writing hundreds of lines just for simple image displaying, which I mostly needed to implement myself, I had more than enough already. I liked the idea of working with very low-level code, but it was simply not fun for me at that time. While my pretty much only alternative, **Vulkan**, needed 1000+ lines of code just for displaying a simple triangle, which is the Hello World of graphics programming, I needed another way.

Here comes the solution, which is my new favorite software library: **Raylib**.

## My time with Raylib
**Raylib** is an extremely simple-to-use C library that provides pretty much all the needed functions to make a working game. Yes, not only did it provide graphic interfaces to render shapes, textures, and models as well as shaders, but it also provided many more features, such as handling input with many devices and also a very comprehensible math library.

I found myself quickly making progress. First testing out simple **2D** mechanics like making a simple Pong game, I tested things in **3D** as well. It was so simple to use; it just was a lot of fun. Even the installation was simple. It being a single C header and having plenty of bindings for other languages, I installed the library via my package manager and included the **raylib.h**.

All in all, I have really enjoyed my time with **Raylib** so far. It's been around for a long time and thus has plenty of examples, tutorials, and even a very dedicated contributor list.

If you want to tinker with it as well, go to [raylib.com](https://www.raylib.com) and start doing what you want. If you don't know what to do first, just take a look at their cheat sheet, which is super simple.
