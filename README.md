# cheeseburger

Cheeseburger is a work-in-progress methodology that Futura IO deploys for Product Development.

Influenced by

  - [d.school DT](http://dschool.stanford.edu/)
  - failing at finishing many products

The name is derived from the idea that a product development process should introduce product variance.

![image](http://cl.ly/OqHB/Screen%20Shot%202013-05-08%20at%207.29.25%20PM.png)

## The System

**Table of Contents**
  - [Prelude](https://github.com/FuturaIO/cheeseburger#prelude)
  - [Requirements](https://github.com/FuturaIO/cheeseburger#requirements)
  - [Structure](https://github.com/FuturaIO/cheeseburger#structure)
  	- [Base](https://github.com/FuturaIO/cheeseburger#base)
    - [Feature Stages](https://github.com/FuturaIO/cheeseburger#feature-stages)
    - [Feature Stage Micros](https://github.com/FuturaIO/cheeseburger#feature-stage-micros)
  - [Formatting](https://github.com/FuturaIO/cheeseburger#formatting)


### Prelude
The Cheeseburger Methodology arose out of a realization for a more tightly knit, yet loosely controlled system for organizing product development. We didn't want to get tied into heavy feature listing and see too many half-finished repos. Cheeseburger is meant to help steer product direction and keep accountability around finishing products entirely.

Addtionally, Cheeseburger is an entirely GitHub Issues managed product development system. It utilizes some customizations to the Issue tagging systema and transitioning information into the Wiki for "always on feature development conversations". 

### Requirements
Organizing product development process with the Cheese is entirely predicated upon working solely out of GitHub issues for communication and management. All issues, milestones, labels and work are done alongside the main repository managing the codebase for the application.

  - [GitHub Isses](https://github.com/blog/831-issues-2-0-the-next-generation)

Cheeseburger applies a slightly different methodology for Web Applicaitons than for iOS applications (the only two it's primarily being tested on). For the purposes of gathering empahty and getting to market with the right niche and speed, web applications are developed without any PSD or Static Image based starting point. All design is created in the browser with front-end development technologies and therefore futher implemented on and changed. 

### Structure
Cheeseburger is facilitated by moving product features through a labeling system. Every product feature is treated on an equal playing field and therefore organized by the same global system for product development. Features can have 3 stages; `proposed`, `testing` and `active`. At any point in development any feature can move forward or backward on this track. Additionally, within each stage - each feature must move along the micro track. Any feature in the `proposed`, `testing` or `active` stage can be in the micro `understand`, `synthesize` or `prototype`. Each feature is it's on GitHub Issue. Each feature has the proper label applied as it's in each stage.


#### Base
Every cheeseburger managed project has a "Base" Issue which definies the units which denote base functional application. The "Base" Issue will change depending on the nature of the applicaiton, i.e. Mobile Web, iOS, etc… 

#### Feature Stages

  - **Proposed**
    - The propsed stage is just what it sounds.
  - **Testing**
    - The testing stage is when a feature is being actively *prototyped on end users.
      - *with code, in the browser, maybe even in the product
  - **Active**
    - An active feature is one that's currently implemented in the live product.

#### Feature Stage Micros

  - **Understand**
    - Features in the understand micro are gathering empathy for the people the feature will impact.
  - **Synthesize**
    - A stage in the synthesize micro is compiling the understand data in a current stage definition (CSD).
  - **Prototype**
    - A stage in the micro *prototype* is one being actively tested on users in low-reslution formats.
    
### Formatting
Formatting issues in a consice matter for clarity of communication is extremely important. Each product feature has it's own Issue. All communication regarding that issue happens underneath each Issue. As features move along the Feature Stages the 
