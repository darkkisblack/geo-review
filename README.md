ГЕООТЗЫВ


Выполнил - Кутиков Роман


Наставник - Александр Несвит



Приложение, которое отображает яндекс-карту на всю страницу. На карте можно выбирать объекты и оставлять отзывы о них.

* При клике на карту - открывайте балун с формой для отзыва;

* После заполнения формы и нажатия на кнопку "Добавить", балун с формой закрывается, а на карту добавляется плейсмарк по тем координатам, по которым был открыт балун;

* Отзывы поблизости группируются в одну метку. У сгруппированных меток выводится их количество;

* При нажатии на сгруппированный объект открывается карусель отзывов. При нажатии на адрес в карусели откроется окно с отзывами по данному адресу; 

* При масштабировании карты, происходит группировка меток;

* При перезагрузке страницы, все отзывы и плейсмарки восстанавливаются. Для реализации этой задачи использован сервер на node.js/


Инструкция по запуску приложения:

1. Склонировать себе сборку;

2. Распоковать, используя команду npm install;

3. Запустить сервер, для этого необходимо открыть папку server в терминале и ввести команду node index.js;

4. Запустить скрипт, используя команду npm start;

5. В окне брауера ввести http://localhost:8080/geo-review-3
