name: User Story
description: Створення нової User Story
labels: ["user story"]

body:
  - type: markdown
    attributes:
      value: |
        ## Нова User Story
        Заповніть поля нижче. Після створення видачі **змініть заголовок** на формат:
        `US-XX — Назва історії 🔴 Високий`

  - type: input
    id: us-id
    attributes:
      label: Номер User Story
      placeholder: US-05
      description: Наприклад: US-05
    validations:
      required: true

  - type: input
    id: title
    attributes:
      label: Назва User Story
      placeholder: Створення оголошення
      description: Коротка назва
    validations:
      required: true

  - type: dropdown
    id: priority
    attributes:
      label: Пріоритет
      options:
        - 🔴 Високий
        - 🟡 Середній
        - 🟢 Низький
    validations:
      required: true

  - type: input
    id: uc
    attributes:
      label: Повязаний Use Case
      placeholder: UC-03
      description: Наприклад: UC-03
    validations:
      required: true

  - type: textarea
    id: story
    attributes:
      label: User Story
      description: "Формат: Як [роль], я хочу [дія], щоб [цінність]"
      placeholder: Як авторизований користувач, я хочу створити оголошення з назвою, описом і ціною, щоб інші користувачі могли знайти мій товар.
      value: "Як "
    validations:
      required: true

  - type: textarea
    id: acceptance
    attributes:
      label: Критерії прийняття
      description: Кожен критерій з нового рядка, починайте з *
      placeholder: |
        * Оголошення зберігається з прив'язкою до авторизованого користувача
        * Поля title, price, categoryId є обов'язковими
        * Після створення встановлюється статус Active
    validations:
      required: true

  - type: textarea
    id: notes
    attributes:
      label: Додаткові нотатки
      description: Технічні деталі, обмеження, крайні випадки (необов'язково)
      placeholder: Редагувати оголошення може лише власник
    validations:
      required: false
