# 📱 Appium Native Regression Test Suite

A standalone mobile automation project engineered from scratch using **Python**, **Appium**, and **Pytest** with the **Page Object Model (POM)** design pattern [13.2]. This repository focuses on end-to-end user validations inside native mobile UI views (`Sauce Labs App`).

## 🛠️ Key Technical Implementations
* **Dynamic Viewport Swipe Navigation:** Engineered directional coordinate swipe controls to handle UI lists sitting below the screen fold.
* **Hardware Keycode Injections:** Integrated direct mobile system backspace keycodes (Keycode 67) to safely bypass secure application numeric entry mask constraints.
* **Page Object Model Architecture:** Clean abstraction separating UI data components and procedural actions into highly maintainable, standalone object classes [13.2].
