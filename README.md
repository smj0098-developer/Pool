In this project we used the images of houses for rent. each house contains at most 8 images. using modified resnet101 and the images we identify whether the house has a swimming pool or not.
The data has been scraped from Jajiga.com website.<br>
link for data : https://drive.google.com/file/d/1b8O_a6ywcsbLqJAGDGCkePrdn1cFlXl0/view?usp=sharing <br>
The data contains images of each house, as well as text data related to that house provided by the owner of the house.<br> we use the text data to generate labels: if the word "استخر" is found in the text related to a property, the label is 1, meaning the property has a swimming pool, and otherwise 0, meaning it does not.
