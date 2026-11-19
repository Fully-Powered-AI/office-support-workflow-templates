# Channel decisions and open questions digest: an example

*Illustrative example with sample data.* Quillbarrow Events is an illustrative 40-person company that produces corporate events. Its client, Client B, is illustrative too, as are the people, suppliers and messages below. Tamsin, the project lead, owns the team channel for Client B's spring gala. On Monday 16 November 2026 she runs the workflow template for the week of Monday 9 to Friday 13 November. She supplies the channel export from her team chat tool, the people list, her settings and the open lines of last week's digest. First come her inputs, in full, then what came back.

## The inputs

### 1. Settings

```
Channel: spring-gala
Period: Monday 9 November 2026 to Friday 13 November 2026, both included
Time zone of the export: GMT
Today: Monday 16 November 2026
Digest owner: Tamsin (project lead)
Wait days: default (3)
Held-back subjects: default (one person's pay, performance, health or conduct)
```

### 2. The channel export from your team chat tool

The default columns: message_id, timestamp, author, thread_id, text.

```
message_id,timestamp,author,thread_id,text
m1000,2026-11-06T16:40,Jonah,,"Venue says load-in can start at 07:00 or 10:00 on the day. Which do we want?"
m1001,2026-11-09T09:05,Tamsin,,"Morning all, how was everyone's weekend?"
m1002,2026-11-09T09:20,Marta,,"The client approved floor plan v3 by email this morning, so that one is settled."
m1003,2026-11-09T09:47,Jonah,m1000,"Picking up the load-in from Friday: I'd go with 07:00 because of the rigging."
m1004,2026-11-09T10:15,Tamsin,m1000,"Agreed, 07:00 load-in. Jonah, please book the crew for 07:00."
m1005,2026-11-09T10:22,Jonah,m1000,"Will do, I'll have the crew booked by Wednesday."
m1006,2026-11-09T11:30,Lucas,,"Does anyone know if the client wants the logo on the stage backdrop or only on the screens?"
m1007,2026-11-09T14:02,Build Bot,,"Reminder: timesheets are due Friday at 17:00."
m1008,2026-11-10T08:55,Priya,,"Caterer B can do the full menu for 250 guests; Caterer A can't do the vegan dishes. I think we should go with B unless anyone objects."
m1009,2026-11-10T09:40,Marta,m1008,"Fine by me."
m1010,2026-11-10T11:05,Lucas,,"Priya, how many guests are confirmed now?"
m1011,2026-11-10T11:20,Priya,m1010,"250 as of this morning."
m1012,2026-11-11T10:05,Lucas,,"Leaning towards a dark blue backdrop rather than white, it photographs better. Thoughts?"
m1013,2026-11-11T16:10,Tamsin,m1008,"Decided: Caterer B. Priya, over to you to confirm the booking."
m1014,2026-11-11T16:25,Priya,m1008,"On it. I'll confirm the booking with Caterer B."
m1015,2026-11-12T09:15,Marta,,"The client asked for a second site visit. Can someone set it up for next week?"
m1016,2026-11-12T09:31,Priya,,"The catering shortlist went to the client yesterday."
m1017,2026-11-12T11:00,Lucas,,"Jonah, what's the most weight the truss can take for the screens?"
m1018,2026-11-12T11:20,Jonah,m1017,"Let me check with the rigger and come back to you by Friday."
m1019,2026-11-12T15:45,Marta,,"We'll sort out the parking permits soon."
m1020,2026-11-12T16:00,Tamsin,,"Marta, can we talk before Friday about Jonah's performance review?"
m1021,2026-11-13T08:30,Priya,,
m1022,2026-11-13T10:40,Jonah,,"Stage drapes: still waiting on the supplier's price, not ordered yet."
```

### 3. The people list

```
author,role
Tamsin,project lead
Marta,account director
Jonah,production manager
Priya,venue and catering coordinator
Lucas,designer
Build Bot,automated
```

### 4. Last week's digest: the open lines, as supplied

```
CHANNEL DIGEST: spring-gala, 2 November 2026 to 6 November 2026
Prepared Monday 9 November 2026 for Tamsin (project lead).

3. Questions still open: 2
Q1. "Has the client approved floor plan v3 yet?" Asked by Tamsin (project
     lead) of Marta (account director). 2 days open at 6 November 2026.
     Source: m0961, 2026-11-04T14:20.
Q2. "Who is collecting the client's signage on the day?" Asked by Priya
     (venue and catering coordinator) of the channel. 1 day open at
     6 November 2026. Source: m0974, 2026-11-05T13:10.

4. Promises with an owner and a date: 1
P1. Send the catering shortlist to the client. Owner: Priya (venue and
     catering coordinator). Due: Thursday 12 November 2026 ("by the 12th").
     Status: Open. Source: m0968, 2026-11-05T09:02.

5. Promises missing an owner or a date: 1
P2. Order the stage drapes. Owner: Jonah (production manager). Due: DATE
     NOT GIVEN ("once I have the price"). Status: Open. Source: m0980,
     2026-11-06T11:45.

6. Carried from the last digest: None
```

## What came back

```
CHANNEL DIGEST: spring-gala, 9 November 2026 to 13 November 2026
Prepared Monday 16 November 2026 for Tamsin (project lead). Export: 23 rows.
Read: 20 messages, 2026-11-09T09:05 to 2026-11-13T10:40. Set aside: 1
outside the period, 1 with empty text, 1 from automated senders. Times as in
the export (GMT). Authors not on the people list: none. Questions asked and
answered within the period: 1 (not listed). Last digest: Monday 9 November
2026.

To raise: 6
1. Q1: the logo question has been open 4 days and was asked of the channel.
   Find out who will answer it.
2. P1: Jonah's crew booking was due Wednesday 11 November 2026 and no
   message says it is done. Ask Jonah whether the crew is booked.
3. P3: Priya's confirmation of the Caterer B booking has no date. Ask Priya
   by when.
4. P4: the parking permits have no owner and no date. Ask Marta, who wrote
   the message, who will do it and by when.
5. Last Q2: the signage question has been open 8 days with no message this
   period. Find out who will collect the signage.
6. Last P2: the stage drapes are still not ordered and still have no date.
   Ask Jonah by when.

1. Decisions made: 3
D1. Floor plan v3 is approved.
     Decided by: the client; reported by Marta (account director).
     Source: m1002, 2026-11-09T09:20.
D2. Load-in on the day starts at 07:00.
     Decided by: Tamsin (project lead).
     Proposed in m1003. In a thread started before the period.
     Source: m1004, 2026-11-09T10:15.
D3. Caterer B does the catering.
     Decided by: Tamsin (project lead).
     Proposed in m1008. Source: m1013, 2026-11-11T16:10.

2. Not counted as decisions: 1
- "Leaning towards a dark blue backdrop rather than white, it photographs
  better. Thoughts?" Lucas (designer). Why not: "leaning towards" and
  "thoughts?", and no later message settles it. Source: m1012,
  2026-11-11T10:05.

3. Questions still open: 3
Q1. "Does anyone know if the client wants the logo on the stage backdrop or
     only on the screens?" Asked by Lucas (designer) of the channel. 4 days
     open at 13 November 2026. Source: m1006, 2026-11-09T11:30.
Q2. "Can someone set it up for next week?" [it: the client's second site
     visit]. Asked by Marta (account director) of the channel. 1 day open
     at 13 November 2026. Source: m1015, 2026-11-12T09:15.
Q3. "What's the most weight the truss can take for the screens?" Asked by
     Lucas (designer) of Jonah (production manager). 1 day open at
     13 November 2026. Partial reply: "Let me check with the rigger and
     come back to you by Friday", Jonah, m1018. Source: m1017,
     2026-11-12T11:00.

4. Promises with an owner and a date: 2
P1. Book the crew for the 07:00 load-in. Owner: Jonah (production manager).
     Due: Wednesday 11 November 2026 ("by Wednesday"). Status: Date passed,
     no message says it is done. Source: m1004, 2026-11-09T10:15; m1005,
     2026-11-09T10:22.
P2. Check the truss's weight limit with the rigger and answer Lucas. Owner:
     Jonah (production manager). Due: Friday 13 November 2026 ("by
     Friday"). Status: Open. Source: m1018, 2026-11-12T11:20.

5. Promises missing an owner or a date: 2
P3. Confirm the booking with Caterer B. Owner: Priya (venue and catering
     coordinator). Due: DATE NOT GIVEN (no date in the message). Status:
     Open. Source: m1013, 2026-11-11T16:10; m1014, 2026-11-11T16:25.
P4. Sort out the parking permits. Owner: OWNER NOT GIVEN ("We"). Due: DATE
     NOT GIVEN ("soon"). Status: Open. Source: m1019, 2026-11-12T15:45.

6. Carried from the last digest: 4
- Last Q1. "Has the client approved floor plan v3 yet?" Asked by Tamsin of
  Marta. Now: Answered: the client approved it, as Marta reports (m1002,
  2026-11-09T09:20; see D1).
- Last Q2. "Who is collecting the client's signage on the day?" Asked by
  Priya of the channel. Now: Still open, no message this period. 8 days
  open at 13 November 2026.
- Last P1. Send the catering shortlist to the client. Owner: Priya. Due
  Thursday 12 November 2026. Now: Reported done: Priya says it went to the
  client the day before her message (m1016, 2026-11-12T09:31).
- Last P2. Order the stage drapes. Owner: Jonah. Due: DATE NOT GIVEN. Now: Still
  open: Jonah says they are not ordered yet, waiting on the supplier's price
  (m1022, 2026-11-13T10:40).

Held back: 1 message on a personal matter, left out.

Draft for Tamsin. Nothing has been posted, nobody has been assigned and
nothing has been decided.
```

## How the figures were found

- **Rows:** 23 in the export. Set aside: m1000 (6 November, before the period), m1021 (empty text) and m1007 (Build Bot, automated). 23 − 3 = 20 messages read, from m1001 at 09:05 on 9 November to m1022 at 10:40 on 13 November.
- **Answered within the period:** Lucas's question on guest numbers (m1010), answered by Priya (m1011). Jonah's m1003 states a preference, not a question, and is the proposal behind D2.
- **Days open,** counted to Friday 13 November: Q1 asked on 9 November, 4 days; Q2 and Q3 asked on 12 November, 1 day each; last week's Q2 first asked on 5 November, 8 days.
- **Dates:** "by Wednesday", written on Monday 9 November, is Wednesday 11 November, two days before the period ends, so P1's date has passed. "By Friday", written on Thursday 12 November, is Friday 13 November, the period's last day, so P2 is Open.
- **To raise:** Q1 (4 days, at or over the default 3); P1 (date passed); P3 and P4 (missing a date, and for P4 an owner); last week's Q2 and P2 (still open). Q2 and Q3 have been open 1 day each and are not raised. 6 in all.
- **Not listed:** the greeting (m1001), "Fine by me" (m1009), and the message on one person's performance review (m1020), which appears only as the count under "Held back".
