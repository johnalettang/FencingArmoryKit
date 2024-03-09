### Introduction and Motivation: 

Sword fighting for sport has been around for as long as swords themselves. Fencing is modern example of sport sword fighting, and despite its long history, it is one of the most technically involved sports in the world, because electronics are mandatory in order to compete in modern fencing.

In most sports, it is quite easy to visually see when a point has been scored. However, fencing, especially at a high level, is extremely fast, and has specific scoring requirements. Therefore, fencing has adapted to using electronic sensors that "complete a circuit" when hitting the correct area of their opponents body. But due to the necessary use of electronics to participate in fencing, it adds a frustrating barrier when one of the many parts of the "circuit" breaks.

The "fencing armory kit" serves as an all-encompasing guide for fixing, maintaining, and testing fencing equipment. It is a set of instructions and open source tools that allow for a better understanding of how fencing equipment works, both mechanically and electronically.

### Related Work / Prior Art
![[Pasted image 20240306154608.png]]
[Professional testing box](https://www.absolutefencinggear.com/favero-professional-tester.html)
Fantastic design for a testing box with really clear diagrams demonstrating electronically what it is testing. However, it is EXTREMELY expensive.

![[Pasted image 20240306154919.png]]
[Smart Test Box](https://fencingstb.com/)
Very expensive for what it is...much cheaper than the last one. However, it is not open source and it is not intuitive.

![[Pasted image 20240306161159.png]]
[I can haz Armory](https://www.youtube.com/channel/UCK9jC6LJLAbxtFnIBvkuyqw/videos)
YouTube channel with short dedicated videos for fencing equipment. Lots of great information in here but not the most organized. However it shows the accumulation of knowledge and some awesome tips and tricks to fix fencing equipment. I especially like the use of 3D printed tools and making use of open source tools.

![[Pasted image 20240306163624.png]]
[Care and Feeding for all Things Fencing](https://store.payloadz.com/go/?id=2675901)
Comprehensive book for fixing fencing equipment. Informative, witty, concise. It does a good job of being approachable while also having information for an experience armorer.

![[Pasted image 20240309111719.png]]
[Open source wireless fencing box](https://github.com/Yohannfra/Touche)
Awesome concept for what an open source fencing product could be. Well organized. Relatively easy to understand. My ideal is that my board is designed to come pre-assembled, so there would be less hassle with assembly.

![[Pasted image 20240309112043.png]]
[Fencing Box Video Tutorial](https://www.youtube.com/watch?v=8p2DS3O2PkE)
From Ball State Fencing Club, shows just how easy the circuitry behind a fencing testing box is, good demonstration of how to make one of these yourself. I am going to try to make it so that it is even easier to understand what the lights mean and such for testing a blade, as opposed to this someone minimal design.

I am hoping to build on these previous works while changing my scope. The first two tools are extremely expensive electronics, that I can use my unique experience to create myself in an open source option. Instead of a linear format of information. I am hoping to make individual tools that have a short guide on their use. This allows for the user to learn from the tool, instead of from a written explanation that abstracts the problem into something the user no longer understands. 

  
### Design/Conceptual Framework

Conceptually, I want to build a tool that helps fencers think, understand, and debug their problem. However, it does not totally debug the problem for them. This is both for the sake of education, and so that I do not have to design for every use case, instead design for general use cases and allow the user easy access to apply the tool to their problem (lowering the floor and widening the walls).

One of the core principles of this Armory kit will be open source. Unfortunately, much of the fencing community sells very simple electrical products for exorbitant amounts of money. The design of this armory kit will be entirely open source so that anyone who wishes to can open up the hood in order to understand and improve my design. Not to mention with the 3D printed tools that I make, this gives anyone in the world access to the tool practically for free, provided they have access to a printer. I am hoping this will help bring down the barrier of someone getting into fencing from a financial point of view.

One last concept for this class that I want to help bring across with this project is debugging. I want to be able to demonstrate to someone learning the equipment behind fencing that something is wrong, what are the steps to fix it? In essence, right from Palpert's view of constructionism, I want for those who use the armory kit to learn how to debug. To understand that their fencing equipment is acting like one big wire, and if their equipment isn't working, that probably means that there is an electrical disconnect somewhere in that big long wire. But as for the process of how the debugging goes, I want that to be up to the user, with no direct step-by-step answer for each possible problem.

### Proposed Work
To start my design process I plan on interviewing the CU fencing team (particularly non-engineers) and ask them what they do or don't understand about fencing equipment. I particularly want to ask them how they think the electronics work and try to explain how they currently check to see if their equipment works.

I am hoping to take this feedback to heart for my design process and my main design will be a PCB that will intuitively show the fencer how to check if their equipment is working. This will be accompanied with some smaller tools that will allow for easier maintenance and explanations of fencing equipment.

In order to properly carry out my goals I hope to go through a design process where I take in the critiques of the current system and use them to drive my product. Starting with interviewing multiple current fencers about their current system and proposing another one that they can also critique.

I want to sketch up the intuitive visuals along with the actual hardware schematic that would make this possible. Then merge the two together in the layout of a PCB. However, if after the initial round of interviews I find that people don't want a PCB and they instead want something else, then I will pivot to whatever is most needed to fill the gap of knowledge.

For this design process I will need skills in electrical engineering, CAD, graphic design, and overall fencing knowledge. I have lots of electrical engineering and 3D design experience, however I currently lack in graphic design skill and will likely need lots of iterations and inputs before coming up with something intuitive to interact with. I will also be taking advantage of the CU fencing team for input of different fencing perspectives on what information will be useful and what people don't know yet. I also plan to involve the CU Fencing team when testing low fidelity prototypes, making sure they like the paper/graphic version before moving to the final hardware.

The final test for the product will be taking it to the CU fencing team and seeing if it is intuitive to use and makes it easy to test equipment and understand more about how weapons electrically work.

I plan on documenting interviews via audio recording and google forms. For the physical prototyping I plan on prototyping visuals in figma and documenting all visuals in there before compiling them into a final paper. Figma works well as it is an open computer space with easy organization and basic graphic design needs.
As this is an "open source" project. I also plan to put up all neccessary documentation for the usage of this tool in github so that anyone can download the files I used in order to test fencing equipment.

### Proposed Timeline

**Week 1, 3/10:** Conduct Interviews of fencing team. Low fidelity designs based on what is needed

**Week 2, 3/17:** Build schematic of testing box, start finding parts and getting dimensions

**Week 3, 3/25:** Order PCB -Spring Break-

**Week 4, 3/31:** Organize github and open source documentation

**Week 5, 4/7:** 3D model/print useful tools for fencing team. Each has documentation

**Week 6, 4/14:** Assemble PCB, debug issues.

**Week 7, 4/21:** User testing, interview with use of device, take feedback

**Week 8, 4/28:** Demo week, final documentation and writeup
