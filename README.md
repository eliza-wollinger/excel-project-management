# Excel Project Management System

A lightweight project management solution built with Microsoft Excel and Office Scripts.

The project combines structured task management with automated visualization, allowing users to organize projects, track progress, monitor deadlines, and generate a dynamic project timeline directly in Excel.

## Overview

This project demonstrates how Excel can be extended beyond traditional spreadsheets to create a simple and automated project management environment.

The workbook provides a structured database for project activities, while Office Scripts automate the generation and formatting of the project timeline.

The solution was designed to remain simple, customizable, and easy to use without requiring additional project management software.

## Features

- Project and task tracking
- Dynamic project timeline
- Automatic timeline generation
- Project-based color identification
- Progress monitoring
- Deadline tracking
- Risk and status visualization
- Structured task database
- Automated formatting with Office Scripts
- Customizable project categories
- Built-in usage guidelines

## Technologies

- Microsoft Excel
- Office Scripts
- TypeScript

## Project Structure

```text
excel-project-management/
│
├── README.md
│
├── excel/
│   └── project_management_public.xlsx
│
└── scripts/
    └── timeline.osts
```

## Workbook Structure

The workbook is organized into three main worksheets.

### Tasks

The main data source of the system.

Users can register and manage project activities, including project information, responsible team members, deadlines, progress, status, and other task-related information.

### Timeline

Provides a visual representation of project activities and their duration.

The timeline is automatically generated and formatted using Office Scripts based on the information available in the Tasks worksheet.

### Guideline

Contains instructions for using and maintaining the workbook, including the expected data structure and general workflow.

## How It Works

1. Project information is registered in the `Tasks` worksheet.
2. Each activity is associated with a project, responsible person, dates, progress, and status.
3. The Office Script reads the task database.
4. The script processes the project information and applies the visualization rules.
5. The `Timeline` worksheet is automatically generated or updated.
6. Project colors, progress indicators, and status information provide a visual overview of the portfolio.

## Requirements

To use the automation features, you will need:

- Microsoft Excel for the Web
- Microsoft 365 account with Office Scripts support

The workbook itself can still be opened in the desktop version of Excel, but Office Scripts are executed through supported Microsoft 365 environments.

## Getting Started

1. Download `project_management_public.xlsx`.
2. Open the workbook in Microsoft Excel.
3. Open the `Tasks` worksheet.
4. Replace the sample data with your own projects and activities.
5. Add the Office Script available in the `scripts` directory to your Office Scripts environment.
6. Run the script to generate or update the project visualization.

## Customization

The project was designed to be adaptable.

Project categories and their corresponding colors can be modified directly in the Office Script.

Additional fields, visualization rules, and automation logic can also be implemented according to the requirements of each project environment.

## Sample Data

All information included in the public workbook is fictional and provided exclusively for demonstration purposes.

Names, projects, activities, dates, and other records do not represent real individuals, organizations, clients, or business operations.

## Privacy and Confidentiality

This repository contains a sanitized demonstration version of the project.

No confidential company information, customer information, credentials, internal URLs, proprietary datasets, or personal data are intentionally included.

## Disclaimer

This project is provided as an independent portfolio.

It is not an official Microsoft product and is not affiliated with or endorsed by Microsoft.

Microsoft Excel, Microsoft 365, and Office Scripts are trademarks or products of Microsoft Corporation.

## License

See the `LICENSE` file for information about permitted use, modification, and distribution.