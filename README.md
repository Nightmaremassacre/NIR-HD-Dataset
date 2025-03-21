# NIR-HumanDetection Dataset (NIR-HD) Creation Using Hongshikang HSK-ZX001-V1.0 Monocular Near-Infrared Camera

We have created a dataset named NIR-HumanDetection Dataset (NIR-HD) using the Hongshikang HSK-ZX001-V1.0 monocular near-infrared camera (850nm wavelength, 1920×1080 resolution, 30fps frame rate). The dataset comprises 1446 valid near-infrared images, covering a variety of scenes. 

![Example Image](/dataset.png)

Here is a detailed breakdown:
## Distance Categories
- **Close Range (Within 1 Meter)**: Images taken from a very short distance.
- **Medium Range (1 Meter to 2 Meters)**: Images captured from an intermediate distance.
- **Long Range (2 Meters to 5 Meters)**: Images taken from a far distance.

## Lighting Conditions
- **No Light**: Images captured in complete darkness.
- **Low Light (Reflected Light from Display Screens)**: Images taken in environments with minimal lighting, primarily from the reflection of display screens.

## Human Poses and Angles
The dataset also includes various human poses and angles, such as:
- Standing
- Crouching
- Squatting
- Lateral positions

## Data Annotation for Object Detection
The images in the dataset have been annotated for object detection purposes. Below are some examples of the collected data detected by the YOLOv5 model:

![Example Image](/dataset_detect.png)

These examples illustrate the diversity of scenarios and conditions present in the NIR-HD dataset, making it a valuable resource for research and development in the field of near-infrared human detection.
