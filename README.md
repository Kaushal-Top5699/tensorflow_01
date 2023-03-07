# tensorflow_01
Shuffling Tensor (Useful for shuffling data).
Simple example is, say, we have 15,000 images of cats and dogs in our dataset. Now if the images are in order for example, first 10,000 images area of cats so our network will start will generating patterns and train itself thinking that I just have to learn how a cat looks like but when it suddenly encounters dog images it might not train itself well. Therefore, if we shuffle data so that all the images of cats and dogs mix up we can train our network better. Hence, comes the tensorflow shuffling!
