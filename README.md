# AI-Powered Newsletter Generator with CrewAI

An automated newsletter generation system that uses CrewAI to research, analyze, and compile the latest AI news into a well-formatted markdown newsletter.

## 🚀 Features

- Automated news gathering using Serper API
- AI-powered analysis of trending AI topics
- Beautiful markdown output
- Configurable agents for different roles
- Support for Google's Gemini model

## 🛠️ Prerequisites

- Python 3.8+
- [UV](https://github.com/astral-sh/uv) package manager
- Google API key with access to Gemini models
- Serper API key for news search

## 🚀 Quick Start

### 1. Clone the repository
```bash
git clone <your-repo-url>
cd crewai-agent-demo
```

2. Set up environment variables:
```bash
cp .env.example .env
```

3. Create and activate a virtual environment
```bash
python -m venv .venv
source .venv/bin/activate
```

4. Install dependencies:
```bash
uv pip install -r requirements.txt
```

5. Create a .env file and add your API key
```bash
GOOGLE_API_KEY=your_google_api_key_here
SERPER_API_KEY=your_serper_api_key_here
```

6. Run the script:
```bash
python crew.py
```

# Updating Dependencies
```bash
uv pip install -r requirements.txt --upgrade
```
