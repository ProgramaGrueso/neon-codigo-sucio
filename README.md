# Neón & Código Sucio

Novela visual **para adultos** con minijuegos, hecha en **Godot 4.7** y exportada a web.

▶ **Jugar online:** https://programagrueso.github.io/neon-codigo-sucio/

> ⚠️ Contenido adulto (temática y escenas sugerentes, sin escenas explícitas). Solo mayores de 18.

## Qué es

Una historia de ciudad nocturna, corporaciones y secretos, con decisiones que cambian la ruta y el final.

- **Temporada 1** (4 episodios) con **5 finales** alcanzables.
- **Temporada 2 – Halcyon** (4 episodios) con ramas según cómo terminaste la primera.
- **Minijuegos:** strip poker, tetris laboral y hackeo de firewall (se pueden saltar).
- Guardado/carga, quicksave, backlog, auto/skip, galería de CGs y logros.
- Música original y arte generado con IA (ComfyUI).
- Soporte de teclado, ratón y mando.

## Controles

| Acción | Teclado/ratón | Mando |
|---|---|---|
| Avanzar | Espacio / Enter / clic | A |
| Pausa / atrás | Esc / clic derecho | B / Start |
| Auto | A | X |
| Skip | Ctrl (mantener = todo, botón = solo lo leído) | RB |
| Backlog | L / Tab | Y |
| Ocultar UI | H | LB |
| Quicksave / Quickload | F5 / F9 | desde pausa |
| Saltar minijuego | botón / pausa | Select |
| Tetris | ← → ↑ ↓ Espacio | D-pad, A, Y |

## Este repositorio

Contiene solo el **build web** (`index.html`, `index.pck`, `index.wasm`…) publicado con GitHub Pages. El código fuente del proyecto Godot (guiones `.vn`, motor en GDScript, tests y scripts de generación de arte) vive aparte.

Para ejecutarlo en local:

```bash
python3 -m http.server 8080
# abre http://localhost:8080
```

## Créditos

Historia, motor y programación: ProgramaGrueso. Arte y música generados con modelos de IA locales.
