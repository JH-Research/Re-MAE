<div align="center">

<h1>Re-MAE</h1>
<h3>Rethinking Masked Autoencoders towards Geometry-Aware<br>Self-Supervised LiDAR-based 3D Object Detection</h3>

<p><strong>Accepted to IEEE ICRA 2026</strong></p>

<p>
Youngho Cheon &nbsp;·&nbsp; Jae-Keun Lee &nbsp;·&nbsp; Soon Kwon &nbsp;·&nbsp; Jin-Hee Lee<sup>*</sup> &nbsp;·&nbsp; Yongseob Lim<sup>*</sup>
</p>

<p>
Daegu Gyeongbuk Institute of Science &amp; Technology (DGIST)<br>
<sub>* Corresponding authors</sub>
</p>

</div>

> **Code and model weights are being prepared for release.** They will be made available in this repository once ready.

## Overview

**Re-MAE** is a geometry-aware self-supervised pre-training framework for **LiDAR-based 3D object detection**. It rethinks **“what to learn”** and **“how to learn”** by considering occlusion, distance-driven sparsity, and occupied–empty voxel structure.

The framework combines three components:

- **Geometry-Aware Masking** simulates spatially contiguous occlusions with a distance-aware masking ratio.
- **Reconstruction-Contextual BCE (ReCon BCE) loss** guides multi-scale occupancy prediction through distance, boundary, and masking weights.
- **Realistic Object Augmentation** increases foreground diversity in unlabeled point clouds while accounting for distance-dependent point density.

Pre-training uses no ground-truth annotations. The pre-trained encoder initializes the backbone of a downstream 3D object detector, which is then fine-tuned with labeled data.

## Release Status

Code and model weights are not yet available. They will be released here once preparation is complete.

The paper link will be added when available.

## Citation

Please cite the accepted conference paper below. Publication details will be updated when available.

```bibtex
@inproceedings{cheon2026remae,
  title     = {{Re-MAE}: Rethinking Masked Autoencoders towards
               Geometry-Aware Self-Supervised {LiDAR}-based
               {3D} Object Detection},
  author    = {Cheon, Youngho and Lee, Jae-Keun and Kwon, Soon
               and Lee, Jin-Hee and Lim, Yongseob},
  booktitle = {2026 IEEE International Conference on Robotics and Automation (ICRA)},
  year      = {2026},
}
```

## Contact

For questions about this work, please contact [Youngho Cheon](mailto:yhcheon@dgist.ac.kr).
