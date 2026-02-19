---
title: Политика конфиденциальности / Privacy Policy
layout: default
---

# Политика конфиденциальности / Privacy Policy

**Дата вступления в силу / Effective date:** 16 февраля 2026

---

# РУССКАЯ ВЕРСИЯ

## 1. Кто мы

**Wellbeing App** — мобильное приложение для ежедневной заботы о себе и wellness с функцией ежедневной кнопки «Всё хорошо», журналом благодарности и опциональными напоминаниями buddy.

Оператор персональных данных: **Wellbeing App**.

По вопросам, связанным с обработкой персональных данных, обращайтесь: **support@wellbeing.app**.

---

## 2. Какие данные мы собираем

### 2.1. Данные учётной записи

- **Телефонный номер** — при регистрации через SMS или для уведомлений (если вы вошли через Google)
- **Имя и фамилия** — для персонализации приложения
- **Email** — при входе через Google Sign-In (если предоставлен провайдером)
- **Имя пользователя Telegram** — для уведомлений и buddy
- **Buddy (доверенный друг)** — телефон или Telegram выбранного вами человека, которому будет отправлено напоминание при длительной неактивности (48 часов без нажатия кнопки)

### 2.2. Пользовательский контент

- **Записи благодарности** — текст, который вы вносите в журнал благодарности
- **Нажатия кнопки «Всё хорошо»** — время и дата нажатий для расчёта статистики и серий (streak)
- **Достижения** — разблокированные достижения в приложении

### 2.3. Данные устройства и технические данные

- **Push-токен** (FCM) — для отправки уведомлений на Android
- **Тип устройства** (iOS/Android) и **версия приложения** — для технической поддержки и совместимости
- **Идентификатор устройства** — для привязки push-токена к вашему аккаунту

### 2.4. Данные подписки и платежей

- **Статус подписки** — активна, пробный период, истекла, отменена
- **Даты подписки** — начало, окончание, следующее списание
- Платежи обрабатываются через **СБП (Система быстрых платежей)** на стороне сервера. Мы не храним данные банковских карт на наших серверах.

### 2.5. Аналитика (без персональных данных)

Мы используем **PostHog** для анализа использования приложения. В аналитику **не передаются**:

- email, телефон, имена
- текст записей благодарности или журнала
- точная геолокация

Передаются только обезличенные данные: платформа (Android/iOS), версия приложения, язык, часовой пояс, тип события (например, «сессия начата», «кнопка нажата»).

---

## 3. Для чего мы используем данные

- **Предоставление сервиса** — работа приложения, синхронизация данных, напоминания
- **Напоминания buddy** — отправка SMS или сообщения в Telegram вашему контакту, если вы не нажимали кнопку 48 часов подряд
- **Улучшение приложения** — анализ обезличенной статистики использования
- **Поддержка** — ответы на обращения по email
- **Платежи** — обработка подписки через СБП

---

## 4. Сторонние сервисы

| Сервис | Назначение | Политика конфиденциальности |
|--------|------------|-----------------------------|
| **Supabase** | Хостинг, аутентификация, база данных | [supabase.com/privacy](https://supabase.com/privacy) |
| **Firebase (FCM)** | Push-уведомления на Android | [firebase.google.com/support/privacy](https://firebase.google.com/support/privacy) |
| **PostHog** | Аналитика (без PII) | [posthog.com/privacy](https://posthog.com/privacy) |
| **Google Sign-In** | Вход через Google | [policies.google.com/privacy](https://policies.google.com/privacy) |
| **Apple Sign-In** | Вход через Apple | [apple.com/legal/privacy](https://www.apple.com/legal/privacy/) |
| **СБП** | Платежи в РФ | Обработка на стороне банка и платёжного провайдера |

---

## 5. Хранение и безопасность

- **Серверы** — данные хранятся в Supabase (PostgreSQL) с включённым Row Level Security (RLS). Каждый пользователь имеет доступ только к своим данным.
- **Локальное хранение** — токены доступа хранятся в зашифрованном виде (EncryptedSharedPreferences на Android, защищённое хранилище на iOS).
- **Передача** — используется HTTPS для всех сетевых запросов.

---

## 6. Права пользователей

Вы имеете право:

- **Доступ** — запросить копию своих персональных данных
- **Исправление** — изменить данные в настройках профиля или через поддержку
- **Удаление** — удалить аккаунт и все связанные данные (см. раздел 7)
- **Отзыв согласия** — прекратить использование приложения и удалить аккаунт

Для пользователей из ЕС/ЕЭП применимы права по GDPR. Для пользователей из Калифорнии — права по CCPA.

---

## 7. Удаление аккаунта

Вы можете удалить аккаунт в разделе **Профиль → Удалить аккаунт**. Это действие **необратимо**.

При удалении аккаунта мы:

1. Удаляем ваши данные из Supabase (профиль, записи благодарности, нажатия, достижения, настройки, push-токены, подписки)
2. Удаляем связанные данные аналитики в PostHog
3. Очищаем локальные данные на вашем устройстве (токены, кэш)

После удаления восстановление данных невозможно.

Подробная инструкция: [Запрос на удаление аккаунта](delete-account)

---

## 8. Дети

Приложение не предназначено для лиц младше 16 лет. Мы не собираем осознанно персональные данные детей. Если вы узнали, что ребёнок предоставил нам данные, пожалуйста, напишите на support@wellbeing.app — мы удалим их.

---

## 9. Изменения политики

Мы можем обновлять эту политику. О существенных изменениях мы уведомим через приложение или по email. Дата последнего обновления указана в начале документа.

Продолжая использовать приложение после публикации изменений, вы соглашаетесь с обновлённой политикой.

---

## 10. Контакты

**Wellbeing App**  
Email: **support@wellbeing.app**  
Сайт: wellbeing.app

---

---

# ENGLISH VERSION

## 1. Who We Are

**Wellbeing App** is a mobile application for daily self-care and wellness with a daily "I'm okay" button, gratitude journal, and optional buddy reminders.

Data controller: **Wellbeing App**.

For questions regarding the processing of personal data, contact: **support@wellbeing.app**.

---

## 2. What Data We Collect

### 2.1. Account Data

- **Phone number** — when registering via SMS or for notifications (if you signed in with Google)
- **First and last name** — for app personalization
- **Email** — when signing in with Google Sign-In (if provided by the provider)
- **Telegram username** — for notifications and buddy
- **Buddy (trusted friend)** — phone number or Telegram of a person you choose, who will receive a reminder if you are inactive for 48 hours without pressing the button

### 2.2. User Content

- **Gratitude entries** — text you add to the gratitude journal
- **"I'm okay" button presses** — date and time of presses for statistics and streak calculation
- **Achievements** — unlocked achievements in the app

### 2.3. Device and Technical Data

- **Push token** (FCM) — for sending notifications on Android
- **Device type** (iOS/Android) and **app version** — for technical support and compatibility
- **Device identifier** — to link the push token to your account

### 2.4. Subscription and Payment Data

- **Subscription status** — active, trial, expired, cancelled
- **Subscription dates** — start, end, next billing
- Payments are processed via **SBP (Faster Payment System)** on the server side. We do not store bank card data on our servers.

### 2.5. Analytics (No Personal Data)

We use **PostHog** to analyze app usage. The following are **not** sent to analytics:

- email, phone numbers, names
- text of gratitude entries or journal
- exact geolocation

Only anonymized data is sent: platform (Android/iOS), app version, language, timezone, event type (e.g., "session started", "button pressed").

---

## 3. How We Use the Data

- **Service delivery** — app functionality, data sync, reminders
- **Buddy reminders** — sending SMS or Telegram message to your contact if you have not pressed the button for 48 hours in a row
- **App improvement** — analysis of anonymized usage statistics
- **Support** — responding to inquiries via email
- **Payments** — processing subscription via SBP

---

## 4. Third-Party Services

| Service | Purpose | Privacy Policy |
|---------|---------|----------------|
| **Supabase** | Hosting, authentication, database | [supabase.com/privacy](https://supabase.com/privacy) |
| **Firebase (FCM)** | Push notifications on Android | [firebase.google.com/support/privacy](https://firebase.google.com/support/privacy) |
| **PostHog** | Analytics (no PII) | [posthog.com/privacy](https://posthog.com/privacy) |
| **Google Sign-In** | Sign in with Google | [policies.google.com/privacy](https://policies.google.com/privacy) |
| **Apple Sign-In** | Sign in with Apple | [apple.com/legal/privacy](https://www.apple.com/legal/privacy/) |
| **SBP** | Payments (Russia) | Processed by bank and payment provider |

---

## 5. Storage and Security

- **Servers** — data is stored in Supabase (PostgreSQL) with Row Level Security (RLS) enabled. Each user has access only to their own data.
- **Local storage** — access tokens are stored encrypted (EncryptedSharedPreferences on Android, secure storage on iOS).
- **Transmission** — HTTPS is used for all network requests.

---

## 6. Your Rights

You have the right to:

- **Access** — request a copy of your personal data
- **Correction** — update data in profile settings or via support
- **Deletion** — delete your account and all associated data (see Section 7)
- **Withdraw consent** — stop using the app and delete your account

For users in the EU/EEA, GDPR rights apply. For California users, CCPA rights apply.

---

## 7. Account Deletion

You can delete your account in **Profile → Delete account**. This action is **irreversible**.

When you delete your account, we:

1. Delete your data from Supabase (profile, gratitude entries, button presses, achievements, settings, push tokens, subscriptions)
2. Delete associated analytics data in PostHog
3. Clear local data on your device (tokens, cache)

Data cannot be recovered after deletion.

Detailed instructions: [Account Deletion Request](delete-account)

---

## 8. Children

The app is not intended for persons under 16 years of age. We do not knowingly collect personal data from children. If you learn that a child has provided us with data, please contact support@wellbeing.app — we will delete it.

---

## 9. Policy Changes

We may update this policy. We will notify you of significant changes via the app or by email. The date of the last update is shown at the beginning of this document.

By continuing to use the app after changes are published, you agree to the updated policy.

---

## 10. Contact

**Wellbeing App**  
Email: **support@wellbeing.app**  
Website: wellbeing.app
