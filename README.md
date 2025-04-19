# 🏋️ BMI Calculator App

<div align="center">
  <img src="https://github.com/username/bmi_calculator_app/raw/main/assets/icon.png" width="150" alt="BMI Calculator Logo">
  <h1>Your Personal Health Companion</h1>
  
  ![Flutter](https://img.shields.io/badge/Flutter-02569B?style=for-the-badge&logo=flutter&logoColor=white)
  ![Dart](https://img.shields.io/badge/Dart-0175C2?style=for-the-badge&logo=dart&logoColor=white)
  ![MIT License](https://img.shields.io/badge/license-MIT-blue?style=for-the-badge)
</div>

## 📱 App Preview

<div align="center">
  <img src="https://github.com/username/bmi_calculator_app/raw/main/screenshots/input_screen.png" width="30%" alt="Input Screen">
  <img src="https://github.com/username/bmi_calculator_app/raw/main/screenshots/result_screen.png" width="30%" alt="Result Screen">
</div>

## ✨ Key Features

- 📏 Calculate BMI instantly with height and weight inputs
- 📊 Get categorized results (Underweight, Normal, Overweight, Obese)
- 🎨 Beautiful Material Design interface
- 🔄 Metric and Imperial unit support
- 💡 Health recommendations based on your BMI
- 📱 Fully responsive for all screen sizes

## 🛠️ Technical Implementation

```dart
// Sample BMI calculation logic
double calculateBMI(double height, double weight) {
  return weight / ((height/100) * (height/100));
}

String interpretBMI(double bmi) {
  if (bmi < 18.5) return 'Underweight';
  else if (bmi < 25) return 'Normal';
  else if (bmi < 30) return 'Overweight';
  else return 'Obese';
}
```

## 🚀 Getting Started

### Prerequisites
- Flutter SDK (>=3.0.0)
- Android Studio/VSCode with Flutter plugin

### Installation
1. Clone the repository
   ```bash
   git clone https://github.com/username/bmi_calculator_app.git
   cd bmi_calculator_app
   ```

2. Install dependencies
   ```bash
   flutter pub get
   ```

3. Run the app
   ```bash
   flutter run
   ```

## 🏗️ Project Structure

```
lib/
├── main.dart          # App entry point
├── constants.dart     # Design constants
├── components/        # Reusable widgets
│   ├── card.dart
│   ├── icon_content.dart
│   └── round_button.dart
├── screens/           # App screens
│   ├── input_page.dart
│   └── results_page.dart
└── calculator_brain.dart # Business logic
```

## 🤝 How to Contribute

1. Fork the repository
2. Create your feature branch (`git checkout -b feature/AmazingFeature`)
3. Commit your changes (`git commit -m 'Add some amazing feature'`)
4. Push to the branch (`git push origin feature/AmazingFeature`)
5. Open a Pull Request

## 📜 License

Distributed under the MIT License. See `LICENSE` for more information.

## 📬 Contact

**Ahmad Khalil Khattak**  
[![Email](https://img.shields.io/badge/Email-ahmadkhanpakistan987@gmail.com-D14836?style=flat&logo=gmail)](mailto:ahmadkhanpakistan987@gmail.com)  
[![LinkedIn](https://img.shields.io/badge/LinkedIn-Ahmad_Khalil-0077B5?style=flat&logo=linkedin)](https://www.linkedin.com/in/ahmad-khalil-33bbb4283/)

---

> "Know your numbers, take control of your health!"  
> Built with ❤️ using Flutter

<div align="center">
  <img src="https://img.shields.io/badge/version-1.0.0-green?style=flat-square">
  <img src="https://img.shields.io/badge/build-passing-brightgreen?style=flat-square">
</div>
