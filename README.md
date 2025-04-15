# 👋 Hi, I'm currently building somthing interesting.

## WYSIWYG editor [REPO](https://github.com/tiptiz/editor) (WIPING)
I will coming back to this repo soon.
| light mode | dark mode|
| -- | -- |
| ![image](https://github.com/user-attachments/assets/30200f47-016c-48dc-8dd0-f0bad68af702) |  ![image](https://github.com/user-attachments/assets/c6eaa144-d530-4615-97e8-23df24aa818c)|

## AI Code Reviewer [REPO](https://github.com/aolyang/cloudflare-deepseek-code-reviewer) (Archived)
used cloudflare workder AI/KV and Github WebHooks (commit events). Deploy doc and dev doc are completed.  
Get into [REPO](https://github.com/aolyang/cloudflare-deepseek-code-reviewer) to see details.  
**This repo is archived because I'm currently focusing on building an AI assistant to run locally.**
| unauthorized |	authorized | update prompts | Api DOC | example |
| -- | -- | -- | -- | -- |
|![image](https://github.com/user-attachments/assets/422e5111-a650-4564-ac75-433b1c5d4268) | ![image](https://github.com/user-attachments/assets/cdf07efd-8d7a-45e7-b6b4-fedc2ea41e59) | ![image](https://github.com/user-attachments/assets/d1cb08ee-93ab-46da-9816-303b426b7d0f) | ![image](https://github.com/user-attachments/assets/0cdd1a09-2a55-41b9-9dd7-fc931fa47fd4) | ![image](https://github.com/user-attachments/assets/ab3049c0-aef8-4498-80ae-453431877196) |

## Basketball game [REPO](https://github.com/aolyang/basketball-game)

A game demo help with [Trae](https://www.trae.ai/) & AI.  
Complete dev logs with AI in [FeiShu](https://g98etdwz8h.feishu.cn/docx/A672d7vf6oeAIfx926scZsSSnWg)

| main page | game page (with debug helper) |
| -- | -- |
| ![image](https://github.com/user-attachments/assets/88e531b7-6c88-4722-a09a-b7a7b543e72f) | ![image](https://github.com/user-attachments/assets/3e9ddac3-4627-4788-b762-428104a2a2df)|

## My personal ESLint Config package [REPO](https://github.com/aolyang/eslint-config)

```javascript
// eslint.config.mjs for react project
import globals from "globals"

import { combine, combineGlobals, ignores } from "@aolyang/eslint-config"
import react from "@aolyang/eslint-config/react"
import stylistic from "@aolyang/eslint-config/stylistic"

export default combine(
    combineGlobals(
        globals.browser,
        globals.node
    ),
    react(),
    stylistic(),
    { ignores }
)
```
