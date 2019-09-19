[//]: # (Image References)
[complete]: ./images/FindThatPokemon.png

# Find That Pokemon using OpenCV's Template Matching

![Find That Pokemon][complete]

Template matching in OpenCV is a technique for finding areas of an image that are similar to a template image. To identify the matching area, the program compares the template image against the source image by sliding it (scanning pixel by pixel across the image left to right and top to bottom searching for a high score match).

### Prerequisites

You will need the following Python packages installed:

```
numpy
cv2
```

## Authors

* **Tyler Wolfe** - *Initial work* - [WolfeTyler](https://github.com/WolfeTyler)

## License

This project is licensed under the MIT License - see the [LICENSE.md](LICENSE.md) file for details

## Acknowledgments

* OpenCV Template Matching Documentation - https://docs.opencv.org/2.4/doc/tutorials/imgproc/histograms/template_matching/template_matching.html
* Using OpenCV, Python and TemplateMatching to play “Where’s Waldo?” - https://www.pyimagesearch.com/wp-content/uploads/2014/11/opencv_crash_course_waldo.pdf
