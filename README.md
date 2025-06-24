# Breast-Cancer-classification-using-VGG16-and-explaining-with-various-XAI-techniques

This project is centered on the automatic classification of breast cancer histopathology images into benign or malignant classes through superior deep learning methods. Building upon the capabilities of VGG16 via transfer learning, this solution provides precise, rapid, and reproducible identification of cancerous tissue from microscope slides.

 Implements Multiple XAI Techniques to Explain Predictions:

📌 Grad-CAM (Gradient-weighted Class Activation Mapping) Highlights the spatial regions in an image that influenced the model’s decision the most.

📌 LIME (Local Interpretable Model-Agnostic Explanations) Explains individual predictions by approximating the model locally with an interpretable model (e.g., linear model).

📌 Integrated Gradients A gradient-based method that attributes a prediction to each input feature by integrating the gradients along the path from a baseline to the input. It produces precise pixel-level attribution maps.

📌 Layer-wise Relevance Propagation (LRP) Propagates the prediction backward through the network, distributing relevance scores to each neuron and input feature.

📌 Decision Tree Interpretation A simple, interpretable decision tree is used:

As a surrogate to approximate CNN behavior in a human-readable format,Or to classify features extracted from intermediate CNN layers.

📌 Feature Map Visualization (Layer Outputs) Helps interpret how the network processes and transforms input images layer by layer, offering insight into what the model "sees" at different depths.
