# character-recognition

## Task:

There are images of hieroglyphs written by hand (about 300 thousand in total), and it is necessary to teach the neural network to classify what kind of hieroglyph is written.

## Quality metric - accuracy.

## Description of data:

The dataset is divided into 5 parts - 4 training and one test. Each part is a .npy file that can be loaded using the np.load () function. Each array is a matrix of size [N, 2], each line contains a picture and its number in Unicode.

To download the dataset: kaggle competitions download -c chinese-char-recognition-smmo19
