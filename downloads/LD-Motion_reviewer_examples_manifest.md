# LD-Motion Reviewer Example Package

This package is provided for NeurIPS reviewers to inspect representative LD-Motion data examples.

Contents:

- Raw synchronized RGB videos for an AP001 02_Lunges sequence across the eight calibrated camera views.
- Face-mosaic RGB videos for privacy-aware visual inspection.
- OpenPose25 overlay videos showing projected 2D skeleton annotations on the RGB frames.
- Per-frame annotation files, including Vicon-derived 2D keypoints and residual/prosthesis-aware keypoint metadata.
- Vicon-derived 3D keypoint references in the example annotation structure.
- Vicon-constrained fitted mesh annotations exported as OBJ files in Vicon millimeter coordinates.
- Rendered image examples for quick inspection of 2D keypoints, 3D keypoints, and fitted mesh references.

The mesh references are benchmark fitting references generated from model initialization and Vicon-constrained refinement. They should not be interpreted as clinical surface scans.
