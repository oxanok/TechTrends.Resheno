# TechTrends.Resheno

## Несколько правил по использованию Git и ведению проекта:

- Каждый делает свое исследование (в своей папке).
- После проведения исследования выяснилось, что вам нужен определенный функционал - разделите его на функции, если это требуется, и вынесите этот функционал в отдельный файл.
- Старайтесь соблюдать принципы SOLID и не смешивать уровни абстракции.
- Оброботать данные - отдельный модуль, обучить модель - отдельный модуль. Под модулем, я подразумеваю отдельный py файл.
* Все изменения делаем в своей ветке, то есть, перед разработкой используем команду - `git checkout -b "Название ветки"`. (правила для названия веток я опишу в Слаке). После этого вливаем в ветку develop. При стабильных изменениях в ветке develop происходит влитие в master.
- Входная точна в приложение - index.py.
