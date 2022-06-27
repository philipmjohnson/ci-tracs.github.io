---
title: "Home"
morea_id: home
morea_type: home
published: true
---

## Welcome to CI-TRACS

<div class="alert alert-danger" role="alert" markdown="1">
<i class="fa-solid fa-circle-exclamation fa-xl"></i> **Warning: Not a real CI-TRACS site.**
<hr/>

This site is currently a mockup that illustrates:

1. how the CI-TRACS workshops could be represented as Morea modules, and
2. to explore the pros and cons of this approach.

It does not include all of the CI-TRACS workshops and/or material that would be needed for a real CI-TRACS site.
</div>



## About this site

Each [CI-TRACS workshop](https://github.com/CI-TRACS) is represented as a separate module. Each module has the following structure:

  * [Prerequisites](/prerequisites), describing skills you should have prior to starting the module.
  * [Learning outcomes](/outcomes), describing the major goals for the module.
  * [Readings and other online resources](/readings), providing background material.
  * [Experiential learning activities](/experiences), providing a structured set of challenges enabling you to acquire mastery of material.
  * [Assessments](/assessments), which help you determine if you have acquired mastery of the material.

## Morea vs. Software Carpentry

Currently, many (but not all) CI-TRACS workshops are implemented using the [Software Carpentry](https://carpentries.org/) workshop format.  Here are some of the pros and cons of these two systems:

#### Advantages of Software Carpentry

* In some cases, it appears that a CI-TRACS workshop is simply a fork of an existing Software Carpentry workshop (i.e. the [High Performance Computing workshop](https://github.com/CI-TRACS/High_Performance_Computing).) In this case, it is less work to simply make a fork than to re-represent the workshop using Morea.

### Advantages of Morea

* Morea allows all of the workshops to be represented as modules within a single site. This results in a "portal" to all workshops, making it easier to browse all of the workshops. For the Software Carpentry approach, the point of entry is the [CI-TRACS github organization home page](https://github.com/CI-TRACS).

* Morea establishes a consistent format where each module is comprised of four pedagogical "elements" (Outcomes, Readings, Experiences, Assessments). Modules can share pedagogical elements. So, for example, an Outcome (such as "Become skilled with Jupyter Notebooks") can be part of multiple Modules, and users can easily see which modules support a given Outcome. This helps to establish relationships among workshops and develop "cohesion" in the set of workshops.

* Morea supports an "Introduction" module, which is a convenient place to provide background material on the CI-TRACS program.

* Morea supports [private files](https://morea-framework.github.io/docs/instructors/private-files), which enables instructors to keep exams and other assessment instruments in the repo.
