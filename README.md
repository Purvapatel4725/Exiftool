# Exiftool

Exiftool is a collection of Python scripts designed to interact with the EXIF data in images. It includes scripts for extracting EXIF data, converting EXIF data to CSV format, and removing EXIF data from images.

## Files

- `exif.py`: Extracts EXIF data from images and optionally outputs it to a file.
- `exif_csv.py`: Extracts EXIF data from images and saves it to a CSV file.
- `remove_exif.py`: Removes EXIF data from images.

## Requirements

- Python 3.x
- PIL (Pillow)

## Installation

Install the required Python package using pip:

```sh
pip install pillow
```

## Usage

### exif.py

Extracts EXIF data from images and outputs it to the terminal or a file.

1. Place the images in a folder named `images` in the same directory as the script.
2. Run the script:

    ```sh
    python3 exif.py
    ```

3. Follow the on-screen prompts to choose the output method (Terminal or File).

### exif_csv.py

Extracts EXIF data from images and saves it to a CSV file.

1. Place the images in a folder named `images` in the same directory as the script.
2. Run the script:

    ```sh
    python3 exif_csv.py
    ```

3. The extracted EXIF data will be saved to a file named `exif_data.csv` in the parent directory.

### remove_exif.py

Removes EXIF data from images.

1. Place the images in a folder named `images` in the same directory as the script.
2. Run the script:

    ```sh
    python3 remove_exif.py
    ```

3. The script will overwrite the original images, removing any EXIF data.

## Warning

- **Backup your images before running these scripts**, especially `remove_exif.py`, as it will overwrite the original images.
- Ensure that the `images` directory contains only the images you wish to process.

## Author

Purva Patel
