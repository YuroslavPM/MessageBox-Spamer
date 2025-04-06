# MessageBox-Spamer
Иnformation and Communication Security Project
Name: Yuroslav Minchev Student ID: 2201321007

To start, we create a program in Visual Studio using Windows Forms. This allows us to spam MessageBoxes on the screen with some text of our choice. In this case, we have a switch that uses Random to select which text to display on the screen. Also, the messages cannot repeat consecutively. The entire process is placed inside an infinite while loop, so regardless of whether the user presses the "Accept" button or the "X" to close the window, they won't be able to exit the program.

The next step is to hide this project inside an image file, allowing us to infect the target user. To do this, we take the project folder and an image. The image is converted to the .ico format to externally hide this rar file. We select the folder as well as the image we want to display, right-click it, and choose WinRar -> Add to archive.

In the General tab, we click on Archiving Options -> Create SFX archive, then go to Advanced -> SFX Options. Next, we go to Setup -> Run after extraction, where we type the name of the image that should open first (e.g., bmw.jpg). Afterward, we write the path of the file we want to open after the image (C:\Users\HP\Desktop\FirstTry\SysDef32\bin\Debug\net6.0-windows\SysDefender Tab.exe). Then we go to Models -> Silent Mode -> Hide start dialog. The next step is to go to Update -> Update mode and select Extract and update files. In the same Update section, click Overwrite all files. Afterward, we go to Text and icon, in the Title of SFX window, write the name of the file (for example, Desktop.jpg), and then click Load SFX icon from the file, where we select the image we saved with the .ico extension.

Click Accept, and the virus will be ready for use.
