# John Carmack

AI/LLM and geospatial/GPU software engineer. Rust and TypeScript, from production LLM systems to GPU map rendering to the cloud infrastructure that runs them. Recently primary author of a safety-critical aviation flight-planning desktop app and lone architect of a real-time analytics platform. Remote, based in Waco, TX.

## What I build

- **Production AI/LLM applications** - schema-validated data extraction, LLM gateways, structured output, and the evaluation harnesses that keep them honest.
- **High-performance maps and GPU/geospatial** - deck.gl, luma.gl, MapLibre, WebGL, vector tiles and PMTiles.
- **Aviation software** - safety-critical flight-planning and dispatch desktop apps.
- **Rust systems and cloud** - Axum/Tokio services, type-safe Rust to TypeScript, serverless on AWS (Lambda, CDK), infrastructure-as-code.

## Featured work

**AI / LLM**
- [llm-extract-evals](https://github.com/johncarmack1984/llm-extract-evals) - schema-validated LLM data extraction with a confidence-gated evaluation harness: accuracy scoring and offline replay.
- [promptward](https://github.com/johncarmack1984/promptward) - an LLM gateway that detects prompt injection and data exfiltration, validates structured output, and meters cost, with an eval harness that proves the detection rate.

**Geospatial / GPU**
- [stormdeck](https://github.com/johncarmack1984/stormdeck) - live weather on a deck.gl map, vector tiles served from AWS Lambda on the free tier.
- [deck-wind-layer](https://github.com/johncarmack1984/deck-wind-layer) - a custom deck.gl v9 layer: GPU-advected wind particles over a moving map.
- [glslint](https://github.com/johncarmack1984/glslint) - a GLSL checker and language server that understands deck.gl/luma.gl shader modules (Rust).

**Rust / systems**
- [typed-geojson](https://github.com/johncarmack1984/typed-geojson) - strongly-typed GeoJSON for Rust (`Feature<G, P>` / `FeatureCollection`), specta-compatible.
- [specta](https://github.com/johncarmack1984/specta) - contributor to specta-rs, exporting Rust types to TypeScript.
- [accept-payments](https://github.com/johncarmack1984/accept-payments) - a payments and invoicing API in Rust/Axum on the AWS Lambda Rust runtime.

## Stack

Rust, TypeScript, React, Next.js, Node, Tauri, Python | deck.gl, luma.gl, MapLibre, WebGL, D3 | Axum, Tokio, Snowflake, PostgreSQL | AWS (Lambda, CDK), Terraform, GitHub Actions | LLM/AI: extraction, evaluation, structured output

## Reach me

[johncarmack.com](https://johncarmack.com) | [linkedin.com/in/johncarmack1984](https://linkedin.com/in/johncarmack1984)
