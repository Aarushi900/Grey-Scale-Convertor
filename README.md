# Grey-Scale-Convertor
Converts large number of images into grey scale

This Python code downloads images of flowers from a specified folder, converts them to grayscale, and saves the converted images in an output folder.

## Instructions

1. Install the required library:

2. Download the code and specify the input folder path.

3. Run the script to download the flower images from the input folder.

4. The code converts each image to grayscale and saves the converted images in the output folder.

## Code Explanation

The code utilizes the `simple_image_download` library to download images. It sets a limit of 100 images to be downloaded from the 'flowers garden' category.

After downloading the images, the code converts each image to grayscale using OpenCV (`cv2`). If the conversion is successful, the grayscale image is saved in the output folder.

## Limitations

- The code assumes that the input folder contains valid image files. It may encounter errors if non-image files are present.
- The code overwrites existing files with the same name in the output folder.

## Usage

1. Specify the input folder path in the code.
2. Run the script to download and convert the flower images.

## Acknowledgments

This code utilizes the `simple_image_download` library, which simplifies the image download process.

## References

- [simple_image_download library](https://pypi.org/project/simple-image-download/)


