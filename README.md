CNN Image Classification — CIFAR-10, CIFAR-100 & Animal-10 (Deep Learning)

Overview: Built and trained Convolutional Neural Networks for image classification across three progressively harder datasets, culminating in a real-world, imbalanced dataset with a competitive accuracy benchmark.

**Part 1: CIFAR-10**
Constructed a CNN using Keras to classify the 10-class CIFAR-10 dataset
Visualized sample images, tracked training/validation accuracy over epochs, and compared predicted vs. true labels

**Part 2: CIFAR-100**
Repeated the CNN pipeline on the more challenging 100-class CIFAR-100 dataset

**Part 3: Animal-10 (Kaggle)**
Loaded and preprocessed a real-world image dataset organized into class folders (80/20 train/test split via image_dataset_from_directory)
Explored dataset characteristics: image sizes, class distribution, sample visualizations
Addressed class imbalance via undersampling and/or data augmentation
Designed and tuned a custom CNN architecture (and explored transfer learning with MobileNetV2) to maximize validation accuracy
Visualized accuracy over training epochs

Benchmark: Achieved above the 60% validation accuracy baseline on Animal-10, with performance scored competitively against class-wide results.

Tech stack: Python, TensorFlow/Keras, CNNs, transfer learning (MobileNetV2)

Environment: Developed and trained using Google Colab.

[View the Project in Document format](DL_PrgAssign2.ipynb_Colab.pdf)

[View the Project in Document format](Prg2DeepLearning.pdf)
