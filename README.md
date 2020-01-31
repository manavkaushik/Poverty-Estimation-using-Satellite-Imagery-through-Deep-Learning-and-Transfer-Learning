# Poverty-Estimation-using-Satellite-Imagery-through-Deep-Learning-and-Transfer-Learning

Accurate measurements of the economic characteristics of any country’s
population critically influence both research and policy development. These
measurements not only help to shape decisions by individual governments about
how to allocate scarce resources but at the same time provide the foundation for
global efforts to understand and track the progress towards improving livelihoods
of the citizens of that country. Although the quantity and quality of economic,
financial and household data available in developing countries have improved in
the past few years, data on some major measures of economic development such as
poverty, living standards, etc are still lacking for several developing countries of
the world. This data gap is badly affecting the efforts to identify and understand
variation in these essential indicators and to target policy changes and interventions
effectively to the regions where it is needed the most.
I draw inspiration from the work of Neal Jean et. al (2016) and aim to help
predict poverty of a given region by combining day-time satellite Imagery and
Convolutional Neural Network with night-time light intensity data. While talking
about using day-time satellite images, I am basically using features hidden in these
high-resolution day time images which will eventually help us to map the poverty
in our region of Interest.
A simple question which might arise here is why to deal with day-time
images while predicting poverty if we are trying to majorly use nighttime light
intensity data? A more direct approach that I can think of is directly predicting
Poverty using Night-time imagery from the satellite. Nighttime images can directly
tell us about some of the key aspects that we may be looking for like how well lit
our area of interest is and thus, accordingly we can divide the area into low,
medium or high poverty ranges to effectively map poverty. But the major issue
here, as also discussed by the author Neal Jean well in his paper, is that the
nighttime satellite imagery can be very deceptive as a highly lit area may be
covered by dense clouds or an area with low light intensity may appear bright
because of its surrounding areas. Also, a sparsely populated area cannot be directly
considered as a low poverty area. Thus, it is not difficult to agree on the fact that
nighttime images are not the best parameter to map poverty in a given region.
Talking about day-time images, earlier scientists had to manually select the
relevant features from their dataset in order to train their models and this process
was known as feature engineering or simply feature selection. However, this can be
a very complex task as it is very difficult to extract features that will be important
and benefit the model especially when we talk about image data. This is where the
role of Convolutional Neural Networks comes into play. One of the greatest
advantages of convolutional neural networks is that they can learn appropriate
features by themselves without any explicit training. We can simply provide them
with raw images as inputs, and CNN can learn how to fetch the appropriate
features for our model training.
At last, let’s focus on Neal Jean’s paper where he explains the developed
model. In this paper, they begin with a Convolutional Neural Network which is
pre-trained on the ImageNet dataset and then fine-tune it using satellite daytime
images and nighttime light intensity data using transfer learning. A final softmax
classifier layer is used to estimate the nighttime light intensity of the particular
region of interest. The paper then tries to extend its goal so that the CNN features
learned from the nightlights classification task can be used to predict indicators of
interest to the international scientific community, such as poverty, or wealth.
