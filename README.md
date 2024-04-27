# HTML File Reuse Example

This repository demonstrates how to store HTML files as artifacts in a test pipeline and reuse them in a deployment pipeline using GitHub Actions.

## Workflow Description

The GitHub Actions workflow defined in this repository consists of the following steps:

1. **Checkout code:** This step checks out the code from the repository using the `actions/checkout` action.

2. **Run tests and generate HTML:** This step runs tests and generates HTML files as part of the test pipeline. Replace the placeholder comment with your actual commands to run tests and generate HTML files.

3. **Upload HTML files as artifacts:** This step uploads the generated HTML files as artifacts using the `actions/upload-artifact` action. The HTML files are stored with the name "html-artifacts" and can be reused in subsequent pipelines.

## Usage

To use this workflow in your project:

1. Copy the contents of the `.github/workflows/main.yml` file into your project's `.github/workflows` directory.

2. Customize the commands in the "Run tests and generate HTML" step to fit your project's requirements.

3. Replace the placeholder comment in the "Run tests and generate HTML" step with your actual commands
