# Didi (滴滴)

## basic
- name: Didi Chuxing / 滴滴出行
- type: company — team-level (Autonomous Driving — Simulation Platform)
- source: official job board (internal referral via share link)
- current status: applied

## note on scope
- This repo keeps only public-safe company research.
- Private interview/process/self-evaluation notes are kept in a personal knowledge base outside this repo and are intentionally not shown here.

## current hypothesis
- Didi's autonomous-driving simulation team is hiring a senior backend engineer to build a distributed cloud computing platform for large-scale offline simulation workloads.
- The JD reads like a genuinely technical platform role: multi-tenant scheduling, lightweight application framework, heterogeneous computing (CPU/GPU), and inference caching for autonomous-driving DNN models.
- This is not a generic backend CRUD role. The team seems serious about building compute infrastructure for simulation-at-scale.

## what I want to know
- whether this simulation platform team is its own org or embedded inside a larger infra team
- what the team's current stack looks like: K8s? Ray? custom scheduler?
- whether GPU inference caching is a new initiative or an existing system needing improvement
- what the team culture is like — autonomous-driving groups in China tend to operate differently from consumer-facing Didi
- whether this role is expected to be deep in one layer (scheduler, framework, caching) or spread across all

## signals
- evidence:
  - JD explicitly lists: distributed cloud computing, multi-tenant scheduling, application framework, heterogeneous compute, GPU inference caching, DNN offline simulation.
  - "Must have: Python, 1+ year high-performance backend, computer fundamentals (OS, compilers, architecture, networking)."
  - "Nice to have: large-scale distributed systems / PaaS, C++, DNN inference optimization, large-model deployment, GPU architecture/CUDA, autonomous-driving/robotics."
  - Didi Autonomous Driving was founded in 2016, one of the earliest L4 AD companies in China.
  - Simulation platform is described as providing "large-scale cloud simulation computing services" for AD R&D.
  - The team operates in an internal-referral context — the user was connected via someone inside Didi.
- interpretation:
  - The role is genuinely infrastructure-facing, not application CRUD. The JD reads like a serious platform engineering description.
  - The compiler requirement ("computer fundamentals: compilers") is concrete enough that xcc (C11 compiler) is a legitimate signal.
  - Multi-tenant scheduling + heterogeneous compute + inference caching are all specific technical areas with their own challenges.
  - The "large model deployment / DNN optimization / GPU architecture" nice-to-haves mean candidates with production LLM deployment experience (DeepSeek-R1 671B on 8×A100) are plausible fits.
  - Internal-referral sourcing suggests the team is expanding and trusts employee referrals over pure cold applications.
- uncertainty:
  - unclear whether the working language is Chinese-only or mixed with English documentation
  - unclear whether the simulation platform team works directly with AD perception/planning teams or is more isolated
  - Didi as a company has a mixed reputation for engineering culture — the autonomous-driving unit may differ from the main ride-hailing org
  - how much autonomy individual engineers have in architecture decisions is unknown

## company model read
- Didi's core business remains ride-hailing (China, LATAM, Africa, emerging markets).
- Autonomous Driving is a long-term strategic bet, not yet revenue-generating, but Didi has a unique advantage: massive real-world driving data.
- The simulation team's job is to make AD development cheaper and faster by running offline simulation at scale.

## workplace read
- mixed signal overall:
  - Didi is a mature company with established engineering practices — not a startup gamble
  - but China's autonomous-driving scene is competitive (Baidu, Pony.ai, WeRide, Momenta), and teams under pressure may have longer hours
  - internal referral is a positive signal about team growth and hiring standards
  - unclear how Didi's recent business restructuring (ride-haling margin pressure, overseas expansion complexity) affects AD investment

## likely fit read
- stronger fit if: the user wants real platform infrastructure work (distributed systems, scheduling, heterogeneous compute, GPU caching) in a driving-application context where the problems are concrete
- weaker fit if: the user wants a pure autonomous-driving algorithms role, a Western-style remote/async workplace, or a startup-like environment

## interview angles to test
- Ask how the simulation platform team is structured: is there a separate scheduler team, framework team, caching team, or does one backend team own it all?
- Ask what the current inference caching solution looks like — is it a Redis-like cache, a dedicated GPU-sharing layer, or something custom?
- Ask how the team handles multi-tenancy: is it namespace-based, quota-based, or a custom hierarchical scheduler?
- Ask what the pain point is: too many simulation tasks, not enough GPU, or poor resource utilization?
- Ask about the team's relationship with the AD perception/planning teams — do they act as internal platform/SRE or as infrastructure product owners?
- Ask what went wrong before that the team is now trying to fix.

## decision
- current recommendation: proceed — the JD genuinely aligns with the profile (distributed systems, PaaS, compiler, GPU inference, Rust/Python/C++), and the team seems to be growing
- what would change my mind:
  - signals that the team is a run-of-the-mill backend team disguised as platform engineering
  - evidence that GPU/compiler/infra depth would not be valued in practice
  - workplace culture red flags from first-hand conversations
- next step:
  - submit application (already done via internal referral share link)
  - prepare for conversation rounds
  - keep this file as public-safe research; keep private notes outside this repo

## sources
- https://talent.didiglobal.com/neitui/jobDetail?shareCode=f8cc9734bcf84a038becbb2364f1134f&jdId=63407
