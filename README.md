# Talk_and_buy

Telegram-чат-бот с тремя интентами. 

Проект реализован при помощи разбиения вариантов на интенты: LogisticRegression (accuracy 0.97) разделяет путь решения на два домена - продуктовый и вопрос-ответный при помощи векторизации запроса пользователя CountVectorizer'ом и его сравнения с обработанными FasText'ом датасетом с товарами на Юле и текстовым файлом с сервиса "Ответы" от mail.ru. При помощи библиотеки Annoy выявляются ближайшие к запросу варианты и в Telegram-чат-боте пользователь видит либо 5 товаров с картинками и ссылками, либо диалоговый ответ. Также есть третий домен: если запрос сформулирован не четко, бот просит конкретизировать его. 

# 

<img align='center' src="https://github.com/rectorkipa/NLP-Talk_and_buy/blob/main/sc_sh_2-qa.JPG" width="640">

#

<img align='center' src="https://github.com/rectorkipa/NLP-Talk_and_buy/blob/main/sc_sh_1-prod.JPG" width="640">

#

<img align='center' src="https://github.com/rectorkipa/NLP-Talk_and_buy/blob/main/sc_sh_3-another.JPG" width="640">
