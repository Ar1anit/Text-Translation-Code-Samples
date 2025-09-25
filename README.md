# Text-Translation-Code-Samples

This repository contains code samples for using text translation services in multiple programming languages, including Python, C#, Java, Go, and Node.js. The samples demonstrate how to perform various translation-related tasks such as translating text, detecting language, breaking sentences, transliterating, and using dictionary features.

## Repository Structure

- **Python-Code-Samples/**: Python examples for translation tasks
- **C#-Code-Samples/**: C# examples for translation tasks
- **Java-Code-Samples/**: Java examples for translation tasks
- **GO-Code-Samples/**: Go examples for translation tasks
- **NodeJS-Code-Samples/**: Node.js examples for translation tasks
- **Text-Translation-AAD/**: C# samples using Azure Active Directory authentication
- **Text-Translation-AzureToken/**: C# samples using Azure Token authentication

## Features Demonstrated
- Text translation
- Language detection
- Sentence breaking
- Transliteration
- Dictionary lookup and examples

## Getting Started (Python Example)

1. **Install Python 3.7+**
2. Navigate to the `Python-Code-Samples` folder:
   ```powershell
   cd Python-Code-Samples
   ```
3. (Optional) Create and activate a virtual environment:
   ```powershell
   python -m venv venv
   .\venv\Scripts\Activate
   ```
4. **Install dependencies:**
   ```powershell
   pip install -r requirements.txt
   ```
5. **Run a sample script:**
   ```powershell
   python Translate.py
   ```

## Configuration

Most samples require an Azure Translator resource key and endpoint. Set these as environment variables or directly in the scripts as described in the code comments.

## License

See `LICENSE.txt` for license information.
