# AYTClips - Watch, Listen and Learn  

### AYTClips Search Our Library of Clips!


-----------------------------------------

[Fediverse Account! (Currently Centralized)](https://threads.net/@superninjahomie1) [Contact](mailto:vxytllcbusinses@gmail.com) [©](./WhatYearIsIt.js)

  
  

Tutorials about Computer Studies
--------------------------------

  
![AYT04](https://yt3.googleusercontent.com/3CQAiWYlAgJf8cznr4wPE19Mj-SkiZXCyqT9gFDm6EFBVrBFprWYoCKq27EuPrkWnTeIbmf22A=s160-c-k-c0x00ffffff-no-rj)[@youtube.com/videos](https://www.youtube.com/@AYT04/videos)

## JavaScript Used:

```js
  // Documenting my Journey...
function myFunction() {
    var input, filter, ul, li, a, i, txtValue;
    input = document.getElementById("clipsearch");
    filter = input.value.toUpperCase();
    ul = document.getElementById("aytclips"); // 
    li = ul.getElementsByTagName("li"); // Catching the Clip Name. // Eg, '<h3>Bad Example of <i>Else If Statements</i>...</h3>'
    p = ul.getElementsByTagName("p"); // Catching the Creators Name. // Eg, '<p>Crash Adams</p>' // Might not work, feel free to contribute.
    for (i = 0; i < li.length; i++) {
        a = li[i].getElementsByTagName("h3")[0];
        txtValue = a.textContent || a.innerText;
        if (txtValue.toUpperCase().indexOf(filter) > -1) {
            li[i].style.display = "";
        } else {
            li[i].style.display = "none";
        }
    }
}
```