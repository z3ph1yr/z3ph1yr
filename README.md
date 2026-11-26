# Hi there

I build software end to end, from data pipelines and APIs to the interface people use.
I also teach Data Structures & Algorithms and OOP at university.

Most of my work is client or commercial and lives in private repos. Happy to walk
through any of it on a call.

## Selected work

### [LexIndia AI](https://github.com/z3ph1yr/lexindia-ai): grounded legal research over Indian penal law
A search-and-answer engine over 933 provisions of IPC 1860 and BNS 2023, each traceable to its source.
- Hybrid retrieval (exact citation, BM25, legal-concept expansion, TF-IDF, optional embeddings) merged with reciprocal-rank fusion
- Built against hallucination: every citation is checked against retrieved text, and anything unverified is removed; weak queries are refused rather than guessed
- Runs with zero config and zero API cost in deterministic mode; LLM answers are opt-in
- 47 tests, including a retrieval-quality evaluation

`Node.js` `SQLite/FTS5` `React` `Vite`

### Lab test-report generator (freelance)
For an electrical testing laboratory: manual entry → validated data → draft and final PDF reports.
- One shared core (domain model, validation, PDF engine) runs both an offline Windows desktop app and a multi-user web app
- Web version has sign-in with per-user drafts and shared org defaults; desktop stays fully offline

`TypeScript` `Electron` `Supabase`

### Interactive DSA learning platform
Algorithms run as instrumented reference code and replay step by step with narration and synced pseudocode.
- Monorepo with a deterministic trace-replay engine, visualization core, React player, and a content validator that checks prerequisite graphs

`TypeScript` `Astro` `React`

### 2v2 Runner/Gunner game (in development)
A Hyrox-Doubles-style team game where one player runs and the other shoots.

`C#` `Unity 6` `URP`

<!-- gameplay GIF here -->

## Currently designing
A lab management + ERP system: enquiry → quotation → work order → testing → approval → report → GST invoice → payment.

`Next.js` `FastAPI` `PostgreSQL`
