# 4. Non-Functional Requirements

## NFR Table

| # | Category | Requirement | Acceptance Criterion |
|---|----------|-------------|----------------------|
| NFR-01 | Performance | [Сторінка каталогу завантажується не довше 2 с при 100 одночасних користувачах] | [Навантажувальний тест (k6/JMeter): 95-й перцентиль ≤ 2 с] |
| NFR-02 | Performance | [API-відповідь на пошук та фільтрацію ≤ 500 мс] | [Середній час відповіді ≤ 500 мс (Postman/Swagger)] |
| NFR-03 | Usability | [Новий користувач реєструється й публікує оголошення менш ніж за 5 хвилин] | [HЮзабіліті-тест з 3 користувачами] |
| NFR-04 | Usability | [Your requirement] | [How to verify] |
| NFR-05 | Responsiveness | [Інтерфейс коректно працює від 375 px до 1920 px] | [Тестування в DevTools + Playwright] |
| NFR-06 | Responsiveness | [Підтримка актуальних Chrome, Firefox, Edge] | [Крос-браузерне тестування] |
| NFR-07 | Security | [Паролі тільки хешовані (bcrypt), передача даних тільки HTTPS] | [Аудит БД + OWASP ZAP] |

---

## Category Reference

| Category | Examples |
|----------|----------|
| Performance | Response time, throughput, load capacity |
| Security | Authentication, data encryption, input validation |
| Compatibility | Browsers, OS, screen sizes |
| Reliability | Uptime, error recovery, data backup |
| Usability (UX) | Accessibility, onboarding, error messages |
| Responsiveness | Mobile layout, screen sizes |
| Export | File formats, print-readiness |

---

## ✅ Submission Checklist

- [ ] Vision is complete — problem, solution, scope
- [ ] Use Case diagram is inserted in [Use Cases](Use-Cases)
- [ ] Use Case list covers all main scenarios
- [ ] User Stories are grouped by Use Case
- [ ] At least 10 User Stories total
- [ ] Each User Story has at least 3 acceptance criteria
- [ ] Priority (🔴 / 🟡 / 🟢) is set for every User Story
- [ ] NFR table has at least 5 entries with measurable criteria
- [ ] All `[brackets]` replaced with real content
- [ ] Team info and date filled in on [Home](Home)

---

← [User Stories](User-Stories) | [Home](Home)
