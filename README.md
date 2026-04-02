ESC50-Image-Classification

The Environmental Sound Classification dataset can be found at https://github.com/karolpiczak/ESC-50.

This notebook builds a LeNet5 model with dropout and trains it on images of the wav file.

To run the program, create a new anaconda environment and install the libraries as described in the environment.yml\
`conda env create -f environment.yml`

If you're using cuda, change **device** to `"cuda"`. If you're using apple sillicon use `torch.device("mps")`.
