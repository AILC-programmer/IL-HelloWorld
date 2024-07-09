# Hello world with IL code

## Tools:
- IL DASM
- Developer Command Prompt for VS ....

## How can I open IL DASM?
Open Developer Command Prompt for VS 2022 or another version and write ILDASM, the app will open automatically.

## CMD's commands We Used in this project
1. CSC
2. gacutil
3. ilasm
4. peverify

<hr>

## How should we use those commands?

- *CSC*:<br>
  Creates the execute file from the cs file. <br>
  Uses like this:<br>
  `CSC file-name.cs`
- *gacutil*:<br>
  gets all versions and assembly information for one assembly name like `System`<br>
  Uses like this:<br>
  `gacutil /l System`
- *ilasm*:<br>
  Creates the execute file from the il file.<br>
  Uses like this:<br>
  `ilasm /exe file-name.il /output:output-file-name.exe`
- *peverify*:<br>
  Debugs the exe files and verifies all classes and methods defined in the exe file.<br>
  Uses like this:<br>
  `peverify file-name.exe`

## How should we get the IL file from the exe file?

1. Open *ILDASM*:<br>
   Open Developer Command Prompt for VS 2022 or another version and write ILDASM, the app will open automatically.
2. Drag exe file in the ILDASM.
3. Go to File>Dump, use directory and file name, then save.
