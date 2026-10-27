# Live demo runbook

A five-minute stage demo for "Owning Your AI Agent Systems." The room should see a temporary Grok Bot do one fictional estate task, draft a reply, and stop before sending.

Proposed time: four minutes inside a twenty-five-minute talk. If questions are inside the same half hour, do one pass and stop at three.

## Hard rules

- Use a separate Grok Bot account that has never held client information. Bots on one account share a computer, including files and signed-in browser sessions. A demo bot on the firm account could see firm files.
- Do not sign that account into firm email, Clio, Filevine, the trust account, 1Password, or any client system.
- Use only the files in `sample-matters/`. They are fictional. There is no real estate, no real personal representative, and no real court.
- Do not type a password, a one-time code, or a client name into the demo chat.
- Do not press Allow, Always allow, or Send. The point is the stop.
- Phone calls and Tailscale are coming. Do not demo either one.

## The night before

1. On the empty demo account, create one Bot named `Demo Mailroom`. In the first message, tell it the job and ask it to remember: it prepares unsent drafts from files you attach, and it stops when authority is unclear. It never sends.
2. Save `sample-matters/skill-waiting-on-the-client.md` into that account as a skill with the same name, or paste the skill text in the night-before chat and ask the Bot to save it. Confirm you can call it with `/`.
3. Put the `sample-matters` folder on the presenting laptop and on a USB stick. The paper slide in the deck is the backup if the Bot will not load.
4. Open the deck at `index.html?mode=present#s16` and walk the clicker once: Right or Space advances, Left goes back, G returns to the guide, F is fullscreen.
5. Turn on Do Not Disturb. Close firm inboxes and password managers on that laptop.
6. Optional, only on the empty account: connect nothing. The reliable demo uses attachments, not a live inbox. If you want to show the Connect screen, open it and stop there. Do not finish a sign-in to a real firm service.

## The five minutes

Slide: **Watch a fake estate. Send nothing.**

Say that the Bot is temporary, the estate is fictional, and you will not send anything.

1. Open `Demo Mailroom` on the demo account.
2. Attach only these three files:
   - `calder-01-task.md`
   - `calder-02-email.txt`
   - `calder-03-attachment.md`
3. Paste the Calder prompt from `sample-matters/PROMPT.txt`.
4. While it works, narrate the skill: read the task, read the message, read the attachment, ask only for what is still missing, do not send.
5. Read the result out loud. The task wanted two items. The attachment is the signed inventory. The October bank statement is still missing. The draft asks only for that statement.
6. If an approval card appears, leave it. Read the target and the body. Do not approve it.
7. If you have thirty extra seconds, start a new message, attach the two Pell files, and paste the Pell prompt. The Bot should stop. Pat Pell has not shown authority. There should be no document request.

Then advance to **The same run, on paper** only if the live result is thin or the network stalls. If the live result was clear, skip that slide.

## What the room should see

- Calder: a narrower unsent draft, plus the three sources.
- Pell, if you run it: a stop, and no draft that treats Pat as the personal representative.
- You, not pressing send.

## If it breaks

- Bot will not answer: advance to the paper slide and talk through Calder from the slide. Do not troubleshoot on stage.
- Bot wants an app or a sign-in: tell it to use only the attachments. If it persists, go to the paper slide.
- Bot drafts a send, or addresses a real inbox: do not approve. Say so, and use the paper slide. Disconnect that session after you leave the stage.
- Bot answers from a file you did not attach: stop. That is a sign this is not the empty account. End the demo.

## After you walk off

1. Delete the `Demo Mailroom` Bot, or hide it and delete it the same day.
2. Remove the sample files from the demo computer's shared workspace if you let the Bot save them there.
3. Confirm the demo account has no connected apps.
4. Keep the firm account untouched. Deleting a Bot does not remove files or browser sessions from a computer it shared, which is why this demo never runs there.

## Checked against

Public Grok Bot docs as of October 2026: one computer per account, a screen per Bot, skills, routines, approval cards, and Auto Review. Re-read the approvals and computer pages before November 5. Product behavior can change.
