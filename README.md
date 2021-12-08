# Wet Run Futurecoder

> - [Issues](https://github.com/school-as-code-testing/wet-run-futurecoder/issues):
>   [`help-wanted`](https://github.com/school-as-code-testing/wet-run-futurecoder/issues?q=is%3Aopen+label%3Ahelp-wanted),
>   [`question`](https://github.com/school-as-code-testing/wet-run-futurecoder/issues?q=is%3Aopen+label%3Aquestion)
> - [Pull Requests](https://github.com/school-as-code-testing/wet-run-futurecoder/pulls)
> - [Discussions](https://github.com/school-as-code-testing/wet-run-futurecoder/discussions/)
> - [Study Board](https://github.com/school-as-code-testing/wet-run-futurecoder/projects/1)
>
> <details>
> <summary>Tech Support</summary>
>
> [![Rubber Ducky](./.school/assets/rubber-ducky.png)](https://rubberduckdebugging.com/)
>
>  </details>

---

## Getting Started

Cloning, installing, and running quality checks.

<details>
<summary>expand/collapse</summary>
<br>

1. `git clone git@github.com:school-as-code-testing/wet-run-futurecoder.git`
2. `cd wet-run-futurecoder`
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

## Path

futurecoder is ... https://futurecoder.io/course/#toc

### [The shell](https://futurecoder.io/course/#IntroducingTheShell)

- [vocabulary](https://github.com/school-as-code-testing/wet-run-futurecoder/projects/1?card_filter_query=milestone%3Athe-shell+label%3Avocabulary)
  |
  [snippets](https://github.com/school-as-code-testing/wet-run-futurecoder/projects/1?card_filter_query=milestone%3Athe-shell+label%3Asnippet)
  |
  [check-ins](https://github.com/school-as-code-testing/wet-run-futurecoder/issues/?q=milestone%3Athe-shell+label%3Acheck-in)
  |
  [retrospectives](https://github.com/school-as-code-testing/wet-run-futurecoder/issues/?q=milestone%3Athe-shell+label%3Aretrospective)
  | [milestone](https://github.com/lab-antwerp-1/home/milestone/0)

### [String basics](https://futurecoder.io/course/#IntroducingStrings)

- [vocabulary](https://github.com/school-as-code-testing/wet-run-futurecoder/projects/1?card_filter_query=milestone%3Astring-basics+label%3Avocabulary)
  |
  [snippets](https://github.com/school-as-code-testing/wet-run-futurecoder/projects/1?card_filter_query=milestone%3Astring-basics+label%3Asnippet)
  |
  [check-ins](https://github.com/school-as-code-testing/wet-run-futurecoder/issues/?q=milestone%3Astring-basics+label%3Acheck-in)
  |
  [retrospectives](https://github.com/school-as-code-testing/wet-run-futurecoder/issues/?q=milestone%3Astring-basics+label%3Aretrospective)
  | [milestone](https://github.com/lab-antwerp-1/home/milestone/0)

### [Variables](https://futurecoder.io/course/#IntroducingVariables)

- [vocabulary](https://github.com/school-as-code-testing/wet-run-futurecoder/projects/1?card_filter_query=milestone%3Avariables+label%3Avocabulary)
  |
  [snippets](https://github.com/school-as-code-testing/wet-run-futurecoder/projects/1?card_filter_query=milestone%3Avariables+label%3Asnippet)
  |
  [check-ins](https://github.com/school-as-code-testing/wet-run-futurecoder/issues/?q=milestone%3Avariables+label%3Acheck-in)
  |
  [retrospectives](https://github.com/school-as-code-testing/wet-run-futurecoder/issues/?q=milestone%3Avariables+label%3Aretrospective)
  | [milestone](https://github.com/lab-antwerp-1/home/milestone/0)

### [For loops](https://futurecoder.io/course/#IntroducingForLoops)

- [vocabulary](https://github.com/school-as-code-testing/wet-run-futurecoder/projects/1?card_filter_query=milestone%3Afor-loops+label%3Avocabulary)
  |
  [snippets](https://github.com/school-as-code-testing/wet-run-futurecoder/projects/1?card_filter_query=milestone%3Afor-loops+label%3Asnippet)
  |
  [check-ins](https://github.com/school-as-code-testing/wet-run-futurecoder/issues/?q=milestone%3Afor-loops+label%3Acheck-in)
  |
  [retrospectives](https://github.com/school-as-code-testing/wet-run-futurecoder/issues/?q=milestone%3Afor-loops+label%3Aretrospective)
  | [milestone](https://github.com/lab-antwerp-1/home/milestone/0)

### [If statements](https://futurecoder.io/course/#IntroducingIfStatements)

- [vocabulary](https://github.com/school-as-code-testing/wet-run-futurecoder/projects/1?card_filter_query=milestone%3Aif-statements+label%3Avocabulary)
  |
  [snippets](https://github.com/school-as-code-testing/wet-run-futurecoder/projects/1?card_filter_query=milestone%3Aif-statements+label%3Asnippet)
  |
  [check-ins](https://github.com/school-as-code-testing/wet-run-futurecoder/issues/?q=milestone%3Aif-statements+label%3Acheck-in)
  |
  [retrospectives](https://github.com/school-as-code-testing/wet-run-futurecoder/issues/?q=milestone%3Aif-statements+label%3Aretrospective)
  | [milestone](https://github.com/lab-antwerp-1/home/milestone/0)

### [Lists](https://futurecoder.io/course/#IntroducingLists)

- [vocabulary](https://github.com/school-as-code-testing/wet-run-futurecoder/projects/1?card_filter_query=milestone%3Alists+label%3Avocabulary)
  |
  [snippets](https://github.com/school-as-code-testing/wet-run-futurecoder/projects/1?card_filter_query=milestone%3Alists+label%3Asnippet)
  |
  [check-ins](https://github.com/school-as-code-testing/wet-run-futurecoder/issues/?q=milestone%3Alists+label%3Acheck-in)
  |
  [retrospectives](https://github.com/school-as-code-testing/wet-run-futurecoder/issues/?q=milestone%3Alists+label%3Aretrospective)
  | [milestone](https://github.com/lab-antwerp-1/home/milestone/0)

### [A bit more about strings](https://futurecoder.io/course/#SingleAndDoubleQuotesInStrings)

- [vocabulary](https://github.com/school-as-code-testing/wet-run-futurecoder/projects/1?card_filter_query=milestone%3Aa-bit-more-about-strings+label%3Avocabulary)
  |
  [snippets](https://github.com/school-as-code-testing/wet-run-futurecoder/projects/1?card_filter_query=milestone%3Aa-bit-more-about-strings+label%3Asnippet)
  |
  [check-ins](https://github.com/school-as-code-testing/wet-run-futurecoder/issues/?q=milestone%3Aa-bit-more-about-strings+label%3Acheck-in)
  |
  [retrospectives](https://github.com/school-as-code-testing/wet-run-futurecoder/issues/?q=milestone%3Aa-bit-more-about-strings+label%3Aretrospective)
  | [milestone](https://github.com/lab-antwerp-1/home/milestone/0)

### [Nested loops](https://futurecoder.io/course/#IntroducingNestedLoops)

- [vocabulary](https://github.com/school-as-code-testing/wet-run-futurecoder/projects/1?card_filter_query=milestone%3Anested-loops+label%3Avocabulary)
  |
  [snippets](https://github.com/school-as-code-testing/wet-run-futurecoder/projects/1?card_filter_query=milestone%3Anested-loops+label%3Asnippet)
  |
  [check-ins](https://github.com/school-as-code-testing/wet-run-futurecoder/issues/?q=milestone%3Anested-loops+label%3Acheck-in)
  |
  [retrospectives](https://github.com/school-as-code-testing/wet-run-futurecoder/issues/?q=milestone%3Anested-loops+label%3Aretrospective)
  | [milestone](https://github.com/lab-antwerp-1/home/milestone/0)

### [Functions](https://futurecoder.io/course/#DefiningFunctions)

- [vocabulary](https://github.com/school-as-code-testing/wet-run-futurecoder/projects/1?card_filter_query=milestone%3Afunctions+label%3Avocabulary)
  |
  [snippets](https://github.com/school-as-code-testing/wet-run-futurecoder/projects/1?card_filter_query=milestone%3Afunctions+label%3Asnippet)
  |
  [check-ins](https://github.com/school-as-code-testing/wet-run-futurecoder/issues/?q=milestone%3Afunctions+label%3Acheck-in)
  |
  [retrospectives](https://github.com/school-as-code-testing/wet-run-futurecoder/issues/?q=milestone%3Afunctions+label%3Aretrospective)
  | [milestone](https://github.com/lab-antwerp-1/home/milestone/0)

### [Boolean operators](https://futurecoder.io/course/#IntroducingOr)

- [vocabulary](https://github.com/school-as-code-testing/wet-run-futurecoder/projects/1?card_filter_query=milestone%3Aboolean-operators+label%3Avocabulary)
  |
  [snippets](https://github.com/school-as-code-testing/wet-run-futurecoder/projects/1?card_filter_query=milestone%3Aboolean-operators+label%3Asnippet)
  |
  [check-ins](https://github.com/school-as-code-testing/wet-run-futurecoder/issues/?q=milestone%3Aboolean-operators+label%3Acheck-in)
  |
  [retrospectives](https://github.com/school-as-code-testing/wet-run-futurecoder/issues/?q=milestone%3Aboolean-operators+label%3Aretrospective)
  | [milestone](https://github.com/lab-antwerp-1/home/milestone/0)

### [Tic tac toe project](https://futurecoder.io/course/#IntroducingTicTacToe)

- [vocabulary](https://github.com/school-as-code-testing/wet-run-futurecoder/projects/1?card_filter_query=milestone%3Atic-tac-toe-project+label%3Avocabulary)
  |
  [snippets](https://github.com/school-as-code-testing/wet-run-futurecoder/projects/1?card_filter_query=milestone%3Atic-tac-toe-project+label%3Asnippet)
  |
  [check-ins](https://github.com/school-as-code-testing/wet-run-futurecoder/issues/?q=milestone%3Atic-tac-toe-project+label%3Acheck-in)
  |
  [retrospectives](https://github.com/school-as-code-testing/wet-run-futurecoder/issues/?q=milestone%3Atic-tac-toe-project+label%3Aretrospective)
  | [milestone](https://github.com/lab-antwerp-1/home/milestone/0)

---

## Suggested Study

<details>
<summary>expand/collapse</summary>
<br />

- [python cheat sheet](http://sixthresearcher.com/wp-content/uploads/2016/12/Python3_reference_cheat_sheet.pdf)

</details>

---

## Learners

<h3 id="lpmi-13">Adam</h3>

- [questions](https://github.com/school-as-code-testing/wet-run-futurecoder/issues/?q=author%3Alpmi-13+label%3Aquestion)
  |
  [help-wanted](https://github.com/school-as-code-testing/wet-run-futurecoder/issues/?q=author%3Alpmi-13+label%3Ahelp-wanted)
  |
  [check-ins](https://github.com/school-as-code-testing/wet-run-futurecoder/issues/?q=author%3Alpmi-13+label%3Acheck-in)
  |
  [deliverables](https://github.com/school-as-code-testing/wet-run-futurecoder/projects/1?card_filter_query=autho%3AAdam+label%3Adeliverable)
  |
  [retrospectives](https://github.com/school-as-code-testing/wet-run-futurecoder/issues/?q=author%3Alpmi-13+label%3Aretrospective)
  | [lpmi-13](https://github.com/lpmi-13)

<details>
<summary>more about Adam</summary>
<br>

![lpmi-13 avatar](./.school/assets/avatars/lpmi-13.jpeg)

![lpmi-13 github activity](https://ghchart.rshah.org/lpmi-13)

![lpmi-13 github stats](https://github-readme-stats.vercel.app/api?username=lpmi-13&show_icons=true&theme=default&hide_title=true&hide_rank=true)

</details>

<h3 id="colevandersWands"><a href="https://colevandersWands.github.io">Evan</a></h3>

- [questions](https://github.com/school-as-code-testing/wet-run-futurecoder/issues/?q=author%3AcolevandersWands+label%3Aquestion)
  |
  [help-wanted](https://github.com/school-as-code-testing/wet-run-futurecoder/issues/?q=author%3AcolevandersWands+label%3Ahelp-wanted)
  |
  [check-ins](https://github.com/school-as-code-testing/wet-run-futurecoder/issues/?q=author%3AcolevandersWands+label%3Acheck-in)
  |
  [deliverables](https://github.com/school-as-code-testing/wet-run-futurecoder/projects/1?card_filter_query=autho%3AEvan+label%3Adeliverable)
  |
  [retrospectives](https://github.com/school-as-code-testing/wet-run-futurecoder/issues/?q=author%3AcolevandersWands+label%3Aretrospective)
  | [colevandersWands](https://github.com/colevandersWands)

<details>
<summary>more about Evan</summary>
<br>

![colevandersWands avatar](./.school/assets/avatars/colevandersWands.jpeg)

![colevandersWands github activity](https://ghchart.rshah.org/colevandersWands)

![colevandersWands github stats](https://github-readme-stats.vercel.app/api?username=colevandersWands&show_icons=true&theme=default&hide_title=true&hide_rank=true)

</details>
