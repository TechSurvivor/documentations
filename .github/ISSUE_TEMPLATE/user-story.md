---
name: User Story
about: Створення нової User Story
title: ''
labels: user-story
assignees: dinlwee

---

- type: markdown
    attributes:
      value: |
        ## User Story
        Заповніть поля нижче. **Номер**, **Назва**, **Пріоритет**, **Use Case**, **User Story** та **Критерії прийняття** є обов'язковими.

  - type: input
    id: us-id
    attributes:
      label: Номер User Story
      description: Наприклад: US-01
      placeholder: US-01
    validations:
      required: true

  - type: input
    id: title
    attributes:
      label: Назва
      description: Коротка назва історії
      placeholder: Реєстрація акаунту
    validations:
      required: true

  - type: dropdown
    id: priority
    attributes:
      label: Пріоритет
      options:
        - "🔴 Високий"
        - "🟡 Середній"
        - "🟢 Низький"
    validations:
      required: true

  - type: input
    id: use-case
    attributes:
      label: Use Case
      description: Наприклад: UC-01
      placeholder: UC-01
    validations:
      required: true

  - type: textarea
    id: story
    attributes:
      label: User Story
      description: "Формат: Як [роль], я хочу [дія], щоб [цінність]"
      placeholder: Як незареєстрований відвідувач, я хочу зареєструватись у системі, вказавши email і пароль, щоб отримати доступ до функцій платформи.
      value: "Як "
    validations:
      required: true

  - type: textarea
    id: acceptance-criteria
    attributes:
      label: Критерії прийняття
      description: Кожен критерій з нового рядка, починайте з *
      placeholder: |
        * Система приймає email, пароль та тип облікового запису (User / Admin)
        * Якщо email вже використовується — повертається помилка з відповідним повідомленням
        * Після успішної реєстрації користувачеві призначається роль
    validations:
      required: true

  - type: textarea
    id: notes
    attributes:
      label: Нотатки
      description: Технічні деталі, обмеження, крайні випадки (необов'язково)
      placeholder: напр. Редагувати оголошення може лише його власник
    validations:
      required: false
