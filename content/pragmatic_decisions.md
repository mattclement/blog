+++
title = "Pragmatism"
date = 2019-08-03
+++

**tl;dr - Be skeptical, and choose new technologies when you need to! Pragmatism is framing choices in terms of customer value.**

> Your scientists were so preoccupied with whether or not they could, they didn't stop to think whether they should.

Using new technologies, architectures, patterns - whatever it is - is fun! The motivation to stay fresh and relevant is healthy, especially in a field that is getting more complex by the day. Using new, "unproven" technologies in production causes the same issues as old, "undesirable" technologies. Making pragmatic choices avoids some of these issues.


## Pressure

You _can_ move faster with stable software than if you're trying to keep up with the Joneses: your customers don't care whether you're using kubernetes<a style='font-size: 12px; vertical-align:top' href="#fn1">[1]</a> or deploying everything manually, as long as you're providing them business value. Business value is more important than getting to brag about your tech stack.

Our industry is fascinated with putting out new technology at an ever increasing pace. It is easy to fall into the filter bubble that tells you that if you're not deploying your login page as 10 microservices into runc containers on kubernetes with istio<a style='font-size: 12px; vertical-align:top' href="#fn2">[2]</a>, then you're behind the times and are leaving so much scalability and developer experience on the table. _Everyone_ has a SaaS product that you need to integrate into your solution. On and on and on and...

We are not immune from the same negative effects from social media platforms. You see what others are doing at their best: fun proof-of-concepts where everything looks so nice and clean. It's easy to compare that to the dumpster fire you know you have in your stack and feel embarrassed. *We are applying imposter syndrome to our tech stacks!* This problem is going to get worse as our industry grows if we ignore it: systems are getting more complex, we're relying on more components. Cool isn't the ruler we should be measuring technologies against.


## Balance

A valuable skill to learn is to apply the metaphorical grain of salt to the technologies you come across. Many technologies will not admit their limitations or give a humble brag "my greatest weakness is that I care too much!" response. It is up to us to be skeptical and put them to the test.

An obvious way to test new technologies is to create a "proof of concept". Being able to try out new technologies is a desirable feature to have in your stack: all things will hit end-of-life eventually (how's the `python2` migration going?). It's worth putting in the effort _to be able to try new stuff_: you might test out 3 different products before finding one that fits correctly. If everything is so tangled that you have to touch 30 different things to replace a simple component (we've all been there!), that is a problem worth solving itself!

Hiring is another reason to not "chase the shiny". If you are using old technologies, your hiring pool shrinks. If you're using unproven technologies, you'll have the same problem. Having a strong hiring pool is important to be able to provide value to your customers. Depth of knowledge of a technology requires time to build. It's difficult to be at the leading edge of a field, just as it's difficult to be trailing behind.


## Benefits

Making pragmatic decisions has some benefits too! When you scrutinize technologies before including them, your stack can stay _simple_. Simple is good! Freeing your mind from having to hold extra complexity lets you move faster and provide that value to your customers before your competitors. Waiting a little bit before including new technologies gives others the chance to lose all of their data! Let others have the security issues! Let others create the workarounds for all the little annoying bugs!

Not everyone will agree with this, which is fine! Its rare (but possible!) to find people who are capable of effectively managing all the issues you come across related to a project, software or not. For us mere mortals, making pragmatic decisions is necessary!

It is easier to provide business value if you can eliminate distractions, and **its all about business value.**

<hr />
<small>
<span id="fn1"><strong>1</strong></span>: Kubernetes is a very cool technology that may be appropriate for your use case! I have nothing against it: it is the 800 pound gorilla in the room and can't be ignored!

<span id="fn2"><strong>2</strong></span>: Yes, this statement is probably already out of date!
</small>
