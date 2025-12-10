# Salesforce File Extractor - Distribution Package

This is a standalone Windows executable that extracts files from Salesforce.

## System Requirements

- Windows 7 or later
- Internet connection
- No Python installation required

## Usage

1. Double-click `SalesforceFileExtractor.exe` to run
2. Choose authentication method (Username/Password or Session ID)
3. Enter your Salesforce credentials
4. Select output directory for downloaded files
5. Click "Start Download"

## Authentication

- **Username/Password**: Use your Salesforce login credentials (NOT TESTED)
- **Session ID**: Use if you have an existing Salesforce session token (TESTED AND WORKS)

## Troubleshooting

- If Windows Defender blocks the file: Click "More info" → "Run anyway"
- If antivirus flags it: This is a false positive. Add an exception if needed
- First run may be slow: This is normal as files are extracted

## Support

For issues or questions, contact the developer.

