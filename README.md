<!--

author:   Alexander Botzki, Bruna Piereck, Jolan Heyse
email:    training@vib.de
version:  1.0
language: en
narrator: UK English Female

icon:     https://vib.be/sites/vib.sites.vib.be/files/logo_VIB_noTagline.svg

comment:  This document shall provide an entire compendium and course on the
          development of Open-courSes with [LiaScript](https://LiaScript.github.io).
          As the language and the systems grows, also this document will be updated.
          Feel free to fork or copy it, translations are very welcome...

script:   https://cdn.jsdelivr.net/chartist.js/latest/chartist.min.js
          https://felixhao28.github.io/JSCPP/dist/JSCPP.es5.min.js

link:     https://cdn.jsdelivr.net/chartist.js/latest/chartist.min.css
link:     https://cdnjs.cloudflare.com/ajax/libs/animate.css/4.1.1/animate.min.css
link:     https://raw.githubusercontent.com/vibbits/material-liascript/master/img/org.css
link:     https://cdnjs.cloudflare.com/ajax/libs/font-awesome/5.11.2/css/all.min.css
link:     https://fonts.googleapis.com/css2?family=Saira+Condensed:wght@300&display=swap
link:     https://fonts.googleapis.com/css2?family=Open+Sans&display=swap
link:     https://raw.githubusercontent.com/vibbits/material-liascript/master/vib-styles.css

tutor:    Application of Generative AI for Scholarly work
edition:  1st 

@JSONLD
<script run-once>
  let json = @0 

  const script = document.createElement('script');
  script.type = 'application/ld+json';
  script.text = JSON.stringify(json);

  document.head.appendChild(script);

  // this is only needed to prevent and output,
  // as long as the result of a script is undefined,
  // it is not shown or rendered within LiaScript
  console.debug("added json to head")
</script>
@end

orcid:    [@0](@1)<!--class="orcid-logo-for-author-list"-->
-->

#  Application of Generative AI for Scholarly work

Lesson overview
----------------

> <i class="fa fa-lock"></i> **License:** [Creative Commons Attribution 4.0 International  License](https://creativecommons.org/licenses/by/4.0/deed.en)
>
>
> <i class="fa fa-user"></i> **Target Audience:** Researchers and Research staff
>
>
> <svg xmlns="http://www.w3.org/2000/svg" height="14" width="16" viewBox="0 0 576 512"><!--!Font Awesome Free 6.5.1 by @fontawesome - https://fontawesome.com License - https://fontawesome.com/license/free Copyright 2023 Fonticons, Inc.--><path d="M384 64c0-17.7 14.3-32 32-32H544c17.7 0 32 14.3 32 32s-14.3 32-32 32H448v96c0 17.7-14.3 32-32 32H320v96c0 17.7-14.3 32-32 32H192v96c0 17.7-14.3 32-32 32H32c-17.7 0-32-14.3-32-32s14.3-32 32-32h96V320c0-17.7 14.3-32 32-32h96V192c0-17.7 14.3-32 32-32h96V64z"/></svg> **Level:** Beginner  
>
>
> <i class="fa fa-arrow-left"></i> **Prerequisites**  
> 
> No prior knowledge of Machine Learning or coding expertise is required
>
>
> <i class="fa fa-bookmark"></i> **Description**  
> 
> Generative AI technologies are quickly becoming an essential part of the academic research toolkit, supporting tasks to create, analyze, and structure information. This training provides a foundation in the core principles of generative AI, their capabilities and limitations, and explores how these systems can be applied responsibly in scholarly work.
>
> During this training, you will explore different AI tools in supporting tasks from literature reviews to content drafting, summarization, and visualization. We will also introduce how you can leverage AI agents to execute actions with predefined context and instructions. You will learn how to design effective prompts to generate high-quality outputs, and critically assess the reliability of AI-generated content. We will also address ethical considerations, including authorship, ownership, and copyright, making sure you can leverage generative AI tools to improve your productivity while maintaining academic integrity.
>
> 
> The **presentations** which goes alongside this material can be found [here](https://docs.google.com/presentation/d/1HcoNIQkAw8q4BHb_721MZAZAQCBp9ZJZ/edit?usp=sharing&ouid=102044173704117471327&rtpof=true&sd=true), version of 2026 04 03.
>
>
> <i class="fa fa-arrow-right"></i> **Learning Outcomes:**  
> By the end of the course, learners will be able to:
>
> 1. Explain the core principles of generative AI and their relevance to academic research.
> 2. Identify the features, capabilities, and limitations of various generative AI tools used in research workflows.
> 3. Apply prompt engineering techniques to generate relevant outputs for scholarly tasks.
> 4. Use generative AI tools and agents to support specific academic tasks, including literature review, content drafting, and brainstorming.
> 5. Evaluate the quality and reliability of AI-generated outputs in academic research.
> 6. Discuss ethical implications, ownership and copyright of AI generated content.
> 7. Plan an integrated research workflow using generative AI tools.
>
>
> <i class="fa fa-hourglass"></i> **Time estimation**: 8h (1 day)
>
> <i class="fa fa-asterisk"></i> **Requirements:** The (technical) installation requirements are described in the Chapters [Get Ready](https://liascript.github.io/course/?https://raw.githubusercontent.com/vibbits/introduction-to-generative-ai/refs/heads/main/Chapters/GetReady4training.md).
>
> <i class="fa fa-envelope-open-text"></i> **Supporting Materials**:
> 
> 1. [Exercises and solutions](https://github.com/vib-tcp/introduction-to-generative-ai/tree/main/exercises)
> 2. [Slides](./presentations)
>
> ## Proposed Schedule
>
>Schedule day 2026 04 03:
>
>> - 9:30 - 11:00 - session Introduction to Generative AI
>>   - Brief historical background: from first AI to generative AI
>>   - Mapping generative AI tools
>>   - Focus on Large Language Models (LLMs)
>> - 11:00 - 11:15 - break
>> - 11:15 - 12:45 - session Introduction to Generative AI
>>   - Tools for genAI (CoPilot, Perplexity and other competitors)
>>   - Prompt engineering
>>   - Ethical considerations
>>   - Ownership, copyright and authenticity
>>- 12:45 - 13:45 - lunch
>>- 13:45 - 15:15 - session Generative AI for Writing
>>   - Conducting a literature review
>>   - Finding research gaps
>>   - Writing an article and where GenAI tools can assist
>>   - Graphics with NotebookLM and Napkin.AI
>>- 15:15 - 15:30 - break
>>- 15:30 - 17:00 - session Generative AI Agents for Writing
>
> <i class="fa fa-life-ring"></i> **Acknowledgement**:
>
> * [ELIXIR Belgium](https://www.elixir-belgium.org/)
> * [VIB Technologies](https://www.vib.be/)
>
> <i class="fa fa-money-bill"></i> **Funding:** This project has received funding from VIB.
>
> <i class="fa fa-anchor"></i> **PURL**: [DOI 10.5281/zenodo.18060252](https://doi.org/10.5281/zenodo.18060252)
>
>
> # Authors and Contributors
>
> Authors
>
>- [Bruna Piereck](@[orcid](https://orcid.org/0000-0001-5958-0669)
>- [Alexander Botzki](@[orcid](https://orcid.org/0000-0001-6691-4233)
>- [Jolan Heyse](@[orcid](https://orcid.org/0000-0003-2179-0366)
>
> Contributors
>
>- we welcome contributors for these materials
>
> ## Citing this lesson
>
>Please cite as:
>
>  1. Botzki, A., Piereck Moura, B., & Heyse, J. (2026, April 3). Introduction to Generative AI. Zenodo. https://doi.org/10.5281/zenodo.19402552
>
> # Chapters List
>
> | Chapter | Title                                                   |
> | :---- | :------------------------------------------------         |
>| 0     | [Get ready for the course, installation and pre-reading](https://liascript.github.io/course/?https://raw.githubusercontent.com/vibbits/introduction-to-generative-ai/refs/heads/main/Chapters/GetReady4training.md) |
> | 1     | [Strategic use of generative AI for all](https://liascript.github.io/course/?https://raw.githubusercontent.com/vibbits/introduction-to-generative-ai/refs/heads/main/ Chapters/Chapter01.md)                                             |
> | 2     | [Strategic use of generative AI for research](https://liascript.github.io/course/?https://raw.githubusercontent.com/vibbits/introduction-to-generative-ai/refs/heads/main/Chapters/Chapter02.md)                                             |>

#  Workshop and Material organization


> We are using the interactive Open Educational Resource online/offline course infrastructure called LiaScript.
> It is a distributed way of creating and sharing educational content hosted on github.
> To see this document as an interactive LiaScript rendered version, click on the
> following link/badge: [LiaScript](https://liascript.github.io/course/?https://raw.githubusercontent.com/vibbits/introduction-to-generative-ai/main/README.md)

# References

Here are some great tips for learning and to get inspired for your own use:

* [Vectara hallucination testing](https://github.com/vectara/hallucination-leaderboard/?tab=readme-ov-file)
* [AI Hallucination Report 2025: Which AI Hallucinates the Most?](https://www.allaboutai.com/resources/ai-statistics/ai-hallucinations/)
* [Generative AI and Copyright - Training, Creation, Regulation](https://www.europarl.europa.eu/thinktank/en/document/IUST_STU(2025)774095) by Nicola LUCCHI, PhD - Serra Hunter Professor of Comparative Law, University Pompeu Fabra, Barcelona, Spain
* [EC ERA Forum doc - CC-BY](https://research-and-innovation.ec.europa.eu/document/download/2b6cf7e5-36ac-41cb-aab5-0d32050143dc_en?filename=ec_rtd_ai-guidelines.pdf)
* [Library Toronto](https://onesearch.library.utoronto.ca/copyright/generative-ai-tools-and-copyright-considerations)
* [tools list Georgetown](https://guides.library.georgetown.edu/ai/tools)
* [UWaterloo CA June 2024](https://uwaterloo.ca/associate-vice-president-academic/sites/default/files/uploads/documents/genai-overview-final-june-2024.pdf)
* [University framework on GenAI for research](https://arxiv.org/html/2404.19244v1)
* [prompting guide from Cape Town university](https://docs.google.com/document/d/1EHMRP4kxADwLsOkHwAbUWQaGD8EGfQ3D/edit)
* [guide for ethical use in research](https://docs.google.com/document/d/14XaTVheTtr7XpDWX33OthT4piMHnYUfl/edit)
* [genAI for marketing content creation](https://sciendo.com/article/10.2478/nimmir-2024-0002)
* [Literature review](https://publications.coventry.ac.uk/index.php/joaw/article/view/1129/1138)
* [Research writing with ChatGPT: A descriptive embodied practice framework](https://www.sciencedirect.com/science/article/pii/S8755461524000069)

# About us

*About ELIXIR Training Platform*

The ELIXIR Training Platform was established to develop a training community that spans all ELIXIR member states (see the list of Training Coordinators). It aims to strengthen national training programmes, grow bioinformatics training capacity and competence across Europe, and empower researchers to use ELIXIR's services and tools.

One service offered by the Training Platform is TeSS, the training registry for the ELIXIR community. Together with ELIXIR France and ELIXIR Slovenia, VIB as lead node for ELIXIR Belgium is engaged in consolidating quality and impact of the TeSS training resources (2022-23) (https://elixir-europe.org/internal-projects/commissioned-services/2022-trp3).

The Training eSupport System was developed to help trainees, trainers and their institutions to have a one-stop shop where they can share and find information about training and events, including training material. This way we can create a catalogue that can be shared within the community. How it works is what we are going to find out in this course.

*About VIB and VIB Technologies*

VIB is an entrepreneurial non-profit research institute, with a clear focus on groundbreaking strategic basic research in life sciences and operates in close partnership with the five universities in Flanders – Ghent University, KU Leuven, University of Antwerp, Vrije Universiteit Brussel and Hasselt University.

As part of the VIB Technologies, the 12 VIB Core Facilities, provide support in a wide array of research fields and housing specialized scientific equipment for each discipline. Science and technology go hand in hand. New technologies advance science and often accelerate breakthroughs in scientific research. VIB has a visionary approach to science and technology, founded on its ability to identify and foster new innovations in life sciences.

The goal of VIB Technology Training is to up-skill life scientists to excel in the domains of VIB Technologies, Bioinformatics & AI, Software Development, and Research Data Management.

--------------------------------------------

*Editorial team for this course*

Authors: @[orcid(Alexander Botzki)](https://orcid.org/0000-0001-6691-4233), @[orcid(Bruna Piereck)](https://orcid.org/0000-0001-5958-0669)

Technical Editors: Alexander Botzki

```json   @JSONLD
{
  "@context": "https://schema.org/",
  "@type": "LearningResource",
  "@id": "https://elixir-europe-training.github.io/ELIXIR-TrP-TeSS/",
  "http://purl.org/dc/terms/conformsTo": {
    "@type": "CreativeWork",
    "@id": "https://bioschemas.org/profiles/TrainingMaterial/1.0-RELEASE"
  },
  "description": "Strategic Use of Generative AI - this is our hands-on course for general use and research-specific use of Generative AI.",
  "keywords": "FAIR, OPEN, Generative AI, Writing, Ethics, Scripting",
  "name": "Strategic Use of Generative AI",
  "license": "https://creativecommons.org/licenses/by/4.0/",
  "educationalLevel": "beginner",
  "competencyRequired": "none",
  "teaches": [
    "Providing a background of the evolution of generative AI models",
    "Providing an overview of the features and capabilities of genAI",
    "Analysing prompt engineering techniques for different purposes",
    "Exploring several applications of genAI in academic research (afternoon session)", 
    "Providing hands-on experience with using different genAI tools for work and research purposes",
    "Critically evaluating the AI generated outcomes"
  ],
  "audience": "researchers",
  "inLanguage": "en-US",
  "learningResourceType": [
    "tutorial"
  ],
  "author": [
    {
      "@type": "Person",
      "name": "Bruna Piereck"
    },
    {
      "@type": "Person",
      "name": "Alexander Botzki"
    }
  ],
  "contributor": [
    {
      "@type": "Person",
      "name": "Christof De Bo"
    }
  ]
}
```





