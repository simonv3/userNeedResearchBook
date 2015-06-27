# Analysis {#Analysis}

## Why Analysis?

In the analysis we will take a closer look at the data and organize it after meaningful pattern.

After the interviews, the data is organized by participants or the research sessions: All notes
from one research session or participant are grouped together. This is a format which is
hard to use for designing.

What would be more useful if we would organize the data by needs of users and their problems.
To do this, we take the data – which is currently organized by participants – and cluster the data by meaningful themes.

![Analysis for creating themes independent from particular participants](images/aggregationAnalysis.svg)

## Organization of data

In the analysis we organize the data hierarchically.
The basis for our analysis are the utterances or observations, usually represented by a line
in your transcript, like »I find it boring to move around all the textboxes again!«.
These pieces of data will be grouped if they may share a similar theme.
These groups get a headline, stating the theme of by  the underlying pieces of data.  
This is useful when designing, since you can refer to the title instead of considering all  the underlying data each time.

Sometimes you will have several themes, which relate to a common theme themselves. In this case, it makes sense to make a group of groups with a title which states the overarching theme of this group of groups.


> Here is a part of an analysis.
>
> -   *Overarching theme*: using existing work for inspiration
>	-   *sub-theme*: review previous projects
>		- *Data:* » have a look at an old project to see how I solved this problem…«
>		- *Data:*  Participant searches for…
>		- …
>	-   *sub-theme*: use other’s work  for inspiration
>		- *Data:* »I look on google images how other calendars look like«
>		- *Data:* browses through the book to see…
>		- …
>


Such a hierarchical analysis could be done in two ways:

1. **Top-Down**: You first name the groups and write the titles and then sort pieces of data into the groups hereafter
2. **Bottom-Up**: You first group pieces of data which seem to share a similar theme and then give the group a comprehensive title which states the topic shared by the underlying pieces of data.

We are going to use mainly the 2nd way, doing a so called »bottom-up« analysis. This does
not mean that we never take a piece of data and sort it into an existing group. It just means
that the group names are initially created are based on actual data.

Thus, in the analysis we may start with grouping moving similar data

> - *Data:*  »I look on google images how other calendars look like«
> - *Data:*  Browses through the book to see…


Then we give that data a headline and name the topic:



>- **Theme:** Use other’s work  for inspiration
>	- *Data:* »I look on google images how other calendars look like«
>	- *Data:*  Browses through the book to see…

When we come across a piece of data which shares the topic we can add it to the group too:



>- *Theme:* use other’s work  for inspiration
>	- **Data:  Searches on amazon to see how covers of books about the same topic look like**
>	- *Data:* »I look on google images how other calendars look like«
>	- *Data:*  Browses through the book to see…


## Create meaningful groups

I already talked about grouping data by shared themes. The question is: What is a meaningful theme?

One method to group data and to derive a theme would be going through the data and see which utterances
and observations mention the same thing or the same assessment. Thus, all notes mentioning »color« would
belong to one theme and get the title »Color«; all notes mblockquote p+p entioning »good«  belong to one theme and get the title »good things«.


> Let’s say we gathered this data (among others) in research on Do-It-Yourself-Work (DIY)
>
> - The shelf looks not as neat as a bought one, but it is mine
> - When it is broken and I need to get to work I can fix my bike quickly
> - The cabinet’s door was loose. It annoyed me, so I repaired it.
> - I look at the assembled bike and think: nobody else has the same
>
> If we put the pieces of data which mention the same things in the same group we get these two groups:
>
> - Theme: Bikes
> 	- I look at the assembled bike and think: nobody else has the same
> 	- When my bike is broken and I need to get to work I can fix my bike quickly
> - Theme: Furniture
> 	- The cabinet’s door was loose. It annoyed me, so I repaired it.
> 	- The shelf looks not as clean as a bought one, but it is mine


Organizing the data by this »same things mentioned«-method would help us  find data concerned
with a specific thing or assessment: If we want see everything that concerned furniture we can go through
the data in the »furniture« group; If we would like to know what people liked we could look it up in a group titled »good«.

However, organizing by the »same things mentioned«-method has its shortcomings: A theme named »furniture« communicates only that the underlying data has *something* to do with furniture. You still need to go through the underlying data
to find out what people did with their furniture and what motivates them or which problems they face.
The names of themes  created by organizing by the »same things mentioned«-method are just labels for the content and have no meaning on its own.

Imagine we would not create the themes by looking for same things being mentioned but by the insights we
drew from the data in the group by focusing on the meaning of activities, problems and goals for the participants.

If we take the data about DIY again this could look like this:


> - Theme ((based on an insight about the participants): Participants need to »make things work«
> 	- The cabinet’s door was loose. It annoyed me, so I repaired it.
> 	- When my bike is broken and I need to get to work with it the next day I can fix my bike quickly
> - Theme (based on an insight about the participants): Good: DIY gives sense of individuality
> 	- The shelf looks not as clean as a bought one, but it is mine
> 	- I look at the assembled bike and think: nobody else has the same


If we organize data by themes based on the insights about the participants and summarize that
insight in the group’s title, the theme’s title is  a useful piece of information on its own:
It is not just for accessing the data, it is an empirically based principle we can follow when
we design.

If you design, let’s say, for a DIY-Online community, a theme based on an insight, like »DIY gives as sense of ownership«  may inspire the implementation of a function which allows people to share their
designs and customizations. The insight that sometimes DIY is just about fixing things may
lead to the provision of a wiki for collecting best practices for doing common repairs and
maintenance.

If you have a new idea you can ask: »Does this idea follow what is stated in the group titles?
Does it violate them?«. You may ask yourself »Which design could I  create based on this theme?«.
Since the themes are based on our data, they will express the actual needs of your users and not
some (potentially stereotypical) assumptions.

Grouping your data based on insights about your participants provides great benefits.
But it can be hard and may be not possible for all your data.
Creating groups using the same-things-mentioned methods is still a useful method and these
groups may still evolve. Usually I have  some »same-things-mentioned«-groups in the beginning
and far fewer at the end – but  my analysis will be a mixture of both styles.




To understand how to organize data by themes based on insights can be hard to grasp for beginners.
To ease the learning I provide another example:

> Let’s say we gathered this data (amongst others) when researching beginners in web programming:
>
> - To try out stuff in HTML is fun
> - I analyze Javascript code to understand patterns
> - It is great to quickly test something using a JavaScript framework
> - To know these ›attributes‹ of HTML-›tags‹ makes writing code easier.
>
> If we put the pieces of data which mention the same things in the same group we get these two groups:
>
> - Theme (based on same-things-being-mentioned):: Utterances with HTML
> 	- To try out stuff in HTML is fun
> 	- To know these 'attributes' of HTML-'tags' makes writing code easier.
> - Theme (based on same-things-being-mentioned):: Utterances with JavaScript
> 	- I analyze JavaScript code to understand patterns
> 	- It is great to quickly test something using a JavaScript framework
>
> Organizing the data by the insights we may draw from the data the structure look like this:
>
> - Theme (based on an insight about the participants): Trying out is good
> 	- To try out stuff in HTML is fun
> 	- It is great to quickly test something using a javascript framework
> - Theme (based on an insight about the participants): Learning makes own coding better
> 	- I analyze Javascript code to understand patterns
> 	- To know these 'attributes' of HTML-'tags' makes writing code easier.


## Doing the »right« Analysis

The data analysis is done by inferring themes from several  data points. Thus the process is
empirical (as it is based on gathered data) but if the same
data is used, analysis made by different people will differ. This is because the result of the
analysis depends on the reasonable but still individual and debatable interpretation of the
data. You could say that »looking at last years design to quickly reuse elements« belongs to a
theme concerned with »I want to save time« or to one related to the topic of »reviewing
designs for inspiration« (given that it could serve both from the user's perspective).

There is no »right« or »wrong« nor a clear cut criteria of being »close enough« to the data when
you group your data in themes. Instead of having a clear, measurable rule like »you
must have p&#060;0.05 significance« in statistics, most important is that your analysis is plausible
(instead of »right« or »wrong«).

I compare the process of analysis to building a house from a pile of Lego® bricks. These
bricks are like the not-yet-analyzed data you start with. When you build a house out of these
bricks, there is no »right« building. But neither is it a process which is arbitrary.

There are many, many ways to stack up the bricks – but only a very few of these generally
possible ways will result in something that can be plausibly called a house.

<div class="gallery two">

![possible arrangement of bricks – but not a house](images/lego_bricksToStartWith.jpg)

![one way to build a house](images/lego_houseFinished.jpg)

</div>

How your final Lego® house will look
like is not determined from the beginning, rather you will change
designs, move walls and sometimes try to use the same piece in different
parts of the building to try out and improve. The same things will
happen when you analyze data: There are many very many possible ways to
just arrange the data, but only some of them will create something that
is meaningful to you and others. This creation of a meaningful structure
is not determined at the beginning, but a process, just like building
your Lego® house, in which you trial, fail, find improvements and step by
step come closer to a structure you are satisfied with.

## Prepare Data for Analysis

Before we start with the analysis we should prepare our data.

### Add Participant Codes

When you create groups of data it is good to know if the theme of the group is
relevant across several participants or only concerns one participant.

Thus, you should supply your each datapoint (=line in the transcript) with a participant code.
A participant code works like a pseudonym: The user is not identifiable by his/her real name,
but by a stand-in for the name. I use neutral number codes: The first person I did a research
session with is P1, the second is P2 etc.

> If you have this on your transcript:
>
> - It is hard to know what exactly the client wants, because I don’t talk directly to the client
> - The document is divided in sections, separated by blank pages.
> - The current ideas/prototypes are in the first section. All discarded or »paused« ones are in later sections (the archive”)
> […]
>
> It will look like this after adding the participant codes (the data is from the second research
> session:
>
> - It is hard to know what exactly the client wants, because I don’t talk directly to the client –  **P2**
> - The document is divided in sections, separated by blank pages.  –  **P2**
> - The current ideas/prototypes are in the first section. All discarded or ›paused‹ ones are in later sections (the archive”) –  **P2**
> […]


You just add the participant code at the end or beginning of each line. It is not the most
exiting work but it can be done quickly – Copy the current coder in the computer's clipboard
(STRG+C), place the cursor with the [arrow keys](http://en.wikipedia.org/wiki/Arrow_keys)
and the [end](http://en.wikipedia.org/wiki/End_key)/
[home](http://en.wikipedia.org/wiki/Home_key) keys and paste the code (STRG+V).

![Annotating data in a wordprocessor](images/commentsAnalysis.png)

## Annotate
After you added your participant codes you can start to review and to annotate your data in
order to find possible interpretations, themes and meaning behind the observations and
utterances.

This will help you to get familiar with the data and to derive meaningful themes and insights
later.

Annotations are possible interpretations and questions tied to a line in your transcript. It can
be full sentences as well as short list of words.

> - It is hard to know what exactly the client wants, because I don’t talk directly to the client –  P2 **ANNOTATION: indirectness, division of tasks, friction, »I need to know the client«.**
> - The document is divided in sections, separated by blank pages.  –  P2 **ANNOTATION: Keeping/imposing order**
> - The current ideas/prototypes are in the first section. All discarded or »paused« ones are in later sections (»the archive«) –  P2 **ANNOTATION: Keeps old ideas. Why? Possible: Later reuse, Inspiration, replication**


I suggest annotating each line, but this is not a must.

The annotations should be clearly distinguishable from data you got directly from observation
or the participant’s answers – just like other things you did add yourself (e.g. design ideas).

I would recommend using a word processor with a comment function. Open your transcript,
mark the part you want to annotate with your interpretation, then click the »comment« button.
If you don't use a word processor, but plaintext, use something like »COMMENT:« or »ANNOTATION:« to mark
your comments; If you prefer to do your annotations with a pen and a highlighter, print your
notes with double line-spacing to have enough room for writing.

Annotating your data is a creative process. If in doubt whether an annotation is relevant or
not: opt for writing it. Later on it might become useful. If you are unsure about something or
an idea seems to be far fetched, just go for it. Since you keep data and comments
distinguishable from each other you can always throw stuff out again. The goal is not to come
up with great annotations but to wrap your head around the data and to find possible ways to
interpreting it.

## Digital or analog analysis?

If you analyze your data using paper notes, your titles will be written on a sticky note of a specific color (choose one,
but stick with it). If you use a word processor, use a headline for the groups’ titles.

After annotating your data you should take the decision in which media you want to conduct your analysis:
Digital in a word processor, where lines hold the basic units of data, or analog on paper, where sticky notes are your means of dealing with the data.

The analysis methods described here can be used in both media. Nevertheless, each way has different strengths.

### Comparison of digital and analog data analysis

![analyzing data analog by using sticky notes. Theme are written on yellow sticky notes, themes of themes are written on orange sticky notes](images/affinityDiagram2.jpg)

![analyzing data digitally by using a word processor. Themes have gray headlines, themes of themes have black headlines](images/hierarchyWordprocessorAnalysis.png)

The resources you need for analyzing on your computer are:

- a word processor

The resources you need for with pen and paper are:

- sticky notes
- paper
- printer (or a lot of patience to write all by hand)
- (removable) tape
- a big wall (2m*3m minimum – which is why the wall is usually the showstopper ).


But why should you want to use an analog analysis if it needs all these resources? Partly, the
decision can be based on preferences: Some people like that they can move around the notes
by hand and can get an overview of their data by just stepping back and glancing over it.

If you work with peers on your analysis you have some advantages when using the analogue
pen and paper approach: you can easily discuss your ideas with other and will get new ideas
how to structure the data. You can as well invite your boss to take a look and be part of the
team, at least for some time. This type of on-site, collaborative, analysis is best done analog.
It is easy to move notes around, and you can refer by pointing to data or just carry it over to
someone and ask for an interpretation. Using digital tools it is not that easy and direct–
despite of all the great digital innovations we have nowadays.

### How-To

#### Analysis on the computer

For analysis on your computer I suggest the following steps for preparing your analysis:

1. Create a new document
2. Paste your transcript into that document
3. Add a page break before the transcript to separate not-yet-grouped data from your (upcoming) structure of lines grouped by themes.

**Creating Groups:** Similar data is organized in lists. To rearrange data you can use copy paste, drag and drop and the tools the word processor provides (toolbar to move points in lists etc.)
\

**State themes in  titles of  groups**: Each group gets a headline. Create a hierarchy by using different paragraph styles – bigger headlines for overarching themes of themes, smaller headlines for themes that encompass the data directly. If you use paragraph styles to format your headlines, you can use the navigation tool of the wordprocessor to go through your structure

#### Analysis with pen and paper

For working analog I recommend the following steps to get analysis-ready:

1. Create table in a word processor, many rows, 2 columns (given you print on DINA4) . Each table cell will be a note.
	1. In the table settings, switch off page breaks in cells and switch »keep paragraphs together« on, so that one note/table cell will not break between pages.
	2. In the table settings, choose a decent padding around each cell, like 0.5cm
	3. Choose a font size of about 12pt, large enough to read it\
	![](images/createAnalogNotes.png)
2. copy/paste all your data (line by line) from the transcript into the cells
3. print it
4. cut out each table cell (=piece of data)
5. cover the wall with the paper from paper rolls (thus you can remove the analysis, roll up the paper and archive it and you can remove it from the wall temporarily)

**Creating groups**: during analysis you will stick your printed notes on the widths of paper
using removable tape, crepe tape or spray glue – something sticky but non-permanent, so you can
move the notes around in order to gradually improve the structure.
\

**State themes in  titles of  groups**: Write your group titles on notes of determined colors,
which are different from the color of the actual data points. If you print your data points on
white paper you can use yellow sticky notes for group titles and
pink ones for titles of a group of groups.

## Develop a first Structure  {#firstStructure}

After you annotated your data you can start to structure the it.
Structuring the data means suggesting themes behind the data, naming
these themes  and decide which data falls under which theme.

You don't use all your data yet. Start with what you find useful when
skimming through it or use just the data of two participants for now.
The goal is to set up some preliminary structure, like a scaffold.


![setting up a basic structure](images/lego_housefirstStructure.jpg)

### Move in Approximation

The easiest way to start a structure is moving similar data in
approximation. If you do you analysis on paper,  cluster notes you
assume to follow a common theme in one place and notes for other
themes in other places. If you analyze using a wordprocessor, move similar
notes in adjacent lines. Create different groups, each containing similar notes,
by using several line breaks above and below such a group or by
creating a list for each assumed theme.


> - Asking herself: what would impress the person (a safety advisor)
 »probably not that the blueprint is beautiful«
> - Good: Something that is not only useful, but aesthetically as well
>
> *These themes have in common that they are about aesthetics
and requirements. I did not have a good idea about a possible
group title or even an insight I can draw from them, so I just moved them in
approximation.*



<div class="gallery two">

![two (preliminary) groups as lines (the digital way)](images/abstractGroupLines.svg)

![two (preliminary) groups as sticky notes (the analog way)](images/abstractGroupPapers.svg)

</div>


### Name Commonalities  

You may have some data you assume to encompass a common theme but you
are unsure about . In this case just give that group of data a
preliminary title. A group name, even if it is not an insight, will
make dealing with the data easier since it gives your data some structure.

As you gather other data that falls under that (yet
vague) category you may be able to formulate and insight you gain about the underlying data.



> - Inspiration
> 	-  I try to get new ideas by looking at google images
> 	-   I get new ideas while showering
> 	-  […]
>
> -  Media
> 	- I like to use photos
> 	- The website is a great way to reach out
>
> *These are mere titles, naming a commonality of the underlying
> data but telling nothing useful for design (yet)*



### State insights  

You may have read through your annotations and have noticed something
that may make a good insight right away. Great. Just write it down and
assign the data to it. Even if you have only one or two pieces
of data that fit the insight, don't worry, just see if the insight
will emerge to be bigger. If not, you can still revise the insight or
just get rid of it and see where else the data might fit.




> My first found insights were these:
>
> -   Review previous projects
> -   Test designs in the media you deliver in
>
>\
>
>The whole structure of my analysis later looked like that (the main list points are titles of groups-of-groups,
the indented sub-lists are group titles):
>
>-   Inspiration
>	-   Review previous projects
>	-   Other (Web, Bookstore)
>
>-   Media
>	-   Do tests in the media you target
>	-   Suitablility of media
>	-   »being closer« : 2 page spreads instead of single pages etc.
> -   Idea Attachment
> -   Motivation at the beginning; then the problems start.
> -   Finishing is good
> -   (Page) Format is hard to change later
> -   TrialAndError
> -   Mutual dependencies of design elements like type area, content, font size etc. (?)
>
> Note that some themes are actual, meaningful insights (»Finishing is
good«, »(Page) Format is hard to change later«), while some are
mere group titles based on commonalities of the  data they encompass (»Inspiration«, »Trial and Error«).


Now you will have some preliminary, data based themes, each created based on a few data points.
Now we will see if these themes are useful for organizing more than just a few data points.

## Fill the Structure  
When you came up with some themes to structure your data
you need to see if the structure is feasible. Go through your data and
sort it into the themes – be it actual insights or just stated commonalities –  
you came up with, or just move the data into proximity to similar data.

The difference to the previous step is that we now focus on involving
all the data into the process of generating themes. In contrast,
in the previous steps we focused more on generating a structure.

If the previous step was building a (data-based) scaffold, now we try to build the actual walls.

![Build upon your preliminary structure to see if the idea actually works](images/lego_houseWalls.jpg)

Aim for 3 to 10 pieces of data per theme. While
it is temporarily ok to have very small groups, at the end each
theme should be derived from several data points and not on a single
utterance. On the other hand if a theme encompasses more than 10
utterances or observations, think if creating two aspects or
»subthemes« would make sense.

Usually I would go chronologically through all my notes starting with
the first participant and ending with the most recent one – though any
other scheme will suffice as well. Just be sure that you know with which data you
dealt with already and with which you did not.

When filling the data in the structure, you may notice that you need to
create additional themes. Some of the titles of the themes may need to be
renamed as well. Just go ahead and make these changes if you feel they are needed.

> - \[Title:\] Test in the media you target
> 	-   I folded prototypes for paper sizes that seem to be suitable
> 	-   This is close the print shops results without spending too much
> 	-   Tedious: Not having an own printer
> 	-   […]
>
> - \[Title\]»being closer«: Page Spreads instead of single pages
> 	- Creates page spreads (In books you have always 2 opposite pages, thus single pages are not useful for design)
>
> \
>
> Actually the example above is not great in terms of analysis:
 The »Test in the Media you target«  data is almost all from one
 person (P3) and the »being closer«-Group
 has only a single data point. In later iterations I'll change this
 group. But for now it suffices.
>
>\
>\
>
> While I was sorting the data I created a new group to accommodate data
 related to changes in designs:
>
>-   \[Titel:\]Changing and determining
>	-   Determining: What do we have? What do we need? What do we want to avoid?
>	-   Sketching, e.g. for »How can I divide the page for 7 days of the week?«
>	-   »This is trial and error«
>
>\
>\
>
>Some data could not be accommodated yet. So I created a misc
group, where I could offload the data for now and try to find a better
place later:
>
>-   \[Titel:\]misc
>	-   God: Shortcuts
>	-   I need to ask the print shop what this design would cost
>	-   Bad: Doing the same steps over and over again.
>	-   \[…many other points…\]
>
>Inside the misc group some possibilities for future insights
emerged – for example the first (god: Shortcuts) and the third
point (»bad: doing the…« could be part of a newly formed
insights named »I want to avoid repetitive tasks«


Now your groups will be informed by several data points each.
But there will be many themes which are created by the »same things mentioned«-Method;
they don’t state insights. In addition, there might be overlapping themes and groups encompassing
many data points  while other groups may be only informed by few data points
from just one participant. It is time to revise the structure.

## Revise the Structure  

After you went through your data and sorted it into themes ,
review your work. You now may have a clearer view of what
constitutes the themes after you sorted the data in these themes.

If you recently dealt with just a particular part of the analysis (like dealing
with two particular groups), your view might be too narrow: Glance over the
whole range of clustered data,  and rediscover themes which might be a better
fit for some data.

Have a look at structures that need improvement: Groups, which  have a title which
does not express an actual insight yet and data, for which you did not find a good place.
This data might be helpful to get insights and create new themes .

Take a critical look at the themes in relation to the data they encompass: Is there a fit or
did you fall prey to wishful thinking? Possibly there is actually only a weak match between
the stated theme and the data. In this case, revise your structure.


![Some parts need to be revised and newly created](images/lego_houseRevise.jpg)


### Find better names  

Groups based on commonalities or vague similarity will hopefully evolve
into insights about the participants. To archive this, try to revise group titles:
 make them more concise, clear and meaningful. If  a group of data is just named
with a title based on mere commonalities of the data in that group,
try to state an actual insight for a group . This will almost certainly
require moving some data between groups as well in order to
accommodate the data to the improved
structure.



> For one group I used the title »Arranging«, since arranging and aligning
 objects, lines and text to a predefined grid or to each other was a
 task that occurred frequently. But the title  »Arranging« just names a
 commonality. To make clear that the group is
 about a user activity and to state the theme as an insight,  I
 renamed »Arranging« to »Arranging objects is an important activity«


> One group was named »repetitive and manually«. This could be easily
 stated as an insight: »repetitive and ›do-it-manually‹
 tasks are tedious«. By just adding the users view (»are tedious«) the
 title became an insight which is a useful principle for design.

\
\

> I had the following structure:
>
> -   Inspiration
>	 -   Review previous projects
>	 -   Others (Web, Bookshop)
>
> »Inspiration« is a title based on the »same-things-mentioned«-principle so I had a look at
 the underlying data. They all were about inspiration – but they
 had another commonality: All inspiration techniques used
 other, existing designs, often ones that were created by the
 same person or even for the same project (It would have been
 possible that people take a walk or have frequent brainstormings or take drugs to get new
 ideas etc.). The insight I came up with was: »I use  existing designs for inspiration«


### (Re) Move data to other groups  

When improving your structure it might be necessary to remove pieces of data from
groups, either moving the data to a temporary »misc« group or to another, more suitable
group.

While we want to make use of the data we have, it is most
important to create sound and helpful principles based on the data –
instead of just  putting everything under a label.

It is possible that you can state an insight more clearly  insight more clearly by rewriting
the group’s title, but as a result, the clearer title
may no longer encompass all data in the group. In this case, go for clarity of the groups title,
even if it means that the theme does not encompass all the data currently subsumed in the group.

Take out the data that does not fit the improved title and see if it might
fit better to another group. If not, place it in a »not yet grouped« or
»misc«-Group. Revise that »misc« group when you made changes to your system and
see if you can use the data from that group to enhance other
groups with that data.


> I reviewed the following group:
>
> -   Feedback
>	-   Good: getting feedback
>	-   Bad: uncertainty before feedback from client
>
> \
> The title was not a meaningful insight and I felt that the
analysis might benefit if I use the data in other themes.
I already had a cluster related to motivations
and emotions– where I moved *»bad: uncertainty before feedback
from client«*. The *»good: getting feedback«* was moved to a
cluster named *»Exchange with others«*.

> While I think I gained something out of it, these changes
did not result in a new much better structure but was
part of trials and errors in the process.

\
\

> Going through the data of a group named »general requirements« I noted
that a big part of the data was concerned with balancing  
*functional* or *practical* requirements (price, readability etc.) with
requirements concerning *style* (using colors, being innovative)

> Thus, I renamed the group to »trying to combine aesthetics and
functionality«. As the new title was more specific some data needed to
be taken out, put into other groups or to the temporary »misc« group.

\
\

> The previous examples were concerned with whole themes and thus focused on the macro level.
Sometimes you just move data itself, without any trigger like renaming, just because
you found a better fit. For example *»using the maximum possible height
on a sheet of paper«* was grouped into »media«. Later, I moved it to *»budget«*
because budget is something the user is directly concerned with,
whereas media is even more abstract. The group *»budget«* was then later
renamed *»having little money and resources«*, expressing that a part of
the participants work was finding out how they could make the most out
of a small budget (*»using the maximum possible height on a sheet of
paper«* is a practice that results from that concern.)


### Create Subgroups  

Some groups may grow rather big, especially if their themes  are not insights
but are based on mere commonalities of underlying data (like
»dealing with color«). This is an excellent opportunity to develop themes
by creating subgroups. The process of developing subgroups
is like in  [»Develop a first structure«](#firstStructure) (just inside the group): Move
similar data in proximity and try to create clear-cut insights if
possible. In this process you might find a more suitable way to state
the theme of the main group as well.


> I had a group with more than ten points regarding »Colleagues and
Friends«. This title was rather general and thus not very useful for
design. I created two subgroups which were more meaningful.
>
> \
> Before:
>
> - Colleagues, Friends etc.
>	-   A friend told her that concrete is visualized dashed
>	-   Puts sketches on the wall: Others will see it and talk with me.
>	-   Which design do we take? Talks with fellow designer
>	-   […]
>
> after splitting and rearrangement:
>
> -   Exchange Knowledge
>	-   A friend told her that concrete is visualized dashed
>	-   Puts sketches on the wall: Others will see it and talk with me.
>	-   […]
>-   making decisions with others
>	-   Which design do we take? Talks with fellow designer
>	-   feedback-rounds with other designers
>

\
\


>One main point in my first structure was »Highly motivated at the
beginning; then the problems start.«. After restructuring this became
a sub point of motivation related groups.
>
>- \[group-of-groups\] Motivations
>	-   \[Subgroup\]: Highly motivated at the beginning; then the problems start.
>	-   \[Subgroup\]: Finishing is good
>	-   \[Subgroup\]: Waiting for feedback is bad
>	-   \[Subgroup\]: being afraid of clients rejection of the design

\
\

> Sometimes you first sort the data under the overarching title or principle
and then move it to an already existing subgroup later:
>
> The utterance: »Its bad that you can do imprecise things here,
compared to programming (talking about Illustrator)« was first sorted
into »Media« and subsequently put into »using the right media«


## Wrap it up  


![it’s done! (though you could still change some things or two…)](images/lego_houseFinished.jpg)

The steps above do build on each other. But like in other creative
tasks there will be a lot of going back and forth between steps of
creating groups, assigning data to them and revising these groups.

These iterations may also happen in parts of the structure you create.
 For example, after you revised your overall structure, you find that a grouping
should undergo a major change and you put all its data out. Then you are
back to developing a structure for a part of your analysis. Or you
notice that some notes that you moved in proximity can be summarized by
a clear principle, and you jump straight to the revision of that part of
the analysis, leaving the »fill in the data« step out.

This process can take up some time. The analysis may never come to an
actual halt, but it will slow down at some point. Continuing to move
data may still do minor improvements but there are no big changes
anymore. Review the data a last time. The analysis is finished and it is
time to communicate your results.


> **Final structure:**
>
> -   Arranging Objects as important part of the work
> -   using existing work for inspiration
> 	-   review previous projects
> 	-   use other’s work  
> 	-   use previous ideas from same project
> -   Media
> 	-   Test design in the target media
> 	-   Find suitable media
> -   Being attached to ones own ideas
> -   Working visually
> -   Social
> 	-   Exchange Knowledge
> 	-   Collaborative decision making
> -   Motivation
> 	-   Highly motivated at the beginning; then the problems start
> 	-   Finishing is good
> 	-   Waiting for feedback is bad
> 	-   being afraid of clients rejection of the design
> -   repetitive and manual work (negative)  
> -   changes and requirements
> 	-   Some changes like page format are hard to change later
> 	-   combine function and aesthetics
> 	-   changes cause other changes
> 	-   considering the budget
> 	-   trial and error as method
> 	-   use the actual content for testing (not fake content)
> 	-   fixate things to have a starting point
> -   Misc
> 	-   designer vs. technology
> 	-   making calculations
> 	-   choosing fonts
>
>These are all the groups I created in my analysis. The results could be
more concise, having fewer groups concentrating on fewer themes.
However, this would probably lead to more abstract insights which would
presumably harder to use in design.
>
>The groups of groups are partly not insights themselves. I tried to
find some, but was not able in a part of the cases: »changes and
requirements« is not an insight (but it’s subordinated
groups are: »combining functions and aesthetics« etc.). In contrast,
»using existing works for inspiration« is a group of groups which states
a meaningful insight.
>
>You see that I could not use all data, so I made some less significant
groups in the »misc« section.