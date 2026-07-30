# Changelog

Development activity for o8 — the governance layer for autonomous engineering teams.

We ship high-signal entries only (features + performance wins). Bug fixes, refactors,
and internal chores live in the private engineering log.

---

## 2026-07-30

- `72b9459b` perf(approvals): stop shipping every stored diff in list responses

## 2026-07-29

- `5483f6e4` feat(connect): relayed surfaces talk over the machine tunnel and paint solid
- `c50d4a98` feat(connect): the browser bridge
- `61b6acf4` feat(connect): cut 3a
- `4dce2e38` feat(connect): cut 2
- `7c378200` feat(runtimes): Qoder CLI as the 13th certified worker runtime, pinned to Qwen3.8-Max-Preview
- `15ec3374` feat(connect): machine-scoped relay tickets + relay machine routing (phase 1b remainder)
- `c95660a7` feat(connect): phase 1b machine registry
- `54992bee` feat(ship): release.mjs announces each release in the community #releases channel
- `211bbb21` feat(connect): o8 connect phase 1a - CLI verbs, machine identity, registry client, server contract (t3-connect answer)
- `4bd04f9c` feat(composer): prompt stash - park a half-written orchestrator prompt, get it back anywhere

## 2026-07-28

- `1c21cdd1` feat: support repo-less orchestrator home sessions
- `9899d4a6` design(settings+motion): All-glass honestly locks the Appearance controls; both palettes open with a 120ms fade
- `4822f845` perf(motion): stop transitioning box-shadow, font-weight and width at the 7 flagged sites

## 2026-07-27

- `9fc6cca1` perf(motion): FLIP tile morphs, DictationPill off width/filter tweens, scaleX analytics bars; view-options glyph loses the ellipsis costume
- `7bfafeee` perf(motion): replace every transition:all in desktop components with explicit property lists
- `6932f7d0` perf(motion): active-row text cue is an opacity pulse, not a background-clip paint loop; delete 6 dead keyframes; slide-in-preview off max-height
- `194cbae7` feat(voice): agent runtime app-server S2S transport - OAuth-sub realtime lifecycle, capability fencing, visible text fallback (,)
- `edd285f5` feat(voice): "Voice via your ChatAI model plan" settings row + narration speaker host
- `4edcd364` design(settings): plan ladder reads Free/Pro/Team
- `2058d963` design(desktop): founder serial chip moves off the status bar into the settings drawer account row

## 2026-07-26

- `a5702bfc` feat(voice): wire dormant narration core to the live lane-event bus

## 2026-07-24

- `9e497a07` feat(runtimes): certify the 12-runtime claim
- `986ae7d7` feat(voice): agent runtime app-server voice capability probe

## 2026-07-23

- `b8a51b4d` feat(entitlement): default to free/BYO when no license server configured

## 2026-07-22

- `655b25d1` feat(voice agent): add governed chained plans
- `6515d4ca` feat(voice agent): require spoken packet review before approval

## 2026-07-21

- `5b3c697d` feat(voice agent): add durable action ledger
- `7745d0a7` feat: add composer undo-send buffer
- `57e13978` feat(runtimes): centralize dispatch registry

## 2026-07-20

- `50ff1ad2` feat: enforce hardened composer modes
- `b130712d` feat(voice agent): ship repo-scoped Code voice control
- `7dca8cb5` feat(mcp): host the operator MCP once as an in-app /api/mcp HTTP endpoint + thin stdio proxy
- `ec7b8a0a` feat(report): preview + consent-gate the auto-attached screenshot before send

## 2026-07-19

- `f86c7e6e` feat(o8md): per-note reply / apply / act on annotations — no full re-review
- `8f8a10c1` feat(voice agent): brain runtime fallback
- `479b2a5e` feat: add declarative community worker adapters
- `00c66673` feat(onboarding): discovery-driven runtime picker
- `d8247975` feat(runtime): kill agent runtime-only production pin
- `972f7422` feat(voice agent): ground phone Code workspace sessions
- `ae093c7f` feat: add declarative CLI runtime adapters
- `6c0809d1` feat(governance): 'surface' approval posture
- `74227c7d` feat: add operator-controlled merge approvals
- `549fb119` perf(brain): share one MCP session across symbol-graph traces — recall p95 1643ms to 146ms
- `6bb5c96a` feat(desktop): Resources tab — tidy pass + guarded per-row Kill action
- `c071f9f6` feat(desktop): Resources tab
- `6da39e30` feat(repos): repoint registered repository paths

## 2026-07-18

- `79feaa0f` feat: close packets without merging
- `8342051e` feat(voice agent): teach the phone voice session to render gen-UI surfaces
- `f781dffd` feat(mobile): managed remote-access desktop contracts — terminal routes + device-scoped steer
- `33b90c46` feat(settings): permissions concierge — live macOS permission status + fix flow
- `b8f0a2bc` feat(security): Tier-2 macOS worker sandbox
- `bbfbc73b` feat(rail): 'missing' repo state first-class across every surface
- `db923792` feat(chat): inline 'Initialize Git here' cure on the no-git-repo orchestrator error
- `c5e491ff` feat(repos): 'missing' readiness state
- `4b7b4fc9` feat(orchestrator): client reconciles against server turn truth
- `b8fac7c1` feat(orchestrator): server-authoritative turn ledger
- `a27aeed5` feat(orchestrator): review-ready self-continuation
- `54bc9eed` perf(review): incremental review scan — dirty-set + stat gate, 60s full sweep
- `cd5c6ee2` perf(fleet): stat-keyed run-log parse cache — stop re-parsing megabytes per poll
- `a060dcf0` feat(governance): every run gets a definite ending — no silent archives
- `051fc2a4` feat(orchestrator): backend-neutral plan-update snapshots for mobile turn progress
- `48bb6d83` feat(rail): finished agents stay in the clean view — Recent tail with truthful outcome chips
- `4d8ef273` feat(review): merge from the review surface
- `bbf36f27` feat(review): summary-first header above the packet diff — agent runtime PR-view parity, our style
- `75269231` feat(spawn): agent-originated workers surface quietly — no screen hijack

## 2026-07-17

- `38a15d4f` feat(all-glass): white ink inside the composer — no slate text on the glass
- `605daace` perf(boot): coalesce the boot API storm
- `ecd14e85` feat(boot): splash owns the window from first paint, one complete reveal
- `67b47b24` design(chrome): AI provider-desktop sidebar float (solid surfaces) + the day's locks in design system.md
- `35b7f84e` feat(canvas): Glass look + the free theme trio — Light / Dark / Glass match the IDE side
- `d4c0dfa0` feat(theme): ALL GLASS locked

## 2026-07-16

- `0fc11c2b` perf: repo switching serves per-repo snapshots and skips work for surfaces that aren't open [via-o8]
- `b1e5751b` perf: workspace/thread restore paints known state instantly — no forced loader hold [via-o8]
- `809d761b` perf: workspace/thread restore paints known state instantly — no forced loader hold [via-o8]
- `4dc2ca48` perf: Settings takeover and right-panel close keep the workspace alive [via-o8]
- `5ae8fa8d` perf: DesktopStatusBar stops observing the entire body subtree for composer position [via-o8]
- `9296c9a4` perf: O8Panel hidden panes stop doing N-repo git scans and duplicate review pipelines [via-o8]
- `d5a553e0` perf: PR detail + panel fetches get stale-while-revalidate snapshots instead of refetch-on-mount [via-o8]
- `5c132e57` perf: lifecycle WS events emit once and reconcile through one coalesced pass [via-o8]
- `dd3e1d21` perf: branch route serves a snapshot instantly, refreshes async with batched git [via-o8]
- `0dab5e43` perf(speed-sprint wave 1a): PTY output and tab clicks stop re-rendering the workspace tree
- `dcf2f911` perf(speed-sprint wave 0): 15 quick wins
- `7bcaafe2` feat(mobile): OpenAI-compatible genui streaming endpoint for the generative-UI spike
- `d0766019` design(all-glass): sidebar preview + toggle polish round
- `822a0d40` feat(theme): All Glass mode (experimental)
- `44d15f6c` design(drawer): merge Theme + Glass into one Appearance row
- `e6374cf4` design(sidebar): left panel becomes a flush dock; account row + drawer lose their duplicate verbs
- `dc85c786` feat(status): the branch chip goes quiet on the default branch
- `65a4b7c9` feat(chrome): move the operator's utilities onto the surfaces they belong to
- `411164aa` design(status): failed runs wear bright red, distinct from the declined-review orange
- `e734a013` feat(chrome): DOM traffic lights that scale with UI zoom — native stoplights hidden
- `0cc4a163` feat(orchestrator): pull Hermes from the composer picker + exec-probe its availability
- `df230c19` feat(orchestrator): pull agent runtime from the backend pickers (not one-click yet)
- `0da5a348` feat(reports): workspace-state snapshot + session-spawn journal in report diagnostics

## 2026-07-15

- `6af65d1f` feat(telemetry): non-crash anomalies phone home
- `c90a8b1a` feat(reports): every bug report carries its own forensics
- `27d279e1` design(workspace-rail): floating branch-details card gets Lisse corners nested to the workspace corner
- `a34abe92` feat(spawn): failed New-session spawns surface a visible error toast — never silent
- `8012daaa` feat(composer): agent runtime + Hermes selectable in the backend picker; chip shows the real next-turn backend
- `b27ae67e` feat(tts): free Steffan male voice is the default for everyone, not the OS voice
- `b40a36a7` feat(workspace): drag a chat from the left rail into the workspace to split it (agent runtime parity)
- `250c5894` feat(voice agent): localize embedded browser targets
- `6c388a8c` feat(voice agent): ground screen guidance in accessibility
- `8f17888b` design(chrome): stoplights + sidebar toggle share one centerline; light-clearance survives UI zoom
- `4cad1e49` perf(dashboard): stop re-rendering the whole page tree on every resize frame
- `63e0051d` feat(license-server): comp-founder script — grant a comped Founding Operator seat
- `e66b54aa` design(theme): dark header chrome matches the paper anchor
- `9d0d9b83` design(theme): de-blue the dark palette — neutral graphite, ThemeLab-picked

## 2026-07-14

- `5d146ad6` feat(dev): ThemeLab
- `841e3c2b` perf(voice): resolve the dictation caret target in one AX round-trip
- `995bf430` feat(voice): add caret streaming and smart compose
- `90139984` feat(workspace-rail): pill stays at any window size, left panel auto-collapses when narrow, real Sources from the conversation
- `ad8c9d06` feat(workspace-rail): the branch-details pill floats its card on click instead of pushing the chat
- `ece1c8d5` design(brain): drop the cost-shape legend cluttering the brain tab bottom
- `c1083742` feat(panel): Incident Queue is a closeable utility tab, not a forced main pane
- `d1bd44ad` design(rail): shimmer flare goes blue on light — orange read too quiet
- `499c8306` feat(workspace): the Orchestrator chat is THE chat — casual Chat surface retired
- `4724af0c` feat(ports): footer ports popover becomes a dev-server launcher
- `27901195` design(panel): terminal-first add-tab menu — shells lead, opens upward
- `dd7db60e` design(boot): loading screen is glass, steady — no black slab, no ticking
- `d01e598e` feat(canvas): Canvas is out of beta — button and mechanics on for everyone
- `73ea7a8d` design(rail): shimmer flare goes orange on light, keeps ice-white on dark
- `0f4c9c13` design(rail): selection reads by shimmer alone — active-row pill off, full-ink flare
- `740ba564` feat(settings): Glass on/off toggle in the quick drawer
- `7983d100` feat(o8-model): free + founders o8 model edits files directly (Composer parity)
- `a55b8d17` feat(ux): right panel opens on Browser, not the dense Activity feed
- `d473a24d` feat(license): analytics labels every signed-in user with their GitHub handle
- `66df3c47` feat(github): desktop side of the managed o8 GitHub App
- `653d1959` feat(license): managed GitHub App token mint

## 2026-07-13

- `f5e6c567` feat(tts): read chord speaks the terminal tail when nothing is selected
- `ea2c0fd2` feat(feedback): the bug queue is the agent's job to remember, not Q's
- `31508e09` feat(dictation): SpeechAnalyzer path for macOS 26+ — the durable Apple Silicon rung
- `c821f598` feat(o8-model): founders rail rides AI provider 3 Flash with a wired 2.5 rollback
- `fd357661` feat(o8-model): land tuned-v2 prompt slot on the founders rail
- `88f9ef0b` design(workspace): branch rail folds to a agent runtime-style icon capsule + scrolls when short
- `c54a54aa` feat(settings): projects show and manage their repos inline
- `18847c57` feat(settings): Models tab + human-first nav order, coming-soon tabs unlisted
- `9c44f25a` feat(settings): Indexing tab
- `7c927bf7` design(settings): drop the SETTINGS/<tab> breadcrumb — the nav already says where you are
- `f133ca3b` design(settings): Connectors reads human-first
- `df4919f1` feat(settings): settings search — 100+ row registry over the nav
- `ca40d881` feat(settings): Git & PRs tab
- `fc92838f` feat(settings): General tab
- `807ffd4b` design(sidebar): collapsed-rail hover overlay
- `b8f037f1` feat(account): What's-new mini-changelog + Show more; Discord row; read-chord selection snapshots
- `115c1781` design(chrome): account click opens the full quick-settings drawer; icon cluster sits flat on the rail
- `ad151be3` design(chrome): utility icons return to the bottom status rail; sidebar footer is the account row alone
- `3e3b2c85` design(sidebar): flat left rail
- `95dc6912` feat(sidebar): competing product-style account block
- `2c8a0ce7` design(command-palette): competing product search parity
- `f3fd2c65` design(automations): design system row grammar + competing product empty state, decompose page
- `67d50ce2` design(customize): inventory counts on tab pills + Show-N-more section truncation
- `977b7ae4` feat(customize): open backing files in-app, connection status dots; settings goes INLINE
- `49a72419` design(customize): design system typography sweep — locked roles across the page
- `36fea238` feat(customize): first-class Customize surface
- `e2e59b26` design(transcript): competing product text-sheen turn grammar
- `8ab04018` feat(feedback): the in-app receipt — tell the reporter their bug is fixed
- `b78ecb5d` feat(transcript): competing product slim-line turn vocabulary — full parity pass
- `c624db31` feat(feedback): private intake, public fixes — reports get an id, fixes get credited
- `7fd70f36` feat(chat): threads name themselves
- `52fa1973` feat(diff-wiring): per-file review list on the ChatActionCard rollup
- `4ea7ff81` feat(diff-wiring): dual-fidelity FileEditRow — inline peek + filename→review
- `70951199` feat(diff-wiring): file-scoped diff seam + inline peek renderer
- `70289f29` feat(chat): loopback links in the transcript open o8's embedded browser
- `c918d8ff` design(files): competing product arrangement

## 2026-07-12

- `3e254a82` feat(design-draw): wire enrichment, region crop + thumbnail into surfaces
- `0a3afad6` feat(design-draw): native draw agent — component names, hover, thumbnail
- `1ac8cb53` feat(design-draw): add React component-name + region-crop primitives
- `d307189c` feat(turn-grammar): wire Thought block + file-edit rows into the transcript
- `9bee5502` feat(turn-grammar): auto-collapsing Thought block with compositor shimmer
- `92f59d76` feat(turn-grammar): live file-edit rows (Editing -> Edited +A -D)
- `bc9a558e` feat(turn-grammar): tool-call error badges with auto-expanded error output
- `5936196f` feat(turn-grammar): thread tool-call error status through the orchestrator stream
- `434b1a6b` design(status): review state becomes Hourglass; round-2 review lab (10 3x3 candidates)
- `acfe6b73` feat(rail): repo drawers, repo-scoped spawn, and ownership nesting in the left rail
- `e3ba46d2` feat(browser): drag-to-draw Design Mode
- `542c9a96` feat(browser): the browser becomes a first-class drawer state with header-rail page tabs and a real toolbelt
- `dc7dc1b8` feat(o8-model): tier-tuned system prompts
- `eb22614c` feat(ui): competing product siphon pass 1
- `bc6c8e3d` feat(operator): plan-gated o8 model rails — nemo for free, AI provider for founders
- `84981ef2` feat(orchestrator): add free o8 chat backend to the composer
- `23de59f7` perf(boot): merge 4 identical capabilities — generate_context! 1665ms -> 971ms
- `901f9313` perf(boot): overlap the orphan reap with generate_context! instead of paying it first
- `5d212cd0` design(status): packetStatusColor failed → brand orange, aligned with the dot family (Q final lock 2026-07-12)
- `9bd94c2e` design(status): failed joins rejected in the brand orange
- `b1b7c792` design(status): idle = Drift
- `ba04f70d` design(status): the locked one-canvas family
- `64b7caf7` design(status): running is always the orbit + rejected wears the failed cross in amber
- `9ec7fb18` perf(sidecar): cache V8 bytecode

## 2026-07-11

- `1420e21e` design(motion): 5 awaiting-review candidates in the lab (AI provider bespoke)
- `cda5c932` design(motion): remove the scan loader from the family (operator cut)
- `c66e3755` design(status): failed = the dispatch pixel mark in alarm red — locked
- `37427c40` perf(server): stop loading a browser-automation library before the app answers a request
- `caf096c1` perf(boot): trace the pre-window path
- `fb36d155` design(motion): bespoke loader family in the lab
- `7508fd2d` perf(boot): record boot-phase timings so cold launch can never silently regress
- `f12dba68` perf(ws): bridge agent-lifecycle to the window event
- `89413fb6` perf(spec-pane): stop polling the server for a pane nobody is looking at
- `28c9decd` perf(ws-server): make the conflict scan event-driven — 45x less idle git work
- `bfa4eb6a` perf(motion): drive the sweep dot from the compositor — 9.5% -> 2.2% idle CPU
- `8c395f0c` perf(render): memoize the orchestrator context; stop animating a full-screen gaussian
- `8a30bed9` perf(worktree): stop the 5-second recursive disk walk that was idling the fans
- `e4a0fffd` perf(boot): build the window before the sidecar bootstrap, not after
- `1fa19cb8` perf(boot): one login-shell probe instead of three
- `8db125ef` perf(ws-server): stop event-loop wedge from sync git in reconcile + backoff pathological merged-by-ancestry lanes
- `640dc22f` perf(prod): stop git-scanning the app's own bundle
- `2c37fec7` feat(mobile): expose huddle plan in fleet
- `420cb48a` perf(dictation): overlap mic open with audio duck instead of serializing
- `2ae49195` feat(files): save edits to any on-disk file, not just registered repos
- `b8f8a913` feat(files): Files view can open any file on disk, not just registered repos
- `b3651041` feat(files): open Finder files on the surface you're on, not a canvas hijack
- `129f6eb2` feat(packet): Request changes -> orchestrator; Discard -> soft dismiss (recoverable)
- `2107a79c` feat(packet): show WHY a review was declined in the decision banner
- `22695b6b` design(status): review-declined = orange o8 dual-pulse (trial)
- `1f449d7c` design(status): Failed pulses (red orb) so it separates from the static rose of rejected
- `766f377b` design(status): awaiting-review is a paused grey with a sweep motion, not a color
- `d74b68c2` design(status): cool the human-decision dot states off the warm cluster
- `3141620d` feat(motion-lab): add a Status vocabulary board
- `17cbe1b1` feat(packet): tighten the decision banner
- `e704cbbf` feat(packet): give a rejected packet a decision banner + stateful dot, and a Discard verb
- `0885c2bd` feat(merge): give the review beacon a 'rejected' state and stop hygiene packets parking the gate
- `e8c1eb0b` feat(merge): drop the 'No open PR'/'Open PR' bottom-bar noise
- `d6394f42` feat(merge): let the bottom-bar review beacon merge, not just view
- `1d4a6a6b` feat(rail): surface the branch's PR inline in the workspace rail
- `fe48365b` design(composer): swap mic and context meter — mic by Send, meter by attach
- `55871530` feat(composer): kill the Fleet/Solo chip — solo vs fleet decided by runtime count
- `1a4ce4ca` feat(composer): thin file-list scrollbar; Rules chip only when rules exist + /rule /rules
- `a51a40ce` design(composer): filename-first file attach rows, match highlight, lighter weights
- `549e5020` design(composer): label Collide as 'Mixture of Agents' in the picker
- `42a0a3ee` design(composer): trigger names the model, not the provider
- `371a85dc` design(composer): house drawers for models, Extra label, dynamic Collide decider
- `5b48be91` design(composer): effort slider with named tiers, Ultracode top notch arms Swarm
- `a92793f8` design(composer): agent runtime-style footer
- `b3e935a8` feat(orchestrator): clarify-first goes silent + auto-arms on a repo's first mission
- `0fb453fa` feat(ui): retire the permission shield — composers always run full access
- `68780725` feat(ui): move add-repo onto the Projects row, slim the footer
- `15d77469` perf(ui): 60fps panel drags via direct-DOM + footer icon tiers

## 2026-07-10

- `e86b96eb` feat(voice agent): control o8 hosted terminals by voice
- `5b009314` feat(voice): main-process capture defaults ON for Intel Macs on Sequoia
- `7a1f0363` feat(voice): main-process microphone capture

## 2026-07-09

- `447fd893` feat: merge-gate test replay + decoupled worktree capture trail
- `bd57aed6` perf: bound mobile worktree diff transport
- `0b2987fd` perf: page mobile chat history
- `b39d0a61` perf: stream revisioned mobile inbox deltas
- `e71e4619` feat(telemetry): native crash capture (SIGSEGV/SIGABRT/SIGBUS/stack-overflow) via minidumps
- `622c4ff5` feat(desktop): explicit Open With UTIs
- `f4f9010a` feat: subject-gone TTL fallthrough
- `81133698` feat(desktop): Finder "Open With → o8" opens land in the workspace on the default IDE surface

## 2026-07-08

- `0598f089` feat(canvas): IDE-parity transcript rendering + honest lifecycle clocks in agent cards
- `fc7b28bd` feat(telemetry): Sentry crash/error reporting across all three desktop layers — dormant without a DSN
- `69ce0531` feat(voice): voice agent Spatial Context
- `641c73a0` feat(entitlement): View as Free dev switch — founder--gated, min-clamped
- `bc0216d3` feat(voice): morph composer into live agent partials + vary voice agent ack lingo
- `6dd2d020` feat(voice): window-aware partials HUD anchor + opt-in Fn dictation HUD
- `1a39e463` feat(voice): outside-the-window live agent-transcription HUD
- `6f33cf45` feat: wedge layer-5 escalation lands on awaiting_human; new status joins the parked-reminder set
- `13c4dbda` feat(lane): unified dead-lane archiver with explicit policy table
- `aaae15c9` feat: awaiting_human as a real persistable lane status
- `f80e338a` feat(canvas+voice agent): Whisper on agent path always + grid tiles agent cards + GA SDP URL in contract
- `5a24d401` feat: wedge-timeout stuck launching lanes to awaiting_orchestrator
- `4f55be71` feat: register kill_escalated + no_session_binding lane-event verbs; roadmap rock-1 delivered
- `9de24d3f` feat: session-binding fault detector
- `c45b3e35` feat: single guarded prune gate for all worktree deletions (Rock 1 item 3)
- `3b778ba6` feat: confirmed-kill escalation for stop-packet ( S1)
- `7bca71c7` feat: wedge-timeouts so parked lanes never park silently (Rock 1 item 2)
- `f2448cca` feat: persisted idempotency for steer/rerun/reset/dispatch
- `cc526c22` feat: o8 Relay v1 desktop connector + wiring, R3 docs (WIP→complete)
- `5a39309e` feat: o8 Relay v1
- `5bfa0776` feat: wire process crash capture into ws-server + defensive WebSocketServer error handler
- `488e8948` feat: terminal-host process seam for ws-server PTYs ( follow-up)
- `e28f11ea` feat: add release rollback script
- `aacbf809` feat: updater safety check skips pulled releases before applying an update
- `d56630af` feat: early-boot crash capture in the packaged server wrapper
- `2c5c0e9f` feat: capture server + renderer crashes into the crash store
- `d733b864` feat: local crash capture store + opt-in uploader
- `0d42766e` feat: add opt-in crash-report setting (Privacy) to operator defaults
- `7b0ac1d3` feat: event-loop lag watchdog for ws-server ( follow-up)
- `b72aeef7` feat: voice agent Agent Mode desktop half

## 2026-07-07

- `043938d1` feat: add canvas file card editor gutter
- `0e1c417f` feat(canvas): chrome-aware, center-gathered card placement
- `05672851` feat(canvas): justified-row form-fit grid
- `f64ca889` feat: canvas keyboard zoom + uniform card body text scale
- `ff313190` feat: canvas agent cards go live
- `9caea345` feat(canvas+voice agent): voice presence
- `c1d5ea0e` feat(proxy): Deepgram Nova-3 primary transcribe arm on /v1/transcribe
- `d959eb12` feat: STT latency harness
- `7c95d184` feat: Groq configuration field in Settings → Voice → Transcription
- `66f730b6` feat: wire local transcription first in the whisper ladder
- `c9cc16f9` feat: on-device transcription tier for Apple Silicon
- `b870c8a0` feat: choreograph canvas card spawns
- `02b4feef` feat: dictation polish default → AI provider-2.5-flash-lite
- `d91a1051` feat: skip Whisper re-transcription under 12 words
- `6e149704` feat: Whisper via Groq
- `d9a6c784` feat: polish model overridable via polish_model dictation-config key
- `c34564d7` feat: move speak-selection chord Ctrl+Shift+S → Ctrl+Shift+R (operator: S kept colliding with muscle memory; R = Read, no default collisions)
- `60c0ed93` feat: spawned-agents hover card v1
- `959762f4` feat: packet cards outcome-first
- `0195a0b0` feat(unknowns): opt-in buy-in doc on merge
- `9278542e` feat(unknowns): clarify-first interview before dispatch
- `ce13a5bb` feat(unknowns): HTML packet explainer + quiz-gated human approve
- `6e12712a` feat(unknowns): worker deviations log surfaced at review
- `80c017f5` feat: reviewer backend split
- `a6424073` feat: mobile parity AGENTS
- `9ef050a8` feat: canonical mobile fleet projection
- `33776cde` feat: mobile review units with explicit authority

## 2026-07-06

- `13f825f4` feat: pair dispatch runtime with orchestrator
- `3745c9fd` feat: add composite webview MCP verbs
- `1884a544` feat: dispatch agent runtime workers
- `f0d201a3` feat(onboarding): Scan again affordance on the runtime step
- `039bb170` feat(mcp): smart add box - paste a config, an npx command line, or a URL and it parses itself; manual JSON fields demoted to a disclosure
- `739040e3` design(composer): run-context chips move up into the empty-state dead space - off the status bar
- `8332d0d8` design(composer): adaptive sits between medium and high in the thinking drawer

## 2026-07-05

- `b3bde7f0` design(composer): mode picker - Swarm drops Ultracode, honest Solo copy, hover explains each mode
- `63d1809c` feat(canvas): free tier is Paper-only light/dark - looks, dials, depth, and advanced are founders
- `64b50913` feat: new o8.app desktop icon
- `a033f3e8` design(canvas): Mine preset renamed Custom; redundant settings-side glass tuner removed - the canvas panel owns tuning
- `529457d5` feat(settings): Canvas keeps Experimental badge; founders-first theme scaffold; instrumentation is internal-only not founder-facing
- `44375b05` feat(settings): Diagnostics keeps user-actionable only - recall/loop/demo instrumentation behind Founders, width rhythm fixed
- `4897d29b` design(settings): project cards collapse to one dense inset group - rows not sub-cards
- `5132080a` feat(settings): Founders fast-path Brain status row; casual-chat toggle unsurfaced for beta
- `e0e30df4` feat(settings): Diagnostics tab on grouped system
- `1724a726` feat(settings): Projects tab on grouped system
- `40a0215f` feat(settings): CLI usage meters in quick drawer are Founders-mode content
- `ed893ca2` feat(settings): Voice keeps app-level only - voice agent owns polish/dictionary/audio; new voice agent settings row opens his window
- `3e1d84da` design(settings): Local models on grouped shell, MCP client row icon tiles
- `27fbbab0` feat(settings): drop voice History from o8 settings - voice agent owns it (double-tap the dock)
- `e08c62c0` design(settings): Connectors bar-raise - icon tiles, casing, ghost buttons
- `14893729` feat(settings): Dispatch tab on grouped system - Founders mode holds the extras
- `d55dd7eb` feat(settings): MCP + Connectors tabs on grouped system
- `2ce98cc3` design(settings): About polish - icon tiles, product casing, grouped report-issue form
- `84f67f00` feat(settings): About tab on grouped system
- `ba95b596` feat(settings): Plan & Billing tab on grouped system
- `bcacf3ed` feat(settings): Mobile pairing tab on grouped system
- `db73b80b` design(settings): palette-aware accent - lighter blue active states in dark mode
- `57ef1236` feat(settings): Account tab on grouped system
- `074cabd2` feat(settings): Voice tab on grouped system; dictation moves Appearance -> Voice
- `511e3f4a` feat(settings): inset-grouped primitives + Appearance pilot (mobile settings style port,)
- `74a81b7b` feat: changelog attributes o8-merged work
- `bfb907c7` feat(analytics): roll top-accounts up by person + label with GitHub handle
- `44631f29` feat(entitlement): link this install to the account on sign-in (device rollup)
- `0d4e891d` feat(analytics): Phase 2
- `ee3a9893` feat: orchestrator crash-survival — detached turns + in-flight rebind [via-o8]
- `3a262973` feat(analytics): count real users (distinct accounts), not install churn
- `543cf115` feat(license-server): return today's managed-Brain usage on /account/license
- `ef810010` feat(status-bar): Founding Operator serial-chip badge by the ?

## 2026-07-04

- `92fdbbf8` feat(license-server): store GitHub handle from checkout metadata as founder displayName
- `7f34928a` feat: agent runtime is a first-class in-UI orchestrator [via-o8]
- `319b9b4c` feat: 'o8 app restart' + auto-apply updates when idle [via-o8]
- `0d9282c0` feat: mission registry core [via-o8]

## 2026-07-03

- `3e0f0a56` feat: add terse o8 ask answers
- `6cf2be30` feat: make agent runtime orchestrator brain-first
- `9d4b083d` feat: add quick docs drawer for operator config files

## 2026-07-02

- `3f9326c3` feat(fable): the decisions-only window — metered-orchestrator mode
- `5e02c891` feat(auth): bake GITHUB_OAUTH_CLIENT_ID into signed builds
- `72fd7db5` perf(workspace): instant skeleton first paint on Workspace tab
- `93e4615c` perf(workspace): changes-only snapshot skips gh network calls
- `6063cccc` perf(o8): voice-playback line highlighting — reads the spoken line + scroll-follows
- `a70b6589` perf(o8-panel): pre-warm the spec reviewer on pane-open so the first review is instant
- `bf2cfe64` feat(o8): launch-polish batch
- `abd039b5` feat(session-rules): Rules chip + tiered popover in the orchestrator composer
- `ce78df6e` feat(session-rules): worker inheritance + rules_applied audit event
- `06591d08` feat(session-rules): pin active rules into every orchestrator turn
- `d1ec49ea` feat(session-rules): gated /api/orchestrator/session-rules route
- `c4d49c5a` feat(session-rules): thread-scoped rule store + prompt block

## 2026-07-01

- `2952ac06` feat(collide): label the Collide toggle with a full hover tooltip + aria
- `a95db82b` feat(orchestrator): warm the orchestrator with a resident-process pool + lockout auto-deny
- `2046e61c` feat(targeting): pass tier effort on dispatch + fix inline-issue number (effort→worker 3/3)

## 2026-06-30

- `e9de87c8` feat(targeting): promote Targeting from utility tab to a main tab (polish)
- `0fd36aba` feat(targeting): observability logging (step 8)
- `a02a655e` feat(targeting): o8_targets MCP tool
- `4caaf0ae` feat(targeting): difficulty→tier routing + Dispatch button (step 6)
- `8879550f` feat(targeting): cheap-triage-model rationales — the money-shot (step 5)
- `f2bdb271` feat(targeting): triage/action config triads (step 4)
- `a453e756` feat(targeting): /api/panel/targets route + Targeting panel surface (step 3)
- `76fd668a` feat(targeting): heuristic scorer + score cache (step 2)
- `11b10339` feat(targeting): signal collection for the Targeting Machine (step 1)
- `11885d78` feat(orchestrator): Collide composer chip + faint→solid proposals UX (Steps 5,6)
- `85a05e58` feat(orchestrator): Collide MoA fusion engine + registration + cap-degrade (Steps 3,4,7,9)
- `7e7cf446` feat(orchestrator): two-layer read-only proposer lockout (Collide Step 2)

## 2026-06-29

- `1336c1c3` feat(orchestrator): Hermes via a generic ACP backend (Step 3b–3d)
- `3abc2816` feat(orchestrator): orchestratorBackend setting — makes agent runtime selectable (Step 1)
- `08d77476` feat(mcp): o8 now configures agent runtime — closes the "any CLI" set (Phase 2)
- `71d2a5ac` feat(mcp): o8 now configures the AI provider CLI from the registry (Phase 2)
- `426927e4` feat(mcp): agent runtime o8 entry from the registry, not passthrough (Step F)

## 2026-06-28

- `5093b05e` feat: desktop half of mobile inline diff comments ( slice 2)
- `5319aa94` feat: STYLEGUIDE.md
- `8642d4b1` feat: Paired-devices settings list with per-device revoke
- `99f4f43f` feat: deterministic 4401 close for a revoked device on reconnect

## 2026-06-27

- `aa37780c` feat: mobile E2EE channel
- `497226ba` feat: mobile device enrollment + per-device token validation ( stage 1b)
- `ea1db204` feat: mobile E2EE crypto + per-device token registry foundation ( stage 1a)
- `5f3ee83a` feat: persistent terminals default ON + hide terminal status bar ( stage 5)
- `6d63264c` feat: canvas terminals re-attach surviving sessions on restore ( stage 4)
- `6851034b` feat: re-attach surviving dash terminals with scrollback after restart ( stage 3)
- `7ab109a5` feat: keep dash terminals alive on detach + bounded orphan GC ( stage 2)
- `8b61e5c5` feat: spawn interactive dash terminals inside terminal, gated ( stage 1)
- `fb72953f` feat: default crash-survivable workers ON (kill-test passed on 0.1.512)
- `ed1497a2` feat: boot re-bind observability + crash-survival contract test ( stage 2)
- `71b8b39d` feat: crash-survivable worker spawn, gated (daemon crash-survival stage 1)
- `a8e86e57` feat: worker-context merge approval card + o8 inbox + o8 packet approve-merge ( stages 5b/6)
- `60764b1f` feat: extract steer-packet route + o8 packet steer (control-plane symmetry stage 4)

## 2026-06-26

- `8cd6f18c` feat(cli): o8 packet reset/retry/rerun/merge-preview (control-plane symmetry stage 3)
- `9531a9d1` feat(cli): o8 mission create/dispatch/status/wait/tail (control-plane symmetry stage 1)
- `e3ea92a7` feat(review): pick the best-of-N winner through the governed merge gate + audit
- `b1e465db` feat(review): per-candidate merge-gate verdict on the compare matrix
- `2173dd4d` feat(review): mount the N-up compare matrix as a contextual O8Panel tab
- `7c648a41` feat(review): N-up comparison diff matrix component (best-of-N)
- `672c45fb` feat(orchestrator): arm best-of-N fan-out via comparisonModels on create_mission
- `491c83f0` feat(browser): Design Mode click-to-grab over the native window (Stage 4b)
- `5982fc51` feat(browser): native browser-view as default operator setting (Stage 6)
- `6c520b0e` feat(browser): occlusion snapshot-swap for the native browser-view (Stage 5)

## 2026-06-25

- `2eb4a758` feat(browser): wire o8_browser_* to the native browser-view (Stage 4, secure)
- `21d17f64` feat(browser): native browser-view panel surface + position sync (Stage 3)
- `81f471a8` feat(browser): inject in-page agent into browser-view (Stage 2 — secure)
- `044d9746` feat(browser): native browser-view child window (Stage 1 — Rust shell)
- `a72e5024` feat(browser): engine-pane fallback so auth-gated apps render + stay drivable
- `014d36a7` feat(browser): render Clerk/auth-gated apps + cut the dead Open Source button
- `a00bcea4` feat: continuous agent ghost competing product + unified agent-driving glow
- `9519fd02` feat: unify Design Mode
- `74dca866` feat: Design-Mode grab

## 2026-06-24

- `f6ee2c63` feat: canvas add-file/open-diff/open-chat/add-video verbs — agent spawns every content kind
- `9863a30b` feat: o8_canvas full verb parity
- `6e6bd49a` feat: canvas add-image/stack/flip/separate intent verbs — agent control parity
- `ef6bd9fa` feat: canvas image-stack UX
- `051c7030` feat: theme-aware ASCII o8 workspace loader
- `cda07a6b` feat: ASCII o8 boot splash — animated wordmark loading screen
- `8e62d763` feat: agent canvas control — see + place/size/raise/close cards
- `db1da35b` feat: ASCII effects suite — image/wordmark, wave field, flow field
- `2edf1d60` feat: liquid ascii fluid effect + extensible effects lab preview
- `01e89e03` feat(lanes): shared archived-dedup primitive + collapse=true structured-state query
- `e39098e9` feat(mcp): semantic locators

## 2026-06-23

- `ff1f1647` feat(voice agent): kill/stop agents by voice
- `859c91b7` feat: home-dir agents
- `c62ba5d8` feat: mailbox in voice agent — relay + read o8 team messages by voice
- `531fd456` feat: voice agent is peer-aware

## 2026-06-22

- `0e9f0950` feat: o8 team mailbox (tell/inbox) + auto-installed guard hook
- `e9bdaf8d` feat: o8 team
- `26e93f23` feat: Huddle mode
- `6e5f107c` feat: canvas navigator loupe size is adjustable in the tuner
- `71631570` feat: global ⌘⇧E "report an issue" hotkey on the IDE dashboard
- `28fb3298` design: float the mission-complete card above the composer
- `b4a55755` feat: home-dir AI provider agent
- `45d63db6` feat(brain): free fast Brain via warm AI provider CLI
- `714d08ee` feat(brain): managed-inference + bring-your-own guardrails so non-paying users never burn founder credits
- `443c9c1e` feat: operator Stop button + fix the phantom "Working forever" latch
- `a8985bdf` feat: mobile voice agent remote — drive voice-to-voice from the phone
- `e7f16c07` feat(brain): local-model inference backend
- `1b2cad53` feat(brain): founders auto-get the fast Brain tier (B-1) — instant answers, not the 15-30s CLI
- `adabd47b` feat(founding): STT sweep harness + complete app-wide inference inventory
- `8f9b2633` feat(founding): managed-inference speed/cost sweep harness + Brain tier results
- `95220fbe` feat(founding): /v1/founders wall endpoint + launch checklist

## 2026-06-21

- `26562426` feat: founding cohort count endpoint + metadata-signal robustness
- `f3def57d` feat: realign Founding Operator tier to locked spec (plan: founder, early access, tiered)
- `1e45dba3` feat: Founding Operator purchase
- `cdc24b56` feat: local models

## 2026-06-20

- `682f4ef1` feat(dispatch): make defaultDispatchModel writable via the operator-defaults API
- `372bea58` feat(dispatch): run workers on local models
- `0a360967` feat(voice): o8_status reports each agent's canvas name — spoken roster
- `2701fdbf` feat(voice): address a working agent by its canvas name — "Atlas, run the tests"
- `a5e3e59c` feat(canvas): memorable agent codenames + color-by-runtime + grid voice verb
- `4a36ccd7` design(canvas): chat title weight 400 — match every other card
- `d839c121` design(canvas): reconcile chrome spec — header layout + zoom-in ladder
- `0f3c9437` feat(canvas): zoom IN
- `75692319` feat(voice): meter realtime voice spend → usage_logs + cost dashboard
- `5d06840e` design(canvas): chat-card header
- `8d0c6816` design(canvas): lock the canvas-chrome system into design system.md
- `3380dcd6` design(canvas): media cards into the shared chrome family
- `a3cde335` design(canvas): browser card header into the shared chrome family
- `a9bed1ae` design(canvas): one chrome vocabulary across cards — shared sizes + dynamic floor
- `ebe1fba5` feat(canvas): render-on-screen
- `762b231a` feat(voice): show in-flight worker count inside the voice-live dock capsule

## 2026-06-19

- `00b85563` feat(voice): voice-live presence shows in the screen dock, not only the IDE window
- `cb7a6b0c` feat(voice): double-tap right Cmd toggles voice-to-voice mode (live indicator + idle auto-off)
- `8d86c7b8` design(chrome): ≥44px hit target on header pills + the panel ✕
- `792857c6` feat(voice): voice agent can reset/retry + wait on a packet by voice — closes
- `9f2ec0bf` feat(voice): voice agent can annotate o8.md by voice — o8_spec_annotate
- `1f559d62` feat(voice): voice agent competing product
- `9f99da63` feat(voice): voice agent can drive a browser + inspect a packet diff by voice
- `e2df9a9e` feat(zoom): global ⌘-/⌘=/⌘+/⌘0 zoom for the IDE shell
- `aae3f55d` feat(voice): voice agent can spawn agent cards by voice — wire spawn-agents canvas verb
- `8c993907` feat(voice): voice agent realtime
- `570eabe0` feat(voice): voice agent realtime — expose all 10 AI modelrealtime voices
- `96191758` feat(voice): voice agent realtime
- `4a14c5c2` feat(voice): voice agent realtime
- `1fc792b5` feat(voice): voice agent realtime
- `914e7a28` feat(voice): voice agent realtime
- `72455b38` feat(canvas): voice spawn-agents
- `24460468` feat(canvas): stream the dock's assistant prose with the smooth-text reveal

## 2026-06-18

- `b2d37e10` perf(chat): make the streaming reveal fast, not just smooth
- `3ca66b6d` feat: smooth streaming reveal in the orchestrator chat (no more bursty text)
- `f1106bb5` design(shell): right-panel glass squircle fill, flat composer, no o8.md auto-collapse
- `9e5a9237` design(shell): glass-mode left-column cohesion + lisse hover-preview edges
- `55956638` design(panel): lisse squircle corners on the right O8Panel
- `5231e568` perf: kill dashboard render storm + realtime snapshot timeout spiral
- `9450a254` feat: wire canvas + mobile orchestrator surfaces into the stream replay path
- `67cad6e5` feat: orchestrator stream replay buffer
- `2304711c` feat: voice agent changes o8 UI settings by voice (theme, surface, canvas mode)

## 2026-06-17

- `f2562078` perf(voice agent): persistent AI provider session + keydown pre-warm to cut agent latency
- `54db150e` feat(voice agent): additive teaching diagrams — keep building on the live drawing
- `4ce723f5` feat(voice agent): draw teaching diagrams on screen instead of writing an HTML file
- `fd33adb4` feat: surface native AI provider scouts as a live crew card (orchestrator + canvas)
- `778d5f47` perf: smoother orchestrator streaming
- `efcb1b74` feat: orchestrator turns can run far longer — raise hang watchdog 30m to 4h
- `be8f479e` feat(voice): teaching-mode P1
- `2d59191c` feat(voice): screen-draw snaps to the real UI element + Fn paste targets o8 + mail draft opens visible
- `f89ea6f4` feat(voice): interrupt a running task + keep the working indicator lit for background work
- `75c50d03` feat(voice): voice agent Draws — [DRAW:rect/arrow] screen annotations
- `1386ce69` feat(voice): read_screen tool
- `1ebb2191` feat(voice): o8_canvas tool — drive the Canvas by voice

## 2026-06-16

- `fceadeb3` feat(voice): VoiceTab escalation-policy toggle (Off / Auto / Deep)
- `0d952a0c` feat(voice): escalation-policy backend + concurrent-task safety
- `80dd5704` feat(voice): two-speed escalation routing for the voice agent
- `fef04513` feat(voice): AI provider background brain + escalate handoff for the voice agent
- `3d2153fe` design(settings): cleaner iOS-style switches, native selects & segmented controls + bold tab headers
- `cf267915` feat(canvas): in-app feedback capture + auto-hiding navigator loupe

## 2026-06-15

- `f1781b55` feat(canvas): ship the operator o8 glass theme + universal orb default
- `e22c9460` feat(canvas): unified corner-resize on all cards + framed terminal + spawn fit
- `d8c39798` feat(canvas): live dispatch dock, balanced grid, alerts open the PR diff
- `ee841229` feat: founding-pass beta invites
- `01d6fed4` design: harmonize the status-bar branch label with the composer chip type
- `8239da16` feat: unify composer chip menus onto ComposerPopover
- `c5972ae8` feat: composer popovers portal out via a shared ComposerPopover primitive
- `74ea3986` feat: auto-collapse the left panel while the o8.md notes tab is open
- `3cbaf806` feat: composer button row collapses to icons when narrow
- `4fbc3de9` feat: supervisor inbox self-closes via escalated/resolved states
- `41d515db` design(canvas): grey-on-white media rim + integrated header + matched resize arc
- `f600eafd` design(canvas): defined rim + off-edge resize arc on photo & video cards

## 2026-06-14

- `2059d0b4` feat(workspace): smooth push for the workspace-detail rail + clearer toggle
- `2f06f761` feat: o8 menu-bar tray icon → new o8 monogram (white template)
- `a76ff215` design(canvas): rename Alerts dropdown + make rows jump to their surface
- `c64ff110` feat(workspace): footer merge beacon -- fleet-wide "ready to merge" pill
- `1c2e9370` feat: new o8 app icon — aurora Liquid Glass o8 monogram
- `537d86c1` design(canvas): glass onboarding panels + behind-glass motes reel, match reel type
- `90d07f0d` feat(workspace): consolidate orchestrator composer chip row + adaptive icons + blocky-o8 boot loader
- `e61993bd` feat(canvas): first-run welcome modal + guided coach-mark tour
- `c5f2710f` feat(canvas): add orchestration MODE selector (Fleet / Single / Fusion) to the canvas composer
- `a53cd8a3` feat(canvas): add Clerk account dossier to the canvas top-right
- `22e43694` feat(canvas): add video cards
- `c68375e9` feat(auth): desktop ticket exchange + sign-in handoff (Clerk signals API)
- `afbd6876` feat(auth): GitHub sign-in via Clerk — shared hook, account UI, o8:// receive
- `6f6782bb` feat(canvas): merge composer model+thinking into one drawer; wrap file cards
- `8e432ad8` feat(canvas): sphere-projection orb navigator + single-toggle bubble UI
- `cfd935f3` feat(canvas): readable o8.md + terminal fonts, caret-correct spec card

## 2026-06-13

- `c3ea71b1` feat(mcp): operator MCP server supports a shared HTTP transport
- `1e6153c2` feat(canvas): result-card synthesis from the orchestrator tool stream
- `5c28f04d` feat(canvas): rich response blocks shared + o8 bench parity + reasoning in seconds
- `974f0dce` feat(canvas): dock solid edge + chat modal at agent-card bench parity
- `e23f58f2` feat(canvas): all-angle hidden resize on the chat-card
- `ccaba352` feat(canvas): shared CardComposer
- `527ae80f` feat(canvas): smooth borderless chrome on dock + chat-card
- `2cff02b7` feat(canvas): borderless DockEntryView
- `d6586a0e` feat(canvas): agent-card bench — side-by-side presence comparison
- `ba4afaa2` feat(canvas): agent-card bench — PR + edited-files result variants
- `9b0b8dc3` feat(canvas): agent-card bench
- `d85e85da` feat(canvas): agent-card bench — user messages + smooth Brain citations
- `7b7f10e5` feat(canvas): agent-card bench
- `1373a8a5` feat(canvas): agent-card bench
- `2c5f8480` feat(canvas): pinned orchestrator dock + split-tab orchestrator modals
- `70dc44b0` feat(canvas): default theme is the operator's tuned light look
- `f284391b` feat(canvas): match reference
- `bc37af61` feat(canvas): orchestrator is a floating draggable card, Brain tab renamed o8
- `c59883c8` feat(canvas): orchestrator + brain spawn as one tabbed pane — never orchestrator-alone
- `80ecab93` feat(canvas): unified theme panel
- `30b8d400` feat(canvas): dock orchestrator gets its own light/dark + tint dial

## 2026-06-12

- `bdc8a159` feat(browser-engine): headless installed-Chrome tier
- `e9717a76` feat(canvas): intent bus
- `5f5ccfe4` feat(browser-agent): agents drive the embedded browser
- `8427ea2e` feat(canvas): the everything run
- `04566147` feat(canvas): UNIVERSAL text slider
- `d0f8784c` feat(canvas): chat ink control (Auto/White/Dark) + 100px chat frost + reasoning TIMELINE
- `61a5af77` feat(canvas): glass TONE axis (dark/Ivory light) + floating-chat sliders + live reasoning & image entries
- `f11a9a83` feat(canvas): agent lifecycle lands live
- `83e9b393` feat(canvas): persistence + talkable chat cards + project-grouped repos; drop scratch chat from o8.md card
- `31d88db6` feat(canvas): o8.md card at FULL parity — mounts the real spec pane in glass
- `c5a5bc37` feat(canvas): agents can open pages in the canvas browser via o8:open-browser
- `a519e866` feat(canvas): browser tabs in glass browser cards + review drawer refetch-on-open
- `e92dcb69` feat(canvas): real diff cards with governance row + review drawer; retire center emblem; sessions repo filter
- `8a74b963` feat(canvas): element picker in browser cards — front-end selector tools
- `5261b01a` feat(orchestrator): composer images actually reach the model — both surfaces
- `b4118c1b` feat(canvas): dock gets its own composer + turn cards + drawer-styled term picker
- `87e96f7d` feat(canvas): Pulse is the real agents-working mark — the o8 binary orbit
- `396a9e97` feat(canvas): Pulse rebranded — the o8 dual-orbit mark in faded dither
- `75b68142` feat(canvas): sessions drawer on the left nav + the amber Pulse backdrop
- `52ab8946` feat(canvas): dock tool calls collapse into one live activity line
- `d6df7f86` feat(canvas): operator-picked depth set — wind-dots field + custom shader moods
- `d704c482` feat(canvas): real Paper Shaders depth layers — WebGL, barely moving
- `845a4064` feat(canvas): depth backdrops + opaque popovers + o8.md reads like a page
- `7a347efb` feat(canvas): past sessions open as their own draggable glass boxes
- `2ef42454` feat(canvas): senior pass
- `86b39fad` feat(canvas): photos surface reference-style — image cards, stacks, top-right search
- `391618f2` feat(canvas): Apple-smooth squircle corners + the dock becomes a real panel
- `151af65c` feat(canvas): markdown rendering in the docked chat
- `c08238b3` feat(canvas): talk to the REAL orchestrator from the canvas composer
- `a37b2117` feat(canvas): Finder "Open With → o8" — OS file opens land as canvas file cards
- `260b240d` feat(canvas): file cards
- `d0dc8a13` feat(canvas): spawn reveal easter egg + summoning verbs + edge-rail handles
- `823ee45b` feat(canvas): terminal cards v2
- `cce40936` feat(canvas): real terminals as glass cards + Liquid frost floor
- `008c7c02` feat(canvas): glass tuner docks under the Canvas word + "Save as my default" personal preset
- `b92ac4dd` feat(canvas): Liquid frost dial
- `c9c2f78b` feat(canvas): docked orchestrator, component cards, image drop, liquid-clear background
- `15d7ae37` feat(canvas): background controls

## 2026-06-11

- `d9c61b70` feat(canvas): desktop-clear glass, material presets, kivo summon choreography
- `4e9f7903` feat(canvas): v2 glass slice
- `79d05f46` feat(canvas): fleet-canvas v1
- `478a5339` feat: workers get the Engineering Brain
- `42aff51c` perf(brain): classify/retrieve overlap + semantic answer cache
- `1e787593` feat(brain): sources parity
- `f05d92bf` feat(brain): Ask Brain streams — UI switches to the SSE route
- `10e831e7` feat(brain): spend ledger + daily cap on the OpenRouter tier, 'fastest' composer knob
- `706b5485` perf(brain): warm REPL pool
- `ed09faad` perf(brain): Tier-0 latency pass
- `9714a5ed` feat(composer): orchestrator model switcher in the thinking chip + Ultracode label
- `d17b9ee1` feat: voice agent terminal voice control adds iTerm2

## 2026-06-10

- `0957243e` feat: voice agent speaking-speed control
- `b2c1d9be` perf: voice agent calendar list goes native EventKit
- `789ae1fd` feat: voice agent update verbs
- `640f4ed7` feat: voice agent second-ten-minutes
- `08be05f0` feat: voice agent day-one basics
- `21ce752f` feat: voice agent parity round 3
- `3b6356f5` feat: voice agent terminal brake + keys + new session, o8 recap + usage (parity round 2)
- `5717a1e8` feat: voice agent terminal voice control v1
- `8d513889` feat(mcp): o8_operator_defaults tool + EXTERNAL_AGENTS.md — external-agent control parity
- `ea1b43d4` feat: voice agent controls Apple Music
- `48e742c5` feat: voice agent edit lane works inside o8 + o8-control frontier v1
- `49e6919a` feat: permissions health
- `ac872f1f` feat: voice agent Guide pointer — dwell variant of Points (magic roadmap)
- `538becc6` feat: voice agent "what needs me?"
- `3b7d9108` feat: selection-as-object
- `1068068f` feat: dock chat continuity
- `676b0737` feat: voice agent routing doctrine in the system prompt + presence-layer architecture doc
- `abcf3da0` feat: memory glints + worker-pulse orbit
- `7bc84518` feat: drag-files-into-voice agent
- `2d0e3d2f` feat: voice agent Points
- `6f879579` feat: Option = voice agent agent (both keys), double-tap Option = long question, say -> Option+S
- `e07a5f27` feat: voice agent opens any installed app — fuzzy open_app + list_apps tools

## 2026-06-09

- `6e98fc2f` feat: unit-test harness (vitest + cargo), CI test gate, CLI version armor

## 2026-06-07

- `c9946f2b` feat: catch dashboard mount crashes in preship gate [via-o8]
- `dc7c69b9` feat: add blind second-pass auto-review [via-o8]
- `bd813b4c` feat: one-click "Clean up" button for stale workspace tabs [via-o8]

## 2026-06-06

- `16c3af60` feat: doctor flags runtimes that are installed but not authed
- `268b1f55` feat: keyboard-navigable orchestrator steer queue

## 2026-06-04

- `6db5eec2` feat: open a non-Git folder as a repo

## 2026-06-03

- `dc6f320a` feat: align feedback report embed fields [via-o8]
- `5fb6a701` feat: add settings feedback reports [via-o8]

## 2026-06-02

- `c5109ac3` feat: add webview idle guard lint [via-o8]
- `0fe62259` feat: add preship webview boot gate [via-o8]

## 2026-06-01

- `7740d1ea` feat: add repeatable benchmark suite [via-o8]
- `1653921e` perf: defer cold boot desktop polling [via-o8]
- `d3926877` feat: route literal o8 lookups to grep [via-o8]
- `086a5be1` feat(qa-eval): rigorous 4-way Brain-vs-grep
- `5737bc9e` feat: add strong grep qa eval baseline [via-o8]
- `e3033481` perf: lazy hydrate o8 secondary panes [via-o8]
- `349ed11a` perf: add server timing to hot routes [via-o8]
- `27d4ced8` perf: add client benchmark instrumentation [via-o8]
- `3df36397` perf: add app speed measurement harness [via-o8]
- `39d854fa` feat: mirror agent visual proof onto GitHub PRs via release assets
- `9e6ef82b` feat: live WS artifacts channel so proof strips update in real time
- `e4ab4117` feat: surface agent visual-proof stills on the PR Changes tab
- `b1868a59` feat: o8 packet capture --clip <selector> — frame the proof to the change
- `f62d1bfe` feat: visual proof UI + agent capture awareness ( phase 1 UI)
- `f62b9cfe` feat: visual verification artifacts

## 2026-05-31

- `b7edfac7` feat: enable mic capture for voice dictation + harden orchestrator steer preempt
- `bf633e33` feat: route long worker processes through o8 run by default
- `f745cdfb` feat: operator controls for o8 run — stop + list
- `84d48534` feat: live o8 run strip in the orchestrator chat
- `264296c1` feat: persist managed-runs registry across restarts
- `1ada2173` feat: footer ports 3-bucket view + watch agent runs live
- `a547b8c4` feat: ContextualPanel.attachLiveAgentTerminal — watch o8 run sessions live
- `4636849f` feat: o8 run
- `555ffc9f` feat: tag ports as agent/browser/noise from managed-runs registry
- `108f9263` feat: managed-runs registry + API for o8 run
- `63026902` design(analytics): lead with Autonomy + Governance (01/02), cost below
- `e8435f31` feat(analytics): cost stays king + autonomy & governance on top
- `f3848866` feat(chat): hide the o8-Default casual chat for alpha behind experimentalChat
- `511015e4` design(settings): neutral + royal-blue accent, squircle corners — no orange
- `a75c11e4` feat(dispatch): ship AI provider + agent runtime only
- `3822fd2a` feat(orchestrator): UltraCode swarm = native AI provider sub-agents (workflow) + agent runtime via o8

## 2026-05-30

- `00ad1f3e` perf(webview): kill the transcript-poll socket leak + remove dead git-watch SSE
- `66430ccf` feat(orchestrator): UltraCode swarm tier + inline crew cards; retire Cmd+Shift+O popover
- `adb0c840` feat(dispatch): swarm composer
- `30dd1280` feat(dispatch): allow agent runtime+AI provider mixed swarms (relax force-to-agent runtime gate)
- `7fe54c7c` feat(status): lower long-run orbit threshold 7min → 1min
- `6c0a4d4a` feat(status): wire the dot vocabulary into every agent surface
- `53bfcbe9` feat(agents): deterministic per-agent identicon
- `7d207899` feat(status): orbit working-indicator everywhere — orchestrator + LLM chat
- `a8a6f9a4` feat(status-dots): full motion vocabulary + long-running orbit on agent dots
- `523ac4f7` feat(orchestrator): inline detail drawer for status cards, not a modal
- `a9b9cb02` feat(sidebar): surface spawned agents + archived in every session grouping
- `3e0f87c6` feat: add review last turn scope [via-o8]
- `8f2a3da8` feat(pr-panel): wrap PR diff lines by default
- `9d085716` feat(workspace-header): wheel-scroll + edge-fade for overflowing tab strip
- `7912035f` feat(review): word-wrap diff lines by default

## 2026-05-29

- `4b2c45ad` feat(orchestrator): deliver the Mission-complete card for dispatched missions
- `1263815e` feat(orchestrator): explain what shipped in the mission-complete detail modal
- `af5a77eb` design: extend locked typography to Activity packet card + session strip
- `c7e49e3f` design: bring packet/status/merge cards to the locked typography spec
- `d212bad7` feat(orchestrator): merge + self-heal status cards with click-through detail view
- `3382e2ef` feat(orchestrator): themed animated status card for mission-complete events
- `11168d71` perf: prewarm bundled next server [via-o8]
- `64b62df3` perf: log dashboard boot timing [via-o8]

## 2026-05-28

- `2214d870` feat(agent runtime-composer): wire attached images into the send payload (sub-pass B)
- `7ea9b88b` feat(agent runtime-composer): in-composer footer parity via shared InputButtons (Pass 3)
- `de886d8d` feat(agent runtime-composer): repo / branch / runtime chip row below the composer (Pass 2)
- `27f8072d` feat(agent runtime-composer): image attachment chips above the textarea (Pass 1)
- `306b35c9` design(tabs): V1 continuity transition on the workspace tab strip
- `b772bae8` design(automations): design system pass on AutomationsPage typography
- `484beb89` design(chrome): design system pass on Cmd+K palette typography
- `2be5464f` feat(cmd-k): chat history + directives providers ( subset)
- `23c1a39b` feat(review): rich preview toggle for markdown + images
- `0adf447d` design(chrome): design system pass on keyboard-shortcuts modal + agent-panel top-nav

## 2026-05-27

- `11e677f3` design(session-replay): staggered entrance + ambient hover on lane cards
- `08ee5816` design(timeline): drop inline play + design system pass on timeline + Session Replay page
- `7dd6ca7e` design(typography): repo hover + alert toast + mobile pair to design system spec
- `01e1ef15` design(chrome-button): bespoke per-icon motion — gear spins, phone leans, folder lifts
- `7c3558e1` design(chrome-button): tilt + nudge icon, not scale
- `eaf7f5d0` design(chrome-button): icon micro-motion on hover — match title-bar pattern
- `013817d8` design(o8-panel): repo selector + Ask o8 button get flat hover bg
- `c200ab2f` design(o8-panel): activity filter pills get flat hover bg
- `6a34c6a5` design(globals): kill the global button:hover translateY — flat-button lock
- `3b2a4ceb` design(agent-panel): flat hover chips for header rows — match terminal toggle
- `913f1267` design(empty-state): thinner title + questions above composer
- `6fc7d4b9` design(empty-state): tighten title↔composer gap + repo chip leftmost in chip row
- `55cd8604` feat(update-card): real release summary from free OpenRouter pool
- `cc3154ff` design(layout): center empty state in available space + relocate UpdateCard
- `e012752f` design(bottom-panel): tab pill weight 300 — design system chrome lock
- `007d2db2` feat(bottom-panel): surfaces beyond terminal
- `c2e7d684` feat(settings): drop the 1080 width cap — content fills the full viewport
- `83bf2c3e` feat(settings): full viewport — fixed position instead of column-bound
- `b79c8d79` design(add-repo): design system font pass + simpler copy + Scan hidden until folder picked
- `3aa0753e` design(status-bar): drop pill chrome on solo settings + inbox active
- `daf2567e` design(chat): professional paragraph spacing — gap on every block
- `703c8de2` feat(agent-panel): hover preview = real AgentPanel below traffic lights
- `f400ed81` feat(agent-panel): merge ports + inbox pills into one locked cluster
- `8a44bdfb` feat(agent-panel): outer margin + wider default + hover-preview drop
- `2abcdf71` feat(agent-panel): wire orchestrator worktree pick to bottom status pill
- `1c19903b` feat(agent-panel): simplify composer chips (mode + repo)
- `0d11e0f6` feat(brain): caption images in spec ingest so Engineering Brain can see specs
- `dd034051` design(agent-panel): surface-aware ink + transparency in glass mode
- `8e941c80` design(ui): sweep entire o8 surface to locked design system font spec
- `65f2037e` feat: push mobile live activity updates
- `58bacac5` feat(orchestrator): compose-first empty state + sidebar lifecycle fixes

## 2026-05-26

- `247fd21a` design(agent-panel): Antigravity pass — Iconoir launcher + right-rail alignment
- `326c64f3` feat(drag-drop): native shell 2 bridge for Finder file paths
- `29bde799` feat(projects): SQLite is now source of truth for color + sort + active ( phase 2)
- `13052a91` feat(db): schema v25 + projects ledger JSON→SQLite migration ( phase 1)
- `8d8d8f81` feat(compactor): weekly digest cron + delivery wrapper ( phase 2)
- `ead3ee87` feat(compactor): --digest-to flag writes markdown summary

## 2026-05-25

- `b7a8474f` feat: tray dropdown lists awaiting-review packets
- `3fb016ef` feat: directive surfacing in review + agent runtime-only worker enum
- `33314ce2` feat: inline TurnSummaryCard + ChatActionCard for orchestrator turns
- `1273589c` design: design system theming pass
- `82c3ac5c` feat: emit mobile activity preview urls
- `1ed67ffb` feat: route orchestrator ws events by thread
- `d88d1fe3` feat: broadcast orchestrator thread sync events
- `43a127e6` feat: add mobile orchestrator thread creation
- `7e7ee367` feat: add steer packet MCP tool [via-o8]
- `db166d26` feat(orchestrator): layered escalation on merge-tsc failure

## 2026-05-24

- `55959cc0` perf(brain): soften composer tightening from — restore factual accuracy
- `c8d9f1bd` feat(orchestrator): parallel mission queries via SQLite registry
- `3592ffe8` feat(brain): three-way memory-substrate eval harness
- `7b214443` perf(brain): warm OpenRouter pool at boot to kill cold-start classifier
- `d5f357e6` design(scratch): premium dot + cost-hint legend on O8ScratchChat composer
- `c37dcb6d` perf(brain): split H2 spec chunks on H3 when ≥3 kids or >4KB
- `37f08c3b` perf(brain): classifier — OpenRouter tier 1 + 60s cache
- `f59f5527` feat(brain): Ask Brain composer button in O8ScratchChat
- `94940596` feat(brain): spec ingestion at repo connect

## 2026-05-23

- `9fd3829b` design(panel): cascade flat-button language to scratch chat + inbox + activity
- `c9241c0f` design(panel): cascade flat-button language to O8 + PR panel surfaces
- `a378ba42` design(spec): lock flat-button language in DESIGN.md + flatten shared primitives
- `8b98f35e` design(panel): flatten all remaining header buttons to match HeaderIconPill
- `e0f44d22` design(panel): generic HeaderIconPill — flat icon pill for header strips
- `76c34fad` design(panel): flat toggle pill, baseline-matched across sidebar open/closed
- `9793dd82` feat(panel): toggle pill matches HeaderPill language + framer-motion variants + traffic lights y=22
- `0063cdf1` feat(panel): floating-card pattern for left column
- `c4d4a78d` feat(left-panel): dainty 1px divider between left panel and workspace
- `007db56d` feat(left-panel): hide Control tab from project-focus drawer
- `ee78c8b4` feat: use git diff review icon [via-o8]
- `c7d6d2a3` feat: auto-widen o8.md panel tab
- `915fab1b` perf: short-TTL cache on repo registry readStore (5s)
- `43a5b44d` feat: stamp mergedClean on session_outcomes when a merge lands
- `5d4dcb71` perf: stale-while-revalidate cache on getRepoReadiness (Phase 5)
- `9475fb3f` feat: directive proposals close the loop in-app — Accept writes the file (Phase 3)
- `8da326d9` feat: persist packet completions to session_outcomes ledger (Phase 2 of)

## 2026-05-22

- `115fc60c` feat: pre-launch typecheck gate on freshly-created worktrees
- `c09ec187` feat: right-click an o8.md inline image to add it to the chat
- `6240e477` feat: o8.md inline images render consecutive lines as a gallery row
- `25ea3a97` feat: render inline images in o8.md (small thumbnails + lightbox)
- `5bfe9d15` feat: inline image authoring in o8.md (drop/paste → o8-assets)
- `c3a38bcc` feat: o8_view_scroll + o8_view_press_key webview tools (pre-ship Phase 4)
- `c0112245` feat: o8 packet diff/commit + o8_packet_diff MCP tool (pre-ship Phase 4)
- `594fae76` perf: parallelize packet-info's events + scope fetches (pre-ship Phase 3)
- `f9c59721` perf: token-bound the o8 CLI command outputs (pre-ship Phase 2b)
- `6377d257` perf: token-bound the MCP + webview tool outputs (pre-ship Phase 2a)
- `9fbce96d` feat: wide control-room mode

## 2026-05-21

- `2b7af8b3` feat: shared project-scoped repo selector across Workspace + Activity
- `68acb8d6` feat: split project select from open-control-room (row click selects, chevron opens control room)
- `2f0ec4de` feat: switching the active project re-points the whole app (O8 panel + new orchestrator) to its primary repo
- `249e2df1` feat: lone pool repos surface as switchable single-repo projects
- `0073c610` feat: o8.md review notes fade in on the rail (framer-motion enter, new notes only)
- `5a149d05` feat: o8.md review runs headless one-shot, no orchestrator chat turn
- `c3cbd853` feat: o8.md note color - add black + neutral swatches alongside the hue picker
- `d4d54b4b` feat: o8.md note settings - hue chooser drawer + desaturated in-note buttons
- `bef27b94` feat: o8.md notes reserve prose room only-when-needed via block spacers (no anchor drift)
- `e3df5248` feat: tighten o8.md review prompt - only-when-real, read-first, commit-aware
- `d599fcff` feat: o8.md click-first review button + reply lands at thread bottom
- `585ead8f` perf: debounce o8.md rail recompute + comment resolve/reply
- `a1e24aac` feat: o8.md panel now uses the CodeMirror review editor (the swap)
- `d5a3c895` feat: interactive task checkboxes in the o8.md editor
- `dff0e94f` feat: o8.md margin-note rail + accept/dismiss in the CM6 editor
- `1dac0e5b` feat: wire the o8.md suggest verb across API + CLI + MCP
- `3391a485` feat: surface operator o8.md threads in dispatch context (phase 3)
- `3d27842f` feat: external AI provider can read + annotate o8.md via CLI + MCP (phase 2)
- `ce95e217` feat: theme-align proposed directives + unread hierarchy
- `c2803c7d` feat: power-user chrome keyboard shortcuts
- `f87a0667` feat: keyboard shortcuts reference overlay (⌘/ or ?)
- `3cb5f366` feat: popover menus always mounted (display toggle) for agent enumeration
- `2690c91a` feat: tab icon morphs to close-X on hover + disambiguate split aria-labels

## 2026-05-20

- `b28a398b` feat: group picker is icon-only + sits inline with first group label
- `82c6b3b8` feat: chat-list group-by picker (Repo / Date / Flat) + uppercase headers
- `5d2d545b` feat: shimmer placeholder during thread restore (no more empty-state flash)
- `6537453f` feat: pre-set tab.label from saved orchestrator title at tab creation
- `1a96169e` feat: GC orphan empty thread files during list calls
- `02a3a9a3` feat: persist last-active orchestrator thread across reloads
- `7cd78e95` feat: inline rename for chat titles in column header
- `946aaaad` feat: per-pane ▶ play + one × close, all in split header
- `42550b41` feat: side-by-side header pills for splits with center divider
- `1ce89260` feat: merge-state preview cycler in status bar
- `fc79c050` feat: terminal toggle moves to status bar next to branch label
- `3c987ee2` feat: terminal toggle moves to bottom-center floating chip
- `cb62afb7` feat: inline split-pane controls (▶ + ×) + cap at 1 split
- `70ff5fa7` feat: kill the lower per-workspace TabBar — pills are the only tab UI
- `d60af06b` feat: top header morphs into agent runtime-style pill strip when 2+ tabs
- `bb39d311` feat: ▶ play button in global header when single workspace (trial)
- `3c9308ac` feat: hide lower TabBar in single workspace mode
- `f34f09b4` feat: title-bar … menu (rename/archive/share) + tighten 44→36
- `5d9a6be6` feat: chat title moves UP into the column header (agent runtime pattern)
- `40e7758a` feat: chat name lives IN the workspace header (step 1)
- `0e5e83e1` feat: top tab bar goes flat
- `746442d5` feat: top tab bar is now bespoke — width-gated, spawned-only
- `f92572d9` feat: unified packet-state color scheme for top tabs + left rail
- `fde61f75` feat: archived agent sessions inline under each repo in left rail
- `0b0d04c4` feat: orchestrator history merges into left rail (Chats + Agents tabs)
- `9f4968aa` feat: orchestrator composer trim — drop enhance + copy, compact send

## 2026-05-19

- `ad27b350` feat: Automations scheduler
- `9c7f9fd7` feat: Automations polish
- `8b28ba7a` feat: Automations nav entry in left rail (agent runtime borrow)
- `b0234ce5` feat: Automations
- `4ed207e5` feat: scratchpad falls back to workspace-wide diff when no file is selected
- `5bb5471a` feat: ⌘⏎ steer queue in orchestrator + chat composer
- `eeb664f0` feat: timeline off by default
- `5156a2cd` feat: Shell layout
- `ce25a5ef` feat: Shell layout
- `5271186b` feat: Shell layout — per-column header strip components
- `81bed0c8` feat: add agent runtime-only task pool routing
- `0205f12e` feat: Review surface
- `36c4e0da` feat: Review surface — repo selector in the header
- `f028dce5` feat: Review surface — untracked files render as all-added
- `7b318f0f` feat: Review surface — word diffs + hide-whitespace toggles
- `a73e44a2` feat: Review surface — Commit / Push / Open PR toolbar actions
- `447255c4` feat: add project task control plane
- `dfeadfa3` feat: Review surface
- `09d0f5f8` feat: Review surface
- `fba40ed2` feat: agent runtime-style Review surface

## 2026-05-18

- `a2e94595` feat: agent runtime orchestrator — governed gateway + per-request agent
- `4332b576` feat: mobile agent runtime orchestrator surface — backend-tagged threads + contract
- `0a36f675` feat: agent runtime orchestrator backend + per-request backend selection

## 2026-05-17

- `7a009550` feat: mobile activity feed + orchestrator packets API routes

## 2026-05-16

- `686d2f55` feat: desktop QR pairing emitter for the o8 mobile app

## 2026-05-15

- `8fc4be0e` feat: add AI provider billing verification smoke
- `21b2fadf` feat: add agent runtime interactive session [via-o8]
- `ebf1be44` feat: render agent runtime chat events [via-o8]
- `67c848d3` feat: extract AI provider-code stream-json parser into a module
- `8d9f5aaf` feat: AI provider-code composer model pill + plan/bypass toggles
- `86628e16` feat: restore AI provider-code as interactive chat-tab runtime

## 2026-05-14

- `7d5b3810` feat: github intake dual-path
- `8e4ba530` feat: promote agent runtime CLI to effective tier 1 in Q&A cascade when in-app orchestrator is off (epic child 4)
- `d0fb7ac9` feat: add agent runtime-orchestrator-session + wire auto-review dual-path (epic child 2)
- `500ee576` feat: gate AI provider-billed paths behind in-app orchestrator toggle
- `2596663c` feat(cli): phase 3 polish + native shell bundling + npm-publish prep

## 2026-05-13

- `eb5f7ed6` feat: modernize workspace runtime reconnect banner
- `8faa025f` feat: modernize stale-gateway alert in AgentPanel
- `c2ede719` feat: branch details launcher + modernized connection banner + chrome polish
- `37e786bc` feat: add packet mission tail stream [via-o8]
- `d9fbe1a3` feat: add o8 observation proposals [via-o8]
- `3e960719` feat: add lane touch lookup
- `4fee97de` feat: add packet agent report events [via-o8]
- `3ecc639b` feat: add packet scope surface [via-o8]
- `8ed0d4b9` feat: /api/panel/status returns server version for o8 CLI
- `e420269d` feat(cli): scaffold Phase 1 of the o8 CLI (epic)

## 2026-05-12

- `1b3d00f6` perf: symlink node_modules into worktrees instead of cp -cR
- `469f8b98` feat: add MCP repo+project bootstrap tools — wedge unlock
- `6c0db544` feat: add MCP repo+project bootstrap tools — wedge unlock
- `14b1de09` feat: add MCP repo+project bootstrap tools — wedge unlock [via-o8]
- `9adee9c9` feat: add MCP repo+project bootstrap tools — wedge unlock
- `204f9d93` feat: add MCP repo bootstrap tools
- `6cd1b83c` feat: default to light theme + solid chrome on fresh install [via-o8]
- `838e470b` feat: default to light theme + solid chrome on fresh install

## 2026-05-11

- `45580677` feat: add typed webview latch

## 2026-05-10

- `716fc4ae` feat(projects): seed scope:project directive + projects field doc [via-o8]
- `4936442d` feat(projects): seed scope:project directive + projects field doc
- `989b9565` feat(projects): seed scope:project directive + projects field doc
- `72dfdb13` feat(projects): seed scope:project directive + document projects field
- `a4d4364c` feat: timeline reads 24h of session history (tail 500 → 15000) + finer cells
- `538e951d` feat: add mcp__o8__rerun_with_feedback tool
- `f51f6644` feat: scope orchestrator memory by project [via-o8]
- `2e08969e` feat: render chat tool calls as chips [via-o8]

## 2026-05-09

- `00c02f53` feat: vocabulary cleanup
- `1004eb6b` feat: live HTML rendering — .html viewer + richer o8.md renderer
- `ca257c60` feat: one-click install of o8 MCP into Hermes Agent + agent runtime

## 2026-05-08

- `634ba8b7` feat: voice agent-style push-to-talk dictation
- `569abdd3` feat: competing product-style PR panel + segmented context popover
- `996f08ee` feat: add macOS APFS workspace isolation
- `71b871bb` feat: agents archive drawer shows every concluded packet
- `08e3bc50` feat: unified project panel + agent / timeline polish
- `f865cd45` feat: add slash orchestration routing
- `d0c7a0e7` feat: pulse the rightmost timeline cell, drop drilldown trigger
- `57d0945b` feat: rolling 24h timeline + error surfacing + settings toggle
- `c42b0e28` feat: rewrite SessionTimeline as Tracker strip + redesign hover card

## 2026-05-06

- `c916f4c6` feat: flatten new-tab drawer to Orchestrator / Chat / Terminal
- `9df37a63` feat: orchestrator mode chip + slash-command routing
- `85c56780` feat: two-axis theme system (palette × surface) + reduce-transparency toggle
- `d05cb944` feat: skiper-style motion on search + browser titlebar buttons
- `8a101fec` feat: skiper-style motion on titlebar left buttons
- `c1300d2e` feat: align titlebar left buttons with right side; agents glows orange
- `10566275` feat: empty project gets a primary "Add a repo" + quick-pick from other projects
- `5fb5aec6` feat(palette): switch projects + move repo from Cmd+K
- `927fd791` feat: project colors + drag-drop repos onto dots + empty-project hint
- `9f777b0d` feat: rename / delete projects + move repos between them
- `3b8a515d` feat: status bar centers under the workspace + cluster matches chrome chip shape
- `96a397b9` feat: status bar centers branch + adds contextual merge action pill
- `3b8465fe` feat: O8 right panel opens on the Pulse tab by default
- `9afd44b1` feat: projects scope the left panel with a bottom-bar dot switcher
- `5adb6303` feat: hover × on each spawned agent row to dismiss it from the panel
- `da88515f` feat: single-runtime chat lifecycle + 3-word tab labels everywhere
- `3493d0f5` feat: breadcrumb minimizes to filename only by default
- `a6923cd4` feat: Changes count gains a cool-to-warm urgency badge
- `a91fad63` feat: move repo selector into the changes rail to free file path space
- `e4249bfe` feat: chat tabs adopt 3-word summary from latest user message
- `9b917c5e` feat: tab strip uses theme-tinted glass instead of raw vibrancy
- `3ad84dcd` feat: round workspace top corners and inset tab cluster
- `b3914738` feat: tab strip becomes vibrancy-passthrough glass
- `ed105ef7` feat: hide thinking chooser in chat tabs and rename Assistant row to Chat
- `4ad3e3df` feat: chat-mode chooser spawns dedicated tabs with tool-wired chat
- `5e66bbb4` feat: align orchestrator empty state
- `d5bb87bb` feat: refine o8 settings and analytics ui
- `80b70540` feat: refine o8 activity review surfaces

## 2026-05-05

- `ac3775fd` feat: redesign o8 pulse briefing
- `4a5bd0ea` feat: refine o8 workspace panel

## 2026-05-03

- `ea76d91f` feat(workspace-tab): green tab marker when packet status === released
- `d5141ca1` feat(workspace-chat): inline status banner at bottom of dispatched chat
- `b891abe4` feat(o8-panel): consolidate Mission rail into Activity tab
- `006255e9` feat(o8-panel): packets render in Activity timeline behind opt-in flag
- `5230aa7e` feat(orchestrator): NEEDS YOU click pops O8 Workspace pinned to the lane's worktree
- `a0959d31` feat(orchestrator): per-section click routing for Recent Work rows
- `cb3fd025` feat(orchestrator): status-anchored Recent Work — Needs you / In flight / Done today
- `e77f8e11` feat(o8-panel): path-lens chip on Workspace tab — shows main vs worktree at a glance
- `2a24df8a` feat: replace o8 file tabs with workspace
- `ca7c07c0` feat: add o8 workspace pane components

## 2026-05-02

- `4fa127f1` feat(o8-panel): restore Pulse tab — live fleet temperature surface
- `3467c7e3` feat(orchestrator): composer footer threads/copy/new + thinking <details> popover
- `826aebfb` feat: stream orchestrator chat from gateway
- `4cff76cc` feat: add clerk gated chat route
- `44f8d4a1` feat: add chat gateway server helpers
- `eeb26320` feat: route orchestrator chat mode locally
- `037c1b1a` feat: add chat mode card
- `571def5e` feat: add orchestrator chat model picker
- `9d3c80ef` feat(mcp): wait_for_mission_ready
- `13a54d4f` feat(orchestrator): wire useFileDrop into ComposerArea

## 2026-05-01

- `454ac82a` feat: auto-release merged review packets
- `fcf185fd` feat: tighten supervisor inbox signal
- `3cdd88c8` feat(browser-button): hover preview iframe of the active browser tab
- `0d956441` feat(titlebar): promote Browser to top header slot
- `27cbe27e` feat(left-panel): collapse branch + agent rows into one work-unit line
- `7be65aec` feat(left-panel): repo focus expands the column inline, no overlay
- `331da228` feat(chrome): move update notice to footer pill, drop top-right toast
- `ac61422e` feat(repo-focus): back-arrow polish + ESC-to-close
- `b4151544` feat: add o8 diff and spec tabs
- `43af588c` feat: add ambient right panel
- `59afbb2b` feat(repo-focus): Spec + Files tabs + first-class CLI usage strip
- `dfc8dd09` feat(ui): repo-focused left-panel mode with Agents/Context/Mission tabs
- `f633e3a4` feat(native shell): O8_DEV_FRONTEND_URL override for hot-reload prod loop [via-o8]
- `9896c8b0` feat(native shell): O8_DEV_FRONTEND_URL override for hot-reload prod loop [via-o8]
- `6448c9e0` feat(native shell): O8_DEV_FRONTEND_URL override for hot-reload prod loop [via-o8]
- `cb47d16c` feat: support dev frontend override in native shell

## 2026-04-30

- `49cbe74e` feat(ui): hide agent runtime pickers behind experimentalagent runtime + thicker tabs
- `56ec188a` feat(operator): default thinkingEffort to high (was adaptive)
- `6312de38` feat(runtime): drop agent runtime from default dispatch picker
- `c4621d6b` feat(brain): fs.watch on docs — incremental re-distill
- `a63506a7` feat(brain): embeddings column + hybrid retrieval
- `71e83c1b` feat(brain): qa-eval regression dashboard
- `087c1470` feat(brain): post-commit hook feeds facts substrate
- `047dd212` feat(ui): /ask quick action in chat composer
- `be7101a9` feat(brain): in-process compactor scheduler
- `dc9c923c` feat(brain): bring-your-own OpenRouter / AI provider key surface
- `0b1ce74a` feat(ui): Recall Card — top-N facts ambient surface
- `1d9be768` feat(qa): configurable Class A composer model
- `a29a89c7` feat(qa): Phase 2b
- `a0d9b4bf` feat(qa): source-update detection + source-of-truth hierarchy
- `11e58c69` feat(qa): fact compactor
- `e626cf3b` feat(qa): Phase 2a
- `b1576227` feat(indexer): heuristic noise pre-filter at enqueue ( north star follow-up)
- `0a87448f` feat(indexer): parallel worker with O8_INDEXER_CONCURRENCY ( north star follow-up)
- `c510cf31` feat(qa): Engineering Brain Indexer worker
- `5b24357f` feat(qa): pin top-6 facts above other retrieval rows ( north star)
- `afdd8aad` feat(qa): smoke:qa fast eval (6 cases, <2min) replaces 30-case heavy eval ( north star)
- `a3918673` feat(qa): facts schema v17 + retriever foundation ( north star)
- `51fa948d` feat(qa): docs_fts ingestion for project rules / README / AGENTS.md ( path-to-70 phase 1.7-)
- `6b1b29cb` feat(qa): github_comments_fts ingestion ( path-to-70 phase 1.7-)
- `a74ac003` feat(qa): rebench OpenRouter primary with credited key ( path-to-70 phase 1.7.1)
- `8370982c` feat(qa): lock OpenRouter primary to grok-4.1-fast from empirical bake-off
- `f2c425fa` feat(qa): project + project_repo retrieval in sqlRetriever ( path-to-70 phase 1.4)

## 2026-04-29

- `e871c60d` feat(qa): 30-question eval set + runner skeleton (epic sub-3 wave A)
- `8d267f73` feat(qa): Schema v14 + FTS5 + retrievers (epic sub-1)
- `76ae84cd` feat(qa): Ask Anything UI scaffold + mock stream (epic sub-4)
- `2dbff900` feat(projects): AI Stage 2 LLM project suggestions + Confident/Plausible UI (epic wave 2)
- `9241d8d6` feat(projects): Settings → Projects UI with manual linking + GitHub-org auto-suggest (epic wave 2)
- `4a15cc84` feat(projects): Recall Card Project pulse section (epic wave 2)
- `e33c6d43` feat(projects): scope:project directives + cross-repo proposer rewrite (epic wave 1)
- `2209e5fa` feat(projects): schema v13 + storage + API + MCP tools (epic wave 1)
- `5efe6920` feat(projects): AI semantics Stage 1 fingerprint extractor (epic wave 1)
- `7129ebf3` feat: agent-proposed spec approval flow
- `2ccc5395` feat(diagnostics): extend demo runner with mission/settings/context-graph steps (closes)
- `0d99a7e6` feat(diagnostics): in-app demo-sequence runner (closes)
- `34fe288a` feat(panel): loop-state writer endpoint + shell helper (closes)
- `3d45e2b7` feat(settings): in-app loop status widget — cron + lanes + recent merges (closes)
- `473622e3` feat(mcp): o8_view_console_errors + o8_view_active_route — close loop observability gaps (closes)
- `1a7ad887` feat(o8): cross-repo learning
- `8ebe02c7` feat(o8): per-runtime outcome telemetry → dispatch routing recommendation (closes)
- `1b4cf0db` feat(o8): auto-directive proposer
- `8b2a0575` feat(o8): temporal validity windows on session_outcomes — auto-decay 30d (closes)
- `3aa4f0a6` feat(mobile): Browser tab gates the chat+iframe split (closes)
- `1770971e` feat(mobile): wire url-push listener into split shell + DevHostFrame handler
- `922aa03f` feat(mobile): long-press port chip pushes URL to connected phone over WS (closes)
- `49402e83` feat(mobile): wire DevHostFrame into MobileSplitShell right pane
- `3d3a2786` feat(mobile): landscape split-view shell
- `ff002edf` feat(mobile): DevHostFrame iframe with URL bar + LAN host discovery (closes)
- `728a9780` feat(context-engine): editable packet spec.md feeds live orchestrator context (closes)
- `35a0e624` feat(mission-control): status-grouped lanes (closes)
- `fbef0b2b` feat(orchestrator): suggested-reply chips under Coordinator messages
- `ec1e1c29` feat(o8): living specs
- `4ad3b66f` feat(context-engine): /context-graph test page — 3-column flow viz (closes)
- `7e90ef70` feat(native shell): dispatch popover redesign

## 2026-04-28

- `ceacf0a2` feat(o8): demo polish
- `16e61b13` feat(o8): inject <context> block into packet bodies on dispatch (closes)
- `6569c41f` feat(orchestrator): context recall card 3-row hero (closes)
- `e80e390e` feat(o8): auto-index registered repos at boot via codebase-memory-mcp (closes)
- `5e4da356` feat(mcp): register codebase-memory-mcp in .mcp.json + setup generator (closes)
- `70415256` feat(mcp): runtime-download codebase-memory-mcp on first launch (closes)
- `02ba3afb` feat(native shell): global-shortcut + notification + menu bar tray (closes)
- `5cb5aff7` feat(orchestrator): packet review card 3-pane (closes)
- `4662dc3a` perf(dashboard): defer non-critical work off the bootstrap path (closes)
- `ceb36160` feat(workspaces): hover-reveal trash + confirm-strip + git branch -D
- `95699660` feat(desktop): auto-hide merged + agent worktrees in Workspaces sidebar + hover-prune
- `f1f2dc4f` perf(desktop): memoize ThoughtsChatPanel message bubbles
- `0a6a2eb7` perf(desktop): widen / remove short polling intervals
- `6ef3137f` perf(desktop): reduce SessionVisualizer render churn
- `a73de9fd` feat(desktop): hit-zone audit — Settings page (44pt minimum)
- `50c43a83` feat(desktop): hit-zone audit
- `f0131483` feat(desktop): hit-zone audit — Approval surfaces (44pt minimum)
- `5284a7ef` feat(desktop): multi-window / split-pane orchestrator transcripts
- `fd0d1995` feat(orchestrator): bump AI provider defaultModel to AI provider-3.1-pro
- `c6f5312d` feat(desktop): Cmd+K command palette across the app
- `dff95375` feat(desktop): one-click rerun-with-feedback on rejected reviews
- `733be178` feat(desktop): inline diff viewer in workspace center
- `08c71472` feat(desktop): steer-in-flight composer on active agent transcripts
- `a35ddc6b` feat(orchestrator): drop AI provider-code from dispatch picker
- `1c29a8d2` feat(mobile): offline send queue + replay on reconnect
- `4f9ea878` feat(mobile): push notifications + Web Push infra
- `14697545` feat(mobile): haptic feedback
- `c3a146bd` feat(mobile): pull-to-refresh across mobile surfaces
- `85b0877a` feat(mobile): universal search ('/') across chats/threads/activity
- `b88d5aad` feat(mobile): markdown + code blocks in agent transcripts
- `6025e7a5` feat(mobile): swipe-to-approve/reject gestures on approvals
- `f361526c` feat(mobile): inline diff viewer for approvals + PR cards + agent transcripts
- `41039d1d` feat(mobile): inline diff viewer for approvals + PR cards + agent transcripts
- `05d3b748` feat(mobile): inline diff viewer for approvals + PR cards + agent transcripts
- `a8bda15c` feat(mobile): inline diff viewer for approvals + PR cards + agent transcripts [via-o8]
- `3f4a5108` design(mobile): dark mode transcript bubble polish [via-o8]
- `c3db5e52` feat(mobile): voice input via long-press to dictate [via-o8]
- `dcb0e65c` feat(mobile): voice input via long-press to dictate

## 2026-04-27

- `82e3b659` feat(mobile): read-only agent transcript sheet (v1 mobile model)
- `17b36f53` feat(mobile): orchestrator brain chip + thread card opacity fix
- `51b31d2a` feat(mobile): rename Chats→Assistant, action-weight order, sidebar subtitles, orchestrator New button
- `9ec9e984` feat(release): post-bundle sign + notarize for nested Node native modules
- `acfea9ca` feat(release): wire Apple Developer ID signing + notarization
- `a1acea5e` design(orchestrator): match Assistant chat breathing room and typography
- `8d5340d9` design(mobile): unify standard topbar across all 5 new tabs
- `4990ff7b` design(mobile): scroll-fade masks on chat list/transcript/orchestrator/approvals scroll surfaces
- `8cbdc943` feat(mobile): profile button + Settings sheet under drawer footer
- `591763c8` feat(mobile): wire 5 unwired tabs (agents/issues/activity/costs/orchestrator)
- `bd36d79f` design(mobile): filter pills, day groupings, FAB, HIG touch-target sweep

## 2026-04-25

- `155466e9` feat(mobile): orchestrator tool bubble flips to done with output preview
- `87bf1e0f` feat(mobile): bind bundled Next server to 0.0.0.0 for LAN access
- `92118945` feat(mobile): orchestrator composer wiring polish
- `34e41fb0` feat(mobile): orchestrator tab — thread strip + transcript + composer
- `864ab76f` feat(settings): factory reset button in Diagnostics tab
- `9d1ecb14` feat(mobile): orchestrator WS hook with transcript buffer
- `29f28cb2` feat(mobile): orchestrator threads list API + types

## 2026-04-23

- `2fde9ae0` feat(onboarding): add default dispatch runtime step to first-run wizard
- `12da6239` feat(v1): gate agent runtime behind experimentalagent runtime flag

## 2026-04-21

- `5016b0f4` feat(AI provider): model fallback cascade on quota + in-chat pill
- `81e4318e` feat(agent-panel): Orchestrator + Assistant rows with accurate shimmer
- `1ca03fe8` feat(hotkeys): Cmd+1-9 jump, Cmd+Opt+Arrow cycle, Cmd+W close + tab flash
- `06944a45` perf: kill AgentTilePane polling + fleet invalidate route + urgent WS (Packet D,)
- `9ab80a27` perf: rewire WorkspaceChatPane to transcript store (Packet B,)
- `06497a58` design(AI provider-code-transcript): emit structured toolCalls for agent runtime-parity italic dropdowns
- `7f0ad44c` perf: visibility swap + render memo on tab panes ( Packet C)
- `6f5b095e` perf: client transcript store + workspace bootstrap ( Packet A)
- `8be8a44d` design(chat): collapsible PacketHeaderCard replaces giant packet prompt
- `82b53bd2` design(branch-hover): Rams-style status rows matching repo hover
- `678d3222` design(branch-hover): match repo-hover theme — solid panel, no glass
- `e0ec20e2` feat(workspace): wire AI provider + agent runtime chat-pane transcript + steering
- `139b1b5c` design: hide SessionTimeline + punchier shimmer + strip branch tooltip
- `7dbef8f1` design: o8 boot splash + shimmer on active agent panel label

## 2026-04-20

- `5b0154af` feat(workspace): wire AI provider + agent runtime into CLI Session live-tail pane
- `9bd62916` feat(orchestrator): expand OrchestratorRuntime union to four runtimes + capability map
- `a03bd54f` feat(runtimes): add first-class AI provider CLI adapter
- `04568bc0` feat(runtimes): add first-class agent runtime CLI adapter
- `b96efdc3` design(chrome): shimmer sweep on active workspace tab label
- `655b4330` feat(runtimes): add turn-dispatcher primitive (no callers yet)

## 2026-04-19

- `fd1966cb` design(theme): unify midnight chrome glass + solid page surface on Settings/Analytics + inbox pill
- `2ead5ba2` design(settings): RamsButton pill sweep + CornerBrackets selection + SectionLabel brightness
- `d016af0c` design(chrome): Rams palette, remove alerts tray, quiet timeline strip, tighten Session Replay
- `cb6295da` feat(ui): reload banner in ThoughtsChatPanel [via-o8]
- `345d7be9` feat(orchestrator): graceful reload endpoint with transcript resume [via-o8]
- `ac7cdf95` feat(mcp-register): add o8.register_mcp tool for conversational MCP install [via-o8]
- `eacbb066` feat(mcp): adaptive probe timeout + npx prewarm [via-o8]
- `66ae6b03` feat(mcp): test connection button with live tools probe [via-o8]
- `4df9dddf` feat(mcp): paste-JSON config input [via-o8]
- `2e395813` design(settings): acronym casing — MCP + configuration [via-o8]
- `868d406e` design(settings): visual polish sweep — spacing, acronyms, typography [via-o8]
- `cf6c24bc` design(analytics): Rams pass [via-o8]
- `dcd63f4e` design(settings): Rams pass on Settings shell + tab bar [via-o8]
- `8715692f` design(settings): Rams pass on About tab [via-o8]
- `981faa0f` design(settings): Rams pass on Diagnostics tab [via-o8]
- `3ab13a34` design(settings): Rams pass on Appearance tab [via-o8]
- `c4528d54` design(settings): Rams pass on Cloud Workers tab [via-o8]
- `7918f9f5` design(settings): Rams pass on Workers tab [via-o8]
- `73c75c95` design(settings): Rams pass on Dispatch tab [via-o8]
- `2a43dd83` design(settings): Rams pass on MCP tab [via-o8]
- `66995528` design(settings): Rams pass on configuration tab [via-o8]
- `b9af994f` design(settings): Rams pass on Connectors tab [via-o8]
- `db8a12bf` design(settings): add TabBreadcrumb + TabHeading + FieldLabel Rams primitives [via-o8]
- `fdd8ca63` feat(agent-hover): diff + last-tool + elapsed on hover [via-o8]
- `2a6314f8` feat(security): promote configuration encryption to macOS Keychain-backed master key
- `21d53cef` feat(delegate): accept baseBranch param for fix dispatches against feature branches [via-o8]
- `3414f9ec` feat(orchestrator): edge-case surfacer at dispatch-prep time [via-o8]
- `f658c6e7` feat(governance): autonomous post-merge decomposition pipeline [via-o8]
- `9dea2fff` feat(chat): streaming DiffCard with partial-apply and interrupt [via-o8]
- `7bd4e4c2` feat(runtime): cloud adapter scaffolding with outbound-only worker protocol [via-o8]
- `2a054521` feat(orchestrator): render ComparisonCard + fan-out cost warning in mission panel [via-o8]
- `353e90d0` feat(orchestrator): guard PacketCard against comparison-group packets [via-o8]
- `3e555ab2` feat(orchestrator): ComparisonCard mission-panel UI for best-of-n groups [via-o8]
- `7e295cfd` feat(orchestrator): comparison-meta API route for best-of-n meta-agent [via-o8]
- `205366cb` feat(orchestrator): add global AgentsSidebar for all-origin agent visibility
- `924e50d7` feat(orchestrator): external MCP servers as orchestrator context sources
- `67d7c3a4` feat(agent runtime): eager-parse auth.json to expose authed providers as picker sub-rows
- `8dc7372f` feat(worktree): force managed mode for AI provider-code lanes so pre-launch rebase runs [via-o8]
- `c3eefd79` feat(orchestrator): wire packet issueUrl into PacketActionStrip open action [via-o8]
- `5b95e058` feat(composer): wire stop pill to real interrupt channel [via-o8]
- `99dbd625` feat(mcp-agent): o8_merge_preview tool + structured gate verdict on workflow action
- `2cc9859f` feat(orchestrator): packet card details popover [via-o8]
- `9d53719e` feat(mcp-agent): o8_packet_transcript MCP tool paginates packet agent runtime events [via-o8]
- `9ccb7934` feat(orchestrator): Cmd+K quick-action palette in OrchestratorTab

## 2026-04-18

- `1d3faf6d` feat(mcp-agent): o8_lane_events MCP tool long-polls workflow transition [via-o8]
- `5a8234ee` feat(mcp-agent): o8_review_state MCP tool [via-o8]
- `70007a08` feat(orchestrator): packet card action strip — retry / reset / open / copy [via-o8]
- `616f36ec` feat(orchestrator): history row actions — pin / rename / export / delete [via-o8]
- `9190c5f6` feat(orchestrator): synchronous worktree cleanup across all merge paths [via-o8]
- `5d332ae5` feat(orchestrator): history sidebar search with first-message match [via-o8]
- `8add62bb` feat(composer): Rams-style send pill with idle / armed / working states [via-o8]
- `0b0ef5e3` feat(orchestrator): packet file-reference validator + emoji fix
- `3c2e25cf` feat(dispatch): learned-rules promotion/demotion cron
- `2da71e62` feat(orchestrator): inject learned rules into packet prompt
- `7fd1e0c6` feat(orchestrator): preserve pinned turns during auto-compact
- `75d92b96` feat: archive orchestrator threads on clear
- `fd62f14f` feat(orchestrator): finish remaining slash commands
- `eed66d8c` feat: usage.jsonl dispatch instrumentation for agent runtime + agent runtime runtimes [via-o8]
- `00591698` feat: wire Thoughts operator-defaults into panel [via-o8]
- `8129e2ec` feat: default operator settings [via-o8]
- `878b56b7` design(agent-chat): unify agent runtime + agent runtime composer with orchestrator aesthetic
- `5de4e802` feat(orchestrator): context inspector side panel with click-to-evict
- `f396942c` feat(worktree): stale local ref check + fetch_unreachable supervisor inbox kind so offline launches don't revert upstream [via-o8]
- `1053704e` feat(worktree): thread packetId through RuntimeLaunchRequest so rebase-conflict inbox rows deep-link to the packet [via-o8]
- `ab0c1c76` design(orchestrator): ThinkingChip matches ContextMeter pill aesthetic [via-o8]
- `12e7dcaf` design(governance): move Supervisor Inbox from lingering /dashboard/inbox route into the O8 right panel as a proper tab [via-o8]
- `6cf93ba6` feat(agent runtime-debug): attach native review screenshots
- `aa6a276f` feat: add orchestrator composer token estimate
- `ed3c4139` design: ThinkingChip uses theme tokens, drops Material shadow + backdrop-blur
- `48334da9` feat: add orchestrator thinking footer chip
- `ed1543e3` feat(orchestrator): refine slash command controls
- `4d69e885` feat: add supervisor escalation inbox
- `cb7db68f` feat(governance): add heal-bot inbox worker
- `3717e8bf` design: slim orchestrator file mutation rows
- `6b1a23ca` feat: add adaptive orchestrator thinking summaries
- `0d32c293` feat(orchestrator): rotate thread after mission completion
- `9e857d95` design(orchestrator): drop SESSIONS strip, compact packet tab labels, highlight latest dispatch
- `36d1b92b` design(orchestrator): CommandStripNode density pass — theme tokens, no Material shadow [via-o8]

## 2026-04-17

- `c27277a4` feat(orchestrator): /clear /compact /focus /status /recall /handoff slash commands [via-o8]
- `899d1a75` feat: add orchestrator slash command controls
- `5c1fb111` feat(orchestrator): /clear command + fresh-thread-preserves-mission-state [via-o8]
- `2c255f16` feat: add orchestrator clear command
- `ae4b9362` feat(infra): wire prompt caching for AI provider 4.7 orchestrator [via-o8]
- `6425c23c` feat: cache AI provider prompt prefixes in llm proxy
- `870b1c4a` design(agent-chat): share DesktopToolCallStack in MessageBubble [via-o8]
- `fee16838` design(agent-chat): share DesktopToolCallStack in MessageBubble [via-o8]
- `bba32599` feat: auto-compact orchestrator threads at 30 percent context
- `d5da6a03` design(orchestrator): move context down, copy up, shrink session cards [via-o8]
- `2d7caac6` feat(orchestrator): token meter + ThreadsDropdown + header compression [via-o8]
- `c01e4274` design(orchestrator): unify expanded tool lines — read uses same format
- `70ebfa73` design(orchestrator): invert batchable — only file writes/edits earn cards
- `76f535fa` design(orchestrator): collapse tool calls into italic Rams-style line
- `e3d805e7` design(chrome): lift text + chrome-pill colors over vibrancy
- `37955006` design(approvals): ghost-orange buttons + clearer expand affordance
- `afbe2089` design(approvals+orchestrator): tighten to Rams density
- `c78267a5` feat(approvals): first-class merge-gate banner under TitleBar
- `c5d36d6d` feat(orchestrator): unified busy-state UI + stream event routing [via-o8]
- `a0fa7b11` feat(lane): tag merged lane tip commits with [via-o8] suffix
- `46d85881` feat(theme): shift light-mode glass family from white to paper base
- `d353988a` feat(theme): light-mode content surfaces use paper (#F4F2ED) — match o8-site

## 2026-04-16

- `7392b369` feat(cloud): standalone worker CLI reference implementation
- `a85e5e03` feat(lane): route remote-customer merges through merge gate
- `85f9f88c` feat(settings): Workers tab UI + worker tokens API + feature-flag helper
- `5cf1b1e3` feat(dispatch): inject learned rules into packet prompt
- `e4b17ed9` feat(dispatch): learned-rules promotion/demotion cron
- `444f054a` feat(cloud): CustomerWorkerTransport + register remote-customer adapter
- `762942dc` feat(cloud): worker poll + event endpoints with token auth
- `865cb893` feat(db): worker_tokens + worker_runs + worker_events tables
- `977c99c5` feat(dispatch): dispatch_rules table + record from lane merge events
- `d1faacb7` feat(runtimes): scaffold remote runtime protocol types
- `3e1943ab` feat(sidebar): replace 'Idle' label with 3-word task summary
- `06358d59` feat(governance): autonomous decomposition pipeline

## 2026-04-15

- `0c548da4` feat(supervisor): mechanical project rules rule enforcement at post-completion
- `3d287104` feat: add design mode overlay
- `ae7bab5d` feat: branch picker wizard in packet dispatch
- `14bbe2e7` feat(delegate): synthesize packet shell so governance tools find the lane
- `aeb3713e` feat: persist orchestrator plan text in chat history
- `594463cd` feat: auto-capture lane review screenshots
- `1a84bbf2` feat: add external orchestrator mcp servers
- `60491060` feat(orchestrator): Apple-style tool call cards + sticky working bar

## 2026-04-14

- `12147d8f` feat(orchestrator): export thread to markdown (closes)
- `7f39c9d8` feat(orchestrator): anti-patterns section + final-message format doctrine
- `642508c2` feat(lane): reap idle abandoned lanes + safety guard main tree
- `4c1f8d83` feat(history): archive tab in orchestrator history drawer
- `80c6ba85` feat(workspace): merged read-only banner on retired chat tabs
- `e7b0679c` feat(lane): hide sidebar cards + packets bound to archived lanes
- `571b4787` feat(lane): auto-wrap manual runtime launches in a governance lane
- `5d5f317b` feat(mcp): add o8_view_wait_for for polling UI readiness
- `81d61deb` feat(lane): auto-archive stuck reviewing lanes + retire standalone native shell-mcp bridge
- `a40d5503` feat(mcp): bundle o8_view_* webview tools + session picker + UI polish
- `d5a9df43` feat: add timeline toggle to appearance settings
- `d067c1ce` feat(theme): chrome-surface sweep + light blue accent + add-repo redesign

## 2026-04-13

- `41b6deaa` feat(theme): chrome-surface scope for light mode glass buttons
- `930415a0` feat(theme): ship Light + Midnight only, light becomes glass chrome
- `7bdf4ef1` feat(mcp): ship native shell-plugin-mcp with the production build
- `e850f363` feat(ship): local release script + ship npm scripts
- `a6dd4113` feat: Operator live fallback notice + Plan/Code permission chip
- `16721114` feat: o8 Operator + drop legacy provider keys + agent runtime CLI runtime

## 2026-04-12

- `73c3020c` feat: thinner fonts + desaturated diff in Changes panel
- `7da4717b` feat: unified user bubbles across all chats — subtle tinted pill
- `27878c12` feat: thinner orchestrator chat text
- `c0c22c6f` feat: roll Plus Jakarta Sans as the app-wide typeface
- `1547e440` feat: add Satoshi, Outfit, Manrope to typography specimen + match app sizes
- `38e3d7c6` feat: add /text typography specimen page for font comparison
- `487609d4` feat: agent click scopes workspace panel to agent's worktree
- `b049641a` feat: aggregated Issues panel shows all repos grouped by sections
- `5a4aa321` feat: repo alignment gesture — click repo name aligns whole app
- `50e7e82a` feat: multiple repos can be expanded simultaneously in sidebar
- `bfdb3bbf` feat: fleet orchestrator UI — repo focus indicator + sidebar status
- `c9982806` feat: orchestrator system prompt is fleet-aware across all repos
- `1b55e6ec` feat: drag-to-reorder workspace tabs
- `0c2c4bad` feat: session rows match orchestrator row layout
- `4ea59cf5` feat: rename CLI session tabs from 'Assistant' to 'Agent'
- `c74e3c0b` feat: orchestrator tab is visually elevated and un-closeable
- `37fa2886` feat: agent session tabs show repo + runtime instead of "Assistant"
- `42c26615` feat: apple squircle corners on right panel (O8 + workspace review)
- `6971294b` feat: move permission + issues controls into composer toolbar

## 2026-04-11

- `5a5aa45b` feat: analytics apple pass + empty state respace + element picker iframe-proxy
- `7017eb38` feat: midnight-aware terminal theme + navrail/titlebar consolidation
- `d3effe19` perf: gate headless sprint loop on queued packets
- `0f34c232` perf: slim ws-server + lazy-spawn dashboard PTY
- `d9e37000` feat: orchestrator becomes a workspace tab with integrated history + mission

## 2026-04-10

- `ef3c1795` feat: mission dispatch echo + plan-mode banner in orchestrator tile
- `8293a3dc` feat: NavRail launchers for Mission Control + Orchestrator History
- `ade022c1` feat: side-effect-class tool rendering + cross-tile orchestrator bus
- `69aa7075` feat: orchestrator/mission/history as tile-native components
- `9fde4716` feat: thread permissionMode through sendToOrchestrator
- `42fe2719` feat: production hardening
- `1e7254af` feat: Node pre-flight + dynamic port allocation

## 2026-04-09

- `b2ffe19d` feat: AI provider Desktop auto-register + setupComplete schema fix
- `a90b84b9` feat: MCP production hardening — auth, config distribution, bundling
- `649b22b2` feat: add shared token formatter
- `99f14c8a` feat: o8 v2 observability — Ledger + Preview tabs in Memory view

## 2026-04-08

- `227476ac` feat: o8 v2 Phase 1 — directives store + session ledger + API
- `a267ef50` feat: @-mention file suggestions on mobile chat compose
- `0f4c1b31` feat: shared useFileDrop hook
- `6b65204d` feat: enriched approval cards
- `6e06ae5b` feat: pre-dispatch file overlap gate
- `21449b28` feat: expandable detail rows in O8 Activity pane — click to expand inline context
- `807b2a0e` feat: specialized mobile tool call cards — diff, shell, read, search

## 2026-04-07

- `4bb973d7` feat: mobile CLI chat backend
- `3a1707a9` feat: CLI chat backend
- `95a0490f` feat: o8 Assistant rebrand
- `56d6dd96` feat: add OpenRouter + xAI providers + key validation on save
- `727e8e60` feat: inline missions

## 2026-04-06

- `e0ca2772` feat: commit viewer in O8 Changes tab — click commit to review inline
- `6d97605d` feat: click worktree to open agent transcript
- `5e17c8dd` feat: collapse tool calls in transcript bubbles
- `7cb7c1f9` feat: Activity tab in O8 Panel — unified activity feed
- `1326d68d` feat: compact activity badges on repo cards for ambient awareness
- `6ab047d1` feat: show conversation preview in chat tab labels instead of generic "Chat"
- `132e3901` feat: show agent runtime/AI provider brand logo in chat tab headers
- `709c60f7` feat: use official agent runtime + AI provider brand logos across all surfaces

## 2026-04-05

- `121d8ccd` feat: add runtime icons to session agent rows + collapsed branch badges
- `aad3a971` feat: replace CX/CC text badges with agent runtime and AI provider SVG logo icons
- `eab3982b` perf: extract DashboardInner state into grouped context hooks
- `037041eb` perf: native shell IPC for SQLite endpoints
- `d4c34fcb` perf: virtualize transcript list for long agent sessions
- `bb3b274b` perf: lazy-load heavy Canvas tab components + o8TaskBoard
- `f8c02868` perf: deduplicate workspaces + inbox API calls on initial load
- `40eafea1` perf: eliminate transcript render storm + 11 more polls → WS-driven + API dedup
- `9f12852c` perf: native shell IPC commands for hot-path data reads — bypass HTTP stack
- `e4defd53` perf: WS-driven invalidation for 18 polling loops + React.memo on 31 components (,)
- `1989fb6a` perf: replace 2 polling loops with useReactiveQuery
- `2e933427` feat: TanStack Query + WS event bridge for reactive data layer
- `ff6b194f` feat: MCP dispatch DX overhaul
- `5e2436ea` feat: truthful worktree status + cleanup stale worktrees
- `7d8b70bd` feat: click worktree → open agent transcript in canvas ( v1)
- `e5fdd2cd` feat: thinking indicator + faster polling for active agent sessions
- `78ce045d` feat: port hover popover + open ports in O8 browser tab
- `2b48f4c0` feat: open activity commits in O8 changes pane
- `053c41f2` feat: instant PR cache invalidation after merge/approve/request changes
- `f18c597c` feat: inline file diffs + merge conflict badge in O8 PR review
- `3f367cda` feat: PR count badge on repo card — click to open O8 PRs list
- `2cd368e5` feat: PR list view in O8 panel — all open PRs on one page
- `cf84dfef` feat: PR review tab in O8 panel — replaces canvas PR viewer
- `74f94333` feat: collapsible root files section in O8 file tree
- `3e4679fe` feat: editable file viewer in O8 Files tab — competing product-style editing
- `fe4be12e` feat: file browser in O8 panel Files tab — competing product-style split layout
- `4d802c36` feat: dispatch pipeline hardening
- `13e1c16b` feat: wire Edit with AI + Open Source callbacks in O8 element panel
- `302ed50a` feat: visual element selection panel for O8 Browser tab

## 2026-04-04

- `17a4c53a` feat: element picker bridge + source mapper API + rate limit fixes
- `f693abaf` feat: O8 Browser tab — wire LocalhostPreviewTabs into O8 panel
- `4123dcd6` feat: O8 panel Changes tab — git status + inline diff + tab bar
- `6abe1c3e` feat: O8 panel
- `f2bdc450` feat: mobile WS reconnect with exponential backoff + approval recovery
- `79e6f9ec` feat: startup lane reconciliation
- `f12beb96` feat: startup lane reconciliation
- `7bfd7817` feat: GitHub intake pipeline — issue assignment to plan approval
- `517d556b` feat: persist runtime session costs to usage logs
- `6ceddcec` feat: o8 agent safety hooks
- `2f165443` feat: mobile repo picker for multi-repo chat
- `93991f5e` feat: repo-scoped tool execution + repos API

## 2026-04-03

- `b307fa45` feat: apply file edits on approval approve
- `2694a599` feat: add github tool for AI provider — gh CLI access
- `5d5a8bef` feat: expand shell allowlist — npm, npx, node, cargo
- `a614f9bb` feat: add create_file tool for AI provider
- `4a7d5f5f` feat: syntax-highlighted tool output — expand shows real code colors
- `aeeae1e0` feat: Apple-style collapsible tool call cards
- `ba0a31da` feat: AI provider tool execution backend
- `ef4d292a` feat: compact model selector + fix theme toggle in settings
- `2325834f` feat: restore light mode with proper theme toggle
- `103b88e0` feat: tool call card renderer components
- `ac93188a` feat: tool call SSE protocol types and parser
- `90361c32` feat: theme-aware markdown renderer + light mode code blocks
- `d55def49` feat: rebrand mobile shell for o8
- `7847e23c` feat: rebuild mobile approvals and sidebar surfaces
- `64befb3d` feat: rebuild mobile approvals and sidebar surfaces
- `5bb12031` feat: replace custom mobile chat with @assistant-ui/react Thread
- `11b45e37` feat: build mobile assistant-ui thread chat
- `cf959e37` feat: mobile settings view + decompose monolithic client into focused modules
- `8877e0f9` feat: mobile redesign
- `84bfd17a` feat: mobile settings view + decompose monolithic client into focused modules
- `fdb6d3fd` feat: mobile settings view + decompose monolithic client into focused modules
- `acc3bec8` feat: mobile settings view + decompose monolithic client into focused modules
- `5f62dba3` feat: mobile settings view + decompose monolithic client into focused modules
- `e79a3128` feat: mobile settings view + decompose monolithic client into focused modules
- `3fe7ca6d` feat: add mobile settings view to glass sidebar

## 2026-04-02

- `f5a1a47b` feat: full glass input field + glass send button + scroll-to-bottom arrow
- `fbd1b373` feat: glassmorphic buttons
- `f1918518` feat: collapsible code blocks with diff coloring and file path labels
- `ba86fdc7` feat: TTS play button on assistant messages + AI provider-style input bar
- `ee46b68d` feat: starred + recents sections in sidebar, revert dots back to long-press
- `eeb3cfad` feat: long-press context menu on chat list — star, rename, delete
- `2b07871d` feat: AI provider-style chat list view
- `243e1cbd` feat: AI provider-style message rendering + mobile markdown for code blocks
- `adee9d2c` feat: wire mobile chat to real chat history store + conversation list in sidebar
- `c64bb792` feat: AI provider-style sliding sidebar + AI provider chat on mobile
- `8fe02832` feat: add npm run tunnel for remote mobile access via Cloudflare
- `6f2b8b85` perf: prefetch mobile inbox on server
- `6aa62e9d` perf: break route barrel imports
- `b9313e24` perf: switch dev to turbopack and lazy init db
- `df98a910` feat: bound onAgentCompletion retry loop
- `e50a0b22` feat: add attempt learning persistence
- `a56aed36` feat: add low-risk auto-approve policy
- `33703be2` feat: add packet self-review confidence gate
- `bbb90c11` feat: objective exit criteria
- `9dcdab9f` feat: compact Apple-style dropdown menu, no full-screen overlay
- `5d0bf0c5` feat: AI provider-style tool cards in mobile chat
- `22e097e8` feat: organize mobile sessions by type — Chats, Sessions, Missions
- `1fd14ac9` feat: warm grey + light beige palette across all 30 mobile surfaces
- `0376ff68` feat: slim compose bar
- `20a5f1a6` feat: in-process mutex on orchestrator-state.json
- `abb14943` feat: merge conflict escalation via approval card
- `3c58e2b1` feat: persist workflow watcher state to SQLite
- `be4166f7` feat: orchestrator session health monitor — 90s timeout + auto-recovery
- `6c2b5ba1` feat: persistent SQLite-backed review queue
- `0d5fc688` feat: inline mission creation — no GitHub dependency
- `13960c88` perf: mobile page is now client-only — zero server-side bootstrap
- `0a82a26c` perf: mobile optimization
- `628015af` feat: copy AI provider mobile session list — clean rows, status groups, FAB
- `f24578dc` feat: mobile new chat — launch LLM session from phone
- `38b06a25` feat: mobile wave 4
- `c3f901d0` feat: purge 4,277 lines of remodex CSS + remaining className from mobile

## 2026-04-01

- `a484d188` feat: mobile waves 2+3
- `c9eeb8e6` feat: mobile wave 1
- `3c513561` perf: P1 bundle + network optimizations
- `72e56798` perf: P0 performance fixes
- `7a2e334b` feat: wire recommendMergeOrder() into merge pipeline
- `846fdcba` feat: merge gate file size block + operator override
- `f21a6ff0` feat: add FILE_SIZE_WAIVERS for layout orchestrators and multiplexers
- `fe3b7b73` feat: skeleton map file size check at dispatch time
- `8b517ecf` feat: InfinityGlow animated status indicator for agent cards
- `692d3a0b` feat: FTUX progressive feature reveal
- `626494a4` feat: FTUX first-merge celebration state
- `30c535d9` feat: FTUX mobile QR prompt
- `8b2e2883` feat: FTUX First Mission Card contextual CTA
- `a195b883` feat: FTUX empty states for all dashboard panels
- `d8da0cfe` feat: FTUX warm dashboard state
- `b5809230` feat: FTUX personalized chat greeting
- `42538c15` feat: workflow transition WebSocket channel
- `657b19ec` feat: workflow transition WebSocket channel for real-time status streaming
- `63249bec` feat: migrate approval store from JSON to SQLite
- `d7864cfe` feat: migrate approval store from JSON to SQLite

## 2026-03-31

- `a787d367` feat: migrate lane registry from JSON to SQLite — kill cross-process clobber
- `4e96d179` feat: sprint 6 wave 3
- `6870f671` perf: sprint 6 wave 2
- `450d0ac5` feat: workflow watcher coordination
- `d362158d` feat: route Audit Log to workspace tab instead of Inspector panel
- `48e057a2` feat: sprint 5
- `2d494c5e` feat: sprint 4
- `83ca5a08` feat: sprint 3
- `062a4566` feat: sprint 2
- `2c4d3079` feat: structured multi-file diff in approval review gate
- `2a37597f` feat: workflow watcher triggers workflow transition
- `e31515e9` feat: agent runtime PreToolUse hook script for policy enforcement
- `51160c3a` feat: one-shot send-as-task from ThoughtsCard chat
- `d1540cd0` feat: server-side packet auto-dispatch loop
- `57eea52b` feat: integrate native shell-plugin-mcp for native app automation in dev builds
- `55baa4c2` perf: JSONL tail-reads, cache-first actions, fingerprint optimization, sleep removal
- `90427815` perf: strip JSON pretty-printing from MCP server responses

## 2026-03-30

- `cc43701b` feat: native shell vibrancy polish, operator bridge fix, ghost session eviction, right panel cleanup
- `8e10449f` feat: operator MCP bridge — agent runtime as o8 control surface
- `77808c86` feat: workspace UI overhaul
- `a6a842c3` feat: UI polish pass

## 2026-03-29

- `946a708b` feat: o8 brand mark — three-circle logo in accent blue
- `f73cc64f` feat: orchestrator loop — plan, delegate, review, approve
- `36dad2fb` feat: governance engine
- `92217778` feat: refine o8 product brief from 3-turn brainstormer session
- `bbbb97d5` feat: add REVIEW.md, agent delegation table in project rules, update agent descriptions
- `b7dd70b9` feat: add o8 product brief, update project rules with orchestrator model, create subagents
- `c4da0521` feat: scrollable workspace lane tabs with transparent arrow overlays
- `2759a9fe` feat: tab scroll arrows, tool cards in Thoughts, right panel defaults to review
- `70cb04b8` feat: workspace tab shows issue context + diagnostics settings tab (,)
- `19831e0d` feat: one-click issue launch icon + lane-scoped review rail (,)

## 2026-03-28

- `fbba93e3` feat: add orchestrator MCP server, delegation tools, and agent supervisor
- `aba6fed9` feat: add GitHub issues to ThoughtsCard Mission Control

## 2026-03-27

- `89627bf8` feat: add translucent desktop dark mode shell
- `80708df7` feat: harden workspace shell and terminal sessions
- `8b2168a3` feat: add o8 board and restore system-wide timeline
- `0470ead2` feat: move repo selection into workspace headers

## 2026-03-26

- `eb996003` feat: fix branch-scoped review flow
- `82e2c5a9` feat: turn workspace side panel into repo companion surface
- `71b9ca05` feat: route repo surfaces into workspace tabs

## 2026-03-25

- `acbf1ff9` feat: tighten workflow lifecycle and operator recovery
- `4003a388` feat: refine desktop dark mode theme
- `2faf19a4` feat: migrate ide to fact-backed o8 recall
- `3fb6e41b` feat: enrich workspace cli chat parity
- `cf00c0d9` feat: polish timeline and workspace chat surfaces
- `340c6340` feat: scope agent surfaces to ide sessions
- `6376ac49` feat: route workspace launches and github flows through broker

## 2026-03-24

- `5711530e` feat: ship github app broker foundation

## 2026-03-23

- `e8b44419` feat: Unified ContextualPanel — canvas tabs merged into bottom panel
- `b4ae4802` feat: Drop bundled Node (prerequisite) + bundle memory binary
- `9f4eba3e` feat: WS server bundled in native shell app — terminals + chat work in production
- `767f89b7` feat: GitHub App authentication — 5,450 req/hr, auto-refreshing tokens
- `acfd21b1` feat: GitHub PAT support + config lives in the user data dir/
- `4e366bfd` feat: Bundle Node.js inside the app — zero-config for users
- `ff96e65a` feat: Standalone server bundling for native shell — real distributable app
- `4ddc7a58` feat: Inline edit
- `e3dc9f76` feat: 'Environments' filter in files dropdown — quick access to .env files
- `6159d0f0` feat: Inline AI widget

## 2026-03-22

- `d2945ad5` feat: Tab autocomplete — AI ghost text suggestions while typing
- `c4414abb` feat: Cmd+E inline AI edit
- `709c8f87` feat: Resizable files panel — drag handle between files and activity
- `41be4578` feat: Monaco Frost v2
- `8302e17a` feat: Monaco 'o8 Frost' theme — icy light blue editor
- `6cfd2856` feat: Monaco Editor v3 — full IDE-grade file editing
- `5989542d` feat: File editor v2
- `4a870b6e` feat: Inline file editor with Cmd+S save + files default to Changes view
- `f59956b4` feat(branding): add o8 logo component + concept assets
- `0f024760` feat: In-app update banner + landing page + version sync
- `cbd5f6bc` feat: native shell updater + GitHub Actions release workflow

## 2026-03-21

- `fee1a9e0` feat: add sidebar runtime capability layer
- `d78a5f38` feat: refine sidebar approval polish
- `2f35b3b6` feat: polish sidebar approvals and file actions
- `8b6b16bf` feat: polish sidebar file actions
- `4453dfcf` feat: add sidebar source actions
- `79b55296` feat: unify sidebar active turn surface
- `a39eb014` feat: show sidebar web source links
- `60c9c287` feat: enrich desktop sidebar source context
- `c5253e4f` feat: refine desktop sidebar runtime turns
- `718f987c` feat: Conflict Resolution UI in Memory settings tab
- `44614a4f` feat: polish desktop sidebar runtime chat
- `39cf7d88` feat: add intent board v1
- `750ee7a2` feat: unify desktop thoughts and sidebar chat rendering
- `8e4f8adb` feat: Codebase seeding engine — solve cold start for new users
- `d81f2c71` feat: Unified chat send route + type fixes
- `1246e89e` perf: WebSocket RPC replaces CLI fallback — agents load in <500ms
- `4688c1b2` feat: First Launch Setup Wizard — blue glass onboarding flow
- `0455f3e6` feat: Setup detection + config API for first-launch wizard
- `ce44ff4f` feat: Graceful degradation when gateway unreachable
- `f8a7df3b` feat: Production polish
- `0c7a85d5` feat: Blocklist guard for public changelog + project rules rule

## 2026-03-20

- `4428a3eb` feat: context-aware recursive compaction — three-pass smart compression
- `e8812258` feat: project rules
- `b7befce8` feat: Chat compaction
- `1bea35aa` feat: File system tools
- `04e490af` feat: Terminal command tool with three-tier safety + editable approval
- `d0a06dfd` feat: Chat-optimized recall — structured facts over raw chunks
- `97d7de7b` feat: Phase B
- `1f4ac087` feat: memory settings
- `ef9b0a19` feat: memory settings tab — configure models, view stats
- `4f5c42c3` feat: memory recall — Phase A
- `f0773456` feat: Steve Jobs polish — 5 UX refinements for LLM chat
- `61b473b7` feat: Unified input container — model picker moves to bottom toolbar
- `59e60cc2` feat: GitHub tools for LLM chat
- `4d5a1b07` feat: Syntax highlighting, thinking text style, citation hover cards
- `cf8f2a92` feat: Chat history sidebar — search, star, open in new tab
- `e42fcf03` feat: Streaming code highlights, keyboard shortcuts, conversation forking
- `b0ede0a5` feat: Inline citations, slash commands, Run in Terminal
- `4484b112` feat: Code block actions — Apply to File + Open in Canvas
- `db78a52d` feat: Smart follow-ups + beautiful empty state onboarding
- `ef4a538c` feat: Phase 3 — Tool use with live indicators + sources
- `e96f08f7` feat: Edge TTS voice playback with animated player
- `4b163d94` feat: AI provider Desktop-style message action bar + proxy logging
- `259de479` feat: Chat persistence + mermaid error isolation
- `02a74be2` feat: Full image support
- `78d634ac` feat: Rich markdown renderer for LLM Chat
- `294fbe74` feat: LLM Chat Phase 1+2 — workspace context + @file attachment
- `8bc7c91f` feat: Add all latest AI provider models (3.1 Pro, 3 Pro, 3 Flash)
- `6a27de6b` feat: configuration settings tab
- `bde2d9af` feat: LLM Token Relay — provider proxy with metering
- `a1e74656` feat: LLM Chat v1 — standalone model access panel
- `f2b3bda6` perf: GitHub API caching + worktrees auth fix across all routes
- `520e563f` perf: Kill scroll jitter — remove per-frame CSS recalculation
- `4ff68917` feat: client abstraction — Local/Cloud/Hybrid
- `62e2f26f` feat: Tier 2+3 intelligence layer

## 2026-03-19

- `a0c66dcd` feat: Repo switcher for Issues & PRs + deeper chat history
- `7084cc18` feat: Issues & PRs combined page + collapsible agents + deploy
- `7ac78028` feat: Issues + Deploy Status + CI on mobile — monitoring & deciding
- `7c6e6a81` feat: land realtime control plane and shell-first render path
- `1b83fb87` feat: Memory page
- `53e0503b` feat: Tap-to-reveal message actions + Telegram-style photo grids
- `ddec920f` feat: Dark mode
- `d0c187b2` feat: Tier 1 UX
- `4520c1f2` feat: Smooth crossfade animation between expanded header and compact pill
- `81af23ac` feat: Hide RuntimeBar when keyboard is up — clean compose
- `683d032c` feat: Auto-grow input + RuntimeBar at true bottom + frosted status bar
- `0ff296e7` feat: Compaction indicator on mobile chat — matches desktop ThoughtsCard
- `84375a1b` feat: Header collapse-to-pill + repo/branch/diff in bottom footer
- `36bd16c1` feat: Costs page
- `667ccb5f` feat: Settings + PR Reviews in Activity + panel status APIs
- `9e4a07da` feat: Notifications + PR Review from mobile
- `adaa7be1` feat: Activity Feed + Launch-to-chat + Fleet → Agents rename
- `fd52241d` feat: Launch Agent — fire agents from mobile
- `aa39ff18` feat: Fleet View — Apple-level agent dashboard for mobile
- `4d4098e3` feat: Glass slash commands on mobile — frosted popover matching desktop
- `9fbe80c0` feat: Speed Dial navigation — floating menu like Mister Copy Trade
- `460e0e6f` feat: ThoughtsCard Apple pass

## 2026-03-18

- `bce489a3` feat: Slash commands + glass attach popover in workspace chat
- `f0bbc5cd` feat: Chat V2 pass 2 — model/thinking, search, media button
- `f5478e87` feat: Chat V2
- `4c9eda21` feat: competing product-style compact agent cards + always-visible running agents
- `a718c389` feat: Add agent runtime + agent runtime to Open In dropdown
- `1c63dec5` feat: Open In button
- `9e784cef` feat: Global Repo Context Bar — first-class repo selector above tabs
- `2219822f` feat: Workspace Chat V1 — full chat tabs alongside terminals
- `39f9c01a` feat: Dedicated Checks tab on PR viewer — competing product-style CI status
- `9590abce` feat: Files tab — Changes filter dropdown
- `115e383e` feat: Close remaining workspace gaps
- `9f2ee7b8` feat: Branch switching from panel — git checkout with dirty check
- `b017fbb6` feat: Running indicator on collapsed repo card
- `563cdf1d` feat: Dev server launch from repo card — one-click Run/Stop
- `e89ace23` feat: Port preview pane — in-IDE iframe via proxy
- `c8260a3e` feat: Agent ↔ Branch association — bidirectional linking
- `0ae02991` feat: First-class ports in NavRail — auto-detect + grouped display
- `a1797b6f` feat: Branch management — create, delete, cleanup
- `6142149c` feat: Optional worktree launch + stale branch detection (,)
- `aff81b7c` feat: Expandable repo cards — branch list with worktree indicators
- `9518a196` feat: Colored file icons + repo-aware file tree
- `05d3667b` feat: PR Review opens in canvas + remove Issues/PRs/CI tabs
- `e401d948` feat: Repo-scoped Activity
- `c804c12d` feat: Repo-aware Activity feed — selector, agent-scoped, PR merge banner
- `5c0ee4f8` feat: Activity feed
- `e62be519` feat: Unified Activity Feed — Apple-grade timeline with GitHub data
- `6349257e` feat: Show all main agent surfaces + smart cron collapsing + fleet display setting
- `abfd7dae` feat: Pin main agents + collapse cron sessions into single card per agent
- `c93b7253` feat: Stall detection for launched agents — 5min silence triggers warning

## 2026-03-17

- `ce48e9e4` feat: Proxy localhost previews to strip frame-busting headers
- `6c74dd81` feat: Agent lifecycle
- `43b1a614` feat: Live localhost preview
- `05e0ac99` feat: Live activity dots + elapsed time on terminal tabs
- `9017787d` feat: Terminal tab persistence — tabs survive app restarts
- `00b33623` feat: Inline images rendered as HTML — bypass xterm IIP entirely
- `2b34a65e` feat: Inline image rendering
- `cea81b93` feat: Inline image rendering in terminal — Sixel + iTerm2 IIP support
- `622898d0` feat: Auto-register folders opened via picker — shows as Recent next time
- `0ca184b7` feat: Native folder picker
- `ca044df8` feat: Open folder picker — launch CLI agents in any directory
- `5aba674f` feat: Two-step CLI picker with repo selection ( foundation)
- `3d2d8ce3` feat: Terminal polish
- `1164370f` feat: Terminal-first workspace
- `136961d6` feat: Live review file-change push via WS — repos + worktrees
- `4ee915ad` feat: Mobile terminal surface — xterm.js on mobile + Terminal/Chat lane
- `1b046b9f` feat: Terminal infrastructure
- `25e769ef` feat: Launch modal UI
- `d60f41e4` feat: Universal launch pipeline
- `b92b59f4` feat: Repo registry polish
- `e58a7e58` feat: Analytics page — cost dashboard with real data
- `5b068248` feat: Agents section collapsible — same pattern as Activity
- `38a9bab6` feat: Activity as collapsible dropdown above agent cards
- `b7d2b624` feat: Issue assignment panel + ThoughtsCard z-index fix
- `a956101f` feat: Active session pulse on timeline drill-down cards
- `afa065a6` feat: Session cost tracking — real token usage + spend per session
- `efe80a15` feat: Connected session panel with live SVG bezier connector
- `951c3b6e` feat: Timeline drill-down — double-click for per-agent breakdown
- `3674fdf8` feat: Clickable PR diff on agent cards — opens PR viewer in Canvas
- `8ba5213e` feat: WS-driven AgentPanel + TitleBar status dot + full dedup (-6)
- `53cade93` perf: Wire WS for diff stats + remove redundant polls

## 2026-03-16

- `170944e3` feat: Wire WebSocket to desktop chat — real-time streaming
- `7d3626fc` feat: agent runtime agents show their active repo's diff
- `01d14821` feat: Live Diffs for all 3 runtimes + UX fixes
- `a2e83af8` feat: Live Diffs — beautiful real-time code change viewer
- `10314573` feat: Live Agent Output panel + agent card pulse
- `158ecce9` feat: Real diff stats on main + real timeline activity bars
- `1e0988c2` feat: Real context % for agent runtime sessions + diff stats
- `597121a4` feat: Wire real workspace data — PR status + diff stats on agent cards
- `e54211d2` feat: agent runtime sidebar chat
- `414b7dfc` feat: agent runtime transcript — read session JSONL into sidebar
- `7e3c59f9` feat: Smart naming on collapsed card dots too
- `a7d65658` feat: Better naming in agent cards
- `991c0a4f` feat: agent runtime sidebar chat — send messages via CLI print mode
- `244cdf19` feat: agent runtime synthetic sessions for unmatched live processes
- `f0d2ae64` feat: agent runtime sessions appear in fleet with live PID detection
- `b7a09047` feat: Status-grouped agent cards + Apple design polish
- `caf2ae39` feat: Full-size agent cards with everything visible
- `e52f8feb` feat: Show heartbeat intervals on agent cards (read-only)
- `c7045ae0` feat: Agents tab in Settings — fleet dashboard with model editing
- `012e3467` feat: Merge WorkspacesPanel into AgentPanel — unified view
- `477db1bb` feat: WorkspacesPanel — status-grouped workspace cards
- `eb94e652` feat: Cmd+K keyboard shortcut to toggle Thoughts Card
- `be554ef9` feat: Context-aware suggestions in Thoughts Card
- `3cd96bc6` feat: Agent picker in Task chat — route to any agent
- `4d92367f` feat: Approval routing in Thoughts Card + test simulation
- `f19252a4` feat: Task mode — mini chat inside Thoughts Card
- `705c68c9` feat: Thoughts Card — Issue vs Task modes + resize fix
- `8bc11ae1` feat: Thoughts Card — resize handles + agent connection
- `e9a94d1d` feat: Thoughts Card — floating glass command surface
- `340fa745` feat: Settings page with GitHub connection status
- `ae83afa6` feat: Intent Canvas V0 — Fleet Command Center in workspace
- `dcaadd01` feat: SessionTimeline Phase 1 — hover scrubber + real data API
- `8f6519af` feat: Timeline Expanded View — full session replay in Canvas
- `e1174456` feat: SessionTimeline V0 — agent activity replay bar
- `f3905032` feat: TitleBar window controls — sidebar/back/fwd/bottom/chat/settings
- `d8fcd900` feat: TitleBar search is now live UniversalSearch + red settings gear
- `da1bdbd1` feat: TitleBar
- `4446e265` feat: Desktop NavRail
- `1080e24d` feat: Session Info Sheet
- `bea6bcbb` feat: Universal search
- `9675a3e5` feat: Proactive alert system — engine, context, bell, tray, toast
- `0527a066` feat: REST API resilience

## 2026-03-15

- `1a9eb7f1` perf: gateway REST API client — 23ms vs 38s CLI cold-start
- `41f29712` feat: Heat map top-down view + fix fly-in stale closure
- `fc531142` feat: Search dropdown with grouped clickable results
- `9bfe3def` feat: Knowledge Graph v3 — double-click fly-in + search fact nodes
- `6c77a404` feat: Knowledge Graph v2.3 — zoom-aware labels + ambient fireflies
- `9adc97a1` feat: Knowledge Graph v2.2 — depth fog + all labels + text polish
- `a9e63faa` feat: Knowledge Graph v2.1 — bar gradients + floor reflections
- `14f14463` feat: Knowledge Graph v2
- `ca19689b` feat: Auto-refresh Knowledge Graph stats every 60s
- `0354daaa` feat: Replace lava lamp with Interactive 3D Knowledge Graph Explorer
- `898a313e` feat: Memory lava lamp v2
- `7f37c210` feat: memory Lava Lamp — living particle visualization
- `3d08e630` feat: Image rendering in mobile chat + click-to-expand lightbox
- `ea6ed3e0` feat: Image rendering in chat + click-to-expand lightbox
- `9863dba3` feat: Typing indicator — animated dots while agent is thinking
- `7d8f218a` feat: Deployment Status (Vercel) + Git Log + Image Preview complete
- `befe61f8` feat: Git Log viewer + Image/Asset preview
- `27b92676` feat: Issue Creator with AI enhancement (AI provider)
- `500293bd` feat: Global workspace search + PR review comments with diff context
- `f18ceac8` feat: CI tab in agent panel
- `ab2a2b19` feat: Changed file highlighting, clickable files, CI button
- `f2d58a7f` feat: README viewer, CI/GitHub Actions, file diff preview
- `e4e1479f` feat: Stop button + project-scoped data + no auto-transcript popup
- `46516d1c` feat: Project-scoped Issues, PRs, and Files — data follows workspace
- `cf8e8239` feat: PR Review tab + canvas viewer — full GitHub PR detail inline
- `e3187196` feat: Commit detail viewer — click any commit in Activity tab
- `b59e2d84` feat: Agent panel groups by workspace — matches chat session picker
- `eab3f4b8` feat: Show all agents including agent runtime/agent runtime in agent panel
- `2917e79f` feat: Issue detail full-width + diff opens in canvas tab
- `e9d67a88` feat: Drag-and-drop + paste + click-to-attach files in desktop chat
- `09cad8a5` feat: Vertical drag handle for canvas — resize workspace/canvas split
- `f7e97fca` feat: Contextual Canvas — bottom-half tabbed workspace
- `df686dbc` feat: Click agent surface → switches chat to that session
- `8541211f` feat: Agent cards v2
- `2f365539` feat: Proper markdown rendering in issue modal
- `f2798a46` feat: Light theme + clickable issues with glass modal
- `bc68e9ab` feat: Three-column layout — Agent Panel | Workspace | Chat
- `0cf1fa1a` feat: Agent Command Center
- `2d3cd046` feat: Glass diff modal
- `11bcc333` feat: Draggable compose bar — resize input height by dragging up
- `5a079ca4` feat: Glass modal for Mermaid diagrams — expand, zoom, pan
- `3e5e5b87` feat: Mermaid diagrams on mobile — same o8 frost theme
- `f26f8464` feat: Styled CodeBlock + Mermaid diagram viewer
- `5bf88d0d` feat: Transport controls — message actions morph during playback
- `6f3c510d` feat: Point-to-Play
- `51933c9c` feat: TTS Engine + Message Action Bar — Play/Copy/Retry on every message
- `d632614f` feat: Desktop chat header — exact mobile TopBar clone
- `c8d2d8e3` feat: Desktop chat sidebar — mobile-identical chat on Dashboard v1
- `fc5d8635` feat: Dashboard v1
- `3566fc4b` feat: wire o8 v1.2.5 fixes — fact_ids, stale flags, real graph
- `01f5ab09` feat: grouped squad picker with expand/collapse
- `dd9b0281` feat: native shell v2 desktop shell
- `13e1ad92` feat: squad picker dropdown on TopBar title tap
- `6af84d2d` feat: wire memory surfaces into shell
- `13ae474a` feat: memory Integration — all 8 issues (-)

## 2026-03-14

- `43cf8d7e` feat: Phase 2
- `708d41bc` feat: worktree isolation Phase 1
- `b835ee03` feat: universal runtime adapter contract + agent runtime integration
- `5a9a5bb4` feat: code block rendering — fenced code + tool output cards
- `6bd7b540` feat: native markdown table rendering — beautiful HTML tables in chat view
- `d83e6050` feat: unified WebSocket — real-time push replaces SSE + polling
- `bd9036a3` feat: PWA
- `26c32b98` feat: virtual scrolling for transcript — DOM bloat eliminated
- `c2f11fe0` feat: consolidated sync API — 5 requests → 1
- `5e01f2d4` feat: prompt enhancement
- `de42f99a` feat: approval primitive
- `8927a99a` feat: cost dashboard
- `0a8b21a1` feat: wire json-render Renderer into mobile shell
- `6da29aed` feat: json-render integration
- `19e51f27` feat: agent runtime chat parity
- `c8b15e42` feat: seamless agent runtime chat
- `36351e8d` feat: auto-switch to launched agent runtime session
- `c426f960` feat: clean agent runtime chat view
- `ebb56869` feat: discovered agent runtime session transcript
- `dcbf0228` feat: live process fallback
- `affef052` feat: mobile agent runtime launch

## 2026-03-13

- `22b3c8db` feat: unified chat for agent runtime sessions
- `b979cf4d` feat: show all agent runtime sessions in squad (no stale filter), dedupe by branch, show branch in pills
- `979c983f` feat: project-grouped squad rail
- `a1860a79` feat: native streaming
- `7a8581b9` feat: commit summary card in diff view (zero AI
- `6c4cb297` feat: observable agents
- `7992ed33` feat: squad cards
- `e3bc0913` perf: diff view
- `6655ee47` perf: review-file 10s cache + only poll when diff open, tighter idle behavior
- `8b61d05d` perf: request dedup, 8s inbox cache, 5s transcript cache, round usedPercent, suppress hydration
- `35bf9434` perf: adaptive polling (20s idle, pause on hidden tab, resume on focus), CSS containment, layout isolation
- `2d241d0f` perf: diff-and-patch transcript + snapshot — eliminate flash on idle polls
- `2dbd368e` perf: skeleton loading, lazy images, send click, API caching (3s transcript, 5s inbox)
- `45f42c8d` perf: smooth scroll, message fade-in, optimistic user messages, image caching, typing bubble animation
- `6deb635e` design: red send button + red typing dots — matches hamburger accent
- `84f9fbb8` design: solid red menu button, context pressure in bottom bar, doc tab apple redesign
- `48522dd5` design: full mobile UX pass
- `12bec3ff` design: apple-grade controls sheet + sticky diff files survive compaction
- `6e2bcde5` design: apple-grade diff polish

## 2026-03-12

- `70bf1c7d` feat: surface queued agent runtime turns and clearer mobile send actions
- `a3c605fc` feat: add quick thread switching for mobile agent runtime lane
- `e2b9e0c0` feat: make owned agent runtime mobile lane feel conversational
- `ca184bef` feat: allow owned agent runtime interrupt on mobile
- `0d4448e4` feat: preload owned mobile diff context on focus
- `054b902f` feat: extend owned agent runtime review and resume on mobile
- `18701e5d` feat: make owned review packets actionable
- `af86dd26` feat: add owned agent runtime review packets
- `09fb81b4` feat: surface owned agent runtime watch lane on mobile
- `9b6d927a` feat: harden owned agent runtime lifecycle and tail views
- `8e88bd67` feat: add owned agent runtime launch and resume lane
- `671b89be` feat: add runtime action ownership seam
- `bb80b33d` feat: promote runtime inventory and agent runtime activity detection
- `2d058c98` feat: surface local agent runtime runtime discovery in desktop shell
- `a327c65b` feat: harden mobile operator chrome and review cockpit
- `79b9f905` feat: add panel and terminal shells to mobile queue
- `ddf224a4` feat: add mobile per-file review drilldown
- `af0c5d58` feat: deepen mobile review lane and glass styling
- `e8d6d758` feat: align desktop repo truth with live review state
- `abc0ee9b` feat: wire direct mobile actions and history

## 2026-03-11

- `38e6f0bb` feat: add mobile control inbox foundation
- `e63edc8d` feat: wire live agent runtime bridge and workflow review
- `868b012d` feat: add native desktop shell wrapper and guardrail surfaces
- `8a8b0775` feat: bootstrap command center shell and runtime contracts
