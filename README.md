# JSM2018_ecosystem
Slides and materials for JSM 2018 "An Emerging Ecosystem for Data Science/Statistics Education" Session. <http://bit.ly/2018JSM_ecosystem> redirects here.

## Speaker Information

* Session Chair: Albert Y. Kim
    + Title: Assistant Professor of Statistical and Data Sciences
    + Affiliation: Smith College, Northampton MA
    + Email: <albert.ys.kim@gmail.com>
    + Webpage: <http://rudeboybert.rbind.io/>
    + GitHub: <https://github.com/rudeboybert>
    + Twitter: <https://twitter.com/rudeboybert>
    
* Chester Ismay
    + Title: Data Science Curriculum Lead
    + Affiliation: DataCamp (headquarters in New York City, based in Portland, OR)
    + Email: <chester@datacamp.com>
    + Webpage: <https://chester.rbind.io>
    + GitHub: <https://github.com/ismayc>
    + Twitter: <https://twitter.com/old_man_chester>

* Alicia Johnson
    + Affiliation: Macalester College

* Andrew Bray
    + Affiliation: Reed College

* Jennifer Bryan
    + Affiliation: RStudio, University of British Columbia
    
* Garrett Grolemund
    + Affiliation: RStudio



## Talks

### Streamline your class with RStudio - Garrett Grolemund

RStudio's free tools provide more than an ecosystem for doing data science; they provide an ecosystem for _teaching data science_. RStudio Cloud provides an easy to access compute environment that your students can use from minute one -- no downloads or installation required. You can use RStudio Cloud to create a shared class space stocked with projects to fork and data sets to use. Packed into RStudio Cloud is a curriculum of self-paced interactive tutorials that cover the basics of the Tidyverse, which frees you up to focus on teaching how to apply R to your subject area (the tutorials cover the same ground as _R for Data Science_ and are written by its authors). You can create your own interactive web tutorials with the learnr package, which transforms R Markdown documents into shiny apps that let students write, run, and submit their own code for feedback. Supporting all of this is the Tidyverse, a clear, coherent system for doing data science in R that is easy to teach and easy to use. This talk will provide a quickstart to using these tools as a foundation for your own data science course.

### Using Data to Drive Curriculum Development - Chester Ismay

Data science is a relatively new and fast-changing field that borrows from many disciplines, which makes it hard to define and even harder to teach. Having now trained over 1.5 million (aspiring) data scientists, we at DataCamp aim to equip our students with the tools and skills needed to operate effectively in the data science field. For this reason, we do as any good data scientist would do and use data to determine what our students need to know. By combining internal data sources—student surveys, course engagement data, website search trends, etc.—with external data sources—job posts, Stack Overflow trends, package downloads, etc.—we’re able to inform curricular decisions that not only reflect what our students want to learn, but also reflect skill sets that are in demand for the 21st century data scientist. DataCamp is among the first to focus on using large amounts of data and corresponding analyses to help drive data science curriculum.

### Authoring and Utilizing Open Source, Reproducible Statistics/Data Science Textbooks - Alicia Johnson

Open source, open access, and reproducible materials are essential to the modern practice of statistics and data science. Combined, these provide (free!) code, data, and software that users can directly implement, modify, and use to verify findings. In this talk we will discuss how the statistics / data science textbook publication model can be aligned with and utilize these best practices. The release of the RStudio Bookdown package facilitates this process. Through Bookdown, authors can publish reproducible and fully customizable textbooks that integrate markdown, code, visualizations, interactivity, and text. We will present first steps for authors of and users looking to adopt open source and open access textbooks, as well as existing examples ranging from an introductory textbook (ModernDive) to an advanced undergraduate textbook on Bayesian statistics.

### Aligning Inference with the tidyverse: Development of the infer Package - Andrew Bray

How do you teach your students to implement a permutation test? What about an analysis of variance? Do you focus on approximation techniques or utilize computational methods like the bootstrap? The infer package was created to unite these and other common statistical inference tasks into a single expressive framework that emphasizes their shared concepts. This talk will focus on the design principles of the package, which are firmly motivated by Hadley Wickham’s tidy tools manifesto. It will also discuss the implementation, centered on the common conceptual threads that link a wide range of hypothesis tests and confidence intervals. Finally, it will serve as a case study for anyone curious about developing an R package.

### Version Control: The Gain You Get For Your Pain - Jenny Bryan

Version control is a system for managing the evolution of a set of files across different people, computers, and time. Its roots are in software development, but it is increasingly important in both the practice and teaching of data science. I'll give an accessible description of what version control is and what it feels like to use it. We'll compare and contrast this to alternatives such as collaboration via Google Drive. Version control is important for educators for at least two reasons. First, it facilitates the exchange of code-rich documents between instructor and student. Second, it is a valid learning objective in and of itself, since version control is widely used by potential employers. I'll provide general information, as well as specifics relevant to the statistical programming environment R, the RStudio IDE, Git, and the GitHub hosting service.
