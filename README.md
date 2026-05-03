# Fix Pagos — Generador VPN SSTP

Herramienta web autocontenida (HTML + CSS + JavaScript puro) para generar
scripts de configuración de **VPN SSTP en Mikrotiks**.

## 🌐 Demo en vivo

https://TU-USUARIO.github.io/fix-pagos-vpn-generator/

*(reemplaza `TU-USUARIO` por tu usuario de GitHub una vez desplegado)*

## ✨ Características

- 100% del lado del cliente (no envía datos a ningún servidor)
- Un solo archivo HTML (funciona offline también)
- Sin dependencias externas
- Listo para producción

## 🚀 Cómo desplegar en GitHub Pages (gratis)

### Paso 1: Crea un repositorio en GitHub

1. Entra a https://github.com
2. Click en **"+"** (arriba derecha) → **"New repository"**
3. Nombre sugerido: `fix-pagos-vpn-generator`
4. Marca **"Public"** (requerido para Pages gratis)
5. NO marques "Add README" (ya tienes uno)
6. Click **"Create repository"**

### Paso 2: Sube los archivos

**Opción A — Desde la web (más fácil):**

1. En la página del repo recién creado, click en **"uploading an existing file"**
2. Arrastra `index.html` y `README.md`
3. Click **"Commit changes"**

**Opción B — Con git (requiere instalar git):**

```bash
git init
git add .
git commit -m "Initial commit"
git branch -M main
git remote add origin https://github.com/TU-USUARIO/fix-pagos-vpn-generator.git
git push -u origin main
```

### Paso 3: Activa GitHub Pages

1. En tu repo, ve a **Settings** (arriba)
2. En el menú izquierdo, click **"Pages"**
3. En **Source**, elige **"Deploy from a branch"**
4. En **Branch**, elige **"main"** y carpeta **"/ (root)"**
5. Click **"Save"**
6. Espera 1-2 minutos

### Paso 4: Tu URL pública

Te aparecerá algo como:
```
https://TU-USUARIO.github.io/fix-pagos-vpn-generator/
```

Esa es tu URL permanente y gratis 24/7.

## 🔄 Actualizar el generador

Cada vez que modifiques `index.html`:

**Desde la web**:
- Abre el archivo en tu repo → botón de lápiz (✏️) → edita → Commit changes

**Con git**:
```bash
git add index.html
git commit -m "Actualización"
git push
```

El cambio se refleja en ~1 minuto en tu URL pública.

## 💡 Dominio personalizado (opcional)

Si quieres usar un dominio propio como `vpn.fixpagos.mx`:

1. En tu dominio, agrega un registro CNAME:
   ```
   vpn.fixpagos.mx  →  TU-USUARIO.github.io
   ```
2. En GitHub → Settings → Pages → **Custom domain**: escribe `vpn.fixpagos.mx`
3. Marca **"Enforce HTTPS"**

## 📌 Notas

- **Gratis**: GitHub Pages es 100% gratis para repos públicos
- **Sin créditos Emergent**: no consume nada de tu plan de Emergent
- **Sin backend**: todo el trabajo lo hace el navegador del usuario
- **Disponibilidad**: 99.9% según SLA de GitHub

## 📞 Soporte

Este generador es parte del sistema **Fix Pagos**. Para soporte:
- WhatsApp: +52 961 898 3556
