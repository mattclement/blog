+++
title = "On Call Health"
date = 2019-07-23
+++


**tl;dr - Responding quickly to changing needs and enforcing rituals promote long term personal and team health. The mental health of your team is higher priority than service you support.**

On call responsibilities are spreading through the software engineering field. Systems are more complex. The depth of knowledge required to support these systems is increasing. How you (managers and individual contributors!) respond to this will have a powerful effect on the overall morale and health of individuals and the team.


## You're not Google

This statement is applicable to 99% of the software industry: **You're not Google, and that is OK.** While the [SRE Book](https://landing.google.com/sre/books/) is a valuable resource, some of the practices described there are probably not realistic or possible where we work. At times, there just isn't bandwidth to automate away all of our problems, and some of them are Hard Problems that we might not have expertise on the team to tackle effectively.

How you respond to problems requires making pragmatic decisions, under constraints that are unique to your organization. There may not be enough people to have 8 hour on-call shifts. You might only have the time to write up some response docs, rather than an automated response. Maybe you're still dealing with the fallout from the last incident. These are absolutely fine (and fun) constraints to have!

Giving the team ownership to direct and participate in making these pragmatic decisions is important. Nobody knows the struggles your team is facing better than the team. The desire to keep on-call stable leads to a lack of experimentation and a temptation to "control" the process. We strive to be agile in our decision making elsewhere, why not apply that to on-call as well? If week long shifts don't work, then just change it!


## The Hero

When left unchecked, on call responsibilities can encourage [hero syndrome](https://en.wikipedia.org/wiki/Hero_syndrome). While there might not be anything as malicious as intentionally causing an outage, neglecting to share prior teachings<a style='font-size: 12px; vertical-align:top' href="#fn1">[1]</a> can be viewed as the same issue. This issue affects the mental health of others on the team by tricking them into believing that they're dependent on the Hero. It can encourage people to work ridiculous hours to try to match their perceived value of the Hero, or cause feelings of self-doubt: all of which lead to decreased effectiveness.

We can mitigate this by creating some rituals<a style='font-size: 12px; vertical-align:top' href="#fn2">[2]</a> that limit the ability for anyone on the team to become a Hero.

- It's dangerous to go alone, take <span style='text-decoration: line-through'>this</span> a coworker!
- Every page requires action: Documentation, runbooks, etc.
- Every shift requires hand-off

Simple rituals like this may seem restrictive or unnecessary: consider that you probably have a co-worker who thinks the exact opposite. These rituals help lift up the more junior members of the team, and are a crucial device for teaching and building rapport within a team.


## Copying from the pros

On-call is a responsibility that predates computers: medical professionals and first responders are some of the first professions that come to mind. While being on call for a system might not rise to the level of importance of those jobs, we all react to stress like human beings.
There are lessons we can copy from the behaviors of first responders throughout the life of an incident.

> Behavioral health damage in first responders may owe to... *inadequate training, unrealistic expectations from leadership, and arbitrary decisions or shows of favoritism.*
>
> Among protective factors during a disaster for first responders, *social support* appears to be important, particularly *organizational support*, in terms of good relationships with leaders and coworkers. Brooks et al. found that *supportive, approachable leaders and camaraderie among responders* helped with first responders’ psychological well-being.
>
> Some reported *positive experiences with CISD* (critical incident stress debriefing), others found the intervention intrusive and reported feeling more distressed after it. They reported experiencing benefits from *peer support and using the crew for bonding* after negative incident.
>
> <small>- [First Responders: Behavioral Health Concerns, Emergency Response, and Trauma](https://www.samhsa.gov/sites/default/files/dtac/supplementalresearchbulletin-firstresponders-may2018.pdf)</small>

Sound familiar? Training, setting expectations, social support, etc. are the _exact same things_ we want in our teams! Let's read on a bit and grab some great snippets from their suggestions.

> - Plan in advance of disaster mobilization, and develop clear written protocols and strategic plans.
> - Include all the team members in the development of the protocol, and ensure they are all adequately trained
> - ... determine factors that could prevent some of the team members from participating
> - Ask potential responders before the disaster to be aware of the stress they are dealing with and to assess whether they have the capacity to deal with the additional stress.


**Getting the fundamentals right is key.**


What these protocols or rituals look like depend entirely on your team, and there is no reason for them to be set in stone. Evolve the process as the team changes and respond quickly to pain points your team is experiencing. It doesn't have to start out fancy and can be monotonous, but a process that isn't great is better than no process at all.



<hr />
<small>
<span id="fn1"><strong>1</strong></span>: Documentation, response playbooks, and post-mortems are great ways to share this knowledge. These make fun role-playing campaigns if you're into that!

<span id="fn2"><strong>2</strong></span>: Why "ritual"? There are already enough protocols in computing! Really, it's so we can be methodical and formal: It shouldn't leave much room for interpretation. This will help avoid a question of who must follow it (hint: everyone should!).
</small>
