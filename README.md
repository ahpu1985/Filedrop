# Filedrop
# FileDrop — Offline P2P File Sharing

[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](https://opensource.org/licenses/MIT)
[![Flutter](https://img.shields.io/badge/Flutter-3.0+-blue.svg)](https://flutter.dev)
[![Go](https://img.shields.io/badge/Go-1.21+-00ADD8.svg)](https://golang.org)

**FileDrop** — полностью офлайн-приложение для обмена файлами между устройствами без интернета.

## ✨ Возможности
- 📱 **Кроссплатформенность**: Android, iOS, Windows, macOS, Linux
- 🔒 **Шифрование end-to-end** (WebRTC DTLS)
- 📶 **Без интернета** — через локальную сеть или Hotspot
- ⚡ **Мгновенное обнаружение** (mDNS)
- 📁 **Отправка файлов, фото, видео, текста**

## 🚀 Быстрый старт

### 1. Запустите сервер сигнализации
```bash
cd backend
go mod tidy
go run main.go
