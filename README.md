# Azure Document Intelligence Form to CSV
## Overview

This repository contains test scripts and sample data to evaluate if **Azure Document Intelligence (DI)** can accurately read and interpret forms containing check marks and put them into csv automatically.

The goal is to verify the capability of Azure DI's prebuilt-layout if it can detect and extract checkbox values from scanned or digital forms.

## Tested contents

**sample-forms/**: Sample form images and PDFs with check marks

> **Note:** The actual form used in this project is proprietary and will **not** be shared publicly. The provided code and tests are optimized specifically for that form’s structure and layout to see if it works without Azure DI finetuning.

## Setup

1. Create an Azure Form Recognizer resource and get the endpoint URL and API key.
2. Install dependencies (Python example):
   ```bash
   pip install azure-ai-formrecognizer

## Conclusion
Since I plan to automate this process with Power Automate in the future—which is both feasible and preferable given the task’s simplicity and lack of complex AI components—I should proceed with fine-tuning and developing a custom extraction model to ensure easier maintenance.
