# Fine-Tuned GPT-3 Demo

Fine-Tuned GPT-3 Demo is a showcase of using the GPT-3.5 Turbo model with fine-tuned capabilities. This repository provides a simple command-line interface for interacting with the fine-tuned model using the OpenAI API.

## Table of Contents
- [Introduction](#introduction)
- [Features](#features)
- [Getting Started](#getting-started)
- [Prerequisites](#prerequisites)
- [Installation](#installation)
- [Usage](#usage)
- [Customization](#customization)
- [Contributing](#contributing)

## Introduction

Fine-Tuned GPT-3 Demo allows users to interact with a fine-tuned version of the GPT-3.5 Turbo model using the OpenAI API. It provides a simple command-line interface for sending user messages and receiving model-generated responses.

## Features

- **GPT-3.5 Turbo:** Leverages the powerful GPT-3.5 Turbo model from OpenAI.
- **Fine-Tuned Capabilities:** Demonstrates the usage of a fine-tuned model for more specialized responses.
- **Interactive CLI:** Allows users to engage in a chat-like interaction with the model.

(Add more features as needed)

## Getting Started

These instructions will guide you through setting up the Fine-Tuned GPT-3 Demo on your local machine for interaction with the fine-tuned GPT-3.5 Turbo model.

### Prerequisites

- Node.js installed on your machine
- OpenAI API key obtained from the [OpenAI platform](https://beta.openai.com/signup/)
- `.env` file configured with your OpenAI API key

### Installation

1. Clone the repository:

    ```bash
    git clone https://github.com/yourusername/fine-tuned-gpt3-demo.git
    ```

2. Change directory:

    ```bash
    cd fine-tuned-gpt3-demo
    ```

3. Install dependencies:

    ```bash
    npm install
    ```

4. Configure OpenAI API key:

    Create a `.env` file in the root directory and add your OpenAI API key:

    ```env
    OPEN_AI_API_KEY=your-api-key
    ```

### Usage

1. Run the demo:

    ```bash
    node index.js
    ```

2. Enter your messages when prompted and observe the model-generated responses.

## Customization

Feel free to customize the code according to your fine-tuning needs or experiment with different prompt structures for optimal results.

## Contributing

We welcome contributions from the community! If you find any issues or have suggestions, please open an issue or submit a pull request. 
