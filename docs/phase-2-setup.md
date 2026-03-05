# Fase 2 - Creación del proyecto con React + Vite

## Objetivo
Inicializar un proyecto frontend moderno, reproducible y listo para escalar sin deuda técnica temprana.

## Resultado esperado
Al finalizar esta fase tendrás:
- Proyecto React + Vite funcional.
- TailwindCSS instalado y validado.
- Base de convenciones para commits y ramas.
- Estructura inicial lista para la Fase 3.

## Decisiones técnicas (y por qué)
- **Vite** por velocidad en desarrollo y build.
- **React** por ecosistema, reutilización de componentes y mantenibilidad.
- **TailwindCSS** para estandarizar diseño y evitar CSS caótico.

## Paso a paso (ejecútalo tú)
> Usa Node LTS (idealmente 20+).

1. Crear proyecto
   ```bash
   npm create vite@latest portfolio -- --template react
   cd portfolio
   npm install
   ```

2. Instalar TailwindCSS
   ```bash
   npm install -D tailwindcss @tailwindcss/vite
   ```

3. Configurar plugin de Tailwind en `vite.config.ts`/`vite.config.js`.

4. Importar Tailwind en `src/index.css`:
   ```css
   @import "tailwindcss";
   ```

5. Validar entorno local
   ```bash
   npm run dev
   ```
   Si todo está correcto, deberías ver el proyecto en `http://localhost:5173`.

## Criterios de aceptación de la fase
- `npm run dev` inicia sin errores.
- `npm run build` compila exitosamente.
- Tailwind aplica estilos en al menos un componente de prueba.
- Proyecto en GitHub con primer commit limpio.

## Buenas prácticas recomendadas
- Commits pequeños y atómicos por tema.
- Mensajes de commit semánticos (`feat:`, `chore:`, `docs:`).
- Crear `README` de proyecto con comandos de setup y run.
- No mezclar lógica de negocio en componentes de presentación.

## Riesgos comunes (evítalos)
- Instalar dependencias sin bloquear versión de Node.
- Configurar Tailwind parcialmente y asumir que funciona.
- Saltar validaciones (`build` y `lint`) en etapa temprana.

## Checklist rápido
- [ ] Proyecto creado con Vite + React.
- [ ] Tailwind instalado y funcionando.
- [ ] Scripts de desarrollo y build probados.
- [ ] Repositorio con commit inicial.
- [ ] Preparado para la Fase 3 (estructura de carpetas).
