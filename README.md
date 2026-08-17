<h1 align="center">Hi, I'm Hirad</h1>
<h3 align="center">CS & AI student building secure, production-shaped web apps</h3>

I'm studying Computer Science & Engineering at OSU, specializing in AI, while building things on the side — most of what's below comes from that side work, but school is the foundation underneath it. I build secure, production-shaped web apps — the kind with actual payments and actual auth, not demos — and care more about a system holding up under abuse than how many frameworks it name-drops.

Most recently I built **[nanomoz.com](https://nanomoz.com)**, an AI image-generation platform, end to end: a Next.js/React frontend and a FastAPI/Python backend, split across a VPS and Cloudflare, with OAuth + OTP sign-in, payment processing, cloud storage, and a Postgres database. Security wasn't an afterthought — the repo carries its own abuse-case checklist and a recurring scan pipeline alongside the usual CI.

**Recent open-source work**

- **[pg-rate-limiter](https://github.com/hirad121/pg-rate-limiter)** — a Postgres-backed, atomic, batched API rate limiter for FastAPI/SQLAlchemy apps. No Redis required; concurrency-proven against real Postgres, not just mocked.
- **[cloudflare-gauth-proxy](https://github.com/hirad121/cloudflare-gauth-proxy)** — an edge-cached proxy for Google's OIDC discovery document and signing keys, deployed as a Cloudflare Worker, with a stale-KV fallback for when Google itself is briefly down.

**Working with coding agents**

As coding agents get better at *building*, the bottleneck stops being "can we bring this idea to life" and becomes "can we keep what we've built secure, scalable, and maintainable." The hard part shifts from writing code to holding a system to a standard — **strong system design**, rigorous testing, and real verification, not just claimed. That shift raises the bar on documentation: clear, well-organized notes on what was done, why, and what went wrong are what let an agent (or a person) pick up a project cold and actually understand it — and increasingly that includes **visual context**, not just prose: architecture diagrams, sequence flows, and system maps that **let an agent see how a project fits together at a glance**, not just read about it.

---

<p align="center"><b>Stack</b></p>

<p align="center">
  <img src="https://skillicons.dev/icons?i=ts,nextjs,react,py,fastapi,postgres,docker,cloudflare,elixir,cs,dotnet" alt="Skills" />
</p>

<p align="center"><i>Don't forget to be kind to your agents :)</i></p>
