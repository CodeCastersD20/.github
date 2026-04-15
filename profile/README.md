<div align="center">

# CodeCasters

**Equipo de desarrollo web — soluciones limpias, eficientes y escalables**

_Universidad Tecnológica de Hermosillo_

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

## Stack principal

| Área              | Tecnologías                                        |
| ----------------- | -------------------------------------------------- |
| **Frontend**      | React, TypeScript, Vite, Tailwind CSS              |
| **Backend**       | NestJS, Node.js, TypeScript                        |
| **Bases de datos**| PostgreSQL, Supabase, Prisma ORM                   |
| **Auth & Storage**| Supabase Auth, JWT                                 |
| **Testing**       | Jest, Vitest, Playwright, Testing Library          |
| **DevOps / CI**   | Git, GitHub Actions, ESLint, Prettier              |

---

## Equipo

| Integrante | Rol | Enfoque |
| ------------------------------------ | -------------------- | ------------------------------------------ |
| **Sadrach Juan Diego Garcia Flores** | Fullstack — Líder general y de backend | Arquitectura, API, lógica de negocio, integración |
| **Adrian Eduardo Santos Rosales** | Frontend — Líder de frontend | UI/UX, componentes, experiencia de usuario |
| **Jesus Adriana Martinez Trillas** | Frontend | Vistas, integración con API, testing de UI |
| **Erick Daniel Arvayo Aviles** | Backend | Servicios, base de datos, validaciones |

---

## Estructura de proyectos

Nuestros repositorios siguen una estructura consistente:

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

> **Universidad Tecnológica de Hermosillo**
> Equipo CodeCasters — Ingeniería en Tecnologías de la Información

---

<div align="center">

_CodeCasters — código con propósito._

</div>
