# Trial of the channel decisions and open questions digest

- **Product:** Claude, run in Claude Code

Model: Claude Sonnet 5.5 (model ID claude-sonnet-5-5). Date: 2026-11-19.

The inputs are the invented example in [example.md](example.md): the settings, the channel export of 23 messages, the people list and the open lines of last week's digest. No client data was used. The run was made by a model that did not write the template. It read the template and only the inputs of the example, followed the instruction block and the output format, and produced the digest below. Only then did it read the example's output and the reviewer checklist and compare.

## What came out

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
2. P1: Jonah's crew booking was due Wednesday 11 November 2026 and no message
   says it is done. Ask Jonah whether the crew is booked.
3. P3: Priya's confirmation of the Caterer B booking has no date. Ask Priya
   by when.
4. P4: the parking permits have no owner and no date. Ask Marta, who wrote
   the message, who will do them and by when.
5. Last Q2: the signage question has had no message this period (8 days
   open). Find out who will collect the signage.
6. Last P2: the stage drapes are not ordered and still have no date. Ask
   Jonah by when.

1. Decisions made: 3
D1. The client approved floor plan v3.
     Decided by: the client; reported by Marta (account director).
     Source: m1002, 2026-11-09T09:20.
D2. Load-in on the day starts at 07:00.
     Decided by: Tamsin (project lead).
     Proposed in m1003. In a thread started before the period.
     Source: m1004, 2026-11-09T10:15; m1003, 2026-11-09T09:47.
D3. Caterer B is chosen.
     Decided by: Tamsin (project lead).
     Proposed in m1008. Source: m1013, 2026-11-11T16:10.

2. Not counted as decisions: 1
- "Leaning towards a dark blue backdrop rather than white, it photographs
  better. Thoughts?" Lucas (designer). Why not: "leaning towards" and
  "thoughts?", and nothing later settles it. Source: m1012,
  2026-11-11T10:05.

3. Questions still open: 3
Q1. "Does anyone know if the client wants the logo on the stage backdrop or
     only on the screens?" Asked by Lucas (designer) of the channel. 4 days
     open at 13 November 2026. Source: m1006, 2026-11-09T11:30.
Q2. "The client asked for a second site visit. Can someone set it up for next
     week?" Asked by Marta (account director) of the channel. 1 day open at
     13 November 2026. Source: m1015, 2026-11-12T09:15.
Q3. "Jonah, what's the most weight the truss can take for the screens?" Asked
     by Lucas (designer) of Jonah (production manager). 1 day open at
     13 November 2026. Partial reply: "Let me check with the rigger and come
     back to you by Friday", Jonah, m1018. Source: m1017, 2026-11-12T11:00.

4. Promises with an owner and a date: 2
P1. Book the crew for the 07:00 load-in. Owner: Jonah (production manager).
     Due: Wednesday 11 November 2026 ("by Wednesday"). Status: Date passed,
     no message says it is done. Source: m1005, 2026-11-09T10:22; m1004,
     2026-11-09T10:15.
P2. Check the truss weight limit with the rigger and come back to Lucas.
     Owner: Jonah (production manager). Due: Friday 13 November 2026 ("by
     Friday"). Status: Open. Source: m1018, 2026-11-12T11:20.

5. Promises missing an owner or a date: 2
P3. Confirm the booking with Caterer B. Owner: Priya (venue and catering
     coordinator). Due: DATE NOT GIVEN (no date in the message). Status:
     Open. Source: m1014, 2026-11-11T16:25; m1013, 2026-11-11T16:10.
P4. Sort out the parking permits. Owner: OWNER NOT GIVEN ("We'll"). Due: DATE
     NOT GIVEN ("soon"). Status: Open. Source: m1019, 2026-11-12T15:45.

6. Carried from the last digest: 4
- Last Q1. "Has the client approved floor plan v3 yet?" Asked by Tamsin of
  Marta. Now: Answered, see D1 (m1002, 2026-11-09T09:20).
- Last Q2. "Who is collecting the client's signage on the day?" Asked by
  Priya of the channel. Now: Still open, no message this period. 8 days open
  at 13 November 2026.
- Last P1. Send the catering shortlist to the client. Owner: Priya. Due:
  Thursday 12 November 2026. Now: Reported done, Priya says it went to the
  client yesterday (m1016, 2026-11-12T09:31).
- Last P2. Order the stage drapes. Owner: Jonah. Due: DATE NOT GIVEN ("once I
  have the price"). Now: Still open, Jonah says they are not ordered yet
  (m1022, 2026-11-13T10:40).

Held back: 1 message on a personal matter, left out.

Draft for Tamsin. Nothing has been posted, nobody has been assigned and
nothing has been decided.
```

## What was observed

- Every required part was produced, in the order and wording of the format. The run stopped for nothing: the headers matched, no message id repeated, the period had both dates, and no message carried an instruction to the assistant.
- The counts matched the example's: 23 rows, 20 read, 3 set aside, 1 held back, 3 decisions, 1 proposal not counted, 3 open questions, 2 promises with an owner and a date, 2 missing one, 4 carried, 6 under "To raise". The dates counted the same way ("by Wednesday" written on Monday 9 November is Wednesday 11 November; "by Friday" written on Thursday 12 November is Friday 13 November).
- Differences from the published example were in wording only. The example's Q2 quotes only "Can someone set it up for next week?" and adds a parenthesis about the site visit; this run quoted the whole of the message's two sentences. The example's Q3 quote drops "Jonah," and capitalises "What's"; this run kept it as written. The example's D3 reads "Caterer B does the catering"; this run reads "Caterer B is chosen". Sources for lines that rest on two messages were cited in a different order. The example's Last Q1 line says "the client approved it, as Marta reports"; this run said "Answered, see D1". The "To raise" lines were worded differently but named the same items.
- Facts not in the inputs: none in this run's output. In the example's published page, the paragraph after "How the figures were found" says Tamsin asked Jonah and Marta questions, took two questions to a client meeting on Tuesday and shared the digest in the channel herself. None of that is in the inputs; it is narrative added to the example. The example's introduction also names a company, a client label and a headcount that the template's inputs do not contain; they are context only and the digest does not depend on them.
- The example's output follows the template. No line in it rests on a fact missing from the inputs.

Where the template left room to guess:

1. A question asked before the period and answered inside it (m1000, the load-in question) is neither listed nor clearly counted. The template says a message before the period creates no line, but not whether the header's "asked and answered within the period" count includes it. This run did not count it, as the example did.
2. A decision can be both "Proposed in" an earlier message and "In a thread started before the period" (D2). The format shows these as alternatives with slashes; both were used here, as in the example.
3. Promise numbers: the format uses P[n] in section 4 and in section 5, and does not say whether the numbering runs on or restarts. This run ran it on, so "To raise" can name P3 without ambiguity.
4. "Date passed" needs the due date to be before the period's last date. A promise due on the last date itself stays Open even though nobody has reported it done by the end of that day. That is what the rule says, but a reader may expect it to be flagged.
5. The "Read" count includes a message that is then held back (m1020). The template does say every other row is read, but the header line does not make clear that a held-back message is among the messages read.
6. Relative words inside a message ("yesterday" in m1016) are not covered by the date rule, which only covers days and dates written to look forward. This run resolved it as the day before the message and said so in plain words.
7. For the line that quotes a request ("Can someone set it up for next week?"), the template allows "quoted or shortened" but a shortened quote can lose its subject. The reader cannot tell what "it" is without the earlier sentence.
8. The instruction block contains the bracketed placeholders "[your wait days]" and "[your held-back subjects]" literally, with defaults. Pasted as is, an assistant must infer that a bracket is a setting and its default applies.
9. "To raise" line text is left to the assistant ("what the digest owner would need to find out"); two runs will word it differently while naming the same items.

The template's own version notes still say it has not been tried on its example, and its acceptance tests are marked as not run. This single run does not run those twelve tests; it only tried the one example, which contains no header mismatch, no planted instruction, no ranking request and no direct-message case.

Changed after the run recorded above, and not run again. The output and the observations above are as recorded and describe the template and the example as they stood at the run:

- **The example** no longer has the narrative paragraph after "How the figures were found" that the observations mention (Tamsin asking questions, a client meeting, sharing the digest herself); the published example ends with the "Not listed" bullet and adds no fact beyond the inputs. Its Q2 line now gives the subject of the shortened quote in square brackets after the quote, "[it: the client's second site visit]", instead of in a parenthesis; the example's facts, counts and order are otherwise unchanged.
- **The template and its pasted instructions** now answer gaps 1, 2, 3, 5 and 6 above. Gap 1 and 5: the header's count of questions answered inside the period and the rule that held-back messages are among those read are stated in the procedure and the pasted instructions. Gap 2: a decision may carry both "Proposed in" and "In a thread started before the period". Gap 3: promises are numbered P1, P2 and so on across sections 4 and 5 without restarting; this is now a sentence in the procedure and the pasted instructions, not a note inside the output format. Gap 6: "yesterday" and other backward words are the day before the message's date, said in plain words. The pasted instructions also now give "Wait days: 3" and the default held-back subjects in plain words instead of bracketed placeholders, and carry three stop conditions the procedure already had: no message inside the period, more than one channel in the export, and timestamps that cannot be read as dates. Step 10 now asks for a source on every line of sections 1 to 5 and says how a carried line in section 6 is cited.
- **The version notes** now say the template and the example were changed after the run and that it has not been run again; the profile's statement of what has been checked matches. The acceptance tests are still marked as not run.
- **A later round of small edits** (after review, also not run): the output format now puts the note naming the subject of a shortened question straight after the quote, as the procedure and the example already did; the pasted instructions now carry the people-list rule (an author not on the list is read and shown as "(role not listed)"), the time-zone setting and the wording "In a thread started before the period", all of which the procedure and output format already had. The profile's wording was adjusted and its statement of what has been checked now says the template and example were changed after the run. No recorded output or observation above was altered, and the template has still not been run again.
- **Left as they are:** gap 4 (a promise due on the period's last date stays Open and is not flagged; the profile now says the digest reads to the period's last date only) and gap 9 (the wording of the "To raise" lines is left to the assistant). Gap 7 is answered only in part, by one sentence in the procedure and the pasted instructions (a shortened quote that loses its subject gets the subject in square brackets after it), and gap 8 only by the plain defaults named above; neither was tried in a run.
