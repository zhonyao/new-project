Створіть гілку

git branch development

Перейти до робочої гілки . Перейдіть до вказаної гілки та оновіть робочий каталог за допомогою git switch:

$ git switch development

Виконуйте роботу. Додавайте свої зміни:

$ git add .
$ git commit -m "my changes"

Надішліть свої зміни на GitHub

$ git push

Об'єднуйте робочу гілку з основною гілкою main. 

$ git switch main
$ git merge development
