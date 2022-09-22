# InferencePatchSampling

The codes for the measurement of the so-called "patch performance" can be found at: https://github.com/IPMI-ICNS-UKE/patch-performance

The patch performance lets you answer the question "What is the optimal stride/ patch-to-patch overlap/ center crop" for your model and data "on the go", e.g., via training. 

As shown in [Widening the Focus: Biomedical Image Segmentation Challenges and the Underestimated Role of Patch Sampling and Inference Strategies](https://rdcu.be/cbiyL), this will usually be much more efficient than the theoretical patch overlap or center crop as derived form the model architecture.
