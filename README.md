# feline_classifier

I created a deep learning model to classify felines into 3 categories: Tiger, Serval and Cheetah. I decided to fine-tune an existing model, rather than creating an entire model from scratch.

Issues:

Finding images for training wasn't that simple. I initially wanted to predict between tigers, leopards and cheetah. I use downloaded images from duckduckgo (programmatically). Searching for leopards frequently returned images of different types of vehicles used in the military forces. So the training set wasn't of very good quality. Searching for servals on the other hand brought many great and related images. Hence, I decided to differentiate between tigers, servals and cheetahs.

You can play around with the deployed app [HERE](https://huggingface.co/spaces/franckbinde/feline_classifier).

Note:
This is for educational purposes. I am familiarizing myself with the process. The aim was to have an end-to-end project done. But the job is far from being perfect. Plenty of steps need improvement. This will be addressed in future notebooks.
