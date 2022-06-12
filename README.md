

# SA-C-GENDER-CLASSIFIER
# Algorithm
1. First install deepface library
2. to install deepface library use the command pip install deepface
3. And also import cv2 and matplotib.pyplot
4. Then read the image,an then show the image

## Program:
```
/*
Program to implement 
Developed by   : GANAPATHI VENKATESH
RegisterNumber :  212220230018
*/
```

```python
!pip install deepface
from deepface import DeepFace
import cv2
import matplotlib.pyplot as plt
img1=cv2.imread('NTR.jpg')
plt.imshow(img1[:,:,::-1])
plt.show()
result=DeepFace.analyze(img1,actions=['gender'])
print("Gender : ",result['gender'])
```

## OUTPUT:

![venky](https://user-images.githubusercontent.com/75234983/173243333-2377b245-6169-458d-a200-f11dbdf39264.png)

YOUTUBE LINK :
https://youtu.be/N3bkjBimi7E

