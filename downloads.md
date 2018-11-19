---
layout: page
title: Downloads
permalink: /downloads/
---
## Downloads

Current version: 0.87 (October 23rd, 2018)

**CCExtractor's source code**

[CLI Source code full](https://github.com/CCExtractor/ccextractor/archive/v0.87.zip "https://github.com/CCExtractor/ccextractor/archive/v0.87.zip")

[Windows GUI Source code](https://sourceforge.net/projects/ccextractor/files/ccextractor/0.84/CCExtractorGUI.src-0.84.zip/download "https://sourceforge.net/projects/ccextractor/files/ccextractor/0.84/CCExtractorGUI.src-0.84.zip/download")  (Windows only; requires Visual Studio)

[Cross platform GUI](https://github.com/kisselef/ccextractor-gui-qt "https://github.com/kisselef/ccextractor-gui-qt")

**Windows binaries**

[Windows binaries](https://github.com/CCExtractor/ccextractor/releases/download/v0.87/ccextractor.0.87-windows.binaries.zip "https://github.com/CCExtractor/ccextractor/releases/download/v0.87/ccextractor.0.87-windows.binaries.zip")  (just the  GUI  and the command line programs, without installation)

[Windows installer, first attempt with InstallShield - if it doesn't work just use the zipped binaries above](https://github.com/CCExtractor/ccextractor/releases/download/v0.87/ccextractor_0.87_windows_installer.exe "https://github.com/CCExtractor/ccextractor/releases/download/v0.87/ccextractor_0.87_windows_installer.exe")

Note: Starting with 0.84 we're bundling two binaries for the main program: With and without OCR. The reason is that the OCR (needed to convert the bitmap based European DVB subtitles into .srt, and also DVD) has its own dependencies, which may or may not be available in the user system. So if you don't need the OCR and don't feel like fighting with dependencies just use the non-OCR version which has no external dependencies and should work fine in everything from XP up.

About the Windows installer, we used to generate .msi installers but that seems to be discontinued by Microsoft - Visual Studio generates them with an expired certificate which causes warnings. We've prepared a new installer using InstallShield. Please report issues if any. Things we are already aware of:

- It doesn't check for NET 2.0 being present, because it's too old. However we're still targeting it because for now we don't need anything advanced and NET 2.0 works in XP. If you are wondering why we care about XP it's because it's the last  OS

Operating System

that supports some ancient hardware that is still in use that cannot be replaced for a number of reasons.  
- It says “Unknown publisher”, because we currently don't have a code signing certificate.  
- You need to uninstall any previous version before installing, it cannot just update, even if all it would take is just to overwrite files.  

**Mac**

[Homebrew package](https://github.com/Homebrew/homebrew-core/blob/master/Formula/ccextractor.rb "https://github.com/Homebrew/homebrew-core/blob/master/Formula/ccextractor.rb")  (3rd party, not maintained by the CCExtractor team)

**Additional software written by the team**

[User Documentation for Subtitle Downloader](http://www.ccextractor.org/doku.php?id=public:gsoc:repository_documentation "http://www.ccextractor.org/doku.php?id=public:gsoc:repository_documentation")

[User Documentation for Activity Extractor](http://www.ccextractor.org/doku.php?id=public:codein:activity_extractor_user_docs "http://www.ccextractor.org/doku.php?id=public:codein:activity_extractor_user_docs")

[CCAligner - Word by Word Audio Subtitle Synchronisation Tool and API](https://www.ccextractor.org/public:gsoc:2017:saurabh "public:gsoc:2017:saurabh")

**Dependencies**

[Visual C++ Redistributable Packages for Visual Studio 2013](https://www.microsoft.com/en-us/download/details.aspx?id=40784 "https://www.microsoft.com/en-us/download/details.aspx?id=40784")  (this might be needed to run CCExtractor 0.70 and above in XP).

[Dependencies for the full CCExtractor version (with FFmpeg, OCR, etc)](https://sourceforge.net/projects/ccextractor/files/ccextractor/0.85-windows.dependencies/CCExtractorDLLs-32bits.zip/download "https://sourceforge.net/projects/ccextractor/files/ccextractor/0.85-windows.dependencies/CCExtractorDLLs-32bits.zip/download")  (they are included in the distribution packages but we have them separately for convenience).

