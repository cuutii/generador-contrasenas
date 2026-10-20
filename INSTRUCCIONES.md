# 01 — Generador de Contraseñas

Mini app web **autocontenida** (un solo archivo, funciona sin internet) que genera
contraseñas seguras aleatorias.

## Qué hace
- Genera contraseñas de 8 a 32 caracteres.
- Opciones: incluir mayúsculas, números y símbolos (minúsculas siempre).
- Botón **Copiar** al portapapeles con aviso "¡Copiada!".
- Indicador de fortaleza en vivo (Débil / Media / Fuerte).
- Aleatoriedad criptográfica (`crypto.getRandomValues`).

## Cómo usarla (local)
1. Abrí el archivo `index.html` con doble clic (se abre en tu navegador).
2. Ajustá la longitud y las opciones.
3. Apretá **Generar** y **Copiar**.

No necesita internet ni instalación.

## Cómo COMPARTIRLA — opciones

### Opción 0 — Link público permanente (YA PUBLICADO ✅)
La app ya está online en GitHub Pages. Solo pasá este link:
**https://cuutii.github.io/generador-contrasenas/**
- Se abre desde cualquier lado (celu, compu), online.
- Es permanente y gratis.
- Repo: https://github.com/cuutii/generador-contrasenas

Para **actualizarla** después (cambios en el `index.html`): ver "Cómo actualizar"
al final de este archivo.

### Opción A — Enviar el archivo (la más fácil)
1. Mandá el archivo `index.html` por WhatsApp, correo o USB.
2. Quien lo recibe hace doble clic y se abre en su navegador.
   - Funciona en celular y compu, online y offline.

### Opción B — Subirlo a la nube y pasar el link (para que cualquiera abra con un clic)
Usá **Netlify Drop** (gratis, sin cuenta para empezar):
1. Entrá a **https://app.netlify.com/drop**
2. Arrastrá la carpeta `01-generador-contrasenas` (o solo el `index.html`).
3. Te da un link público (algo como `https://....netlify.app`) que abrís desde cualquier lado.
   - Ojo: es público. No subas nada privado.

Alternativa con GitHub Pages si ya tenés cuenta de GitHub.

### Opción C — Google Drive (guardar, no "ejecutar")
1. Subí `index.html` a tu Google Drive.
2. **Importante:** Drive lo muestra como código o lo baja, NO lo ejecuta como app.
   - Para que lo prueben, hay que **descargarlo** y abrirlo con doble clic.
   - Sirve más para GUARDAR una copia que para compartir viva.

### ¿Cuál usar?
- **Para un amigo rápido:** Opción A (mandar el archivo).
- **Para que many uses lo abran con un link:** Opción B (Netlify Drop).

## Detalles técnicos
- Un solo archivo `index.html` (~12,6 KB): HTML + CSS + JS embebidos.
- Sin dependencias externas (ni CDNs) → funciona 100% offline.
- Se creó con el proceso multi-agente de OpenCode
  (planner → implementer → reviewer). Verificado: APROBADO.

## Cómo ACTUALIZAR la web (si cambiás algo)
Si modificás el `index.html`, para que el link público se refleje:
1. Editá el archivo en `MIS-PROYECTOS\01-generador-contrasenas\index.html`.
2. Decime "actualizá la web" y yo hago el resto, o hacelo a mano:
   - `git add index.html`
   - `git commit -m "cambio"`
   - `git push`
3. GitHub Pages lo reconstruye solo en ~1 minuto.

## Origen
- Creado: 2026-10-20 como prueba del proceso multi-agente.
- Publicado: 2026-10-20 en GitHub Pages (https://cuutii.github.io/generador-contrasenas/).
- Registro completo en `ANOTADOR.md` del proyecto de OpenCode.
