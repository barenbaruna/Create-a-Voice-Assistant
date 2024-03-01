# Create a Voice Assistant with OpenAI's GPT-3 and IBM Watson

## Author: Cognitive Class by Rohit and Talha

## 🚀 Mentee Information
| Name             | Program         | Mentor                  |
|------------------|----------------|------------------------|
| Baren Baruna Harahap | MSIB Batch 6 (IBM Advance AI) | Ichsan Takwa       |

Welcome to this guided project about creating a voice assistant using OpenAI and IBM Watson Speech Libraries for Embed. This project takes you through building a virtual assistant that can take voice input, convert it to text using speech-to-text technology, send the text to OpenAI’s GPT-3 model, receive a response, convert it to speech using text-to-speech technology, and finally play it back to the user. The voice assistant will have a responsive front-end using HTML, CSS, and JavaScript, and a reliable back-end using Flask.

[Click here to play with a demo](https://ai-personal-assistant.xs6r134s1i6.us-east.codeengine.appdomain.cloud/) of the final application that you will create!

## Introduction

By the end of this project, you will have a deep understanding of voice assistants and the skills to create your own AI-powered assistant that can communicate through voice input and output. You will also have a strong foundation in web development using Python, Flask, HTML, CSS, and JavaScript, and a finished full-stack application that is sure to impress anyone that comes across it!

### OpenAI

OpenAI is a research organization aiming to promote and develop friendly artificial intelligence for the benefit of humanity. We will be utilizing OpenAI's GPT-3, a state-of-the-art natural language processing model, in our assistant to enable it to understand and respond to a wide range of user inputs.

### IBM Watson Speech Libraries for Embed

IBM Watson® Speech Libraries for Embed are a set of containerized text-to-speech and speech-to-text libraries designed to offer our IBM partners greater flexibility to infuse the best of IBM Research® technology into their solutions. These technologies allow the assistant to communicate with users through voice input and output.

### Voice Assistants

A virtual assistant is a program designed to simulate conversation with human users, especially over the Internet using natural human voice.

### Python (Flask)

Python is a popular programming language widely used in web development and data science. Flask is a web framework for Python that simplifies building web applications. We will use Python and Flask to build the backend of our voice assistant.

### HTML - CSS - JavaScript

HTML (Hypertext Markup Language), CSS (Cascading Style Sheets), and JavaScript are fundamental technologies for building web pages. Together, they enable us to create a visually appealing and interactive front end for our assistant.

## Project Objectives

- Understand the basics of voice assistants and their various applications
- Set up a development environment for building an assistant using Python, Flask, HTML, CSS, and JavaScript
- Implement speech-to-text functionality to allow the assistant to understand voice input from users
- Integrate the assistant with OpenAI’s GPT-3 model to give it a high level of intelligence and the ability to understand and respond to user requests
- Implement text-to-speech functionality to allow the assistant to communicate with users through voice output
- Combine all of the above components to create a functioning assistant that can take voice input and provide a spoken response
- (Optional) Understand how to deploy the assistant to a web server for use by a wider audience

## Prerequisites

Knowledge of the basics of HTML/CSS, JavaScript, and Python are nice to have but not essential. 

## Starting the Application

To start the application, follow these steps:

1. **Building the Docker image:**

    ```bash
    docker build . -t voice-chatapp-powered-by-openai
    ```

2. **Running the Docker container:**

    ```bash
    docker run -p 8000:8000 voice-chatapp-powered-by-openai
    ```

These commands first build the application (running the commands in the Dockerfile) and tag (name) the built container as `voice-chatapp-powered-by-openai`, then run it in the foreground on port 8000. You’ll need to run these commands every time you wish to make a new change to one of the files.

## Conclusion
Throughout this project, we have learned about the various components that make up an assistant, including speech-to-text technology, natural language processing with GPT-3, text-to-speech technology, and web development using Python, Flask, HTML, CSS, and JavaScript.
