FORMATWIZARD – SETUP GUIDE

Overview

This guide explains how to configure and run FormatWizard using n8n and Google Drive.

Prerequisites

Ensure you have:

- n8n installed and running.
- A Google account with access to Google Drive.
- Google Drive credentials configured in n8n.
- Required file conversion integrations configured in the workflow.
- The FormatWizard workflow imported or created in n8n.

1. Configure Google Drive

Connect your Google Drive account to n8n.

Verify that the connected account has permission to:
- Access the required storage location.
- Upload converted files.
- Update file information.
- Configure file-sharing permissions where required.

2. Configure the n8n Form

Open the FormatWizard workflow.

Verify that the form includes:

- A file upload field.
- A target format selection field.
- Appropriate submission settings.

The form should allow users to upload a file and select the desired output format.

3. Configure Conversion Processing

Verify that the workflow contains the required conversion paths.

Check that:

- Uploaded files are received correctly.
- The source file format is identified.
- The selected target format is validated.
- The appropriate conversion path is executed.
- The converted output is handled correctly.
- Scanned PDF files follow their dedicated processing path.

4. Configure Google Drive Operations

Verify the Google Drive nodes used by the workflow.

Ensure that:
- The correct Drive account is connected.
- The destination location is configured.
- Converted files are handled correctly.
- File updates and sharing operations use the intended settings.

5. Run the Workflow

1. Start n8n.
2. Open the FormatWizard form.
3. Upload a supported file.
4. Select the desired target format.
5. Submit the form.
6. Allow the workflow to complete.
7. Verify the converted output.
8. Check the corresponding Google Drive file.

Troubleshooting

Form Submission Failure

- Verify the form configuration.
- Check that a file has been uploaded.
- Confirm that the target format is selected.

Conversion Failure

- Verify the source file is valid.
- Confirm that the selected conversion path is configured.
- Inspect the relevant conversion node's execution output.

Google Drive Error

- Verify Google Drive credentials.
- Check file and folder permissions.
- Confirm the destination configuration.

Scanned PDF Processing Issue

- Verify that the scanned PDF follows the dedicated processing path.
- Inspect the relevant processing nodes for errors.

Notes

- FormatWizard uses n8n for workflow orchestration.
- Google Drive handles file management.
- Conversion availability depends on the configured conversion paths.
- Exact node settings may vary depending on the workflow configuration.
