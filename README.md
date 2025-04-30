# Website Downloader with HTML to Markdown Conversion

A powerful tool to download entire websites and convert HTML content to Markdown format while preserving all resources and structure.

## Features

- **Batch Downloading**: Download multiple web pages at once
- **HTML to Markdown Conversion**: Convert downloaded HTML files to clean Markdown
- **File Management**: Organize and manage downloaded files
- **Resource Preservation**: Maintains all CSS, JavaScript and media files

## Installation

1. Clone this repository:
```bash
git clone https://github.com/your-repo/website-downloader.git
```
2. Install dependencies:
```bash
npm install
```
3. Start the development server:
```bash
npm run dev
```

## Usage

1. Enter the target website URL in the download page
2. Click "Download" to start downloading
3. Use the "Convert to Markdown" button to transform HTML files
4. Manage your downloaded files through the file list interface

## Examples

### Download a single page
```javascript
// Example API call
await downloadPage('https://example.com/page1');
```

### Convert HTML to Markdown
```javascript
// Convert all downloaded HTML files to Markdown
await convertAllToMarkdown();
```

## Contributing

Pull requests are welcome. For major changes, please open an issue first to discuss what you would like to change.

## License

[Apache License 2.0](https://www.apache.org/licenses/LICENSE-2.0)

Copyright [yyyy] [name of copyright owner]

Licensed under the Apache License, Version 2.0 (the "License");
you may not use this file except in compliance with the License.
You may obtain a copy of the License at

    http://www.apache.org/licenses/LICENSE-2.0

Unless required by applicable law or agreed to in writing, software
distributed under the License is distributed on an "AS IS" BASIS,
WITHOUT WARRANTIES OR CONDITIONS OF ANY KIND, either express or implied.
See the License for the specific language governing permissions and
limitations under the License.
