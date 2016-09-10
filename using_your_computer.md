

## Setting up your computer for 76388/788 Coding for Humanists

### Windows 7 or 8

**Step 1. Install Python 3.5.2 (or newer)**
- Download Python 3.5.2 from [https://www.python.org/downloads/]
- On the installer panel, make sure to check the **Add Python 3.5 to PATH** checkbox

**Step 2. Create a course folder on your desktop**
- Launch Windows PowerShell from the start menu
- Change current working folder to Desktop using the following command:
  ```cd Desktop```
- Make a new folder for the course:
  ```mkdir cfh```

**Step 3. Create a virtual environment**
- Launch Windows PowerShell
- Change your currnt folder to the course folder ```cd Desktop/cfh```
- Execute the following command from the course folder:
  ```python -m venv venv```

**Step 4. Activate the Virtual Environment**
- Launch Windows PowerShel
- From the course folder, execute the following command
  ```venv\Scripts\activate```

**Step 5. Install Jupyter Notebook**
- Launch Windows PowerShell 
- Activate the virtual environment (You may need to run Windows PowerShell as an administrator. See above).
- From the course folder, execute the following command:
  ```pip install jupyter```

**Step 6. Launch Jupyter Notebook**
- Launch Windows PowerShell
-  Activate the virtual environment
-  Execute the following command:
   ```jupyter notebook```





