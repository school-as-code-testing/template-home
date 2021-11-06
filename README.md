<!-- BEGIN HEADER -->


# School As Code Testing

> - [Issues](https://github.com/school-as-code-testing/home/issues): [`help-wanted`](https://github.com/school-as-code-testing/home/issues?q=is%3Aopen+label%3Ahelp-wanted), [`question`](https://github.com/school-as-code-testing/home/issues?q=is%3Aopen+label%3Aquestion)
> - [Discussions](https://github.com/school-as-code-testing/home/discussions/)
> - [Deliverables](https://github.com/school-as-code-testing/home/projects/1)
> - [Random Groups](https://school-as-code-testing.github.io/home/randomizer)
> <details>
> <summary>Tech Support</summary>
>
> [![Rubber Ducky](./assets/rubber-ducky.png)](https://rubberduckdebugging.com/)
>
>  </details>


<!-- END HEADER -->

This repository is yours to keep track of what you've covered so far, to get to
know each other, to share helpful resources, to practice collaboration
workflows, ... to do everything!

Slack is great for chatting but links and good explanations can easily get lost
in message history. Think of this repository as your class' forum and home page.

<!-- BEGIN TOC -->

- [Getting Started](#getting-started)
- [Class Calendar](#class-calendar)
- [Modules](#modules)
- [Students](#students)
- [Coaches](#coaches)
- Class Notes
  - [Vocabulary](./vocabulary) (_[PRs](https://github.com/school-as-code-testing/home/pulls?q=label%3Avocabulary)_)
  - [Snippets](./snippets) (_[PRs](https://github.com/school-as-code-testing/home/pulls?q=label%3Asnippets)_)
  - [Chill Zone](./chill-zone)
- HYF Links
  - [Student Guidebook](https://home.hackyourfuture.be/students)
  - [Curriculum](https://home.hackyourfuture.be/curriculum)
  - [Study Book](https://hackyourfuture.github.io/study)
  - [GitHub](https://github.com/hackyourfuturebelgium)
- [Using this Repo](#using-this-repo)

<!-- END TOC -->

---

## Getting Started

<!-- a guide to using this repository -->

<details>
<summary>expand/collapse</summary>
<br>

1. `git clone git@github.com:HackYourFutureBelgium/template-markdown.git`
2. `cd template-markdown`
3. `npm install`

## Code Quality Checks

- `npm run format`: Makes sure all the code in this repository is well-formatted
  (looks good).
- `npm run lint:ls`: Checks to make sure all folder and file names match the
  repository conventions.
- `npm run lint:md`: Will lint all of the Markdown files in this repository.
- `npm run lint:css`: Will lint all of the CSS files in this repository.
- `npm run validate:html`: Validates all HTML files in your project.
- `npm run spell-check`: Goes through all the files in this repository looking
  for words it doesn't recognize. Just because it says something is a mistake
  doesn't mean it is! It doesn't know every word in the world. You can add new
  correct words to the [./.cspell.json](./.cspell.json) file so they won't cause
  an error.
- `npm run accessibility -- ./path/to/file.html`: Runs an accessibility analysis
  on all HTML files in the given path and writes the report to
  `/accessibility_report`

## Continuous Integration (CI)

When you open a PR to `main`/`master` in your repository, GitHub will
automatically do a linting check on the code in this repository, you can see
this in the[./.github/workflows/lint.yml](./.github/workflows/lint.yml) file.

If the linting fails, you will not be able to merge the PR. You can double check
that your code will pass before pushing by running the code quality scripts
locally.

</details>

---

## Class Calendar

<details>
<summary>expand/collapse</summary>
<br>

![Lesson Plan Calendar](./assets/lesson-plan-calendar.png)

</details>

---

## Modules

<!-- BEGIN MODULES -->
  <ol start="1">

<li><h3><a href="https://home.hackyourfuture.be/curriculum/precourse" style="display: inline">precourse</a></h3>  <ul><li><p>    0 chapters   | <a href="https://github.com/school-as-code-testing/home/projects/1?card_filter_query=label%3Adeliverable+milestone%3Aprecourse">deliverables</a>     | <a href="https://github.com/school-as-code-testing/home/milestone/1">milestone</a> | <a href="https://github.com/HackYourFutureBelgium/precourse">materials</a>  </p></li></ul></li>
<li><h3><a href="https://home.hackyourfuture.be/curriculum/workflows" style="display: inline">workflows</a></h3>  <ul><li><p>    2 chapters   | <a href="https://github.com/school-as-code-testing/home/projects/1?card_filter_query=label%3Adeliverable+milestone%3Aworkflows">deliverables</a>    | <a href="https://github.com/school-as-code-testing/home/issues?q=milestone%3Aworkflows+label%3Acheck-in">check-ins</a>     | <a href="https://github.com/school-as-code-testing/home/milestone/2">milestone</a> | <a href="https://github.com/HackYourFutureBelgium/workflows">materials</a>  </p></li></ul></li>
<li><h3><a href="https://home.hackyourfuture.be/curriculum/agile-development" style="display: inline">agile-development</a></h3>  <ul><li><p>    3 chapters   | <a href="https://github.com/school-as-code-testing/home/projects/1?card_filter_query=label%3Adeliverable+milestone%3Aagile-development">deliverables</a>    | <a href="https://github.com/school-as-code-testing/home/issues?q=milestone%3Aagile-development+label%3Acheck-in">check-ins</a>     | <a href="https://github.com/school-as-code-testing/home/milestone/3">milestone</a> | <a href="https://github.com/HackYourFutureBelgium/agile-development">materials</a>  </p></li></ul></li>
<li><h3><a href="https://home.hackyourfuture.be/curriculum/ux-ui-design" style="display: inline">ux-ui-design</a></h3>  <ul><li><p>    2 chapters   | <a href="https://github.com/school-as-code-testing/home/projects/1?card_filter_query=label%3Adeliverable+milestone%3Aux-ui-design">deliverables</a>    | <a href="https://github.com/school-as-code-testing/home/issues?q=milestone%3Aux-ui-design+label%3Acheck-in">check-ins</a>     | <a href="https://github.com/school-as-code-testing/home/milestone/4">milestone</a> | <a href="https://github.com/HackYourFutureBelgium/ux-ui-design">materials</a>  </p></li></ul></li>
<li><h3><a href="https://home.hackyourfuture.be/curriculum/welcome-to-js" style="display: inline">welcome-to-js</a></h3>  <ul><li><p>    2 chapters   | <a href="https://github.com/school-as-code-testing/home/projects/1?card_filter_query=label%3Adeliverable+milestone%3Awelcome-to-js">deliverables</a>    | <a href="https://github.com/school-as-code-testing/home/issues?q=milestone%3Awelcome-to-js+label%3Acheck-in">check-ins</a>     | <a href="https://github.com/school-as-code-testing/home/milestone/5">milestone</a> | <a href="https://github.com/HackYourFutureBelgium/welcome-to-js">materials</a>  </p></li></ul></li>
<li><h3><a href="https://home.hackyourfuture.be/curriculum/debugging" style="display: inline">debugging</a></h3>  <ul><li><p>    4 chapters   | <a href="https://github.com/school-as-code-testing/home/projects/1?card_filter_query=label%3Adeliverable+milestone%3Adebugging">deliverables</a>    | <a href="https://github.com/school-as-code-testing/home/issues?q=milestone%3Adebugging+label%3Acheck-in">check-ins</a>     | <a href="https://github.com/school-as-code-testing/home/milestone/6">milestone</a> | <a href="https://github.com/HackYourFutureBelgium/debugging">materials</a>  </p></li></ul></li>
<li><h3><a href="https://home.hackyourfuture.be/curriculum/behavior-strategy-implementation" style="display: inline">behavior-strategy-implementation</a></h3>  <ul><li><p>    3 chapters   | <a href="https://github.com/school-as-code-testing/home/projects/1?card_filter_query=label%3Adeliverable+milestone%3Abehavior-strategy-implementation">deliverables</a>    | <a href="https://github.com/school-as-code-testing/home/issues?q=milestone%3Abehavior-strategy-implementation+label%3Acheck-in">check-ins</a>     | <a href="https://github.com/school-as-code-testing/home/milestone/7">milestone</a> | <a href="https://github.com/HackYourFutureBelgium/behavior-strategy-implementation">materials</a>  </p></li></ul></li>
<li><h3><a href="https://home.hackyourfuture.be/curriculum/separation-of-concerns" style="display: inline">separation-of-concerns</a></h3>  <ul><li><p>    3 chapters   | <a href="https://github.com/school-as-code-testing/home/projects/1?card_filter_query=label%3Adeliverable+milestone%3Aseparation-of-concerns">deliverables</a>    | <a href="https://github.com/school-as-code-testing/home/issues?q=milestone%3Aseparation-of-concerns+label%3Acheck-in">check-ins</a>     | <a href="https://github.com/school-as-code-testing/home/milestone/8">milestone</a> | <a href="https://github.com/HackYourFutureBelgium/separation-of-concerns">materials</a>  </p></li></ul></li>
<li><h3><a href="https://home.hackyourfuture.be/curriculum/architecture" style="display: inline">architecture</a></h3>  <ul><li><p>    4 chapters   | <a href="https://github.com/school-as-code-testing/home/projects/1?card_filter_query=label%3Adeliverable+milestone%3Aarchitecture">deliverables</a>    | <a href="https://github.com/school-as-code-testing/home/issues?q=milestone%3Aarchitecture+label%3Acheck-in">check-ins</a>     | <a href="https://github.com/school-as-code-testing/home/milestone/9">milestone</a> | <a href="https://github.com/HackYourFutureBelgium/architecture">materials</a>  </p></li></ul></li>
<li><h3><a href="https://home.hackyourfuture.be/curriculum/asynchronous-programming" style="display: inline">asynchronous-programming</a></h3>  <ul><li><p>    3 chapters   | <a href="https://github.com/school-as-code-testing/home/projects/1?card_filter_query=label%3Adeliverable+milestone%3Aasynchronous-programming">deliverables</a>    | <a href="https://github.com/school-as-code-testing/home/issues?q=milestone%3Aasynchronous-programming+label%3Acheck-in">check-ins</a>     | <a href="https://github.com/school-as-code-testing/home/milestone/10">milestone</a> | <a href="https://github.com/HackYourFutureBelgium/asynchronous-programming">materials</a>  </p></li></ul></li>
<li><h3><a href="https://home.hackyourfuture.be/curriculum/web-apps" style="display: inline">web-apps</a></h3>  <ul><li><p>    5 chapters   | <a href="https://github.com/school-as-code-testing/home/projects/1?card_filter_query=label%3Adeliverable+milestone%3Aweb-apps">deliverables</a>    | <a href="https://github.com/school-as-code-testing/home/issues?q=milestone%3Aweb-apps+label%3Acheck-in">check-ins</a>     | <a href="https://github.com/school-as-code-testing/home/milestone/11">milestone</a> | <a href="https://github.com/HackYourFutureBelgium/web-apps">materials</a>  </p></li></ul></li>
<li><h3><a href="https://home.hackyourfuture.be/curriculum/databases" style="display: inline">databases</a></h3>  <ul><li><p>    2 chapters   | <a href="https://github.com/school-as-code-testing/home/projects/1?card_filter_query=label%3Adeliverable+milestone%3Adatabases">deliverables</a>    | <a href="https://github.com/school-as-code-testing/home/issues?q=milestone%3Adatabases+label%3Acheck-in">check-ins</a>     | <a href="https://github.com/school-as-code-testing/home/milestone/12">milestone</a> | <a href="https://github.com/HackYourFutureBelgium/databases">materials</a>  </p></li></ul></li>
<li><h3><a href="https://home.hackyourfuture.be/curriculum/final-project" style="display: inline">final-project</a></h3>  <ul><li><p>    4 chapters   | <a href="https://github.com/school-as-code-testing/home/projects/1?card_filter_query=label%3Adeliverable+milestone%3Afinal-project">deliverables</a>    | <a href="https://github.com/school-as-code-testing/home/issues?q=milestone%3Afinal-project+label%3Acheck-in">check-ins</a>     | <a href="https://github.com/school-as-code-testing/home/milestone/13">milestone</a> | <a href="https://github.com/HackYourFutureBelgium/final-project">materials</a>  </p></li></ul></li>
</ol><br>


[TOP](#home)
<!-- END MODULES -->

---

## Students

<!-- BEGIN STUDENTS -->
  <ul  style="list-style-type:none;">

</ul><br>


[TOP](#home)
<!-- END STUDENTS -->

---

## Coaches

<!-- BEGIN COACHES -->
  <ul  style="list-style-type:none;">

</ul><br>


[TOP](#home)
<!-- END COACHES -->

---

## Using this Repo

<details>
<summary>Here are 5 tips for using issues in this repository:</summary>

### Help Wanted

- **The Template**: If you're blocked on something in an assignment or
  self-study you can use the `help-wanted` template to create a new issue and
  ask for help.
- **The Label**: You can attach the `help-wanted` label to any issue or PR that
  you need help completing. If the code you are blocked on is in another
  repository, you can create a new issue using the `help-wanted` template to
  describe your problem and link to your code.

### Question

- **The Template** Got a question about anything? Go ahead and ask! You can use
  create a new issue using the `question` template to ask your question in a
  clear and structured way.
- **The Label**: Or add the `question` label to any other issue! This can help
  be helpful for searching check-ins or deliverables.

### Check-Ins

> template + label

Each module you will create a new check-in issue. You will use this issue to
keep track of your self-study progress, and to post a check-in comment for each
chapter including:

- **I need help with**
- **What Went Well**
- **What Went Less Well**
- **Lessons Learned**
- **Prep Work** (for the next chapter)

### Deliverable

> template + label

For each project/exercise/assignment (individual or group) you will place a new
issue on the Class Projects board.

- If you are blocked, add the `help-wanted` label
- When you think you're finished, move your issue into the Ready for Review
  column
  - If your assignment is complete, a coach will move it into the Done column
  - Else they will move it to Needs Revision. When you've addressed the feedback
    you can move it back into Ready for Review

### Roll-Calls

Each Sunday before class your coach will create a new Roll Call issue. Leave a
little comment to say hello and let us all know how your week went.

</details>
<br>
