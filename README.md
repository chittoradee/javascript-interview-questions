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
	<td><a href="#user-content-what-are-the-es6-classes">What are the ES6 classes?</a></td>
</tr>
<tr>
	<td>6</td>
	<td><a href="#user-content-what-are-prototypes-in-javascript">What are prototypes in javascript?</a></td>
</tr>
<tr>
	<td>7</td>
	<td><a href="#user-content-what-is-the-this-keyword">What is the this keyword?</a></td>
</tr>
<tr>
	<td>8</td>
	<td><a href="#user-content-difference-between-event-bubbling-and-capturing">Difference between event bubbling and capturing</a></td>
</tr>
<tr>
	<td>9</td>
	<td><a href="#user-content-what-is-document-object-model-dom">What is Document Object Model (DOM)?</a></td>
</tr>
<tr>
	<td>10</td>
	<td><a href="#user-content-difference-between-async-and-defer">Difference between async and defer</a></td>
</tr>
<tr>
	<td>11</td>
	<td><a href="#user-content-what-is-event-delegation">What is event delegation</a></td>
</tr>
<tr>
	<td>12</td>
	<td><a href="#user-content-what-is-the-difference-between-throttling-and-debouncing">What is the difference between throttling and debouncing?</a></td>
</tr>
<tr>
	<td>13</td>
	<td><a href="#user-content-what-are-the-closures">What are the Closures?</a></td>
</tr>
<tr>
	<td>14</td>
	<td><a href="#user-content-what-are-iife">What are IIFE?</a></td>
</tr>
<tr>
	<td>15</td>
	<td><a href="#user-content-how-to-get-geolocation-with-javascript">How to get geolocation with javascript?</a></td>
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
<ol start="5" dir="auto">
<li>
<h3 dir="auto"><a id="user-content-what-are-the-es6-classes" class="anchor" aria-hidden="true" href="#what-are-the-es6-classes"><svg class="octicon octicon-link" viewBox="0 0 16 16" version="1.1" width="16" height="16" aria-hidden="true"><path fill-rule="evenodd" d="M7.775 3.275a.75.75 0 001.06 1.06l1.25-1.25a2 2 0 112.83 2.83l-2.5 2.5a2 2 0 01-2.83 0 .75.75 0 00-1.06 1.06 3.5 3.5 0 004.95 0l2.5-2.5a3.5 3.5 0 00-4.95-4.95l-1.25 1.25zm-4.69 9.64a2 2 0 010-2.83l2.5-2.5a2 2 0 012.83 0 .75.75 0 001.06-1.06 3.5 3.5 0 00-4.95 0l-2.5 2.5a3.5 3.5 0 004.95 4.95l1.25-1.25a.75.75 0 00-1.06-1.06l-1.25 1.25a2 2 0 01-2.83 0z"></path></svg></a>What are the ES6 classes</h3>
<p dir="auto">A JavaScript class is a blueprint for creating objects. A class encapsulates data and functions that manipulate the data.</p>
<p dir="auto">Unlike other programming languages such as Java and C++, JavaScript classes are syntactic sugar over the prototypal inheritance. In other words, ES6 classes are just special functions.</p>
<div class="highlight highlight-source-js position-relative overflow-auto" data-snippet-clipboard-copy-content="class Person {
    constructor(name) {
        this.name = name;
    }
    getName() {
        return this.name;
    }
}

let john = new Person(&quot;John Doe&quot;);

let name = john.getName();
console.log(name); // &quot;John Doe&quot;"><pre><span class="pl-k">class</span> <span class="pl-v">Person</span> <span class="pl-kos">{</span>
    <span class="pl-en">constructor</span><span class="pl-kos">(</span><span class="pl-s1">name</span><span class="pl-kos">)</span> <span class="pl-kos">{</span>
        <span class="pl-smi">this</span><span class="pl-kos">.</span><span class="pl-c1">name</span> <span class="pl-c1">=</span> <span class="pl-s1">name</span><span class="pl-kos">;</span>
    <span class="pl-kos">}</span>
    <span class="pl-en">getName</span><span class="pl-kos">(</span><span class="pl-kos">)</span> <span class="pl-kos">{</span>
        <span class="pl-k">return</span> <span class="pl-smi">this</span><span class="pl-kos">.</span><span class="pl-c1">name</span><span class="pl-kos">;</span>
    <span class="pl-kos">}</span>
<span class="pl-kos">}</span>

<span class="pl-k">let</span> <span class="pl-s1">john</span> <span class="pl-c1">=</span> <span class="pl-k">new</span> <span class="pl-v">Person</span><span class="pl-kos">(</span><span class="pl-s">"John Doe"</span><span class="pl-kos">)</span><span class="pl-kos">;</span>

<span class="pl-k">let</span> <span class="pl-s1">name</span> <span class="pl-c1">=</span> <span class="pl-s1">john</span><span class="pl-kos">.</span><span class="pl-en">getName</span><span class="pl-kos">(</span><span class="pl-kos">)</span><span class="pl-kos">;</span>
<span class="pl-smi">console</span><span class="pl-kos">.</span><span class="pl-en">log</span><span class="pl-kos">(</span><span class="pl-s1">name</span><span class="pl-kos">)</span><span class="pl-kos">;</span> <span class="pl-c">// "John Doe"</span></pre></div>
</li>
</ol>
<hr>
<ol start="6" dir="auto">
<li>
<h3 dir="auto"><a id="user-content-what-are-prototypes-in-javascript" class="anchor" aria-hidden="true" href="#what-are-prototypes-in-javascript"><svg class="octicon octicon-link" viewBox="0 0 16 16" version="1.1" width="16" height="16" aria-hidden="true"><path fill-rule="evenodd" d="M7.775 3.275a.75.75 0 001.06 1.06l1.25-1.25a2 2 0 112.83 2.83l-2.5 2.5a2 2 0 01-2.83 0 .75.75 0 00-1.06 1.06 3.5 3.5 0 004.95 0l2.5-2.5a3.5 3.5 0 00-4.95-4.95l-1.25 1.25zm-4.69 9.64a2 2 0 010-2.83l2.5-2.5a2 2 0 012.83 0 .75.75 0 001.06-1.06 3.5 3.5 0 00-4.95 0l-2.5 2.5a3.5 3.5 0 004.95 4.95l1.25-1.25a.75.75 0 00-1.06-1.06l-1.25 1.25a2 2 0 01-2.83 0z"></path></svg></a>What are prototypes in javascript</h3>
<p dir="auto">In JavaScript, prototype refers to a system. This system allows you to define properties on objects that can be accessed via the object’s instances.</p>
<p dir="auto">For example, an Array is a blueprint for array instances. You create an array instance with [] or new Array().</p>
<div class="highlight highlight-source-js position-relative overflow-auto" data-snippet-clipboard-copy-content="const array = ['one', 'two', 'three']
console.log(array);

// Same result as above
const array = new Array('one', 'two', 'three');"><pre><span class="pl-k">const</span> <span class="pl-s1">array</span> <span class="pl-c1">=</span> <span class="pl-kos">[</span><span class="pl-s">'one'</span><span class="pl-kos">,</span> <span class="pl-s">'two'</span><span class="pl-kos">,</span> <span class="pl-s">'three'</span><span class="pl-kos">]</span>
<span class="pl-smi">console</span><span class="pl-kos">.</span><span class="pl-en">log</span><span class="pl-kos">(</span><span class="pl-s1">array</span><span class="pl-kos">)</span><span class="pl-kos">;</span>

<span class="pl-c">// Same result as above</span>
<span class="pl-k">const</span> <span class="pl-s1">array</span> <span class="pl-c1">=</span> <span class="pl-k">new</span> <span class="pl-v">Array</span><span class="pl-kos">(</span><span class="pl-s">'one'</span><span class="pl-kos">,</span> <span class="pl-s">'two'</span><span class="pl-kos">,</span> <span class="pl-s">'three'</span><span class="pl-kos">)</span><span class="pl-kos">;</span></pre></div>
<p dir="auto">If you console.log this array you won’t see any methods, but you can use methods like concat, slice, filter, and map!</p>
<p dir="auto">Why?</p>
<p dir="auto">Because these methods are located in the Array’s prototype. You can expand the <strong>proto</strong> object (Chrome Devtools) or prototype object (Firefox Devtools) and you’ll see a list of methods.</p>
<p dir="auto">When you use map, JavaScript looks for map in the object itself. If map is not found, JavaScript will try to look for a Prototype. If JavaScript finds a prototype, it continues to search for map in that prototype.</p>
<p dir="auto">So the correct definition for Prototype is: An object that instances can access when they’re trying to look for a property.</p>
<hr>
<h5 dir="auto"><a id="user-content-prototype-chains" class="anchor" aria-hidden="true" href="#prototype-chains"><svg class="octicon octicon-link" viewBox="0 0 16 16" version="1.1" width="16" height="16" aria-hidden="true"><path fill-rule="evenodd" d="M7.775 3.275a.75.75 0 001.06 1.06l1.25-1.25a2 2 0 112.83 2.83l-2.5 2.5a2 2 0 01-2.83 0 .75.75 0 00-1.06 1.06 3.5 3.5 0 004.95 0l2.5-2.5a3.5 3.5 0 00-4.95-4.95l-1.25 1.25zm-4.69 9.64a2 2 0 010-2.83l2.5-2.5a2 2 0 012.83 0 .75.75 0 001.06-1.06 3.5 3.5 0 00-4.95 0l-2.5 2.5a3.5 3.5 0 004.95 4.95l1.25-1.25a.75.75 0 00-1.06-1.06l-1.25 1.25a2 2 0 01-2.83 0z"></path></svg></a>Prototype Chains</h5>
<p dir="auto">Step 1: JavaScript checks if the property is available inside the object. If yes, JavaScript uses the property straight away.</p>
<p dir="auto">Step 2: If the property is NOT inside the object, JavaScript checks if there’s a Prototype available. If there is a Prototype, repeat Step 1 (and check if the property is inside the prototype).</p>
<p dir="auto">Step 3: If there are no more Prototypes left, and JavaScript cannot find the property, it does returns undefined or throws error depending upon if you called a property or method.</p>
</li>
</ol>
<hr>
<ol start="7" dir="auto">
<li>
<h3 dir="auto"><a id="user-content-what-is-the-this-keyword" class="anchor" aria-hidden="true" href="#what-is-the-this-keyword"><svg class="octicon octicon-link" viewBox="0 0 16 16" version="1.1" width="16" height="16" aria-hidden="true"><path fill-rule="evenodd" d="M7.775 3.275a.75.75 0 001.06 1.06l1.25-1.25a2 2 0 112.83 2.83l-2.5 2.5a2 2 0 01-2.83 0 .75.75 0 00-1.06 1.06 3.5 3.5 0 004.95 0l2.5-2.5a3.5 3.5 0 00-4.95-4.95l-1.25 1.25zm-4.69 9.64a2 2 0 010-2.83l2.5-2.5a2 2 0 012.83 0 .75.75 0 001.06-1.06 3.5 3.5 0 00-4.95 0l-2.5 2.5a3.5 3.5 0 004.95 4.95l1.25-1.25a.75.75 0 00-1.06-1.06l-1.25 1.25a2 2 0 01-2.83 0z"></path></svg></a>What is the this keyword</h3>
<p dir="auto">The this references the object of which the function is a property. In other words, the this references the object that is currently calling the function.</p>
<p dir="auto">Suppose that you have an object called counter. This object counter has a method called next().</p>
<p dir="auto">When you call the next() method, you can access the this object.</p>
<div class="highlight highlight-source-js position-relative overflow-auto" data-snippet-clipboard-copy-content="const counter = {
    count: 0,
    next: function () {
        return ++this.count;
    }
};

counter.next();    "><pre><span class="pl-k">const</span> <span class="pl-s1">counter</span> <span class="pl-c1">=</span> <span class="pl-kos">{</span>
    <span class="pl-c1">count</span>: <span class="pl-c1">0</span><span class="pl-kos">,</span>
    <span class="pl-en">next</span>: <span class="pl-k">function</span> <span class="pl-kos">(</span><span class="pl-kos">)</span> <span class="pl-kos">{</span>
        <span class="pl-k">return</span> <span class="pl-c1">++</span><span class="pl-smi">this</span><span class="pl-kos">.</span><span class="pl-c1">count</span><span class="pl-kos">;</span>
    <span class="pl-kos">}</span>
<span class="pl-kos">}</span><span class="pl-kos">;</span>

<span class="pl-s1">counter</span><span class="pl-kos">.</span><span class="pl-en">next</span><span class="pl-kos">(</span><span class="pl-kos">)</span><span class="pl-kos">;</span>    </pre></div>
<p dir="auto">The next() is a function which is the property of the counter object. Therefore, inside the next() function, the this references the counter object.</p>
<p dir="auto">By the way, when a function is a property of an object, it is called a method.</p>
</li>
</ol>
<hr>
<ol start="11" dir="auto">
<li>
<h3 dir="auto"><a id="user-content-difference-between-currenttarget-property-and-target-property" class="anchor" aria-hidden="true" href="#difference-between-currenttarget-property-and-target-property"><svg class="octicon octicon-link" viewBox="0 0 16 16" version="1.1" width="16" height="16" aria-hidden="true"><path fill-rule="evenodd" d="M7.775 3.275a.75.75 0 001.06 1.06l1.25-1.25a2 2 0 112.83 2.83l-2.5 2.5a2 2 0 01-2.83 0 .75.75 0 00-1.06 1.06 3.5 3.5 0 004.95 0l2.5-2.5a3.5 3.5 0 00-4.95-4.95l-1.25 1.25zm-4.69 9.64a2 2 0 010-2.83l2.5-2.5a2 2 0 012.83 0 .75.75 0 001.06-1.06 3.5 3.5 0 00-4.95 0l-2.5 2.5a3.5 3.5 0 004.95 4.95l1.25-1.25a.75.75 0 00-1.06-1.06l-1.25 1.25a2 2 0 01-2.83 0z"></path></svg></a>Difference between currentTarget property and target property</h3>
<p dir="auto">In Javascript, events bubbles by default, so it becomes extremely important to understand the difference:</p>
<p dir="auto"><i>target</i> = element that triggered event</p>
<p dir="auto"><i>currentTarget</i> = element that listens to event.</p>
<p dir="auto">For example - you can have a click event listener on ul but if you click on li when target event.target will be li and event.currentTarget will be the ul.</p>
</li>
</ol>
<hr>
<ol start="8" dir="auto">
<li>
<h3 dir="auto"><a id="user-content-difference-between-event-bubbling-and-capturing" class="anchor" aria-hidden="true" href="#difference-between-event-bubbling-and-capturing"><svg class="octicon octicon-link" viewBox="0 0 16 16" version="1.1" width="16" height="16" aria-hidden="true"><path fill-rule="evenodd" d="M7.775 3.275a.75.75 0 001.06 1.06l1.25-1.25a2 2 0 112.83 2.83l-2.5 2.5a2 2 0 01-2.83 0 .75.75 0 00-1.06 1.06 3.5 3.5 0 004.95 0l2.5-2.5a3.5 3.5 0 00-4.95-4.95l-1.25 1.25zm-4.69 9.64a2 2 0 010-2.83l2.5-2.5a2 2 0 012.83 0 .75.75 0 001.06-1.06 3.5 3.5 0 00-4.95 0l-2.5 2.5a3.5 3.5 0 004.95 4.95l1.25-1.25a.75.75 0 00-1.06-1.06l-1.25 1.25a2 2 0 01-2.83 0z"></path></svg></a>Difference between event bubbling and capturing</h3>
<p dir="auto">Back in the old days, Netscape advocated event capturing, while Microsoft promoted event bubbling.</p>
<p dir="auto">Event bubbling and capturing are two ways of event propagation in the HTML DOM API, when an event occurs in an element inside another element, and both elements have registered a handle for that event. The event propagation mode determines in which order the elements receive the event.</p>
<p dir="auto">With bubbling, the event is first captured and handled by the innermost element and then propagated to outer elements.</p>
<p dir="auto">With capturing, the event is first captured by the outermost element and propagated to the inner elements.</p>
<p dir="auto">We can use the below code -</p>
<div class="highlight highlight-source-js position-relative overflow-auto" data-snippet-clipboard-copy-content="addEventListener(type, listener, useCapture)"><pre><span class="pl-en">addEventListener</span><span class="pl-kos">(</span><span class="pl-s1">type</span><span class="pl-kos">,</span> <span class="pl-s1">listener</span><span class="pl-kos">,</span> <span class="pl-s1">useCapture</span><span class="pl-kos">)</span></pre></div>
<p dir="auto">to register event handlers for in either bubbling (default) or capturing mode. To use the capturing model pass the third argument as true.</p>
</li>
</ol>
<hr>
<ol start="9" dir="auto">
<li>
<h3 dir="auto"><a id="user-content-what-is-document-object-model-dom" class="anchor" aria-hidden="true" href="#what-is-document-object-model-dom"><svg class="octicon octicon-link" viewBox="0 0 16 16" version="1.1" width="16" height="16" aria-hidden="true"><path fill-rule="evenodd" d="M7.775 3.275a.75.75 0 001.06 1.06l1.25-1.25a2 2 0 112.83 2.83l-2.5 2.5a2 2 0 01-2.83 0 .75.75 0 00-1.06 1.06 3.5 3.5 0 004.95 0l2.5-2.5a3.5 3.5 0 00-4.95-4.95l-1.25 1.25zm-4.69 9.64a2 2 0 010-2.83l2.5-2.5a2 2 0 012.83 0 .75.75 0 001.06-1.06 3.5 3.5 0 00-4.95 0l-2.5 2.5a3.5 3.5 0 004.95 4.95l1.25-1.25a.75.75 0 00-1.06-1.06l-1.25 1.25a2 2 0 01-2.83 0z"></path></svg></a>What is Document Object Model (DOM)</h3>
<p dir="auto">The Document Object Model (DOM) is a programming API for HTML and XML documents. The document object represents the whole html document.</p>
<p dir="auto">When html document is loaded in the browser, it becomes a document object. It is the root element that represents the html document. It has properties and methods. By the help of document object, we can add dynamic content to our web page.</p>
<p dir="auto">After the browser reads your HTML document, it creates a representational tree called the Document Object Model and defines how that tree can be accessed.</p>
<a target="_blank" rel="noopener noreferrer" href="https://camo.githubusercontent.com/733486ea4e7ca2311ea19dcecc01e6c6addf3795360be78ae2ae7ace0fb559fb/68747470733a2f2f63646e2d6d656469612d312e66726565636f646563616d702e6f72672f696d616765732f336e365350634d48306d6d47366346654233534a4245412d3959796667703378595a3775"><img src="https://camo.githubusercontent.com/733486ea4e7ca2311ea19dcecc01e6c6addf3795360be78ae2ae7ace0fb559fb/68747470733a2f2f63646e2d6d656469612d312e66726565636f646563616d702e6f72672f696d616765732f336e365350634d48306d6d47366346654233534a4245412d3959796667703378595a3775" alt="DOM" data-canonical-src="https://cdn-media-1.freecodecamp.org/images/3n6SPcMH0mmG6cFeB3SJBEA-9Yyfgp3xYZ7u" style="max-width: 100%;"></a>
<p dir="auto">In the image above, we can see the representational tree and how it is created by the browser. In this example, we have four important elements that you’re gonna see a lot:</p>
<p dir="auto"><i>Document:</i> It treats all the HTML documents.</p>
<p dir="auto"><i>Elements:</i> All the tags that are inside your HTML or XML turn into a DOM element.</p>
<p dir="auto"><i>Text:</i> All the tags’ content.</p>
<p dir="auto"><i>Attributes:</i> All the attributes from a specific HTML element. In the image, the attribute class=”hero” is an attribute from the "p" element.</p>
</li>
</ol>
<hr>
<ol start="10" dir="auto">
<li>
<h3 dir="auto"><a id="user-content-difference-between-async-and-defer" class="anchor" aria-hidden="true" href="#difference-between-async-and-defer"><svg class="octicon octicon-link" viewBox="0 0 16 16" version="1.1" width="16" height="16" aria-hidden="true"><path fill-rule="evenodd" d="M7.775 3.275a.75.75 0 001.06 1.06l1.25-1.25a2 2 0 112.83 2.83l-2.5 2.5a2 2 0 01-2.83 0 .75.75 0 00-1.06 1.06 3.5 3.5 0 004.95 0l2.5-2.5a3.5 3.5 0 00-4.95-4.95l-1.25 1.25zm-4.69 9.64a2 2 0 010-2.83l2.5-2.5a2 2 0 012.83 0 .75.75 0 001.06-1.06 3.5 3.5 0 00-4.95 0l-2.5 2.5a3.5 3.5 0 004.95 4.95l1.25-1.25a.75.75 0 00-1.06-1.06l-1.25 1.25a2 2 0 01-2.83 0z"></path></svg></a>Difference between async and defer</h3>
<p dir="auto">In modern websites, scripts are often “heavier” than HTML: their download size is larger, and processing time is also longer.</p>
<p dir="auto">When the browser loads HTML and comes across a &lt;script&gt;...&lt;/script&gt; tag, it can’t continue building the DOM. It must execute the script right now. The same happens for external scripts &lt;script src="..."&gt;&lt;/script&gt;: the browser must wait for the script to download, execute the downloaded script, and only then can it process the rest of the page.</p>
<p dir="auto">That leads to two important issues:</p>
<p dir="auto">Scripts can’t see DOM elements below them, so they can’t add handlers etc.</p>
<p dir="auto">If there’s a bulky script at the top of the page, it “blocks the page”. Users can’t see the page content till it downloads and runs.</p>
<p dir="auto">Luckily, there are two <i>script</i> attributes that solve the problem for us: defer and async.</p>
<h4 dir="auto"><a id="user-content-defer" class="anchor" aria-hidden="true" href="#defer"><svg class="octicon octicon-link" viewBox="0 0 16 16" version="1.1" width="16" height="16" aria-hidden="true"><path fill-rule="evenodd" d="M7.775 3.275a.75.75 0 001.06 1.06l1.25-1.25a2 2 0 112.83 2.83l-2.5 2.5a2 2 0 01-2.83 0 .75.75 0 00-1.06 1.06 3.5 3.5 0 004.95 0l2.5-2.5a3.5 3.5 0 00-4.95-4.95l-1.25 1.25zm-4.69 9.64a2 2 0 010-2.83l2.5-2.5a2 2 0 012.83 0 .75.75 0 001.06-1.06 3.5 3.5 0 00-4.95 0l-2.5 2.5a3.5 3.5 0 004.95 4.95l1.25-1.25a.75.75 0 00-1.06-1.06l-1.25 1.25a2 2 0 01-2.83 0z"></path></svg></a>Defer</h4>
<p dir="auto">The defer attribute tells the browser not to wait for the script. Instead, the browser will continue to process the HTML, build DOM. The script loads “in the background”, and then runs when the DOM is fully built.</p>
<h4 dir="auto"><a id="user-content-async" class="anchor" aria-hidden="true" href="#async"><svg class="octicon octicon-link" viewBox="0 0 16 16" version="1.1" width="16" height="16" aria-hidden="true"><path fill-rule="evenodd" d="M7.775 3.275a.75.75 0 001.06 1.06l1.25-1.25a2 2 0 112.83 2.83l-2.5 2.5a2 2 0 01-2.83 0 .75.75 0 00-1.06 1.06 3.5 3.5 0 004.95 0l2.5-2.5a3.5 3.5 0 00-4.95-4.95l-1.25 1.25zm-4.69 9.64a2 2 0 010-2.83l2.5-2.5a2 2 0 012.83 0 .75.75 0 001.06-1.06 3.5 3.5 0 00-4.95 0l-2.5 2.5a3.5 3.5 0 004.95 4.95l1.25-1.25a.75.75 0 00-1.06-1.06l-1.25 1.25a2 2 0 01-2.83 0z"></path></svg></a>Async</h4>
<p dir="auto">The async attribute is somewhat like defer. It also makes the script non-blocking. But it has important differences in the behavior. async scripts load in the background and run when ready.</p>
</li>
</ol>
<hr>
<ol start="11" dir="auto">
<li>
<h3 dir="auto"><a id="user-content-what-is-event-delegation" class="anchor" aria-hidden="true" href="#what-is-event-delegation"><svg class="octicon octicon-link" viewBox="0 0 16 16" version="1.1" width="16" height="16" aria-hidden="true"><path fill-rule="evenodd" d="M7.775 3.275a.75.75 0 001.06 1.06l1.25-1.25a2 2 0 112.83 2.83l-2.5 2.5a2 2 0 01-2.83 0 .75.75 0 00-1.06 1.06 3.5 3.5 0 004.95 0l2.5-2.5a3.5 3.5 0 00-4.95-4.95l-1.25 1.25zm-4.69 9.64a2 2 0 010-2.83l2.5-2.5a2 2 0 012.83 0 .75.75 0 001.06-1.06 3.5 3.5 0 00-4.95 0l-2.5 2.5a3.5 3.5 0 004.95 4.95l1.25-1.25a.75.75 0 00-1.06-1.06l-1.25 1.25a2 2 0 01-2.83 0z"></path></svg></a>What is event delegation</h3>
<p dir="auto">When building an application, sometimes you’ll need to attach event listeners to buttons, text, or images on the page in order to perform some action when the user interacts with the element.</p>
<p dir="auto">If we take a simple todo list as an example, the interviewer may tell you that they want an action to occur when a user clicks one of the list items. And they want you to implement this functionality in JavaScript assuming the following HTML code:</p>
<div class="highlight highlight-text-html-basic position-relative overflow-auto" data-snippet-clipboard-copy-content="&lt;ul id=&quot;todo-app&quot;&gt;
&lt;li class=&quot;item&quot;&gt;Walk the dog&lt;/li&gt;
&lt;li class=&quot;item&quot;&gt;Pay bills&lt;/li&gt;
&lt;li class=&quot;item&quot;&gt;Make dinner&lt;/li&gt;
&lt;li class=&quot;item&quot;&gt;Code for one hour&lt;/li&gt;
&lt;/ul&gt;"><pre><span class="pl-kos">&lt;</span><span class="pl-ent">ul</span> <span class="pl-c1">id</span>="<span class="pl-s">todo-app</span>"<span class="pl-kos">&gt;</span>
<span class="pl-kos">&lt;</span><span class="pl-ent">li</span> <span class="pl-c1">class</span>="<span class="pl-s">item</span>"<span class="pl-kos">&gt;</span>Walk the dog<span class="pl-kos">&lt;/</span><span class="pl-ent">li</span><span class="pl-kos">&gt;</span>
<span class="pl-kos">&lt;</span><span class="pl-ent">li</span> <span class="pl-c1">class</span>="<span class="pl-s">item</span>"<span class="pl-kos">&gt;</span>Pay bills<span class="pl-kos">&lt;/</span><span class="pl-ent">li</span><span class="pl-kos">&gt;</span>
<span class="pl-kos">&lt;</span><span class="pl-ent">li</span> <span class="pl-c1">class</span>="<span class="pl-s">item</span>"<span class="pl-kos">&gt;</span>Make dinner<span class="pl-kos">&lt;/</span><span class="pl-ent">li</span><span class="pl-kos">&gt;</span>
<span class="pl-kos">&lt;</span><span class="pl-ent">li</span> <span class="pl-c1">class</span>="<span class="pl-s">item</span>"<span class="pl-kos">&gt;</span>Code for one hour<span class="pl-kos">&lt;/</span><span class="pl-ent">li</span><span class="pl-kos">&gt;</span>
<span class="pl-kos">&lt;/</span><span class="pl-ent">ul</span><span class="pl-kos">&gt;</span></pre></div>
<p dir="auto">You may want to do something like the following to attach event listeners to the elements:</p>
<div class="highlight highlight-source-js position-relative overflow-auto" data-snippet-clipboard-copy-content="document.addEventListener('DOMContentLoaded', function() {

let app = document.getElementById('todo-app');
let items = app.getElementsByClassName('item');

// attach event listener to each item
for (let item of items) {
    item.addEventListener('click', function() {
    alert('you clicked on item: ' + item.innerHTML);
    });
}

});"><pre><span class="pl-smi">document</span><span class="pl-kos">.</span><span class="pl-en">addEventListener</span><span class="pl-kos">(</span><span class="pl-s">'DOMContentLoaded'</span><span class="pl-kos">,</span> <span class="pl-k">function</span><span class="pl-kos">(</span><span class="pl-kos">)</span> <span class="pl-kos">{</span>

<span class="pl-k">let</span> <span class="pl-s1">app</span> <span class="pl-c1">=</span> <span class="pl-smi">document</span><span class="pl-kos">.</span><span class="pl-en">getElementById</span><span class="pl-kos">(</span><span class="pl-s">'todo-app'</span><span class="pl-kos">)</span><span class="pl-kos">;</span>
<span class="pl-k">let</span> <span class="pl-s1">items</span> <span class="pl-c1">=</span> <span class="pl-s1">app</span><span class="pl-kos">.</span><span class="pl-en">getElementsByClassName</span><span class="pl-kos">(</span><span class="pl-s">'item'</span><span class="pl-kos">)</span><span class="pl-kos">;</span>

<span class="pl-c">// attach event listener to each item</span>
<span class="pl-k">for</span> <span class="pl-kos">(</span><span class="pl-k">let</span> <span class="pl-s1">item</span> <span class="pl-k">of</span> <span class="pl-s1">items</span><span class="pl-kos">)</span> <span class="pl-kos">{</span>
    <span class="pl-s1">item</span><span class="pl-kos">.</span><span class="pl-en">addEventListener</span><span class="pl-kos">(</span><span class="pl-s">'click'</span><span class="pl-kos">,</span> <span class="pl-k">function</span><span class="pl-kos">(</span><span class="pl-kos">)</span> <span class="pl-kos">{</span>
    <span class="pl-en">alert</span><span class="pl-kos">(</span><span class="pl-s">'you clicked on item: '</span> <span class="pl-c1">+</span> <span class="pl-s1">item</span><span class="pl-kos">.</span><span class="pl-c1">innerHTML</span><span class="pl-kos">)</span><span class="pl-kos">;</span>
    <span class="pl-kos">}</span><span class="pl-kos">)</span><span class="pl-kos">;</span>
<span class="pl-kos">}</span>

<span class="pl-kos">}</span><span class="pl-kos">)</span><span class="pl-kos">;</span></pre></div>
<p dir="auto">While this does technically work, the problem is that you’re attaching an event listener to every single item individually. This is fine for 4 elements, but what if someone adds 10,000 items (they may have a lot of things to do) to their todo list? Then your function will create 10,000 separate event listeners and attach each of them to the DOM. This isn’t very efficient.</p>
<p dir="auto">Here’s the code for event delegation:</p>
<div class="highlight highlight-source-js position-relative overflow-auto" data-snippet-clipboard-copy-content="document.addEventListener('DOMContentLoaded', function() {

let app = document.getElementById('todo-app');

// attach event listener to whole container
app.addEventListener('click', function(e) {
    if (e.target &amp;&amp; e.target.nodeName === 'LI') {
    let item = e.target;
    alert('you clicked on item: ' + item.innerHTML);
    }
});

});"><pre><span class="pl-smi">document</span><span class="pl-kos">.</span><span class="pl-en">addEventListener</span><span class="pl-kos">(</span><span class="pl-s">'DOMContentLoaded'</span><span class="pl-kos">,</span> <span class="pl-k">function</span><span class="pl-kos">(</span><span class="pl-kos">)</span> <span class="pl-kos">{</span>

<span class="pl-k">let</span> <span class="pl-s1">app</span> <span class="pl-c1">=</span> <span class="pl-smi">document</span><span class="pl-kos">.</span><span class="pl-en">getElementById</span><span class="pl-kos">(</span><span class="pl-s">'todo-app'</span><span class="pl-kos">)</span><span class="pl-kos">;</span>

<span class="pl-c">// attach event listener to whole container</span>
<span class="pl-s1">app</span><span class="pl-kos">.</span><span class="pl-en">addEventListener</span><span class="pl-kos">(</span><span class="pl-s">'click'</span><span class="pl-kos">,</span> <span class="pl-k">function</span><span class="pl-kos">(</span><span class="pl-s1">e</span><span class="pl-kos">)</span> <span class="pl-kos">{</span>
    <span class="pl-k">if</span> <span class="pl-kos">(</span><span class="pl-s1">e</span><span class="pl-kos">.</span><span class="pl-c1">target</span> <span class="pl-c1">&amp;&amp;</span> <span class="pl-s1">e</span><span class="pl-kos">.</span><span class="pl-c1">target</span><span class="pl-kos">.</span><span class="pl-c1">nodeName</span> <span class="pl-c1">===</span> <span class="pl-s">'LI'</span><span class="pl-kos">)</span> <span class="pl-kos">{</span>
    <span class="pl-k">let</span> <span class="pl-s1">item</span> <span class="pl-c1">=</span> <span class="pl-s1">e</span><span class="pl-kos">.</span><span class="pl-c1">target</span><span class="pl-kos">;</span>
    <span class="pl-en">alert</span><span class="pl-kos">(</span><span class="pl-s">'you clicked on item: '</span> <span class="pl-c1">+</span> <span class="pl-s1">item</span><span class="pl-kos">.</span><span class="pl-c1">innerHTML</span><span class="pl-kos">)</span><span class="pl-kos">;</span>
    <span class="pl-kos">}</span>
<span class="pl-kos">}</span><span class="pl-kos">)</span><span class="pl-kos">;</span>

<span class="pl-kos">}</span><span class="pl-kos">)</span><span class="pl-kos">;</span></pre></div>
</li>
</ol>
<hr>
<ol start="12" dir="auto">
<li>
<h3 dir="auto"><a id="user-content-what-is-the-difference-between-throttling-and-debouncing" class="anchor" aria-hidden="true" href="#what-is-the-difference-between-throttling-and-debouncing"><svg class="octicon octicon-link" viewBox="0 0 16 16" version="1.1" width="16" height="16" aria-hidden="true"><path fill-rule="evenodd" d="M7.775 3.275a.75.75 0 001.06 1.06l1.25-1.25a2 2 0 112.83 2.83l-2.5 2.5a2 2 0 01-2.83 0 .75.75 0 00-1.06 1.06 3.5 3.5 0 004.95 0l2.5-2.5a3.5 3.5 0 00-4.95-4.95l-1.25 1.25zm-4.69 9.64a2 2 0 010-2.83l2.5-2.5a2 2 0 012.83 0 .75.75 0 001.06-1.06 3.5 3.5 0 00-4.95 0l-2.5 2.5a3.5 3.5 0 004.95 4.95l1.25-1.25a.75.75 0 00-1.06-1.06l-1.25 1.25a2 2 0 01-2.83 0z"></path></svg></a>What is the difference between throttling and debouncing</h3>
</li>
</ol>
<p dir="auto"><strong>Throttling</strong> will delay executing a function. It will reduce the notifications of an event that fires multiple times. Throttling enforces a maximum number of times a function can be called over time. As in "execute this function at most once every 100 milliseconds."</p>
<p dir="auto"><strong>Debouncing</strong> will bunch a series of sequential calls to a function into a single call to that function. It ensures that one notification is made for an event that fires multiple times. Debouncing enforces that a function not be called again until a certain amount of time has passed without it being called. As in "execute this function only if 100 milliseconds have passed without it being called."</p>
<p dir="auto"><strong>Throttle (1 sec):</strong> Hello, I am a robot. As long as you keep pinging me, I will keep talking to you, but after exactly 1 second each. If you ping me for a reply before a second is elapsed, I will still reply to you at exactly 1 second interval. In other words, I just love to reply at exact intervals.</p>
<p dir="auto"><strong>Debounce (1 sec):</strong> Hi, I am that ^^ robot's cousin. As long as you keep pinging me, I am going to remain silent because I like to reply only after 1 second is passed since last time you pinged me. I don't know, if it is because I have an attitude problem or because I just don't like to interrupt people. In other words, if you keeping asking me for replies before 1 second is elapsed since your last invocation, you will never get a reply. Yeah yeah...go ahead! call me rude.</p>
<hr>
<ol start="13" dir="auto">
<li>
<h3 dir="auto"><a id="user-content-what-are-the-closures" class="anchor" aria-hidden="true" href="#what-are-the-closures"><svg class="octicon octicon-link" viewBox="0 0 16 16" version="1.1" width="16" height="16" aria-hidden="true"><path fill-rule="evenodd" d="M7.775 3.275a.75.75 0 001.06 1.06l1.25-1.25a2 2 0 112.83 2.83l-2.5 2.5a2 2 0 01-2.83 0 .75.75 0 00-1.06 1.06 3.5 3.5 0 004.95 0l2.5-2.5a3.5 3.5 0 00-4.95-4.95l-1.25 1.25zm-4.69 9.64a2 2 0 010-2.83l2.5-2.5a2 2 0 012.83 0 .75.75 0 001.06-1.06 3.5 3.5 0 00-4.95 0l-2.5 2.5a3.5 3.5 0 004.95 4.95l1.25-1.25a.75.75 0 00-1.06-1.06l-1.25 1.25a2 2 0 01-2.83 0z"></path></svg></a>What are the Closures</h3>
<p dir="auto">Whenever a function is invoked, a new scope is created for that call. The local variable declared inside the function belong to that scope – they can only be accessed from that function -. It’s very important to understand that before moving further.</p>
<p dir="auto">Remember:</p>
<ol dir="auto">
<li>The function scope is created for a function call, not for the function itself</li>
</ol>
<p dir="auto">2)Every function call creates a new scope</p>
<p dir="auto">When the function has finished the execution, the scope is usually destroyed.</p>
<div class="highlight highlight-source-js position-relative overflow-auto" data-snippet-clipboard-copy-content="
function buildName(name) { 
    var greeting = &quot;Hello, &quot; + name; 
    return greeting;
}"><pre><span class="pl-k">function</span> <span class="pl-en">buildName</span><span class="pl-kos">(</span><span class="pl-s1">name</span><span class="pl-kos">)</span> <span class="pl-kos">{</span> 
    <span class="pl-k">var</span> <span class="pl-s1">greeting</span> <span class="pl-c1">=</span> <span class="pl-s">"Hello, "</span> <span class="pl-c1">+</span> <span class="pl-s1">name</span><span class="pl-kos">;</span> 
    <span class="pl-k">return</span> <span class="pl-s1">greeting</span><span class="pl-kos">;</span>
<span class="pl-kos">}</span></pre></div>
<p dir="auto">The function buildName() declares a local variable greeting and returns it. Every function call creates a new scope with a new local variable and  after the function is done executing, we have no way to refer to that scope again, so it’s garbage collected.</p>
<p dir="auto">But how about when we have a link to that scope? Let’s look at the next function:</p>
<div class="highlight highlight-source-js position-relative overflow-auto" data-snippet-clipboard-copy-content="function buildName(name) { 
    var greeting = &quot;Hello, &quot; + name + &quot;!&quot;; 
    var sayName = function() {
        var welcome = greeting + &quot; Welcome!&quot;;
        console.log(greeting); 
    };
    return sayName; 
}

var sayMyName = buildName(&quot;John&quot;);
sayMyName();  // Hello, John. Welcome!
sayMyName();  // Hello, John. Welcome!
sayMyName();  // Hello, John. Welcome!"><pre><span class="pl-k">function</span> <span class="pl-en">buildName</span><span class="pl-kos">(</span><span class="pl-s1">name</span><span class="pl-kos">)</span> <span class="pl-kos">{</span> 
    <span class="pl-k">var</span> <span class="pl-s1">greeting</span> <span class="pl-c1">=</span> <span class="pl-s">"Hello, "</span> <span class="pl-c1">+</span> <span class="pl-s1">name</span> <span class="pl-c1">+</span> <span class="pl-s">"!"</span><span class="pl-kos">;</span> 
    <span class="pl-k">var</span> <span class="pl-en">sayName</span> <span class="pl-c1">=</span> <span class="pl-k">function</span><span class="pl-kos">(</span><span class="pl-kos">)</span> <span class="pl-kos">{</span>
        <span class="pl-k">var</span> <span class="pl-s1">welcome</span> <span class="pl-c1">=</span> <span class="pl-s1">greeting</span> <span class="pl-c1">+</span> <span class="pl-s">" Welcome!"</span><span class="pl-kos">;</span>
        <span class="pl-smi">console</span><span class="pl-kos">.</span><span class="pl-en">log</span><span class="pl-kos">(</span><span class="pl-s1">greeting</span><span class="pl-kos">)</span><span class="pl-kos">;</span> 
    <span class="pl-kos">}</span><span class="pl-kos">;</span>
    <span class="pl-k">return</span> <span class="pl-en">sayName</span><span class="pl-kos">;</span> 
<span class="pl-kos">}</span>

<span class="pl-k">var</span> <span class="pl-s1">sayMyName</span> <span class="pl-c1">=</span> <span class="pl-en">buildName</span><span class="pl-kos">(</span><span class="pl-s">"John"</span><span class="pl-kos">)</span><span class="pl-kos">;</span>
<span class="pl-s1">sayMyName</span><span class="pl-kos">(</span><span class="pl-kos">)</span><span class="pl-kos">;</span>  <span class="pl-c">// Hello, John. Welcome!</span>
<span class="pl-s1">sayMyName</span><span class="pl-kos">(</span><span class="pl-kos">)</span><span class="pl-kos">;</span>  <span class="pl-c">// Hello, John. Welcome!</span>
<span class="pl-s1">sayMyName</span><span class="pl-kos">(</span><span class="pl-kos">)</span><span class="pl-kos">;</span>  <span class="pl-c">// Hello, John. Welcome!</span></pre></div>
<p dir="auto">The function sayName() from this example is a closure.</p>
<p dir="auto">A closure is a function which has access to the variable from another function’s scope. This is accomplished by creating a function inside a function. Of course, the outer function does not have access to the inner scope.</p>
<p dir="auto">The sayName() function has it’s own local scope (with variable welcome) and has also access to the outer (enclosing) function’s scope. It this case, the variable greeting from buildName().</p>
<p dir="auto">After the execution of buildName is done, the scope is not destroyed in this case. The sayMyName() function still has access to it, so it won’t be garbage collected. However, there is not other way of accessing data from the outer scope except the closure.</p>
<p dir="auto">This is the big gotcha of the entire concept. The closure serve as the gateway between the global context and the outer scope. I cannot access directly variables from the outer scope if the closure is not allowing it. This way, I can protect the variables from the outer scope. They are – by all means – private and the closure can serve as a getter or setter for them.</p>
<p dir="auto">Remember:</p>
<ol dir="auto">
<li>
<p dir="auto">Closure are nested function which has access to the outer scope</p>
</li>
<li>
<p dir="auto">After the outer function is returned, by keeping a reference to the inner function (the closures) we prevent the outer scope to be destroyed.</p>
</li>
</ol>
<p dir="auto">Another extremely important thing to understand is that a closure is created at every function call. Whenever I’m using the closure, it will reference the same outer scope. If any variable is change in the outer scope, than the change will be visible in the next call as well.</p>
<div class="highlight highlight-source-js position-relative overflow-auto" data-snippet-clipboard-copy-content="function buildContor(i) { 
    var contor = i;
    var displayContor = function() {
        console.log(contor++);
        contor++;
    };
    return displayContor; 
}

var myContor = buildContor(1);
myContor(); // 1
myContor(); // 2
myContor(); // 3

// new closure - new outer scope - new contor variable
var myOtherContor = buildContor(10);
myOtherContor(); // 10 
myOtherContor(); // 11

// myContor was not affected 
myContor(); // 4"><pre><span class="pl-k">function</span> <span class="pl-en">buildContor</span><span class="pl-kos">(</span><span class="pl-s1">i</span><span class="pl-kos">)</span> <span class="pl-kos">{</span> 
    <span class="pl-k">var</span> <span class="pl-s1">contor</span> <span class="pl-c1">=</span> <span class="pl-s1">i</span><span class="pl-kos">;</span>
    <span class="pl-k">var</span> <span class="pl-en">displayContor</span> <span class="pl-c1">=</span> <span class="pl-k">function</span><span class="pl-kos">(</span><span class="pl-kos">)</span> <span class="pl-kos">{</span>
        <span class="pl-smi">console</span><span class="pl-kos">.</span><span class="pl-en">log</span><span class="pl-kos">(</span><span class="pl-s1">contor</span><span class="pl-c1">++</span><span class="pl-kos">)</span><span class="pl-kos">;</span>
        <span class="pl-s1">contor</span><span class="pl-c1">++</span><span class="pl-kos">;</span>
    <span class="pl-kos">}</span><span class="pl-kos">;</span>
    <span class="pl-k">return</span> <span class="pl-en">displayContor</span><span class="pl-kos">;</span> 
<span class="pl-kos">}</span>

<span class="pl-k">var</span> <span class="pl-s1">myContor</span> <span class="pl-c1">=</span> <span class="pl-en">buildContor</span><span class="pl-kos">(</span><span class="pl-c1">1</span><span class="pl-kos">)</span><span class="pl-kos">;</span>
<span class="pl-s1">myContor</span><span class="pl-kos">(</span><span class="pl-kos">)</span><span class="pl-kos">;</span> <span class="pl-c">// 1</span>
<span class="pl-s1">myContor</span><span class="pl-kos">(</span><span class="pl-kos">)</span><span class="pl-kos">;</span> <span class="pl-c">// 2</span>
<span class="pl-s1">myContor</span><span class="pl-kos">(</span><span class="pl-kos">)</span><span class="pl-kos">;</span> <span class="pl-c">// 3</span>

<span class="pl-c">// new closure - new outer scope - new contor variable</span>
<span class="pl-k">var</span> <span class="pl-s1">myOtherContor</span> <span class="pl-c1">=</span> <span class="pl-en">buildContor</span><span class="pl-kos">(</span><span class="pl-c1">10</span><span class="pl-kos">)</span><span class="pl-kos">;</span>
<span class="pl-s1">myOtherContor</span><span class="pl-kos">(</span><span class="pl-kos">)</span><span class="pl-kos">;</span> <span class="pl-c">// 10 </span>
<span class="pl-s1">myOtherContor</span><span class="pl-kos">(</span><span class="pl-kos">)</span><span class="pl-kos">;</span> <span class="pl-c">// 11</span>

<span class="pl-c">// myContor was not affected </span>
<span class="pl-s1">myContor</span><span class="pl-kos">(</span><span class="pl-kos">)</span><span class="pl-kos">;</span> <span class="pl-c">// 4</span></pre></div>
</li>
</ol>
<hr>
<ol start="14" dir="auto">
<li>
<h3 dir="auto"><a id="user-content-what-are-iife" class="anchor" aria-hidden="true" href="#what-are-iife"><svg class="octicon octicon-link" viewBox="0 0 16 16" version="1.1" width="16" height="16" aria-hidden="true"><path fill-rule="evenodd" d="M7.775 3.275a.75.75 0 001.06 1.06l1.25-1.25a2 2 0 112.83 2.83l-2.5 2.5a2 2 0 01-2.83 0 .75.75 0 00-1.06 1.06 3.5 3.5 0 004.95 0l2.5-2.5a3.5 3.5 0 00-4.95-4.95l-1.25 1.25zm-4.69 9.64a2 2 0 010-2.83l2.5-2.5a2 2 0 012.83 0 .75.75 0 001.06-1.06 3.5 3.5 0 00-4.95 0l-2.5 2.5a3.5 3.5 0 004.95 4.95l1.25-1.25a.75.75 0 00-1.06-1.06l-1.25 1.25a2 2 0 01-2.83 0z"></path></svg></a>What are IIFE</h3>
<p dir="auto">An immediately-invoked function expression (IIFE) immediately calls a function. This simply means that the function is executed immediately after the completion of the definition.</p>
<div class="highlight highlight-source-js position-relative overflow-auto" data-snippet-clipboard-copy-content="(function() {
    console.log('Welcome to the Github.');
}());"><pre><span class="pl-kos">(</span><span class="pl-k">function</span><span class="pl-kos">(</span><span class="pl-kos">)</span> <span class="pl-kos">{</span>
    <span class="pl-smi">console</span><span class="pl-kos">.</span><span class="pl-en">log</span><span class="pl-kos">(</span><span class="pl-s">'Welcome to the Github.'</span><span class="pl-kos">)</span><span class="pl-kos">;</span>
<span class="pl-kos">}</span><span class="pl-kos">(</span><span class="pl-kos">)</span><span class="pl-kos">)</span><span class="pl-kos">;</span></pre></div>
<ol dir="auto">
<li>
<p dir="auto">Avoiding pollution in the global namespace.</p>
</li>
<li>
<p dir="auto">Variables defined in IIFE (or even any normal function) don't overwrite definitions in global scope.</p>
</li>
<li>
<p dir="auto">Protecting code from being accessed by outer code.</p>
<p dir="auto">Everything that you define within the IIFE can be only be accessed within the IIFE. It protects code from being modified by outer code. Only what you explicitly return as the result of function or set as value to outer variables is accessible by outer code.</p>
</li>
<li>
<p dir="auto">Avoid naming functions that you don't need to use repeatedly. Though it's possible to use a named function in IIFE pattern you don't do it as there is no need to call it repeatedly, generally.</p>
</li>
<li>
<p dir="auto">For Universal Module Definitions which is used in many JS libraries. Check this question for details.</p>
</li>
</ol>
</li>
</ol>
<hr>
<ol start="15" dir="auto">
<li>
<h3 dir="auto"><a id="user-content-how-to-get-geolocation-with-javascript" class="anchor" aria-hidden="true" href="#how-to-get-geolocation-with-javascript"><svg class="octicon octicon-link" viewBox="0 0 16 16" version="1.1" width="16" height="16" aria-hidden="true"><path fill-rule="evenodd" d="M7.775 3.275a.75.75 0 001.06 1.06l1.25-1.25a2 2 0 112.83 2.83l-2.5 2.5a2 2 0 01-2.83 0 .75.75 0 00-1.06 1.06 3.5 3.5 0 004.95 0l2.5-2.5a3.5 3.5 0 00-4.95-4.95l-1.25 1.25zm-4.69 9.64a2 2 0 010-2.83l2.5-2.5a2 2 0 012.83 0 .75.75 0 001.06-1.06 3.5 3.5 0 00-4.95 0l-2.5 2.5a3.5 3.5 0 004.95 4.95l1.25-1.25a.75.75 0 00-1.06-1.06l-1.25 1.25a2 2 0 01-2.83 0z"></path></svg></a>How to get geolocation with javascript</h3>
<div class="highlight highlight-source-js position-relative overflow-auto" data-snippet-clipboard-copy-content="navigator.geolocation.getCurrentPosition(function(location) {
    console.log(location.coords.latitude);
    console.log(location.coords.longitude);
    console.log(location.coords.accuracy);
});"><pre><span class="pl-s1">navigator</span><span class="pl-kos">.</span><span class="pl-c1">geolocation</span><span class="pl-kos">.</span><span class="pl-en">getCurrentPosition</span><span class="pl-kos">(</span><span class="pl-k">function</span><span class="pl-kos">(</span><span class="pl-s1">location</span><span class="pl-kos">)</span> <span class="pl-kos">{</span>
    <span class="pl-smi">console</span><span class="pl-kos">.</span><span class="pl-en">log</span><span class="pl-kos">(</span><span class="pl-s1">location</span><span class="pl-kos">.</span><span class="pl-c1">coords</span><span class="pl-kos">.</span><span class="pl-c1">latitude</span><span class="pl-kos">)</span><span class="pl-kos">;</span>
    <span class="pl-smi">console</span><span class="pl-kos">.</span><span class="pl-en">log</span><span class="pl-kos">(</span><span class="pl-s1">location</span><span class="pl-kos">.</span><span class="pl-c1">coords</span><span class="pl-kos">.</span><span class="pl-c1">longitude</span><span class="pl-kos">)</span><span class="pl-kos">;</span>
    <span class="pl-smi">console</span><span class="pl-kos">.</span><span class="pl-en">log</span><span class="pl-kos">(</span><span class="pl-s1">location</span><span class="pl-kos">.</span><span class="pl-c1">coords</span><span class="pl-kos">.</span><span class="pl-c1">accuracy</span><span class="pl-kos">)</span><span class="pl-kos">;</span>
<span class="pl-kos">}</span><span class="pl-kos">)</span><span class="pl-kos">;</span></pre></div>
</li>
</ol>
<hr>
