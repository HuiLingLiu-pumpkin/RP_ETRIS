# RP_ETRIS
Reproduce ICCV 2023 paper----"Bridging Vision and Language Encoders: Parameter-Efficient Tuning for Referring Image Segmentation"

In the original paper, the authors used three datasets (RefCOCO, RefCOCO+, and G-Ref). The reproduction of this paper was carried out in the RefCOCO dataset and the following table shows the experimental results of the evaluation metric IoU.

| Method | Backbone | Param. | val | test A | test B |
| ------------- | ------------- | ------------- | ------------- | ------------- | ------------- |
| ETRIS  | CLIP ResNet-101  |1.94M  | 71.06  |74.11  | 66.66  |
| ETRIS_RP  | CLIP ResNet-101  |1.94M  | 71.09  |73.72  | 66.79  |
| ETRIS  | ResNet-50  |1.68M  | 70.39  |73.11  | 66.38  |
| ETRIS_RP  | ResNet-50  |1.68M  | 69.88  |72.76  | 65.35  |
| ETRIS  | ViT-B-16  |1.39M  | 70.51  |73.51  | 66.63  |
| ETRIS_RP  | ViT-B-16   |1.39M  | 70.66   |  73.89 |   66.84 |
