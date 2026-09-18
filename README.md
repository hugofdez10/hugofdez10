<h1 align="center">Hugo Fernández Díez</h1>

<h3 align="center">
  Estudiante de Ingeniería Informática · Universidad de Deusto
</h3>

<p align="center">
  Desarrollo Web · SaaS · IA aplicada · Sistemas y Backend
</p>

<p align="center">
  <a href="mailto:hugofdezdiez@gmail.com">hugofdezdiez@gmail.com</a> ·
  <a href="https://www.linkedin.com/in/hugo-fernandez-diez/">LinkedIn</a> ·
  <a href="https://github.com/hugofdez10">GitHub</a>
</p>

---

<h2 align="center">⚡ Stack Tecnológico</h2>

<h3 align="center">Web & Frontend</h3>

<p align="center">
  <img src="https://skillicons.dev/icons?i=html,css,js,ts,react,nextjs,tailwind" />
</p>

<h3 align="center">Backend & Bases de Datos</h3>

<p align="center">
  <img src="https://skillicons.dev/icons?i=nodejs,supabase,postgres,mysql,java" />
</p>

<h3 align="center">Lenguajes, herramientas y despliegue</h3>

<p align="center">
  <img src="https://skillicons.dev/icons?i=c,cpp,git,github,vscode,vercel,linux" />
</p>

---

<h2 align="center">🚀 Proyectos Destacados</h2>

| Proyecto | Tecnología | Descripción |
|---|---|---|
| 🏘️ [Housing Management System](https://housing-management-system-jade.vercel.app/) | Next.js · Supabase · TypeScript | Plataforma de gestión del alojamiento del personal de temporada de Enchanted Parks (empresa estadounidense): cabañas, residentes, incidencias con fotos, roles e informes. Repositorio privado. |
| 🏠 [GestiDomus](https://gestidomus-os.vercel.app/) | Next.js · Supabase · TypeScript | SaaS de gestión inmobiliaria para administrar inmuebles, contratos, pagos, incidencias y recibos. Repositorio privado. |
| 💈 [Samoset Barbershop](https://github.com/hugofdez10/samoset-barbershop) | Next.js · Supabase · TypeScript | Web de mi servicio de barbería en el alojamiento Samoset (Nueva York): vídeos de trabajos, reservas por WhatsApp y panel de administración. [Web](https://samosetbarbershop.vercel.app/) |
| 🚌 [W&T Walmart Shuttle](https://walmart-shuttle.vercel.app/) | Next.js · Supabase · TypeScript | Sistema de reservas y gestión de plazas para el transporte semanal a Walmart para Enchanted Parks (empresa estadounidense). Repositorio privado. |
| ✅ [HugosProductivity](https://github.com/hugofdez10/HugosProductivity) | JavaScript · Web App | Aplicación personal de productividad para tareas, planificación y hábitos. |
| 🌍 [DeustoAir](https://github.com/hugofdez10/DeustoAir) | C · C++ · Cliente-Servidor | Proyecto académico colaborativo para gestionar y consultar datos de calidad del aire. |
| ♟️ [DeustoChess](https://github.com/hugofdez10/DeustoChess) | Java | Proyecto académico de ajedrez centrado en programación orientada a objetos y lógica de juego. |

---

<h2 align="center">🧩 Proyectos Web & SaaS</h2>

### 🏘️ Housing Management System · Enchanted Parks

Plataforma web para gestionar el alojamiento del personal de temporada de Enchanted Parks, una empresa estadounidense: cabañas, residentes, mudanzas e incidencias de mantenimiento, cada perfil con su propio acceso.

**Funcionalidades principales:**

- Gestión de alojamientos y cabañas, con capacidad máxima garantizada por la base de datos.
- Alta de residentes, asignación de cabaña e invitación por correo para que cada residente active su cuenta.
- Mudanzas entre cabañas con historial.
- Vista *My Housing* para que cada residente consulte su cabaña y sus compañeros.
- Incidencias con fotos: el residente las reporta, administración las clasifica y las resuelve con una nota y fotos de la reparación.
- Informe de ocupación en pantalla y exportable a Excel.
- Roles (Super Admin, Admin, Resident Assistant, Staff y residente) con menú y permisos según el rol.
- Directorio de contactos con botones de WhatsApp y llamada.
- Instalable en el móvil como aplicación.

**Aspectos técnicos:**

- Row Level Security (RLS) en todas las tablas y permisos mínimos por tabla.
- Fotos en almacenamiento privado, servidas con URLs firmadas que caducan.
- Esquema de base de datos controlado con más de 50 migraciones SQL versionadas.
- TypeScript en modo estricto, con tipos generados a partir del esquema.

**Stack:** Next.js · React · TypeScript · Supabase (PostgreSQL, Auth, Storage) · Tailwind CSS · shadcn/ui · Vercel

🔗 Web: [housing-management-system-jade.vercel.app](https://housing-management-system-jade.vercel.app/) (acceso con cuenta)

🔒 Repositorio privado.

---

### 🏠 GestiDomus

Plataforma SaaS para la gestión de propiedades en alquiler.

**Funcionalidades principales:**

- Gestión de inmuebles.
- Gestión de contratos.
- Control de pagos mensuales.
- Registro de incidencias.
- Generación de recibos PDF.
- Panel de control con métricas.
- Backend con Supabase.
- Gestión documental y almacenamiento de archivos.

**Stack:** Next.js · React · TypeScript · Supabase · PostgreSQL · Tailwind CSS · Vercel

🔗 Demo: [gestidomus-os.vercel.app](https://gestidomus-os.vercel.app/dashboard)

🔒 Repositorio privado.

---


### 💈 Samoset Barbershop

Web de mi servicio de barbería en el alojamiento Samoset (Queensbury, Nueva York), creada durante el programa Work & Travel.

**Funcionalidades principales:**

- Landing responsive pensada para móvil.
- Vídeos verticales de mis cortes, editados y optimizados para web.
- Reserva directa por WhatsApp con el mensaje ya escrito.
- Servicios, duración y precio.
- Panel de administración con login para aceptar o rechazar solicitudes de cita.
- Base de datos con RLS y una restricción que impide aceptar dos citas a la misma hora.

**Stack:** Next.js · React · TypeScript · Supabase · Tailwind CSS · Vercel

🔗 Web: [samosetbarbershop.vercel.app](https://samosetbarbershop.vercel.app/) · Código: [samoset-barbershop](https://github.com/hugofdez10/samoset-barbershop)

---

### 🚌 W&T Walmart Shuttle

Sistema web para organizar las reservas del transporte semanal a Walmart durante el programa Work & Travel.

**Funcionalidades principales:**

- Reserva de plazas por turno.
- Control del límite de pasajeros.
- Organización de viajes y horarios.
- Consulta de disponibilidad.
- Gestión de reservas desde el móvil.
- Reglas para evitar reservas duplicadas.
- Panel de administración del servicio.

**Stack:** Next.js · React · TypeScript · Supabase · Tailwind CSS · Vercel

🔗 Web: [walmart-shuttle.vercel.app](https://walmart-shuttle.vercel.app/)

🔒 Repositorio privado.

---

### ✅ HugosProductivity

Aplicación web personal de productividad enfocada en organización diaria, planificación y hábitos.

**Funcionalidades principales:**

- Gestión de tareas.
- Organización diaria.
- Planificación personal.
- Seguimiento de hábitos.
- Interfaz simple y práctica.

**Stack:** JavaScript · Web App


---


<h2 align="center">🎓 Proyectos Académicos</h2>

### 🌍 DeustoAir

Proyecto académico colaborativo desarrollado para la gestión y consulta de datos de calidad del aire mediante una arquitectura cliente-servidor.

**Aspectos trabajados:**

- Programación en C y C++.
- Arquitectura cliente-servidor.
- Gestión de datos.
- Comunicación entre procesos.
- Organización modular del código.
- Trabajo colaborativo mediante GitHub.

**Tecnologías:** C · C++ · SQLite · Cliente-Servidor

---

### ♟️ DeustoChess

Proyecto académico desarrollado en Java, centrado en la programación orientada a objetos y la lógica de un juego de ajedrez.

**Aspectos trabajados:**

- Diseño orientado a objetos.
- Gestión de piezas y tablero.
- Lógica de movimientos.
- Separación de responsabilidades.
- Estructura modular del proyecto.

**Tecnologías:** Java

---

<h2 align="center">👨‍💻 Sobre mí</h2>

Soy estudiante de Ingeniería Informática en la Universidad de Deusto, con interés en el desarrollo de aplicaciones web, productos SaaS y soluciones digitales con utilidad real.

Me gusta crear proyectos que no se queden solo en código, sino que intenten resolver problemas concretos: desde plataformas de gestión hasta herramientas para empresas, productividad personal o experiencias reales como mi estancia en Estados Unidos donde fui seleccionado por la directora de recursos humanos para desarrollar más software para la empresa debido a una solución de software que desarrollé para el supervisor de los alojamientos ya que me eligió como asistente residente, me ocupaba de cubrir su lugar cuando no estaba y en ayudarle en lo que fuera necesario.

Actualmente estoy centrado en:

- Desarrollo web con Next.js, React y TypeScript.
- Backend y bases de datos con Supabase y PostgreSQL.
- Aplicaciones SaaS.
- Automatización e integración de IA en flujos de desarrollo.
- Mejora de arquitectura, diseño y experiencia de usuario.
- Desarrollo de proyectos reales aplicables a empresas y usuarios.

---

<h2 align="center">📚 Actualmente aprendiendo</h2>

- Desarrollo full-stack moderno.
- Arquitectura de software.
- Bases de datos relacionales.
- Despliegue de aplicaciones web.
- Integración de IA en procesos de desarrollo.

---

<h2 align="center">📫 Contacto</h2>

<p align="center">
  <a href="mailto:hugofdezdiez@gmail.com">
    <img src="https://img.shields.io/badge/Email-hugofdezdiez%40gmail.com-red?style=for-the-badge&logo=gmail&logoColor=white" />
  </a>
  <a href="https://www.linkedin.com/in/hugo-fernandez-diez/">
    <img src="https://img.shields.io/badge/LinkedIn-Hugo%20Fernández-blue?style=for-the-badge&logo=linkedin&logoColor=white" />
  </a>
  <a href="https://github.com/hugofdez10">
    <img src="https://img.shields.io/badge/GitHub-hugofdez10-181717?style=for-the-badge&logo=github" />
  </a>
</p>

---

<p align="center">
  <i>Construyendo proyectos reales mientras aprendo, mejoro y convierto ideas en software.</i>
</p>
