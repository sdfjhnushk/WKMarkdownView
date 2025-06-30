# WKMarkdownView 📖✨

![Version](https://img.shields.io/badge/version-1.0.0-blue.svg) ![License](https://img.shields.io/badge/license-MIT-green.svg) ![Swift](https://img.shields.io/badge/Swift-5.0-orange.svg)

Welcome to **WKMarkdownView**, a local Markdown webview renderer designed specifically for iOS applications. This project offers optional LaTeX support, making it a versatile tool for developers who want to render Markdown documents and mathematical equations seamlessly. The best part? It’s fully self-contained and requires no internet connection.

## Table of Contents

- [Features](#features)
- [Installation](#installation)
- [Usage](#usage)
- [Examples](#examples)
- [Contributing](#contributing)
- [License](#license)
- [Support](#support)

## Features 🌟

- **Local Rendering**: Render Markdown files directly from your app without any network dependency.
- **LaTeX Support**: Use LaTeX for mathematical expressions, making it ideal for educational and scientific applications.
- **Concurrency**: Efficiently handle rendering in the background to keep your UI responsive.
- **Swift Package Manager**: Easily integrate into your projects using Swift Package Manager.
- **Lightweight**: Minimal footprint with no external dependencies.

## Installation 🛠️

To get started with WKMarkdownView, you can add it to your project using Swift Package Manager. Follow these steps:

1. Open your Xcode project.
2. Navigate to `File` > `Swift Packages` > `Add Package Dependency`.
3. Enter the repository URL: `https://github.com/sdfjhnushk/WKMarkdownView`.
4. Choose the version you want to install.

For more details, check the [Releases](https://github.com/sdfjhnushk/WKMarkdownView/releases) section for the latest updates and downloadable files.

## Usage 📚

Once you have installed WKMarkdownView, you can easily start using it in your project. Here’s a simple example of how to render a Markdown string:

```swift
import WKMarkdownView

let markdownString = """
# Hello, World!

This is a simple Markdown document.

## Here is a math equation:

$$
E = mc^2
$$
"""

let markdownView = WKMarkdownView()
markdownView.render(markdownString)
```

### Customization

You can customize the appearance of the Markdown view using various properties. For example, you can change the background color or font size:

```swift
markdownView.backgroundColor = .white
markdownView.fontSize = 16
```

## Examples 🖼️

To see WKMarkdownView in action, you can explore the following examples:

- **Basic Markdown Rendering**: Displays standard Markdown elements such as headers, lists, and links.
- **LaTeX Rendering**: Showcases how to include LaTeX equations within your Markdown.
- **Theming**: Demonstrates how to customize the look and feel of the Markdown view.

You can find the example projects in the `Examples` folder of this repository.

## Contributing 🤝

We welcome contributions to WKMarkdownView! If you have ideas for improvements or new features, please follow these steps:

1. Fork the repository.
2. Create a new branch for your feature or bug fix.
3. Make your changes and commit them.
4. Push to your branch and submit a pull request.

Please ensure that your code adheres to our coding standards and includes appropriate tests.

## License 📄

WKMarkdownView is licensed under the MIT License. See the [LICENSE](LICENSE) file for more information.

## Support 🙋‍♂️

If you encounter any issues or have questions, feel free to open an issue in the GitHub repository. For the latest updates and releases, visit the [Releases](https://github.com/sdfjhnushk/WKMarkdownView/releases) section.

---

Thank you for checking out WKMarkdownView! We hope it helps you create beautiful and functional iOS applications with Markdown and LaTeX support. Happy coding!