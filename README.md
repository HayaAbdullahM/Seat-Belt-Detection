# Seat Belt Detection

This project focuses on Seat Belt Detection using various versions of YOLO (You Only Look Once) models, including YOLOv5, YOLOv8, and YOLOv9. It is developed as part of an image processing course to evaluate the performance of different YOLO versions on a consistent dataset. The primary objective is to compare the variations in YOLO models concerning accuracy, speed, and other relevant metrics.

## Introduction

Seat belt detection is a crucial task in ensuring road safety. By employing computer vision techniques, we can automatically detect the presence or absence of seat belts in images, which can aid in enforcing safety regulations and promoting awareness among drivers and passengers.

## Dataset

The dataset used for this project consists of annotated images containing various scenarios with seat belts. This dataset is carefully curated to ensure consistency across different YOLO models' evaluations. The dataset can be accessed and downloaded from the following link: [Seat Belt Dataset](https://universe.roboflow.com/fay-regu8/seat_belt-iauiy).

## YOLO Models

### YOLOv5
YOLOv5 is the latest version of the YOLO family, known for its lightweight architecture and improved performance. It offers a balance between speed and accuracy, making it suitable for real-time applications.

### YOLOv8
YOLOv8 is a modified version of the YOLO architecture, incorporating enhancements and optimizations to improve detection accuracy and speed. It aims to address some of the limitations observed in earlier versions while maintaining efficiency.

### YOLOv9
YOLOv9 represents further advancements in the YOLO series, leveraging state-of-the-art techniques to achieve superior performance in object detection tasks. It introduces novel features and optimizations to push the boundaries of accuracy and speed.

## Evaluation

The performance of each YOLO model will be evaluated on various metrics, including:

- **Accuracy**: The ability of the model to correctly detect seat belts in images.
- **Speed**: The inference speed of the model, measured in frames per second (FPS).
- **Robustness**: The model's ability to generalize to unseen data and handle different scenarios.
- **Resource Usage**: The computational resources required to deploy and run the model effectively.

## Usage

To replicate the experiments conducted in this project, follow the steps outlined in the repository:

1. Clone the repository:
   ```bash
   git clone https://github.com/HayaAbdullahM/Seat-Belt-Detection.git
   ```

2. Install the necessary dependencies:
   ```bash
   pip install -r requirements.txt
   ```

3. Train and evaluate the YOLO models on the provided dataset.

## Conclusion

Through this project, we aim to provide insights into the performance characteristics of different YOLO models for seat belt detection. By comparing and analyzing the results, we can identify strengths, weaknesses, and potential areas for improvement in each model. Ultimately, our goal is to contribute to the advancement of computer vision techniques for enhancing road safety measures.

## License

This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for more details.

