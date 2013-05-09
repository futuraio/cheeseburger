# cheeseburger

Cheeseburger is a work-in-progress methodology that Futura IO deploys for Product Development.

Influenced by

  - [d.school DT](http://dschool.stanford.edu/)
  - failing at finishing many products

The name is derived from the idea that a product development process should introduce product variance.

![image](http://cl.ly/OqHB/Screen%20Shot%202013-05-08%20at%207.29.25%20PM.png)

## The System

**Table of Contents**
  - [idea.json](https://github.com/FuturaIO/cheeseburger#idea.json)
  - [Prelude](https://github.com/FuturaIO/cheeseburger#prelude)
  - [Structure](https://github.com/FuturaIO/cheeseburger#structure)
    - [Feature Stages](https://github.com/FuturaIO/cheeseburger#feature-stages)
    - [Feature Stage Micros](https://github.com/FuturaIO/cheeseburger#feature-stage-micros)

### idea.json

```javascript

{
	"name": "cheeseburger",
	"description": "An empathy first, prototype informed, github organized methodology for building new products",
	"version": "0.0.1",
	"contributors": [
		{
			"name": "TJ Krusinski",
			"role": "cheese layer"
		},
		{
			"name": "Chris Constable",
			"role": "fry fryer"
		},
		{
			"name": "Robb Schiller",
			"role": "grease drinker"
		}
	],
	"ideaDependencies": []
}

```

### Prelude
This is not a joke. One day, TJ and Robb were talking about how many unfinished products there are. We lamented the repo graveyards that tend to gingerly decay into tutorials of how not to code for future self. Inspired by the progress of our forefathers, we took to the task of creating a simple system for managing, discussing and organizing product development by it's smallest unit - the feature.

Using GitHub issues as a project management system - We're synthesizing the product development ideas behind Design Thinking and the experinces we've all had working on products that have failed and succeeded.

### Structure
Cheeseburger is facilitated by moving product features through a flagging system. Every product feature is treated on an equal playing field and therefore organized by the same global system for product development. Features can have 3 stages; `proposed`, `testing` and `active`. At any point in development any feature can move forward or backward on this track. Additionally, within each stage - each feature must move along the micro track. Any feature in the `proposed`, `testing` or `active` stage can be in the micro 'understand', 'synthesize' or 'prototype'.

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
