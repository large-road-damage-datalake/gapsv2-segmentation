# GAPSv2

## Overview

GAPSv2 is a task-specific segmentation package derived from GAPs v2 with pixel-level labels.

- Task: segmentation
- Images: 2410
- Annotations: 4179
- Classes in local package stats: 6 (applied_patch, crack, inlaid_patch, open_joint, pothole, street_inventory)
- Annotation format: grayscale PNG masks (class-coded)

## Source Dataset

- Name: German Asphalt Pavement Distress Dataset - GAPs v2
- Source URL: https://www.tu-ilmenau.de/neurob/data-sets-code/german-asphalt-pavement-distress-dataset-gaps
- Source paper: https://ieeexplore.ieee.org/document/8852257

## Access Requirement

The source website states the dataset is not fully open download. Access requires written permission and login credentials for academic use.

## Acquisition Process (as described on source website)

1. Install downloader package: `pip install gaps-dataset`
2. Send completed request form to provider email to receive login:
   - Form: https://www.tu-ilmenau.de/fileadmin/Bereiche/IA/neurob/Datasets/Request-Gaps3.pdf
   - Email: nikr-datasets-request@tu-ilmenau.de
3. Download GAPs v2 segmentation with provider-issued login:
   - `gaps.download(login='...', output_dir='...', version=2, patchsize='segmentation')`

## Repository Links

- Package repo: https://github.com/large-road-damage-datalake/gapsv2-segmentation
- Source dataset: https://www.tu-ilmenau.de/neurob/data-sets-code/german-asphalt-pavement-distress-dataset-gaps
