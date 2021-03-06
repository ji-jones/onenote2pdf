**Usage**
run in Console mode using following syntax:
Export2PDF {"[Command command-parameter](Command-command-parameter)"}
where available commands are:
* **-ExportGroup** {"[Section group Name](Section-group-Name)"}
Specifies the Section group name you want to export.
* **-ExportNotebook** {"[true](false)"} (default is false)
Export entire notebook specified in -Notebook param in your current OneNote 2007.
* **-ExportSection** {"[Section Name](Section-Name)"}
Specifies the Section name you want to export.
* **-Help** {"[Argument](Overview_Full)"} (Overview is default)
Use the help to show detail description of the arguments.
* **-ListAllNotebook** {"[true](false)"} (default is false)
List all notebooks in your current OneNote 2007.
* **-Notebook** {"[Notebook Name](Notebook-Name)"}
Specifies the notebook name you want to export.
* **-Output** {"[base path name of the exported PDF](base-path-name-of-the-exported-PDF)"}
Specifies the base path name of the exported PDF.
* **-CacheFolder** {"[base path for cache folder to store all exported PDFs within one Notebook](base-path-for-cache-folder-to-store-all-exported-PDFs-within-one-Notebook)"}
Specifies the base path to store all exported PDFs within one Notebook.
* **-ShowTOC** {"[true](false) default is true"}
Specifies whether to show **Table of Contents** at the beginning of PDF output or not.
* **-TOCLevel** {"[level](level)"}
Specifies maximum level of TOC entries whose title is prefixed by automatic numbering such as _3.4.1 Sub section 1_
* **-TraceLevel** {"[Off](Error_Warning_Info_Verbose)"} (Defaut value is Info)
The trace level switch setting for the application. It's possible to add more Trace listeners in OneNote2PDF.exe.config file.