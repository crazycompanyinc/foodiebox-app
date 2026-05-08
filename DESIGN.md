---
version: alpha
name: FoodieBox
description: Planificación de Comidas con IA — 100% digital. Recetas personalizadas, meal planning inteligente, lista de compras automática, tracking nutricional. Estética warm minimal inspirada en Notion: fondos cálidos, verdes orgánicos, tipografía serif para headlines.
colors:
  primary: "#faf9f7"
  secondary: "#f5f3f0"
  tertiary: "#ebe8e3"
  surface: "#ffffff"
  accent: "#2d6a4f"
  accent-hover: "#40916c"
  accent-light: "#b7e4c7"
  accent-glow: "rgba(45,106,79,0.08)"
  accent-warm: "#d4a373"
  success: "#52b788"
  warning: "#e9c46a"
  text-primary: "#1a1a1a"
  text-secondary: "#5c5c5c"
  text-muted: "#8a8a8a"
  border: "rgba(0,0,0,0.06)"
  border-accent: "rgba(45,106,79,0.15)"
typography:
  h1:
    fontFamily: "Lora"
    fontSize: "clamp(2.2rem, 4.5vw, 3.2rem)"
    fontWeight: 600
    lineHeight: 1.15
    letterSpacing: "-0.02em"
  h2:
    fontFamily: "Lora"
    fontSize: "clamp(1.6rem, 3vw, 2.2rem)"
    fontWeight: 600
    lineHeight: 1.2
    letterSpacing: "-0.01em"
  h3:
    fontFamily: "Inter"
    fontSize: "clamp(1.1rem, 1.8vw, 1.3rem)"
    fontWeight: 600
    lineHeight: 1.3
    letterSpacing: "-0.01em"
  body-lg:
    fontFamily: "Inter"
    fontSize: "1.125rem"
    fontWeight: 400
    lineHeight: 1.65
    letterSpacing: "0"
  body:
    fontFamily: "Inter"
    fontSize: "1rem"
    fontWeight: 400
    lineHeight: 1.65
    letterSpacing: "0"
  caption:
    fontFamily: "Inter"
    fontSize: "0.875rem"
    fontWeight: 500
    lineHeight: 1.4
    letterSpacing: "0.01em"
  mono:
    fontFamily: "JetBrains Mono"
    fontSize: "0.8rem"
    fontWeight: 500
    lineHeight: 1.5
    letterSpacing: "0"
rounded:
  sm: "6px"
  md: "10px"
  lg: "14px"
  xl: "20px"
  full: "9999px"
spacing:
  xs: "4px"
  sm: "8px"
  md: "16px"
  lg: "24px"
  xl: "40px"
  xxl: "64px"
  xxxl: "96px"
shadows:
  sm: "0 1px 3px rgba(0,0,0,0.04), 0 1px 2px rgba(0,0,0,0.03)"
  md: "0 4px 12px rgba(0,0,0,0.06), 0 2px 4px rgba(0,0,0,0.04)"
  lg: "0 12px 32px rgba(0,0,0,0.08), 0 4px 8px rgba(0,0,0,0.04)"
  glow: "0 0 30px rgba(45,106,79,0.08)"
gradients:
  hero: "linear-gradient(180deg, #faf9f7 0%, #f0ede8 100%)"
  accent: "linear-gradient(135deg, #2d6a4f 0%, #40916c 100%)"
  warm: "linear-gradient(135deg, #d4a373 0%, #e9c46a 100%)"
  card: "linear-gradient(180deg, #ffffff 0%, #faf9f7 100%)"
  section-alt: "linear-gradient(180deg, #f5f3f0 0%, #faf9f7 100%)"
components:
  button-primary:
    background: "linear-gradient(135deg, #2d6a4f 0%, #40916c 100%)"
    textColor: "#ffffff"
    rounded: "10px"
    padding: "14px 32px"
    fontWeight: 600
    fontSize: "1rem"
    shadow: "0 4px 16px rgba(45,106,79,0.2)"
  button-secondary:
    background: "rgba(45,106,79,0.06)"
    textColor: "#2d6a4f"
    rounded: "10px"
    padding: "14px 32px"
    fontWeight: 600
    fontSize: "1rem"
    border: "1px solid rgba(45,106,79,0.12)"
  button-warm:
    background: "linear-gradient(135deg, #d4a373 0%, #e9c46a 100%)"
    textColor: "#1a1a1a"
    rounded: "10px"
    padding: "14px 32px"
    fontWeight: 600
    fontSize: "1rem"
  card:
    background: "#ffffff"
    border: "1px solid rgba(0,0,0,0.06)"
    rounded: "14px"
    padding: "28px"
    shadow: "0 2px 8px rgba(0,0,0,0.03)"
  card-hover:
    shadow: "0 8px 24px rgba(0,0,0,0.08)"
    border: "1px solid rgba(45,106,79,0.12)"
  nutrition-badge:
    background: "rgba(45,106,79,0.08)"
    textColor: "#2d6a4f"
    rounded: "9999px"
    padding: "4px 12px"
    fontSize: "0.75rem"
    fontWeight: 600
  macro-bar:
    background: "rgba(45,106,79,0.1)"
    fill: "#2d6a4f"
    rounded: "9999px"
    height: "6px"
  input:
    background: "#ffffff"
    border: "1px solid rgba(0,0,0,0.1)"
    textColor: "#1a1a1a"
    rounded: "10px"
    padding: "12px 16px"
---

## Overview

FoodieBox es una plataforma 100% digital de planificación de comidas con IA. NO es reparto de comida física — es un servicio SaaS que genera planes de comida personalizados, recetas adaptadas a tus objetivos nutricionales, listas de compras automáticas y tracking de macros/micros.

El diseño es warm minimal inspirado en Notion: fondos cálidos (#faf9f7) que se sienten como papel de calidad, con acentos verde bosque (#2d6a4f) que evocan lo orgánico y natural. La tipografía Lora (serif) en headlines aporta calidez y personalidad, mientras Inter maneja el body text con legibilidad perfecta. Es un diseño que se siente como una revista de cocina premium encontrada con la productividad de Notion.

## Colors

- **Primary (#faf9f7):** Warm white — como papel de calidad, no blanco clínico.
- **Accent (#2d6a4f):** Verde bosque — orgánico, natural, saludable. El verde de la vida.
- **Accent Light (#b7e4c7):** Verde menta suave — para badges y highlights.
- **Accent Warm (#d4a373):** Dorado cálido — para elementos de comida/recetas.
- **Text Primary (#1a1a1a):** Casi negro cálido — legibilidad máxima.
- **Text Secondary (#5c5c5c):** Gris cálido — texto de apoyo.
- **Border (rgba 0,0,0,0.06):** Whisper borders como Notion.
- **Section Alt (#f5f3f0):** Fondo alterno para ritmo visual.

## Typography

- **Lora** (serif) para headlines — weight 600, letter-spacing negativo sutil. Aporta calidez y carácter editorial.
- **Inter** para body y UI — weight 400 body, 600 labels, 500 captions.
- **JetBrains Mono** para datos nutricionales (calorías, macros, gramos).
- **Headlines:** Lora 600 con letter-spacing -0.02em — elegante pero legible.
- **Body:** Inter 400, line-height 1.65 — lectura cómoda y cálida.
- **Principio:** La serif en headlines es la identidad. No usar sans-serif para títulos.

## Layout

- **Max-width:** 1160px centrado
- **Secciones:** Full-width con fondos alternos (warm white / warm gray)
- **Grid de features:** 3 columnas desktop → 1 mobile
- **Hero:** Asimétrico — texto a la izquierda, visual/interactivo a la derecha
- **Spacing vertical:** 80px desktop, 48px mobile
- **Bordes redondeados generosos:** 14-20px para sensación amigable

## Secciones

1. **Hero:** "Come mejor. Vive mejor. Todo con IA." — Lora serif headline, subtítulo, CTA verde, preview del planificador semanal
2. **Cómo funciona:** 3 pasos — 1) Define objetivos, 2) IA genera tu plan, 3) Compra y cocina
3. **Features:** 4 cards — Planificador IA, Recetas Personalizadas, Lista de Compras, Tracking Nutricional
4. **Preview del Plan:** Muestra visual de un plan semanal con cards de comidas (desayuno/almuerzo/cena)
5. **Nutrition Dashboard:** Preview del dashboard con macros, calorías, progreso semanal
6. **Planes:** 3 tiers (Basic/Premium/Family) — Basic gratis
7. **Testimonials:** 3 cards con fotos, nombres, resultados de salud
8. **FAQ:** 5 preguntas con accordion
9. **CTA Final:** "Empieza a comer mejor hoy" con gradient verde
10. **Footer:** Links, blog, social, legal

## Motion

- Scroll reveal con fade-up suave
- Hover en cards con elevación y borde verde
- Animación de barras de macros (fill animation)
- Transiciones orgánicas (0.3s ease-in-out)
- Respetar prefers-reduced-motion

## Unique Elements

- **Weekly Plan Preview:** Grid visual de 7 días con cards de comidas (iconos de comida, calorías)
- **Macro Bars:** Barras de progreso para proteína/carbs/grasa con animación fill
- **Nutrition Badges:** Pills con color verde para tags (keto, vegan, high-protein, etc.)
- **Recipe Cards:** Cards con placeholder de imagen, tiempo, dificultad, calorías
- **Warm section alternation:** Secciones alternan entre warm white y warm gray
- **Serif headlines:** Lora serif es la identidad visual — cálido, editorial, único
- **Organic shapes:** Bordes redondeados generosos, sin esquinas agresivas
