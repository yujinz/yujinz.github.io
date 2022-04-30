---
title: "STARTS Offline Mode"
date: 2017-12-05
weight: 61
summary: "Contributed to STAtic Regression Test Selection Maven plugin by making the dependency analysis phase run in parallel with the test execution phase."
links:
    another_link:
        text: "github link"
        icon: "fab alt brands fa-github"
        href: "https://github.com/yujinz/starts"
        weight: 1
---

![starts offline workflow](https://lh3.googleusercontent.com/iPvJCKC6MGpAsM4-O0_2yNIxUcHnhVYI4GiHrGacqCBn5kmrq4dNX_J0x6Vbti_gZSFfJ5h93lkpd4pQCe2QoqSNwQ-RB1gMQvT9WJWE947uS-s-o2vKeglHOWmA83pri0_H_go58VmOfaDPrjwza7rQDK11hhnvwK8W98qzSgWVc9WiTpLCg89ewvBkUrqId3-JPUD72C2axzg6esouq2wj07WbsPpfKjSY0oN0NvlZuJohwobnyPvNx_9tJjv-iph9xJ8lfoqhMlf3XnIOL4RW-CGzLHiRRjcRr8cJveAjw9UFrXX0S1wCu7vyqMs0Q4bG8odBr3YefcHd5MSJVch4oaL3ckiWVhBhEgZfMLjc_6dRXhOEsluXrKzfDm5eODTQVfOqonDAl0_g5R2AHZtawHBv2X_HjAedCVouD2gcWpoJOQBpjCiMISkwIKpl-VJMkSy2dINUUWQU47jiuimvkUSCWiZHnyTSBYqEEEMKpxSVvC4zjD6xEJTdHLhiFhf2ny8_k7l5x1vm5xz2I2vbA4kZNdMedHOYA5hN2gmZTsVfewWoDQ3sqW7soQ93LCySvOGaEDAGwuHHpTEETK4-mIyK6aLLff-It0A=w740-h309-no)

STARTS (STAtic Regression Test Selection) is a Maven plugin to run only the impacted tests since last build. I implemented the idea of offline mode from [this paper at ASE 2017](http://mir.cs.illinois.edu/legunsen/pubs/LegunsenETALSTARTSDemo.pdf) and speeded up the phase by 70%.

This was a semester-long project of [CS 527 Advanced Topics in Software Engineering](https://wiki.illinois.edu/wiki/display/cs527fa17) at UIUC.
