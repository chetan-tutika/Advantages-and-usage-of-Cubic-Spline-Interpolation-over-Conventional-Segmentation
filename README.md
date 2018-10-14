# Advantages-and-usage-of-Cubic-Spline-Interpolation-over-Conventional-Segmentation
While working with conventional segmentations, I have noticed that they are not adaptive and can sometimes result in loss of information. I wanted to create a segmentation procedure to overcome these difficulties<br />
##### The published results can be viewed at [//arxiv.org/abs/1803.04621](//arxiv.org/abs/1803.04621)
## Abstract
To design a novel method for segmenting image using Cubic Spline Interpolation and compare it with different techniques to determine which gives an efficient data to segment an image. This paper compares polynomial least square interpolation and the conventional Otsu thresholding with spline interpolation technique for image segmentation. The threshold value is determined using the above-mentioned techniques which is then used to segment an image into the binary image. The better technique is determined based on the results using multiple images
## Results
![screenshot 94](https://user-images.githubusercontent.com/41950483/46920143-dab41580-cfb7-11e8-9bbe-b5438d6d8bee.png)<br />
 More features of the image are seen as opposed to the polynomial curve fitting technique<br />
 <br />
![screenshot 95](https://user-images.githubusercontent.com/41950483/46920270-accfd080-cfb9-11e8-805b-7613997a10c3.png)<br />
it can be viewed that Cubic spline shows better results when compares to Otsu’s thresholding method. The prosposed method captures most of the segments while in Otsu and Polynomial Thresholding, few of the segments are lost<br />
<br />
![screenshot 97](https://user-images.githubusercontent.com/41950483/46920232-274c2080-cfb9-11e8-8206-bcaabe43003a.png)
Spline interpolation technique produces better clarity in the segmented image. More features of the image are seen as opposed to the polynomial curve fitting technique and Otsu. While distortions are prevalent in case of cubic spline interpolation, these can be removed using motion blur operators and other image processing techniques
## Inference
While the results of the proposed and conventional thresholding seem to be similar, we can notice loss of few pixels of data after segmenting with traditional methods. While the proposed method does add noise to the image, there is very little loss when compared to other techniques<br />
Cubic Spline Data interpolation showed better results than Otsu thresholding method and Polynomial curve fitting technique. While noise is added to the image during Cubic Spline Data interpolation, it can be eliminated using morphological operators and other techniques.

 
