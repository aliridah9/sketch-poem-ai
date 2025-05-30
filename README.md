# Sketch Poem AI

A machine learning project that generates sketches from poems using Stable Diffusion and LoRA fine-tuning.

## Project Overview

This project uses Stable Diffusion with LoRA fine-tuning to generate artistic sketches based on poems. It combines the power of text-to-image generation with custom sketch style training.

## Features

- Fine-tunes Stable Diffusion model with custom sketch style
- Uses LoRA for efficient fine-tuning
- Integrates with Hugging Face Hub
- Supports Google Colab for GPU acceleration
- Includes automated image captioning with BLIP

## Setup

1. Clone the repository:
```bash
git clone https://github.com/aliridah9/sketch-poem-ai.git
cd sketch-poem-ai
```

2. Install dependencies:
```bash
pip install -r requirements.txt
```

3. Create a `.env` file with your Hugging Face token:
```
HUGGINGFACE_TOKEN=your_token_here
```

## Usage

1. Open the Jupyter notebook in Google Colab
2. Mount your Google Drive
3. Follow the notebook cells in sequence:
   - Installation
   - Hugging Face login
   - Training setup
   - Model training
   - Inference

## Project Structure

```
sketch-poem-ai/
├── .env                    # Environment variables (not tracked)
├── .gitignore             # Git ignore file
├── README.md              # Project documentation
├── requirements.txt       # Project dependencies
├── Untitled7.ipynb        # Main notebook
└── train_dreambooth_lora.py  # Training script
```

## Requirements

- Python 3.8+
- CUDA-compatible GPU
- Google Colab account
- Hugging Face account with API token

## License

MIT License

## Contributing

Contributions are welcome! Please feel free to submit a Pull Request.