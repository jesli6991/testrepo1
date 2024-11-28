# Install.md

## Manual Installation

1. **Download UpdateDep**:  
   Visit the [UpdateDep GitHub Releases Page](https://github.com/teamextension/homebrew-updatedep/releases) to download the latest version of `UpdateDep`.

## Install Using Chocolatey

1. **Open Command Prompt as Administrator**:  
   Right-click on the Start button, and select **Command Prompt (Admin)** or **Windows Terminal (Admin)**.

2. **Execute the Installation Command**:
   ```
   choco install updatedep
## Install Using Homebrew
1. **Open Terminal**:
   Use the Terminal app on macOS or Linux.

2. **Tap the Repository**:
   ```
   brew tap teamextension/updatedep
3. **Install the Package**:
    ```
   brew install updatedep

## Upgrade Using the Upgrade Action

1. **Open Terminal or Command Prompt**:  
   Use the **Terminal** app on macOS/Linux or **Command Prompt** on Windows.

2. **Navigate to the Location of `updatedep.jar`**:  
   Use `cd` to change directories to where the `updatedep.jar` file is located.
    #### (Note: The filename of the jar to updatedep.jar for it to upgrade properly)
3. **Execute the Upgrade Command**:  
    ```
   java -jar updatedep.jar upgrade

## Upgrade Using Chocolatey

1. **Open Command Prompt as Administrator**:  
   Right-click on the Start button, and select **Command Prompt (Admin)** or **Windows Terminal (Admin)**.

2. **Execute the Upgrade Command**:  
    ```
   choco upgrade updatedep

## Upgrade Using Homebrew

1. **Open Terminal**:  
   Use the **Terminal** app on macOS or Linux.

2. **Execute the Upgrade Command**:  
    ```
   brew upgrade updatedep
