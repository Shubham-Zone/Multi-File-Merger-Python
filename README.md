# Multi-File Merger (Python)

Multi-File Merger is a Python script that allows you to merge multiple files of a specific type into a single document. It's useful for consolidating various files into one document for easier management and sharing.

## Features

- Merges multiple files of a specified type (e.g., `.pl`, `.txt`, `.docx`) into a single document.
- Supports customization of the file type to merge.
- Simple and easy-to-use Python script.
- Generates a formatted Word document (.docx) with the merged content.
- Works on Windows, macOS, and Linux.

## Usage

1. Clone the repository to your local machine:

```bash
git clone https://github.com/Shubham-Zone/Multi-File-Merger-Python.git
```

2. Navigate to the project directory:

```bash
cd Multi-File-Merger-Python
```

3. Install the required Python packages:

```bash
pip install python-docx
```

4. Run the script with the desired folder path containing the files to merge:

```bash
python merge_files.py <folder_path> <output_file>
```

Replace `<folder_path>` with the path to the folder containing the files to merge, and `<output_file>` with the desired name of the merged document.

## Example

```bash
python merge_files.py /path/to/files merged_document.docx
```

## Contributing

Contributions are welcome! Feel free to open issues or submit pull requests.
