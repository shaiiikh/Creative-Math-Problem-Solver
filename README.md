# Creative Math Problem Solver

## Project Overview

The **Creative Math Problem Solver** project explores the boundaries of generative AI by combining **creativity**, **humor**, and **mathematics** into one fun challenge. The goal is to train a model to solve math problems written entirely in **emoji**. For example, solving problems like 🍎 + 🍎 + 🍎 = 12, where 🍎 = 4.

The model used for this project is **unsloth/deepseek-r1-distill-llama-8b-unsloth-bnb-4bit**, fine-tuned with a custom dataset of **30 emoji-based math problems**. The fine-tuning process used **Unsloth** for efficient model training.

## Goal

- **Fine-tune a model** to **solve math problems in emoji**.
- Generate correct and engaging **emoji-based math problems** and solutions.

## Files in the Repository

- **fine-tuned-OA-deepseek-lama-8B**: Folder containing the fine-tuned model for emoji math problem solving.
- **outputs/**: Folder containing the output files, including solved emoji math problems.
- **LICENSE**: License file for the project.
- **Q3.ipynb**: Jupyter notebook for the fine-tuning process and testing.
- **README.md**: Documentation for the Creative Math Problem Solver project.
- **emoji_math.csv**: Dataset file containing emoji math problems and their solutions.
- **requirements.txt**: List of Python dependencies required to run the project.

## Steps

### 1. Dataset Creation
- Created a dataset of **30 emoji-based math problems** and their corresponding solutions.
- Each problem used emoji symbols to represent numbers and mathematical operations (e.g., 🍎 + 🍎 + 🍎 = 12).

### 2. Fine-Tuning
- Used the **unsloth/deepseek-r1-distill-llama-8b-unsloth-bnb-4bit** model and fine-tuned it on the emoji math dataset for **2-3 epochs**.
- Fine-tuning utilized **Unsloth** for efficient training and **4-bit quantization** to optimize memory usage.

### 3. Testing
- Provided **3 new emoji-based math problems** to the fine-tuned model.
- Evaluated if the model could correctly solve the problems and explain the process.

## Deliverables

- A **before/after example**, showing an emoji math problem and the model's solution.
- A fun, engaging **error rating** for the model’s humor and creativity when solving the problems.

### Example:

- **Problem**: 🍎 + 🍎 + 🍎 = 12
  - **Solution**: 🍎 = 4

- **Problem**: 🚗 + 🚗 + 🚗 + 🚗 = 20
  - **Solution**: 🚗 = 5

## Technologies Used

- **Model**: [unsloth/deepseek-r1-distill-llama-8b-unsloth-bnb-4bit](https://huggingface.co/unsloth/deepseek-r1-distill-llama-8b-unsloth-bnb-4bit)  
- **Fine-Tuning Framework**: **Unsloth**, **4-bit Quantization**
- **Libraries**: **Hugging Face Transformers**, **PyTorch**

## How to Run

1. Clone the repository:  
   `git clone https://github.com/shaiiikh/Creative-Math-Problem-Solver.git`

2. Install dependencies:  
   `pip install -r requirements.txt`

3. Fine-tune the model:  
   run the cells in the **Q3.ipynb** file

4. Generate emoji math problem solutions:  
   run the inference cell in the **Q3.ipynb** file


## Conclusion

The **Creative Math Problem Solver** project demonstrates how **Generative AI** can be applied to **emoji-based math problems**, combining creativity and humor in a unique way. By using **unsloth/deepseek-r1-distill-llama-8b-unsloth-bnb-4bit**, **Unsloth**, and **4-bit quantization**, we were able to fine-tune the model efficiently and generate fun, engaging solutions to math problems represented with emojis.
