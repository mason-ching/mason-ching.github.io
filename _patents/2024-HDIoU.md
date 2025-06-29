---
title: "Intelligent Analysis Method of Stomatal Phenotype of Crop Non-destructive Leaves Based on HDIoU"
collection: patents
# permalink: /patents/2024-HDIoU
excerpt: |
    <p style="font-size: 16px; margin: 5px 0 0 20px; margin-left: 0px; color: #666; text-align: justify;">
        In this invention, we design a triphasic Hellinger Distance based Intersection over Union (HDIoU) for oriented bounding boxes, and apply it to train YOLOv8-OBB on non-destructive leaf stomatal images. HDIoU models each oriented bounding box as a 2D normal distribution and computes the triphasic Hellinger distance between predicted and ground-truth distributions as the box regression loss. It enables models to focus on different objectives at different training periods: in the first phase, the goal is to quickly move the predicted box close to the target; in the second phase, the emphasis shifts to maximizing the overlap between the predicted and ground-truth boxes; in the third phase, the model additionally fine-tunes the predicted box dimensions to closely match the target box’s length and width. The triphasic mechanism does not require manually splitting the training, but leverages a dynamic indicator to automatically determine the current optimization focus during training, allowing the loss function to continuously transition within a single unified learning process. This design enables the model to progressively refine predicted boxes by adjusting its attention—from general proximity to precise alignment of orientation and shape—without interrupting training. Moreover, HDIoU is scale-invariant, making it particularly well-suited for accurately detecting small objects such as stomata.
    </p>
link: 'https://patents.google.com/patent/CN118691972A/en'
date: 2024-09-24
prefix-venue: 'Henan University'
venue: 'CN118691972A'
inventors: "Lichao Peng, Meng’en Qin, Xiaohui Yang, Chen Miao, Yanfeng Sun"
---