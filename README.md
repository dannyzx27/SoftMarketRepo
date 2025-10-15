# SoftMarketRepo
Simulación del flujo GitFlow y aplicación de buenas prácticas en SoftMarket S.A.

# 🧪 Rama `develop` – Integración de nuevas funcionalidades

Esta rama representa el entorno de integración donde se reúnen todas las nuevas funcionalidades desarrolladas en ramas `feature/*` y correcciones desde `hotfix/*`, antes de ser preparadas para producción en `release/*`.

## 🔧 Propósito

- Integrar cambios de múltiples desarrolladores.
- Ejecutar pruebas automáticas.
- Realizar revisiones de código.
- Validar que el sistema se mantenga estable antes de pasar a `release`.

## 📌 Contenido actual
- Ejemplos de mensajes de commits (`commit_examples.txt`).
- Documentación técnica en desarrollo.
- Código en revisión proveniente de `feature/gestion-clientes` y `hotfix/fix-impuesto`.

## 📄 Convenciones de commits

Formato: `<tipo>(<módulo>): <descripción breve>`

Ejemplos:
- `feat(clientes): agregar validación de correo electrónico`
- `fix(facturación): corregir cálculo de impuesto en total`
- `refactor(api): separar lógica de negocio del controlador`

## ✅ Buenas prácticas en esta rama

- Todo cambio debe venir desde un **Pull Request**.
- Las revisiones de código son obligatorias.
- Las pruebas automáticas deben pasar antes de hacer merge.
- Se recomienda mantener esta rama siempre funcional y libre de errores graves.

---

> Esta rama es clave para garantizar la calidad del software antes de su liberación
