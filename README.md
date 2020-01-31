Data Collection:
  ○ Collect nighttime light intensity data from the National Oceanic and
    Atmospheric Administration (NOAA)
  ○ Download economic data from the Demographic and Health Surveys
    (DHS Data)
  ○ Download day-time satellite of the region of interest from Google
    Static Maps
● Setup a Transfer Learning Model:
  ○ Prepare a VGG16 model for transfer learning
  ○ Use ImageNet dataset for training weights with VGG16 model to
    transfer knowledge to predict nightlight intensity.
● Poverty Estimation using Deep Learning and Transfer Learning:
  ○ Fine-tune the CNN model using satellite daytime images and
    nighttime light intensity data through transfer learning
  ○ Use the features that the model has learned from the nighttime light
    intensity classification task to map poverty in the region of interest.
