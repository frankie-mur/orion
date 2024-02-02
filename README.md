# Orion 🌌

![Golang](https://img.shields.io/badge/Go-00add8.svg?labelColor=171e21&style=for-the-badge&logo=go)

![Build](https://github.com/kmesiab/orion/actions/workflows/go-build.yml/badge.svg)
![Build](https://github.com/kmesiab/orion/actions/workflows/go-lint.yml/badge.svg)
![Build](https://github.com/kmesiab/orion/actions/workflows/go-test.yml/badge.svg)
[![Go Report Card](https://goreportcard.com/badge/github.com/kmesiab/orion)](https://goreportcard.com/report/github.com/kmesiab/orion)

---

Welcome to Orion 🚀, where elegant design meets powerful AI for transformative
code reviews. Orion leverages advanced Large Language Models (LLMs) to deliver
insightful, detailed code analyses and suggestions 🧠. Our goal is to enhance the
code review process with a blend of aesthetics and intelligence 💡.

![Screenshot](https://github.com/kmesiab/orion/assets/161768/6501c7a5-d49d-41ed-9489-36fa53e0ee3f "Screenshot showing diff view")

## Features 🌟

- **Elegant User Interface** 💻: A clean, intuitive UI that simplifies code
  reviews.
- **AI-Powered Analysis** 🤖: Deep insights and actionable suggestions from
  advanced LLMs.
- **Cross-Platform Support** 📱💻: Desktop and mobile versions for a seamless
  experience.
- **Open Source** ❤️: Contribute and customize to suit your needs.
- **Real-Time Collaboration** 🤝: Streamlined team reviews and feedback.
- **Customizable Settings** ⚙️: Tailor reviews to match your coding standards.

## Getting Started 🚀

### Prerequisites

- Go (vX.X or later)
- Additional dependencies...

### Installation

1. Clone the repository:

   ```bash
   git clone https://github.com/kmesiab/orion.git
   ```

2. Navigate to the project directory:

   ```bash
   cd orion
   ```

3. Install dependencies:

   ```bash
   npm install
   ```

4. Start the server:

   ```bash
   go run server.go
   ```

5. Run the React app:

   ```bash
   npm start
   ```

## Usage 💡

- Instructions on how to use Orion and its features.

### App Configuration 🔨

To configure the app, you can use an `env.json`
file placed in the root project directory.
This file should contain various configuration parameters
necessary for the proper functioning of the application.

#### Usage

Create an env.json file in the root project directory.

Populate the file with the required configuration
parameters following the examples provided.

Save the file.

The application will read the configuration from env.json during runtime.

- Example configuration

```json
{
  "OPENAI_API_KEY": "some_secret_key",
  "CONTEXT_TIMEOUT": "10s",
  "IGNORE_FILES": "go.mod,go.sum,config.json"
}
```

#### Configuration Parameters

1. **OPENAI_API_KEY**
   - Set your OpenAI API key in the OpenAIAPIKey field.
     This key is required for the app to interact with the OpenAI API.
2. **CONTEXT_TIMEOUT**
   - Adjust this field to set the timeout
     for context-related operations. The value should be provided in seconds.
3. **IGNORE_FILES**
   - Specify files to be ignored during code review.
     Use a comma-separated list for multiple files.

#### Important Note

Keep your env.json file secure and do not expose sensitive information,
especially the OpenAI API key.

## Contributing 🤝

Contributions are welcome! Please read our contributing guidelines to get
started.

## License 📜

Distributed under the MIT License. See `LICENSE` for more information.

## Contact 📫

Kevin Mesiab - [LinkedIn](https://linkedin.com/in/kmesiab) | twitter: @kmesiab

Frankie Murillo - [LinkedIn](https://www.linkedin.com/in/frankie-murillo) |
twiter(x): @spacescript\_
