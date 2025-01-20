# Chatbot HTML Frame with OpenAI Integration

This project is a simple chatbot interface built using HTML, CSS, and JavaScript. It integrates with the OpenAI API to provide intelligent responses powered by GPT models.

## Features
- Interactive chatbot interface.
- Sends user messages to OpenAI's API and displays responses.
- Clean and responsive design.

## How It Works
1. Users type a message in the input field.
2. The message is sent to the OpenAI API using `fetch`.
3. The chatbot displays the response from OpenAI.

## Setup Instructions

### Prerequisites
- An OpenAI API key. You can obtain one by signing up at [OpenAI's website](https://platform.openai.com/).
- A web browser to run the HTML file.

### Steps
1. Clone the repository:
   ```bash
   git clone https://github.com/yourusername/chatbot-frame.git
   cd chatbot-frame
   ```

2. Open the `index.html` file in a text editor.

3. Replace `your-api-key-here` with your actual OpenAI API key:
   ```javascript
   const OPENAI_API_KEY = "your-api-key-here";
   ```

4. Open `index.html` in a browser to test the chatbot.

### Example Interaction
- **User:** What is the capital of France?
- **Bot:** The capital of France is Paris.

## Customization
- **Chatbot Header**: Edit the `chat-header` section in the HTML to change the title.
- **Styles**: Modify the CSS in the `<style>` tag to customize the design.
- **API Model**: Change the `model` field in the API call (e.g., `gpt-4` instead of `gpt-3.5-turbo`).

## Dependencies
This project does not require any external libraries or frameworks. It uses:
- HTML for structure.
- CSS for styling.
- JavaScript for functionality and API integration.

## Limitations
- Requires a valid API key to function.
- Dependent on OpenAI API availability.

## Future Enhancements
- Add persistent chat history.
- Integrate speech-to-text for voice input.
- Add a back-end for storing messages and user sessions.

## License
This project is licensed under the MIT License. See the LICENSE file for more details.


