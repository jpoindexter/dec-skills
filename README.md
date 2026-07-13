# dec-skills

**Design Engineering Canon — 21 agent skills.**

Named design & engineering principles — Nielsen, Norman, Rams, Krug, Gestalt, UX laws, cognitive load, web performance — packaged as agent skills so the agent reasons from principles instead of eyeballing it.

Works with any agent that reads markdown skills: Claude Code, Codex CLI, Gemini CLI, Copilot, Cursor.

## Install

```bash
npx skills add jpoindexter/dec-skills
```

Or manually: clone and symlink the folders under `skills/` into your agent's skills directory (e.g. `~/.claude/skills/`).

## The Skills

| Skill | Covers |
|---|---|
| [`dec`](skills/dec/SKILL.md) | Use when the user invokes /dec, says 'run design engineering skills', or starts any design-engineering task — building/reviewing UI, scoping a product, shipp… |
| [`dec-accessibility`](skills/dec-accessibility/SKILL.md) | Accessibility foundations for design engineers — WCAG / POUR, semantic-HTML-first then ARIA, keyboard and focus management, inclusive design for permanent/te… |
| [`dec-ai-native-patterns`](skills/dec-ai-native-patterns/SKILL.md) | AI-native design engineering patterns — generative/adaptive UI, streaming as interaction, prompt-as-interface, human-in-the-loop / agentic UX, eval-driven de… |
| [`dec-cognitive-load`](skills/dec-cognitive-load/SKILL.md) | Cognitive Load Theory for interfaces — intrinsic (task difficulty), extraneous (poor-design overhead), and germane (useful mental-model building) load. Use w… |
| [`dec-core-principles`](skills/dec-core-principles/SKILL.md) | Foundational design-engineering principles that govern where complexity lives and how interfaces stay fast and consistent — Tesler's Law, progressive disclos… |
| [`dec-css-architecture`](skills/dec-css-architecture/SKILL.md) | CSS and styling architecture — scaling methodologies (BEM, ITCSS, CUBE CSS) and fluid/responsive technique (mobile-first, clamp() fluid type/space, container… |
| [`dec-design-system-depth`](skills/dec-design-system-depth/SKILL.md) | Design system depth beyond "tokens are data" — three-tier token architecture (primitive → semantic → component), W3C DTCG format and tooling, scales as syste… |
| [`dec-discovery-validation`](skills/dec-discovery-validation/SKILL.md) | Product discovery and validation frameworks — Jobs To Be Done, Continuous Discovery / Opportunity Solution Tree, Lean UX / Build-Measure-Learn, Design Sprint… |
| [`dec-gestalt-principles`](skills/dec-gestalt-principles/SKILL.md) | Gestalt principles of grouping — proximity, similarity, common region, continuity, closure, figure/ground, common fate, prägnanz, uniform connectedness. The … |
| [`dec-krug-laws`](skills/dec-krug-laws/SKILL.md) | Steve Krug's "Don't Make Me Think" laws — self-evidence as the goal, mindless clicks over fewer clicks, and ruthless word-cutting. Use when reviewing copy de… |
| [`dec-motion-animation`](skills/dec-motion-animation/SKILL.md) | Interface motion and animation — the 12 principles of animation applied to UI, easing and spring physics (ease-out entrances / ease-in exits), the FLIP techn… |
| [`dec-nielsen-heuristics`](skills/dec-nielsen-heuristics/SKILL.md) | Jakob Nielsen's 10 usability heuristics — the bedrock checklist for evaluating any interface. Use when running a heuristic evaluation, reviewing a screen for… |
| [`dec-norman-principles`](skills/dec-norman-principles/SKILL.md) | Don Norman's principles of interaction design — affordances & signifiers, mapping, feedback, constraints, conceptual model, and the gulfs of execution and ev… |
| [`dec-prioritization-frameworks`](skills/dec-prioritization-frameworks/SKILL.md) | Prioritization frameworks — RICE, Kano model, MoSCoW, Value vs Effort 2×2. Use when ranking a backlog, deciding what ships in v0 vs later, defending a sequen… |
| [`dec-product-metrics`](skills/dec-product-metrics/SKILL.md) | Product metrics and outcome frameworks — North Star Framework, Google HEART, AARRR (Pirate Metrics), OKRs. Use when defining what success means, choosing whi… |
| [`dec-quality-testing`](skills/dec-quality-testing/SKILL.md) | Frontend quality and testing strategy — visual regression testing (snapshot diffing) and the Testing Trophy (favor integration tests over the classic pyramid… |
| [`dec-rams-principles`](skills/dec-rams-principles/SKILL.md) | Dieter Rams' 10 principles of good design — the taste-and-restraint rubric (innovative, useful, aesthetic, understandable, unobtrusive, honest, long-lasting,… |
| [`dec-rendering-architecture`](skills/dec-rendering-architecture/SKILL.md) | Frontend rendering and state architecture — CSR/SSR/SSG/ISR/streaming SSR/RSC chosen per route, state colocation and derived state, server-state vs client-st… |
| [`dec-software-principles`](skills/dec-software-principles/SKILL.md) | Core software engineering principles for the engineering half of design engineering — SOLID, DRY/KISS/YAGNI, Conway's Law, Principle of Least Astonishment. U… |
| [`dec-ux-laws`](skills/dec-ux-laws/SKILL.md) | The Laws of UX and cognitive heuristics beyond the common five — Doherty Threshold, Goal-Gradient, Zeigarnik, Peak-End, Serial Position, Von Restorff, Postel… |
| [`dec-web-performance`](skills/dec-web-performance/SKILL.md) | Web performance as a UX constraint — Core Web Vitals (LCP, INP, CLS) and the RAIL model with perception-keyed budgets. Use when setting performance budgets, … |

## License

MIT — see [LICENSE](LICENSE).
