# Telegram Bot using Aiogram, Stable Diffusion, and Llama3

This project is a Telegram bot built using the Aiogram framework. The bot allows users to generate images using the models Stable Diffusion and Llama3 using Replicate API. The choice between image and text generation is made via keyboard buttons in the Telegram bot interface. API tokens are sourced from [replicate.com](https://replicate.com).

## Features

- **Image Generation**: Generate images using the Stable Diffusion model via the Replicate API.
- **Text Generation**: Generate text using the Llama3 model via the Replicate API.
- **Interactive Keyboard**: Users can choose between generating images or text through an interactive keyboard.

## Installation

1. **Clone the repository**:
    ```bash
    git clone https://github.com/Merunj/Aiogram-with-Stable-Diffusion-and-Llama3.git
    cd Aiogram-with-Stable-Diffusion-and-Llama3
    ```

2. **Create and activate a virtual environment**:
    ```bash
    python -m venv venv
    source venv/bin/activate  # On Windows use `venv\Scripts\activate`
    ```

3. **Install dependencies**:
    ```bash
    pip install -r requirements.txt
    ```

4. **Set up environment variables**:
    Create a `.env` file in the project root directory and add your API token:
    ```env
    REPLICATE_API_TOKEN = 'YOUR_TOKEN'
    ```
    In config.py add telegram token:
   ```python
   TOKEN = "YOUR_TOKEN"
   ```

## Usage

1. **Run the bot**:
    ```bash
    python run.py
    ```

2. **Interact with the bot**:
    Open your Telegram app and start a chat with your bot. Use the /start command for further instructions on how to use the bot

## Configuration

- **Aiogram**: Used for creating the Telegram bot.
- **Stable Diffusion**: Model used for generating images via the Replicate API.
- **Llama3**: Model used for generating text via the Replicate API.
- **Replicate.com**: Platform providing access to machine learning models.

## Example

When you start the bot, use the /info command, where you will be presented with a choice between generating photos and text. Select one of the two options and start generating. After each generation, you can return to the main menu to select a different generation method

## Contributing

1. Fork the repository.
2. Create a new branch (`git checkout -b feature-branch`).
3. Commit your changes (`git commit -am 'Add new feature'`).
4. Push to the branch (`git push origin feature-branch`).
5. Create a new Pull Request.

## Acknowledgements

- [Aiogram](https://github.com/aiogram/aiogram) - A powerful and easy-to-use framework for Telegram Bot API.
- [Stable Diffusion](https://replicate.com/stability-ai/stable-diffusion) - API for image generation.
- [Llama3](https://replicate.com/meta/meta-llama-3-70b-instruct) - API for text generation.
- [Replicate.com](https://replicate.com) - Platform providing access to machine learning models.

## Contact

If you have any questions or suggestions, feel free to open an issue or contact me at [meowsweep@gmail.com](mailto:meowsweep@gmail.com).
