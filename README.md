A console-based banking application demonstrating object-oriented programming principles in C#. The system manages multiple account types, facilitates transfers, and handles automated service charges.

 🎯 Features

 *Multiple Account Types*
  - Savings Account (R50 service charge)
  - Current Account (R100 service charge)

 *Account Operations*
  - Transfer funds between accounts (same owner only)
  - Automated service charge deductions
  - Real-time balance updates

  *Security & Validation*
  - Owner verification for transfers
  - Insufficient funds checking
  - Input validation for all operations

 *Event-Driven Notifications*
  - Email simulation when service charges are deducted
  - Real-time transaction feedback



Key Components

Account (Abstract Base Class)
  - Properties: Name, Surname, AccountNumber, AccountType, ServiceChargeDate, Balance
  - Methods: Transfer(), serviceCharge()
  - Events: ServiceChargeDeducted

  Savings Account
  - Default balance: R1,000
  - Service charge: R50

- **Current Account**
  - Default balance: R500
  - Service charge: R100

🚀 Getting Started

 Prerequisites
- .NET Framework 4.5 or higher
- Visual Studio 2017 or higher (or any C# IDE)


📋 Business Rules

1. Transfers
   - Only allowed between accounts with the same owner
   - Must have sufficient balance
   - Cannot transfer to the same account

2. Service Charges
   - Deducted automatically on specified date
   - Savings: R50 monthly charge
   - Current: R100 monthly charge

3. Account Management
   - Each account has unique account number
   - Balance cannot be directly modified (encapsulated)
   - All transactions are validated

🔮 Future Enhancements

- [ ] Database integration for data persistence
- [ ] User authentication and login system
- [ ] Transaction history and statements
- [ ] Interest calculation for savings accounts
- [ ] Overdraft facility for current accounts
- [ ] Multiple currency support
- [ ] GUI interface (WPF/Windows Forms)
- [ ] Email integration for real notifications
- [ ] Account creation and deletion
- [ ] Administrative dashboard

**Charmaine Mkhabela**
- GitHub: [Charmaine18](github.com/Charmaine18)
- Email:mkhabelacharmaine4@gmail.com

## 🙏 Acknowledgments

- Developed as part of PRG281 course examination
- Demonstrates practical application of OOP principles in C#

---

⭐ If you found this project helpful, please give it a star!
