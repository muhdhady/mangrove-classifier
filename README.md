# Mangrove Classifier
A group project completed as part of COE-476: Neural Networks at the American University of Sharjah, aiming to predict mangrove presence at the pixel level using satellite-derived embeddings. The model frames mangrove mapping as a predictive task, using features from one year to predict mangrove extent in the following year.

- **Dataset:** AlphaEarth DeepMind embeddings and Global Mangrove Watch v3.0 labels
- **Training regions:** Abu Dhabi, Mexico, Australia; validated on Saudi Arabia and tested on Umm Al Quwain, UAE
- **Constraints / Challenges:** Severe class imbalance, spatial heterogeneity across regions, noisy ground truth labels, limited GPU resources for training
- **Approach:** Implemented data extraction and preprocessing, developed the full modeling pipeline including U-Net with Squeeze-and-Excitation attention blocks, residual connections, and deep supervision, and conducted model training and evaluation.
- **Results:** On the held-out UAE test region, the model achieved IoU (Mangrove) 0.575, F1-score 0.73, and recall 0.85
- **Future directions:** Improving label quality, exploring semi-supervised learning, and scaling models for larger datasets

**Tech Stack**

Python · TensorFlow · U-Net · Satellite Embeddings (AlphaEarth DeepMind)

_My contributions: Implemented data extraction and preprocessing, developed the full modeling pipeline, and performed model training and evaluation._
