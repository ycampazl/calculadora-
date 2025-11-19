# calculadora-Yuliet Campaz
# Calculadora de Presupuesto Mensual

## 📌 Descripción del caso
La **Calculadora de Presupuesto Mensual** es una herramienta diseñada para que los usuarios puedan gestionar sus finanzas personales de manera eficiente. Permite registrar ingresos, gastos (fijos y variables) y obtener un balance mensual que refleje el estado financiero del usuario.

---

## 🎯 Objetivos
- Facilitar el seguimiento de ingresos y gastos mensuales.
- Proporcionar un balance mensual actualizado automáticamente.
- Permitir la categorización de gastos para un análisis más detallado.
- Mejorar la toma de decisiones financieras del usuario.

---

## 📄 Requerimientos

### Funcionales
- RF01: Registrar ingresos y gastos del mes.
- RF02: Validar que los valores ingresados sean numéricos y positivos.
- RF03: Mostrar balance mensual calculado automáticamente.
- RF04: Clasificar los gastos por categorías (alimentación, transporte, ocio, etc.).
- RF05: Generar un resumen visual (tabla y gráficos) del presupuesto.

### No Funcionales
- RNF01: Interfaz simple e intuitiva.
- RNF02: Cálculos rápidos (menos de 1 segundo por operación).
- RNF03: Compatible con dispositivos web y móviles.
- RNF04: Código documentado y mantenible.
- RNF05: Seguridad en la entrada de datos (evitar registros inválidos).

---

## 🧪 Tabla de pruebas funcionales

| ID Prueba | Descripción | Datos de Entrada | Resultado Esperado | Validación |
|-----------|-------------|-----------------|------------------|------------|
| CP01 | Registrar ingreso válido | Ingreso: 1500 | Se añade ingreso y aparece en la lista | ✔ Registro correcto |
| CP02 | Registrar gasto inválido | Gasto: -200 | El sistema muestra mensaje de error | ✔ Bloqueo del registro |
| CP03 | Cálculo del balance | Ingresos: 2000, Gastos: 750 | Balance esperado: 1250 | ✔ Balance calculado correctamente |

---

## 🔧 Tipo de mantenimiento propuesto
**Perfectivo**: se sugiere mejorar el sistema agregando nuevas funcionalidades como:  
- Gráficos interactivos del presupuesto.  
- Exportación del resumen a PDF.  
- Historial de balances mensuales.  
- Optimización de la interfaz de usuario.

---

## 🔄 Reflexión sobre control de versiones
El uso de **GitHub y control de versiones** permite:
- Mantener un historial claro de los cambios en el proyecto.  
- Recuperar versiones previas de la documentación y del código.  
- Mejorar la colaboración en caso de trabajar con otros desarrolladores.  
- Garantizar la trazabilidad de los cambios y la seguridad de la información técnica.

---
