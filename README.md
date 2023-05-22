# PLUSH-SFM

**P**ractically **L**aughable, **U**n**S**uccessful, **H**aphazardous **S**tructure **F**rom **M**otion

### Check pipeline details in the projects page

### Rough steps of SFM pipeline:

1. feature point detection
2. feature matching
3. pose estimation
4. 3D coordinate triangulation
5. bundle adjustment (or other optimization techniques?)

### Milestones

- [ ] Implement steps of SFM pipeline in C++
- [ ] Verification/comparison with OpenCV implementations
- [ ] Parallelize each step of SFM pipeline (using either MPI or CUDA)
