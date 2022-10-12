# test
i don't know what im doing but its slay anyways 

https://github.com/SheepTester/uxdy/blob/main/webreg-scraping/scrape.ts 
^ look at this and then search "fetch" 

https://www.w3schools.com/jsref/api_fetch.asp



also hofohhfo hhdosg

<!DOCTYPE html>
<html>
<body>

<h1>JavaScript Fetch API</h1>
<h2>The fetch() Method</h2>
<p id="demo">Fetch a file to change this text.</p>

<script>
let response = await fetch('https://www.dictionary.com/e/word-of-the-day/');

if (response.ok) {
  let myText = await response.text();
  document.getElementById("demo").innerHTML = myText;
} else {
  alert("HTTP-Error: " + response.status);
}


</script>

</body>
</html>




<!-- <!DOCTYPE html>
<html>
<body>
<h1>JavaScript Fetch API</h1>
<h2>The fetch() Method</h2>
<p id="demo">Fetch a file to change this text.</p>

<script>
getText("fetch_info.txt");

async function getText(file) {
  let myObject = await fetch(file);
  let myText = await myObject.text();
  document.getElementById("demo").innerHTML = myText;
}
</script>

</body>
</html>

----------------------

lol

<!DOCTYPE html>
<html>
<body>

<h1>JavaScript Fetch API</h1>
<h2>The fetch() Method</h2>
<p id="demo">Fetch a file to change this text.</p>

<script>
let file = "fetch_info.txt"
fetch (file)
.then(x => x.text())
.then(y => document.getElementById("demo").innerHTML = y);
</script>

</body>
</html>



-->


0----------------0


<!DOCTYPE html>

<h1>JavaScript Fetch API</h1>
<h2>The fetch() Method</h2>
<p id="demo">Fetch a file to change this text.</p>

<script>
"use strict";

(async () => {
let response = await fetch('https://www.dictionary.com/e/word-of-the-day/');

let text = await response.text(); // read response body as text

document.getElementById("demo").innerHTML = text;

})()
</script>

=]

