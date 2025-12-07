# Star Tracker Attitude Determination Pipeline

This project implements a star tracker pipeline for satellite attitude determination, developed as part of aerospace systems coursework. The pipeline includes:

- **Star Detection:** Identifies bright stars in image frames  
- **Centroiding:** Computes precise star positions for accurate measurements  
- **Geometric Voting:** Matches detected stars with a reference star catalog  
- **SVD-based Attitude Estimation:** Computes spacecraft attitude using Singular Value Decomposition  

The project is implemented in Python using image processing, linear algebra, and visualization tools to validate accuracy and robustness on test datasets.

## Key Features
- Accurate star detection and centroiding  
- Geometric voting for star identification  
- SVD-based attitude determination  
- Visualization of estimated vs. reference attitude  
- Test datasets included for validation  

## Author
**Rayan Syed**  
UIUC Aerospace Engineering | FAA Part 107 Certified
