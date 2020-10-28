**Choosen Dataset from Kaggle** : [https://www.kaggle.com/andrewmvd/face-mask-detection](https://www.kaggle.com/andrewmvd/face-mask-detection)

## Tried both ssdlite\_mobilenet\_v2\_coco and faster\_rcnn\_inception\_v2\_coco

- I have trained both the models with **150k steps** and have acheived good accuracy in Faster RCNN when compared to SSDlite.
- Loss in Faster RCNN after 150k steps is 0.3.
- Loss in SSDlite mobilenet after 150k steps is around 1.2
- But the Frames per second is very good in SSD(10+ FPS) when compared to Faster RCNN(0.7 FPS). 

## **References:**

https://github.com/hgoyal194/real-time-facemask-detection/blob/master/README.md
