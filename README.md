# Setup

You will need to install the following software on your computer.

### Git
Mac users can download and install the latest version of git from https://sourceforge.net/projects/git-osx-installer/files/

Windows users can download the latest version of git from https://gitforwindows.org/. Then run the installer and follow the steps below:
  1. Click on "Next".
  2. Click on "Next".
  3. **Keep "Use Git from the Windows Command Prompt" selected and click on "Next".** If you forgot to do this programs that you need for the workshop will not work properly. If this happens rerun the installer and select the appropriate option.
  4. Click on "Next".
  5. **Keep "Checkout Windows-style, commit Unix-style line endings" selected and click on "Next".**
  6. **Keep "Use Windows' default console window" selected and click on "Next".**
  7. Click on "Install".
  8. Click on "Finish".
  9. If your "HOME" environment variable is not set (or you don't know what this is):
        a) Open command prompt (Open Start Menu then type `cmd` and press [Enter])
        b) Type the following line into the command prompt window exactly as shown:
        `setx HOME "%USERPROFILE%"`
        c) Press [Enter], you should see `SUCCESS: Specified value was saved.`
        d) Quit command prompt by typing exit then pressing [Enter]

### Anaconda

Mac and Windows users can download and install the latest version from http://continuum.io/downloads 
Windows users should check the **Make Anaconda the default Python** option.

### Datarail repositories
For the upcoming Datarail tutorial (5/31/2018), we will be drawing on code from three repositoires. Follow the steps below to install these packages on your computer.
1. Open the terminal on Mac or git bash on Windows
2. Type the commands below in the given order. Press `Enter` after each command.
  ```
  mkdir git_repos
  cd git_repos
  git clone https://github.com/datarail/datarail.git
  git clone https://github.com/datarail/DrugResponse.git
  git clone https://github.com/datarail/gr_metrics.git
  cd datarail
  pip install -e .
  cd ../DrugResponse/python
  pip install -e .
  cd ../../gr_metrics/SRC/python
  pip install -e .  
  ```

