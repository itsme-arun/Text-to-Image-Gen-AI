# Text-to-Image-Gen-AI
## Overview

The **AI Image Generator** is a web application that allows users to generate images using AI technology. By entering a prompt, users can create detailed and high-resolution images through the power of AI. This project leverages the Stability AI's Stable Diffusion model to generate unique images based on user input.

## Features

- **Image Generation**: Input a text prompt to generate up to 4 unique images.
- **Responsive Design**: Works seamlessly on both desktop and mobile devices.
- **User-Friendly Interface**: Clean and modern design with intuitive controls.
- **Download Images**: Easily download generated images with a single click.

## Technologies Used

- **HTML**: Structure of the web application.
- **CSS**: Styling and layout of the application.
- **JavaScript**: Handles user interactions and API integration.
- **Google Fonts**: For custom typography.
- **Stability AI's Stable Diffusion**: For generating images from prompts.

## Installation

To get started with this project, follow these steps:

### 1. Clone the Repository

```bash
git clone https://github.com/yourusername/ai-image-generator.git
cd ai-image-generator
```

### 2. Open in a Browser

Simply open the `index.html` file in a web browser. There is no need for a local server to run this project.

## Usage

1. **Enter a Prompt**: Type your desired image prompt into the input field. For example: `"A futuristic cityscape at sunset"`.
2. **Generate Images**: Click the "Generate" button to start the image generation process.
3. **View and Download**: Once the images are generated, they will appear in the grid. Click on any image to download it.

## Configuration

Replace the `apiKey` in the `script.js` file with your own API key if needed:

```javascript
const apiKey = "your-api-key-here";
```

**Important**: Make sure to keep your API key secure. For production use, consider handling API requests on the server side to keep your API key confidential.

## Development

To contribute to this project or make changes:

1. **Fork the Repository**: Create a personal copy of the repository on GitHub.
2. **Create a Branch**: Make changes in a separate branch.
3. **Commit Changes**: Commit your changes with descriptive messages.
4. **Push Changes**: Push your changes to your forked repository.
5. **Submit a Pull Request**: Open a pull request to the main repository for review.

## Acknowledgments

- **Stability AI** for providing the image generation model.
- **Google Fonts** for the typography used in the design.
- **All Contributors** who helped in the development of this project.
