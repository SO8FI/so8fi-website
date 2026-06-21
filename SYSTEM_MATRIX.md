1. Єдине Вікно

1.01 Товари
1.02 Послуги
1.03 Сервіс
1.04 Підписка
1.05 P2P
1.06 Біржа-муляж

1.07-1.99 Резерв
Правило трьох ролей:

ШІ-Формуляр
Користувач
ШІ-Наглядач
Тестові ячейки

1.0.xx

Термін:
90 днів
## 1.1 Джерело входу

1.1.01 Реферальне посилання
1.1.02 Google
1.1.03 TikTok
1.1.04 Facebook
1.1.05 Instagram
1.1.06 YouTube
1.1.07 Прямий перехід
1.1.08 Інше
1.1.09 Джерело невідоме
1.2 Країна користувача
1.2.01 Україна
1.2.02 Польща
1.2.03 Німеччина
...
1.2.99 Інша країна
1.3 Час сесії гостя
## 1.3 Час сесії гостя

1.3.01 Початок сесії
1.3.02 Активна сесія
1.3.03 Попередження про завершення
1.3.04 Сесію завершено

Правила:

- Гість має обмежений час роботи.
- Перед завершенням показується повідомлення.
- Після завершення пропонується реєстрація.
- Дані сесії записуються в журнал.
# SECTION 2 — REGISTERED USER

## 2.1 Registration

Purpose:
Create a verified user account and provide access to the personal cabinet.

Registration Trigger:

- Attempt to pay for a product.
- Attempt to pay for a service.
- Attempt to activate a subscription.
- Attempt to use a premium service.
- Any action requiring user ownership.

Registration Flow:

Step 1:
User accepts Platform Rules.

Step 2:
User confirms responsibility for personal access keys.

Step 3:
User completes biometric verification through personal device.

Supported methods:

- Face ID
- Fingerprint
- Device biometric authentication

Step 4:
System creates user account.

Step 5:
System generates:

- Main Access Key
- Backup Key #1
- Backup Key #2

Step 6:
Keys are shown ONCE.

User Warning:

"I understand that access keys are generated only once.
I am fully responsible for storing them.
If all keys are lost, access to the account,
history, assets and personal data cannot be restored."

Rule:

Stored keys = account access available.

All keys lost = account permanently inaccessible.

System does not store recovery copies.

Registration Result:

User status changes:

Guest (1.xx)
→
Registered User (2.xx)

--------------------------------------------------

## 2.2 Personal Cabinet

Entry Rule:

All registered users enter the system only through Personal Cabinet.

Direct access to internal modules is prohibited.

Main Cabinet Menu:

2.01 Continue Last Session

2.02 Profile

2.03 My Products

2.04 My Services

2.05 My Service Tools

2.06 My Subscriptions

2.07 Internal Social Network

2.08 P2P Marketplace

2.09 Training Exchange

2.10 Referral System

2.11 Notifications

2.12 Bookmarks

2.13 Activity History

2.14 Assets

2.15 Settings

2.16 Security & Keys

2.17 Logout

--------------------------------------------------

## Last Session Rule

System stores the last active category.

At the next login:

Last active category becomes item #1 in menu.

Example:

User exits from Exchange.

Next login:

2.01 Exchange
2.02 Profile
2.03 Notifications
...

Purpose:

Reduce navigation time.
Return user to unfinished activity.

--------------------------------------------------

## Guest Assistance System

If user loses activity momentum:

Indicators:

- Long inactivity.
- Repeated page switching.
- Multiple returns to same product/service.

System opens Help Window.

Help Level 1:

Short Text Instruction.

Help Level 2:

Visual Scheme.

Help Level 3:

Short Embedded Video.

Rules:

- No external websites.
- No YouTube redirects.
- No third-party resources.

All assistance remains inside platform.

--------------------------------------------------

## Guest Session Rules

Guest may browse:

- Products
- Services
- Service Tools
- Subscriptions

Guest cannot:

- Pay
- Use P2P
- Access Social Network
- Access Referral System
- Access Exchange
- Create listings

Any restricted action:

→ Registration Required.

--------------------------------------------------

## Navigation Codes

1.xx = Guest Area

2.xx = Registered User Area

Future:

3.xx = Business Accounts

4.xx = Administration
