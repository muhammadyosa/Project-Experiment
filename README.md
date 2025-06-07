# Experiment Data Search App

A portable desktop app built using Tauri with search features for Excel data and GitHub Actions-based deployment.

## 🔧 Features

- ✅ Search by Customer Name, Hostname OLT, Service ID, ID FAT, SN ONT
- 📁 Upload Excel to update data
- 🌗 Toggle Dark/Light Mode
- ✂️ Copy & 🗑️ Clear buttons
- ⚙️ Auto-build with GitHub Actions

---

## 🚀 How to Upload and Run from GitHub

### 1. Create a repository on GitHub

### 2. Clone and set up locally:
```bash
git clone https://github.com/YOUR_USERNAME/YOUR_REPO.git
cd YOUR_REPO
```

### 3. Copy extracted folder contents here, then:
```bash
git init
git add .
git commit -m "Initial commit with full app"
git branch -M main
git remote add origin https://github.com/YOUR_USERNAME/YOUR_REPO.git
git push -u origin main
```

### 4. Trigger GitHub Actions by tagging:
```bash
git tag v1.0.0
git push origin v1.0.0
```

### 5. Check GitHub Actions tab → wait for `.exe` + `.msi` + `.zip` to appear in Releases.

