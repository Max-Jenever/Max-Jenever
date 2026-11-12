### Обо мне
Backend / Systems Developer. Специализируюсь на разработке высоконагруженных систем, микросервисной архитектуре и низкоуровневом программировании. Имею опыт создания производительных приложений с использованием асинхронных паттернов и межъязыкового взаимодействия.

---

<p align="center">
  <img src="https://media1.tenor.com/m/VpOrXjIJhHgAAAAC/rust-ferris.gif" alt="Developer Animation" width="100%" />
</p>

---

### Проекты

#### 1. [datanvil](https://github.com/Max-Jenever/datanvil)
Распределенная система для приема, нормализации и агрегации высокоскоростных потоков данных в реальном времени. Обеспечивает высокую пропускную способность, низкую задержку (low latency) и гарантированную доставку сообщений в условиях неравномерной нагрузки.
- **Стек:** ![Rust](https://img.shields.io/badge/Rust-000000?style=flat-square&logo=rust&logoColor=white) ![Tokio](https://img.shields.io/badge/Tokio-Async-orange?style=flat-square) ![Kafka](https://img.shields.io/badge/Kafka-Broker-231F20?style=flat-square&logo=apache-kafka&logoColor=white) ![PostgreSQL](https://img.shields.io/badge/PostgreSQL-316192?style=flat-square&logo=postgresql&logoColor=white) ![Redis](https://img.shields.io/badge/Redis-DC382D?style=flat-square&logo=redis&logoColor=white)
- **Ключевые особенности:**
  - **Асинхронная архитектура:** Реализация неблокирующей обработки потоков на базе Tokio, обеспечивающая эффективное использование ресурсов CPU и памяти.
  - **Межъязыковая интеграция:** Подключение оптимизированных C-библиотек через безопасный FFI-интерфейс для ресурсоемких операций.
  - **Отказоустойчивость:** Использование Apache Kafka для буферизации событий и реализации паттернов гарантированной доставки (включая обработку Dead Letter Queue).
  - **Управление состоянием:** Кэширование промежуточных результатов агрегации в Redis для минимизации задержек и персистентное хранение итоговых метаданных в PostgreSQL.
- **Ссылки:** [Репозиторий](https://github.com/Max-Jenever/datanvil)

#### 2. [arlloc](https://github.com/Max-Jenever/arlloc)
Высокопроизводительный арена-аллокатор памяти (bump allocator) с ядром на языке C и безопасной оберткой на Rust.
- **Стек:** ![C](https://img.shields.io/badge/C-00599C?style=flat-square&logo=c&logoColor=white) ![Rust](https://img.shields.io/badge/Rust-000000?style=flat-square&logo=rust&logoColor=white) 
- **Ключевые особенности:** Обеспечивает выделение памяти за время O(1) без фрагментации, блокировок или системных вызовов в процессе работы.
- **Ссылки:** [Репозиторий](https://github.com/Max-Jenever/arlloc) | [Документация](https://max-jenever.github.io/arlloc/)

---

### Технологический стек

<p align="left">
  <img src="https://img.shields.io/badge/Rust-000000?style=for-the-badge&logo=rust&logoColor=white" />
  <img src="https://img.shields.io/badge/C-00599C?style=for-the-badge&logo=c&logoColor=white" />
  
  <img src="https://img.shields.io/badge/PostgreSQL-316192?style=for-the-badge&logo=postgresql&logoColor=white" />
  <img src="https://img.shields.io/badge/Apache_Kafka-231F20?style=for-the-badge&logo=apache-kafka&logoColor=white" />
  <img src="https://img.shields.io/badge/Redis-DC382D?style=for-the-badge&logo=redis&logoColor=white" />
  
  <img src="https://img.shields.io/badge/Tokio-Async_Runtime-orange?style=for-the-badge&logoColor=white" />
  <img src="https://img.shields.io/badge/FFI-blueviolet?style=for-the-badge" />
</p>

---

### Контакты
<p align="left">
  <a href="mailto:birovmax@gmail.com">
    <img src="https://img.shields.io/badge/Email-D14836?style=for-the-badge&logo=gmail&logoColor=white" />
  </a>
  <a href="https://t.me/paieufem">
    <img src="https://img.shields.io/badge/Telegram-2CA5E0?style=for-the-badge&logo=telegram&logoColor=white" />
  </a>
</p>
