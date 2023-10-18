# SolveX

SolveX is a ChatGPT clone built using Python, HTML, CSS, JavaScript, and Docker. It enables you to set up a chatbot interface and have interactive conversations with an AI-powered model. This project is perfect for experimenting with chatbot development, AI models, and web technologies.

## Features

- **Chat Interface**: Engage in interactive conversations with the ChatGPT model.
- **Easy Setup**: Utilize Docker for a straightforward setup and deployment.
- **Customizable**: Adapt and extend the chatbot for your specific use cases.
- **User-Friendly**: The user interface is designed for a smooth chat experience.

## Getting Started

### Prerequisites

Before you start, ensure you have the following prerequisites installed:

- Docker: [Docker Installation Guide](https://docs.docker.com/get-docker/)
- Python 3: [Python Installation Guide](https://www.python.org/downloads/)
- Git: [Git Installation Guide](https://git-scm.com/downloads)

### Installation

1. Clone the repository:

   ```bash
   git clone https://github.com/awkwardpy/solveX.git
   cd solveX
   ```

2. Build the Docker container:

   ```bash
   docker build -t chatgpt .
   ```

3. Run the container:

   ```bash
   docker run -p 8000:8000 chatgpt
   ```

4. Open your web browser and access `http://localhost:8000` to start chatting with your ChatGPT clone.

## Usage

1. Open the web interface in your browser.

2. Start a conversation by typing a message and pressing Enter.

3. Chat with the ChatGPT model, which will respond with AI-generated text.

4. Continue the conversation by adding more messages.

## Customization

You can customize the ChatGPT clone by modifying the Python code and adjusting the HTML and CSS to change the appearance and behavior of the chat interface.

## Contributing

Feel free to contribute to this project by creating pull requests. You can improve the code, add new features, or fix issues. Your contributions are welcome!

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

## Acknowledgments

- OpenAI for their GPT-3 model, which inspired this project.

Happy Chatting with SolveX!
