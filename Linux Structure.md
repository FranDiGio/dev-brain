
Linux (OS)
└── Linux User Space
    └── Linux Package Management
        ├── DEB Package Ecosystem
        │   ├── DEB Package Format (.deb)
        │   ├── dpkg
        │   ├── APT (CLI)
        │   ├── Update Manager
        │   └── Software Center (GUI)
        │
        ├── RPM Package Ecosystem
        │   ├── RPM Package Format (.rpm)
        │   ├── DNF (CLI)
        │   ├── YUM (CLI, legacy)
        │   └── PackageKit / YaST (GUI)
        │
        ├── Pacman Package Ecosystem
        │   ├── PKG Package Format (.pkg.tar.zst)
        │   └── Pacman (CLI)
        │
        ├── APK Package Ecosystem
        │   ├── APK Package Format (.apk)
        │   └── apk (CLI)
        │
        └── Package Conversion Tools
            └── alien   (only handles .deb ↔ .rpm)



└── RPM-based Distributions
│   ├── RHEL
│   ├── AlmaLinux
│   ├── Rocky Linux
│   ├── Fedora
│   └── openSUSE
│
└── Arch-based Distributions
│   ├── Arch Linux
│   ├── Manjaro
│   └── EndeavourOS
│
└── Alpine-based Distributions
    └── Alpine Linux
