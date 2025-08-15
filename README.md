# ChatGPT Test with GitHub Actions

This repository contains a GitHub Actions workflow that connects to the OpenAI API (ChatGPT) and runs a simple prompt.

## How it works
- You store your OpenAI API key as a GitHub Actions secret.
- The workflow runs in GitHub’s cloud and calls ChatGPT using the OpenAI API.
- ChatGPT’s response is shown in the Actions log.

## Steps to try it
1. Add your OpenAI API key as a secret called `OPENAI_API_KEY`.
2. Run the workflow from the Actions tab.

## Notes
- Keep your API key private — never commit it into code.
- This repo is for testing only.
