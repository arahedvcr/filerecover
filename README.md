# FileRecover

FileRecover is a Python program designed to aid in the recovery of accidentally deleted files on Windows systems. It supports various file systems and provides a simple interface for users to restore files from specified drives.

## Features

- **Drive Scanning:** Scans specified drives for recoverable deleted files.
- **File Recovery:** Recovers selected files to a specified destination folder.
- **Cross-File System Support:** Works with various file systems on Windows.

## Requirements

- Windows Operating System
- Python 3.x

## Installation

1. Clone the repository:
   ```bash
   git clone https://github.com/yourusername/filerecover.git
   ```
2. Navigate to the project directory:
   ```bash
   cd filerecover
   ```

## Usage

1. Run the program:
   ```bash
   python file_recover.py
   ```

2. Follow the prompts:
   - Enter the drive letter from which you want to recover files (e.g., `C:`).
   - Enter the destination folder path where recovered files should be saved.

## Important Notes

- This program is a simulation and does not perform actual file recovery. Implementing real file recovery requires low-level system access and is beyond the scope of this script.
- Ensure that the destination folder exists before running the program.

## License

This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for more information.

## Contributing

Contributions are welcome! Please submit a pull request or open an issue to discuss your ideas.

## Disclaimer

Use this program at your own risk. The developers are not responsible for any data loss or damage.