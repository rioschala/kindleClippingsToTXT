# kindleClippingsToTXT
Kindle Clippings file to individual TXT files with date. 

Highlight Exporter
This tool extracts multi-word highlights from a given text file and exports them into individual .txt files per selected book.

<p align="center">
  <img src="https://pub-18229f9d31f241a4b80d8d8a9c50ec52.r2.dev/Screenshot%202024-12-13%20182431.png" />
</p>

**Features**
* GUI Selection:
Choose the highlights source file on the Kindle and a desired output folder.

* Book Filtering:
The app scans the source file, identifies all books, and displays them with checkboxes so you can select which ones to export.

* Highlight Quality Filter:
Highlights with two or fewer words are ignored to maintain meaningful excerpts.

* Batch Export:
Selected books’ highlights are saved to separate .txt files in the chosen output directory.

**Getting Started**
- Clone the Repository:

```bash
git clone https://github.com/yourusername/highlight-exporter.git
cd highlight-exporter
```
- Install Dependencies: Ensure you have Python installed.

```bash
pip install pyinstaller
```
Build the Executable (Optional):

```bash
pyinstaller --onefile highlight_exporter.py
```
The .exe will be in the <kbr>dist<kbr> folder.

Run the App:

From Source:
```bash
python highlight_exporter.py
```
From Executable:
Run the highlight_exporter.exe file in dist.

**Usage**
1. Open the App:
Run the .exe or the Python script (if you have Python and tkinter) to launch the GUI.

2. Select Input File & Output Folder:
Click “Browse…” to pick the highlights file and then select the output folder.

3. Choose Books:
Tick the boxes next to the books you want to export.

4. Export:
Click "Export Selected Highlights" to generate .txt files.

5. After exporting, each chosen book will have its own text file containing only its multi-word highlights.
