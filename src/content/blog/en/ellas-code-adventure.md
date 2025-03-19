---
title: "Ella's Code Adventure - About Shift Left and Secure Coding"
description: "About integrating security early in development"
pubDate: "19 Mar 2025"
---
# Ella's Code Adventure - About Shift Left and Secure Coding

"Everything is ruined!"

An upset voice echoed through the classroom as Henrik, the school's IT teacher, rushed in with a worried expression. Teacher Lisa and the children looked up in surprise from their morning assembly.

"What happened, Henrik?" asked Teacher Lisa calmly.

"The school's new system for registering lunch meals – the one we've been working on for three months – we were supposed to launch it today, but the security team just found a serious bug! Now we have to postpone the launch for several weeks!"

Ella and her classmates exchanged confused glances. They had heard about the new system where students would be able to register their lunch choices digitally instead of on paper, and everyone had been looking forward to testing it.

"But how could this happen?" asked Teacher Lisa. "I thought everything was ready."

Henrik sighed. "The development team built everything exactly according to the specification, but when the security team tested the system at the last minute, they discovered that anyone could change other people's lunch choices. We've been working in the wrong order; the security team should have been involved from the beginning!"

Ella suddenly raised her hand. "Is it a bit like when we created our digital museum for the school's centenary? When Kim, Rami, and Maya told us about DevOps and how important it is for everyone to work together from the start?"

Henrik looked at Ella in surprise and then at Teacher Lisa. "Ella is actually completely right. That's exactly what happened. We haven't followed the 'shift left' principle that Maya from the security team always talks about."

"Maybe this will be a good opportunity for the children to learn more about it," suggested Teacher Lisa. "Henrik, do you have time to tell them a bit about what 'shift left' means for security and code testing?"

Henrik brightened up. "I'd be happy to! It fits perfectly since class 5B starts with basic programming next term."

Later that day, Henrik had returned, now together with Maya, whom the children recognized from their DevOps project. They had set up a large screen and prepared a presentation.

"Today we're going to talk about something called 'shift left' and how it helps us create secure, good code," began Henrik. "First, can anyone guess what 'shift left' means?"

Ella raised her hand. "Does it have to do with a timeline? Doing things earlier?"

"Exactly!" said Maya with a smile. "In a traditional development process, the project goes from left to right on a timeline: first planning, then development, then testing, and finally security. But in 'shift left', we move important tests and security checks earlier in the process – we 'shift' them 'left', that is, to the left on the timeline."

Henrik drew a timeline on the board with four phases: "Planning", "Development", "Testing", and "Launch". Then he drew an arrow that moved "Testing" to start already during "Planning" and continue throughout the entire process.

"Can anyone guess why it's good to test and check security early instead of late?" asked Henrik.

"Because it's easier to fix problems early?" suggested Johan.

"Exactly!" nodded Henrik. "Imagine you're building a house. If you discover that the blueprint has an error when the house is already built, it's much harder and more expensive to fix than if you discover it when you're still planning."

"Or like when I built my Lego castle," said Li. "I didn't realize until the end that I had built on a base plate that was too small, and by then it was too late to change without tearing down almost everything."

"An excellent analogy!" said Maya. "And that's exactly what happened with the lunch system. We discovered a security problem at the last minute, and now we have to make big changes."

Henrik took over again. "To avoid such situations, modern development teams use something called 'continuous integration and continuous delivery', abbreviated CI/CD. Who can explain what continuous integration means from our DevOps lesson?"

"It means that you put everyone's work together often, preferably every day, so you quickly discover if something doesn't work together!" said Ella, proud to remember.

"Exactly!" said Henrik. "And in this flow, we include different types of automatic tests that run every time someone makes a change to the code."

Maya brought out her laptop and showed a screen where different types of code tests were listed:

1. **Unit Tests** - Test individual parts of the code
2. **Integration Tests** - Test that different parts work together
3. **Security Scans** - Look for security problems in the code
4. **Performance Tests** - Check that the program is fast enough
5. **Accessibility Tests** - Ensure that everyone can use the program

"When a developer writes code, all these tests run automatically before the code can move forward," explained Maya. "If any test fails, the developer must fix the problem right away, not later."

"That sounds smart!" said Sofia. "But isn't it annoying for the developers to have to fix everything right away?"

"It might feel that way at first," admitted Henrik. "But fixing small problems continuously is actually much easier than having to fix a big pile of problems at the end of a project. Think of it like cleaning your room a little every day instead of letting it become a big mess that takes a whole weekend to clean up."

Maya continued: "Another important part of 'shift left' is having security built in from the beginning. This is sometimes called 'Security by Design'. It means that already when we plan what we're going to build, we think about how to make it secure."

"Like when we built our digital museum and you helped us think about what information we should share and how we should protect the images," said Ella.

"Exactly!" confirmed Maya. "And we have different tools that help us with this. One example is SAST – Static Application Security Testing – which is like a detector that scans the code to find security problems."

Henrik went to the board and drew a picture of a pipeline, like a tube with several stations along the way.

"Imagine that the code travels through this tube. At each station, there are different detectors looking for problems. If a detector finds something, the code stops there until the problem is fixed. Only when the code has passed all stations without problems is it allowed to continue to the next phase."

"It sounds like a security system at an airport!" said Johan enthusiastically. "Where you have to go through metal detectors and X-ray machines before you can board the plane."

"A perfect analogy!" smiled Maya. "Just like at the airport where security is important to protect all travelers, security in our code is important to protect all users."

Henrik took a stack of papers and handed them out to the children. "Now we're going to do an exercise to understand this better. I've written a simple code for a chat application where two people can send messages to each other. I want you to try to find security problems in the code."

The children worked in small groups to review the code. To Henrik's surprise, several of the groups actually found real security problems, such as that anyone could read all messages and that passwords were saved in plain text.

"You are really good!" praised Henrik. "Just imagine if we had had you as security consultants for the lunch system from the beginning!"

After the exercise, Maya gathered the children again for an important reflection.

"What we've learned today, about 'shift left' and secure coding, isn't just about computers. It's about a way of thinking that you can use in all kinds of projects."

"Exactly," agreed Henrik. "When you build something, whether it's a physical thing or a computer program, it's always better to think through the problems from the beginning and test frequently along the way, than to discover errors at the end."

Teacher Lisa, who had been sitting quietly and listening, now came forward. "I think we can use this in our new class project about climate too. We can have 'checkpoints' along the way to make sure we're on the right track, instead of waiting until the end."

When the school day was over, Ella waited for Henrik outside the classroom. "I wonder... could I learn more about programming and secure coding?" she asked cautiously.

Henrik smiled broadly. "Absolutely, Ella! We actually have a coding club after school on Thursdays. You would be more than welcome to join!"

On the way home, Ella eagerly told her mother about the day's lesson.

"Mom, do you know what I learned today? That it's much better to find problems early than late! It's called 'shift left'! And I'm going to join the coding club on Thursdays!"

"That sounds exciting," said her mother. "And the principle of 'shift left' could actually be used at home too. For example, by planning our weekends better so we don't discover at the last minute that we've double-booked."

"Exactly!" exclaimed Ella. "And do you know what Henrik said? He said that test-driven development is like having a map before you start traveling. You write the tests first, so you know where you're going. Isn't that smart?"

Ella fell asleep with a big idea bubbling in her head. Maybe, she thought, she could use her new knowledge about secure coding to help build the next version of the school's lunch system. Or even better – maybe she could one day create apps that were designed to be secure from the beginning, with security built in from the start, not as an afterthought.

"Shift left," she whispered before falling asleep. "Find the problems early, not late."
