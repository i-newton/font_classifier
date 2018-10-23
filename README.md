# font_classifier
Classify fonts based on image
dataset generation - generates train/val/test datasets based on ubuntu fonts, every dataset image has fixed size(25*100)
font_classifier - train and save model, be aware that model state contains optimizer state and moel state,
so when loading model you need to unpack model state dict from file.
