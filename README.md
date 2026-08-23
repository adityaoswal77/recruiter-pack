RATCH DESIGN EXERCISE 
Aditya Oswal
This is a repo with my submission for the assignment


-------- 

Primary actor: the recruiter.
Open code.html in any browser. 
Typepace: Inter, Helvetica Neue, Arial.
Click the "States" button in the bottom right to jump to any state. Also supports (url switch) ?state=score-got-it-wrong
Decision buttons are the sticky bar at the bottom of the screen.
Three views in the top bar: Review, Pipeline, The role.

Click the "States" button in the bottom right to jump to any state.
Three tabs at the top: Review, Pipeline, The role.

I designed this for the recruiter. The pack under review is this role. All the names, quotes and scores are made up.


THE IDEA

The recruiter is deciding one thing: does this person get an interview.

If they say yes to a weak candidate, the interview catches it. If they say no to a strong one, nobody ever finds out. So saying no is the dangerous one, and saying no is what a busy person does when a score looks low.

So: saying yes is one click. Saying no asks for a reason. And if the evidence disagrees with the score, saying no asks twice.

The score is next to the candidate, not above them. If you put a verdict at the top, people stop reading and start rubber-stamping.

Open any row and it shows two things: what the job needs, and the hiring manager saying it on the intake call. If nothing was said, the row says "no source" and you can delete it. Recruiters work roles they do not own, so they need a way to check a claim instead of just believing it.


1. WHAT WORKS, AND WHAT DOES NOT

Works: all 21 states, every expander, the reason forms and their validation, deleting a claim with no source, undo (which disappears once the person has actually been emailed), the lock when someone else has the pack, and the queue
that hands you the next candidate after you decide.

Does not: nothing is saved and nothing is real. The data is typed into the file. Buttons like Retry and Ping show a message saying what they would do in an ideal world. 


2. WHAT I WOULD NEED FROM ENGINEERING

- better ai model (LOL) and allowing them to review each others claim
- A saved record of each decision: what, why, who, when, and the score at the time. This is what stops the reasoning vanishing later.
- Read status per file, so a half-broken upload can say which half is missing.
- model learning from deleted, rejected claims to make better decisions.
- Tracking which overrides became good hires, similar to the bad, the good hires can help decide what the model can learn better.


3. WHAT I LEFT OUT

- The hiring manager and candidate views. drawback is the hiring manager only sees what the recruiter passed on, and the candidate never sees any of this uxui.

- Bulk actions and comparing candidates side by side. bulk delete is literally against what we are trying to do. 

- The resume and portfolio themselves. The links are here. The pack is the argument about the person, not the person's files.

- Editing the JD. The role tab is read-only currently. 
