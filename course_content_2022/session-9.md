back to [course content](index)


# Week 9: Evaluation

[Lecture](#lecture) | [Tutorial](#tutorial-usability-evaluation) | [Assignment](#assignment)

Lecture topics: 

* Evaluating Visualizations
* Heuristics and Guidelines
* Case studies
* Subjective Feedback
* Objective Measurements

# Lecture

### Slides
* [Evaluation](files/9-Evaluation.pdf)  

#### Video lectures
* [Datavis-9: Evaluation-1 Intro (7:42min)](https://drive.google.com/file/d/1y56Oh0M_VqtjpqijU7CT92x58wUOrw6V/view?usp=sharing)
* [Datavis-9: Evaluation-2 Heuristics and Guidelines (20:30min)](https://drive.google.com/file/d/1dpkF0vILbYYIAQjn9CAtMbmMSfFfiL41/view?usp=sharing)
* [Datavis-9: Evaluation-3 Case Studies (2:26min)](https://drive.google.com/file/d/1oxc5ckWNZl0SkC3Tljtr0O88f1Gy1-pX/view?usp=sharing)
* [Datavis-9: Evaluation-4 Subjective Feedback (5:47min)](https://drive.google.com/file/d/1OgkNRU5Onxi0BI-hc2kgvLOXkndsIed6/view?usp=sharing)
* [Datavis-9: Evaluation-5 Objective Measurements (3:48min)](https://drive.google.com/file/d/1IUSsGVGB_QfEYkAf0vYsyAQ8nSASMDIk/view?usp=sharing)
* [Datavis-9: Evaluation-6 Wrap up (2:30min)](https://drive.google.com/file/d/1kLQsBUOezs4Zq1WRvhdbfZqZ2Ul-QpUP/view?usp=sharing)


## Suggested Reading

* Elmqvist, Niklas, and Ji Soo Yi. "Patterns for visualization evaluation." Information Visualization 14.3 (2015): 250-269.
* Lam, Heidi, et al. "Empirical studies in information visualization: Seven scenarios." IEEE transactions on visualization and computer graphics 18.9 (2011): 1520-1536.
* Lam, Heidi, et al. "Seven guiding scenarios for information visualization evaluation." (2011).
* Isenberg, Tobias, et al. "A systematic review on the practice of evaluating visualization." IEEE Transactions on Visualization and Computer Graphics 19.12 (2013): 2818-2827.
* Borgo, Rita, et al. "Information visualization evaluation using crowdsourcing." Computer Graphics Forum. Vol. 37. No. 3. 2018.
* Kang, Youn-ah, and John Stasko. "Examining the use of a visual analytics system for sensemaking tasks: Case studies with domain experts." IEEE Transactions on Visualization and Computer Graphics 18.12 (2012): 2869-2878

<p>&nbsp;</p>


<a name = "tutorial-usability-evaluation"></a>
# Tutorial: Usability Evaluation
1. Discussion 1 (10 min)
    * ___Whole class &ndash; reflection___
        - review project definition and [design guidelines](session-2#design_guidelines)
        - review feedback (given and received) during 'Critical Analysis' tutorial
        - review of evaluation heuristics 

1. Activity 1 (15 min)
    * ___On your own___ (even if working on a group project)
        - reflect on:
        - your brief and design
            - what is your "___big question___"? Has it changed over the last few weeks?
            - same for your target users, tasks and overall context of use &ndash; any updates and impact on your initial design?
        - define 3-5 heuristics you would like to be used to evaluate your project 
            - you may find it useful to review the recommended evaluation heuristics in the [lecture material](#lecture), along with guidelines such as [Nielsen's 10 heuristics](https://www.nngroup.com/articles/ten-usability-heuristics) and the [SUS (System Usability Scale) questionnaire](https://www.usability.gov/how-to-and-tools/methods/system-usability-scale.html)
            - centre each in a user task or scenario
            - critically evaluate your project &ndash; definition, design and implementation &ndash; based on your own and more general guidelines

1. Discussion & Reflection 2 (55 min)
    * __Within your group__ (15min * 2)
    * __NOTE:__ ___if your implementation reveals sensitive data and/or processes please speak to a course tutor about adjustments for this exercise___
        * exchange design briefs (with) evaluation checklists) - each must be evaluated by two others in your group
            - provide __constructive__, albeit critical, feedback, suggestions for improvement, scope for extension. This is an opportunity for peer learning, to gain from others' experience and perspectives.
            - start with general heuristics, then follow those defined by its owner

    * __On your own or within your project group__ (10min)
        * review feedback
            - note any questions for reviewers
      
    * __Within your groups__ (15min)
        * round table discussion
            - discuss feedback at a more general level, ask any followup questions
 
1. Activity 2 (25 min)
    * ___In the main classroom___  
    ___On your own (or within your project group)___
        - create an evaluation plan for your project, using as a guide:
            - your project brief and design
            - feedback from the critical analysis exercises
            - general evaluation heuristics and those you defined
                - feedback you have received based on these heuristics

      
  __Note:__ the guidelines below specify components of a usability evaluation; use these as a framework for building your plan
  <p>&nbsp;</p>
  
<a name = "guidelines_evaluation_plan"></a>
__General guidelines &amp; best practice for creating an evaluation plan__

* Write a brief a scenario of use that includes:
    * a description of your target user(s)
    * a description of key tasks
        - provide 3&ndash;5 tasks; if necessary break complex tasks down into simpler sub-tasks
    * the context of use of your visualisation, including
        - data that will be used normally and the sub-set in your evaluation
        - environment in which visualisation will be used, e.g., device, physical environment, technology and other tools used in tandem
        - what other information or knowledge the end user needs to make use of the visualisation
    * How do these together answer your big question?
    * Are you testing a hypothesis(es)?

* What are you measuring? Evaluation of information visualisation poses some challenges
    - how do you measure insight? intuitiveness? innovation?
    - how do you evaluate the process involved in using an interactive visualisation?
    - how do you evaluate how your visualisation supports effective communication of data content? and transform this to usable knowledge that can be acted on?
    * Consider also the __RUSTIC heuristic__:
        - Readability, Understandability, Supportiveness, Truthfulness, Insightfulness, Communication

* What study design, protocols or methodology do you want to follow?
    - one-off or longitudinal?
    - expert reviews using heuristics
    - lab-based evaluation
    - in-situ or in-the-wild studies
* What data are you collecting?
    - qualitative (subjective), based on
        - some form of think-aloud
        - observation (recorded using notes)
        - recordings of users (audio and/or video)
        - among others, data collected from semi-structured interviews, focus groups, diaries
    - quantitative (objective) &ndash; typically data on performance
        - time to complete tasks
        - results from tasks performed
        - errors during task completion (or not)
        - automated logging of actions and results

* Create your questionnaires
    * pre-evaluation &ndash; including demographics as appropriate
    * post-evaluation &ndash; collect opinions on utility and usability
        - frame questions to collect information on experience
        - include specific questions evaluating task performance
        - allow users free-form space for unprompted feedback
    
* How will you analyse or evaluate your results?
    
__NOTE:__ In the actual evaluation __remind users they are evaluating the tool, not themselves!!!__
<p>&nbsp;</p>

#### Additional tutorial resources &amp; links:

* Elmqvist, N., & Yi, J. S. (2015). [Patterns for visualization evaluation](http://dx.doi.org/10.1177/1473871613513228). Information Visualization, 14(3), 250-269. [UoE library link](https://discovered.ed.ac.uk/permalink/f/1s15qcp/TN_sage_s10_1177_1473871613513228)
* Scholtz, J. et al. (2014) [Evaluation of visual analytics environments: The road to the Visual Analytics Science and Technology challenge evaluation methodology](http://dx.doi.org/10.1177/1473871613490290), Information Visualization, 13(4), pp. 326–335. [UoE library link](https://discovered.ed.ac.uk/permalink/f/1s15qcp/TN_sage_s10_1177_1473871613490290)
* Heidi Lam, Enrico Bertini, Petra Isenberg, Catherine Plaisant, Sheelagh Carpendale. [Empirical Studies in Information Visualization: Seven Scenarios](https://hal.inria.fr/hal-00932606/document). IEEE Transactions on Visualization and Computer Graphics, Institute of Electrical and Electronics Engineers, 2012, 18 (9), pp.1520–1536. [UoE library link](https://discovered.ed.ac.uk/permalink/f/1s15qcp/TN_hal_soai_HAL_hal_00932606v1)
* Carpendale S. (2008) Evaluating Information Visualizations. In: Kerren A., Stasko J.T., Fekete JD., North C. (eds) [Information Visualization](https://doi.org/10.1007/978-3-540-70956-5_2). Lecture Notes in Computer Science, vol 4950. Springer, Berlin, Heidelberg [UoE library link](https://discovered.ed.ac.uk/permalink/f/1s15qcp/TN_scopus2-s2.0-50549104903)
* [BELIV workshops](https://beliv-workshop.github.io)


1. [Jakob Nielsen's 10 general principles for interaction design](https://www.nngroup.com/articles/ten-usability-heuristics)
1. Nielsen, J. (2014) [Guerrilla HCI: Using Discount Usability Engineering to Penetrate the Intimidation Barrier](https://www.nngroup.com/articles/guerrilla-hci)
1. interaction-design.org: [How to Conduct a Heuristic Evaluation for Usability in HCI and Information Visualization](https://www.interaction-design.org/literature/article/how-to-conduct-a-heuristic-evaluation-for-usability-in-hci-and-information-visualization)
1. [Art meets science: IBM's Data visualization guidelines](https://www.ibm.com/design/v1/language/experience/data-visualization)
1. [SUS questionnaire](https://www.usability.gov/how-to-and-tools/methods/system-usability-scale.html)

* Brooke, J. (2013). [SUS: a retrospective](https://dl.acm.org/doi/abs/10.5555/2817912.2817913), Journal of Usability Studies 8(2), 29–40.
* Brooke, J. (1996). SUS: A "quick and dirty" usability scale. In P. W. Jordan, B. Thomas, B. A. Weerdmeester, & A. L. McClelland (Eds.), Usability Evaluation in Industry. London: Taylor and Francis.

<p>&nbsp;</p>

***

<p>&nbsp;</p>

# Assignment

Complete the exercise in <a href="#tutorial-usability-evaluation">this tutorial</a>.  Summarise your evaluation plan on a single page (A4, min font size 11), taking into account also any feedback and discussions during the tutorial, and the <a href="#guidelines_evaluation_plan">guidelines & best practice for creating an evaluation plan</a>. Include your evaluation plan as an appendix with your final project.


<p>&nbsp;</p>

       
back to [course content](index)
