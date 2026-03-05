# Fase 1 - Planificación y arquitectura del portafolio

## Objetivo
Definir una base técnica y de producto clara para construir un portafolio profesional con React + Vite + TailwindCSS, con foco en demostrar perfil backend/full stack.

## Alcance inicial (MVP)
Secciones del portafolio:
- Hero
- Sobre mí
- Tecnologías
- Proyectos
- Experiencia
- Contacto

## Stack y decisiones técnicas
- **React + Vite**: rapidez de desarrollo y build moderno.
- **TailwindCSS**: consistencia visual y escalabilidad en estilos.
- **Datos en JSON**: separación de contenido/presentación para facilitar mantenimiento.
- **Deploy en Vercel**: integración simple con GitHub y CI/CD básico.

## Arquitectura propuesta
```text
src/
  assets/
  components/
    ui/
    layout/
  sections/
  pages/
  data/
  styles/
  hooks/
  utils/
```

## Criterios de calidad
- Componentes reutilizables y con responsabilidad única.
- Convenciones de nombres consistentes.
- Accesibilidad básica (semántica, labels, contraste).
- Rendimiento inicial (imágenes optimizadas, lazy load donde aplique).
- Código mantenible (estructura por dominio + UI compartida).

## Riesgos a evitar
- Mezclar lógica de datos con presentación.
- Crear componentes demasiado grandes.
- Diseñar sin sistema de espaciado/tipografía definido.
- Publicar sin metadata SEO básica.

## Entregables de la fase
- Mapa de secciones y objetivo por sección.
- Estructura de carpetas acordada.
- Guía corta de estilos (tokens base).
- Lista de proyectos priorizados para mostrar.
