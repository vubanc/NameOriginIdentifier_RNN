# NameOriginIdentifier_RNN
This is an NLP (Natural Language Processing) project that builds a PyTorch-based recurrent neural network (RNN) to identify the origin of names. The RNN is trained on a total of 20074 names from 18 origins.

An RNN is a neural network that can take sequences of inputs and produce output(s). In this project, the inputs are names. Hence, the alphabets in the names form a sequence of input which the RNN uses to predict the origin. For each alphabet in the name, the RNN calculates an output and a hidden state. The hidden state is passed on to the next layer as an input along with the next alphabet. Hidden states get passed on to the next layer recurrently until the RNN takes the final alphabet and final hidden state as the inputs to produce the output. 

Here is a visual representation of the model.
![Conceptual Model](https://github.com/vubanc/NameOriginIdentifier_RNN/assets/108584512/8d91ebe0-fb31-408a-9359-6c8cd6063b25)

