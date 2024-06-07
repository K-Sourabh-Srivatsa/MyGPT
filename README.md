# Bigram Language Model with PyTorch

This project contains a simple implementation of a bigram language model using PyTorch. The model learns to predict the next character in a sequence based on the preceding character.

**Key Features:**

- **Transformer Blocks:** Utilizes Transformer architecture with self-attention layers for capturing dependencies in the text sequence.
- **Training and Evaluation:** Implements a training loop for optimizing model parameters and evaluates the model's performance on a validation set.
- **Text Generation:** Allows for text generation starting from a user-provided prompt.

**Libraries Used:**

- **PyTorch:** The core deep learning library used for building and training the model.
- **torch.nn:** PyTorch's neural network module for defining and using layers.
- **torch.nn.functional:** PyTorch's functional module for common operations.
- **torch.optim:** PyTorch's optimizer module used for updating model parameters during training.

## **Running the Project: Step-by-Step Guide**

Here's a formatted guide to follow the instructions for running a project:

**1. Download Project Files:**

- Clone the repository (preferred) or download it as a zip file.

**2. Access Google Colab:**

- Go to Google Colab.

**3. Open the MyGPT Notebook:**

- In your Colab workspace, open the notebook named "MyGPT".

**4. Upload Dataset:**

- On the left navigation bar, click on the "Files" tab.
- Upload the file named "Transformer Dataset.txt" to your Colab workspace.

**5. Set File Path (Optional):**

- If the notebook doesn't recognize the file path automatically:
    - Right-click on "Transformer Dataset.txt" in the "Files" tab.
    - Copy the file path.
    - Paste the copied path into the `file_path` variable within the text generation section of the notebook.

**6. Run the Project:**

- Once the file path is set (if necessary) or automatically detected, run the notebook cells to execute the project.

**7. Provide Input (Optional):**

- The instructions mention a `prompt` variable in the text generation section. You can provide your own text prompt here to guide the model's generation.

**8. Execute the Project:**

- After setting any prompts (optional), run the notebook cells to start the project.
