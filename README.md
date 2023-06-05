# Vue micro cousre

## Сторінки

- Intro
- Map
- Login
- Register

## Modlue1. Компоненти та стилі
- Встановлення Вью
    - Встановлення VScode розширення
    - Встановлення вью за допомогою Vite
    - Додавання Prettier and ESlint
- знайомство з базовою структурою папок і файлів
- Сигнатура створення Vue компонента
    - Описання SFC(single file component)
    - створення першого компонента
- Додавання стилів
    - З використанням звичайних стилів
    - Додавання тегу `scoped` для ізоляції стилів
    - Описання додатковів методів стилізації
    - Підєднання Tailwind
- Практика
    - Створення першої сторнінки

## Module2. Робота з шаблоном
- відображення
    - умовний рендеринг
    - відображдення колекцій
    - основні директиви
- Слоти
    - default слот
    - іменовапі слоти
- Практика
    - перероблюємо layout під іменновані слоти футеру і хедеру
    - додаємо сторінку логінізації

## Modlue3. Стан компонента та івенти
- Дата байндинг
    - data - для створення локального стейту
    - ref 
    - reactive
    - ref vs reactive
    - computed
- Props компонрентів
    - defineProps
    - v-bind
    - для чого використовувати $options
    - вивeдення сирого HTML
    - як передати усі пропси до дочірнього елемента
- Events
    - Базові івенти html тегів та слухання їх
    - підписатись на івент
    - Emitting Events
    - Event Arguments
    - Не забуваэмо оголошувати еміти(Declaring Emitted Events)
    - як передати усі івенти до дочірнього елемента
- Watch
    - як описується і коли виористовувати
    - основні налаштування вотч

- v-model
    - Де застосовуэться та з чого сладається
    - Пишемо свій v-model
    - Використання декількох v-model
    - робота з формою
- devtools
    - Підключаємо VUE devtools
    - Основні можливості девтулзів

- Практичне завдання
    - додаємо сторінку регістрації
    - додаємо сабміт форми для логіну і регістрації

## Modlue4. Хуки життєвого циклу(Life Cycle Hooks)
- Опис основних хуків
- Робота з апі запитами
- Composable
    - Вдімінність Composables від React hooks
    - робимо кастомний композабл для api запитів
- Практика
    - Створюємо основну сторінку з картою
    - Опис як додати карту на проект
    - додаємо бібліотеку попапів
    - реалізуємо логіку додавання, редагування або видалення нашого маркеру

## Modlue5. Роутинг
- Налштування
    - додаємо роутинг на проект
    - опис основних налаштуваннь роутингу
    - динамічні роути
    - лезі роути
Практика
    - налаштовуємо лейзі роутинг для наших сторінок

## Modlue6. Глобальний стейт менеджмент
- Опис основних стейменджерів
    - Vuex
    - Pinya
- вбудованні можливості стейтменжменту
    - provide/inject коли використовувати
    - створення властного provide/inject
    - Як працювати з реактивністю в Provide / inject
- Практика
    - додаємо данні юзера до Pinya
    - адптуємо глобальний стейт до нашого логіну зі збереженням токену

## Modlue7. Вбудованні компоненти
- Transition
- KeepAlive
- Teleport
- Suspense(під питанням так як ще під експерементальним прапорцем)
- Практика
    - додаємо транзішини до нашого роутинга
    - додаємо портали до модалок

## Modlue8. Додаткові можливості
- Template Refs
- Кастомні директиви(поради про те що краще їх не писати)
- Scoped Slots​

