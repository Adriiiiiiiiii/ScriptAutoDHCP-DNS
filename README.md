# 🚀 Configuración Automática de Servidor DHCP + DNS

Este script automatiza la configuración de un servidor DHCP y DNS en un sistema Linux con interfaz gráfica o sin ella.

## 📋 Requisitos
- Sistema operativo basado en Linux (Ubuntu/Debian recomendado)
- Acceso de root
- Al menos 2 interfaces de red (una para internet y otra para la red interna)

## 🛠️ Características
- Configuración automática de interfaces de red con Netplan
- Instalación y configuración de:
  - Servidor DHCP (isc-dhcp-server)
  - Servidor DNS (BIND9)
- Creación de zonas DNS directa e inversa
- Configuración de rangos DHCP personalizables
