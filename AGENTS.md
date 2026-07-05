# Agents guide

## Project overview
This is a project to maintain my CV and cover letter in a structured format using LaTeX. The project includes multiple versions of the CV (frontend, fullstack) and a cover letter, all formatted using the Awesome-CV LaTeX class.

## Core working rules
- Follow unquestioningly the "only facts, no inventions" rule. Do not add any information that is not present in the source files or provided by the user. If you are unsure about a fact, ask for clarification instead of making assumptions.
- Ensure the project successfully compiles to PDF without errors by running `make` or the appropriate LaTeX build command.
- Maintain a clean and organized directory structure, separating content, documents, and other files.
- If you write text, ensure it is grammatically correct and free of spelling errors, ATS-friendly, and formatted according to the Awesome-CV style.
- When editing content files, ensure that changes are consistent across all relevant versions (e.g., frontend and fullstack CVs) unless a specific version requires unique content (frontend and fullstack CVs may have different experiences or skills highlighted).
- When mentioning specific technologies, frameworks, or tools, ensure that they are accurately represented and relevant to the context of the CV or cover letter. Ensure that naming is consistent across all documents (e.g., "Web3Modal" vs. "Reown AppKit"). Use standard, searchable terminology and correct capitalization, for example React, Next.js, Node.js, CI/CD, Playwright, GitHub Actions, Reown AppKit.
- Prefer concrete nouns and verbs; avoid generic phrases like worked on, responsible for, various; quantify only when verified; keep one main idea per bullet; optimize for recruiter skim.
- Change discipline: prefer editing content .tex files over awesome-cv.cls; touch the class only for layout/systemic issues.
- Reporting: in the final response, list changed files, which PDF was rebuilt, whether warnings remain, and any assumptions made.