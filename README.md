# Windows Dev Environment Setup Script

This PowerShell script automates the setup of a comprehensive Python and web development environment on Windows.

## What it does

- Installs [Chocolatey](https://chocolatey.org/) package manager
- Installs core development tools:
  - Git
  - Visual Studio Code
  - PyCharm Community Edition
  - Node.js
- Installs [Anaconda](https://www.anaconda.com/)
- Installs Docker Desktop
- Updates PATH to include Anaconda
- Installs essential Python packages:
  - jupyter, pytest, black
  - keras, tensorflow, scikit-learn
  - flask, django
  - pandas, numpy
- Installs Pipenv

## Prerequisites

- Windows 10 or later
- PowerShell 5.1 or later
- Administrator privileges

## How to use

1. Open PowerShell as Administrator
2. Copy the entire script content
3. Paste into the PowerShell window
4. Press Enter to run

## Notes

- The script may take a considerable amount of time to run, depending on your internet speed and system performance.
- Some installations (like Docker Desktop) may require a system restart to complete.
- It's recommended to restart your computer after the script finishes to ensure all changes take effect.

## Customization

You can modify the `$devTools` and `$packages` arrays in the script to add or remove tools and Python packages according to your needs.

## Troubleshooting

If you encounter any issues:
1. Ensure you're running PowerShell as Administrator
2. Check your internet connection
3. Review the error messages in the console output
4. Try running the problematic parts of the script individually

## Disclaimer

This script makes significant changes to your system. While it's designed to be safe, please review the script and understand its actions before running. Use at your own risk.

## Contributing

Feel free to fork this repository and submit pull requests with improvements or additional features.

## License

[MIT License](LICENSE)
