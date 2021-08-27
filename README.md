# google_translation_api
You need "type": "service_account" json file which you can get from https://cloud.google.com/ and switch on Google Translate API.
Any questions you can read on: alexey.websearch@gmail.com

<p>В работе мне нужно автоматом перевести большой пул ключей или текст на разные языки.</p>
<p>Нашел отличный и быстрый способ.</p>
<li>1) Для этого нам нужно зайти в https://console.cloud.google.com/marketplace/product/google/translate.googleapis.com и включить API;</li>
<li>2) Получить ключик API.json из постов выше;</li>
<li>3) Взять код что прикреплен;</li>
<li>4) В txt файл "translate.txt" занести текст что хотим перевести;</li>
<li>5) Найти строку "target='en'" - поставить нужный язык для перевода; Нужный язык ищем тут (https://cloud.google.com/translate/docs/languages).</li>
<li>6) Запускаем скрипт и наслаждаемся переводом, он конечно не самый будет хороший, но довольно быстрый.</li>
