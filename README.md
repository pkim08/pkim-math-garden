# pkim-math-garden

These are the files that are serving a Tensorflow Model through a Website.

If you take note of the first two folders, namely 'TFJS' and 'TFJS_2', the project files are executed using the files within the folder labeled 'TFJS_2'. An issue arose when converting the originally saved model to TensorFlow.js from folder 'TFJS' returned a mismatched input tensor error when predicting the model. The 'TFJS_2' folder contains results where the model was run under a different seed and version for compatability issues. The notebooks provided are still under the seed and versions where folder 'TFJS' was created while the working .js files reference 'TFJS_2'.

Here is the link to the project website:
https://pkim08.github.io/pkim-project/
