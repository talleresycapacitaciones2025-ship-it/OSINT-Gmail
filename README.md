# 🕵️ Google OSINT Tool

Herramienta OSINT para buscar información en Google usando SerpAPI. Extrae automáticamente:

- 📧 Correos electrónicos
- 🔗 Perfiles de redes sociales (Facebook, LinkedIn, Twitter, Instagram, etc.)
- 🌐 Enlaces relevantes
- 🤖 Informes generados con IA (Groq)

---

## Ejemplo de salida

HERRAMIENTA OSINT CON SERPAPI (GOOGLE)


🔍 Buscando en Google: Juan Pérez
✅ Total de resultados encontrados: 1,234,567
ℹ️ Mostrando los primeros 30 enlaces.

PRINCIPALES ENLACES

1. Juan Pérez - LinkedIn
   https://ec.linkedin.com/in/juanperez
   Experto en ciberseguridad...

🔗 PERFILES DE REDES SOCIALES

▸ LINKEDIN (1)
  1. Juan Pérez - LinkedIn
     https://ec.linkedin.com/in/juanperez

▸ FACEBOOK (1)
  1. Juan Pérez - Facebook
     https://www.facebook.com/juanperez

CORREOS ELECTRÓNICOS ENCONTRADOS

📧 juan.perez@empresa.com
   → https://www.empresa.com/contacto
   → https://ec.linkedin.com/in/juanperez

---

## Requisitos

- Python 3.8+
- Clave de API de SerpAPI (https://serpapi.com/)
- (Opcional) Clave de API de Groq para informes con IA

---

## Configuración
Crea un archivo .env en la raíz con:

text
SERPAPI_KEY="tu_clave_serpapi"
GROQ_API_KEY="gsk_tu_clave_groq"   # opcional

---

## Uso
python3 google_osint.py

---

## ⚠️ Nota legal
Esta herramienta solo debe usarse para investigaciones legítimas, con consentimiento o sobre información pública. No uses para acosar o vulnerar la privacidad de terceros.

---
MIT License

Copyright (c) 2026 Artemisa

Permission is hereby granted, free of charge, to any person obtaining a copy
of this software and associated documentation files (the "Software"), to deal
in the Software without restriction, including without limitation the rights
to use, copy, modify, merge, publish, distribute, sublicense, and/or sell
copies of the Software, and to permit persons to whom the Software is
furnished to do so, subject to the following conditions:

The above copyright notice and this permission notice shall be included in all
copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR
IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY,
FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE
AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER
LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM,
OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN THE
SOFTWARE.
