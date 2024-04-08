Computational Creativity, Leiden University October 2023
By Lin He, Lily Kientz, Ruilin Ma


SETTING UP:
To set up the Poem-generator you first have to upload the 'finalCC.ipynb' to google colab.
Next you have to put the 'kaggle_poem_dataset.csv' dataset in the following google drive folder: '/content/drive/MyDrive/'
Open 'finalCC.ipynb' in Google Colab and make sure you are connected with a GPU instead of a CPU.
Run the topmost codeblock to install and import the correct packages, then run the class and definition code-blocks. 


GENERATING MODEL:
To generate the model, run the codeblocks from top to bottom in the 'generate model' section.
This can take quite some time, so instead one can also upload the model we have already trained and fine-tuned 'checkpoint_whole.pth' to the following 
google drive folder: '/content/drive/MyDrive/'


GENERATING POEM:
after having generated/uploaded a model, you can run the generate poems codeblocks. 
The first codeblock is to load in the model. 
The second codeblock contains some text which the user can input. The generated poem will be influenced by this text.
The third codeblock will run the model which generates the poem.

It is recommended to follow the same format as we did if you want to try some new poem topics, for example, "The most adj. poem about noun. is written as follows:".

Note: The generator can only generate poems in text form. Our production is further feed into LLM models and other AI tools to generate the painting form, the emoji form, and its voiceover. This part is not included in this generator, but can be easily done with available tools. For reference, the painting is created with DALLE3, the emojis are produced by ChatGPT with special prompts, and the Voiceover is produced with naturalreaders.com.
