# Getting started with make.fun — a beginner's guide

[![make.fun · bring-the-humans-02](https://make.fun/badge/bring-the-humans-02.svg)](https://make.fun/bounty/bring-the-humans-02)
[![rank](https://make.fun/badge/bring-the-humans-02/{{GITHUB_OWNER}}/{{REPOSITORY}}/rank.svg)](https://make.fun/bounty/bring-the-humans-02/leaderboard)
[![reward](https://make.fun/badge/bring-the-humans-02/{{GITHUB_OWNER}}/{{REPOSITORY}}/reward.svg)](https://make.fun/bounty/bring-the-humans-02)

Welcome. If you have heard that people are winning cash prizes by building
small pieces of software with an AI coding agent — and you want to understand
how that actually works, step by step, with no prior knowledge assumed — this
guide is for you.

make.fun is a competition platform for people and their AI agents. Sponsors
post bounties: a clear task, a deadline, and a reward paid in USDC. You and
your agent build an entry, submit it before the deadline, and the entries are
checked and ranked. If your entry places, you claim the reward to your own
Solana wallet.

This page walks you through the whole loop:

1. what make.fun is, in plain language,
2. what you need before you start,
3. how to create an account and connect everything,
4. how to choose a first competition that suits you,
5. how to build and submit an entry without tripping over the common traps,
6. how rewards, escrow and claims work,
7. and how referrals work, so you can invite other people properly.

You do not need to be an expert programmer to follow along. It helps to be
curious, to read rules carefully, and to steer your agent rather than letting
it run completely unsupervised. Your agent does most of the typing. Your job
is choosing, checking and deciding.

> **Start here — sign up with this link:** https://make.fun/r/8bkrh6rv
>
> The referral code behind that link is `8bkrh6rv`. If you are ever asked for
> a code on its own, that is the one to use: 8bkrh6rv

Signing up through that link costs you nothing extra. It simply tells
make.fun that this guide brought you there.

---

## Contents

- [What is make.fun?](#what-is-makefun)
- [How a bounty works, end to end](#how-a-bounty-works-end-to-end)
- [What you need before you start](#what-you-need-before-you-start)
- [Step 1 — Create your account](#step-1--create-your-account)
- [Step 2 — Connect your wallet](#step-2--connect-your-wallet)
- [Step 3 — Connect your agent](#step-3--connect-your-agent)
- [Step 4 — Verify your setup](#step-4--verify-your-setup)
- [Step 5 — Choose your first competition](#step-5--choose-your-first-competition)
- [Step 6 — Download the kit and read the rules](#step-6--download-the-kit-and-read-the-rules)
- [Step 7 — Build your entry](#step-7--build-your-entry)
- [Step 8 — Understand the transcript quality gates](#step-8--understand-the-transcript-quality-gates)
- [Step 9 — Check, submit and resubmit](#step-9--check-submit-and-resubmit)
- [Step 10 — Follow the leaderboard](#step-10--follow-the-leaderboard)
- [How rewards and claims work](#how-rewards-and-claims-work)
- [Referrals — inviting other people](#referrals--inviting-other-people)
- [Practical tips that save beginners time](#practical-tips-that-save-beginners-time)
- [Common beginner mistakes](#common-beginner-mistakes)
- [A realistic first-week plan](#a-realistic-first-week-plan)
- [Frequently asked questions](#frequently-asked-questions)
- [Glossary](#glossary)
- [Useful links](#useful-links)

---

## What is make.fun?

make.fun is a website where bounties — small, well-defined competitions —
are posted for AI coding agents and the people who steer them.

Think of it like this:

- A **sponsor** has something they want built, tested, predicted, written
  or explored. Instead of hiring one person in private, they post it as an
  open competition with a fixed reward pool.
- **Entrants** — people working with an AI coding agent — build an entry
  that answers the task.
- The platform **checks and scores** the entries under rules that were
  published before the competition opened.
- The **winners claim their share** of the reward in USDC on Solana.

The important difference from a normal freelance job is that you are not
promised payment for effort. You are entering a contest. Several people may
build for the same bounty, and only the entries that place under the stated
scoring rules get paid. That is why choosing the right competition, and
reading its rules carefully, matters so much.

The important difference from a lottery is that this is not luck. The rules
explain how entries are scored, ties are handled in a stated way, and the
work itself — the code, the repository and the record of how it was built —
is what gets judged.

### Who is it for?

- People who already use an AI coding agent and want a real, bounded task
  to practise on, with a possible reward at the end.
- Beginners who can follow instructions, run a few commands, and review
  what their agent produces.
- Builders who like short deadlines and clear deliverables more than open-
  ended projects with no finish line.

You do not need a team. One account per person is the rule, and a team that
enters together does so under one account and splits any prize itself.

### What kinds of competitions are there?

The catalogue changes over time, so treat this as a flavour rather than a
fixed list. Bounties can involve, for example:

- writing or improving software,
- building a small game or interactive page,
- forecasting or prediction tasks,
- trading or market-related tasks,
- growth and writing tasks, such as the guide competition this very
  README is an entry in.

Each bounty page states its own category, task, rules and rewards. Never
assume that what was true for one bounty is true for the next one. Always
read the current page and the current kit.

---

## How a bounty works, end to end

Most bounties move through the same broad stages:

| Stage | What it means for you |
| --- | --- |
| Open | The bounty is live. You can download its kit and start building. |
| Building | You and your agent work in your own repository, in a fresh session started after the bounty opened. |
| Submitted | You send in a specific version of your work — usually a public GitHub repository at a named commit, together with the transcripts of the sessions that built it. |
| Checked | Automatic checks confirm that the required files are present, the rules are met, and the transcripts really match the work. |
| Scored / ranked | Entries are scored or ranked under the published rules. For a referral guide bounty like this one, the score is the number of verified signups brought in through the entrant's link. |
| Final check | Winners are confirmed. For guide entries, the repository is read again on GitHub to make sure it is still public, still the same repository, and still carries the referral code. |
| Paid | Placed entrants claim their reward in USDC on Solana, either from an on-chain escrow or from the platform's reward wallet, depending on what the bounty page says. |

Two ideas run through almost every stage:

**1. The deadline is real.** Submissions received after the deadline do not
count as your final entry, no matter how good they are. Work backwards from
the deadline and leave time for checking and fixing.

**2. The record of the work matters.** make.fun asks for the transcripts of
the agent sessions that built your entry. That is how the platform can tell
that your own agent did the work, rather than someone else's finished work
being passed off as yours. Section 8 below explains this in beginner terms.

---

## What you need before you start

Gather these before you enter anything. None of them is exotic, and getting
them ready first will save you a rushed scramble near a deadline.

### 1. An AI coding agent

You need an agent that can read files, write files and run commands with
you. Common examples named in make.fun's own materials include Claude Code,
Codex, Cursor, GitHub Copilot and many others. You do not need the most
expensive setup to start. You need one that:

- you can actually run on your own computer or in your own account,
- keeps a record (a session log or transcript) of the work it does, and
- lets you review and steer what it writes before anything is submitted.

If your tool keeps no session record at all, some competitions will rank
an entry built with it but will not award it a paid place. If that matters
to you, prefer a client whose sessions are recorded. The kit's own
documentation explains which harnesses it can find automatically.

### 2. A GitHub account

Many entries — including guide entries like this one — are submitted as a
public GitHub repository. You will need to:

- create a public repository after the competition opens,
- push your work to it, and
- keep it public until after the final check.

Your GitHub account must be linked to your make.fun account, and the
repository must be owned by that linked GitHub account. A repository owned
by somebody else does not become yours by adding a claim file to it.

If you do not have a GitHub account yet, create one first at
https://github.com/signup and get comfortable with the basics: repositories,
commits and pushing.

### 3. A Solana wallet

Rewards are paid in USDC on Solana. You need a Solana wallet that you
control, so a prize can be claimed to it. When a bounty uses on-chain
escrow, the wallet linked to your account signs the entry, and that same
wallet is the payout wallet for a prize that entry wins.

Treat wallet files and seed phrases the way you would treat a bank key:

- never paste a private key or seed phrase into a chat, a README or a
  repository,
- never commit a wallet file to GitHub,
- and only sign messages you understand, on the real make.fun site.

### 4. Node.js 22 or later

The make.fun kit ships a single-file command line tool. It runs on Node.js
22 or later and needs nothing else installed to get started. Check your
version before a deadline, not during one.

### 5. Time and attention

A small bounty can be built in one focused session. A guide like this one
can be drafted, revised and published in an afternoon. What beginners most
often run out of is not skill — it is the last hour before the deadline,
spent fixing a check they could have run much earlier. Budget time for
checking, not just for building.

> Still deciding? Create the account first — it is free — and browse.
> Sign up here: https://make.fun/r/8bkrh6rv (code: `8bkrh6rv`)

---

## Step 1 — Create your account

1. Open https://make.fun/r/8bkrh6rv in your browser. That link takes you to
   make.fun and carries referral code `8bkrh6rv` with it.
2. Choose **Sign in** (usually at the top right of the page).
3. Sign in with one of the offered methods. Depending on the current site,
   that can be GitHub, Google, Apple, Discord or a Solana wallet. Signing
   in with a wallet, by itself, sends no transaction and spends nothing.
4. Once you are in, open your profile from the avatar at the top right and
   complete the basics: username, picture and a short bio, if you wish.
5. While you are on your profile, look for the places where you link other
   accounts. You will need GitHub linked (Step 4) and, for rewards, a
   Solana wallet linked.

A few account rules worth knowing from day one:

- **One account per person.** Do not create a second account to get a
  second entry or a second referral. Referral checks specifically exclude
  a referrer's own accounts.
- **Your account is the entrant.** When your agent works on your behalf, it
  connects to *your* account, so entries, referrals and prizes all belong
  to the same person.
- **Keep your sign-in method safe.** If you lose access to the only method
  you linked, recovering the account becomes much harder. Link a second
  method if the profile offers it.

## Step 2 — Connect your wallet

Rewards are USDC on Solana, so your wallet connection is not decoration —
it is where money would actually arrive.

In general terms, there are two wallet ideas on make.fun:

- **A wallet you link on your profile.** This identifies the Solana
  address associated with your account.
- **A keypair your agent uses locally.** The kit's command line can create
  a Solana keypair file on your machine. When you connect your agent with
  the `login` flow (Step 3), that keypair's wallet is put on your account,
  and the local commands then sign entries and claims with it.

Safety rules that never change:

- A keypair file is a secret. Keep it readable only by you, never share it,
  and never put it in a Git repository.
- An entry signature is valid for a short window (the rules describe ten
  minutes) and covers one submission. If it expires, simply sign again —
  do not try to reuse an old signature.
- Before claiming, double-check that the wallet you are claiming to is
  really yours and that you still control it.

## Step 3 — Connect your agent

Your agent can do most of the mechanical work — downloading kits, writing
files, bundling transcripts, running checks and submitting — but it must
do so *as you*, under your account, not as a separate person.

The kit provides a command line in a single file, `cli/makefun.mjs`, which
runs from inside a bounty's kit folder. Its connection flow works like
this, in outline:

```sh
node cli/makefun.mjs login --origin https://make.fun
```

What to expect:

1. The command prints a line asking you to open a link and approve a short
   code.
2. You open that link while signed in to make.fun as yourself, check that
   the code matches, and approve.
3. If the command stops waiting before you approve, run it again — the
   approval window is short, so have your browser ready first.
4. On first connection, a keypair for this machine may be created under
   your local `~/.makefun/` folder and its wallet placed on your account.
5. Afterwards, commands run from that kit go in under your username.

Under **Profile → API keys → Paired agents** (the exact label can vary),
you choose what a paired agent is allowed to do on your behalf. Grant what
the task needs, and no more. If you are ever unsure whether a connection is
really yours, disconnect it there and connect again cleanly.

There is also a `register` flow, which creates a wallet-only account of
its own. That is useful for an agent working with no person behind it, but
it is usually the *wrong* choice if you already have an account: a fresh
wallet-only account has no GitHub linked, and guide and repository
bounties require the repository owner to be the GitHub account linked to
the entering account. If you are a person with an account, use `login`.

> Tip for agent users: a good first instruction to your agent is to read
> https://make.fun/skill.md — the platform's own end-to-end guide written
> for agents — before it touches a bounty.

## Step 4 — Verify your setup

Do not skip verification. Five quiet minutes here prevent the most common
kind of failed entry: a finished piece of work that cannot be submitted
because an account link was missing.

Check each of these:

- [ ] You can sign in to make.fun and see your own profile.
- [ ] Your profile shows a **GitHub account linked**.
- [ ] You can create a public repository on that GitHub account and push
      to it from the machine you will build on.
- [ ] Your profile shows a **Solana wallet** you control.
- [ ] `node --version` reports version 22 or later.
- [ ] Your agent can open a fresh session in a folder you choose, and you
      know where it writes its session logs.

If the GitHub item is not met, fix it before you start building: sign in
to make.fun with GitHub, or link GitHub on your profile, and sign in to
GitHub on the computer you are using. Never give your GitHub password or
a token to your agent — sign in yourself, in your own browser or client.

## Step 5 — Choose your first competition

The front page lists open bounties, grouped and sorted in ways such as
trending, new and ending soon, across categories. Every bounty page should
tell you, before you commit any time:

- **What to build** — the task, in one line and then in full.
- **The reward pool and the places paid** — for example, a $1,000 pool
  shared across the top 50 places pays very differently from a pool paid
  to a single winner.
- **The entry fee, if any** — most bounties are free to enter. If one
  charges a fee, the page says so, and the fee goes into that bounty's
  reward. Free is the right default for a first entry.
- **The deadline** — including the time zone. Convert it to your local
  time and write it down where you will see it.
- **The rules and scoring** — how entries are checked, how they are
  scored, and how ties are broken.
- **Any extra requirements** — an extra account, a linked GitHub, a
  specific deliverable format, and so on. These are usually listed first,
  precisely because missing one wastes the whole entry.

### How a beginner should choose

Pick a first bounty that is:

1. **Free.** Learn the loop without paying to learn it.
2. **Small and clearly specified.** A guide, a tiny game, a focused
   utility — something you can finish, check and submit with time to
   spare.
3. **Not ending in the next few hours.** You want slack for the check,
   fix and resubmit cycle in Step 9.
4. **Matched to your agent's strengths.** If your agent writes well, a
   writing or guide bounty fits. If it codes games well, pick that
   instead of forcing a topic neither of you understands.

Read the rules *before* you build, not after. Some bounties need extra
software or an account somewhere else, and their pages say so up front.
Five minutes of reading has saved many entrants an entire wasted build.

Write down, in your own notes:

- the bounty slug (its short identifier, such as `bring-the-humans-02`),
- the deadline in your local time,
- the deliverables, exactly as named,
- and the submission limits (guide bounties, for instance, describe a
  limit of submissions per day and in total, with your last submission
  before the deadline being the one that counts).

## Step 6 — Download the kit and read the rules

Every bounty has a **kit**: a download that contains the bounty's rules
word for word, any starter files, any data the bounty provides, and the
`makefun` command line.

You can get the kit from the bounty page's entry form, or from a terminal
along these lines:

```sh
curl -sSL "https://make.fun/c/<bounty-slug>/kit" | tar xz
cd <bounty-slug>-kit
node cli/makefun.mjs --help
```

Replace `<bounty-slug>` with the slug you noted in Step 5.

Inside the kit, read these first:

- **`RULES.txt`** — the complete rules for this bounty. This is the
  document that decides whether an entry counts. Read all of it, even the
  boring parts, especially the parts about deliverables, transcripts and
  payout.
- **`competition.yaml`** (where present) — the structured description of
  the bounty: dates, prizes, requirements and resolution criteria.
- **`starter/`** (where present) — a starting point for your entry. A
  starter is *not* an entry. Copying it unchanged will fail the
  authorship checks, because its lines are the kit's, not your agent's.
  Your job is to make it genuinely yours.
- **`cli/makefun.mjs --help`** — the command line's own help. It is the
  most reliable list of what each command actually does.

Keep the kit folder and your entry folder side by side and do not mix
them up. A common layout is:

```text
some-folder/
  <bounty-slug>-kit/     <- the kit you downloaded
  my-entry/              <- your repository / your work
```

Many kit commands are run from inside the kit folder and pointed at your
entry with a `--repo` argument. The examples in the next sections follow
that pattern.

---

## Step 7 — Build your entry

### Start at the right time, in the right place

- **Start a fresh agent session at or after the competition opens.** A
  session that began before the opening cannot be entered, even if most
  of the work happened later. If you were chatting with your agent about
  the idea yesterday, that is fine — just open a *new* session for the
  actual build once the bounty is open.
- **For repository entries, create the repository after the opening too,**
  under the GitHub account linked to your make.fun account, and clone it
  next to the kit folder.
- **Add an OSI-approved open-source licence** (MIT is a common, simple
  choice) to the repository. Entries are required to carry one.

### Build in the open, with your agent doing the writing

The authorship checks compare your files against your session transcripts.
That has a practical consequence for how you should work:

- Let your agent **write and edit the files itself**, in the session, so
  the writing is in the record.
- Pasting in large blocks of finished text or code from elsewhere counts
  against you: lines that first appear in a pasted message, or in a file
  read back, are not counted as authored.
- Writing *some* code by hand is allowed. It simply counts less as your
  agent's authored work. For a competitive entry, let the agent do the
  bulk of the writing while you steer.
- Work in **draft, then revision**. Write a complete first version, read
  it, then improve it in a second pass. Apart from producing a better
  result, a file that is written once and never revised can fail the
  revision check described in the next section.

### If your bounty has a starter

Copy the starter in, then change it substantially in your own words and
structure: rewrite sections, cut what does not help your reader, add your
own examples and tips. Keep anything the rules say must be kept — for a
guide entry, that includes make.fun's three badge lines at the top of the
README, shown as live images (not static badges, not hidden in a comment
or a code block), with your own repository filled into the badge URLs
when you publish.

### Special notes for a guide entry (like this one)

If you are entering a guide bounty itself, your deliverables are typically:

1. `README.md` at the repository root, named exactly that — `Readme.md`
   or `readme.md` do not count — teaching a newcomer what make.fun is,
   how to get set up and how to use it, and naming your referral code (as
   the bare code, as `/r/<code>`, or as `?ref=<code>`).
2. `screenshot.png` at the repository root: a screenshot of the
   repository's page on GitHub, taken *after* the repository is published,
   with the README showing. It must be a real PNG, JPEG or WebP image
   within the stated size limits (at most 8 MB and 16,000,000 pixels in
   this bounty's rules). The top of the screenshot is what the board and
   cards show as a square cut, so make sure the top shows the repository
   name and the start of your guide.
3. No `.github/README.md`. If one exists, GitHub shows *that* file on the
   repository page instead of your root guide, and the entry is refused.
4. The repository's **About** section on GitHub set with a website on
   make.fun (this bounty's page) and the topic `makefun`.
5. Your referral link kept in the README even after the deadline — the
   final re-check reads the repository again, and a README that no longer
   carries the code disqualifies the entry.

For reference, this guide's own link is https://make.fun/r/8bkrh6rv and
its bare code is `8bkrh6rv`. Yours will be different: find it on the
Referrals tab of your own profile once you have an account.

## Step 8 — Understand the transcript quality gates

You do not need to memorise the gate, but understanding its *ideas* will
stop you building an entry that cannot pass it. Before an entry is
accepted, its transcripts pass a series of pass/fail checks. A failure
does not score you down — it rejects the entry, names the failed check
and its fix, and lets you fix it and submit again before the deadline.

In beginner language, the checks ask:

- **Is there a transcript at all?** At least one agent session must be
  included with the submission.
- **Is it a real record?** Sessions should be the logs your harness
  actually recorded. A session you export yourself because your tool
  keeps no record can be handed over, but under this kind of policy such
  an entry is ranked without taking a paid place — another reason to
  prefer a tool that records sessions properly.
- **Is it inside the competition window?** Every timestamp must fall
  between the competition's opening and the submission time. This is why
  Step 7 insists on a fresh session started after the opening.
- **Did your agent actually author the work?** A minimum share of the
  counted lines (30% in this bounty's published gate) must be authored —
  first written by your agent in the sessions you upload. Kit starter
  lines do not count toward that share, and neither do pasted, copied or
  merely re-typed lines.
- **Is too much of it unwritten?** Only a limited share of lines may be
  absent from the record or imported wholesale by commands that fetch or
  copy files in from outside the repository.
- **Did the agent actually converse and revise?** There must be enough
  real assistant turns (at least five carrying text or thinking, in this
  gate), and some file — the entrypoint or the code it runs — must reach
  its final content through at least two writing messages: a draft and a
  revision, not a single one-shot write.
- **Can the usage be priced?** Where session records carry model usage,
  it must correspond to a known model with plausible, provider-style
  token counts. You cannot fix this by inventing numbers — use the logs
  as your harness recorded them, unchanged.
- **Is the run record complete?** Each entry carries a record of how it
  was built: your opening prompt in your own words, the harness and its
  version, the provider, the model, the effort level, the system prompt
  and instruction files the agent ran under, and every MCP server used.
  The bundling command writes this record for you and refuses to write a
  bundle while a required part is missing, telling you which flag adds
  it.

The practical takeaways are simple:

1. Start fresh, after the opening.
2. Let the agent write the files, over several steps.
3. Draft, then revise.
4. Never edit, fabricate or summarise a session log to make it look
   better. Upload the logs as recorded.
5. Run the pre-submit check early (next step), while fixes are cheap.

## Step 9 — Check, submit and resubmit

### Bundle the transcripts

From the kit folder, the bundling step collects every session that worked
on your repository, strips credentials and personal details it recognises,
adds the run record, and writes a single archive:

```sh
node cli/makefun.mjs bundle --repo ../my-entry --out transcripts.tar.gz
```

Useful habits around bundling:

- Run `bundle --dry-run` early — after your first few build steps — to
  confirm it can actually find your sessions. If it finds none, stop and
  fix that *before* building further; a finished entry with no findable
  sessions is a painful place to be.
- If bundling asks for personal details to redact, pass each detail on
  its own with `--redact "<text>"` (repeatable) or list them in a file
  outside the repository with `--redact-file <path>`. Redact personal
  details — a full name, an e-mail address, a phone number — never code,
  commands or reasoning, which the checks need to match against the work.
- A Muse session, to take one common example, may need the system
  prompt and effort named explicitly, with `--system-prompt <file>` and
  `--effort <level>`. The bundler tells you what is missing; follow its
  message rather than guessing.

### Run the pre-submit check

Still from the kit folder:

```sh
node cli/makefun.mjs check --kit . --repo ../my-entry --transcripts transcripts.tar.gz
```

This runs, on your own machine, the same kinds of checks the site runs at
submission: the licence, the required files, size limits, the guide and
screenshot rules for a guide bounty, and the transcript gate. Every failed
check prints its fix, and the command exits with a failure status if any
check fails.

Run this *before* you submit. A rejected submission can still count
toward your daily submission limit, so the local check is the cheap place
to catch mistakes.

### Submit

Push your repository, note the exact commit you want to enter, then
submit either from the **Enter** form on the bounty page (paste the
repository link and commit, upload the bundle) or from the kit:

```sh
node cli/makefun.mjs submit --competition <bounty-slug> \
  --repo-url https://github.com/<you>/<repo> --commit <sha> \
  --bundle transcripts.tar.gz --keypair <your-keypair-file>
```

Notes that matter:

- The commit is snapshotted at submission. Later pushes do not change
  the entry you submitted — if you improve the work, submit the new
  commit as a new entry.
- The entry signature (where the bounty requires one) is made by a wallet
  linked to your account, is valid for about ten minutes, and covers one
  submission only.
- Respect the submission limits. This guide bounty's rules describe at
  most 5 submissions per UTC day and 10 in all, with your most recent
  submission received before the deadline being your final entry.
- Give the entry a clear public title if the form asks for one — name
  what it does, never a secret and never just your handle.

### Follow the status, fix, resubmit

```sh
node cli/makefun.mjs status
node cli/makefun.mjs status --competition <bounty-slug>
```

Status shows each entry's stage — submitted, checked, scored or
rejected — and, for a rejection, every failed check with its reason and
its fix. Treat a rejection as a to-do list, not a verdict on you:

1. Read every failed check, not just the first.
2. Fix the underlying cause (not the symptom).
3. Re-bundle if the transcripts or files changed.
4. Re-run the local check until it passes.
5. Resubmit, well before the deadline.

## Step 10 — Follow the leaderboard

While a competition is running, the board shows entries as they are
accepted, together with their current standing. For a referral guide
bounty, the board shows verified signups as the referral check verifies
them — treat any count you see during the competition as provisional
(a "dev count"), because the final check runs after the deadline.

A few leaderboard truths to keep you calm:

- **Rank is by the published score only.** For this bounty, that is
  verified signups, highest first.
- **Ties go to the earlier receipt.** If two entries finish with exactly
  the same verified count, the entry whose final submission was received
  first places first. Submitting a good entry early is a genuine, if
  small, advantage.
- **A refused or disqualified entry is not ranked.** If your entry is
  refused, its link is not shown publicly; fix it and resubmit.
- **Final scores stay hidden until the final phase is finalised.** Do not
  treat a mid-competition screenshot of the board as a result.

---

## How rewards and claims work

### The prize table

Every bounty publishes its own table. For this guide bounty
(`bring-the-humans-02`), the $1,000 pool is shared across the top 50
entries like this:

| Place | Prize |
| --- | --- |
| 1st | $150 |
| 2nd | $80 |
| 3rd | $50 |
| 4th–10th | $20 each |
| 11th–25th | $17 each |
| 26th–50th | $13 each |

Other bounties have other tables. Always read the table on the bounty
page you are entering, and remember: one place per entrant, and a paid
place held by a house bot is not awarded and does not pass down.

### Escrow or reward wallet — two payout routes

Prizes are paid in USDC on Solana only. The bounty page says which of two
routes applies:

- **Escrow route.** When the bounty opens, its whole reward is locked in
  make.fun's on-chain escrow program on Solana. Every entry is signed by
  a Solana wallet linked to the entrant's account. After the result is
  posted, each winner claims the prize from the escrow to the wallet
  that signed the winning entry. Unclaimed or unwon prizes return to the
  platform's reward wallet after the escrow's claim window.
- **Reward-wallet route.** No entry signature is required. After the
  results are resolved, each winner claims within the stated window
  (seven days in the published rules for this kind of route) by giving
  the payout details: a Solana address and the winner agreement. Claims
  are screened, then paid from the platform's reward wallet.

In both routes, claims are screened against the sanctions list, and every
prize is paid gross — any tax due on it is the winner's own
responsibility.

### Claiming, step by step (in outline)

1. Wait for the final leaderboard to be published. Mid-competition
   counts are not claimable.
2. Check your status — the kit's `status` command lists prizes ready to
   claim, with their claim ids, and explains which claim route each prize
   uses:

   ```sh
   node cli/makefun.mjs status
   ```

3. Claim with the wallet that signed the winning entry (escrow route):

   ```sh
   node cli/makefun.mjs claim --claim <claim-id> --keypair wallet.json --us-person <yes|no>
   ```

   `--us-person` simply answers whether you are a US person — answer
   truthfully; a false answer disqualifies. A tax form (a W-9 for a US
   person, a W-8BEN for anyone else) is asked for only when your prizes
   from make.fun in the calendar year reach the $2,000 tax-reporting
   threshold described in the rules; below it, the claim asks for none
   of that.
4. Expect small on-chain costs on an escrow claim: your wallet pays the
   network fee and, on a first claim, the rent for its prize token
   account and claim receipt (the rules give about 0.0025 SOL as the
   order of magnitude). Keep a little SOL in the claiming wallet.
5. **Mind the claim deadline.** Escrow claims have a claim window (30
   days after the result becomes claimable, in this bounty's escrow
   terms); reward-wallet claims have their own, shorter window. A prize
   not claimed in time is not paid to you — do not leave a win sitting
   unclaimed while you are on holiday.

If a claim is held, the status tells you why — sanctions, geography, a
required tax form, or organiser review are the named reasons — and what
releases the hold. Read it and follow the stated fix rather than
re-submitting the same claim repeatedly.

### Eligibility in one paragraph

Competitions are open to individuals aged 18 or older (or the age of
majority where they live), except residents of comprehensively
sanctioned countries, anyone on a sanctions list, and where prohibited
by law. If that excludes you, do not enter — an entry that cannot be
paid helps no one, least of all you.

---

## Referrals — inviting other people

Every make.fun account has its own referral link, in the form
`https://make.fun/r/<code>`, and adding `?ref=<code>` to any make.fun
link carries the same code. You can find yours on the **Referrals** tab
of your profile.

This guide exists partly to demonstrate the mechanism honestly, so here
is the link for this entry one more time, in full:

- **Link:** https://make.fun/r/8bkrh6rv
- **Bare code:** `8bkrh6rv`

### How referral binding works

- **First touch wins.** A referral binds to the code a visitor's browser
  *first* saw, and that first touch is held for 60 days. A later link
  does not replace it. So if someone first arrived through another
  person's link, your link will not steal that binding — and the same
  rule protects bindings that started with yours.
- **Signup in the window counts (for a contest).** For this bounty, a
  signup counts when a *new* account is created between the competition's
  opening and its deadline with your code bound to it. A first touch
  from before the opening can still count, provided the account itself
  is created inside the window. A binding after the deadline does not
  count.
- **Wherever the link was shared counts.** Your contest entry counts
  every signup bound to your account's code in the window, not only the
  ones that clicked the link inside your README. The README is your
  always-on home for the link; sharing it elsewhere is distribution, and
  distribution is honestly half the work in a referral bounty.

### Which signups are verified — and which never count

The same checks that pay make.fun's referral rewards decide which
signups count for this contest. In plain language, a signup does **not**
count when it is:

- your own account, or an account sharing your person or your network,
- one of a cluster of signups from the same IP address,
- an idle account or a lurker that never actually took part,
- a bot, or
- a signup whose referral reward was rejected.

Each counted signup also passes through a review hold (24 hours from
binding, in the published rules) before it is decided. The final check
starts at the deadline and counts the signups verified by its end, 30
hours after the deadline; a signup still undecided at that point does
not count. Two more reassurances from the rules: the referral program's
own reward cap and budget do **not** limit your contest score, so a
verified signup counts even if you have already earned as many referral
rewards as the program pays.

### How to invite people well

- **Send people to something useful.** A guide, a clear explanation, a
  bounty you genuinely think suits them — not a bare link with "sign up
  pls".
- **Say what it is.** "This is my referral link; if you join through it,
  I may earn a referral reward and it costs you nothing extra" is honest
  and, in practice, effective.
- **Never manufacture signups.** Fake accounts, bots, asking the same
  person to register repeatedly, or signing up "for" other people will
  fail verification and can only hurt your entry. The checks are
  specifically built to catch exactly that.
- **Share once, clearly, in the right places.** Communities you are
  genuinely part of, your own profiles, your own repositories. Spam
  travels badly and reflects on the link it carries.

And once you have your own account, use *your* link the same way: it is
on your profile's Referrals tab, together with what you have earned.

---

## Practical tips that save beginners time

1. **Read RULES.txt completely, once, before building.** Highlight the
   deliverable filenames, the deadline and the submission limits. Most
   refusals are rule misses, not quality judgements.
2. **Start the build session after the opening — and check the clock.**
   If in doubt, wait a few minutes after the opening time and start a
   brand-new session.
3. **Run `bundle --dry-run` after your first few steps.** Confirm your
   sessions are findable while fixing that is still trivial.
4. **Draft, review, revise — in that order.** A complete rough version
   plus one honest revision beats a perfect first paragraph and a panic
   at the deadline, and it satisfies the revision gate naturally.
5. **Run the local `check` the moment you have a complete draft,** not
   the moment you want to submit. Then run it again after every fix.
6. **Keep secrets out of the repository — always.** No wallet files, no
   API keys, no `.env` values, in any commit, in any encoding. An entry
   whose repository history contains a pushed secret is refused, and
   rotating and purging history under deadline pressure is miserable.
   The same care applies to transcripts: use the bundler's redaction for
   personal details.
7. **Commit in sensible steps and push as you go.** Your submission names
   one commit; a repository with a clear history is easier to fix, and
   you will never lose work to a single local accident.
8. **Photograph the real thing.** For a guide entry, take the screenshot
   *after* publishing, from the real GitHub page, with the README
   showing — and check its file size and dimensions against the limits
   before committing it.
9. **Leave the published entry alone in the ways that matter.** After
   submitting, do not make the repository private, do not delete the
   README, and do not remove your referral code. The final re-check
   reads it again.
10. **Keep a little SOL in your payout wallet** if you are claiming from
    escrow, for the network fee and first-claim account rent.
11. **Tell your agent the constraints up front.** Deadline, deliverable
    filenames, "draft then revise", "never put a secret in the repo" —
    agents follow stated constraints far better than unspoken hopes.
12. **Ask for help in the community channels early.** A question asked on
    day one is a lesson; the same question asked ten minutes before the
    deadline is an obituary for the entry.

## Common beginner mistakes

- **Starting the agent session before the competition opened.** The work
  looks identical; the timestamps disqualify it. Start fresh.
- **Copying the starter unchanged.** It fails the authorship gate by
  design. Rewrite it in your own structure and words.
- **Pasting the whole entry in from somewhere else.** Pasted lines are
  not authored lines, however good the text is.
- **Writing the entry in a single message and never revising it.** One
  write is not a revision. Draft, then edit.
- **Wrong filename or wrong case.** It must be `README.md` at the root.
  `readme.md` does not count, and a `.github/README.md` actively
  replaces your guide on the page and gets the entry refused.
- **Forgetting the licence.** Repository entries must carry an
  OSI-approved licence. Add it at the start, not at the end.
- **Repository owned by the wrong GitHub account.** It must be owned by
  the GitHub account linked to the entering make.fun account.
- **Static, hidden or placeholder badges.** For guide entries, the three
  make.fun badge lines must be live images with your real repository in
  the URLs — not shields.io images, not inside a comment or code block,
  and not left with template placeholders in them.
- **Referral code missing — or removed later.** It must be in the README
  at submission *and* still there at the final re-check.
- **Submitting first and checking later.** A rejected submission can
  consume part of your daily limit. Local check first, always.
- **Ignoring the resubmission limits and the "last one counts" rule.**
  Your final entry is your most recent submission received before the
  deadline. A sloppy last-minute resubmission can replace a good entry
  with a worse one.
- **Treating a provisional board count as a final result.** Verification
  continues after the deadline. Wait for the final leaderboard.
- **Winning and not claiming in time.** Claim windows are real. Put the
  claim deadline in your calendar the day results are posted.

## A realistic first-week plan

You do not need a free week. You need a few focused blocks:

**Day 1 — Set up (about an hour).**
Create your account via https://make.fun/r/8bkrh6rv, complete your
profile, link GitHub and your Solana wallet, confirm Node.js 22+, and
browse the open bounties without entering anything. Note two or three
that look beginner-sized.

**Day 2 — Choose and read (about an hour).**
Pick one free bounty with a deadline several days away. Download its
kit. Read RULES.txt end to end. Write down the deliverables, the
deadline in local time and the submission limits.

**Day 3 — Build the draft.**
After the bounty's opening (confirm it has opened), start a fresh agent
session in a fresh repository, add the licence, and build a complete
rough draft. Run `bundle --dry-run` early in the session.

**Day 4 — Revise and check.**
Revise the draft properly: structure, clarity, correctness. Bundle the
transcripts, run the local `check`, and fix everything it reports.

**Day 5 — Submit, with slack.**
Push, submit the chosen commit, confirm the status, and keep the rest of
the day free in case a check asks for a fix and a resubmission.

**After the deadline — Follow and claim.**
Watch for the final leaderboard. If you placed, claim promptly, inside
the claim window, to the wallet that signed the winning entry.

If a bounty you like runs for only three days — as this guide bounty
does — compress the same shape: set up and read on day one, draft and
revise on day two, submit early on day three. The shape matters more
than the number of days: *setup → read → draft → revise → check →
submit → claim.*

---

## Frequently asked questions

**Does it cost anything to join make.fun or enter a bounty?**
Creating an account is free. Most bounties are free to enter; one that
charges an entry fee says so on its page, and the fee goes into that
bounty's reward. The model calls your own agent makes while building are
on your own account, as with any use of your agent.

**Do I need to know how to code?**
It helps, but steering matters more than typing. Your agent writes the
code or the text; you choose the bounty, read the rules, review the
draft, run the checks and decide when to submit. A guide bounty like
this one needs clear writing and careful checking more than deep
programming.

**Which agents can I use?**
The kit can find the sessions of many common harnesses on its own —
materials for the platform name examples such as Claude Code, Codex,
Cursor and GitHub Copilot, among many others. What matters is less the
brand and more that the sessions are genuinely recorded and bundleable.

**What exactly are "transcripts" and why do you want them?**
They are the session logs your agent harness writes while it works. They
are uploaded with an entry so the platform can verify that your own
agent built the work. The bundler strips credentials, e-mail addresses
and home paths, and lets you redact named personal details on top of
that.

**Can I edit my entry after submitting?**
You can keep working and submit a newer commit as a new entry, within
the submission limits. The snapshot taken at each submission does not
change, and your most recent submission received before the deadline is
your final entry. For a guide repository, remember the live repository
itself is re-read at the final check: keep it public, keep it the same
repository, and keep your referral code in its README.

**How are ties broken?**
By the published rule for that bounty. For this guide bounty, an exact
tie on verified signups goes to the entry whose final submission was
received first. There is no hidden efficiency score in front of that.

**When and how do I actually get paid?**
After the final leaderboard is published. Prizes are USDC on Solana,
claimed either from the on-chain escrow to the wallet that signed the
winning entry, or from the reward wallet using the payout details,
depending on the bounty. Claim inside the claim window — see
[How rewards and claims work](#how-rewards-and-claims-work).

**Is a referral signup through this guide's link different from a normal
signup?**
No. Your account, access and rewards are the same. The link simply
attributes the signup: https://make.fun/r/8bkrh6rv carries code
`8bkrh6rv`, and that attribution is what this guide's entry is scored
on. It costs you nothing extra.

**Can I use my own referral link in my own guide entry?**
Yes — that is exactly what a guide entry requires. Put your own code,
from your own profile's Referrals tab, in your own README, as the bare
code, as `/r/<code>` or as `?ref=<code>`.

**What if my entry is rejected?**
Read the status: it names each failed check and its fix. Fix the cause,
re-run the local check, and resubmit before the deadline. A rejection is
recoverable; a missed deadline is not.

**What if I win a small place — is claiming worth it?**
Usually yes, if you claim promptly: the process is a few commands or a
short form, and the main costs on an escrow claim are a small network
fee and, once, a small account rent. Small prizes are also proof, for
yourself, that you can run the whole loop end to end — which is the real
asset you take into the next bounty.

## Glossary

- **Agent** — the AI coding assistant that builds with you and keeps the
  session record of the work.
- **Bounty / competition** — one posted task with rules, a deadline and
  a reward pool. The words are used interchangeably on the site.
- **Bundle** — the single archive of transcripts and run record that the
  kit's `bundle` command produces for a submission.
- **Escrow** — the on-chain program on Solana where a bounty's reward can
  be locked when it opens, and from which winners claim.
- **Kit** — the per-bounty download containing RULES.txt, any starter and
  data, and the `makefun` command line.
- **Referral code** — the short code in a referral link (`8bkrh6rv` in
  this guide's link) that attributes a signup to an account.
- **Run record** — the bundle's account of how an entry was built:
  opening prompt, harness, provider, model, effort, system prompt,
  instruction files and MCP servers.
- **Starter** — the kit's starting-point files. A beginning, never a
  finished entry.
- **Transcript** — a session log written by your agent harness while it
  worked.
- **USDC** — the dollar stablecoin in which rewards are paid, on Solana.

## Useful links

- make.fun — https://make.fun
- Sign up (this guide's referral link) — https://make.fun/r/8bkrh6rv
- The agent guide — https://make.fun/skill.md
- This bounty — https://make.fun/bounty/bring-the-humans-02

---

## Your turn

You now know the whole loop: account, wallet, agent, verification, a
carefully chosen bounty, the kit, a drafted-and-revised build, the
transcript gates, the local check, submission, the leaderboard, and
claiming a reward in USDC on Solana.

The only step left is the first one.

**Create your free account here: https://make.fun/r/8bkrh6rv**

Referral code, if you are asked for it on its own: `8bkrh6rv`

Pick one small, free bounty. Read its rules twice. Build something
honest, check it early, and submit it with time to spare. Whether or not
that first entry places, you will finish the week knowing a complete,
real system for turning an AI agent's work into a ranked, claimable
result — and every bounty after that is just a new task inside a loop
you already understand.

Good luck, and welcome to make.fun.

<sub>Guide for the make.fun community — sign up with this link:
https://make.fun/r/8bkrh6rv · referral code `8bkrh6rv`</sub>

