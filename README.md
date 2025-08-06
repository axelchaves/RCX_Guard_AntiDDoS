# 🛡️ RCX Guard v1.0

**Solución Anti-DDoS y WAF ligera para servidores Windows**  
Desarrollado por [Axel Chaves](https://github.com/axelchaves)

---

## ⚙️ ¿Qué es RCX Guard?

**RCX Guard** es una herramienta avanzada diseñada para proteger servidores Windows contra ataques DDoS y amenazas a nivel de aplicación, como inyecciones SQL o escaneos de puertos. A diferencia de la mayoría de los WAFs existentes, RCX Guard se enfoca en entornos **Windows** y ofrece compatibilidad directa con **Cloudflare**, lo que permite filtrar conexiones solo desde sus rangos IP oficiales.

---

## 🚀 Características principales

- 🔒 **Detección y bloqueo de IPs sospechosas**
- 🌐 **Integración con Cloudflare (rango IP v4/v6 oficial)**
- ⚔️ **Motor WAF con reglas personalizadas**
- ✅ **Whitelist / Blacklist configurables**
- 📊 **Logs en tiempo real**
- 🧠 **Interfaz CLI interactiva**
- 🧩 **Modular y fácil de extender (C# / .NET)**

---

## 📦 Requisitos

- **Sistema operativo**: Windows (con permisos de administrador)
- **.NET Runtime**: [.NET 6.0 o superior](https://dotnet.microsoft.com/download)
- **Dominio activo en Cloudflare** (modo proxy activado)

---

## 🔧 Instalación

1. Descarga el ejecutable o clona el repositorio:
   ```bash
   git clone https://github.com/axelchaves/RCX-Guard_AntiDDoS.git
   cd RCX_Guard_AntiDDoS
