# CAMUS 3D LAB — Calculadora de Cotización y Rentabilidad

Aplicación web interactiva para cotización precisa, cálculo de márgenes netos y análisis comparativo de rentabilidad en servicios de impresión 3D profesional (FDM / SLA).

Desarrollada para sustituir los métodos tradicionales de cobro informal por hora plana, implementando un modelo técnico trifactorial basado en:
1. **Costo Fijo Base (Setup / STL):** Revisión técnica de malla, espesores, preparación y orientación en cama.
2. **Material Consumido:** Cobro proporcional exacto por gramo según el polímero (PLA+, PETG, ABS, Fibra de Carbono, Resina).
3. **Tiempo de Impresión:** Amortización por hora de máquina calibrada para equipos de alta velocidad (Bambu Lab A1, Creality K1C, Voron).

---

## Características Principales

- **Cotización Dinámica en Tiempo Real:** Ajuste instantáneo de parámetros mediante controles deslizantes o ingreso numérico manual.
- **Cotización por Lotes y Escala:** Soporte para pedidos por volumen con optimización de costos fijos y desglose del ahorro generado al cliente frente a compras individuales.
- **Modal de Costos Base e Insumos:** Configuración personalizada de potencia de máquinas, costo del kWh, vida útil del hardware, costo de bobinas y consumibles de taller.
- **Persistencia Local Automática:** Todos los cambios en tarifas y parámetros se guardan automáticamente en el navegador (`localStorage`) del usuario.
- **Cálculo de Margen Neto Riguroso:** Exclusión de insumos transferidos (empaque rígido, delivery courier) para evitar dilución artificial del margen operativo del taller.
- **Diseño Responsive Multipantalla:** Adaptación fluida a dispositivos móviles (smartphones), tablets y pantallas de escritorio.
- **Comparativa de Viabilidad:** Diagnóstico visual frente al modelo informal tradicional de cobro plano (S/ 5.00/h).

---

## Estructura del Proyecto

```text
├── index.html                           # Aplicación principal (Punto de entrada web)
├── CALCULADORA_PRECIOS_CAMUS3D.html     # Archivo fuente de la calculadora
├── vercel.json                          # Configuración para despliegue automático en Vercel
├── INFORME_EJECUTIVO_CAMUS3D.md         # Informe ejecutivo de estrategia de pricing
├── INFORME_EJECUTIVO_CAMUS3D.docx       # Versión en documento de Word del informe
├── 730315832_...jpg                     # Identidad gráfica y mascota de CAMUS 3D
├── .gitignore                           # Archivos excluidos del control de versiones
└── README.md                            # Documentación del proyecto
```

---

## Despliegue en Producción (Vercel)

El proyecto está preparado para ser desplegado directamente en Vercel con cero configuración adicional:

1. Conecta este repositorio en tu panel de control de Vercel.
2. Vercel detectará automáticamente el archivo `index.html` y las directivas de `vercel.json`.
3. Haz clic en **Deploy** para obtener una URL pública con certificado SSL (HTTPS) y CDN global inmediata.

---

## Licencia y Derechos

Desarrollado para **CAMUS 3D LAB**. Todos los derechos reservados.
