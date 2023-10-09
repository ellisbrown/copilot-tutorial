# VSCode, Copilot, Jupyter, Git, Mamba
### NYU[x] Research Tooling Meeting

Ellis Brown

10/09/2023
## 0. Why this matters?
---
## 1. VSCode
---

## 2. Jupyter
---
## 3. GitHub Copilot
---
Oct 2021 beta — changed the way I approach coding



### 3.1 Code As "Context"
ChatGPT as a lens to understand Copilot
- context = prompt + history (in ChatGPT parlance)
- the better the context, the better the suggestions

***Copilot Context:*** code + comments
1. in ***current file***
    - especially current/previous line
    - "Fill-In-the-Middle" paradigm
        - code before & after the cursor
2. from ***neighboring tabs***
    - Copilot attends significantly more to code if it is open in a tab
3. from ***other files in the repo***, (but much less likely to be added to the context)
    - other files in the repo are scanned too, but much less likely to be added to the context
    

https://github.blog/2023-05-17-how-github-copilot-is-getting-better-at-understanding-your-code/


### 3.4 Copilot Best Practices

https://github.blog/2023-06-20-how-to-write-better-prompts-for-github-copilot/#3-best-practices-for-prompt-crafting-with-github-copilot

#### 1. block comments to set the stage / give it a high-level goal
- top of file
- above a section

#### 2. inline comments to prompt for specific output
- articulate the logic / steps for it to follow
    - often will be able to auto-complete!
- start writing code to get more specific suggestions
## 4. Mamba — drop-in replacement for Conda rewritten in C++ ⚡⚡
---
## 5. Git
---

- `.gitignore`
    - toptal: top google result for "gitignore generator"
    - https://www.toptal.com/developers/gitignore?templates=linux,macos,python,jupyternotebooks,data
- 
