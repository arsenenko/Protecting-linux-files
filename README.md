# Protection preventing file changes linux chattr Ubuntu-16.04
<a href="https://ibb.co/hSHFZJ"><img src="https://preview.ibb.co/eboNEJ/chattr_command_tech_tutorials.jpg" alt="chattr_command_tech_tutorials" border="0"></a><br /><a target='_blank' ></a><br />

Данная  команда может изменять атрибуты файлов, Linux запреты на удаления файлов или изменения и даже из под правами суперпользователя /root.
Chattr - поддерживает файловые системы как (ReiserFS.XFS.Btrfs ext2.ext3.ext4)......
#Структура синтаксиса команд:
1. chattr - (Изменения Атрибутов) 
2. lsattr - (Просмотр Атрибутов)

#chattr [-RVf] [Оператор][атрибуты] /файл
[ Оператор ] :
“+” - Добаваить 
“-” - Удалить 
“=” - Перезаписать 
“-R +i” - Папка 

#[ Пример атрибутов ]
“a” - Только редактировать в режиме добавления 
“A” - не обновлять время перезаписи 
“c” - авто.сжать при записи на диск 
“C” -Отек. копирования при записи 
“i” - сделать не известным …. 

