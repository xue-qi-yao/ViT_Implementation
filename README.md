## 1. Using
* Dataset 
   Flower classification dataset download link: [https://storage.googleapis.com/download.tensorflow.org/example_images/flower_photos.tgz](https://storage.googleapis.com/download.tensorflow.org/example_images/flower_photos.tgz) and set ***--data-path*** in args.

* Pre-trained parameters   \
   Pre-trained parameters download link: [vit_base_patch16_224](https://github.com/rwightman/pytorch-image-models/releases/download/v0.1-vitjx/jx_vit_base_patch16_224_in21k-e5005f0a.pth) 
   , and set ***--weights*** in args.
   
* Training \
   run the train.py file.

* Prediction \
   run the predict.py file.

## 2. Explaination

* ### Patch embedding
![patch_embedding](md_pictures/patch_embedding.png)

* ### Class and positional embedding
![class&positional_embedding](md_pictures/class&positional_embedding.png)

* ### ViT encoder 
![encoder_1](md_pictures/encoder_1.png)
![encoder_2](md_pictures/encoder_2.png)