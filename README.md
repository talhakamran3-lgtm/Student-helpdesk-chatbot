College Helpdesk Chatbot
This project is a simple, browser-based chatbot designed to provide information about a college, such as admission details, fees, and library hours. The chatbot is built using HTML, Tailwind CSS, and vanilla JavaScript, with the core logic running entirely on the client side.

The chatbot's responses are based on a predefined set of intents and patterns, which are stored directly in the index.html file. This makes the project portable and easy to run without a separate server.

Features
Conversational Interface: A clean and modern chat UI for easy interaction.

Predefined Responses: The chatbot provides instant answers to common questions based on an embedded intents.json dataset.

Client-Side: The entire application runs in a single HTML file, making it highly portable.

Responsive Design: The interface is designed to work well on both desktop and mobile devices.

Project Structure
index.html: The main file containing all the HTML, CSS, and JavaScript for the chatbot.

intents.json: The JSON data that defines the chatbot's conversational patterns and responses. Note: This data is embedded directly in the index.html file to ensure the app runs without a server.

How to Run
Clone this repository to your local machine.

git clone [https://github.com/talhakamran3-lgtm/chatbot.git](https://github.com/talhakamran3-lgtm/chatbot.git)

Navigate to the project directory.

cd chatbot

Open the index.html file in any modern web browser (Google Chrome, Firefox, Edge, etc.).

How to Customize
You can easily customize the chatbot's knowledge base by modifying the intentsData JavaScript object within the index.html file.

Each intent has:

tag: A unique identifier for the intent (e.g., "fees", "admission").

patterns: An array of example phrases a user might say.

responses: An array of possible answers the chatbot can give.

Simply add or edit the objects in the intentsData array to expand the chatbot's capabilities.

Credits
Tailwind CSS: For the modern and responsive styling.

Inter Font: Used for clean and readable typography.

Author: Talha Kamran
