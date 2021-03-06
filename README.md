# **LIRAT**

## Project

- Frontend: [link](https://github.com/YSC9848/LIRAT-Frontend)

	- Not Open-Sourced Yet

- Backend: [link](https://github.com/YSC9848/LIRAT-Backend)

	- Not Open-Sourced Yet

## The vedio of the tool can be seen at: https://youtu.be/fnIi2SrzKmg

## **LIRAT**: Layout and Image Recognition Driving Automated Mobile Testing of Cross-Platform

The fragmentation issue spreads over multiple mobile platforms such as Android, iOS, mobile web and even WeChat, which hinders test scripts from running across platforms. To reduce the cost of adapting scripts for various platforms, some existing tools apply conventional computer vision techniques to replay the same script on multiple platforms automatically. However, because these solutions can hardly identify dynamic or similar widgets, it becomes difficult for engineers to apply them in practice. 

In this paper, we present an image-driven tool, namely **LIRAT**, to record and replay test scripts cross platforms, solving the problem of test script cross-platform replay for the first time. **LIRAT** records screenshots and layouts of the widgets, and leverages image understanding techniques to locate them in the replay process. Based on accurate widget localization, **LIRAT** supports replaying test scripts across devices and platforms. We employed **LIRAT** to replay 25 scripts from 5 application across 8 Android devices and 2 iOS devices. The results show that **LIRAT** can replay 88% scripts on Android platforms and 60% on iOS platforms.

![workflow](workflow.png)
