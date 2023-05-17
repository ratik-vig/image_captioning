# Descriptive Image Captioning using Deep Learning
A project on image captioning using Encoder(CNN) and Decoder (LSTM and GRU). Trained using the Flickr30k dataset.
We used a pretrained ResNet50 model to extract features from images and train a GRU to generate relevant captions.

To run the project, you will need a copy of the Flickr30k dataset and annotated captions file (with .token extension).
If you are uploading the dataset on google drive, you can run the following code on google colab notebook to connect it to your GDrive.

```
from google.colab import drive
drive.mount('/content/drive', force_remount=True)
```

If you uploaded a zip file of the dataset on Google Drive, you can use to following code to extract the dataset

```
%%shell
tar -xvzf /content/drive/MyDrive/flickr30k-images.tar.gz
```

After you have the dataset, change the path in the code with your own dataset and annotations path.
