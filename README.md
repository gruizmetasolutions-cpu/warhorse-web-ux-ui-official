# UX UI Warhorse official (V1.0)

Sistema de Diseño Oficial y Biblioteca de Componentes de Business Intelligence (BI) para la plataforma **Warhorse Logistics Group**.

## 🎨 Tokens Principales

- **Fondo General**: `#0f0f10`
- **Tarjetas Glassmorphism**: `rgba(26, 26, 27, 0.7)` con `backdrop-filter: blur(12px)`
- **Acento Principal (Gold)**: `#C5A059` (Bordes `rgba(197, 160, 89, 0.2)` a `0.5`)
- **Estado Éxito**: `#10b981`
- **Estado Alerta / Retraso**: `#f43f5e`

## 🚀 Instalación y Ejecución

```bash
# Instalar dependencias
npm install

# Levantar servidor de desarrollo
npm run dev

# Compilar producción
npm run build
```

## 📦 Componentes Incluidos

1. **`GlassCard`**: Contenedor translúcido con efecto de vidrio esmerilado.
2. **`Button`**: Botón principal en dorado metálico, variantes outline y ghost.
3. **`Input` & `Select`**: Entradas de formulario de alto contraste.
4. **Gráfico de Líneas Multivariable BI**: Selección de rangos (`24h`, `7d`, `30d`, `12m`) y métricas activas (Millas, Fuel MPG, Demora).
5. **Gráficos BI de Barras y Anillo**: Volumen de carga y eficiencia de flota 5PL.
6. **Tabla de Datos BI**: Con búsqueda, filtros y píldoras de estado (`CTPAT Aprobado`, `En Tránsito`, `Inspección 19-Pts`, `Retrasado`).
