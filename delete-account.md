---
title: Запрос на удаление аккаунта / Account Deletion Request
layout: default
---

# Запрос на удаление аккаунта / Account Deletion Request

**Wellbeing App** — разработчик приложения Wellbeing App

Эта страница содержит инструкцию по запросу удаления аккаунта и связанных с ним данных в приложении **Wellbeing App**.

---

# РУССКАЯ ВЕРСИЯ

## Как запросить удаление аккаунта

### Способ 1: Через приложение (рекомендуется)

1. Откройте приложение **Wellbeing App** на вашем устройстве.
2. Перейдите в раздел **Профиль** (иконка профиля в нижней навигации).
3. Прокрутите вниз до кнопки **«Удалить аккаунт»**.
4. Нажмите **«Удалить аккаунт»**.
5. Подтвердите действие в диалоговом окне. Обратите внимание: удаление **необратимо**.
6. После подтверждения ваш аккаунт и все связанные данные будут удалены.

### Способ 2: Через поддержку

Если вы не можете войти в приложение или удалить аккаунт самостоятельно:

1. Напишите на **vlrjarsenev@gmail.com**.
2. Укажите email или номер телефона, с которым зарегистрирован аккаунт.
3. Напишите: «Прошу удалить мой аккаунт и все связанные данные».
4. Мы обработаем запрос в течение **14 рабочих дней** и подтвердим удаление по email.

---

## Какие данные будут удалены

При удалении аккаунта мы **полностью удаляем** следующие данные:

| Тип данных | Где хранится | Срок удаления |
|------------|--------------|---------------|
| Профиль (имя, телефон, email, Telegram) | Supabase | Немедленно |
| Записи благодарности (журнал) | Supabase | Немедленно |
| Нажатия кнопки «Всё хорошо» | Supabase | Немедленно |
| Достижения | Supabase | Немедленно |
| Настройки уведомлений | Supabase | Немедленно |
| Push-токены | Supabase | Немедленно |
| Данные подписки | Supabase | Немедленно |
| События аналитики (PostHog) | PostHog | В течение 30 дней |
| Токены и кэш на устройстве | Ваше устройство | При следующем запуске приложения |

Удаление выполняется в течение **48 часов** с момента запроса. Данные аналитики в PostHog удаляются в течение **30 дней** в соответствии с политикой провайдера.

---

## Какие данные не хранятся и не удаляются

- **Платежные данные** (номера карт, реквизиты) — обрабатываются платёжной системой СБП, мы их не храним.
- **Сообщения buddy** — отправляются через SMS/Telegram, мы не храним их содержимое после отправки.

---

## Технические логи

Мы можем сохранять минимальные технические логи об операции удаления (идентификатор запроса, дата, статус) **без** вашего email, телефона или другого персонального содержания. Эти логи используются только для отладки и хранятся не более **90 дней**, доступ к ним имеют только администраторы.

---

## Контакты

**Wellbeing App**  
Email: **vlrjarsenev@gmail.com**

---

---

# ENGLISH VERSION

## How to Request Account Deletion

### Method 1: Through the App (Recommended)

1. Open the **Wellbeing App** on your device.
2. Go to **Profile** (profile icon in the bottom navigation).
3. Scroll down to the **"Delete account"** button.
4. Tap **"Delete account"**.
5. Confirm the action in the dialog. Note: deletion is **irreversible**.
6. After confirmation, your account and all associated data will be deleted.

### Method 2: Via Support

If you cannot log in or delete your account yourself:

1. Email **support@wellbeing.app**.
2. Provide the email or phone number associated with your account.
3. Write: "I request deletion of my account and all associated data."
4. We will process your request within **14 business days** and confirm deletion by email.

---

## What Data Will Be Deleted

When you delete your account, we **permanently delete** the following data:

| Data type | Where stored | Deletion timeframe |
|-----------|--------------|---------------------|
| Profile (name, phone, email, Telegram) | Supabase | Immediately |
| Gratitude entries (journal) | Supabase | Immediately |
| "I'm okay" button presses | Supabase | Immediately |
| Achievements | Supabase | Immediately |
| Notification settings | Supabase | Immediately |
| Push tokens | Supabase | Immediately |
| Subscription data | Supabase | Immediately |
| Analytics events (PostHog) | PostHog | Within 30 days |
| Tokens and cache on device | Your device | On next app launch |

Deletion is completed within **48 hours** of the request. Analytics data in PostHog is deleted within **30 days** in accordance with the provider's policy.

---

## Data We Do Not Store or Delete

- **Payment data** (card numbers, bank details) — processed by the SBP payment system; we do not store it.
- **Buddy reminders messages** — sent via SMS/Telegram; we do not store their content after sending.

---

## Technical Logs

We may retain minimal technical logs of the deletion operation (request ID, date, status) **without** your email, phone, or other personal content. These logs are used only for debugging and are retained for no more than **90 days**; only administrators have access.

---

## Contact

**Wellbeing App**  
Email: **vlrjarsenev@gmail.com**
