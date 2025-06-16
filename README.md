Here we provide the code for generation of synthetic AMD images using GAN. This project won title in IEEE IES Generative AI Hackathon' 2024 (https://ai.ieee-ies.org/previous_winners/index.html)

There are both Retrospective and Prospective Images.
Retrospective data - The folders CNVM, Drusen, CNVM Labels and Drusen labels are the retrospective images with the corresponding anomalies. i.e., the folders Drusen and CNVM contain whole-slode images with those anomalies. The folders CNVM Labels and Drusen labels contain the annotations done for CNVM and Drusen on these images.Totally there are 60 retrospective images.

Inside the folder Prospective images, the similar images collected in real-time from hospitals are available. There are 41 CNVM images and 15 Drusen images.


The utility of this repositary can be two-fold
1. To generate AMD classification algorithms with whole-slide images  (Or) to generate algorithms for Segmentation of Drusen and CNVM with whole-slide images and ground truth label-maps.
2. To execute generative AI algorithms to generate synthetic AMD images. In the IEEE-IES Generative AI hackathon, we synthesized AMD images with specific anomalies by directing attentions to the label maps.
