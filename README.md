# LuneWeb

LuneWeb uses [Tao](https://github.com/tauri-apps/tao) and [Wry](https://github.com/tauri-apps/wry) to add standard libraries for creating web applications for luau, and runs the application using [Mlua](https://github.com/mlua-rs/mlua) and [Lune](https://github.com/lune-org/lune).

# To-Do

- Add WebView support for Linux
- Move the [custom-aliases](https://github.com/HighFlowey/luneweb/tree/custom-aliases) fork of lune to this organization
- Make a fork of lune-std where we can customize the way the `require` function interacts with the file system, we can use that to compile all the scripts and then bundle them with the application
