# Standalone Flutter Hello App for iPhone 15

This is a complete, standalone Flutter project configured to build an iOS `.ipa` file using GitHub Actions (Cloud Mac) and install directly onto an **iPhone 15** from a **Windows PC** without using Expo Go or needing a local Mac.

---

## 📁 Project Structure

* `lib/main.dart` - Full Flutter application with interactive UI.
* `pubspec.yaml` - Project configurations & dependencies.
* `.github/workflows/build_ios.yml` - Automated GitHub Actions workflow to compile the iOS `.ipa` on cloud Mac hardware.

---

## 🚀 How to Build & Install on iPhone 15 (Step-by-Step)

### Step 1: Push Code to GitHub
1. Create a free repository on [GitHub.com](https://github.com).
2. Push all files inside this `flutter_hello_app` folder to your GitHub repository.

---

### Step 2: Download compiled `.ipa` from GitHub
1. Open your GitHub repository in your web browser.
2. Click on the **Actions** tab at the top.
3. Click on the latest run named **Build iOS IPA for iPhone 15**.
4. Scroll down to the **Artifacts** section at the bottom.
5. Click **HelloApp-iPhone15-IPA** to download the `HelloApp-iPhone15.ipa` file to your Windows PC.

---

### Step 3: Enable Developer Mode on iPhone 15
1. On your iPhone 15, open **Settings**.
2. Go to **Privacy & Security** -> scroll to the bottom -> **Developer Mode**.
3. Toggle Developer Mode **ON**.
4. Restart your iPhone 15 when prompted.

---

### Step 4: Install `.ipa` on iPhone 15 using Sideloadly (Windows)
1. Download & install **Sideloadly** on your Windows PC from [sideloadly.io](https://sideloadly.io/).
2. Connect your iPhone 15 to your Windows PC via USB-C cable.
3. Open **Sideloadly**:
   * Your iPhone 15 will appear in the **Device** field.
   * Drag & drop `HelloApp-iPhone15.ipa` into Sideloadly.
   * Enter your standard free **Apple ID** in the Apple ID field.
   * Click **Start**.
4. Once Sideloadly shows **Done**, the app icon will appear on your iPhone 15 home screen!

---

### Step 5: Trust the App on iPhone 15
1. On your iPhone 15: Go to **Settings > General > VPN & Device Management**.
2. Under **Developer App**, tap your Apple ID.
3. Tap **Trust [Your Email]** and confirm.
4. Launch your **Hello App** from your iPhone 15 home screen! 🎉
