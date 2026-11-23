---
trigger: always_on
---

# Instructions to the agent

- The intended product goal is defined in the ".agents/rules/REQUIREMENTS.md" file.
- The product must be designed according to the functional and non-functional requirements provided in the ".agents/rules/REQUIREMENTS.md" file.
- Create a ".agents/rules/TECH_STACK.md" file featuring the set of tools required to satisfy the provided requirements, alongside the cost and the justification to use each of them.
- Create a ".agents/logs/" subdirectory and feed it with logs indexed by the associated requirement number reporting successful, failed and pending actions.
- Never edit the ".agents/rules/REQUIREMENTS.md" file. If you have suggestions on it, just share it with me and then let me decide whether to adopt it or not.
- Never add, remove or edit any content in the ".agents/" directory, except ".agents/rules/TECH_STACK.md" file and ".agents/logs/" subdirectory.
- Always you implement a new feature, let me know what requirement it is about, then I will be able to evaluate it and mark it as done.
- Regardless of programming language, any block of code must be properly commented for maintenance and audit purposes.
- By default, the product must be available in English language, unless other languages are explicitly requested.
- Create a "README.md" file where you will describe the project and the steps required to execute and maintain it.
- Always a new feature is implemented or changed, you must update the "README.md" file.
