<!--

  you will write dev strategies in this module basically the same as in Incremental Developments
  the only difference is that there are now more types of tasks, for example:
    `type: css`
    `type: html`
    `type: logic`
    `type: handlers`
    `type: procedures`
    `type: listeners`
    `type: init`
    `type: data`
    ...

  a single user story may require a little bit of code in each of these folders
  it will take some time and practice to get used to this

-->

## Input words `for: input words`

### css `type: css`

- Size of the input field and buttons.
- Red color for warning message.

### html `type: html`

Input form:

- Input field (name="text")
- Button Add (type=button)
- Button Remove (type=button)

Warnings <code id="warnings" class="warning"></code>

### logic `type: logic`

- _const isWord_: to test if input is a word (check every symbol for being a letter of latin alphabet). If it is not - send warning.

### handlers `type: handlers`

- _const handleInputWord_ - functional expression to add word in the list.

### procedures `type: procedures`

- update list _const updateList_ - function that renders an array of strings as an unordered list into the #list-container element.

### listeners `type: listeners`

- for input form with id 'input-form' to perform handleInputWord (event handler) triggered by 'click'.

### init `type: init`

- import listener for input word so it can attach to the DOM.

### data `type: data`

- _const data_ - object that contains:

- an array of words that the user has provided.
- a string indicating the order string should be displayed in the UI.
