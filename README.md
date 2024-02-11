# Image-Classification
  - Use Deep Learning models from scratch like (Xception, DenseNet, AlexNet, AlexNet with Transformer)
  - Apply Data Preparation steps :
    - Image Preprocessing :
         - Convert image from BGR to RGB
         - Resizing Images
         - Normalize Image by Dividing by Maximum

    - Data Augmentation For Train Like:
         - Horizontal flip
         - Vertical flip
         - Rotation range by 40
         - Width shift range  
         - Height shift range
         - Zoom range  
         - Fill mode by Nearest
           
  - Apply OneHotEncoder to convert Classes to labels
  - Split into train and validation 

  - ### Transfomer :
      - It uses a conventional CNN backbone to learn a 2D representation of an input image.
      - The model flattens it and supplements it with a positional encoding before passing it into a transformer encoder. 
      - After features + positional encoding , additionally attends to the encoder. 
      - After Encoder pass to linear layer then to classification layer ‘softmax’ .


  - submit results on Kaggle competition and rank the best accuracy achieved in the competition.

