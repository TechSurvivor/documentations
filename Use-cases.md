# 2. Use Cases

## 2.1 Diagram

> Insert your Use Case diagram here.
> Tools: [draw.io](https://draw.io) (free), Lucidchart, PlantUML.
> Drag and drop your image into the Wiki editor — GitHub will insert the link automatically.

[insert image here]

> Actors are outside the system boundary. Use Cases are inside as ellipses.
> Use `<<include>>` when one UC always triggers another. Use `<<extend>>` for optional extensions.

[Актори системи: Незареєстрований відвідувач, Зареєстрований користувач (продавець / покупець), Адміністратор.
Основні зв'язки: «Розміщення оголошення» <<include>> «Авторизація»; «Перегляд оголошення» <<extend>> «Пошук і фільтри».]

---

## 2.2 Use Case List

| UC # | Name | Actor(s) |
|------|------|----------|
| UC-01 | [Реєстрація нового користувача] | [Незареєстрований відвідувач] |
| UC-02 | [Авторизація (вхід в акаунт)] | [Зареєстрований користувач] |
| UC-03 | [Розміщення оголошення] | [Авторизований користувач] |
| UC-04 | [Перегляд каталогу та оголошення] | [Будь-який відвідувач] |
| UC-05 | [Пошук та фільтрація товарів] | [Будь-який відвідувач] |
| UC-06 | [Управління оголошеннями (адмін)] | [Адміністратор] |

---

← [Vision](Vision) | [User Stories →](User-Stories)
