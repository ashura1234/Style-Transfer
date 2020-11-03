
# Image Style Transfer

-   Reimplement the style transfer pipeline from a CVPR paper: [10.1109/CVPR.2016.265](https://www.cv-foundation.org/openaccess/content_cvpr_2016/papers/Gatys_Image_Style_Transfer_CVPR_2016_paper.pdf)
-   Manipulated images to adopt the appearance or visual style of another image.
-   Transfer learning VGG-19 model to extract content feature points and style feature points from the convolution layers.
## Environment
- python 3.7.9
- jupyter core     : 4.6.3
- jupyter-notebook : 6.0.3
- pytorch 1.6.0
- torchvision 0.7.0
- matplotlib 3.3.1
- numpy 1.19.1

## Installation

Clone the repository with the following command:

```bash
git clone https://github.com/ashura1234/Style-Transfer
```
## Data Preperation
Prepare images you like to change the style and extract the style from.
Example:

| Original Image | Style Image|
|---|---|
|<img  src="https://github.com/ashura1234/Style-Transfer/blob/main/Images/City.jpg?raw=true"  width=240>|<img  src="https://github.com/ashura1234/Style-Transfer/blob/main/Styles/StarryNight.jpg?raw=true"  width=240>|

## Execution
Assign paths of images at the 5tht cell and run all cells

## Result
Result by running 10000 steps with 0.003 learning rate:
| Original Image | Style Image|Result|
|---|---|---|
|<img  src="https://github.com/ashura1234/Style-Transfer/blob/main/Images/CatPortrait.jpg?raw=true"  width=240>|<img  src="https://github.com/ashura1234/Style-Transfer/blob/main/Styles/ThePersistenceOfMemory.jpg?raw=true"  width=240>|<img  src="https://github.com/ashura1234/Style-Transfer/blob/main/Results/0001.jpg?raw=true"  width=240>|
|<img  src="https://github.com/ashura1234/Style-Transfer/blob/main/Images/FireSkeleton.jpg?raw=true"  width=240>|<img  src="https://github.com/ashura1234/Style-Transfer/blob/main/Styles/Roses.jpg?raw=true"  width=240>|<img  src="https://github.com/ashura1234/Style-Transfer/blob/main/Results/0002.jpg?raw=true"  width=240>|
|<img  src="https://github.com/ashura1234/Style-Transfer/blob/main/Images/Eagle.jpg?raw=true"  width=240>|<img  src="https://github.com/ashura1234/Style-Transfer/blob/main/Styles/Oak.jpg?raw=true"  width=240>|<img  src="https://github.com/ashura1234/Style-Transfer/blob/main/Results/0003.jpg?raw=true"  width=240>|
|<img  src="https://github.com/ashura1234/Style-Transfer/blob/main/Images/Dog.jpg?raw=true"  width=240>|<img  src="https://github.com/ashura1234/Style-Transfer/blob/main/Styles/Desert.jpg?raw=true"  width=240>|<img  src="https://github.com/ashura1234/Style-Transfer/blob/main/Results/0004.jpg?raw=true"  width=240>|
|<img  src="https://github.com/ashura1234/Style-Transfer/blob/main/Images/City.jpg?raw=true"  width=240>|<img  src="https://github.com/ashura1234/Style-Transfer/blob/main/Styles/StarryNight.jpg?raw=true"  width=240>|<img  src="https://github.com/ashura1234/Style-Transfer/blob/main/Results/0005.jpg?raw=true"  width=240>|

### Output Video

![](https://github.com/ashura1234/Style-Transfer/blob/main/Results/0005.gif?raw=true)


## Credit
  
rslim087a
https://github.com/rslim087a
<!--stackedit_data:
eyJoaXN0b3J5IjpbMTg0MjQ2MTExOV19
-->