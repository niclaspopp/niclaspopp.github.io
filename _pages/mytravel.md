---
title: "Feature Distillation Improves Zero-Shot Transfer from Synthetic Images"
permalink: /SDKD/
author_profile: true
---
<br>
*Abstract:* Abstract: Vision-language foundation models such as CLIP have showcased impressive zero-shot capabilities. However, their applicability in resource-constrained environments is limited due to their size and the resulting latency. Knowledge distillation allows to mitigate these challenges by distilling small image encoders that can replace the large CLIP image encoder. In a zero-shot setting, where only the class names are known, no real domain images can be used for this process. Instead, we investigate the use of synthetic images for this purpose. Unlike existing works that focus on improving the quality of synthetic images to bridge the performance gap compared to training on natural images, we find the choice of loss to be a crucial factor. Specifically, minimizing only the distance between the student and teacher image features, without incorporating image captions in the loss function, increases the robustness to spurious features and data corruptions. As a result, this feature distillation approach greatly improves the transfer performance from synthetic to real images. Leveraging these insights, we are able to train domain-specific students that achieve zero-shot performance comparable to a ViT-B/32 teacher on six fine-grained classification datasets while using up to 92% fewer parameters.
<br>
<br>
Pictures of my travels: [Instagram](https://www.instagram.com/this_shutter/)<br>
<br>
<br>
<iframe src="https://www.google.com/maps/d/u/0/embed?mid=1N5l37bKWb69Rj_Sv-wVEjZOTq6m3J2-n&ehbc=2E312F" width="640" height="480"></iframe>
