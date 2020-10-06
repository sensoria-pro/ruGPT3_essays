# AI Journey Junior 
## написание эссе по 4 предметам с помощью ruGPT3

Соревнование NLP-моделей, автоматически пишущих эссе по тексту/ на заданную тему по предметам:
 - русский язык
 - литература
 - история
 - обществознание
  

### Постановка задачи
Необходимо разработать алгоритм, который получает на вход задание - название предмета и сопроводительный текст, тему, и в качестве результата генерирует новое релевантное эссе. В рамках соревнования, решения тестируются на эссе (письменная часть) ЕГЭ.

### Данные
[essays.tar.gz](https://drive.google.com/file/d/1LTRE3JE1T3tXXv_TavWXIUHXp0w8PD24/view?usp=sharing)
 - Русский язык
 - Литература
 - Обществознание
 - История

### Метрики


### Baseline
ruGPT3 large
finetuned on essays
[ссылка на скачивание]()

Пример работы бейслайна:
```
Предмет: литература
Тема: Кем является Чацкий: победителем или побежденным? (по комедии А.С. Грибоедова «Горе от ума»)
Сочинение: В соответствии с теми характеристиками образа, которые дает Грибоедов Чацкому в комедии «Горе от ума», он оказывается так или иначе победителем, поскольку удаляется от людей и не видит их. У Чацкого один путь — к самоубийству. Однако при этом он не производит впечатления побежденного героя. Второй путь Чацкого (эгоцентрический) — сохранить достоинство, и он не рассматривает самоубийство как путь к бессмертию.  Поэтому, на наш взгляд, читателю важно понять, кто такой Чацкий и на каком пути он живет.
На каком пути живет Чацкий? На его взгляд, Чацкому свойственна не только всеядность: способность говорить как человек, не чуждый эгоизму и самолюбованию. В его внутренней «темнице» развиваются внутренние конфликты, связанные с его судьбой. Чацкий хотел быть «добрым помещиком». Он хотел служить обществу, но оказался неудачником. Можно ли назвать его победителем? Нам представляется, что нет. Чацкий живет в противоречии с самим собой. Будучи членом дворянского общества, он должен служить ему, но не может соответствовать его требованиям. Человек чести должен служить своей стране, но при этом не хочет быть для общества слугой. Только вера в лучшие идеалы может помочь человеку сохранить свое достоинство.
```


### Формат решений

Организаторам необходимо прислать:
 - архив с решениями
 - архив с воспроизводимым кодом/Colab-ноутбук с обучением и генерацией
