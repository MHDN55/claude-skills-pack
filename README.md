# Claude Skills Pack

286 skills from [affaan-m/ECC](https://github.com/affaan-m/ECC) (Everything Claude Code, MIT license), sorted by category.
Downloaded 2026-08-26. Each skill is a folder containing a SKILL.md.

To use a skill: copy its folder into `~/.claude/skills/` (personal) or `.claude/skills/` (per project).

## 01 Core Workflow

- **agentic-engineering** — Operate as an agentic engineer using eval-first execution, decomposition, and cost-aware model routing. Use when planning or executing engineering work that age
- **ai-first-engineering** — Engineering operating model for teams where AI agents generate a large share of implementation output. Use when setting team process, review gates, or ownership
- **architecture-decision-records** — Capture architectural decisions made during Claude Code sessions as structured ADRs. Auto-detects decision moments, records context, alternatives considered, an
- **blueprint** — >-
- **codebase-onboarding** — Analyze an unfamiliar codebase and generate a structured onboarding guide with architecture map, key entry points, conventions, and a starter CLAUDE.md. Use whe
- **codehealth-mcp** — Real-time structural Code Health via CodeScene MCP — review before edits, verify score deltas after changes, gate commits and PRs. Use when reviewing code qua
- **code-tour** — Create CodeTour `.tour` files — persona-targeted, step-by-step walkthroughs with real file and line anchors. Use for onboarding tours, architecture walkthroug
- **coding-standards** — Baseline cross-project coding conventions for naming, readability, immutability, and code-quality review. Use detailed frontend or backend skills for framework-
- **contract-first** — Use when multiple consumers and providers must evolve an API or event schema without field drift, integration surprises, or one side silently redefining the int
- **delivery-gate** — Stop hook that blocks Claude from finishing until quality checks pass. Detects rationalization patterns (surface text heuristics), stale learning logs (filesyst
- **dynamic-workflow-mode** — "Design task-local harnesses, eval gates, and reusable skill extraction for Claude dynamic workflow mode and other adaptive agent harnesses. Use when building a
- **error-handling** — Patterns for robust error handling across TypeScript, Python, and Go. Covers typed errors, error boundaries, retries, circuit breakers, and user-facing error me
- **git-workflow** — Git workflow patterns including branching strategies, commit conventions, merge vs rebase, conflict resolution, and collaborative development best practices for
- **hexagonal-architecture** — Design, implement, and refactor Ports & Adapters systems with clear domain boundaries, dependency inversion, and testable use-case orchestration across TypeScri
- **inherit-legacy-style** — Legacy-project style inheritance skill. Use when the user types /inherit-legacy-style, or when onboarding an AI coding agent onto a hand-written legacy project 
- **intent-driven-development** — Turn ambiguous or high-impact product and engineering changes into scoped, verifiable acceptance criteria before or alongside implementation. Use when a user as
- **living-docs-governance** — "Keep a long-lived project's documentation from rotting by assigning existing project docs clear constitution, map, status, and history roles, then wiring the a
- **opensource-pipeline** — "Open-source pipeline: fork, sanitize, and package private projects for safe public release. Chains 3 agents (forker, sanitizer, packager). Triggers: '/opensour
- **orch-add-feature** — Orchestrate building a brand-new feature end to end — research, plan, TDD implementation, review, and gated commit — by delegating each phase to the matchin
- **orch-build-mvp** — Orchestrate bootstrapping a working MVP from a design or spec document — ingest the doc, plan thin vertical slices, scaffold the first end-to-end slice, then 
- **orch-change-feature** — Orchestrate altering an existing, working feature to new desired behavior — update its tests to the new spec, change the implementation to match, review, and 
- **orch-fix-defect** — Orchestrate fixing a bug — reproduce it as a failing regression test, fix to green, review, and gated commit — by delegating each phase to the matching ECC 
- **orch-pipeline** — Shared orchestration engine for the orch-* skill family. Defines the gated Research-Plan-TDD-Review-Commit pipeline, the size classifier, the agent map, and the
- **orch-refine-code** — Orchestrate a behavior-preserving refactor — confirm tests are green, restructure without changing behavior, keep tests green, review, and gated commit. Use w
- **plan-canvas** — Open plans and HTML artifacts in a local browser canvas where the human annotates elements, chats, and approves or requests changes without leaving the page. Us
- **plankton-code-quality** — "Write-time code quality enforcement using Plankton — auto-formatting, linting, and Claude-powered fixes on every file edit via hooks. Use when setting up wri
- **plan-orchestrate** — Read a plan document, decompose it into steps, design a per-step agent chain from the ECC catalogue, and emit ready-to-paste /orchestrate custom prompts. Genera
- **ralphinho-rfc-pipeline** — RFC-driven multi-agent DAG execution pattern with quality gates, merge queues, and work unit orchestration. Use when running RFC-driven multi-agent execution wi
- **recursive-decision-ledger** — Use when the user asks for repeated rollouts, marked decision processes, high-dimensional search, stochastic optimization, local-optima exploration, ensemble co
- **repo-scan** — Bootstrap pointer that installs the external repo-scan skill from a pinned, reviewable commit. Use when repo-scan must be installed before running its cross-sta
- **santa-method** — "Multi-agent adversarial verification with convergence loop. Two independent review agents must both pass before output ships. Use when output must clear two in
- **tdd-workflow** — Use this skill when writing new features, fixing bugs, or refactoring code. Enforces test-driven development with 80%+ coverage including unit, integration, and
- **verification-loop** — "A comprehensive verification system for Claude Code sessions. Use when verifying a Claude Code session's work before claiming it is complete."

## 02 Agents & Orchestration

- **agent-architecture-audit** — Full-stack diagnostic for agent and LLM applications. Audits the 12-layer agent stack for wrapper regression, memory pollution, tool discipline failures, hidden
- **agent-eval** — Head-to-head comparison of coding agents (Claude Code, Aider, Codex, etc.) on custom tasks with pass rate, cost, time, and consistency metrics. Use when choosin
- **agent-harness-construction** — Design and optimize AI agent action spaces, tool definitions, and observation formatting for higher completion rates. Use when defining or revising an agent's t
- **agentic-os** — Build persistent multi-agent operating systems on Claude Code. Covers kernel architecture, specialist agents, slash commands, file-based memory, scheduled autom
- **agent-introspection-debugging** — Structured self-debugging workflow for AI agent failures using capture, diagnosis, contained recovery, and introspection reports. Use when an agent run fails an
- **agent-payment-x402** — Add x402 payment execution to AI agents with per-task budgets, spending controls, and non-custodial wallets. Supports Base through agentwallet-sdk and X Layer t
- **agent-self-evaluation** — Use after completing any non-trivial task. The agent self-rates its output on 5 axes — accuracy, completeness, clarity, actionability, conciseness — with co
- **agent-sort** — Build an evidence-backed ECC install plan for a specific repo by sorting skills, commands, rules, hooks, and extras into DAILY vs LIBRARY buckets using parallel
- **autonomous-agent-harness** — Transform Claude Code into a fully autonomous agent system with persistent memory, scheduled operations, computer use, and task queuing. Replaces standalone age
- **autonomous-loops** — "Patterns and architectures for autonomous Claude Code loops — from simple sequential pipelines to RFC-driven multi-agent DAG systems. Retained for compatibil
- **benchmark** — Use this skill to measure performance baselines, detect regressions before/after PRs, and compare stack alternatives.
- **benchmark-methodology** — >-
- **benchmark-optimization-loop** — Use when the user asks to make something faster, try many variants, run recursive optimization, benchmark latency/throughput/cost, or choose the best implementa
- **claude-devfleet** — Orchestrate multi-agent coding tasks via Claude DevFleet — plan projects, dispatch parallel agents in isolated worktrees, monitor progress, and read structure
- **continuous-agent-loop** — Patterns for continuous autonomous agent loops with quality gates, evals, and recovery controls. Use when running an agent loop that must self-check, gate on ev
- **cost-aware-llm-pipeline** — Cost optimization patterns for LLM API usage — model routing by task complexity, budget tracking, retry logic, and prompt caching. Use when LLM spend needs to
- **cost-tracking** — Track and report Claude Code token usage, spending, and budgets from the local ECC cost-tracker metrics log. Use when the user asks about costs, spending, usage
- **council** — Convene a four-voice council for ambiguous decisions, tradeoffs, and go/no-go calls. Use when multiple valid paths exist and you need structured disagreement be
- **council-multi-model** — Add one optional external Codex critique after the existing council has produced a decision draft. Use when an ambiguous, high-consequence decision would benefi
- **dev-team** — Simulate a collaborative dev team session where multiple role-based personas (PM, Architect, Developer, QA) respond to the same problem together in one session.
- **enterprise-agent-ops** — Operate long-lived agent workloads with observability, security boundaries, and lifecycle management. Use when running long-lived agent workloads that need obse
- **eval-harness** — Formal evaluation framework for Claude Code sessions implementing eval-driven development (EDD) principles. Use when a Claude Code workflow needs a formal eval 
- **gan-style-harness** — "GAN-inspired Generator-Evaluator agent harness for building high-quality applications autonomously. Based on Anthropic's March 2026 harness design paper. Use w
- **loop-design-check** — "Design a goal-oriented agent loop, and review it for the ways loops go wrong — spinning and burning tokens, Goodhart-gaming the verifier, or running a wrong 
- **mcp-server-patterns** — Build MCP servers with Node/TypeScript SDK — tools, resources, prompts, Zod validation, stdio vs Streamable HTTP. Use Context7 or official MCP docs for latest
- **parallel-execution-optimizer** — Use when the user wants a task done much faster through parallel work, concurrent agents, batched tool calls, isolated worktrees, or many independent verificati
- **prompt-optimizer** — >-
- **regex-vs-llm-structured-text** — Decision framework for choosing between regex and LLM when parsing structured text — start with regex, add LLM only for low-confidence edge cases.
- **team-agent-orchestration** — "Run team-based orchestration for agent squads using work items, ownership, agent Kanban, merge gates, and control pane handoffs. Use when coordinating an agent
- **team-builder** — Interactive agent picker for composing and dispatching parallel teams. Use when composing and dispatching a parallel team of agents for a task.

## 03 Context & Memory

- **config-gc** — Garbage collection for your Claude Code configuration. Periodically scans ~/.claude (skills, memory, hooks, permissions, MCP servers, caches) for redundant, sta
- **context-budget** — Audits Claude Code context window consumption across agents, skills, MCP servers, and rules. Identifies bloat, redundant components, and produces prioritized to
- **continuous-learning** — "[DEPRECATED - use continuous-learning-v2] Legacy v1 stop-hook skill extractor. v2 is a strict superset with instinct-based, project-scoped, hook-reliable learn
- **continuous-learning-v2** — Instinct-based learning system that observes sessions via hooks, creates atomic instincts with confidence scoring, and evolves them into skills/commands/agents.
- **hookify-rules** — This skill should be used when the user asks to create a hookify rule, write a hook rule, configure hookify, add a hookify rule, or needs guidance on hookify ru
- **knowledge-ops** — Knowledge base management, ingestion, sync, and retrieval across multiple storage layers (local files, MCP memory, vector stores, Git repos). Use when the user 
- **rules-distill** — "Scan skills to extract cross-cutting principles and distill them into rules — append, revise, or create new rule files. Use when the same principle keeps rec
- **skill-comply** — Visualize whether skills, rules, and agent definitions are actually followed — auto-generates scenarios at 3 prompt strictness levels, runs agents, classifies
- **skill-scout** — Search existing local, marketplace, GitHub, and web skill sources before creating a new skill. Use when the user wants to create, build, fork, or find a skill f
- **skill-stocktake** — "Use when auditing Claude skills and commands for quality. Supports Quick Scan (changed skills only) and Full Stocktake modes with sequential subagent batch eva
- **strategic-compact** — Suggests manual context compaction at logical intervals to preserve context through task phases rather than arbitrary auto-compaction. Use when a session is app
- **token-budget-advisor** — >-
- **unified-memory** — Share durable, inspectable context and handoffs between Claude, Codex, Hermes, Cursor, OpenCode, and other agents through the local ECC Memory Vault. Use when a
- **workspace-surface-audit** — Audit the active repo, MCP servers, plugins, connectors, env surfaces, and harness setup, then recommend the highest-value ECC-native skills, hooks, agents, and

## 04 Testing & QA

- **ai-regression-testing** — Regression testing strategies for AI-assisted development. Sandbox-mode API testing without database dependencies, automated bug-check workflows, and patterns t
- **automation-audit-ops** — Evidence-first automation inventory and overlap audit workflow for ECC. Use when the user wants to know which jobs, hooks, connectors, MCP servers, or wrappers 
- **browser-qa** — Use this skill to automate visual testing and UI interaction verification using browser automation after deploying features.
- **canary-watch** — Use this skill to monitor and verify a deployed URL after releases — checks HTTP endpoints, SSE streams, static assets, console errors, and performance regres
- **click-path-audit** — "Trace every user-facing button/touchpoint through its full state change sequence to find bugs where functions individually work but cancel each other out, prod
- **e2e-testing** — Playwright E2E testing patterns, Page Object Model, configuration, CI/CD integration, artifact management, and flaky test strategies. Use when writing Playwrigh
- **production-audit** — Local-evidence production readiness audit for shipped apps, pre-launch reviews, post-merge checks, and "what breaks in prod?" questions without sending repo dat
- **windows-desktop-e2e** — E2E testing for Windows native desktop apps (WPF, WinForms, Win32/MFC, Qt) using pywinauto and Windows UI Automation. Use when writing E2E tests for a Windows n

## 05 Security

- **defi-amm-security** — Security checklist for Solidity AMM contracts, liquidity pools, and swap flows. Covers reentrancy, CEI ordering, donation or inflation attacks, oracle manipulat
- **gateguard** — Fact-forcing gate that blocks Edit/Write/Bash (including MultiEdit) and demands concrete investigation (importers, data schemas, user instruction) before allowi
- **llm-trading-agent-security** — Security patterns for autonomous trading agents with wallet or transaction authority. Covers prompt injection, spend limits, pre-send simulation, circuit breake
- **safety-guard** — Use this skill to prevent destructive operations when working on production systems or running agents autonomously.
- **security-bounty-hunter** — Hunt for exploitable, bounty-worthy security issues in repositories. Focuses on remotely reachable vulnerabilities that qualify for real reports instead of nois
- **security-review** — Use this skill when adding authentication, handling user input, working with secrets, creating API endpoints, or implementing payment/sensitive features. Provid
- **security-scan** — Scan your Claude Code configuration (.claude/ directory) for security vulnerabilities, misconfigurations, and injection risks using AgentShield. Checks CLAUDE.m

## 06 Research & Knowledge

- **competitive-platform-analysis** — >-
- **competitive-report-structure** — >-
- **deep-research** — Multi-source deep research using firecrawl and exa MCPs. Searches the web, synthesizes findings, and delivers cited reports with source attribution. Use when th
- **documentation-lookup** — Use up-to-date library and framework docs via Context7 MCP instead of training data. Activates for setup questions, API references, code examples, or when the u
- **exa-search** — Neural search via Exa MCP for web, code, and company research. Use when the user needs web search, code examples, company intel, people lookup, or AI-powered de
- **iterative-retrieval** — Pattern for progressively refining context retrieval to solve the subagent context problem. Use when a subagent lacks the context it needs and retrieval must be
- **lead-intelligence** — AI-native lead intelligence and outreach pipeline. Replaces Apollo, Clay, and ZoomInfo with agent-powered signal scoring, mutual ranking, warm path discovery, s
- **market-research** — Conduct market research, competitive analysis, investor due diligence, and industry intelligence with source attribution and decision-oriented summaries. Use wh
- **research-ops** — Evidence-first current-state research workflow for ECC. Use when the user wants fresh facts, comparisons, enrichment, or a recommendation built from current pub
- **scientific-db-pubmed-database** — Direct PubMed and NCBI E-utilities search workflows for biomedical literature, MeSH queries, PMID lookup, citation retrieval, and API-backed literature monitori
- **scientific-db-uspto-database** — USPTO patent and trademark data workflow for official record lookup, PatentSearch queries, TSDR checks, assignment data, and reproducible IP research logs. Use 
- **scientific-pkg-gget** — gget CLI and Python workflow for quick genomic database queries, sequence lookup, BLAST-style searches, enrichment checks, and reproducible bioinformatics evide
- **scientific-thinking-literature-review** — Systematic literature-review workflow for academic, biomedical, technical, and scientific topics, including search planning, source screening, synthesis, citati
- **scientific-thinking-scholar-evaluation** — Structured scholarly-work evaluation for papers, proposals, literature reviews, methods sections, evidence quality, citation support, and research-writing feedb
- **search-first** — Research-before-coding workflow. Search for existing tools, libraries, and patterns before writing custom code. Invokes the researcher agent.

## 07 Frontend & UI

- **accessibility** — Design, implement, and audit inclusive digital products using WCAG 2.2 Level AA. Use when building or auditing UI that must meet WCAG 2.2 Level AA, or when revi
- **angular-developer** — Generates Angular code and provides architectural guidance. Trigger when creating projects, components, or services, or for best practices on reactivity (signal
- **design-system** — Use this skill to generate or audit design systems, check visual consistency, and review PRs that touch styling. Use when generating or auditing a design system
- **frontend-a11y** — >
- **frontend-design-direction** — Set an ECC-specific frontend design direction for production UI work. Use when building or improving websites, dashboards, applications, components, landing pag
- **frontend-patterns** — Frontend development patterns for React, Next.js, state management, performance optimization, and UI best practices. Use when building or reviewing React or Nex
- **frontend-slides** — Create stunning, animation-rich HTML presentations from scratch or by converting PowerPoint files. Use when the user wants to build a presentation, convert a PP
- **liquid-glass-design** — iOS 26 Liquid Glass design system — dynamic glass material with blur, reflection, and interactive morphing for SwiftUI, UIKit, and WidgetKit. Use when buildin
- **make-interfaces-feel-better** — Apply concrete design-engineering details that make interfaces feel polished. Use when reviewing or improving UI spacing, typography, borders, shadows, motion, 
- **motion-advanced** — Advanced motion patterns for React / Next.js — drag & drop, gestures, text animations, SVG path drawing, custom hooks, imperative sequences (useAnimate), load
- **motion-foundations** — Motion tokens, spring presets, performance rules, device adaptation, accessibility enforcement, and SSR safety for React / Next.js using motion/react. Foundatio
- **motion-patterns** — Production-ready animation patterns for React / Next.js — button, modal, toast, stagger, page transitions, exit animations, scroll, and layout — built on mo
- **motion-ui** — "Production-ready UI motion system for React/Next.js. Use when implementing animations, transitions, or motion patterns."
- **nextjs-turbopack** — Next.js 16+ and Turbopack — incremental bundling, FS caching, dev speed, and when to use Turbopack vs webpack.
- **nuxt4-patterns** — Nuxt 4 app patterns for hydration safety, performance, route rules, lazy loading, and SSR-safe data fetching with useFetch and useAsyncData. Use when building o
- **react-patterns** — React 18/19 patterns including hooks discipline, server/client component boundaries, Suspense + error boundaries, form actions, data fetching, state management 
- **react-performance** — React and Next.js performance optimization patterns adapted from Vercel Engineering's React Best Practices (https://github.com/vercel-labs/agent-skills). Organi
- **react-testing** — React component testing with React Testing Library, Vitest/Jest, MSW for network mocking, accessibility assertions with axe, and the decision boundary between c
- **taste** — A creative-direction (taste) layer for music videos and short-form edits in the angelcore / cloud-trance / hyperpop visual family. Distills a named-genre aesthe
- **ui-demo** — Record polished UI demo videos using Playwright. Use when the user asks to create a demo, walkthrough, screen recording, or tutorial video of a web application.
- **ui-to-vue** — Use when the user has UI screenshots or design exports that need batch conversion into Vue 3 components, especially with Vant, Element Plus, or Ant Design Vue.
- **vite-patterns** — Vite build tool patterns including config, plugins, HMR, env variables, proxy setup, SSR, library mode, dependency pre-bundling, and build optimization. Activat
- **vue-patterns** — Vue.js 3 Composition API patterns, component architecture, reactivity best practices, Pinia state management, Vue Router navigation, and Nuxt SSR patterns. Acti

## 08 Backend & APIs

- **api-connector-builder** — Build a new API connector or provider by matching the target repo's existing integration pattern exactly. Use when adding one more integration without inventing
- **api-design** — REST API design patterns including resource naming, status codes, pagination, filtering, error responses, versioning, and rate limiting for production APIs. Use
- **backend-patterns** — Backend architecture patterns, API design, database optimization, and server-side best practices for Node.js, Express, and Next.js API routes. Use when building
- **bun-runtime** — Bun as runtime, package manager, bundler, and test runner. When to choose Bun vs Node, migration notes, and Vercel support.
- **content-hash-cache-pattern** — Cache expensive file processing results using SHA-256 content hashes — path-independent, auto-invalidating, with service layer separation. Use when repeated f
- **data-throughput-accelerator** — Use when large data ingestion, backfill, export, ETL, warehouse loading, manifest catch-up, or table synchronization needs to become much faster while preservin
- **django-celery** — Django + Celery async task patterns — configuration, task design, beat scheduling, retries, canvas workflows, monitoring, and testing. Use when adding backgro
- **django-patterns** — Django architecture patterns, REST API design with DRF, ORM best practices, caching, signals, middleware, and production-grade Django apps. Use when building or
- **django-security** — Django security best practices, authentication, authorization, CSRF protection, SQL injection prevention, XSS prevention, and secure deployment configurations. 
- **django-tdd** — Django testing strategies with pytest-django, TDD methodology, factory_boy, mocking, coverage, and testing Django REST Framework APIs. Use when writing Django o
- **django-verification** — "Verification loop for Django projects: migrations, linting, tests with coverage, security scans, and deployment readiness checks before release or PR."
- **dotnet-patterns** — Idiomatic C# and .NET patterns, conventions, dependency injection, async/await, and best practices for building robust, maintainable .NET applications. Use when
- **fastapi-patterns** — FastAPI best practices covering project structure, Pydantic v2 schemas, dependency injection, async handlers, authentication, authorization, transactional servi
- **jpa-patterns** — JPA/Hibernate patterns for entity design, relationships, query optimization, transactions, auditing, indexing, pagination, and pooling in Spring Boot. Use when 
- **laravel-patterns** — Laravel architecture patterns, routing/controllers, Eloquent ORM, service layers, queues, events, caching, and API resources for production apps. Use when build
- **laravel-plugin-discovery** — Discover and evaluate Laravel packages via LaraPlugins.io MCP. Use when the user wants to find plugins, check package health, or assess Laravel/PHP compatibilit
- **laravel-security** — Laravel security best practices — authentication, authorization, Eloquent safety, CSRF, XSS prevention, API security, and secure deployment configurations. Us
- **laravel-tdd** — Laravel testing strategies with PHPUnit, Pest, model factories, HTTP tests, Sanctum authentication testing, mocking, and coverage. Use when writing Laravel test
- **laravel-verification** — "Verification loop for Laravel projects: env checks, linting, static analysis, tests with coverage, security scans, and deployment readiness. Use when verifying
- **latency-critical-systems** — Use for latency-sensitive systems such as realtime dashboards, market data, streaming agents, execution gateways, queues, caches, or HFT-like infrastructure whe
- **nestjs-patterns** — NestJS architecture patterns for modules, controllers, providers, DTO validation, guards, interceptors, config, and production-grade TypeScript backends. Use wh
- **nodejs-keccak256** — Prevent Ethereum hashing bugs in JavaScript and TypeScript. Node's sha3-256 is NIST SHA3, not Ethereum Keccak-256, and silently breaks selectors, signatures, st
- **quarkus-patterns** — Quarkus 3.x LTS architecture patterns with Camel for messaging, RESTful API design, CDI services, data access with Panache, and async processing. Use for Java Q
- **quarkus-security** — Quarkus Security best practices for authentication, authorization, JWT/OIDC, RBAC, input validation, CSRF, secrets management, and dependency security. Use when
- **quarkus-tdd** — Test-driven development for Quarkus 3.x LTS using JUnit 5, Mockito, REST Assured, Camel testing, and JaCoCo. Use when adding features, fixing bugs, or refactori
- **quarkus-verification** — "Verification loop for Quarkus projects: build, static analysis, tests with coverage, security scans, native compilation, and diff review before release or PR."
- **springboot-patterns** — Spring Boot architecture patterns, REST API design, layered services, data access, caching, async processing, and logging. Use for Java Spring Boot backend work
- **springboot-security** — Spring Security best practices for authn/authz, validation, CSRF, secrets, headers, rate limiting, and dependency security in Java Spring Boot services. Use whe
- **springboot-tdd** — Test-driven development for Spring Boot using JUnit 5, Mockito, MockMvc, Testcontainers, and JaCoCo. Use when adding features, fixing bugs, or refactoring.
- **springboot-verification** — "Verification loop for Spring Boot projects: build, static analysis, tests with coverage, security scans, and diff review before release or PR."
- **tinystruct-patterns** — Expert guidance for developing with the tinystruct Java framework. Use when working on the tinystruct codebase or any project built on tinystruct — including 

## 09 Languages & Mobile

- **android-clean-architecture** — Clean Architecture patterns for Android and Kotlin Multiplatform projects — module structure, dependency rules, UseCases, Repositories, and data layer pattern
- **compose-multiplatform-patterns** — Compose Multiplatform and Jetpack Compose patterns for KMP projects — state management, navigation, theming, performance, and platform-specific UI. Use when b
- **cpp-coding-standards** — C++ coding standards based on the C++ Core Guidelines (isocpp.github.io). Use when writing, reviewing, or refactoring C++ code to enforce modern, safe, and idio
- **cpp-testing** — Use only when writing/updating/fixing C++ tests, configuring GoogleTest/CTest, diagnosing failing or flaky tests, or adding coverage/sanitizers.
- **csharp-testing** — C# and .NET testing patterns with xUnit, FluentAssertions, mocking, integration tests, and test organization best practices. Use when writing or reviewing xUnit
- **dart-flutter-patterns** — Production-ready Dart and Flutter patterns covering null safety, immutable state, async composition, widget architecture, popular state management frameworks (B
- **flutter-dart-code-review** — Library-agnostic Flutter/Dart code review checklist covering widget best practices, state management patterns (BLoC, Riverpod, Provider, GetX, MobX, Signals), D
- **fsharp-testing** — F# testing patterns with xUnit, FsUnit, Unquote, FsCheck property-based testing, integration tests, and test organization best practices. Use when writing F# te
- **generating-python-installer** — "Commercial-grade Python installer expert for Windows: Nuitka extreme compilation, dist slimming, DLL footprint analysis, and Inno Setup packaging to ship the s
- **golang-patterns** — Idiomatic Go patterns, best practices, and conventions for building robust, efficient, and maintainable Go applications. Use when writing or reviewing Go code a
- **golang-testing** — Go testing patterns including table-driven tests, subtests, benchmarks, fuzzing, and test coverage. Follows TDD methodology with idiomatic Go practices. Use whe
- **java-coding-standards** — "Java coding standards for Spring Boot and Quarkus services: naming, immutability, Optional usage, streams, exceptions, generics, CDI, reactive patterns, and pr
- **kotlin-coroutines-flows** — Kotlin Coroutines and Flow patterns for Android and KMP — structured concurrency, Flow operators, StateFlow, error handling, and testing. Use when writing cor
- **kotlin-exposed-patterns** — JetBrains Exposed ORM patterns including DSL queries, DAO pattern, transactions, HikariCP connection pooling, Flyway migrations, and repository pattern. Use whe
- **kotlin-ktor-patterns** — Ktor server patterns including routing DSL, plugins, authentication, Koin DI, kotlinx.serialization, WebSockets, and testApplication testing. Use when building 
- **kotlin-patterns** — Idiomatic Kotlin patterns, best practices, and conventions for building robust, efficient, and maintainable Kotlin applications with coroutines, null safety, an
- **kotlin-testing** — Kotlin testing patterns with Kotest, MockK, coroutine testing, property-based testing, and Kover coverage. Follows TDD methodology with idiomatic Kotlin practic
- **perl-patterns** — Modern Perl 5.36+ idioms, best practices, and conventions for building robust, maintainable Perl applications. Use when writing or reviewing modern Perl 5.36+ c
- **perl-security** — Comprehensive Perl security covering taint mode, input validation, safe process execution, DBI parameterized queries, web security (XSS/SQLi/CSRF), and perlcrit
- **perl-testing** — Perl testing patterns using Test2::V0, Test::More, prove runner, mocking, coverage with Devel::Cover, and TDD methodology. Use when writing Perl tests with Test
- **python-patterns** — Pythonic idioms, PEP 8 standards, type hints, and best practices for building robust, efficient, and maintainable Python applications. Use when writing or revie
- **python-testing** — Python testing strategies using pytest, TDD methodology, fixtures, mocking, parametrization, and coverage requirements. Use when writing pytest tests — fixtur
- **react-native-patterns** — React Native and Expo app patterns — Expo Router navigation, state separation (server/client/route/form), TanStack Query data fetching with Zod, performant li
- **rust-patterns** — Idiomatic Rust patterns, ownership, error handling, traits, concurrency, and best practices for building safe, performant applications. Use when writing or revi
- **rust-testing** — Rust testing patterns including unit tests, integration tests, async testing, property-based testing, mocking, and coverage. Follows TDD methodology. Use when w
- **swift-actor-persistence** — Thread-safe data persistence in Swift using actors — in-memory cache with file-backed storage, eliminating data races by design. Use when persisting data in S
- **swift-concurrency-6-2** — Swift 6.2 Approachable Concurrency — single-threaded by default, @concurrent for explicit background offloading, isolated conformances for main actor types. U
- **swift-protocol-di-testing** — Protocol-based dependency injection for testable Swift code — mock file system, network, and external APIs using focused protocols and Swift Testing. Use when
- **swiftui-patterns** — SwiftUI architecture patterns, state management with @Observable, view composition, navigation, performance optimization, and modern iOS/macOS UI best practices

## 10 Data & Databases

- **clickhouse-io** — ClickHouse database patterns, query optimization, analytics, and data engineering best practices for high-performance analytical workloads. Use when writing Cli
- **dashboard-builder** — Build monitoring dashboards that answer real operator questions for Grafana, SigNoz, and similar platforms. Use when turning metrics into a working dashboard in
- **database-migrations** — Database migration best practices for schema changes, data migrations, rollbacks, and zero-downtime deployments across PostgreSQL, MySQL, and common ORMs (Prism
- **data-scraper-agent** — Build a fully automated AI-powered data collection agent for any public source — job boards, prices, news, GitHub, sports, anything. Runs on a schedule, enric
- **mysql-patterns** — MySQL and MariaDB schema, query, indexing, transaction, replication, and connection-pool patterns for production backends. Use when designing MySQL or MariaDB s
- **postgres-patterns** — PostgreSQL database patterns for query optimization, schema design, indexing, and security. Based on Supabase best practices. Use when designing PostgreSQL sche
- **prisma-patterns** — Prisma ORM patterns for TypeScript backends — schema design, query optimization, transactions, pagination, and critical traps like updateMany returning count 
- **redis-patterns** — Redis data structure patterns, caching strategies, distributed locks, rate limiting, pub/sub, and connection management for production applications. Use when ad

## 11 AI & ML

- **foundation-models-on-device** — Apple FoundationModels framework for on-device LLM — text generation, guided generation with @Generable, tool calling, and snapshot streaming in iOS 26+. Use 
- **ml-adoption-playbook** — End-to-end methodology for AI agents and software engineers to add machine learning algorithms to existing non-ML codebases. Covers problem framing, data readin
- **mle-workflow** — Production machine-learning engineering workflow for data contracts, reproducible training, model evaluation, deployment, monitoring, and rollback. Use when bui
- **pytorch-patterns** — PyTorch deep learning patterns and best practices for building robust, efficient, and reproducible training pipelines, model architectures, and data loading. Us
- **recsys-pipeline-architect** — Design composable recommendation, ranking, and feed pipelines using the six-stage Source→Hydrator→Filter→Scorer→Selector→SideEffect framework populari

## 12 DevOps & Infra

- **cisco-ios-patterns** — Cisco IOS and IOS-XE review patterns for show commands, config hierarchy, wildcard masks, ACL placement, interface hygiene, and safe change-window verification.
- **deployment-patterns** — Deployment workflows, CI/CD pipeline patterns, Docker containerization, health checks, rollback strategies, and production readiness checklists for web applicat
- **dmux-workflows** — Multi-agent orchestration using dmux (tmux pane manager for AI agents). Patterns for parallel agent workflows across Claude Code, Codex, OpenCode, and other har
- **docker-patterns** — Docker and Docker Compose patterns for local development, hardened CLI installer harnesses, container security, networking, volumes, and multi-service orchestra
- **flox-environments** — "Create reproducible, cross-platform (macOS/Linux) development environments with Flox, a declarative Nix-based environment manager. Use when setting up project 
- **github-ops** — GitHub repository operations, automation, and management. Issue triage, PR management, CI/CD operations, release management, and security monitoring using the g
- **homelab-network-readiness** — Readiness checklist for homelab VLAN segmentation, local DNS filtering, and WireGuard-style remote access before changing router, firewall, DHCP, or VPN configu
- **homelab-network-setup** — Practical home and homelab network planning for gateways, switches, access points, IP ranges, DHCP reservations, DNS, cabling, and common beginner mistakes. Use
- **homelab-pihole-dns** — Pi-hole installation, blocklist management, DNS-over-HTTPS setup, DHCP integration, local DNS records, and troubleshooting broken DNS resolution on a home netwo
- **homelab-vlan-segmentation** — Segmenting home networks into VLANs for IoT, guest, trusted, and server traffic using UniFi, pfSense/OPNsense, and MikroTik — including switch trunk config, f
- **homelab-wireguard-vpn** — WireGuard VPN server setup, peer configuration, key generation, split tunneling vs full tunnel routing, and remote access to a home network from mobile and lapt
- **kubernetes-patterns** — Kubernetes workload patterns, resource management, RBAC, probes, autoscaling, ConfigMap/Secret handling, and kubectl debugging for production-grade deployments.
- **netmiko-ssh-automation** — Safe Python Netmiko patterns for read-only collection, bounded batch SSH, TextFSM parsing, guarded config changes, timeouts, and network automation error handli
- **network-bgp-diagnostics** — Diagnostics-only BGP troubleshooting patterns for neighbor state, route exchange, prefix policy, AS path inspection, and safe evidence collection. Use when a BG
- **network-config-validation** — Pre-deployment checks for router and switch configuration, including dangerous commands, duplicate addresses, subnet overlaps, stale references, management-plan
- **network-interface-health** — Diagnose interface errors, drops, CRCs, duplex mismatches, flapping, speed negotiation issues, and counter trends on routers, switches, and Linux hosts. Use whe
- **terminal-opener** — Open an executable and its argument array in a visible terminal window through a reusable, shell-free launch plan with dry-run, JSON, capability detection, deta
- **terminal-ops** — Evidence-first repo execution workflow for ECC. Use when the user wants a command run, a repo checked, a CI failure debugged, or a narrow fix pushed with exact 
- **uncloud** — Use when managing an Uncloud cluster — deploying services, configuring Caddy ingress, adding static proxy routes for non-cluster devices, publishing ports, sc

## 13 Media & Video

- **blender-motion-state-inspection** — Use this skill when inspecting Blender characters, rigs, poses, animation retargeting, ground contact, facing direction, or model-vs-motion alignment where scre
- **fal-ai-media** — Unified media generation via fal.ai MCP — image, video, and audio. Covers text-to-image (Nano Banana), text/image-to-video (Seedance, Kling, Veo 3), text-to-s
- **ios-icon-gen** — Generate iOS app icons as PNG imagesets for Xcode asset catalogs from SF Symbols (5000+ Apple-native) or Iconify API (275k+ open source icons from 200+ collecti
- **manim-video** — Build reusable Manim explainers for technical concepts, graphs, system diagrams, and product walkthroughs, then hand off to the wider ECC video stack if needed.
- **remotion-video-creation** — Best practices for Remotion - Video creation in React. 29 domain-specific rules covering 3D, animations, audio, captions, charts, transitions, and more. Use whe
- **tasteforge-video** — Use for file-driven multimodal image, video, and 3D-asset discovery; taste interviews; distill or apply workflows; style-pack validation; editable EDL/FCPXML ex
- **videodb** — See, Understand, Act on video and audio. See- ingest from local files, URLs, RTSP/live feeds, or live record desktop; return realtime context and playable strea
- **video-editing** — AI-assisted video editing workflows for cutting, structuring, and augmenting real footage. Covers the full pipeline from raw capture through FFmpeg, Remotion, E

## 14 Content & Marketing

- **article-writing** — Write articles, guides, blog posts, tutorials, newsletter issues, and other long-form content in a distinctive voice derived from supplied examples or brand gui
- **brand-discovery** — >-
- **brand-voice** — Build a source-derived writing style profile from real posts, essays, launch notes, docs, or site copy, then reuse that profile across content, outreach, and so
- **connections-optimizer** — Reorganize the user's X and LinkedIn network with review-first pruning, add/follow recommendations, and channel-specific warm outreach drafted in the user's rea
- **content-engine** — Create platform-native content systems for X, LinkedIn, TikTok, YouTube, newsletters, and repurposed multi-platform campaigns. Use when the user wants social po
- **crosspost** — Multi-platform content distribution across X, LinkedIn, Threads, and Bluesky. Adapts content per platform using content-engine patterns. Never posts identical c
- **growth-log** — "Use after a complex task, failure, or when reviewing what was learned. Teaches how to write growth logs that extract reusable patterns — not diary entries."
- **investor-materials** — Create and update pitch decks, one-pagers, investor memos, accelerator applications, financial models, and fundraising materials. Use when the user needs invest
- **investor-outreach** — Draft cold emails, warm intro blurbs, follow-ups, update emails, and investor communications for fundraising. Use when the user wants outreach to angels, VCs, s
- **marketing-campaign** — End-to-end marketing campaign planning and execution. Covers audience research, positioning, campaign angle definition, landing page copy, email sequences, soci
- **seo** — Audit, plan, and implement SEO improvements across technical SEO, on-page optimization, structured data, Core Web Vitals, and content strategy. Use when the use
- **social-graph-ranker** — Weighted social-graph ranking for warm intro discovery, bridge scoring, and network gap analysis across X and LinkedIn. Use when the user wants the reusable gra
- **social-publisher** — Agent-driven scheduling and publishing of social media posts across 13 platforms via SocialClaw. Use when the user wants to publish to X, LinkedIn, Instagram, F
- **x-api** — X/Twitter API integration for posting tweets, threads, reading timelines, search, and analytics. Covers OAuth auth patterns, rate limits, and platform-native co

## 15 Business & Domain

- **carrier-relationship-management** — >
- **customer-billing-ops** — Operate customer billing workflows such as subscriptions, refunds, churn triage, billing-portal recovery, and plan analysis using connected billing tools like S
- **customs-trade-compliance** — >
- **energy-procurement** — >
- **evm-token-decimals** — Prevent silent decimal mismatch bugs across EVM chains. Covers runtime decimal lookup, chain-aware caching, bridged-token precision drift, and safe normalizatio
- **finance-billing-ops** — Evidence-first revenue, pricing, refunds, team-billing, and billing-model truth workflow for ECC. Use when the user wants a sales snapshot, pricing comparison, 
- **healthcare-cdss-patterns** — Clinical Decision Support System (CDSS) development patterns. Drug interaction checking, dose validation, clinical scoring (NEWS2, qSOFA), alert severity classi
- **healthcare-emr-patterns** — EMR/EHR development patterns for healthcare applications. Clinical safety, encounter workflows, prescription generation, clinical decision support integration, 
- **healthcare-eval-harness** — Patient safety evaluation harness for healthcare application deployments. Automated test suites for CDSS accuracy, PHI exposure, clinical workflow integrity, an
- **healthcare-phi-compliance** — Protected Health Information (PHI) and Personally Identifiable Information (PII) compliance patterns for healthcare applications. Covers data classification, ac
- **hipaa-compliance** — HIPAA-specific entrypoint for healthcare privacy and security work. Use when a task is explicitly framed around HIPAA, PHI handling, covered entities, BAAs, bre
- **inventory-demand-planning** — >
- **ito-baskets** — Read-only Itô basket and prediction-market data skill. Index the live basket catalog, compare a basket against user-supplied research or a watchlist, build a s
- **ito-compute** — Query live GPU inventory, submit an authenticated Itô fixed-rate RFQ, inspect RFQ or procurement status, revoke device credentials, and run explicitly gated no
- **ito-inference** — Inspect the availability of model serving on a completed Itô compute booking and, when the canonical backend becomes available, hand off an explicitly confirme
- **ito-training** — Inspect the availability of ML training on a completed Itô compute booking and, when the canonical backend becomes available, hand off an explicitly confirmed 
- **logistics-exception-management** — >
- **prediction-market-oracle-research** — Research prediction markets as data sources or oracle signals for products, agents, dashboards, and corporate decision intelligence. Use for source-grounded ana
- **prediction-market-risk-review** — Review prediction-market, basket, oracle, and trading-agent workflows for compliance, safety, data-quality, privacy, and execution risk. Use before any workflow
- **product-capability** — Translate PRD intent, roadmap asks, or product discussions into an implementation-ready capability plan that exposes constraints, invariants, interfaces, and un
- **production-scheduling** — >
- **product-lens** — Use this skill to validate the "why" before building, run product diagnostics, and pressure-test product direction before the request becomes an implementation 
- **quality-nonconformance** — >
- **returns-reverse-logistics** — >
- **visa-doc-translate** — Translate visa application documents (images) to English and create a bilingual PDF with original and translation. Use when visa application document images mus

## 16 Productivity & Integrations

- **email-ops** — Evidence-first mailbox triage, drafting, send verification, and sent-mail-safe follow-up workflow for ECC. Use when the user wants to organize email, draft or s
- **google-workspace-ops** — Operate across Google Drive, Docs, Sheets, and Slides as one workflow surface for plans, trackers, decks, and shared documents. Use when the user needs to find,
- **jira-integration** — Use this skill when retrieving Jira tickets, analyzing requirements, updating ticket status, adding comments, or transitioning issues. Provides Jira API pattern
- **mailtrap-email-integration** — Guides agents through integrating transactional email sending via Mailtrap's Email API, including sandbox testing, domain verification, and API authentication. 
- **messages-ops** — Evidence-first live messaging workflow for ECC. Use when the user wants to read texts or DMs, recover a recent one-time code, inspect a thread before replying, 
- **nutrient-document-processing** — Process, convert, OCR, extract, redact, sign, and fill documents using the Nutrient DWS API. Works with PDFs, DOCX, XLSX, PPTX, HTML, and images. Use when conve
- **project-flow-ops** — Operate execution flow across GitHub and Linear by triaging issues and pull requests, linking active work, and keeping GitHub public-facing while Linear remains
- **unified-notifications-ops** — Operate notifications as one ECC-native workflow across GitHub, Linear, desktop alerts, hooks, and connected communication surfaces. Use when the real problem i

## 17 ECC Meta

- **ck** — Persistent per-project memory for Claude Code. Auto-loads project context on session start, tracks sessions with git activity, and writes to native memory. Comm
- **configure-ecc** — Guide ECC installation, update, or reconfiguration from inside Claude Code, Codex, or Kimi while respecting each harness's real plugin, scope, and hook capabili
- **ecc-guide** — Guide users through ECC's current agents, skills, commands, hooks, rules, install profiles, and project onboarding by reading the live repository surface before
- **ecc-recipes** — "Map a described workflow to the right ECC command-GROUP with run-order and stop condition, and browse all command-group recipe families. Adds a family-grouping
- **ecc-tools-cost-audit** — Evidence-first ECC Tools burn and billing audit workflow. Use when investigating runaway PR creation, quota bypass, premium-model leakage, duplicate jobs, or Gi
- **hermes-imports** — Convert local Hermes operator workflows into sanitized ECC skills and release-pack artifacts. Use when preparing a Hermes workflow for public ECC reuse without 
- **nanoclaw-repl** — Operate and extend NanoClaw v2, ECC's zero-dependency session-aware REPL built on claude -p. Use when operating or extending the NanoClaw REPL.
- **nasiko-control-plane** — Install, detect, and operate the optional Nasiko agent control plane through ECC with pinned artifacts, explicit consent, and telemetry and secrets boundaries.
- **openclaw-persona-forge** — "为 OpenClaw AI Agent 锻造完整的龙虾灵魂方案。根据用户偏好或随机抽卡， 输出身份定位、灵魂描述(SOUL.md)、角色化底线规�

