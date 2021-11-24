# TypePred
## Trigram/Bigram Typing Prediction Program
### Program requirements
- Python 3.5+
- tkinter
- numpy
- json
- re
### Instructions
#### Start the GUI for the Trigram + Bigram model 
    python typepred.py
The program loads pre-built models from <em>trigram_model.json</em> and <em>bigram_model.json</em> and starts the GUI application automatically.
#### Start the GUI for the Bigram model
    python typepredBI.py
The program loads the pre-built model from <em>bigram_model.json</em> and starts the GUI application automatically.
#### Train the Trigram + Bigram model
    python train.py
The program reads training data from the file <em>input.txt</em> and creates <em>trigram_model.json</em> and <em>bigram_model.json</em>.
#### Train the Bigram model
    python trainBI.py
The program reads training data from the file <em>input.txt</em> and creates <em>bigram_model.json</em>.
#### Training data
Training data is stored in the <em>input.txt</em> file. No specific requirements, preferably well formed natural sentences. 

### GUI Sample
![image](https://user-images.githubusercontent.com/20507222/143152600-662e68fd-4e91-41eb-abf3-715fe287fecc.png)

