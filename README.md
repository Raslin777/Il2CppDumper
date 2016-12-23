# Il2CppDumper
Better version of https://github.com/Jumboperson/PokemonGoDumper

Forked project from Jumboperson

# Changes in this project
- CLI interactive where user can input the unk offset
- DLL runtime included so that Windows does not require any Visual C++ runtime
- Path fixes. The program must be located in the same directory as your binary to be dumped
- OS detection. The CLI will look different if using Win 8.1 and below. This project will require Windows 10 SDK to compile.
