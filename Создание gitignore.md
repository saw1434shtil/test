[< к содержанию >](./readme.md)



## Как создать файл .gitignore

Обычно файл _.gitignore_ помещается в корневой каталог репозитория. Корневой каталог также известен как родительский или текущий рабочий каталог. Корневая папка содержит все файлы и другие папки, из которых состоит проект.

Тем не менее, вы можете поместить этот файл в любую папку в репозитории. Если на то пошло, но у вас может быть несколько файлов _.gitignore._

Для того, чтобы создать файл _.gitignore_ в Unix-подобной системе, такой как macOS или Linux, с помощью командной строки, откройте приложение терминала (например, в macOS это Terminal.app). Затем для того, чтобы создать файл _.gitignore_ для вашего каталога, перейдите в корневую папку, которая содержит проект, и при помощи команды cd введите следующую команду:

```bash=
touch .gitignore
```