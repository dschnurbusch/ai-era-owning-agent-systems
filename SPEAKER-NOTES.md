# Owning Your AI Agent Systems — speaker notes

About twenty minutes, then questions. The times below are a rehearsal plan, not a measured run. If questions share the half hour, keep the demo to one pass.

Plain talk track for Dan Schnurbusch. Not a transcript. No firm results. Grok Bot claims were checked against public docs on October 27, 2026. Re-read the computer, approvals, and Team Bot pages before November 5.

Demo rule: use an account that has never held client information. Bots on one account share a computer. Do not use the account that runs Research, Ops, Finance, Mailroom, or any other firm bot. The script and the fictional files are in `demo/RUNBOOK.md`.

## 1. Title — 0:30 (0:30)

Say the title. Say your name and that the hour is for firm owners. Point once at the handout. The handout is a separate document. Tell them the demo uses fictional matters.

## 2. What owning means — 1:30 (2:00)

Owning used to sound like running the server. You tried that. It is not what this talk means.

Walk the four parts. Skills and playbooks: how the firm does one job, including the stop. Choice of tools: what you connect, and what stays closed. Your data: what may leave, and where it goes. Who approves what: a person says yes before anything is sent, filed, paid, or deleted.

Those are the parts that make the firm different. A rack of servers is not one of them.

## 3. The range of options — 1:20 (3:20)

Three places. Do not score them.

Built-in agents: Lois in Filevine, Vincent in Clio. A fine starting point when the job already lives on the matter. Ryan McKean is right to favor buying that ready-made when the work does not need to leave the case system. Lois can read the matter and write work back for review. Vincent, in Clio Work, researches and drafts, and with a matter selected can act in Clio Manage. A lawyer still reviews the output.

General agents: Claude, ChatGPT, Grok Bot. This is where the rest of the hour goes, on Grok Bot.

Running your own: Hermes. One slide, next.

Firms can use more than one. The picture is a map.

## 4. Hermes — 2:00 (5:20)

Say this plainly. You built it. It works. It is a lot of work.

Hermes is an extremely powerful desktop agent. Some of what it can do is more useful than what the commercial apps allow. It is built for people who want to assemble the system.

By default it runs only on your computer. You can give it a cloud computer. Then you manage that computer. ChatGPT, Claude, and Grok Bot come with a computer, and they take care of it.

You also piece together memory, web search, telemetry, and the rest. Those services exist. Vendor agents ship them already joined.

You did not like the desktop app's design, so you kept your own branch. Every update meant resolving conflicts with the main branch.

The second cost was the team. Getting skills and connectors out so people could share them, and update them for each other, took more technical work to set up and to maintain. A newer portal has improved that. Say so. It is better than it was. It is still more to run than an admin console.

Fair reasons to take this on: data sovereignty or security, a worry that prices get run up later, and open-source models. You pay with a rougher experience, a harder setup, and the maintenance. Most firms can buy a ready-made system instead.

Do not explain how to install it.

## 5. Grok Bot — 2:00 (7:20)

This is the product you use. Walk the six lines. Do not sell them.

Connect an app and sign in with that provider. The token stays off the computer. The bot calls the tool and does not receive the login. A connected app is available to every bot on the account. Week one is two apps.

Point it at a skill library if you have one. Otherwise there is nothing extra to set up. A skill is the procedure: when to use it, the steps, how to check, and what needs a person. Type / to call one.

Routines are a sentence: when, which bot, what it returns, what it must not send, and what to do if the source is missing. A test run does real work. It can run with the laptop closed.

A cloud computer, with a browser, files, and a terminal. It keeps working after the laptop closes. The next slide is the limit on that computer.

Password vault, or 1Password. The bot can sign in. It does not see the password, the one-time code, or the card number. A saved card can be used at checkout without a fresh approval. Leave the firm card out if you want a yes on every charge. Vault is the whole account, and it is not on Team Bots. Say the card line if you have the breath. Say the Team Bot line only if asked.

It asks before sending. The card shows the action. Allow once, always allow, or deny. An ask-first rule beats an allow rule. Auto Review is a backstop. The lawyer still reviews the work.

Phone calls, and private-network reach such as Tailscale, are coming. Do not build this month's workflow on either one. Voice chat inside the app is a different, shipped control. Mention it only if someone mixes the two up.

## 6. One bot per job — 1:00 (8:20)

Read your list without apologizing: Research, Ops, Finance, Marketing, Leads, Mailroom, Home, and others. It is your shop. The idea is a name, a job, and a boundary. A group chat when someone should see the handoff.

Then the limit, out loud. On one account there is one computer. Each bot has its own screen. Files and sign-ins are shared. A second bot is not a wall around a client's file. Between users, the computers are isolated.

## 7. Admin controls — 2:00 (10:20)

Business account, not a personal login.

ChatGPT, and say it is your firm's account, not every plan. The skills marketplace is connected at the admin level. Skills are packaged into plugins that install themselves for everyone in those ChatGPT accounts. The admin work is light.

Grok Bot, from the public Team Bot docs. A Team Bot shares plugins, secrets, skills, and memory. The owner sets those once, and changes reach the people using the bot. Each person signs in for their own connectors, so one person's login is not lent to the team. Admins set connector policy, including turning a connector off for the team. Team memory is shared. A person can keep private notes. If someone wants the finer print: only an owner or manager saves team skills, a key or token uses the bot's credential, and secret values stay hidden from teammates and from the model.

Claude. Business and enterprise plans include admin controls for the organization. Describe the current console. Do not name a switch you have not rechecked.

Then the point of the slide. On a business account, an admin keeps the setup current. That is true for ChatGPT, Claude, and Grok. Grok Bot is the one you use, because it is easy to use.

## 8. Live demo — 4:30 (14:50)

Say what they are about to see: a few bots, a routine, a skill, a connector. This account has never held a client file. You will not send anything.

Do Calder, from `demo/RUNBOOK.md`. Temporary bot. Fictional estate. Read the draft. If an approval card appears, leave it up.

Pell is optional, and only with extra time. The sender has no authority, so the bot should stop.

If the network stalls, do not troubleshoot. Narrate the same steps from the runbook. Do not sign into firm email, Clio, Filevine, trust, or 1Password.

## 9. What you still own — 2:00 (16:50)

Confidentiality. Rule 1.6. Where the information goes, who can see it, whether it trains a model, how long it is kept. Answer that before a real matter is connected. Missouri numbers the same duty 4-1.6. Say the Missouri number only if the room needs it. Grok Bot stores data and does not offer Legacy Privacy Mode. Training choices follow the account's privacy settings.

Approval rules. Send, file, pay, and delete wait for a person. Put that in the skill and in an ask-first rule. A sentence in a prompt is not the control.

Checking and supervising. Rules 5.3 and 1.1. You read the output. Competence includes understanding the tool. The bot is not a member of the bar. Missouri: 4-5.3 and 4-1.1. ABA Formal Opinion 512 is the longer piece, in the handout. This is a discussion for owners, not an opinion on anyone's stack.

Skill portability. Keep a plain-language copy outside the product. Test it on the next platform before you need to switch. The open Agent Skills format is one way to structure the file.

## 10. First week — 1:10 (18:00)

Read the four. One tool. Two apps. One process written as a skill. One routine.

If the job lives in Clio or Filevine, the tool can be Vincent or Lois. If it crosses systems, pick one general agent and stay there for the week.

Sample data until you have watched the draft. The worksheet is in the handout, which is separate from these slides.

## 11. Sources — 0:30 (18:30)

Do not read the list. Say the docs were checked in October 2026, and that the current page wins if a control has moved. Point at the handout. Questions.

## If you are long

Shorten the branch story on Hermes to one sentence. Keep the team line and the note that the newer portal improved sharing. Do only Calder. Do not skip Hermes, the admin slide, or the duties.

## If you are asked

- Can it file with the court? Not unsupervised. Draft, then a person.
- Does each bot have its own computer? Each has a screen. The computer is one per account.
- Is Auto Review enough? No. It is a backstop. You still read the work.
- Should we run Hermes? It works. It is a lot of work: your computer or a cloud computer you manage, your own branch, and more technical work to share skills and connectors with a team. A newer portal has improved the sharing. Data control, later prices, and open-source models are fair reasons. Most firms are better off buying a ready-made system.
- Can staff share one setup? On a business account, yes, through admin controls. In our ChatGPT account, admin-level skills install for everyone. On Grok Bot, a Team Bot shares plugins, secrets, skills, and memory. Each person signs in for their own connectors. A shared computer on a personal account is not a permission system.
- Are phone calls or Tailscale ready? Treat both as coming for this room. A team pattern for private networks exists in enterprise material. Do not demo it.

## Stage

- Open `index.html`. Right, Down, Page Down, or Space advances. Left, Up, or Page Up goes back. Home and End jump. F toggles fullscreen.
- Demo account signed in. Firm account signed out. Sample folder on the laptop. `demo/RUNBOOK.md` is the script.
- The deck and the handout PDF work offline. The demo bot needs a network.
- The handout link is in the top bar. No analytics on the page.
