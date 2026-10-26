# PlainAcademy receipts

AI, made plain. We check the hype and teach what works, from zero to advanced.

This repository holds the evidence behind every PlainAcademy verdict. If you saw a verdict on Instagram, TikTok, Facebook or YouTube, its receipt is in `checks/`, named by date and topic.

Hosted by IRIS, our AI. Every script is checked and approved by a person.

## How we check

### Claims (Fact or Hype)
1. Find the original source: the paper, the announcement, the repository, the demo. Not a repost.
2. Check the date. AI changes fast; an answer from six months ago may no longer be true.
3. Look for what is missing: the setup, the cost, the failed attempts, the conditions of the test. Look for evidence that points the other way.
4. Note who gains if people believe it, and whether they say so.
5. Test it ourselves when it can be tested, and say exactly what we tested.

### Repositories (Repo Check)
1. Run it in an isolated sandbox, never on a personal computer.
2. Test the headline claim from the README, exactly as written.
3. Review the history: commits against stars, last update, licence, open issues.
4. Scan for security problems before and after running it.

### Claude skills and plugins (Skill Check)
1. Scan with NVIDIA SkillSpector (`skillspector scan <repo-or-folder> --no-llm`).
2. Read every serious finding by hand. A scanner score alone is never the verdict: some findings are false alarms, and we say which.
3. Note what the skill can read, write and send, in plain words.

## Verdicts

Every verdict is one of four ratings, with an evidence score and a date. A verdict is our assessment of a claim, based on the evidence in its receipt. It is not a statement about anyone's intent.

| Verdict | Meaning |
|---|---|
| Holds up | The claim is true as stated, under the conditions we tested |
| Partly true | Some of it holds, some of it is overstated or missing context |
| Hype | The evidence does not support the claim as stated |
| Unproven | We could not gather enough evidence either way |

**Evidence score:** five squares, filled by how much proof we gathered. The score is our judgement, and each receipt explains it. ■■■■□ (4 of 5) means strong evidence behind the verdict. ■□□□□ (1 of 5) means little evidence, so treat the verdict with care.

A verdict covers the version we tested, on the date shown. A clean Repo Check or Skill Check is not a guarantee of safety.

## Corrections

When we get a verdict wrong, we post a correction in the same format within 48 hours of confirming the error, add a correction note to the original caption where the platform allows it (or pin a comment where it does not), and log it in [CORRECTIONS.md](CORRECTIONS.md). We never delete a wrong verdict quietly. The history of this repository is public.

Think we got a verdict wrong, or are you the maker of a claim we checked? Send us the evidence by DM on Instagram or open an issue in this repository. A maker's response is added to the receipt, dated and unedited, unless it breaks the law or contains personal data.

## Money

Here, "paid" means any payment, free product, free credit or affiliate arrangement a company gives us.

- A tool must get "Holds up" in our own check before any paid relationship.
- Payment never changes a verdict. No company we have a paid relationship with sees a verdict before it is published.
- Paid content is always labelled and never uses the verdict format.
- Every paid relationship is listed in [PAID-RELATIONSHIPS.md](PAID-RELATIONSHIPS.md).

## Send us a claim

Seen a claim you want checked? Send a DM with the word CHECK to @plainacademy on Instagram. We choose which claims to check.
