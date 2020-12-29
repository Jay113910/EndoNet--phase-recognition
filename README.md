# EndoNet (phase recognition)

This is a PyTorch implementation of ['EndoNet: A Deep Architecture for Recognition Tasks on Laparoscopic Videos'(2016)](https://arxiv.org/abs/1602.03012) by Twinanda et al.

## Dataset
[Cholec80](http://camma.u-strasbg.fr/datasets) : The Cholec80 dataset contains 80 videos of cholecystectomy surgeries performed by 13 surgeons. The videos are captured at 25 fps. The dataset is labeled with the phase (at 25 fps) and tool presence annotations (at 1 fps). The phases have been defined by a senior surgeon in our partner hospital. Since the tools are sometimes hardly visible in the images and thus difficult to be recognized visually, we define a tool as present in an image if at least half of the tool tip is visible.
