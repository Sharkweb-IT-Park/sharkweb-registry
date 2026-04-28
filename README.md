# Sharkweb Registry

Official module registry for Sharkweb CLI.

## 📦 What is this?

This repository hosts the public registry used by the Sharkweb CLI to:

* Discover modules
* Install modules
* Resolve dependencies

## 🔗 Registry URL

Use this URL in your CLI:

```
https://raw.githubusercontent.com/Sharkweb-IT-Park/sharkweb-registry/main/registry.json
```

## 📁 Structure

```json
{
  "modules": {
    "crm": {
      "repo": "https://github.com/Sharkweb-IT-Park/test.git",
      "version": "1.0.0",
      "description": "CRM module",
      "dependencies": [],
      "backend": true,
      "frontend": true
    }
  }
}
```

## 🚀 Contributing

Add new modules by updating `registry.json`.
