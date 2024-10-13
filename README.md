# 🤗 HuggingFace-Compatible Tokenizers

[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](https://opensource.org/licenses/MIT)

A curated collection of Hugging Face-compatible `tokenizer.json` files for various Large Language Models (LLMs) 🤖.

## 🌟 Overview

This repository houses a collection of `tokenizer.json` files compatible with Hugging Face's tokenizer ecosystem. These files enable seamless integration with various LLMs, facilitating natural language processing tasks across different programming environments.

## 🛠 Usage

You can utilize these tokenizers in your projects using any Hugging Face tokenizer-compatible libraries. Here are some popular options:

- Python: [tokenizers](https://pypi.org/project/tokenizers/)
- Rust: [tokenizers](https://crates.io/crates/tokenizers)
- JavaScript/TypeScript: [tokenizers](https://www.npmjs.com/package/tokenizers)
- JavaScript/TypeScript (FlexPilot AI): [@flexpilot-ai/tokenizers](https://www.npmjs.com/package/@flexpilot-ai/tokenizers)

## 📂 Available Tokenizers

- mistralai
  - [codestral-22b.json](/mistralai/codestral-22b.json) - [\[Source\]](https://huggingface.co/mistralai/Codestral-22B-v0.1)
- openai
  - [o200k_base.json](/openai/o200k_base.json) - [\[Source\]](https://huggingface.co/Xenova/gpt-4o)
  - [cl100k_base.json](/openai/cl100k_base.json) - [\[Source\]](https://huggingface.co/Xenova/gpt-3.5-turbo)

## 💻 Installation

To use a tokenizer in your project, download the desired `tokenizer.json` file and include it in your project directory. Then, load it using your preferred Hugging Face tokenizer-compatible library.

Example using Python:

```python
from tokenizers import Tokenizer

tokenizer = Tokenizer.from_file("path/to/tokenizer.json")
```

## 🤝 Contributing

Contributions are welcome! If you'd like to add a new tokenizer or improve existing ones:

1. Fork the repository
2. Create a new branch (`git checkout -b feature/new-tokenizer`)
3. Add the new tokenizer file
4. Update the README.md with the new tokenizer information
5. Commit your changes (`git commit -am 'Add new tokenizer: MODEL_NAME'`)
6. Push to the branch (`git push origin feature/new-tokenizer`)
7. Create a new Pull Request

Please ensure that you have the right to distribute the tokenizer files and include proper attribution.

## 📄 License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

---

📣 If you find this repository helpful, please consider giving it a star ⭐️ and sharing it with others!
