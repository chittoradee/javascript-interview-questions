# Complete JavaScript Interview Questions & Answers
<table>
  <thead>
    <tr>
      <th>No.</th>
      <th>Questions</th>
    </tr>
  </thead>
  <tbody>
    <tr>
	<td>1</td>
	<td><a href="#user-content-what-are-the-primitive-data-types-in-javascript">What are the primitive data types in javascript?</a></td>
</tr>
<tr>
	<td>2</td>
	<td><a href="#user-content-what-is-the-difference-between-null-and-undefined">What is the difference between null and undefined?</a></td>
</tr>
<tr>
	<td>3</td>
	<td><a href="#user-content-how-to-remove-duplicate-values-from-an-array">How to remove duplicate values from an array?</a></td>
</tr>
<tr>
	<td>4</td>
	<td><a href="#user-content-what-are-arrow-functions-in-es6">What are arrow functions in ES6?</a></td>
</tr>
<tr>
	<td>5</td>
	<td>What are the ES6 classes?</td>
</tr>
<tr>
	<td>6</td>
	<td>What are prototypes in javascript?</td>
</tr>
<tr>
	<td>7</td>
	<td>What is the this keyword?</td>
</tr>
<tr>
	<td>8</td>
	<td>Difference between event bubbling and capturing</td>
</tr>
<tr>
	<td>9</td>
	<td>What is Document Object Model (DOM)?</td>
</tr>
<tr>
	<td>10</td>
	<td>Difference between async and defer</td>
</tr>
<tr>
	<td>11</td>
	<td>What is event delegation</td>
</tr>
<tr>
	<td>12</td>
	<td>What is the difference between throttling and debouncing?</td>
</tr>
<tr>
	<td>13</td>
	<td>What are the Closures?</td>
</tr>
<tr>
	<td>14</td>
	<td>What are IIFE?</td>
</tr>
<tr>
	<td>15</td>
	<td>How to get geolocation with javascript?</td>
</tr>

  </tbody>
  </table>
  <ol dir="auto">
<li>
<h3 dir="auto"><a id="user-content-what-are-the-primitive-data-types-in-javascript" class="anchor" aria-hidden="true" href="#what-are-the-primitive-data-types-in-javascript"><svg class="octicon octicon-link" viewBox="0 0 16 16" version="1.1" width="16" height="16" aria-hidden="true"><path fill-rule="evenodd" d="M7.775 3.275a.75.75 0 001.06 1.06l1.25-1.25a2 2 0 112.83 2.83l-2.5 2.5a2 2 0 01-2.83 0 .75.75 0 00-1.06 1.06 3.5 3.5 0 004.95 0l2.5-2.5a3.5 3.5 0 00-4.95-4.95l-1.25 1.25zm-4.69 9.64a2 2 0 010-2.83l2.5-2.5a2 2 0 012.83 0 .75.75 0 001.06-1.06 3.5 3.5 0 00-4.95 0l-2.5 2.5a3.5 3.5 0 004.95 4.95l1.25-1.25a.75.75 0 00-1.06-1.06l-1.25 1.25a2 2 0 01-2.83 0z"></path></svg></a>What are the primitive data types in javascript</h3>
<p dir="auto">These six types are considered to be primitives. A primitive is not an object and has no methods
of its own. All primitives are immutable.</p>
<ol dir="auto">
<li>
<p dir="auto"><strong>String:</strong> Collection of characters i.e words.</p>
</li>
<li>
<p dir="auto"><strong>Number:</strong> integers, floats, etc.</p>
</li>
<li>
<p dir="auto"><strong>Boolean</strong> true or false</p>
</li>
<li>
<p dir="auto"><strong>Null</strong> it represents no value. However, the typeof(null) is an object in javascript</p>
</li>
<li>
<p dir="auto"><strong>Undefined</strong> a declared variable but hasn’t been given a value.</p>
</li>
<li>
<p dir="auto"><strong>Symbol</strong> a unique value that's not equal to any other value.</p>
</li>
</ol>
</li>
</ol>
<hr>
<ol start="2" dir="auto">
<li>
<h3 dir="auto"><a id="user-content-what-is-the-difference-between-null-and-undefined" class="anchor" aria-hidden="true" href="#what-is-the-difference-between-null-and-undefined"><svg class="octicon octicon-link" viewBox="0 0 16 16" version="1.1" width="16" height="16" aria-hidden="true"><path fill-rule="evenodd" d="M7.775 3.275a.75.75 0 001.06 1.06l1.25-1.25a2 2 0 112.83 2.83l-2.5 2.5a2 2 0 01-2.83 0 .75.75 0 00-1.06 1.06 3.5 3.5 0 004.95 0l2.5-2.5a3.5 3.5 0 00-4.95-4.95l-1.25 1.25zm-4.69 9.64a2 2 0 010-2.83l2.5-2.5a2 2 0 012.83 0 .75.75 0 001.06-1.06 3.5 3.5 0 00-4.95 0l-2.5 2.5a3.5 3.5 0 004.95 4.95l1.25-1.25a.75.75 0 00-1.06-1.06l-1.25 1.25a2 2 0 01-2.83 0z"></path></svg></a>What is the difference between null and undefined</h3>
<p dir="auto">In JavaScript, undefined means a variable has been declared but has not yet been assigned a value, such as:</p>
<div class="highlight highlight-source-js position-relative overflow-auto" data-snippet-clipboard-copy-content="var testVar;
console.log(testVar); //shows undefined
console.log(typeof testVar); //shows undefined"><pre><span class="pl-k">var</span> <span class="pl-s1">testVar</span><span class="pl-kos">;</span>
<span class="pl-smi">console</span><span class="pl-kos">.</span><span class="pl-en">log</span><span class="pl-kos">(</span><span class="pl-s1">testVar</span><span class="pl-kos">)</span><span class="pl-kos">;</span> <span class="pl-c">//shows undefined</span>
<span class="pl-smi">console</span><span class="pl-kos">.</span><span class="pl-en">log</span><span class="pl-kos">(</span><span class="pl-k">typeof</span> <span class="pl-s1">testVar</span><span class="pl-kos">)</span><span class="pl-kos">;</span> <span class="pl-c">//shows undefined</span></pre></div>
<p dir="auto">null is an assignment value. It can be assigned to a variable as a representation of no value:</p>
<div class="highlight highlight-source-js position-relative overflow-auto" data-snippet-clipboard-copy-content="var testVar = null;
console.log(testVar); //shows null
console.log(typeof testVar); //shows object"><pre><span class="pl-k">var</span> <span class="pl-s1">testVar</span> <span class="pl-c1">=</span> <span class="pl-c1">null</span><span class="pl-kos">;</span>
<span class="pl-smi">console</span><span class="pl-kos">.</span><span class="pl-en">log</span><span class="pl-kos">(</span><span class="pl-s1">testVar</span><span class="pl-kos">)</span><span class="pl-kos">;</span> <span class="pl-c">//shows null</span>
<span class="pl-smi">console</span><span class="pl-kos">.</span><span class="pl-en">log</span><span class="pl-kos">(</span><span class="pl-k">typeof</span> <span class="pl-s1">testVar</span><span class="pl-kos">)</span><span class="pl-kos">;</span> <span class="pl-c">//shows object</span></pre></div>
<p dir="auto">You may wonder why the typeof returns 'object' for a value that is null. This was actually an error in the original JavaScript implementation that was then copied in ECMAScript. Today, it is rationalized that null is considered a placeholder for an object, even though, technically, it is a primitive value."</p>
</li>
</ol>
<hr>
<ol start="3" dir="auto">
<li>
<h3 dir="auto"><a id="user-content-how-to-remove-duplicate-values-from-an-array" class="anchor" aria-hidden="true" href="#how-to-remove-duplicate-values-from-an-array"><svg class="octicon octicon-link" viewBox="0 0 16 16" version="1.1" width="16" height="16" aria-hidden="true"><path fill-rule="evenodd" d="M7.775 3.275a.75.75 0 001.06 1.06l1.25-1.25a2 2 0 112.83 2.83l-2.5 2.5a2 2 0 01-2.83 0 .75.75 0 00-1.06 1.06 3.5 3.5 0 004.95 0l2.5-2.5a3.5 3.5 0 00-4.95-4.95l-1.25 1.25zm-4.69 9.64a2 2 0 010-2.83l2.5-2.5a2 2 0 012.83 0 .75.75 0 001.06-1.06 3.5 3.5 0 00-4.95 0l-2.5 2.5a3.5 3.5 0 004.95 4.95l1.25-1.25a.75.75 0 00-1.06-1.06l-1.25 1.25a2 2 0 01-2.83 0z"></path></svg></a>How to remove duplicate values from an array</h3>
<p dir="auto">Using the Set constructor and the spread syntax:</p>
<div class="highlight highlight-source-js position-relative overflow-auto" data-snippet-clipboard-copy-content="uniq = [...new Set(array)];"><pre><span class="pl-s1">uniq</span> <span class="pl-c1">=</span> <span class="pl-kos">[</span>...<span class="pl-k">new</span> <span class="pl-v">Set</span><span class="pl-kos">(</span><span class="pl-s1">array</span><span class="pl-kos">)</span><span class="pl-kos">]</span><span class="pl-kos">;</span></pre></div>
<p dir="auto">for example  -</p>
<div class="highlight highlight-source-js position-relative overflow-auto" data-snippet-clipboard-copy-content="let arr = [1,2,1,1,4,6,3,5,2,6,5];
console.log([...new Set(arr)]);     //console.log([...new Set(arr)])"><pre><span class="pl-k">let</span> <span class="pl-s1">arr</span> <span class="pl-c1">=</span> <span class="pl-kos">[</span><span class="pl-c1">1</span><span class="pl-kos">,</span><span class="pl-c1">2</span><span class="pl-kos">,</span><span class="pl-c1">1</span><span class="pl-kos">,</span><span class="pl-c1">1</span><span class="pl-kos">,</span><span class="pl-c1">4</span><span class="pl-kos">,</span><span class="pl-c1">6</span><span class="pl-kos">,</span><span class="pl-c1">3</span><span class="pl-kos">,</span><span class="pl-c1">5</span><span class="pl-kos">,</span><span class="pl-c1">2</span><span class="pl-kos">,</span><span class="pl-c1">6</span><span class="pl-kos">,</span><span class="pl-c1">5</span><span class="pl-kos">]</span><span class="pl-kos">;</span>
<span class="pl-smi">console</span><span class="pl-kos">.</span><span class="pl-en">log</span><span class="pl-kos">(</span><span class="pl-kos">[</span>...<span class="pl-k">new</span> <span class="pl-v">Set</span><span class="pl-kos">(</span><span class="pl-s1">arr</span><span class="pl-kos">)</span><span class="pl-kos">]</span><span class="pl-kos">)</span><span class="pl-kos">;</span>    </pre></div>
</li>
</ol>
<hr>
<ol start="4" dir="auto">
<li>
<h3 dir="auto"><a id="user-content-what-are-arrow-functions-in-es6" class="anchor" aria-hidden="true" href="#what-are-arrow-functions-in-es6"><svg class="octicon octicon-link" viewBox="0 0 16 16" version="1.1" width="16" height="16" aria-hidden="true"><path fill-rule="evenodd" d="M7.775 3.275a.75.75 0 001.06 1.06l1.25-1.25a2 2 0 112.83 2.83l-2.5 2.5a2 2 0 01-2.83 0 .75.75 0 00-1.06 1.06 3.5 3.5 0 004.95 0l2.5-2.5a3.5 3.5 0 00-4.95-4.95l-1.25 1.25zm-4.69 9.64a2 2 0 010-2.83l2.5-2.5a2 2 0 012.83 0 .75.75 0 001.06-1.06 3.5 3.5 0 00-4.95 0l-2.5 2.5a3.5 3.5 0 004.95 4.95l1.25-1.25a.75.75 0 00-1.06-1.06l-1.25 1.25a2 2 0 01-2.83 0z"></path></svg></a>What are arrow functions in ES6</h3>
<p dir="auto">Arrow functions allow us to write shorter function syntax. The handling of this is also different in arrow functions compared to regular functions. In regular functions the this keyword represented the object that called the function, which could be the window, the document, a button or whatever. With arrow functions the this keyword always represents the object that defined the arrow function.</p>
<div class="highlight highlight-source-js position-relative overflow-auto" data-snippet-clipboard-copy-content="//before
hello = function() {
    return &quot;Hello World!&quot;;
}

//after
hello = () =&gt; {
    return &quot;Hello World!&quot;;
}"><pre><span class="pl-c">//before</span>
<span class="pl-en">hello</span> <span class="pl-c1">=</span> <span class="pl-k">function</span><span class="pl-kos">(</span><span class="pl-kos">)</span> <span class="pl-kos">{</span>
    <span class="pl-k">return</span> <span class="pl-s">"Hello World!"</span><span class="pl-kos">;</span>
<span class="pl-kos">}</span>

<span class="pl-c">//after</span>
<span class="pl-en">hello</span> <span class="pl-c1">=</span> <span class="pl-kos">(</span><span class="pl-kos">)</span> <span class="pl-c1">=&gt;</span> <span class="pl-kos">{</span>
    <span class="pl-k">return</span> <span class="pl-s">"Hello World!"</span><span class="pl-kos">;</span>
<span class="pl-kos">}</span></pre></div>
</li>
</ol>
<hr>
