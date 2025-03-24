# Music-Generation

# Music Generation with AudioCraft

This repository contains code for generating music from text using **AudioCraft**, a powerful framework for audio generation developed by Meta (formerly Facebook). The objective of this project is to create music based on textual descriptions or prompts, leveraging the capabilities of AudioCraft's models.

## Table of Contents
- [Introduction](#introduction)
- [Features](#features)
- [Installation](#installation)
- [Usage](#usage)
- [Examples](#examples)
- [Contributing](#contributing)
- [License](#license)

## Introduction
AudioCraft is a framework that simplifies the process of generating high-quality audio, including music, from text prompts. This repository demonstrates how to use AudioCraft to generate music based on textual input. The generated music can be used for creative projects, background scores, or experimentation.

## Features
- Generate music from text descriptions.
- Leverage pre-trained models from AudioCraft for high-quality audio generation.
- Easy-to-use scripts for music generation.
- Customizable parameters for controlling the output.

## Installation
To use this repository, follow these steps:

1. **Clone the repository:**
   ```bash
   git clone https://github.com/abm984/Music-Generation.git
   cd music-generation-audiocraft
   ```

2. **Set up a Python environment:**
   It is recommended to use a virtual environment to manage dependencies.
   ```bash
   python -m venv venv
   source venv/bin/activate  # On Windows, use `venv\Scripts\activate`
   ```

3. **Install dependencies:**
   Install the required Python packages using `pip`.
   ```bash
   pip install -r requirements.txt
   ```

4. **Install AudioCraft:**
   AudioCraft is not available on PyPI, so you need to install it from the source. Follow the official [AudioCraft installation guide](https://github.com/facebookresearch/audiocraft) to set it up.

## Usage
To generate music from text, use the provided script `generate_music.py`.

1. **Run the script:**
   ```bash
   python app.py --text "A joyful and uplifting melody with a fast tempo"
   ```

2. **Customize parameters:**
   You can customize the generation process by modifying the script or passing additional arguments:
   - `--text`: The text prompt describing the music.
   - `--duration`: Duration of the generated music in seconds (default: 10).
   - `--output`: Output file name (default: `output.wav`).

   Example:
   ```bash
   streamlit run app.py 
   ```

3. **Output:**
   The generated music will be saved as a `.wav` file in the specified output location.

## Examples
Here are some example text prompts you can use to generate music:
- "A dramatic orchestral piece with heavy drums and strings."
- "A futuristic electronic track with a fast beat and synth melodies."
- "A soothing ambient track with soft pads and gentle rhythms."

## Contributing
Contributions are welcome! If you have any ideas, improvements, or bug fixes, feel free to open an issue or submit a pull request. Please ensure your code follows the project's style and includes appropriate documentation.

1. Fork the repository.
2. Create a new branch for your feature or bugfix.
3. Commit your changes and push to the branch.
4. Open a pull request.

## License
This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for details.

---

Enjoy generating music with AudioCraft! If you have any questions or need assistance, feel free to reach out or open an issue in the repository. 🎵
