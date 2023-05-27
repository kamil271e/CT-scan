# Computed Tomography Scan

University project which simulates CT scan.

## Capabilities

User can choose an image and parameters used during radon transform.

<img src="https://user-images.githubusercontent.com/71709842/235885570-aec5327a-a98c-4e54-b6a4-77bbcb80ec01.png">

The program will perform radon transform and extract sinogram of the original image.

<img src="https://user-images.githubusercontent.com/71709842/235886169-35561427-ca2a-4721-96e3-ee042f2b7fbe.png">

The sinogram will be filtered and inverse radon transform will be performed on both, unfiltered and filtered version.

The final output contains (from the left) - original, unfiltered output, filtered output:

![shepp](https://github.com/kamil271e/CT-scan/assets/82380348/94597f9c-e5ba-4b19-823d-60d47a77590a)

![image](https://github.com/kamil271e/CT-scan/assets/82380348/86a87814-cc8c-4a5f-a165-7799372271dc)

In the end user can save the file in the DICOM format.

