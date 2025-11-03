# Contributing to TesseraCore

Thanks for your interest! Contributions are welcome across specs, code, tests, docs, and examples.

## How to contribute
1. **Discuss first**: open an issue (type = proposal/bug) or join an existing thread.
2. **Fork & branch**: `feat/<scope>`, `fix/<scope>`, `docs/<scope>`.
3. **Design / spec** (if API-facing): add a short RFC in `docs/rfcs/`.
4. **Code style**: TypeScript, ESM; keep functions pure; tests first for tricky math.
5. **Tests**: include unit tests and, for rendering, golden images + tolerances.
6. **Commits**: Conventional Commits (`feat:`, `fix:`, `chore:`…).
7. **PR**: link issues, fill the checklist, keep PRs focused.

## Development quick-start
- Node 20+, pnpm
- `pnpm i && pnpm -w build && pnpm -w test`
- For golden tests: `pnpm -w test:visual`

## Areas
- **Rendering** (WebGPU/WebGL/Canvas)
- **Color** (ICC/LUTs, linear pipeline)
- **Annotations** (geometry, tools, hit-test)
- **Plugins** (LUTs, overlays, shader passes)
- **Calibration** (spatial, grayscale, ΔE)
- **Docs & Examples**

## Code of Conduct
By participating you agree to our [Code of Conduct](./CODE_OF_CONDUCT.md).

## License
Unless noted otherwise, contributions are licensed under the project’s main license.
