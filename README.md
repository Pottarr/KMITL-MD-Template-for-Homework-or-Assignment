# KMITL MD Template for Homework or Assignment

## Feel free to use this in your Homework Reports

# How to use

## Using VS Code :

### Setup:

#### Download VS Code Extension

![Extension Markdown PDF](./images/Markdown%20PDF.png)

#### If you do not want the header and footer, (Optional)

1. Open setting by
    - Commands
        - Window: Ctrl + ,
        - MacOs: Cmd + ,
2. Type "pdf" and find this setting.
   ![PDF header and footer setting](./images/PDF%20header%20and%20footer%20setting.png)

3. Uncheck the setting and you are now good to go.

### Usage:

1. Git Clone.
2. Removing .git file from the directory using command below

Window:

```powershell
cd .\KMITL-MD-Template-for-Homework-or-Assignment\
Remove-Item .\.git\ -Force
```

MacOS:

```bash
cd .\KMITL-MD-Template-for-Homework-or-Assignment\
rm -rf .git/
```

3. Edit the template.

4. Make sure that you change the file name from [Template.md](Template.md) to your choice.

5. Open setting
    - Commands
        - Window: Ctrl + Shift + P
        - MacOS: Cmd + Shift + P

6. Type "pdf" and find this command

![Search Bar](./images/Search%20Bar.png)

7. Use the command (The result will be a file like [Template.pdf](Template.pdf))
