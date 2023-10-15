#  Jupyter Notebooks: Facial Expression Recognition

![Image Plot of Class Examples](https://github.com/LeanderWernst/facial-expression-recognition/blob/2145e7f4310c3a7f27253b21995435cf266e484b/class-examples.jpg)

This project contains the Jupyter Notebooks that where used to learn the basics of Deep Neural Networks (DNNs) and become familiar with Facial Expression Recognition (FER) Tasks.  
The [AffectNet database](http://mohammadmahoor.com/affectnet/ "AffecNet")[^affectnet] was used as dataset for training and evaluation of the models.

## Setup

The needed Conda environment _"tf-vggface"_ with the dependencies to run these notebooks can be set up by using the ``environment.yml`` and running:

```conda env create -f environment.yml```

or 

```conda env create -f environment.yml --name ENV_NAME```

## Relevant Notebooks

The most relevant notebooks in regards to the final results of the project are the following:
- **230531_occlusion_pipeline_v3_final.ipynb**  
  _(calculating & applying patches to the faces for partial occlusion)_
- **230706_convnet_classification_from-scratch_v3.ipynb**  
  _(modelling a Convnet from scratch with Keras)_
- **230712_fer_vggFace_vgg16_finetunting_v2.ipynb**  
  _(finetuning a VGG16 model pretrained with VGGFace dataset)_
- **230717_fer_vggFace_senet50_finetuned_v1.ipynb**  
  _(finetuning a SeNet50 model pretrained with VGGFace dataset)_
- **230919_fer_vggFace_resnet50_finetuned_final.ipynb**  
  _(finetuning a ResNet50 model pretrained with VGGFace dataset; including evaluations on test set)_

[^affectnet]: Ali Mollahosseini, Behzad Hasani, and Mohammad H. Mahoor, “AffectNet: A New Database for Facial Expression, Valence, and Arousal Computation in the Wild”, IEEE Transactions on Affective Computing, 2017.
