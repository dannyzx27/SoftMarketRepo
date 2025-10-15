# SoftMarketRepo
Simulación del flujo GitFlow y aplicación de buenas prácticas en SoftMarket S.A.

# 🛠️ Rama `hotfix/fix-impuesto` – Corrección urgente en facturación

Esta rama contiene una corrección crítica relacionada con el cálculo de impuestos en el módulo de facturación. Fue creada directamente desde `main` para solucionar un error detectado en producción.

## ⚠️ Contexto del error

Se identificó un problema en el cálculo del total de la factura, donde el impuesto no se aplicaba correctamente. Esto generaba inconsistencias en los montos finales facturados a los clientes.

## 🔧 Solución aplicada

- Se corrigió la fórmula de cálculo en el archivo `fix_impuesto.py`.
- Se validó la corrección con pruebas unitarias.
- Se revisó el impacto en otros módulos antes de hacer merge.

## 🔁 Flujo de trabajo

1. Rama creada desde `main`.
2. Corrección aplicada y validada.
3. Merge hacia `main` para desplegar la solución.
4. Merge hacia `develop` para mantener la coherencia del código.

## ✅ Buenas prácticas aplicadas

- Corrección aislada y específica.
- Validación previa al despliegue.
- Documentación clara del cambio.
- Integración posterior en `develop`.

---

> Las ramas `hotfix/*` deben usarse exclusivamente para errores críticos que afecten directamente al entorno de producción.
