# Telegraph Bounties

<img src="assets/social-preview.png" alt="Telegraph Bounties" width="100%">

## Season II — 15 commercial missions. Three tracks.

**Start with a real customer problem and work backwards.** Choose a mission, build something people would use, and supply or evaluate the intelligence it needs. The aim is working applications powered by useful, measurable intelligence—not disconnected registrations or technical tasks.

Every mission has one GitHub Issue covering the customer problem, example products, shared Intents, Provider and Evaluator opportunities, integration references, acceptance criteria, judging, growth and submissions. **A participant or team can work in one, two or all three tracks.** Multiple independent teams can enter the same mission or Intent; claims are not exclusive.

### The 15 mission workspaces

| # | Mission | GitHub Issue |
|---|---|---|
| 01 | Exchange | [Build and power Exchange](https://github.com/telegraphprotocol/bounties/issues/189) |
| 02 | Stablecoin | [Build and power Stablecoin](https://github.com/telegraphprotocol/bounties/issues/190) |
| 03 | Institutional Markets | [Build and power Institutional Markets](https://github.com/telegraphprotocol/bounties/issues/191) |
| 04 | Legal | [Build and power Legal](https://github.com/telegraphprotocol/bounties/issues/192) |
| 05 | Conflict Intelligence | [Build and power Conflict Intelligence](https://github.com/telegraphprotocol/bounties/issues/193) |
| 06 | Resources & Agriculture | [Build and power Resources & Agriculture](https://github.com/telegraphprotocol/bounties/issues/194) |
| 07 | Consumer Platform | [Build and power Consumer Platform](https://github.com/telegraphprotocol/bounties/issues/195) |
| 08 | Commodities | [Build and power Commodities](https://github.com/telegraphprotocol/bounties/issues/196) |
| 09 | Personal Agent | [Build and power Personal Agent](https://github.com/telegraphprotocol/bounties/issues/197) |
| 10 | Model Economy | [Build and power Model Economy](https://github.com/telegraphprotocol/bounties/issues/198) |
| 11 | Autonomous Systems | [Build and power Autonomous Systems](https://github.com/telegraphprotocol/bounties/issues/199) |
| 12 | Mining & Power | [Build and power Mining & Power](https://github.com/telegraphprotocol/bounties/issues/200) |
| 13 | Asset Management | [Build and power Asset Management](https://github.com/telegraphprotocol/bounties/issues/201) |
| 14 | Web3 Native & DeFi | [Build and power Web3 Native & DeFi](https://github.com/telegraphprotocol/bounties/issues/202) |
| 15 | Consumer Automation | [Build and power Consumer Automation](https://github.com/telegraphprotocol/bounties/issues/203) |

[See the mission catalogue on Anjoman](https://anjoman.ai/dashboard/hackathon/season-2/missions) · [Official rules, scoring and prizes](https://anjoman.ai/dashboard/hackathon/season-2/rules) · [Telegraph docs](https://anjoman.ai/docs)

### How to take part

1. **Pick a mission.** Read its Issue to understand the customer, outcome, example builds and relevant intelligence. Choose your own useful approach; the examples are not exclusive assignments.
2. **Build across the tracks you want to enter.** Apps & Agents produce working products and paid Telegraph consumption. Miners / Providers supply intelligence for the mission's canonical Intents. Evaluators contribute the truth sources, material or adapters that those Intents actually need. One person or team may contribute across all three, with distinct qualifying evidence for each entry.
3. **Work with the shared network.** An Intent can appear in several missions, but remains one canonical capability with shared Providers, evaluation and ranking. Use the live node schemas and current documentation rather than inventing Intent names or requirements.
4. **Share your work in the mission Issue.** Read recent comments, post your scope, use `/claim`, and post `/progress <update>` at least every 72 hours while claimed. Others may work on the same product, mission or Intent independently. Comments make progress, lessons and collaboration visible; nobody receives exclusive rights by claiming first.
5. **Show what works.** Provide runnable code or an endpoint, a useful result, genuine Telegraph calls and accounting evidence where relevant, test cases (including a failure case), cost per completed outcome and clear limitations. Publish a demo and invite independent feedback in line with the official organic-growth rules.
6. **Submit correctly.** Use `/submit <links and evidence>` to record your contribution in GitHub. Provider registrations and evaluation material are submitted through their respective Anjoman flows. **The final competition entry must also be submitted through the official Season II form** when available; a GitHub comment is not a final hackathon entry.

**November 20** is the community progress showcase. **December 1, 2026, 23:59 UTC** is the main competition submission deadline. Read the [official rules](https://anjoman.ai/dashboard/hackathon/season-2/rules) for eligibility, scoring, growth requirements and prizes. In addition to prizes, eligible Providers and Evaluators may earn from qualifying network activity, and applications may generate revenue if customers adopt them. Earnings are not guaranteed.

### Three tracks, one mission

| Track | What to deliver | Where the work goes |
|---|---|---|
| **Apps & Agents** | A useful application or agent making genuine paid requests or sales through Telegraph, with a reproducible outcome | [Build and integration docs](https://anjoman.ai/docs) · [Anjoman Apps](https://anjoman.ai/dashboard/apps) · Official Season II submission |
| **Miners / Providers** | A working service for a supported canonical Intent, registered and tested on the network | [Miner documentation](https://anjoman.ai/docs/miners/miner-registration) · [Explorer](https://anjoman.ai/dashboard/explore) |
| **Evaluators** | Valid evaluation material, a truth source or a compatible adapter as required by the Intent's actual scoring path | [Anjoman Evaluate](https://anjoman.ai/dashboard/eval) · [Evaluation guidance](https://anjoman.ai/docs/scoring/contribute-evaluation-data) |

The Intent catalogue is a technical reference, **not the starting point for Season II participation**. Providers and Evaluators still compete on canonical shared Intents rather than separate copies for each mission. Contributions to other supported network Intents remain permitted under the published rules.

---

## Other Telegraph contribution opportunities

This repository also tracks customer, mainnet, protocol, tooling, security and release-coverage work beyond the fifteen Season II missions. Those issues remain available and retain their existing claims and review histories. The mission-first presentation does not invalidate earlier contributions or change competition eligibility.

| Work | What it covers | Label |
|---|---|---|
| **Miner / Provider** | Missing, weak or unreliable intelligence supply for an Intent | `work:miner` |
| **Evaluator: adapter** | Missing or weak scoring logic for an eligible Intent family | `work:evaluator` |
| **Evaluator: material** | Missing or stale evaluation material and truth sources | `work:evaluator` |
| **App / Agent / integration** | A working application or integration facing an identifiable gap | `work:app` |
| **Tooling / protocol** | SDKs, examples, observability and reliability | `work:tooling`, `work:protocol` |
| **Security hardening** | Public, non-sensitive hardening of repository tooling | `work:security` |
| **Release coverage** | A major AI release the network cannot yet measure fairly | `source:release` |

**Evaluation contributions go through [Anjoman Evaluate](https://anjoman.ai/dashboard/eval), not GitHub comments.** GitHub records coordination and proof. The network decides material eligibility, active evaluators and rankings. Check the [Intent catalogue](docs/INTENTS.md) and [contribution instructions](CONTRIBUTING.md#contributing-evaluation-material-or-a-scoring-module) for technical details.

### General GitHub contribution workflow

1. Choose an Issue marked `status:open` or an available Season II mission.
2. Read the acceptance criteria and the `## Reward` section before starting. A mission coordination Issue is not itself a separately funded GitHub bounty.
3. Comment `/claim`. Multiple contributors may claim the same Issue; each claim is tracked separately.
4. Post `/progress <update>` at least every 72 hours while claimed; otherwise that claim may lapse without affecting others.
5. Comment `/submit <links and evidence>` when your contribution is ready for review.
6. A maintainer verifies each person's evidence and uses `/approve @user` or `/changes @user <reason>` as appropriate. **A mission must remain available for other contributors when one entry is approved.** Non-mission bounties follow their own published completion criteria.

See [CONTRIBUTING.md](CONTRIBUTING.md) for the detailed workflow. A claim or GitHub approval does not itself establish protocol eligibility, an evaluation result, a hackathon award or a payment commitment.

### More ways to get involved

| I want to… | Go to |
|---|---|
| Enter Season II | [The 15 mission Issues](#the-15-mission-workspaces) |
| Find a general high-priority task | [P0 bounties](../../issues?q=is%3Aissue+is%3Aopen+label%3Apriority%3Ap0+label%3Astatus%3Aopen) |
| Find a small general task | [Good first bounties](../../issues?q=is%3Aissue+is%3Aopen+label%3A%22good+first+bounty%22+label%3Astatus%3Aopen) |
| Contribute outside the fifteen missions | [Miner work](../../issues?q=is%3Aissue+is%3Aopen+label%3Awork%3Aminer) · [Evaluator work](../../issues?q=is%3Aissue+is%3Aopen+label%3Awork%3Aevaluator) · [Customer gaps](../../issues?q=is%3Aissue+is%3Aopen+label%3Asource%3Acustomer) |
| Report a new gap | [Open an Issue](../../issues/new/choose) |
| Cover an important AI release | [Release coverage](docs/RELEASE_COVERAGE.md) |
| Explore the canonical Intent catalogue | [Intents](docs/INTENTS.md) · [Mission mapping](docs/MISSIONS.md) · [Reuse map](docs/NETWORK_MAP.md) |
| Find documentation | [Docs index](docs/README.md) · [Glossary](docs/GLOSSARY.md) · [Integration](docs/INTEGRATION.md) |

Provider recruitment listings (`opportunity:provider`) are for established services exploring onboarding. Their commercial process runs outside the bounty claim workflow.

### Explore from the command line

The catalogue commands need only Python 3 and no network. On Windows use `tb.cmd` instead of `./tb`.

```bash
./tb map
./tb mission exchange
./tb intent SANCTIONS_SCREENING_MATCH
./tb search weather
```

Live board commands need the [GitHub CLI](https://cli.github.com/) signed in (`gh auth login`):

```bash
./tb next
./tb claim 189
./tb progress 189 "Working on a paid Exchange listing-risk flow."
./tb submit 189 "https://github.com/you/project — live demo and Telegraph receipts"
```

The examples illustrate the existing claim workflow. Maintainers must verify the mission Issues accept multiple claims, progress updates and independent submissions before announcing the transition.

## Rewards

Funded GitHub bounties specify an amount, denomination, payout asset, any conversion rule, eligibility, verification conditions and payout window. The bot records a snapshot and SHA-256 hash of the applicable reward terms at claim time. Payouts require separate funding authorization.

Unfunded Issues carry no GitHub payout commitment. Season II prizes and any ongoing network earnings are separate and governed by their published rules. See [docs/REWARDS.md](docs/REWARDS.md).

## Board boundaries

- Start from real demand, an observed failure or a verified release gap.
- Multiple independent implementations and competing Providers or Evaluators are welcome. Claims are non-exclusive.
- Public reports must use authorized, sanitized evidence. Report security issues privately through [SECURITY.md](SECURITY.md) and [docs/DEMAND_INTAKE.md](docs/DEMAND_INTAKE.md).
- Every Issue states its funding status and acceptance criteria. GitHub tracks contributions; the network independently determines ranking and protocol eligibility.
- Previous claims, submissions and pending reviews must remain traceable through any migration or archiving.

## Project health

| | |
|---|---|
| Contributing | [CONTRIBUTING.md](CONTRIBUTING.md) |
| Governance and roles | [GOVERNANCE.md](GOVERNANCE.md) |
| Security reports | [SECURITY.md](SECURITY.md) |
| Code of conduct | [CODE_OF_CONDUCT.md](CODE_OF_CONDUCT.md) |
| Getting help | [SUPPORT.md](SUPPORT.md) |
| License | [MIT](LICENSE) |

## For maintainers and operators

```bash
python scripts/prepush.py
npm test
make seed-h2
make launch-check
```

The maintainer runbooks are in [docs/maintainers](docs/maintainers/README.md). Confirm issue automation and preserve existing review history before publicly announcing the new mission-first board.
