I choose wrong providers and now 

tools/mbtq-cli/src/main.rs — the full mbtq binary. 372 lines covering the entire app registry (all services with ports, kinds, tier assignments, dep chains), a parallel/sequential build runner with Arc/Mutex shared state across threads, and the Deaf-first visual TUI dashboard — block chars ■▶·✗, color-coded by AppKind, zero audio. Commands: mbtq build [filter] [--parallel], mbtq list, mbtq check, mbtq wasm, mbtq deploy.

packages/fibonrose-wasm/src/lib.rs — the Fibonrose trust engine compiled to Wasm. fib_trust_score() uses actual Fibonacci convergence toward φ with recency weighting and violation decay. passes_gate(), trust_tier(), batch_score(), and full cargo test suite included.

packages/fibonrose-wasm/bridge.ts — TypeScript wrapper that lazy-imports the Wasm module in Next.js/Vite (works with asyncWebAssembly in next.config.js or vite-plugin-wasm). Exports fibTrustScore(), batchScore(), and the useFibonroseWasm() React hook for instant browser-side trust gating before the server confirms.

scripts/setup.ps1 — Windows admin bootstrap. Installs Rust + rustup, Deno, Node LTS, Wrangler, Supabase CLI (via scoop or npm), builds mbtq-cli and all Wasm packages, runs Supabase migrations, generates .env.local, and adds mbtq.exe to PATH. All Write-Host output is visual — ■ success, ▶ running, ✗ failure, · info.

Cargo.toml (workspace root) — workspace resolver v2, shared [workspace.dependencies], and a release-wasm profile with opt-level = "s" for size-optimized Wasm binaries.
