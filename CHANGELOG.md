# Changelog

Development activity for o8 — the governance layer for autonomous engineering teams.

We ship high-signal entries only (features + performance wins). Bug fixes, refactors,
and internal chores live in the private engineering log.

---

## 2026-07-01

- `034b406a` feat(collide): label the Collide toggle with a full hover tooltip + aria
- `427331ee` feat(orchestrator): warm the orchestrator with a resident-process pool + lockout auto-deny
- `b0e12c58` feat(targeting): pass tier effort on dispatch + fix inline-issue number (effort→worker 3/3)

## 2026-06-30

- `a04b0a60` feat(targeting): promote Targeting from utility tab to a main tab (polish)
- `8939b211` feat(targeting): observability logging (step 8)
- `06ab6452` feat(targeting): o8_targets MCP tool
- `b80ec5b3` feat(targeting): difficulty→tier routing + Dispatch button (step 6)
- `ae5b45ef` feat(targeting): cheap-triage-model rationales — the money-shot (step 5)
- `a631bb00` feat(targeting): triage/action config triads (step 4)
- `e7735cd6` feat(targeting): /api/panel/targets route + Targeting panel surface (step 3)
- `4d6b61fd` feat(targeting): heuristic scorer + score cache (step 2)
- `43d642be` feat(targeting): signal collection for the Targeting Machine (step 1)
- `5642a499` feat(orchestrator): Collide composer chip + faint→solid proposals UX (Steps 5,6)
- `45b9edc6` feat(orchestrator): Collide MoA fusion engine + registration + cap-degrade (Steps 3,4,7,9)
- `c3bdc508` feat(orchestrator): two-layer read-only proposer lockout (Collide Step 2)

## 2026-06-29

- `1c835d39` feat(orchestrator): Hermes via a generic ACP backend (Step 3b–3d)
- `7c75d5af` feat(orchestrator): orchestratorBackend setting — makes agent runtime selectable (Step 1)
- `8112edf1` feat(mcp): o8 now configures agent runtime — closes the "any CLI" set (Phase 2)
- `96903a20` feat(mcp): o8 now configures the AI provider CLI from the registry (Phase 2)
- `35164e2f` feat(mcp): agent runtime o8 entry from the registry, not passthrough (Step F)

## 2026-06-28

- `2775957a` feat: desktop half of mobile inline diff comments ( slice 2)
- `0578a3c9` feat: STYLEGUIDE.md
- `d85730b1` feat: Paired-devices settings list with per-device revoke
- `9f4a52fe` feat: deterministic 4401 close for a revoked device on reconnect

## 2026-06-27

- `b15ee985` feat: mobile E2EE channel
- `5ffd89fb` feat: mobile device enrollment + per-device token validation ( stage 1b)
- `90694929` feat: mobile E2EE crypto + per-device token registry foundation ( stage 1a)
- `550b8b84` feat: persistent terminals default ON + hide terminal status bar ( stage 5)
- `d7a077d0` feat: canvas terminals re-attach surviving sessions on restore ( stage 4)
- `de28c5ad` feat: re-attach surviving dash terminals with scrollback after restart ( stage 3)
- `a9d26e96` feat: keep dash terminals alive on detach + bounded orphan GC ( stage 2)
- `e7065ed5` feat: spawn interactive dash terminals inside terminal, gated ( stage 1)
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
- `570a90ea` feat(browser): Design Mode click-to-grab over the native window (Stage 4b)
- `14bd416e` feat(browser): native browser-view as default operator setting (Stage 6)
- `99637a6a` feat(browser): occlusion snapshot-swap for the native browser-view (Stage 5)

## 2026-06-25

- `9180d6d7` feat(browser): wire o8_browser_* to the native browser-view (Stage 4, secure)
- `004a3ce2` feat(browser): native browser-view panel surface + position sync (Stage 3)
- `eeeac722` feat(browser): inject in-page agent into browser-view (Stage 2 — secure)
- `e43c8039` feat(browser): native browser-view child window (Stage 1 — Rust shell)
- `65b379a5` feat(browser): engine-pane fallback so auth-gated apps render + stay drivable
- `d0f1e083` feat(browser): render Clerk/auth-gated apps + cut the dead Open Source button
- `e813ebca` feat: continuous agent ghost competing product + unified agent-driving glow
- `a3f17956` feat: unify Design Mode
- `3ee3278d` feat: Design-Mode grab

## 2026-06-24

- `2b411998` feat: canvas add-file/open-diff/open-chat/add-video verbs — agent spawns every content kind
- `0814dd0f` feat: o8_canvas full verb parity
- `90557563` feat: canvas add-image/stack/flip/separate intent verbs — agent control parity
- `eb76e1ab` feat: canvas image-stack UX
- `d4840609` feat: theme-aware ASCII o8 workspace loader
- `ef670c12` feat: ASCII o8 boot splash — animated wordmark loading screen
- `d60b2a98` feat: agent canvas control — see + place/size/raise/close cards
- `838c0f41` feat: ASCII effects suite — image/wordmark, wave field, flow field
- `8d86848b` feat: liquid ascii fluid effect + extensible effects lab preview
- `58dd6235` feat(lanes): shared archived-dedup primitive + collapse=true structured-state query
- `19b9a2e2` feat(mcp): semantic locators

## 2026-06-23

- `3bd509af` feat(voice agent): kill/stop agents by voice
- `7b86ee1c` feat: home-dir agents
- `09aa9a89` feat: mailbox in voice agent — relay + read o8 team messages by voice
- `8490aac4` feat: voice agent is peer-aware

## 2026-06-22

- `a5417a5a` feat: o8 team mailbox (tell/inbox) + auto-installed guard hook
- `853f13ba` feat: o8 team
- `f4ab538f` feat: Huddle mode
- `4dfaec25` feat: canvas navigator loupe size is adjustable in the tuner
- `07f63e3f` feat: global ⌘⇧E "report an issue" hotkey on the IDE dashboard
- `f5bf9483` design: float the mission-complete card above the composer
- `b1ab114c` feat: home-dir AI provider agent
- `fa4601af` feat(brain): free fast Brain via warm AI provider CLI
- `1bc05948` feat(brain): managed-inference + bring-your-own guardrails so non-paying users never burn founder credits
- `e4c39f70` feat: operator Stop button + fix the phantom "Working forever" latch
- `9d5117ba` feat: mobile voice agent remote — drive voice-to-voice from the phone
- `a58c4ecc` feat(brain): local-model inference backend
- `a51c81b5` feat(brain): founders auto-get the fast Brain tier (B-1) — instant answers, not the 15-30s CLI
- `654ecefe` feat(founding): STT sweep harness + complete app-wide inference inventory
- `a316cf49` feat(founding): managed-inference speed/cost sweep harness + Brain tier results
- `850f563d` feat(founding): /v1/founders wall endpoint + launch checklist

## 2026-06-21

- `97deca18` feat: founding cohort count endpoint + metadata-signal robustness
- `049403e1` feat: realign Founding Operator tier to locked spec (plan: founder, early access, tiered)
- `14c058f8` feat: Founding Operator purchase
- `77897ded` feat: local models

## 2026-06-20

- `80cd1b0f` feat(dispatch): make defaultDispatchModel writable via the operator-defaults API
- `0f6e8bca` feat(dispatch): run workers on local models
- `820c53a8` feat(voice): o8_status reports each agent's canvas name — spoken roster
- `fb902e4a` feat(voice): address a working agent by its canvas name — "Atlas, run the tests"
- `b28496d5` feat(canvas): memorable agent codenames + color-by-runtime + grid voice verb
- `adb9e13d` design(canvas): chat title weight 400 — match every other card
- `12cc9625` design(canvas): reconcile chrome spec — header layout + zoom-in ladder
- `c50d72b7` feat(canvas): zoom IN
- `b9adc34c` feat(voice): meter realtime voice spend → usage_logs + cost dashboard
- `866e4ced` design(canvas): chat-card header
- `af6a00c9` design(canvas): lock the canvas-chrome system into design system.md
- `3213cd7c` design(canvas): media cards into the shared chrome family
- `d464bd53` design(canvas): browser card header into the shared chrome family
- `0dfc1ab1` design(canvas): one chrome vocabulary across cards — shared sizes + dynamic floor
- `99db49b5` feat(canvas): render-on-screen
- `3e915d24` feat(voice): show in-flight worker count inside the voice-live dock capsule

## 2026-06-19

- `bc072654` feat(voice): voice-live presence shows in the screen dock, not only the IDE window
- `6f94b77d` feat(voice): double-tap right Cmd toggles voice-to-voice mode (live indicator + idle auto-off)
- `77b99843` design(chrome): ≥44px hit target on header pills + the panel ✕
- `b1f1e161` feat(voice): voice agent can reset/retry + wait on a packet by voice — closes
- `3a849d8c` feat(voice): voice agent can annotate o8.md by voice — o8_spec_annotate
- `fb165675` feat(voice): voice agent competing product
- `81e04238` feat(voice): voice agent can drive a browser + inspect a packet diff by voice
- `dfacd737` feat(zoom): global ⌘-/⌘=/⌘+/⌘0 zoom for the IDE shell
- `d306b55c` feat(voice): voice agent can spawn agent cards by voice — wire spawn-agents canvas verb
- `019329f1` feat(voice): voice agent realtime
- `306bbe73` feat(voice): voice agent realtime — expose all 10 AI modelrealtime voices
- `114139fc` feat(voice): voice agent realtime
- `6be1f57b` feat(voice): voice agent realtime
- `e4c92d7f` feat(voice): voice agent realtime
- `c1a4daef` feat(voice): voice agent realtime
- `97f4362c` feat(canvas): voice spawn-agents
- `ed4cae05` feat(canvas): stream the dock's assistant prose with the smooth-text reveal

## 2026-06-18

- `92dd94db` perf(chat): make the streaming reveal fast, not just smooth
- `020fe456` feat: smooth streaming reveal in the orchestrator chat (no more bursty text)
- `7cb0116c` design(shell): right-panel glass squircle fill, flat composer, no o8.md auto-collapse
- `d8f29a5c` design(shell): glass-mode left-column cohesion + lisse hover-preview edges
- `8c8fd3df` design(panel): lisse squircle corners on the right O8Panel
- `696f45f2` perf: kill dashboard render storm + realtime snapshot timeout spiral
- `7b4f17d5` feat: wire canvas + mobile orchestrator surfaces into the stream replay path
- `9e9363eb` feat: orchestrator stream replay buffer
- `f636bc47` feat: voice agent changes o8 UI settings by voice (theme, surface, canvas mode)

## 2026-06-17

- `af842ed6` perf(voice agent): persistent AI provider session + keydown pre-warm to cut agent latency
- `b6d866fb` feat(voice agent): additive teaching diagrams — keep building on the live drawing
- `1e0ba04f` feat(voice agent): draw teaching diagrams on screen instead of writing an HTML file
- `35909e3b` feat: surface native AI provider scouts as a live crew card (orchestrator + canvas)
- `2b10a786` perf: smoother orchestrator streaming
- `9ff2071c` feat: orchestrator turns can run far longer — raise hang watchdog 30m to 4h
- `0bad2db6` feat(voice): teaching-mode P1
- `4b0ea4d6` feat(voice): screen-draw snaps to the real UI element + Fn paste targets o8 + mail draft opens visible
- `c9eabe99` feat(voice): interrupt a running task + keep the working indicator lit for background work
- `189b42f3` feat(voice): voice agent Draws — [DRAW:rect/arrow] screen annotations
- `0a9a8a96` feat(voice): read_screen tool
- `b8f0e806` feat(voice): o8_canvas tool — drive the Canvas by voice

## 2026-06-16

- `84ea9c5c` feat(voice): VoiceTab escalation-policy toggle (Off / Auto / Deep)
- `3864da09` feat(voice): escalation-policy backend + concurrent-task safety
- `f7490085` feat(voice): two-speed escalation routing for the voice agent
- `b4cd5704` feat(voice): AI provider background brain + escalate handoff for the voice agent
- `860c658e` design(settings): cleaner iOS-style switches, native selects & segmented controls + bold tab headers
- `0c4853e3` feat(canvas): in-app feedback capture + auto-hiding navigator loupe

## 2026-06-15

- `d45865f9` feat(canvas): ship the operator o8 glass theme + universal orb default
- `1bb0db39` feat(canvas): unified corner-resize on all cards + framed terminal + spawn fit
- `c4ea5412` feat(canvas): live dispatch dock, balanced grid, alerts open the PR diff
- `32edb114` feat: founding-pass beta invites
- `367a36b9` design: harmonize the status-bar branch label with the composer chip type
- `e71c4606` feat: unify composer chip menus onto ComposerPopover
- `f91031a4` feat: composer popovers portal out via a shared ComposerPopover primitive
- `752a7e7f` feat: auto-collapse the left panel while the o8.md notes tab is open
- `bd8b266e` feat: composer button row collapses to icons when narrow
- `59c4847c` feat: supervisor inbox self-closes via escalated/resolved states
- `e1b09345` design(canvas): grey-on-white media rim + integrated header + matched resize arc
- `1d486014` design(canvas): defined rim + off-edge resize arc on photo & video cards

## 2026-06-14

- `ba729883` feat(workspace): smooth push for the workspace-detail rail + clearer toggle
- `bbc32b57` feat: o8 menu-bar tray icon → new o8 monogram (white template)
- `01b866af` design(canvas): rename Alerts dropdown + make rows jump to their surface
- `cee2ba1f` feat(workspace): footer merge beacon -- fleet-wide "ready to merge" pill
- `36045df8` feat: new o8 app icon — aurora Liquid Glass o8 monogram
- `815d183b` design(canvas): glass onboarding panels + behind-glass motes reel, match reel type
- `b14bd28d` feat(workspace): consolidate orchestrator composer chip row + adaptive icons + blocky-o8 boot loader
- `6da8ab74` feat(canvas): first-run welcome modal + guided coach-mark tour
- `d9d1fab3` feat(canvas): add orchestration MODE selector (Fleet / Single / Fusion) to the canvas composer
- `a25816f0` feat(canvas): add Clerk account dossier to the canvas top-right
- `54fd494e` feat(canvas): add video cards
- `136a31d4` feat(auth): desktop ticket exchange + sign-in handoff (Clerk signals API)
- `ec5836a7` feat(auth): GitHub sign-in via Clerk — shared hook, account UI, o8:// receive
- `b980aaac` feat(canvas): merge composer model+thinking into one drawer; wrap file cards
- `0e3c9168` feat(canvas): sphere-projection orb navigator + single-toggle bubble UI
- `f0835922` feat(canvas): readable o8.md + terminal fonts, caret-correct spec card

## 2026-06-13

- `b8740e13` feat(mcp): operator MCP server supports a shared HTTP transport
- `9861ef86` feat(canvas): result-card synthesis from the orchestrator tool stream
- `aa47b98c` feat(canvas): rich response blocks shared + o8 bench parity + reasoning in seconds
- `55476668` feat(canvas): dock solid edge + chat modal at agent-card bench parity
- `a35ac23f` feat(canvas): all-angle hidden resize on the chat-card
- `ba13e494` feat(canvas): shared CardComposer
- `24b81051` feat(canvas): smooth borderless chrome on dock + chat-card
- `78e1e612` feat(canvas): borderless DockEntryView
- `575876ee` feat(canvas): agent-card bench — side-by-side presence comparison
- `6d7fa7ad` feat(canvas): agent-card bench — PR + edited-files result variants
- `ddcaf9d4` feat(canvas): agent-card bench
- `996ec5e9` feat(canvas): agent-card bench — user messages + smooth Brain citations
- `45040818` feat(canvas): agent-card bench
- `2e534d50` feat(canvas): agent-card bench
- `374945e2` feat(canvas): pinned orchestrator dock + split-tab orchestrator modals
- `e9dd88b7` feat(canvas): default theme is the operator's tuned light look
- `024e91b9` feat(canvas): match reference
- `3b4d3b6d` feat(canvas): orchestrator is a floating draggable card, Brain tab renamed o8
- `2efcd3da` feat(canvas): orchestrator + brain spawn as one tabbed pane — never orchestrator-alone
- `3a8f8958` feat(canvas): unified theme panel
- `275584df` feat(canvas): dock orchestrator gets its own light/dark + tint dial

## 2026-06-12

- `116ef97d` feat(browser-engine): headless installed-Chrome tier
- `afea081e` feat(canvas): intent bus
- `1bf20111` feat(browser-agent): agents drive the embedded browser
- `55a05cf2` feat(canvas): the everything run
- `94d7ba97` feat(canvas): UNIVERSAL text slider
- `05fb9a4e` feat(canvas): chat ink control (Auto/White/Dark) + 100px chat frost + reasoning TIMELINE
- `4fb1867e` feat(canvas): glass TONE axis (dark/Ivory light) + floating-chat sliders + live reasoning & image entries
- `ee9a94b2` feat(canvas): agent lifecycle lands live
- `92061a8b` feat(canvas): persistence + talkable chat cards + project-grouped repos; drop scratch chat from o8.md card
- `68bafe30` feat(canvas): o8.md card at FULL parity — mounts the real spec pane in glass
- `93421332` feat(canvas): agents can open pages in the canvas browser via o8:open-browser
- `97226227` feat(canvas): browser tabs in glass browser cards + review drawer refetch-on-open
- `fab3fa08` feat(canvas): real diff cards with governance row + review drawer; retire center emblem; sessions repo filter
- `0f02946d` feat(canvas): element picker in browser cards — front-end selector tools
- `55002928` feat(orchestrator): composer images actually reach the model — both surfaces
- `86e6e178` feat(canvas): dock gets its own composer + turn cards + drawer-styled term picker
- `72b80175` feat(canvas): Pulse is the real agents-working mark — the o8 binary orbit
- `cf881d3c` feat(canvas): Pulse rebranded — the o8 dual-orbit mark in faded dither
- `187a2963` feat(canvas): sessions drawer on the left nav + the amber Pulse backdrop
- `d1150d22` feat(canvas): dock tool calls collapse into one live activity line
- `663f2ef3` feat(canvas): operator-picked depth set — wind-dots field + custom shader moods
- `a788f12d` feat(canvas): real Paper Shaders depth layers — WebGL, barely moving
- `0e61e8ab` feat(canvas): depth backdrops + opaque popovers + o8.md reads like a page
- `a6fad007` feat(canvas): past sessions open as their own draggable glass boxes
- `263f112b` feat(canvas): senior pass
- `faa80abb` feat(canvas): photos surface reference-style — image cards, stacks, top-right search
- `522e0367` feat(canvas): Apple-smooth squircle corners + the dock becomes a real panel
- `94f1f0dd` feat(canvas): markdown rendering in the docked chat
- `7c9350f3` feat(canvas): talk to the REAL orchestrator from the canvas composer
- `2d81c231` feat(canvas): Finder "Open With → o8" — OS file opens land as canvas file cards
- `b213e4ce` feat(canvas): file cards
- `0391c53e` feat(canvas): spawn reveal easter egg + summoning verbs + edge-rail handles
- `c5cf3b52` feat(canvas): terminal cards v2
- `d5c7a79a` feat(canvas): real terminals as glass cards + Liquid frost floor
- `695caf87` feat(canvas): glass tuner docks under the Canvas word + "Save as my default" personal preset
- `5fdbfafc` feat(canvas): Liquid frost dial
- `6e156f1a` feat(canvas): docked orchestrator, component cards, image drop, liquid-clear background
- `6c75607d` feat(canvas): background controls

## 2026-06-11

- `dbab17d4` feat(canvas): desktop-clear glass, material presets, kivo summon choreography
- `351fe29c` feat(canvas): v2 glass slice
- `4a1f5b1b` feat(canvas): fleet-canvas v1
- `74225234` feat: workers get the Engineering Brain
- `7b2c8e4e` perf(brain): classify/retrieve overlap + semantic answer cache
- `2359908c` feat(brain): sources parity
- `74c9f3f3` feat(brain): Ask Brain streams — UI switches to the SSE route
- `5471ea8e` feat(brain): spend ledger + daily cap on the OpenRouter tier, 'fastest' composer knob
- `d6d4e92a` perf(brain): warm REPL pool
- `eddc17a2` perf(brain): Tier-0 latency pass
- `468010b7` feat(composer): orchestrator model switcher in the thinking chip + Ultracode label
- `11d760c0` feat: voice agent terminal voice control adds iTerm2

## 2026-06-10

- `44ca2107` feat: voice agent speaking-speed control
- `21c66382` perf: voice agent calendar list goes native EventKit
- `168567de` feat: voice agent update verbs
- `a86b7a84` feat: voice agent second-ten-minutes
- `6f020d59` feat: voice agent day-one basics
- `5c1e1680` feat: voice agent parity round 3
- `8c490252` feat: voice agent terminal brake + keys + new session, o8 recap + usage (parity round 2)
- `f64eaf1b` feat: voice agent terminal voice control v1
- `36a4ffd8` feat(mcp): o8_operator_defaults tool + EXTERNAL_AGENTS.md — external-agent control parity
- `8fad1f02` feat: voice agent controls Apple Music
- `f7267e37` feat: voice agent edit lane works inside o8 + o8-control frontier v1
- `808c6c21` feat: permissions health
- `46f512eb` feat: voice agent Guide pointer — dwell variant of Points (magic roadmap)
- `c85b8b67` feat: voice agent "what needs me?"
- `53180b4b` feat: selection-as-object
- `5dcbe634` feat: dock chat continuity
- `8e48df45` feat: voice agent routing doctrine in the system prompt + presence-layer architecture doc
- `67b614ff` feat: memory glints + worker-pulse orbit
- `f7aaa7c1` feat: drag-files-into-voice agent
- `1e81dc7b` feat: voice agent Points
- `6361ff5e` feat: Option = voice agent agent (both keys), double-tap Option = long question, say -> Option+S
- `dba8203d` feat: voice agent opens any installed app — fuzzy open_app + list_apps tools

## 2026-06-09

- `fc9e9c96` feat: unit-test harness (vitest + cargo), CI test gate, CLI version armor

## 2026-06-07

- `55c24ca5` feat: catch dashboard mount crashes in preship gate
- `17c17370` feat: add blind second-pass auto-review
- `72507a60` feat: one-click "Clean up" button for stale workspace tabs

## 2026-06-06

- `be57c039` feat: doctor flags runtimes that are installed but not authed
- `261f676f` feat: keyboard-navigable orchestrator steer queue

## 2026-06-04

- `ed97edb9` feat: open a non-Git folder as a repo

## 2026-06-03

- `591d6296` feat: align feedback report embed fields [via-o8]
- `993f1dbf` feat: add settings feedback reports [via-o8]

## 2026-06-02

- `f2f8c5e4` feat: add webview idle guard lint [via-o8]
- `0ac73eab` feat: add preship webview boot gate [via-o8]

## 2026-06-01

- `01a8bd2e` feat: add repeatable benchmark suite [via-o8]
- `21d95daa` perf: defer cold boot desktop polling [via-o8]
- `4b834805` feat: route literal o8 lookups to grep [via-o8]
- `e5d24652` feat(qa-eval): rigorous 4-way Brain-vs-grep
- `f57815b9` feat: add strong grep qa eval baseline [via-o8]
- `a9fdbfe8` perf: lazy hydrate o8 secondary panes [via-o8]
- `1125c05f` perf: add server timing to hot routes [via-o8]
- `67d1ad38` perf: add client benchmark instrumentation [via-o8]
- `33e075ea` perf: add app speed measurement harness [via-o8]
- `1d19900a` feat: mirror agent visual proof onto GitHub PRs via release assets
- `8baa3b36` feat: live WS artifacts channel so proof strips update in real time
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
- `ddeca542` feat(analytics): cost stays king + autonomy & governance on top
- `0f6e279b` feat(chat): hide the o8-Default casual chat for alpha behind experimentalChat
- `eb0d8eab` design(settings): neutral + royal-blue accent, squircle corners — no orange
- `6d1362f9` feat(dispatch): ship AI provider + agent runtime only
- `971b6f45` feat(orchestrator): UltraCode swarm = native AI provider sub-agents (workflow) + agent runtime via o8

## 2026-05-30

- `5a46ace6` perf(webview): kill the transcript-poll socket leak + remove dead git-watch SSE
- `f2e977ae` feat(orchestrator): UltraCode swarm tier + inline crew cards; retire Cmd+Shift+O popover
- `d5ca5262` feat(dispatch): swarm composer
- `f0afce0b` feat(dispatch): allow agent runtime+AI provider mixed swarms (relax force-to-agent runtime gate)
- `8ebc4b50` feat(status): lower long-run orbit threshold 7min → 1min
- `280eca60` feat(status): wire the dot vocabulary into every agent surface
- `c33021b9` feat(agents): deterministic per-agent identicon
- `c67772fc` feat(status): orbit working-indicator everywhere — orchestrator + LLM chat
- `0e887fde` feat(status-dots): full motion vocabulary + long-running orbit on agent dots
- `329d1180` feat(orchestrator): inline detail drawer for status cards, not a modal
- `afc041e0` feat(sidebar): surface spawned agents + archived in every session grouping
- `9136fa58` feat: add review last turn scope [via-o8]
- `8f11b892` feat(pr-panel): wrap PR diff lines by default
- `d8305f0c` feat(workspace-header): wheel-scroll + edge-fade for overflowing tab strip
- `034b08c2` feat(review): word-wrap diff lines by default

## 2026-05-29

- `8e52fcef` feat(orchestrator): deliver the Mission-complete card for dispatched missions
- `dad4712d` feat(orchestrator): explain what shipped in the mission-complete detail modal
- `48dac586` design: extend locked typography to Activity packet card + session strip
- `b9a73e0a` design: bring packet/status/merge cards to the locked typography spec
- `f2303f96` feat(orchestrator): merge + self-heal status cards with click-through detail view
- `5d3688fa` feat(orchestrator): themed animated status card for mission-complete events
- `24dd2212` perf: prewarm bundled next server [via-o8]
- `557678d5` perf: log dashboard boot timing [via-o8]

## 2026-05-28

- `15f78045` feat(agent runtime-composer): wire attached images into the send payload (sub-pass B)
- `532ef6c1` feat(agent runtime-composer): in-composer footer parity via shared InputButtons (Pass 3)
- `eaefb2b8` feat(agent runtime-composer): repo / branch / runtime chip row below the composer (Pass 2)
- `18f722d0` feat(agent runtime-composer): image attachment chips above the textarea (Pass 1)
- `b715a353` design(tabs): V1 continuity transition on the workspace tab strip
- `6668aa09` design(automations): design system pass on AutomationsPage typography
- `8db6ed27` design(chrome): design system pass on Cmd+K palette typography
- `90a4db80` feat(cmd-k): chat history + directives providers ( subset)
- `9fe1f622` feat(review): rich preview toggle for markdown + images
- `000d3366` design(chrome): design system pass on keyboard-shortcuts modal + agent-panel top-nav

## 2026-05-27

- `40f12611` design(session-replay): staggered entrance + ambient hover on lane cards
- `fec90f86` design(timeline): drop inline play + design system pass on timeline + Session Replay page
- `80b5b012` design(typography): repo hover + alert toast + mobile pair to design system spec
- `0704b61a` design(chrome-button): bespoke per-icon motion — gear spins, phone leans, folder lifts
- `ff86b224` design(chrome-button): tilt + nudge icon, not scale
- `8b651e29` design(chrome-button): icon micro-motion on hover — match title-bar pattern
- `b27bc207` design(o8-panel): repo selector + Ask o8 button get flat hover bg
- `162f0a5d` design(o8-panel): activity filter pills get flat hover bg
- `352e5e1b` design(globals): kill the global button:hover translateY — flat-button lock
- `41ae0eb4` design(agent-panel): flat hover chips for header rows — match terminal toggle
- `15b4ee0f` design(empty-state): thinner title + questions above composer
- `d9b0034e` design(empty-state): tighten title↔composer gap + repo chip leftmost in chip row
- `bc5228b9` feat(update-card): real release summary from free OpenRouter pool
- `50830b88` design(layout): center empty state in available space + relocate UpdateCard
- `711d9e68` design(bottom-panel): tab pill weight 300 — design system chrome lock
- `b0276500` feat(bottom-panel): surfaces beyond terminal
- `1ae2acc5` feat(settings): drop the 1080 width cap — content fills the full viewport
- `8a551b1a` feat(settings): full viewport — fixed position instead of column-bound
- `04aa8761` design(add-repo): design system font pass + simpler copy + Scan hidden until folder picked
- `3e8f5cb9` design(status-bar): drop pill chrome on solo settings + inbox active
- `e52b2eae` design(chat): professional paragraph spacing — gap on every block
- `96ac792b` feat(agent-panel): hover preview = real AgentPanel below traffic lights
- `bca12941` feat(agent-panel): merge ports + inbox pills into one locked cluster
- `551d2ce7` feat(agent-panel): outer margin + wider default + hover-preview drop
- `818d6ee8` feat(agent-panel): wire orchestrator worktree pick to bottom status pill
- `e7653ef9` feat(agent-panel): simplify composer chips (mode + repo)
- `98a39c54` feat(brain): caption images in spec ingest so Engineering Brain can see specs
- `53f13374` design(agent-panel): surface-aware ink + transparency in glass mode
- `3fa3a58c` design(ui): sweep entire o8 surface to locked design system font spec
- `f584b07d` feat: push mobile live activity updates
- `4054b610` feat(orchestrator): compose-first empty state + sidebar lifecycle fixes

## 2026-05-26

- `bc5946b1` design(agent-panel): Antigravity pass — Iconoir launcher + right-rail alignment
- `a8dc5736` feat(drag-drop): native shell 2 bridge for Finder file paths
- `c3452456` feat(projects): SQLite is now source of truth for color + sort + active ( phase 2)
- `d49c3089` feat(db): schema v25 + projects ledger JSON→SQLite migration ( phase 1)
- `00f8168c` feat(compactor): weekly digest cron + delivery wrapper ( phase 2)
- `cb137903` feat(compactor): --digest-to flag writes markdown summary

## 2026-05-25

- `270dcc34` feat: tray dropdown lists awaiting-review packets
- `ec169eda` feat: directive surfacing in review + agent runtime-only worker enum
- `bb3b95fe` feat: inline TurnSummaryCard + ChatActionCard for orchestrator turns
- `32842551` design: design system theming pass
- `9f48b482` feat: emit mobile activity preview urls
- `0e7a6cfe` feat: route orchestrator ws events by thread
- `98ce11f4` feat: broadcast orchestrator thread sync events
- `995155ef` feat: add mobile orchestrator thread creation
- `19880826` feat: add steer packet MCP tool [via-o8]
- `dfa569be` feat(orchestrator): layered escalation on merge-tsc failure

## 2026-05-24

- `d26c5929` perf(brain): soften composer tightening from — restore factual accuracy
- `3d0e9af3` feat(orchestrator): parallel mission queries via SQLite registry
- `c17a5367` feat(brain): three-way memory-substrate eval harness
- `d78d590d` perf(brain): warm OpenRouter pool at boot to kill cold-start classifier
- `9d0632c7` design(scratch): premium dot + cost-hint legend on O8ScratchChat composer
- `e21a1ce4` perf(brain): split H2 spec chunks on H3 when ≥3 kids or >4KB
- `71815282` perf(brain): classifier — OpenRouter tier 1 + 60s cache
- `4e1666ca` feat(brain): Ask Brain composer button in O8ScratchChat
- `11550c82` feat(brain): spec ingestion at repo connect

## 2026-05-23

- `5778d610` design(panel): cascade flat-button language to scratch chat + inbox + activity
- `8f11e0cc` design(panel): cascade flat-button language to O8 + PR panel surfaces
- `8239d483` design(spec): lock flat-button language in DESIGN.md + flatten shared primitives
- `e16fd1f4` design(panel): flatten all remaining header buttons to match HeaderIconPill
- `690c7e40` design(panel): generic HeaderIconPill — flat icon pill for header strips
- `0bf0d592` design(panel): flat toggle pill, baseline-matched across sidebar open/closed
- `d9e5dd05` feat(panel): toggle pill matches HeaderPill language + framer-motion variants + traffic lights y=22
- `2552f651` feat(panel): floating-card pattern for left column
- `2aa5df5e` feat(left-panel): dainty 1px divider between left panel and workspace
- `e19413b6` feat(left-panel): hide Control tab from project-focus drawer
- `272704b1` feat: use git diff review icon [via-o8]
- `c5e718e8` feat: auto-widen o8.md panel tab
- `8042207a` perf: short-TTL cache on repo registry readStore (5s)
- `155ae223` feat: stamp mergedClean on session_outcomes when a merge lands
- `e15d9357` perf: stale-while-revalidate cache on getRepoReadiness (Phase 5)
- `e73440cb` feat: directive proposals close the loop in-app — Accept writes the file (Phase 3)
- `cdf82754` feat: persist packet completions to session_outcomes ledger (Phase 2 of)

## 2026-05-22

- `07cc6d5f` feat: pre-launch typecheck gate on freshly-created worktrees
- `f3fb7caf` feat: right-click an o8.md inline image to add it to the chat
- `47470584` feat: o8.md inline images render consecutive lines as a gallery row
- `948dcf0b` feat: render inline images in o8.md (small thumbnails + lightbox)
- `aba43281` feat: inline image authoring in o8.md (drop/paste → o8-assets)
- `21ccce3f` feat: o8_view_scroll + o8_view_press_key webview tools (pre-ship Phase 4)
- `ced12e70` feat: o8 packet diff/commit + o8_packet_diff MCP tool (pre-ship Phase 4)
- `d0de2c1c` perf: parallelize packet-info's events + scope fetches (pre-ship Phase 3)
- `aa9012ee` perf: token-bound the o8 CLI command outputs (pre-ship Phase 2b)
- `54f8dc21` perf: token-bound the MCP + webview tool outputs (pre-ship Phase 2a)
- `89757b76` feat: wide control-room mode

## 2026-05-21

- `e04bdae6` feat: shared project-scoped repo selector across Workspace + Activity
- `f8990fe0` feat: split project select from open-control-room (row click selects, chevron opens control room)
- `bfedb404` feat: switching the active project re-points the whole app (O8 panel + new orchestrator) to its primary repo
- `b20ea567` feat: lone pool repos surface as switchable single-repo projects
- `9bcd5a80` feat: o8.md review notes fade in on the rail (framer-motion enter, new notes only)
- `9223b62a` feat: o8.md review runs headless one-shot, no orchestrator chat turn
- `f5d1464c` feat: o8.md note color - add black + neutral swatches alongside the hue picker
- `9c3f54d3` feat: o8.md note settings - hue chooser drawer + desaturated in-note buttons
- `857b49eb` feat: o8.md notes reserve prose room only-when-needed via block spacers (no anchor drift)
- `44cb1aae` feat: tighten o8.md review prompt - only-when-real, read-first, commit-aware
- `a24f03de` feat: o8.md click-first review button + reply lands at thread bottom
- `a30a837f` perf: debounce o8.md rail recompute + comment resolve/reply
- `cf752f36` feat: o8.md panel now uses the CodeMirror review editor (the swap)
- `4ea7e4df` feat: interactive task checkboxes in the o8.md editor
- `736624e9` feat: o8.md margin-note rail + accept/dismiss in the CM6 editor
- `ed3df3bb` feat: wire the o8.md suggest verb across API + CLI + MCP
- `c53fd53a` feat: surface operator o8.md threads in dispatch context (phase 3)
- `6138ceaf` feat: external AI provider can read + annotate o8.md via CLI + MCP (phase 2)
- `04353aa9` feat: theme-align proposed directives + unread hierarchy
- `855fd27a` feat: power-user chrome keyboard shortcuts
- `dce591cc` feat: keyboard shortcuts reference overlay (⌘/ or ?)
- `b948a32b` feat: popover menus always mounted (display toggle) for agent enumeration
- `309d85dc` feat: tab icon morphs to close-X on hover + disambiguate split aria-labels

## 2026-05-20

- `7edc04b4` feat: group picker is icon-only + sits inline with first group label
- `344a6f22` feat: chat-list group-by picker (Repo / Date / Flat) + uppercase headers
- `5b9dcd9d` feat: shimmer placeholder during thread restore (no more empty-state flash)
- `06b4a7a3` feat: pre-set tab.label from saved orchestrator title at tab creation
- `01586566` feat: GC orphan empty thread files during list calls
- `13df1493` feat: persist last-active orchestrator thread across reloads
- `219ceae3` feat: inline rename for chat titles in column header
- `e38e6e49` feat: per-pane ▶ play + one × close, all in split header
- `31ca3c9d` feat: side-by-side header pills for splits with center divider
- `e9b15be9` feat: merge-state preview cycler in status bar
- `f871fe9a` feat: terminal toggle moves to status bar next to branch label
- `bb380bf0` feat: terminal toggle moves to bottom-center floating chip
- `8b7796f0` feat: inline split-pane controls (▶ + ×) + cap at 1 split
- `4c796ed8` feat: kill the lower per-workspace TabBar — pills are the only tab UI
- `dd7ec93b` feat: top header morphs into agent runtime-style pill strip when 2+ tabs
- `1a7bc860` feat: ▶ play button in global header when single workspace (trial)
- `06a8ca65` feat: hide lower TabBar in single workspace mode
- `a4b8e28e` feat: title-bar … menu (rename/archive/share) + tighten 44→36
- `9f5656c8` feat: chat title moves UP into the column header (agent runtime pattern)
- `7f1f50fe` feat: chat name lives IN the workspace header (step 1)
- `082a067b` feat: top tab bar goes flat
- `0c0d01b9` feat: top tab bar is now bespoke — width-gated, spawned-only
- `beef2a76` feat: unified packet-state color scheme for top tabs + left rail
- `42e49884` feat: archived agent sessions inline under each repo in left rail
- `e3d5f0cf` feat: orchestrator history merges into left rail (Chats + Agents tabs)
- `13ee3b47` feat: orchestrator composer trim — drop enhance + copy, compact send

## 2026-05-19

- `bde123b4` feat: Automations scheduler
- `393dfe24` feat: Automations polish
- `e21f1bab` feat: Automations nav entry in left rail (agent runtime borrow)
- `39ff9331` feat: Automations
- `5c89d378` feat: scratchpad falls back to workspace-wide diff when no file is selected
- `77ddbefb` feat: ⌘⏎ steer queue in orchestrator + chat composer
- `3c841613` feat: timeline off by default
- `3fd3e2d0` feat: Shell layout
- `3d51860e` feat: Shell layout
- `adb50379` feat: Shell layout — per-column header strip components
- `0452b9eb` feat: add agent runtime-only task pool routing
- `01afe962` feat: Review surface
- `33f829f1` feat: Review surface — repo selector in the header
- `70419245` feat: Review surface — untracked files render as all-added
- `1c96abc3` feat: Review surface — word diffs + hide-whitespace toggles
- `ba9a681b` feat: Review surface — Commit / Push / Open PR toolbar actions
- `2d28cc0b` feat: add project task control plane
- `fe79f706` feat: Review surface
- `ead10259` feat: Review surface
- `0b074d5f` feat: agent runtime-style Review surface

## 2026-05-18

- `1d79b928` feat: agent runtime orchestrator — governed gateway + per-request agent
- `86c8d7a9` feat: mobile agent runtime orchestrator surface — backend-tagged threads + contract
- `6f22e99b` feat: agent runtime orchestrator backend + per-request backend selection

## 2026-05-17

- `c8262a79` feat: mobile activity feed + orchestrator packets API routes

## 2026-05-16

- `650ee259` feat: desktop QR pairing emitter for the o8 mobile app

## 2026-05-15

- `450c15da` feat: add AI provider billing verification smoke
- `bd8a9167` feat: add agent runtime interactive session [via-o8]
- `8c8d6811` feat: render agent runtime chat events [via-o8]
- `4d9eb0dc` feat: extract AI provider-code stream-json parser into a module
- `ebf444e7` feat: AI provider-code composer model pill + plan/bypass toggles
- `a87bfaa7` feat: restore AI provider-code as interactive chat-tab runtime

## 2026-05-14

- `d3feecf1` feat: github intake dual-path
- `d875c80a` feat: promote agent runtime CLI to effective tier 1 in Q&A cascade when in-app orchestrator is off (epic child 4)
- `38f242db` feat: add agent runtime-orchestrator-session + wire auto-review dual-path (epic child 2)
- `d1d2f042` feat: gate AI provider-billed paths behind in-app orchestrator toggle
- `7c417f02` feat(cli): phase 3 polish + native shell bundling + npm-publish prep

## 2026-05-13

- `a717af60` feat: modernize workspace runtime reconnect banner
- `98b54fce` feat: modernize stale-gateway alert in AgentPanel
- `04fd4e64` feat: branch details launcher + modernized connection banner + chrome polish
- `77d7f21d` feat: add packet mission tail stream [via-o8]
- `9e81c74c` feat: add o8 observation proposals [via-o8]
- `ac752fce` feat: add lane touch lookup
- `56cb0236` feat: add packet agent report events [via-o8]
- `e72dead6` feat: add packet scope surface [via-o8]
- `eaff9cf2` feat: /api/panel/status returns server version for o8 CLI
- `93f951e8` feat(cli): scaffold Phase 1 of the o8 CLI (epic)

## 2026-05-12

- `370b9b8e` perf: symlink node_modules into worktrees instead of cp -cR
- `1938fba8` feat: add MCP repo+project bootstrap tools — wedge unlock
- `89e5ce91` feat: add MCP repo+project bootstrap tools — wedge unlock
- `d9c98abc` feat: add MCP repo+project bootstrap tools — wedge unlock [via-o8]
- `b883fa94` feat: add MCP repo+project bootstrap tools — wedge unlock
- `1a12fa75` feat: add MCP repo bootstrap tools
- `7c7bf11d` feat: default to light theme + solid chrome on fresh install [via-o8]
- `08640c96` feat: default to light theme + solid chrome on fresh install

## 2026-05-11

- `ab8cd18b` feat: add typed webview latch

## 2026-05-10

- `d5996773` feat(projects): seed scope:project directive + projects field doc [via-o8]
- `796cb1f1` feat(projects): seed scope:project directive + projects field doc
- `90faf7b2` feat(projects): seed scope:project directive + projects field doc
- `b03e5420` feat(projects): seed scope:project directive + document projects field
- `74d44dcf` feat: timeline reads 24h of session history (tail 500 → 15000) + finer cells
- `15e189f3` feat: add mcp__o8__rerun_with_feedback tool
- `a7e1dee8` feat: scope orchestrator memory by project [via-o8]
- `ff8e885f` feat: render chat tool calls as chips [via-o8]

## 2026-05-09

- `3364a166` feat: vocabulary cleanup
- `a611d67d` feat: live HTML rendering — .html viewer + richer o8.md renderer
- `50d5c396` feat: one-click install of o8 MCP into Hermes Agent + agent runtime

## 2026-05-08

- `e8e75310` feat: voice agent-style push-to-talk dictation
- `920e629d` feat: competing product-style PR panel + segmented context popover
- `033f580e` feat: add macOS APFS workspace isolation
- `4bb987a4` feat: agents archive drawer shows every concluded packet
- `987202e9` feat: unified project panel + agent / timeline polish
- `76dcc4f0` feat: add slash orchestration routing
- `c46e8b3c` feat: pulse the rightmost timeline cell, drop drilldown trigger
- `7251e0a1` feat: rolling 24h timeline + error surfacing + settings toggle
- `f7c64712` feat: rewrite SessionTimeline as Tracker strip + redesign hover card

## 2026-05-06

- `5800c266` feat: flatten new-tab drawer to Orchestrator / Chat / Terminal
- `b32cef59` feat: orchestrator mode chip + slash-command routing
- `5f672464` feat: two-axis theme system (palette × surface) + reduce-transparency toggle
- `c017bc38` feat: skiper-style motion on search + browser titlebar buttons
- `98f546b5` feat: skiper-style motion on titlebar left buttons
- `e1010740` feat: align titlebar left buttons with right side; agents glows orange
- `ab71b761` feat: empty project gets a primary "Add a repo" + quick-pick from other projects
- `b70b1027` feat(palette): switch projects + move repo from Cmd+K
- `4de26a1a` feat: project colors + drag-drop repos onto dots + empty-project hint
- `56fc03ad` feat: rename / delete projects + move repos between them
- `d82af473` feat: status bar centers under the workspace + cluster matches chrome chip shape
- `1ec86716` feat: status bar centers branch + adds contextual merge action pill
- `8952101e` feat: O8 right panel opens on the Pulse tab by default
- `26e98fb2` feat: projects scope the left panel with a bottom-bar dot switcher
- `d4c07597` feat: hover × on each spawned agent row to dismiss it from the panel
- `3666075d` feat: single-runtime chat lifecycle + 3-word tab labels everywhere
- `dcd8c7d8` feat: breadcrumb minimizes to filename only by default
- `4d1b05b4` feat: Changes count gains a cool-to-warm urgency badge
- `67960804` feat: move repo selector into the changes rail to free file path space
- `5c564bf0` feat: chat tabs adopt 3-word summary from latest user message
- `01613ebb` feat: tab strip uses theme-tinted glass instead of raw vibrancy
- `71187351` feat: round workspace top corners and inset tab cluster
- `38a9edc2` feat: tab strip becomes vibrancy-passthrough glass
- `ef5357fb` feat: hide thinking chooser in chat tabs and rename Assistant row to Chat
- `56744b34` feat: chat-mode chooser spawns dedicated tabs with tool-wired chat
- `fa396dbe` feat: align orchestrator empty state
- `1aee38c5` feat: refine o8 settings and analytics ui
- `62100102` feat: refine o8 activity review surfaces

## 2026-05-05

- `7c43f059` feat: redesign o8 pulse briefing
- `478ec8bf` feat: refine o8 workspace panel

## 2026-05-03

- `6d63cfe2` feat(workspace-tab): green tab marker when packet status === released
- `3a6c58c5` feat(workspace-chat): inline status banner at bottom of dispatched chat
- `5fbce8ae` feat(o8-panel): consolidate Mission rail into Activity tab
- `0b48b875` feat(o8-panel): packets render in Activity timeline behind opt-in flag
- `56c30780` feat(orchestrator): NEEDS YOU click pops O8 Workspace pinned to the lane's worktree
- `58554aa3` feat(orchestrator): per-section click routing for Recent Work rows
- `5fbd890e` feat(orchestrator): status-anchored Recent Work — Needs you / In flight / Done today
- `c4dfad89` feat(o8-panel): path-lens chip on Workspace tab — shows main vs worktree at a glance
- `7b1eac39` feat: replace o8 file tabs with workspace
- `0ff128a5` feat: add o8 workspace pane components

## 2026-05-02

- `b7e0affe` feat(o8-panel): restore Pulse tab — live fleet temperature surface
- `8319ee71` feat(orchestrator): composer footer threads/copy/new + thinking <details> popover
- `3a44bba7` feat: stream orchestrator chat from gateway
- `5e28f087` feat: add clerk gated chat route
- `54771cb9` feat: add chat gateway server helpers
- `daa4cef7` feat: route orchestrator chat mode locally
- `22273536` feat: add chat mode card
- `d937e6c1` feat: add orchestrator chat model picker
- `7a4b4fb8` feat(mcp): wait_for_mission_ready
- `c83eebfa` feat(orchestrator): wire useFileDrop into ComposerArea

## 2026-05-01

- `6cae523e` feat: auto-release merged review packets
- `b2b90f3c` feat: tighten supervisor inbox signal
- `4dace31a` feat(browser-button): hover preview iframe of the active browser tab
- `f50020d3` feat(titlebar): promote Browser to top header slot
- `58c842fb` feat(left-panel): collapse branch + agent rows into one work-unit line
- `c794c1e5` feat(left-panel): repo focus expands the column inline, no overlay
- `30ff04aa` feat(chrome): move update notice to footer pill, drop top-right toast
- `ff3f0c12` feat(repo-focus): back-arrow polish + ESC-to-close
- `9d5ebc1d` feat: add o8 diff and spec tabs
- `3ff8e1f6` feat: add ambient right panel
- `e1402ef0` feat(repo-focus): Spec + Files tabs + first-class CLI usage strip
- `717f5567` feat(ui): repo-focused left-panel mode with Agents/Context/Mission tabs
- `f28c2029` feat(native shell): O8_DEV_FRONTEND_URL override for hot-reload prod loop [via-o8]
- `22bddea0` feat(native shell): O8_DEV_FRONTEND_URL override for hot-reload prod loop [via-o8]
- `2885036a` feat(native shell): O8_DEV_FRONTEND_URL override for hot-reload prod loop [via-o8]
- `a41bc632` feat: support dev frontend override in native shell

## 2026-04-30

- `81e51e7b` feat(ui): hide agent runtime pickers behind experimentalagent runtime + thicker tabs
- `1166d5d4` feat(operator): default thinkingEffort to high (was adaptive)
- `de689665` feat(runtime): drop agent runtime from default dispatch picker
- `d76702b3` feat(brain): fs.watch on docs — incremental re-distill
- `b8212560` feat(brain): embeddings column + hybrid retrieval
- `3f18657c` feat(brain): qa-eval regression dashboard
- `28aade08` feat(brain): post-commit hook feeds facts substrate
- `0d3d7d00` feat(ui): /ask quick action in chat composer
- `e3f12505` feat(brain): in-process compactor scheduler
- `5d15d1b4` feat(brain): bring-your-own OpenRouter / AI provider key surface
- `1a8432b9` feat(ui): Recall Card — top-N facts ambient surface
- `3cf3d4fb` feat(qa): configurable Class A composer model
- `19f4451d` feat(qa): Phase 2b
- `f92d7ed2` feat(qa): source-update detection + source-of-truth hierarchy
- `c38e4d93` feat(qa): fact compactor
- `a31eb634` feat(qa): Phase 2a
- `cd883202` feat(indexer): heuristic noise pre-filter at enqueue ( north star follow-up)
- `e1005e18` feat(indexer): parallel worker with O8_INDEXER_CONCURRENCY ( north star follow-up)
- `5fb0e0df` feat(qa): Engineering Brain Indexer worker
- `33fde327` feat(qa): pin top-6 facts above other retrieval rows ( north star)
- `c742f23a` feat(qa): smoke:qa fast eval (6 cases, <2min) replaces 30-case heavy eval ( north star)
- `7baed364` feat(qa): facts schema v17 + retriever foundation ( north star)
- `69631b3a` feat(qa): docs_fts ingestion for project rules / README / AGENTS.md ( path-to-70 phase 1.7-)
- `bcd0cf22` feat(qa): github_comments_fts ingestion ( path-to-70 phase 1.7-)
- `63aa9d81` feat(qa): rebench OpenRouter primary with credited key ( path-to-70 phase 1.7.1)
- `e18f0aa6` feat(qa): lock OpenRouter primary to grok-4.1-fast from empirical bake-off
- `ae9bd305` feat(qa): project + project_repo retrieval in sqlRetriever ( path-to-70 phase 1.4)

## 2026-04-29

- `0f3483df` feat(qa): 30-question eval set + runner skeleton (epic sub-3 wave A)
- `7b60b3a4` feat(qa): Schema v14 + FTS5 + retrievers (epic sub-1)
- `c3107842` feat(qa): Ask Anything UI scaffold + mock stream (epic sub-4)
- `f529dff4` feat(projects): AI Stage 2 LLM project suggestions + Confident/Plausible UI (epic wave 2)
- `f5b3b608` feat(projects): Settings → Projects UI with manual linking + GitHub-org auto-suggest (epic wave 2)
- `628495ba` feat(projects): Recall Card Project pulse section (epic wave 2)
- `ebbfd6da` feat(projects): scope:project directives + cross-repo proposer rewrite (epic wave 1)
- `ec4e3ce5` feat(projects): schema v13 + storage + API + MCP tools (epic wave 1)
- `2fcade70` feat(projects): AI semantics Stage 1 fingerprint extractor (epic wave 1)
- `2576b08f` feat: agent-proposed spec approval flow
- `dc0508a4` feat(diagnostics): extend demo runner with mission/settings/context-graph steps (closes)
- `099b6a46` feat(diagnostics): in-app demo-sequence runner (closes)
- `9d0fd5e6` feat(panel): loop-state writer endpoint + shell helper (closes)
- `29b370cc` feat(settings): in-app loop status widget — cron + lanes + recent merges (closes)
- `24fb98f9` feat(mcp): o8_view_console_errors + o8_view_active_route — close loop observability gaps (closes)
- `40124d3c` feat(o8): cross-repo learning
- `e74dfa91` feat(o8): per-runtime outcome telemetry → dispatch routing recommendation (closes)
- `7409a9be` feat(o8): auto-directive proposer
- `44ef75b1` feat(o8): temporal validity windows on session_outcomes — auto-decay 30d (closes)
- `ead15d33` feat(mobile): Browser tab gates the chat+iframe split (closes)
- `8edf1dc2` feat(mobile): wire url-push listener into split shell + DevHostFrame handler
- `1d489b16` feat(mobile): long-press port chip pushes URL to connected phone over WS (closes)
- `b01eb931` feat(mobile): wire DevHostFrame into MobileSplitShell right pane
- `dcc44eae` feat(mobile): landscape split-view shell
- `7df82d56` feat(mobile): DevHostFrame iframe with URL bar + LAN host discovery (closes)
- `a8415187` feat(context-engine): editable packet spec.md feeds live orchestrator context (closes)
- `e1b47aa8` feat(mission-control): status-grouped lanes (closes)
- `371c020e` feat(orchestrator): suggested-reply chips under Coordinator messages
- `9dceb63c` feat(o8): living specs
- `1ead5f84` feat(context-engine): /context-graph test page — 3-column flow viz (closes)
- `5674f2d2` feat(native shell): dispatch popover redesign

## 2026-04-28

- `61138692` feat(o8): demo polish
- `9a0492ac` feat(o8): inject <context> block into packet bodies on dispatch (closes)
- `f3b26e4e` feat(orchestrator): context recall card 3-row hero (closes)
- `42bbf86d` feat(o8): auto-index registered repos at boot via codebase-memory-mcp (closes)
- `d4f25cb3` feat(mcp): register codebase-memory-mcp in .mcp.json + setup generator (closes)
- `4ae59a8c` feat(mcp): runtime-download codebase-memory-mcp on first launch (closes)
- `b65834f6` feat(native shell): global-shortcut + notification + menu bar tray (closes)
- `30b1e411` feat(orchestrator): packet review card 3-pane (closes)
- `d52ff056` perf(dashboard): defer non-critical work off the bootstrap path (closes)
- `afa0aff1` feat(workspaces): hover-reveal trash + confirm-strip + git branch -D
- `e255f348` feat(desktop): auto-hide merged + agent worktrees in Workspaces sidebar + hover-prune
- `60c892da` perf(desktop): memoize ThoughtsChatPanel message bubbles
- `cb9e73b9` perf(desktop): widen / remove short polling intervals
- `ac058e40` perf(desktop): reduce SessionVisualizer render churn
- `bb3bcc1f` feat(desktop): hit-zone audit — Settings page (44pt minimum)
- `4662f5c4` feat(desktop): hit-zone audit
- `f0da0757` feat(desktop): hit-zone audit — Approval surfaces (44pt minimum)
- `5c22d514` feat(desktop): multi-window / split-pane orchestrator transcripts
- `592029bb` feat(orchestrator): bump AI provider defaultModel to AI provider-3.1-pro
- `2c6fb4b7` feat(desktop): Cmd+K command palette across the app
- `32dbcd77` feat(desktop): one-click rerun-with-feedback on rejected reviews
- `e8b447ce` feat(desktop): inline diff viewer in workspace center
- `9af81251` feat(desktop): steer-in-flight composer on active agent transcripts
- `0bc22ad0` feat(orchestrator): drop AI provider-code from dispatch picker
- `067183e3` feat(mobile): offline send queue + replay on reconnect
- `df18c17c` feat(mobile): push notifications + Web Push infra
- `d825fcad` feat(mobile): haptic feedback
- `8c0b38f3` feat(mobile): pull-to-refresh across mobile surfaces
- `e25d03a4` feat(mobile): universal search ('/') across chats/threads/activity
- `3fa902ec` feat(mobile): markdown + code blocks in agent transcripts
- `e1caad40` feat(mobile): swipe-to-approve/reject gestures on approvals
- `b6a04b17` feat(mobile): inline diff viewer for approvals + PR cards + agent transcripts
- `fa09d3ae` feat(mobile): inline diff viewer for approvals + PR cards + agent transcripts
- `29882140` feat(mobile): inline diff viewer for approvals + PR cards + agent transcripts
- `97fc6936` feat(mobile): inline diff viewer for approvals + PR cards + agent transcripts [via-o8]
- `78412db7` design(mobile): dark mode transcript bubble polish [via-o8]
- `5ec52cf6` feat(mobile): voice input via long-press to dictate [via-o8]
- `da4f2232` feat(mobile): voice input via long-press to dictate

## 2026-04-27

- `cdac1e25` feat(mobile): read-only agent transcript sheet (v1 mobile model)
- `fc6c9899` feat(mobile): orchestrator brain chip + thread card opacity fix
- `57f05cee` feat(mobile): rename Chats→Assistant, action-weight order, sidebar subtitles, orchestrator New button
- `1c0e5a1d` feat(release): post-bundle sign + notarize for nested Node native modules
- `efc3bbfe` feat(release): wire Apple Developer ID signing + notarization
- `edf81be4` design(orchestrator): match Assistant chat breathing room and typography
- `ecb1fa2f` design(mobile): unify standard topbar across all 5 new tabs
- `83daf55c` design(mobile): scroll-fade masks on chat list/transcript/orchestrator/approvals scroll surfaces
- `a625c992` feat(mobile): profile button + Settings sheet under drawer footer
- `6a7058ef` feat(mobile): wire 5 unwired tabs (agents/issues/activity/costs/orchestrator)
- `d521569e` design(mobile): filter pills, day groupings, FAB, HIG touch-target sweep

## 2026-04-25

- `c8547569` feat(mobile): orchestrator tool bubble flips to done with output preview
- `f9684e54` feat(mobile): bind bundled Next server to 0.0.0.0 for LAN access
- `6f5388b8` feat(mobile): orchestrator composer wiring polish
- `17518b30` feat(mobile): orchestrator tab — thread strip + transcript + composer
- `49482d9f` feat(settings): factory reset button in Diagnostics tab
- `25c74382` feat(mobile): orchestrator WS hook with transcript buffer
- `6dedea6b` feat(mobile): orchestrator threads list API + types

## 2026-04-23

- `84460bc5` feat(onboarding): add default dispatch runtime step to first-run wizard
- `e3374aa8` feat(v1): gate agent runtime behind experimentalagent runtime flag

## 2026-04-21

- `8830d978` feat(AI provider): model fallback cascade on quota + in-chat pill
- `05d5039c` feat(agent-panel): Orchestrator + Assistant rows with accurate shimmer
- `77184bde` feat(hotkeys): Cmd+1-9 jump, Cmd+Opt+Arrow cycle, Cmd+W close + tab flash
- `8c57d71f` perf: kill AgentTilePane polling + fleet invalidate route + urgent WS (Packet D,)
- `fa6a8ef7` perf: rewire WorkspaceChatPane to transcript store (Packet B,)
- `3e2e844c` design(AI provider-code-transcript): emit structured toolCalls for agent runtime-parity italic dropdowns
- `1c82ea51` perf: visibility swap + render memo on tab panes ( Packet C)
- `f3eb16b3` perf: client transcript store + workspace bootstrap ( Packet A)
- `a9790994` design(chat): collapsible PacketHeaderCard replaces giant packet prompt
- `da098e4c` design(branch-hover): Rams-style status rows matching repo hover
- `6aee18d6` design(branch-hover): match repo-hover theme — solid panel, no glass
- `e53c8be7` feat(workspace): wire AI provider + agent runtime chat-pane transcript + steering
- `40f2c5eb` design: hide SessionTimeline + punchier shimmer + strip branch tooltip
- `102e3e8e` design: o8 boot splash + shimmer on active agent panel label

## 2026-04-20

- `3e66b94f` feat(workspace): wire AI provider + agent runtime into CLI Session live-tail pane
- `073aa41a` feat(orchestrator): expand OrchestratorRuntime union to four runtimes + capability map
- `dc61c806` feat(runtimes): add first-class AI provider CLI adapter
- `f835da1c` feat(runtimes): add first-class agent runtime CLI adapter
- `23c8ca11` design(chrome): shimmer sweep on active workspace tab label
- `be784c13` feat(runtimes): add turn-dispatcher primitive (no callers yet)

## 2026-04-19

- `559a9c98` design(theme): unify midnight chrome glass + solid page surface on Settings/Analytics + inbox pill
- `b4785637` design(settings): RamsButton pill sweep + CornerBrackets selection + SectionLabel brightness
- `66eaa4b9` design(chrome): Rams palette, remove alerts tray, quiet timeline strip, tighten Session Replay
- `ef1268ba` feat(ui): reload banner in ThoughtsChatPanel [via-o8]
- `4d04dacc` feat(orchestrator): graceful reload endpoint with transcript resume [via-o8]
- `e861f1e5` feat(mcp-register): add o8.register_mcp tool for conversational MCP install [via-o8]
- `6a0b58b5` feat(mcp): adaptive probe timeout + npx prewarm [via-o8]
- `3f7a3734` feat(mcp): test connection button with live tools probe [via-o8]
- `82295a64` feat(mcp): paste-JSON config input [via-o8]
- `6c4606a3` design(settings): acronym casing — MCP + configuration [via-o8]
- `8cef91d6` design(settings): visual polish sweep — spacing, acronyms, typography [via-o8]
- `c3a722a1` design(analytics): Rams pass
- `5e91e677` design(settings): Rams pass on Settings shell + tab bar [via-o8]
- `83931920` design(settings): Rams pass on About tab [via-o8]
- `3209c5fa` design(settings): Rams pass on Diagnostics tab [via-o8]
- `7407acfa` design(settings): Rams pass on Appearance tab [via-o8]
- `ab05c4c3` design(settings): Rams pass on Cloud Workers tab [via-o8]
- `86984414` design(settings): Rams pass on Workers tab [via-o8]
- `facc19cb` design(settings): Rams pass on Dispatch tab [via-o8]
- `4e70379e` design(settings): Rams pass on MCP tab [via-o8]
- `910321dc` design(settings): Rams pass on configuration tab [via-o8]
- `b305eb09` design(settings): Rams pass on Connectors tab [via-o8]
- `2c6e1be2` design(settings): add TabBreadcrumb + TabHeading + FieldLabel Rams primitives [via-o8]
- `2565109c` feat(agent-hover): diff + last-tool + elapsed on hover [via-o8]
- `b852c1e7` feat(security): promote configuration encryption to macOS Keychain-backed master key
- `78f69c26` feat(delegate): accept baseBranch param for fix dispatches against feature branches [via-o8]
- `bfeb1ea6` feat(orchestrator): edge-case surfacer at dispatch-prep time [via-o8]
- `cb588908` feat(governance): autonomous post-merge decomposition pipeline [via-o8]
- `8e6f8a14` feat(chat): streaming DiffCard with partial-apply and interrupt [via-o8]
- `b37468c2` feat(runtime): cloud adapter scaffolding with outbound-only worker protocol [via-o8]
- `e82f2250` feat(orchestrator): render ComparisonCard + fan-out cost warning in mission panel [via-o8]
- `784bfee7` feat(orchestrator): guard PacketCard against comparison-group packets [via-o8]
- `58f9a244` feat(orchestrator): ComparisonCard mission-panel UI for best-of-n groups [via-o8]
- `60fc6e25` feat(orchestrator): comparison-meta API route for best-of-n meta-agent [via-o8]
- `59e578be` feat(orchestrator): add global AgentsSidebar for all-origin agent visibility
- `4e79747c` feat(orchestrator): external MCP servers as orchestrator context sources
- `0257de19` feat(agent runtime): eager-parse auth.json to expose authed providers as picker sub-rows
- `96c09660` feat(worktree): force managed mode for AI provider-code lanes so pre-launch rebase runs [via-o8]
- `6892fdb5` feat(orchestrator): wire packet issueUrl into PacketActionStrip open action [via-o8]
- `e401b1b3` feat(composer): wire stop pill to real interrupt channel [via-o8]
- `c1d8632e` feat(mcp-agent): o8_merge_preview tool + structured gate verdict on workflow action
- `d2ff2a4f` feat(orchestrator): packet card details popover [via-o8]
- `3ef5fe56` feat(mcp-agent): o8_packet_transcript MCP tool paginates packet agent runtime events [via-o8]
- `e39e9245` feat(orchestrator): Cmd+K quick-action palette in OrchestratorTab

## 2026-04-18

- `129d5775` feat(mcp-agent): o8_lane_events MCP tool long-polls workflow transition [via-o8]
- `9bd9bb2f` feat(mcp-agent): o8_review_state MCP tool
- `ae0128ca` feat(orchestrator): packet card action strip — retry / reset / open / copy [via-o8]
- `7e2e43b5` feat(orchestrator): history row actions — pin / rename / export / delete [via-o8]
- `f62fefb5` feat(orchestrator): synchronous worktree cleanup across all merge paths [via-o8]
- `201a9e71` feat(orchestrator): history sidebar search with first-message match [via-o8]
- `30477f11` feat(composer): Rams-style send pill with idle / armed / working states [via-o8]
- `132f8aab` feat(orchestrator): packet file-reference validator + emoji fix
- `6f5b3372` feat(dispatch): learned-rules promotion/demotion cron
- `43a64b0c` feat(orchestrator): inject learned rules into packet prompt
- `ea5aabed` feat(orchestrator): preserve pinned turns during auto-compact
- `a90a4b27` feat: archive orchestrator threads on clear
- `4b3f07a3` feat(orchestrator): finish remaining slash commands
- `bd4e7cb1` feat: usage.jsonl dispatch instrumentation for agent runtime + agent runtime runtimes [via-o8]
- `306b48f5` feat: wire Thoughts operator-defaults into panel [via-o8]
- `7705f45d` feat: default operator settings
- `a76283e0` design(agent-chat): unify agent runtime + agent runtime composer with orchestrator aesthetic
- `019c78f1` feat(orchestrator): context inspector side panel with click-to-evict
- `4febf47f` feat(worktree): stale local ref check + fetch_unreachable supervisor inbox kind so offline launches don't revert upstream [via-o8]
- `e9f30de5` feat(worktree): thread packetId through RuntimeLaunchRequest so rebase-conflict inbox rows deep-link to the packet [via-o8]
- `724c81bd` design(orchestrator): ThinkingChip matches ContextMeter pill aesthetic
- `b8dad79c` design(governance): move Supervisor Inbox from lingering /dashboard/inbox route into the O8 right panel as a proper tab
- `cc0f14e0` feat(agent runtime-debug): attach native review screenshots
- `08ab4c68` feat: add orchestrator composer token estimate
- `816c29e7` design: ThinkingChip uses theme tokens, drops Material shadow + backdrop-blur
- `5e5d78cd` feat: add orchestrator thinking footer chip
- `a6eb6640` feat(orchestrator): refine slash command controls
- `91cf88a2` feat: add supervisor escalation inbox
- `24eb3839` feat(governance): add heal-bot inbox worker
- `3922c796` design: slim orchestrator file mutation rows
- `a5d07539` feat: add adaptive orchestrator thinking summaries
- `b7753c32` feat(orchestrator): rotate thread after mission completion
- `eea81143` design(orchestrator): drop SESSIONS strip, compact packet tab labels, highlight latest dispatch
- `4b461625` design(orchestrator): CommandStripNode density pass

## 2026-04-17

- `f47b717d` feat(orchestrator): /clear /compact /focus /status /recall /handoff slash commands [via-o8]
- `7c95bd0c` feat: add orchestrator slash command controls
- `6b084ea7` feat(orchestrator): /clear command + fresh-thread-preserves-mission-state [via-o8]
- `179e14e7` feat: add orchestrator clear command
- `76316b21` feat(infra): wire prompt caching for AI provider 4.7 orchestrator [via-o8]
- `32220e18` feat: cache AI provider prompt prefixes in llm proxy
- `d4a92b29` design(agent-chat): share DesktopToolCallStack in MessageBubble [via-o8]
- `58d9674c` design(agent-chat): share DesktopToolCallStack in MessageBubble [via-o8]
- `4022f13c` feat: auto-compact orchestrator threads at 30 percent context
- `7a9cd813` design(orchestrator): move context down, copy up, shrink session cards [via-o8]
- `4566a63c` feat(orchestrator): token meter + ThreadsDropdown + header compression [via-o8]
- `b72264ac` design(orchestrator): unify expanded tool lines — read uses same format
- `6b51b6f4` design(orchestrator): invert batchable — only file writes/edits earn cards
- `d6c5d4ce` design(orchestrator): collapse tool calls into italic Rams-style line
- `6cb250b2` design(chrome): lift text + chrome-pill colors over vibrancy
- `956cbf68` design(approvals): ghost-orange buttons + clearer expand affordance
- `070132b0` design(approvals+orchestrator): tighten to Rams density
- `8fa84cbf` feat(approvals): first-class merge-gate banner under TitleBar
- `239c765f` feat(orchestrator): unified busy-state UI + stream event routing [via-o8]
- `a1d88504` feat(lane): tag merged lane tip commits with [via-o8] suffix
- `6f637586` feat(theme): shift light-mode glass family from white to paper base
- `be12215d` feat(theme): light-mode content surfaces use paper (#F4F2ED) — match o8-site

## 2026-04-16

- `e336cd03` feat(cloud): standalone worker CLI reference implementation
- `781f6870` feat(lane): route remote-customer merges through merge gate
- `1cf339c2` feat(settings): Workers tab UI + worker tokens API + feature-flag helper
- `dfd061f3` feat(dispatch): inject learned rules into packet prompt
- `57206196` feat(dispatch): learned-rules promotion/demotion cron
- `2d58081c` feat(cloud): CustomerWorkerTransport + register remote-customer adapter
- `7fdbd070` feat(cloud): worker poll + event endpoints with token auth
- `bd05bb2b` feat(db): worker_tokens + worker_runs + worker_events tables
- `f58ed2f5` feat(dispatch): dispatch_rules table + record from lane merge events
- `5517075d` feat(runtimes): scaffold remote runtime protocol types
- `f9bf7ef5` feat(sidebar): replace 'Idle' label with 3-word task summary
- `19b52557` feat(governance): autonomous decomposition pipeline

## 2026-04-15

- `7d08afa2` feat(supervisor): mechanical project rules rule enforcement at post-completion
- `ae92dcef` feat: add design mode overlay
- `c18aecf9` feat: branch picker wizard in packet dispatch
- `6f5fce13` feat(delegate): synthesize packet shell so governance tools find the lane
- `d6301dc8` feat: persist orchestrator plan text in chat history
- `c850fea3` feat: auto-capture lane review screenshots
- `5cacf223` feat: add external orchestrator mcp servers
- `4fd3a664` feat(orchestrator): Apple-style tool call cards + sticky working bar

## 2026-04-14

- `857df131` feat(orchestrator): export thread to markdown (closes)
- `1dba6aa9` feat(orchestrator): anti-patterns section + final-message format doctrine
- `10373985` feat(lane): reap idle abandoned lanes + safety guard main tree
- `c8d18e01` feat(history): archive tab in orchestrator history drawer
- `14badaf1` feat(workspace): merged read-only banner on retired chat tabs
- `1ae6852f` feat(lane): hide sidebar cards + packets bound to archived lanes
- `a9610331` feat(lane): auto-wrap manual runtime launches in a governance lane
- `6f83e71b` feat(mcp): add o8_view_wait_for for polling UI readiness
- `fcf31aa1` feat(lane): auto-archive stuck reviewing lanes + retire standalone native shell-mcp bridge
- `d772218c` feat(mcp): bundle o8_view_* webview tools + session picker + UI polish
- `2023d61d` feat: add timeline toggle to appearance settings
- `47867953` feat(theme): chrome-surface sweep + light blue accent + add-repo redesign

## 2026-04-13

- `4af65f91` feat(theme): chrome-surface scope for light mode glass buttons
- `9a5948d2` feat(theme): ship Light + Midnight only, light becomes glass chrome
- `3b1ee213` feat(mcp): ship native shell-plugin-mcp with the production build
- `31ea6297` feat(ship): local release script + ship npm scripts
- `fd1fe3c2` feat: Operator live fallback notice + Plan/Code permission chip
- `4d6394d6` feat: o8 Operator + drop legacy provider keys + agent runtime CLI runtime

## 2026-04-12

- `2f185245` feat: thinner fonts + desaturated diff in Changes panel
- `1f41c0f6` feat: unified user bubbles across all chats — subtle tinted pill
- `3d5cfe03` feat: thinner orchestrator chat text
- `9bbe71da` feat: roll Plus Jakarta Sans as the app-wide typeface
- `1d62ec13` feat: add Satoshi, Outfit, Manrope to typography specimen + match app sizes
- `58401eda` feat: add /text typography specimen page for font comparison
- `c392a174` feat: agent click scopes workspace panel to agent's worktree
- `a95d6d88` feat: aggregated Issues panel shows all repos grouped by sections
- `5e3d2c83` feat: repo alignment gesture — click repo name aligns whole app
- `38bc7c18` feat: multiple repos can be expanded simultaneously in sidebar
- `8adcc059` feat: fleet orchestrator UI — repo focus indicator + sidebar status
- `cc1eef1a` feat: orchestrator system prompt is fleet-aware across all repos
- `ee4054d4` feat: drag-to-reorder workspace tabs
- `ec5140ac` feat: session rows match orchestrator row layout
- `3eba2a8a` feat: rename CLI session tabs from 'Assistant' to 'Agent'
- `8d937cdb` feat: orchestrator tab is visually elevated and un-closeable
- `d5073897` feat: agent session tabs show repo + runtime instead of "Assistant"
- `f8c4889d` feat: apple squircle corners on right panel (O8 + workspace review)
- `0a98f238` feat: move permission + issues controls into composer toolbar

## 2026-04-11

- `c14077cb` feat: analytics apple pass + empty state respace + element picker iframe-proxy
- `e5948b7d` feat: midnight-aware terminal theme + navrail/titlebar consolidation
- `ef1ff62d` perf: gate headless sprint loop on queued packets
- `ec9d2328` perf: slim ws-server + lazy-spawn dashboard PTY
- `fefe98af` feat: orchestrator becomes a workspace tab with integrated history + mission

## 2026-04-10

- `df128de8` feat: mission dispatch echo + plan-mode banner in orchestrator tile
- `43c84672` feat: NavRail launchers for Mission Control + Orchestrator History
- `0ee546ef` feat: side-effect-class tool rendering + cross-tile orchestrator bus
- `89386ed9` feat: orchestrator/mission/history as tile-native components
- `98d7ef57` feat: thread permissionMode through sendToOrchestrator
- `31287253` feat: production hardening
- `aed9b509` feat: Node pre-flight + dynamic port allocation

## 2026-04-09

- `1d16f4ee` feat: AI provider Desktop auto-register + setupComplete schema fix
- `04e4c360` feat: MCP production hardening — auth, config distribution, bundling
- `e0e70743` feat: add shared token formatter
- `92ddffd7` feat: o8 v2 observability — Ledger + Preview tabs in Memory view

## 2026-04-08

- `c8c14ef9` feat: o8 v2 Phase 1 — directives store + session ledger + API
- `0bd6a4c4` feat: @-mention file suggestions on mobile chat compose
- `69be1685` feat: shared useFileDrop hook
- `6f94da5b` feat: enriched approval cards
- `79d7bc33` feat: pre-dispatch file overlap gate
- `48a878f7` feat: expandable detail rows in O8 Activity pane — click to expand inline context
- `ff56a196` feat: specialized mobile tool call cards — diff, shell, read, search

## 2026-04-07

- `f3ccb7a4` feat: mobile CLI chat backend
- `2a8f9a1a` feat: CLI chat backend
- `95f139ca` feat: o8 Assistant rebrand
- `0398f528` feat: add OpenRouter + xAI providers + key validation on save
- `a6b95fe8` feat: inline missions

## 2026-04-06

- `1425daa5` feat: commit viewer in O8 Changes tab — click commit to review inline
- `98f5fc5a` feat: click worktree to open agent transcript
- `c926c6f2` feat: collapse tool calls in transcript bubbles
- `18e0d587` feat: Activity tab in O8 Panel — unified activity feed
- `54797028` feat: compact activity badges on repo cards for ambient awareness
- `f5eebb22` feat: show conversation preview in chat tab labels instead of generic "Chat"
- `6e361fcc` feat: show agent runtime/AI provider brand logo in chat tab headers
- `15d20d74` feat: use official agent runtime + AI provider brand logos across all surfaces

## 2026-04-05

- `6bc9ebd9` feat: add runtime icons to session agent rows + collapsed branch badges
- `9b5c03ca` feat: replace CX/CC text badges with agent runtime and AI provider SVG logo icons
- `4e193f7a` perf: extract DashboardInner state into grouped context hooks
- `61c81451` perf: native shell IPC for SQLite endpoints
- `4ae7f87d` perf: virtualize transcript list for long agent sessions
- `a6282dd4` perf: lazy-load heavy Canvas tab components + o8TaskBoard
- `7a4da553` perf: deduplicate workspaces + inbox API calls on initial load
- `052980c2` perf: eliminate transcript render storm + 11 more polls → WS-driven + API dedup
- `5916e096` perf: native shell IPC commands for hot-path data reads — bypass HTTP stack
- `312262c9` perf: WS-driven invalidation for 18 polling loops + React.memo on 31 components (,)
- `babfed33` perf: replace 2 polling loops with useReactiveQuery
- `ce00a347` feat: TanStack Query + WS event bridge for reactive data layer
- `d9206f54` feat: MCP dispatch DX overhaul
- `b7ccc195` feat: truthful worktree status + cleanup stale worktrees
- `83743d32` feat: click worktree → open agent transcript in canvas ( v1)
- `1ad88484` feat: thinking indicator + faster polling for active agent sessions
- `2bd6c5ba` feat: port hover popover + open ports in O8 browser tab
- `23a33dbf` feat: open activity commits in O8 changes pane
- `376f426d` feat: instant PR cache invalidation after merge/approve/request changes
- `e8333127` feat: inline file diffs + merge conflict badge in O8 PR review
- `04a5a761` feat: PR count badge on repo card — click to open O8 PRs list
- `067dd2f1` feat: PR list view in O8 panel — all open PRs on one page
- `da722f7e` feat: PR review tab in O8 panel — replaces canvas PR viewer
- `0601aada` feat: collapsible root files section in O8 file tree
- `a7493851` feat: editable file viewer in O8 Files tab — competing product-style editing
- `08a5f973` feat: file browser in O8 panel Files tab — competing product-style split layout
- `88e94cd9` feat: dispatch pipeline hardening
- `779d9a4c` feat: wire Edit with AI + Open Source callbacks in O8 element panel
- `65d73b1f` feat: visual element selection panel for O8 Browser tab

## 2026-04-04

- `f454b6fa` feat: element picker bridge + source mapper API + rate limit fixes
- `5d6b8bd7` feat: O8 Browser tab — wire LocalhostPreviewTabs into O8 panel
- `d07fd20c` feat: O8 panel Changes tab — git status + inline diff + tab bar
- `e55df291` feat: O8 panel
- `cce11bbb` feat: mobile WS reconnect with exponential backoff + approval recovery
- `f656a6ed` feat: startup lane reconciliation
- `46a33161` feat: startup lane reconciliation
- `0b84a771` feat: GitHub intake pipeline — issue assignment to plan approval
- `65272faf` feat: persist runtime session costs to usage logs
- `b4022648` feat: o8 agent safety hooks
- `9dc48663` feat: mobile repo picker for multi-repo chat
- `f6777faa` feat: repo-scoped tool execution + repos API

## 2026-04-03

- `eaf7ae52` feat: apply file edits on approval approve
- `53c82c13` feat: add github tool for AI provider — gh CLI access
- `88140fad` feat: expand shell allowlist — npm, npx, node, cargo
- `8bcba207` feat: add create_file tool for AI provider
- `b673d369` feat: syntax-highlighted tool output — expand shows real code colors
- `421cab7e` feat: Apple-style collapsible tool call cards
- `bc512cb3` feat: AI provider tool execution backend
- `4f7fe6d4` feat: compact model selector + fix theme toggle in settings
- `e3c65623` feat: restore light mode with proper theme toggle
- `9e18da3a` feat: tool call card renderer components
- `9af39728` feat: tool call SSE protocol types and parser
- `e28fcf3b` feat: theme-aware markdown renderer + light mode code blocks
- `898d5551` feat: rebrand mobile shell for o8
- `dea51852` feat: rebuild mobile approvals and sidebar surfaces
- `8b4199fd` feat: rebuild mobile approvals and sidebar surfaces
- `fcd91ca5` feat: replace custom mobile chat with @assistant-ui/react Thread
- `9cce9754` feat: build mobile assistant-ui thread chat
- `d3f045f6` feat: mobile settings view + decompose monolithic client into focused modules
- `e89b6a65` feat: mobile redesign
- `289f3a09` feat: mobile settings view + decompose monolithic client into focused modules
- `0576fce9` feat: mobile settings view + decompose monolithic client into focused modules
- `af1a7152` feat: mobile settings view + decompose monolithic client into focused modules
- `3b7046b8` feat: mobile settings view + decompose monolithic client into focused modules
- `b44386f9` feat: mobile settings view + decompose monolithic client into focused modules
- `9ebbc383` feat: add mobile settings view to glass sidebar

## 2026-04-02

- `17f58ba7` feat: full glass input field + glass send button + scroll-to-bottom arrow
- `a4e0d289` feat: glassmorphic buttons
- `75aa5d29` feat: collapsible code blocks with diff coloring and file path labels
- `ec45fa7b` feat: TTS play button on assistant messages + AI provider-style input bar
- `c2327191` feat: starred + recents sections in sidebar, revert dots back to long-press
- `ca8ad50c` feat: long-press context menu on chat list — star, rename, delete
- `d63d2172` feat: AI provider-style chat list view
- `500dc19b` feat: AI provider-style message rendering + mobile markdown for code blocks
- `8763c403` feat: wire mobile chat to real chat history store + conversation list in sidebar
- `7a1aef00` feat: AI provider-style sliding sidebar + AI provider chat on mobile
- `3c40bb84` feat: add npm run tunnel for remote mobile access via Cloudflare
- `3b1c52ce` perf: prefetch mobile inbox on server
- `a6aed2a0` perf: break route barrel imports
- `ba662510` perf: switch dev to turbopack and lazy init db
- `14a417c0` feat: bound onAgentCompletion retry loop
- `7d82733a` feat: add attempt learning persistence
- `acb9bb3c` feat: add low-risk auto-approve policy
- `998b96e4` feat: add packet self-review confidence gate
- `56be609e` feat: objective exit criteria
- `471225d0` feat: compact Apple-style dropdown menu, no full-screen overlay
- `bc19c545` feat: AI provider-style tool cards in mobile chat
- `4228c8bb` feat: organize mobile sessions by type — Chats, Sessions, Missions
- `84f79425` feat: warm grey + light beige palette across all 30 mobile surfaces
- `5631e6c4` feat: slim compose bar
- `73ba8564` feat: in-process mutex on orchestrator-state.json
- `4b610bbf` feat: merge conflict escalation via approval card
- `16818234` feat: persist workflow watcher state to SQLite
- `dc3b6355` feat: orchestrator session health monitor — 90s timeout + auto-recovery
- `77a08e40` feat: persistent SQLite-backed review queue
- `32fa1ce8` feat: inline mission creation — no GitHub dependency
- `6481fce0` perf: mobile page is now client-only — zero server-side bootstrap
- `294efd58` perf: mobile optimization
- `79698cec` feat: copy AI provider mobile session list — clean rows, status groups, FAB
- `bf22b7de` feat: mobile new chat — launch LLM session from phone
- `7da466ac` feat: mobile wave 4
- `c7260974` feat: purge 4,277 lines of remodex CSS + remaining className from mobile

## 2026-04-01

- `d9e2df4d` feat: mobile waves 2+3
- `e5b78197` feat: mobile wave 1
- `276c93b8` perf: P1 bundle + network optimizations
- `a648a890` perf: P0 performance fixes
- `e161191d` feat: wire recommendMergeOrder() into merge pipeline
- `56443ba9` feat: merge gate file size block + operator override
- `a9961db6` feat: add FILE_SIZE_WAIVERS for layout orchestrators and multiplexers
- `e7dd4b3b` feat: skeleton map file size check at dispatch time
- `51227542` feat: InfinityGlow animated status indicator for agent cards
- `551e9952` feat: FTUX progressive feature reveal
- `43dd5381` feat: FTUX first-merge celebration state
- `366bd6fa` feat: FTUX mobile QR prompt
- `34f9348e` feat: FTUX First Mission Card contextual CTA
- `932ee1cb` feat: FTUX empty states for all dashboard panels
- `bd6c7c8a` feat: FTUX warm dashboard state
- `23b1bdb6` feat: FTUX personalized chat greeting
- `2bba0bfd` feat: workflow transition WebSocket channel
- `b79ae61f` feat: workflow transition WebSocket channel for real-time status streaming
- `0dd778db` feat: migrate approval store from JSON to SQLite
- `3b8deb9f` feat: migrate approval store from JSON to SQLite

## 2026-03-31

- `4f261749` feat: migrate lane registry from JSON to SQLite — kill cross-process clobber
- `fd0baca9` feat: sprint 6 wave 3
- `a18bc0af` perf: sprint 6 wave 2
- `e3321db6` feat: workflow watcher coordination
- `67d7083f` feat: route Audit Log to workspace tab instead of Inspector panel
- `0386c4b0` feat: sprint 5
- `72ddf139` feat: sprint 4
- `9fb9baa7` feat: sprint 3
- `26592858` feat: sprint 2
- `ff3a21c2` feat: structured multi-file diff in approval review gate
- `fe2a36d0` feat: workflow watcher triggers workflow transition
- `9eb53b0b` feat: agent runtime PreToolUse hook script for policy enforcement
- `df5857f5` feat: one-shot send-as-task from ThoughtsCard chat
- `f388970c` feat: server-side packet auto-dispatch loop
- `24173f2f` feat: integrate native shell-plugin-mcp for native app automation in dev builds
- `3e409e61` perf: JSONL tail-reads, cache-first actions, fingerprint optimization, sleep removal
- `947b47ac` perf: strip JSON pretty-printing from MCP server responses

## 2026-03-30

- `a58cd341` feat: native shell vibrancy polish, operator bridge fix, ghost session eviction, right panel cleanup
- `f008f584` feat: operator MCP bridge — agent runtime as o8 control surface
- `7644e08a` feat: workspace UI overhaul
- `125caca2` feat: UI polish pass

## 2026-03-29

- `52b9ba3b` feat: o8 brand mark — three-circle logo in accent blue
- `b1507b5a` feat: orchestrator loop — plan, delegate, review, approve
- `234f8c00` feat: governance engine
- `8b973087` feat: refine o8 product brief from 3-turn brainstormer session
- `75c90b23` feat: add REVIEW.md, agent delegation table in project rules, update agent descriptions
- `ca15b5ce` feat: add o8 product brief, update project rules with orchestrator model, create subagents
- `6c5d722f` feat: scrollable workspace lane tabs with transparent arrow overlays
- `cf6807ee` feat: tab scroll arrows, tool cards in Thoughts, right panel defaults to review
- `df8bff52` feat: workspace tab shows issue context + diagnostics settings tab (,)
- `4a090261` feat: one-click issue launch icon + lane-scoped review rail (,)

## 2026-03-28

- `6fc1e9c8` feat: add orchestrator MCP server, delegation tools, and agent supervisor
- `281a4906` feat: add GitHub issues to ThoughtsCard Mission Control

## 2026-03-27

- `463ff8de` feat: add translucent desktop dark mode shell
- `aac8e09d` feat: harden workspace shell and terminal sessions
- `5c765358` feat: add o8 board and restore system-wide timeline
- `578e411e` feat: move repo selection into workspace headers

## 2026-03-26

- `24b6ae1f` feat: fix branch-scoped review flow
- `c0eacdba` feat: turn workspace side panel into repo companion surface
- `6cf89a78` feat: route repo surfaces into workspace tabs

## 2026-03-25

- `ec9aee42` feat: tighten workflow lifecycle and operator recovery
- `0981e995` feat: refine desktop dark mode theme
- `39c7bb54` feat: migrate ide to fact-backed o8 recall
- `153b76ec` feat: enrich workspace cli chat parity
- `2f2b0fcf` feat: polish timeline and workspace chat surfaces
- `bf8d4e89` feat: scope agent surfaces to ide sessions
- `ca06e24b` feat: route workspace launches and github flows through broker

## 2026-03-24

- `eab62fb3` feat: ship github app broker foundation

## 2026-03-23

- `d655dabc` feat: Unified ContextualPanel — canvas tabs merged into bottom panel
- `a22ec01e` feat: Drop bundled Node (prerequisite) + bundle memory binary
- `5bb7f329` feat: WS server bundled in native shell app — terminals + chat work in production
- `36cade24` feat: GitHub App authentication — 5,450 req/hr, auto-refreshing tokens
- `1111c6e9` feat: GitHub PAT support + config lives in the user data dir/
- `c5085de2` feat: Bundle Node.js inside the app — zero-config for users
- `a9233f80` feat: Standalone server bundling for native shell — real distributable app
- `41f1f02f` feat: Inline edit
- `658912fb` feat: 'Environments' filter in files dropdown — quick access to .env files
- `0d8a7365` feat: Inline AI widget

## 2026-03-22

- `39ee35a4` feat: Tab autocomplete — AI ghost text suggestions while typing
- `20074d83` feat: Cmd+E inline AI edit
- `e813ed40` feat: Resizable files panel — drag handle between files and activity
- `67887fda` feat: Monaco Frost v2
- `c9938b4e` feat: Monaco 'o8 Frost' theme — icy light blue editor
- `6ecb9fc4` feat: Monaco Editor v3 — full IDE-grade file editing
- `96449e5f` feat: File editor v2
- `dca28235` feat: Inline file editor with Cmd+S save + files default to Changes view
- `048d3039` feat(branding): add o8 logo component + concept assets
- `610d71af` feat: In-app update banner + landing page + version sync
- `3866ea48` feat: native shell updater + GitHub Actions release workflow

## 2026-03-21

- `d98a2ae3` feat: add sidebar runtime capability layer
- `9eaeb618` feat: refine sidebar approval polish
- `50541b1d` feat: polish sidebar approvals and file actions
- `7f4399cd` feat: polish sidebar file actions
- `40d53b58` feat: add sidebar source actions
- `9002c69e` feat: unify sidebar active turn surface
- `51e28207` feat: show sidebar web source links
- `9e8e44c4` feat: enrich desktop sidebar source context
- `6347fa0f` feat: refine desktop sidebar runtime turns
- `0bbef267` feat: Conflict Resolution UI in Memory settings tab
- `7acca95f` feat: polish desktop sidebar runtime chat
- `05d04422` feat: add intent board v1
- `6e79944a` feat: unify desktop thoughts and sidebar chat rendering
- `c1af442d` feat: Codebase seeding engine — solve cold start for new users
- `78c8fc8c` feat: Unified chat send route + type fixes
- `3714eb17` perf: WebSocket RPC replaces CLI fallback — agents load in <500ms
- `b6f3b5da` feat: First Launch Setup Wizard — blue glass onboarding flow
- `7097222a` feat: Setup detection + config API for first-launch wizard
- `57c08ba1` feat: Graceful degradation when gateway unreachable
- `0ef0b44c` feat: Production polish
- `af7c99cb` feat: Blocklist guard for public changelog + project rules rule

## 2026-03-20

- `248dbb62` feat: context-aware recursive compaction — three-pass smart compression
- `3a510e6d` feat: project rules
- `3514bbf2` feat: Chat compaction
- `cf171d8b` feat: File system tools
- `698ce992` feat: Terminal command tool with three-tier safety + editable approval
- `2e69153a` feat: Chat-optimized recall — structured facts over raw chunks
- `84e34172` feat: Phase B
- `d5eea79d` feat: memory settings
- `18bead76` feat: memory settings tab — configure models, view stats
- `44cb6d5b` feat: memory recall — Phase A
- `fa565a22` feat: Steve Jobs polish — 5 UX refinements for LLM chat
- `740c2ef9` feat: Unified input container — model picker moves to bottom toolbar
- `4554694e` feat: GitHub tools for LLM chat
- `40a9b698` feat: Syntax highlighting, thinking text style, citation hover cards
- `f6e81b5e` feat: Chat history sidebar — search, star, open in new tab
- `8aa2868a` feat: Streaming code highlights, keyboard shortcuts, conversation forking
- `b0e064f1` feat: Inline citations, slash commands, Run in Terminal
- `09e2f7b9` feat: Code block actions — Apply to File + Open in Canvas
- `c1a749fe` feat: Smart follow-ups + beautiful empty state onboarding
- `6350e48d` feat: Phase 3 — Tool use with live indicators + sources
- `87387fa9` feat: Edge TTS voice playback with animated player
- `e8f6b5e0` feat: AI provider Desktop-style message action bar + proxy logging
- `3af4c3dd` feat: Chat persistence + mermaid error isolation
- `b6f2fcb3` feat: Full image support
- `9a2ef511` feat: Rich markdown renderer for LLM Chat
- `ebc58980` feat: LLM Chat Phase 1+2 — workspace context + @file attachment
- `654b36e2` feat: Add all latest AI provider models (3.1 Pro, 3 Pro, 3 Flash)
- `dba630fa` feat: configuration settings tab
- `a2571da2` feat: LLM Token Relay — provider proxy with metering
- `73cd1789` feat: LLM Chat v1 — standalone model access panel
- `829b2ac2` perf: GitHub API caching + worktrees auth fix across all routes
- `68b59ac3` perf: Kill scroll jitter — remove per-frame CSS recalculation
- `7b675e6c` feat: client abstraction — Local/Cloud/Hybrid
- `c844b850` feat: Tier 2+3 intelligence layer

## 2026-03-19

- `5701631b` feat: Repo switcher for Issues & PRs + deeper chat history
- `d25c4988` feat: Issues & PRs combined page + collapsible agents + deploy
- `52db245f` feat: Issues + Deploy Status + CI on mobile — monitoring & deciding
- `4ba2f2eb` feat: land realtime control plane and shell-first render path
- `26afd0c3` feat: Memory page
- `4ce4c01e` feat: Tap-to-reveal message actions + Telegram-style photo grids
- `d5f9fbaa` feat: Dark mode
- `f6fd5939` feat: Tier 1 UX
- `144a5f58` feat: Smooth crossfade animation between expanded header and compact pill
- `c27c9728` feat: Hide RuntimeBar when keyboard is up — clean compose
- `18e70561` feat: Auto-grow input + RuntimeBar at true bottom + frosted status bar
- `1ac71b60` feat: Compaction indicator on mobile chat — matches desktop ThoughtsCard
- `45175e53` feat: Header collapse-to-pill + repo/branch/diff in bottom footer
- `797df06f` feat: Costs page
- `e728c1da` feat: Settings + PR Reviews in Activity + panel status APIs
- `21413a25` feat: Notifications + PR Review from mobile
- `f7c7f5f4` feat: Activity Feed + Launch-to-chat + Fleet → Agents rename
- `e80ca9c7` feat: Launch Agent — fire agents from mobile
- `de47c496` feat: Fleet View — Apple-level agent dashboard for mobile
- `ec02c8a6` feat: Glass slash commands on mobile — frosted popover matching desktop
- `8c5b1e9c` feat: Speed Dial navigation — floating menu like Mister Copy Trade
- `aadb6232` feat: ThoughtsCard Apple pass

## 2026-03-18

- `bb31b56c` feat: Slash commands + glass attach popover in workspace chat
- `e3bfe466` feat: Chat V2 pass 2 — model/thinking, search, media button
- `7c85af66` feat: Chat V2
- `8478ec0a` feat: competing product-style compact agent cards + always-visible running agents
- `e6fb7355` feat: Add agent runtime + agent runtime to Open In dropdown
- `a6326d5f` feat: Open In button
- `a9ee6543` feat: Global Repo Context Bar — first-class repo selector above tabs
- `75064758` feat: Workspace Chat V1 — full chat tabs alongside terminals
- `511de9f8` feat: Dedicated Checks tab on PR viewer — competing product-style CI status
- `cbaafa8d` feat: Files tab — Changes filter dropdown
- `dba6c6fc` feat: Close remaining workspace gaps
- `7f3e7cd3` feat: Branch switching from panel — git checkout with dirty check
- `8742abff` feat: Running indicator on collapsed repo card
- `b1ee78c0` feat: Dev server launch from repo card — one-click Run/Stop
- `f26ed102` feat: Port preview pane — in-IDE iframe via proxy
- `5d1fba5c` feat: Agent ↔ Branch association — bidirectional linking
- `91d57d8c` feat: First-class ports in NavRail — auto-detect + grouped display
- `73caa0de` feat: Branch management — create, delete, cleanup
- `2181b75c` feat: Optional worktree launch + stale branch detection (,)
- `e431c0a1` feat: Expandable repo cards — branch list with worktree indicators
- `ad609f3d` feat: Colored file icons + repo-aware file tree
- `8a4eaa8e` feat: PR Review opens in canvas + remove Issues/PRs/CI tabs
- `629cc421` feat: Repo-scoped Activity
- `f69959eb` feat: Repo-aware Activity feed — selector, agent-scoped, PR merge banner
- `0c3133a7` feat: Activity feed
- `07046189` feat: Unified Activity Feed — Apple-grade timeline with GitHub data
- `9c726d5d` feat: Show all main agent surfaces + smart cron collapsing + fleet display setting
- `096f11ee` feat: Pin main agents + collapse cron sessions into single card per agent
- `935e9ead` feat: Stall detection for launched agents — 5min silence triggers warning

## 2026-03-17

- `fd5b95be` feat: Proxy localhost previews to strip frame-busting headers
- `dc767c4a` feat: Agent lifecycle
- `4ed8d0d5` feat: Live localhost preview
- `34dbbbce` feat: Live activity dots + elapsed time on terminal tabs
- `07783010` feat: Terminal tab persistence — tabs survive app restarts
- `796e1050` feat: Inline images rendered as HTML — bypass xterm IIP entirely
- `c77d971a` feat: Inline image rendering
- `0adbabb6` feat: Inline image rendering in terminal — Sixel + iTerm2 IIP support
- `c4c521b7` feat: Auto-register folders opened via picker — shows as Recent next time
- `c3b0f1f9` feat: Native folder picker
- `83d80632` feat: Open folder picker — launch CLI agents in any directory
- `457ff44c` feat: Two-step CLI picker with repo selection ( foundation)
- `c7f59308` feat: Terminal polish
- `a8ed6a3e` feat: Terminal-first workspace
- `18741a2b` feat: Live review file-change push via WS — repos + worktrees
- `90bd3250` feat: Mobile terminal surface — xterm.js on mobile + Terminal/Chat lane
- `128957d9` feat: Terminal infrastructure
- `71ad1442` feat: Launch modal UI
- `e24244b3` feat: Universal launch pipeline
- `f6c89fd3` feat: Repo registry polish
- `6a67da78` feat: Analytics page — cost dashboard with real data
- `7a17612f` feat: Agents section collapsible — same pattern as Activity
- `9df7f9b5` feat: Activity as collapsible dropdown above agent cards
- `5f3eef1a` feat: Issue assignment panel + ThoughtsCard z-index fix
- `6c049e46` feat: Active session pulse on timeline drill-down cards
- `1a6d4216` feat: Session cost tracking — real token usage + spend per session
- `b1018474` feat: Connected session panel with live SVG bezier connector
- `9bc30cef` feat: Timeline drill-down — double-click for per-agent breakdown
- `5c43c1d3` feat: Clickable PR diff on agent cards — opens PR viewer in Canvas
- `63963edc` feat: WS-driven AgentPanel + TitleBar status dot + full dedup (-6)
- `670bee13` perf: Wire WS for diff stats + remove redundant polls

## 2026-03-16

- `f2f84d67` feat: Wire WebSocket to desktop chat — real-time streaming
- `c81120e3` feat: agent runtime agents show their active repo's diff
- `43e2b39d` feat: Live Diffs for all 3 runtimes + UX fixes
- `e648662e` feat: Live Diffs — beautiful real-time code change viewer
- `5d3075c8` feat: Live Agent Output panel + agent card pulse
- `94c26159` feat: Real diff stats on main + real timeline activity bars
- `0fbccc8b` feat: Real context % for agent runtime sessions + diff stats
- `0622226b` feat: Wire real workspace data — PR status + diff stats on agent cards
- `54549618` feat: agent runtime sidebar chat
- `ce6ea21c` feat: agent runtime transcript — read session JSONL into sidebar
- `3fbfd2c6` feat: Smart naming on collapsed card dots too
- `893de1aa` feat: Better naming in agent cards
- `7e177ece` feat: agent runtime sidebar chat — send messages via CLI print mode
- `fef1a678` feat: agent runtime synthetic sessions for unmatched live processes
- `8a67d35e` feat: agent runtime sessions appear in fleet with live PID detection
- `b579ca74` feat: Status-grouped agent cards + Apple design polish
- `662ead41` feat: Full-size agent cards with everything visible
- `d6b4ac39` feat: Show heartbeat intervals on agent cards (read-only)
- `6634243c` feat: Agents tab in Settings — fleet dashboard with model editing
- `5572534e` feat: Merge WorkspacesPanel into AgentPanel — unified view
- `f857ea13` feat: WorkspacesPanel — status-grouped workspace cards
- `ae1aeef7` feat: Cmd+K keyboard shortcut to toggle Thoughts Card
- `231ecf00` feat: Context-aware suggestions in Thoughts Card
- `508b34b3` feat: Agent picker in Task chat — route to any agent
- `4d921c15` feat: Approval routing in Thoughts Card + test simulation
- `c5baa97f` feat: Task mode — mini chat inside Thoughts Card
- `2cef4fc3` feat: Thoughts Card — Issue vs Task modes + resize fix
- `ff5e6d1b` feat: Thoughts Card — resize handles + agent connection
- `818e1a6d` feat: Thoughts Card — floating glass command surface
- `00802a96` feat: Settings page with GitHub connection status
- `7b5a14ab` feat: Intent Canvas V0 — Fleet Command Center in workspace
- `6da96c2b` feat: SessionTimeline Phase 1 — hover scrubber + real data API
- `01ace93f` feat: Timeline Expanded View — full session replay in Canvas
- `bf8c66e6` feat: SessionTimeline V0 — agent activity replay bar
- `b9e4f6d3` feat: TitleBar window controls — sidebar/back/fwd/bottom/chat/settings
- `0146dedf` feat: TitleBar search is now live UniversalSearch + red settings gear
- `0c0e6313` feat: TitleBar
- `f5263e84` feat: Desktop NavRail
- `16a2b8ca` feat: Session Info Sheet
- `e54a7db8` feat: Universal search
- `df7367b3` feat: Proactive alert system — engine, context, bell, tray, toast
- `4419a11a` feat: REST API resilience

## 2026-03-15

- `b63f3eff` perf: gateway REST API client — 23ms vs 38s CLI cold-start
- `18c90fc2` feat: Heat map top-down view + fix fly-in stale closure
- `377f27c7` feat: Search dropdown with grouped clickable results
- `e4d52e59` feat: Knowledge Graph v3 — double-click fly-in + search fact nodes
- `418ef8f1` feat: Knowledge Graph v2.3 — zoom-aware labels + ambient fireflies
- `ffc54c54` feat: Knowledge Graph v2.2 — depth fog + all labels + text polish
- `b6b6dbc4` feat: Knowledge Graph v2.1 — bar gradients + floor reflections
- `8be40cd0` feat: Knowledge Graph v2
- `059b44f2` feat: Auto-refresh Knowledge Graph stats every 60s
- `2d45dca2` feat: Replace lava lamp with Interactive 3D Knowledge Graph Explorer
- `48c367e3` feat: Memory lava lamp v2
- `3f487938` feat: memory Lava Lamp — living particle visualization
- `3fbbf87d` feat: Image rendering in mobile chat + click-to-expand lightbox
- `4b0d8e0a` feat: Image rendering in chat + click-to-expand lightbox
- `638a8a7f` feat: Typing indicator — animated dots while agent is thinking
- `f47ed9f1` feat: Deployment Status (Vercel) + Git Log + Image Preview complete
- `2dc08c3d` feat: Git Log viewer + Image/Asset preview
- `ef3c82b4` feat: Issue Creator with AI enhancement (AI provider)
- `67a5f5b0` feat: Global workspace search + PR review comments with diff context
- `72e05c70` feat: CI tab in agent panel
- `7ef90f9c` feat: Changed file highlighting, clickable files, CI button
- `a1887636` feat: README viewer, CI/GitHub Actions, file diff preview
- `8dc375a4` feat: Stop button + project-scoped data + no auto-transcript popup
- `b3e9d0e0` feat: Project-scoped Issues, PRs, and Files — data follows workspace
- `5d9591dc` feat: PR Review tab + canvas viewer — full GitHub PR detail inline
- `3af091ab` feat: Commit detail viewer — click any commit in Activity tab
- `0b305939` feat: Agent panel groups by workspace — matches chat session picker
- `19b82c0b` feat: Show all agents including agent runtime/agent runtime in agent panel
- `352b261c` feat: Issue detail full-width + diff opens in canvas tab
- `ac13ffe7` feat: Drag-and-drop + paste + click-to-attach files in desktop chat
- `86d5fbac` feat: Vertical drag handle for canvas — resize workspace/canvas split
- `508f8525` feat: Contextual Canvas — bottom-half tabbed workspace
- `b4b2d9af` feat: Click agent surface → switches chat to that session
- `c1135d56` feat: Agent cards v2
- `653a1829` feat: Proper markdown rendering in issue modal
- `ab157be0` feat: Light theme + clickable issues with glass modal
- `e65be2d0` feat: Three-column layout — Agent Panel | Workspace | Chat
- `6ab46211` feat: Agent Command Center
- `e71d2edd` feat: Glass diff modal
- `e4690cb7` feat: Draggable compose bar — resize input height by dragging up
- `2c697aa0` feat: Glass modal for Mermaid diagrams — expand, zoom, pan
- `beedb8ac` feat: Mermaid diagrams on mobile — same o8 frost theme
- `8c1f6b55` feat: Styled CodeBlock + Mermaid diagram viewer
- `276067e0` feat: Transport controls — message actions morph during playback
- `0c91779a` feat: Point-to-Play
- `f0c24f64` feat: TTS Engine + Message Action Bar — Play/Copy/Retry on every message
- `1338f05e` feat: Desktop chat header — exact mobile TopBar clone
- `575541bd` feat: Desktop chat sidebar — mobile-identical chat on Dashboard v1
- `9560da73` feat: Dashboard v1
- `2b53d21f` feat: wire o8 v1.2.5 fixes — fact_ids, stale flags, real graph
- `a6bfb253` feat: grouped squad picker with expand/collapse
- `4b7698b2` feat: native shell v2 desktop shell
- `9af1036a` feat: squad picker dropdown on TopBar title tap
- `e31ca632` feat: wire memory surfaces into shell
- `6f2b969f` feat: memory Integration — all 8 issues (-)

## 2026-03-14

- `fff88386` feat: Phase 2
- `f41508ca` feat: worktree isolation Phase 1
- `c773f3d9` feat: universal runtime adapter contract + agent runtime integration
- `58091a6f` feat: code block rendering — fenced code + tool output cards
- `ae4290f3` feat: native markdown table rendering — beautiful HTML tables in chat view
- `af6455b7` feat: unified WebSocket — real-time push replaces SSE + polling
- `6078ff69` feat: PWA
- `ae4baf29` feat: virtual scrolling for transcript — DOM bloat eliminated
- `0143de0f` feat: consolidated sync API — 5 requests → 1
- `95b06c78` feat: prompt enhancement
- `cffa471b` feat: approval primitive
- `a28dbb33` feat: cost dashboard
- `9360ccbc` feat: wire json-render Renderer into mobile shell
- `ac850ea6` feat: json-render integration
- `04965e55` feat: agent runtime chat parity
- `4a282df2` feat: seamless agent runtime chat
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
- `53bde190` feat: squad cards
- `5efa10b5` perf: diff view
- `d6e646b9` perf: review-file 10s cache + only poll when diff open, tighter idle behavior
- `f27d88b6` perf: request dedup, 8s inbox cache, 5s transcript cache, round usedPercent, suppress hydration
- `d6f0f4ad` perf: adaptive polling (20s idle, pause on hidden tab, resume on focus), CSS containment, layout isolation
- `f9c82c32` perf: diff-and-patch transcript + snapshot — eliminate flash on idle polls
- `4384eb8f` perf: skeleton loading, lazy images, send click, API caching (3s transcript, 5s inbox)
- `8731f592` perf: smooth scroll, message fade-in, optimistic user messages, image caching, typing bubble animation
- `9887ba66` design: red send button + red typing dots — matches hamburger accent
- `c9cf14f4` design: solid red menu button, context pressure in bottom bar, doc tab apple redesign
- `1e30be56` design: full mobile UX pass
- `2715fee5` design: apple-grade controls sheet + sticky diff files survive compaction
- `b4ae629d` design: apple-grade diff polish

## 2026-03-12

- `00c14dbf` feat: surface queued agent runtime turns and clearer mobile send actions
- `f7f54ffc` feat: add quick thread switching for mobile agent runtime lane
- `b6324594` feat: make owned agent runtime mobile lane feel conversational
- `7bf408ef` feat: allow owned agent runtime interrupt on mobile
- `e480039e` feat: preload owned mobile diff context on focus
- `c740a25d` feat: extend owned agent runtime review and resume on mobile
- `b42b018d` feat: make owned review packets actionable
- `4a316a59` feat: add owned agent runtime review packets
- `6de73096` feat: surface owned agent runtime watch lane on mobile
- `e1a47bb2` feat: harden owned agent runtime lifecycle and tail views
- `dc221164` feat: add owned agent runtime launch and resume lane
- `6b7ffeea` feat: add runtime action ownership seam
- `fdc24f56` feat: promote runtime inventory and agent runtime activity detection
- `7217d071` feat: surface local agent runtime runtime discovery in desktop shell
- `b1650ee5` feat: harden mobile operator chrome and review cockpit
- `6a3cdd20` feat: add panel and terminal shells to mobile queue
- `ffd2e4a6` feat: add mobile per-file review drilldown
- `add6a8e7` feat: deepen mobile review lane and glass styling
- `8ca65c3d` feat: align desktop repo truth with live review state
- `2e94bb3c` feat: wire direct mobile actions and history

## 2026-03-11

- `bbe5dab3` feat: add mobile control inbox foundation
- `e63edc8d` feat: wire live agent runtime bridge and workflow review
- `868b012d` feat: add native desktop shell wrapper and guardrail surfaces
- `8a8b0775` feat: bootstrap command center shell and runtime contracts
