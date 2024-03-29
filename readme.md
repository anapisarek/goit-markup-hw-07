https://anapisarek.github.io/goit-markup-hw-07/

# Task 07

1. Create a repository goit-markup-hw-07.
2. Clone the created repository and copy the previous work files into it.
3. Set up GitHub Pages and add a link to the live page in the header of the GitHub repository.

# Project file structure

```
- goit-markup-hw-07/
 - index.html
 - sass/
  - utils/
   -vars.scss
  - components/
   ... component style files
 - css/
  - main.min.css
  ... sourcemaps
 - images/
  ... image files
```

# Criteria for work acceptance by the tutor

<b>Project</b>

«A1» Refactoring of the project HTML-code is done using the BEM methodology.

«A2» Refactoring of the project CSS code is done using the SASS preprocessor.

«A3» In the root of the project, there is a sass folder, which contains all the preprocessor style sheets.

«A4» In the sass folder, there is a main.scss file, the main file into which all SASS fragments are imported (partials, _name.scss files).

«A5» Layout color palette and font sets are presented as variables in the variables.scss file in the sass/utils folder. CSS or SASS variables can be used (optionally).

«A6» For each component, a separate fragment style sheet is created in the sass/components folder. For example, _page-header.scss, _logo.scss, etc.

«A7» In the index.html and portfolio.html files, a minified style sheet, main.min.css from the css folder, is linked.

<b>Markup</b>

«B1» Proper naming of box classes according to the BEM methodology.

«B2» Proper naming of element classes according to the BEM methodology.

«B3» Proper naming of modifier classes according to BEM methodology.

«B4» Proper naming of mixin classes according to BEM methodology.

«B5» BEM class names are clear and descriptive, all in English.

<b>Styling</b>

«C1» Selector nesting is used.

«C2» Maximum selector nesting is 4 levels.

«C3» The concatenation operator (&) is used to describe pseudo-classes and pseudo-elements.