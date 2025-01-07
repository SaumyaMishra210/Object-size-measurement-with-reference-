# Object Size Measurement with Reference Object

This project demonstrates a method to measure the real-world dimensions of objects in an image using a reference object. The reference object, placed in the top-left corner of the image, serves as a known size standard to calculate the dimensions of other objects in the scene.

By detecting objects and their bounding boxes, the system computes the width and height of each object in real-world units (e.g., centimeters) based on the reference object's size and pixel dimensions. The measurements are annotated directly on the image for easy interpretation.

This approach is useful in scenarios where accurate size estimation is required, such as logistics, manufacturing, and quality control.

## Example Images

### Input Image
![Input Image](path/to/input_image.jpg](https://github.com/SaumyaMishra210/Object-size-measurement-with-reference-/blob/main/example_01.jpg)

### Annotated Output Image
![Annotated Output Image](path/to/annotated_output_image.jpg](https://github.com/SaumyaMishra210/Object-size-measurement-with-reference-/blob/main/output1.png)
