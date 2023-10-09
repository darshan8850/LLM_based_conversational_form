# LLM_based_conversational_form

## Project Overview

This repository provides a seamless solution for creating a conversational form using the Hugging Face Chat API. With this setup, you can interact with a Language Learning Model (LLM) powered by Hugging Face to fill out form details. The conversational interface not only simplifies the form-filling process but also validates the provided information and generates a CSV file for further processing.

## Prerequisites

Before you begin, make sure you have the following:

1. Google Colab: Ensure you have colab account.
2. Hugging Face API Key: You need email and password of  Hugging Face to access their Chat API.

## How It Works

1. Conversation Initialization:
The conversation starts with a welcome message from the LLM.
The LLM asks questions related to the form fields, guiding the user through the conversation.

2. Form Filling:
The user responds to the LLM's questions, providing the required details.
The conversational interface processes user input and validates it in real-time.

3. Validation:
The provided details are validated to ensure accuracy and completeness.
If there are any errors, the LLM asks for corrections before proceeding.

4. CSV Generation:
Once all details are successfully collected and validated, the information is stored in a CSV file.
The CSV file contains the form data, ready for further use or analysis.

## Customize and Extend
Feel free to customize the conversation flow, form fields, and validation logic according to your specific use case. You can modify the questions asked by the LLM, add new form fields, or implement additional validation checks.

## Contributing
Contributions are welcome! If you find any issues or have suggestions for improvements, please create an issue or submit a pull request.


## License
This project is licensed under the MIT License.
