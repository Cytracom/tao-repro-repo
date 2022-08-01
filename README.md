## Steps to reproduce
* `yarn create tauri-app` with all default options
* add to tray icon to `tauri.conf.json`
* build system tray **with menu** in `main.rs`
* run app with `yarn tauri dev` (running a production build should work too)
* Launch slack and join a huddle
* Screenshare a webview based window in slack i.e. microsoft edge or vs code
* right click tauri tray icon
* weird window appears