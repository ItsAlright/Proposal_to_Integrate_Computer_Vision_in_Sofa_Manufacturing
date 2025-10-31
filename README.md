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

**Dataset Plan:**
There will be two groups of data. One for fabric defects, and one for frame defects. The source of the data can be a combination of fabric/frame defects and perfections from a public dataset, like Kaggle.
The size will generally be around 1000-2000, not too small to limit the model’s knowledge on defect detection, but not to big as to take away processing power from the already power-intensive model.
This data will be used to detect and differentiate perfect frames/fabric, and defective frames/fabric.
Due to the nature of this training, the data needs to be labelled so that we can quantify how many the model got right and wrong and improve on that. The data also needs to be cleaned to make it easier to track.

**Week-by-Week Plan**




This is a repository to house all the data needed to apply computer vision into sofa manufacturing.
