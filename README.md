# JOAQUIN BERBOTTO


# Aplicación de Autenticación en React con Supabase

Una aplicación simple en React con pantallas de autenticación que incluyen Inicio de Sesión, Registro y una página de Inicio, conectada a Supabase para autenticación en el backend.

## Características

- Página de inicio de sesión con autenticación mediante Supabase
- Página de registro con creación de usuarios en Supabase
- Página de inicio con funcionalidad para cerrar sesión
- Enrutamiento entre páginas


### Requisitos previos

- Node.js (versión 14 o superior)
- npm o yarn
- Cuenta y proyecto en Supabase

### Instalación

1. Clona el repositorio  
2. Instala las dependencias:

```bash
npm install
```

3. Configura tus credenciales de Supabase:
   - Crea un archivo llamado `.env.local` en la raíz del proyecto
   - Agrega las siguientes variables de entorno:
   ```
   VITE_SUPABASE_URL=https://tu_proyecto_id.supabase.co
   VITE_SUPABASE_ANON_KEY=your_VITE_SUPABASE_ANON_KEY
   ```
   - Reemplaza `your_VITE_SUPABASE_ANON_KEY` con tu clave pública/anon de Supabase

4. Runea el servidor:

```bash
npm run dev
```

5. Abre tu navegador y dirigíte a `http://localhost:5173`

## Tecnologías Utilizadas

- React
- TypeScript
- React Router
- Vite
- Supabase (Autenticación y Backend)

## Estructura del Proyecto

```
src/
  ├── lib/
  │   └── supabaseClient.ts
  ├── pages/
  │   ├── Home.tsx
  │   ├── Login.tsx
  │   └── Signup.tsx
  ├── App.tsx
  ├── App.css
  ├── config.ts
  ├── main.tsx
  └── index.css
```

## Notas

- Debes configurar tu propio proyecto de Supabase y las variables de entorno para que funcione la autenticación
- Para producción, asegúrate de proteger correctamente tus variables de entorno
- Considera implementar funciones adicionales como restablecimiento de contraseña, verificación de correo electrónico y gestión de perfil

## Fotos

### Cuenta Activada
![Captura de pantalla 2025-06-12 102733](https://github.com/user-attachments/assets/ad5aa69d-2637-418b-b707-bf97da39b6b0)


### Excusa en Español
![Captura de pantalla 2025-06-12 102800](https://github.com/user-attachments/assets/89818331-1f7a-4ba3-91f4-f677f8bbf657)


### Excusa en Inglés
![Captura de pantalla 2025-06-12 102751](https://github.com/user-attachments/assets/4be82833-e314-456b-bd3f-c5997df1d79f)

