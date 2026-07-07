<h1 align="center">Christian Wandling</h1>

Senior Full-Stack Engineer with 9+ years building enterprise-scale web applications. Frontend depth in **Angular** and **Nx monorepos**, with production backend work in **.NET**, and hands-on with **React** and **NestJS**.
I care most about clean, modular architecture: making large codebases maintainable, testable, and fast to ship.

Currently migrating a .NET solution of 400+ projects that controls semiconductor manufacturing equipment to a new framework version, including a WCF blocking-to-async refactor and a SQLite-to-PostgreSQL move.
Additionally, I'm building infrastructure for multi-agent orchestration in a private lab: a ticket tracker that lets concurrent AI agents coordinate work across projects, exposed to agents via MCP, and a verification-first self-learning failure loop (not public yet).

Based in Ho Chi Minh City.


## Demo Shop - a cross-stack reference build

A self-directed project implementing one e-commerce domain across four interoperable stacks, built as a hands-on study in clean, well-tested architecture.
The same domain is built on each side: the API in **NestJS** and **ASP.NET Core**, the storefront in **Angular** and **React**, with a shared **Playwright** e2e suite catching behaviour drift.

A study project, not a production store (payment flow intentionally incomplete).

| Repo | What it is |
| --- | --- |
| [demo-shop-angular-nestjs](https://github.com/christian-wandling/demo-shop-angular-nestjs) | Angular + NgRx front end with a NestJS + Prisma API. The primary full-stack build |
| [demo-shop-dotnet-api](https://github.com/christian-wandling/demo-shop-dotnet-api) | ASP.NET Core re-implementation of the API (DDD, CQRS, EF Core, hexagonal) |
| [demo-shop-react-ui](https://github.com/christian-wandling/demo-shop-react-ui) | React + Zustand re-implementation of the storefront |
| [demo-shop-e2e](https://github.com/christian-wandling/demo-shop-e2e) | Implementation-agnostic Playwright suite, run across all versions to verify parity |

**Cross-cutting:** OAuth2/OIDC (Keycloak) · PostgreSQL · Docker · Storybook · Playwright · CI/CD (GitHub Actions) · Terraform/AWS

&nbsp;

## Contact

[LinkedIn](https://linkedin.com/in/christian-wandling)
