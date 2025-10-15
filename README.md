# SoftMarketRepo
Simulación del flujo GitFlow y aplicación de buenas prácticas en SoftMarket S.A.

# 🧩 Rama `feature/gestion-clientes` – Refactorización del módulo de clientes

Esta rama contiene el desarrollo de la nueva versión del módulo **Gestión de Clientes**, aplicando los principios **SOLID** para mejorar la calidad, mantenibilidad y escalabilidad del código.

## 🎯 Objetivo de esta funcionalidad

Refactorizar el módulo de clientes para:

- Separar responsabilidades (SRP).
- Permitir extensiones sin modificar el código base (OCP).
- Asegurar que las subclases puedan sustituir a sus clases base (LSP).
- Definir interfaces específicas (ISP).
- Aplicar inyección de dependencias (DIP).

## 📄 Archivos incluidos

- `cliente_refactor.py`: Pseudocódigo que muestra la aplicación de los principios SOLID.
- Documentación técnica del diseño propuesto.

## ✅ Buenas prácticas aplicadas

- Código modular y desacoplado.
- Interfaces claras y específicas.
- Preparado para pruebas unitarias.
- Fácil de extender sin romper funcionalidades existentes.

## 🔁 Flujo de trabajo

1. Desarrollo de la funcionalidad en esta rama.
2. Revisión de código mediante Pull Request.
3. Merge hacia `develop` una vez validado.

---

> Esta rama es temporal y será eliminada una vez que la funcionalidad sea integrada correctamente.
