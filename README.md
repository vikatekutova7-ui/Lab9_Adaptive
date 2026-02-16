# Лабораторная работа №9. Адаптивная верстка: Медиа-запросы

---

## Структура проекта

- index.html — основная HTML-разметка
- styles.css — стили проекта index.html
- responsive.html — создание адаптивного макета
- responsive.css — стили для responsive.html
- README.md — для описания
- img/ — папка для скриншотов
- nav-practice.html — создание адаптивного меню
- nav-practice.css — стили для nav-practice.html
- flexbox-practice.html — создание Flexbox-макета
- flexbox-practice.css — стили для flexbox-practice.html

---

## Описание

**Цель работы:** Изучить принципы адаптивной верстки и медиа-запросов. В конце создать адаптивную страницу портфолио, которая корректно отображается на всех устройствах.

---

## Теория. Медиа-запросы и адаптивность

**Медиа-запросы (Media Queries)** — это техника CSS, которая позволяет применять разные стили в зависимости от характеристик устройства (ширина экрана, ориентация, разрешение).

Синтаксис медиа-запросов:
```css
@media (условие) {
    /* стили для этого условия */
}
```

## Примеры 
```css
/* Для экранов шириной до 768px */
@media (max-width: 768px) {
    .container {
        flex-direction: column;
    }
}
/* Для экранов шириной от 1024px */
@media (min-width: 1024px) {
    .container {
        grid-template-columns: repeat(4, 1fr);
    }
}
/* Диапазон */
@media (min-width: 768px) and (max-width: 1023px) {
    .container {
        grid-template-columns: repeat(2, 1fr);
    }
}
```
## Как запустить проект
```bash
git clone <URL_репозитория>
```

---

## Автор
Текутова В.Д.
ИСП-231