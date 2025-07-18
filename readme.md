# PriLabel

A tool for analyzing APK files.

## Executable JAR Package
[executable JAR package]([https://github.com/CybWeea/PriLabel/releases/download/PriLabel/PriLabel.jar](https://github.com/CybWeea/PriLabel/releases/download/JAR/PriLabel.jar))

## Requirements
- Java Runtime Environment (JRE) 8 or later
- Valid OpenAI API key

## Usage
```bash
java -jar -Xmx8096m PriLabel.jar apkPath OpenAiApiKey ModelName
```

## Parameters
- **apkPath**: Path to the APK file to analyze
- **OpenAiApiKey**:	Your OpenAI API key (security-sensitive)
- **ModelName**: Base model to use (e.g., gpt-4o or other OpenAI base models like o3-mini)

## Example
```bash
java -jar -Xmx8096m PriLabel-5352.jar \
  /Users/xxx/Downloads/app.apk \
  sk-xxxxxxxxxxxxxx \
  gpt-4o
```

## Important Notes
#### 🔒 API Key Security:
- We cannot provide our OpenAI API key directly due to security reasons.
- We cannot provide direct access to our fine-tuned model due to OpenAI's restrictions (only model owners can access fine-tuned models).
- You must use your own OpenAI API key and base models (e.g., gpt-4o, o3-mini).
#### 🚀 Model Selection:
- Use OpenAI's base models for analysis. You may choose more powerful models like o3-mini if available under your account.
- Example options: gpt-4o, gpt-4o-mini.
