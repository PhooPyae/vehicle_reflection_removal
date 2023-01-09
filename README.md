# Reflection Removal on Cars
GROUNDTRUTH            |  AFTER REFLECTION REMOVAL
:-------------------------:|:-------------------------:
![tesla-model3--performance-DO8J67-carro-002](https://user-images.githubusercontent.com/20230956/211248602-432b2853-4ad1-4f44-821a-3c1e74b93fd4.jpg)  | ![download (1)](https://user-images.githubusercontent.com/20230956/211249058-3c19012a-01e5-45e8-a080-caa682fb06ae.png)

Background Replacement without reflection removal            |  Background Replacement with reflection removal
:-------------------------:|:-------------------------:
![regression-01-03-G3Z6YG-carro-003](https://user-images.githubusercontent.com/20230956/211249694-7457923a-72eb-48f3-b074-ab2c0c478594.jpg) | ![regression-01-03-G3Z6YG-carro-013](https://user-images.githubusercontent.com/20230956/211249762-8a524e45-1521-43c6-a4bb-9def47ebe119.jpg)


## Objective
Reflection removal plays an important role in background repalcement. There are different types of reflection such as glare, environmental reflection. Among those reflections, environmental reflection makes the output wrong and unnatural. 

## Reflection Removal Approaches
1. Detect reflection and inpaint using inpainting models (On Progress)
2. Remove reflection instantly using SIR models (Not Started Yet)

## Approach 1: Detect reflection and inpaint using inpainting models
* Detect reflection with reflection detection model (Single class)
* Inpaint using Large Mask Inpainting (LaMa) model

