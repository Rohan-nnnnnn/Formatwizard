FORMATWIZARD – SYSTEM ARCHITECTURE

Overview

FormatWizard is an automated file conversion workflow built with n8n and Google Drive.

The system accepts file uploads through an n8n form, processes the user's selected target format, executes the appropriate conversion path, and manages the resulting file through Google Drive.

System Components

1. n8n Form – User Input

Provides the interface for uploading a file and selecting the desired output format.

2. n8n – Workflow Orchestration

Coordinates form submission, file handling, format validation, conversion processing, and Google Drive operations.

3. File Processing – Input Handling

Receives the uploaded file and prepares it for the appropriate conversion operation.

4. Conversion Processing – Format Transformation

Routes the uploaded file through the configured conversion path based on its source format and selected target format.

A dedicated processing path handles scanned PDF documents.

5. Google Drive – File Management

Handles the converted output through configured file update and sharing operations.

Processing Flow

1. The user opens the FormatWizard form.
2. The user uploads a file.
3. The user selects the desired target format from the available options.
4. The form submits the file and conversion preferences to n8n.
5. n8n receives and processes the submitted information.
6. The workflow identifies the required conversion path.
7. The uploaded file is passed through the appropriate conversion process.
8. Scanned PDF files are handled through their dedicated processing path.
9. The converted output is passed to the Google Drive operations.
10. Google Drive handles the configured file update and sharing operations.

Data Flow

User Form Submission
→ n8n Workflow
→ File and Format Processing
→ Conversion Path
→ Converted Output
→ Google Drive

Technology Stack

- Workflow Automation: n8n
- User Input: n8n Forms
- File Storage: Google Drive
- File Processing: Configured conversion integrations
- Document Handling: Dedicated scanned PDF processing path

Architecture Objective

The architecture separates user input, workflow orchestration, conversion processing, and cloud file management.

This makes FormatWizard a practical example of automating repetitive file conversion tasks through workflow integration.
