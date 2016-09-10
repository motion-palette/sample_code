

## Setting up your computer for 76388/788 Coding for Humanists

### Mac OS X (10.5 or higher)

**Step 1. Install Python 3.5.2 (or newer)**
- Download Python 3.5.2 from [https://www.python.org/downloads/]
- Follow the instructions to install it.

**Step 2. Follow the Getting Started handout (from the first class).**

- It's the last 2 pages of the syllabus, which is also on Blackboard.


### Windows 7 or 8

**Step 1. Install Python 3.5.2 (or newer)**
- Download Python 3.5.2 from [https://www.python.org/downloads/]
- Follow the instructions to install it.
- On the installer panel, make sure to check the **Add Python 3.5 to PATH** checkbox

**Step 2. Create a course folder on your desktop**
- Launch Windows PowerShell from the start menu
- Change current working folder to Desktop using the following command:

  ```
  cd Desktop
  ```

- Make a new folder for the course:

  ```
  mkdir cfh
  ```

**Step 3. Create a virtual environment**
- Launch Windows PowerShell
- Change your currnt folder to the course folder ```cd Desktop/cfh```
- Execute the following command from the course folder:

  ```
  python -m venv venv
  ```

**Step 4. Activate the Virtual Environment**
- Launch Windows PowerShel
- From the course folder, execute the following command:

  ```
  venv\Scripts\activate
  ```

    This may give you an error saying something like "Running scripts is disabled on this system." If this happens, you need to launch Windows PowerShell as an administrator (From the application menu, right-click Windows PowerShell, and select *Run as administrator* from the context menu).

    Then, after you launch Windows PowerShell, execute the following command:
    
    ```
    set-executionpolicy remote signed
    ```
  
    You should see "(venv)" at the beginning of each command line if you have successfully activated your virtual env. 

**Step 5. Install Jupyter Notebook**
- Launch Windows PowerShell 
- Activate the virtual environment (You may need to run Windows PowerShell as an administrator. See above).
- From the course folder, execute the following command:

  ```
  pip install jupyter
  ```

**Step 6. Launch Jupyter Notebook**
- Launch Windows PowerShell
- Activate the virtual environment
- Execute the following command:

  ```
  jupyter notebook
  ```

 




