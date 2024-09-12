<center><h1>DualAnoDiff</h1></center>
# DualAnoDiff
<!-- ::--:DualAnoDiff: Dual-Interrelated Diffusion Model for Few-Shot Anomaly Image Generation::--: -->

## Abstract
The performance of anomaly inspection in industrial manufacturing is constrained by the scarcity of anomaly data. To overcome this challenge, researchers have started employing anomaly generation approaches to augment the anomaly dataset. However, existing anomaly generation methods suffer from limited diversity in the generated anomalies and struggle to achieve a seamless blending of this anomaly with the original image. In this paper, we overcome these challenges from a new perspective, simultaneously generating a pair of the overall image and the corresponding anomaly part. We propose DualAnoDiff, a novel diffusion-based few-shot anomaly image generation model, which can generate diverse and realistic anomaly images by using a dual-interrelated diffusion model, where one of them is employed to generate the whole image while the other one generates the anomaly part. Moreover, we extract background and shape information to mitigate the distortion and blurriness phenomenon in few-shot image generation. Extensive experiments demonstrate the superiority of our proposed model over state-of-the-art methods in terms of both realism and diversity. Overall, our approach significantly improves the performance of downstream anomaly detection tasks, including anomaly detection, anomaly localization, and anomaly classification tasks.
<img src="https://github.com/user-attachments/assets/187ef4ce-eaf0-4743-a94b-f627e26ab894" width="450px">
<!-- ![image](https://github.com/user-attachments/assets/187ef4ce-eaf0-4743-a94b-f627e26ab894) -->


# Method
![image](https://github.com/user-attachments/assets/8ef86e87-4c48-42b4-8dec-235a9d744f8a)


# Result
![image](https://github.com/user-attachments/assets/7128b95d-3a35-4838-ad88-c2150afdee2d)

## Comparison in Anomaly Generation
### Anomaly Generation Quality
![image](https://github.com/user-attachments/assets/196d6147-f010-4c69-a5d5-89df94a80bb6)
### Anomaly Generation for Anomaly Detection and Localization
![image](https://github.com/user-attachments/assets/18e29fe2-b613-4fc2-98e3-1a5f2860b8a1)

## Comparison with Anomaly Detection Models
![image](https://github.com/user-attachments/assets/f793f984-e746-4d2d-bc1b-8d50144a0eb2)



