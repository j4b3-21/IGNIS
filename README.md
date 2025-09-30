#  IGNIS

IGNIS is a high-performance AI/ML framework with native acceleration and modular design.  
This repository contains the core library, native bindings, and example usage. 

---

## 📦 Project Structure

```
IGNIS/
 ├── ignis-core       # Core JVM library
 ├── ignis-native     # Native JNI / CUDA bindings
 ├── ignis-examples   # Example applications
 ├── build.gradle     # Root Gradle build file
 └── settings.gradle  # Gradle multi-project setup
```

---

## 🚀 Getting Started

### Prerequisites
- **Java 21+** (Temurin recommended)
- **Gradle 9+** (wrapper included, no manual install needed)
- On macOS/Linux: `gcc` or `clang` (for native builds)
- On Windows: MSVC Build Tools

### Clone the repo
```bash
git clone https://github.com/j4b3-21/IGNIS.git
cd IGNIS
```

### Build everything
```bash
./gradlew build
```

### Run example
```bash
./gradlew :ignis-examples:run
```

---

## 🧪 Running Tests
```bash
./gradlew test
```

CI runs on every push/PR with a **Ubuntu/Windows/macOS build matrix**.

---

## ⚙️ Development

- Code style is enforced via **.editorconfig**
- Recommended IDE: **IntelliJ IDEA**
- Open the Gradle tool window in IntelliJ and **Reload All Gradle Projects**

---

## 🤝 Contributing

1. Fork the repo and create a feature branch
   ```bash
   git checkout -b feature/my-feature
   ```
2. Make changes and commit
   ```bash
   git commit -m "Add new feature"
   ```
3. Push and open a Pull Request

---

## 📜 License
[MIT License](LICENSE) © 2025 IGNIS contributors
