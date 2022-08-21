# Tauri / React / Typescript
Testing ground

Tauri uses Rust in the backend but its not as easy to make it work on Android and IOS
its supposed to be more secure than nodejs and its for sure faster than Electron, BUT Electron uses nodejs in the backend
and with that in mind, i could use Cordova Apache to parse the app to IOS and Android cordova also uses Nodejs in the backend

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
cd testing
npm run tauri dev
```
