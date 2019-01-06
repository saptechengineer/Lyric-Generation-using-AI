# Can AI Generate Lyrics?

****IDEA****

The idea is to build a model which is trained on a series of song lyrics and then use it to generate further lyrics with some input. 
For example, the model will take a small string from the user (Like: Happy Birthday to you) and then it will try to generate the lyrics from this line!
For this purpose, I'm using a Keras based RNN, i.e., Recurrent Neural Network with Long Short Term Memory(LSTM) for genrating lyrics which will differ in each case and will also memorize or learns from the past predictions.

****GCP****

- http://cloud.google.com
- compute --> compute engine --> new

****SUDO****

 - sudo apt-get update
 - sudo apt-get upgrade
 - sudo apt-get install git
 - sudo apt-get install python3-pip
 
 ****pip install****
 - pip3 install keras
 - pip3 install tensorflow

****git clone****
 - git clone https://github.com/saptechengineer/Lyric-Generation-using-AI/
 
 ****Edit and Save python file (main.py)****
  - vi main.py (to open the file)
  - press 'a' (to edit the file)
    ## uncomment the below lines
    - ## model.fit(X, y, batch_size=128, nb_epoch=EPOCHS)
    - ## model.save('any_name.h5')
    ## comment the below line
    - ## model = load_model("model.h5")
  - press escape 
  - press ':'
  - press 'x'
  - ENTER

****Coding the Network****

We are using Keras with Tensorflow as backened. Keras lets us to create and solve our problems in an object oriented way.
So, there are basically two dependencies for this repo, which can be installed in CMD by typing:

    pip install keras
    pip install tensorflow

We are done to proceed further!
Now just run the following in CMD:
    
    python main.py
    
This will just print the lyrics with some default sentence in it.
If you want to give it your own sentence, then open the ****main.py**** program and in the last:
    
    Give your sentence in:
    sentence = "Your first line of lyric here"
    
 That's it.
 
 Please do ****STAR**** this Repo if you think it helped you.
 
 ## credit:
 https://medium.com/@ivanliljeqvist/using-ai-to-generate-lyrics-5aba7950903
