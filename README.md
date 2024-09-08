# Invoice Processing
An automatic Invoice processing system that performs OCR using tesseract and classifies the retrieved text using Bi-Directional LSTM which uses ELMO Embedding into categories like Company Name, Address, Date, and Total, this result is then stored in a structured format.

* [Results](https://github.com/shivanshu1641/Invoice-Processing/blob/main/Readme.md#results)
    * [Training Graphs](https://github.com/shivanshu1641/Invoice-Processing/blob/main/Readme.md#training-graphs)
    * [Classification Report](https://github.com/shivanshu1641/Invoice-Processing/blob/main/Readme.md#classification-report)
    * [Result Snippet](https://github.com/shivanshu1641/Invoice-Processing/blob/main/Readme.md#result-snippets)
* [Technology Used](https://github.com/shivanshu1641/Invoice-Processing/blob/main/Readme.md#language-used-)
* [Package](https://github.com/shivanshu1641/Invoice-Processing/blob/main/Readme.md#packageslibrary-used) 
* [Models Used](https://github.com/shivanshu1641/Invoice-Processing/blob/main/Readme.md#elmo-model-used)

## Results
### Training Graphs
#### Accuracy
![](https://github.com/shivanshu1641/Invoice-Processing/blob/main/Figures/Accuracy.png?raw=true)
#### Loss
![](https://github.com/shivanshu1641/Invoice-Processing/blob/main/Figures/Loss.png?raw=true)
### Classification Report
![](https://github.com/shivanshu1641/Invoice-Processing/blob/main/Figures/ClassificationReport.png?raw=true)
### Result Snippets
#### Input
![](https://github.com/shivanshu1641/Invoice-Processing/blob/main/Figures/ResultData.png?raw=true)
#### Ouput
![](https://github.com/shivanshu1641/Invoice-Processing/blob/main/Figures/ResultOutput.png?raw=true)


### Language Used : 
[Python](https://www.python.org/)
### Packages/Library Used  
[Tensorflow](https://www.tensorflow.org/), [Keras](https://keras.io/), [Tesseract](https://github.com/tesseract-ocr/tesseract)
### ELMO Model Used
[ELMO Model](https://tfhub.dev/google/elmo/2)
