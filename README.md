# Tauri / React / Typescript
Testing ground

## Usage instructions

Tauri prerequisites
[Tauri docs](https://tauri.app/v1/guides/getting-started/prerequisites)

installing dependencies
```bash
sudo apt update
sudo apt install libwebkit2gtk-4.0-dev \
    build-essential \
    curl \
    wget \
    libssl-dev \
    libgtk-3-dev \
    libayatana-appindicator3-dev \
    librsvg2-dev

curl --proto '=https' --tlsv1.2 https://sh.rustup.rs -sSf | sh

cargo upgrade

rustup update
```

run app
```bash
npm run tauri dev
```
