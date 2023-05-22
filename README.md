# Vue micro cousre

## Сторінки

- Intro
- Map
- Marker details
- Login
- Register

## Установка

The recommended IDE setup is VSCode + the Vue Language Features (Volar) extension

```
 npm init vue@latest
> cd <your-project-name>
> npm install
> npm run dev
```

- Базова структура проекту
- Шляхи підключення Vue

## Структура компонента

- що таке SFC
- Тег template
- Тег script

## Основні маніпуляції з шаблоном

- setup() vs <script setup>(згадати про Options API)
- виведення значення в шаблонні
- умовний рендерінг(Conditional Rendering)
- Виведення списку(List Rendering)
- вивeдення сирого HTML

## Реактивність у компонентах

- Як реалізована рективність
- State компонента(ref vs reactive);
- computed props
- watch

## Стилізація компонента

- class and :class
- inline styles
- scoped styles

## Props

- як передаються пропси. Пропси повинні бути readonly
- описання пропсів в компоненті. Різниця в описі між опшнс API та Composition Api
- Передавання усіх пропсів від батьківського компонента в дочірній

## Emiting Events

- Базові івенти html тегів та слухання їх
- підписатись на івент
- Emitting Events
- Event Arguments
- Не забуваэмо оголошувати еміти(Declaring Emitted Events)
- як передати усі івенти до дочірнього елемента

## v-model

- Де застосовуэться та з чого сладається
- Пишемо свій v-model
- Використання декількох v-model
- робота з формою

## Lifecycle Hooks

- опис основних хуків

## Composables

- Вдімінність Composables від React hooks
- Пишемо свій композабл на основі запиту на сервер

## slots

- Базовий слот
- Доступ к даним у слотів
- Fallback Content
- Named Slots
- Scoped Slots​

## Browser Devtools

- Підключаємо VUE devtools
- Основні можливості девтулзів

## Routing

- Базове налаштування роутингу
- дочірні роути
- Lazy routes

* описуємо наші основні роути

## Provide / inject

- Загальний опис
- Provide
- Inject
- Як працювати з реактивністю в Provide / inject

## Piniya

- Що таке стейт менеджмент
- Чому Piniya а не Vuex
- Створення простого стору та підключення його до проекту

## Built-in Components

- Transition
- KeepAlive
- Teleport
- Suspense(під питанням так як ще під експерементальним прапорцем)

## Додатково

- Template Refs
- Кастомні директиви(поради про те що краще їх не писати)
