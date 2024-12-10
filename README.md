# Critical-AI 🔍

Critical-AI is an AI-powered news analysis tool that helps users understand news from multiple perspectives. Users can paste multiple article URLs to get a critical, balanced analysis of the same story from different sources. It also provides a news digest for any topic or category. It does this using local LLMs for privacy and efficiency.

## Features 🌟

### Current Features
- **Article Comparison**: Paste multiple article URLs to get a critical, balanced analysis of the same story from different sources
- **News Digest**: Get personalized news digests for specific topics or categories
- **Local Processing**: All analysis runs locally using LM Studio, ensuring privacy and data control
- **Sentiment Analysis**: Understand the tone and bias of different news sources
- **Markdown Support**: Clean, formatted output for better readability

### Planned Features 🚀
- Model Selection: Choose from different LLMs/SLMs for analysis depending on your hardware
- Comprehensive Daily Summaries
- Custom Analysis Parameters
- Browser Extension Integration
- RSS Feed Support
- Email Digest Service

## Tech Stack 💻

- **Backend**: Python/Flask
- **Frontend**: HTML, CSS, JavaScript
- **LLM Integration**: LM Studio API
- **News Data**: NewsAPI
- **Additional Libraries**:
  - `requests` for API handling
  - `markdown` for text formatting
  - Additional dependencies in `requirements.txt`

## Prerequisites 📋

- Python 3.x
- LM Studio with compatible models (tested with llama-3.2-3b-qnn)
- Hardware capable of running LLMs locally
- NewsAPI key
- LM Studio API endpoint

## Installation 🛠️

1. Clone the repository
```
git clone <repo-url>
cd Critical-AI
```

2. Install dependencies
```
pip install -r requirements.txt
```

3. Start LM Studio and run the model you want to use.

4. Update the `config.py` file with your LM Studio API endpoint and NewsAPI key.

5. Run the app
```
python app.py
```

6. Open the app in your browser at the specified url.

## Limitations ⚠️

- Analysis quality depends on the LLM/SLM model used
- Requires sufficient hardware for local LLM processing
- News API rate limits may apply
- Currently supports English articles only

## Contributing 🤝

Contributions are welcome! Here's how you can help:

1. Fork the repository
2. Create a feature branch (`git checkout -b feature/AmazingFeature`)
3. Commit your changes (`git commit -m 'Add some AmazingFeature'`)
4. Push to the branch (`git push origin feature/AmazingFeature`)
5. Open a Pull Request

### Feature Requests 💡
Have an idea for a new feature? Open an issue with the tag `feature request` and describe:
- The feature you'd like to see
- Why it would be useful
- Any implementation ideas you have

## License 📄

This project is licensed under the MIT License.

## Acknowledgments 👏

- LM Studio for local LLM capabilities
- NewsAPI for news data access
- All contributors and users of Critical-AI