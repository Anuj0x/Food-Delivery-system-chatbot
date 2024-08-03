# Food-ChatBot-DialogFlow

This project demonstrates the integration of a chatbot powered by Dialogflow with a web-based user interface. Users can interact with the chatbot through a web interface built with HTML and CSS. The backend is powered by FastAPI, which connects to a MySQL database to store and retrieve chatbot conversation data.


## Table of Contents

- [Prerequisites](#prerequisites)
- [Getting Started](#getting-started)
- [Project Structure](#project-structure)
- [Usage](#usage)
- [Deployment](#deployment)
- [Contributing](#contributing)
- [License](#license)
- [Acknowledgments](#acknowledgments)
- [Contact](#contact)

## Prerequisites

Before you begin, ensure you have met the following requirements:

- **Dialogflow Account:** You need a Dialogflow agent set up. Visit [Dialogflow](https://cloud.google.com/dialogflow) to get started.

- **FastAPI**: Ensure you have FastAPI installed on your development environment.

- **MySQL Database**: Set up a MySQL database to store chatbot conversation data.

- **HTML and CSS Knowledge**: Basic knowledge of HTML and CSS for customizing the web interface.

## Getting Started

1. Clone the repository:

   ```bash
   git clone https://github.com/mitensahoo/Food-ChatBot-DialogFlow.git
   cd Food-ChatBot-DialogFlow
   ```

2. Install the required Python packages:

   ```bash
   pip install -r requirements.txt
   ```

3. Configure Dialogflow:

   - Create a new Dialogflow agent.
   - Set up the necessary intents, entities, and fulfillment for your chatbot.

4. Configure MySQL Database:

   - Update the database connection details.

5. Start the FastAPI server:

   ```bash
   uvicorn main:app --reload
   ```

6. Access the chatbot interface:

   - Open `index.html` in your web browser or host it on a web server.


