<h1>SafeEval</h1>
<p>A safe, secure, and simple version of the eval function in PHP.</p>
<h1>How to Install:</h1>
<ol>
<li>Copy "interpret.php" onto your webserver</li>
<li>Use <code>require_once("interpret.php")</code></li>
<li>Where you would normally use eval, use <code>safeEval(<i>code</i>)</code></li>
<i>NOTE: Do not include any <code>&lt;?php</code> and <code>?&gt;</code> tags in the code which you want to run.</i>
</ol>
<h1>How Does It Work?</h1>
SafeEval uses rextester.com in order to remotely execute any code that is passed to it. 
This is more of a proof-of-concept than anything else, and introduces too many of its own security flaws to be considered remotely useful.
