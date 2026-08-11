# 🎨 UX UI Warhorse official (V1.0)

> **Sistema de Diseño Oficial y Biblioteca de Componentes de Business Intelligence (BI)** para la plataforma de **Warhorse Logistics Group**.

Este repositorio independiente sirve como **manual de estandarización visual y guía de emulación** para ser consumido por otros desarrolladores o agentes de Inteligencia Artificial al construir módulos de software compatibles con el estilo institucional de Warhorse.

![Warhorse Logo](public/logo.png)

## 🎨 Design System Tokens

### 1. Paleta de Colores Corporativa (Dark Glassmorphism)

| Token / Nombre | Valor HEX / CSS | Descripción |
| :--- | :--- | :--- |
| **Background Dark** | `#0f0f10` | Fondo general de pantalla con degradados tenues. |
| **Card Base (Glass)** | `rgba(26, 26, 27, 0.7)` | Fondo de tarjetas translúcidas. |
| **Accent Gold (Branding)** | `#C5A059` | Color primario de acento, CTAs e indicadores clave. |
| **Glass Border** | `rgba(197, 160, 89, 0.2)` | Bordes sutiles dorados. |
| **Glass Border Hover** | `rgba(197, 160, 89, 0.5)` | Resplandor al interactuar con las tarjetas. |
| **Status Success** | `#10b981` | Verde esmeralda para estado CTPAT Aprobado o SLA positivo. |
| **Status Alert / Danger** | `#f43f5e` | Rosa / Rojo para retrasos o advertencias. |
| **Text Primary** | `#ffffff` | Texto principal de alto contraste. |
| **Text Muted** | `#9ca3af` | Texto secundario y etiquetas. |

### 2. Reglas de Glassmorphism (Efecto Vidrio Esmerilado)

```css
.glass-card {
  background: rgba(26, 26, 27, 0.7);
  backdrop-filter: blur(12px);
  -webkit-backdrop-filter: blur(12px);
  border: 1px solid rgba(197, 160, 89, 0.2);
  border-radius: 1rem;
  transition: all 0.3s cubic-bezier(0.4, 0, 0.2, 1);
}

.glass-card:hover {
  border-color: rgba(197, 160, 89, 0.5);
  box-shadow: 0 10px 30px -10px rgba(197, 160, 89, 0.15);
}
```

## 🚀 Inicio Rápido

```bash
# 1. Clonar este proyecto de guía de estilo
git clone https://github.com/gruizmetasolutions-cpu/ux-ui-warhorse-official.git
cd ux-ui-warhorse-official

# 2. Instalar dependencias
npm install

# 3. Iniciar entorno interactivo
npm run dev
```

La guía estará disponible en `http://localhost:5173/`.

## 📦 Componentes Incluidos

1. **`GlassCard.tsx`**: Contenedor genérico translúcido con soporte para brillo dorado (`glow`).
2. **`Button.tsx`**: Botón táctil con variantes `primary` (Dorado sólido), `outline` y `ghost`.
3. **`Input.tsx` & `Select.tsx`**: Entradas de formulario oscuras de alto contraste.
4. **Gráfico de Líneas Multivariable BI**: Selección de rangos (`24h`, `7d`, `30d`, `12m`) e interruptores de métricas activas (Millas, Fuel MPG, Demora).
5. **Gráficos BI de Barras y Anillo**: Volumen de carga y eficiencia de flota 5PL.
6. **Tabla de Datos BI**: Con búsqueda, filtros y píldoras de estado (`CTPAT Aprobado`, `En Tránsito`, `Inspección 19-Pts`, `Retrasado`).

---

© 2026 **Warhorse Logistics Group**. Todos los derechos reservados.
