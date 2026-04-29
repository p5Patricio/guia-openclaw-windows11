# 🦞 Guía: OpenClaw en Windows 11 — Nativo con PowerShell

> Guía gratuita y open-source para correr AI agents locales en Windows sin WSL2.

## 📖 ¿Qué es esta guía?

Esta guía te enseña a instalar **OpenClaw** (un framework de agentes de IA open-source) de forma **100% nativa en Windows 11** usando PowerShell 7.

El objetivo es tener un agente de IA que corra **modelos locales gratuitos** (via Ollama en tu GPU) con **Gemini API como fallback** (1,500 requests/día gratis), todo sin depender de Linux ni WSL2.

## 🎯 ¿Qué vas a conseguir?

| Componente | Propósito |
|------------|-----------|
| 🦙 **Ollama + GPU** | Modelos locales Qwen3 y Qwen Coder corriendo en tu RTX 4060 |
| 🔑 **Gemini API** | Fallback gratuito para tareas complejas (1,500 req/día) |
| 🐳 **Docker Desktop** | Aislamiento de contenedores como alternativa a NemoClaw |
| 🛡️ **Hardening** | Firewall, permisos NTFS y auditoría de seguridad |
| 🧰 **Skills** | Web search, memory, code-assistant, summarizer |

## ⚠️ Importante: Limitación de Windows

**NemoClaw** (el sandbox de seguridad de NVIDIA con runtime OpenShell) **no tiene soporte completo en Windows nativo**. Funciona solo en Linux nativo o WSL2. En esta guía usamos Docker Desktop como capa de aislamiento alternativa.

Si necesitás NemoClaw completo, usá la guía WSL2 en su lugar.

## 🔗 Ver la guía online

**👉 [https://p5patricio.github.io/guia-openclaw-windows11/](https://p5patricio.github.io/guia-openclaw-windows11/)**

La guía incluye:
- Verificación de requisitos (GPU, virtualización, drivers)
- Instalación paso a paso de PowerShell 7, Node.js 24, Docker Desktop, Ollama
- Configuración de OpenClaw con wizard interactivo
- Descarga de modelos optimizados para 8GB VRAM
- Configuración de Gemini API Key
- `openclaw.json` completo para Windows
- Hardening de seguridad (NTFS, Firewall, auditoría)
- Checklist de verificación final

## 🙌 Para la comunidad

Esta guía es **100% gratuita** y de código abierto. Si te sirvió, considerá:

- ⭐ Darle estrella al repo
- 🐛 Reportar errores o información desactualizada
- 🔀 Proponer mejoras vía Pull Request
- 📢 Compartirla en tus redes para que llegue a más devs

> *"Correr IA local en tu propio hardware es libertad. Esta guía te muestra cómo hacerlo en Windows."* — Comunidad Gentleman Programming

---

Hecho con ❤️ para la comunidad hispanohablante de desarrolladores.
