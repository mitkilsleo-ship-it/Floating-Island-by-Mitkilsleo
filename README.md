# Floating-Island-by-Mitkilsleo
A Simple floating island with customization options and various features
> **Внимание:** Программа находится в альфа-версии, поэтому в ней может быть много багов.

Здравствуйте! Чтобы установить Floating Island на ваш ПК, вам понадобится:

- Программа .NET ((https://dotnet.microsoft.com))

Инструкция:

Распакуйте файл и перенесите его на рабочий стол для удобства. Запустите файл build.bat и подождите примерно 50–70 сек. (зависит от скорости вашего диска). У вас появятся папки bin, obj и out — вам нужна папка out, в ней появится само приложение.

Удаление:

Если вы захотите удалить приложение полностью, сначала пропишите в PowerShell (от имени администратора) следующую команду (если что-то мешает закрыть программу):

```powershell
\(d = Get-CimInstance Win32_SystemDriver \vert{} Where-Object PathName -like '*FloatingIsland.sys*'\)d | Select Name, State, PathName
foreach (x in d) { sc.exe stop x.Name; sc.exe delete x.Name }
```
⠀
⠀
⠀
⠀
//ENG//

> **Note:** This program is currently in alpha, so there may be many bugs.

Hello! To install Floating Island on your PC, you will need:

- .NET ((https://dotnet.microsoft.com))

Instructions:

Extract the archive and move it to your Desktop for convenience. Run the `build.bat` file and wait for about 50–70 seconds (depending on your drive speed). Once finished, the `bin`, `obj`, and `out` folders will appear — you will need the `out` folder, where the application itself will be located.

Uninstallation:

If you want to completely uninstall the application, first run the following command in PowerShell as Administrator (in case something prevents you from closing the program):

```powershell
\(d = Get-CimInstance Win32_SystemDriver \vert{} Where-Object PathName -like '*FloatingIsland.sys*'\)d | Select Name, State, PathName
foreach (x in d) { sc.exe stop x.Name; sc.exe delete x.Name }
```





