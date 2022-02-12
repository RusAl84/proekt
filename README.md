# Приложение дополненной реальности для визуализации содержания ячеек хранения систем складского учета – “Warehouse” 

![hedgehog.png](/hedgehog.png)

**Цель работы:** Разработать приложение для упрощения просмотра содержимого закрытых контейнеров. 

**Задачи:** Создать реалистичные контейнеры и их содержащиеся в них предметы хранения. Прописать элементы управления этими предметами без физического вскрытия контейнера; функцию визуального сохранения и изменения положения предметов; добавить возможность создавать дополнительные предметы; создать удобный виртуальный интерфейс. 

**Этапы исследования:** Было создано несколько различных контейнеров и предметов подходящим к этим контейнерам. Код писался на языке программирования C#. Каждый контейнер был привязан к своей внешней метке – ImageTarget. Перенос проекта в дополненную реальность совершён с помощью технологии Vuforia.  

**Методы исследования и оборудование:** Программное обеспечение (Unity 3D, 
Vuforia), компьютер под управлением OS Windows и телефон Android. Для создания правдоподобных элементов управления складом было проведено ознакомление с несколькими системами складского учёта. 

**Исправление ошибок:** В ходе разработки остались невыясненными некоторые вопросы, связанные с управлением системой координат дополненной реальности (возможно, ошибка в стандартной библиотеке разработчика), что будет дальнейшим направлением для исследования. В настоящий момент, код использующий эти функции временно не используется. 

**Результаты:** В результате была создана система виртуального доступа внутрь закрытых контейнеров для контроля и управления их содержимым. Управление происходит с телефона, который сканирует камерой метку контейнера, и с экрана телефона может управлять его содержимым. 

**Перспективы проекта:** Данный проект пригодится на любом складском предприятии, при управлении перевозками, в быту. С помощью этого приложения пользователь может эффективно организовывать поиск и управление предметами, даже не имея к ним физического доступа. Возможно разграничение прав доступа, хранение истории изменений. 

[**Ссылка на презентацию**](/docs/Фамилия_И_О_Презентация_ИТ.pdf)
