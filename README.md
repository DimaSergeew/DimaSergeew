## Hi, I'm Nikita

Founder and tech admin of **[PinkyFoxy](https://pinkyfoxy.com)** — an anarchy Minecraft SMP running CanvasMC (Folia fork).

### What I do

- Run the PinkyFoxy stack: CanvasMC 26.1.2, MariaDB, Pelican panel, Cloudflare-fronted infra
- Write small Paper/Folia plugins for in-house needs
- Contribute fixes and bug reports to the plugin ecosystem I depend on

### Active plugins

| Plugin | Description |
|---|---|
| **[AuthSecurity](https://github.com/DimaSergeew/AuthSecurity)** | Paper/Folia auth plugin — holds the player in the configuration phase until login. Argon2id, H2/MariaDB via HikariCP, IP rate-limit, Brigadier commands. |
| **[ItemDonate](https://github.com/DimaSergeew/ItemDonate)** | Donate-as-items system for Paper/Folia with anti-dupe protection (LuckPerms + PlayerPoints). |

### Recent upstream contributions

- [RayTraceAntiXray PR #8](https://github.com/TauCu/RayTraceAntiXray/pull/8) — concurrency & error-handling fixes
- [CMI #10251](https://github.com/Zrips/CMI/issues/10251) · [#10252](https://github.com/Zrips/CMI/issues/10252) — Folia thread violations (fixed in next CMI)
- [Canvas #222](https://github.com/CraftCanvasMC/Canvas/issues/222) — PluginClassLoader lifecycle bug on plugin self-disable
- [Grim #2662](https://github.com/GrimAnticheat/Grim/issues/2662) — NPE in `BukkitPlatformPlayer` on reconnect
- [AxAuctions repro #1040](https://github.com/Artillex-Studios/Issues/issues/1040) — Folia thread violation in auction creation

### Stack

`Java · Paper API · Folia · CanvasMC · MariaDB · HikariCP · Brigadier · Pelican · Cloudflare`

---

🦊 **[pinkyfoxy.com](https://pinkyfoxy.com)**
