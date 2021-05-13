# Medical Image Annotation Job

In this project I tested my habilities to build a labeled dataset that distinguishes between healthy and pneumonia x-ray images; this can be used by ML engineers later on down the line to build a classification product. The data used is a modified version of the [Kaggle chest x-ray dataset](https://www.kaggle.com/paultimothymooney/chest-xray-pneumonia), with most labels removed. The goal is to build a product that can helps doctors quickly identify cases of pneumonia in children. It uses a classification system that:

- Can help flag serious cases
- Quickly identify healthy cases
- Act as a diagnostic aid for doctors

Annotators should identify visual symptoms on x-ray images that indicate pneumonia. The most important areas to have annotators pay attention to are the lungs and the diaphragm.

- A normal, healthy image will depict clear lungs without any areas of abnormal cloudiness/opacity; there may be structured, web-like vasculature in the lungs but otherwise that area should be clear. In healthy images, you are also more likely to see a diaphragm shadow.
- A pneumonia image may include a few things: areas of cloudiness/opacity in several concentrated areas or one large area. You may also see a general pattern of opacity that obscures the structure of the lungs, heart and diaphragm.

The data labeling job was design with the Appen's platform, and it includes instructions for annotation and example test questions. Additionally, it was added a proposal document that discusses the design of the job and the steps I took for quality assurance.
