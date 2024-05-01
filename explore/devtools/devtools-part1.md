1. What is the name of the new json file? citylots.json
2. Which file initiated the download of the new file? expose.js
3. What is the file size of the downloaded file? (Hint: you can find this in the network tab, or the response headers) 779 kb
4. How long did it take to download? 110 ms
5. What was your User-Agent for the browser that made the request? Mozilla/5.0 (Windows NT 10.0; Win64; x64) AppleWebKit/537.36 (KHTML, like Gecko) Chrome/124.0.0.0 Safari/537.36
6. In the response header, what type of server did it come from? GitHub.com
7. When was the file last modified? Thu, 15 Sep 2022 22:44:30 GMT
8. What was the Content-Type of the file? application/json; charset=utf-8
9. Which function inside the initiating file made the request? function fetchData() { fetch('./citylots.json') } function init() { document.getElementById('fetchData').addEventListener('click', fetchData); } window.addEventListener('DOMContentLoaded', init);

1. The bug was that num1 and num2 weren't initialized.
2. added initialization for it.