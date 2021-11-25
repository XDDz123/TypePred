# Trigram/Bigram Typing Prediction Program
## Program requirements
- Python 3.5+
- tkinter
- numpy
- json
- re
## Instructions
#### Start the GUI for the Trigram + Bigram model 
    python typepred.py
><em>Warning: computationally and memory intensive</em></br>

The program loads pre-built models from <em>trigram_model.json</em> and <em>bigram_model.json</em> and starts the GUI application automatically.
#### Start the GUI for the Bigram model
    python typepredBI.py
The program loads the pre-built model from <em>bigram_model.json</em> and starts the GUI application automatically.
#### Train the Trigram + Bigram model
    python train.py
> <em>Warning: computationally and memory intensive</em></br>

The program reads training data from the file <em>input.txt</em> and creates <em>trigram_model.json</em> and <em>bigram_model.json</em>.
#### Train the Bigram model
    python trainBI.py
The program reads training data from the file <em>input.txt</em> and creates <em>bigram_model.json</em>.
#### Training data
Training data is stored in the <em>input.txt</em> file. No specific requirements, preferably well formed natural sentences. 

## GUI sample
![gui](https://user-images.githubusercontent.com/20507222/143170097-40b8f299-9d7d-45fb-89d4-acd1cb3648a5.gif)

## Sample training data
[Click here to download sample training data](https://d396qusza40orc.cloudfront.net/dsscapstone/dataset/Coursera-SwiftKey.zip)
#### To generate the relevant models:
1. Unzip the zip file
2. Copy the contents of <em>final/en_US/en_US.news.txt</em>
3. Paste the contents into <em>input.txt</em>
4. Run <em>train.py</em> or <em>trainBI.py</em>
