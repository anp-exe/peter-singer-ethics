# Singer's Practical Ethics: A Companion

An interactive companion to my notes on the first five chapters of Peter Singer's *Practical Ethics*. Positions are Singer's unless marked as my own commentary.

**Live page:** https://anp-exe.github.io/peter-singer-ethics/

## What it covers

| Chapter                      | Focus                                                                                                                                    |
|------------------------------|------------------------------------------------------------------------------------------------------------------------------------------|
| 01 What ethics is            | Why ethics is not a list of prohibitions, divine command and Plato's reply, universalizability.                                          |
| 02 Equality                  | Equality as a moral principle not a fact, equal consideration of interests, sex differences and the opportunity gap, affirmative action. |
| 03 Animals                   | Bentham's "can they suffer?", speciesism, the line between sentience and rights.                                                         |
| 04 What's wrong with killing | Person vs human, Locke and Fletcher's indicators, the case of Baby Andrew.                                                               |
| 05 Taking life               | Animal self-consciousness, replaceability, total vs prior-existence views.                                                               |

Each chapter has a live interactive demo (the morphine case, a build-a-person meter, scenario toggles) and a "My take" note where I push back on Singer in my own words.

## Structure

```
.
├─ peter-singer-ethics.html
└─ assets/
   ├─ chimp.jpg            chapter 3, animals
   └─ ethics-scales.jpg    chapter 1, what is ethics
```

## Run locally

Single static HTML file, no build step:

```bash
python3 -m http.server 8000
# then open http://localhost:8000
```

Both images live in the `assets/` folder, so keep that folder next to the HTML or the images will not load.

## Source

Peter Singer, *Practical Ethics* (chapters 1 to 5). All quotations are kept short; the page summarises and responds rather than reproducing the text.
