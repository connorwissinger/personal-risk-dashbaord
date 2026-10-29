# Personal Risk Dashboard
A Flutter application designed to help users understand their overall exposure to risk across multiple areas of everyday life. The project brings financial, personal, health, and digital privacy considerations into one dashboard, with the goal of making risk easier to interpret and act on.
Overview
Risk is often evaluated in isolation. The Personal Risk Dashboard explores a more holistic approach: considering several categories together and presenting an overall risk score alongside category-specific insights.

The goal is to help users identify potential vulnerabilities, understand which areas contribute most to their risk profile, and make more informed decisions.
Risk Categories
- Financial: Factors affecting financial stability and exposure.
- Personal: Everyday circumstances and personal safety considerations.
- Health: Health-related factors that may influence overall risk.
- Digital Privacy: Exposure related to online activity and personal information.
The categories above describe the project's intended scope. The precise scoring methodology and implemented features should be documented as development progresses.

Technology Stack
- Flutter — application UI framework
- Dart — application programming language
- Material Design — Flutter UI components
- Flutter Test — testing framework
The repository includes project targets for Windows and web.
Getting Started
Prerequisites
- Flutter SDK
- A compatible Dart SDK (provided with Flutter)
- A configured development environment for your target platform
Installation
git clone https://github.com/connorwissinger/personal-risk-dashbaord.git
cd personal-risk-dashbaord
flutter pub get
Run the application
For a browser:
flutter run -d chrome
For Windows (with Windows desktop development configured):
flutter run -d windows
Run tests
flutter test
Project Structure
lib/         Dart application source code
test/        Flutter tests
web/         Web application assets and configuration
windows/     Windows desktop runner and configuration
pubspec.yaml Flutter package configuration and dependencies
Development Goals
- Provide an understandable overview of risk across multiple categories.
- Explain the factors contributing to risk scores.
- Make risk-related information accessible through a clear dashboard interface.
- Refine the assessment methodology and presentation as the project develops.
Project Status
Under development. Features and scoring logic may change as the application evolves.
Disclaimer
This application is intended for informational and educational use. Any risk assessments it provides should not be treated as professional financial, medical, security, or legal advice.
