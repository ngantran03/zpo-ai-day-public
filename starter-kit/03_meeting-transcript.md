# Mid-sprint risk sync, Sprint 2026-S20

Date: Wed 2026-09-30, 16:00-16:10
Attendees: An Tran (PO), Dung Pham (Dev lead), Linh Bui (PO, Safety), Hoa Dang (QC), Giang Vo (Dev), Khoa Ho (Dev), Binh Le (PO)

**[00:00] An:** Okay, quick one. Two days left and we're at about a quarter of the points done. I want to walk through the risky tickets and leave with owners. Dung, start with the stuck-money work?

**[00:25] Dung:** Yeah. SBX-104 is still blocked. We don't have access to the NAPAS reconciliation API yet. I pinged their team on Friday and got nothing back. And SBX-105 can't start until 104 is done, because the notification needs the status from the reconciliation.

**[00:48] An:** So both of those are stuck behind one email.

**[00:52] Dung:** Pretty much. I'll email their partner manager directly and copy our BD contact. I'll do that tomorrow morning.

**[01:05] An:** Thanks. If we don't hear back by Friday, I think we have to carry both into next sprint. Let's decide that on Friday, not now.

**[01:15] An:** Next, SBX-102, the guided support flow for users who can't link a bank. That's 8 points and nobody has touched it since last Tuesday.

**[01:28] Binh:** That's on me. I got pulled into the World Cup campaign. Honestly, there's no way it fits in two days.

**[01:36] An:** Agreed. I'll move SBX-102 to Sprint 21 and let the stakeholders know. I'll do it today, before I log off.

**[01:50] Hoa:** Can I jump in on SBX-109? The duplicate debit bug. Chi pushed a fix this afternoon. I need to run regression on both Android and iOS before we can close it.

**[02:05] An:** How long do you need?

**[02:08] Hoa:** I can finish it by Friday.

**[02:12] An:** Good. That one's Highest priority, so please flag me the minute you find anything.

**[02:20] Linh:** On forced bank linking: the CS macro went live last week. I've got a few days of numbers now on how often agents are using it.

**[02:32] An:** Can you share those in the team channel? It would help the explain-screen discussion.

**[02:38] Linh:** Sure, I'll post them by Friday.

**[02:45] Giang:** Also, a lot of reviews are about face verification failing. Maybe someday we should add tips in the flow, like "take off your glasses".

**[02:55] An:** Good point, but it's not this sprint. Let's park it.

**[03:05] An:** Khoa, SBX-114, gallery scan. It's been sitting in progress since last Friday.

**[03:12] Khoa:** I'm stuck on image cropping for large photos. It's mostly done otherwise.

**[03:18] Giang:** I've done that before on the QR hub prototype. I can pair with you tomorrow.

**[03:24] Khoa:** That would help a lot. Then I can close it by Thursday.

**[03:30] An:** Great, Khoa owns it, Giang helps. Thursday.

**[03:40] Binh:** One more thing. Users complain that fees only show up on the last screen. Should we pull the fee display into this sprint?

**[03:50] An:** Hmm. I'll think about it. Not committing to anything today.

**[04:00] An:** SBX-115, the history filter bug. It's Low and nobody's started it. Anyone want it?

**[04:08] Khoa:** Not with 114 still open.

**[04:12] An:** Fine. Leave it where it is.

**[04:20] An:** Last thing from me. SBX-101, the explain screen before bank linking. Dev is going fine, but design hasn't reviewed the latest copy. I'll book a 30-minute review with design. Let's say by Monday.

**[04:35] Dung:** Monday the 5th?

**[04:37] An:** Yes, by Monday the 5th.

**[04:45] Hoa:** Is SBX-120 in scope? The crash when pasting an account number with spaces. It came in on Monday.

**[04:55] An:** It's Highest, so yes, it stays in. Hoa, it's assigned to you already, right?

**[05:00] Hoa:** Yes. It's in To Do.

**[05:05] An:** Okay. That's everything. Thanks, everyone.
