---
title: "Artistic Face Stylizer"
date: 2018-05-05
link: https://github.com/yujinz/face-stylizer
weight: 60
categories:
- Projects
thumbnailImagePosition: left
thumbnailImage: https://lh3.googleusercontent.com/piS-UvqgX7pkmB8YssS8j9U6m1-dAd9KumbTx5Fg3wJLnxfFT72wC_jlGem2njx_7D6yZnJcC1CrkuNrMc8yhb-mi_hlW6wLYyoW25bQO1fY2bmlcGHW2bcOOOYQ7HocCP_TyStBUiYhD7ehZMJDKkTpFStYmWf1Pdpnl1MuMyz6NPZJuDJzcC5wB7Pq8Sp099PbWwPZKF9TDHuXnAIXl02rGCtK8lcAEYO3ucv1PhT_Mswbcnc-M1USaPOOJyQgyxJtT-2m0cbibubeYAG_HLgaagII8r_FH3tRHRj95nPMrcA4PQh__bM5Ik724WviTXSL06_WYJyHO0nxURWxkFFkNh2zgyYivSGnDaQvTrnX8S0b-dqsT6Za3QIgMpWsTsZoHhcYE8cHZecRXfRcqdTeDGH5FiFil4OAgl33emHW2dHXgQB3WoAYPidAK7Wgd-tOBdNfrDZ5TJgJ_7Hpn5aVwvf6BFRp7O2mljHKFqx5ztMX0vmjWsdFgD2eQ1G-UP-ykbFyn4c3-YAG0LKdeu9pFg5qnCXsoMZoDRAWXfTOYSq0i9qRyjWi27uDlTTszGvQW0-pGx73rOCzXoITrXZywSJiXhlgFZnJ9VEqVksQez4RmUrsOlMVV-nzaQv0ugpMHwjBHtMuQI1S-ufIqbhJ_Cb8bm8s=s540-no
---

A face stylizer that puts an artistic mask generated from a portrait painting on the face in a photo. It detects facial keypoints in both the painting and the photo, warps the painting onto the photo according to the keypoints, and blends them with different weights on different areas.  
<!-- more -->

![face-stylizer sample output](https://lh3.googleusercontent.com/KKVgCAmuKaKoM25gazrU052NLO9K_IIafS2i-i7zf6YJ6LRGZbdgZe0vehgfqJ8ybyu6p_oe5uS8-1v0mjL_uPZSSiTS3pU9rUkftuZ7M-W5ZNvVzj1-LO7ZwLBDlI9iRKtuUVkUsqHkFuwPvE0fF2OQx4HsjVe4dRtWQj3GkeqrwYQVdoQLCc4_DBYCU3grd1wuahSm3nlyGa2fY1StNb82eVvrXfHI7VDmiyj3zKHUsucQ3YGaYzNscEC1PUjUNC9chs_TFYhmoa9MfkX4LTA8nR7DJA5Y7POe3KlqqTQFvxRTLZNQRklL-KzqvZBvQYe4v6A1hljfr_liOQtNGygY5n5a8afa-7bEiFPXtfj-jAsPN9iUHArSLg04IooRVnRGTGQ2gR4hja9uuLYYwntpLDQL27muOKUoyOdWxBPXOoFYyod9NU-FPhbyzz3dEk94em9LyWyulnpRWbZyMYezga9KDpgRnLUEIj6FJ65FkiGnUwjnhi6F8N71kKvpNfLBL730iaoWF89Bt4ndGLCbqDrw1gB5wR9OQpopFObnOv4WCyl8Umz49pdO81zF2gwLbCYq-RAZtclXqMtYq07wC0g55YfRlJYYvjAotoYjd4jnJUE1350NRg1eotF_FyFEVcDSBN0p_c0C0Rvl0y5hf1q9iCZX=w644-h451-no)

Inspired by [this paper at SIGGRAPH 2017](http://dcgi.fel.cvut.cz/home/sykorad/facestyle.html). Simplified the input from stream videos to static photos.

Collaborated with [Yukang Shen](https://github.com/JohnsonSYK) as the final project of [CS 543 Computer Vision](http://slazebni.cs.illinois.edu/spring18/) at UIUC.
