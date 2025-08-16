# kernal-build
PasswordVault/                # repo root
├─ .github/
│  └─ workflows/
│     └─ swift-ci.yml
├─ PasswordVault/
│  ├─ PasswordVaultApp.swift
│  ├─ ContentView.swift
│  ├─ AddEditView.swift
│  ├─ Models/
│  │  └─ VaultItem.swift
│  ├─ Services/
│  │  ├─ KeychainService.swift
│  │  ├─ VaultStore.swift
│  │  └─ ExportImport.swift
│  ├─ Utils/
│  │  ├─ PasswordGenerator.swift
│  │  └─ Clipboard.swift
│  └─ Info.plist
├─ Tests/
│  └─ PasswordVaultTests/
│     └─ VaultStoreTests.swift
├─ .gitignore
├─ README.md
└─ LICENSE
