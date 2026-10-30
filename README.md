# FormatWizard – Automated File Conversion System

FormatWizard is an automated file conversion system built with **n8n and Google Drive**. It allows users to upload a file through an n8n form, select a desired output format, and automate the conversion process.

The workflow handles file input, format selection, conversion, and Google Drive file management, reducing repetitive manual document conversion tasks.

## Features

- **Form-Based File Upload:** Accepts files through an n8n form.
- **Target Format Selection:** Allows users to choose from seven supported target formats.
- **Automated Conversion:** Processes files according to the selected output format.
- **Multiple Conversion Paths:** Supports different source and target format combinations.
- **Google Drive Integration:** Manages converted files through Google Drive.
- **Automated File Handling:** Updates and organizes files after conversion.
- **Scanned PDF Handling:** Includes a separate handling path for scanned PDF documents.

## Technology Stack

| Technology | Purpose |
|---|---|
| n8n | Workflow automation and orchestration |
| Google Drive | File storage and management |
| n8n Forms | File upload and target format selection |
| Conversion Services | File format conversion |

## Workflow

1. The user opens the n8n form.
2. The user uploads a file.
3. The user selects the desired target format.
4. n8n receives the submitted file and conversion preferences.
5. The workflow identifies the required conversion path.
6. The file is processed using the configured conversion mechanism.
7. The converted output is handled by the workflow.
8. Google Drive is updated with the converted file.

## Supported Conversions

FormatWizard supports seven target format options through its conversion workflow.

Available conversions depend on the selected source file format and target format.

## Setup Requirements

Before running FormatWizard, ensure you have:

- n8n installed and running.
- Google Drive credentials configured in n8n.
- The required conversion services or processing integrations configured.
- The FormatWizard workflow imported or created in n8n.
- The required Google Drive storage location configured.

## How to Use

1. Open the FormatWizard form.
2. Upload the file you want to convert.
3. Select the desired output format.
4. Submit the form.
5. Allow the workflow to process the conversion.
6. Access the converted file through the configured Google Drive location.

## Project Objective

The objective of FormatWizard is to demonstrate how workflow automation can simplify file conversion, reduce repetitive manual operations, and integrate document processing with cloud storage.

## Author

**Rohan Narlawar**

- GitHub: [Rohan-nnnnnn](https://github.com/Rohan-nnnnnn)
- LinkedIn: [linkedin.com/in/rohan-narlawar-149291354](https://www.linkedin.com/in/rohan-narlawar-149291354)
- Email: [rohannarlawar31@gmail.com](mailto:rohannarlawar31@gmail.com)
