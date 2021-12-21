# A Convolution Neural Network for Classification of Indian Coins by Denomination

![Python 3.7](https://img.shields.io/badge/Python-3.7-yellow)  ![Tensforflow 2.7.0](https://img.shields.io/badge/Tensorflow-2.7.0-blue)   ![License](https://img.shields.io/badge/License-CC%20BY%204.0-orange)

The code is this repository is part of a research paper titled "A Novel Convolution Neural Network for Classification of Indian Coins by Denomination". The article is under the review process as of December 2021 but a 'Preprint' of the article can be found here Preprint DOI : 
 
## About Data:

The data used in this study is collected by the authors and stored using the follow filling structure:

``` 
dataset/
     test_set/
            five/
            one/
            ten/
            twenty/
            two/
      test_set/
            five/
            one/
            ten/
            twenty/
            two/
 ```
The data contains images of One (1), Two (2), Five (5), Ten (10), and Twenty (20) Rupee coins in Indian denomination and their variations that are in circulation as of December 2021. The dataset only contains images of one side of each coin (Tail side) which contains the denomination value.\
In total the dataset contains 900 images out of which there are 210 images of one rupee class, 120 images of two rupee class, 270 images of five rupee class, 180 images of ten rupee class, and another 120 images of twenty rupee class.

For more information on the data refer to the documentation available on IEEE DataPort [Here](https://ieee-dataport.org/documents/indian-coin-denomination-dataset-icdd)

