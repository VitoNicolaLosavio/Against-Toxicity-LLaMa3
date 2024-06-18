# Natural Languange Process
This project is for a natural language process university project in which you will analyze the sentences within toxic relationships,
creating two models of multiclass classification and performing two fine tuning steps

The first with the dataset containing the data made by hand with the help of a psychologist and generative models (GPT 4 and GPT 3.5)
monitored by human supervision. 

For the second step of fine tuning, instead, we used a dataset made with an LLM (LLaMa 3 quantizzated) with a prompt designed for 
the generation of sentences similar to those of the original dataset.

The model on which fine tuning was made is llama 3 and for the evaluation we saw how the model 
generated the explanation before and after fine tuning.

For this project you will add the key of HuggingFace inside a .env file like the file .env.example
