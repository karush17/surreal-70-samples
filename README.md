# Paper Reviews

## Introduction
This repository is a collection of short reviews of papers in Deep Learning. Reviews are based on papers which explore novel groundbreaking ideas or consist of theoretically rich concepts. A total of 2 short reviews are typically added each week which explore essential aspects of the work, its technical innovation and new questions and ideas raised by the work. Length of each review is 1 page. Each review is based on a fixed set of guidlines which are given [here](#guidlines). If you would like to contribute to the reviews then please read [this](#contributions).

## Available Paper Reviews

|Review Number|Paper Title|Author List|Review Link|Contributor|
|:-----------:|:---------:|:---------:|:---------:|:---------:|
|1|[Action and Perception as Divergence Minimization](https://arxiv.org/pdf/2009.01791.pdf)|Danijar Hafner,Pedro A. Ortega,Jimmy Ba,Thomas Parr,Karl Friston,Nicolas Heess|TBA|[@karush17](https://github.com/karush17)|
|2|[Momentum Contrast for Unsupervised Visual Representation Learning](https://arxiv.org/pdf/1911.05722.pdf)|Kaiming He,Haoqi Fan,Yuxin Wu,Saining Xie,Ross Girshick|TBA|[@karush17](https://github.com/karush17)|

## <a name="guidlines"></a>Review Guidlines
This section outlines the guidlines which are used to write reviews for the repository. Note that these guidlines must be strictly followed for providing high quality reviews to the reader. 

### Paper Selection
Since Deep Learning is a fast-moving field, papers can span a broad variety of topics. In order to shorten the range of literature, papers must be selected using the following rules-  
* Any review paper, survey or a long article should not be considered since these are themselves a review of previous works and reviewing them would defeat the purpose of literature writing.
* Short papers, Journal papers and theoretical works are suitable as these present a single idea which may be of interest to the reader.
* Papers containing experimental results balanced with theory are encouraged as these validate the practical applications of the proposed methods.
* There is no constraint on the publication date and time of papers. However, papers which date back to the 'AI Winter' are highly encouraged since these provide insights which were never looked at for a very long time.
* Papers containing simply applications of pre-existing methods to various regimes are not preferred since they do not provide any new insights into the algorithm itself and only deal with its applicability.
* Workshop papers and incomplete works are also welcome as researchers can always build on these ideas.
* While there is no specific restriction on the content of papers, reviewer must consider fields in AI which are growing and require a new outlook, eg. Reinforcement Learning, Gradient-Free methods, Meta-Learning, Natural Language at Scale, Explainability, etc.


### Introduction
This section provides points on writing a good introduction for the review. Note that these review points are not strict and only serve as a guiding principle for drafting a good introduction.  
* The introduction should be a high-level idea of the paper and what the work deals with.
* The reviewer must refrain from going into any technical detail and highlight the broad idea of the work and its scope.
* No mathematical terms, definitions, technical explanations or algorithmic details should be provided to the reader.
* The main focus should be on the problem statement and how the method aims to solve this.
* A possible checklist of questions one might want to answer while writing a good introduction is as followed-
    - [ ] What is the main area of the work?
    - [ ] What are some of the open problems in this area?
    - [ ] What has been done so far to address these problems?
    - [ ] What still remains as the scope of this paper?
    - [ ] What does the paper propose?
    - [ ] How does the paper solve this problem?
    - [ ] What theoretical/practical insights does the work achieve?
    - [ ] What could have been (or is) done better to solve the problem?
* Key takeaway- Detail is your enemy!


### Methodology
This section deals with the proposed method and its essential aspects in solving the problem highlighted in the introduction section. Following points serve as a guide to writing this section-  
* The content must provide a brief overview of the method. This informs the reader about what he is getting into.
* Once an overview has been provided, the draft can start diving into the detail which should be highlighted intuitively.
* Mathematical details must be followed by words, complicated terminology must be explained intuitively using examples or instances from work.
* Reasons related to technical details and there usage must be provided to the reader. The whole point of reading a review is to crisply go over the details of the paper without wanting to read the entire text.
* While the draft should highlight the method and its details, it should also provide the reader with insights from the reviewer's point of view. These could consist of specific reasons for selecting a set of parameter values, usage of a specific technique existing in literature, novel contributions and the reason behind its usage and any improvements/changes from previous works.
* A possible checklist of constituents of this section is as followed-
    - [ ] Overview of the method and its details
    - [ ] Mathematical/technical details related to the algorithm and/or its implementations
    - [ ] Proper reasoning behind technical contributions
    - [ ] Detailed discussion of novel contributions
    - [ ] Differences/improvements and their reasons from previous literature
    - [ ] Critical insights into the method's applicability to practical scenarios
    - [ ] Reviewer's own discussion about the method and its components
* Key takeway- Intuition is king!


### Critical Analysis
The critical analysis section deals with the reviewer's analysis and understanding of the method. Specifically, this section should highlight what the reviewer thinks about the proposed approach, its strengths, weaknesses and potential areas of improvement and applicability. This is the most important section of the review since the reviewer needs to critically evaluate and comment on the technical aspects of the work. The following points should be kept in mind while writing a good critical analysis-
* One should evaluate all aspects of the work before diving into this section. A comprehensive analysis of the work is essential as it builds on the reviewer's understanding of the method.
* Once the complete details have been established, a proper structure for evaluation should be constructed. Typically, this structure should consist of comments on motivational aspect, strengths, weaknesses, novel contributions, applicability of the method, extensions and improvements of the method's components and their shortcomings. 
* The draft should be written in a critical yet formal manner. For instance, the reviewer must highlight the intriguing aspects of the algorithm and at the same time throw light on its critical parts in a decorous manner.
* Reviewer's comments should be their own and not focus on explaining the work. The main idea behind this section is to present your understanding of the text to the reader, not the text itself.
* A possible checklist of questions one may ask while writing this section is as followed-
    - [ ] Have all the aspects of the work been convered in an articulate manner?
    - [ ] What are the key components of the method?
    - [ ] What are the strengths, weaknesses, applications, extensions and shortcomings of these components?
    - [ ] How are these components novel in nature?
    - [ ] How can these components be used in theoretical/practical scenarios related to the area of work?
    - [ ] How can these components be improved and in theoretical/practical scenarios related to the area of work?
* Key takeway- Your own contributions matter!


### New Ideas/Questions
This section follows and builds upon the critical analysis section. The main idea behind this section is to highlight and examine the novel contributions of the proposed method and their contributions towards improving prior techniques. Another reason to study new ideas proposed by a paper is to identify potential directions of research and answer open questions from different perspectives. Following points may come in handy while writing this section-
* One should concisely summarize the novel contributions of the work (not more than 1-2 sentences).
* The summary should be followed by a critical analysis or a set of possible questions which maybe asked while using the novel aspects of the method.
* Since the focus is on novelty, reviewer may also be interested in asking questions related to other potential techniques and their applicability in place of the novel method.
* The section should conclude with brief comments on substitutes/extensions to the novel components and questions left unanswered (if any) in the work.
* A possible checklist of constituents of this section is as followed-
    - [ ] What is the novelty of the proposed method?
    - [ ] Can the novelty be used in other methods related to the area of work?
    - [ ] What are some of the potential substitutes to the novel contributions?
    - [ ] How would these compare to the novel contributions?
    - [ ] What are some of the questions answered/addressed by the novel contributions? 
    - [ ] What are some of the questions the method opens up? Is it suitable as a future research direction?
 

### Conclusion
* 

## <a name="contributions"></a>Contributions
*"No one can whistle a symphony. It takes a whole orchestra to play it."* – H.E. Luccock  

Collaboration is most welcome for this repository. If you believe that you would like to practice your research writing skills or would like to do a literature survey for your independent study, then feel free to hop in! Reviews in this repository follow a general LaTeX template which is available in the template folder. Furthermore, reviews written for the repository must follow the review guidlines which are available [here](#guidlines). Feel free to submit the paper and its review by opening a pull request.


