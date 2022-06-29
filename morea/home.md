---
title: "Home"
morea_id: home
morea_type: home
published: true
---

<div class="alert alert-danger mt-4" role="alert" markdown="1">
<i class="fa-solid fa-circle-exclamation fa-xl"></i> **Warning: This is not the real CI-TRACS site.**
<hr/>

This site is currently a mockup that illustrates:

1. How the CI-TRACS workshops could be represented as Morea modules, and
2. The pros and cons of Morea vs. Software Carpentry

It does not include all of the CI-TRACS workshops and/or material that would be needed for a real CI-TRACS site.

The "real" CI-TRACS site is at: [https://github.com/ci-tracs](https://github.com/ci-tracs)
</div>

## Welcome to CI-TRACS

You have reached the home page for the University of Hawaii CyberInsfrastructure TRaining to Advance Climate Science (CI-TRACS) project. This site provides access to a number of modules, many of which provide access to materials in support of one day workshops presented by the CI-TRACS team.  


## About this site

Each CI-TRACS workshop is represented as a separate module. Each module has the following structure:

  * [Prerequisites](/prerequisites), (optional) describing skills you should have prior to starting the module.
  * [Learning outcomes](/outcomes), describing the major goals for the module.
  * [Readings and other online resources](/readings), providing background material.
  * [Experiential learning activities](/experiences), providing a structured set of challenges enabling you to acquire mastery of material.
  * [Assessments](/assessments), which help you determine if you have acquired mastery of the material.

In addition, there are some modules that provide access to useful background resources, such as Python or Jupyter Notebooks.

## Morea vs. Software Carpentry

In the real CI-TRACS site, many (but not all) workshops are implemented using the [Software Carpentry](https://carpentries.org/) workshop format.  The development of this Morea site has helped me understand some of the pros and cons of these two approaches:

#### Advantages of Software Carpentry

* In some cases, a CI-TRACS workshop might be a (barely modified) fork of an existing Software Carpentry workshop. In this case, it is less work to simply make a fork than to re-represent the workshop using Morea.

* Each Software Carpentry page has arrow links to go forward and backward, which simplifies linear navigation within a workshop. In Morea, when you finish a page, there is no "next" link. Instead, you have to go back up to the Module level and then down into the next page. 

* Software Carpentry has specialized support for workshops, such as a timeline of activities. 

### Advantages of Morea

* Perhaps the most important advantage of Morea is that it provides a single site to represent (and inter-relate) all of the workshops.  This makes it easier to browse the workshops for users, and makes it easier to show the relationships between workshops.  The Software Carpentry approach results in entirely independent sites for each workshop. Currently, the point of entry is the [CI-TRACS github organization home page](https://github.com/CI-TRACS), which is not particularly user friendly. To create a better top-level "portal", one would have to create a brand new site, which would need to be updated manually to maintain consistency with the set of workshops. 

* A second advantage of Morea is its [pedagogical pattern](https://morea-framework.github.io/docs/instructors/pedagogical-pattern) (Outcomes, Readings, Experiences, Assessments). This helps instructors represent workshops in a consistent manner, and helps them to remember to include all elements (for example, Assessments seems to be lacking in most of the Workshops).  In addition to helping instructors structure their workshops consistently and completely, it is possible to share elements across multiple modules (i.e. workshops).  For example, the "CI-TRACS Code of Conduct" reading is defined once, and then included as a reading in all workshop modules. 

* Unlike Software Carpentry, Morea is not designed specifically for workshops. This makes it easier to support other kinds of educational activities, such as going through a Python tutorial. 

* By putting all material in a single site, Morea makes it easy to provide useful non-workshop material, such as an "Introduction" module with background material on the CI-TRACS program and information on how to get involved.

* For instructors, a very useful feature of Morea is [private files](https://morea-framework.github.io/docs/instructors/private-files), which enables instructors to keep exams, "to do" lists, notes for future instructors, and other information that is not appropriate for sharing with student participants.  
