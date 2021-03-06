# Colorbrewer ArcMap Extension

This extension allows the user to symbolize vector data using Colorbrewer configurations imported from the included *cb.csv*.  You must have ArcMap installed and the current installation procedure requires the use of Visual Studio.

Point and polygon data is supported.  Line data is not supported.  The user can choose between simple fill and classbreaks for numeric fields.

## Installation

To install the Colorbrewer Extension:
1. Download the ZIP
2. Extract the files
3. Locate the *cb.csv* file (in the project root)
4. Copy the path of *cb.csv* to your clipboard (*Colorbrewer* > *Colorbrewer.sln*)
5. Open the project solution in Visual Studio
6. Open *ColorbrewerExtension.cs* (*Colorbrewer* > *Colorbrewer* > *ColorbrewerExtension.cs*)
7. Assign the value of *const string FILEPATH* by pasting the path to *cb.csv*
8. Save *ColorbrewerExtension.cs*
9. Build the project
10. Start debugging. ArcMap will launch.
11. Use __Customize__ -> __Customize Mode__ -> __Add From File__ to install the extension using the AddIn file.
