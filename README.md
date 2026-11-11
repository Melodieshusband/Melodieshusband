<div align="center">

# Hi, I'm Meloten 👋

**Independent developer · Lua/Luau tooling · Reverse engineering · Language design**

![Python](https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python&logoColor=white)
![Lua](https://img.shields.io/badge/Lua-2C2D72?style=for-the-badge&logo=lua&logoColor=white)
![Luau](https://img.shields.io/badge/Luau-00A2FF?style=for-the-badge&logo=roblox&logoColor=white)
![C](https://img.shields.io/badge/C-A8B9CC?style=for-the-badge&logo=c&logoColor=black)

</div>

---

## About me

I build tools that take code apart and put it back together: obfuscators, deobfuscators, virtual machines and small compilers. Most of my work is in pure Python with zero third-party dependencies, and most of it is about understanding how protected Lua/Luau scripts and custom VMs actually behave.

- 🔍 Static and dynamic deobfuscation of Lua/Luau protectors
- 🧬 Custom bytecode VMs, control-flow flattening and string encryption
- 🎮 Language and toolchain design for PlayStation 2 homebrew
- 🛠️ Binary format reverse engineering (RenderWare, Lua bytecode)

---

## Featured projects

### 🌑 [Weak-Lua-Obfuscator](https://github.com/Melodieshusband/Weak-Lua-Obfuscator)
Multi-dialect Lua and Luau obfuscator written in pure Python. Custom bytecode VM, ChaCha20 string encryption, control-flow flattening and anti-tamper, with support for Lua 5.1 to 5.5, LuaJIT, Luau and GLua.

### 🎮 [MeloScript](https://github.com/Melodieshusband/MeloScript)
A statically-typed language and toolchain for PlayStation 2 homebrew (MIPS R5900). Lexer, parser, register-based bytecode VM and an AOT-to-C translator, all written from scratch. Includes VU0/VU1 microcode generation, scratchpad and VRAM management, and has been verified on PCSX2.

### 🔥 [FireFly-Protector-Deobfuscator](https://github.com/Melodieshusband/FireFly-Protector-Deobfuscator)
Static deobfuscator for Lua and Luau scripts protected with Firefly. It never executes the script: it decodes the state table and both string cipher layers, then evaluates the VM symbolically or lifts it back into structured Lua.

### 🧩 [Wynfuscate-deobf](https://github.com/Melodieshusband/Wynfuscate-deobf)
Deobfuscation toolkit for wYnFuscate with a dynamic logger (bundled Luau, hooked environment), a static string extractor, and an experimental hybrid engine. To my knowledge, the first open-source deobfuscator for wYnFuscate.

### 🛡️ [WeAreDevs-deobfuscator](https://github.com/Melodieshusband/WeAreDevs-deobfuscator)
Static deobfuscator for WeAreDevs and Prometheus-style protected scripts. Lexer, parser and AST transforms, VM dispatcher analysis, block graph recovery and structure lifting back into plain functions.

### 💾 [gta-sa-ps2-mod-converter](https://github.com/Melodieshusband/gta-sa-ps2-mod-converter)
Converts GTA San Andreas PC mods (`.dff` and `.txd`) into PS2-native RenderWare format, with `.img` unpack and repack tools. Round-trip validated, not yet tested in-game.

---

## Tech stack

| Area | Tools |
| --- | --- |
| Languages | Python, Lua, Luau, C |
| Focus | Deobfuscation, VM analysis, bytecode, compilers, binary formats |
| Targets | Roblox, Garry's Mod, PlayStation 2 |

---

## GitHub stats

<div align="center">

<img src="https://github-stats-extended.vercel.app/api?username=Melodieshusband&show_icons=true&theme=tokyonight&hide_border=true&hide_rank=true&hide=prs,issues,contribs&custom_title=Meloten%27s%20Stats" alt="Meloten's GitHub stats" />
<img src="https://github-stats-extended.vercel.app/api/top-langs/?username=Melodieshusband&layout=compact&theme=tokyonight&hide_border=true" alt="Top languages" />

</div>

---

## Currently learning

![C++](https://img.shields.io/badge/C%2B%2B-00599C?style=for-the-badge&logo=cplusplus&logoColor=white)
![C#](https://img.shields.io/badge/C%23-512BD4?style=for-the-badge&logo=csharp&logoColor=white)

Expanding my toolbox beyond Python and Lua with **C++** and **C#**, aiming to apply them to reverse engineering tools and language tooling.

---

</div>
