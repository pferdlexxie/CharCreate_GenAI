# Character generation based on user input analysis
During these weeks our team explored the ways and strategies to implement text-to-audio and text-to-image models. We track all the progress in folder "Intermediate_solutions", while the final best-performing models will be stored in "Final_solutions" by the end of the project.

Text-to-audio. \
Abc folder. Model uses abc notation to generate sequences. Shows more meaningful music files for now, so we plan to proceed with fine-tuning it and turning from semi-random assignment to strict difference between mood labels. \
Rnn folder. Contains implementation of rnn and lstm model. After rounds of tuning and ideas we couldnt manage to generate sequences with good sounds, even though some notes and melodies are captured

Text-to-image.
Several files and actions are used to generate images. Initially, the code uses information retrieval technologies and collects all available posts on a topic from Pinterest. After that, the code is launched to process this dataset so that it fits the required format. The last file performs additional training of the diffusion model, creating a Lora adapter for generating images in the style of Harry Potter.
