# Kriti Behl

**Backend · Systems · Reliability Engineering**  
MS CS, University of Florida (Dec 2025) · GPA 3.8 · Open to full-time roles

---

## Systems Index

| System | Domain | What it proves |
|---|---|---|
| [Faultline](https://github.com/kritibehl/faultline) | Distributed systems · Execution correctness | 1,500 deterministic race runs · 0 duplicate commits · exactly-once semantics under fault injection |
| [AutoOps-Insight](https://github.com/kritibehl/autoops-insight) | Reliability analytics · Release safety | Config-driven YAML rules · incident replay · admin audit log · 11 failure families · 16 tests |
| [KubePulse](https://github.com/kritibehl/KubePulse) | Resilience validation | Controlled disruption + automated scorecards · 8s recovery · resilience score 86/100 |
| [ResuMate](https://github.com/kritibehl/ResuMate) | Workflow engine · Full-stack | Async job lifecycle (queued→running→retrying→failed→completed) · 8 workflow capabilities · 12 API endpoints · React/Next.js dashboard · 12 tests · GitHub Actions CI |
| [FairEval Suite](https://github.com/kritibehl/FairEval-Suite) | ML evaluation infrastructure | DistilBERT inference · RAG + classification scorers · /evaluate /compare /gate FastAPI · runs/→reports/→compare/→gate/ artifacts · 11 tests |
| [DetTrace](https://github.com/kritibehl/dettrace) | Deterministic debugging | C++17 + Swift replay · first divergence at event index 5 · 4 artifacts/run |
| [Chrome Copilot](https://github.com/kritibehl/chrome-copilot) | Developer tooling · Debugging | Signature clustering · local fallback · 8 steps → 3 · 1,000 benchmarked runs |
| [AccelSim-Lite](https://github.com/kritibehl/accelsim-lite) | Systems modeling · Performance | 7-stage pipeline simulator · 5 stall categories · bottleneck analysis |
| [JailBreakDefense](https://github.com/kritibehl/JailBreakDefense) | AI safety middleware | Intent-repair routing · benchmarks · traceable logs |
| [SpeechIntentEval](https://github.com/kritibehl/SpeechIntentEval) | Regression dataset · Robustness | High-context intent regression suite · indirect / polite / sarcastic / ambiguous phrasing |

---

## Open Source Contributions

**Temporal Go SDK**
- [PR #2212](https://github.com/temporalio/sdk-go/pull/2212) — Fixed goroutine leak caused by child workflows blocking on unclosed `doneChannel`; enforced idempotent closure with `sync.Once` · **Merged**
- [PR #2200](https://github.com/temporalio/sdk-go/pull/2200) — Fixed `OnWorkflow` mock to observe propagated context headers; applied `workflowContextWithHeaderPropagated` to `ctxCopy`; added `Test_OnWorkflowMockSeesHeaderContext` regression test; closes #2005 · **Merged**

**Azure Go SDK (azcore)**
- [PR #26051](https://github.com/Azure/azure-sdk-for-go/pull/26051) — Surfaced silently dropped `realClose()` transport errors using `errors.Join` to improve retry-path diagnosability · Under review
- [PR #26106](https://github.com/Azure/azure-sdk-for-go/pull/26106) — Implemented W3C Trace Context (`traceparent` / `tracestate`) propagation using OpenTelemetry propagators; added header-injection unit tests · Under review

---

## Stack

```
Languages     Python · Go · C++17 · Swift · TypeScript · Java · SQL
Systems       State machines · Idempotency · Deterministic replay · Fencing tokens · Retries/backoff
Reliability   Failure mode analysis · Chaos testing · Regression gating · Release readiness
Observability Prometheus · Grafana · Structured logging · Metrics design
Backend       FastAPI · REST · Pydantic · Node.js/Express
ML            PyTorch · HuggingFace Transformers · DistilBERT · Evaluation pipelines
Runtime       PostgreSQL · SQLite · Docker · Kubernetes · GitHub Actions
```

---

## Writing

- [Detecting Silent Regressions in GenAI Systems at Scale](https://medium.com/@kriti0608/detecting-silent-regressions-in-genai-systems-at-scale-039ec03db1e4) — stable metrics, reproducibility, CI gating
- [The Day My Distributed System Failed — and Why That Was the Point](https://medium.com/@kriti0608) — deterministic failure drills, invariants, recovery artifacts
- [Why AI Refusals Feel Like Punishment](https://medium.com/@kriti0608) — safety like reliability: measurable behavior, intent repair

---

## Contact

[kriti0608@gmail.com](mailto:kriti0608@gmail.com) · [LinkedIn](https://www.linkedin.com/in/kriti-behl/) · [Portfolio](https://kriti-portfolio-six.vercel.app) · [Hugging Face](https://huggingface.co/kriti0608) · [Medium](https://medium.com/@kriti0608)

---

**Pin these repos:** Faultline · AutoOps-Insight · ResuMate · FairEval-Suite · Chrome-Copilot · DetTrace
