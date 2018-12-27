# sigmoid-neuron

Inside the human brain is a neural network composed of around 100 billion neurons. In this neural network, each neuron is connected to many other neurons. 

In this notebook, we look at modelling an artificial neuron. We will create a neuron that can accept any number of input voltages and then determine what its output voltage will be. We will create a certain type of neuron called a **sigmoid neuron** because it uses a **sigmoid function** to determine what its output will be based upon the inputs it receives. 

We will create our neuron so that it has **weights** and a **bias**. Each of the inputs coming into our neuron will receive a weight that represents its individual importance in getting the neuron to fire. The bias of the neuron will be a measure of how easy the neuron wants to fire in general. If the bias is high, the neuron will fire easy. If it is low, then the neuron will be biased towards not firing.

The Jupyter notebook will create the following plots. 

![Alt text](./images/bias.png?raw=true "Title")

![Alt text](./images/neuron-output.png?raw=true "Title")
