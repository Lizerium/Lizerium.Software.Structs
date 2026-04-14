<h1 align="center">🖥️ Lizerium.Software.Structs 🖥️</h1>

<p align="center">
  Структурная карта основных программных продуктов, системных модулей и прикладных узлов экосистемы Lizerium
</p>

<div align="center" style="margin: 20px 0; padding: 10px; background: #1c1917; border-radius: 10px;">
  <strong>🌐 Язык: </strong>
  
  <span style="color: #F5F752; margin: 0 10px;">
    ✅ 🇷🇺 Русский (текущий)
  </span>
  | 
  <a href="./README.md" style="color: #0891b2; margin: 0 10px;">
    🇺🇸 English
  </a>
</div>

---

> [!NOTE]
> Этот проект является частью экосистемы **Lizerium** и относится к направлению:
>
> - [`Lizerium.Hub`](https://github.com/Lizerium/Lizerium.Hub)
>
> Если вы ищете связанные инженерные и вспомогательные инструменты, начните оттуда.

## Назначение

Этот репозиторий является **структурным индексом основного software-контура** внутри экосистемы **Lizerium**.

Он не является основной реализацией, а служит как:

- карта ключевых программных компонентов
- точка навигации по software-архитектуре экосистемы
- описание ролей прикладных систем
- место для логической классификации основных программных продуктов
- слой архитектурного обзора operational software-контура

---

## Роль в экосистеме

Этот репозиторий помогает понять:

- какие проекты относятся к основным программным продуктам Lizerium
- как разделены серверные, клиентские, административные и игровые системные узлы
- где находятся точки входа в ключевые программные решения
- как устроена логика взаимодействия между программными компонентами
- какие приложения формируют прикладное ядро экосистемы

---

## Что входит в это направление

### 1. 🌐 Серверная и административная инфраструктура

Основные серверные и административные системы, обеспечивающие управление и сопровождение экосистемы.

- [`LizeriumServer`](https://github.com/Lizerium/LizeriumServer)
- [`Lizerium.FLAdmin`](https://github.com/Lizerium/Lizerium.FLAdmin)
- [`LizeriumAccauntManager`](https://github.com/Lizerium/LizeriumAccauntManager)

---

### 2. 🚀 Распространение и запуск

Программные решения, отвечающие за запуск, обновление и доставку приложений и игровых компонентов.

- [`LizeriumSteam`](https://github.com/Lizerium/LizeriumSteam)

---

### 3. 🎮 Игровые прикладные системы

Основные игровые прикладные продукты и системные модули, взаимодействующие с классической игровой веткой.

- [`LizeriumFLHook`](https://github.com/Lizerium/LizeriumFLHook)
- [`FLGameCompanion`](https://github.com/Lizerium/FLGameCompanion)

---

## Архитектурная схема

```text
Lizerium.Software.Structs
├── Infrastructure
│   ├── LizeriumServer
│   └── Lizerium.FLAdmin
│
├── Distribution
│   └── LizeriumSteam
│
└── Game Software
    ├── LizeriumFLHook
    └── FLGameCompanion
```
