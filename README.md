# CodeObfuscator

***You can use the tool at  https://zhoufuz.github.io/CodeObfuscator/CodeObfu2.0.html***

**Code Obfuscator Web Tool**  
This webpage provides a multi-language code obfuscation tool designed to protect source code from unauthorized viewing or copying. Featuring a modern dark-themed interface with gradient backgrounds and responsive card layouts, it supports seven programming languages: HTML, JavaScript, Python, Lua, Roblox Lua, C++, and JSON.

The interface is divided into two main sections:  
1. **Input Panel** (left): Users select a programming language via color-coded buttons, paste source code into a text editor (with sample code available), and access language-specific obfuscation information.  
2. **Output Panel** (right): Displays obfuscated results with options to copy, test, or download the processed code. A loading animation appears during the 2-second obfuscation process.

Key technical features include:  
- Language-specific obfuscation techniques: Base64 encoding for HTML/Python, hexadecimal conversion for JavaScript/Lua, ASCII decimal encoding for Roblox Lua, and character-shifting for C++.  
- Version watermarking in outputs for traceability  
- One-click testing for HTML/JavaScript results  
- File export with proper extensions (.html, .js, .py, etc.)  
- Responsive design adapting to mobile devices

The tool includes detailed documentation explaining each obfuscation method's approach and limitations, noting that while it deters casual copying, it doesn't provide absolute security. A persistent footer disclaimer highlights its educational purpose.

JavaScript powers the interactive elements:  
- Dynamic language switching updates examples and techniques  
- Notification system for copy operations  
- Simulated processing delay for realistic user feedback  
- Example code snippets for each language  

The design utilizes FontAwesome icons, Google Fonts (Poppins/Roboto Mono), CSS variables for consistent theming, and modern UI elements like blurred card backgrounds with subtle hover effects. Obfuscation preserves functionality while transforming code readability, though performance/SEO impacts are noted for HTML implementation.
