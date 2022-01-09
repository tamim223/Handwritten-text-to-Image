# Handwritten-text-to-Image

## Project Synopsis
One of the most difficult tasks in NLP is handwriting. It's because it can differ from person to person. However, certain characters (for example, English) are very similar. We use contextualized information and lexical matching as a human starting point.
While humans have the ability to determine whether it is "O" or "0" from contextualised information, "O" can sometimes be written as "0." For instance, "0" will be used in phone numbers, whereas "O" will be part of an English word. Searching the lexicon is another talent. Even if we don't recognise every single character, it helps us guess words.
Here I seek to classify individual words so the word can be converted into a digital form. Firstly, I took a dataset from Kaggle containing around 50000 handwritten words. Then I process and prepare the data for training and in the process, I remove the unreadable images. After processing the data and labels, I made a CRNN model which will use CNN and RNN sequentially. The model was then trained and checked for performance on the validation set. Finally, I took some custom inputs to check and the text was recognized with ease.

![Diagram](https://media.discordapp.net/attachments/764117206350823464/929590539505008650/HTR_Diagram.png?width=860&height=598)

## Dataset

This dataset consists of more than four hundred thousand handwritten names collected through charity projects.

Character Recognition utilizes image processing technologies to convert characters on scanned documents into digital forms. It typically performs well in machine-printed fonts. However, it still poses difficult challenges for machines to recognize handwritten characters, because of the huge variation in individual writing styles.

There are 206,799 first names and 207,024 surnames in total. The data was divided into a training set (331,059), testing set (41,382), and validation set (41,382) respectively.

Link: https://www.kaggle.com/landlord/handwriting-recognition 
