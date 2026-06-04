# MemAtom — Developer Deck

A single-file, zero-dependency HTML pitch/dev deck for **MemAtom**, a drop-in
memory SDK for AI agents — per-message memory atoms, local embeddings (no API
key), and GraphRAG retrieval.

### ▶ View it live
**https://rajuroopani.github.io/mematom-deck/**

### Run locally
Just open `index.html` in any browser — no build, no dependencies.

```bash
open index.html        # macOS
# or: python3 -m http.server  → http://localhost:8000
```

### Navigation
- **→ / ↓ / Space** — next slide · **← / ↑** — previous
- **scroll** or **swipe** on touch · **click the dots** to jump

### Customize
Theme values live in the `:root` CSS block at the top of `index.html`
(`--accent`, `--bg`, fonts). Each slide is a `<section class="slide">`.

---

Built with the `frontend-slides` approach (zero-dependency, viewport-fit,
animation-rich). Style: *Bold Signal* — charcoal + hot-orange, Archivo Black.
