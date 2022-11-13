## Теоретичні питання

1. Опишіть своїми словами різницю між функціями `setTimeout()` і `setInterval(`)`.
setTimeout - запускає колбек-функцію тільки 1 раз через заданий інтервал,
setInterval - запускає колбек-функцію циклічно кожен інтервал

2. Що станеться, якщо в функцію `setTimeout()` передати нульову затримку? Чи спрацює вона миттєво і чому?
Вона спрацює лише після виконання коду

3. Чому важливо не забувати викликати функцію `clearInterval()`, коли раніше створений цикл запуску вам вже не потрібен?
 ВОна потрібна щоб зупинити функцію setInterval() та очистити память.


## Завдання

Реалізувати програму, яка циклічно показує різні картинки. Завдання має бути виконане на чистому Javascript без використання бібліотек типу jQuery або React.

#### Технічні вимоги:

- У папці `banners` лежить HTML код та папка з картинками.
- При запуску програми на екрані має відображатись перша картинка.
- Через 3 секунди замість неї має бути показано друга картинка.
- Ще через 3 секунди – третя.
- Ще через 3 секунди – четверта.
- Після того, як будуть показані всі картинки - цей цикл має розпочатися наново.
- Після запуску програми десь на екрані має з'явитись кнопка з написом `Припинити`.
- Після натискання на кнопку `Припинити` цикл завершується, на екрані залишається показаною та картинка, яка була там при натисканні кнопки.
- Поруч із кнопкою `Припинити` має бути кнопка `Відновити показ`, при натисканні якої цикл триває з тієї картинки, яка в даний момент показана на екрані.
- Розмітку можна змінювати, додавати потрібні класи, ID, атрибути, теги. 

#### Необов'язкове завдання підвищеної складності
- При запуску програми на екрані повинен бути таймер з секундами та мілісекундами, що показує, скільки залишилося до показу наступної картинки.
- Робити приховування картинки та показ нової картинки поступовим (анімація fadeOut/fadeIn) протягом 0.5 секунди.

#### Література:
- [setTimeout и setInterval](https://learn.javascript.ru/settimeout-setinterval)
