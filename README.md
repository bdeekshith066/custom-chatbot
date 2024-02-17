## ChatBot with Message Recognition

This repository contains a simple chatbot implemented in Python that utilizes message recognition techniques to generate appropriate responses based on user input. The chatbot is designed to engage in conversations on various topics and respond accordingly.

### Features:

- **Message Recognition:** The chatbot analyzes user messages using predefined word lists to determine the probability of specific topics being mentioned.
- **Response Generation:** Based on the analysis of user messages, the chatbot generates responses tailored to the recognized topics.
- **Customizable Responses:** Responses can be easily customized and expanded by adding new predefined messages along with associated word lists.
- **Unknown Query Handling:** If the user input does not match any predefined messages, the chatbot provides a random response to prompt for clarification.

### How it works:

1. **Message Analysis:** User input is split into individual words and compared against predefined word lists associated with potential topics.
2. **Probability Calculation:** The chatbot calculates the probability of each predefined message based on the presence of recognized words in the user input.
3. **Response Selection:** The chatbot selects the response with the highest probability or provides an unknown response if no matches are found.

### Usage:

To use the chatbot, simply run the provided Python script. The chatbot will prompt you to input a message, to which it will respond accordingly based on the recognized topics.

### Contribution:

Contributions to this project are welcome! If you have ideas for improving the chatbot's functionality, adding new features, or enhancing its performance, feel free to submit a pull request.

### Author:

Deekshith B

### License:

This project is licensed under the [MIT License](LICENSE).

