# bonus aflevering - DeSci a Descentralised Open Science Ecosystem for FAIR research

**Alan:** Welcome to U B 20 30, the podcast about the University Library who has to innovate due to technology and policy driven changes in higher education and research. 

This is a bonus track, where our professor Philipp Koelinger talks about his startup De-Sci Labs, and De-Sci Foundation. De-Sci Stands for Decentralised Science. With De-Sci he wants to transform Science to an Open Science Ecosystem for FAIR research. Research that is made transparent and fully replicable. The ecosystems is able to reward those with attestations for Open Science practices. 

Let's now listen to Phillipp Koelinger...

...


## Introduction

**Philipp Koellinger:** So thanks everyone for joining this morning. So I'm I'm Philip Koellinger. I'm a professor in economics at the free university in Amsterdam. And I've done a lot of interdisciplinary research over the years. Worked in social science, genetics, worked with big data, have been working on open science practices and replicability for most of my career.

And then two years ago we started DeSci Labs and the DeSci Foundation with the goals to improve the way that science is being published and financed. And we're building technology for that. I'm going to tell you a little bit about that today. So I'm gonna start by just briefly mentioning some of the problems that we're currently facing in science.

And then I will start talking about the solutions that we're building. Some of the things that I'll be talking about is this concept of interoperable persistent identifiers that are based on content, addressed data storage. And I'll explain in much more detail what I mean with that. And Vida is actually a really powerful technology.

Then I'll talk a little bit about decentralized open data storage, open data, and this concept of interoperable dynamic fair digital research objects which we call DeSci node in which we have build an application that that went into beta testing two month ago and that people can already use and are using already.

And then if you still have a little bit of time at the end I'll briefly touch upon the co the concepts of content curation and branding using gateways. And I'll start brainstorming with you guys about some potential ideas for a pilot project that we may be running with with SURF. 


## Science is facing a Crisis

**Philipp Koellinger:** Let's get started by talking about the the current crisis that I think science is facing.

So there's many aspects to that, and I think it really goes pretty deep. It's a pretty at a pretty systemic level that, that we're facing serious challenges to a scientific progress at the moment. One of them is that the scientific publishing technology that that is still being run today is.

Still based on concepts that date back to the 17th century when we had the printing press. So what we have nowadays is basically it's an analog to that in the digital world, but not much else. But the problem is, of course, that science is not the same anymore as it was 300 years ago.

So one of the really major and important trends that that we're seeing at the moment is this massive growth of of scientific data and the importance of of computation and everything that has to do with it including accords and the the ability to run complex operations on huge data sets.

So we're currently estimating that around three zetabytes of scientific data already exist and this trend keeps growing exponentially. So three zetabytes that. 3 billion terabytes. So that's a whole lot of data. And that brings about, of course cost and infrastructure problems. So the truth is, of course, that a vast majority of that data is currently not being available to the public or to researchers.

It is also a problem for researchers who have really large data sets to make them accessible to the research community. So one one example for that, one of our colleagues he's a professor and statistical genetics at the Broad Institute at Harvard and m i t. And this group is developing new methods for for analyzing genetic data.

So on. Every time they develop a new method, there's usually also reference data that comes with it and that people need to be able to access in order to use these tools. Now he has been using the the service of the Broad Institute, as you can imagine. They have a very good infrastructure for that.

But he still faced a huge problem, which is that the data that he made available is so popular in the research community that just one of his papers that was published two years ago has about four terabytes of data. So it's not even that much, but just the fact that the research community was constantly downloading that data was creating.

Egress costs of more than a hundred thousand dollars a year that he didn't budget for, that he didn't have money for. So he basically sends an alarm on Twitter saying, guys, we cannot pay for this anymore. Somebody needs to come up with a solution, otherwise we need to shut down access to that data.

And then what happened is they literally shut down access to the data so nobody could access anymore. They moved it over to the Google Cloud. And now researchers who want to use that data have to pay to download it. So we came in and we actually offered him a solution and and we're actually going to make all this data and code and all the stuff that he has done available again on our platform in the next couple of weeks.

Another related problem is that the data that. Is currently being created and that people have doesn't fulfill fear requirements. So fear is this acronym that stands for Findable, accessible, interoperable and Reusable. It's a very powerful, very far-reaching initiative that is led by the Go Fear Foundation and that has enormous support from from policy makers and funding agencies from around the globe.

And one of the reasons why there is so much support for it is because not having data being fair actually creates a. Very substantial economic costs. So the EU has a study out that estimated that just for the EU countries themselves, not having faired scientific data creates over 10 billion of of wasted costs.

And it's primarily because there's duplications of effort and time wasted and these sorts of things. And it doesn't take even take into account that as a result of not having fair data, very often people are using suboptimal data sets. And there is just a slowdown in the rate of scientific progress.

Another issue is, of course, that the current internet technology is very much based on this concept of data silos which enable commercial participants in the scientific ecosystem to actually exploit that. And we know that publishers are doing that. And this is of course it's a problem for everybody who is on the paying and producing side.

And we have pretty bad incentives. So we have these problematic quantitative measures for scientific productivity where, basically you're doing counts of how much, how many papers somebody has published and what does the impact factor. And then the journals that are actually publishing that work, they primarily have a review mechanism that that evaluates the subject of novelty of of a contribution much more than the replica ability and reproducibility for which there is.

No wheel infrastructure to check that. And that of course produces really perverse incentives that contribute to this raging reproducibility and replica replicability crisis that we have in many fields and science, which are undermining trust and and scientific progress. 


## Towards a Research Record of Versions

**Philipp Koellinger:** If you look at the current unit of knowledge that we have in scientific publishing, it is, like I said, it is basically a digital analog of what the printing press was.

So we have an infrastructure for PDFs that publishers put on their websites, often behind a paywall. And then we have some very minimal metadata on top of that. And we have DOIs as PIDs, and I'll I have a little rant about DOIs prepared for you. But that's basically it. So that's the infrastructure we have.

There is no real infrastructure for data or for code or rep reproducibility or any of that. Which basically means that these important scientific artifacts such as data and code, they're very often lost. They're hidden or they're scattered around with very limited possibilities for the research community or even the public to, to interact with them and to reuse them.

So I think we need to move away from that and we need to move to a world where the actual unit of knowledge are. Digital research objects that are fair, enabling by design that are interactive, that are dynamic that allow creativity in new ways of actually sharing all aspects of a research objects and also making contributions to it in ways that we that we currently are not able to do.

And. All of that should happen ideally in based on an infrastructure that that is open source. So everything that is enabling that infrastructure needs to be open source. It also should be an infrastructure that is without paywall. So basically read and writes access and permissions for everybody without data silos or vendor login.

So that is really the future that, that we think is what we need to drive for. 


## The interactive scientific paper of the future

**Philipp Koellinger:** And related to that, we're actually rethinking the concept of the scientific paper. So rather than just having the static P D F, what we're thinking of is an interactive. Type of scientific paper that actually links the core results to the underlying data and codes that were producing them.

So think of the main figures or tables in a paper where in order to check how those results actually ended up being produced, you would wanna be able to check the data and the court, and ideally you would actually be able to to just run the court on that data directly and verify that the figure or the table that is in the paper really has been derived from these artifacts.

In addition, that research paper should actually enable. Updates over time. So rather than just having a static version, you can think of a paper that actually evolves over time, where the authors can actually collaborate with each other and and make improvements on that over time. And where it's also possible for others that are not part of the original authorship list to come in and suggest and make improvements to such a research object.

So think of, for example, data stewards. That could come in and that could improve the the quality of the metadata of of the data that is linked to that research article. Or think of other scientists in the field who actually provide additional contents content or context to a research paper by adding annotations.

And of course, you can also think of of peer review and other types of of contributions. So you may also think of other researchers who. Who add to such a research object or or project by adding additional analysis that that are either robustness checks that the original authors haven't done or that add new perspective on what the data is actually telling us.

And in these cases we're thinking of basically composable authorship tables that have git primitives in implemented, right? So you have an original version where anybody can then come in into this open state repository and actually suggest the fork to the original research object. That fork is also going to be publicly available.

And then you can send a merch request to the original authors. And if they actually think that you're making a very important contribution to their work, then they can accept the merch request. And then you have a new version of that research object which lists the new contributors, either as authors or as as a type of external contribute.


## DOI's are not persistent identifiers

**Philipp Koellinger:** Let me back up for a second and talk a little bit about the importance of having persistent identifiers on how we're currently doing this. Having persistent identifiers is really absolutely crucial for maintaining a scientific records that can be preserved over time, where people can find content over time.

And of course, we have the problems of link bot and content drift and the current internet architecture. So your URLs are obviously not persistent identifiers. So what we currently have as a solution are DUIs. And they're supposed to be solving these problems of linko and content drift. And ultimately what the d i system is the lookup table where the publisher basically mins a d i and then puts the URL to which that DOI's resolving into that table.

And if anything changes. So if you know the service structure changes or the journal is being merged or anything and the URL changes, they actually need to go into that database and fix that now. You won't be surprised that this is actually not working very well in practice. So there is a study that came out two years ago which basically showed that about 50% of all DOI's do not correctly result in a target resource.

And also do you not resolve to the to the target resource consistently. So you can actually get very different results for the same d i depending on the request method and the network environment from which you sent the request. So you may get very different results for a dui if, say you sit at surfer and you use your computer here, or you're using let's say a tablet somewhere in a village in Africa you may get very different results for that d y.

And then on top of that this manual updating, of course it, it requires a lot of work for the publishers. You will not be surprised that some of them are doing that much better than others. But overall the system is just very costly, inefficient and just very, like from a very strict technical perspective, DOI's are actually neither persistent nor unique identifiers for for these reasons.


## Content addressing based on hashes

**Philipp Koellinger:** So that is actually something that, that we can solve with technologies that are now available from the decentralized web. So in the decentralized web that problem is solved by the concept of content address data storage, which relies on cryptographic hashes that identify a particular piece of content.

So let me unbundle this a little bit. So what's a cryptographic hash? It is basically, it's a mathematical function that converts a string of arbitrary length. Into a string of fixed length. So it's a one way mathematical function in a sense that it is actually an encryption algorithm. So the content that you put in yields this this output string.

But once you have the output string, you cannot reconstruct what the input actually was. But if you have both, you can actually check that they're matching. So there's various algorithms for doing that. Probably the most widely used is called s h a 2 56, and that was originally developed by the National Security Agency of the United States.

And it creates a 64 hexa decimal string for any input. And now interestingly, if you change even the tiniest thing in that input, be it a single word, be it a single pixel, be it a comma, you're actually getting a totally different hash. And these hashes are statistically unique. So with that algorithm, you can actually create 10 to the power of 77 different hashes, which is literally billions of times more than we have atoms on planet Earth.

Which means that the statistical probability of you ending up with the same hash for two different pieces of output or or content, are a virtually zero. So for example, I could say I could make a prediction. I could say, man City will win the Champions League 2023, and I'm gonna get the hash on top, or I can say inter will win the Champions League 2023.

So just one word change and I'm getting a completely different hash. So that's basically this concept of of addressing content with these cryptographic hashes. And of course, once, once you have used such a hash to access the content, you can run the content through a cash calculator and double check that the content actually matches the address.

So with that system we actually have a data storage system that is immune to content drift and to link rot, which are two of the most fundamental problems of the current internet infrastructure. 


## DeSci Nodes

**Philipp Koellinger:** And with that we can now create a publication protocol for these rich. Digital research objects that have permanent identifiers in which we can then actually index on a public ledger where they will be available and where they can be searchable for everybody.

And that's essentially what what DeSci nodes are doing. And I'll show you what that looks like a little bit later. But in principle, these research objects, they can consist of various different components. So they may have manuscript, they may have data and code, and then for each of these components, so each of these files that belong to a research object, they would all have their unique hash, which is minted from the content directly.

And then there is a root Node of that research object which actually has two identifiers. One of them is a hash that is a combination of the hashes of the included research objects or research components. And the other one is a unique identifier is basically a random number. And then when the authors are ready to publish their work, then they literally press the the published button.

It gets distributed to this decentralized rep, to this peer-to-peer infrastructure. And then an entrance is written into a blockchain smart contract. That tells us that for this particular research object, this is the current hash based content address. Sorry. So what happens if you add a component to that?

So let's say that in addition to manuscript data and code, you now add a video. That video will also get its unique hash, and then the the hash of the root of the research object will be updated. And the new entrance is being written into a smart contract that says, so now there's a new version, and the new address is this.

And if you update a component, so let's say you have a new version of the manuscript you just upload that again, that gets its unique hash, which is different from the original version. Again, the hash of the root Node is updated and new entrance is written on this on this ledger. So that way this decentralized peer-to-peer infrastructure allows us to upgrade the scientific record from static manuscripts without persistent IDs or version control to these rich, dynamic, interoperable research objects that have persistent identifiers and allow for version control.


## Provenance

**Philipp Koellinger:** So here's an example of the metadata that that you would get on this public ledger. Blockchains are ultimately public ledger. So if you act if you actually index something on a smart contract of a blockchain, then you're basically making an entrance to this public ledger that can be accessed and queried by anybody.

And so the entrance is basically telling us who has committed this update, when did this happen? And then it lists the the current id the most current version of the research object and its unique identifier. And from there computer programs and people can then access all the metadata that belong to that research object and resolve it and address it.


## Distribution

**Philipp Koellinger:** Because that metadata lives on a public ledger, it basically means that the same version of that index will be stored on different servers at different locations operated by different storage providers. And the consensus mechanism of the blockchain ensures that the same version of the ledger is stored everywhere.

So we have the storage redundancy in a protocol that cannot be shut off or put behind a paywall. Instead of having the current infrastructure, which pr which basically generates a very limited amount of media data that feeds into the data silos of publishers, which then sell it back to the scientific community at outrageous prices.


## Descentralized Persistent Identifiers

**Philipp Koellinger:** So let me talk a little bit about the the persistent identifiers that we have in the system. So in addition to these content addressed hashes, we have created something that we call the decentralized Persistent identifier or D P I D. So that is basically our way of having unique addresses for each research object that allow you to reference not only the most recent version or a particular version of the past, but you can go down into a particular component of that research object.

For example, a data set or a code file. And you can even go further and you can actually address a particular part of the data set or a particular part of the code or a particular sentence in the paper. And there's basically two different formats for that. There is a long format. Which has the entire cryptographic gra hash of the root Node, of the research object.

No, that's great. For machines. They love that. But for humans, that's not very not very human friendly. So there's also a short version which is actually human readable, and human meaningful meaningful and. This is actually a really interesting thing because this is a solution to an alt problem in computer science that is called Zuko Triangle.

So Zuko wrote a paper in 2001 where he basically defined three desirable properties of a persistent identifier. And he said the ideal persistent identifier should be human friendly, meaning it should a chat have meaning and be memorable. Low entropy names. It should be secure in the sense that the amount of damage that a malicious entity can inflict on the system should be as low as possible.

And finally, it should be decentralized, meaning that the names should correctly resolve their underlying. Respective entities without the use of a central authority, which also means that there, there's not going to be a single point of failure and no no way of actually censoring that that that identifier or to commercially exploit it.

And Zuko originally proposed that it is actually impossible to have all of these three desirable properties at the same time. He said that you need to choose two out of the three, so you can have two out of three at most. But then 10 years later, the famous Aaron Schwartz, he actually wrote a paper that showed that it is theoretically possible to combine these three things to some extent.

And this D P I D system that we have created is literally a technical implementation of of that solution to zuko, SPRI triangle. So it's secure, it's decentralized, but it's also human friendly. 


## Operations on research objects

**Philipp Koellinger:** And with these DP IDs, you can now actually have new ways of interacting with these research objects that were previously not possible.

So the first one is, of course, that you can resolve to the metadata over the HTTP protocol which means that it is now possible for for crawling services and for software that people are writing to just do up to date analysis of what is actually out there what type of impact does it have, how are things connected to each other, and so on and so forth.

Second, you can actually use them as an address for edge compute jobs. So you could say so send this particular code to the data set that lives in that in that research object, and then run that code on the server where that data set is already stored. So that's basically decentralized compute.

And the infrastructure for that is actually also up and running already. And we're in the process of integrating it into our into our protocol. And it solves this really important problem that if you have very large amounts of data that you wanna analyze, you actually do not wanna move them around.

So there, there is this idea that data has gravity, right? So if you have a data set that is several hundreds of terabytes large, you really don't wanna move it around, first of all, because it takes so long. But then also because it is actually really expensive to do that. So there's always data egress cost if you move it around.

So instead what you wanna do is you actually wanna send the compute and run it on the server where the data already lifts. So that's that would be so much more efficient. And it would also create a track record about what type of computation has already been done by whom. And it would be a way for us to to avoid this unnecessary duplications of effort.

Furthermore, you can use these DP ideas to just import specific resources directly into your yo local compute environment. So you can sayi that and then use that DP i d and pull particular parts of code or data from that research object into your into your r compute environment or your Jupyter notebook or whatever else it is that you're using.

And then finally, these d p IDs can be used as addresses to send attestations to research objects. So what's an attestation? An attestation can be thought of as, let's say a batch that verifies. A particular type of quality that the research object has. So for example you could have a batch that says for this research object data is available, or code is available, or the results are actually reproducible.

We have checked it. The results the paper has been peer reviewed, it is now published in, or the research object was sponsored and endorsed by. All of these are just examples of attestations that you can send to these research objects and that will then be visible to anybody who actually surfaces and looks at these research objects.


## Decentralized data storage

**Philipp Koellinger:** Now let's talk a little bit about what data storage looks like in the system. The DeSci node system basically has two layers. So there's a private staging area where the authors are creating their research object and they can make edits and private, and when they feel ready, then they basically push it onto this decentralized peer to peer network, which is called I P F S which is short for interplanetary file system.

So I'm happy to tell you the story about why it's called bad later. But that's a side quest. And once you publish that, what happens is that there will be at least five. Identical copies of that research being stored by at least three different storage providers different entities that are providing these storage services and at least three different countries and and at least two different continents.

So you literally spread this around the globe. And this data redundancy is obviously, is a safeguard against data loss and it simultaneously protects against gender lockin. And one of the really interesting things here is that the I P F S system is completely open source. Anybody can participate from people that have a laptop or or a phone to commercial or professional data centers, such as serve.

And yeah. And it's also possible to basically have I P F S nodes or servers that, that have data which use the addressing system, but is actually still private. So there is a way how we can also store sensitive data on I P F S and have these persistent identifiers for them, but still be able to regulate access to particularly sensitive data.

So there, there is ways to make that happen and that network is is already up and running. There is Several hundreds of storage providers that are participating in it. It has literally like hundreds of exabytes of storage capacity, and it does that at extremely competitive prices. So storing data through that network actually means cost savings of up to a, like 95% or more comp compared to commercial solutions such as AWS or or fix share.

So that also means that it actually solves a lot of the financial and economic problems that, the data a of today's research brings about for the scientific community. And then finally for really very large and particularly valuable data sets, we we will actually have a sponsorship program through the DeSci Foundation where we can actually sponsor the long-term archival of those data.


## FAIR-enabling metadata

**Philipp Koellinger:** So a couple of words about FAIR enabling metadata. We talked about this concept of fear at the beginning. So again, just as a reminder, fear is this abbreviation that stands for findable, accessible, interoperable and reusable. And there is a number of of fear implementation principles that have been spelled out and articulated by the Gopher Foundation.

And they primarily focus on two major building blocks. One of them is the need to have a persistent identifier, which we have and the DUIs are not. And then second it's about the machine readability of the meter data. So ultimately what you want is that that a machine can actually tell what is that data and where can I find it and access it.

And there are several solutions how it can make metadata thes or is there's controlled vocabularies on ontologies and nano publications and all of them play a very important role in the ecosystem. But they're usually not very scalable and they usually involve a substantial amount of bureaucracy and negotiations.

And they also usually provide for really louser user experience and bring additional burden for the researcher. So in addition to that, we're actually working together with the goofier Foundation on a way. To generate a minimum amount of fair metadata just from the artifacts that researchers are uploading into their DeSci nodes by, for example, by using embeddings for for the paper.

And that the purpose here is that we wanna be able that even if people do not have the time or the expertise to actually link their research object with these controlled vocabularies or ontologies that that there is a minimum amount of fair data metadata that is automatically being generated and it just happens under the hood and the researcher doesn't even need to know about it.

They don't need to care about it, but we're still contributing to the fairness of the overall research ecosystem. 


## Open-state repository for FAIR interoperable research objects ...

**Philipp Koellinger:** So with all of that, we basically now have a full stack for sharing scientific research with with the world. So we basically have a separation between the data layer and the application layer.

So the data layer is this I P F S protocol where research is being stored and being made publicly available and it independent from that. But running on it is that application layer which is the DeSci Nodes application, but there may be others in the future. But the application layer basically allows you to create an update research objects and to view and interact with them.


## ... with compute integration ...

**Philipp Koellinger:** And then underneath that we're now implementing this capability of running compute jobs on the servers where the data is already stored. So this decentralized compute, which would allow the user to run reproducibility checks or to actually use these decentralized resources to actually do research.

And then there is the registration layer above that where we index the recent version of these research objects on that public ledger. And where we can see in a cryptographically verified way, who created what, when, who has the right to update this version and so on and so forth. Then we have the D P I D system which allows us to interact with these research objects and to resolve metadata from them.


## ... and shortened, human adapted PID's

**Philipp Koellinger:** And then finally, in the future that there can be an indexing layer where something like GraphQL Indexers could be used to create re and report real-time data analytics on that on that research that lives on that open state repository. 


## DEMO: DeSci Nodes

**Philipp Koellinger:** So at that point, I actually wanna show you what the DeSci Nodes app currently looks like.

As I said, this is this is in beta testing. But this is this is a Node here that has been created by NASA scientist and program officer Megan Ansel. So she's leading the open science initiative at at nasa. 

Yeah, so it's basically this browser interface and so you can basically scroll through the article and you can download it obviously. But then you have this this menu on the right hand side, which actually gives you access to all the other components of the research object.

So you can explore the code. So here, it then just basically connects to all the code that has been uploaded by the author. You can browse the data. So there is the data drive where you can go through the various data sets. You can download them you can address them specifically. And then let me show you what interaction actually looks like.

So you can browse through the annotations in this research object. So for example here there is a, there is an annotation that links figure one to the underlying data and code, and you can click it and then basically reproduce the the figure from from scratch by basically running the the compute on that dataset.

So I'm gonna try that again. Usually it doesn't work on the first time. Still a bèta, it's still a little bit buggy. So yes, here we go. So there we go. So we we have now run the code that that produced that figure, and we can double check it. And then you can basically scroll further through these various annotations and people can add them.

And then you can look at the at the activities that happen to that research object. So here you see the version history. So you can see that there is now five versions of this research object. And you can browse through and look at the previous versions. You can look at the credits, so the people that contributed to it and the people that sponsored it.

And then very importantly here are these attestations that I was mentioning. So this particular research object has two attestations. The first one says that this was an author collaboration between node stewards that helped to create that research object and the original authors of the work.

And that was a badge that was granted by the DeSci Foundation. And then there is a second one, which basically verifies computational reproducibility. And again, this has been issued by the DeSci Foundation. And in principle these attestations they can be created by trusted that entities and then sent you these research objects.


## Reporting: User Statisitics on EtherScan

**Philipp Koellinger:** This here is an example of the publicly available metadata that you can already see from the system. As I said, the system architecture basically creates this public record of user statistics.

So basically, each research object is a token that was minted by a specific user. That user is represented by its wallet address. And then if you go to ethers scan, you can see how many DeSci nodes have already been published and by how many users. And you can see how many nodes each user has created.


## Open Source Software

**Philipp Koellinger:** And as I said, of course, this is an open source project. So all our source codes is accessible at GitHub, at DESI Labs. Enter same as true for the D P I D systems, or all of that will continue to live in the open. And and we're very happy to have a growing, active community of developers in that system.


## Gateways - Content Curation and Branding

**Philipp Koellinger:** Now just a few final words about these ideas of content curation and branding in this in this ecosystem. So I actually think that content curation and branding have always been important in scientific publishing. But they will probably be even more important. So moving forward. In that open state repository, content curation and branding will happen through what we call gateway.

And you can think of content creation as a process that can happen at least on two different levels. So it could be on a personal level where you basically whitelist users where you say, I trust this person and whoever. And so if that person has new research, I'm just gonna feature it on my gateway.

Or you can say, I don't care about who has done that. I have some type of content curation review selection mechanism in place where I or my editorial team or my scientific society make a decision about what research we actually wanna surface. And you can of course, combine these two things.

So you can think of a curation mechanism that, that both whitelist users and does some type of content level curation. And then what you end up with is basically a reviewed repository that could be operated by communities and institutions. If you have only content level curation but no whitelisting of users, then ultimately what you have as a journal or you have a pre-print server with some light type of review FE features.

And if you don't do content level curation, you only whitelist users. Then basically you have an institutional pre-print server or repository that just automatically lists everything that your trusted users are creating. And if you do none of these things, then you basically have a gateway that will just have certain brows functions that give you access to all the node that were created.


## Gateway functions

**Philipp Koellinger:** And so what is the gateway then actually doing? It surfaces content from that open state repository through your own website. And then the gateways, they control their own D P I D prefix. So for example, there could be dpd.org slasher, or for the view maybe dpd dot org slash vu. And then through that gateway, people can submit their research.

And then you have, as a gateway operator, you have fine grain control over the the user interface and branding. So of course, you control how you display that content on your own website. And then basically the content that is being surfaced through your D P I D address or your gateway can actually have a branded Node viewer.

So where the PDF viewer that that I showed you earlier can have the branding of your institution or your journal or whatever you are. And then these gateways can provide at the stations. So they can act as these trusted third parties that can say here's certain characteristics of a research object that we have verified, and that we now tell everybody that this research object fulfills these requirements.

And then the gateway repository, they can manage permissions on the Nodes app for their whitelisted users. So for example, they can give them access to edge computing and in browser computing capabilities, they can give them right to publish to their gateway prefix. And of course, they can give access to large data storage plans.


## Gateways - Frontend and Dashboard

**Philipp Koellinger:** So Gateway is then basically at the front end is just the website of the institution where you have an ability to then just basically pin Nodes and then show them on your website. And on the back end, there is a dashboard where you choose your creation mechanism where you have analytics, where you can manage your attestations, and where potentially we can have integrations with other software systems that That matter for you as an institution.

So that's basically the idea. 


## Brainstorm: FAIRpilot project with SURF

**Philipp Koellinger:** And with that, I just wanna bring up like one of many potential possibilities that that we may have for actually working together. So let me just tell you that I, as a researcher I have always been incredibly grateful that I actually ended up in the Netherlands and that I was able to use the se compute infrastructure.

So my team and I were one of the like very intensive users of the SEF infrastructure. And this is really bread and butter. And I had this this episode where I was at least on paper, hired by a very famous US University for a while. And they promised that they would be able to give me everything that Surf has and they never delivered it.

And I just, that just made me realize just how incredibly valuable these services are that you guys are offering. And in any case so one thing we could do together is, for example, a pilot project that, that tests the the ability of this of this new infrastructure to actually mirror some of the data that you have and to to make it fair and open.

That would require actually identifying some of these data sets that researchers have created on your system. Figuring out if those data can be put into the open, and then we can work together with the researchers to actually mirror that data to create these research objects, ideally make them reproducible and then adds metadata and make it fair and openly available.

So that could be a first user case. And in the future, I think it is possible that serv could, for example, run their own gateway, which would enable researchers to actually publish their data make it fear and and interoperable and available to the research community and just participate in this open state repository for science.

And so th this would be a very interesting use case because this would literally be the first like major data and infrastructure provider for the scientific community that would do, that we are already in in talks with the free university, but also with with several publishers including Springer and Nature and PLOS, who are very interested in doing something similar.

And there's also conversations that are going on now between us and bioRxiv and medRxiv who could also basically enable their users to, to create research objects and to serve as a sort of gateway. So with that thanks for your attention and I'm really looking forward to to the discussions and questions we will have.

