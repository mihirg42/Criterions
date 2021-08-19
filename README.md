# Criterions

**Comparing different loss functions via linear and 2nd degree polynomial regression.**

```Data Generation.ipynb``` is the notebook used to generated the data used for the task. We apply Gaussian noise on a half degree polynomial to generated the required dataset.<br>
```data.csv``` is the dataset used for the task.<br>
```Criterion.ipynb``` is the main notebook for the task.

### Results

![alt text](https://i.ibb.co/ftQwfGn/pclub.jpg)

In Linear Regression, we see that the loss functions 
![equation](http://www.sciweavers.org/upload/Tex2Img_1629390763/render.png)
 and 
 ![equation](http://www.sciweavers.org/upload/Tex2Img_1629390848/render.png)
 performs equally well.

Whereas, in polynomial regression ![equation](http://www.sciweavers.org/upload/Tex2Img_1629391012/render.png)
 and ![equation](http://www.sciweavers.org/upload/Tex2Img_1629391129/render.png)
 do not give acceptable results even after 100,000 iterations. But ![equation](http://www.sciweavers.org/upload/Tex2Img_1629391012/render.png) performs much better than ![equation](http://www.sciweavers.org/upload/Tex2Img_1629391129/render.png)
. These models penalise the high values of variation more than that is required and the model is not trained properly.

**Therefore the order of usability of the loss functions is:**

![equation](http://www.sciweavers.org/upload/Tex2Img_1629392315/eqn.png)


