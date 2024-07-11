# Page Load Time Chrome Extension

## Introduction

The Page Load Time Chrome extension monitors tab updates and displays page load times in the toolbar. It also provides a detailed breakdown using Navigation Timings.

## Features

- Displays page load times in the toolbar badge.
- Provides a detailed breakdown of the Page Load Time using Navigation Timings.
- Stores performance data in session storage for use in the extension.
- Tracks and reports user interactions (page views, clicks, right-clicks) using Google Analytics.


## Installation

1. Clone the repository.
2. Open Google Chrome and navigate to `chrome://extensions/`.
3. Enable "Developer mode" using the toggle switch in the top-right corner.
4. Click on "Load unpacked" and select the extension directory.

## Usage

1. The extension will automatically monitor tab updates.
2. When a tab finishes loading, the page load time will be displayed in the toolbar badge.
3. Click on the badge to view detailed performance metrics and additional information in the popup.

## Permissions

The extension requires the following permissions:

- **Host Permissions:** To access all URLs for monitoring and managing page load times in the toolbar.
- **Scripting:** To execute scripts within the active tab to collect performance metrics.
- **Storage:** To store performance data and the unique client ID locally on your device.
- **Tabs:** To monitor tab updates and changes in their loading status for real-time update on page load times.

## Privacy Policy

Please refer to the [Privacy Policy](PRIVACY.md) for details on how we collect, use, and safeguard your information.


## License

This project is licensed under the Apache License, Version 2.0. See the [LICENSE](LICENSE) file for details.

## Contact

If you have any questions or concerns, please contact Sembian Mani at [sembian.m@gmail.com](mailto:sembian.m@gmail.com).

