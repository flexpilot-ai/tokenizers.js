
<p align="center">
    <br/>
    <picture> 
        <source media="(prefers-color-scheme: dark)" srcset="https://raw.githubusercontent.com/flexpilot-ai/tokenizers.js/main/assets/dark-logo.svg" width="500" style="max-width: 100%;">
        <source media="(prefers-color-scheme: light)" srcset="https://raw.githubusercontent.com/flexpilot-ai/tokenizers.js/main/assets/light-logo.svg" width="500" style="max-width: 100%;">
        <img alt="transformers.js javascript library logo" src="https://raw.githubusercontent.com/flexpilot-ai/tokenizers.js/main/assets/light-logo.svg" width="500" style="max-width: 100%;">
    </picture>
    <br/>
</p>

<p align="center">
    <a href="https://www.npmjs.com/package/@flexpilot-ai/tokenizers.js"><img alt="NPM" src="https://img.shields.io/npm/v/@flexpilot-ai/tokenizers.js"></a>
    <a href="https://github.com/flexpilot-ai/tokenizers.js/blob/main/LICENSE"><img alt="License" src="https://img.shields.io/github/license/flexpilot-ai/tokenizers.js?color=blue"></a>
    <a href="https://huggingface.co/docs/transformers.js/index"><img alt="Documentation" src="https://img.shields.io/website/http/huggingface.co/docs/transformers.js/index.svg?down_color=red&down_message=offline&up_message=online"></a>
</p>

This repository provides a lightweight, pure JavaScript implementation of Hugging Face's tokenizers. It is based on the tokenizers available in the transformers.js library. By removing dependencies such as ONNX and others, this library focuses solely on efficient text tokenization, offering a streamlined solution without the overhead of additional dependencies.

This project is ideal for those who require a simple and efficient way to tokenize text data using Hugging Face's tokenizers in JavaScript environments, without the need for heavy or unnecessary components.

## Table of Contents

- [Installation](#installation)
- [Usage](#usage)
- [Development](#development)
- [Contributing](#contributing)
- [License](#license)

## Installation

You can install the package via npm:

```sh
npm install @flexpilot-ai/tokenizers.js
```

## Usage

Here is a basic example of how to use the tokenizer:

```javascript
import { AutoTokenizer } from "./tokenizers.js";
const tokenizer = await AutoTokenizer.from_pretrained('Xenova/bert-base-uncased');
const { input_ids } = await tokenizer('I love tokenizers.js!');
```

## Issue Tracking

If you encounter any issues, please report them [here](https://github.com/flexpilot-ai/tokenizers.js/issues).

## License

This project is licensed under the Apache-2.0 License. See the [`LICENSE`](https://github.com/flexpilot-ai/tokenizers.js/blob/main/LICENSE) file for details.
