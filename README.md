# TalkingImage 2 
This repository countains the source code to reproduce the preprint 
https://www.researchgate.net/profile/Ohini-Toffa/publication/355480327_Dataset_and_Semantic_Based-Approach_For_Image_Sonification/links/617366b53c987366c3cf5fb7/Dataset-and-Semantic-Based-Approach-For-Image-Sonification.pdf

TalkingImage 2 is an image sonification software constituted of multiple parts :
- Python code to identify objects in the image
- C++ part to segment the image in regions ( 
http://www.iro.umontreal.ca/~mignotte/ResearchMaterial/VOIBFM-SourceCode/ProgVOIBFM.tar.gz )
- C++ part to generate sounds from the abstract content ( https://github.com/ohinitoffa/ImgSonification )
- Java part which run on Android device and represente the client code. See apk 
- A server part in PHP which serves the images and sound
- A dataset of images and sound

  
