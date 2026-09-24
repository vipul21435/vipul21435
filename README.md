## Vipul Raj Jha

Software engineer. I write production code for LLM training and evaluation programmes, build the pipelines and tooling around them, and lead the squads that ship it.

CS from IIIT Delhi, 2025. Based in Delhi.

### Things I have built

**[research-harvest](https://github.com/vipul21435/Web-Scraping-Tools-for-Research-Paper)** pulls papers from PubMed and OpenAlex over their REST APIs, merges the duplicates on DOI then source id then normalised title, and reads the methods, cohort sizes and headline metrics straight out of the abstracts. The extraction is the hard part: an abstract is written for a human, so anything clever enough to catch every phrasing also catches a p-value and calls it a cohort. Python, 115 tests, 95% coverage, and the suite runs offline against recorded API fixtures.

**[SilverPass](https://github.com/vipul21435/SilverPass)** is passport services for people over 70. Express API and React client, full English and Hindi, a status machine that refuses illegal transitions, and two interchangeable storage backends held to one contract test so neither can drift. 135 tests, and CI runs the server suite twice, once per backend.

**[CourseBot360](https://github.com/vipul21435/CourseBot360-main)** answers questions about university courses. The interesting bit is the split: the intent engine never touches the DOM, so the whole conversation runs in a test in milliseconds, and answers come back as data rather than HTML. 108 tests. [Live](https://vipul21435.github.io/CourseBot360-main/).

**[Cab Booking System](https://github.com/vipul21435/CabBooking-PHP)** is fleet and booking management in PHP and MySQL. It started from a template carrying a hardcoded admin backdoor, MD5 passwords and 60 injectable queries. Fixing that meant binding every query, moving to bcrypt with an in-place migration for the old hashes so nobody got locked out, and adding CI that proves it by booting the stack and signing in.

### Work

**Handshake**, since July 2026. Building LLM training and evaluation systems.

**Scale AI**, July 2025 to July 2026. Most of my time went into the coding programmes: writing and reviewing production-grade C++, Python and JavaScript against per-task quality bars, at volume. Every submission I made was accepted. 100%.

I also led a squad. I scoped the task sets, wrote the evaluation rubrics and technical assessments, built the review workflow, and ran delivery. Over 11,000 hours shipped at a 3.9/5 average quality rating. I was lead reviewer on more than half the projects I got put on, at 4.3/5 across 51 internal quality reviews.

On the tooling side: Python validation pipelines for data quality and model output monitoring, RLHF and SFT feedback loops, fine-tuning with LoRA and PEFT, and RAG pipelines for context-aware evaluation.

**Zinnia Digital Services**, 2025. QA automation in Python and Selenium for insurance client applications, plus two phases of their CI/CD pipeline. Regression runs got about 65% faster and we cut roughly three hours of manual estimation out of every release.

**IIIT Delhi labs**, 2023 to 2024. AI-assisted design evaluation tooling in Java across 150+ structured evaluations, which turned into a co-authored paper. Separately, a Blender-inspired 3D modelling application in Unity and C# with 3-axis manipulation, validated through user testing.

### Stack

Python, C++, JavaScript, Java, SQL, PHP, C#. PyTorch, Hugging Face, scikit-learn. LoRA and PEFT, RAG, embeddings and vector search. Node, React, Express, MySQL, MongoDB, Docker, GitHub Actions, Selenium. pytest, vitest, node:test.

### Other

Codeforces Specialist, 1485. World rank 979 in Round 994 out of 35,000-odd. Over 1000 DSA problems. Dean's List 2023-24.

[LinkedIn](https://www.linkedin.com/in/vipul-raj-jha-491b2023a/) | [vipul21435@iiitd.ac.in](mailto:vipul21435@iiitd.ac.in) | [Codeforces](https://codeforces.com/profile/Vipul21435)
