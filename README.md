# Исследовательское тестирование приложения TO-DO-MVP
*Домашнее задание из курса Артёма Русова "Функциональное тестирование ПО"*

Тестирование проводилось на эмуляторе смартфона в Android Studio

Для выполнения задания декомпозировала задачу на список пунктов:
1. Mind map
2. Чек-лист
3. Тест-кейсы
4. Баг-репорты

## Mind map
После первого знакомства с приложением я составила интеллектуальную карту, в которой показала функциональности

![TO DO app](https://github.com/juuliadidenko/mobile_app_testing/assets/104693196/b7f61770-6604-49af-8aac-fe2c2c44b489)

Благодаря такой схеме создала чек-лист проверок

## Чек-лист
Для работы над чек-листом использовала Google таблицу. Разбила каждый модуль из интеллектуальной карты на подмодули с элементами и функциями. В комментариях к проверкам добавила суть дефектов. 
Для проверки полей ввода (названия и описания to-do) выделила позитивные и негативные классы эквивалентности (сочетание латиницы и спецсимволов, латиницы и эмодзи, только цифры и т.д.)  
Таблица находится [по ссылке](https://docs.google.com/spreadsheets/d/1fyChHrYQFxHKjdU32QE4zcwVctQxVEGOE_VMvQUcudQ/edit#gid=0) 
Содержание комментариев взяла за основу для названия баг-репортов

![checklist_table](https://github.com/juuliadidenko/mobile_app_testing/assets/104693196/4db13cc8-bf9d-46c2-ab24-84bc0d98f9c6)

## Тест-кейсы
Тест-кейсы создала в TMS QASE, [здесь](https://github.com/juuliadidenko/mobile_app_testing/blob/main/TO-DO%20test%20cases.pdf) примеры позитивных кейсов

## Баг-репорты
Прохождение проверок из чек-листа помогло мне обнаружить дефекты приложения.
Баг-репорты создала в YouTrack. В кейсах, где приложение падало после выполненных шагов, приложила логи из Android Studio.  
Примеры баг-репортов [здесь]()

