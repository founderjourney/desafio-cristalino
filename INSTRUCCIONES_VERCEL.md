# 🚀 INSTRUCCIONES PARA SUBIR A VERCEL

## Pasos para deployar tu landing page en Vercel:

### 1. **Crear cuenta en Vercel (si no tienes)**
- Ve a https://vercel.com
- Regístrate con tu correo: **mosaikolabs@gmail.com**
- Conecta tu cuenta de GitHub (recomendado)

### 2. **Preparar los archivos**
✅ **Ya están listos estos archivos:**
- `index.html` - Landing page principal
- `vercel.json` - Configuración de Vercel
- `package.json` - Información del proyecto
- `README.md` - Documentación

### 3. **Opción A: Deploy directo desde archivos**

1. **Comprimir archivos**:
   - Selecciona todos los archivos del proyecto
   - Crea un archivo ZIP llamado `landing-poder-interior.zip`

2. **Subir a Vercel**:
   - Ve a https://vercel.com/dashboard
   - Haz clic en **"New Project"**
   - Arrastra y suelta el archivo ZIP
   - Vercel detectará automáticamente que es un sitio estático
   - Haz clic en **"Deploy"**

### 4. **Opción B: Deploy desde GitHub (Recomendado)**

1. **Crear repositorio en GitHub**:
   ```bash
   # En tu terminal, ve a la carpeta del proyecto
   cd /home/us4rthink13/Documents/RetoVytex

   # Inicializar git (si no está inicializado)
   git init

   # Agregar archivos
   git add index.html vercel.json package.json README.md

   # Hacer commit
   git commit -m "Add landing page for poder interior webinar"

   # Crear repositorio en GitHub y conectar
   # (Seguir las instrucciones de GitHub)
   ```

2. **Conectar con Vercel**:
   - En Vercel dashboard, clic en **"New Project"**
   - Selecciona **"Import Git Repository"**
   - Elige el repositorio que acabas de crear
   - Vercel configurará automáticamente el deployment

### 5. **Configuración automática**
✅ **Vercel detectará automáticamente:**
- Tipo de proyecto: Static HTML
- Comando de build: No necesario
- Directorio de output: Raíz del proyecto
- Framework: None (Static)

### 6. **Después del deployment**
- **URL personalizada**: Puedes cambiar la URL en Project Settings
- **Dominio custom**: Conectar tu propio dominio si lo tienes
- **Analytics**: Activar para ver estadísticas de visitas

### 7. **URL de ejemplo**
Tu sitio estará disponible en algo como:
`https://landing-poder-interior-xxx.vercel.app`

### 8. **Actualizaciones futuras**
- Solo necesitas hacer push a GitHub (si usaste Opción B)
- O subir nuevos archivos (si usaste Opción A)
- Vercel hará deploy automático de los cambios

---

## 📞 **¿Necesitas ayuda?**

Si tienes problemas:
1. Revisa la documentación de Vercel: https://vercel.com/docs
2. El soporte de Vercel es muy rápido
3. Todo está configurado para funcionar automáticamente

## 🎯 **¡Tu landing page estará online en menos de 5 minutos!**

---

**Notas importantes:**
- La imagen de Tomás Gracia usará una imagen temporal de placeholder
- Una vez online, puedes reemplazarla con la imagen real desde el panel de Vercel
- El formulario redirige automáticamente al grupo de WhatsApp