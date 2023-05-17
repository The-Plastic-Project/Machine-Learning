Repository contains code for **The Plastic Project** garbage and trash recycling initiative via Artificial Intelligence. 

###### File structure 

At the moment, we have notebooks folder in the repository. Which contains, a jupyter notebook for our image classification algorithms that can be used to train for sorting different recyclable garbage. 

We have used trashnet to train our models. Trashnet is a state of the art waste classification dataset developed by Stanford University. And is considered as a benchmark dataset among waste datasets. 

###### Approach

Currently, we are using a combination of Shallow deep learning models e.g. **LeNet-5** and **WasteNet**. 

- LeNet-5, is widely tested and proven model architecture used by experts across the domain, both for its shallow nature and competitive results against VGG-16 model. 

- WasteNet is a state of the art, waste classification algorithm developed by the UK government to be used in smart bins in public. The original algorithm/code is not released in public both by the researchers and the UK government. Neither the dataset that it is trained on before deployment contains 3 million images. (Though in the research paper it was trained on trashnet dataset)

**Our team has successfully reverse engineered the algorithm aka WasteNet and in the notebooks folder, you can access it via jupyter notebooks.** 



