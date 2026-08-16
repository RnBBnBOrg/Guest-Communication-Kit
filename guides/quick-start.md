# Quick-Start Guide

Go from download to a fully customized message set in one sitting. This should take 30-45 minutes.

---

## Step 1: Gather Your Property Details (5 minutes)

Before you touch the templates, write down these details. You'll need them to customize:

- [ ] Property name
- [ ] Full address
- [ ] Check-in and checkout times
- [ ] Entry method and code/instructions
- [ ] Parking instructions
- [ ] Wi-Fi network name and password
- [ ] Key amenities worth mentioning
- [ ] 2-3 nearby highlights (restaurants, activities, landmarks)
- [ ] Your house rules (short version)
- [ ] Checkout tasks for guests (keep it to 4-6 items)

---

## Step 2: Customize Your Templates With AI (15-20 minutes)

This is the fast path.

1. Open `prompts/message-customizer.md`
2. Copy **Prompt 1** (Customize All Templates for Your Property)
3. Paste it into ChatGPT, Claude, or your preferred AI tool
4. Fill in your property details from Step 1
5. Run it — you'll get a complete set of messages tailored to your property in minutes

**Review the output.** Read each message and adjust anything that doesn't sound like you. The AI gets you 80% there; the last 20% is your voice.

---

## Step 3: Set Up Your Messages (10 minutes)

### On Airbnb:
1. Go to **Hosting** > **Inbox** > **Scheduled Messages**
2. Create a scheduled message for each stage:
   - Booking confirmation: Trigger on "Reservation confirmed"
   - Pre-arrival: Trigger "3 days before check-in"
   - Check-in day: Trigger "Day of check-in, 9:00 AM"
   - Mid-stay: Trigger "2 days after check-in" (adjust for stay length)
   - Checkout: Trigger "1 day before checkout, 6:00 PM"
   - Post-stay: Trigger "1 day after checkout"
3. Paste your customized messages into each

### On VRBO:
1. Go to your **Dashboard** > **Inbox** > **Templates**
2. Save each message as a template
3. VRBO's automation is more limited — you may need to send some manually
4. At minimum, automate: booking confirmation, pre-arrival, checkout reminder

### Manual vs. Automated:
| Message | Automate? |
|---------|-----------|
| Booking confirmation | Yes — always |
| Pre-arrival | Yes — always |
| Check-in day | Yes — always |
| Mid-stay check-in | Yes, but review first for longer stays |
| Checkout reminder | Yes — always |
| Post-stay review request | Yes, but only after you've inspected |
| Inquiry responses | No — always manual, each is different |
| Issue handling | No — always manual |

---

## Step 4: Test It (5 minutes)

Before your next guest arrives:

- [ ] Read through each automated message as if you were the guest
- [ ] Verify all details are correct (address, code, Wi-Fi, times)
- [ ] Check that no placeholder text like "[Property Name]" slipped through
- [ ] Send yourself a test message to see how it looks on mobile
- [ ] Confirm the automation triggers are set to the right timing

---

## What to Do Next

**This week:**
- [ ] Set up automations for your next booking
- [ ] Save your issue-handling templates somewhere accessible (you'll need them on short notice)

**This month:**
- [ ] After 2-3 guests, review your messages — are guests asking questions your pre-arrival should have answered?
- [ ] Use **Prompt 3** to create seasonal variations if your area has distinct seasons

**Every quarter:**
- [ ] Update property details (new Wi-Fi password, changed amenities, updated local recommendations)
- [ ] Review your most-used messages — do they still sound like you?
- [ ] Check if any new templates would help (new issue type, new guest demographic)

---

## Troubleshooting

**"The AI output doesn't sound like me."**
Add more voice direction to the prompt: "I'm casual and use short sentences" or "I'm warm but professional — no exclamation points." You can also paste an example of a message you've already sent and ask the AI to match that tone.

**"I'm getting the same questions even with automations."**
Your pre-arrival message might be missing something, or guests aren't reading it. Try reformatting — put the most critical info (entry code, parking) at the very top in bold.

**"A guest responded badly to an automated message."**
Check the timing. An upbeat "Hope you're having a great stay!" hits wrong if they just messaged you about a problem. Review your mid-stay and checkout automations — consider adding a condition to pause them if there's an active conversation.

**"I have multiple properties."**
Run Prompt 1 separately for each property. Save each set of messages in its own folder or as separate automation groups on your platform.
