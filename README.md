# Virtual CD3 Immunohistochemistry from Hematoxylin and Eosin with Feature Correspondence

Virtual CD3 immunohistochemistry (IHC) from H&E using feature correspondence. This project identifies the H&E features linked to CD3 and uses them to guide a virtual staining model.

Final year project (COMP3025 Individual Dissertation, 2026/2027), BSc (Hons) Computer Science with Artificial Intelligence, supervised by Dr. Iman Yi Liao.

## Motivation

CD3 IHC identifies T lymphocytes, which are hard to distinguish on H&E. It helps classify lymphomas, and CD3+ cell density can help estimate patient survival. However, IHC is slow and costly, needs specialised laboratories, and permanently alters the tissue.

Virtual staining generates IHC computationally from H&E, but existing CD3 models focus on overall image similarity, so staining can still appear in the wrong places. The specific relationship between H&E features and CD3 also remains unclear. This project investigates whether identifying that relationship can guide a model towards more accurate staining.

## Aim and objectives

The aim is to develop a virtual staining model that improves the accuracy of generated CD3 staining by using the correspondence between H&E features and CD3 as guidance.

1. Establish correspondence by identifying the correlation between H&E features and CD3.
2. Develop a virtual staining model that uses this correspondence to guide CD3 staining.
3. Evaluate the accuracy of the generated staining against VihcGAN while maintaining image quality.

## Dataset

The project uses registered H&E and CD3 whole-slide images from the Malaysian Breast Cancer (MyBrCa) dataset, provided by Cancer Research Malaysia. The dataset is not included in this repository.

