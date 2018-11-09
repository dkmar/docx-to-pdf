# Convert Docx files to PDF on macOS 
Finder "Quick Action" to convert docx files to pdf using Automator and a bit of AppleScript(😂)
![](better_demo.gif)
## Installing
### Option 1:
1. Download the zip
2. Double-click on the zip in Finder to unzip it. This should yield the workflow.
3. Double-click the workflow and click "Install" on the pop-up dialog.
### Option 2:
```bash
cd ~/Library/Services
wget https://github.com/dkmar/docx-to-pdf/raw/master/DocxToPDF.workflow.zip
tar xf DocxToPDF.workflow.zip && rm -r DocxToPDF.workflow.zip
```
## Basic Automator Workflow
![](DocxToPDF.workflow/Contents/QuickLook/Preview.png?raw=true)
Note: tested on macOS 10.14 mojave
