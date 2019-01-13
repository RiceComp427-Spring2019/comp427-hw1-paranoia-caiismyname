# <img src="http://www.rice.edu/_images/rice-logo.jpg" width=180> Comp427, Spring 2018, Homework 1
## Rational Paranoia
The homework specifications, as well as the corresponding course slide decks,
can be found on the [Comp427 Piazza](https://piazza.com/class/jqifhp864b37ju).
This assignment is due **Thursday, January 17 at 6 p.m.**

You will do this homework by editing the _README.md_ file. It's in
[MarkDown format](https://guides.github.com/features/mastering-markdown/)
and will be rendered to beautiful HTML when you visit your GitHub repo.

## Student Information
Please also edit _README.md_ and replace your instructor's name and NetID with your own:

_Student name_: David CAI

_Student NetID_: djc5

Your NetID is typically your initials and a numeric digit. That's
what we need here.

_If you contacted us in advance and we approved a late submission,
please cut-and-paste the text from that email here._

## Problem 1
- Scenario: Stadium
- Assumptions:
  - None
- Assets:
  - The first asset under our protection are the two football teams — both the home team and their opponent — and their associated staff. This primarily includes just their personnel, but is also relevant to their equipment/accessories as these objects are likely to come into close contact with them and have large opportunities to affect them. The second asset under protection is the audience watching the game. The third is the physical stadium (and associated equipment). The fourth is the abstract notion of “the game of football” — since the teams want (arguably, need) to play football, and that’s the purpose for the crowd gathering, a disruption that does not affect the previous three assists but still manages to stop the game is also a threat, though not at the same level since human lives are not at risk.
  - Taking a closer look at the football teams, we can see that we would want to  protect their confidentiality (play calls, game plan, etc) as well as their availability for the game (getting constantly mobbed by fans is not conducive to a football game).
- Threats:
  - The possible threats can be categorized into groups based on the asset delineation above.
  - Threats on the football team (these apply to both teams, but will only be described in the context of the home team): Attackers could include fans of the opposing team who wish to 1) disable the home team by injuring the players, or their necessary equipment 2) steal confidential information regarding the team’s operation to disrupt them at a later time 3) not physically injure them, but still render them unavailable for the game. These attacks would typically be motivated by an allegiance to the opposing team (official or otherwise), and would either be carried out by fans or “says” from the opposing team. Note that the pool of potential attackers is magnified by the status of the team.
  - Threats on the audience include: 1) Typical violence that may occur between passionate fans of opposing teams 2) attacks that take advantage of the high density of people (a bomb going off in the stands would injure more people in a stadium than in a parking lot) 3) attacks that take advantage of people’s focus on the game (e.g. pickpocketing). These attacks are not specific to a football stadium, but rather to large, public areas — (imagine a public square in a tourist city on a national holiday), and so these attackers motives would have to be based on affecting as many people as possible with their actions.
  - Threats on the stadium are possible, but unlikely to occur in isolation (destruction fo destruction’s sake) — this would likely be a by-product of one of the previous two attacks.
  - Threats on the game of football would likely include be fans interfering with the field, or interfering with the electronics used to run the game. These likely have no motives because attention seeking.
- Countermeasures:
  - The countermeasure that covers the largest number of the threats above is security personnel, coupled with screening the audience for unusual objects. Through the security screening, any weapons of force would be confiscated, leaving most attackers to only their physical bodies. Any threat they pose (trying to injury players, other fans, break the stadium, run onto the field) can easily be stopped early in the act by having an adequate number of appropriately placed security personnel. It should be noted that this does not _prevent_ the most motivated of attackers, but is still able to quickly extinguish the attack. Prevention is largely supplied by the screening, and it would be unreasonable to govern the individual behaviors of a large crowd _that_ closely. While this strategy may require the hiring of many security personnel, that one action covers almost the entire range of possible attacks, and has the added benefit of being able to scale with the attack (more personnel can come to help address a larger issue). 

## Problem 2
- Scenario: Grading
- Assumptions:
	- The homework is to be submitted on paper with each student’s identifying information written clearly on the front. There is a computer system where the “ground truth” of grades is recorded, by the staff. The problem at hand is not to address any cheating that may occur before the homework was submitted.
- Assets:
  - The physical homeworks need to be protected, and they their access needs to be restricted to only the grading staff. The confidentiality of the grades must be kept (within this system — students can tell each other their grades, but they shouldn’t be able to _find out_ each others’ grades in any other way). The integrity of the grades, from when the homework was graded to when it was used in the final grade calculation, must be maintained. 
- Threats:
  - Threats may come from students or the graders (who may have ulterior motives). Students may try to sneak in a late submission, or replace a previous submission with a corrected version. If they receive an unfavorable grade, they may try to change their grade within the record system. Graders with misaligned motives may grade their friends (or those who bribed them) too leniently, or facilitate any of those previous actions a student may attempt. 
- Countermeasures:
  - Ideally, preventative measures would be taken early on to only hire trusted graders. However, the more interesting version of the problem is when graders can also be attackers, so let’s address that version.   
	- The counter measures hinge on ensuring the integrity of the homeworks. To do this, we must designate the professor as the only known-good actor — they will be the only one to hold the keys to some parts of this system. Upon collection of the homeworks, the professor marks them in some difficult to replicate way, changing for each assignment. The professor then places these  in an access controlled box in his office. Grading must occur all at once, where the graders and professor gather in a room together. At this time, the professor will control access to the homeworks, handing one out to a grader only after they have returned the previous homework they were grading, and determining that the integrity mark made earlier is present. The professor randomly chooses two graders to grade each instance of a homework, and only upon receiving agreeing grades does he (and only he) enter the grade in a password protected computer system. The protection of the computer system is left for another time, but let us assume that by having sole knowledge of the password, the professor has secured the system. 
	- This system prevents against any student having access to the homeworks, and makes it significantly more difficult for a grader to tampering with the homeworks or give unfair grades. The system imposes some costs on the professor (marking the homeworks), but that is a one-time, low effort cost that can be incurred. The biggest problem with the system is that it does not allow for distributed grading of the homework (each grader takes a couple and enters them in on their own), but since the graders can’t be trusted, this is a reasonable tradeoff of efficiency vs. security, and can be further addressed by having more graders attending the grading party.

## Problem 3
- Scenario: In light of recent thefts on campus, I will investigate the situation of leaving one’s laptop in a college commons.
- Assumptions:
  - None
- Assets:
  - The primary asset is my laptop, and secondarily any accessories (e.g. headphones, backpack). Ideally, the availability of my laptop would be maintained (keeping a laptop open on a table is much easier to use than putting it away and taking it out every time). Finally, the convenience of not having to take my laptop with me every time I have to get up is a major asset, and is fundamentally what creates this entire problem.
- Threats:
  - The main threat is an adversary stealing my laptop while I am not at my laptop (e.g. using the bathroom, getting coffee). If my laptop is logged in, they also have access to my data and any accounts that are accessible from my computer. There is also the secondary threat of damage, intentional or accidental, to my laptop. 
- Countermeasures:
	- The obvious solution would to place my laptop in my bag and taking it with me where I go. However, this directly impacts the availability of my laptop, having to open/login every time I get up. If I were to optimize for availability — leaving the laptop out and logged in no matter where I go — the laptop or my digital resources could easily be taken. The two assets seem to run directly in opposition to each other. Furthermore, it seems difficult to achieve an in-between state in terms of availability, since something like ‘closing and locking my laptop’ does not affect its physical security, but only decreases its availability. 
	- A partial solution can be seen in asking someone nearby to “keep an eye” on my laptop, but this has no benefit when there is no one around (that I trust). If I accept having to give up immediate availability of the laptop (keeping it open), camouflage becomes an option; hiding the laptop under a pile of books and notebooks significantly reduces the possibility of a thief seeing the laptop as a target. Finally, I could give up availability and convenience to ensure security, if my laptop is valuable enough. As a CS major, that is certainly the case and given my set of values, would be my chosen solution. However, those with different value balances may chosen a different solution from the above options.

