# AI & Law survival guide: a technical perspective

## TLDR 
> Doing a PhD at the intersection of AI and Law is challenging in many ways. One of these is the lack of guidance and resources that one can find online. With this survival guide I aim to create a non-exhaustive, imperfect, biased list of resources and advice that I wish I had access to when I started my PhD. 

## Why am I writing about this?

When I started my PhD at the intersection of AI and Law I could find very little information about it online. I knew AI research was usually published at conferences such as ICML, NeurIPS or ICLR and that legal research was mostly published in journals or as monographs. But where could I find papers working on both?

Quickly I came to realize the angle one could approach this intersection could lead to completely different kinds of research. If approaching AI as a tool to be used in the legal domain then one could aim to predict the outcome of a case by looking at the case text and relevant regulations, one could also use AI as an information retrieval system that helps either in finding relevant regulations or evidence. If approaching the law as a software engineering requirement for AI systems then interesting problems could arise both in terms of improving compliance with such requirements or assessing said compliance. 

My research focuses mostly on the latter (and mostly to the EU context), so this document will be biased towards it.

I would love for this to become a more broadly useful resource so please feel free to submit PRs or issues to include further thoughts, resources, or other useful information! 

## The friction
While there are plenty of resources and guidance on doing a PhD ($P$), doing an interdisciplinary PhD ($IP$), doing a law PhD ($L$) and doing an AI PhD ($A$), this is not so much the case for doing a PhD at the intersection of AI and Law ($AL$). 

Sadly, standard set theory does not apply here. The intersection is its own distinct beast:

$$
AL \not\subset [P \cup IP \cup L \cup A]
$$ 

Much of the advice you may have heard from other disciplines is hard to translate. The following are some of the sources of friction that you may find in conducting your research:
1. AI is a relatively new and rapidly evolving field
2. AI regulation is relatively new (newer than 1.) and rapidly evolving (less rapidly than 1. but faster than regulation historically does)
3. AI regulation is uncertain: one of my first findings about regulation is that the text is far from being everything. Often other (just as important if not more) processes can shape how a regulation is implemented such as standards, case law, judicial interpretation, compliance approach, omnibus packages, political will, and more! 
4. Law and AI mix as well as water and oil: while interdisciplinary research comes with its own set of issues, AI and Law are two fields that are especially difficult to connect. This is due to many reasons
   1. Current AI deals in probabilistic/statistical approximations, Law often prefers to deal in absolutes
   2. Legal papers and AI papers use different language, formats (LaTeX vs Word), citations, structures, and are published in different venues
   3. Law and AI research have very different incentive structures! While in legal research journals are the most prestigious; in AI research conferences are usually considered more so. While in legal research a single-author paper is the ideal; in AI research these rarely exist since collaboration is more common and smaller contributing roles also lead to co-authorship. 
5. Choosing your main audience and scope (who you want to do what?) will make the writing process very non-linear. But it's an important choice that can help avoid making your work feel either too trivial or too complex. 
6. Cool technical experiments are very difficult to align with regulations and/or relevant legal insights.  

## The grease
Sadly, there are no definitive solutions to these sources of friction. But there are some mindsets, approaches and ideas that can make things go more smoothly:
1. Say the right things, in the right way, to the right people: decide whether your message will have a stronger impact in one community or the other, and format your paper accordingly to fit their expectations. This does not mean that you should avoid addressing the other community, rather that you facilitate reading your papers for your primary audience. This is a process that you will have to iterate over repeatedly for your paper and that will require feedback from different researchers to ensure you get it right. Here LLMs can sometimes be useful to see how the issue you want to present could be phrased for either audience and which one you'd prefer to go forward with. 
2. Make sure your technical solutions are solving a real legal problem: often, the challenges related to regulation are more complex than they may seem. A common mistake AI developers make is over-simplify legal issues leading to advanced technical solutions that solve non-existent issues or that don't solve a problem at all. 
3. Simplify where possible: a full in-depth innovative legal analysis combined with state-of-the-art technical innovations with exhaustive experiments is not a paper, it's a PhD dissertation. So very often, you will have to decide where it's more important to go in-depth, what can be simplified and what should be a part of a different paper. 
4. Stay curious, humble and informed: this applies to most research, but especially so in the case of interdisciplinary research. Very often you will talk to people that know more about Law or AI than you do. So listen and ask questions, be open about what you don't know and be ready to update your priors. 
5. Learn to explain things simply: extracting the relevance of your research for different people is a skill and takes practice. I quickly learned that using the words "compliance" and "regulation" in a technical conference will lead to yawns, as will the use of words such as "loss landscape exploration" or "model multiplicity" in a legal conference. So it is important that you meet people where they are, decide on which aspects they may find most insightful and take them outside their comfort zone only one step at a time. 

## Beyond academic research
Very interesting research and discoveries in this field are happening outside academia. While journals and academic conferences can be useful, do not underestimate how much you can learn from industry and regulators. 

I've found [Anthropic's alignment and interpretability research](https://www.anthropic.com/research) to be particularly interesting on the industry side. In terms of regulators, research from the EU AI Office and Joint Research Centre (JRC) can sometimes be found at conferences, such as [here](https://icml.cc/virtual/2025/48352) while the [UK AISI](https://www.aisi.gov.uk/research) shares their latest research on their website. 

Another interesting source for insights specifically into regulations are technical standards. These often include details about possible technical implementations of regulatory requirements, therefore providing a more granular technical view on the requirement. A challenging aspect about these technical standards is that you often have to pay to get access to them, but sometimes university libraries can provide them. 

## The keyword salad

While for other fields it's easy to identify relevant research, this is hardly the case for me. I've found the events that I discuss in "Relevant events" to be a useful place to find interesting research, [Scholar inbox](https://www.scholar-inbox.com/) also helps in building a digest of relevant papers. I've also come to collect a bit of a keyword salad that can come in handy as a low precision high recall approach to identifying potentially relevant research. 

These are some of the fields that can sometimes intersect with my areas of interests: 
* AI safety
* AI alignment
* Interpretable AI
* Trustworthy AI
* Responsible AI
* Private AI
* Robust AI
* Technical AI governance. 

While in terms of potentially interesting techniques I've had some success with: 
* Continual learning
* Machine unlearning
* Model multiplicity


## Relevant events
Conference workshops are a great entrypoint into the field, since they showcase relevant work, allow you to meet some of the people who actively contribute to it and allow you to present your work. Below I include a list of workshops I keep an eye out for:
* [RegulatableML](https://regulatableml.github.io/) (NeurIPS)
* [Private Governance & Oversight Mechanisms for AI](https://sites.google.com/adalovelaceinstitute.org/paig-eurips) (EurIPS)
* [Technical AI Governance](https://www.taig-icml.com/) (ICML)

In terms of conferences, the ones I've heard most commonly discussed especially when aiming to contribute to the intersection of AI & Law (and with other fields) are [ACM Conference on Fairness, Accountability, and Transparency (FAccT)](https://facctconference.org/), [ACM Symposium on Computer Science and Law (CS&Law)](https://computersciencelaw.org/2026) and [AI, Ethics, and Society (AIES)](https://www.aies-conference.com/2025/). 

Some topic specific events that I've found interesting are
* For benchmarking and evaluation:
  * [The science of benchmarking and evaluating AI](https://sites.google.com/view/benchmarking-and-evaluating-ai) part of EurIPS
* For privacy:
  *  [CPDP](https://www.cpdpconferences.org/)
  *  [Privacy Law Scholars Conference Europe](https://plsc-europe.eu/)
* For model multiplicity:
  * [MURE workshop](https://sites.google.com/view/rashomon-aaai-workshop/home) part of AAAI
  * [The many faces of Multiplicity in ML](https://prakharg24.github.io/multiplicity-tutorial-aaai/) part of AAAI. Includes an extensive reading list on the topic

## Miscellaneous Resources
Programs/fellowships:
* [Cambridge ERA:AI fellowship](https://erafellowship.org) a fellowship focusing on AI safety & Governance. 
* [MATS program](https://www.matsprogram.org/) a seminar program providing mentorship in the fields of AI alignment, transparency, and security. 
  
Tools:
* [AI conference deadlines tracker](http://aideadlines.org/?sub=ML,CV,NLP,RO,SP,DM,AP,KR,HCI,IRSM,MISC) to stay on top of upcoming AI conference deadlines
* [Scholar inbox](https://www.scholar-inbox.com/) useful as a recommender system for papers, especially when planning to attend a large conference to identify the most obviously relevant papers
* [Google Scholar Labs](https://scholar.google.com/scholar_labs/search): a RAG search tool to look through papers available in google scholar. 

Miscellaneous: 
* [Various papers, datasets, models and events](https://nllpw.org/resources/) shared by the Natural Legal Language Processing workshop part of the [Conference on Empirical Methods in Natural Language Processing](https://2025.emnlp.org/). 
 



## About me

I am a PhD candidate at the Law and Tech Lab of Maastricht University. My research focuses on approaches to ensuring the safe deployment of AI models. By approaches, I mean everything from computational techniques, to recommendations on how to adequately assess compliance with regulations. I care less about the specific tools that are used and more about the outcome I'm trying to achieve with them. 

My MSc was on Artificial Intelligence and my BSc was on Data Science and Artificial Intelligence. My research before the PhD focused on varied applications to biological sciences, such as pharmacogenomic models for drug-resistance prediction, mouse behavior detection in neuroscience experiments, binge-eating episode forecasting, or genome-scale metabolic models. So while I had some experience doing interdisciplinary research, law was a completely different beast for me. 
