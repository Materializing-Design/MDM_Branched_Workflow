# Journal 

> [!NOTE]
> This is a sample journal from another repo.
> Clear it out before you start. 


# February 5th 2025 

Form of the paper and the article-reader boundary. 
This understanding can be enhanced if I were to compare this in digital form and the print form because in print form this boundary does not exist -- Is this due to the persistent nature (materiality) of paper? 
This only occurs in the digital form. 

-- Affordances of paper article,  K Ohara 

## 8:06AM 
Continuing, setting up the boilerplate stuff -- done 

I can begin coding the first prototype.
For this, I need to 
1. read the MD file and bring it into its constituent parts. These will be:
	1. The headings 
	2. The sections 
	3. The paragraphs 
	4. The references & bibliography 
	5. The footnotes 
	6. The figures and figure references
2. then I need to put them on the screen. One section goes the whole way, one paragraph highlighted at a time. Switch sections horizontally. 
3. Once this is done, I'm interested in:
	1. Changing citation style, font size, font family (serif and sans serif), and line spacing up to the reader. Put citations and footnotes on hover 
	2. A word highlighter that the reader gets to shift with the arrow key and it helps the reader focus on the paper. arrow keys are used to move between the arrow  
	3. In this one, I also need to lay extra emphasis on metacues. In print form, we have the thickness of the page and we can move forward or backwards at a non-linear pace, we can skim in a different way than we do on screen... perhaps a way to see the whole of the paper and then hover the mouse on the page to see it in a more readable form... 
	4. Hover really is a brilliant interaction it affords "kinda". as in... unlike other transitions which are integral, black and white, hover invites me "come inside, have a look dearie" and if you like something, take the next step. 
4. prototype zero is about only reading. prototype one is going to be about writing alongside reading. The prototype two works with shifting things around, which also includes opening multiple pages at once and connecting things together in them; concept maps and the sort. As for four, Im wondering if its interesting to put some AI into this that *forces* the reader to read. This makes it the edgy part again. A co-reader that pushes you to write as you read. try to make the reader uncomfortable or challenge with questions?
5. I still havent gotten a good answer about: what do we want to do when we read on screen? How does a computer afford and how do we want to read. On a paper we can run a pencil along the text but on screen we cant do that. But really: What do we want to do when we read on a screen? HOW Do we want to read on a screen? 

Stopping at: 12:15PM 

## 12:00AM 
Fixed the problems with MD on github. Don't know why though, its kinda irrelevant to my purpose... lol  
Anyway. Whats next? 

I'll stop here and move to writing and let this stir in my mind. I need a throughline of execution - like the thread for Tanjiro. 
Stopped 12:32AM 

# February 4th 2025 

## 9:45 PM 

Okay lets begin. I want to start and take prototype zero to a far enough state. As for the template Im using for repository, I'll change the home screen to the different prototypes. 
I have to first make a paper into an MD file. 

--- 10:09 PM MacOS wants to update now, fuckin A... brb 

--- 10:54 Back in action.

Paper converted 
End of day


## 11:20 AM 
Okay. I've been processing this for about 2 months in my head and it is finally go time. I imagine this system as one base prototype that provides the core structure of an academic article, and then 4 other prototypes that use this base structure to build other interactions on top of it. 

To power this base structure I will convert a paper - likely Rilla and Pippin's paper from 2023 - into a formatted MD files collection. This strips the paper of its strict formatting from the publisher and extracts the data into a malleable form. 

From this I build a system in react that loads this MD file into a web app.
Scrolling vertically implies continuity, whereas scrolling horizontally -- like cards -- implies a shift in the entity. So with that rationale in mind I think each section of the paper should be a vertical entity and transition between each section should be a horizontal swipe. 

A paragraph is the quanta of an essay. A paragraph represents an idea in an essay. So instead of swiping continiously, there should be a gentle "flick" that jumps between paragraphs. This way, there is also a ==meta-cue== for the reader: "so and so idea was 4 flicks ago". 

I think for prototype zero this idea of meta-cues is of peak importance. This is one thing severely missing from the current form and I think this is exactly what disorients people or makes them feel out of control. 

I am yet to think of how sub-sections should be dealt with but I will figure that out once this much is in. 

As for the other prototypes, I have some main ideas . 
1. Writing and Rewriting layers
	1. to engage with a text we need to be able to write our thoughts. As Eric hayot writes, we dont write what we have thought, we write to think. (case in point, this very journal).
2. Ability to restructure the paper
	1. People don't read a paper in the same order as is put together by a publisher, they read it usually first as abstract only, then introduction and conclusion, then maybe some survey of the methodology and look at the discussions 
	2. Point being: the ability to focus in on things that
3. concept map -- nodes 
4. deep references 
	1. The ability to reference the nodes or markers in *other* papers? how would this work 
5. manual markers
	1. Like bookmarks at different spots of the paper drawing a through-line through the paper.  
6. lowlighting 
	1. the reverse of highlighting? Would this be useful? How would this make the reader feel? 
7. Still curious to think of something that would be somewhat... *edgy* like *forcing* a user to be an active reader. 


# January 9th 2025 

- If we think about it, the ability to write in margins is not really a feature but more like a “making it work”. We do it because the material doesn’t deny us — A library book annotated For instance is frowned upon. 
- So I wonder what the optimal invitation would be in this case. Rewriting? Summarizing? 

- Highlighting is to guide the eyes to focus on whats important. Color coding was something people did ad-hoc; it was a way to group/cluster information
- Based on these, I wonder how useful it is to continue the note-taking and highlighting metaphor into the digital realm 


# January 8th 2025

The digital world is an entirely new universe. Anything that I need there, I must build it from scratch (in the same way as it exists in the real world). All interactions need to be rebuilt. So if someone needs a certain ability, to be able to shuffle the pages of a PDF, that functionality needs to be built into it, it needs to be meticulously well defined and programmed; call that a side effect of programming. 

For these interactions to be intuitive, we need gestures and animations. But when we read on a computer, we are limited by the cursor; which just might be why people prefer to read on ipads, but even there the gestures are limited and contained in the 

But see that is not the case with the real world. The ability to shuffle papers of a printed article are a consequence of a page being a discrete entity that can be moved around and is not inherently bound to the container that is the collection of pages we call the printed article. It is a byproduct of the laws of nature, shuffle-able papers did not need to be invented. Print reading allows shuffling for anyone with hands, it enables the reader to impose their own sequence, structure, and as a result: meaning. 
A book, for instance, may *deny* shuffling, a bound book does not afford the shuffling of pages. But then you can go ahead and tear a page out. Once again, a byproduct of the laws of nature. The force exerted on the page i stronger than the structural integrity of the materials used in the book (paper, glue, thread, binding, etc.). Someone who is unable to exert this strength, or access an angle at which breaking force can be applied will not be able to tear the page out of the book. 

The universe we inhabit affords us through the laws of nature, we can directly impact it because we can apply forces. 

But in the digital realm, in the universe of bits, we do not have that degree of freedom/control. In the digital space, all interactions need to be programmed, built from the ground up. There are few side effects and pages cant be torn. And so if every possible interaction needs to be programmed, then and built into the system as an intuitive thing, (if a user is going to interact with a system their expectations need to be met, enough for them to be able to be productive while they adapt to the new things in the system.) then a skeuomorphic, linear translation is an inadequate version of the article, which is why we find people printing the article to read it on paper where their expectations match the affordances.  

The reader doesn't get e-readers where they can impose their own structure on paragraphs or pages of an article, unless the underlying interactions are programmed in, which can then afford a certain kind of ability to the reader. 

The ability to impose a unique order of pages/sections along with the ability to rewrite paragraphs, invites the reader to write as they read. These two interactions together invite the reader to now make sense of the paper in their own way. This breaks the rigidity of the paper as the author saw it and allows the reader to approach it on their own level.  
Then the ability to compare the rewritten with the original, or multiple rewritten versions over time helps the append more material, isolate section sand draw connections between concepts, write a second layer of narrative on top of the paper, write multiple of these layers 

The above mentioned challenge with computing, of having to build everything from the ground up, is precisely what is the key strength of computation. No matter how pedantic and meticulous one needs be when developing these tools, the system is not bound by space and instead of physics, these systems lean on human psychology. `Talk about bruner's three representations and how this leans on the visual part. Then talk about what Alan kay had to say about this.` 

This now begs the question once again: What is the boundary between the form of the paper and the form of the reader. Because when we look at a two column layout, that is not the form of the reader it is embedded in the pdf. 

In the real world we are able to isolate a page and remove it from the whole. In the digital world however, the entire paper is contained within a pdf. If i were to remove the page, it would then be contained inside another pdf but it can not exist outside the container. 


- How would we shuffle pages inside a pdf? Why do we even have pages? 

Digital reading should be enhanced reading, we are finally free from the constraints of text. 
*"But now I'm free... there are no strings on me..."*

What's missing? What makes it worse than print reading?  
