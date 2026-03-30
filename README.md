

This repository contains a Spring Boot application that demonstrates the integration of multiple Large Language Models (LLMs) including OpenAI, Anthropic, and Ollama, using the Spring AI library. The project also includes a React-based UI for comparing responses from different models.
This is the learning project.Which helps Programmers to learn about the Spring AI internal workings and how API Hits are Working through the Different LLMs

## Project Structure

```
SpringAIDemo/
├── src/
│   ├── main/
│   │   ├── java/             # backend code
│   │   ├── resources/        # Application properties and static resources
└── ...
```

### UI

the directory named SpringAIFrontend is the ReactBased UI Component/it helps the User to trigger the Request to the SpringAIwithModels 
and prompt to the specific LLMs through the API KEYS and get BAck the response and Render it to the Browser Client

### Important steps to Taken :-

Create the All Required API KEYS by your own using the Official websites below and paste the Keys to the Application.Properties.
Which is in the Spring Backend Contains 

## Features

- Integration with multiple LLM providers:
    - OpenAI (GPT models)
    - Anthropic (Claude models)
    - Ollama (Local models)
- REST API endpoints for interacting with each LLM
- React-based user interface for comparing model responses side-by-side
- Configurable prompts and model parameters

## Prerequisites

- Java 17 or higher
- Maven 3.6 or higher
- Node.js and npm (for the React UI)
- API keys for OpenAI and Anthropic
- Ollama installed locally


### Backend Setup

1. Clone the repository:
   ```bash
   git clone https://github.com/REEGAN444/SpringAI-Exploring-Diff-LLM-Model.git
  
   ```

2. Configure your API keys in `application.properties` or via environment variables:
   ```properties
   spring.ai.openai.api-key=your_openai_key
   spring.ai.anthropic.api-key=your_anthropic_key
   # Other configuration properties...
   ```

3. Build the Spring Boot application:
   ```bash
   mvn clean package -DskipTests
   ```

## Acknowledgements

- [Spring AI](https://spring.io/projects/spring-ai)
- [OpenAI API](https://openai.com/blog/openai-api)
- [Anthropic Claude API](https://www.anthropic.com/product)
- [Ollama](https://ollama.ai/)

