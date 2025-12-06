# Text-to-Image Generation System

A minimal, no-nonsense implementation of text-to-image generation using the Stable Diffusion XL (SDXL) pre-trained pipeline.
The project focuses on clarity and correctness — nothing extra, no UI, no fancy wrappers, just the core model and clean code.

🚀 Features

  1. Generates images directly from text prompts
  2. Uses SDXL, one of the strongest publicly available diffusion models
  3. Simple Python script — easy to read and modify
  4. Supports GPU acceleration (CUDA)
  5. Zero unnecessary files or bloat

📂 Project Structure
  Text-to-Image-Generation-System/
     │
     ├── text_to_image.ipynb       # Main script that loads SDXL and generates images
     ├── README.md              # Documentation
     └── .gitignore             # Keeps repo clean

📦 Installation
1. Clone the repo
   git clone https://github.com/Shalini6654/Text-to-Image-Generation-System.git
   cd Text-to-Image-Generation-System

2. Install dependencies
    pip install torch diffusers transformers accelerate


If using CUDA, install the CUDA version of PyTorch:
pip install torch --index-url https://download.pytorch.org/whl/cu118

🧠 How It Works (Short + Accurate)

  Script loads pre-trained SDXL model.
  Takes a text prompt.
  Diffusion process converts noise → image.
  Saves the final output.
  No fine-tuning.
  No UI.
  No extra steps.
  just a clean pipeline execution.

📌 Requirements

   Python 3.9+
   PyTorch
   Diffusers
   Transformers
   Accelerate
   GPU recommended (but CPU will work, very slow)

🎯 Use Cases

  This project is suitable for:
  Students learning basics of diffusion models
  People testing SDXL without using heavy tools
  Demonstrating GenAI fundamentals in simple form
  Extending later into fine-tuning or prompt-based experiments

🤝 Contributions

If someone wants to improve:
   Better prompt templates
   Add more parameters
   Support for multiple outputs
   Cleanup / optimization
   They can open a PR.
