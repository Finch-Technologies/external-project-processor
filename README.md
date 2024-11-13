# Bank Statement Processor Project

## Overview

This project is a statement parser designed to extract account and transactional information from bank statements. The parser is controlled via three API endpoints. Additionally, there is an optional bonus task to build a small UI component for statement uploads.

The purpose of this project is to test coding skills and problem-solving abilities. Developers are encouraged to be creative.

*This project will require a database/retention functionality to retrieve the account and transactional information.*

## API Endpoints

1. **Upload Statement**
    - **Endpoint**: `/statement`
    - **Method**: `POST`
    - **Description**: Upload a bank statement.

2. **Get Status**
    - **Endpoint**: `/account`
    - **Method**: `GET`
    - **Description**: Return the statement account information.

3. **Stop Scraping**
    - **Endpoint**: `/transactions`
    - **Method**: `GET`
    - **Description**: Return the statement transactional information.

*Developers can define the specifics of these endpoints based on their design choices.*

## Input and Output Guidelines

- **input.json**: Provides a guideline for the API server functionality and commands. Use it as a reference for expected input formats.
- **output.json**: Serves as a guideline for the expected output from the scraper.
- **./files**: Contains the pdf files that you can use to build your system.

## Operation

1. Upload one of the files to your server.
2. Call GET account for the account information.
3. Call GET transactions for the transactional information.

## Bonus Task (Optional)

Implement a small frontend application for file upload and to display the parsed information in a table.

## Getting Started

1. **Set Up Environment**: Install necessary dependencies and configure the development environment.
2. **Run API Server**: Start the server to make the API endpoints available.
3. **Use Endpoints**: Interact with the application through the provided API endpoints.
4. **UI Upload (Optional)**: Implement the bonus task and build a single page UI for the statement upload.

## Outcome

You should create a private repository for the project and share access with Finch Technologies. The repository must include a README file detailing the setup instructions and how to interact with the API endpoints. The README should also outline any specific configurations needed to run the project, along with instructions for running the optional UI task if implemented.

## Purpose

This project aims to showcase coding proficiency and problem-solving skills. Creativity is encouraged to develop an effective algorithm to parse the documents. Don't worry if you can't implement all of the functionality. We will be assessing your coding ability and your approach to problem solving.

---
