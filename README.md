**This work was performed under the auspices of the U.S. Department of Energy by Lawrence Livermore National Laboratory under Contract DE-AC52-07NA27344.**

---

# Data Science Challenge 2025

Full Dataset Release: [MOVi-MC-AC](https://huggingface.co/datasets/Amar-S/MOVi-MC-AC)

<video src=ex_vis.mp4 width="320" height="240" controls></video>

Welcome to the **2025 Lawrence Livermore National Laboratory Data Science Challenge!**

Launch Presentation consists of:
- (1) High-Level overview **(Short Slidedeck)** of current state-of-the-art methods for a variety of tasks
- (2) High-Level overview **(Dataset Card)** of MOVi-MC-AC
- (3) High-Level overview of **(OneDrive Folder)** of DSC Target Dataset: <u>**Robotics Laboratory Pick and Place Dataset**</u>
- (4) Low-Level example **(Jupyter Notebook)** of using state-of-the-art methods (SAM2) on DSC Target Dataset
- (5) Low-Level overview **(Jupyter Notebook)** of MOVi-MC-AC + DSC Tasks

**This notebook serves as the technical introduction to LLNL's MOVi-MC-AC Dataset (last bullet above), covering**:
- (1) Introduction to Image Processing / Computer Vision
- (2) Example Baseline Experiment
- (3) DSC Challenge & Tasking
  - **Task 1.1**: (Image-based) Modal Mask -> Amodal Mask
  - **Task 1.2**: (Image-based) Modal Content (RGB) -> Amodal Content (RGB)
  - **Task 2.1**: (Video-based) Modal Mask -> Amodal Mask
  - **Task 2.2**: (Video-based) Modal Content (RGB) -> Amodal Content (RGB)
  - **Transfer Test**: Apply Models on DSC Target Dataset:
    - Gather Modal Masks from some SotA method (SAM2)
    - Predict Amodal Masks, using Modal Masks
  - **Bonus Task 3**: Create Modal Masks with SAM2
  - **Bonus Task 4**: Re-ID of Objects
