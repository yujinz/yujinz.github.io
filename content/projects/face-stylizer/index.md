---
title: "Artistic Face Stylizer"
date: 2018-05-05
weight: 60
summary: "A face stylizer that generates artistic mask from portrait painting and puts it onto another portrait photo."
links:
    another_link:
        text: "github link"
        icon: "fab alt brands fa-github"
        href: "https://github.com/yujinz/face-stylizer"
        weight: 1
---

The program detects facial keypoints, warps the painting onto the photo according to the keypoints, and blends them with different weights on different areas.

Inspired by [this paper](http://dcgi.fel.cvut.cz/home/sykorad/facestyle.html) from SIGGRAPH 2017. Simplified the scenario by taking static photo as input instead of video stream.

Collaborated with [Yukang Shen](https://github.com/JohnsonSYK) as the final project of [CS 543 Computer Vision](http://slazebni.cs.illinois.edu/spring18/) at UIUC.

![face-stylizer sample output](https://lh3.googleusercontent.com/d/1czIvnAaIXjvKJiOm_KrrSAyKr9AMQvsy=s220?authuser=0)
