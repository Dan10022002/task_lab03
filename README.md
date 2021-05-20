# Отчёт по lab03

## Report

![report](https://github.com/Dan10022002/task_lab03/blob/master/report03.png)

## Homework

### Preparing

1. Создаём папку для работы

_cd Dan10022002/workspace/tasks<br/>
mkdir task_timp_lab03<br/>
cd task_timp_lab03_

2. Клонируем репозиторий с заданием и удаляем лишнее

![clone](https://github.com/Dan10022002/task_lab03/blob/master/clone.png)

3. Инициализируем локальный репозиторий

_git remote remove origin<br/>
git remote add origin https://github.com/Dan10022002/task_lab03.git_

### Task 1

В папке formatter_lib был создан файл CMakeLists.txt и открыт через vim для редактирования

_cd formatter_lib<br/>
touch CMakeLists.txt<br/>
vim CMakeLists.txt_

![cmake](https://github.com/Dan10022002/task_lab03/blob/master/cmake.png)

Затем была создана папка, в которую был собран проект

![build](https://github.com/Dan10022002/task_lab03/blob/master/build.png)

### Task 2

В папке formatter_ex_lib был создан файл CMakeLists.txt и открыт через vim для редактирования

_cd ../..<br/>
cd formatter_ex_lib<br/>
touch CMakeLists.txt<br/>
vim CMakeLists.txt_

![cmake2](https://github.com/Dan10022002/task_lab03/blob/master/cmake2.png)

Затем была создана папка, в которую был собран проект

![build2](https://github.com/Dan10022002/task_lab03/blob/master/build2.png)

### Task 3

В папке hello_world_application был создан файл CMakeLists.txt и открыт через vim для редактирования

_cd ../..<br/>
cd hello_world_application<br/>
touch CMakeLists.txt<br/>
vim CMakeLists.txt_

![cmake3](https://github.com/Dan10022002/task_lab03/blob/master/cmake3.png)

Затем была создана папка, в которую был собран проект

![build3](https://github.com/Dan10022002/task_lab03/blob/master/build3.png)

В папке solver_application был создан файл CMakeLists.txt и открыт через vim для редактирования

_cd ../..<br/>
cd solver_application<br/>
touch CMakeLists.txt<br/>
vim CMakeLists.txt_

![cmake4](https://github.com/Dan10022002/task_lab03/blob/master/cmake4.png)

Затем была создана папка, в которую был собран проект

![build4](https://github.com/Dan10022002/task_lab03/blob/master/build4.png)

В конце работы все изменения были залиты на гитхаб

_git add .<br/>
git commit -m "Complit task"<br/>
git push origin master
