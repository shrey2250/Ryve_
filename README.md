# RYVE — Your Personal Money OS 💳

> A premium, privacy-first cross-platform personal finance operating system built with Flutter.

![Flutter](https://img.shields.io/badge/Flutter-02569B?style=for-the-badge&logo=flutter&logoColor=white)
![Dart](https://img.shields.io/badge/Dart-0175C2?style=for-the-badge&logo=dart&logoColor=white)
![SQLite](https://img.shields.io/badge/SQLite-07405E?style=for-the-badge&logo=sqlite&logoColor=white)
![License](https://img.shields.io/badge/license-MIT-blue.svg?style=for-the-badge)

---

## ✨ Features

- 💼 **Account Management**: Multi-account tracking (Bank, Cash, Wallets, Credit Cards) with real-time balance calculations.
- 💸 **Expense & Income Tracking**: Fast transaction logging, category tags, smart transaction parsing, and receipt details.
- 👥 **Group Expenses & Debt Splitting**: Track shared group tabs, calculate who owes what, and settle debts with one tap.
- 🤝 **IOU & Debt Management**: Keep clear tabs on borrowed and lent money with partial repayments.
- 🎯 **Financial Planning & Goals**: Set up dynamic savings goals, budgets by category, and recurring subscription bills.
- 📊 **CSV Data Export & Local Backup**: Full offline-first capability with SQLite. Back up, restore, or export to CSV anytime.
- 🔒 **App Security**: Built-in PIN setup and biometric app lock screen to keep sensitive financial data private.

---

## 🛠️ Architecture & Tech Stack

- **Framework:** [Flutter](https://flutter.dev) (Dart SDK `>=3.3.0 <4.0.0`)
- **State Management:** [Riverpod](https://riverpod.dev) (`flutter_riverpod`, `riverpod_annotation`)
- **Local Database:** [sqflite](https://pub.dev/packages/sqflite) (Offline-first local storage)
- **Routing:** [go_router](https://pub.dev/packages/go_router)
- **Styling:** Custom theme engine with dark/light mode and currency formatting

---

## 🚀 Getting Started

### Prerequisites

- [Flutter SDK](https://flutter.dev/docs/get-started/install) (3.3.0 or higher)
- Android Studio / VS Code with Flutter extension
- Windows / macOS / Linux developer toolchain for desktop builds

### Installation

1. Clone the repository:
   ```bash
   git clone https://github.com/shrey2250/Ryve_.git
   cd Ryve_
   ```

2. Install dependencies:
   ```bash
   flutter pub get
   ```

3. Run code generation (for Riverpod):
   ```bash
   dart run build_runner build --delete-conflicting-outputs
   ```

4. Launch the application:
   ```bash
   flutter run
   ```

---

## 📄 License

This project is licensed under the MIT License - see the LICENSE file for details.
