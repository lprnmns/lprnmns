## Alperen Manas

Final-year Computer Engineering student in Türkiye, working on backend and AI systems.

I find bugs in widely used open-source software by checking it against a reference (the spec, the official test suite, or another implementation), then fix each one with a test that proves it.

[Portfolio](https://alperenmanas.app) · [LinkedIn](https://linkedin.com/in/alperen-manas) · [Email](mailto:manasalperen@gmail.com)

&nbsp;

| Highlights | |
|---|---|
| **150 merged PRs** in 56 open-source projects | including [Vite](https://github.com/vitejs/vite/pull/23780), [Microsoft Semantic Kernel](https://github.com/microsoft/semantic-kernel/pull/14375), [Node.js undici](https://github.com/nodejs/undici/pull/6031), [Material UI](https://github.com/mui/material-ui/pull/49090), [three.js](https://github.com/mrdoob/three.js/pull/34459) |
| **1st place** | Monad Blitz blockchain hackathon, 2025 |
| **Finalist + Best System Design Award** | TEKNOFEST 2026, Air Defense Systems |
| **2 live products** | [Zenith Trader](https://zenithtrader.alperenmanas.app) (100+ users) · [Klinik Akış AI](https://klinikakis.com) |

&nbsp;

### Where I go deep

**[meriyah](https://github.com/meriyah/meriyah)**: JavaScript parser, ~40M npm downloads a month. **23 merged PRs.**
I ran it against test262 (the official ECMAScript test suite) and other parsers, then fixed the places where it accepted invalid code or rejected valid code.
Examples: [`for await` in class static blocks](https://github.com/meriyah/meriyah/pull/680) · [`let` as an arrow parameter in strict mode](https://github.com/meriyah/meriyah/pull/671) · [`await` in a non-async arrow body](https://github.com/meriyah/meriyah/pull/673)

**[minijinja](https://github.com/mitsuhiko/minijinja)**: template engine by the creator of Flask and Jinja2. **15 merged PRs.**
I made the Go port behave exactly like the Rust reference: filters, comparisons, slicing, strict-undefined handling.
Examples: [negative-step slicing panic](https://github.com/mitsuhiko/minijinja/pull/1002) · [`tojson` float output](https://github.com/mitsuhiko/minijinja/pull/983) · [`trim` and Unicode whitespace](https://github.com/mitsuhiko/minijinja/pull/989)

&nbsp;

### A few other fixes

| Project | ★ | Fix |
|---|---|---|
| [Vite](https://github.com/vitejs/vite/pull/23780) | 84k | Watch files referenced with `new URL(…, import.meta.url)` when they have a query or hash |
| [marked](https://github.com/markedjs/marked/pull/4159) | 37k | End a list item before a lazy line after an HTML block |
| [Semantic Kernel](https://github.com/microsoft/semantic-kernel/pull/14375) | 29k | Python: handle empty chat message function results instead of crashing |
| [KaTeX](https://github.com/KaTeX/KaTeX/pull/4277) | 20k | Keep equation tags on empty final rows in arrays |
| [Compiler Explorer](https://github.com/compiler-explorer/compiler-explorer/pull/9105) | 19k | Disable color decorators in assembly output |
| [Node.js undici](https://github.com/nodejs/undici/pull/6031) | 7.7k | MockAgent: ignore the trailing slash before a query string |

[All merged PRs →](https://github.com/pulls?q=is%3Apr+author%3Alprnmns+is%3Amerged+-user%3Alprnmns)

&nbsp;

### Things I've built

| Project | What it does |
|---|---|
| **[Zenith Trader](https://zenithtrader.alperenmanas.app)** · [code](https://github.com/lprnmns/zenith-trader) | Live copy-trading platform. Watches large OKX wallets and mirrors their trades on users' accounts. 100+ users. |
| **[Klinik Akış AI](https://klinikakis.com)** | WhatsApp assistant for clinics. Reads appointment requests, checks live availability, books after confirmation, and hands unclear messages to staff. |
| **[Target Tracking & Engagement System](https://github.com/lprnmns/target-tracking-engagement-system)** | TEKNOFEST 2026 air-defense turret. YOLO tracking, friend/foe identification, PID fire control, Pico 2 firmware, 3D digital twin. 11/12 hits in the final. |
| **[Document Intelligence](https://github.com/lprnmns/document-intelligence)** | Local-first RAG service with hybrid search, cited answers and a reproducible evaluation set (Recall@5 0.92). |

&nbsp;

**Stack:** TypeScript · Python · Go · Rust · C# · Node.js · FastAPI · Next.js · Docker

**Now:** Kırıkkale University, Computer Engineering (2023–2027). Looking for a long-term internship starting **8 February 2027** (14 weeks, full-time). Open to relocating.
