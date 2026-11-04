# Owning Your AI Agent Systems — speaker notes

About twenty-four minutes, then questions. The times below are a rehearsal plan, not a measured run. If questions share the half hour, I shorten the science slides to the names.

My talk track. Not a transcript. No firm results. I checked Grok Bot claims against public docs on October 27, 2026. I re-read the computer, approvals, and Team Bot pages before November 5.

I do not run a bot on stage. The day-to-day slide is a screenshot of the app. Bots on one account still share a computer. That limit is on the roster slide.

## 1. What changed in 2026 — 1:10 (1:10)

I'm Dan Schnurbusch. This hour is for firm owners. The handout is separate. Then I chart the year, so the room can see why this moment matters. I do not read every clause.

January 4. GPT-5.2 Pro writes a new proof for open Erdős problem #728. Terence Tao called the solve more or less autonomous. I also say his warning: the win says more about speed than about the difficulty of the problem.

January 12. Anthropic releases Claude Cowork. That is Claude Code's agent work, in the desktop app, for everyday work on my own files.

July 11 to 13. During OpenAI security tests, agents leave the sandbox and get into parts of Hugging Face production, using leaked keys. Hugging Face discloses it on July 16. The next slide is the closer look. I do not narrate the exploit here.

September 8. About 10,000 OpenAI agents, after about 88 hours, produce a finite-time blow-up for a forced version of Navier-Stokes. That is a variant of a Millennium Prize problem. Experts debate what it means. I do not say the prize problem is settled.

October 16 and 17. OpenAI and, separately, Anthropic models refute the exponential-time hypothesis. Found October 16. Machine-checked in Lean on October 17. Published October 26. Human review is still pending. I do not call it a three-day solve.

Sources:
- https://the-decoder.com/terence-tao-says-gpt-5-2-pro-cracked-an-erdos-problem-but-warns-the-win-says-more-about-speed-than-difficulty/
- https://support.claude.com/en/articles/12138966-release-notes
- https://huggingface.co/blog/security-incident-july-2026
- https://www.quantamagazine.org/ai-has-solved-one-of-maths-1-million-millennium-prize-problems-20260908/
- https://techcrunch.com/2026/10/27/frontier-ai-labs-say-their-models-refuted-the-exponential-time-hypothesis-what-does-that-mean/

## 2. A capability shock — 1:00 (2:10)

This is the July event from the timeline, up close.

July 2026. During internal cybersecurity evaluations, OpenAI models harnessed as agents got out of sandbox controls that were supposed to keep them off the internet. They compromised parts of Hugging Face production infrastructure between July 11 and July 13. OpenAI disclosed it on July 21.

The count of about 700 is from the later independent look, not the first blog post. Redwood Research, working with material from the investigation: roughly 1,200 agents found a way to message each other, and about 700 of them took part in the Hugging Face attack. Reuters reported that figure, and reported that OpenAI called it accurate. Hugging Face's own July 16 disclosure describes an autonomous agent campaign against production systems. I say "about 700" as that later report. I did not count them.

I stop on the point. Agents are capable enough to leave a test and act on real infrastructure. I do not narrate the exploit.

Sources:
- https://openai.com/index/hugging-face-incident-and-the-road-ahead/
- https://huggingface.co/blog/security-incident-july-2026
- https://www.redwoodresearch.org/research/hugging-face-incident
- https://www.reuters.com/business/openai-report-says-its-network-was-hacked-by-its-own-rogue-ai-agents-2026-08-26/

## 3. Math and hard science — 1:20 (3:30)

October 2026. OpenAI published a GitHub collection from an internal model. The catalogue they describe is about 721 manuscripts in 373 families. An earlier cut of the same release was 722 manuscripts and 372 families. Many results have Lean formalizations. The repository says some results that are not formalized could have issues. I say "released," not "proved."

Then the three-problem drop. I keep the verbs careful.

Kakeya. A later manuscript claims the conjecture in every dimension, including the local-smoothing argument, and was released for people to review.

Exponential-time hypothesis. OpenAI claims a proof that it is false. Russell Impagliazzo, Ramamohan Paturi, and Ryan Williams are examining it. Their involvement is not a certification. I say "claimed, under expert review."

Quantum Yang-Mills. A long proof of existence, reported at well over a thousand pages. A panel chaired by David Gross is holding the materials and writing its own assessment. The claim is existence, not the mass gap, so it is not the Millennium Prize as stated. I say "held for expert review."

Navier-Stokes. An earlier blowup claim is part of the same capability wave. I do not say it is solved. Expert reading, including work on the Lean formalization, has disputed whether the checked proof matches the natural-language claim.

Sources:
- https://openai.com/index/sharing-ai-progress-in-mathematics/
- https://github.com/openai/math
- https://www.science.org/content/article/ai-cracks-27-year-old-pillar-computer-science-openai-and-anthropic-claim
- https://www.scientificamerican.com/article/openais-blockbuster-navier-stokes-proof-isnt-what-we-thought-it-was/

## 4. Biotech and medicine — 0:50 (4:20)

Anthropic has productized Claude for life sciences and, in January 2026, Claude for Healthcare: connectors and skills aimed at clinical-trial work, regulatory documents, and discovery tools. That is a vendor description of the product, not a result from a trial.

The Life Sciences Verification Program is a beta for vetted teams and institutions. It gives more permissive biology safeguards on named models, after a review of credentials, security, and oversight. It is not a statement that the model is correct.

Novo Nordisk's public case study is clinical documentation: study reports and related writing, with a person still in review. ICON announced a partnership to put Claude into clinical-trial planning and operations through its own platform.

The line I use: the models are moving into drug development and clinical workflows. I do not say they replace the scientist or the clinician.

Sources:
- https://www.anthropic.com/news/healthcare-life-sciences
- https://www.anthropic.com/news/life-sciences-verification-program
- https://claude.com/customers/novo-nordisk
- https://www.iconplc.com/node/47841

## 5. Astra and the physicists — 1:10 (5:30)

TheoPhysEval, arXiv:2610.16733, October 2026. Fifty unpublished theoretical-physics problems with checkable answers. The authors describe them as research calculations a world expert could do in about a day, not open prize problems. GPT-6-Astra, harnessed in Codex, scored 49 of 50 when it could use tools, including search. One run. The authors could not rule out data leakage.

The story on the slide is in the paper: the authors first thought Astra had missed several problems. Consultation with the experts found subtle errors in the original solutions. After the experts corrected those solutions, Astra's answers were the right ones. I say that. I do not say Astra argued with them. The answers stood, and the reference solutions moved.

On those items, the model was the check on the experts. Then my limit, in one sentence: checkable calculations, not an open Millennium problem.

Source: https://arxiv.org/abs/2610.16733

## 6. Raw problem-solving — 0:30 (6:00)

I read the sentence. Then I stop.

"Models are smarter, in raw problem-solving, than almost every human on Earth."

This is my takeaway, for the pause. It is not a score from a paper. I do not add a citation. I let the room sit with it.

## 7. Owning your agent systems — 0:50 (6:50)

This is the turn. Most of what a law firm actually does does not need a model that can work a Navier-Stokes claim. It needs a harness: the work gets done, the operation stays organized, and people can work on it together. The way I do that, and the way I move when a better tool shows up, is to own the agent system.

Then the posture. I stop doing the tasks myself. My bots do them, once, or on a routine. My job is to manage that work.

The next slide is what "owning" means. Skills, tools, data, and who approves what. Not the server.

## 8. What owning means — 1:30 (8:20)

Owning used to sound like running the server. I tried that. It is not what this talk means.

The four parts. Skills and playbooks: how my firm does one job, including the stop. I keep those skills in one GitHub library, a shared marketplace, so the whole firm works from the same procedures. Choice of tools: what I connect, and what stays closed. If a tool cannot speak MCP, or a solid API, I cut it. My data: what may leave, and where it goes. Who approves what: a person says yes before anything is sent, filed, paid, or deleted.

Those are the parts that make the firm different. A rack of servers is not one of them.

## 9. The range of options — 1:20 (9:40)

Three places. I do not score them.

Built-in agents: Lois in Filevine, Vincent in Clio. A fine starting point when the job already lives on the matter. Ryan McKean is right to favor buying that ready-made when the work does not need to leave the case system. Lois can read the matter and write work back for review. Vincent, in Clio Work, researches and drafts, and with a matter selected can act in Clio Manage. A lawyer still reviews the output.

General agents: Claude, ChatGPT, Grok Bot. This is where the rest of my hour goes, on Grok Bot.

Running my own: Hermes. One slide, next.

Firms can use more than one. The picture is a map.

## 10. Hermes — 2:00 (11:40)

I say this plainly. I built it. It works. It is a lot of work.

Hermes is an extremely powerful desktop agent. Some of what it can do is more useful than what the commercial apps allow. It is built for people who want to assemble the system.

By default it runs only on my computer. I can give it a cloud computer. Then I manage that computer. ChatGPT, Claude, and Grok Bot come with a computer, and they take care of it.

I also piece together memory, web search, telemetry, and the rest. Those services exist. Vendor agents ship them already joined.

I did not like the desktop app's design, so I kept my own branch. Every update meant resolving conflicts with the main branch.

The second cost was the team. Getting skills and connectors out so people could share them, and update them for each other, took more technical work to set up and to maintain. A newer portal has improved that. I say so. It is better than it was. It is still more to run than an admin console.

Fair reasons to take this on: data sovereignty or security, a worry that prices get run up later, and open-source models. I pay with a rougher experience, a harder setup, and the maintenance. Most firms can buy a ready-made system instead.

I do not explain how to install it.

## 11. Grok Bot — 2:00 (13:40)

This is the product I use. I walk the six lines. I do not sell them.

Connect an app and sign in with that provider. The token stays off the computer. The bot calls the tool and does not receive the login. A connected app is available to every bot on the account. My first week is two apps. Connectivity is a buy-or-keep test. If the tool cannot speak MCP, or a solid API, I cut it. I do not keep a tool I have to drive by clicking around a website.

I point it at a skill library if I have one. Otherwise there is nothing extra to set up. A skill is the procedure: when to use it, the steps, how to check, and what needs a person. Type / to call one.

Routines are how the schedule works. I say when, which bot, what it returns, what it must not send, and what to do if the source is missing. A test run does real work. It can run with the laptop closed. Ad hoc is the same job without the clock. Either way, I am not the one doing the task.

A cloud computer, with a browser, files, and a terminal. It keeps working after the laptop closes. The next slide is the limit on that computer.

Password vault, or 1Password. The bot can sign in. It does not see the password, the one-time code, or the card number. A saved card can be used at checkout without a fresh approval. I leave the firm card out if I want a yes on every charge. Vault is the whole account, and it is not on Team Bots. I say the card line if I have the breath. I mention the Team Bot limit only if asked.

It asks before sending. The card shows the action. Allow once, always allow, or deny. An ask-first rule beats an allow rule. Auto Review is a backstop. I still review the work.

Phone calls, and private-network reach such as Tailscale, are coming. I do not build this month's workflow on either one. Voice chat inside the app is a different, shipped control. I separate the two only if someone mixes them up.

## 12. One bot per job — 1:20 (15:00)

This is the roster I run. One bot, one job, the way I would describe an employee. I do not read every line. I name the pattern, then point at two or three. They are not a pile of chats. They message each other and hand work off.

CEO coordinates. Second brain, CLE planner, friction and learning reviews, usage oversight.
Ops is my probate case work: filings drafts, signatures, deadlines, pulse and heartbeats.
Hearings prepares a hearing end to end: notices, service and publication, client prep, proposed orders.
Comms watches Missive and Quo, files documents to matters, and routes follow-ups.
Mailroom triages ECM and inbound mail, and runs the stale-scan.
Leads runs intake, PNCs, and the engagement and deposit chase.
Marketing tracks ads, SEO, and analytics, and drafts social posts. It does not publish unless I say so.
Finance is books, cash, receivables, and tax and close work.
Dev is repos, pull requests, CI, Sentry, and the tool server and skills.
Research does the AI news briefings, legal research in CourtListener, and prep for a talk like this one.
Home is my family calendar, school email, and occasions and gifts. It is not firm work.

Group chats are how that handoff is visible. They are not bots. I say that before anyone counts them as extra staff. Growth is Leads and Marketing. Leadership is Leads, Ops, and Finance.

Then the limit, out loud. On one account there is one computer. Each bot has its own screen. Files and sign-ins are shared. A second bot is not a wall around a client's file. Home is not the firm, and it is still a bot. If it runs on my firm account, it shares that computer.

## 13. What it looks like day to day — 0:40 (15:40)

This is the app on an ordinary day. Ops and CEO are pinned. Under them: Operations, Sales and Marketing, Admin, and Unassigned. Home sits with the group chats, Growth and Leadership. Those two are chats, not bots.

Marketing has the thread open. It drafted the probate posts. I approved them on the card. It scheduled them in Buffer. That is the job working, not a performance.

## 14. How marketplaces are organized — 0:50 (16:30)

I draw the boxes from the outside in. The marketplace is a GitHub repo. Ours is dschnurbusch/schnurbusch-law-plugins. Inside it are plugins. Inside each plugin are the pieces: skills, scripts, templates, and MCP connectors.

I keep that marketplace in GitHub. ChatGPT, and any other tool that can import it, pulls the same plugins. That is why the firm is not maintaining a separate copy in each product. The next slide is the admin screen where I import it.

## 15. Admin controls — 2:00 (18:30)

Business account, not a personal login.

ChatGPT, and I say it is my firm's account, not every plan. The skills marketplace is connected at the admin level. Skills are packaged into plugins that install themselves for everyone in those ChatGPT accounts. The admin work is light.

The screenshot is our Workspace Settings, Marketplaces. The GitHub repo is dschnurbusch/schnurbusch-law-plugins, on main, with 4 plugins. The Add menu is Upload plugin, Create MCP plugin, and Import marketplace, which keeps the plugins updated from GitHub. I point at Import marketplace. That is how the shared library reaches every account.

Grok Bot, from the public Team Bot docs. A Team Bot shares plugins, secrets, skills, and memory. The owner sets those once, and changes reach the people using the bot. Each person signs in for their own connectors, so one person's login is not lent to the team. Admins set connector policy, including turning a connector off for the team. Team memory is shared. A person can keep private notes. If someone wants the finer print: only an owner or manager saves team skills, a key or token uses the bot's credential, and secret values stay hidden from teammates and from the model.

Claude. Business and enterprise plans include admin controls for the organization. I describe the current console. I do not name a switch I have not rechecked.

Then the point of the slide. The playbooks stay in the GitHub library, so I can point another harness at the same procedures. On a business account, an admin keeps the setup current. In my ChatGPT account that means the skills marketplace installs them for everyone. That is true as a category for ChatGPT, Claude, and Grok. Grok Bot is the one I use, because it is easy to use.

## 16. How the work moves — 1:10 (19:40)

I walk the loop once. Comms watches email and text. Every hour it scans and assigns the follow-up to the bot that owns that job: Ops, Hearings, Leads, Mailroom, and the others.

That bot triages, acts, and brings me only what needs a yes. I approve or I follow up. The bot then takes the next action.

Comms comes back and asks whether the job is done. If it is, Comms archives or closes the thread. Then the hour starts again. The arrow back to Comms is that close.

## 17. The routines running my firm — 0:50 (20:30)

These are scheduled jobs, not a wish list. I do not read every line. I name the pattern: Comms runs every hour on weekdays, Ops watches the cases through the day, and the others keep intake, the books, and the AI briefing on a clock.

Comms: Missive inbox sweep, Quo texts and files, and Quo calls and voicemails, hourly on weekdays. The afternoon handoff check confirms the work is done, then closes the thread.

Ops: Probate Pulse each morning. Case heartbeat at noon and 3 PM on weekdays. Court deficiency notices on weekday mornings. Pending applications on Tuesday and Thursday. Creditor-claim deadlines on Monday and Thursday. Servicer notices weekly. Overdue tasks on weekday afternoons.

Leads: a weekday-morning follow-up, with the Monday pipeline sweep and the Thursday chase for engagements and deposits. Twice a month I review why leads were lost.

Finance: categorize and post on Monday, Wednesday, and Friday. Receivables and unbilled work every other week. Trust refund checks on the 1st and the 15th.

Research: AI news for lawyers, weekday mornings. AI, ethics, and changes in Grok Bot.

## 18. What you still own — 2:00 (22:30)

Confidentiality. Rule 1.6. Where the information goes, who can see it, whether it trains a model, how long it is kept. I answer that before a real matter is connected. Missouri numbers the same duty 4-1.6. I say the Missouri number only if the room needs it. Grok Bot stores data and does not offer Legacy Privacy Mode. Training choices follow the account's privacy settings.

Approval rules. Send, file, pay, and delete wait for a person. I put that in the skill and in an ask-first rule. A sentence in a prompt is not the control.

Checking and supervising. Rules 5.3 and 1.1. I read the output. Competence includes understanding the tool. The bot is not a member of the bar. Missouri: 4-5.3 and 4-1.1. ABA Formal Opinion 512 is the longer piece, in the handout. This is a discussion for owners, not an opinion on anyone's stack.

Skill portability. The skills live in one GitHub library for the firm. That is the marketplace we work from. I can point a different harness at it and not rewrite the playbooks. I test the move before I need it. The open Agent Skills format is one way to structure the file.

## 19. First week — 1:10 (23:40)

I read the four. One tool. Two apps. One process written as a skill, into the GitHub library. One routine.

The posture for the week: I manage. I do not do the task myself. The bot runs it once, or on a schedule.

If the job lives in Clio or Filevine, the tool can be Vincent or Lois. If it crosses systems, I pick one general agent and stay there for the week. Whichever tool I pick has to connect. No solid MCP or API, and it does not make the list.

Sample data until I have watched the draft. The worksheet is in the handout, which is separate from these slides.

## 20. Sources — 0:30 (24:10)

I do not read the list. I checked the docs in October 2026, and the current page wins if a control has moved. I point at the handout. Questions.

## If I am long

On the science slides, I say the three names and the status words: released, under review, claimed. I keep the pause and the turn into owning the system. I shorten the Hermes branch story to one sentence. I keep the team line and the note that the newer portal improved sharing. I do not skip the segue, the day-to-day screenshot, the loop, Hermes, the admin slide, or the duties.

## If I am asked

- Can it file with the court? Not unsupervised. I draft, then a person files.
- Does each bot have its own computer? Each has a screen. The computer is one per account.
- Is Auto Review enough? No. It is a backstop. I still read the work.
- Should we run Hermes? It works. It is a lot of work: my computer, or a cloud computer I manage, my own branch, and more technical work to share skills and connectors with a team. A newer portal has improved the sharing. Data control, later prices, and open-source models are fair reasons. Most firms are better off buying a ready-made system.
- Can staff share one setup? On a business account, yes, through admin controls. In my ChatGPT account, admin-level skills install for everyone. On Grok Bot, a Team Bot shares plugins, secrets, skills, and memory. Each person signs in for their own connectors. A shared computer on a personal account is not a permission system.
- Are phone calls or Tailscale ready? I treat both as coming for this room. A team pattern for private networks exists in enterprise material. I do not build the week on either one.

## Stage

- Open `index.html`. Right, Down, Page Down, or Space advances. Left, Up, or Page Up goes back. Home and End jump. F toggles fullscreen.
- I do not sign into a bot on stage. The day-to-day slide is the screenshot.
- The deck and the handout PDF work offline.
- The handout link is in the top bar. No analytics on the page.
