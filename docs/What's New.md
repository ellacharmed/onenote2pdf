* New command: **ExcludeOnly** {"[section name](section-name)"}
Specifies the only section that you want to export. This command is similar to command ExportSection, however, it does not create entire cache folder for exporting. It creates cache only for that section.
* New command: **Exclude** {"[section1,section2,...](section1,section2,...)"}
Specifies list of sections (absolute path) to be excluded from exporting to PDF 
* New command: **ShowTOC** {"[true](false)"} default is true
Specifies wherether to show Table of Contents at the beginning of output PDF file.
* New command: **TOCLevel** {"[level](level)"}
Specifies the maximum level at which the automatic numbering will be added to TOC entries
* New command: **RefreshCache** {"[true](false)"} default is false
If set, cache folder will be deleted.
* Rename command **TempPath** to **CacheFolder** to better describe the meaning of the command               
* Remove command: **ExportGroup**
Section and sectiongroup is now merged to one entity. Use command ExportSection for export both section and sectiongroup
* Add UnitTest for most of classes in the project