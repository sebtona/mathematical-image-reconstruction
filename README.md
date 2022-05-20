# Mathematical Image Reconstruction
This MATLAB project completed in my Advanved Engineering Mathematics course demonstrates how eigenvectors and eigenvalues can be used for image re-synthesis and compression.

## Important Takeaways
- Any image can be represented as a set of eigenpairs (eigenvalues and corresponding eigenvectors).

<img src="https://github.com/sebtona/mathematical-image-reconstruction/blob/main/images/image002.png" alt="cameraman" width="350" /> <img src="https://github.com/sebtona/mathematical-image-reconstruction/blob/main/images/image003.png" alt="eigenvalues" width="400" />
- Some image eigenvalues have greater magnitudes than others.

<img src="https://github.com/sebtona/mathematical-image-reconstruction/blob/main/images/image004.png" alt="mag_eigenvalues" width="400" />
- When reconstructing an image, eigenvalues with greater magnitudes contribute more information to the image than eigenvalues with smaller magnitudes when paired with their corresponding eigenvectors.

<img src="https://github.com/sebtona/mathematical-image-reconstruction/blob/main/images/image005.png" alt="1_eigenvalue" width="400" /> <img src="https://github.com/sebtona/mathematical-image-reconstruction/blob/main/images/image007.png" alt="5_eigenvalues" width="400" />

<img src="https://github.com/sebtona/mathematical-image-reconstruction/blob/main/images/image008.png" alt="50_eigenvalues" width="400" /> <img src="https://github.com/sebtona/mathematical-image-reconstruction/blob/main/images/image009.png" alt="100_eigenvalues" width="400" />
- By finding the absolute error in pixel values between a reconstructed image and the original one, you can make an informed decision when dealing with a trade off between information storage and image quality. "Throwing away" the eigenpairs that contribute little to no important visual information can be used as a crude image compression algorithm.

<img src="https://github.com/sebtona/mathematical-image-reconstruction/blob/main/images/image012.png" alt="abs_error" width="400" />

<img src="https://github.com/sebtona/mathematical-image-reconstruction/blob/main/images/image010.png" alt="200_eigenvalues" width="425" /> <img src="https://github.com/sebtona/mathematical-image-reconstruction/blob/main/images/image011.png" alt="all_eigenvalues" width="400" />

## Run my Code
1. Download and install the latest version of MATLAB.
2. Fork this repo or download `mathematical_image_reconstruction.m`.
3. Open the `.m` file in MATLAB and click Run.
