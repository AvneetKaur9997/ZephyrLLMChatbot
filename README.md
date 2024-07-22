
# Indian Dance Form Chatbot

This is a Gradio-based chatbot that helps users explore various Indian dance forms such as Bharatanatyam, Kathak, and Odissi. The chatbot uses the HuggingFace Zephyr-7b-beta model to provide information and answer questions about these dance styles.

## Features

- Explore different Indian dance forms
- Learn about Bharatanatyam, Kathak, Odissi, and more
- Interactive chat interface built with Gradio
- Customizable system messages, token limits, temperature, and top-p values

## Requirements

- Python 3.x
- `gradio`
- `huggingface_hub==0.22.2`

You can install the required packages using the following command:

```bash
pip install -r requirements.txt
```

## Usage

1. Clone the repository:

```bash
git clone https://github.com/yourusername/indian-dance-form-chatbot.git
cd indian-dance-form-chatbot
```

2. Install the required packages:

```bash
pip install -r requirements.txt
```

3. Run the application:

```bash
python app.py
```

The application will launch a Gradio interface in your browser, where you can interact with the chatbot.

## File Structure

- `app.py`: The main application script containing the Gradio interface and chatbot logic.
- `requirements.txt`: The file listing the required Python packages.

## Customization

You can customize the system message, max tokens, temperature, and top-p values through the Gradio interface. Additionally, you can add more examples to guide the interaction with the chatbot.

## Example Questions

- Which Indian dance style emphasizes storytelling?
- Can you recommend a beginner-friendly Indian dance style?
- What is the significance of mudras in classical Indian dance?

## License

This project is licensed under the MIT License. See the `LICENSE` file for details.

## Acknowledgments

- [Gradio](https://www.gradio.app/) for the easy-to-use interface
- [HuggingFace](https://huggingface.co/) for the powerful language model

For more information on `huggingface_hub` Inference API support, please check the [docs](https://huggingface.co/docs/huggingface_hub/v0.22.2/en/guides/inference).

---

Feel free to contribute to the project by opening issues or submitting pull requests.
```

Replace `https://github.com/yourusername/indian-dance-form-chatbot.git` with the actual URL of your GitHub repository.
