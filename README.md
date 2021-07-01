# Quality assessment of coffee beans through computer vision and machine learning algorithms

This repository contains codes in both python and R to process digital images of coffee beans and extract geometric features that allow quality assessment, such as area, perimeter, and color features; and to classify coffee beans based on the extracted features through different machine learning algorithms, such as Deep Neural Network, Random Forest, and Support Vector Machine. If you're interested in getting to know more about this project, please search:

1. Open source iterative bayesian classifier algorithm for quality assessment of processed coffee beans. 
Link: https://periodicoscientificos.ufmt.br/ojs/index.php/nativa/article/view/8074

2. Quality assessment of coffee beans through computer vision and machine learning algorithms. 
Link: http://www.coffeescience.ufla.br/index.php/Coffeescience/article/view/1752

## Background

The increasing market interest in coffee beverage, lead coffee growers around the world to adopt more efficient methods to select the best-quality coffee
beans. Currently, coffee beans selection is carried out either manually, which is a costly and unreliable process, or using electronic sorting machines, which
are often inefficient because some coffee beans defects, such as sour and immature beans, have similar spectral response patterns. In this sense, the
present work aimed to analyze the importance of shape and color features for different machine learning techniques, such as Support Vector Machine
(SVM), Deep Neural Network (DNN) and Random Forest (RF), to assess coffee beans’ defects.

## Project scope

![image](https://user-images.githubusercontent.com/72997145/124165085-d259dc80-da77-11eb-950e-d581650d72d3.png)

First, to obtain the shape and color features of the beans, the images were segmented from the background and then the beans were labeled.

![image](https://user-images.githubusercontent.com/72997145/124165007-beae7600-da77-11eb-88bc-4634c6fe964e.png)

The obtained proportional importance of the features for each classifier were:

![image](https://user-images.githubusercontent.com/72997145/124165998-ce7a8a00-da78-11eb-934a-a5e041f1a11a.png)

The classifiers' performance for this project were:

![image](https://user-images.githubusercontent.com/72997145/124166175-e94cfe80-da78-11eb-8ad6-13b97f5514da.png)

## Conclusion

The data reported in this study provides evidence that computer vision along with machine learning algorithms can be used to identify and classify coffee beans with a very
high accuracy (> 88%). In addition, all the classifier models presented similar performance. The features area, Gmean and Vmean are the most important variables for classifying coffee beans according to its defects. Since color descriptors presented the most relevant contribution in the classification process, different variables, such as components from different color spaces should be considered to improve classification accuracy.
