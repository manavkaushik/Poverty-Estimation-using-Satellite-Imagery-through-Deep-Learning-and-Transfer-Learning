The flow of the project goes down in the following way:<br/>

Data Collection: <br/>
  ○ Collect nighttime light intensity data from the National Oceanic and
    Atmospheric Administration (NOAA)<br/>
  ○ Download economic data from the Demographic and Health Surveys
    (DHS Data)<br/>
  ○ Download day-time satellite of the region of interest from Google
    Static Maps<br/><br/>
Setup a Transfer Learning Model:<br/>
  ○ Prepare a VGG16 model for transfer learning<br/>
  ○ Use ImageNet dataset for training weights with VGG16 model to
    transfer knowledge to predict nightlight intensity.<br/><br/>
Poverty Estimation using Deep Learning and Transfer Learning:<br/>
  ○ Fine-tune the CNN model using satellite daytime images and
    nighttime light intensity data through transfer learning<br/>
  ○ Use the features that the model has learned from the nighttime light
    intensity classification task to map poverty in the region of interest.<br/><br/>

For a detail explanation of the whole project please find the below attached link for the project report<br/>
[Project Report](https://drive.google.com/file/d/1UbffLKdWzYwtPKAT17F4lN2liDuvqOQ0/view?usp=sharing)
