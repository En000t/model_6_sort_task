# model_6_sort_task

File Sorting Script
The File Sorting Script is a Python script that helps you organize files in a given folder by sorting them into specific subfolders based on their file extensions. This can be useful for decluttering and organizing your files in a systematic manner.

Features
Sorts files into different categories: images, videos, documents, audio files, archives, and other files.
Renames files using a normalization process that replaces non-alphanumeric characters and performs transliteration.
Unpacks archive files (ZIP, GZ, TAR) into their respective folders for easier access.
Removes empty directories after sorting.
Prerequisites
Python 3.x installed on your system.
The required Python packages listed in the requirements.txt file.
Usage
Clone the repository or download the script file.
Open a terminal or command prompt and navigate to the directory containing the script.
Install the required packages by running the following command:

pip install -r requirements.txt

Run the script with the following command:

python sort.py <folder_path>

Replace <folder_path> with the path to the folder you want to sort.
The script will organize the files in the specified folder into subfolders according to their file types.
Once the sorting is complete, the script will display a summary of the sorted files.
