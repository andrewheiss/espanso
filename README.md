# Espanso shortcuts

I've used TextExpander since 2008(!!) and have loved it. I use it for everything, like little shortcuts for typographic things like 

- `;comm` for ⌘, `;shift` for ⇧, `;opt` for ⌥
- `;times` for a true multiplication sign ×, `;minus` for a true subtraction sign −
- `;prime1` and `;prime2` for ′ and ″ (like 5′ 11″)

…and date things like:

- `;dt` for "2025-03-22"
- `;dz` for "2025-03-22T12:09"
- `;date` for "March 22, 2025"

…and longer words with repeated letters that I always mess up, like these:

- `insttn` for "institution"
- `consttal` for "constitutional"
- `entrepal` for "entrepreneurial"

…and code snippets like `;dplyrsum` for inserting this R code to disable {dplyr}'s grouping messages:

```r
options(dplyr.summarise.inform = FALSE)
```

…and longer pre-written templates for emails and code.

It's a delightful piece of software and I type and navigate far slower on computers without it. It's $40/year, and I've happily paid for it for years, but I've always been on the lookout for an open source alternative.

And I found one: [**Espanso**](https://espanso.org/)! It can do everything TextExpander can, and more (like multiple triggers for the same shortcut, one trigger for multiple shortcuts, regular expression-based triggers, etc.)

Espanso is [configured with YAML](https://espanso.org/docs/matches/basics/), so I exported all my shortcut groups from TextExpander, reworked/reformatted them to YAML entries with VS Code, and now everything is working perfectly for free.

Because I'm a huge believer in sharing everything, I've included all my match settings (triggers, replacements, forms, etc.) in this repository in the [`match` directory](/match/). Each YAML file there corresponds to one of my old TextExpander groups.
