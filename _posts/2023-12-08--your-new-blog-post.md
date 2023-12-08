<!-- 

There is a substantial body of academic work estimating more subtle changes in socio-economic indicators – e.g. economic growth, quality of the built environment, and wider wellbeing indicators. 

There seem to be broadly three technical approaches, applied across different domains of public policy:

	• Studies extracting some set of features from images using a pretrained model, and then fitting a ML model on these pretrained features and some outcome of interest- this method seems most prominent at the moment – E.g. Suel (2021) pretains using vgg16 CNN.
	• Studies training a model on the “raw” satellite imagery – very high computational costs but has produced some stunning results, Khachiyan et. al. (2022) train a neural net on multispectral Landsat data to predict economic growth with good results. Khachiyan also used this to understand local impacts of fracking on mean income, at a very high spatial resolution. I can see how this type of approach could work on programmes/interventions relevant to DLUHC policy objectives – see his working paper here:  https://drive.google.com/file/d/1-7wQZdrQLZxfKXm44jH0qr4zhbY7x6GA/view
Work to establish generalisable frameworks for machine learning with satellite imagery – this potentially avoids a lot of the costly pre-processing and training of model weights. The recent seminal work here is from Rolf et.al. (2021)
-->

## List of papers discussing machine learning and satellite data in policy making

- Hall et al (2022) provide a literature review of how to measure human develompent indicators using satellite imagery, in particular asset-based measures of welfare and deprivation. They provide a number of examples where these approaches have been used to estimate welfare or poverty-related measures with precision and resolution close to large-scale household surveys. They conclude that explainability of large-scale machine learning models in this domain is a key barrier for further adoption by policy makers.  https://www.sciencedirect.com/science/article/pii/S2666389922002252


## List of papers discussing machine learning and streetview data in policy making

- Suel et al (2023) establish an unsupervised method to measure progress in urban development, using time series google streetview data for London from 2012 - 2020: https://arxiv.org/abs/2309.11354 





<!-- 



Charitidis, P., Moschos, S., Pipertzis, A., Theologou, I. J., Michailidis, M., Doropoulos, S., ... & Vologiannidis, S. (2022). StreetScouting: A Deep Learning Platform for Automatic Detection and Geotagging of Urban Features from Street-Level Images. Applied Sciences, 13(1), 266.
 
Khachiyan, Arman, Anthony Thomas, Huye Zhou, Gordon Hanson, Alex Cloninger, Tajana Rosing, and Amit K. Khandelwal. 2022. "Using Neural Networks to Predict Microspatial Economic Growth." American Economic Review: Insights, 4 (4): 491-506.
 
Rolf, E., J. Proctor, T. Carleton, I. Bolliger, V. Shankar, M. Ishihara, B. Recht, and S. Hsiang (2021). A generalizable and accessible approach to machine learning with global satellite imagery. Nature Communications.
 
Stevenson, M., Mues, C., & Bravo, C. (2022). Deep residential representations: Using unsupervised learning to unlock elevation data for geo-demographic prediction. ISPRS Journal of Photogrammetry and Remote Sensing, 187, 378-392.
 
Suel, E., Bhatt, S., Brauer, M., Flaxman, S., & Ezzati, M. (2021). Multimodal deep learning from satellite and street-level imagery for measuring income, overcrowding, and environmental deprivation in urban areas. Remote Sensing of Environment, 257, 112339.![image](https://github.com/janspiegel/janspiegel.github.io/assets/83724772/70f0ddc0-f5d6-49f8-99cf-1674fe02bdb6)



-->
