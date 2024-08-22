
<p align="center">
    <br/>
    <picture> 
        <source media="(prefers-color-scheme: dark)" srcset="https://raw.githubusercontent.com/mohankumarelec/tokenizer.js/main/assets/dark-logo.svg" width="500" style="max-width: 100%;">
        <source media="(prefers-color-scheme: light)" srcset="https://raw.githubusercontent.com/mohankumarelec/tokenizer.js/main/assets/light-logo.svg" width="500" style="max-width: 100%;">
        <img alt="transformers.js javascript library logo" src="https://raw.githubusercontent.com/mohankumarelec/tokenizer.js/main/assets/light-logo.svg" width="500" style="max-width: 100%;">
    </picture>
    <br/>
</p>

<p align="center">
    <a href="https://www.npmjs.com/package/@mohankumarelec/tokenizer.js"><img alt="NPM" src="https://img.shields.io/npm/v/@mohankumarelec/tokenizer.js"></a>
    <a href="https://www.npmjs.com/package/@mohankumarelec/tokenizer.js"><img alt="NPM Downloads" src="https://img.shields.io/npm/dw/@mohankumarelec/tokenizer.js"></a>
    <a href="https://www.jsdelivr.com/package/npm/@mohankumarelec/tokenizer.js"><img alt="jsDelivr Hits" src="https://img.shields.io/jsdelivr/npm/hw/@mohankumarelec/tokenizer.js"></a>
    <a href="https://github.com/mohankumarelec/tokenizer.js/blob/main/LICENSE"><img alt="License" src="https://img.shields.io/github/license/mohankumarelec/tokenizer.js?color=blue"></a>
    <a href="https://huggingface.co/docs/transformers.js/index"><img alt="Documentation" src="https://img.shields.io/website/http/huggingface.co/docs/transformers.js/index.svg?down_color=red&down_message=offline&up_message=online"></a>
</p>

# Hugging Face Tokenizers for JavaScript

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
npm install @mohankumarelec/tokenizer.js
```

## Usage

Here is a basic example of how to use the tokenizer:

```javascript
import { AutoTokenizer } from "./tokenizers.js";
const tokenizer = await AutoTokenizer.from_pretrained('Xenova/bert-base-uncased');
const { input_ids } = await tokenizer('I love tokenizer.js!');
```

## Development

### Building the Project

To build the project, run:

```sh
npm run build
```

### Running in Development Mode

To start the development server, run:

```sh
npm run dev
```

### Generating Type Definitions

To generate type definitions, run:

```sh
npm run typegen
```

### Issue Tracking

If you encounter any issues, please report them [here](https://github.com/mohankumarelec/tokenizer.js/issues).

## License

This project is licensed under the Apache-2.0 License. See the [`LICENSE`](https://github.com/mohankumarelec/hf-tokenizer.js/blob/main/LICENSE) file for details.
