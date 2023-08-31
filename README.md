# Automatic Generation of German Dramatic Dialogue

This project aims to fine-tune a German GPT-2 model on German plays, enabling the generation of coherent and contextually relevant text in the style of theatrical scripts. The resulting model can be used for various creative writing and text generation applications.

## Project Structure

- `data-collection.ipynb`: Jupyter Notebook for collecting and preprocessing training data from German theater plays.
- `train_model.ipynb`: Jupyter Notebook for fine-tuning the pretrained GPT-2 model using the preprocessed data.
- `prompting.ipynb`: Jupyter Notebook for text generation using the trained model.
- `data-overview.ipynb`: Jupyter Notebook for generating corpora for stylometric analysis.
- `environment.yml`: Environment file specifying required dependencies.
- `build`: Shell script for automating project setup on Linux distributions.

## Getting Started

### Prerequisites

- Linux distribution (for automated setup using `build` script)
- Python 3.11 (if manual installation is required)
- Anaconda environment (if manual installation is required)
- GPU from NVIDIA (if training the model locally)
- Access to Google Colab (if training the model on Google Colab)

### Automated Setup (Linux)

1. Clone this repository: `git clone https://github.com/yourusername/DL-in-DH.git`
2. Navigate to the project directory: `cd DL-in-DH`
3. Run the build script: `. ./build`

### Manual Setup

1. Clone this repository: `git clone https://github.com/yourusername/DL-in-DH.git`
2. Install Anaconda with Python 3.11.
3. Create a new Anaconda environment with required dependencies: `conda env create --file environment.yml`
4. Activate the environment: `conda activate dl-in-dh`
6. Open Jupyter Notebook and explore the provided notebooks.

## Training and Inference

1. Use `data-collection.ipynb` to gather and preprocess training data.
2. Train the model using `train_model.ipynb`.
3. Generate text using the fine-tuned model with `prompting.ipynb`.

## Scene Generation (Prototype)

After training the model, you can use the `scene_generation.ipynb` notebook to generate a scene based on a given prompt using the gradio interface. Run the notebook and click on the link that appears in the output. This will open the interface in a new tab. 

## Note

Training the model requires substantial computational resources, such as Google Colab or a powerful GPU.

## Colaborators

Quian Liu,
Jeremy Büdinger,
Mikhail Sonkin,
Manuel John

## License

This project is licensed under the [MIT License](LICENSE).

Feel free to contribute, report issues, and suggest improvements!
