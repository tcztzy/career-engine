# NVIDIA

## basic
- name: NVIDIA
- type: company - role-level (Software Test Development Engineer, JR1994195 / job 893380869460)
- source: official NVIDIA careers page and Workday posting
- current status: applied / pursue cautiously

## note on scope
- This repo keeps only public-safe company research.
- Private application, referral, interview, or self-evaluation notes should stay outside this repo.

## current hypothesis
- This is a more practical NVIDIA application than the previous US-based AI Agent Runtime role because it is listed for China Remote and asks for 3+ years rather than L5/L6 12+ years.
- It is also a less exact technical match. The role is test development for NVIDIA networking and interconnect products, not AI agent runtime or LLM infrastructure.
- The user's strongest fit is software-side test automation, Linux/Python/C++ debugging, distributed-system validation, cloud/local infrastructure, and root-cause analysis. The weaker fit is hardware validation, electrical test equipment, embedded firmware, and production test deployment.

## what I want to know
- whether the team primarily needs software automation or hands-on hardware/electrical validation
- how much daily work is Python/C++ test tooling versus lab equipment, board bring-up, firmware, or production-site support
- whether "networking and interconnect products" means InfiniBand/Ethernet/NIC/Switch validation, GPU interconnect validation, or broader hardware release testing
- whether China Remote is real remote work or remote from a China office/team with frequent site/lab dependency
- whether the role has growth path into infrastructure/test platform engineering or stays as product validation/support

## signals
- evidence:
  - Official title: "Software Test Development Engineer."
  - Workday identifier: JR1994195. NVIDIA careers job URL uses job id 893380869460.
  - Official Workday page marks the posting as available and lists the hiring organization as CN05 NVIDIA Shanghai WFOE.
  - Date posted: March 10, 2025. The older NVIDIA careers schema shows `validThrough` September 6, 2025, but the current Workday page still exposes `postingAvailable: true`; this should be treated as a live-but-old posting until the application system says otherwise.
  - Location: China, Remote.
  - The role works on NVIDIA networking and interconnect products.
  - Responsibilities include test plans, automated/manual testing for hardware releases, test automation/tools, HW/SW failure debug, root-cause isolation, technical processes, production-site deployment/support, and training personnel on complex test systems.
  - Required profile: CS/EE/CE or equivalent technical degree, 3+ years experience, programming in Python/Java/C#/C++, problem solving, independent project work, English communication.
  - Standout signals include validating large-scale distributed systems, electrical test equipment, microcontrollers/DSP/embedded firmware, C/C++/C#/Linux, and verification-code experience.
- interpretation:
  - This role screens for test engineering judgment more than AI infrastructure depth.
  - The user's profile can match the software/test side: Python, C/C++, Linux, xcc validation, yallm integration tests, cloud/local infrastructure, Microsoft support/root-cause work, and GPU/HPC operational debugging.
  - The user's current AI-infra resume is too agent/LLM-runtime-forward for this role. A targeted version should lead with "test automation / infrastructure validation / Linux debugging" rather than "AI Agent Runtime."
  - This may be easier to enter than the US NemoClaw role, but the day-to-day work may be farther from the user's long-term AI infrastructure direction.
- uncertainty:
  - whether the application system is genuinely accepting this old posting
  - whether hardware lab experience is a hard requirement or just a standout signal
  - how much of the work is production test support versus reusable test platform/tooling
  - whether the team values AI/HPC/cloud experience or mostly wants networking hardware validation experience

## comparison with previous NVIDIA target
- Previous target: Senior Software Engineer, AI Agent Runtime and Open Source Infrastructure, NemoClaw/OpenShell.
- Stronger fit technically: previous role.
- Stronger fit logistically: this role, because it is China Remote and lower seniority.
- Risk in previous role: US location, L5/L6 seniority, visa/relocation, TypeScript/Node/open-source runtime expectations.
- Risk in this role: hardware validation domain mismatch and possible drift away from AI infra / agent runtime work.

## likely fit read
- stronger fit if the team needs:
  - Python/C++/Linux automation
  - test harnesses and verification code
  - distributed-system validation
  - root-cause debugging across software and infrastructure
  - cloud/local server test environments
- weaker fit if the team needs:
  - oscilloscope/spectrum-analyzer-heavy lab work
  - embedded firmware and microcontroller bring-up
  - production-line test deployment as the main job
  - deep networking hardware validation experience from day one

## resume positioning
- Lead with: Test automation, infrastructure validation, Linux/Python/C++ debugging, hybrid local/cloud servers, GPU/HPC operations, verification code.
- Keep visible: Microsoft Azure production support, iFlytek big-data platform, xcc test coverage / clang validation, yallm compatibility/integration tests, local+cloud AI infrastructure.
- Move lower: AI agent runtime branding, biology, research identity.
- Avoid: making the CV read as pure LLM/agent research; this role is hardware-release test development.

## interview angles to test
- Ask what percentage of the role is software automation versus hardware lab validation.
- Ask which products the team validates: NICs, switches, InfiniBand/Ethernet, GPU interconnect, or broader platforms.
- Ask what test framework/language stack is used today and what is painful about it.
- Ask for a recent HW/SW failure example and how the team isolated root cause.
- Ask how often the China Remote engineer needs access to physical equipment or production sites.
- Ask whether there is room to build reusable test infrastructure or whether the role is mostly release execution.

## decision
- current recommendation: apply, but do not treat this as the highest-fit NVIDIA role
- reason: it is more realistic geographically and seniority-wise, and the software automation side is defensible; the hardware validation side is the main mismatch
- what would change my mind:
  - if the team says the role is mostly Python/C++/Linux test tooling for distributed/networked systems
  - if lab equipment and embedded firmware are nice-to-have rather than day-one requirements
  - if the role has a path into test infrastructure/platform engineering
- what would make me pause:
  - if the work is mostly manual hardware release testing or production-site support
  - if physical lab presence is frequent despite "China Remote"
  - if they expect deep oscilloscope/signal-integrity/embedded experience as a hard requirement
- next step:
  - use a test-development-focused resume variant, not the AI-agent-runtime resume unchanged
  - prepare examples around xcc verification, yallm compatibility tests, Azure support root-cause diagnosis, and hybrid local/cloud GPU infrastructure operations

## sources
- https://jobs.nvidia.com/careers/job/893380869460
- https://nvidia.wd5.myworkdayjobs.com/en-US/NVIDIAExternalCareerSite/job/Software-Test-Development-Engineer_JR1994195
