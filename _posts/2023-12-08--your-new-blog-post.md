<!-- 

There is a substantial body of academic work estimating more subtle changes in socio-economic indicators – e.g. economic growth, quality of the built environment, and wider wellbeing indicators. 

There seem to be broadly three technical approaches, applied across different domains of public policy:

	• Studies extracting some set of features from images using a pretrained model, and then fitting a ML model on these pretrained features and some outcome of interest- this method seems most prominent at the moment – E.g. Suel (2021) pretains using vgg16 CNN.
	• Studies training a model on the “raw” satellite imagery – very high computational costs but has produced some stunning results, Khachiyan et. al. (2022) train a neural net on multispectral Landsat data to predict economic growth with good results. Khachiyan also used this to understand local impacts of fracking on mean income, at a very high spatial resolution. I can see how this type of approach could work on programmes/interventions relevant to DLUHC policy objectives – see his working paper here:  https://drive.google.com/file/d/1-7wQZdrQLZxfKXm44jH0qr4zhbY7x6GA/view
Work to establish generalisable frameworks for machine learning with satellite imagery – this potentially avoids a lot of the costly pre-processing and training of model weights. The recent seminal work here is from Rolf et.al. (2021)
-->

## List of papers discussing machine learning and satellite data in policy making

- Hall et al (2022) provide a literature review of how to measure human development indicators using satellite imagery, in particular asset-based measures of welfare and poverty. They provide a number of examples where these approaches have been used to estimate welfare or poverty-related measures with precision and resolution close to large-scale household surveys. They conclude that explainability of large-scale machine learning models in this domain is a key barrier for further adoption by policy makers.  https://www.sciencedirect.com/science/article/pii/S2666389922002252
- Zhu and Kondmann argue that predicting local poverty with daytime satellite imagery and machine learning has shown promising results. While this approach excels at predicting relative levels of local poverty, it is, however, unclear if it can also be used to monitor changes in poverty over time. In this paper, we test this property and find that the approach struggles to capture changes in local development - https://elib.dlr.de/137108/2/camera_ready.pdf


## List of papers discussing machine learning and streetview data in policy making

- Suel et al (2023) establish an unsupervised method to measure progress in urban development, using time series google streetview data for London from 2012 - 2020: https://arxiv.org/abs/2309.11354 





<!-- 

## Streetview

Charitidis, P., Moschos, S., Pipertzis, A., Theologou, I. J., Michailidis, M., Doropoulos, S., ... & Vologiannidis, S. (2022). StreetScouting: A Deep Learning Platform for Automatic Detection and Geotagging of Urban Features from Street-Level Images. Applied Sciences, 13(1), 266.

## Satellite images
 
Khachiyan, Arman, Anthony Thomas, Huye Zhou, Gordon Hanson, Alex Cloninger, Tajana Rosing, and Amit K. Khandelwal. 2022. "Using Neural Networks to Predict Microspatial Economic Growth." American Economic Review: Insights, 4 (4): 491-506.
 
Rolf, E., J. Proctor, T. Carleton, I. Bolliger, V. Shankar, M. Ishihara, B. Recht, and S. Hsiang (2021). A generalizable and accessible approach to machine learning with global satellite imagery. Nature Communications.
 
Stevenson, M., Mues, C., & Bravo, C. (2022). Deep residential representations: Using unsupervised learning to unlock elevation data for geo-demographic prediction. ISPRS Journal of Photogrammetry and Remote Sensing, 187, 378-392.
 
Suel, E., Bhatt, S., Brauer, M., Flaxman, S., & Ezzati, M. (2021). Multimodal deep learning from satellite and street-level imagery for measuring income, overcrowding, and environmental deprivation in urban areas. Remote Sensing of Environment, 257, 112339.

Hamid Sarmadi∗, Thorsteinn R¨ognvaldsson∗,Nils Roger Carlsson∗, Mattias Ohlsson∗‡, Ibrahim Wahab†, Ola Hall† (2023). Towards Explaining Satellite Based Poverty
Predictions with Convolutional Neural Networks. https://arxiv.org/pdf/2312.00416.pdf

Xie, M., Jean, N., Burke, M., Lobell, D. and Ermon, S., 2016, March. Transfer learning from deep features for remote sensing and poverty mapping. In Proceedings of the AAAI conference on artificial intelligence (Vol. 30, No. 1). https://ojs.aaai.org/index.php/AAAI/article/view/9906/9765

Y. Tan, P. Wu, G. Zhou, Y. Li and B. Bai, "Combining Residual Neural Networks and Feature Pyramid Networks to Estimate Poverty Using Multisource Remote Sensing Data," in IEEE Journal of Selected Topics in Applied Earth Observations and Remote Sensing, vol. 13, pp. 553-565, 2020, doi: 10.1109/JSTARS.2020.2968468. https://ieeexplore.ieee.org/document/8970370

Liu, Haoyu, Xianwen He, Yanbing Bai, Xing Liu, Yilin Wu, Yanyun Zhao, and Hanfang Yang. 2021. "Nightlight as a Proxy of Economic Indicators: Fine-Grained GDP Inference around Chinese Mainland via Attention-Augmented CNN from Daytime Satellite Imagery" Remote Sensing 13, no. 11: 2067. https://doi.org/10.3390/rs13112067 

Chi G, Fang H, Chatterjee S, Blumenstock JE. Microestimates of wealth for all low- and middle-income countries. Proc Natl Acad Sci U S A. 2022 Jan 18;119(3):e2113658119. doi: 10.1073/pnas.2113658119. PMID: 35017299; PMCID: PMC8784134. https://www.ncbi.nlm.nih.gov/pmc/articles/PMC8784134/


## Literature reviews

Ola Hall, Mattias Ohlsson, Thorsteinn Rögnvaldsson (2022), A review of explainable AI in the satellite data, deep machine learning, and human poverty domain,
Patterns. https://www.sciencedirect.com/science/article/pii/S2666389922002252



-->
