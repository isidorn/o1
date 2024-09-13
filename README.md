# OpenAI Chat Extension for VS Code

This Visual Studio Code extension integrates OpenAI's chat capabilities directly into your development environment, allowing you to interact with AI models like GPT-3.5-turbo or GPT-4 without leaving your editor.

## Features

- Seamless integration with VS Code's chat interface
- Direct communication with OpenAI's API
- Support for streaming responses

## Prerequisites

Before using this extension, you need to have an OpenAI API key. If you don't have one, you can obtain it from [OpenAI's website](https://openai.com/).

## Installation

1. Install the extension from the VS Code marketplace or by searching for "OpenAI Chat" in the Extensions view.
2. Reload VS Code after installation.

## Setup

1. Create a `.env` file in the root directory of your extension with your OpenAI API key:
   ```
   OPENAI_API_KEY=your_api_key_here
   ```
2. If you prefer not to use a `.env` file, the extension will prompt you to enter your API key when you first use it.

## Usage

1. Open the Command Palette (Ctrl+Shift+P or Cmd+Shift+P on macOS).
2. Type "OpenAI Chat" and select it from the list.
3. Type your question or prompt in the chat input.
4. The AI's response will be streamed back to you in the chat window.

## Configuration

The extension currently uses the "o1-preview" model by default. You can change this in the `src/extension.ts` file if you prefer a different model.

## Error Handling

The extension includes basic error handling. If an error occurs, it will be displayed in the chat window and logged for debugging purposes.

## Contributing

Contributions are welcome! Please feel free to submit a Pull Request.

## License

This project is licensed under the MIT License.

## Disclaimer

This extension is not officially associated with OpenAI. It's an independent project that uses OpenAI's API.

## Support

If you encounter any issues or have questions, please open an issue on the GitHub repository.
