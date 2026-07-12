# Changelog

Development activity for o8 — the governance layer for autonomous engineering teams.

We ship high-signal entries only (features + performance wins). Bug fixes, refactors,
and internal chores live in the private engineering log.

---
- `b4022648` feat: o8 agent safety hooks

## 2026-07-12

- `88e3701f` feat(o8-model): tier-tuned system prompts
- `13a8fa38` feat(ui): competing product siphon pass 1
- `00a00211` feat(operator): plan-gated o8 model rails — nemo for free, AI provider for founders
- `7cab6b47` feat(orchestrator): add free o8 chat backend to the composer
- `9dc48663` feat: mobile repo picker for multi-repo chat
- `a66f3403` perf(boot): merge 4 identical capabilities — generate_context! 1665ms -> 971ms
- `5c94ed58` perf(boot): overlap the orphan reap with generate_context! instead of paying it first
- `ac1d1f36` design(status): packetStatusColor failed → brand orange, aligned with the dot family (Q final lock 2026-07-12)
- `9102fafa` design(status): failed joins rejected in the brand orange
- `f6777faa` feat: repo-scoped tool execution + repos API
- `1a2c461b` design(status): idle = Drift
- `82f2395d` design(status): the locked one-canvas family
- `b4354186` design(status): running is always the orbit + rejected wears the failed cross in amber
- `febf7a1c` perf(sidecar): cache V8 bytecode

## 2026-07-11

- `dd462e32` design(motion): 5 awaiting-review candidates in the lab (AI provider bespoke)

## 2026-04-03

- `eaf7ae52` feat: apply file edits on approval approve
- `0563f9fd` design(motion): remove the scan loader from the family (operator cut)
- `6bf9d93c` design(status): failed = the dispatch pixel mark in alarm red — locked
- `0f280979` perf(server): stop loading a browser-automation library before the app answers a request
- `a90e0c8b` perf(boot): trace the pre-window path
- `53c82c13` feat: add github tool for AI provider — gh CLI access
- `7a751104` design(motion): bespoke loader family in the lab
- `be24af3f` perf(boot): record boot-phase timings so cold launch can never silently regress
- `06e33e60` perf(ws): bridge agent-lifecycle to the window event
- `7abfb4ef` perf(spec-pane): stop polling the server for a pane nobody is looking at
- `cdacbba1` perf(ws-server): make the conflict scan event-driven — 45x less idle git work
- `88140fad` feat: expand shell allowlist — npm, npx, node, cargo
- `ce6b1669` perf(motion): drive the sweep dot from the compositor — 9.5% -> 2.2% idle CPU
- `771beff2` perf(render): memoize the orchestrator context; stop animating a full-screen gaussian
- `6e9270f0` perf(worktree): stop the 5-second recursive disk walk that was idling the fans
- `cd24cca4` perf(boot): build the window before the sidecar bootstrap, not after
- `b6a5bff9` perf(boot): one login-shell probe instead of three
- `8bcba207` feat: add create_file tool for AI provider
- `90de23b5` perf(ws-server): stop event-loop wedge from sync git in reconcile + backoff pathological merged-by-ancestry lanes
- `b673d369` feat: syntax-highlighted tool output — expand shows real code colors
- `6a72e85f` perf(prod): stop git-scanning the app's own bundle
- `421cab7e` feat: Apple-style collapsible tool call cards
- `05d923ed` feat(mobile): expose huddle plan in fleet
- `f7363068` perf(dictation): overlap mic open with audio duck instead of serializing
- `751d1e56` feat(files): save edits to any on-disk file, not just registered repos
- `37213a35` feat(files): Files view can open any file on disk, not just registered repos
- `124855a3` feat(files): open Finder files on the surface you're on, not a canvas hijack
- `bc512cb3` feat: AI provider tool execution backend
- `8c95baad` feat(packet): Request changes -> orchestrator; Discard -> soft dismiss (recoverable)
- `4f7fe6d4` feat: compact model selector + fix theme toggle in settings
- `21f478bf` feat(packet): show WHY a review was declined in the decision banner
- `e3c65623` feat: restore light mode with proper theme toggle
- `3b488961` design(status): review-declined = orange o8 dual-pulse (trial)
- `cdfdb548` design(status): Failed pulses (red orb) so it separates from the static rose of rejected
- `31a9dccb` design(status): awaiting-review is a paused grey with a sweep motion, not a color
- `1c06710b` design(status): cool the human-decision dot states off the warm cluster
- `9e18da3a` feat: tool call card renderer components
- `c3a67010` feat(motion-lab): add a Status vocabulary board
- `812ecfa8` feat(packet): tighten the decision banner
- `54e8521a` feat(packet): give a rejected packet a decision banner + stateful dot, and a Discard verb
- `b0b4d50a` feat(merge): give the review beacon a 'rejected' state and stop hygiene packets parking the gate
- `6f03dc21` feat(merge): drop the 'No open PR'/'Open PR' bottom-bar noise
- `9af39728` feat: tool call SSE protocol types and parser
- `f9ac73de` feat(merge): let the bottom-bar review beacon merge, not just view
- `e28fcf3b` feat: theme-aware markdown renderer + light mode code blocks
- `1198271f` feat(rail): surface the branch's PR inline in the workspace rail
- `898d5551` feat: rebrand mobile shell for o8
- `6f81d4dd` design(composer): swap mic and context meter — mic by Send, meter by attach
- `5f579f7d` feat(composer): kill the Fleet/Solo chip — solo vs fleet decided by runtime count
- `8dec8819` feat(composer): thin file-list scrollbar; Rules chip only when rules exist + /rule /rules
- `40b0b831` design(composer): filename-first file attach rows, match highlight, lighter weights
- `e0f42697` design(composer): label Collide as 'Mixture of Agents' in the picker
- `dea51852` feat: rebuild mobile approvals and sidebar surfaces
- `a039464a` design(composer): trigger names the model, not the provider
- `8b4199fd` feat: rebuild mobile approvals and sidebar surfaces
- `51aed567` design(composer): house drawers for models, Extra label, dynamic Collide decider
- `7ec4f4c1` design(composer): effort slider with named tiers, Ultracode top notch arms Swarm
- `e264927d` design(composer): agent runtime-style footer
- `db55ccd4` feat(orchestrator): clarify-first goes silent + auto-arms on a repo's first mission
- `3aa4d16a` feat(ui): retire the permission shield — composers always run full access
- `fcd91ca5` feat: replace custom mobile chat with @assistant-ui/react Thread
- `86c99f16` feat(ui): move add-repo onto the Projects row, slim the footer
- `9cce9754` feat: build mobile assistant-ui thread chat
- `5b9a557d` perf(ui): 60fps panel drags via direct-DOM + footer icon tiers
- `d3f045f6` feat: mobile settings view + decompose monolithic client into focused modules

## 2026-07-10

- `98bd1229` feat(voice agent): control o8 hosted terminals by voice
- `e89b6a65` feat: mobile redesign
- `289f3a09` feat: mobile settings view + decompose monolithic client into focused modules
- `0576fce9` feat: mobile settings view + decompose monolithic client into focused modules
- `af1a7152` feat: mobile settings view + decompose monolithic client into focused modules
- `77e61810` feat(voice): main-process capture defaults ON for Intel Macs on Sequoia
- `3b7046b8` feat: mobile settings view + decompose monolithic client into focused modules
- `b44386f9` feat: mobile settings view + decompose monolithic client into focused modules
- `9ebbc383` feat: add mobile settings view to glass sidebar

## 2026-04-02

- `17f58ba7` feat: full glass input field + glass send button + scroll-to-bottom arrow
- `f6987cd0` feat(voice): main-process microphone capture
- `a4e0d289` feat: glassmorphic buttons
- `75aa5d29` feat: collapsible code blocks with diff coloring and file path labels
- `ec45fa7b` feat: TTS play button on assistant messages + AI provider-style input bar
- `c2327191` feat: starred + recents sections in sidebar, revert dots back to long-press
- `ca8ad50c` feat: long-press context menu on chat list — star, rename, delete
- `d63d2172` feat: AI provider-style chat list view

## 2026-07-09

- `07dab129` feat: merge-gate test replay + decoupled worktree capture trail
- `500dc19b` feat: AI provider-style message rendering + mobile markdown for code blocks
- `ab13f9a3` perf: bound mobile worktree diff transport
- `8763c403` feat: wire mobile chat to real chat history store + conversation list in sidebar
- `8619b451` perf: page mobile chat history
- `7a1aef00` feat: AI provider-style sliding sidebar + AI provider chat on mobile
- `24056205` perf: stream revisioned mobile inbox deltas
- `3c40bb84` feat: add npm run tunnel for remote mobile access via Cloudflare
- `5e016418` feat(telemetry): native crash capture (SIGSEGV/SIGABRT/SIGBUS/stack-overflow) via minidumps
- `3b1c52ce` perf: prefetch mobile inbox on server
- `81fc33d2` feat(desktop): explicit Open With UTIs
- `a6aed2a0` perf: break route barrel imports
- `ba662510` perf: switch dev to turbopack and lazy init db
- `14a417c0` feat: bound onAgentCompletion retry loop
- `7d82733a` feat: add attempt learning persistence
- `dfea5ff4` feat: subject-gone TTL fallthrough
- `acb9bb3c` feat: add low-risk auto-approve policy
- `998b96e4` feat: add packet self-review confidence gate
- `d2f42e86` feat(desktop): Finder "Open With → o8" opens land in the workspace on the default IDE surface

## 2026-07-08

- `1333fb23` feat(canvas): IDE-parity transcript rendering + honest lifecycle clocks in agent cards
- `6e2a71e6` feat(telemetry): Sentry crash/error reporting across all three desktop layers — dormant without a DSN
- `fb01941f` feat(voice): voice agent Spatial Context
- `56be609e` feat: objective exit criteria
- `471225d0` feat: compact Apple-style dropdown menu, no full-screen overlay
- `6f31460d` feat(entitlement): View as Free dev switch — founder--gated, min-clamped
- `bc19c545` feat: AI provider-style tool cards in mobile chat
- `4360e99a` feat(voice): morph composer into live agent partials + vary voice agent ack lingo
- `9aa6dc9a` feat(voice): window-aware partials HUD anchor + opt-in Fn dictation HUD
- `d1fd1f65` feat(voice): outside-the-window live agent-transcription HUD
- `2da95924` feat: wedge layer-5 escalation lands on awaiting_human; new status joins the parked-reminder set
- `4228c8bb` feat: organize mobile sessions by type — Chats, Sessions, Missions
- `728ea434` feat(lane): unified dead-lane archiver with explicit policy table
- `84f79425` feat: warm grey + light beige palette across all 30 mobile surfaces
- `5631e6c4` feat: slim compose bar
- `73ba8564` feat: in-process mutex on orchestrator-state.json
- `c194777a` feat: awaiting_human as a real persistable lane status
- `f841991c` feat(canvas+voice agent): Whisper on agent path always + grid tiles agent cards + GA SDP URL in contract
- `4b610bbf` feat: merge conflict escalation via approval card
- `9c32fad8` feat: wedge-timeout stuck launching lanes to awaiting_orchestrator
- `75290f04` feat: register kill_escalated + no_session_binding lane-event verbs; roadmap rock-1 delivered
- `16818234` feat: persist workflow watcher state to SQLite
- `a1c0ce1a` feat: session-binding fault detector
- `7c83deca` feat: single guarded prune gate for all worktree deletions (Rock 1 item 3)
- `e859da18` feat: confirmed-kill escalation for stop-packet ( S1)
- `dc3b6355` feat: orchestrator session health monitor — 90s timeout + auto-recovery
- `1ac9cfe8` feat: wedge-timeouts so parked lanes never park silently (Rock 1 item 2)
- `77a08e40` feat: persistent SQLite-backed review queue
- `49d6e654` feat: persisted idempotency for steer/rerun/reset/dispatch
- `db39127f` feat: o8 Relay v1 desktop connector + wiring, R3 docs (WIP→complete)
- `43a2575e` feat: o8 Relay v1
- `a10e4047` feat: wire process crash capture into ws-server + defensive WebSocketServer error handler
- `32fa1ce8` feat: inline mission creation — no GitHub dependency
- `74cdb75b` feat: terminal-host process seam for ws-server PTYs ( follow-up)
- `5f27f47a` feat: add release rollback script
- `6481fce0` perf: mobile page is now client-only — zero server-side bootstrap
- `11118fe3` feat: updater safety check skips pulled releases before applying an update
- `4a8ddf13` feat: early-boot crash capture in the packaged server wrapper
- `10cf8619` feat: capture server + renderer crashes into the crash store
- `d9b41f4f` feat: local crash capture store + opt-in uploader
- `294efd58` perf: mobile optimization
- `4ca2b0fc` feat: add opt-in crash-report setting (Privacy) to operator defaults
- `48c7e035` feat: event-loop lag watchdog for ws-server ( follow-up)
- `79698cec` feat: copy AI provider mobile session list — clean rows, status groups, FAB
- `8edbfe16` feat: voice agent Agent Mode desktop half

## 2026-07-07

- `b88dab6f` feat: add canvas file card editor gutter
- `edafbbca` feat(canvas): chrome-aware, center-gathered card placement
- `bf22b7de` feat: mobile new chat — launch LLM session from phone
- `135b2901` feat(canvas): justified-row form-fit grid
- `7da466ac` feat: mobile wave 4
- `80ddb4f6` feat: canvas keyboard zoom + uniform card body text scale
- `c7260974` feat: purge 4,277 lines of remodex CSS + remaining className from mobile
- `9319116e` feat: canvas agent cards go live

## 2026-04-01

- `d9e2df4d` feat: mobile waves 2+3
- `e5b78197` feat: mobile wave 1
- `b3def2a8` feat(canvas+voice agent): voice presence
- `276c93b8` perf: P1 bundle + network optimizations
- `743dd350` feat(proxy): Deepgram Nova-3 primary transcribe arm on /v1/transcribe
- `a648a890` perf: P0 performance fixes
- `25bf6087` feat: STT latency harness
- `cc317d43` feat: Groq configuration field in Settings → Voice → Transcription
- `8c2f6749` feat: wire local transcription first in the whisper ladder
- `dd58879f` feat: on-device transcription tier for Apple Silicon
- `e161191d` feat: wire recommendMergeOrder() into merge pipeline
- `a953e623` feat: choreograph canvas card spawns
- `5fe79f38` feat: dictation polish default → AI provider-2.5-flash-lite
- `7c2b2d2d` feat: skip Whisper re-transcription under 12 words
- `56443ba9` feat: merge gate file size block + operator override
- `fe3a4e17` feat: Whisper via Groq
- `a9961db6` feat: add FILE_SIZE_WAIVERS for layout orchestrators and multiplexers
- `1d657bb3` feat: polish model overridable via polish_model dictation-config key
- `81e7862d` feat: move speak-selection chord Ctrl+Shift+S → Ctrl+Shift+R (operator: S kept colliding with muscle memory; R = Read, no default collisions)
- `2ca0cfbb` feat: spawned-agents hover card v1
- `e7dd4b3b` feat: skeleton map file size check at dispatch time
- `f9362fac` feat: packet cards outcome-first
- `51227542` feat: InfinityGlow animated status indicator for agent cards
- `c69541e8` feat(unknowns): opt-in buy-in doc on merge
- `551e9952` feat: FTUX progressive feature reveal
- `fde60e91` feat(unknowns): clarify-first interview before dispatch
- `43dd5381` feat: FTUX first-merge celebration state
- `83914aac` feat(unknowns): HTML packet explainer + quiz-gated human approve
- `366bd6fa` feat: FTUX mobile QR prompt
- `23a6d291` feat(unknowns): worker deviations log surfaced at review
- `57b0835b` feat: reviewer backend split
- `34f9348e` feat: FTUX First Mission Card contextual CTA
- `d78ba854` feat: mobile parity AGENTS
- `6a5fe067` feat: canonical mobile fleet projection
- `e214e6c3` feat: mobile review units with explicit authority
- `932ee1cb` feat: FTUX empty states for all dashboard panels

## 2026-07-06

- `8d6caf4b` feat: pair dispatch runtime with orchestrator
- `bd6c7c8a` feat: FTUX warm dashboard state
- `229377b4` feat: add composite webview MCP verbs
- `ceb826c2` feat: dispatch agent runtime workers
- `c7083850` feat(onboarding): Scan again affordance on the runtime step
- `23b1bdb6` feat: FTUX personalized chat greeting
- `6719ee53` feat(mcp): smart add box - paste a config, an npx command line, or a URL and it parses itself; manual JSON fields demoted to a disclosure
- `2bba0bfd` feat: workflow transition WebSocket channel
- `b9da9962` design(composer): run-context chips move up into the empty-state dead space - off the status bar
- `b79ae61f` feat: workflow transition WebSocket channel for real-time status streaming
- `baf95396` design(composer): adaptive sits between medium and high in the thinking drawer
- `0dd778db` feat: migrate approval store from JSON to SQLite

## 2026-07-05

- `9331c782` design(composer): mode picker - Swarm drops Ultracode, honest Solo copy, hover explains each mode
- `3b8deb9f` feat: migrate approval store from JSON to SQLite

## 2026-03-31

- `4f261749` feat: migrate lane registry from JSON to SQLite — kill cross-process clobber
- `fd0baca9` feat: sprint 6 wave 3
- `2064acbb` feat(canvas): free tier is Paper-only light/dark - looks, dials, depth, and advanced are founders
- `a18bc0af` perf: sprint 6 wave 2
- `9e151eec` feat: new o8.app desktop icon
- `e3321db6` feat: workflow watcher coordination
- `1b42ba67` design(canvas): Mine preset renamed Custom; redundant settings-side glass tuner removed - the canvas panel owns tuning
- `67d7083f` feat: route Audit Log to workspace tab instead of Inspector panel
- `b2d9f013` feat(settings): Canvas keeps Experimental badge; founders-first theme scaffold; instrumentation is internal-only not founder-facing
- `0386c4b0` feat: sprint 5
- `57b3a68c` feat(settings): Diagnostics keeps user-actionable only - recall/loop/demo instrumentation behind Founders, width rhythm fixed
- `72ddf139` feat: sprint 4
- `9fb9baa7` feat: sprint 3
- `26592858` feat: sprint 2
- `1ebf3367` design(settings): project cards collapse to one dense inset group - rows not sub-cards
- `b4b02339` feat(settings): Founders fast-path Brain status row; casual-chat toggle unsurfaced for beta
- `ff3a21c2` feat: structured multi-file diff in approval review gate
- `ead97167` feat(settings): Diagnostics tab on grouped system
- `fe2a36d0` feat: workflow watcher triggers workflow transition
- `a2bf7184` feat(settings): Projects tab on grouped system
- `9eb53b0b` feat: agent runtime PreToolUse hook script for policy enforcement
- `652fabef` feat(settings): CLI usage meters in quick drawer are Founders-mode content
- `4cde921d` feat(settings): Voice keeps app-level only - voice agent owns polish/dictionary/audio; new voice agent settings row opens his window
- `f9a3f16a` design(settings): Local models on grouped shell, MCP client row icon tiles
- `df5857f5` feat: one-shot send-as-task from ThoughtsCard chat
- `b7a1c7da` feat(settings): drop voice History from o8 settings - voice agent owns it (double-tap the dock)
- `016b20c8` design(settings): Connectors bar-raise - icon tiles, casing, ghost buttons
- `f388970c` feat: server-side packet auto-dispatch loop
- `1fdb67f8` feat(settings): Dispatch tab on grouped system - Founders mode holds the extras
- `24173f2f` feat: integrate native shell-plugin-mcp for native app automation in dev builds
- `3e409e61` perf: JSONL tail-reads, cache-first actions, fingerprint optimization, sleep removal
- `947b47ac` perf: strip JSON pretty-printing from MCP server responses

## 2026-03-30

- `a58cd341` feat: native shell vibrancy polish, operator bridge fix, ghost session eviction, right panel cleanup
- `0b649b0c` feat(settings): MCP + Connectors tabs on grouped system
- `f008f584` feat: operator MCP bridge — agent runtime as o8 control surface
- `6da8da9c` design(settings): About polish - icon tiles, product casing, grouped report-issue form
- `7644e08a` feat: workspace UI overhaul
- `125caca2` feat: UI polish pass

## 2026-03-29

- `52b9ba3b` feat: o8 brand mark — three-circle logo in accent blue
- `611fbc2e` feat(settings): About tab on grouped system
- `b1507b5a` feat: orchestrator loop — plan, delegate, review, approve
- `234f8c00` feat: governance engine
- `8b973087` feat: refine o8 product brief from 3-turn brainstormer session
- `9c27c5e7` feat(settings): Plan & Billing tab on grouped system
- `75c90b23` feat: add REVIEW.md, agent delegation table in project rules, update agent descriptions
- `ca15b5ce` feat: add o8 product brief, update project rules with orchestrator model, create subagents
- `6c5d722f` feat: scrollable workspace lane tabs with transparent arrow overlays
- `2d73fdb7` feat(settings): Mobile pairing tab on grouped system
- `cf6807ee` feat: tab scroll arrows, tool cards in Thoughts, right panel defaults to review
- `0d87fd2c` design(settings): palette-aware accent - lighter blue active states in dark mode
- `df8bff52` feat: workspace tab shows issue context + diagnostics settings tab (,)
- `4a090261` feat: one-click issue launch icon + lane-scoped review rail (,)

## 2026-03-28

- `6fc1e9c8` feat: add orchestrator MCP server, delegation tools, and agent supervisor
- `87f530db` feat(settings): Account tab on grouped system
- `281a4906` feat: add GitHub issues to ThoughtsCard Mission Control

## 2026-03-27

- `463ff8de` feat: add translucent desktop dark mode shell
- `aac8e09d` feat: harden workspace shell and terminal sessions
- `5c765358` feat: add o8 board and restore system-wide timeline
- `a3d7165f` feat(settings): Voice tab on grouped system; dictation moves Appearance -> Voice
- `46bdeee9` feat(settings): inset-grouped primitives + Appearance pilot (mobile settings style port,)
- `578e411e` feat: move repo selection into workspace headers
- `1b17287b` feat: changelog attributes o8-merged work

## 2026-03-26

- `24b6ae1f` feat: fix branch-scoped review flow
- `c0eacdba` feat: turn workspace side panel into repo companion surface
- `f1cd6bf7` feat(analytics): roll top-accounts up by person + label with GitHub handle
- `6cf89a78` feat: route repo surfaces into workspace tabs
- `8be1edbe` feat(entitlement): link this install to the account on sign-in (device rollup)

## 2026-03-25

- `ec9aee42` feat: tighten workflow lifecycle and operator recovery
- `0c133401` feat(analytics): Phase 2
- `0981e995` feat: refine desktop dark mode theme
- `39c7bb54` feat: migrate ide to fact-backed o8 recall
- `153b76ec` feat: enrich workspace cli chat parity
- `2f2b0fcf` feat: polish timeline and workspace chat surfaces
- `bf8d4e89` feat: scope agent surfaces to ide sessions
- `0267dcd1` feat: orchestrator crash-survival — detached turns + in-flight rebind [via-o8]
- `ca06e24b` feat: route workspace launches and github flows through broker
- `1684294b` feat(analytics): count real users (distinct accounts), not install churn

## 2026-03-24

- `eab62fb3` feat: ship github app broker foundation
- `56394953` feat(license-server): return today's managed-Brain usage on /account/license

## 2026-03-23

- `d655dabc` feat: Unified ContextualPanel — canvas tabs merged into bottom panel
- `a22ec01e` feat: Drop bundled Node (prerequisite) + bundle memory binary
- `09d43570` feat(status-bar): Founding Operator serial-chip badge by the ?
- `5bb7f329` feat: WS server bundled in native shell app — terminals + chat work in production
- `36cade24` feat: GitHub App authentication — 5,450 req/hr, auto-refreshing tokens

## 2026-07-04

- `f3712756` feat(license-server): store GitHub handle from checkout metadata as founder displayName
- `1111c6e9` feat: GitHub PAT support + config lives in the user data dir/
- `c5085de2` feat: Bundle Node.js inside the app — zero-config for users
- `a9233f80` feat: Standalone server bundling for native shell — real distributable app
- `41f1f02f` feat: Inline edit
- `658912fb` feat: 'Environments' filter in files dropdown — quick access to .env files
- `8dcd7f53` feat: agent runtime is a first-class in-UI orchestrator [via-o8]
- `0d8a7365` feat: Inline AI widget

## 2026-03-22

- `39ee35a4` feat: Tab autocomplete — AI ghost text suggestions while typing
- `20074d83` feat: Cmd+E inline AI edit
- `e813ed40` feat: Resizable files panel — drag handle between files and activity
- `67887fda` feat: Monaco Frost v2
- `8433a523` feat: 'o8 app restart' + auto-apply updates when idle [via-o8]
- `c9938b4e` feat: Monaco 'o8 Frost' theme — icy light blue editor
- `6ecb9fc4` feat: Monaco Editor v3 — full IDE-grade file editing
- `96449e5f` feat: File editor v2
- `dca28235` feat: Inline file editor with Cmd+S save + files default to Changes view
- `048d3039` feat(branding): add o8 logo component + concept assets
- `610d71af` feat: In-app update banner + landing page + version sync
- `10ec0e4b` feat: mission registry core [via-o8]
- `3866ea48` feat: native shell updater + GitHub Actions release workflow

## 2026-03-21

- `d98a2ae3` feat: add sidebar runtime capability layer
- `9eaeb618` feat: refine sidebar approval polish
- `50541b1d` feat: polish sidebar approvals and file actions

## 2026-07-03

- `76dc0582` feat: add terse o8 ask answers
- `7f4399cd` feat: polish sidebar file actions
- `beaae360` feat: make agent runtime orchestrator brain-first
- `40d53b58` feat: add sidebar source actions
- `84d0309a` feat: add quick docs drawer for operator config files
- `9002c69e` feat: unify sidebar active turn surface

## 2026-07-02

- `642e13c1` feat(fable): the decisions-only window — metered-orchestrator mode
- `51e28207` feat: show sidebar web source links
- `9e8e44c4` feat: enrich desktop sidebar source context
- `6347fa0f` feat: refine desktop sidebar runtime turns
- `a6564bf4` feat(auth): bake GITHUB_OAUTH_CLIENT_ID into signed builds
- `0bbef267` feat: Conflict Resolution UI in Memory settings tab
- `7acca95f` feat: polish desktop sidebar runtime chat
- `b6b0fb4b` perf(workspace): instant skeleton first paint on Workspace tab
- `05d04422` feat: add intent board v1
- `6e79944a` feat: unify desktop thoughts and sidebar chat rendering
- `8dc50134` perf(workspace): changes-only snapshot skips gh network calls
- `c1af442d` feat: Codebase seeding engine — solve cold start for new users
- `9ae95bd7` perf(o8): voice-playback line highlighting — reads the spoken line + scroll-follows
- `f69d6eba` perf(o8-panel): pre-warm the spec reviewer on pane-open so the first review is instant
- `36708cf2` feat(o8): launch-polish batch
- `78c8fc8c` feat: Unified chat send route + type fixes
- `b5284259` feat(session-rules): Rules chip + tiered popover in the orchestrator composer
- `3714eb17` perf: WebSocket RPC replaces CLI fallback — agents load in <500ms
- `b6f3b5da` feat: First Launch Setup Wizard — blue glass onboarding flow
- `df9673ac` feat(session-rules): worker inheritance + rules_applied audit event
- `7097222a` feat: Setup detection + config API for first-launch wizard
- `02c87908` feat(session-rules): pin active rules into every orchestrator turn
- `57c08ba1` feat: Graceful degradation when gateway unreachable
- `0ef0b44c` feat: Production polish
- `267bd64b` feat(session-rules): gated /api/orchestrator/session-rules route
- `af7c99cb` feat: Blocklist guard for public changelog + project rules rule

## 2026-03-20

- `248dbb62` feat: context-aware recursive compaction — three-pass smart compression
- `3a510e6d` feat: project rules
- `33c1b2ff` feat(session-rules): thread-scoped rule store + prompt block
- `3514bbf2` feat: Chat compaction
- `cf171d8b` feat: File system tools

## 2026-07-01

- `034b406a` feat(collide): label the Collide toggle with a full hover tooltip + aria
- `698ce992` feat: Terminal command tool with three-tier safety + editable approval
- `427331ee` feat(orchestrator): warm the orchestrator with a resident-process pool + lockout auto-deny
- `b0e12c58` feat(targeting): pass tier effort on dispatch + fix inline-issue number (effort→worker 3/3)

## 2026-06-30

- `a04b0a60` feat(targeting): promote Targeting from utility tab to a main tab (polish)
- `8939b211` feat(targeting): observability logging (step 8)
- `2e69153a` feat: Chat-optimized recall — structured facts over raw chunks
- `06ab6452` feat(targeting): o8_targets MCP tool
- `b80ec5b3` feat(targeting): difficulty→tier routing + Dispatch button (step 6)
- `ae5b45ef` feat(targeting): cheap-triage-model rationales — the money-shot (step 5)
- `a631bb00` feat(targeting): triage/action config triads (step 4)
- `84e34172` feat: Phase B
- `e7735cd6` feat(targeting): /api/panel/targets route + Targeting panel surface (step 3)
- `d5eea79d` feat: memory settings
- `4d6b61fd` feat(targeting): heuristic scorer + score cache (step 2)
- `18bead76` feat: memory settings tab — configure models, view stats
- `43d642be` feat(targeting): signal collection for the Targeting Machine (step 1)
- `44cb6d5b` feat: memory recall — Phase A
- `5642a499` feat(orchestrator): Collide composer chip + faint→solid proposals UX (Steps 5,6)
- `fa565a22` feat: Steve Jobs polish — 5 UX refinements for LLM chat
- `45b9edc6` feat(orchestrator): Collide MoA fusion engine + registration + cap-degrade (Steps 3,4,7,9)
- `740c2ef9` feat: Unified input container — model picker moves to bottom toolbar
- `c3bdc508` feat(orchestrator): two-layer read-only proposer lockout (Collide Step 2)
- `4554694e` feat: GitHub tools for LLM chat

## 2026-06-29

- `1c835d39` feat(orchestrator): Hermes via a generic ACP backend (Step 3b–3d)
- `40a9b698` feat: Syntax highlighting, thinking text style, citation hover cards
- `7c75d5af` feat(orchestrator): orchestratorBackend setting — makes agent runtime selectable (Step 1)
- `8112edf1` feat(mcp): o8 now configures agent runtime — closes the "any CLI" set (Phase 2)
- `f6e81b5e` feat: Chat history sidebar — search, star, open in new tab
- `96903a20` feat(mcp): o8 now configures the AI provider CLI from the registry (Phase 2)
- `8aa2868a` feat: Streaming code highlights, keyboard shortcuts, conversation forking
- `35164e2f` feat(mcp): agent runtime o8 entry from the registry, not passthrough (Step F)
- `b0e064f1` feat: Inline citations, slash commands, Run in Terminal
- `09e2f7b9` feat: Code block actions — Apply to File + Open in Canvas

## 2026-06-28

- `2775957a` feat: desktop half of mobile inline diff comments ( slice 2)
- `c1a749fe` feat: Smart follow-ups + beautiful empty state onboarding
- `0578a3c9` feat: STYLEGUIDE.md
- `6350e48d` feat: Phase 3 — Tool use with live indicators + sources
- `d85730b1` feat: Paired-devices settings list with per-device revoke
- `87387fa9` feat: Edge TTS voice playback with animated player
- `e8f6b5e0` feat: AI provider Desktop-style message action bar + proxy logging
- `3af4c3dd` feat: Chat persistence + mermaid error isolation
- `b6f2fcb3` feat: Full image support
- `9f4a52fe` feat: deterministic 4401 close for a revoked device on reconnect
- `9a2ef511` feat: Rich markdown renderer for LLM Chat

## 2026-06-27

- `b15ee985` feat: mobile E2EE channel
- `5ffd89fb` feat: mobile device enrollment + per-device token validation ( stage 1b)
- `90694929` feat: mobile E2EE crypto + per-device token registry foundation ( stage 1a)
- `ebc58980` feat: LLM Chat Phase 1+2 — workspace context + @file attachment
- `550b8b84` feat: persistent terminals default ON + hide terminal status bar ( stage 5)
- `654b36e2` feat: Add all latest AI provider models (3.1 Pro, 3 Pro, 3 Flash)
- `d7a077d0` feat: canvas terminals re-attach surviving sessions on restore ( stage 4)
- `de28c5ad` feat: re-attach surviving dash terminals with scrollback after restart ( stage 3)
- `dba630fa` feat: configuration settings tab
- `a9d26e96` feat: keep dash terminals alive on detach + bounded orphan GC ( stage 2)
- `a2571da2` feat: LLM Token Relay — provider proxy with metering
- `e7065ed5` feat: spawn interactive dash terminals inside terminal, gated ( stage 1)
- `73cd1789` feat: LLM Chat v1 — standalone model access panel
- `0644dd16` feat: default crash-survivable workers ON (kill-test passed on 0.1.512)
- `829b2ac2` perf: GitHub API caching + worktrees auth fix across all routes
- `746bf704` feat: boot re-bind observability + crash-survival contract test ( stage 2)
- `c8f0a3bf` feat: crash-survivable worker spawn, gated (daemon crash-survival stage 1)
- `68b59ac3` perf: Kill scroll jitter — remove per-frame CSS recalculation
- `c1f589d9` feat: worker-context merge approval card + o8 inbox + o8 packet approve-merge ( stages 5b/6)
- `7b675e6c` feat: client abstraction — Local/Cloud/Hybrid
- `6b7ab567` feat: extract steer-packet route + o8 packet steer (control-plane symmetry stage 4)
- `c844b850` feat: Tier 2+3 intelligence layer

## 2026-06-26

- `52748a74` feat(cli): o8 packet reset/retry/rerun/merge-preview (control-plane symmetry stage 3)

## 2026-03-19

- `5701631b` feat: Repo switcher for Issues & PRs + deeper chat history
- `c0e0e159` feat(cli): o8 mission create/dispatch/status/wait/tail (control-plane symmetry stage 1)
- `d25c4988` feat: Issues & PRs combined page + collapsible agents + deploy
- `52db245f` feat: Issues + Deploy Status + CI on mobile — monitoring & deciding
- `4ba2f2eb` feat: land realtime control plane and shell-first render path
- `26afd0c3` feat: Memory page
- `3aafbf32` feat(review): pick the best-of-N winner through the governed merge gate + audit
- `d194200d` feat(review): per-candidate merge-gate verdict on the compare matrix
- `4ce4c01e` feat: Tap-to-reveal message actions + Telegram-style photo grids
- `0bc0e37b` feat(review): mount the N-up compare matrix as a contextual O8Panel tab
- `3382ae5f` feat(review): N-up comparison diff matrix component (best-of-N)
- `d5f9fbaa` feat: Dark mode
- `f6fd5939` feat: Tier 1 UX
- `afc71bd8` feat(orchestrator): arm best-of-N fan-out via comparisonModels on create_mission
- `144a5f58` feat: Smooth crossfade animation between expanded header and compact pill
- `570a90ea` feat(browser): Design Mode click-to-grab over the native window (Stage 4b)
- `c27c9728` feat: Hide RuntimeBar when keyboard is up — clean compose
- `14bd416e` feat(browser): native browser-view as default operator setting (Stage 6)
- `99637a6a` feat(browser): occlusion snapshot-swap for the native browser-view (Stage 5)
- `18e70561` feat: Auto-grow input + RuntimeBar at true bottom + frosted status bar

## 2026-06-25

- `9180d6d7` feat(browser): wire o8_browser_* to the native browser-view (Stage 4, secure)
- `1ac71b60` feat: Compaction indicator on mobile chat — matches desktop ThoughtsCard
- `004a3ce2` feat(browser): native browser-view panel surface + position sync (Stage 3)
- `45175e53` feat: Header collapse-to-pill + repo/branch/diff in bottom footer
- `eeeac722` feat(browser): inject in-page agent into browser-view (Stage 2 — secure)
- `797df06f` feat: Costs page
- `e43c8039` feat(browser): native browser-view child window (Stage 1 — Rust shell)
- `e728c1da` feat: Settings + PR Reviews in Activity + panel status APIs
- `65b379a5` feat(browser): engine-pane fallback so auth-gated apps render + stay drivable
- `21413a25` feat: Notifications + PR Review from mobile
- `d0f1e083` feat(browser): render Clerk/auth-gated apps + cut the dead Open Source button
- `f7c7f5f4` feat: Activity Feed + Launch-to-chat + Fleet → Agents rename
- `e813ebca` feat: continuous agent ghost competing product + unified agent-driving glow
- `e80ca9c7` feat: Launch Agent — fire agents from mobile
- `a3f17956` feat: unify Design Mode
- `de47c496` feat: Fleet View — Apple-level agent dashboard for mobile
- `3ee3278d` feat: Design-Mode grab
- `ec02c8a6` feat: Glass slash commands on mobile — frosted popover matching desktop

## 2026-06-24

- `2b411998` feat: canvas add-file/open-diff/open-chat/add-video verbs — agent spawns every content kind
- `8c5b1e9c` feat: Speed Dial navigation — floating menu like Mister Copy Trade
- `0814dd0f` feat: o8_canvas full verb parity
- `90557563` feat: canvas add-image/stack/flip/separate intent verbs — agent control parity
- `aadb6232` feat: ThoughtsCard Apple pass
- `eb76e1ab` feat: canvas image-stack UX

## 2026-03-18

- `bb31b56c` feat: Slash commands + glass attach popover in workspace chat
- `d4840609` feat: theme-aware ASCII o8 workspace loader
- `e3bfe466` feat: Chat V2 pass 2 — model/thinking, search, media button
- `ef670c12` feat: ASCII o8 boot splash — animated wordmark loading screen
- `d60b2a98` feat: agent canvas control — see + place/size/raise/close cards
- `838c0f41` feat: ASCII effects suite — image/wordmark, wave field, flow field
- `7c85af66` feat: Chat V2
- `8d86848b` feat: liquid ascii fluid effect + extensible effects lab preview
- `8478ec0a` feat: competing product-style compact agent cards + always-visible running agents
- `e6fb7355` feat: Add agent runtime + agent runtime to Open In dropdown
- `a6326d5f` feat: Open In button
- `58dd6235` feat(lanes): shared archived-dedup primitive + collapse=true structured-state query
- `19b9a2e2` feat(mcp): semantic locators
- `a9ee6543` feat: Global Repo Context Bar — first-class repo selector above tabs
- `75064758` feat: Workspace Chat V1 — full chat tabs alongside terminals

## 2026-06-23

- `3bd509af` feat(voice agent): kill/stop agents by voice
- `511de9f8` feat: Dedicated Checks tab on PR viewer — competing product-style CI status
- `cbaafa8d` feat: Files tab — Changes filter dropdown
- `dba6c6fc` feat: Close remaining workspace gaps
- `7b86ee1c` feat: home-dir agents
- `09aa9a89` feat: mailbox in voice agent — relay + read o8 team messages by voice
- `8490aac4` feat: voice agent is peer-aware
- `7f3e7cd3` feat: Branch switching from panel — git checkout with dirty check

## 2026-06-22

- `a5417a5a` feat: o8 team mailbox (tell/inbox) + auto-installed guard hook
- `853f13ba` feat: o8 team
- `f4ab538f` feat: Huddle mode
- `8742abff` feat: Running indicator on collapsed repo card
- `4dfaec25` feat: canvas navigator loupe size is adjustable in the tuner
- `b1ee78c0` feat: Dev server launch from repo card — one-click Run/Stop
- `07f63e3f` feat: global ⌘⇧E "report an issue" hotkey on the IDE dashboard
- `f26ed102` feat: Port preview pane — in-IDE iframe via proxy
- `f5bf9483` design: float the mission-complete card above the composer
- `5d1fba5c` feat: Agent ↔ Branch association — bidirectional linking
- `b1ab114c` feat: home-dir AI provider agent
- `fa4601af` feat(brain): free fast Brain via warm AI provider CLI
- `91d57d8c` feat: First-class ports in NavRail — auto-detect + grouped display
- `1bc05948` feat(brain): managed-inference + bring-your-own guardrails so non-paying users never burn founder credits
- `e4c39f70` feat: operator Stop button + fix the phantom "Working forever" latch
- `9d5117ba` feat: mobile voice agent remote — drive voice-to-voice from the phone
- `a58c4ecc` feat(brain): local-model inference backend
- `73caa0de` feat: Branch management — create, delete, cleanup
- `a51c81b5` feat(brain): founders auto-get the fast Brain tier (B-1) — instant answers, not the 15-30s CLI
- `2181b75c` feat: Optional worktree launch + stale branch detection (,)
- `654ecefe` feat(founding): STT sweep harness + complete app-wide inference inventory
- `a316cf49` feat(founding): managed-inference speed/cost sweep harness + Brain tier results
- `850f563d` feat(founding): /v1/founders wall endpoint + launch checklist

## 2026-06-21

- `97deca18` feat: founding cohort count endpoint + metadata-signal robustness
- `049403e1` feat: realign Founding Operator tier to locked spec (plan: founder, early access, tiered)
- `e431c0a1` feat: Expandable repo cards — branch list with worktree indicators
- `14c058f8` feat: Founding Operator purchase
- `ad609f3d` feat: Colored file icons + repo-aware file tree
- `8a4eaa8e` feat: PR Review opens in canvas + remove Issues/PRs/CI tabs
- `77897ded` feat: local models
- `629cc421` feat: Repo-scoped Activity

## 2026-06-20

- `80cd1b0f` feat(dispatch): make defaultDispatchModel writable via the operator-defaults API
- `0f6e8bca` feat(dispatch): run workers on local models
- `f69959eb` feat: Repo-aware Activity feed — selector, agent-scoped, PR merge banner
- `820c53a8` feat(voice): o8_status reports each agent's canvas name — spoken roster
- `0c3133a7` feat: Activity feed
- `fb902e4a` feat(voice): address a working agent by its canvas name — "Atlas, run the tests"
- `07046189` feat: Unified Activity Feed — Apple-grade timeline with GitHub data
- `b28496d5` feat(canvas): memorable agent codenames + color-by-runtime + grid voice verb
- `9c726d5d` feat: Show all main agent surfaces + smart cron collapsing + fleet display setting
- `096f11ee` feat: Pin main agents + collapse cron sessions into single card per agent
- `adb9e13d` design(canvas): chat title weight 400 — match every other card
- `935e9ead` feat: Stall detection for launched agents — 5min silence triggers warning

## 2026-03-17

- `fd5b95be` feat: Proxy localhost previews to strip frame-busting headers
- `12cc9625` design(canvas): reconcile chrome spec — header layout + zoom-in ladder
- `dc767c4a` feat: Agent lifecycle
- `c50d72b7` feat(canvas): zoom IN
- `b9adc34c` feat(voice): meter realtime voice spend → usage_logs + cost dashboard
- `4ed8d0d5` feat: Live localhost preview
- `34dbbbce` feat: Live activity dots + elapsed time on terminal tabs
- `866e4ced` design(canvas): chat-card header
- `07783010` feat: Terminal tab persistence — tabs survive app restarts
- `796e1050` feat: Inline images rendered as HTML — bypass xterm IIP entirely
- `c77d971a` feat: Inline image rendering
- `af6a00c9` design(canvas): lock the canvas-chrome system into design system.md
- `0adbabb6` feat: Inline image rendering in terminal — Sixel + iTerm2 IIP support
- `c4c521b7` feat: Auto-register folders opened via picker — shows as Recent next time
- `c3b0f1f9` feat: Native folder picker
- `3213cd7c` design(canvas): media cards into the shared chrome family
- `83d80632` feat: Open folder picker — launch CLI agents in any directory
- `457ff44c` feat: Two-step CLI picker with repo selection ( foundation)
- `c7f59308` feat: Terminal polish
- `d464bd53` design(canvas): browser card header into the shared chrome family
- `a8ed6a3e` feat: Terminal-first workspace
- `0dfc1ab1` design(canvas): one chrome vocabulary across cards — shared sizes + dynamic floor
- `18741a2b` feat: Live review file-change push via WS — repos + worktrees
- `99db49b5` feat(canvas): render-on-screen
- `3e915d24` feat(voice): show in-flight worker count inside the voice-live dock capsule

## 2026-06-19

- `bc072654` feat(voice): voice-live presence shows in the screen dock, not only the IDE window
- `90bd3250` feat: Mobile terminal surface — xterm.js on mobile + Terminal/Chat lane
- `6f94b77d` feat(voice): double-tap right Cmd toggles voice-to-voice mode (live indicator + idle auto-off)
- `128957d9` feat: Terminal infrastructure
- `77b99843` design(chrome): ≥44px hit target on header pills + the panel ✕
- `71ad1442` feat: Launch modal UI
- `b1f1e161` feat(voice): voice agent can reset/retry + wait on a packet by voice — closes
- `e24244b3` feat: Universal launch pipeline
- `3a849d8c` feat(voice): voice agent can annotate o8.md by voice — o8_spec_annotate
- `f6c89fd3` feat: Repo registry polish
- `6a67da78` feat: Analytics page — cost dashboard with real data
- `7a17612f` feat: Agents section collapsible — same pattern as Activity
- `fb165675` feat(voice): voice agent competing product
- `9df7f9b5` feat: Activity as collapsible dropdown above agent cards
- `5f3eef1a` feat: Issue assignment panel + ThoughtsCard z-index fix
- `6c049e46` feat: Active session pulse on timeline drill-down cards
- `1a6d4216` feat: Session cost tracking — real token usage + spend per session
- `81e04238` feat(voice): voice agent can drive a browser + inspect a packet diff by voice
- `b1018474` feat: Connected session panel with live SVG bezier connector
- `dfacd737` feat(zoom): global ⌘-/⌘=/⌘+/⌘0 zoom for the IDE shell
- `9bc30cef` feat: Timeline drill-down — double-click for per-agent breakdown
- `5c43c1d3` feat: Clickable PR diff on agent cards — opens PR viewer in Canvas
- `63963edc` feat: WS-driven AgentPanel + TitleBar status dot + full dedup (-6)
- `d306b55c` feat(voice): voice agent can spawn agent cards by voice — wire spawn-agents canvas verb
- `670bee13` perf: Wire WS for diff stats + remove redundant polls
- `019329f1` feat(voice): voice agent realtime
- `306bbe73` feat(voice): voice agent realtime — expose all 10 AI modelrealtime voices
- `114139fc` feat(voice): voice agent realtime
- `6be1f57b` feat(voice): voice agent realtime

## 2026-03-16

- `f2f84d67` feat: Wire WebSocket to desktop chat — real-time streaming
- `e4c92d7f` feat(voice): voice agent realtime
- `c81120e3` feat: agent runtime agents show their active repo's diff
- `c1a4daef` feat(voice): voice agent realtime
- `43e2b39d` feat: Live Diffs for all 3 runtimes + UX fixes
- `97f4362c` feat(canvas): voice spawn-agents
- `e648662e` feat: Live Diffs — beautiful real-time code change viewer
- `ed4cae05` feat(canvas): stream the dock's assistant prose with the smooth-text reveal
- `5d3075c8` feat: Live Agent Output panel + agent card pulse

## 2026-06-18

- `92dd94db` perf(chat): make the streaming reveal fast, not just smooth
- `94c26159` feat: Real diff stats on main + real timeline activity bars
- `0fbccc8b` feat: Real context % for agent runtime sessions + diff stats
- `020fe456` feat: smooth streaming reveal in the orchestrator chat (no more bursty text)
- `7cb0116c` design(shell): right-panel glass squircle fill, flat composer, no o8.md auto-collapse
- `d8f29a5c` design(shell): glass-mode left-column cohesion + lisse hover-preview edges
- `8c8fd3df` design(panel): lisse squircle corners on the right O8Panel
- `0622226b` feat: Wire real workspace data — PR status + diff stats on agent cards
- `696f45f2` perf: kill dashboard render storm + realtime snapshot timeout spiral
- `54549618` feat: agent runtime sidebar chat
- `7b4f17d5` feat: wire canvas + mobile orchestrator surfaces into the stream replay path
- `ce6ea21c` feat: agent runtime transcript — read session JSONL into sidebar
- `9e9363eb` feat: orchestrator stream replay buffer
- `3fbfd2c6` feat: Smart naming on collapsed card dots too
- `f636bc47` feat: voice agent changes o8 UI settings by voice (theme, surface, canvas mode)
- `893de1aa` feat: Better naming in agent cards

## 2026-06-17

- `af842ed6` perf(voice agent): persistent AI provider session + keydown pre-warm to cut agent latency
- `7e177ece` feat: agent runtime sidebar chat — send messages via CLI print mode
- `b6d866fb` feat(voice agent): additive teaching diagrams — keep building on the live drawing
- `fef1a678` feat: agent runtime synthetic sessions for unmatched live processes
- `1e0ba04f` feat(voice agent): draw teaching diagrams on screen instead of writing an HTML file
- `8a67d35e` feat: agent runtime sessions appear in fleet with live PID detection
- `35909e3b` feat: surface native AI provider scouts as a live crew card (orchestrator + canvas)
- `b579ca74` feat: Status-grouped agent cards + Apple design polish
- `2b10a786` perf: smoother orchestrator streaming
- `662ead41` feat: Full-size agent cards with everything visible
- `9ff2071c` feat: orchestrator turns can run far longer — raise hang watchdog 30m to 4h
- `d6b4ac39` feat: Show heartbeat intervals on agent cards (read-only)
- `0bad2db6` feat(voice): teaching-mode P1
- `6634243c` feat: Agents tab in Settings — fleet dashboard with model editing
- `4b0ea4d6` feat(voice): screen-draw snaps to the real UI element + Fn paste targets o8 + mail draft opens visible
- `5572534e` feat: Merge WorkspacesPanel into AgentPanel — unified view
- `c9eabe99` feat(voice): interrupt a running task + keep the working indicator lit for background work
- `f857ea13` feat: WorkspacesPanel — status-grouped workspace cards
- `189b42f3` feat(voice): voice agent Draws — [DRAW:rect/arrow] screen annotations
- `ae1aeef7` feat: Cmd+K keyboard shortcut to toggle Thoughts Card
- `0a9a8a96` feat(voice): read_screen tool
- `231ecf00` feat: Context-aware suggestions in Thoughts Card
- `b8f0e806` feat(voice): o8_canvas tool — drive the Canvas by voice
- `508b34b3` feat: Agent picker in Task chat — route to any agent

## 2026-06-16

- `84ea9c5c` feat(voice): VoiceTab escalation-policy toggle (Off / Auto / Deep)
- `4d921c15` feat: Approval routing in Thoughts Card + test simulation
- `3864da09` feat(voice): escalation-policy backend + concurrent-task safety
- `c5baa97f` feat: Task mode — mini chat inside Thoughts Card
- `f7490085` feat(voice): two-speed escalation routing for the voice agent
- `2cef4fc3` feat: Thoughts Card — Issue vs Task modes + resize fix
- `b4cd5704` feat(voice): AI provider background brain + escalate handoff for the voice agent
- `ff5e6d1b` feat: Thoughts Card — resize handles + agent connection
- `860c658e` design(settings): cleaner iOS-style switches, native selects & segmented controls + bold tab headers
- `818e1a6d` feat: Thoughts Card — floating glass command surface
- `0c4853e3` feat(canvas): in-app feedback capture + auto-hiding navigator loupe
- `00802a96` feat: Settings page with GitHub connection status

## 2026-06-15

- `d45865f9` feat(canvas): ship the operator o8 glass theme + universal orb default
- `7b5a14ab` feat: Intent Canvas V0 — Fleet Command Center in workspace
- `1bb0db39` feat(canvas): unified corner-resize on all cards + framed terminal + spawn fit
- `6da96c2b` feat: SessionTimeline Phase 1 — hover scrubber + real data API
- `c4ea5412` feat(canvas): live dispatch dock, balanced grid, alerts open the PR diff
- `01ace93f` feat: Timeline Expanded View — full session replay in Canvas
- `32edb114` feat: founding-pass beta invites
- `bf8c66e6` feat: SessionTimeline V0 — agent activity replay bar
- `367a36b9` design: harmonize the status-bar branch label with the composer chip type
- `e71c4606` feat: unify composer chip menus onto ComposerPopover
- `b9e4f6d3` feat: TitleBar window controls — sidebar/back/fwd/bottom/chat/settings
- `f91031a4` feat: composer popovers portal out via a shared ComposerPopover primitive
- `0146dedf` feat: TitleBar search is now live UniversalSearch + red settings gear
- `752a7e7f` feat: auto-collapse the left panel while the o8.md notes tab is open
- `0c0e6313` feat: TitleBar
- `bd8b266e` feat: composer button row collapses to icons when narrow
- `f5263e84` feat: Desktop NavRail
- `59c4847c` feat: supervisor inbox self-closes via escalated/resolved states
- `16a2b8ca` feat: Session Info Sheet
- `e1b09345` design(canvas): grey-on-white media rim + integrated header + matched resize arc
- `1d486014` design(canvas): defined rim + off-edge resize arc on photo & video cards
- `e54a7db8` feat: Universal search

## 2026-06-14

- `ba729883` feat(workspace): smooth push for the workspace-detail rail + clearer toggle
- `df7367b3` feat: Proactive alert system — engine, context, bell, tray, toast
- `bbc32b57` feat: o8 menu-bar tray icon → new o8 monogram (white template)
- `01b866af` design(canvas): rename Alerts dropdown + make rows jump to their surface
- `4419a11a` feat: REST API resilience
- `cee2ba1f` feat(workspace): footer merge beacon -- fleet-wide "ready to merge" pill

## 2026-03-15

- `b63f3eff` perf: gateway REST API client — 23ms vs 38s CLI cold-start
- `36045df8` feat: new o8 app icon — aurora Liquid Glass o8 monogram
- `18c90fc2` feat: Heat map top-down view + fix fly-in stale closure
- `815d183b` design(canvas): glass onboarding panels + behind-glass motes reel, match reel type
- `377f27c7` feat: Search dropdown with grouped clickable results
- `b14bd28d` feat(workspace): consolidate orchestrator composer chip row + adaptive icons + blocky-o8 boot loader
- `6da8ab74` feat(canvas): first-run welcome modal + guided coach-mark tour
- `e4d52e59` feat: Knowledge Graph v3 — double-click fly-in + search fact nodes
- `d9d1fab3` feat(canvas): add orchestration MODE selector (Fleet / Single / Fusion) to the canvas composer
- `418ef8f1` feat: Knowledge Graph v2.3 — zoom-aware labels + ambient fireflies
- `a25816f0` feat(canvas): add Clerk account dossier to the canvas top-right
- `ffc54c54` feat: Knowledge Graph v2.2 — depth fog + all labels + text polish
- `54fd494e` feat(canvas): add video cards
- `b6b6dbc4` feat: Knowledge Graph v2.1 — bar gradients + floor reflections
- `136a31d4` feat(auth): desktop ticket exchange + sign-in handoff (Clerk signals API)
- `8be40cd0` feat: Knowledge Graph v2
- `ec5836a7` feat(auth): GitHub sign-in via Clerk — shared hook, account UI, o8:// receive
- `059b44f2` feat: Auto-refresh Knowledge Graph stats every 60s
- `b980aaac` feat(canvas): merge composer model+thinking into one drawer; wrap file cards
- `0e3c9168` feat(canvas): sphere-projection orb navigator + single-toggle bubble UI
- `f0835922` feat(canvas): readable o8.md + terminal fonts, caret-correct spec card

## 2026-06-13

- `b8740e13` feat(mcp): operator MCP server supports a shared HTTP transport
- `2d45dca2` feat: Replace lava lamp with Interactive 3D Knowledge Graph Explorer
- `9861ef86` feat(canvas): result-card synthesis from the orchestrator tool stream
- `48c367e3` feat: Memory lava lamp v2
- `aa47b98c` feat(canvas): rich response blocks shared + o8 bench parity + reasoning in seconds
- `55476668` feat(canvas): dock solid edge + chat modal at agent-card bench parity
- `3f487938` feat: memory Lava Lamp — living particle visualization
- `a35ac23f` feat(canvas): all-angle hidden resize on the chat-card
- `3fbbf87d` feat: Image rendering in mobile chat + click-to-expand lightbox
- `ba13e494` feat(canvas): shared CardComposer
- `4b0d8e0a` feat: Image rendering in chat + click-to-expand lightbox
- `24b81051` feat(canvas): smooth borderless chrome on dock + chat-card
- `638a8a7f` feat: Typing indicator — animated dots while agent is thinking
- `78e1e612` feat(canvas): borderless DockEntryView
- `f47ed9f1` feat: Deployment Status (Vercel) + Git Log + Image Preview complete
- `575876ee` feat(canvas): agent-card bench — side-by-side presence comparison
- `2dc08c3d` feat: Git Log viewer + Image/Asset preview
- `6d7fa7ad` feat(canvas): agent-card bench — PR + edited-files result variants
- `ddcaf9d4` feat(canvas): agent-card bench
- `ef3c82b4` feat: Issue Creator with AI enhancement (AI provider)
- `996ec5e9` feat(canvas): agent-card bench — user messages + smooth Brain citations
- `67a5f5b0` feat: Global workspace search + PR review comments with diff context
- `45040818` feat(canvas): agent-card bench
- `72e05c70` feat: CI tab in agent panel
- `2e534d50` feat(canvas): agent-card bench
- `7ef90f9c` feat: Changed file highlighting, clickable files, CI button
- `374945e2` feat(canvas): pinned orchestrator dock + split-tab orchestrator modals
- `a1887636` feat: README viewer, CI/GitHub Actions, file diff preview
- `e9dd88b7` feat(canvas): default theme is the operator's tuned light look
- `8dc375a4` feat: Stop button + project-scoped data + no auto-transcript popup
- `024e91b9` feat(canvas): match reference
- `b3e9d0e0` feat: Project-scoped Issues, PRs, and Files — data follows workspace
- `3b4d3b6d` feat(canvas): orchestrator is a floating draggable card, Brain tab renamed o8
- `5d9591dc` feat: PR Review tab + canvas viewer — full GitHub PR detail inline
- `2efcd3da` feat(canvas): orchestrator + brain spawn as one tabbed pane — never orchestrator-alone
- `3af091ab` feat: Commit detail viewer — click any commit in Activity tab
- `3a8f8958` feat(canvas): unified theme panel
- `275584df` feat(canvas): dock orchestrator gets its own light/dark + tint dial
- `0b305939` feat: Agent panel groups by workspace — matches chat session picker

## 2026-06-12

- `116ef97d` feat(browser-engine): headless installed-Chrome tier
- `19b82c0b` feat: Show all agents including agent runtime/agent runtime in agent panel
- `afea081e` feat(canvas): intent bus
- `352b261c` feat: Issue detail full-width + diff opens in canvas tab
- `1bf20111` feat(browser-agent): agents drive the embedded browser
- `ac13ffe7` feat: Drag-and-drop + paste + click-to-attach files in desktop chat
- `55a05cf2` feat(canvas): the everything run
- `86d5fbac` feat: Vertical drag handle for canvas — resize workspace/canvas split
- `94d7ba97` feat(canvas): UNIVERSAL text slider
- `05fb9a4e` feat(canvas): chat ink control (Auto/White/Dark) + 100px chat frost + reasoning TIMELINE
- `4fb1867e` feat(canvas): glass TONE axis (dark/Ivory light) + floating-chat sliders + live reasoning & image entries
- `508f8525` feat: Contextual Canvas — bottom-half tabbed workspace
- `ee9a94b2` feat(canvas): agent lifecycle lands live
- `b4b2d9af` feat: Click agent surface → switches chat to that session
- `92061a8b` feat(canvas): persistence + talkable chat cards + project-grouped repos; drop scratch chat from o8.md card
- `c1135d56` feat: Agent cards v2
- `68bafe30` feat(canvas): o8.md card at FULL parity — mounts the real spec pane in glass
- `653a1829` feat: Proper markdown rendering in issue modal
- `93421332` feat(canvas): agents can open pages in the canvas browser via o8:open-browser
- `ab157be0` feat: Light theme + clickable issues with glass modal
- `97226227` feat(canvas): browser tabs in glass browser cards + review drawer refetch-on-open
- `e65be2d0` feat: Three-column layout — Agent Panel | Workspace | Chat
- `fab3fa08` feat(canvas): real diff cards with governance row + review drawer; retire center emblem; sessions repo filter
- `6ab46211` feat: Agent Command Center
- `0f02946d` feat(canvas): element picker in browser cards — front-end selector tools
- `e71d2edd` feat: Glass diff modal
- `55002928` feat(orchestrator): composer images actually reach the model — both surfaces
- `e4690cb7` feat: Draggable compose bar — resize input height by dragging up
- `86e6e178` feat(canvas): dock gets its own composer + turn cards + drawer-styled term picker
- `72b80175` feat(canvas): Pulse is the real agents-working mark — the o8 binary orbit
- `2c697aa0` feat: Glass modal for Mermaid diagrams — expand, zoom, pan
- `beedb8ac` feat: Mermaid diagrams on mobile — same o8 frost theme
- `cf881d3c` feat(canvas): Pulse rebranded — the o8 dual-orbit mark in faded dither
- `187a2963` feat(canvas): sessions drawer on the left nav + the amber Pulse backdrop
- `8c1f6b55` feat: Styled CodeBlock + Mermaid diagram viewer
- `d1150d22` feat(canvas): dock tool calls collapse into one live activity line
- `663f2ef3` feat(canvas): operator-picked depth set — wind-dots field + custom shader moods
- `a788f12d` feat(canvas): real Paper Shaders depth layers — WebGL, barely moving
- `276067e0` feat: Transport controls — message actions morph during playback
- `0e61e8ab` feat(canvas): depth backdrops + opaque popovers + o8.md reads like a page
- `a6fad007` feat(canvas): past sessions open as their own draggable glass boxes
- `263f112b` feat(canvas): senior pass
- `0c91779a` feat: Point-to-Play
- `faa80abb` feat(canvas): photos surface reference-style — image cards, stacks, top-right search
- `f0c24f64` feat: TTS Engine + Message Action Bar — Play/Copy/Retry on every message
- `522e0367` feat(canvas): Apple-smooth squircle corners + the dock becomes a real panel
- `1338f05e` feat: Desktop chat header — exact mobile TopBar clone
- `94f1f0dd` feat(canvas): markdown rendering in the docked chat
- `575541bd` feat: Desktop chat sidebar — mobile-identical chat on Dashboard v1
- `7c9350f3` feat(canvas): talk to the REAL orchestrator from the canvas composer
- `9560da73` feat: Dashboard v1
- `2d81c231` feat(canvas): Finder "Open With → o8" — OS file opens land as canvas file cards
- `b213e4ce` feat(canvas): file cards
- `2b53d21f` feat: wire o8 v1.2.5 fixes — fact_ids, stale flags, real graph
- `0391c53e` feat(canvas): spawn reveal easter egg + summoning verbs + edge-rail handles
- `a6bfb253` feat: grouped squad picker with expand/collapse
- `c5cf3b52` feat(canvas): terminal cards v2
- `d5c7a79a` feat(canvas): real terminals as glass cards + Liquid frost floor
- `695caf87` feat(canvas): glass tuner docks under the Canvas word + "Save as my default" personal preset
- `5fdbfafc` feat(canvas): Liquid frost dial
- `6e156f1a` feat(canvas): docked orchestrator, component cards, image drop, liquid-clear background
- `6c75607d` feat(canvas): background controls

## 2026-06-11

- `dbab17d4` feat(canvas): desktop-clear glass, material presets, kivo summon choreography
- `4b7698b2` feat: native shell v2 desktop shell
- `351fe29c` feat(canvas): v2 glass slice
- `9af1036a` feat: squad picker dropdown on TopBar title tap
- `4a1f5b1b` feat(canvas): fleet-canvas v1
- `e31ca632` feat: wire memory surfaces into shell
- `74225234` feat: workers get the Engineering Brain
- `7b2c8e4e` perf(brain): classify/retrieve overlap + semantic answer cache
- `2359908c` feat(brain): sources parity
- `6f2b969f` feat: memory Integration — all 8 issues (-)
- `74c9f3f3` feat(brain): Ask Brain streams — UI switches to the SSE route
- `5471ea8e` feat(brain): spend ledger + daily cap on the OpenRouter tier, 'fastest' composer knob
- `d6d4e92a` perf(brain): warm REPL pool
- `eddc17a2` perf(brain): Tier-0 latency pass
- `468010b7` feat(composer): orchestrator model switcher in the thinking chip + Ultracode label
- `11d760c0` feat: voice agent terminal voice control adds iTerm2

## 2026-06-10

- `44ca2107` feat: voice agent speaking-speed control

## 2026-03-14

- `fff88386` feat: Phase 2
- `21c66382` perf: voice agent calendar list goes native EventKit
- `168567de` feat: voice agent update verbs
- `a86b7a84` feat: voice agent second-ten-minutes
- `6f020d59` feat: voice agent day-one basics
- `5c1e1680` feat: voice agent parity round 3
- `8c490252` feat: voice agent terminal brake + keys + new session, o8 recap + usage (parity round 2)
- `f41508ca` feat: worktree isolation Phase 1
- `f64eaf1b` feat: voice agent terminal voice control v1
- `c773f3d9` feat: universal runtime adapter contract + agent runtime integration
- `36a4ffd8` feat(mcp): o8_operator_defaults tool + EXTERNAL_AGENTS.md — external-agent control parity
- `8fad1f02` feat: voice agent controls Apple Music
- `58091a6f` feat: code block rendering — fenced code + tool output cards
- `f7267e37` feat: voice agent edit lane works inside o8 + o8-control frontier v1
- `ae4290f3` feat: native markdown table rendering — beautiful HTML tables in chat view
- `808c6c21` feat: permissions health
- `af6455b7` feat: unified WebSocket — real-time push replaces SSE + polling
- `46f512eb` feat: voice agent Guide pointer — dwell variant of Points (magic roadmap)
- `6078ff69` feat: PWA
- `c85b8b67` feat: voice agent "what needs me?"
- `ae4baf29` feat: virtual scrolling for transcript — DOM bloat eliminated
- `53180b4b` feat: selection-as-object
- `0143de0f` feat: consolidated sync API — 5 requests → 1
- `5dcbe634` feat: dock chat continuity
- `95b06c78` feat: prompt enhancement
- `8e48df45` feat: voice agent routing doctrine in the system prompt + presence-layer architecture doc
- `cffa471b` feat: approval primitive
- `67b614ff` feat: memory glints + worker-pulse orbit
- `a28dbb33` feat: cost dashboard
- `f7aaa7c1` feat: drag-files-into-voice agent
- `9360ccbc` feat: wire json-render Renderer into mobile shell
- `1e81dc7b` feat: voice agent Points
- `ac850ea6` feat: json-render integration
- `6361ff5e` feat: Option = voice agent agent (both keys), double-tap Option = long question, say -> Option+S
- `04965e55` feat: agent runtime chat parity
- `dba8203d` feat: voice agent opens any installed app — fuzzy open_app + list_apps tools
- `4a282df2` feat: seamless agent runtime chat

## 2026-06-09

- `fc9e9c96` feat: unit-test harness (vitest + cargo), CI test gate, CLI version armor
- `2cfbf887` feat: auto-switch to launched agent runtime session
- `9d8aa6bb` feat: clean agent runtime chat view
- `ea09b713` feat: discovered agent runtime session transcript
- `07f0dcd7` feat: live process fallback
- `286f3397` feat: mobile agent runtime launch

## 2026-03-13

- `ce3a5ef7` feat: unified chat for agent runtime sessions
- `6d9cf064` feat: show all agent runtime sessions in squad (no stale filter), dedupe by branch, show branch in pills
- `59dd7471` feat: project-grouped squad rail
- `e3abcb80` feat: native streaming
- `2766c248` feat: commit summary card in diff view (zero AI
- `3a295ceb` feat: observable agents

## 2026-06-07

- `55c24ca5` feat: catch dashboard mount crashes in preship gate [via-o8]
- `53bde190` feat: squad cards
- `5efa10b5` perf: diff view
- `d6e646b9` perf: review-file 10s cache + only poll when diff open, tighter idle behavior
- `f27d88b6` perf: request dedup, 8s inbox cache, 5s transcript cache, round usedPercent, suppress hydration
- `d6f0f4ad` perf: adaptive polling (20s idle, pause on hidden tab, resume on focus), CSS containment, layout isolation
- `17c17370` feat: add blind second-pass auto-review [via-o8]
- `f9c82c32` perf: diff-and-patch transcript + snapshot — eliminate flash on idle polls
- `4384eb8f` perf: skeleton loading, lazy images, send click, API caching (3s transcript, 5s inbox)
- `8731f592` perf: smooth scroll, message fade-in, optimistic user messages, image caching, typing bubble animation
- `9887ba66` design: red send button + red typing dots — matches hamburger accent
- `c9cf14f4` design: solid red menu button, context pressure in bottom bar, doc tab apple redesign
- `1e30be56` design: full mobile UX pass
- `72507a60` feat: one-click "Clean up" button for stale workspace tabs [via-o8]
- `2715fee5` design: apple-grade controls sheet + sticky diff files survive compaction

## 2026-06-06

- `be57c039` feat: doctor flags runtimes that are installed but not authed
- `b4ae629d` design: apple-grade diff polish
- `261f676f` feat: keyboard-navigable orchestrator steer queue

## 2026-03-12

- `00c14dbf` feat: surface queued agent runtime turns and clearer mobile send actions

## 2026-06-04

- `ed97edb9` feat: open a non-Git folder as a repo
- `f7f54ffc` feat: add quick thread switching for mobile agent runtime lane

## 2026-06-03

- `591d6296` feat: align feedback report embed fields [via-o8]
- `b6324594` feat: make owned agent runtime mobile lane feel conversational
- `993f1dbf` feat: add settings feedback reports [via-o8]
- `7bf408ef` feat: allow owned agent runtime interrupt on mobile
- `e480039e` feat: preload owned mobile diff context on focus

## 2026-06-02

- `f2f8c5e4` feat: add webview idle guard lint [via-o8]
- `c740a25d` feat: extend owned agent runtime review and resume on mobile
- `0ac73eab` feat: add preship webview boot gate [via-o8]
- `b42b018d` feat: make owned review packets actionable

## 2026-06-01

- `01a8bd2e` feat: add repeatable benchmark suite [via-o8]
- `4a316a59` feat: add owned agent runtime review packets
- `21d95daa` perf: defer cold boot desktop polling [via-o8]
- `4b834805` feat: route literal o8 lookups to grep [via-o8]
- `6de73096` feat: surface owned agent runtime watch lane on mobile
- `e5d24652` feat(qa-eval): rigorous 4-way Brain-vs-grep
- `e1a47bb2` feat: harden owned agent runtime lifecycle and tail views
- `f57815b9` feat: add strong grep qa eval baseline [via-o8]
- `dc221164` feat: add owned agent runtime launch and resume lane
- `a9fdbfe8` perf: lazy hydrate o8 secondary panes [via-o8]
- `6b7ffeea` feat: add runtime action ownership seam
- `1125c05f` perf: add server timing to hot routes [via-o8]
- `fdc24f56` feat: promote runtime inventory and agent runtime activity detection
- `67d1ad38` perf: add client benchmark instrumentation [via-o8]
- `7217d071` feat: surface local agent runtime runtime discovery in desktop shell
- `33e075ea` perf: add app speed measurement harness [via-o8]
- `b1650ee5` feat: harden mobile operator chrome and review cockpit
- `6a3cdd20` feat: add panel and terminal shells to mobile queue
- `ffd2e4a6` feat: add mobile per-file review drilldown
- `1d19900a` feat: mirror agent visual proof onto GitHub PRs via release assets
- `add6a8e7` feat: deepen mobile review lane and glass styling
- `8ca65c3d` feat: align desktop repo truth with live review state
- `2e94bb3c` feat: wire direct mobile actions and history

## 2026-03-11

- `bbe5dab3` feat: add mobile control inbox foundation
- `8baa3b36` feat: live WS artifacts channel so proof strips update in real time
- `e63edc8d` feat: wire live agent runtime bridge and workflow review
- `868b012d` feat: add native desktop shell wrapper and guardrail surfaces
- `8a8b0775` feat: bootstrap command center shell and runtime contracts
- `c5e26bdf` feat: surface agent visual-proof stills on the PR Changes tab
- `2f7d04ac` feat: o8 packet capture --clip <selector> — frame the proof to the change
- `c15ecbc5` feat: visual proof UI + agent capture awareness ( phase 1 UI)
- `0a381e2f` feat: visual verification artifacts

## 2026-05-31

- `66f2b40a` feat: enable mic capture for voice dictation + harden orchestrator steer preempt
- `06bac7d2` feat: route long worker processes through o8 run by default
- `bcdcdf02` feat: operator controls for o8 run — stop + list
- `1a66517f` feat: live o8 run strip in the orchestrator chat
- `c8784b2d` feat: persist managed-runs registry across restarts
- `df2738fd` feat: footer ports 3-bucket view + watch agent runs live
- `7658c11a` feat: ContextualPanel.attachLiveAgentTerminal — watch o8 run sessions live
- `d8eabac0` feat: o8 run
- `0902aa99` feat: tag ports as agent/browser/noise from managed-runs registry
- `82fcfa5c` feat: managed-runs registry + API for o8 run
- `65672340` design(analytics): lead with Autonomy + Governance (01/02), cost below
