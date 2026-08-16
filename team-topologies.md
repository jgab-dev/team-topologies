---
title: Team Topologies — Key Points
subtitle: Organizing Business and Technology for Fast Flow of Value
authors: Matthew Skelton & Manuel Pais
edition: 2nd Edition (IT Revolution, 2025)
---

### 
# Team Topologies
## Organizing Business and Technology for Fast Flow of Value
Matthew Skelton & Manuel Pais — 2nd Edition, 2025
Key ideas, distilled to 25 slides

---

### THE PROBLEM
# Org charts don't ship software. Team boundaries do.
- Most delivery bottlenecks are organizational, not technical
- Conway's Law: system design mirrors communication structure
- Ad hoc team design creates a hidden coordination tax
- The fix isn't a better process — it's a better team topology

---

### THE CORE IDEA
# The team is the smallest unit of delivery
- Stop optimizing individuals; optimize the team
- Teams should be long-lived, not project-shaped
- Give teams clear boundaries and real ownership
- "Team-first" thinking replaces "org chart" thinking

---

### 2ND EDITION — REFRAMED
# From efficient machines to flourishing ecosystems
- 1st edition (2019) optimized primarily for throughput and flow efficiency
- 2nd edition (2025) foregrounds purpose, people, and adaptability
- Clear intent and purpose are now treated as prerequisites for speed
- Cognitive load moves from "a consideration" to a foundational design principle

---

### DESIGN CONSTRAINT #1
# Team cognitive load is the limiting resource
- Every team has a finite capacity to hold context
- Assign a team more than it can hold, and delivery slows, quality drops
- Team size and scope must be set deliberately, not by default
- Ask of every team: "what can this team actually own well?"

---

### DESIGN CONSTRAINT #1, CONTINUED
# Three kinds of load, only one worth spending
<!-- diagram: cognitive-load -->
#### Intrinsic
Load inherent to the task itself — irreducible domain complexity.
#### Extraneous
Load from poor tooling, unclear docs, noisy environments — reduce this.
#### Germane
Load spent on the problem that actually matters — protect this.

---

### THE VOCABULARY
# Four team types cover almost every org
<!-- diagram: four-teams -->
#### Stream-aligned
Owns a flow of work end-to-end.
#### Enabling
Helps other teams close a capability gap.
#### Complicated-subsystem
Owns a piece of deep technical specialism.
#### Platform grouping
Provides self-service capability to stream-aligned teams.

---

### TEAM TYPE 1 OF 4
# Stream-aligned team
- The default, primary team type — most teams should be this
- Aligned to a single valuable stream of work: a product, service, or user journey
- Empowered to build, test, and release without heavy handoffs
- Success metric: can it ship a change without waiting on another team?

---

### TEAM TYPE 2 OF 4
# Enabling team
- Specialists who help stream-aligned teams gain a missing capability
- Engages temporarily — weeks to a quarter, not permanently
- Goal is to leave the stream-aligned team more capable, not to do the work for them
- Watch for enabling teams that quietly become a permanent dependency

---

### TEAM TYPE 3 OF 4
# Complicated-subsystem team
- Owns a subsystem that genuinely requires specialist knowledge — a codec, a pricing engine, a model core
- Reduces cognitive load on stream-aligned teams by hiding deep complexity
- Used sparingly — most "complicated" code isn't actually complicated enough to justify one
- Exposed to other teams as a service, not as shared code to modify

---

### TEAM TYPE 4 OF 4 — RENAMED IN 2ND EDITION
# Platform grouping
- Provides internal services that stream-aligned teams consume to reduce their load
- 2nd edition renames "platform team" to "platform grouping"
- Reflects reality: most real platforms are built by several teams, not one
- A good platform is a compelling internal product, with its own UX and support bar

---

### A SHARED CONCEPT
# Every team has an API, whether it names one or not
<!-- diagram: team-api -->
- Team API = everything another team experiences when interacting with yours
- Code and interfaces, but also docs, wikis, on-call practice, response times, roadmap visibility
- Designing it deliberately reduces friction and cognitive load for everyone else
- Bad team APIs are the real source of most "communication problems"

---

### THE UNDERLYING FORCE
# Conway's Law: architecture mirrors communication
<!-- diagram: conway -->
- "Organizations design systems that mirror their own communication structure" — Mel Conway, 1967
- Team boundaries become software boundaries whether you plan it or not
- Fighting it with process alone is a losing battle
- Better approach: design the org you want, and let the architecture follow

---

### THE UNDERLYING FORCE, CONTINUED
# The inverse Conway maneuver
<!-- diagram: inverse-conway -->
- Deliberately shape team structure to produce the architecture you want
- Want loosely-coupled services? Start with loosely-coupled teams
- Team boundaries become a design tool, not an HR afterthought
- Org design and software architecture should be decided together, not sequentially

---

### HOW TEAMS MEET
# Three modes govern every team-to-team interaction
<!-- diagram: three-modes -->
#### Collaboration
Work closely together, shared responsibility, for a bounded time.
#### X-as-a-Service
Consume or provide with minimal collaboration, through a clear interface.
#### Facilitating
One team helps another get unstuck, with no shared delivery ownership.

---

### INTERACTION MODE 1 OF 3
# Collaboration
- Two teams work side by side toward a shared outcome
- High bandwidth, high discovery — good for genuinely novel problems
- Also high cognitive load — use it deliberately, not by default
- Time-box it: collaboration should resolve into X-as-a-Service once the interface is clear

---

### INTERACTION MODE 2 OF 3
# X-as-a-Service
- One team consumes what another provides through a well-defined interface
- Low collaboration overhead, clear ownership, minimal cognitive load
- Requires a genuinely usable interface — API, docs, self-service tooling
- The steady state most platform and complicated-subsystem interactions should reach

---

### INTERACTION MODE 3 OF 3
# Facilitating
- A team, often an enabling team, helps another learn, unblock, or adopt a practice
- Deliberately temporary — success means the facilitating team is no longer needed
- No shared delivery responsibility — facilitators don't own the outcome
- Common failure: facilitation that never ends becomes a silent dependency

---

### HOW TO SPLIT WORK
# Fracture planes: where to cut, deliberately
<!-- diagram: fracture-planes -->
- A fracture plane is a natural seam along which a system and its teams can split
- Common planes: business domain, regulatory boundary, change cadence, risk, geography, tech stack
- Split along a plane that reduces cross-team coupling, not one that's merely convenient
- A bad split recreates the coordination tax you were trying to remove

---

### THIS ISN'T A ONE-TIME DESIGN
# Organizational sensing
- Team topologies are a starting hypothesis, not a permanent structure
- Watch for signals: rising lead time, repeated hand-offs, a team that can't explain its own scope
- Sensing is a continuous, lightweight practice — not a yearly reorg
- Treat team structure the way you treat architecture: refactor it as you learn

---

### TOPOLOGIES CHANGE OVER TIME
# Team structures should evolve, not calcify
- As a product or platform matures, the right topology for it changes
- Merge teams once an interface stabilizes; split teams once cognitive load grows
- Reteaming is disruptive — do it deliberately, on a cadence people can plan around
- Keep two maps: the current reality, and where you intend to move next

---

### WHAT TO AVOID
# Patterns that quietly recreate the old problems
- Enabling teams that never leave and become a permanent bottleneck
- Platform teams built without product or UX discipline — "internal, but still painful"
- Collaboration mode used everywhere by default, spiking everyone's cognitive load
- Reorgs driven by hierarchy and headcount instead of by flow of value

---

### WHAT'S NEW IN THE 2025 EDITION
# Five years of real-world evidence
- Ten new case studies spanning pharma, law, HR, healthcare, and more — beyond the original tech-sector focus
- New foreword and afterword reflecting on the model's global adoption since 2019
- "Platform grouping" replaces "platform team," based on real-world road-testing
- The core four team types and three interaction modes are unchanged — the model held up

---

### TAKE THIS BACK TO YOUR ORG
# If you remember five things
- Optimize for fast flow of value, not for org-chart neatness
- Stream-aligned teams should be the default; the other three exist to serve them
- Protect team cognitive load like you'd protect a production system's capacity
- Choose the interaction mode deliberately, and let it change over time
- Team structure is a live design decision, not a one-time chart

---

### GO DEEPER
# Team Topologies, 2nd Edition
- Matthew Skelton & Manuel Pais — IT Revolution Press, 2025
- teamtopologies.com — assessments, case studies, community resources
- This deck is an orientation summary — read the book for the full model and case studies
- Diagrams in this deck are original illustrations created for this summary, not reproductions of the book's artwork — see teamtopologies.com/use-of-team-topologies-materials
