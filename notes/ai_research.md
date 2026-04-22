---
layout: default
title: AI in Research -- Notes
---

# Ethics, GS 580
## AI in Research

## Readings

### AI and the scientific record
- Low-quality papers are surging by exploiting public data sets and AI (Science)
- AI-enabled image fraud (2022)
- ChatGPT fools scientists (2023)

### Policy and publishing
- Nature ChatGPT Editorial (2023)
- Lancet Digital Health, LLM Ethics in Medical Publishing (2023)

## Topics to Discuss

### Authorship and accountability
- All major publishers now say LLMs cannot be authors. Which of the ICMJE criteria do they fail, and does that settle the question?
- If an LLM drafts substantial portions of a paper, who is accountable for errors, for fabricated citations, for plagiarism?
- What should journal disclosure policies look like for LLM use in writing, analysis, and figure generation?
- When does LLM assistance shift from "tool" (like a spell checker) to "contribution" (like a coauthor)?

### Writing, reviewing, and editing
- Is it acceptable to use an LLM to polish a manuscript? To write the first draft? To respond to reviewers?
- Is it acceptable for a reviewer to use an LLM to help write a review? To summarize the paper? To generate critiques?
- What do you do if you suspect a review you received was LLM-generated?
- What do you do if you suspect a paper you are reviewing was substantially LLM-generated and contains fabricated citations?

### Fabrication at scale
- "Paper mills" using LLMs can produce plausible-looking papers in minutes. How should journals defend against this, and who pays the cost?
- AI-generated images are increasingly hard to distinguish from real microscopy and western blots. What detection and deterrence strategies are realistic?
- Is the appropriate response to raise the quality bar, to require raw data deposition, to restrict who can submit, or something else?

### AI in analysis
- Where is the line between using AI as an analysis tool and using it as an oracle whose output you do not understand?
- What does reproducibility mean for an analysis that depends on a closed-weights model that may be deprecated next year?
- What should methods sections say about model version, prompts, random seeds, and any human post-editing?
- Should peer reviewers be expected to audit the AI components of a paper's analysis? What would that look like?

### Training data and consent
- Commercial LLMs are trained on scientific literature, often without explicit permission. Does that matter, and if so, whose concern is it?
- If a model memorized a copyrighted figure and reproduces it in an output, who is responsible?
- What are the confidentiality concerns when researchers paste unpublished manuscripts, grants, or clinical notes into commercial LLMs?

### Equity and access
- Do AI writing tools advantage non-native English writers, disadvantage them, or both?
- Are we moving toward a system where researchers without access to top-tier AI tools are systematically disadvantaged in publication and grants?
- What is the equitable response at the institution, journal, and funder level?

## Case Scenarios

### Scenario 1: The fabricated citation
A reviewer is checking references on a manuscript and finds that three cited papers do not exist: the DOIs resolve, but to entirely unrelated articles, and the "authors" named in the reference have never collaborated. The writing style suggests extensive LLM involvement. The authors, when queried, say they used a chatbot to "help organize" the references.

- What does the reviewer recommend: reject, request revision, refer to the editor, report to the institution?
- What is the authors' responsibility for citations they did not personally verify?
- Does this meet the definition of research misconduct? Who decides?
- How should the journal respond going forward, and what tooling would actually help?

### Scenario 2: The AI-drafted grant
A senior postdoc drafts an R01 proposal with substantial LLM assistance and does not mention it to the PI. The PI reviews and edits the proposal, submits it, and it is funded. Three years later a reviewer of the renewal notes that the first proposal's Aim 2 background section contained claims about prior work that are subtly but materially wrong.

- Was the first submission dishonest? At what point, and by whom?
- What is the PI's responsibility for verifying a trainee's writing, AI-assisted or not?
- What is the NIH's interest here, and what would you report to whom?
- How should the lab update its practice for the renewal?

### Scenario 3: The LLM review
You submit a paper. The review comes back technically accurate in its summary but oddly generic in its critiques, with suggestions that apply to almost any paper in the field. You suspect the reviewer used an LLM. You have no way to prove it.

- Do you raise the concern with the editor? What would you ask them to do?
- Is it your place to care how the review was produced, if the content is reasonable?
- What if the review is wrong on a technical point in a way that suggests the reviewer did not actually read the paper?
- What policies should journals have for reviewers' use of AI, and how could they be enforced?

### Scenario 4: The synthetic figure
A graduate student generates a "representative" microscopy image using a generative model, to illustrate a phenotype that was observed in actual experiments but is hard to capture cleanly. The figure is labeled as illustrative in the legend. The PI is uneasy but the student argues the actual data in the quantification panels are real.

- Is the illustrative-figure practice acceptable with disclosure, or not at all?
- Where is the line between a schematic (clearly a drawing), a "representative image," and a synthetic image?
- How should the journal respond if this practice were disclosed at submission?
- What broader norms should the field establish before synthetic imagery becomes undetectable?
