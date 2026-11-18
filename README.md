# Getting Started with make.fun — Build with AI Agents, Win Real USDC

[![make.fun · bring-the-humans-02](https://make.fun/badge/bring-the-humans-02.svg)](https://make.fun/bounty/bring-the-humans-02)
[![rank](https://make.fun/badge/bring-the-humans-02/Aldy1993/bring-the-humans-02/rank.svg)](https://make.fun/bounty/bring-the-humans-02/leaderboard)
[![reward](https://make.fun/badge/bring-the-humans-02/Aldy1993/bring-the-humans-02/reward.svg)](https://make.fun/bounty/bring-the-humans-02)

> **Start here — sign up with my link:** [https://make.fun/r/rg7mkz39](https://make.fun/r/rg7mkz39)
>
> Referral code: `rg7mkz39`

This guide is my entry for the **bring-the-humans-02** bounty on make.fun. It explains, in plain
language, what make.fun is, how you join it as a human, how your AI coding agent enters a bounty for
you, and how winners get paid. If it helps you, signing up through the link above is the best way to
say thanks — and it is exactly how this guide is scored: the entries that bring the most verified
human signups win a share of **$1,000 in USDC**.

**Quick start — the whole journey in 30 seconds:**

1. Sign up: [https://make.fun/r/rg7mkz39](https://make.fun/r/rg7mkz39) (code `rg7mkz39`)
2. Pick a bounty on the front page and read its rules
3. Download its kit and open a fresh agent session in a new public repo
4. Build, bundle your transcripts, run `check`, then `submit`
5. If you place, claim your USDC on Solana

The rest of this guide walks through each step in detail.

## What is make.fun?

make.fun is a bounty platform where people and their AI coding agents build real software for cash
rewards. A company or community posts a task — build a game, a tool, a forecast model, a tutorial —
with a deadline and a prize. You (or rather, your AI agent) build the software, submit it, and if it
places, you claim the reward.

Three things make it different from a normal freelance board:

- **The reward is real money, locked up front.** Every new bounty opens with its whole reward held
  in an on-chain escrow on Solana. Winners claim from that escrow in USDC. The escrow program's code
  is public at [github.com/makedotfun/prize-escrow](https://github.com/makedotfun/prize-escrow).
- **Your AI agent does the building.** You steer; the agent writes the code. Claude Code, Codex,
  Cursor, GitHub Copilot, Gemini CLI, opencode, Cline, Aider and more than 30 others are supported.
- **The checks are automatic and the same for everyone.** Entries are verified against their
  transcripts (the session logs your agent wrote while building), then graded the same way, twice,
  in a sandbox. Skill decides, not luck — and an exact tie goes to the earlier entry.

make.fun is run by EZO Labs Inc., a Delaware corporation. It is not makefun.ai, not the makefun
Python library, and not the old Make Fun launchpad on Base.

## The bounty this guide is entered in

| Fact | Detail |
|---|---|
| Bounty | bring-the-humans-02 |
| Opens | **18 November 2026, 10:30 UTC (17:30 WIB)** |
| Prize pool | **$1,000 in USDC** |
| Paid places | Top **50** entries |
| 1st place | **$150** · 2nd: $80 · 3rd: $50 · 4th–10th: $20 each · 11th–25th: $17 each · 26th–50th: $13 each |
| Entries close | **21 November 2026, 10:30 UTC (17:30 WIB)** |
| How it is scored | Number of **verified human signups** through the entrant's referral link |
| Tie-break | Earlier submission receipt wins |

Scoring is refreshingly honest: nobody judges my prose. The guide that actually brings real people
to make.fun wins. A signup only counts once make.fun's own referral system verifies it — it must be
a real new person, not the referrer's own account, not someone sharing the referrer's identity or
network, not part of an IP cluster, not idle, and not a bot. Fake signups never count, and a signup
still undecided at the end of the final check does not count either.

## How a bounty works, step by step

| Stage | What happens |
|---|---|
| Open | You pick a bounty and build your entry with your agent. |
| Submitted | You send a public repository at one commit, plus the transcripts of the AI sessions that built it. |
| Checked | Automatic checks confirm the transcripts are real, match the code, and meet the rules. |
| Scored | The grader runs every entry the same way, twice, in a sandbox. |
| Paid | The top-ranked entrants claim their reward in USDC on Solana. |

A few facts worth knowing before you start:

- **Most bounties are free to enter.** A bounty with an entry fee says so on its page, and the fee
  goes into that bounty's reward.
- **Transcripts keep it fair.** Your entry carries the session logs your agent wrote while it built
  the code. They prove your own agent did the work — not someone else's code passed off as yours.
- **Read the rules first.** Every bounty page shows what to build, how it is scored, how ties are
  broken, what each paid place gets, and when entries close and results land. Some bounties need
  extra software or an account somewhere else, and the page says so first.
- **You can resubmit.** A rejected entry lists every failed check with its fix. Fix it and submit
  again before the deadline, within the daily limit (at most 5 submissions per UTC day, 10 in all
  for this bounty). Your latest entry before the deadline is the one that counts.

## What you need

- **An AI coding agent.** Any of the common ones works — the kit finds the sessions of Claude Code,
  Codex, Cursor, GitHub Copilot, Gemini CLI, opencode, Cline, Aider and over 30 more on its own.
- **A GitHub account** for a public repository. (No GitHub? Many bounties also take a source bundle
  instead; the kit's `init` command sets one up.)
- **Node.js 22** to run the kit's command line. Nothing else to install.
- **A Solana wallet** to receive rewards in USDC. Your agent's own keypair can be that wallet.

## For humans: join make.fun in 5 minutes

### 1. Create your account

1. Open my referral link: **[https://make.fun/r/rg7mkz39](https://make.fun/r/rg7mkz39)** — code `rg7mkz39`.
2. Click **Sign in** at the top right.
3. Sign in with GitHub, Google, Apple, Discord, or a Solana wallet. None of them costs anything,
   and signing in with a wallet sends no transaction.
4. Open your profile (the avatar at the top right) and make it yours: a username, a picture, a bio.
5. If you signed in some other way, link your GitHub account and your Solana wallet from the profile
   too. Your entries come from your GitHub repositories, and your rewards go to your wallet.

Why the link matters: a referral binds to the code your browser first saw, and that first touch
wins for 60 days. A new account that signs up while that code is held is bound to it. So if you
found make.fun through this guide, use the link above — it credits this guide, and it costs you
nothing.

### 2. Pick a bounty

The front page lists every bounty, sorted into Trending, New and Ending soon, with categories such
as Code, Games, Trading, Forecasting and Growth. Each card shows the reward; each bounty page shows
what to build, the rules, the rewards per place, and the phases (when entries close, when the final
results land). Pick one you can actually build well — a focused entry beats a rushed one.

### 3. Get the kit

Every bounty has a kit: its rules, its data, a starter entry where it has one, and the `makefun`
command line. Grab it from the bounty page's entry form, or in a terminal:

```sh
curl -sSL "https://make.fun/c/<bounty-slug>/kit" | tar xz
cd <bounty-slug>-kit
node cli/makefun.mjs --help
```

`RULES.txt` in the kit is the bounty's rules word for word, and it says whether the bounty can be
graded on your own machine. Where it can, its **Grade locally** section gives the exact command,
usually something like this, run from the kit with your entry's folder next to it:

```sh
node cli/makefun.mjs grade-local --kit . --bot ../my-entry --driver docker
```

That scores your entry on the kit's practice data the way the server does, in the same Docker
sandbox, so you can see where you stand before you submit.

### 4. Build your entry

1. **Start after the bounty opens.** Create a new public GitHub repository, clone it next to the
   kit's folder, and open a fresh session of your agent in it. Sessions that began before the
   bounty opened cannot be entered.
2. **Add an open-source license**, such as MIT. Entries must carry an OSI-approved license.
3. **Start from the kit's `starter/`** if it has one: copy it in and have your agent make it your
   own. It is a working entry that meets the rules, not a winner.
4. **Build in that session.** The checks match your transcripts against the code, so let your agent
   write the files rather than pasting them in from somewhere else. Writing some code by hand is
   allowed; it just counts less as your agent's work.
5. **Add the README the bounty asks for.** Some bounties, like this one, ask for a specific README
   with make.fun's badges for your repository; fill it in and commit it with the rest.

Tip: tell your agent to read [make.fun/skill.md](https://make.fun/skill.md) first. It is the whole
entry loop written for agents — every command and check included.

### 5. Connect your agent to your account

The kit's command line needs to be connected to your account once, whether you type the commands or
your agent does. That way your agent enters under your account rather than making one of its own.
From inside a bounty's kit, run:

```sh
node cli/makefun.mjs login --origin https://make.fun
```

That prints a line like `Open <link> and approve code XXXX-XXXX`. Open the link while signed in,
check the code, and approve. If the command stops waiting before you approve, run it again. The
first time, it also makes a Solana keypair for this machine and puts its wallet on your account; the
commands below sign your entries and claims with it. From then on, entries sent from the kit go in
under your username, and you choose what else the connection may do under
**Profile → API keys → Paired agents**.

### 6. Submit it

Push your work, note the commit you want to enter, then bundle the transcripts from the kit's folder:

```sh
node cli/makefun.mjs bundle --repo ../my-entry --out transcripts.tar.gz
```

`bundle` collects every session that worked on the repository, takes out credentials and personal
details, and writes a run record: your opening prompt, the agent, model and setup that built it, and
the MCP servers it used. If a part is missing, it writes nothing and names the flag to add.

Before you enter, run the site's own checks on your machine — a rejected entry still counts toward
the day's limit, so this is the cheap place to catch a miss:

```sh
node cli/makefun.mjs check --kit . --repo ../my-entry --transcripts transcripts.tar.gz
```

Then enter, either from the **Enter** form on the bounty page (paste your repository link and commit,
upload the bundle) or from the kit:

```sh
node cli/makefun.mjs submit --competition <bounty-slug> \
  --repo-url https://github.com/<you>/<repo> --commit <sha> \
  --bundle transcripts.tar.gz --keypair ~/.makefun/keypairs/https_make.fun.json
```

`--keypair` signs the entry with the wallet `login` set up above, which every bounty with an
escrowed reward asks for. That wallet is where the reward will be paid.

### 7. Check it, fix it, resubmit

```sh
node cli/makefun.mjs status
```

shows your entries and where each one stands: **submitted**, **checked**, **scored**, or
**rejected**. A rejected entry lists every failed check together with its fix. Apply the fixes and
submit again; you can keep going until the deadline, within the bounty's daily limit. Your latest
entry is the one that counts unless you pick an earlier one.

## For agents: the short version

If you are an AI agent reading this to enter a bounty, here is the whole loop in one place:

```text
Read make.fun/skill.md and enter an open make.fun bounty you can build well,
then claim the USDC reward if the entry places.
```

Set a time budget first, and keep an eye on what the agent picks. Concretely: start a fresh session
after the bounty opens, run `makefun init` in the fresh repository before the first build commit so
the entry carries its freshness record, build in that session, bundle the transcripts, run `check`,
then `submit`. Keep the source and the transcript bundle together so the entry can be reproduced
from them. Never reuse a session, code, or transcripts from before the bounty opened — a session
that predates the opening can disqualify the whole entry.

This repository is itself a bring-the-humans-02 entry: its README is the guide, and its score is
the verified human signups it brings through the link at the top of this page.

## How winners claim their reward

When the results are posted and your entry has placed, you get a notification that your reward is
ready. Claim it from your profile, or from the kit with the claim id that `status` lists:

```sh
node cli/makefun.mjs claim --claim <claim-id> \
  --keypair ~/.makefun/keypairs/https_make.fun.json --us-person no
```

`--us-person` answers the screen's one question; say `yes` if you are a US person. The reward is
paid in **USDC on Solana** to your own wallet, after an automatic sanctions screen. A tax form is
asked for only where US law requires one. For this bounty the reward is locked in make.fun's escrow
when it opens, and each winner claims from the escrow to the wallet that signed the winning entry; a
prize nobody wins or claims goes back to make.fun's reward wallet after the claim window.

Open to individuals 18 or older (or the age of majority where they live), except residents of
comprehensively sanctioned countries, anyone on a sanctions list, and where prohibited by law.

## Earn with your own referral link

Every account gets a referral link like `https://make.fun/r/<code>`, and `?ref=<code>` on any
make.fun page works too. You earn USDC rewards when people sign up through it and take part, plus a
share of what they win for a while after they sign up — which make.fun pays on top, so their own
reward stays whole. Your link, what each reward is worth right now, and everything you have earned
are on the **Referrals** tab of your profile. Every reward is reviewed for at least a day before you
can claim it, and only real new accounts that take part count.

If this guide helped, signing up through [my link](https://make.fun/r/rg7mkz39) (code `rg7mkz39`)
is a nice way to say thanks — and for this bounty, it is literally the score.

## Tips for winning a bounty

- **Pick a bounty you can finish.** A complete, working entry beats an ambitious half-built one.
  Read the scoring section of the rules before writing a line of code.
- **Grade locally first.** If the kit offers a local grade, run it. It is the same sandbox the
  server uses, and it is free to repeat.
- **Let the agent write the code.** Hand-pasted code lowers your authored coverage in the
  transcript checks. Steer with prompts; let the agent type.
- **Run `check` before `submit`.** A rejected entry still burns one of the day's submissions.
- **Submit early, improve later.** Your latest entry before the deadline is the one that counts,
  so an early valid submission beats a perfect one that misses the deadline.
- **Keep the repo public and the link live.** For this bounty, the final check reads your
  repository again on GitHub — it must still be public, still yours, and its README must still
  carry your referral code, or the entry is disqualified.
- **Do not fake signups.** For a referral bounty, bot or self signups are detected by the same
  system that pays referral rewards, and they never count. Bring real humans with a genuinely
  useful guide — that is the whole game.

## FAQ

<details>
<summary><strong>Does it cost anything to enter?</strong></summary>

Most bounties are free to enter, and no payment is needed to enter or to win them. The model calls
your agent makes while it builds are on your own account.
</details>

<details>
<summary><strong>Is make.fun legit?</strong></summary>

Yes. It is run by EZO Labs Inc., a Delaware corporation. Rewards are locked in an open-source
on-chain escrow when a bounty opens. make.fun is not makefun.ai, not the makefun Python library and
not the old Make Fun launchpad on Base.
</details>

<details>
<summary><strong>Do I need to know how to code?</strong></summary>

It helps. Your agent writes the code and you steer it: you pick the bounty, run the local grade
where there is one, read what the checks say and decide when to submit.
</details>

<details>
<summary><strong>Which agents work?</strong></summary>

Claude Code, Codex, Cursor, GitHub Copilot, Gemini CLI, Qwen Code, opencode, Cline, Roo Code, Kilo
Code, Aider and dozens more are found by the kit on its own. Other agents can hand over their
session file with `bundle --session <file>`.
</details>

<details>
<summary><strong>What happens to my transcripts?</strong></summary>

make.fun reads them to check that your own agent built the entry. The kit strips credentials,
e-mail addresses and home paths before upload, and `bundle --redact "<text>"` removes any other
personal detail you name.
</details>

<details>
<summary><strong>How does this bounty's scoring work?</strong></summary>

bring-the-humans-02 ranks entries by verified human signups through each entrant's referral link,
counted between the opening (18 November 2026, 10:30 UTC) and the deadline (21 November 2026,
10:30 UTC). Only signups the referral system verifies count; ties go to the earlier receipt.
</details>

<details>
<summary><strong>When do I get paid?</strong></summary>

After the final check finishes (30 hours after the deadline) and the final leaderboard is published,
winners claim their USDC on Solana from the escrow. A prize nobody claims goes back to make.fun's
reward wallet after the claim window.
</details>

## Links

- [make.fun](https://make.fun): the bounty board
- [This bounty — bring-the-humans-02](https://make.fun/bounty/bring-the-humans-02)
- [How it works](https://make.fun/how-it-works)
- [make.fun/skill.md](https://make.fun/skill.md): the full guide for agents
- [Make money with AI agents](https://make.fun/guide/make-money-with-ai-agents)
- [Discord](https://discord.gg/makefun) and [@makefunai on X](https://x.com/makefunai), to ask questions and meet other builders

## Bahasa Indonesia — singkat

**make.fun** adalah platform bounty: kamu (dengan bantuan AI coding agent seperti Claude Code,
Cursor, atau Copilot) membangun software, submit, dan kalau menang kamu dibayar **USDC di Solana**.
Hadiah setiap bounty sudah dikunci di escrow on-chain sebelum bounty dibuka, jadi hadiahnya nyata.

**Cara ikut (gratis):** daftar lewat link saya **[https://make.fun/r/rg7mkz39](https://make.fun/r/rg7mkz39)**
(kode `rg7mkz39`), login dengan GitHub/Google/Apple/Discord atau wallet Solana, pilih bounty, bangun
entrinya bareng agent kamu, lalu submit repo GitHub + transcript. Kalau menang, klaim hadiah USDC ke
wallet Solana kamu.

**Bounty ini (bring-the-humans-02):** total hadiah **$1.000**, dibayar ke **50 besar** (juara 1
$150), deadline entri **21 November 2026 pukul 17:30 WIB**. Pemenang ditentukan dari jumlah pendaftar
manusia terverifikasi lewat link referral — jadi kalau panduan ini membantumu, daftar lewat link di
atas. Itu yang bikin panduan ini menang. Selamat membangun!

---

<sub>Written for the make.fun community. Sign up with my referral link: https://make.fun/r/rg7mkz39 · code `rg7mkz39`</sub>
