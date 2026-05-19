# 🌾 АГРО - Информационная система для производства средств защиты растений

<div align="center">

![Version](https://img.shields.io/badge/version-1.0-blue)
![.NET Framework](https://img.shields.io/badge/.NET-4.8-purple)
![C#](https://img.shields.io/badge/C%23-8.0-green)
![SQL Server](https://img.shields.io/badge/SQL%20Server-2019-red)
![License](https://img.shields.io/badge/license-MIT-yellow)

**Автоматизация процессов производства средств защиты растений**

</div>

---

## 📋 О проекте

Информационная система **«АГРО»** разработана для автоматизации производства средств защиты растений. Система объединяет трёх ключечастников производственного цикла в единой цифровой среде.

### 👥 Пользователи системы

| Роль | Обязанности |
|:---|:---|
| 🧪 **Технолог** | Разработка рецептур, технологических карт, управление заказами и партиями |
| 🔬 **Лаборант** | Контроль качества сырья и готовой продукции |
| ⚙️ **Аппаратчик** | Выполнение технологических операций |

---

## 🏗️ Архитектура системы

### 🛠️ Технологический стек

| Компонент | Технология |
|:---|:---|
| Desktop-приложение | WPF (.NET Framework 4.8) |
| API | ASP.NET Web API 2 |
| База данных | Microsoft SQL Server |
| HTTP-клиент | HttpClient |
| Сериализация | Newtonsoft.Json |
| Графика (капча) | SkiaSharp |
| Тестирование | MSTest, xUnit |

---

## 💾 База данных

### Структура БД «AGRO»

База данных содержит **19 таблиц**:

| Таблица | Назначение |
|:---|:---|
| `Users` | Пользователи системы |
| `Roles` | Роли пользователей |
| `Products` | Продукция |
| `Recipes` | Рецептуры |
| `RecipeComposition` | Состав рецептур |
| `ProcessCards` | Технологические карты |
| `ProductionOrders` | Производственные заказы |
| `Batches` | Производственные партии |
| `ProductionSteps` | Шаги производства |
| `Deviations` | Отклонения |
| `LaboratoryTests` | Лабораторные испытания |
| `TestResults` | Результаты испытаний |
| `QualityControl` | Контроль качества |
| `RawMaterialBatches` | Партии сырья |
| `EventLog` | Журнал событий |

### 📊 ERD диаграмма

<img width="893" height="869" alt="ERD" src="https://github.com/user-attachments/assets/5eb2e5d8-2945-4166-92c5-5a72cee6f00f" />

---

## 🔌 API (APIAGRO)

### Основные контроллеры

| Контроллер | Назначение |
|:---|:---|
| `AuthController` | Авторизация и регистрация |
| `ReferenceController` | Справочная информация |
| `RecipesController` | Рецептуры |
| `ProcessCardsController` | Технологические карты |
| `ProductionController` | Заказы и партии |
| `LabController` | Лабораторные испытания |
| `DeviationsController` | Отклонения |


