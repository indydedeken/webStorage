<h1>Web Storage (sessionStorage & localStorage)</h1>

Spec W3C : http://www.w3.org/TR/webstorage/#contents
D'après un article de alsacreations.com (<a href="http://www.alsacreations.com/article/lire/1402-web-storage-localstorage-sessionstorage.html">celui-ci</a>).<br>
Testing web storage, some examples of using.

<h2>The Storage interface</h2>

<pre>localStorage.length; // no comment</pre>
<pre>localStorage.key(Unsigned long index); // return the name of the key</pre>
<pre>localStorage.getItem("String key"); // get the value of the key</pre>
<pre>localStorage.setItem("String key", "String value"); // set a couple of key/value </pre>
<pre>localStorage.removeItem("String key"); // remove a specific key</pre>
<pre>localStorage.clear(); // delete all keys</pre>