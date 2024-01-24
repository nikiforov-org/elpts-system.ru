Чтобы стянуть актуальную версию кода:
```
git pull
```


Чтобы создать pull request (пул-реквест) в GitHub, следуйте этим шагам:

1. Форкните репозиторий:
Перейдите на страницу репозитория, который вы хотите изменить, и нажмите кнопку "Fork" в правом верхнем углу страницы. Это создаст копию репозитория у вас в аккаунте.

2. Клонируйте свой форк:
Склонируйте свой форк репозитория на локальную машину с помощью команды git clone.
```
git clone https://github.com/ваш_логин/название_репозитория.git
```

3. Создайте новую ветку:
Перейдите в директорию клонированного репозитория и создайте новую ветку, где вы будете вносить изменения. Название ветки следует писать английскими буквами, цифрами, - или _.
Название ветки должно соответствовать смыслу выполняемой работы, или иметь какую-нибудь нумерацию. Например, по номеру задачи. Так как пока задач нет, можно ветки нумеровать по порядку.
Например, с префиксом ES: ES-1, ES-2, ES-3, и т. п.
```
git checkout -b ваша_новая_ветка
```

4. Внесите изменения:
Внесите необходимые изменения в код, добавьте новые файлы, и так далее.

5. Закоммитьте и запушьте изменения:
Закоммитьте ваши изменения и отправьте их в ваш форк на GitHub. Комментарий к изменениям надо писать на английском языке, комментарий должен отражать суть изменений, а не неведомую хуйню типа `jjjjjj`.
```
git add .
git commit -m "Ваш комментарий к изменениям"
git push origin ваша_новая_ветка
```

6. Создайте pull request:
После того как вы закоммитили и запушили изменения, перейдите на страницу вашего форка на GitHub. Виджет "Compare & pull request" должен появиться сверху. Нажмите на него.

7. Настройте pull request:
Выберите базовую (base) ветку (в какую ветку вы хотите внести изменения) и сравниваемую (compare) ветку (ваша новая ветка).

8. Заполните описание pull request:
Опишите ваши изменения в текстовом поле. Это поможет рецензентам и владельцу репозитория понять, что именно было сделано.

9. Отправьте pull request:
Нажмите на кнопку "Create pull request" для создания самого pull request.

10. Ожидайте рецензии и мержа:
Владелец оригинального репозитория сможет просмотреть ваши изменения, оставить комментарии и принять или отклонить pull request. После принятия изменения будут включены в оригинальный репозиторий.

Таким образом, вы успешно создали и отправили pull request в GitHub.
