# Real Estate Web Scraping Project

## Overview
This project is an automated web scraping solution built using UiPath to extract data from real estate websites. The automation process is designed to collect property information efficiently and systematically.

## Technical Details

### Project Specifications
- **Project Name**: RealStateScrapping
- **Studio Version**: 19.12.0.61
- **Framework**: Legacy
- **Expression Language**: VisualBasic

### Dependencies
- UiPath.Excel.Activities (2.8.0-preview)
- UiPath.Mail.Activities (1.8.0-preview)
- UiPath.System.Activities (19.12.0-preview)
- UiPath.UIAutomation.Activities (20.4.1)

### Runtime Configuration
- **Execution Type**: Workflow
- **Mode**: Unattended
- **User Interaction**: Required
- **Pausable**: Yes
- **Auto Dispose**: No
- **Persistence Support**: No

## Setup and Installation

1. Clone this repository:
```bash
git clone https://github.com/AishwaryaBhargava/Data-Scrapping-from-Real-estate-website.git
```

2. Open the project in UiPath Studio (version 19.12.0 or compatible)
3. Ensure all dependencies are properly restored
4. Configure any necessary credentials or settings
5. Run the Main.xaml workflow

## Project Structure
- `Main.xaml`: Primary workflow entry point
- `project.json`: Project configuration and dependency definitions

## Features
- Automated web scraping of real estate data
- Excel integration for data export
- Email functionality for notifications/reports
- System and UI automation capabilities

## Requirements
- UiPath Studio (19.12.0 or later)
- .NET Framework (Legacy support)
- Internet connection for web scraping

## Usage
1. Open the project in UiPath Studio
2. Configure any necessary parameters or settings
3. Execute the Main.xaml workflow
4. Retrieved data will be processed according to the workflow configuration

## Privacy and Security Notes
- The project is configured to exclude logging of private data and passwords
- Ensure compliance with the target website's terms of service and robots.txt
- Review and adjust the data collection settings as needed

## Contributing
Contributions are welcome! Please feel free to submit a Pull Request.
