# John Carmack

AI/LLM and geospatial/GPU software engineer. Rust and TypeScript. I build production LLM systems, GPU map rendering, and the cloud infrastructure that runs them. Remote, based in Waco, TX.

Not the Doom guy. Different guy.

**Currently:** a lot of [Martin](https://github.com/maplibre/martin) (mostly the 2.0 release) and custom projections in [MapLibre GL JS](https://github.com/maplibre/maplibre-gl-js).

## Open source

MapLibre [voting member](https://github.com/maplibre/maplibre/pull/541) since August 2026. Counts below are merged PRs and link to the receipts.

- [maplibre/martin](https://github.com/maplibre/martin/pulls?q=is%3Apr+author%3Ajohncarmack1984+is%3Amerged) - 120 since July 2026: tile caching, PMTiles on S3 and Lambda, tile grids beyond Web Mercator, a Rust harness for the e2e tests, and the 2.0 cleanup and migration guide.
- [maplibre/maplibre-gl-js](https://github.com/maplibre/maplibre-gl-js/pulls?q=is%3Apr+author%3Ajohncarmack1984+is%3Amerged) - 40: rebuilt the benchmark suite on Vitest bench, then render-path work (integer vertex attributes, terrain elevation sampling, a CPU raycast replacing framebuffer picking) and custom projections for non-Mercator tile grids.
- [maplibre/maplibre-agent-skills](https://github.com/maplibre/maplibre-agent-skills/pulls?q=is%3Apr+author%3Ajohncarmack1984+is%3Amerged) - 19: eval-gated releases and an upstream release watch.
- [biomejs/biome](https://github.com/biomejs/biome/pulls?q=is%3Apr+author%3Ajohncarmack1984+is%3Amerged) - 16: Tailwind v4 class sorting in `useSortedClasses` (variants, container queries, the `!` suffix).
- [specta-rs/specta](https://github.com/specta-rs/specta/pulls?q=is%3Apr+author%3Ajohncarmack1984+is%3Amerged) - 14 toward 2.0-stable: enum rendering fixes, zod 4 output, the OpenAPI exporter, a bigint remapper.
- [maplibre/maplibre-tile-spec](https://github.com/maplibre/maplibre-tile-spec/pulls?q=is%3Apr+author%3Ajohncarmack1984+is%3Amerged) - 11: the `mlt` terminal UI (background scanning, a decoded-tile cache, layer summaries, tessellation drawing).

## Featured work

**AI / LLM**
- [promptward](https://github.com/johncarmack1984/promptward) - an LLM gateway that catches prompt injection and data exfiltration, validates structured output, and meters cost. Wire-compatible with the OpenAI and Anthropic SDKs. The eval harness proves the detection rate. [Live](https://promptward.johncarmack.com).
- [llm-extract-evals](https://github.com/johncarmack1984/llm-extract-evals) - schema-validated LLM data extraction with a confidence-gated evaluation harness: per-field accuracy, failure taxonomy, deterministic offline replay.
- [sidework](https://github.com/johncarmack1984/sidework) - a Claude Code skill that runs each task in a git worktree beside the checkout, because one nested inside it can pick up the checkout's Cargo config, just recipes, and node_modules. Evals included.

**Geospatial / GPU**
- [geo-desktop-bench](https://github.com/johncarmack1984/geo-desktop-bench) - benchmarks for the fastest geospatial desktop stack: deck.gl and MapLibre on WebGL2, Tauri vs Electron, DuckDB and PMTiles. [Report and demos](https://geobench.johncarmack.com).
- [deck-wind-layer](https://johncarmack1984.github.io/deck-wind-layer/) - a deck.gl v9 wind-particle layer: GPU advection, comet trails, constant on-screen density at any zoom.
- [glslint](https://github.com/johncarmack1984/glslint) - a GLSL checker and language server that understands deck.gl/luma.gl shader modules (Rust).

**Rust / systems**
- [tauri-plugin-tracing](https://github.com/fltsci/tauri-plugin-tracing) - logging for Tauri through the `tracing` crate. 32k downloads on crates.io.
- [tauri-typed-ipc](https://github.com/johncarmack1984/tauri-typed-ipc) - trait-based, type-safe Tauri IPC built on specta. Sync by default, async opt-in.
- [typed-geojson](https://github.com/johncarmack1984/typed-geojson) - strongly-typed GeoJSON for Rust (`Feature<G, P>` / `FeatureCollection`), specta-compatible.
- [accept-payments](https://github.com/johncarmack1984/accept-payments) - a payments and invoicing API in Rust/Axum on the AWS Lambda Rust runtime.

**Frontend**
- [tradecn/ui](https://github.com/tradecn/ui) - trading-terminal components for shadcn/ui: grids that take a feed, prices in 32nds, scoped hotkeys, order tickets. `shadcn add` copies the source into your repo. [Docs and demos](https://tradecn.dev).

**Benchmarks**
- [warefeats](https://warefeats.com) - benchmarks for developer tools with the runs attached: Redis vs Valkey vs Dragonfly, Martin vs Tegola vs BBOX, MapLibre vs Mapbox, Tauri vs Electron, ESLint vs Biome, Varnish vs NGINX. Every result names the rig, pins the versions, and publishes every pass.

**Shipped** (all since July 2026)
- [lux](https://github.com/johncarmack1984/lux) - DMX stage lighting, on the App Store for iOS and macOS. Rust, Tauri, and an Enttec or sACN/Art-Net node, auto-detected.
- [vegify.app](https://vegify.app) - plant-based nutrition tracking, on the App Store.
- [Message to PDF](https://message-to-pdf.com) - exports an iMessage or SMS conversation to a PDF that looks like Messages, all on your Mac. GPL-3.0 [on GitHub](https://github.com/NewEarthTech/message-to-pdf), with a signed build for sale.

Before this: primary author of a safety-critical aviation flight-planning desktop app, lone architect of a real-time analytics platform.

## Stack

Rust, TypeScript, React, Tauri, Node, Python | deck.gl, luma.gl, MapLibre, WebGL, PMTiles | Axum, Tokio, PostgreSQL | AWS (Lambda, CDK), Terraform, GitHub Actions | LLM production: extraction, evaluation, structured output, injection defense

## Reach me

[johncarmack.com](https://johncarmack.com) | [linkedin.com/in/johncarmack1984](https://linkedin.com/in/johncarmack1984)
