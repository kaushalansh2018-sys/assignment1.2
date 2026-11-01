# 1. Create and navigate into the main project folder
mkdir web-development-practice
cd web-development-practice

# 2. Create week-1, week-2, and week-3 folders
mkdir week-1, week-2, week-3

# 3. Create an index.html file inside each folder
New-Item week-1/index.html -ItemType File
New-Item week-2/index.html -ItemType File
New-Item week-3/index.html -ItemType File

# 4. Practice navigation and file operations (optional practice)
cd week-1
cd ..
Rename-Item week-3 week-three    # Renaming example
Rename-Item week-three week-3    # Change back
Remove-Item week-3 -Recurse      # Deleting a folder if needed
mkdir week-3
New-Item week-3/index.html -ItemType File

# 5. Open the project folder in VS Code
code .