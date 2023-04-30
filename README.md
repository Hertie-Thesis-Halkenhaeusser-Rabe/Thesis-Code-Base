<p align="center">
<b><a href="##summary">Summary</a></b>
|
<b><a href="##methodology">Methodology</a></b>
|
<b><a href="#experiments">Experiments</a></b>
|
<b><a href="#results-&-policy-implications">Results & Policy Implications</a></b>
</p>




# Hertie School Master of Data Science for Public Policy - Thesis 

## Summary

Accurate data about the structure of the electricity grid is crucial for all stakeholders working on the Seventh Sustainable Development Goal which aims for clean and affordable energy for everyone, especially in developing countries. Conventional ways of collecting this data, mostly relying on manual work by humans, are cost-intensive, slow, and hard-to-scale. Meanwhile, recent advancements in deep learning models have enabled automated localisation and classification of objects in imagery, referred to as object detection. These models, such as \emph{Faster-RCNN}, have proven their capability to detect even small objects like solar panels or electricity towers in satellite imagery \citep{huang_gridtracer_2021}. However, it remains unclear to what extent the spatial resolution of these images affects the performance of such an object detection model, since earlier studies have always relied on satellite imagery with the highest, yet costly, available resolution of 30 cm/pixel. Therefore, in this work, we explore three questions: (1) How does a decrease in image resolution affect the ability of an object detection model to find distribution and transmission towers in satellite imagery, (2) what is the effect of changing the composition of geographies within the training set, and (3) how do differences in electricity tower sizes impact the detection performance? In our experiments we observe that the networks' precision deteriorates as we gradually decrease the resolution. 
When focusing on subsets of geographies we find, besides a high in-sample precision, that the inclusion of a variety of biotopes can lead to marginal improvements in the otherwise poor out-of-sample performance. Finally, the results suggest that the detection performance of the model, when specifically trained to detect larger towers, is more resilient to a decrease in resolution, even when size variance is high.

## Methodology

### Data

- überischts bild rein
- link zu daten

### Downsampling

- bild vom downsampling
- link zum script


## Experiments

### Experiment 1

\insert timeline image and basic results

### Experiment 2

...

### Experiment 3

## Results & Policy Implications

## Disclaimer
