# VIDEON IA - Como Grok (Funcional)

## PASO A PASO - Crear tu nuevo repositorio

### PASO 1: Crear repo nuevo
1. Ve a https://github.com/new
2. Repository name: videon-grok
3. Description: Generador de videos IA como Grok
4. Public
5. NO marques Add README
6. Click Create repository

### PASO 2: Subir archivos
1. Descomprime videon-grok-final.zip
2. En tu nuevo repo, click Add file > Upload files
3. Arrastra:
   - index.html
   - .nojekyll
   - carpeta js/
4. Commit changes

### PASO 3: Activar GitHub Pages
1. Ve a Settings > Pages (en tu repo)
2. Build and deployment > Source: Deploy from a branch
3. Branch: main / (root) > Save
4. Espera 60 segundos

### PASO 4: Abrir tu web
Tu web estará en:
https://TU-USUARIO.github.io/videon-grok/

Ejemplo: https://adnanjenoui3-afk.github.io/videon-grok/

### PASO 5: Usar
- Sube foto (opcional)
- Escribe prompt
- Click GENERAR
- Descarga video

Tu API ya está fija, no tienes que pegarla.

Si da error 401, regenera key en https://apimodels.app y pega en js/config.js y en index.html (busca API_KEY)
