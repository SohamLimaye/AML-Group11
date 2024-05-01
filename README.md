# AML-Group11
AML SCE task submission. 

We will be submitting the following as part of our SCE
- Code
- Report
- Presentation slides

Link to the dataset: https://github.com/vimal-isi-edu/BioFors

Link to the reference paper: https://arxiv.org/pdf/2108.12961v1.pdf

Link to colab file: [https://colab.research.google.com/drive/18HoC7KfQl0NVKqJZKbvpcQde9BjSLxFq#scrollTo=AIhn5g1zQfR0](https://colab.research.google.com/drive/18HoC7KfQl0NVKqJZKbvpcQde9BjSLxFq?usp=sharing)

Images in BioFors are divided into four categories – Microscopy, Blot/Gel, FACS and Macroscopy.

Work done
- Imported dataset
- created a sample training subset
- compiled and trained VGG19 model
- tested the model

Future work to be done:
1. Since the dataset is huge, I couldn't create a good amount of training subset. So creating a properly labeled training set is first task
2. I've only implemented VGG19 model, and we need to implement ResNet, GoogleNet, AlexNet, and other possible architectures as well
3. Next we need to compare the performance of these architectures
