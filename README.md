**Описание задачи**

Создайте модель, обрабатывающую фрагмент текста и определяющую, какой вид продукции в нём содержится.\
Датасет поделите на 80%/20% - обучающая/тестовая выборки.\
Используйте библиотеку PyTorch.\
Виды продукции (брать только виды продукции, для которых в датасете есть не менее 500 примеров):\
Баранина Ягнятина Индейка Говядина Свинина Кура Цыплено Гусь Буйволятина Оленина Конина Телятина Кролик Утка Куропатка Перепел Глухарь Страус Заяц Кенгуру Изюбр Кабан Коза Косуля Лось Марал Медвежатина Бобер Цесарка Нутрия Рябчик Тетерев Фазан Як

Примеры входных текстов и видов продукции:
Набор для бульона свиной -> Свинина\
Набор для бульона свиной, в наличии, 76р/кг. -> Свинина\
Мясо премиум Предлагаем котлетное мясо мраморной говядины. -> Говядина\
спинка цб -> Цыпленок

Проверьте вашу модель на образцах:\
Говядина блочная 2 сорт в наличии ООО “АгроСоюз” реализует блочную говядину 2 сорт (80/20)\
Свободный объем 8 тонн Самовывоз или доставка. Все подробности по телефону.\
Куриная разделка Продам кур и куриную разделку гост и халяль по хорошей цене .Тел:\
Говяжью мукозу Продам говяжью мукозу в охл и замороженном виде. Есть объем.
