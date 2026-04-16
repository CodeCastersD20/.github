<div align="center">

<img src="../assets/CodeCasters.png" alt="CodeCasters Logo" width="180"/>

# CodeCasters

**soluciones limpias, eficientes y escalables**

_Ingenieros de la Universidad Tecnológica de Hermosillo_

![TypeScript](https://img.shields.io/badge/TypeScript-007ACC?style=for-the-badge&logo=typescript&logoColor=white)
![NestJS](https://img.shields.io/badge/nestjs-%23E0234E.svg?style=for-the-badge&logo=nestjs&logoColor=white)
![Next.js](https://img.shields.io/badge/next%20js-000000?style=for-the-badge&logo=nextdotjs&logoColor=white)
![React](https://img.shields.io/badge/react-%2320232a.svg?style=for-the-badge&logo=react&logoColor=%2361DAFB)
![Vite](https://img.shields.io/badge/Vite-B73BFE?style=for-the-badge&logo=vite&logoColor=FFD62E)
![Supabase](https://img.shields.io/badge/Supabase-181818?style=for-the-badge&logo=supabase&logoColor=white)
![MongoDb](https://img.shields.io/badge/MongoDB-4EA94B?style=for-the-badge&logo=mongodb&logoColor=white)
![MariaDb](https://img.shields.io/badge/MariaDB-003545?style=for-the-badge&logo=mariadb&logoColor=white)
![Node](https://img.shields.io/badge/Node%20js-339933?style=for-the-badge&logo=nodedotjs&logoColor=white)
![Python](https://img.shields.io/badge/Python-FFD43B?style=for-the-badge&logo=python&logoColor=blue)
![Prisma](https://img.shields.io/badge/Prisma-3982CE?style=for-the-badge&logo=Prisma&logoColor=white)
[![Ko-fi](https://img.shields.io/badge/Ko--fi-F16061?style=for-the-badge&logo=ko-fi&logoColor=white)](www.ko-fi.com/codecasters)
![ArchLinux](https://img.shields.io/badge/Arch_Linux-1793D1?style=for-the-badge&logo=arch-linux&logoColor=white)
![Linux](https://img.shields.io/badge/Linux-FCC624?style=for-the-badge&logo=linux&logoColor=black)
![Windows](https://img.shields.io/badge/Windows-0078D6?style=for-the-badge&logo=windows&logoColor=white)
![Github](https://img.shields.io/badge/GitHub-100000?style=for-the-badge&logo=github&logoColor=white)
![Git](https://img.shields.io/badge/GIT-E44C30?style=for-the-badge&logo=git&logoColor=white)
![Docker](https://img.shields.io/badge/Docker-2CA5E0?style=for-the-badge&logo=docker&logoColor=white)

</div>

---

## ¿Quiénes somos?

CodeCasters es un equipo de desarrollo de software especializado en aplicaciones web modernas. Priorizamos código limpio, arquitecturas mantenibles y soluciones eficientes adaptadas a cada problema. Aunque nuestro fuerte es el desarrollo web, también construimos aplicaciones de escritorio, móviles y herramientas de propósito general cuando el proyecto lo requiere.

---

## Filosofía de trabajo

- **Código limpio sobre código rápido** — escribimos pensando en quien lo lee después.
- **Soluciones al problema real** — nada de over-engineering innecesario.
- **Colaboración abierta** — revisamos, comentamos y aprendemos en equipo.
- **Tecnología al servicio del producto** — elegimos el stack que mejor resuelve, no el más de moda.

---

## ¿Qué entregamos?
- **Gestión ágil** — Seguimiento mediante tableros Kanban (GitHub Projects) y entregas incrementales.
- **Documentación técnica completa** — Diagramas de arquitectura, DER y documentación de API (Swagger/OpenAPI).
- **Código fuente auditable** — Repositorios organizados, con historial de commits limpio y semántico.
- **Garantía de calidad** — Software testeado y listo para producción, no solo "código que funciona".

---

## Stack web principal

| Área              | Tecnologías                                        |
| ----------------- | -------------------------------------------------- |
| **Frontend**      | React, TypeScript, Vite, Next.js, Tailwind CSS     |
| **Backend**       | NestJS, Node.js, TypeScript                        |
| **Bases de datos**| PostgreSQL, Supabase, Prisma ORM, MongoDb          |
| **Auth & Storage**| Supabase Auth, JWT                                 |
| **Testing**       | Jest, Vitest, Playwright, Testing Library          |
| **DevOps / CI**   | Git, GitHub Actions, ESLint, Prettier              |
| **Despliege**     | Vercel, Railway, Docker, VPS (Linux/Ubuntu/Arch)   |

---

## Equipo

| Integrante | Rol | Enfoque |
| ------------------------------------ | -------------------- | ------------------------------------------ |
| **Sadrach Juan Diego Garcia Flores** | Fullstack — Líder general y de backend | Arquitectura, API, lógica de negocio, integración, Linux Ops, etc |
| **Adrian Eduardo Santos Rosales** | Frontend — Líder de frontend | UI/UX, componentes, Vistas, etc |
| **Jesus Adriana Martinez Trillas** | Frontend | Vistas, integración con API, testing de UI, etc |
| **Erick Daniel Arvayo Aviles** | Backend | Servicios, lógica de negocio, base de datos, validaciones, etc |

---

## Estructura de proyectos

Nuestros repositorios siguen una estructura consistente para mono repo (usamos 2 repos en casi todos los casos):

```
proyecto/
├── docs/               # Documentación técnica
├── api/                # Backend — NestJS + Prisma
│   ├── src/
│   │   ├── modules/    # Módulos por dominio
│   │   └── common/     # Guards, interceptores, DTOs compartidos
│   └── prisma/
│       └── schema.prisma
│
├── web/                # Frontend — React + Vite
│   ├── src/
│   │   ├── pages/
│   │   ├── components/
│   │   ├── services/
│   │   └── lib/
│   └── e2e/
│
└── README.md
```

---

## Estándares de calidad

- Tipado estricto con TypeScript en todo el stack.
- DTOs validados con `class-validator`; sin datos sin validar llegando al core.
- Tests unitarios y E2E en cada proyecto antes de merge a `main`.
- Pipelines de CI (`lint → type-check → test → build`) automatizados.
- Revisión de código obligatoria entre pares antes de merge.
- Commits semánticos (`feat:`, `fix:`, `refactor:`, etc.).

---

## Seguridad

- JWT validado por guard en cada endpoint protegido.
- Control de acceso por roles en backend y frontend.
- Rate limiting en endpoints sensibles (autenticación, operaciones críticas).
- Variables de entorno nunca en el repositorio (`.env.example` como referencia).
- Headers de seguridad HTTP con Helmet en todos los servicios.
- Validación estricta de entrada con `whitelist: true`.

---

## Contacto

¿Tienes un proyecto o quieres colaborar?

> Equipo CodeCasters — Ingeniería en Tecnologías de la Información
> ContactUS: `jdiegodev0805+contactus@gmail.com`

---

<div align="center">

_CodeCasters — código con propósito._

</div>
