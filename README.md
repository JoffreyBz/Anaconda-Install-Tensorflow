# Anaconda-Install-Tensorflow
Install Tensorflow in Anconda


I found it kind of tricky to install Tensorflow (for compatible GPU), going through installation of Visual Studio, CUDA, cuDNN ...


I am explaning here how I did it on my system, which seems easier, faster, and still install all required components.

1/ Open Anaconda Prompt (make sure you have the latest version - Refer to Anaconda webpage)

2/Type the following in the prompt window and the package will be downloaded and installed. Please note that the "tensorflow_gpu" is a virtual enviroment name, feel free to change it at your convenience:
**_conda create --name tensorflow_gpu tensorflow-gpu_**

3/Next time you run a script where "import tensorflow" is required, start the Anaconda prompt and change environment using: 
**_conda activate tensorflow_gpu_**

