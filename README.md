# Crack Detection with Pytorch 

In this project it was used 40_000 images of walls with cracks and without them to train neural networks to detect if an image has either a crack or not. Considering the magnitude of the project first it was used a NN made by the author [Juan Ortuño][https://github.com/Juan0rt72]
but later on it was used a pre-trained ResNet18 network with some modifications  to the final fully connected layer for the final classification.

<br>

The images used for this project are from the course [IBM AI Engineering][https://www.coursera.org/professional-certificates/ai-engineer?&utm_medium=sem&utm_source=gg&utm_campaign=B2C_LATAM_ai-engineer_ibm_FTCOF_professional-certificates_countrygroup-1&campaignid=21401010914&adgroupid=161645073817&device=c&keyword=ibm%20ai%20engineering%20professional%20certificate&matchtype=p&network=g&devicemodel=&adposition=&creativeid=703407787860&hide_mobile_promo&gad_source=1&gclid=Cj0KCQjw1qO0BhDwARIsANfnkv9K5ii1jVLNGV4egbvrGfytD7KbHQnKqJSF3oHUX6WPLytkWKcfnm4aAsQsEALw_wcB]
This project will be published without these images but feel free of using the trained model inside the `Labs/` folder.
