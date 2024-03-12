The File Search by Term is a Python script that recursively searches for files containing a specific term in their filename within a specified directory. It utilizes the pathlib module for file path manipulation.

Clone the repo:

``git clone https://github.com/your-username/file-search-by-term.git``

Run the script:

``python file_search_by_term.py``

Features:

- Recursively searches for files within a directory and its subdirectories.
- Filters files based on a specified search term in their filename.
- Prints the absolute paths of files containing the search term.

Config:

- Modify the root_dir variable to specify the directory to search for files.
- Adjust the search_term variable to specify the term to search for in filenames.

Ex., Suppose you have the following directory structure: 

``project/
    ├── file1.txt
    ├── file2.txt
    ├── folder1/
    │   └── file3.txt
    ├── folder2/
    │   └── file14.txt
    └── folder3/
        └── folder4/
            └── file5.txt
``

After running the script with the search term '14', it will print the absolute path of the file file14.txt:

``/Users/username/project/folder2/file14.txt``
