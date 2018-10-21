# DeepFruit ;)

## Project description
The aim of this project is to write AI software that can recognize fruits (and later vegetables) in plastic bags from close (<1m) distance.

## 2018 October 14.:
Currently this repo contains a dataset of images containing fruits. The following fruits are included: Apples (different varieties: Golden, Golden-Red, Granny Smith, Red, Red Delicious), Apricot, Avocado, Avocado ripe, Banana (Yellow, Red), Cactus fruit, Cantaloupe (2 varieties), Carambula, Cherry (different varieties, Rainier), Cherry Wax (Yellow, Red, Black), Clementine, Cocos, Dates, Granadilla, Grape (Pink, White, White2), Grapefruit (Pink, White), Guava, Huckleberry, Kiwi, Kaki, Kumsquats, Lemon (normal, Meyer), Lime, Lychee, Mandarine, Mango, Maracuja, Melon Piel de Sapo, Mulberry, Nectarine, Orange, Papaya, Passion fruit, Peach, Pepino, Pear (different varieties, Abate, Monster, Williams), Physalis (normal, with Husk), Pineapple (normal, Mini), Pitahaya Red, Plum, Pomegranate, Quince, Rambutan, Raspberry, Salak, Strawberry (normal, Wedge), Tamarillo, Tangelo, Tomato (different varieties, Maroon, Cherry Red), Walnut.

Total number of images: 55244.

Training set size: 41322 images (one fruit per image).

Test set size: 13877 images (one fruit per image).

Multi-fruits set size: 45 images (more than one fruit (or fruit class) per image)

Number of classes: 81 (fruits).

Image size: 100x100 pixels.

Filename format: image_index_100.jpg (e.g. 32_100.jpg) or r_image_index_100.jpg (e.g. r_32_100.jpg) or r2_image_index_100.jpg. "r" stands for rotated fruit. "r2" means that the fruit was rotated around the 3rd axis. "100" comes from image size (100x100 pixels).

Different varieties of the same fruit (apple for instance) are stored as belonging to different classes.

### Repository structure
Folders Training and Test contain images for training and validation/testing purposes.

Folder test-multiple_fruits contains images with multiple fruits. Some of them are partially covered by other fruits. This is an excelent test for real-world detection. In the future after the first version of the nerual network we will extend this folder with pictures containing furits in plastic bags.

### Dataset origin
This dataset is originated from https://github.com/Horea94/Fruit-Images-Dataset project, which is under MIT License.
