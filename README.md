# AWS Mistral Tavily Etheroi

A project that integrates AWS services with Mistral AI and Tavily search to create an enhanced information retrieval and processing system.

## Project Overview

This project leverages the power of:
- **AWS Services**: For cloud infrastructure and serverless computing
- **Mistral AI**: For advanced language model capabilities
- **Tavily Search**: For efficient web search and information retrieval

## Getting Started

### Prerequisites

- Python 3.8+
- AWS Account with appropriate permissions
- Tavily API key
- Mistral AI API key

### Installation

1. Clone the repository:
   ```bash
   git clone <repository-url>
   cd aws-mistral-tavily-etheroi
   ```

2. Create and activate a virtual environment:
   ```bash
   python -m venv .venv
   source .venv/bin/activate  # On Windows: .venv\Scripts\activate
   ```

3. Install the required packages:
   ```bash
   pip install -r requirements.txt
   ```

4. Set up your environment variables:
   ```bash
   cp .env.example .env
   # Edit .env with your credentials
   ```

## Usage

Open and run the Jupyter notebook `aws-etheroi.ipynb` to explore the project's functionality.

```bash
jupyter notebook aws-etheroi.ipynb
```

## Project Structure

- `aws-etheroi.ipynb`: Main Jupyter notebook containing the project code
- `.gitignore`: Specifies intentionally untracked files to ignore
- `LICENSE`: Project license
- `requirements.txt`: Project dependencies

## Contributing

Contributions are welcome! Please feel free to submit a Pull Request.

## License

This project is licensed under the terms of the [MIT License](LICENSE).
