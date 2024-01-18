# Field Validator PCF Control

## Overview

The Field Validator PCF Control is a custom control for Microsoft Power Apps that provides real-time validation of input based on a specified regular expression (regex) pattern.

## Features

- Real-time input validation.
- Customizable regex pattern for validation.
- Display of error message for invalid input.
- Easy integration into Microsoft Power Apps.

## Installation

### Prerequisites

Before installing the Field Validator PCF Control, make sure you have the following:

- A Microsoft Power Apps environment.
- Appropriate permissions to add and configure custom controls.

### Steps

1. Download the latest release of the Field Validator PCF Control from the [releases page](https://github.com/Jagadeesan20/PCF-Controls-TS).

2. In your Power Apps environment, navigate to the **Apps** section.

3. Open the app where you want to add the Field Validator PCF Control.

4. Go to the **View** menu and select **Data**.

5. In the data panel, select the entity and the field where you want to use the Field Validator PCF Control.

6. Click on the field to open the property pane.

7. In the property pane, navigate to the **Controls** tab.

8. Click **Add Control** and select **Custom Controls**.

9. Configure the control properties, including the regex pattern and error message.

10. Save and publish your changes.

11. Open the app and test the Field Validator PCF Control in action!

## Configuration

### Properties

- **Field to Validate**: The field in the entity to which the validation should be applied.
- **Regex Pattern**: The regular expression pattern used for validation.
- **Error Message**: Custom error message to display for invalid input.

## Development

### Prerequisites

To modify or build the Field Validator PCF Control, you need the following:

- [Node.js](https://nodejs.org/) installed.
- [Power Apps CLI](https://docs.microsoft.com/powerapps/developer/component-framework/get-powerapps-cli) installed.

### Build and Test

1. Clone the repository: `git clone https://github.com/Jagadeesan20/PCF-Controls-TS`
2. Navigate to the control folder: `cd FieldValidatorControl`
3. Install dependencies: `npm install`
4. Build the control: `npm run build`
5. Test the control locally: `npm start`

