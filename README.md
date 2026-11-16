<div align="center">
  <h1>Look-ahead Distance Validation for Neon-IMU-Analysis</h1>
  <p>
    Vignesh Radhakrishnan, Mark Hollands<br>
    School of Sport &amp; Exercise Sciences, Liverpool John Moores University, UK
  </p>

  [<img src="https://img.shields.io/badge/Website--blue?style=social&logo=googlechrome" alt="Website">](https://vigneshrk29.github.io/gazeVerification/)

  <img src="assets/preview.gif" alt="ScaRF-SLAM map of a trial with the camera path and the gaze rays landing short of the target" width="80%">
</div>

Validation of the look-ahead distance computed from Pupil Labs Neon gaze and our VidMap + VI trajectories (and MASt3R-Fusion), against motion capture: eight trials at LJMU, four on level ground (Qualisys) and four on a staircase (Vicon). The target is tracked in the scene video (SAM 2, CoTracker3) to split the error into its gaze and trajectory parts. Other eye metrics (fixations, saccades, pupil size) are taken as provided by Pupil Labs.

The results page is on the [website](https://vigneshrk29.github.io/gazeVerification/): pipeline, dataset, reference, metrics, ScaRF-SLAM maps with the gaze, tables and summary. The trajectories are validated on the [trajectory validation](https://vigneshrk29.github.io/trajectory-validation/) page.
