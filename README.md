# Overleaf-Workshop

**This project is in very early stage, stay tuned!**

Open Overleaf (ShareLatex) projects in VSCode, with full collaboration support.

[demo.webm](https://github.com/iamhyc/Overleaf-Workshop/assets/9068301/eb298b9b-0d08-4200-a61a-9df96692bc02)


### TODO

- REST API (Overleaf Web Route List, [webapi.md](./docs/webapi.md))
  - [x] Login / Logout server
  - [x] List projects
  - [ ] Compile project
  - [ ] Get project build output (PDF)
  - [ ] Jump between "code" and "pdf"
  - [ ] Get file history updates and diff
  - [x] Download original files
- WebSocket API
  - [x] Init websocket connection
  - [x] Request: `joinProject`, `joinDoc`, `leaveDoc`
  - [x] Request: `clientTracking.getConnectedUsers`
  - [ ] Request: `clientTracking.updatePosition`
  - [ ] Request: `applyOtUpdate`
  - [ ] Event: ...
- Open project as virtual workspace
  - [ ] sync remote project via `FileSystemProvider`
  - [ ] support local syntax check (via other extension)
  - [ ] compile project: 1) on save, 2) on `ctrl+alt+b`
  - [ ] display "build icon" on status bar
- Collaboration
  - [ ] Display online users on side bar
  - [ ] Display multiple colored selections (via `setDecorations`)
  - [ ] send/receive chat message
- Miscs
  - [ ] support project-specific settings:
    > "Compiler", "Main document", "Spell check", "Dictionary"
  - [ ] support local git bridge


### References

- Overleaf Official Logos, [link](https://www.overleaf.com/for/partners/jlogos)
