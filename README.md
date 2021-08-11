# Windows chcp
Change the Code Page in CMD permanently.

## Usage
- Save `startup.cmd` in one directory. (You can edit the page number and in this example it is `437`, United States.)
- Open **Registry Editor** using keyboard shortcut `WIN + r` and type `regedit`. Find `Computer\HKEY_LOCAL_MACHINE\SOFTWARE\Microsoft\Command Processor` and edit (or add) string item `Autorun` with the value of your path like `C:\Users\Admin\startup.cmd`.

## Reference
https://stackoverflow.com/questions/7432545/change-codepage-in-cmd-permanently

## License
This is under the [MIT License](LICENSE).