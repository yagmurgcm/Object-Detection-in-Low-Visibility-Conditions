

This project investigates object detection performance in low-visibility environments such as fog, snow, rain, and dust, where reduced contrast and blurred object boundaries make detection significantly harder. The study focuses on intelligent transportation and micromobility safety by comparing CNN-based and Transformer-based detection models using the DAWN (Detection in Adverse Weather Nature) dataset.

The dataset is organized in Ultralytics YOLO format to ensure compatibility with modern detection frameworks. However, due to the large number of images, the DAWN dataset could not be uploaded to GitHub. You will need to download or prepare the dataset separately and place it in the appropriate directory structure before running the code.

The project compares four model families: YOLO9000, YOLOv10, RT-DETR, and YOLOv11. Since running all original models under the same environment is not practical, proxy models are used. YOLOv5n represents YOLO9000, YOLOv8n represents YOLOv10, RT-DETR is used directly, and YOLOv8s represents YOLOv11.

Due to hardware limitations, full training and benchmarking on the DAWN dataset were not completed. Instead, the project focuses on dataset validation and a literature-supported comparative analysis. The results suggest that modern YOLO-style models offer a strong balance between accuracy and speed, while RT-DETR provides better contextual understanding but requires higher computational resources.
