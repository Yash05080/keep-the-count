# IntelliSpend 💰

A smart personal finance management mobile application built with Flutter that automates expense tracking through OCR receipt scanning and intelligent categorization.

## ✨ Features

- **Real-time Expense Tracking** - Track income and expenses with automatic balance calculations
- **OCR Receipt Scanning** - Extract transaction details directly from receipt images using Google Cloud Vision API
- **Smart Categorization** - ML-powered automatic expense classification with learning capabilities
- **Interactive Analytics** - Visual insights with charts and graphs to understand spending patterns
- **Cross-platform** - Seamless experience on both Android and iOS
- **Secure Authentication** - Protected user data with Supabase authentication

## 🛠️ Tech Stack

- **Frontend**: Flutter, Provider (State Management)
- **Backend**: Supabase, PostgreSQL
- **APIs**: Google Cloud Vision API
- **Visualization**: FL Chart
- **Machine Learning**: Custom categorization algorithms (Decision Tree, Random Forest, SVM)

## 🚀 Getting Started

### Prerequisites
- Flutter SDK (latest stable version)
- Android Studio / Xcode
- Supabase account
- Google Cloud Platform account (for Vision API)

### Installation

1. Clone the repository
```bash
git clone https://github.com/Yash05080/IntelliSpend.git
cd IntelliSpend
```

2. Install dependencies
```bash
flutter pub get
```

3. Set up environment variables
Create a `.env` file in the root directory and add:
```
SUPABASE_URL=your_supabase_url
SUPABASE_ANON_KEY=your_supabase_anon_key
GOOGLE_CLOUD_API_KEY=your_google_cloud_api_key
```

4. Run the app
```bash
flutter run
```

## 📱 Screenshots

### Home & Expense Management
<div align="center">
  <img src="https://github.com/user-attachments/assets/3a91e43c-37c9-496e-8f30-ede3545e904d" width="28%" alt="Home Page" />
  <img src="https://github.com/user-attachments/assets/a76f1e40-d7e8-4710-9e38-d9e927a70791" width="28%" alt="All Expenses Page" />
  <img src="https://github.com/user-attachments/assets/40b3a529-def4-4e0b-95a1-9e4ca6b9c45c" width="28%" alt="Add Expense Page" />
</div>

### Analytics & Insights
<div align="center">
  <img src="https://github.com/user-attachments/assets/180ef01c-bf55-4090-8ec8-a56dd45d0a73" width="28%" alt="Analytics Overview" />
  <img src="https://github.com/user-attachments/assets/6cfb3900-3727-4d5a-a068-373577ae516b" width="28%" alt="Detailed Financial Analytics" />
  <img src="https://github.com/user-attachments/assets/0b6e0183-9636-42a1-b44f-f3acb2e1fd82" width="28%" alt="Spending Trends" />
</div>

### Advanced Analytics
<div align="center">
  <img src="https://github.com/user-attachments/assets/a0fce43c-f156-460d-b6f4-f2130e721d6d" width="38%" alt="Category Breakdown" />
  <img src="https://github.com/user-attachments/assets/fe5d9b2a-b028-4596-a7d6-c1f22e11c922" width="38%" alt="Financial Summary" />
</div>
## 🏗️ Project Structure

```
lib/
├── models/           # Data models
├── providers/        # State management with Provider
├── screens/          # UI screens
├── services/         # API services and OCR integration
├── utils/            # Helper functions and constants
└── widgets/          # Reusable UI components
```

## 🔮 Future Enhancements

- [ ] Advanced ML for personalized financial insights
- [ ] Budget planning and spending alerts
- [ ] Multi-device synchronization
- [ ] Bank integration for automatic imports
- [ ] Multi-currency support
- [ ] Gamification features

## 📄 License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

## 🤝 Contributing

Contributions are welcome! Please feel free to submit a Pull Request.

## 📞 Contact

Yash Agarwal - Yash05080@gmail.com - https://www.linkedin.com/in/yash05080/

Project Link: [https://github.com/Yash05080/IntelliSpend](https://github.com/Yash05080/IntelliSpend)
