# LLM-Development-From-Scratch

This repository contains code to build a Large Language Model (LLM) from scratch using Python. The model is trained on text data and can be used for various natural language processing tasks.

 Prerequisites

- Python 3.x
- Matplotlib
- NumPy
- PyLZMA
- IPyKernel
- Jupyter Notebook
- PyTorch with CUDA support

 Installation

1. Clone the repository:

bash
git clone https://github.com/Nani1-glitch/LLM-Development-From-Scratch.git


2. Create a virtual environment and activate it:

bash
python -m venv llm-env
source llm-env/bin/activate  # On Windows, use llm-env\Scripts\activate


3. Install the required packages:

bash
pip install -r requirements.txt


4. Download and install Visual Studio C++ tools if you encounter an error while installing PyLZMA.

5. Install PyTorch with CUDA support:

bash
pip install torch --index-url https://download.pytorch.org/whl/cu118


6. Install the Jupyter Notebook kernel:

bash
python -m ipykernel install --user --name=llm-env --display-name "LLM Environment"


7. Start the Jupyter Notebook:

bash
jupyter notebook


8. Open the `BIGRAM.ipynb` notebook and select the `LLM Environment` kernel.

 Usage

1. Prepare your text data by removing any unwanted content (e.g., license information, illustrations).

2. Update the `data_path` variable in the notebook to point to your text file.

3. Run the cells in the notebook to preprocess the data, train the model, and generate text.

4. Customize the model architecture, hyperparameters, and training process as needed.

 Contributing

If you find any issues or have suggestions for improvements, feel free to open an issue or submit a pull request.

 License

This project is licensed under the [MIT License] (LICENSE).


