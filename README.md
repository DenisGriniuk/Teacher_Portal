----
![Header](https://github.com/DenisGriniuk/My_work_1/blob/main/assets/Skyeng.jpg)
<br><br>
**Продукт: _портал для преподавателей_**

**Заказчик: _Компания “Skyeng”_**

**Сайт: _Портал учителя Skyeng (вкладка Расписание)_**

----
### Основные требования (главная user-story): 
_Мы добавили в календарь новый элемент — личные события. Преподаватель может использовать личные события для собственных встреч. Они служат напоминанием, что у преподавателя что-то запланировано на это время._

### Все требования можно посмотреть по ссылке: 
[Документация к проекту](https://skyengpublic.notion.site/282e0bc0c4c342bd8081a8c34fcec026)

----
- **Анализ требований, основанный на документации к проекту:**

><img src="https://github.com/DenisGriniuk/My_work_1/blob/main/assets/Requirements_1.jpg?raw=true" width="600">
><img src="https://github.com/DenisGriniuk/My_work_1/blob/main/assets/Requirements_2.jpg?raw=true" width="600">
><img src="https://github.com/DenisGriniuk/My_work_1/blob/main/assets/Requirements_3.jpg?raw=true" width="600">

- **Декомпозиция в Miro:** 
[Функционал "Личные события"](https://miro.com/app/board/uXjVPURZ520=/)

Пример:

><img src="https://github.com/DenisGriniuk/My_work_1/blob/main/assets/Decomposition_1.jpg?raw=true" width="600">

### Были проведены следующие виды тестирования:

- **Smoke-тестирование:**

>![smoke](https://github.com/DenisGriniuk/My_work_1/blob/main/assets/smoke.jpg)

Пример:

>>![smoke](https://github.com/DenisGriniuk/My_work_1/blob/main/assets/smoke_testing_1.jpg)
>>![smoke](https://github.com/DenisGriniuk/My_work_1/blob/main/assets/smoke_testing_2.jpg)

- **Тестирование новой функциональности:**

>[Операции с личными событиями.pdf](https://github.com/DenisGriniuk/My_work_1/blob/main/assets/%D0%A2%D0%B5%D1%81%D1%82%D0%B8%D1%80%D0%BE%D0%B2%D0%B0%D0%BD%D0%B8%D0%B5%20%D0%BD%D0%BE%D0%B2%D0%BE%D0%B9%20%D1%84%D1%83%D0%BD%D0%BA%D1%86%D0%B8%D0%BE%D0%BD%D0%B0%D0%BB%D1%8C%D0%BD%D0%BE%D1%81%D1%82%D0%B8.pdf "PDF")

- **Тестирование API:**

><img src="https://github.com/DenisGriniuk/My_work_1/blob/main/assets/API_1.jpg?raw=true" width="800">

- **Приемочное тестирование:**

>![acceptance](https://github.com/DenisGriniuk/My_work_1/blob/main/assets/Acceptance_testing.jpg)

Пример:

>>![acceptance](https://github.com/DenisGriniuk/My_work_1/blob/main/assets/acceptance_testing_1.jpg)
>>![acceptance](https://github.com/DenisGriniuk/My_work_1/blob/main/assets/acceptance_testing_2.jpg)

- **Регрессионное тестирование:**

>[Регресс в итогом проекте.pdf](https://github.com/DenisGriniuk/My_work_1/blob/main/assets/%D0%A0%D0%B5%D0%B3%D1%80%D0%B5%D1%81%D1%81%20%D0%B2%20%D0%B8%D1%82%D0%BE%D0%B3%D0%BE%D0%BC%20%D0%BF%D1%80%D0%BE%D0%B5%D0%BA%D1%82%D0%B5.pdf "PDF")

---

- **Баг репорты по новому функционалу, API:**

Пример:

><img src="https://github.com/DenisGriniuk/My_work_1/blob/main/assets/bug_API.jpg?raw=true" width="800">

- **Баг репорты регресс тестирования:** 

Пример:

><img src="https://github.com/DenisGriniuk/My_work_1/blob/main/assets/bug_regress.jpg?raw=true" width="800">

----

### Отчёт о тестировании:

_При тестировании новой функциональности “Личные события” был обнаружен один баг “Урок не отображается сверху над событием при добавлении последнего, когда они совпадают по времени” и ему был присвоен приоритет Medium, так как это не влияет на общее пользование сайтом и возможность добавлять, редактировать и удалять события, но не удобно с точки зрения опыта взаимодействия с порталом или UX,  приоритета урока над событием и не совпадает с представленной документацией.
При тестировании API был обнаружен один баг “Создаётся цвет вне дозволенной палитры при создании или редактировании личного события через API”. Ему был присвоен приоритет Low, так как он также не влияет на бизнес-логику портала для учителей, как и предыдущий, и не приносит неудобство пользователям, но противоречит представленной документации._

### Выводы:

_Новый функционал не имеет критических багов. Найдена 2 бага, из которых первый имеет приоритет Medium, а второй Low. Следовательно, новый функционал к релизу готов, но исследовательское тестирование показало критические баги в основной функциональности, связанной с уроками. Например, такие, как невозможность отменить урок ни по инициативе учителя, ни по инициативе ученика. Следовательно, продукт не готов к выпуску на данной стадии разработки и требует исправлений._











