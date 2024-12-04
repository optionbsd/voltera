# Voltera
Voltera is an SDK for building OPA packages for OptionBSD.  
Voltera supports GTK3 in C. It builds `main.c` from the `src` folder on supported platforms (x86_64, i386, aarch64, and others).

# Create a Project
- `vproj ~/ProjectName` generates a new project. Edit `Manifest.xml` to modify the information about your application. Change the icon in `res/AppIcon.png`.
- `voltera ~/ProjectName` builds your project into an ELF binary and creates an OPA package.

# Project Tree
```
.
├── Manifest.xml
├── YourAppName-1.0.0-debug.opa
├── bin
│   ├── aarch64
│   │   └── main
│   └── x86_64
│       └── main
├── res
│   └── AppIcon.png
├── src
│   └── main.c
└── temp
```
