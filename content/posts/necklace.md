---
title: necklace
tags:
draft: true
---

## 避免震盪

yaw/roll how to label?

## model structure

resnet50

stem ->4 stage-> fc

3.53M

MMCV?

## how to label by human?

occulor

where is the plane

gaussian factor for data sugmentation

ViTAE transformer (background changing)

## pramerter
cosine annealing
normalized mean error
batchsize:128

AP(Average precision, defaultrange[0.06,0.1], tep=0.005)

SDD(standartd deviation of difference)

## QA
inputsize? 192*256
what is the bounding box for?
head enlarge怎麼做？

## loss
192*256
compositional human pose regression (ICCV)

batchsize 兩倍 learning rate 兩倍

AdamW

HRVITON(換衣服)

mish activation functions

AID(augmentatiion by information dropping)

## next
juggling plate
regressor?

yaw/roll/pitch

differitiable renderer