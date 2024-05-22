# LuneWeb

LuneWeb is an alternative to electron and tauri, in LuneWeb you can use Luau + Javascript to make cross-platform web based applications!

LuneWeb uses [Tao](https://github.com/tauri-apps/tao) and [Wry](https://github.com/tauri-apps/wry) to add standard libraries for creating web applications for luau, and runs the application using [MLua](https://github.com/mlua-rs/mlua) and [Lune](https://github.com/lune-org/lune).

# To-Do

- [x] Add CustomProtocol ([commit](https://github.com/LuneWeb/LuneWeb-rs/commit/09cd20c6892b78a24d45630ec31739a590d75d20))
- [ ] LuneWeb/LuneWeb-rs#1
- [x] LuneWeb/LuneWeb-rs#2 ([commit](https://github.com/LuneWeb/LuneWeb-rs/commit/f4e1b3b3afd8f9b48942b633bb7e783954cf3d76))
- [x] Move the [custom-aliases](https://github.com/HighFlowey/luneweb/tree/custom-aliases) fork of lune to this organization
- [ ] Make a fork of lune-std where we can customize the way the `require` function interacts with the file system, we can use that to compile all the scripts and then bundle them with the application
- [x] Add WebView support for Linux ([commit](https://github.com/LuneWeb/LuneWeb-rs/commit/b7efd57c9be92f78f975007d58d18a140380ebc5))
- [ ] Better way of managing templates
- [ ] Add luneweb to https://github.com/HighFlowey/create-luau-app and then move it to this organization
- [ ] Documentation repo
