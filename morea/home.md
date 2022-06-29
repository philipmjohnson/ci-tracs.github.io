---
title: "Home"
morea_id: home
morea_type: home
published: true
---

<div class="alert alert-danger mt-4" role="alert" markdown="1">
<i class="fa-solid fa-circle-exclamation fa-xl"></i> **Warning: This is not the real CI-TRACS site.**
<hr/>

This site is currently a mockup that is intended to help us understand:

1. How the CI-TRACS workshops could be represented as Morea modules, and
2. The pros and cons of Morea vs. Software Carpentry

It does not include all of the CI-TRACS workshops and/or material that would be needed for a real CI-TRACS site.

The "real" CI-TRACS site is at: [https://github.com/ci-tracs](https://github.com/ci-tracs)
</div>

## Welcome to CI-TRACS

You have reached the home page for the University of Hawaii CyberInsfrastructure TRaining to Advance Climate Science (CI-TRACS) project. This site provides access to a number of modules, many of which provide access to materials in support of one day workshops presented by the CI-TRACS team.  


## About this site

Each CI-TRACS workshop is represented as a separate module. Each workshop module has one or more of the following components:

  * [Prerequisites](/prerequisites), describing skills you should acquire in order to be ready for the module.
  * [Learning outcomes](/outcomes), describing the major goals for the module.
  * [Readings and other online resources](/readings), providing background or reference material.
  * [Experiential learning activities](/experiences), providing a structured set of exercises enabling you to acquire mastery of material.
  * [Assessments](/assessments), which help you determine if you have acquired mastery of the material.

In addition, there are a few non-Workshop modules that provide useful additional information for CI-TRACS.

<div class="alert alert-info" role="alert" markdown="1">
<i class="fa-solid fa-circle-info fa-xl"></i> **Morea vs Software Carpentry**
<hr/>

In the [real CI-TRACS site](https://github.com/ci-tracs), many (but not all) workshops are implemented using the [Software Carpentry](https://carpentries.org/) workshop format.  The development of this Morea site helps clarify some of the pros and cons of these two approaches:

**Potential Advantages of Software Carpentry**

* In some cases, a CI-TRACS workshop might be a (barely modified) fork of an existing Software Carpentry workshop. In this case, it is less work to simply make a fork than to re-represent the workshop using Morea.

* Each Software Carpentry page has arrow links to go forward and backward, which simplifies linear navigation within a workshop. In Morea, when you finish a page, there is no "next" link. Instead, you have to go back up to the Module level and then down into the next page.

* Software Carpentry has specialized support for workshops, such as a timeline of activities. So, for representing workshops, Software Carpentry has some UI advantages.

* CI-TRACS personnel are already familiar with Software Carpentry and understand how to use it. Unless they've already used it, CI-TRACS folks will additional work to learn how to use Morea.  Documentation on Morea is available at: [https://morea-framework.github.io/](https://morea-framework.github.io/).

**Potential Advantages of Morea**

* Morea implements a single site where each workshop is represented as a module. This makes it easy to: represent (and inter-relate) all of the workshops; browse the workshops for users; and show relationships between workshops.  The Software Carpentry approach results in entirely independent sites for each workshop. Currently, the point of entry to all the workshops is the [CI-TRACS github organization home page](https://github.com/CI-TRACS), which is not particularly user friendly. To create a better top-level "portal" for the current approach, one would have to create a brand new site (presumably in the ci-tracs/ci-tracs.github.io repo), which would need to be updated manually to maintain consistency as the set of workshops change over time.

* Morea implements a [pedagogical pattern](https://morea-framework.github.io/docs/instructors/pedagogical-pattern) (Outcomes, Readings, Experiences, Assessments). This pattern helps instructors represent workshops in a consistent manner, and helps them to assess whether or not they are missing useful pedagogical elements (for example, Assessments seems to be lacking in most of the Workshops).  In addition to helping instructors structure their workshops consistently and completely, it is possible to share elements across multiple modules (i.e. workshops).  For example, the "CI-TRACS Code of Conduct" reading is defined once, and then included as a reading in all workshop modules. Similarly, the "Python and Jupyter" module is a prerequisite for multiple workshops.

* Unlike Software Carpentry, Morea is not designed specifically for workshops. This makes it easier to expand CI-TRACS to support other kinds of educational activities.

* By putting all material in a single site, Morea makes it easy to provide useful non-workshop material, such as an "Introduction" module with background material on the CI-TRACS program and information on how to get involved.

* For instructors, a very useful feature of Morea is [private files](https://morea-framework.github.io/docs/instructors/private-files), which enables instructors to keep exams, "to do" lists, notes for future instructors, and other information that is not appropriate for sharing with student participants.

</div>
