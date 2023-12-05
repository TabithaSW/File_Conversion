# Data-File-Convertor

Creating a file conversion tool that allows users to select XML, CSV, EXCEL, or JSON  files and create a new version in their file type choice. 
Python is the main language used, the GUI is created through Tkinter.

# Additions/Changes 12/5:
- Users can view summary stats for Teradata queries.
- Users can choose filename and save location for Teradata queries.

# Additions/Changes 12/4:
- User receives auto-generated preview of raw data in table format prior to conversion for both selected file data and query data.
- User can request to preview raw file content without any conversion, limit of 1000 rows.
- Data summary available of rows, columns, nulls, or missing data avilable when selecting file preview.
- Horizontal scroll added for file preview.
- Updated read/write functions for Excel, faster processing, less data amount limitations.

# Additions/Changes 11/30:
- User can connect to Teradata and save the file in CSV Format!

# Additions/Changes 11/29:
- Select multiple files to convert at one time.
- Allows users to choose the conversion type for each file.
- Added new file type! Excel format available.

# Additions/Changes 11/28:
- Allow users to save the file to specific locations on their PC.
- User options for file name.

# Additions/Changes 11/22:
- Displays a progress bar for the file being converted.
- Displays file selected in the application and the chosen conversion type.

# COMING SOON ADDITIONS/CHANGES:
- Allow file merge into singular format.
- Connect to Tableau or Power BI.
- Logging and error handling.
- File compression.
- Convert to PDF or have an additional PDF option for download.
- Downloading multiple copies on one run.
- Support for other formats such as MLoad. (From MLoad to CSV for Teradata)
- Drag and drop ability for files.
- Allow user to use the program script in command prompt.
- Allow users to make changes based off raw data in the file preview option.
- Highlight values missing/null found from summary function.


# Small fixes to do:
- Fix ? and * counts.
- Finish error logging py file so users can generate bug reports.