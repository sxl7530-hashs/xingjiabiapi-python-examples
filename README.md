# xingjiabiapi-python-examples

Python examples for Claude/GPT/Gemini API via xingjiabiapi.org

## 🚀 Quick Start

```python
import anthropic

client = anthropic.Anthropic(
    api_key="sk-YOUR_KEY",
    base_url="https://xingjiabiapi.org/v1"
)

message = client.messages.create(
    model="claude-opus-4-6",
    max_tokens=1024,
    messages=[{"role": "user", "content": "Hello"}]
)
print(message.content[0].text)
```

## 📦 Installation

```bash
pip install anthropic
```

## 🔑 Get API Key

Visit [xingjiabiapi.org](https://xingjiabiapi.org) to get your API key.

**Price Comparison:**
- Official Claude Opus 4.6: $15/M input, $75/M output
- xingjiabiapi.org: ¥31.50/M input, ¥157.50/M output (48% cheaper)

## 📞 Contact

- Website: https://xingjiabiapi.org
- WeChat: malimalihongbebe
- Email: xingjiabiapi@163.com

## 📄 License

MIT
