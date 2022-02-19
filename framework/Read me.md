<div id="top"></div>

<!-- PROJECT SHIELDS -->
<!--
*** I'm using markdown "reference style" links for readability.
*** Reference links are enclosed in brackets [ ] instead of parentheses ( ).
*** See the bottom of this document for the declaration of the reference variables
*** for contributors-url, forks-url, etc. This is an optional, concise syntax you may use.
*** https://www.markdownguide.org/basic-syntax/#reference-style-links
-->


<!-- PROJECT LOGO -->
<br />

<!-- TABLE OF CONTENTS -->
<details>
  <summary>Table of Contents</summary>
  <ol>
    <li>
      <a href="#about-the-project">About The Project</a>
      <ul>
        <li><a href="#built-with">How we help</a></li>
      </ul>
    </li>
    <li>
      <a href="#getting-started">Getting Started</a>
      <ul>
        <li><a href="#prerequisites">Prerequisites</a></li>
        <li><a href="#installation">Installation</a></li>
      </ul>
    </li>
    <li><a href="#usage">Usage</a></li>
    <li><a href="#roadmap">Roadmap</a></li>
    <li><a href="#contributing">Contributing</a></li>
    <li><a href="#license">License</a></li>
    <li><a href="#contact">Contact</a></li>
    <li><a href="#acknowledgments">Acknowledgments</a></li>
  </ol>
</details>

# SWADDLE

<!-- ABOUT THE PROJECT -->
## Beet.Framework
![alt text](https://github.com/jyoung122/swaddlefy/blob/b6a072d96ab850cead6163715f0c70b09628725d/framework/images/fw.PNG)



## Integration
The Integration Layer begins the actual work of the bot building process. It collects information about the various applications, screens, and elements from those screens that are used by the bot. The information includes:

- For each application use by the bot
  - For each screen, page, or panel use from the application
    - Identify each field from which data will be retrieved or viewed
    - Identify each field into which data will be entered or modified
    - Identify each button or control (including tabs, etc.) that will be activated

This information is collected repetitively for each screen in each application until the entire automation is mapped.


## Task
The Task Layer defines who each of the items on a screen will be used. Specifically, every item can be used in one of four, and only four, specific ways. 
These are: 
* PUT Data – placing data onto the screen, and includes modifying existing data; 
* GET Data – retrieving or viewing data from the screen; 
* ACTION – using a control (e.g. a button) to cause another action to occur; 
* START – Initiating new action based on the completion of the display of an item on the page. The information collected for these elements includes:


## Business Steps/Recovery
### Business Steps

The Business Process Layer focuses on decision rules and navigation within the automation. These rules are called steps and are used to direct the bot to move between various screens, and to take certain actions related to information that it has collected in previous get tasks. These actions will often lead to set tasks on a screen.

- For each step in the business process, the following is defined:
  - A name for the step, along with a description
  - A name for the assessment performed by the step
  - The nature of the assessment condition being evaluated
  - The resultant assessment condition(s) that is expected
  - The next step to follow (action to be taken) if the condition is true
  - Any messaging that should be displayed or delivered if the condition is true

### Recovery Steps
Like the Business Process Layer, the Process Recovery Layer focuses on decision rules and navigation within the automation. However, these rules handled condition that occur when the normal step processes are not properly handled. Business rules should cover every expected occurrence that the bot can and should handle, but in those cases where they bot encounters something that is either not expected, or that cannot be handled, the Process Recovery Layer tells the bot what to do, and what steps to take next

- For each step in the business process, at least one recovery process step should be established:
  - A name for the recovery step, along with a description
  - The name the assessment with which the recovery is associated
  - The resultant recovery condition(s) that are expected
  - The next step to follow (action to be taken) if the recovery condition occurs
  - Any messaging that should be displayed or delivered if the condition is occurs
- In some cases the automation will end, in some cases it will be sent for attempted autocorrection and potentially continue, in other cases, it could be sent to a human-in-the-loop operator for correction, then resume the automation.




<!-- CONTACT -->
## Contact

_[Contact Us](email@swaddle.io)_ </br>
https://example.com
<p align="right">(<a href="#top">back to top</a>)</p>


