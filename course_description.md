---
title: "Course description"
---

**TODO**
- morning/afternoon split in theoretical/practical is not maintained in the lessons, perhaps remove?
- update data section 
- add project description
- add grading rubric (more detailed breakdown, e.g. originality).

**END TODO**

# Viromics - Big data analysis and interpretation (MMB019-9)
An advanced module of the Masters program in Microbiology at Friedrich-Schiller University of Jena.

## Prerequisites
Before the first day of the Viromics module, please set up your laptop according to [these instructions](https://mgxlab.github.io/Viromics2026/laptop_setup/index.html).

## Purpose and contents of the class
Metagenomics of viruses, often referred to as viromics, is the study of viral communities in a sample or environment by directly sequencing and analysing their genetic material. Unlike approaches that rely on virus isolation or cultivation, viromics can capture both culturable and unculturable viruses, allowing the discovery of novel viruses and characterising whole communities. 

In this class, you will learn how to analyse bacteriophage sequences using computational approaches. The workflow will cover:

- Sequencing quality control
- Assembly of long-read sequences
- Identification of viral contigs
- Open reading frame (ORF) prediction
- Gene annotation
- Host prediction
- Viral taxonomy and phylogeny
- Data visualization

{% include base_path.html %}
<p align="center">
    <a href="{{ site.carpentries_site }}"><img src="{{ relative_root_path }}/assets/img/logo_no_highlight.png" alt="Viromics workflow" width="1600" /></a>
</p>

## Data

We will be using viromics sequencing data from Natia Geliashvili, a PhD student in [the VEO  Group](https://veo.uni-jena.de/). The samples came from a sediment/river microbial community, into which a target phage and its host were added. The samples were passed through a 0.22um filter and sequenced using [Oxford Nanopore Technologies (ONT) long-read sequencing](https://nanoporetech.com/platform/technology). 

## Course structure

The theoretical parts of the course are covered in the mornings. This includes reading relevant papers, watching video lectures, and discussion of the concepts and tools.

The practical parts of the course are covered in the afternoons. You will work with real viromics data and use a range of bioinformatics tools to analyse and interpret the data. The focus is on understanding the concepts, evaluating the results, and drawing biological conclusions rather than on programming itself. Some basic command-line and scripting skills are required, and we will be available to help and guide you.

_Solutions for each step are provided. Try to complete the exercises yourself first, but use the solutions if you get stuck or need to move on to the next step._

Each day will end with a plenary discussion of that day. Your participation in this discussion will be important part of your final grade (see below). 

During the second week of the course, you will work on a small independent project using the viromics data and approaches introduced during the course. You will develop a question that you find interesting and design the appropriate bioinformatics analysis to investigate it.

## Final Presentation

You will give a final presentation on Friday 11 September. This is where you can demonstrate your understanding of the material and share what interesting techniques you came up with.

## Final evaluation

Your final grade is based on an evaluation of three factors.
- Participation and engagement (asking questions, helping others): 40%
- Daily practical reports: 20%
- Presentation of your final project: 40%

## Statement on AI/Large Language Model use
Large language models (LLMs), such as ChatGPT, Le Chat, and Claude, are increasingly becoming part of the daily work of bioinformaticians. **Nevertheless, we advise you not to use LLMs during the practicals of this course.** This is not because they are never useful, but because using them may hinder your learning more than it helps. We want you to focus on understanding the concepts and analyses yourself. We provide scripts where you mainly need to modify parameters and interpret the results, and discussing questions with your fellow students or the TAs is more useful for your learning than asking an LLM.

**If you decide to use LLMs, you must include a sentence explaining how you used them in your daily report.**
