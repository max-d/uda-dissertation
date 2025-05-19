# MSc Dissertation Artifacts – GAN-Based Domain Adaptation for Crop Segmentation  
*University of Essex, Department of Computing*

*Max Dudkin*

This repository has been created to archive every artifact generated during the MSc dissertation **“GAN-Based Domain Adaptation for Crop Segmentation in Aerial Imagery.”**  
The study explores whether style-transfer networks can reduce the domain gap between heterogeneous remote-sensing datasets and thereby sustain semantic-segmentation accuracy in precision-agriculture workflows.

## Contents
| Path / File | Purpose |
|-------------|---------|
| `notebooks/` | Jupyter Notebooks that document each project stage (data inspection, baseline U-Net training, CycleGAN adaptation, fine-tuning, evaluation, and ablation studies). |
| `data/dataset_AB/` | **Custom synthetic set** produced by transferring Dataset A into the visual style of Dataset B via CycleGAN. |
| `models/` | Checkpoints for U-Net, CycleGAN, DAFormer, and comparison baselines. |

## Quick Start
1. Clone the repository and create a Python 3.11 environment.  
2. Upload noteooks to Google Collab or another Jupiter Notebook environment.
3. Run notebooks in enumerated order

## Licence & Data Use
All code is released under the MIT Licence.  
Source datasets carry their original CC BY 4.0 licences; the synthetic **Dataset AB** inherits the same permissive terms.

---

*This repository supports the submission of the above-mentioned MSc dissertation (2025). It is intended for academic, non-commercial use. Feedback and pull requests are welcome.*
