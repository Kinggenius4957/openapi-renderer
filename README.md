# OpenAPI Renderer: Simple OpenAPI Spec to HTML Renderer 🌐✨

![OpenAPI Renderer](https://img.shields.io/badge/OpenAPI%20Renderer-v1.0-blue)

## Table of Contents
- [Overview](#overview)
- [Features](#features)
- [Installation](#installation)
- [Usage](#usage)
- [Examples](#examples)
- [Contributing](#contributing)
- [License](#license)
- [Support](#support)

## Overview
OpenAPI Renderer is a straightforward tool designed to convert OpenAPI specifications into visually appealing HTML documents. With this tool, developers can easily share and present their API specifications in a user-friendly format. Whether you are working on a small project or a large-scale API, OpenAPI Renderer helps streamline the documentation process.

## Features
- **Simple Conversion**: Transform OpenAPI specs to HTML with minimal effort.
- **User-Friendly Interface**: Generate clean and readable documentation.
- **Customizable Templates**: Modify the appearance to match your branding.
- **Lightweight**: Quick to set up and use without unnecessary bloat.
- **Markdown Support**: Integrate Markdown for enhanced documentation.

## Installation
To get started with OpenAPI Renderer, download the latest release from the [Releases section](https://github.com/Kinggenius4957/openapi-renderer/releases). Once downloaded, execute the necessary files to set up the renderer on your system.

```bash
# Example command to run the renderer
./openapi-renderer your-openapi-spec.yaml
```

## Usage
Using OpenAPI Renderer is straightforward. After installation, you can convert your OpenAPI specification by following these steps:

1. **Prepare Your OpenAPI Spec**: Ensure your OpenAPI spec is in YAML or JSON format.
2. **Run the Renderer**: Execute the renderer with your spec file as an argument.

```bash
# Command to render the OpenAPI spec
./openapi-renderer path/to/your-spec.yaml
```

3. **View the Output**: The renderer will generate an HTML file that you can open in any web browser.

## Examples
Here are some examples to help you understand how to use OpenAPI Renderer effectively.

### Example 1: Basic Usage
Assuming you have a file named `api-spec.yaml`, you can render it as follows:

```bash
./openapi-renderer api-spec.yaml
```

This command will create an `index.html` file in the same directory, which you can open to view your API documentation.

### Example 2: Custom Template
If you want to use a custom template, specify the template path when running the command:

```bash
./openapi-renderer -t path/to/template api-spec.yaml
```

### Example 3: Markdown Integration
To include Markdown content in your OpenAPI spec, ensure you follow the Markdown syntax within your descriptions. The renderer will convert it into HTML automatically.

## Contributing
We welcome contributions to OpenAPI Renderer. If you would like to contribute, please follow these steps:

1. Fork the repository.
2. Create a new branch for your feature or bug fix.
3. Make your changes and commit them.
4. Push your branch and create a pull request.

Please ensure your code adheres to our coding standards and includes appropriate tests.

## License
OpenAPI Renderer is licensed under the MIT License. See the [LICENSE](LICENSE) file for more details.

## Support
For any issues or questions, please check the [Releases section](https://github.com/Kinggenius4957/openapi-renderer/releases) or open an issue in the repository. We appreciate your feedback and will do our best to assist you.

---

Feel free to explore the OpenAPI Renderer and enhance your API documentation process. Happy coding!