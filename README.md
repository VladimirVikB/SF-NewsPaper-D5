# SF_NewsPЧто вы должны сделать в консоли Django?

Создать двух пользователей (с помощью метода User.objects.create_user).
Создать два объекта модели Author, связанные с пользователями.
Добавить 4 категории в модель Category.
Добавить 2 статьи и 1 новость.
Присвоить им категории (как минимум в одной статье/новости должно быть не меньше 2 категорий).
Создать как минимум 4 комментария к разным объектам модели Post (в каждом объекте должен быть как минимум один комментарий).
Применяя функции like() и dislike() к статьям/новостям и комментариям, скорректировать рейтинги этих объектов.
Обновить рейтинги пользователей.
Вывести username и рейтинг лучшего пользователя (применяя сортировку и возвращая поля первого объекта).
Вывести дату добавления, username автора, рейтинг, заголовок и превью лучшей статьи, основываясь на лайках/дислайках к этой статье.
Вывести все комментарии (дата, пользователь, рейтинг, текст) к этой статье.