I was curious if one could predict the pronunciation of Chinese characters based solely on the character per se.\n
This project served to test this hypothesis and explore neural networks.\n
The CNN model takes 10K+ Chinese sorted by stroke count, split 80/20 for training and validation.\n
\n
Notes:
-Image augmentation worked during my testing but seemed to break when fed into the model.\n
-Other fonts may be used for analysis but ensure that the font covers all the characters used.\n
-Data derived from: https://www.reddit.com/r/datasets/comments/d9mxiy/i_have_compiled_a_dataset_of_11062_chinese\n
