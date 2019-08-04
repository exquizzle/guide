---
title: Replacing If Else Chains with Switch
---
## Replacing If Else Chains with Switch

This is a stub. <a href='https://github.com/freecodecamp/guides/tree/master/src/pages/certifications/javascript-algorithms-and-data-structures/basic-javascript/replacing-if-else-chains-with-switch/index.md' target='_blank' rel='nofollow'>Help our community expand it</a>.

<a href='https://github.com/freecodecamp/guides/blob/master/README.md' target='_blank' rel='nofollow'>This quick style guide will help ensure your pull request gets accepted</a>.

<!-- The article goes here, in GitHub-flavored Markdown. Feel free to add YouTube videos, images, and CodePen/JSBin embeds  -->

/* 
Solution
*/

function chainToSwitch(val) {
  var answer = "";
  // Only change code below this line
  
  switch(val)  {
    case "bob":
      answer = "Marley";
      break;
    case 42:
      answer = "The Answer";
      break;
    case 1:
      answer = "There is no #1";
      break;
    case 99:
      answer = "Missed me by this much!";
      break;
    case 7:
      answer = "Ate Nine";
      break;
    default:
      answer = "";
      break;
  }

  
  // Only change code above this line  
  return answer;
}

// Change this value to test
chainToSwitch(7);
