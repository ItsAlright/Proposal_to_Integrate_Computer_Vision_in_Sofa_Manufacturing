# Proposal_to_Integrate_Computer_Vision_in_Sofa_Manufacturing

Proposal to Integrate Computer Vision in Sofa Manufacturing


**The Problem:**
The sofas are often in low quality and are of inconsistent quality between each other. 
This is significant as the company who manufactures sofas prioritizes them to be of high quality to increase their appeal. Plus, in the case that the company will make other furniture with fabric, it needs to improve how it manufactures the already existing sofas.

**Our Solution:**
Present frame of the Sofa → Camera → Use computer vision to inspect defects in the frame of the sofa → Generates report → If successful, present the fabric of the sofa → Camera → Use computer vision to inspect defects in the fabric of the sofa → Generates report → If successful, finish the creation of the sofa.
This process will tackle the structure and presentation of the sofa to improve its quality.

**Technical Approach:**
This plan will utilize automated visual inspections. As such, a combination of techniques are necessary to properly preform the inspection. Techniques such as image processing, object detection, classification, and defect detection, the process of identifying imperfections, often using an automated approach.
Models like ResNet or CNNs are good models to use due to their high-accuracy and precision in detecting defects. However, especially for ResNet, they will take more training time will require careful regularization to prevent overfitting.
TensorFlow and PyTorch are good frameworks for the purposes of detecting defects model.
Since the model needs to detect defects big and small, it needs to dedicate time to it, which is why models like ResNet and CNN are my preferred models. However, for the framework, popular frameworks like TensorFlow and Pytorch can work just fine.

**Dataset:**



This is a repository to house all the data needed to apply computer vision into sofa manufacturing.
