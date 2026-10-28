# Hi 👋

Software developer working with C#/.NET and web technologies, and exploring systems programming in Rust and C++. In my free time I'm a hobby game developer, making games with Godot.

I'm also deeply interested in AI and how it changes software engineering.

## Tech stack

<p align="left">
  <img src="https://skillicons.dev/icons?i=cs,dotnet,js,ts,html,css,rust,cpp,godot" alt="C#, .NET, JavaScript, TypeScript, HTML, CSS, Rust, C++, Godot" />
</p>

## Projects

### [Cipher](https://github.com/mikkoryynanen/Cipher)
A small desktop app for encrypting messages before you paste them into any messenger, and decrypting the ones you receive. It works through copy and paste, makes no network connections and keeps no message history. Encryption uses XChaCha20-Poly1305 with Argon2id passphrases. Built with Rust, Tauri and TypeScript.

### [MMO](https://github.com/mikkoryynanen/MMO)
A multiplayer game backend and client in C#/.NET, built to learn how an MMO fits together. Players log in through an auth API, then connect to an authoritative world server over TCP. The server tracks every connected player and broadcasts their positions to the others, and a Raylib client renders the shared world. Binary MessagePack packets carry the network traffic, and MySQL with EF Core stores accounts and world data. .NET Aspire starts the whole stack (database, migrations, services and clients) with one command. A dummy client and a dev API support testing.

### [SimpleEngine](https://github.com/mikkoryynanen/SimpleEngine)
A small 2D game engine in C++, written to practise engine architecture. It is built on an entity-component-system with EnTT, with separate systems for input, movement, AI and rendering, and a state machine that switches between game states such as intro and play. SFML handles windowing and graphics, and Loguru handles logging.

### [game](https://github.com/mikkoryynanen/game)
An early C++ game prototype built with SFML and CMake. It sets up the basic game structure: a game loop, a renderer, game objects and interfaces for input and rendering.

## Contact

[![LinkedIn](https://img.shields.io/badge/LinkedIn-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/mikko-ryynanen)
