---
layout: default
title: 2 Methodology
description: "Chapter 2 details the methodology of agile project management adapted for practice research, discussing iterative cycles in developing BCMI systems for meditation support in NFT and artistic performance settings, and outlines the literature review method."
keywords: "agile project management, practice research, bcmi systems, neurofeedback therapy, meditation, artistic performance, literature review method, interdisciplinary research, eeg sonification, music therapy."
nav_order: 7
permalink: /docs/02-methodology
---

# 2 Methodology

{: .no_toc }

## Table of contents
{: .no_toc .text-delta }

1. TOC
{:toc}

---

## 2.1 Agile Project Management
To guide my practice research and address emerging questions and methods, I adapted ideas from agile project management (APM), a framework that transfers principles from agile software management to general project management (Drechsler and Ahlemann, 2015). While traditional waterfall project management focuses on one important outcome at the end of the project, APM produces cumulative outcomes by iterating the cycle of development stages. These cumulative outcomes can result in benefits throughout the process, not only for one project but also for other projects running parallel. As the iterative cycles of the projects running parallel during this research often informed each other, the flexibility of APM proved to be a practical method for managing the research overall (Fig. 2.1).

![An illustration of APM's use in my research. The large diagram (middle) illustrates all research projects with examples of how they informed each other. The two smaller diagrams (top right and bottom right corners) contrast APM with traditional waterfall management, indicating stages and outcomes. An alternative layout of the projects can be seen at [https://bcmi.khofstadter.com/timeline](https://bcmi.khofstadter.com/timeline).](../assets/img/apm-all-projects.jpg) <center>Figure 2.1: An illustration of the use of APM in my research. The large diagram (middle) depicts all of my research projects with examples of how they informed each other. The two smaller diagrams (top right and bottom right corners) contrast APM with traditional waterfall management, indicating the different stages and outcomes. An alternative layout of the projects can be seen at https://bcmi.khofstadter.com/timeline.</center>

The non-linear and practical aspects of my research inquiry are captured in how Miranda (2014) outlines their approach to developing BCMI systems:

> Our approach is hands-on orientated. We often start by dreaming scenarios followed by implementing proof-of-concept or prototype systems. Then, as we test these systems, we learn what needs to be further developed, improved, discarded, replaced, and so on. These often lead to new dreamed scenarios and the cycle continues incrementally. In reality, … vision, practice and theory do not necessarily take place sequentially in our research.

The concept of practice research is commonly separated into two types: practice-based and practice-led. While practice-based creates an artefact that is the ‘basis of the contribution to knowledge’, practice-led ‘leads primarily to new understandings about [the] practice’ (Candy, 2006). However, as Bulley and Sahin (2021) state, these definitions and the interchangeable use of related terminology (e.g. ‘creative arts research’, ‘practice-as-research’) have often confused researchers. As established earlier, the main contributions of my research consist of the creation of the BCMI-2 system and my recommendations based on the knowledge gained while developing and testing its suitability to support meditation practices in NFT and artistic performance settings. Therefore, my research can be considered both practice-based (as it created a proof-of-concept technical BCMI system) and practice-led (as it provides recommendations based on my new understanding of the practice). I used the following five APM stages in the BCMI-1 and BCMI-2 projects:

**(1) Goals**  
During this stage, I used the RQ and the ROs, the relevant findings from the literature and the outcomes of previous or parallel-running projects to inform the project goals. I reviewed the literature using keywords through my university’s digital search engine and Google Scholar and examined relevant publications. As each project had different goals, the keywords, publication date ranges and resource types in my searches were changed accordingly. Literature was often downloaded in the form of PDF files, which were then skimmed or scanned. Relevant information was highlighted and labelled with a continuously evolving list of tags, including the following:  

#are, #art-science, #asc, #bci, #bci-art, #bci-science, #bci-sound, #consumer-grade, #eeg, #emotive, #engagement, #ibva, #immersion, #meditation, #muse, #music, #musification, #neurogame, #neuromarker, #neurosky, #nft, #off-line, #on-line, #openbci, #performance, #reseach-grade, #serious-gaming, #shamanism, #sonification, #sound, #sound-design, #substance-alternative, #supercollider, #surround-sound, #systematic-review

**(2) Design**  
In this stage, to help meet the project goals, I often drafted creative concepts (probable narratives) in a physical notebook with colour-coded drawings and text. I later fine-tuned these notes on the computer using Markdown language in Visual Studio Code (VSC) and Adobe Illustrator. Later in the research process, I organised my notes using the Zettelkasten – also called the Second Brain – method (Schmidt, 2016), which was provided by the Foam VSC extension (Ferretti and Eväkallio, 2020). Foam’s non-hierarchical tagging and visualisation helped me see connections between the concepts in my notes.

**(3) Development**  
This stage used prospective concepts that were established in the design stage. In some projects, I developed software for interfacing, and in others, the requirements for testing the developed software. In the listening study project, this stage resulted in the development of an accessible online survey.

**(4) Testing**  
This stage consisted of testing the developed concepts. For instance, while BCMI-1 was tested informally by participants at my residence and at events where I demonstrated its use, BCMI-2 was tested in two types of formal settings: NFT and performance settings. In addition, my ARE that gradually decreases in tempo and rhythmic complexity was tested in the online listening study using SurveyMonkey. This study utilised SoundCloud's audio player without interactive audio (i.e. without using the neurofeedback protocol of the BCMI-2 system).

**(5) Deployment**  
In this stage, in addition to analysing data from the testing stages to draw conclusions, I often demonstrated and presented my progress at public or academic events and published code on GitHub, music on Bandcamp and videos on YouTube. I also used OpenOffice and RAWGraphs to analyse the data collected with SurveyMonkey. The final deployment of the research consisted of generating this commentary, which was written in Markdown and exported to PDF with Pandoc’s LaTeX converter.

**Examples of APM cycles** (also called sprints): 

Here is a typical example of APM cycles in which, after the testing stage (4), parts of the project need to be redesigned (2), redeveloped (3) and retested (4) a few times before achieving an outcome:

APM stages 1,2,3,4,2,3,4,2,3,4,2,3,4,2,3,4,5, cumulative outcome, 1,2,3 ...

What follows is an example in which the development stage (3) highlights issues in design (2), and hence, the project needs to be redesigned (2) before testing:

APM stages 1,2,3,2,3,2,3,4, ...

Next is an example in which the design stage (2) highlights issues with the goals (1), which then need readjustment:

APM stages 1,2,1,2,3,4,5, cumulative outcome, ...

## 2.2 Literature Review Method
In order to logically narrate my literature review in Chapter 3, I organised it thematically. However, to help articulate the research inquiry that has emerged in my practice, I will outline its chronological order in four stages:

1. Initial: before the start of the research
2. Exploratory: Autumn 2015 (start of research)—Summer 2018
3. Focused: Summer 2018—Summer 2019
4. Refined: August 2021—December 2021

Before I began this research, during my BA and MA studies in Creative Music Technology, I used the EEG hardware IBVA and NeuroSky with Max/MSP and SuperCollider software for artistic purposes (Hofstädter, 2009; 2013). After my MA, I wanted to gain a deeper understanding of the use of EEG with sound and apply this understanding beyond entertainment to help myself and others manage stress. This desire led me to conduct my initial literature review, in which I examined NFT and music therapy publications and discussed my initial ideas with key researchers in these disciplines. Amongst these researchers were Prof Jörg Fachner at the Cambridge Institute for Music Therapy Research, who later became my supervisor, Dr Tony Steffert, a London-based NFT practitioner with extensive knowledge regarding EEG sonification and Dr Eric Miller at Montclair University, author of Bio-Guided Music Therapy (2011). The initial literature review and subsequent discussions highlighted that there had been little investigation into the combined use of NFT and music therapy and that most software used in NFT primarily used visual feedback. Where the software used auditory feedback, it was old-fashioned. In other words, these systems did not employ modern software’s many available techniques for mapping classified brain signals to sound control parameters. For example, in one of our early correspondences, Miller (2012)
wrote:

> One of the reasons I wrote my book was that I also found that most NFT programs blatantly neglect the wide capabilities of audio and music, and I could find hardly any other works that attempted to integrate music and NF in more than just a basic manner.

Feeling encouraged, in my research proposal, I put forward to develop a new music-based invention, a BCMI system capable of utilising a wide range of compositional techniques for NFT that could strengthen many aspects of music therapy. First, NFT can make music-based inventions more interactive and engaging since users can not only see how their state of mind is affected by listening to music, but they can also affect the music with their state of mind in real time. Second, NFT can support music therapy's intangible experience with quantitative data from brain analysis. This proposal was the point of departure for this research.

This doctoral research began with an exploratory literature review, in which I continued the study of the domains of music therapy and NFT while extending its scope to others (e.g. meditation, spatial audio, serious gaming and, later, auditory entrainment). Parallel to this review, I was developing the BCMI-1 system by implementing ideas that emerged in this review (e.g. gaming elements for accumulative neurofeedback protocols and musical elements to support concentrative and receptive meditation). This stage of the research clarified that meditation was the method I wanted to explore for stress management and that I wanted to support meditation by combining a neurofeedback protocol inspired by Jeff Tarrant’s work (Tarrant, 2017) and ARE inspired by Jeff Strong’s work (Strong, 1998).

While further exploring these two methods in my **focused literature review**, I began addressing BCMI-1's limitation linked to its single, fixed EEG channel, by designing the multi-channel BCMI-2. Having a system that can record multi-channel signals from various locations on the head was important, as several neurofeedback protocols linked to enhancing meditation practices (including the NeuroMeditation protocols by Tarrant) use locations other than the forehead and more than one EEG channel. During this review, I completed the development of BCMI-2 with the idea of combining a neurofeedback protocol that would reward increased theta brainwaves with ARE that would gradually decrease in tempo and rhythmic complexity. I synthesised this idea through my literature review findings and discussions with Tarrant, Strong and several shamanic practitioners – all of which helped me become more experimental and intuitive in my drumming during my meditation practices. The system’s suitability for supporting meditation was first demonstrated with two participants in NFT and later – as a natural progression – in an artistic performance setting. To further explore the ARE used in these settings, I conducted a listening study (Section 5.6) in which most participants experienced an increase in focus (67%) and recalled being at their most focused state towards the end of the soundscape. In this proof-of-concept research, this outcome does not contribute to scientific knowledge with evidence on the effectiveness of the ARE that gradually decreases in tempo and rhythmic complexity. It only strengthens my understanding of, and trust in, the potential of ARE in supporting meditation. In order to provide scientific evidence for the effectiveness of different ARE and neurofeedback protocol parameters and their combinations, I plan to conduct more studies with scientific rigour.

Finally, I conducted my **refined literature review** to help better situate my main contribution to knowledge. This review enabled me to provide a brief overview of the use of BCMI in artistic performance and academic research settings and describe the related classifications for sonification and musification with active and passive user control. This stage also helped refine my RQ and ROs so that they better reflect my main contribution. 

Throughout the years, my research has undergone numerous changes and has turned out to be more complex than I envisioned initially. Still, I think the overall approach was effective; it resulted in a stable BCMI system that can be used to support meditation practices in two different settings. Furthermore, I hope my experience, as outlined in this written commentary, will help researchers better understand the interdisciplinary processes involved in developing BCMI systems for meditation.
