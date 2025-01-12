# All-FROND_LANG
Тут ви знайдете все про HTML, CSS, SCSS тощо.

---

## 📚 Перший урок: Основи HTML

Поїхали! Т_Т

---

### 1. Створення файлу `index.html`
Створіть файл `index.html`, щоб почати роботу.

---

### 2. Як створити головний скелет HTML?

Все дуже просто! Якщо виникнуть питання, ось стандартний шаблон:

```html
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Document</title>
</head>
<body>
    
</body>
</html>
```

Щоб швидко створити такий скелет, просто напишіть ! і натисніть Tab або Enter (цей шорткат працює в більшості редакторів коду, наприклад, Visual Studio Code).

### 3. Чи можна вкладати якийсь елемент в якийсь, і як це перевірти?

Наприклад:

```html
<p><h1></h1></p>
```
Виникло питання, чи це допустимо? Для цього звернемося до документації HTML. Ви можете знайти всю необхідну інформацію за цим посиланням:
👉 [HTML Spec](https://html.spec.whatwg.org/multipage/)

## Як знайти відповідь:

1. Перейдіть до розділу **4 The elements of HTML**.
2. Відкрийте підрозділ **4.4 Grouping content**.
3. Перегляньте опис елементів, які вас цікавлять. У нашому випадку це:
   - **4.4.1 The p element**
   - **4.3.6 The h1, h2, h3, h4, h5, and h6 elements**

## Що ми бачимо в документації?

- Для **4.4.1 The p element**:
  - Категорії:
    - Flow content
    - Palpable content

- Для **4.3.6 The h1, h2, h3, h4, h5, and h6 elements**:
  - Категорії:
    - Flow content
    - Heading content
    - Palpable content

## Висновок:

Елементи `<h1>` та `<p>` **не можуть бути використані разом**.  
Причина в тому, що `<h1>` відноситься до **Heading content** (заголовки), тоді як `<p>` є **параграфним елементом**. 

Якщо ви напишете код так:

```html
<p><h1>Заголовок</h1></p>
```

Браузер автоматично інтерпретує його так:

```html
<p></p>
<h1>Заголовок</h1>
<p></p>
```

Тобто, браузер закриє <p> до того, як почнеться <h1>, і результат може не відповідати нашим очікуванням.













<!-- # All-FROND_LANG
Here you can find everything about HTML, CSS, SCSS, etc.

Отже, це перший урок наш, поїхали Т_Т:

1) Створюємо index.html файл, далі
2) Для того якщо у вас виникнуть питання як в html створити головний скелет:

<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Document</title>
</head>
<body>
    
</body>
</html>

То все просто, пишете ! і нажимаєте Tab/Enter

3) Якщо у вас виникнуть питання, чи можна ставити в елемент h1 в елемент p Приклад:

<p><h1></h1></p>

То тут вам допоможе документація за цим посиланням: https://html.spec.whatwg.org/multipage/

переходимо туди, шукаємо пункт: 4 The elements of HTML, далі 4.4 Grouping content, і тут вже відкриваємо елементи які ми не знаємо чи можна їх поєднювати разом, у нашому випадку це елемент p і h1, відкриваємо:

4.4.1 The p element і 4.3.6 The h1, h2, h3, h4, h5, and h6 elements

Дивимось в категорії (Categories):

у нас в 4.4.1 The p element категорія: 
- Flow content.
- Palpable content.
а в 4.3.6 The h1, h2, h3, h4, h5, and h6 elements:
- Flow content.
- Heading content.
- Palpable content.

Як бачимо вони не можуть бути разом, оскільки h1, h2, h3, h4, h5 і h6 це є Heading content, тобто головний контент, поки p це параграфний елемент, якщо ми їх так напишемо (<p><h1></h1></p>), то наша сторінка інтепруватиме їх так:

<p></p>
<h1>Heading</h1>
<p></p> -->

