# Creative-poem-generator
A set of poem generators that can create poems in various media formats.

Computational Creativity, Leiden University October 2023
By Lin He, Lily Kientz, Ruilin Ma

This folder acts as a backup and repo for the creative poem generator. For more detailed explanation and material, please refer to this repo: https://github.com/RylinnM/Creative-poem-generator

## SETTING UP:
To set up the Poem-generator you first have to upload the 'finalCC.ipynb' which is in the code directory to Google Colab.
Next, you have to put the 'kaggle_poem_dataset.csv' dataset in the Dataset and checkpoint directory to the following Google Drive folder: '/content/drive/MyDrive/'
Open 'finalCC.ipynb' in Google Colab and make sure you are connected with a GPU instead of a CPU. 
Run the topmost code block to install and import the correct packages, then run the class and definition code blocks. 


## GENERATING MODEL:
To generate the model, run the code blocks from top to bottom in the 'generate model' section.
This can take quite some time, so instead one can also upload the model we have already trained and fine-tuned 'checkpoint_whole.pth' to the following 
Google Drive folder: '/content/drive/MyDrive/'


## GENERATING POEM:
After having generated/uploaded a model, you can run the generate poems code blocks. 
The first code block is to load in the model. 
The second code block contains some text which the user can input. The generated poem will be influenced by this text.
The third code block will run the model which generates the poem.

It is recommended to follow the same format as we did if you want to try some new poem topics, for example, "The most adj. poem about noun. is written as follows:".

*Note 1: The generator can only generate poems in text form. Our production is further fed into LLM models and other AI tools to generate the painting form, the emoji form, and its voiceover. This part is not included in this generator, but can be easily done with available tools. For reference, the painting is created with DALLE3, the emojis are produced by ChatGPT with special prompts, and the Voiceover is produced with naturalreaders.com.*

*Note 2: The checkpoint file is too big to be uploaded to the repo. If needed, please contact the author(s).*

