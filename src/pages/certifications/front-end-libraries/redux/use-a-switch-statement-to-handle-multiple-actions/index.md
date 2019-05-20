---
title: Use a Switch Statement to Handle Multiple Actions
---
## Use a Switch Statement to Handle Multiple Actions

### Hint 1
Tip: Make sure you don't use "break" commands after return statements within the switch cases.


### Hint 2
### Solution
Don't forget to use the ````return```` command to return the value of each case statement.

````
  switch (action.type) {
    case 'LOGIN':
      return { authenticated: true }

    case 'LOGOUT':
      return { authenticated: false }

    default: return state;
  }
````

This is a stub. <a href='https://github.com/freecodecamp/guides/tree/master/src/pages/certifications/front-end-libraries/redux/use-a-switch-statement-to-handle-multiple-actions/index.md' target='_blank' rel='nofollow'>Help our community expand it</a>.

<a href='https://github.com/freecodecamp/guides/blob/master/README.md' target='_blank' rel='nofollow'>This quick style guide will help ensure your pull request gets accepted</a>.

<!-- The article goes here, in GitHub-flavored Markdown. Feel free to add YouTube videos, images, and CodePen/JSBin embeds  -->
