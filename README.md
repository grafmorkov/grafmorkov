```bash
 _                         _                  _             
 ██████╗ ██████╗  █████╗ ███████╗    ███╗   ███╗ ██████╗ ██████╗ ██╗  ██╗ ██████╗ ██╗   ██╗
██╔════╝ ██╔══██╗██╔══██╗██╔════╝    ████╗ ████║██╔═══██╗██╔══██╗██║ ██╔╝██╔═══██╗██║   ██║
██║  ███╗██████╔╝███████║█████╗      ██╔████╔██║██║   ██║██████╔╝█████╔╝ ██║   ██║██║   ██║
██║   ██║██╔══██╗██╔══██║██╔══╝      ██║╚██╔╝██║██║   ██║██╔══██╗██╔═██╗ ██║   ██║╚██╗ ██╔╝
╚██████╔╝██║  ██║██║  ██║██║         ██║ ╚═╝ ██║╚██████╔╝██║  ██║██║  ██╗╚██████╔╝ ╚████╔╝ 
 ╚═════╝ ╚═╝  ╚═╝╚═╝  ╚═╝╚═╝         ╚═╝     ╚═╝ ╚═════╝ ╚═╝  ╚═╝╚═╝  ╚═╝ ╚═════╝   ╚═══╝  


$ neofetch


user        grafmorkov
os          github
focus       systems / compilers / low-level

languages   C, C++, C#
engine      Unity (legacy)

project     Quark (language)
repo        https://github.com/grafmorkov/quark-lang

uptime      3+ year
status      active transition to systems programming

$ cat ~/projects/quark

Quark is a compiler-based language project I am building.

It focuses on:
- predictable behavior
- explicit state
- simple rules for programs
- no hidden runtime behavior
- memory is always explicit

Pipeline:
Source → AST → IR → checks → C → native binary

Currently, Quark generates C code as an intermediate backend.
C is used as a compilation target, not the core of the language.

The long-term goal is to reduce dependency on C and move toward more direct compilation approaches.

Quark is designed for systems programming and for learning how compilers work in practice.

Repo:
https://github.com/grafmorkov/Quark

$ cat stack.conf

C++        low-level systems, compiler backend
C          memory-level programming, tooling
C#         Unity tooling (legacy)
Compiler   lexer / parser / IR / codegen (Quark)

$ curl contact.local

Discord: grafmorkov
Telegram: @grafmorkov

```