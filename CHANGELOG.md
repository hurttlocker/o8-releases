# Changelog

Development activity for o8 — the governance layer for autonomous engineering teams.

We ship high-signal entries only (features + performance wins). Bug fixes, refactors,
and internal chores live in the private engineering log.

---

## 2026-07-11

- `21f478bf` feat(packet): show WHY a review was declined in the decision banner
- `73caa0de` feat: Branch management — create, delete, cleanup
- `3b488961` design(status): review-declined = orange o8 dual-pulse (trial)
- `2181b75c` feat: Optional worktree launch + stale branch detection (,)
- `cdfdb548` design(status): Failed pulses (red orb) so it separates from the static rose of rejected
- `31a9dccb` design(status): awaiting-review is a paused grey with a sweep motion, not a color
- `1c06710b` design(status): cool the human-decision dot states off the warm cluster
- `c3a67010` feat(motion-lab): add a Status vocabulary board
- `e431c0a1` feat: Expandable repo cards — branch list with worktree indicators
- `812ecfa8` feat(packet): tighten the decision banner
- `ad609f3d` feat: Colored file icons + repo-aware file tree
- `54e8521a` feat(packet): give a rejected packet a decision banner + stateful dot, and a Discard verb
- `b0b4d50a` feat(merge): give the review beacon a 'rejected' state and stop hygiene packets parking the gate
- `8a4eaa8e` feat: PR Review opens in canvas + remove Issues/PRs/CI tabs
- `6f03dc21` feat(merge): drop the 'No open PR'/'Open PR' bottom-bar noise
- `629cc421` feat: Repo-scoped Activity
- `f9ac73de` feat(merge): let the bottom-bar review beacon merge, not just view
- `f69959eb` feat: Repo-aware Activity feed — selector, agent-scoped, PR merge banner
- `1198271f` feat(rail): surface the branch's PR inline in the workspace rail
- `0c3133a7` feat: Activity feed
- `6f81d4dd` design(composer): swap mic and context meter — mic by Send, meter by attach
- `07046189` feat: Unified Activity Feed — Apple-grade timeline with GitHub data
- `5f579f7d` feat(composer): kill the Fleet/Solo chip — solo vs fleet decided by runtime count
- `8dec8819` feat(composer): thin file-list scrollbar; Rules chip only when rules exist + /rule /rules
- `9c726d5d` feat: Show all main agent surfaces + smart cron collapsing + fleet display setting
- `40b0b831` design(composer): filename-first file attach rows, match highlight, lighter weights
- `096f11ee` feat: Pin main agents + collapse cron sessions into single card per agent
- `e0f42697` design(composer): label Collide as 'Mixture of Agents' in the picker
- `a039464a` design(composer): trigger names the model, not the provider
- `51aed567` design(composer): house drawers for models, Extra label, dynamic Collide decider
- `935e9ead` feat: Stall detection for launched agents — 5min silence triggers warning
- `7ec4f4c1` design(composer): effort slider with named tiers, Ultracode top notch arms Swarm

## 2026-03-17

- `fd5b95be` feat: Proxy localhost previews to strip frame-busting headers
- `e264927d` design(composer): agent runtime-style footer
- `db55ccd4` feat(orchestrator): clarify-first goes silent + auto-arms on a repo's first mission
- `3aa4d16a` feat(ui): retire the permission shield — composers always run full access
- `86c99f16` feat(ui): move add-repo onto the Projects row, slim the footer
- `dc767c4a` feat: Agent lifecycle
- `5b9a557d` perf(ui): 60fps panel drags via direct-DOM + footer icon tiers

## 2026-07-10

- `98bd1229` feat(voice agent): control o8 hosted terminals by voice
- `4ed8d0d5` feat: Live localhost preview
- `34dbbbce` feat: Live activity dots + elapsed time on terminal tabs
- `77e61810` feat(voice): main-process capture defaults ON for Intel Macs on Sequoia
- `07783010` feat: Terminal tab persistence — tabs survive app restarts
- `796e1050` feat: Inline images rendered as HTML — bypass xterm IIP entirely
- `c77d971a` feat: Inline image rendering
- `f6987cd0` feat(voice): main-process microphone capture
- `0adbabb6` feat: Inline image rendering in terminal — Sixel + iTerm2 IIP support
- `c4c521b7` feat: Auto-register folders opened via picker — shows as Recent next time
- `c3b0f1f9` feat: Native folder picker
- `83d80632` feat: Open folder picker — launch CLI agents in any directory

## 2026-07-09

- `07dab129` feat: merge-gate test replay + decoupled worktree capture trail
- `457ff44c` feat: Two-step CLI picker with repo selection ( foundation)
- `ab13f9a3` perf: bound mobile worktree diff transport
- `c7f59308` feat: Terminal polish
- `8619b451` perf: page mobile chat history
- `24056205` perf: stream revisioned mobile inbox deltas
- `5e016418` feat(telemetry): native crash capture (SIGSEGV/SIGABRT/SIGBUS/stack-overflow) via minidumps
- `a8ed6a3e` feat: Terminal-first workspace
- `81fc33d2` feat(desktop): explicit Open With UTIs
- `dfea5ff4` feat: subject-gone TTL fallthrough
- `18741a2b` feat: Live review file-change push via WS — repos + worktrees
- `d2f42e86` feat(desktop): Finder "Open With → o8" opens land in the workspace on the default IDE surface

## 2026-07-08

- `1333fb23` feat(canvas): IDE-parity transcript rendering + honest lifecycle clocks in agent cards
- `90bd3250` feat: Mobile terminal surface — xterm.js on mobile + Terminal/Chat lane
- `6e2a71e6` feat(telemetry): Sentry crash/error reporting across all three desktop layers — dormant without a DSN
- `128957d9` feat: Terminal infrastructure
- `fb01941f` feat(voice): voice agent Spatial Context
- `71ad1442` feat: Launch modal UI
- `6f31460d` feat(entitlement): View as Free dev switch — founder--gated, min-clamped
- `4360e99a` feat(voice): morph composer into live agent partials + vary voice agent ack lingo
- `9aa6dc9a` feat(voice): window-aware partials HUD anchor + opt-in Fn dictation HUD
- `e24244b3` feat: Universal launch pipeline
- `f6c89fd3` feat: Repo registry polish
- `d1fd1f65` feat(voice): outside-the-window live agent-transcription HUD
- `2da95924` feat: wedge layer-5 escalation lands on awaiting_human; new status joins the parked-reminder set
- `6a67da78` feat: Analytics page — cost dashboard with real data
- `728ea434` feat(lane): unified dead-lane archiver with explicit policy table
- `7a17612f` feat: Agents section collapsible — same pattern as Activity
- `9df7f9b5` feat: Activity as collapsible dropdown above agent cards
- `5f3eef1a` feat: Issue assignment panel + ThoughtsCard z-index fix
- `6c049e46` feat: Active session pulse on timeline drill-down cards
- `c194777a` feat: awaiting_human as a real persistable lane status
- `1a6d4216` feat: Session cost tracking — real token usage + spend per session
- `f841991c` feat(canvas+voice agent): Whisper on agent path always + grid tiles agent cards + GA SDP URL in contract
- `b1018474` feat: Connected session panel with live SVG bezier connector
- `9c32fad8` feat: wedge-timeout stuck launching lanes to awaiting_orchestrator
- `75290f04` feat: register kill_escalated + no_session_binding lane-event verbs; roadmap rock-1 delivered
- `9bc30cef` feat: Timeline drill-down — double-click for per-agent breakdown
- `5c43c1d3` feat: Clickable PR diff on agent cards — opens PR viewer in Canvas
- `a1c0ce1a` feat: session-binding fault detector
- `63963edc` feat: WS-driven AgentPanel + TitleBar status dot + full dedup (-6)
- `7c83deca` feat: single guarded prune gate for all worktree deletions (Rock 1 item 3)
- `e859da18` feat: confirmed-kill escalation for stop-packet ( S1)
- `670bee13` perf: Wire WS for diff stats + remove redundant polls
- `1ac9cfe8` feat: wedge-timeouts so parked lanes never park silently (Rock 1 item 2)

## 2026-03-16

- `f2f84d67` feat: Wire WebSocket to desktop chat — real-time streaming
- `49d6e654` feat: persisted idempotency for steer/rerun/reset/dispatch
- `c81120e3` feat: agent runtime agents show their active repo's diff
- `db39127f` feat: o8 Relay v1 desktop connector + wiring, R3 docs (WIP→complete)
- `43e2b39d` feat: Live Diffs for all 3 runtimes + UX fixes
- `43a2575e` feat: o8 Relay v1
- `e648662e` feat: Live Diffs — beautiful real-time code change viewer
- `a10e4047` feat: wire process crash capture into ws-server + defensive WebSocketServer error handler
- `5d3075c8` feat: Live Agent Output panel + agent card pulse
- `74cdb75b` feat: terminal-host process seam for ws-server PTYs ( follow-up)
- `5f27f47a` feat: add release rollback script
- `94c26159` feat: Real diff stats on main + real timeline activity bars
- `11118fe3` feat: updater safety check skips pulled releases before applying an update
- `0fbccc8b` feat: Real context % for agent runtime sessions + diff stats
- `4a8ddf13` feat: early-boot crash capture in the packaged server wrapper
- `10cf8619` feat: capture server + renderer crashes into the crash store
- `d9b41f4f` feat: local crash capture store + opt-in uploader
- `0622226b` feat: Wire real workspace data — PR status + diff stats on agent cards
- `4ca2b0fc` feat: add opt-in crash-report setting (Privacy) to operator defaults
- `54549618` feat: agent runtime sidebar chat
- `48c7e035` feat: event-loop lag watchdog for ws-server ( follow-up)
- `ce6ea21c` feat: agent runtime transcript — read session JSONL into sidebar
- `8edbfe16` feat: voice agent Agent Mode desktop half
- `3fbfd2c6` feat: Smart naming on collapsed card dots too

## 2026-07-07

- `b88dab6f` feat: add canvas file card editor gutter
- `893de1aa` feat: Better naming in agent cards
- `edafbbca` feat(canvas): chrome-aware, center-gathered card placement
- `7e177ece` feat: agent runtime sidebar chat — send messages via CLI print mode
- `135b2901` feat(canvas): justified-row form-fit grid
- `fef1a678` feat: agent runtime synthetic sessions for unmatched live processes
- `80ddb4f6` feat: canvas keyboard zoom + uniform card body text scale
- `8a67d35e` feat: agent runtime sessions appear in fleet with live PID detection
- `9319116e` feat: canvas agent cards go live
- `b579ca74` feat: Status-grouped agent cards + Apple design polish
- `b3def2a8` feat(canvas+voice agent): voice presence
- `662ead41` feat: Full-size agent cards with everything visible
- `743dd350` feat(proxy): Deepgram Nova-3 primary transcribe arm on /v1/transcribe
- `d6b4ac39` feat: Show heartbeat intervals on agent cards (read-only)
- `25bf6087` feat: STT latency harness
- `6634243c` feat: Agents tab in Settings — fleet dashboard with model editing
- `cc317d43` feat: Groq configuration field in Settings → Voice → Transcription
- `5572534e` feat: Merge WorkspacesPanel into AgentPanel — unified view
- `8c2f6749` feat: wire local transcription first in the whisper ladder
- `f857ea13` feat: WorkspacesPanel — status-grouped workspace cards
- `dd58879f` feat: on-device transcription tier for Apple Silicon
- `ae1aeef7` feat: Cmd+K keyboard shortcut to toggle Thoughts Card
- `a953e623` feat: choreograph canvas card spawns
- `231ecf00` feat: Context-aware suggestions in Thoughts Card
- `5fe79f38` feat: dictation polish default → AI provider-2.5-flash-lite
- `508b34b3` feat: Agent picker in Task chat — route to any agent
- `7c2b2d2d` feat: skip Whisper re-transcription under 12 words
- `4d921c15` feat: Approval routing in Thoughts Card + test simulation
- `fe3a4e17` feat: Whisper via Groq
- `c5baa97f` feat: Task mode — mini chat inside Thoughts Card
- `1d657bb3` feat: polish model overridable via polish_model dictation-config key
- `2cef4fc3` feat: Thoughts Card — Issue vs Task modes + resize fix
- `81e7862d` feat: move speak-selection chord Ctrl+Shift+S → Ctrl+Shift+R (operator: S kept colliding with muscle memory; R = Read, no default collisions)
- `ff5e6d1b` feat: Thoughts Card — resize handles + agent connection
- `2ca0cfbb` feat: spawned-agents hover card v1
- `818e1a6d` feat: Thoughts Card — floating glass command surface
- `f9362fac` feat: packet cards outcome-first
- `00802a96` feat: Settings page with GitHub connection status
- `7b5a14ab` feat: Intent Canvas V0 — Fleet Command Center in workspace
- `c69541e8` feat(unknowns): opt-in buy-in doc on merge
- `6da96c2b` feat: SessionTimeline Phase 1 — hover scrubber + real data API
- `01ace93f` feat: Timeline Expanded View — full session replay in Canvas
- `bf8c66e6` feat: SessionTimeline V0 — agent activity replay bar
- `fde60e91` feat(unknowns): clarify-first interview before dispatch
- `b9e4f6d3` feat: TitleBar window controls — sidebar/back/fwd/bottom/chat/settings
- `0146dedf` feat: TitleBar search is now live UniversalSearch + red settings gear
- `83914aac` feat(unknowns): HTML packet explainer + quiz-gated human approve
- `0c0e6313` feat: TitleBar
- `f5263e84` feat: Desktop NavRail
- `23a6d291` feat(unknowns): worker deviations log surfaced at review
- `16a2b8ca` feat: Session Info Sheet
- `57b0835b` feat: reviewer backend split
- `e54a7db8` feat: Universal search
- `d78ba854` feat: mobile parity AGENTS
- `df7367b3` feat: Proactive alert system — engine, context, bell, tray, toast
- `6a5fe067` feat: canonical mobile fleet projection
- `4419a11a` feat: REST API resilience
- `e214e6c3` feat: mobile review units with explicit authority

## 2026-03-15

- `b63f3eff` perf: gateway REST API client — 23ms vs 38s CLI cold-start
- `18c90fc2` feat: Heat map top-down view + fix fly-in stale closure
- `377f27c7` feat: Search dropdown with grouped clickable results
- `e4d52e59` feat: Knowledge Graph v3 — double-click fly-in + search fact nodes
- `418ef8f1` feat: Knowledge Graph v2.3 — zoom-aware labels + ambient fireflies

## 2026-07-06

- `8d6caf4b` feat: pair dispatch runtime with orchestrator
- `ffc54c54` feat: Knowledge Graph v2.2 — depth fog + all labels + text polish
- `229377b4` feat: add composite webview MCP verbs
- `b6b6dbc4` feat: Knowledge Graph v2.1 — bar gradients + floor reflections
- `ceb826c2` feat: dispatch agent runtime workers
- `8be40cd0` feat: Knowledge Graph v2
- `c7083850` feat(onboarding): Scan again affordance on the runtime step
- `059b44f2` feat: Auto-refresh Knowledge Graph stats every 60s
- `6719ee53` feat(mcp): smart add box - paste a config, an npx command line, or a URL and it parses itself; manual JSON fields demoted to a disclosure
- `b9da9962` design(composer): run-context chips move up into the empty-state dead space - off the status bar
- `2d45dca2` feat: Replace lava lamp with Interactive 3D Knowledge Graph Explorer
- `baf95396` design(composer): adaptive sits between medium and high in the thinking drawer
- `48c367e3` feat: Memory lava lamp v2

## 2026-07-05

- `9331c782` design(composer): mode picker - Swarm drops Ultracode, honest Solo copy, hover explains each mode
- `3f487938` feat: memory Lava Lamp — living particle visualization
- `3fbbf87d` feat: Image rendering in mobile chat + click-to-expand lightbox
- `4b0d8e0a` feat: Image rendering in chat + click-to-expand lightbox
- `2064acbb` feat(canvas): free tier is Paper-only light/dark - looks, dials, depth, and advanced are founders
- `9e151eec` feat: new o8.app desktop icon
- `638a8a7f` feat: Typing indicator — animated dots while agent is thinking
- `1b42ba67` design(canvas): Mine preset renamed Custom; redundant settings-side glass tuner removed - the canvas panel owns tuning
- `f47ed9f1` feat: Deployment Status (Vercel) + Git Log + Image Preview complete
- `b2d9f013` feat(settings): Canvas keeps Experimental badge; founders-first theme scaffold; instrumentation is internal-only not founder-facing
- `2dc08c3d` feat: Git Log viewer + Image/Asset preview
- `57b3a68c` feat(settings): Diagnostics keeps user-actionable only - recall/loop/demo instrumentation behind Founders, width rhythm fixed
- `ef3c82b4` feat: Issue Creator with AI enhancement (AI provider)
- `67a5f5b0` feat: Global workspace search + PR review comments with diff context
- `72e05c70` feat: CI tab in agent panel
- `1ebf3367` design(settings): project cards collapse to one dense inset group - rows not sub-cards
- `7ef90f9c` feat: Changed file highlighting, clickable files, CI button
- `b4b02339` feat(settings): Founders fast-path Brain status row; casual-chat toggle unsurfaced for beta
- `a1887636` feat: README viewer, CI/GitHub Actions, file diff preview
- `8dc375a4` feat: Stop button + project-scoped data + no auto-transcript popup
- `b3e9d0e0` feat: Project-scoped Issues, PRs, and Files — data follows workspace
- `ead97167` feat(settings): Diagnostics tab on grouped system
- `5d9591dc` feat: PR Review tab + canvas viewer — full GitHub PR detail inline
- `3af091ab` feat: Commit detail viewer — click any commit in Activity tab
- `a2bf7184` feat(settings): Projects tab on grouped system
- `0b305939` feat: Agent panel groups by workspace — matches chat session picker
- `19b82c0b` feat: Show all agents including agent runtime/agent runtime in agent panel
- `652fabef` feat(settings): CLI usage meters in quick drawer are Founders-mode content
- `352b261c` feat: Issue detail full-width + diff opens in canvas tab
- `4cde921d` feat(settings): Voice keeps app-level only - voice agent owns polish/dictionary/audio; new voice agent settings row opens his window
- `f9a3f16a` design(settings): Local models on grouped shell, MCP client row icon tiles
- `ac13ffe7` feat: Drag-and-drop + paste + click-to-attach files in desktop chat
- `b7a1c7da` feat(settings): drop voice History from o8 settings - voice agent owns it (double-tap the dock)
- `86d5fbac` feat: Vertical drag handle for canvas — resize workspace/canvas split
- `016b20c8` design(settings): Connectors bar-raise - icon tiles, casing, ghost buttons
- `1fdb67f8` feat(settings): Dispatch tab on grouped system - Founders mode holds the extras
- `508f8525` feat: Contextual Canvas — bottom-half tabbed workspace
- `b4b2d9af` feat: Click agent surface → switches chat to that session
- `0b649b0c` feat(settings): MCP + Connectors tabs on grouped system
- `c1135d56` feat: Agent cards v2
- `6da8da9c` design(settings): About polish - icon tiles, product casing, grouped report-issue form
- `653a1829` feat: Proper markdown rendering in issue modal
- `ab157be0` feat: Light theme + clickable issues with glass modal
- `611fbc2e` feat(settings): About tab on grouped system
- `e65be2d0` feat: Three-column layout — Agent Panel | Workspace | Chat
- `6ab46211` feat: Agent Command Center
- `e71d2edd` feat: Glass diff modal
- `9c27c5e7` feat(settings): Plan & Billing tab on grouped system
- `e4690cb7` feat: Draggable compose bar — resize input height by dragging up
- `2c697aa0` feat: Glass modal for Mermaid diagrams — expand, zoom, pan
- `beedb8ac` feat: Mermaid diagrams on mobile — same o8 frost theme
- `2d73fdb7` feat(settings): Mobile pairing tab on grouped system
- `0d87fd2c` design(settings): palette-aware accent - lighter blue active states in dark mode
- `8c1f6b55` feat: Styled CodeBlock + Mermaid diagram viewer
- `87f530db` feat(settings): Account tab on grouped system
- `276067e0` feat: Transport controls — message actions morph during playback
- `a3d7165f` feat(settings): Voice tab on grouped system; dictation moves Appearance -> Voice
- `46bdeee9` feat(settings): inset-grouped primitives + Appearance pilot (mobile settings style port,)
- `1b17287b` feat: changelog attributes o8-merged work
- `0c91779a` feat: Point-to-Play
- `f0c24f64` feat: TTS Engine + Message Action Bar — Play/Copy/Retry on every message
- `f1cd6bf7` feat(analytics): roll top-accounts up by person + label with GitHub handle
- `8be1edbe` feat(entitlement): link this install to the account on sign-in (device rollup)
- `1338f05e` feat: Desktop chat header — exact mobile TopBar clone
- `0c133401` feat(analytics): Phase 2
- `575541bd` feat: Desktop chat sidebar — mobile-identical chat on Dashboard v1
- `9560da73` feat: Dashboard v1
- `2b53d21f` feat: wire o8 v1.2.5 fixes — fact_ids, stale flags, real graph
- `a6bfb253` feat: grouped squad picker with expand/collapse
- `0267dcd1` feat: orchestrator crash-survival — detached turns + in-flight rebind [via-o8]
- `1684294b` feat(analytics): count real users (distinct accounts), not install churn
- `56394953` feat(license-server): return today's managed-Brain usage on /account/license
- `4b7698b2` feat: native shell v2 desktop shell
- `09d43570` feat(status-bar): Founding Operator serial-chip badge by the ?
- `9af1036a` feat: squad picker dropdown on TopBar title tap

## 2026-07-04

- `f3712756` feat(license-server): store GitHub handle from checkout metadata as founder displayName
- `e31ca632` feat: wire memory surfaces into shell
- `8dcd7f53` feat: agent runtime is a first-class in-UI orchestrator [via-o8]
- `6f2b969f` feat: memory Integration — all 8 issues (-)
- `8433a523` feat: 'o8 app restart' + auto-apply updates when idle [via-o8]

## 2026-03-14

- `fff88386` feat: Phase 2
- `10ec0e4b` feat: mission registry core [via-o8]
- `f41508ca` feat: worktree isolation Phase 1
- `c773f3d9` feat: universal runtime adapter contract + agent runtime integration

## 2026-07-03

- `76dc0582` feat: add terse o8 ask answers
- `beaae360` feat: make agent runtime orchestrator brain-first
- `58091a6f` feat: code block rendering — fenced code + tool output cards
- `84d0309a` feat: add quick docs drawer for operator config files
- `ae4290f3` feat: native markdown table rendering — beautiful HTML tables in chat view

## 2026-07-02

- `642e13c1` feat(fable): the decisions-only window — metered-orchestrator mode
- `af6455b7` feat: unified WebSocket — real-time push replaces SSE + polling
- `6078ff69` feat: PWA
- `ae4baf29` feat: virtual scrolling for transcript — DOM bloat eliminated
- `a6564bf4` feat(auth): bake GITHUB_OAUTH_CLIENT_ID into signed builds
- `0143de0f` feat: consolidated sync API — 5 requests → 1
- `95b06c78` feat: prompt enhancement
- `cffa471b` feat: approval primitive
- `b6b0fb4b` perf(workspace): instant skeleton first paint on Workspace tab
- `a28dbb33` feat: cost dashboard
- `9360ccbc` feat: wire json-render Renderer into mobile shell
- `ac850ea6` feat: json-render integration
- `8dc50134` perf(workspace): changes-only snapshot skips gh network calls
- `04965e55` feat: agent runtime chat parity
- `9ae95bd7` perf(o8): voice-playback line highlighting — reads the spoken line + scroll-follows
- `4a282df2` feat: seamless agent runtime chat
- `f69d6eba` perf(o8-panel): pre-warm the spec reviewer on pane-open so the first review is instant
- `2cfbf887` feat: auto-switch to launched agent runtime session
- `36708cf2` feat(o8): launch-polish batch
- `9d8aa6bb` feat: clean agent runtime chat view
- `ea09b713` feat: discovered agent runtime session transcript
- `07f0dcd7` feat: live process fallback
- `b5284259` feat(session-rules): Rules chip + tiered popover in the orchestrator composer
- `286f3397` feat: mobile agent runtime launch

## 2026-03-13

- `ce3a5ef7` feat: unified chat for agent runtime sessions
- `6d9cf064` feat: show all agent runtime sessions in squad (no stale filter), dedupe by branch, show branch in pills
- `df9673ac` feat(session-rules): worker inheritance + rules_applied audit event
- `59dd7471` feat: project-grouped squad rail
- `e3abcb80` feat: native streaming
- `02c87908` feat(session-rules): pin active rules into every orchestrator turn
- `2766c248` feat: commit summary card in diff view (zero AI
- `3a295ceb` feat: observable agents
- `267bd64b` feat(session-rules): gated /api/orchestrator/session-rules route
- `53bde190` feat: squad cards
- `5efa10b5` perf: diff view
- `d6e646b9` perf: review-file 10s cache + only poll when diff open, tighter idle behavior
- `33c1b2ff` feat(session-rules): thread-scoped rule store + prompt block
- `f27d88b6` perf: request dedup, 8s inbox cache, 5s transcript cache, round usedPercent, suppress hydration

## 2026-07-01

- `034b406a` feat(collide): label the Collide toggle with a full hover tooltip + aria
- `d6f0f4ad` perf: adaptive polling (20s idle, pause on hidden tab, resume on focus), CSS containment, layout isolation
- `427331ee` feat(orchestrator): warm the orchestrator with a resident-process pool + lockout auto-deny
- `f9c82c32` perf: diff-and-patch transcript + snapshot — eliminate flash on idle polls
- `b0e12c58` feat(targeting): pass tier effort on dispatch + fix inline-issue number (effort→worker 3/3)
- `4384eb8f` perf: skeleton loading, lazy images, send click, API caching (3s transcript, 5s inbox)

## 2026-06-30

- `a04b0a60` feat(targeting): promote Targeting from utility tab to a main tab (polish)
- `8731f592` perf: smooth scroll, message fade-in, optimistic user messages, image caching, typing bubble animation
- `8939b211` feat(targeting): observability logging (step 8)
- `9887ba66` design: red send button + red typing dots — matches hamburger accent
- `06ab6452` feat(targeting): o8_targets MCP tool
- `c9cf14f4` design: solid red menu button, context pressure in bottom bar, doc tab apple redesign
- `b80ec5b3` feat(targeting): difficulty→tier routing + Dispatch button (step 6)
- `ae5b45ef` feat(targeting): cheap-triage-model rationales — the money-shot (step 5)
- `1e30be56` design: full mobile UX pass
- `a631bb00` feat(targeting): triage/action config triads (step 4)
- `2715fee5` design: apple-grade controls sheet + sticky diff files survive compaction
- `e7735cd6` feat(targeting): /api/panel/targets route + Targeting panel surface (step 3)
- `b4ae629d` design: apple-grade diff polish
- `4d6b61fd` feat(targeting): heuristic scorer + score cache (step 2)
- `43d642be` feat(targeting): signal collection for the Targeting Machine (step 1)

## 2026-03-12

- `00c14dbf` feat: surface queued agent runtime turns and clearer mobile send actions
- `5642a499` feat(orchestrator): Collide composer chip + faint→solid proposals UX (Steps 5,6)
- `f7f54ffc` feat: add quick thread switching for mobile agent runtime lane
- `45b9edc6` feat(orchestrator): Collide MoA fusion engine + registration + cap-degrade (Steps 3,4,7,9)
- `b6324594` feat: make owned agent runtime mobile lane feel conversational
- `c3bdc508` feat(orchestrator): two-layer read-only proposer lockout (Collide Step 2)

## 2026-06-29

- `1c835d39` feat(orchestrator): Hermes via a generic ACP backend (Step 3b–3d)
- `7bf408ef` feat: allow owned agent runtime interrupt on mobile
- `7c75d5af` feat(orchestrator): orchestratorBackend setting — makes agent runtime selectable (Step 1)
- `e480039e` feat: preload owned mobile diff context on focus
- `8112edf1` feat(mcp): o8 now configures agent runtime — closes the "any CLI" set (Phase 2)
- `c740a25d` feat: extend owned agent runtime review and resume on mobile
- `96903a20` feat(mcp): o8 now configures the AI provider CLI from the registry (Phase 2)
- `b42b018d` feat: make owned review packets actionable
- `35164e2f` feat(mcp): agent runtime o8 entry from the registry, not passthrough (Step F)
- `4a316a59` feat: add owned agent runtime review packets

## 2026-06-28

- `2775957a` feat: desktop half of mobile inline diff comments ( slice 2)
- `6de73096` feat: surface owned agent runtime watch lane on mobile
- `0578a3c9` feat: STYLEGUIDE.md
- `e1a47bb2` feat: harden owned agent runtime lifecycle and tail views
- `dc221164` feat: add owned agent runtime launch and resume lane
- `6b7ffeea` feat: add runtime action ownership seam
- `d85730b1` feat: Paired-devices settings list with per-device revoke
- `fdc24f56` feat: promote runtime inventory and agent runtime activity detection
- `7217d071` feat: surface local agent runtime runtime discovery in desktop shell
- `b1650ee5` feat: harden mobile operator chrome and review cockpit
- `9f4a52fe` feat: deterministic 4401 close for a revoked device on reconnect
- `6a3cdd20` feat: add panel and terminal shells to mobile queue

## 2026-06-27

- `b15ee985` feat: mobile E2EE channel
- `ffd2e4a6` feat: add mobile per-file review drilldown
- `5ffd89fb` feat: mobile device enrollment + per-device token validation ( stage 1b)
- `add6a8e7` feat: deepen mobile review lane and glass styling
- `90694929` feat: mobile E2EE crypto + per-device token registry foundation ( stage 1a)
- `8ca65c3d` feat: align desktop repo truth with live review state
- `550b8b84` feat: persistent terminals default ON + hide terminal status bar ( stage 5)
- `2e94bb3c` feat: wire direct mobile actions and history
- `d7a077d0` feat: canvas terminals re-attach surviving sessions on restore ( stage 4)

## 2026-03-11

- `bbe5dab3` feat: add mobile control inbox foundation
- `de28c5ad` feat: re-attach surviving dash terminals with scrollback after restart ( stage 3)
- `e63edc8d` feat: wire live agent runtime bridge and workflow review
- `a9d26e96` feat: keep dash terminals alive on detach + bounded orphan GC ( stage 2)
- `868b012d` feat: add native desktop shell wrapper and guardrail surfaces
- `e7065ed5` feat: spawn interactive dash terminals inside terminal, gated ( stage 1)
- `8a8b0775` feat: bootstrap command center shell and runtime contracts
- `0644dd16` feat: default crash-survivable workers ON (kill-test passed on 0.1.512)
- `746bf704` feat: boot re-bind observability + crash-survival contract test ( stage 2)
- `c8f0a3bf` feat: crash-survivable worker spawn, gated (daemon crash-survival stage 1)
- `c1f589d9` feat: worker-context merge approval card + o8 inbox + o8 packet approve-merge ( stages 5b/6)
- `6b7ab567` feat: extract steer-packet route + o8 packet steer (control-plane symmetry stage 4)

## 2026-06-26

- `52748a74` feat(cli): o8 packet reset/retry/rerun/merge-preview (control-plane symmetry stage 3)
- `c0e0e159` feat(cli): o8 mission create/dispatch/status/wait/tail (control-plane symmetry stage 1)
- `3aafbf32` feat(review): pick the best-of-N winner through the governed merge gate + audit
- `d194200d` feat(review): per-candidate merge-gate verdict on the compare matrix
- `0bc0e37b` feat(review): mount the N-up compare matrix as a contextual O8Panel tab
- `3382ae5f` feat(review): N-up comparison diff matrix component (best-of-N)
- `afc71bd8` feat(orchestrator): arm best-of-N fan-out via comparisonModels on create_mission
