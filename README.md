# The-Github-History-Of-Scala-Language
<details open="open">
  <summary>Table of Contents</summary>
  <ol>
    <li>
      <a href="#about-the-project">About The Project</a>
      <ul>
        <li><a href="#built-with">Built With</a></li>
      </ul>
    </li>
    <li>
      <a href="#plots">Plots</a>
      <ul>
        <li><a href="#plot3">Pull Requests by specific user vs Date</a></li>
        <li><a href="#plot4">Pull Requests by specific user on a specific file vs Date</a></li>
      </ul>
    </li>
 </details>
 
## About The Project
  
Open source projects contain entire development histories, such as who made changes, the changes themselves, and code reviews. In this project, the real-world project repository of Scala that spans data from a version control system (Git) as well as a project hosting site (GitHub) was readed in, cleaned up, and visualized. With almost 30,000 commits and a history spanning over ten years, Scala is a mature language. Who is the most influencial in the development of this language and who are the experts were found.

The dataset includes the project history of [Scala](http://www.scala-lang.org) retrieved from Git and GitHub as a set of CSV files.
  
 ### Built With

* [Python](https://www.python.org)
* [pandas](https://pandas.pydata.org)
* [matplotlib](https://matplotlib.org)
  
## Plots
The following are the plots generated to answer the following questions:
* Is the project still actively maintained?
  - To answer this will calculate the number of pull requests submitted each (calendar) month during the project's lifetime and plot the result
  - ### Date vs Pull Requests

![plot1](https://github.com/pranjwalsingh236/The-Github-History-Of-Scala-Language/blob/main/plots/Scala-DateVSPullRequests.PNG)
* How big is the contributing community?
  - Distribution that shows that there are few people that only contribute a small number of pull requests can be used as in indicator that the project is not welcoming of new contributors.
  - ### Histogram of the number of pull requests submitted by each user
  
![plot2](https://github.com/pranjwalsingh236/The-Github-History-Of-Scala-Language/blob/main/plots/Scala-HistogramOfPullRequests.PNG)
* Who made the most recent pull request?
  - For each calendar year, we were interested in understanding the number of pull requests the authors submitted. That gave us a high-level image of their contribution trend to the project.
  - ### Pull Requests by specific users vs Date
  
![plot3](https://github.com/pranjwalsingh236/The-Github-History-Of-Scala-Language/blob/main/plots/Scala-PlotOfTwoDevelopers.PNG)
* Who was more actively contributing to a specific file in the recent times?
  - We measured experience by the number of pull requests submitted that affect that file and how recent those pull requests were submitted.
  - ### Pull Requests by specific user on a specific file vs Date
 
![plot4](https://github.com/pranjwalsingh236/The-Github-History-Of-Scala-Language/blob/main/plots/Scala-PullRequestOnSpecificFile.PNG)
