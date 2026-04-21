# vineyard

## the idea

### one-liner

ai-powered online markdown editor for non-technical people

### story

lots of ai-usage problems have been largely "solved" by developers

but these features are "gatekeeped" by needing developer pre-requisite knowledge

need something as easy to pickup as using Gemini, but also having enough for power users

also, dev tooling is centered on handling local files synced via git, but non-technical users would likely appreciate things on the web and being able to easily continue on different devices

vineyard = "grow" and "tend" to your markdown writings

### user stories
- book writers
- academics
- researchers
- note takers

it has to be a great web markdown editor out-of-the-box first, ai is supposed to be only for enhancing the flow

### features

#### essential
- cursor-like IDE experience but very stripped down for just markdown
- basic markdown syntax highlighting, no need for markdown previewing (yet)
- "git" support: basic version control is super important
    - auto-save would be important, but auto-save should also not "pollute" the "commit history"
- filetree
- ai chat panel (no inline / tab completions)

#### future
- choose models...?
    - thinking to first support gemini flash only for the pricing and familiarity as im targetting gemini users...?
    - should probably support open source models for the cost...? (again, see opencode go)
    - maybe also... gpt mini? (see copilot)
    - also allow free models available in OpenRouter...?
- pay-as-you-go pricing...?
    - after $10 and want to continue to use better models... pay-as-you-go?
- basic vim support
- export files
- import files
- quality of life features
    - @files in chat
    - reorganize panels
    - settings and personalization (colors, fonts) => frictionless experience on bring ideas from the brain to words

#### future-future
- bring your own API key...?
- collaborative editing aka multiplayer google docs style

### business model
- flat $10 per month pricing, with rate limits (see opencode go)
- be super honest on the profit margin, and that the rate limits are calculated via provider pricing, and will adjust over time

## the implementation
- is there an existing web editor i can just "use out-of-the-box" for potential future vim support?
- whats a good way to "save" markdown files? drag-and-drop support needed too
- use openrouter so can use different models...?

