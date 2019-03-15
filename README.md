# TV_Script
In this project, you'll generate your own Seinfeld TV scripts using RNNs. You'll be using part of the Seinfeld dataset of scripts from 9 seasons. The Neural Network will generate a new ,"fake" TV script, based on patterns it recognizes in this training data.

# Get the Data
The data is already provided for you in ./data/Seinfeld_Scripts.txt and you're encouraged to open that file and look at the text.

As a first step, we'll load in this data and look at some samples.
Then, you'll be tasked with defining and training an RNN to generate a new script!

<img src = '/seinfeld.jpg' width=300px>

## Prerequisites

* Python 3.
* Numpy 
* Pandas
* MatPlotLib
* OpenCv
* Pytorch. 

## Project Instruction

### Instructions
1. Clone the repository and navigate to the downloaded folder.
	```	
	git clone https://github.com/shyamStarwalt/TV_script.git
	```
2. Download and Install Anaconda [from here](https://www.anaconda.com/)

3. Install the above packages mentioned in the Prerequisites (Anaconda Prompt)

4. Open the cloned repository and navigate to
	```
	cd Tv_script
	```
5. Open the TV_script_generation.ipynb
	```
	jupyter notebook TV_script_generation.ipynb	
	```
6. Read and follow the instructions!  

## Project Information

### Contents

- Intro
- Step 0: Import Datasets
- Step 1: Implement Pre-processing Functions
- Step 2: Build the Neural Network
- Step 3: Create a RNN to Generate tv scripts (from Scratch)
- Step 4: Train the Neural Network
- Step 5: Generate a New Script

## Losses

### Model scratch:
loss: 3.5087 

## Output

jerry: hello

george: i think i have the same.

jerry: i mean, it's like you can get the money.

jerry:(to himself) what?

elaine: oh!

kramer:(to jerry) i think we have a big salad.

kramer: yeah.

jerry: i don't know.

jerry: well, you can't believe that.

george: i think you may have.

jerry:(to jerry) you know, i'm not gonna go. i'm going to the airport, i don't even know why i want.

jerry: what?

elaine: what is that?

jerry: you know. you can't believe it. it's like a sauna.

jerry: i know.

elaine: oh, no, you know, i was a good driver, and i have no idea.

george: oh, yeah. i don't want to know that i was a little bit...

jerry: what are you going to do?

george: i don't think so.

jerry:(sarcastic) yeah, i know, i just wanted to see you.

george: what?

jerry: i don't know, i know.

jerry: i know. it's not the kind of thing i could do.

jerry: you know, we could get some sleep for it.

jerry: i don't know how much it was to get to a movie, and then i get it, i was wondering that i was gonna have to have to be able to get to a plane and you have a lot of trouble, you know i think you could do this for me.

george:(to jerry) i don't understand.(he exits)

george: i mean, you have to be careful.

jerry: what?

elaine: well, you know, i just wanted to know that.(she leaves)

jerry: so?

jerry:(still pulling) oh, i don't think i can

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details

## Acknowledgments

* The data comes from Udacity.
