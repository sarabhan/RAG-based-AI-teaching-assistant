#How to use this RAG AI teaching assistant on your own data

##Step 1: convert video to audios using "video to audio process" python file 

##Step 2: convert audios to text using "audio_to_text_process" python file

##Step 3: for final step use "read_text_from_chunks_and_answer" file to store the chunks to database and then use this same file to create a dataframe from the stored data in database and save it as joblib pickle then the use case 3 to use llm to answer the question.

#points to remember:
1.remember to download ollama and the model. The model that i am using is llama3.2, you can change the model according to you, in the third step file
2.remember to download the mongodb database and create a connection as same as i am using in this third step file

And at last just run the model.

#to Increase the accuracy of the project:
1.use a model like gpt-5
2.use chunks are full of more context what i mean is that i have used chunks that are mostly snippet's, so you should use more bigger chunks or you can just increase the lines that are being taken into a single chunk
