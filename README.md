# MessageBox-Spamer
Проект по Информационна и комуникационна сигурност
Име: Юрослав Минчев   Студентски номер: 2201321007

За начало създаваме една програма на Visual Studio, в която ще използваме Windows Forms, благодарение на което ще можем да спамим на екрана MessageBox-ве  с някакъв текст избран от нас, в случая имаме един switch който използва Random за да си избере кой текст да възпроизведе на екрана,  също така съобщенията не могат да се повтарят два пъти последователно. Целият този процес е вкаран в един while цикъл който е безкраен, така съответния заразен независимо дали натиска бутона “Accept” или „Х“ няма да може да излезе от програмата.
Следващата стъпка е да скрием този проект в една снимка, така че да можем да заразим съответния потребител, за целта взимаме папката на проекта и една снимка. Снимката я превръщаме във формат .ico за да можем външно да скрием този rar файл, селектираме папката, както и снимката която искаме да се изведем на екрана, натискаме десен бутон  WinRar -> Add to archive.
След това на General натискаме на Archiving Options -> Create SFX archive, отиваме на Advanced -> SFX Options, след което отиваме на Setup -> Run after extraction ,където пишем името на снимката която да се отвори първа, в случая (bmw.jpg) след което пишем директорията на файла който искаме да отворим след снимката (C:\Users\HP\Desktop\FirstTry\SysDef32\bin\Debug\net6.0-windows\SysDefender Tab.exe) , отиваме на Models -> Silent Mode -> Hide start dialog , следващата стъпка е да отидем на Update -> Update mode и да изберем Extract and update files, в същия Update натискаме Overwrite all files, след което отиваме на Text and icon на Title of SFX window пишем името на файла (примерно Desktop.jpg), след което натискаме Load SFX icon from the file, където селектираме снимката която сме запазили с разширение .ico.
Натискаме Accept и вече съответния вирус ще е готов за използване.
