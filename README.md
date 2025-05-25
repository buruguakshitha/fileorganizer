#  File  manager

This is a simple Python script that organizes files in a specified folder into categorized subfolders based on file extensions such as documents, images, videos, and audio files.

##  Features

- Automatically sorts files into subfolders:
  - `Documents`
  - `Images`
  - `Videos`
  - `Audio`
  - `Others` (for uncategorized files)
- Uses `shutil` and `os` for file handling
- Logs each operation with timestamps
- Skips folders during processing

## 🧠 How It Works

1. You specify a target directory (`target_directory`).
2. The script creates subfolders for each category (if not already present).
3. It loops through each file in the directory:
   - Checks the file extension.
   - Moves it to the appropriate subfolder.
   - If no category matches, it moves the file to the `Others` folder.
4. Logs every file movement or error.

## 🔧 Requirements

- Python 3.x
- No external libraries required (uses built-in libraries: `os`, `shutil`, `logging`)



