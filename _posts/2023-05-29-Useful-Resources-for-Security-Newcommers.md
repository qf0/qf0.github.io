---
layout: post
title: "Useful Resources for Security Newcommers"
date: 2023-05-29
---

Career advice:

Parisa Tabriz

Chris Palmer

Foundational books and general infosec references:
Counterhack Reloaded - http://www.amazon.com/Counter-Hack-Reloaded-Step-Step/dp/0131481045

Hacking exposed - http://www.hackingexposed.com/

Phrack ‘zine and back catalog - www.phrack.com

[Advanced] Silence on the Wire by Michal Zalewski

Security Engineering

Security Engineering by Ross Anderso

Web Application Security

Tangled Web by Michal Zalewski

Web App Hacker’s Handbook by Dafydd Stuttard and Marcus Pinto

Operating System Security

Mac Hacker’s handbook by Charlie Miller, Dino Dai Zovi

Cryptography

Handbook of Applied Cryptography by Menezes et al.

Cryptography Engineering by Niels Ferguson, Bruce Schneier, Tadayoshi Kohno

Applied Cryptography by Bruce Schneier

Reverse Engineering

Practical Reverse Engineering by Bruce Dang

Secrets of Reversing by Eldad Eilam

Assessments / Pen-Testing / Exploitation

[Assessment] The Art of Software Security Assessment by Mark dowd, John McDonald, Justin Schuh

[Exploitation] Hacking: Art of Exploitation by Jon Erickson

[Pentesting/Intro] Network Security Assessment by Chris McNab

[Malware] Practical Malware Analysis by Michael Sikorski, Andrew Honig

[Pentesting] The Hacker Playbook 2: Practical Guide to Penetration testing by Peter Kim

[Exploitation] Shellcoders Handbook  by Chris Anley

Scripting/Coding

[Python] Violent Python: A cookbook for Hackers, Forensic Analysts, Penetration testers and Security Engineers by TJ O’Conor

[Python] Dive into Python and Dive into Python 3 [free e-books and exercises]

[Algorithms] Introduction to Algorithms by Thomas Cormen, Charles Leiserson, Ronald Rivest, Clifford Stein

Programming Pearls by Jon Bentley

Detection strategies
https://www.sans.org/reading-room/whitepapers/detection

Well Known CTFs
CSAW CTF: https://ctf.isis.poly.edu/

Plaid CTF: http://play.plaidctf.com/

Defcon CTF: https://www.defcon.org/html/links/dc-ctf.html

Hands on Security Challenges
http://www.root-me.org/?lang=en

http://www.crackmes.de/

http://www.malware-traffic-analysis.net/

http://contagiodump.blogspot.com/2013/04/collection-of-pcap-files-from-malware.html

Training Courses
http://www.sans.org/course/intrusion-detection-in-depth

https://www.sans.org/course/hacker-techniques-exploits-incident-handling

https://www.sans.org/media/security-training/courses/sec_essentials.php

Network fundamentals and protocols
Various layers of the OSI (http://en.wikipedia.org/wiki/OSI_model) or IP (http://en.wikipedia.org/wiki/Internet_protocol_suite) models

DHCP, DNS, IP Suite, HTTP, etc. (there are too many protocols to list that are interesting or important)

Examples:

HTTP: http://www.tutorialspoint.com/http/

DNS: https://technet.microsoft.com/en-us/library/cc775637(v=ws.10).aspx


Identifying malware on the network + IDS signatures:
https://lists.emergingthreats.net/mailman/listinfo/emerging-sigs

Malware Analysis:
https://zeltser.com/mastering-4-stages-of-malware-analysis/

https://www.virustotal.com/

https://www.blackhat.com/docs/us-15/materials/us-15-MarquisBoire-Big-Game-Hunting-The-Peculiarities-Of-Nation-State-Malware-Research.pdf

Cryptography:
http://www.cs.umd.edu/~waa/414-F11/IntroToCrypto.pdf

http://www.amazon.com/Applied-Cryptography-Protocols-Algorithms-Source/dp/0471117099

http://www.sans.edu/research/security-laboratory/article/hash-functions

Host forensics
http://windowsir.blogspot.com/

Some miscellaneous topic agnostic resources:
https://github.com/kbandla/APTnotes

https://www.reddit.com/r/netsec/wiki/start

http://www.covert.io/security-datascience-papers/

Some analysis of common mass malware and current events:
http://malware.dontneedcoffee.com/

https://www.fireeye.com/blog.html

http://contagiodump.blogspot.com/

Tools:
http://holisticinfosec.blogspot.com/

Meetups and groups:
CitySec: https://www.reddit.com/r/netsec/wiki/meetups/citysec

Local Defcon: https://www.defcon.org/html/defcon-groups/dc-groups-index.html

BSides: http://www.securitybsides.com/w/page/12194156/FrontPage

Amazon loop interview prep: https://www.youtube.com/watch?v=Vh20A2TMVKE

Amazon phone screen prep: https://www.youtube.com/watch?v=A-SzF5xYJPY

Meta offical Security role prep: 

Product Security Tech Screen Interview Prep
Technical skills aren’t the same as interview skills, so even the most experienced
engineers need to prepare and practice to do well in an interview. For example, it’s
difficult for interviewers to get a clear signal on coding ability from someone who hasn’t
practiced solving new problems under time constraints. This can make someone who’s
simply under-prepared look under-qualified. This guide can help you plan, practice, and
prepare for your initial technical screen at Facebook.
What You’ll Find in This Guide:
What We Look For
How to Prepare
How to Approach Problems During Your Interview
What to Practice: An Example Tech Screen Study
WHAT WE LOOK FOR
Coding
Communication. Are you asking for requirements and clarity when necessary, or are
you just diving into the code? Your initial tech screen should be a conversation, so don’t
forget to ask questions.
Problem solving. We’re evaluating how you comprehend and explain complex ideas.
Are you providing the reasoning behind a particular solution? Developing and
comparing multiple solutions? Using appropriate data structures? Speaking about space
and time complexity? Optimizing your solution?
Coding. Can you convert solutions to executable code? Is the code organized and does it
capture the right logical structure? Do you notice edge cases and failure scenarios?
Verification. Are you considering a reasonable number of test cases or coming up with a
good argument for why your code is correct? If your solution has bugs, are you able to
walk through your own logic to find them and explain what the code is doing?
Security
Be able to identify security flaws via code review and demonstrate deep understanding
of the issues found. We want you to be able to explain your approach to code review
and explain the risk of each issue and how the issue might get exploited. Suggest fixes
with practical security and defense-in-depth in mind. Here is a read on how Facebook

Designs Security for Billions (https://about.fb.com/news/2019/01/designing-security-
for-billions/)

Topics that may be covered:
Web Security
OWASP Top 10
In depth understand of SOP (Same Origin Policy)
CSRF
XSS (Reflected and DOM)
SQL injection
HTTPS
Cryptography:
Encryption at rest and in transit
Symmetric encryption and its applications
PublicKeyCryptography and its applications
Credentials (password) storage and Hashing
Native Security
Typical native code (C++) issues such as buffer overflows and how they’re exploited
Use-after-free
Integer overflows
Leaking uninitiated memory
Memory corruption
Mobile Security
OWASP Mobile Top 10
Platform security model and promises
Access to resources and IPC from security perspective (ie. Data storage)
Mobile app interactions (Binder/Intents or URIs)
What should you focus on when writing secure apps
Development lifecycle and eco-system (Google Play/AppStore)
HOW TO PREPARE
How to prepare for a security engineer interview tips

(https://medium.com/@eraymitrani/how-to-prepare-for-a-security-engineer-interview-
6cf1d84de22f)

Interviewers can only assess your skills and abilities based on what you show them
during your interview, so it’s important to plan and prepare to best showcase your
strengths. In addition to the preparation guidance below, this video:
https://vimeo.com/357608978 (password: fbprep) will give you an example of what to
expect during the coding portion of the technical screen.

Before you practice, plan!
Be honest with yourself—only you know how much prep time you’ll need. Make the
most of your prep time by following these steps to plan your approach with your
recruiter before you start practicing. Schedule time to study and practice.
For the security practical portion, you should be able to spot security issues in a timely
manner and be able to explain the vulnerabilities and how to mitigate. Brush up on the
security topics listed above if you need to. Revision and repetition will strengthen your
understanding of core concepts.
Use key practice strategies to practice effectively.
Reading through sample questions, recognizing concepts, and having a vague
understanding of these concepts won’t be enough to help you shine. You need to
practice! Make sure you’re setting your practice sessions up for success by following
these tips from engineers who’ve been through the process.
Practice coding the way you’ll code during your tech screen. Use CoderPad.io if your
interview is via phone or video call, or use a whiteboard or pen and paper if your
interview will be in person. Check with your recruiter if you’re not sure which format
you’ll use.
Set a time constraint when you practice problems. In your tech screen, you’ll be asked
to solve 1-2 coding problems in under 30 minutes. Code in your strongest language.
Provide the most efficient solution and find and fix the bugs yourself. Practice talking
through the problem space and possible solutions before you dive in and talk through
your decisions out loud as you code. Interviewers will be evaluating your thought
process as well as your coding abilities. Explaining your decisions as you code is crucial
to helping them understand your choices. The more you practice this, the more natural
it will feel during the interview.
Understand the types of problems you may encounter
Practice a variety of different problems—and understand why we ask them—so you’re
prepared to solve them during your interview.
Don’t be surprised if the questions sound contrived. Problems may be different than
what you’re probably tackling in a day-to-day job. We won’t ask a “puzzle” question, but
questions may be different than real-world questions because they need to be
described and solved in 10-20 minutes.
Problems may assess the depth of your knowledge and your versatility. For example,
your interviewer might ask you to solve a problem any way you want. Then, they could
add constraints on the running or space characteristics and ask you to solve it again.
Problems may focus on edge cases. You might be asked to parse some data format or
mini language. Your answers demonstrate your ability to handle multiple states in your
head.
Problems may test how well you know how things work under the hood. For example,
you might be asked to implement well-known library functions.

Decide what resources you’ll use to prepare
It’s easy to be overwhelmed by the number of online resources or the detail in an entire
theoretical algorithms book. Here are some sites that our engineers found helpful when
preparing for their coding interviews
Top sites for practice problems from Facebook:
Facebook Sample Interview Problems and Solutions
Leet Code
Video prep guides for tech interviews:
Cracking the Facebook Coding Interview: The Approach https://vimeo.com/157480836
Cracking the Facebook Coding Interview: Problem Walk-through
https://vimeo.com/158532188
The password is FB_IPS. Portions of the videos that cover soft skills tips may be more
relevant for preparing for your onsite interview than for preparing for your initial tech
screen.
Example tech screen study list:
See exercises below for an example list compiled from Facebook’s engineering team you
can use as a starting point to help you prepare. Feel free to tailor it to your specific
practice needs.
HOW TO APPROACH PROBLEMS DURING YOUR INTERVIEW
Before you code:
Ask clarifying questions. Talk through the problem and ask follow-up questions to make
sure you understand the exact problem you’re trying to solve before you jump into
building the solution.
Let us know if you’ve seen the problem previously. That will help us understand your
context.
Present multiple potential solutions, if possible. Talk through which solution you’re
choosing and why
While you code:
Ask questions and plan your solution rather than jumping right into implementation.
Explain your decisions to the interviewer and be open to feedback. It’s totally fine to
present a rough solution in the beginning and iterate as you go.
Defensive coding is important, but don’t focus on details to the detriment of the overall
solution. If you’re not sure if a given error handling or edge case is important, ask the
interviewer.
Be flexible. Some problems have elegant solutions, and some must be brute forced. If
you get stuck, just describe your best approach and ask the interviewer if you should go
that route. It’s much better to have non-optimal but working code than just an idea with
nothing written down.

Be open to changing your mind if you think you’ve started your solution in the wrong
way and pay attention to whether the interviewer is trying to guide you to a better
approach. Take the interviewer’s hints to improve your code.
If you can’t remember the order or arguments to a function or its name, just say so,
leave a placeholder and move on. Don’t get hunt up on syntax.
Iterate rather than immediately trying to jump to the clever solution. If you can’t explain
your concept clearly in five minutes, it’s probably too complex.

Consider (and be prepared to talk about):
Different algorithms and algorithmic techniques, such as sorting, divide-and-conquer,
recursion, etc.
Data structures, particularly those used most often (array, stack/queue,
hashset/hashmap/hashtable/dictionary, heap, graph, etc.)
O memory constraints on the complexity of the algorithm you’re writing and its running
time as expressed by big-O notation.
Generally, avoid solutions with lots of edge cases or huge if/else if/else blocks, in most
cases. Deciding between iteration and recursion can be an important step.
WHAT TO PRACTICE: An Example Tech Screen Study List
Everyone could use a refresher in at least one core area! Before your initial tech screen,
brush up on CS fundamentals— especially algorithms, data structures, object-oriented
design, and design patterns in general. Review foundational techniques—recursion,
graph theory, combinatorial problems, and so on.
Looking for more detailed guidance on what to review for your tech screen? The
exercises below have been helpful for many engineers preparing for a Facebook tech
screen and can assist you in solidifying your understanding of data structures and
algorithms. Feel free to use this list as a starting point and tailor it to suit your areas of
need.

Exercises
Overview:
Each exercise could take you up to one hour.
These solutions are written in Java, but you will be able to use your language of
preference in an interview.
Remember how to analyze how “good” your solution is: how long does it take for your
solution to complete? Watch this video to get familiar with Big O Notation.
Note: These exercises assume you have knowledge in coding but not necessarily
knowledge of binary trees, sorting algorithms, or related concepts.

Topic 1 | Arrays & Strings
Exercises:
A Very Big Sum (Warm-up, learning how to use HackerRank)
Designer PDF Viewer
Left Rotation
Topic 2 | Lists
Pre-work: If you need to familiarize yourself with how lists work, watch this video
Exercises:
Insert a Node at a Position Given in a List
Cycle Detection

Topic 3 | Stacks & Queues
Pre-work: If you need a refresher, take a look at this video
https://www.youtube.com/watch?v=wjI1WNcIntg&feature=youtu.be
Exercises
Balanced Brackets
Queue Using Two Stacks
Topic 4 | Hash & Maps
Pre-work: If you need a refresher, take a look at this video
Exercises
Ice Cream Parlor
Colorful Number (This one might be challenging. Remember, if you get stuck, refer to
our proposed solution.)
Topic 5 | Sorting Algorithms
Pre-work: If you need a refresher take a look at this video: Merge Sort
Exercises:
Insertion Sort part 2
Quicksort part 2

Topic 6 | Graphs (BFS & DFS)
Theory: Watch this video to understand what a graph is and how to traverse it
Exercises:
Breath First Search
Snakes and Ladders
Topic 7 | Recursion
Theory: Watch this video to review concepts on recursion
Exercises:
Fibonacci Numbers
Solutions: All solutions are available in this public repository:
https://github.com/lolapriego/coursework
