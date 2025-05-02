# Carga_Imperial


# 📦 QR & Barcode Scanner - Google Apps Script + Google Sheets

Esta es una aplicación web simple desarrollada con **Google Apps Script** que permite escanear **códigos QR y códigos de barras** desde un celular o navegador y guardar los datos directamente en una **hoja de cálculo de Google Sheets**.

---

## ✨ Características

- 📱 Compatible con celulares y cámara trasera
- 📷 Escaneo en tiempo real (QR, Code128, Code39)
- 🗂️ Guarda automáticamente en Google Sheets
- ✅ Interfaz simple, con Bootstrap
- 🚫 No requiere instalación de apps

---

## 🔧 Tecnologías usadas

- `Google Apps Script` (Frontend + Backend)
- `html5-qrcode` (Librería para escaneo)
- `Bootstrap 5` (Diseño)

---

## 📂 Estructura del Proyecto

| Archivo               | Descripción                                 |
|------------------------|---------------------------------------------|
| `Code.gs`             | Lógica del servidor (guardar en Sheets)     |
| `Index.html`          | HTML principal, incluye el resto de vistas  |
| `Form.html`           | Formulario de ingreso de producto           |
| `CSS.html`            | Bootstrap + estilos personalizados          |
| `JavaScript.html`     | Envío de formulario + escáner QR/barcode    |
| `html5-qrcode.min.js` | Librería de escaneo cargada desde GitHub Pages |

---

## 🚀 Cómo usar

1. Abre el proyecto en Google Apps Script
2. Conéctalo a una hoja de cálculo de Google
3. Publica como Web App:  
   `Deploy > Manage Deployments > New Deployment`
4. Acepta permisos y abre el enlace
5. ¡Escanea y registra!

---


## 🔗 Basado en

- [`html5-qrcode`](https://github.com/mebjas/html5-qrcode)
