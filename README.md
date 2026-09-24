## Vipul Raj Jha

Software engineer. I build evaluation environments and tooling for coding agents: containers that build and verify reproducibly, tasks hard enough to defeat frontier models, and the pipelines that gate all of it.

CS from IIIT Delhi, 2025. Based in Delhi.

### Work

**Handshake**, since July 2026.

I build hard, verifiable tasks for coding-agent evaluation. Each one ships self-contained: a digest-pinned Dockerfile that builds the environment for both the agent and the verifier, a reference solution that solves the problem by genuine computation, and a test suite that grades real output instead of matching strings. Everything goes in as a pull request and iterates against automated review gates until every check is green.

The design problem is the interesting part. A task is only hard if the naive reading of the data looks correct and is wrong, the deciding cases are hidden from the sample but fully determined by it, and the result is still gradeable byte-exact. That has meant generating synthetic corpora and then proving they admit exactly one consistent interpretation, and recovering hidden structure with integer linear algebra and modular arithmetic.

I also build reproducible environments for arbitrary open-source repositories at a specific historical commit: pinning dependencies until a suite that failed before the fix passes after it, then wrapping it in tooling. Per-repository build recipes, collision detection against a shared ledger, build locks, dedupe caches.

Every submission I have made across these programmes has been accepted. 100%.

**Scale AI**, July 2025 to July 2026.

Squad lead on an LLM coding-data programme. I scoped the task sets, wrote the evaluation rubrics and the technical assessments, built the review workflow, and ran delivery. Over 11,000 hours shipped at a 3.9/5 average quality rating.

Lead reviewer on more than half the projects I got put on, including multi-model coding and reasoning evaluation, at 4.3/5 across 51 internal quality reviews. Alongside that, Python validation pipelines for data quality and model output monitoring, RLHF and SFT feedback loops, and fine-tuning with LoRA and PEFT.

**Zinnia Digital Services**, 2025. QA automation in Python and Selenium for insurance client applications, plus two phases of their CI/CD pipeline. Regression runs got about 65% faster and we cut roughly three hours of manual estimation out of every release.

**IIIT Delhi labs**, 2023 to 2024. AI-assisted design evaluation tooling in Java across 150+ structured evaluations, which turned into a co-authored paper. Separately a Blender-inspired 3D modelling application in Unity and C#, with 3-axis manipulation, validated through user testing.

### Things I have built

**[research-harvest](https://github.com/vipul21435/Web-Scraping-Tools-for-Research-Paper)** pulls papers from PubMed and OpenAlex over their REST APIs, merges duplicates on DOI then source id then normalised title, and reads the methods, cohort sizes and headline metrics out of the abstracts. The extraction is the hard part: an abstract is written for a human, so anything clever enough to catch every phrasing also catches a p-value and calls it a cohort. Python, 115 tests, 95% coverage, and the suite runs offline against recorded API fixtures.

**[SilverPass](https://github.com/vipul21435/SilverPass)** is passport services for people over 70. Express API and React client, full English and Hindi, a status machine that refuses illegal transitions, and two interchangeable storage backends held to one contract test so neither can drift. 135 tests, and CI runs the server suite twice, once per backend.

**[CourseBot360](https://github.com/vipul21435/CourseBot360-main)** answers questions about university courses. The intent engine never touches the DOM, so the whole conversation runs in a test in milliseconds and answers come back as data rather than HTML. 108 tests. [Live](https://vipul21435.github.io/CourseBot360-main/).

**[Cab Booking System](https://github.com/vipul21435/CabBooking-PHP)** is fleet and booking management in PHP and MySQL. It started from a template carrying a hardcoded admin backdoor, MD5 passwords and 60 injectable queries. Fixing it meant binding every query, moving to bcrypt with an in-place migration so nobody got locked out, and CI that proves it by booting the stack and signing in.

### Stack

Python, C++, JavaScript, Java, SQL, PHP, C#, Bash. Docker, GitHub Actions, pytest, vitest, node:test. PyTorch, Hugging Face, LoRA and PEFT, RAG, embeddings and vector search. Node, React, Express, MySQL, MongoDB, Selenium.

### Other

Codeforces Specialist, 1485. World rank 979 in Round 994 out of 35,000-odd. Over 1000 DSA problems. Dean's List 2023-24.

[LinkedIn](https://www.linkedin.com/in/vipul-raj-jha-491b2023a/) | [vipul21435@iiitd.ac.in](mailto:vipul21435@iiitd.ac.in) | [Codeforces](https://codeforces.com/profile/Vipul21435)
