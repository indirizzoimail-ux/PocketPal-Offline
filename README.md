# PocketPal-Offline

App Android offline con LLM locale tramite `llama.cpp` + JNI.

## Cosa farà

- Eseguire un modello `.gguf` direttamente sul telefono.  
- Comunicare tra Java (Android) e C++ via JNI (JNI bridge a `llama.cpp`).  
- Niente connessione a cloud, totalmente offline.

## Come usare questo repo (su PC)

1. Clona:

```bash
git clone https://github.com/indirizzoimail-ux/PocketPal-Offline.git
cd PocketPal-Offline
