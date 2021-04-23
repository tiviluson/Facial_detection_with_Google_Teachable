# TensorFlow Examples

## Description
- In this project, I am testing my facial dectection model (to detect me and my two lecturers). 
- The model is later implemented with **TensorflowLite** framework. Its initial *EfficientNet* and *MobileNet* models are rewritten to test several configurations on my model.
- Sample data is not uploaded due to privacy issues.

## Result
- Due to the lack of sample data, although the models offer quite disappointing confidence and accuaracy (around 70%).
- One of the class shows worse predictions to the other two, suggesting a posible bias in the model.
- The model stagnates quite soon (at the 10th epoch, with accuracy about 2/3 * 100%), which means the said class is undifferentiable.
<p align="center">
  <img src="/assets/training_visualization.png" alt="Training visualization"/>
</p>
