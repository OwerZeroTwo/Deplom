Анализ и сравнение разработки веб-приложений с использованием различных фреймворков
Введение
В этой работе мы проанализируем и сравним разработку простых веб-приложений с использованием трех популярных фреймворков Python: Django, Flask и FastAPI. Мы создадим простое веб-приложение с использованием каждого фреймворка и сравним их сильные и слабые стороны.
Разработка веб-приложений
Джанго
Django — это высокоуровневый фреймворк Python, который поощряет быструю разработку и чистый, практичный дизайн. Он предоставляет архитектуру, шаблоны и API для создания надежных и масштабируемых веб-приложений.
Пример кода
Проект:  не удалось добавить новый проект с внесёнными изменениями изза проблем с добавлениям нескольких деректорий он основной код был перенесён
Для запуска прописать: python manage.py runserver
после чего перейти по ссылке http://127.0.0.1:8000/


Функции
Высокоуровневый фреймворк со встроенной системой ORM и аутентификации
Особое внимание уделяется возможности повторного использования кода и модульности
Большое и активное сообщество
Поддерживает быструю разработку и прототипирование
Flask
Flask — это микровеб-фреймворк, написанный на Python. Он классифицируется как микрофреймворк, поскольку не требует специальных инструментов или библиотек. Он не имеет уровня абстракции базы данных, проверки форм или других компонентов, где существующие сторонние библиотеки предоставляют общие функции.
Пример кода
Проект:  старый проэкт перенесёны в эту репазиторию 
для запусска python app.py и перейти по ссылке http://127.0.0.1:5000/
Функции
Легкий и гибкий каркас
Идеально подходит для малых и средних предприятий
Поддерживает расширения и библиотеки для дополнительной функциональности
Легко изучить и использовать
FastAPI
FastAPI — это современный, быстрый (высокопроизводительный) веб-фреймворк для создания API с Python 3.7+ на основе стандартных подсказок типов Python. Он разработан, чтобы быть быстрым, масштабируемым и простым в использовании.


Пример кода
Проект: старый проэкт перенесёны в эту репазиторию

для запуска используйте  uvicorn main:app --reload после перейдите по ссылке http://localhost:8000/

Функции
Высокопроизводительная структура с автоматической документацией API
Поддерживает асинхронное программирование и WebSockets
Строго типизированная и автоматически сгенерированная документация API
Легко изучить и использовать
Сравнение фреймворков
Скорость разработки
Django: Высокая скорость разработки благодаря высокоуровневому фреймворку и встроенному ORM.
Flask: Средняя скорость разработки из-за микрофреймворковой природы и необходимости дополнительных библиотек.
FastAPI: Высокая скорость разработки благодаря современному дизайну и автоматическому документированию API.
Кривая обучения
Django: Более сложная кривая обучения из-за сложной архитектуры и встроенного ORM.
Flask: более простая кривая обучения благодаря своей легкости и гибкости.
FastAPI: более простая кривая обучения благодаря современному дизайну и строго типизированному коду.
Масштабируемость
Django: Высокая масштабируемость благодаря встроенному ORM и поддержке больших приложений.
Flask: Масштабируемость, но для крупных приложений могут потребоваться дополнительные библиотеки и инструменты.
FastAPI: Высокая масштабируемость благодаря асинхронному программированию и поддержке WebSockets.
Заключение
В заключение, каждый фреймворк имеет свои сильные и слабые стороны. Django идеально подходит для больших и сложных приложений, Flask подходит для небольших и средних приложений, а FastAPI идеально подходит для создания высокопроизводительных API. Выбор фреймворка в конечном итоге зависит от требований проекта и опыта разработчика.
мне нужно приложене на FastAPI для замето в которой будет функцеонал добавления и удаления заметок также нельзя использавать Flask и Django и можно использовать только питон и html дизайн страницы должен быть минималестичный
