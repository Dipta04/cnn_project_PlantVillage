A convolutional neural network built from scratch in PyTorch to classify plant leaf diseases across 38 categories using the PlantVillage dataset (~43K training images). The model uses a 3-block feature extractor (Conv → BatchNorm → MaxPool) followed by a fully connected classifier with dropout, trained with Adam and CrossEntropyLoss on GPU via Google Colab.

**Dataset Link:** https://www.kaggle.com/datasets/mohitsingh1804/plantvillage 

**Project Mind Map:**

![Project Mind Map](https://raw.githubusercontent.com/Dipta04/cnn_project_PlantVillage/main/Project_mind_map.png)
