# Medium Posts:

<h1 id="a-collection-of-my-most-useful-gist-entries">A Collection of my most useful Gist Entries</h1>
<p>This list is in no particular order!</p>
<hr />
<h3 id="a-collection-of-my-most-useful-gist-entries-1">A Collection of my most useful Gist Entries</h3>
<p><strong>This list is in no particular order!</strong></p>
<p><a href="https://blog2-backup.netlify.app/" class="markup--anchor markup--mixtapeEmbed-anchor" title="https://blog2-backup.netlify.app/"><strong>Web-Dev-Hub</strong>
<br/>

<em>Memoization, Tabulation, and Sorting Algorithms by Example Why is looking at runtime not a reliable method of…</em>bgoonz-blog.netlify.app</a><a href="https://blog2-backup.netlify.app/" class="js-mixtapeImage mixtapeImage u-ignoreBlock"></a></p>

<h3 id="ubuntu-setup">Ubuntu Setup:</h3>
<h3 id="markdown-notes-template">Markdown Notes Template:</h3>
<h3 id="jquery-cheat-sheet">Jquery Cheat Sheet:</h3>
<h3 id="useful-bash-commands">Useful Bash Commands:</h3>
<h3 id="python-cheat-sheet">Python Cheat Sheet:</h3>
<h3 id="html-cheat-sheet">Html Cheat Sheet:</h3>
<h3 id="git-cheat-sheet">Git Cheat Sheet:</h3>
<h3 id="deploy-react-app-to-heroku">Deploy React App To Heroku:</h3>
<h3 id="bash-aliases">Bash Aliases:</h3>
<h3 id="js-cheat-sheet">JS Cheat Sheet:</h3>
<h3 id="css-cheat-sheet">CSS Cheat Sheet:</h3>
<h4 id="if-you-found-this-guide-helpful-feel-free-to-checkout-my-githubgists-where-i-host-similar-content">If you found this guide helpful feel free to checkout my github/gists where I host similar content:</h4>
<p><a href="https://gist.github.com/bgoonz" class="markup--anchor markup--p-anchor">bgoonz's gists · GitHub</a></p>
<p><a href="https://github.com/bgoonz" class="markup--anchor markup--mixtapeEmbed-anchor" title="https://github.com/bgoonz"><strong>bgoonz — Overview</strong>
<br/>

<em>Web Developer, Electrical Engineer JavaScript | CSS | Bootstrap | Python | React | Node.js | Express | Sequelize…</em>github.com</a><a href="https://github.com/bgoonz" class="js-mixtapeImage mixtapeImage u-ignoreBlock"></a></p>

<p>Or Checkout my personal Resource Site:</p>
<p><a href="https://blog2-backup.netlify.app/" class="markup--anchor markup--p-anchor">https://blog2-backup.netlify.app/</a></p>
<p>By <a href="https://medium.com/@bryanguner" class="p-author h-card">Bryan Guner</a> on <a href="https://medium.com/p/f4314f3ba3ab">March 6, 2021</a>.</p>
<p><a href="https://medium.com/@bryanguner/a-collection-of-my-most-useful-gist-entries-f4314f3ba3ab" class="p-canonical">Canonical link</a></p>
<p>Exported from <a href="https://medium.com">Medium</a> on August 31, 2021.</p>
<h1 id="a-comprehensive-deep-dive-into-react">A Comprehensive Deep Dive into React</h1>
<p>An in-depth look into the world of React.</p>
<hr />
<h3 id="react-in-depth-a-comprehensive-guide">React in Depth: A Comprehensive Guide</h3>
<h4 id="a-deep-dive-into-the-world-of-react.">A deep dive into the world of React.</h4>
<figure>
<img src="https://cdn-images-1.medium.com/max/800/0*LnugLVhKbiGfSSHr" alt="Photo by Ferenc Almasi on Unsplash" class="graf-image" />
<figcaption>
Photo by <a href="https://unsplash.com/@flowforfrank?utm_source=medium&amp;utm_medium=referral" class="markup--anchor markup--figure-anchor">Ferenc Almasi</a> on <a href="https://unsplash.com?utm_source=medium&amp;utm_medium=referral" class="markup--anchor markup--figure-anchor">Unsplash</a>
</figcaption>
</figure>
<p> </p>
<h3 id="random-things-to-remember">Random Things to Remember</h3>
<ul>
<li><span id="1e39">Using <code>()</code> implictly returns components.</span></li>
<li><span id="a547">Role of <code>index.js</code> is to <em>render</em> your application.</span></li>
<li><span id="c38f">The reference to <code>root</code> comes from a div in the body of your public HTML file.</span></li>
<li><span id="a364">State of a component is simply a regular JS Object.</span></li>
<li><span id="d64b">Class Components require <code>render()</code> method to return JSX.</span></li>
<li><span id="fa3d">Functional Components directly return JSX.</span></li>
<li><span id="4928"><code>Class</code> is <code>className</code> in React.</span></li>
<li><span id="e51a">When parsing for an integer just chain <code>Number.parseInt("123")</code></span></li>
<li><span id="2924">Use ternary operator if you want to make a conditional inside a fragment.</span></li>
</ul>
<!-- -->
<pre><code>{ x === y ? &lt;div&gt;Naisu&lt;/div&gt; : &lt;div&gt;Not Naisu&lt;/div&gt;; }</code></pre>
<ul>
<li><span id="ccda">Purpose of <code>React.Fragment</code> is to allow you to create groups of children without adding an extra dom element.</span></li>
</ul>
<hr />
<h3 id="front-end-history">Front-End History</h3>
<ul>
<li><span id="904c">React makes it easier for you to make front-end elements. A front-end timeline</span></li>
<li><span id="646a">Some noteworthy front end libraries that have been used in the past few years:</span></li>
<li><span id="febf">2005: Script.aculo.us</span></li>
<li><span id="d5ae">2005: Dojo</span></li>
<li><span id="0657">2006: YUI</span></li>
<li><span id="c1f9">2010: Knockout</span></li>
<li><span id="e742">2011: AngularJS</span></li>
<li><span id="ed7b">2012: Elm</span></li>
<li><span id="06e4">2013: React (Considered the standard front-end library)</span></li>
<li><span id="4ff0">React manages the creation and updating of DOM nodes in your Web page.</span></li>
<li><span id="53cd">All it does is dynamically render stuff into your DOM.</span></li>
<li><span id="c393">What it doesn't do:</span></li>
<li><span id="3088">Ajax</span></li>
<li><span id="54ee">Services</span></li>
<li><span id="5e4a">Local Storage</span></li>
<li><span id="a437">Provide a CSS framework</span></li>
<li><span id="06e5">React is unopinionated</span></li>
<li><span id="721c">Just contains a few rules for developers to follow, and it just works.</span></li>
<li><span id="e2c0">JSX : Javascript Extension is a language invented to help write React Applications (looks like a mixture of JS and HTML)</span></li>
<li><span id="916b">Here is an overview of the difference between rendering out vanilla JS to create elements, and JSX:</span></li>
</ul>
<!-- -->
<pre><code>fetch(&quot;https://example.com/api/people&quot;)
  .then((response) =&gt; response.json())
  .then((people) =&gt; {
    const html = &quot;&lt;ul&gt;&quot;;
    for (let person of data.people) {
      html += `&lt;li&gt;${person.lastName}, ${person.firstName}&lt;/li&gt;`;
    }
    html += &quot;&lt;/ul&gt;&quot;;
    document.querySelector(&quot;#people-list&quot;).innerHTML = html;
  });

function PeopleList(props) {
return (
&lt;ul&gt;
$
{props.people.map((person) =&gt; (
&lt;li&gt;
{person.lastName}, {person.firstName}
&lt;/li&gt;
))}
&lt;/ul&gt;
);
}
const peopleListElement = document.querySelector(&quot;#people-list&quot;);
fetch(&quot;https://example.com/api/people&quot;)
.then((response) =&gt; response.json())
.then((people) =&gt; {
const props = { people };
ReactDOM.render(&lt;PeopleList props={props} /&gt;, peopleListElement);
});</code></pre>

<ul>
<li><span id="7ea4">This may seem like a lot of code but when you end up building many components, it becomes nice to put each of those functions/classes into their own files to organize your code. Using tools with React</span></li>
<li><span id="e220"><code>React DevTools</code> : New tool in your browser to see ow React is working in the browser</span></li>
<li><span id="9051"><code>create-react-app</code> : Extensible command-line tool to help generate standard React applications.</span></li>
<li><span id="af96"><code>Webpack</code> : In between tool for dealing with the extra build step involved.</span></li>
</ul>
<figure>
<img src="https://cdn-images-1.medium.com/max/800/0*LHVHf7SPZ1t0UVAj" class="graf-image" />
</figure>
<ul>
<li><span id="e0ad">HMR : (Hot Module Replacement) When you make changes to your source code the changes are delivered in real-time.</span></li>
<li><span id="923a">React Developers created something called <code>Flux Architecture</code> to moderate how their web page consumes and modifies data received from back-end API's.</span></li>
</ul>
<figure>
<img src="https://cdn-images-1.medium.com/max/800/0*wR-lbD4zf45-IHoQ" class="graf-image" />
</figure>
<ul>
<li><span id="b16e">Choosing React</span></li>
<li><span id="eefd">Basically, React is super important to learn and master.</span></li>
</ul>
<hr />
<h3 id="react-concepts-and-features">React Concepts and Features</h3>
<p>There are many benefits to using React over just Vanilla JavaScript.</p>
<ul>
<li><span id="8107"><code>Modularity</code></span></li>
<li><span id="15ac">To avoid the mess of many event listeners and template strings, React gives you the benefit of a lot of modularity.</span></li>
<li><span id="c1c5"><code>Easy to start</code></span></li>
<li><span id="90ce">No specials tools are needed to use Basic React.</span></li>
<li><span id="9ec9">You can start working directly with <code>createElement</code> method in React.</span></li>
<li><span id="dd3c"><code>Declarative Programming</code></span></li>
<li><span id="d3e6">React is declarative in nature, utilizing either it's built-in createElement method or the higher-level language known as JSX.</span></li>
<li><span id="ba8b"><code>Reusability</code></span></li>
<li><span id="a3c2">Create elements that can be re-used over and over. One-flow of data</span></li>
<li><span id="27d2">React apps are built as a combination of parent and child components.</span></li>
<li><span id="6da8">Parents can have one or more child components, all children have parents.</span></li>
<li><span id="26d8">Data is never passed from child to the parent.</span></li>
<li><span id="86be"><code>Virtual DOM</code> : React provides a Virtual DOM that acts as an agent between the real DOM and the developer to help debug, maintain, and provide general use.</span></li>
<li><span id="6747">Due to this usage, React handles web pages much more intelligently; making it one of the speediest Front End Libraries available.</span></li>
</ul>
<h3 id="es6-refresher">ES6 Refresher</h3>
<p>Exporting one item per file</p>
<ul>
<li><span id="5538">Use <code>export default</code> statement in ES6 to export an item. ES6</span></li>
</ul>
<!-- -->
<pre><code>export default class Wallet {
  // ...
}
// sayHello will not be exported
function sayHello() {
  console.log(&quot;Hello!&quot;);
}</code></pre>
<p>CommonJS (Equivalent)</p>
<pre><code>class Wallet {
  // ...
}
// sayHello will not be exported
function sayHello() {
  console.log(&quot;Hello!&quot;);
}
module.exports = Wallet;</code></pre>
<p>Exporting multiple items per file</p>
<ul>
<li><span id="9a6e">Use just thw <code>export</code> keyword (without default) to export multiple items per file. ES6 (Better to export them individually like this, rather than bunching them all into an object)</span></li>
</ul>
<!-- -->
<pre><code>export class Wallet {
  // ...
}
export function sayHello() {
  console.log(&quot;Hello!&quot;);
}
export const sayHi = () =&gt; {
  console.log(&quot;Hi!&quot;);
};
class Wallet {
  // ...
}
function sayHello() {
  console.log(&quot;Hello!&quot;);
}
const sayHi = () =&gt; {
  console.log(&quot;Hi!&quot;);
};
export { Wallet, sayHello, sayHi };</code></pre>
<p>CommonJS (Equivalent)</p>
<pre><code>class Wallet {
  // ...
}
function sayHello() {
  console.log(&quot;Hello!&quot;);
}
const sayHi = () =&gt; {
  console.log(&quot;Hi!&quot;);
};
module.exports = {
  Wallet,
  sayHello,
  sayHi,
};</code></pre>
<p>Importing with ES6 vs CommonJS</p>
<figure>
<img src="https://cdn-images-1.medium.com/max/800/0*7EZESKf0XPbncXAY" class="graf-image" />
</figure>
<ul>
<li><span id="18b1">Import statements in ES6 modules must always be at the top of the file, because all imports must occur before the rest of the file's code runs. ES6</span></li>
</ul>
<!-- -->
<pre><code>import { Wallet } from &quot;./wallet&quot;;
import * as fs from &quot;fs&quot;;
const wallet = new Wallet();</code></pre>
<p>CommonJS</p>
<pre><code>let { Wallet } = require(&quot;./wallet&quot;);
const wallet = new Wallet();
let fs = require(&quot;fs&quot;);</code></pre>
<p>Unnamed default imports</p>
<ul>
<li><span id="75e2">You can name unnamed items exported with export default any name when you import them.</span></li>
</ul>
<!-- -->
<pre><code>// exporting
export default class Wallet {
  // ...
}
// importing
import Money from &quot;wallet.js&quot;;
const wallet = new Money();</code></pre>
<ul>
<li><span id="5042">Just remember if you use <code>export</code> instead of <code>export default</code> then your import is already named and cannot be renamed.</span></li>
</ul>
<!-- -->
<pre><code>// exporting
export class Wallet {
  // ...
}
// importing
import { Wallet } from &quot;wallet.js&quot;;
const wallet = new Wallet();</code></pre>
<p>Aliasing imports</p>
<ul>
<li><span id="3535">Use as asterisk to import an entire module's contents.</span></li>
<li><span id="3f1c">Keep in mind you must use an <code>as</code> keyword to refer to it later.</span></li>
</ul>
<!-- -->
<pre><code>// export
export function sayHello() {
  console.log(&quot;Hello!&quot;);
}
export const sayHi = () =&gt; {
  console.log(&quot;Hi!&quot;);
};
//import
import * as Greetings from &quot;greetings.js&quot;;
Greetings.sayHello(); // Hello!
Greetings.sayHi(); // Hi!</code></pre>
<ul>
<li><span id="bfbc">You can also name identically named functions or items from different files.</span></li>
</ul>
<!-- -->
<pre><code>import { Wallet as W1 } from &quot;./wallet1&quot;;
import { Wallet as W2 } from &quot;./wallet2&quot;;
const w1 = new W1();
const w2 = new W2();</code></pre>
<p>Browser support for ES6 Modules</p>
<ul>
<li><span id="69b4">ES6 Modules can only be used when a JS file is specified as a module. <code>&lt;script type="module" src="./wallet.js"&gt;&lt;/script&gt;</code></span></li>
<li><span id="4f5c">You can get browser support for ES6 modules by adding module into your script tag.</span></li>
</ul>
<hr />
<h3 id="notes">Notes</h3>
<h3 id="jsx-in-depth">JSX In Depth</h3>
<ul>
<li><span id="2a0d">Remember that JSX is just syntactic sugar for the built in <code>React.createElement(component, props, ...children)</code></span></li>
<li><span id="1532">React Library must always be in scope from your JSX code.</span></li>
<li><span id="72b2">Use Dot Notation for JSX Type</span></li>
<li><span id="0cbc">User-Defined Components Must Be Capitalized <code>&lt;Foo /&gt;</code> vs <code>&lt;div&gt;</code></span></li>
<li><span id="553a">Cannot use a general expression as the React element type. (<code>Incorrect</code>)</span></li>
</ul>
<!-- -->
<pre><code>function Story(props) {
  // Wrong! JSX type can&#39;t be an expression.
    return &lt;components[props.storyType] story={props.story} /&gt;;
  };</code></pre>
<p>(<code>Corrected</code>)</p>
<pre><code>function Story(props) {
  // Correct! JSX type can be a capitalized variable.
  const SpecificStory = components[props.storyType];
  return &lt;SpecificStory story={props.story} /&gt;;
}</code></pre>
<p>Props in JSX</p>
<ul>
<li><span id="e549">Several ways to specify props in JSX.</span></li>
<li><span id="257d"><code>Javascript Expressions as Props</code></span></li>
</ul>
<!-- -->
<pre><code>&lt;MyComponent foo={1 + 2 + 3 + 4} /&gt;</code></pre>
<ul>
<li><span id="57f8"><code>String Literals</code></span></li>
</ul>
<!-- -->
<pre><code>&lt;MyComponent message=&quot;hello world&quot; /&gt; &lt;MyComponent message={&#39;hello world&#39;} /&gt; &lt;MyComponent message=&quot;&amp;lt;3&quot; /&gt; &lt;MyComponent message={&#39;❤&#39;} /&gt;</code></pre>
<ul>
<li><span id="48df"><code>Props Default to "True"</code></span></li>
</ul>
<!-- -->
<pre><code>&lt;MyTextBox autocomplete /&gt; &lt;MyTextBox autocomplete={true} /&gt;</code></pre>
<ul>
<li><span id="2072"><code>Spread Attributes</code></span></li>
</ul>
<!-- -->
<pre><code>function App1() { return &lt;Greeting firstName=&quot;Ben&quot; lastName=&quot;Hector&quot; /&gt;; } function App2() { const props = { firstName: &quot;Ben&quot;, lastName: &quot;Hector&quot; }; return &lt;Greeting {…props} /&gt;; }</code></pre>
<p>Children in JSX</p>
<ul>
<li><span id="2238"><code>props.children</code> : The content between opening and closing tag. JavaScript Expressions as Children</span></li>
</ul>
<!-- -->
<pre><code>function Item(props) {
  return &lt;li&gt;{props.message}&lt;/li&gt;;
}
function TodoList() {
  const todos = [&quot;finish doc&quot;, &quot;submit pr&quot;, &quot;nag dan to review&quot;];
  return (
    &lt;ul&gt;
      {todos.map((message) =&gt; (
        &lt;Item key={message} message={message} /&gt;
      ))}
    &lt;/ul&gt;
  );
}</code></pre>
<p>Functions as Children</p>
<ul>
<li><span id="bf0a"><code>props.children</code> works like any other prop, meaning it can pass any sort of data.</span></li>
</ul>
<!-- -->
<pre><code>// Calls the children callback numTimes to produce a repeated component
function Repeat(props) {
  let items = [];
  for (let i = 0; i &lt; props.numTimes; i++) {
    items.push(props.children(i));
  }
  return &lt;div&gt;{items}&lt;/div&gt;;
}
function ListOfTenThings() {
  return (
    &lt;Repeat numTimes={10}&gt;
      {(index) =&gt; &lt;div key={index}&gt;This is item {index} in the list&lt;/div&gt;}
    &lt;/Repeat&gt;
  );
}</code></pre>
<p>Booleans, Null, and Undefined Are Ignored</p>
<ul>
<li><span id="7017"><code>false</code>, <code>null</code>, <code>undefined</code>, and <code>true</code> are all valid children.</span></li>
<li><span id="5af2">They will not render.</span></li>
<li><span id="10dc">You can use these to conditionally render items.</span></li>
</ul>
<!-- -->
<pre><code>&lt;div&gt;
  {showHeader &amp;&amp; &lt;Header /&gt;}
  &lt;Content /&gt;
&lt;/div&gt;</code></pre>
<ul>
<li><span id="fa28">In this example, the component will only render if <code>showHeader</code> evals to True.</span></li>
</ul>
<!-- -->
<pre><code>// Before work-around
&lt;div&gt;
  {props.messages.length &amp;&amp;
    &lt;MessageList messages={props.messages} /&gt;
  }
&lt;/div&gt;
// After work-around
&lt;div&gt;
  {props.messages.length &gt; 0 &amp;&amp;
    &lt;MessageList messages={props.messages} /&gt;
  }
&lt;/div&gt;</code></pre>
<ul>
<li><span id="3701">Note that certain falsy values such as zero will still be rendered by React, you can work around this by ensuring situations like the above eval. into a boolean.</span></li>
<li><span id="9586">In the times you want booleans to be rendered out, simply convert it into a string first.</span></li>
</ul>
<!-- -->
<pre><code>&lt;div&gt;My JavaScript variable is {String(myVariable)}.&lt;/div&gt;</code></pre>
<h3 id="reconciliation">Reconciliation</h3>
<p>The Diffing Algorithm</p>
<ul>
<li><span id="76c4"><code>Diffing</code> : When the state of a component changes React creates a new virtual DOM tree.</span></li>
<li><span id="9a73">Elements of Different Types</span></li>
<li><span id="d680">Every time the root elements have different types, React tears down the old tree and builds the new tree from scratch.</span></li>
<li><span id="84a6">DOM Elements Of the Same Type</span></li>
<li><span id="4b94">When comparing two DOM elements of the same type, React keeps the same underlying DOM node and only updates the changes attributes.</span></li>
</ul>
<!-- -->
<pre><code>&lt;div className="before" title="stuff" /&gt; &lt;div className="after" title="stuff" /&gt;

&lt;div style={{ color: "red", fontWeight: "bold" }} /&gt; &lt;div style={{color: 'green', fontWeight: 'bold'}} /&gt;</code></pre>

<ul>
<li><span id="0a0c">Component Elements Of The Same Type</span></li>
<li><span id="cf3a">When components update, instances will remain the same, so that state maintains across renders.</span></li>
<li><span id="b8ab">React will only update the props, to match the new element.</span></li>
<li><span id="82f3">Recursing On Children</span></li>
<li><span id="4a59">React will iterate both lists of children and generate a mutation whenever there's a difference.</span></li>
<li><span id="74a8">This is why we use <code>keys</code>.</span></li>
<li><span id="381c">Makes it easier for React to match children in the original tree with children in the subsequent tree.</span></li>
<li><span id="f1f5">Tradeoffs</span></li>
<li><span id="e98a">Important to remember that reconciliation algorithm is an <em>implementation detail</em>.</span></li>
<li><span id="7f57">Re-rendering only to apply the differences following the rules stated in the previous sections.</span></li>
</ul>
<h3 id="typechecking-with-proptypes">Typechecking With PropTypes</h3>
<ul>
<li><span id="0bc0">As your application grows, you can use React's <code>typechecking</code> to catch bugs.</span></li>
<li><span id="638c"><code>propTypes</code> is a special property to run typechecking.</span></li>
<li><span id="e725">exports range of built in validators to ensure your received data is valid.</span></li>
<li><span id="f590">propTypes is only checked in development mode.</span></li>
</ul>
<!-- -->
<pre><code>import PropTypes from &quot;prop-types&quot;;
class Greeting extends React.Component {
  render() {
    return &lt;h1&gt;Hello, {this.props.name}&lt;/h1&gt;;
  }
}
Greeting.propTypes = {
  name: PropTypes.string,
};</code></pre>
<p>Requiring Single Child</p>
<ul>
<li><span id="e2db">Use <code>PropTypes.element</code> to specify only a single child can be passed to a component as children.</span></li>
</ul>
<!-- -->
<pre><code>import PropTypes from &quot;prop-types&quot;;
class MyComponent extends React.Component {
  render() {
    // This must be exactly one element or it will warn.
    const children = this.props.children;
    return &lt;div&gt;{children}&lt;/div&gt;;
  }
}
MyComponent.propTypes = {
  children: PropTypes.element.isRequired,
};</code></pre>
<p>Default Prop Values</p>
<ul>
<li><span id="7d3d">Use <code>defaultProps</code> to assign default values for props.</span></li>
</ul>
<!-- -->
<pre><code>class Greeting extends React.Component {
  render() {
    return &lt;h1&gt;Hello, {this.props.name}&lt;/h1&gt;;
  }
}
// Specifies the default values for props:
Greeting.defaultProps = {
  name: &quot;Stranger&quot;,
};
// Renders &quot;Hello, Stranger&quot;:
ReactDOM.render(&lt;Greeting /&gt;, document.getElementById(&quot;example&quot;));

class Greeting extends React.Component {
static defaultProps = {
name: &#39;stranger&#39;
}
render() {
return (
&lt;div&gt;Hello, {this.props.name}&lt;/div&gt;
)
}</code></pre>

<hr />
<h3 id="notes-1">Notes</h3>
<h3 id="react-router-introduction">React Router Introduction</h3>
<ul>
<li><span id="48a7"><code>React Router</code> is the answer for rendering different components for different pages.</span></li>
<li><span id="78b3">A front-end library that allows you to control which components to display using the browser location.</span></li>
<li><span id="aa2a"><code>Client-side Routing</code> Getting started with routing</span></li>
<li><span id="0940">Install React Router with:</span></li>
<li><span id="742a">npm install — save react-router-dom@⁵.1.2</span></li>
<li><span id="f07f">Import <code>Browser Router</code> from package.</span></li>
<li><span id="9e4e">import { BrowserRouter } from "react-router-dom";</span></li>
<li><span id="cb01"><code>BrowserRouter</code> is the primary component of the router that wraps your route hierarchy.</span></li>
<li><span id="adfa">Wrap it around components.</span></li>
<li><span id="0276">Creates a <code>React Context</code> that passes routing information down to all its descendant components.</span></li>
<li><span id="dd45">You can also use <code>HashRouter</code>, where it would generate a hash before the endpoint. Creating frontend routes</span></li>
<li><span id="37c2">React Router helps your app render specific components based on the URL.</span></li>
<li><span id="54c4">The most common component is <code>&lt;Route&gt;</code></span></li>
<li><span id="500a">Wrapped around another component, causing the comp. to only render if the a certain URL is matched.</span></li>
<li><span id="5a94"><code>Props</code> : path, component, exact, and [render]</span></li>
<li><span id="9f06">Browser Router can only have a single child component.</span></li>
<li><span id="6305">The Browser Router wraps all routes within a parent div element.</span></li>
</ul>
<!-- -->
<pre><code>const Root = () =&gt; {
  const users = {
    1: { name: &quot;Andrew&quot; },
    2: { name: &quot;Raymond&quot; },
  };
  return (
    &lt;BrowserRouter&gt;
      &lt;div&gt;
        &lt;h1&gt;Hi, I&#39;m Root!&lt;/h1&gt;
        &lt;Route exact path=&quot;/&quot; component={App} /&gt;
        &lt;Route path=&quot;/hello&quot; render={() =&gt; &lt;h1&gt;Hello!&lt;/h1&gt;} /&gt;
        &lt;Route path=&quot;/users&quot; render={() =&gt; &lt;Users users={users} /&gt;} /&gt;
      &lt;/div&gt;
    &lt;/BrowserRouter&gt;
  );
};</code></pre>
<ul>
<li><span id="c057">component</span></li>
<li><span id="2dcc">Indicates component to render.</span></li>
<li><span id="740c">path</span></li>
<li><span id="3030">Indicates path to render a specific component.</span></li>
<li><span id="0741">exact</span></li>
<li><span id="52cb">Tells route to not pattern match and only render a certain route exclusively to it's associated component.</span></li>
<li><span id="cb93">render</span></li>
<li><span id="c702">Optional prop that takes in a function to be called.</span></li>
<li><span id="594b">Causes extra work for React.</span></li>
<li><span id="5320">Preferred for inline rendering of simple functional components.</span></li>
<li><span id="0d3e">Difference between <code>component</code> and <code>render</code> is that component returns new JSX that be re-mounted, but render returns the JSX that will be mounted only once.</span></li>
<li><span id="4a08">// This inline rendering will work, but is unnecessarily slow. &lt;Route path="/hello" component={() =&gt; &lt;h1&gt;Hello!&lt;/h1&gt;} /&gt; // This is the preferred way for inline rendering. &lt;Route path="/hello" render={() =&gt; &lt;h1&gt;Hello!&lt;/h1&gt;} /&gt;</span></li>
<li><span id="a2d3">Also useful if you need to pass in specific props to a component.</span></li>
<li><span id="e09f">// `users` to be passed as a prop: const users = { 1: { name: "Andrew" }, 2: { name: "Raymond" }, }; &lt;Route path="/users" render={() =&gt; &lt;Users users={users} /&gt;} /&gt;;</span></li>
</ul>
<p>Route path params</p>
<ul>
<li><span id="3d09">Your component's props can hold information about URL's parameters.</span></li>
<li><span id="52f3">Will match segments starting at <code>:</code> to the next <code>/</code>, <code>?</code>, <code>#</code>.</span></li>
</ul>
<!-- -->
<pre><code>&lt;Route
  path=&quot;/users/:userId&quot;
  render={(props) =&gt; &lt;Profile users={users} {...props} /&gt;}
/&gt;</code></pre>
<ul>
<li><span id="f2b4"><code>{...props}</code> spreads out the router's props.</span></li>
<li><span id="1edb"><code>props.match.params</code> is used to access the match prop's parameters.</span></li>
<li><span id="b6a9">Useful keys on the <code>match</code> object:</span></li>
<li><span id="290f"><code>isExact</code> : boolean that tells you whether or not the URL exactly matches the path.</span></li>
<li><span id="27ea"><code>url</code> : the currentURL</span></li>
<li><span id="b979"><code>path</code> : Route path it matched against (w/o wildcards)</span></li>
<li><span id="6c59"><code>params</code> : Matches for the individual wildcard segments.</span></li>
</ul>
<hr />
<h3 id="navigation">Navigation</h3>
<p>React Router Navigation</p>
<ul>
<li><span id="a548"><code>Link</code>, <code>NavLink</code>, <code>Redirect</code>, <code>history</code> props of React Router are used to help your user navigate routes. Adding links for navigation</span></li>
<li><span id="643f">Issues on-click navigation event to a route defined in app.</span></li>
<li><span id="949d">Usage renders an anchor tag with a correctly set <code>href</code> attribute.</span></li>
</ul>
<!-- -->
<pre><code>import { BrowserRouter, Route, Link } from &quot;react-router-dom&quot;;</code></pre>
<ul>
<li><span id="b5a5"><code>Link</code> takes two properties: <code>to</code> and <code>onClick</code>.</span></li>
<li><span id="995b"><code>to</code> : route location that points to an absolute path.</span></li>
<li><span id="978c"><code>onClick</code> : clickHandler.</span></li>
<li><span id="b8c0"><code>NavLink</code> works just like <code>Link</code> but has a bit of extra functionality.</span></li>
<li><span id="6334">Adds extra styling, when the path it links to matches the current path.</span></li>
<li><span id="07b8">As it's name suggests, it is used to Nav Bars.</span></li>
<li><span id="8a33">Takes three props:</span></li>
<li><span id="e501"><code>activeClassName</code> : allows you to set a CSS class name for styling. (default set to 'active')</span></li>
<li><span id="81da"><code>activeStyle</code> : style object that is applied inline when it's <code>to</code> prop. matches the current URL.</span></li>
<li><span id="8c71"><code>exact</code> prop is a boolean that defaults to false; you can set it to true to apply requirement of an exact URL match.</span></li>
<li><span id="755b">exact can also be used as a flag instead of a reg. property value.</span></li>
<li><span id="dd12">benefit of adding this is so that you don't trigger other matches. Switching between routes</span></li>
<li><span id="4fb6"><code>&lt;Switch&gt;</code> : Component allows you to only render one route even if several match the current URL.</span></li>
<li><span id="7be7">You may nest as many routes as you wish but only the first match of the current URL will be rendered.</span></li>
<li><span id="3f8a">Very useful if we want a default component to render if none of our routes match.</span></li>
</ul>
<!-- -->
<pre><code>&lt;Switch&gt;
  &lt;Route path=&quot;some/url&quot; component={SomeComponent} /&gt;
  &lt;Route path=&quot;some/other/url&quot; component={OtherComponent} /&gt;
  &lt;Route component={DefaultComponent} /&gt;
&lt;/Switch&gt;</code></pre>
<ul>
<li><span id="b901"><code>DefaultComponent</code> will only render if none of the other URLs match up.</span></li>
<li><span id="21a3"><code>&lt;Redirect&gt;</code> : Helps redirect users.</span></li>
<li><span id="ee88">Only takes a single prop: <code>to</code>.</span></li>
</ul>
<!-- -->
<pre><code>&lt;Route
  exact
  path=&quot;/&quot;
  render={() =&gt; (this.props.currentUser ? &lt;Home /&gt; : &lt;Redirect to=&quot;/login&quot; /&gt;)}
/&gt;</code></pre>
<p>History</p>
<ul>
<li><span id="6456"><code>History</code> allows you to update the URL programmatically.</span></li>
<li><span id="bac6">Contains two useful methods:</span></li>
<li><span id="9b00"><code>push</code> : Adds a new URL to the end of the history stack.</span></li>
<li><span id="d539"><code>replace</code> : Replaces the current URL on the history stack, so the back button won't take you to it.</span></li>
</ul>
<!-- -->
<pre><code>// Pushing a new URL (and adding to the end of history stack):
const handleClick = () =&gt; this.props.history.push(&quot;/some/url&quot;);
// Replacing the current URL (won&#39;t be tracked in history stack):
const redirect = () =&gt; this.props.history.replace(&quot;/some/other/url&quot;);</code></pre>
<hr />
<h3 id="nested-routes">Nested Routes</h3>
<p>Why nested routes?</p>
<ul>
<li><span id="6403">Create routes that tunnel into main components vs getting rendered on the main page as it's own thing. What are nested routes?</span></li>
</ul>
<!-- -->
<pre><code>const Profile = (props) =&gt; {
  // Custom call to database to fetch a user by a user ID.
  const user = fetchUser(props.match.params.userId);
  const { name, id } = user;
  return (
    &lt;div&gt;
      &lt;h1&gt;Welcome to the profile of {name}!&lt;/h1&gt;
      &lt;Link to={`/users/${id}/posts`}&gt;{name}&#39;s Posts&lt;/Link&gt;
      &lt;Link to={`/users/${id}/photos`}&gt;{name}&#39;s Photos&lt;/Link&gt;
      &lt;Route path=&quot;/users/:userId/posts&quot; component={UserPosts} /&gt;
      &lt;Route path=&quot;/users/:userId/photos&quot; component={UserPhotos} /&gt;
    &lt;/div&gt;
  );
};</code></pre>
<p>Alt. version using <code>props.match</code></p>
<pre><code>// Destructure `match` prop
const Profile = ({ match: { url, path, params }) =&gt; {
  // Custom call to database to fetch a user by a user ID.
  const user = fetchUser(params.userId);
  const { name, id } = user;
  return (
    &lt;div&gt;
      &lt;h1&gt;Welcome to the profile of {name}!&lt;/h1&gt;
      &lt;Link to={`${url}/posts`}&gt;{name}&#39;s Posts&lt;/Link&gt;
      &lt;Link to={`${url}/photos`}&gt;{name}&#39;s Photos&lt;/Link&gt;
      &lt;Route path={`${path}/posts`} component={UserPosts} /&gt;
      &lt;Route path={`${path}/photos`} component={UserPhotos} /&gt;
    &lt;/div&gt;}
  );
};</code></pre>
<ul>
<li><span id="03fb">As you can see above, our end URL isn't even defined until we apply those flexible values in.</span></li>
</ul>
<hr />
<h3 id="react-builds">React Builds</h3>
<ul>
<li><span id="0fae"><code>Build</code> : Process of converting code into something that can actually execute or run on the target platform.</span></li>
<li><span id="6fdb">In regards to React, the minimum a build should do is convert JSX to something that browsers can understand. Reviewing common terminology</span></li>
<li><span id="779d"><code>Linting</code> : Process of using a tool to analyze your code to catch common errors, bugs, inconsistencies etc…</span></li>
<li><span id="f1e5"><code>Transpilation</code> : Process of converting source code, like JS, from one version to another.</span></li>
<li><span id="9f9f"><code>Minification</code> : Process of removing all unnecessary characters in your code.</span></li>
<li><span id="57df"><code>Bundling</code> : Process of combining multiple code files into a single file.</span></li>
<li><span id="d052"><code>Tree Shaking</code> : Process of removing unused or dead code from your application before it's bundled. Configuration or code?</span></li>
<li><span id="ce13"><code>Configuration</code> allows developers to create build tasks by declaring either JSON, XML, or YAML without explicitly writing every step in the process.</span></li>
<li><span id="16a6"><code>Coding</code> or <code>Scripting</code> simply requires code. Babel and webpack (yes, that's intentionally a lowercase 'w')</span></li>
<li><span id="4363"><code>Babel</code> : Code Transpiler that allows you to use all of the latest features and syntax wihtout worrying about what browsers support what.</span></li>
<li><span id="804b"><code>webpack</code> : Allows developers to use JS modules w/o requiring users to use a browser that natively supports ES modules.</span></li>
<li><span id="77f2">Create React App uses webpack and Babel under the hood to build applications. The Create React App build process</span></li>
<li><span id="222f">What happens when you run <code>npm start</code>:</span></li>
</ul>
<ol type="1">
<li><span id="d245">.env variables are loaded.</span></li>
<li><span id="6209">list of browsers to support are checked.</span></li>
<li><span id="1c34">config'd HTTP port checked for availability.</span></li>
<li><span id="950b">application compiler is configured and created.</span></li>
<li><span id="8e30"><code>webpack-dev-starter</code> is started</span></li>
<li><span id="48cc"><code>webpack-dev-starter</code> compiles app.</span></li>
<li><span id="68ad"><code>index.html</code> is loaded into browser</span></li>
<li><span id="e670">file watcher is started to watch for changes. Ejecting</span></li>
</ol>
<ul>
<li><span id="428b">There is a script in Create React App called <code>eject</code> that allows you to 'eject' your application and expose all the hidden stuff. Preparing to deploy a React application for production</span></li>
<li><span id="eb79">Defining Env Variables</span></li>
</ul>
<!-- -->
<pre><code>REACT_APP_FOO: some value
REACT_APP_BAR: another value

console.log(process.env.REACT_APP_FOO);

Can be referenced in your index.html like so: &lt;title&gt;%REACT_APP_BAR%&lt;/title&gt;</code></pre>

<p>Configuring the supported browsers</p>
<pre><code>{
  &quot;browserslist&quot;: {
    &quot;production&quot;: [
      &quot;&gt;0.2%&quot;,
      &quot;not dead&quot;,
      &quot;not op_mini all&quot;
    ],
    &quot;development&quot;: [
      &quot;last 1 chrome version&quot;,
      &quot;last 1 firefox version&quot;,
      &quot;last 1 safari version&quot;
    ]
  }
}</code></pre>
<ul>
<li><span id="8a03">If you specify older browsers it will affect how your code get's transpiled. Creating a production build</span></li>
<li><span id="fee3">Run <code>npm run build</code> to create a production build.</span></li>
<li><span id="bdaf">Bundles React in production mode and optimizes the build for the best performance.</span></li>
</ul>
<hr />
<h3 id="notes-2">Notes</h3>
<h3 id="introduction-to-react">Introduction to React</h3>
<ul>
<li><span id="7224">Simply a nice library that turns data into DOM.</span></li>
<li><span id="a9de"><code>Tree Diffing</code> : Fast comparison and patching of data by comparing the current virtual DOM and new virtual DOM - updating only the pieces that change.</span></li>
<li><span id="1bbc"><code>It's just a tree with some fancy diffing</code></span></li>
</ul>
<hr />
<h3 id="create-element">Create Element</h3>
<p>From JavaScript To DOM</p>
<ul>
<li><span id="cae8">The <code>React.createElement</code> function has the following form:</span></li>
</ul>
<!-- -->
<pre><code>React.createElement(type, [props], [...children]);</code></pre>
<ul>
<li><span id="1688"><code>Type</code> : Type of element to create, i.e. a string for an HTML element or a reference to a function or class that is a React component.</span></li>
<li><span id="3249"><code>Props</code> : Object that contains data to render the element.</span></li>
<li><span id="56ab"><code>Children</code> : Children of the elemet, as many as you want. Creating elements</span></li>
<li><span id="ee64">Our rendering goal:</span></li>
</ul>
<!-- -->
<pre><code>&lt;ul&gt;
  &lt;li class=&quot;selected&quot;&gt;
    &lt;a href=&quot;/pets&quot;&gt;Pets&lt;/a&gt;
  &lt;/li&gt;
  &lt;li&gt;
    &lt;a href=&quot;/owners&quot;&gt;Owners&lt;/a&gt;
  &lt;/li&gt;
&lt;/ul&gt;</code></pre>
<ul>
<li><span id="eb8b">There are five tags to create:</span></li>
<li><span id="ea28">One <code>ul</code></span></li>
<li><span id="a4ba">Two <code>li</code></span></li>
<li><span id="de01">Two <code>a</code></span></li>
<li><span id="90b5">There are certain attributes we want to appear in the DOM for these tags as well:</span></li>
<li><span id="dab5">Each <code>li</code> has a <code>class</code> (or <code>className</code> in React)</span></li>
<li><span id="e88e">Both <code>a</code> ele's have <code>href</code> attributes</span></li>
<li><span id="fd8c">Also keep in mind the parent child relationships happening between the tags.</span></li>
<li><span id="9893"><code>ul</code> is the parent of both <code>li</code></span></li>
<li><span id="eafa">Each <code>li</code> has an <code>a</code> element as a child</span></li>
<li><span id="84cc">Each <code>a</code> has a <code>text content</code> child</span></li>
</ul>
<figure>
<img src="https://cdn-images-1.medium.com/max/800/0*8ls0PmtREELbf5Wm" class="graf-image" />
</figure>
<p>React.createElement( "ul", null, React.createElement( "li", { className: "selected" }, React.createElement("a", { href: "/pets" }, "Pets") ), React.createElement( "li", null, React.createElement("a", { href: "/owners" }, "Owners") ) );</p>
<p>Converting to virtual DOM</p>
<ul>
<li><span id="e7d4">After you set up your <code>React.createElement</code>, you use <code>React.render</code> to take the value returned from cE and a DOM node to insert into the conversion of the real DOM.</span></li>
</ul>
<!-- -->
<pre><code>// Put the element tree in a variable
const navList = React.createElement(
  &quot;ul&quot;,
  null,
  React.createElement(
    &quot;li&quot;,
    { className: &quot;selected&quot; },
    React.createElement(&quot;a&quot;, { href: &quot;/pets&quot; }, &quot;Pets&quot;)
  ),
  React.createElement(
    &quot;li&quot;,
    null,
    React.createElement(&quot;a&quot;, { href: &quot;/owners&quot; }, &quot;Owners&quot;)
  )
);
// Get a DOM node for React to render to
const mainElement = document.querySelector(&quot;main&quot;);
// Give React the element tree and the target
ReactDOM.render(navList, mainElement);</code></pre>
<ul>
<li><span id="2cbc">JS Code =&gt; Virtual DOM =&gt; Real Dom Updates</span></li>
<li><span id="25d5">If you call React.render a second or multiple times it just checks the existing Virtual DOM and it knows which smaller areas to change. Thinking in Components</span></li>
<li><span id="fe61">Components are pieces of reusable front-end pieces.</span></li>
<li><span id="bffa">Components should be Single Responsibility Principle compliant.</span></li>
</ul>
<hr />
<h3 id="create-element-1">Create Element</h3>
<p><code>React.createElement Demo</code></p>
<ul>
<li><span id="a288">Can import non-local dependencies with <code>import 'package-link'</code></span></li>
</ul>
<!-- -->
<pre><code>const App = () =&gt; React.createElement(&quot;h1&quot;, null, &quot;Hello, Programmers!&quot;);
const target = document.querySelector(&quot;main&quot;);
const app = React.createElement(App, null);
// Give React the element tree and the target
ReactDOM.render(app, target);</code></pre>
<ul>
<li><span id="0693">Remember when importing modules from other files you have to denote the file type in the import statement. HTML Original</span></li>
</ul>
<!-- -->
<pre><code>&lt;section class=&quot;clue&quot;&gt;
  &lt;h1 class=&quot;clue__title&quot;&gt;Clue$ 268530&lt;/h1&gt;
  &lt;div class=&quot;clue__question&quot;&gt;
      2009: I dreamed a Dream
  &lt;/div&gt;
  &lt;div class=&quot;clue__category&quot;&gt;
      &lt;&lt;unparsed&gt;&gt;
  &lt;/div&gt;
  &lt;div class=&quot;clue__amount&quot;&gt;
      $800
  &lt;/div&gt;
&lt;/section&gt;</code></pre>
<p>React Version</p>
<pre><code>const Clue = () =&gt;
  React.createElement(
    &quot;section&quot;,
    { className: &quot;clue&quot; },
    React.createElement(&quot;h1&quot;, { className: &quot;clue__title&quot; }, &quot;Title&quot;),
    React.createElement(&quot;div&quot;, { className: &quot;clue__question&quot; }, &quot;?&quot;),
    React.createElement(&quot;div&quot;, { className: &quot;clue__category&quot; }, &quot;Category&quot;),
    React.createElement(&quot;div&quot;, { className: &quot;clue__amount&quot; }, &quot;$800&quot;)
  );</code></pre>
<ul>
<li><span id="f587">Because <code>class</code> is a reserved keyword in JS, in React we can use <code>className</code> to assign a class to an element.</span></li>
<li><span id="4d51">Remember the data that goes into createElement: element type, data to pass into the element, and then children.</span></li>
<li><span id="8199"><code>props</code> : Properties;</span></li>
<li><span id="6b53">To handle certain values that are initially undefined, we can use <code>defaultProps</code>.</span></li>
</ul>
<!-- -->
<pre><code>Clue.defaultProps = {
  category: {},
};</code></pre>
<ul>
<li><span id="4abe">You can change in the devTools Network tab the internet speed to check for values that may be undefined to hangle with defaultProps.</span></li>
<li><span id="79e3">If we fetch multiple pieces of data, we can render many things by using <code>map</code>.</span></li>
<li><span id="06f2">You need to assign a unique key to each of the clues.</span></li>
<li><span id="c12e">We need to keep track of them individually so that React can easily refer to a specific one if there is an issue. <code>clue =&gt; { key:clue.id, ...clue }</code></span></li>
</ul>
<!-- -->
<pre><code>const App = (props) =&gt;
  React.createElement(
    &quot;h1&quot;,
    null,
    props.clues.map((clue) =&gt;
      React.createElement(Clue, { key: clue.id, ...clue })
    )
  );
export default App;</code></pre>
<ul>
<li><span id="1dd5">Note: JSX is preferred over React.createElement;</span></li>
</ul>
<hr />
<h3 id="notes-from-hello-programmer-exercise">Notes from Hello Programmer Exercise</h3>
<ul>
<li><span id="1fb8">When you import modules from websites they must have CORs activated.</span></li>
<li><span id="1ef6">These import statements, import <code>global variables</code>.</span></li>
<li><span id="6613">When we want to move our code into production we need to change the imports into the production minified versions.</span></li>
</ul>
<!-- -->
<pre><code>import &quot;https://unpkg.com/react@16/umd/react.production.min.js&quot;;
import &quot;https://unpkg.com/react-dom@16.13.1/umd/react-dom.production.min.js&quot;;</code></pre>
<ul>
<li><span id="0046">While we will never actually be creating full apps with just React.createElement =&gt; it is the enginer that is running under the hood!</span></li>
</ul>
<!-- -->
<pre><code>import &quot;https://unpkg.com/react@16/umd/react.development.js&quot;;
import &quot;https://unpkg.com/react-dom@16/umd/react-dom.development.js&quot;;
const Links = () =&gt;
  React.createElement(
    &quot;ul&quot;,
    { id: &quot;nav-links&quot; },
    React.createElement(
      &quot;li&quot;,
      { className: &quot;is-selected&quot; },
      React.createElement(&quot;a&quot;, { href: &quot;http://appacademy.io&quot; }, &quot;App Academy&quot;)
    ),
    React.createElement(
      &quot;li&quot;,
      null,
      React.createElement(&quot;a&quot;, { href: &quot;https://aaonline.io&quot; }, &quot;a/A Open&quot;)
    )
  );
// Set up React Element: Type, Imported Data, Child (Child is Text in this Scenario)
// HelloWorld is a function based component
const HelloWorld = () =&gt; React.createElement(&quot;h1&quot;, null, &quot;Hello, Programmers&quot;);
const AllTogether = () =&gt;
  React.createElement(
    &quot;div&quot;,
    null,
    React.createElement(HelloWorld, null),
    React.createElement(Links, null)
  );
// Target the Element to append new Ele
const target = document.querySelector(&quot;main&quot;);
// Assign your &#39;App&#39; to your created Elements
// We are creating an element from the HelloWorld function.
const app = React.createElement(AllTogether, null);
// Render from the Virtual Dom to the Actual Dom
ReactDOM.render(app, target);</code></pre>
<hr />
<h3 id="introduction-to-jsx">Introduction to JSX</h3>
<ul>
<li><span id="a5ee"><code>JSX</code> : Javascript Extension, a new language created by React developers to have an easier way of interacting with the React API. How to use JSX</span></li>
<li><span id="24bf">We will use <code>babel</code> to convert version of modern JS into an older version of JS. React Create Element</span></li>
</ul>
<!-- -->
<pre><code>const ExampleComponent = (props) =&gt;
  React.createElement(
    React.Fragment,
    null,
    React.createElement(&quot;h1&quot;, null, &quot;Hello!&quot;),
    React.createElement(&quot;img&quot;, { src: &quot;https://via.placeholder.com/150&quot; }),
    React.createElement(&quot;a&quot;, { href: props.searchUrl }, props.searchText)
  );</code></pre>
<p>JSX Version</p>
<pre><code>const ExampleComponent = (props) =&gt; (
  &lt;React.Fragment&gt;
    &lt;h1&gt;Hello!&lt;/h1&gt;
    &lt;img src=&quot;https://via.placeholder.com/150&quot; /&gt;
    &lt;a href={props.searchUrl}&gt;{props.searchText}&lt;/a&gt;
  &lt;/React.Fragment&gt;
);</code></pre>
<ul>
<li><span id="b00d">Keep in mind that self closing tags in React must have a <code>forward slash</code> to close it.</span></li>
</ul>
<figure>
<img src="https://cdn-images-1.medium.com/max/800/0*NNxuFMF-sOL8Wvdl" class="graf-image" />
</figure>
<ul>
<li><span id="346d">Properties and Data</span></li>
</ul>
<!-- -->
<pre><code>&lt;img src=&quot;https://via.placeholder.com/150&quot; /&gt;;
// becomes..
React.createElement(&quot;img&quot;, { src: &quot;https://via.placeholder.com/150&quot; });
// if we want to pass in data vs just a string literal
&lt;a href={props.searchUrl}&gt;{props.searchText}&lt;/a&gt;;
// so it becomes..
React.createElement(&quot;a&quot;, { href: props.searchUrl }, props.searchText);
// if you want the text search uppercase..
&lt;a href={props.searchUrl}&gt;{props.searchText.toUpperCase()}&lt;/a&gt;;</code></pre>
<ul>
<li><span id="467c">Comments in JSX have the following syntax:</span></li>
</ul>
<!-- -->
<pre><code>&lt;div&gt;
  &lt;h2&gt;This is JSX&lt;/h2&gt;
  {/* This is a comment in JSX */}
&lt;/div&gt;</code></pre>
<ul>
<li><span id="8cb8"><code>Property Names</code>:</span></li>
<li><span id="837b"><code>checked</code> : Attribute of input components such as checkbox or radio, use it to set whether the component is checked or not.</span></li>
<li><span id="aec0"><code>className</code> : Used to specify a CSS class.</span></li>
<li><span id="2f92"><code>dangerouslySetInnerHTML</code> : React's equivalent of innerHTML because it is risky to cross-site scripting attacks.</span></li>
<li><span id="3eab"><code>htmlFor</code> : Because <code>for</code> is protected keyword, React elements use this instead.</span></li>
<li><span id="9194"><code>onChange</code> : Event fired whenever a form field is changed.</span></li>
<li><span id="014a"><code>style</code> : Accepts a JS object with camelCase properties rather than a CSS string.</span></li>
<li><span id="76d8"><code>value</code> : Supported by Input, Select, and TextArea components; use it to set the value of the component.</span></li>
<li><span id="22c2">Note: React uses camel-case!!! The JSX semicolon gotcha</span></li>
</ul>
<!-- -->
<pre><code>function App() {
  return (
    &lt;div&gt;
      &lt;h1&gt;Hello!&lt;/h1&gt;
      &lt;div&gt;Welcome to JSX.&lt;/div&gt;
    &lt;/div&gt;
  );
}</code></pre>
<p>create Element equivalent</p>
<pre><code>is equivalent to
function App() {
  return (
    React.createElement(
      &#39;div&#39;,
      null,
      React.createElement(&#39;h1&#39;, null, &#39;Hello!&#39;),
      React.createElement(&#39;div&#39;, null, &#39;Welcome to JSX.&#39;),
    )
  );
}</code></pre>
<ul>
<li><span id="dbc1">We wrap what want to return in parenthesis so JS doesn't auto add semi-colons after every line and run the code incorrectly.</span></li>
<li><span id="62c0">Just remember if you decided to use the return keyword in a function to 'return some JSX', then make sure you wrap the JSX in parenthesis.</span></li>
</ul>
<hr />
<p><code>npx create-react-app my-app</code></p>
<ul>
<li><span id="8ad9">Single line used to initiate a React application.</span></li>
<li><span id="3cb1">React has a great toolchain where you can see changes live as you're editing your application.</span></li>
<li><span id="c1d0">React errors will be rendered directly onto the browser window.</span></li>
<li><span id="1365">A downside is that it installs a lot of bloat files.</span></li>
<li><span id="aaed">Examples of React create Element and JSX equivalent</span></li>
</ul>
<!-- -->
<pre><code>React.createElement(
  &quot;a&quot;,
  {
    className: &quot;active&quot;,
    href: &quot;https://appacademy.io&quot;,
  },
  &quot;App Academy&quot;
);
// JSX Version
&lt;a className=&quot;active&quot; href=&quot;https://appacademy.io&quot;&gt;
  App Academy
&lt;/a&gt;;

React.createElement(
OwnerDetails,
{
owner: props.data.owner,
number: props.index + 1,
},
props.name
);
// JSX Version
&lt;OwnerDetails owner={props.data.owner} number={props.index + 1}&gt;
{props.name}
&lt;/OwnerDetails&gt;;</code></pre>

<p>More Complex JSX Example</p>
<pre><code>const BookPanel = (props) =&gt; {
  &lt;section className=&quot;book&quot; id={`book-${props.id}`}&gt;
    &lt;h1 className=&quot;book__title&quot;&gt;{props.title}&lt;/h1&gt;
    &lt;img src={props.coverUrl} /&gt;
    &lt;div className=&quot;book__desc&quot;&gt;{props.description}&lt;/div&gt;
  &lt;/section&gt;;
};</code></pre>
<hr />
<h3 id="notes-3">Notes</h3>
<h3 id="using-custom-cra-templates">Using Custom CRA Templates</h3>
<p>Using a Custom Template <code>npx create-react-app my-app --template @appacademy/simple</code></p>
<ul>
<li><span id="9607">Keep in mind that using <code>create-react-app</code> automatically initializes a git repository for you!</span></li>
<li><span id="f0fe">App Academy custom template for creating a react app.</span></li>
<li><span id="1b4e">If using the default react create project you can delete the following files:</span></li>
<li><span id="ef1c">favicon.ico</span></li>
<li><span id="627b">robots.txt</span></li>
<li><span id="3b34">logo192.png</span></li>
<li><span id="9b50">logo512.png</span></li>
<li><span id="8101">manifest.json</span></li>
<li><span id="77db">You can also simplify the <code>html</code> file into:</span></li>
</ul>
<!-- -->
<pre><code>&lt;!DOCTYPE html&gt;
&lt;html lang=&quot;en&quot;&gt;
  &lt;head&gt;
    &lt;meta charset=&quot;utf-8&quot; /&gt;
    &lt;title&gt;React App&lt;/title&gt;
  &lt;/head&gt;
  &lt;body&gt;
    &lt;div id=&quot;root&quot;&gt;&lt;/div&gt;
  &lt;/body&gt;
&lt;/html&gt;</code></pre>
<p>Simplifying the src folder</p>
<ul>
<li><span id="ac69">Remove: App.css App.test.js logo.svg serviceWorker.js setupTests.js</span></li>
<li><span id="064f">Update the Following Files:</span></li>
</ul>
<!-- -->
<pre><code>// ./src/App.js
import React from &quot;react&quot;;
function App() {
  return &lt;h1&gt;Hello world!&lt;/h1&gt;;
}
export default App;
``;

// ./src/index.js
import React from &quot;react&quot;;
import ReactDOM from &quot;react-dom&quot;;
import &quot;./index.css&quot;;
import App from &quot;./App&quot;;
ReactDOM.render(
&lt;React.StrictMode&gt;
&lt;App /&gt;
&lt;/React.StrictMode&gt;,
document.getElementById(&quot;root&quot;)
);</code></pre>

<hr />
<h3 id="react-class-components">React Class Components</h3>
<p>Class Components</p>
<ul>
<li><span id="b5e6">You can write React components using ES2015 Classes: Function Component</span></li>
</ul>
<!-- -->
<pre><code>// ./src/Message.js
import React from &quot;react&quot;;
const Message = (props) =&gt; {
  return &lt;div&gt;{props.text}&lt;/div&gt;;
};
export default Message;</code></pre>
<p>ES2015 Version</p>
<pre><code>// ./src/Message.js
import React from &quot;react&quot;;
class Message extends React.Component {
  render() {
    return &lt;div&gt;{this.props.text}&lt;/div&gt;;
  }
}
export default Message;</code></pre>
<ul>
<li><span id="ae33">We can access props within a <code>class component</code> by using <code>this.props</code></span></li>
<li><span id="0b60">Keep in mind Class Components are used just like function components.</span></li>
</ul>
<!-- -->
<pre><code>// ./src/index.js
import React from &quot;react&quot;;
import ReactDOM from &quot;react-dom&quot;;
import Message from &quot;./Message&quot;;
ReactDOM.render(
  &lt;React.StrictMode&gt;
    &lt;Message text=&quot;Hello world!&quot; /&gt;
  &lt;/React.StrictMode&gt;,
  document.getElementById(&quot;root&quot;)
);</code></pre>
<p>Setting and accessing props</p>
<pre><code>class Message extends React.Component {
  constructor(props) {
    super(props);
    // TODO Initialize state, etc.
  }
  render() {
    return &lt;div&gt;{this.props.text}&lt;/div&gt;;
  }
}</code></pre>
<ul>
<li><span id="cd5a">If we define a constructor method in our Class Component, we have to define the <code>super</code> method with <code>props</code> passed through it.</span></li>
<li><span id="8bf7">Side Note: Before React used ES2015 Classes, it used <code>React.createclass</code> function, if you ever need to use this antiquated method make sure you install a module called <code>create-react-class</code> Stateful components</span></li>
<li><span id="4b12">One of the major reasons why you would choose to use a Class Component over a Function Component is to add and manage local or internal state to your component.</span></li>
<li><span id="8e82">Second of the major reasons is to be able to use a Class Component's lifecycle methods. What is state?</span></li>
<li><span id="7fab">Props are data that are provided by the consumer or caller of the component.</span></li>
<li><span id="98f4">Not meant to be changed by a component.</span></li>
<li><span id="c6a9">State is data that is <code>internal</code> to the component.</span></li>
<li><span id="3e89">Intended to be updated or mutated. When to use state</span></li>
<li><span id="c03f"><em>Only Use State when it is absolutely necessary</em></span></li>
<li><span id="204b">If the data never changes, or if it's needed through an entire application use props instead.</span></li>
<li><span id="0b53">State is more often used when creating components that retrieve data from APIs or render forms.</span></li>
<li><span id="1b6b">The general rule of thumb: If a component doesn't need to use state or lifecyle methods, it should be prioritized as a <code>function component</code>.</span></li>
<li><span id="d708">Functional:Stateless || Class:Stateful Initializing state</span></li>
<li><span id="e5d5">Use a class constructor method to initialize <code>this.state</code> object. // Application Entry Point</span></li>
</ul>
<!-- -->
<pre><code>// ./src/index.js
import React from &#39;react&#39;
import ReactDOM from &#39;react-dom&#39;;
import RandomQuote from &#39;./RandomQuote&#39;;
ReactDOM.render(
  &lt;React.StrictMode&gt;
    &lt;RandomQuote /&gt;
  &lt;/React.StrictMode&gt;
  document.getElementById(&#39;root&#39;);
)</code></pre>
<p>// Class Component: RandomQuote</p>
<pre><code>import React from &quot;react&quot;;
class RandomQuote extends React.Component {
  constructor() {
    super();
    const quotes = [
      &quot;May the Force be with you.&quot;,
      &quot;There&#39;s no place like home.&quot;,
      &quot;I&#39;m the king of the world!&quot;,
      &quot;My mama always said life was like a box of chocolates.&quot;,
      &quot;I&#39;ll be back.&quot;,
    ];
    this.state = {
      quotes,
      currentQuoteIndex: this.getRandomInt(quotes.length);
    }
  }
  getRandomInt(max) {
    return Math.floor(Math.random() * Math.floor(max));
  }
  render() {
    return (
      &lt;div&gt;
        &lt;h2&gt;Random Quote&lt;/h2&gt;
        &lt;p&gt;{this.state.quotes[this.state.currentQuoteIndex]}&lt;/p&gt;
      &lt;/div&gt;
    )
  }
}
export default RandomQuote;</code></pre>
<p>Updating State</p>
<ul>
<li><span id="3fdc">Let's say we want to update our state with a new quote.</span></li>
<li><span id="eddc">We can set up event listeners in React similarly to how we did them before.</span></li>
<li><span id="106c">&lt;button type="button" onClick={this.changeQuote}&gt; Change Quote &lt;/button&gt;</span></li>
<li><span id="a77a"><code>onClick</code> is the event listener.</span></li>
<li><span id="f406"><code>{this.changeQuote}</code> is the event handler method.</span></li>
<li><span id="7dca">Our Class Component File should now look like this with the new additions:</span></li>
</ul>
<!-- -->
<pre><code>import React from &quot;react&quot;;
class RandomQuote extends React.Component {
  constructor() {
    super();
    const quotes = [
      &quot;May the Force be with you.&quot;,
      &quot;There&#39;s no place like home.&quot;,
      &quot;I&#39;m the king of the world!&quot;,
      &quot;My mama always said life was like a box of chocolates.&quot;,
      &quot;I&#39;ll be back.&quot;,
    ];
    this.state = {
      quotes,
      currentQuoteIndex: this.getRandomInt(quotes.length);
    }
  }
  changeQuote = () =&gt; {
    const newIndex = this.getRandomInt(this.state.quotes.length);
    // Setting the &#39;new state&#39; of currentQuoteIndex state property
    // to newly generated random index #.
    this.setState({
      currentQuoteIndex: newIndex;
    })
  }
  getRandomInt(max) {
    return Math.floor(Math.random() * Math.floor(max));
  }
  render() {
    return (
      &lt;div&gt;
        &lt;h2&gt;Random Quote&lt;/h2&gt;
        &lt;p&gt;{this.state.quotes[this.state.currentQuoteIndex]}&lt;/p&gt;
        &lt;button type=&quot;button&quot; onClick={this.changeQuote}&gt;
          Change Quote
        &lt;/button&gt;
      &lt;/div&gt;
    )
  }
}
export default RandomQuote;</code></pre>
<p>Don't modify state directly</p>
<ul>
<li><span id="ca27">It is important to <code>never</code> modify your state directly!</span></li>
<li><span id="780d">ALWAYS use <code>this.setState</code> method to update state.</span></li>
<li><span id="1581">This is because when you only use this.state to re-assign, no re-rendering will occur =&gt; leaving our component out of sync. Properly updating state from the previous state</span></li>
<li><span id="dc5a">In our current example, the way we have <code>changeQuote</code> set up leaves us with occasionally producing the same index twice in a row.</span></li>
<li><span id="0bff">One solution is to design a loop but keep in mind that state updates are handled asynchronously in React (your current value is not guaranteed to be the latest)</span></li>
<li><span id="39f9">A safe method is to pass an anonymous method to <code>this.setState</code> (instead of an object literal) Previous</span></li>
</ul>
<!-- -->
<pre><code>changeQuote = () =&gt; {
    const newIndex = this.getRandomInt(this.state.quotes.length);
    this.setState({
      currentQuoteIndex: newIndex;
    })
  }</code></pre>
<p>Passing w/ Anon Method</p>
<pre><code>changeQuote = () =&gt; {
  this.setState((state, props) =&gt; {
    const { quotes, currentQuoteIndex } = state;
    let newIndex = -1;
    do {
      newIndex = this.getRandomInt(quote.length);
    } while (newIndex === currentQuoteIndex);
    return {
      currentQuoteIndex: newIndex,
    };
  });
};</code></pre>
<p>Providing default values for props</p>
<ul>
<li><span id="7e8c">In our current example, we pass in a static array of predefined quotes in our constructor.</span></li>
<li><span id="3e8f">The way it is set up right now leaves our list of quotes unchanged after initialization.</span></li>
<li><span id="add0">We can make quotes more dynamic by replacing our static array with a <code>props</code> argument passed into <code>super</code>.</span></li>
<li><span id="53d6">constructor(props) { super(props); }</span></li>
<li><span id="918a">We can now move our quotes array to our application entry point and pass it in as a prop. // Application Entry Point</span></li>
</ul>
<!-- -->
<pre><code>// ./src/index.js
import React from &#39;react&#39;
import ReactDOM from &#39;react-dom&#39;;
import RandomQuote from &#39;./RandomQuote&#39;;
// Re-assign our array here and pass it in as a prop in Render.
const quotes = [
      &quot;May the Force be with you.&quot;,
      &quot;There&#39;s no place like home.&quot;,
      &quot;I&#39;m the king of the world!&quot;,
      &quot;My mama always said life was like a box of chocolates.&quot;,
      &quot;I&#39;ll be back.&quot;,
      &quot;This way I can define more quotes&quot;,
    ];
ReactDOM.render(
  &lt;React.StrictMode&gt;
    &lt;RandomQuote quotes={quotes}/&gt;
  &lt;/React.StrictMode&gt;
  document.getElementById(&#39;root&#39;);
)</code></pre>
<ul>
<li><span id="a0bb">One thing to note about this workaround is that the caller of the component <em>must</em> set the quotes prop or the component will throw an error =&gt; so use <code>defaultProps</code>!</span></li>
</ul>
<!-- -->
<pre><code>// At the bottom of RandomQuote.js...
RandomQuote.defaultProps = {
  quotes: [
    &quot;May the Force be with you.&quot;,
    &quot;There&#39;s no place like home.&quot;,
    &quot;I&#39;m the king of the world!&quot;,
    &quot;My mama always said life was like a box of chocolates.&quot;,
    &quot;I&#39;ll be back.&quot;,
    &quot;This way I can define more quotes&quot;,
  ],
};</code></pre>
<ul>
<li><span id="c575">A good safety net in case the consumer/caller doesn't provide a value for the quotes array.</span></li>
<li><span id="3be6">We can even remove it from our index.js now and an error will not be thrown.</span></li>
</ul>
<hr />
<h3 id="handling-events">Handling Events</h3>
<ul>
<li><span id="a82e">To add an event listener to an element, just define a method to handle the event and associate that method with the element event you are listening for. Example</span></li>
</ul>
<!-- -->
<pre><code>import React from &quot;react&quot;;
class AlertButton extends React.Component {
  showAlert = () =&gt; {
    window.alert(&quot;Button Clicked!&quot;);
  };
  render() {
    return (
      &lt;button type=&quot;button&quot; onClick={this.showAlert}&gt;
        Submit
      &lt;/button&gt;
    );
  }
}</code></pre>
<ul>
<li><span id="a852">Note that when refering the handler method in onClick we're not invoking showAlert simply just passing a reference. Preventing default behavior</span></li>
<li><span id="5cb0">HTML Elements in the browser often have a lot of default behavior.</span></li>
<li><span id="df4d">I.E. Clicking on an <code>&lt;a&gt;</code> element navigates so a resource denoted by <code>&lt;href&gt;</code> property.</span></li>
<li><span id="952c">Here is an example of where using <code>e.preventDefault()</code> could come in handy.</span></li>
</ul>
<!-- -->
<pre><code>import React from &quot;react&quot;;
class NoDefaultSubmitForm extends React.Component {
  submitForm = (e) =&gt; {
    e.preventDefault();
    window.alert(&quot;Handling form submission...&quot;);
  };
  render() {
    return (
    &lt;form onSubmit={this.submitForm}&gt;
      &lt;button&gt;Submit&lt;/button&gt;
    &lt;/form&gt;;
    )}
}</code></pre>
<ul>
<li><span id="b149">The button contained within the form will end up refreshing the page before <code>this.submitForm</code> method can be completed.</span></li>
<li><span id="a034">We can stick an <code>e.preventDefault()</code> into the actual method to get around this problem.</span></li>
<li><span id="004a"><code>e</code> : Parameter that references a <code>Synthetic Event</code> object type. Using <code>this</code> in event handlers</span></li>
</ul>
<!-- -->
<pre><code>// ./src/AlertButton.js
import React from &quot;react&quot;;
class AlertButton extends React.Component {
  showAlert = () =&gt; {
    window.alert(&quot;Button clicked!&quot;);
    console.log(this);
  };
  render() {
    return (
      &lt;button type=&quot;button&quot; onClick={this.showAlert}&gt;
        Click Me
      &lt;/button&gt;
    );
  }
}
export default AlertButton;</code></pre>
<ul>
<li><span id="3c8f">When we console log <code>this</code> we see the AlertButton object.</span></li>
<li><span id="42a0">If we were to write the showAlert method with a regular class method like:</span></li>
</ul>
<!-- -->
<pre><code>showAlert() {
  console.log(this);
}</code></pre>
<ul>
<li><span id="c081">We would get <code>undefined</code> =&gt; remember that fat arrow binds to the current context! Reviewing class methods and the <code>this</code> keyword</span></li>
<li><span id="e98e">Let's refresh on binding.</span></li>
</ul>
<!-- -->
<pre><code>class Boyfriend {
  constructor() {
    this.name = &quot;Momato Riruru&quot;;
  }
  displayName() {
    console.log(this.name);
  }
}
const Ming = new Boyfriend();
Ming.displayName(); // =&gt; Momato Riruru
const displayAgain = Ming.displayName;
displayAgain(); // =&gt; Result in a Type Error: Cannot read property &#39;name&#39; of undefined.</code></pre>
<ul>
<li><span id="fb85">The first time we use our <code>displayMethod</code> call, it is called directly on the instance of the boyfriend class, which is why <code>Momato Riruru</code> was printed out.</span></li>
<li><span id="3a9b">The second time it was called, the ref of the method is stored as a variable and method is called on that variable instead of the instance; resulting in a type error (it has lost it's context)</span></li>
<li><span id="0a2c">Remember we can use the <code>bind</code> method to rebind context!</span></li>
<li><span id="d6d9">We can refactor to get the second call working like this:</span></li>
<li><span id="7ead">const displayAgain = Ming.displayName.bind(Ming); displayAgain(); // =&gt; Now Momato Riruru will be printed out.</span></li>
<li><span id="a8b0">To continue using function declarations vs fat arrow we can assign context in a constructor within a class component.</span></li>
</ul>
<!-- -->
<pre><code>import React from &quot;react&quot;;
class AlertButton extends React.Component {
  constructor() {
    super();
    this.showAlert = this.showAlert.bind(this); // binding context
  }
  showAlert() {
    console.log(this);
  }
  render() {
    return (
      &lt;button type=&quot;button&quot; onClick={this.showAlert}&gt;
        Submit
      &lt;/button&gt;
    );
  }
}
export default AlertButton;</code></pre>
<ul>
<li><span id="a4e6"><code>Experimental Syntax</code> : Syntax that has been proposed to add to ECMAScript but hasn't officially been added to the language specification yet.</span></li>
<li><span id="801d">It's good to pick one approach and use it consistently, either:</span></li>
</ul>
<ol type="1">
<li><span id="2e3e">Class Properties &amp; Arrow Functions</span></li>
<li><span id="cc27">Bind Method &amp; This Keyword The <code>SyntheticEvent</code> object</span></li>
</ol>
<ul>
<li><span id="f177">Synthetic Event Objects: Cross Browser wrappeds around the browser's native event.</span></li>
<li><span id="418f">Includes the use of stopPropagation() and preventDefault();</span></li>
<li><span id="b94f">Attributes of the Synthetic Event Object:Attributesboolean bubblesboolean cancelableDOMEventTarget currentTargetboolean defaultPreventednumber eventPhaseboolean isTrustedDOMEvent nativeEventvoid preventDefault()boolean isDefaultPrevented()void stopPropagation()boolean isPropagationStopped()void persist()DOMEventTarget targetnumber timeStampstring type</span></li>
<li><span id="7484"><code>nativeEvent</code> : property defined in a synthetic event object that gives you access to the underlying native browser event (rarely used!)</span></li>
</ul>
<hr />
<h3 id="forms-in-react">Forms in React</h3>
<p><em>Exercise being done in a separate file</em> Random Notes</p>
<ul>
<li><span id="45ec"><code>onChange</code> : detects when a value of an input element changes.</span></li>
<li><span id="9ca4">Assigning <code>onChange</code> to our input fields makes our component's state update in real time during user input.</span></li>
<li><span id="eb83">Dont forget to add <code>preventDefault</code> onto form submissions to deal with the default behavior of the browser refreshing the page!</span></li>
<li><span id="c413"><code>submittedOn: new Date(),</code> Can be added to a form, most likely will persist into a DB.</span></li>
<li><span id="b97f">Controlled Components</span></li>
<li><span id="ac48">We use the <code>onChange</code> event handlers on form fields to keep our component's state as the <code>"one source of truth"</code></span></li>
<li><span id="4685">Adding an <code>onChange</code> event handler to every single input can massively bloat your code.</span></li>
<li><span id="448c">Try assiging it to it's own method to apply everywhere.</span></li>
<li><span id="f229"><code>textarea</code> is handled differently in react: it takes in a value property to handle what the inner text will be.</span></li>
</ul>
<!-- -->
<pre><code>// ./src/ContactUs.js
import React from &quot;react&quot;;
class ContactUs extends React.Component {
  constructor() {
    super();
    this.state = {
      name: &quot;&quot;,
      email: &quot;&quot;,
      phone: &quot;&quot;,
      phoneType: &quot;&quot;,
      comments: &quot;&quot;,
      validationErrors: [],
    };
  }
  onChange = (e) =&gt; {
    const { name, value } = e.target;
    this.setState({ [name]: value });
  };
  // Vanilla JS Function for validating inputs
  validate(name, email) {
    const validationErrors = [];
    if (!name) {
      validationErrors.push(&quot;Please provide a Name&quot;);
    }
    if (!email) {
      validationErrors.push(&quot;Please provide an Email&quot;);
    }
    return validationErrors;
  }
  onSubmit = (e) =&gt; {
    // Prevent the default form behavior
    // so the page doesn&#39;t reload.
    e.preventDefault();
    // Retrieve the contact us information from state.
    const { name, email, phone, phoneType, comments } = this.state;
    // Get Validation Errors - proceeding destructuring values from this.state.
    const validationErrors = this.validate(name, email);
    // If we have errors...
    if (validationErrors.length &gt; 0) {
      this.setState({ validationErrors });
    } else {
      // Proceed normally
      // Create a new object for the contact us information.
      const contactUsInformation = {
        name,
        email,
        phone,
        phoneType,
        comments,
        submittedOn: new Date(),
      };
      console.log(contactUsInformation);
      // Reset the form state.
      this.setState({
        name: &quot;&quot;,
        email: &quot;&quot;,
        phone: &quot;&quot;,
        phoneType: &quot;&quot;,
        comments: &quot;&quot;,
        validationErrors: [],
      });
    }
  };
  render() {
    const { name, email, phone, phoneType, comments, validationErrors } =
      this.state;
    return (
      &lt;div&gt;
        &lt;h2&gt;Contact Us&lt;/h2&gt;
        {validationErrors.length &gt; 0 &amp;&amp; (
          &lt;div&gt;
            The following errors were found:
            &lt;ul&gt;
              {validationErrors.map((error) =&gt; (
                &lt;li key={error}&gt;{error}&lt;/li&gt;
              ))}
            &lt;/ul&gt;
          &lt;/div&gt;
        )}
        &lt;form onSubmit={this.onSubmit}&gt;
          &lt;div&gt;
            &lt;label htmlFor=&quot;name&quot;&gt;Name:&lt;/label&gt;
            &lt;input
              id=&quot;name&quot;
              name=&quot;name&quot;
              type=&quot;text&quot;
              onChange={this.onChange}
              value={name}
            /&gt;
          &lt;/div&gt;
          &lt;div&gt;
            &lt;label htmlFor=&quot;email&quot;&gt;Email:&lt;/label&gt;
            &lt;input
              id=&quot;email&quot;
              name=&quot;email&quot;
              type=&quot;text&quot;
              onChange={this.onChange}
              value={email}
            /&gt;
          &lt;/div&gt;
          &lt;div&gt;
            &lt;label htmlFor=&quot;phone&quot;&gt;Phone:&lt;/label&gt;
            &lt;input
              id=&quot;phone&quot;
              name=&quot;phone&quot;
              type=&quot;text&quot;
              onChange={this.onChange}
              value={phone}
            /&gt;
            &lt;select name=&quot;phoneType&quot; onChange={this.onChange} value={phoneType}&gt;
              &lt;option value=&quot;&quot;&gt;Select a phone type...&lt;/option&gt;
              {this.props.phoneTypes.map((phoneType) =&gt; (
                &lt;option key={phoneType}&gt;{phoneType}&lt;/option&gt;
              ))}
            &lt;/select&gt;
          &lt;/div&gt;
          &lt;div&gt;
            &lt;label htmlFor=&quot;comments&quot;&gt;Comments:&lt;/label&gt;
            &lt;textarea
              id=&quot;comments&quot;
              name=&quot;comments&quot;
              onChange={this.onChange}
              value={comments}
            /&gt;
          &lt;/div&gt;
          &lt;div&gt;
            &lt;button&gt;Submit&lt;/button&gt;
          &lt;/div&gt;
        &lt;/form&gt;
      &lt;/div&gt;
    );
  }
}
ContactUs.defaultProps = {
  phoneTypes: [&quot;Home&quot;, &quot;Work&quot;, &quot;Mobile&quot;],
};
export default ContactUs;</code></pre>
<ul>
<li><span id="a2da">We can use validation libraries like <code>validate</code> to make our validation functions more complex.</span></li>
</ul>
<!-- -->
<pre><code>import isEmail from &quot;validator/es/lib/isEmail&quot;;
  validate(name, email) {
    const validationErrors = [];
    if (!name) {
      validationErrors.push(&quot;Please provide a Name&quot;);
    }
    if (!email) {
      validationErrors.push(&quot;Please provide an Email&quot;);
    } else if (!isEmail(email)) {
      validationErrors.push(&quot;Please provide a valid Email&quot;);
    }
    return validationErrors;
  }</code></pre>
<p>Note About Client-side vs server-side validation</p>
<ul>
<li><span id="5808">Server-side validation is not optional.</span></li>
<li><span id="3bb8">Tech-savvy users can manipulate client-side validations.</span></li>
<li><span id="311f">Sometimes the 'best approach' is to skip implementing validations on the client-side and rely completely on the server-side validation.</span></li>
</ul>
<hr />
<h3 id="component-lifecycle">Component Lifecycle</h3>
<figure>
<img src="https://cdn-images-1.medium.com/max/800/0*c24XQBvqBBg0Eztz" class="graf-image" />
</figure>
<ul>
<li><span id="e1d9">Component Lifecycle is simply a way of describing the key moments in the lifetime of a component.</span></li>
</ul>
<ol type="1">
<li><span id="8e64">Loading (Mounting)</span></li>
<li><span id="7e94">Updating</span></li>
<li><span id="2cd3">Unloading (Unmounting) The lifecycle of a React component</span></li>
</ol>
<ul>
<li><span id="7740">Each <code>Class Component</code> has several <code>lifecycle methods</code> that you can add to run code at specific times.</span></li>
<li><span id="e7d0"><code>componentDidMount</code> : Method called after your component has been added to the component tree.</span></li>
<li><span id="6d92"><code>componentDidUpdate</code> : Method called after your component has been updated.</span></li>
<li><span id="9ee2"><code>componentWillUnmount</code> : Method called just before your component is removed from the component tree.</span></li>
<li><span id="7bd8"><code>Mounting</code></span></li>
</ul>
<ol type="1">
<li><span id="6f9e"><code>constructor</code> method is called</span></li>
<li><span id="e9c7"><code>render</code> method is called</span></li>
<li><span id="eef3">React updates the <code>DOM</code></span></li>
<li><span id="19bb"><code>componentDidMount</code> is called</span></li>
</ol>
<ul>
<li><span id="85f1"><code>Updating</code></span></li>
<li><span id="94f5">When component receives new <code>props</code></span></li>
</ul>
<ol type="1">
<li><span id="e635"><code>render</code> method is called</span></li>
<li><span id="70f9">React updates the <code>DOM</code></span></li>
<li><span id="9507"><code>componentDidUpdate</code> is called</span></li>
</ol>
<ul>
<li><span id="b00a">When <code>setState</code> is called</span></li>
</ul>
<ol type="1">
<li><span id="6864"><code>render</code> method is called</span></li>
<li><span id="e13b">React updates the <code>DOM</code></span></li>
<li><span id="c459"><code>componentDidUpdate</code> is called</span></li>
</ol>
<ul>
<li><span id="bfdd"><code>Unmounting</code></span></li>
<li><span id="10c1">The moment before a class component is removed from the component tree:</span></li>
<li><span id="c214"><code>componentDidMount</code> will be called. Avoiding the legacy lifecycle methods</span></li>
<li><span id="d438">Occasionally you will encounter some deprecated lifecycle methods:</span></li>
<li><span id="1f6b">UNSAFE_componentWillMount</span></li>
<li><span id="48ac">UNSAFE_componentWillReceiveProps</span></li>
<li><span id="df27">UNSAFE_componentWillUpdate</span></li>
<li><span id="af07">Just know they will be removed soon from React's API, peace. Using the class component lifecycle methods <em>Exercise done in sep. directory</em></span></li>
<li><span id="344c">Assorted Notes:</span></li>
<li><span id="d6b1">Common Use for <code>componentDidMount</code> lifecycle method is for fetching data from an API.</span></li>
</ul>
<hr />
<p>—</p>
<h3 id="notes-4">Notes</h3>
<h3 id="react-context">React Context</h3>
<ul>
<li><span id="e968">You can use <code>React Context</code> to pass data through a component tree without having to manually thread props.</span></li>
<li><span id="89d9">Convenient way to share &amp; update <code>global data</code>. Creating a Context</span></li>
</ul>
<!-- -->
<pre><code>// PupContext.js
import { createContext } from &quot;react&quot;;
const PupContext = createContext();
export default PupContext;</code></pre>
<ul>
<li><span id="a8bf">We use <code>React.createContext</code> to create context.</span></li>
<li><span id="98b9">Keep in mind if you invoke this method with aruguments, those arguments will be set as default context. Adding a Provider to the App component</span></li>
<li><span id="a919">In order to pass context over to child components we need to wrap them in a provider component.</span></li>
<li><span id="9afc">The provider component takes in a value property that points to the information that needs to be passed to the children.</span></li>
</ul>
<!-- -->
<pre><code>&lt;MyContext.Provider value={/* some value */}&gt;
  &lt;ChildComponent /&gt;
&lt;/MyContext.Provider&gt;</code></pre>
<p>Setting up a Consumer</p>
<pre><code>&lt;MyContext.Consumer&gt;
  {(value) =&gt; &lt;Component value={value} /&gt;}
&lt;/MyContext.Consumer&gt;</code></pre>
<ul>
<li><span id="2693">Keep in mind that <code>Context.Consumer</code> expects a function as a child.</span></li>
<li><span id="19fc">The function has a value prop passed in from <code>Context.Provider</code></span></li>
</ul>
<hr />
<h3 id="notes-5">Notes</h3>
<h3 id="redux-explained">Redux Explained</h3>
<ul>
<li><span id="eab4">JS Framework for managing the frontend state of a web application.</span></li>
<li><span id="3c8b">Gives us ability to store information in an organized manner in a web app and quickly retrieve that information from anywhere in the app.</span></li>
<li><span id="695d"><code>Redux</code></span></li>
<li><span id="00d5">Client Side Data Management</span></li>
<li><span id="dd41">Controls "Frontend State"</span></li>
<li><span id="d828">NOT Your Database</span></li>
<li><span id="855a">NOT Component State</span></li>
<li><span id="4c1a">Just used for managing Data</span></li>
</ul>
<figure>
<img src="https://cdn-images-1.medium.com/max/800/0*N7KFfhOZZ7UrY8s4" class="graf-image" />
</figure>
<ul>
<li><span id="04c0">Visual of how an app without React manages it's data.</span></li>
<li><span id="bae2">A lot of prop threading happening.</span></li>
<li><span id="989f">Data stored in a sep. location — <code>global data</code>. The Anatomy of Redux</span></li>
<li><span id="cd66"><code>Store</code></span></li>
<li><span id="9453">Holds the Frontend State</span></li>
<li><span id="cea4">Provides an API for the Frontend State</span></li>
<li><span id="c653"><code>Action</code></span></li>
<li><span id="7fb4">POJOs</span></li>
<li><span id="69a1">Outline Changes to Frontend State</span></li>
<li><span id="1a0a"><code>Reducers</code></span></li>
<li><span id="a372">Functions</span></li>
<li><span id="8bb8">Make Changes to Frontend State Where did Redux come from?</span></li>
<li><span id="6d0b">There are three central philosophies of Redux:</span></li>
</ul>
<ol type="1">
<li><span id="12ac"><code>A Single Source of Truth</code> : state is stored in a POJO</span></li>
<li><span id="d178"><code>State is Read Only</code> : State is immutable, modified by dispatching actions.</span></li>
<li><span id="51c5"><code>Changes are Made with Pure Functions</code> : Reducers that receive the actions and return updated state are pure functions of the old state and action. When is it appropriate to use Redux?</span></li>
</ol>
<ul>
<li><span id="117f">When doing a project with simpler global state requirements, it may be better to choose React's Context API over Redux.</span></li>
<li><span id="5d3d">Redux offers more flexibility and support for middleware along with richer developer tools. Vocabulary</span></li>
<li><span id="1ceb"><code>State</code></span></li>
<li><span id="49e7"><em>Redux is a State Manager</em></span></li>
<li><span id="5018">State is all the information stored by that program at a particular point in time.</span></li>
<li><span id="8fdb">Redux's main job is to store the state and make it directly available to your entire app.</span></li>
<li><span id="8bbd"><code>Store</code></span></li>
<li><span id="f027"><em>Redux stores state in a single store</em>.</span></li>
<li><span id="c97e">Redux store is a single JS object with a couple of methods (not a class!)</span></li>
<li><span id="199d">Methods include: <code>getState</code>, <code>dispatch(action)</code>, and <code>subscribe(listener)</code></span></li>
<li><span id="8bcf"><code>Actions</code></span></li>
<li><span id="2049"><em>Redux store is updated by dispatching actions</em></span></li>
<li><span id="cbac">Action is just a POJO that includes a mandatory <code>type</code> property.</span></li>
<li><span id="f2d5">Contain info to update the store.</span></li>
<li><span id="1bd9">We dispatch actions in response to User actions or AJAX requests.</span></li>
<li><span id="1b78"><code>Pure Functions</code></span></li>
<li><span id="c436"><em>Redux Reducers are Pure Functions</em></span></li>
<li><span id="e204">Functions are pure when their behavior depends only on it's arguments as has no side effects.</span></li>
<li><span id="450b">Simply takes in an argument and outputs a value.</span></li>
<li><span id="e146"><code>Reducer</code></span></li>
<li><span id="9721"><em>Redux handles actions using reducers</em></span></li>
<li><span id="c312">A function that is called each time an action is dispatched.</span></li>
<li><span id="84d8">Takes in an <code>action</code> and <code>current state</code></span></li>
<li><span id="90a3">Required to be pure functions so their behavior is predictable.</span></li>
<li><span id="5c36"><code>Middleware</code></span></li>
<li><span id="6b22"><em>Customize response to dispatch actions by using Middleware</em></span></li>
<li><span id="9287">Middleware is an optional component of Redus that allows custom responses to dispatched actions.</span></li>
<li><span id="f953">Most common use is to dispatch async requests to a server.</span></li>
<li><span id="773e"><code>Time Traveling Dev Tools</code></span></li>
<li><span id="d703"><em>Redux can time travel wow</em></span></li>
<li><span id="7187">Time travel refers to Redux's ability to revert to a previous state because reducers are all pure functions.</span></li>
<li><span id="ada3"><code>Thunks</code></span></li>
<li><span id="ee0f"><em>Convenient format for taking async actions in Redux</em></span></li>
<li><span id="586e">General concept in CS referring to a function who's primary purpose is to call another function.</span></li>
<li><span id="6f45">Most commonly used to make async API requests.</span></li>
</ul>
<hr />
<h3 id="flux-and-redux">Flux and Redux</h3>
<p>What is Flux?</p>
<ul>
<li><span id="06d1">Front-end application architecutre.</span></li>
<li><span id="8311">A pattern in which to structure an application.</span></li>
<li><span id="05e6">Unidirectional Data Flow — offers more predictability.</span></li>
<li><span id="751c"><code>Actions</code> : Begins the data flow of data, simple object that contains a type; type indicates the type of change to be performed.</span></li>
<li><span id="e8e7"><code>Dispatcher</code> : Mechanism for distributing actions to the store.</span></li>
<li><span id="af4f"><code>Store</code> : The entire state of the application, responsible for updating the state of your app.</span></li>
<li><span id="d7ff"><code>View</code> : Unit of code that's responsible for rendering the user interface. Used to re-render the application when actions and changes occur.</span></li>
</ul>
<figure>
<img src="https://cdn-images-1.medium.com/max/800/0*ywV6dO4a4QcGJxK5" class="graf-image" />
</figure>
<ul>
<li><span id="af94">Redux</span></li>
</ul>
<figure>
<img src="https://cdn-images-1.medium.com/max/800/0*Nd73GjTY1PVQtjtQ" class="graf-image" />
</figure>
<ul>
<li><span id="dc16">Library that facilitates the implementation of Flux.</span></li>
<li><span id="623a">Redux Three Principles</span></li>
<li><span id="2ac6"><code>Single Source of Truth</code></span></li>
<li><span id="a2b9"><code>State is Read-Only</code></span></li>
<li><span id="897b"><code>Only Pure Functions Change State</code></span></li>
</ul>
<hr />
<h3 id="store">Store</h3>
<ul>
<li><span id="cd1e">Simply an object that holds the application state wrapped in an API.</span></li>
<li><span id="f57c"><code>Three methods</code>:</span></li>
<li><span id="354c"><code>getState()</code> : Returns the store's current state.</span></li>
<li><span id="537c"><code>dispatch(action)</code> : Passes an action into the store's reducer to tell it what info to update.</span></li>
<li><span id="4539"><code>subscribe(callback)</code> : Registers a callback to be triggered whenever the store updates. Updating the Store</span></li>
</ul>
<!-- -->
<pre><code>store.dispatch(action);
// Add Orange Action
const addOrange = {
  type: &quot;ADD_FRUIT&quot;,
  fruit: &quot;orange&quot;,
};
// Reducer for Orange Action
const fruitReducer = (state = [], action) =&gt; {
  switch (action.type) {
    case &quot;ADD_FRUIT&quot;:
      return [...state, action.fruit];
    default:
      return state;
  }
};
// Run the Dispatch
console.log(store.getState()); // []
store.dispatch(addOrange);
console.log(store.getState()); // [ &#39;orange&#39; ]</code></pre>
<p>Subscribing to the store</p>
<ul>
<li><span id="1a02">Whenever a store process a dispatch(), it triggers all its subscribers.</span></li>
<li><span id="e667"><code>Subscribers</code> : callbacks that can be added to the store via subscribe().</span></li>
</ul>
<!-- -->
<pre><code>const display = () =&gt; {
  console.log(store.getState());
};
const unsubscribeDisplay = store.subscribe(display);
store.dispatch(addOrange); // [ &#39;orange&#39;, &#39;orange&#39; ]
// display will no longer be invoked after store.dispatch()
unsubscribeDisplay();
store.dispatch(addOrange); // no output</code></pre>
<p>Reviewing a simple example</p>
<pre><code>// app.js
const { createStore } = require(&quot;redux&quot;);
// Define the store&#39;s reducer.
const fruitReducer = (state = [], action) =&gt; {
  switch (action.type) {
    case &quot;ADD_FRUIT&quot;:
      return [...state, action.fruit];
    default:
      return state;
  }
};
// Create the store.
const store = createStore(fruitReducer);
// Define an &#39;ADD_FRUIT&#39; action for adding an orange to the store.
const addOrange = {
  type: &quot;ADD_FRUIT&quot;,
  fruit: &quot;orange&quot;,
};
// Log to the console the store&#39;s state before and after
// dispatching the &#39;ADD_FRUIT&#39; action.
console.log(store.getState()); // []
store.dispatch(addOrange);
console.log(store.getState()); // [ &#39;orange&#39; ]
// Define and register a callback to listen for store updates
// and console log the store&#39;s state.
const display = () =&gt; {
  console.log(store.getState());
};
const unsubscribeDisplay = store.subscribe(display);
// Dispatch the &#39;ADD_FRUIT&#39; action. This time the `display` callback
// will be called by the store when its state is updated.
store.dispatch(addOrange); // [ &#39;orange&#39;, &#39;orange&#39; ]
// Unsubscribe the `display` callback to stop listening for store updates.
unsubscribeDisplay();
// Dispatch the &#39;ADD_FRUIT&#39; action one more time
// to confirm that the `display` method won&#39;t be called
// when the store state is updated.
store.dispatch(addOrange); // no output</code></pre>
<h3 id="reducers">Reducers</h3>
<ul>
<li><span id="98f3">Reducer function receives the current <code>state</code> and <code>action</code>, updates the state appropriately based on the <code>action.type</code> and returns the following state.</span></li>
<li><span id="4cee">You can bundles different action types and ensuing logic by using a switch/case statement.</span></li>
</ul>
<!-- -->
<pre><code>const fruitReducer = (state = [], action) =&gt; {
  switch (action.type) {
    case &quot;ADD_FRUIT&quot;:
      return [...state, action.fruit];
    case &quot;ADD_FRUITS&quot;:
      return [...state, ...action.fruits];
    case &quot;SELL_FRUIT&quot;:
      const index = state.indexOf(action.fruit);
      if (index !== -1) {
        // remove first instance of action.fruit
        return [...state.slice(0, index), ...state.slice(index + 1)];
      }
      return state; // if action.fruit is not in state, return previous state
    case &quot;SELL_OUT&quot;:
      return [];
    default:
      return state;
  }
};</code></pre>
<p>Reviewing how Array#slice works</p>
<pre><code>const fruits = [&quot;apple&quot;, &quot;apple&quot;, &quot;orange&quot;, &quot;banana&quot;, &quot;watermelon&quot;];
// The index of the &#39;orange&#39; element is 2.
const index = fruits.indexOf(&quot;orange&quot;);
// `...fruits.slice(0, index)` returns the array [&#39;apple&#39;, &#39;apple&#39;]
// `...fruits.slice(index + 1)` returns the array [&#39;banana&#39;, &#39;watermelon&#39;]
// The spread syntax combines the two array slices into the array
// [&#39;apple&#39;, &#39;apple&#39;, &#39;banana&#39;, &#39;watermelon&#39;]
const newFruits = [...fruits.slice(0, index), ...fruits.slice(index + 1)];</code></pre>
<ul>
<li><span id="f322">Approach that can be used to remove an element without mutating the original array. Avoiding state mutations</span></li>
<li><span id="f862">Your reducer must always return a new object if the state changes. GOOD</span></li>
</ul>
<!-- -->
<pre><code>const goodReducer = (state = { count: 0 }, action) =&gt; {
  switch (action.type) {
    case &quot;INCREMENT_COUNTER&quot;:
      const nextState = Object.assign({}, state);
      nextState.count++;
      return nextState;
    default:
      return state;
  }
};</code></pre>
<p>BAD</p>
<pre><code>const badReducer = (state = { count: 0 }, action) =&gt; {
  switch (action.type) {
    case &quot;INCREMENT_COUNTER&quot;:
      state.count++;
      return state;
    default:
      return state;
  }
};</code></pre>
<hr />
<h3 id="actions">Actions</h3>
<ul>
<li><span id="64b4">Actions are the only way to trigger changes to the store's state. Using action creators</span></li>
</ul>
<!-- -->
<pre><code>const addOrange = {
  type: &quot;ADD_FRUIT&quot;,
  fruit: &quot;orange&quot;,
};
store.dispatch(addOrange);
console.log(store.getState()); // [ &#39;orange&#39; ]</code></pre>
<ul>
<li><span id="c39d">fruit is the <code>payload key</code> and orange is the <code>state data</code></span></li>
<li><span id="43e2"><code>Action Creators</code> : Functions created from extrapolating the creation of an action object.</span></li>
</ul>
<!-- -->
<pre><code>const addFruit = (fruit) =&gt; ({
  type: &quot;ADD_FRUIT&quot;,
  fruit,
});</code></pre>
<ul>
<li><span id="11fd">Use parenthesis for implicit return value.</span></li>
<li><span id="eea8">We can now add whatever fruit we'd like.</span></li>
</ul>
<!-- -->
<pre><code>store.dispatch(addFruit(&quot;apple&quot;));
store.dispatch(addFruit(&quot;strawberry&quot;));
store.dispatch(addFruit(&quot;lychee&quot;));
console.log(store.getState()); // [ &#39;orange&#39;, &#39;apple&#39;, &#39;strawberry&#39;, &#39;lychee&#39; ]</code></pre>
<p>Preventing typos in action type string literals</p>
<pre><code>const ADD_FRUIT = &quot;ADD_FRUIT&quot;;
const ADD_FRUITS = &quot;ADD_FRUITS&quot;;
const SELL_FRUIT = &quot;SELL_FRUIT&quot;;
const SELL_OUT = &quot;SELL_OUT&quot;;
const addFruit = (fruit) =&gt; ({
  type: ADD_FRUIT,
  fruit,
});
const addFruits = (fruits) =&gt; ({
  type: ADD_FRUITS,
  fruits,
});
const sellFruit = (fruit) =&gt; ({
  type: SELL_FRUIT,
  fruit,
});
const sellOut = () =&gt; ({
  type: SELL_OUT,
});</code></pre>
<ul>
<li><span id="ae86">Using constant variables helps reduce simple typos in a reducer's case clauses.</span></li>
</ul>
<hr />
<h3 id="debugging-arrow-functions">Debugging Arrow Functions</h3>
<ul>
<li><span id="43c6">It is important to learn how to use debugger statements with arrow functions to effectively debug Redux cycle. Understanding the limitations of implicit return values</span></li>
</ul>
<!-- -->
<pre><code>const addFruit = (fruit) =&gt; {
  return {
    type: &quot;ADD_FRUIT&quot;,
    fruit,
  };
};
const addFruit = (fruit) =&gt; {
  debugger;
  return {
    type: &quot;ADD_FRUIT&quot;,
    fruit,
  };
};</code></pre>
<ul>
<li><span id="2806">You must use explicit return statement arrow function to use a debugger.</span></li>
</ul>
<hr />
<h3 id="react-router-introduction-1">React Router Introduction</h3>
<p>Now that you know how to render components in a React app, how do you handle rendering different components for different website pages? React Router is the answer!</p>
<p>Think of how you have created server-side routes in Express. Take the following URL and server-side route. Notice how the <code>/users/:userId</code> path corresponds with the <code>http://localhost:3000/users/2</code> URL to render a specific HTML page.</p>
<pre><code>// http://localhost:3000/users/2
app.get(&#39;/users/:userId&#39;, (req, res) =&gt; {
  res.render(&#39;userProfile.pug&#39;);
});</code></pre>
<p>In the default React setup, you lose the ability to create routes in the same manner as in Express. This is what React Router aims to solve!</p>
<p><a href="https://github.com/ReactTraining/react-router" class="markup--anchor markup--p-anchor">React Router</a> is a frontend routing library that allows you to control which components to display using the browser location. A user can also copy and paste a URL and email it to a friend or link to it from their own website.</p>
<p>When you finish this article, you should be able to use the following from the <code>react-router-dom</code> library:</p>
<ul>
<li><span id="e5d3"><code>&lt;BrowserRouter&gt;</code> to provide your application access to the <code>react-router-dom</code> library; and</span></li>
<li><span id="e1cd"><code>&lt;Route&gt;</code> to connect specific URL paths to specific components you want rendered; and</span></li>
<li><span id="bf15"><code>&lt;Switch&gt;</code> to wrap several <code>Route</code> elements, rendering only one even if several match the current URL; and</span></li>
<li><span id="0318">React Router's <code>match</code> prop to access route path parameters.</span></li>
</ul>
<h3 id="getting-started-with-routing">Getting started with routing</h3>
<p>Since you are writing single page apps, you don't want to refresh the page each time you change the browser location. Instead, you want to update the browser location and your app's response using JavaScript. This is known as client-side routing. You are using React, so you will use React Router to do this.</p>
<p>Create a simple react project template:</p>
<pre><code>npx create-react-app my-app --template @appacademy/simple</code></pre>
<p>Then install React Router:</p>
<pre><code>npm install --save react-router-dom@^5.1.2</code></pre>
<p>Now import <code>BrowserRouter</code> from <code>react-router-dom</code> in your entry file:</p>
<pre><code>import { BrowserRouter } from &#39;react-router-dom`;</code></pre>
<h3 id="browserrouter">BrowserRouter</h3>
<p><code>BrowserRouter</code> is the primary component of the router that wraps your route hierarchy. It creates a React context that passes routing information down to all its descendent components. For example, if you want to give <code>&lt;App&gt;</code> and all its children components access to React Router, you would wrap <code>&lt;App&gt;</code> like so:</p>
<pre><code>// ./src/index.js
import React from &#39;react&#39;;
import ReactDOM from &#39;react-dom&#39;;
import { BrowserRouter } from &#39;react-router-dom&#39;;
import App from &#39;./App&#39;;

const Root = () =&gt; {
return (
&lt;BrowserRouter&gt;
&lt;App /&gt;
&lt;/BrowserRouter&gt;
);
};

ReactDOM.render(
&lt;React.StrictMode&gt;
&lt;Root /&gt;
&lt;/React.StrictMode&gt;,
document.getElementById(&#39;root&#39;),
);</code></pre>

<p>Now you can route the rendering of certain components to certain URLs (i.e <code>https://www.website.com/profile</code><a href="https://www.website.com/profile%29." class="markup--anchor markup--p-anchor">).</a></p>
<h3 id="hashrouter">HashRouter</h3>
<p>Alternatively, you could import and use <code>HashRouter</code> from <code>react-router-dom</code>. Links for applications that use <code>&lt;HashRouter&gt;</code> would look like <code>https://www.website.com/#/profile</code> (with an <code>#</code> between the domain and path).</p>
<p>You'll focus on using the <code>&lt;BrowserRouter&gt;</code>.</p>
<h3 id="creating-frontend-routes">Creating frontend routes</h3>
<p>React Router helps your React application render specific components based on the URL. The React Router component you'll use most often is <code>&lt;Route&gt;</code>.</p>
<p>The <code>&lt;Route&gt;</code> component is used to wrap another component, causing that component to only be rendered if a certain URL is matched. The behavior of the <code>&lt;Route&gt;</code> component is controlled by the following props: <code>path</code>, <code>component</code>, <code>exact</code>, and <code>render</code> (optional).</p>
<p>Create a simple <code>Users</code> component that returns <code>&lt;h1&gt;This is the users index!&lt;/h1&gt;</code>. Now let's refactor your <code>index.js</code> file so that you can create your routes within the component:</p>
<pre><code>// ./src/index.js
import React from &#39;react&#39;;
import ReactDOM from &#39;react-dom&#39;;
import { BrowserRouter, Route } from &#39;react-router-dom&#39;;
import App from &#39;./App&#39;;
import Users from &#39;./Users&#39;;

const Root = () =&gt; {
return (
&lt;BrowserRouter&gt;
&lt;div&gt;
{/_ TODO: Routes _/}
&lt;/div&gt;
&lt;/BrowserRouter&gt;
);
};

ReactDOM.render(
&lt;React.StrictMode&gt;
&lt;Root /&gt;
&lt;/React.StrictMode&gt;,
document.getElementById(&#39;root&#39;),
);</code></pre>

<p>Note that <code>BrowserRouter</code> can only have a single child component, so the snippet above wraps all routes within parent a <code>&lt;div&gt;</code> element. Now let's create some routes!</p>
<h3 id="component">component</h3>
<p>Begin with the <code>component</code> prop. This prop takes a reference to the component to be rendered. Let's render your <code>App</code> component:</p>
<pre><code>const Root = () =&gt; {
  return (
    &lt;BrowserRouter&gt;
      &lt;div&gt;
        &lt;Route component={App} /&gt;
      &lt;/div&gt;
    &lt;/BrowserRouter&gt;
  );
};</code></pre>
<p>Now you'll need to connect a path to the component!</p>
<h3 id="path">path</h3>
<p>The wrapped component will only be rendered when the path is matched. The path matches the URL when it matches some initial portion of the URL. For example, a path of <code>/</code> would match both of the following URLs: <code>/</code> and <code>/users</code>. (Because <code>/users</code> begins with a <code>/</code> it matches the path <code>/</code>)</p>
<pre><code>&lt;Route path=&#39;/&#39; component={App} /&gt;
&lt;Route path=&#39;/users&#39; component={Users} /&gt;</code></pre>
<p>Take a moment to navigate to <code>http://localhost:3000/users</code> to see how both the <code>App</code> component and <code>Users</code> component are rendering.</p>
<h3 id="exact">exact</h3>
<p>If this <code>exact</code> flag is set, the path will only match when it exactly matches the URL. Then browsing to the <code>/users</code> path would no longer match <code>/</code> and only the <code>Users</code> component will be rendered (instead of both the <code>App</code> component and <code>Users</code> component).</p>
<pre><code>&lt;Route exact path=&#39;/&#39; component={App} /&gt;
&lt;Route path=&#39;/users&#39; component={Users} /&gt;</code></pre>
<h3 id="render">render</h3>
<p>This is an optional prop that takes in a function to be called. The function will be called when the path matches. The function's return value is rendered. You could also define a functional component inside the <code>component</code> prop, but this results in extra, unnecessary work for React. The <code>render</code> prop is preferred for inline rendering of simple functional components.</p>
<p>The difference between using <code>component</code> and <code>render</code> is that <code>component</code> returns new JSX to be re-mounted every time the route renders, while <code>render</code> simply returns to JSX what will be mounted once and re-rendered. For any given route, you should only use either the <code>component</code> prop, or the <code>render</code> prop. If both are supplied, only the <code>component</code> prop will be used.</p>
<pre><code>// This inline rendering will work, but is unnecessarily slow.
&lt;Route path=&quot;/hello&quot; component={() =&gt; &lt;h1&gt;Hello!&lt;/h1&gt;} /&gt;

// This is the preferred way for inline rendering.
&lt;Route path=&quot;/hello&quot; render={() =&gt; &lt;h1&gt;Hello!&lt;/h1&gt;} /&gt;</code></pre>

<p>It can be helpful to use <code>render</code> instead of <code>component</code> in your <code>&lt;Route&gt;</code> when you need to pass props into the rendered component. For example, imagine that you needed to pass the <code>users</code> object as a prop to your <code>Users</code> component. Then you could pass in props from <code>Root</code> to <code>Users</code> by returning the <code>Users</code> component like so:</p>
<pre><code>// `users` to be passed as a prop:
const users = {
  1: { name: &#39;Andrew&#39; },
  2: { name: &#39;Raymond&#39; }
};

&lt;Route path=&quot;/users&quot; render={() =&gt; &lt;Users users={users} /&gt;} /&gt;</code></pre>

<p>As a reminder, <code>BrowserRouter</code> can only have a single child component. That's why you have wrapped all your routes within parent a <code>&lt;div&gt;</code> element.</p>
<pre><code>const Root = () =&gt; {
  const users = {
    1: { name: &#39;Andrew&#39; },
    2: { name: &#39;Raymond&#39; }
  };

return (
&lt;BrowserRouter&gt;
&lt;div&gt;
&lt;h1&gt;Hi, I&#39;m Root!&lt;/h1&gt;
&lt;Route exact path=&quot;/&quot; component={App} /&gt;
&lt;Route path=&quot;/hello&quot; render={() =&gt; &lt;h1&gt;Hello!&lt;/h1&gt;} /&gt;
&lt;Route path=&quot;/users&quot; render={() =&gt; &lt;Users users={users} /&gt;} /&gt;
&lt;/div&gt;
&lt;/BrowserRouter&gt;
);
};</code></pre>

<p>With this <code>Root</code> component, you will always render the <code>&lt;h1&gt;Hi, I'm Root!&lt;/h1&gt;</code>, regardless of the path. Because of the first <code>&lt;Route&gt;</code>, you will only render the <code>App</code> component if the path exactly matches <code>/</code>. Because of the second <code>&lt;Route&gt;</code>, you will only render the <code>Users</code> component if the path matches <code>/users</code>.</p>
<h3 id="route-path-params">Route path params</h3>
<p>A component's props can also hold information about a URL's parameters. The router will match route segments starting at <code>:</code> up to the next <code>/</code>, <code>?</code>, or <code>#</code>. Those matched values are then passed to components via their props. Such segments are <em>wildcard</em> values that make up your route parameters.</p>
<p>For example, take the route below:</p>
<pre><code>&lt;Route path=&quot;/users/:userId&quot;
       render={(props) =&gt; &lt;Profile users={users} {...props} /&gt;} /&gt;</code></pre>
<p>The router would break down the full <code>/users/:userId/photos</code> path to two parts: <code>/users</code>, <code>:userId</code>.</p>
<p>The <code>Profile</code> component's props would have access to the <code>:userId</code> part of the <code>http://localhost:3000/users/:userId/photos</code> URL through the <code>props</code> with router parameter information. You would access the the <code>match</code> prop's parameters (<code>props.match.params</code>). If you are using the <code>render</code> prop of the <code>Route</code> component, make sure to spread the props back into the component if you want it to know about the "match" parameters.</p>
<pre><code>// Route&#39;s `render` prop allows you to pass the `users`
// prop and spread the router `props`.
render={(props) =&gt; &lt;Profile users={users} {...props} /&gt;}</code></pre>
<p>The <code>params</code> object would then have a property of <code>userId</code> which would hold the value of the <code>:userId</code> <em>wildcard</em> value. Let's render the <code>userId</code> parameter in a user profile component. Take a moment to create a <code>Profile.js</code> file with the following code:</p>
<pre><code>// ./src/Profile.js
import React from &quot;react&quot;;

const Profile = (props) =&gt; (
&lt;div&gt;
The user&#39;s id is {props.match.params.userId}.
&lt;/div&gt;
);

export default Profile;</code></pre>

<p>Notice how it uses the <code>match</code> prop to access the <code>:userId</code> parameter from the URL. You can use this wildcard to make and AJAX call to fetch the user information from the database and render the return data in the <code>Profile</code> component. Recall that your <code>Profile</code> component was rendered at the path <code>/users/:userId</code>. Thus you can use your <code>userId</code> parameters from <code>match.params</code> to fetch a specific user:</p>
<pre><code>// ./src/Profile.js
import React from &quot;react&quot;;

const Profile = ({ users, match: { params } }) =&gt; {

// In a real-world scenario, you&#39;d make a call to an API to fetch the user,
// instead of passing down and keying into a `users` prop.
const user = users[params.userId];

return (
&lt;div&gt;
The user&#39;s id is {params.userId} and the user&#39;s name is {user.name}.
&lt;/div&gt;
);
};

export default Profile;</code></pre>

<h3 id="match">Match</h3>
<p>Now that you've seen your React Router's <code>match</code> prop in action, let's go over more about <a href="https://reacttraining.com/react-router/web/api/Route/route-props" class="markup--anchor markup--p-anchor">route props</a>! React Router passes information to the components as route props, accessible to all components with access to the React Router. The three props it makes available are <code>location</code>, <code>match</code> and <code>history</code>. You've learned about <code>props.match.params</code>, but now let's review the other properties of the <code>match</code> prop!</p>
<p>This is an object that contains important information about how the current URL matches the route path. Here are some of the more useful keys on the <code>match</code> object:</p>
<ul>
<li><span id="1d2c"><code>isExact</code>: a boolean that tells you whether or not the URL exactly matches the path</span></li>
<li><span id="b558"><code>url</code>: the current URL</span></li>
<li><span id="ab28"><code>path</code>: the route path it matched against (without wildcards filled in)</span></li>
<li><span id="be5b"><code>params</code>: the matches for the individual wildcard segments, nested under their names</span></li>
</ul>
<p>When you use React Router, the browser <code>location</code> and <code>history</code> are a part of the state of your app. You can store information about which component should be displayed, which user profile you are currently viewing, or any other piece of state, in the browser location. You can then access that information from anywhere your Router props are passed to in your app.</p>
<p>Now that you've learned about parameters and route props, let's revisit your <code>Root</code> component to add an <code>exact</code> flag to your <code>/users</code> route so that it does not render with your <code>/users/:userId</code> route. Your component should look something like this:</p>
<pre><code>const Root = () =&gt; {
  const users = {
    1: { name: &#39;Andrew&#39; },
    2: { name: &#39;Raymond&#39; }
  };

return (
&lt;BrowserRouter&gt;
&lt;h1&gt;Hi, I&#39;m Root!&lt;/h1&gt;
&lt;div&gt;
&lt;Route exact path=&quot;/&quot; component={App} /&gt;
&lt;Route path=&quot;/hello&quot; render={() =&gt; &lt;h1&gt;Hello!&lt;/h1&gt;} /&gt;

        {/* Render the `Users` page if no ID is included. */}
        &lt;Route exact path=&quot;/users&quot; render={() =&gt; &lt;Users users={users} /&gt;} /&gt;

        {/* Otherwise, render the profile page for that userId. */}
        &lt;Route path=&quot;/users/:userId&quot; component={(props) =&gt; &lt;Profile users={users} {...props} /&gt;} /&gt;
      &lt;/div&gt;
    &lt;/BrowserRouter&gt;

);
};</code></pre>

<h3 id="what-you-learned">What you learned</h3>
<p>In this article, you learned how to:</p>
<ul>
<li><span id="92fc">Use components from the React Router library; and</span></li>
<li><span id="19b5">Create routes to render specific components; and</span></li>
<li><span id="fc9d">Manage the order of rendered routes; and</span></li>
<li><span id="3281">Use the <code>exact</code> flag to ensure that a specific path renders a specific component; and</span></li>
<li><span id="3949">Use the React Router <code>match</code> prop to access Router params.</span></li>
</ul>
<hr />
<h3 id="react-router-navigation">React Router Navigation</h3>
<p>Now that you know how to create front-end routes with React Router, you'll need to implement a way for your users to navigate the routes! This is what using React Router's <code>Link</code>, <code>NavLink</code>, <code>Redirect</code>, and <code>history</code> prop can help you do.</p>
<p>In this article, you'll be working off of the demo project you built in the React Router Intro reading. When you finish this article, you should be able to use the following components from the <code>react-router-dom</code> library:</p>
<ul>
<li><span id="76bc"><code>&lt;Link&gt;</code> or <code>&lt;NavLink&gt;</code> to create links with absolute paths to routes in your application (like "/users/1"); and,</span></li>
<li><span id="cdc2"><code>&lt;Redirect&gt;</code> to redirect a user to another path (i.e. a login page when the user is not logged in); and</span></li>
<li><span id="d8a7">React Router's <code>history</code> prop to update a browser's URL programmatically.</span></li>
</ul>
<h3 id="adding-links-for-navigation">Adding links for navigation</h3>
<p>React Router's <code>&lt;Link&gt;</code> is one way to simplify navigation around your app. It issues an on-click navigation event to a route defined in your app's router. Using <code>&lt;Link&gt;</code> renders an anchor tag with a correctly set <code>href</code> attribute.</p>
<h3 id="link">Link</h3>
<p>To use it, update your imports from the <code>react-router-dom</code> package to include <code>Link</code>:</p>
<pre><code>import { BrowserRouter, Route, Link } from &#39;react-router-dom&#39;;</code></pre>
<p>Note that <code>&lt;Link&gt;</code> can take two props: <code>to</code> and <code>onClick</code>.</p>
<p>The <code>to</code> prop is a route location description that points to an absolute path, (i.e. <code>/users</code>). Add the following <code>Link</code> components in your <code>index.js</code> file above your routes:</p>
<pre><code>&lt;Link to=&quot;/&quot;&gt;App&lt;/Link&gt;
&lt;Link to=&quot;/users&quot;&gt;Users&lt;/Link&gt;
&lt;Link to=&quot;/users/1&quot;&gt;Andrew&#39;s Profile&lt;/Link&gt;</code></pre>
<p>The <code>onClick</code> prop is just like any other JSX click handler. You can write a function that takes in an <code>event</code> and handles it. Add the following <code>Link</code> before your routes and the following click handler function within your <code>Root</code> component:</p>
<pre><code>// Link with onClick prop
&lt;Link to=&quot;/&quot; onClick={handleClick}&gt;App with click handler&lt;/Link&gt;

// Click handler function
const handleClick = () =&gt; {
console.log(&#39;Thanks for clicking!&#39;)
};</code></pre>

<p>Now, test your routes and links! If you inspect the page, you'll see that your links are now rendered as <code>&lt;a&gt;</code> elements. Notice that clicking the <code>App with click handler</code> link logs a message in your console while directing your browser to render the <code>App</code> component.</p>
<h3 id="navlink">NavLink</h3>
<p>The <code>&lt;NavLink&gt;</code> works just like a <code>&lt;Link&gt;</code>, but with a little extra functionality. It has the ability to add extra styling when the path it links to matches the current path. This makes it an ideal choice for a navigation bar, hence the name. This styling can be controlled by three extra props: <code>activeClassName</code>, <code>activeStyle</code>, and <code>exact</code>. To begin using <code>NavLink</code>, update your imports from the <code>react-router-dom</code> package:</p>
<pre><code>import { BrowserRouter, Route, NavLink } from &#39;react-router-dom&#39;;</code></pre>
<p>The <code>activeClassName</code> prop of the <code>NavLink</code> component allows you to set a CSS class name for styling the <code>NavLink</code> when its route is active. By default, the <code>activeClassName</code> is already set to <code>active</code>. This means that you simply need to add an <code>.active</code> class to your CSS file to add active styling to your link. A <code>NavLink</code> will be active if its <code>to</code> prop path matches the current URL.</p>
<p>Let's change your "Users", "Hello", and "Andrew's Profile" links to be different colors and have a larger font size when active.</p>
<pre><code>&lt;NavLink to=&quot;/&quot;&gt;App&lt;/NavLink&gt;
&lt;NavLink activeClassName=&quot;red&quot; to=&quot;/users&quot;&gt;Users&lt;/NavLink&gt;
&lt;NavLink activeClassName=&quot;blue&quot; to=&quot;/hello&quot;&gt;Hello&lt;/NavLink&gt;
&lt;NavLink activeClassName=&quot;green&quot; to=&quot;/users/1&quot;&gt;Andrew&#39;s Profile&lt;/NavLink&gt;
&lt;NavLink to=&quot;/&quot; onClick={handleClick}&gt;App with click handler&lt;/NavLink&gt;</code></pre>
<p>For example, this is what the rendered HTML <code>&lt;a&gt;</code> tag would look like when when the browser is navigated to the <code>/</code> path or the <code>/users</code> path:</p>
<pre><code>&lt;!-- Navigated to the / path (the activeClassName
     prop is set to active by default) --&gt;
&lt;a href=&quot;/&quot; class=&quot;active&quot;&gt;App&lt;/a&gt;

&lt;!-- NOT navigated to the `/` path --&gt;
&lt;a href=&quot;/&quot;&gt;App&lt;/a&gt;

&lt;!-- Navigated to the /users path (the activeClassName
prop is manually set to red) --&gt;
&lt;a href=&quot;/users&quot; class=&quot;red&quot;&gt;Users&lt;/a&gt;

&lt;!-- NOT navigated to the `/users` path --&gt;
&lt;a href=&quot;/users&quot;&gt;Users&lt;/a&gt;</code></pre>

<p>Import <code>NavLink</code> into your <code>index.js</code> file and take a moment to update all your <code>Link</code> elements to <code>NavLink</code> elements. Set an <code>activeClassName</code> prop to an <code>active</code> class. Add the following <code>.active</code> class to your <code>index.css</code> file:</p>
<pre><code>.active {
  font-weight: bold;
}

.red {
color: red;
font-size: 30px;
}

.blue {
color: blue;
font-size: 30px;
}

.green {
color: green;
font-size: 30px;
}</code></pre>

<p>Test your styled links! Notice how the <code>App</code> and <code>App with click handler</code> links are always bolded. This is because all of your links include the <code>/</code> path, meaning that the link to <code>/</code> will be active when browsing to <code>/users</code> and <code>/users/1</code> because of how <code>users</code> and <code>users/1</code> are both prefaced by a <code>/</code>.</p>
<p>The <code>activeStyle</code> prop is a style object that will be applied inline to the <code>NavLink</code> when its <code>to</code> prop matches the current URL. Add the following <code>activeStyle</code> to your <code>App</code> link and comment out the <code>.active</code> class in your CSS file.</p>
<pre><code>&lt;NavLink to=&quot;/&quot; activeStyle={{ fontWeight: &quot;bold&quot; }}&gt;App&lt;/NavLink&gt;</code></pre>
<p>The following html is rendered when at the <code>/</code> path:</p>
<pre><code>&lt;a href=&quot;/&quot; style=&quot;font-weight:bold;&quot; class=&quot;active&quot;&gt;App&lt;/a&gt;</code></pre>
<p>Notice how your <code>App with click handler</code> is not bolded anymore. This is because the default <code>active</code> class being applied does not have any CSS stylings set to the class. Uncomment your <code>.active</code> class in your CSS file to bring back bolding to this NavLink.</p>
<p>The <code>exact</code> prop is a boolean that defaults to <code>false</code>. If set to <code>true</code>, then the <code>activeStyle</code> and <code>activeClassName</code> props will only be applied when the current URL exactly matches the <code>to</code> prop. Update your <code>App</code> and <code>App with click handler</code> links with an <code>exact</code> prop set. Just like in your routes, you can use the <code>exact</code> flag instead of <code>exact={true}</code>.</p>
<pre><code>&lt;NavLink to=&quot;/&quot; exact={true} activeStyle={{ fontWeight: &quot;bold&quot; }}&gt;App&lt;/NavLink&gt;
&lt;NavLink to=&quot;/&quot; exact onClick={handleClick}&gt;App with click handler&lt;/NavLink&gt;</code></pre>
<p>Now your <code>App</code> and <code>App with click handler</code> links will only be bolded when you have navigated precisely to the <code>/</code> path.</p>
<h3 id="switching-between-routes">Switching between routes</h3>
<p>You came across styling issues when the <code>/users</code> and <code>/users/1</code> paths matched the <code>/</code> path. Routing can have this issue as well. This is why you need to control the switching between routes.</p>
<p>React Router's <code>&lt;Switch&gt;</code> component allows you to only render one <code>&lt;Route&gt;</code> even if several match the current URL. You can nest as many <code>Route</code>s as you wish between the opening and closing <code>Switch</code> tags, but only the first one that matches the current URL will be rendered.</p>
<p>This is particularly useful if you want a default component that will only render if none of our other routes match. View the example below. Without the Switch, <code>DefaultComponent</code> would always render. Since there isn't set a path in the <code>DefaultComponent</code> route, it will simply use the default path of <code>/</code>. Now the <code>DefaultComponent</code> will only render when neither of the preceding routes match.</p>
<pre><code>&lt;Switch&gt;
  &lt;Route path=&quot;some/url&quot; component={SomeComponent} /&gt;
  &lt;Route path=&quot;some/other/url&quot; component={OtherComponent} /&gt;
  &lt;Route component={DefaultComponent} /&gt;
&lt;/Switch&gt;</code></pre>
<p>Import <code>Switch</code> from <code>react-router-dom</code> and add <code>&lt;Switch&gt;</code> tags around your routes to take care of ordering and switching between your routes! Begin by adding the following route to the bottom of your routes to render that a <code>404: Page not found</code> message:</p>
<pre><code>&lt;Route render={() =&gt; &lt;h1&gt;404: Page not found&lt;/h1&gt;} /&gt;</code></pre>
<p>This is what your <code>Root</code> component should look like at this point:</p>
<pre><code>const Root = () =&gt; {
  const users = [
    { name: &#39;andrew&#39; },
    { name: &#39;raymond&#39; }
  ];

const handleClick = () =&gt; {
console.log(&#39;Thanks for clicking!&#39;)
};

return (
&lt;BrowserRouter&gt;
&lt;h1&gt;Hi, I&#39;m Root!&lt;/h1&gt;

      &lt;div&gt;
        &lt;NavLink to=&quot;/&quot; exact={true} activeStyle={{ fontWeight: &quot;bold&quot; }}&gt;App&lt;/NavLink&gt;
        &lt;NavLink activeClassName=&quot;red&quot; to=&quot;/users&quot;&gt;Users&lt;/NavLink&gt;
        &lt;NavLink activeClassName=&quot;blue&quot; to=&quot;/hello&quot;&gt;Hello&lt;/NavLink&gt;
        &lt;NavLink activeClassName=&quot;green&quot; to=&quot;/users/1&quot;&gt;Andrew&#39;s Profile&lt;/NavLink&gt;
        &lt;NavLink to=&quot;/&quot; exact onClick={handleClick}&gt;App with click handler&lt;/NavLink&gt;

        &lt;Switch&gt;
          &lt;Route path=&quot;/users/:userId&quot; component={(props) =&gt; &lt;Profile users={users} {...props} /&gt;} /&gt;
          &lt;Route exact path=&quot;/users&quot; render={() =&gt; &lt;Users users={users} /&gt;} /&gt;
          &lt;Route path=&quot;/hello&quot; render={() =&gt; &lt;h1&gt;Hello!&lt;/h1&gt;} /&gt;
          &lt;Route exact path=&quot;/&quot; component={App} /&gt;
          &lt;Route render={() =&gt; &lt;h1&gt;404: Page not found&lt;/h1&gt;} /&gt;
        &lt;/Switch&gt;
      &lt;/div&gt;
    &lt;/BrowserRouter&gt;

);
};</code></pre>

<p>Now you have control over the precedence of rendered components! Try navigating to <code>http://localhost:3000/asdf</code> or any other route you have not defined. The <code>&lt;h1&gt;404: Page not found&lt;/h1&gt;</code> JSX of the last <code>&lt;Route&gt;</code> will be rendered whenever the browser attempts to visit an undefined route.</p>
<h3 id="redirecting-users">Redirecting users</h3>
<p>But what if you want to redirect users to a login page when they aren't logged in? The <code>&lt;Redirect&gt;</code> component from React Router helps you redirect users!</p>
<p>The component takes only one prop: <code>to</code>. When it renders, it replaces the current URL with the value of its <code>to</code> prop. Typically you conditionally render <code>&lt;Redirect&gt;</code> to redirect the user away from some page you don't want them to visit. The example below checks whether there is a defined <code>currentUser</code> prop. If so, the <code>&lt;Route&gt;</code> will render the <code>Home</code> component. Otherwise, it will redirect the user to the <code>/login</code> path.</p>
<pre><code>&lt;Route
  exact path=&quot;/&quot;
  render={() =&gt; (this.props.currentUser ? &lt;Home /&gt; : &lt;Redirect to=&quot;/login&quot; /&gt;)}
/&gt;</code></pre>
<p>Note: you will learn how to use a more flexible auth pattern — don't directly imitate this example.</p>
<h3 id="history">History</h3>
<p>You know how to redirect users with a <code>&lt;Redirect&gt;</code> component, but what if you need to redirect users programmatically? You've learned about the React Router's <code>match</code> prop, but now let's go over another one of the <a href="https://reacttraining.com/react-router/web/api/Route/route-props" class="markup--anchor markup--p-anchor">route props</a>: <code>history</code>!</p>
<pre><code>// Pushing a new URL (and adding to the end of history stack):
const handleClick = () =&gt; this.props.history.push(&#39;/some/url&#39;);

// Replacing the current URL (won&#39;t be tracked in history stack):
const redirect = () =&gt; this.props.history.replace(&#39;/some/other/url&#39;);</code></pre>

<p>This prop lets you update the URL programmatically. For example, suppose you want to push a new URL when the user clicks a button. It has two useful methods:</p>
<ul>
<li><span id="31f3"><code>push</code> - This adds a new URL to the end of the history stack. That means that clicking the back button will take the browser to the previous URL. Note that pushing the same URL multiple times in a row will have no effect; the URL will still only show up on the stack once. In development mode, pushing the same URL twice in a row will generate a console warning. This warning is disabled in production mode.</span></li>
<li><span id="90c1"><code>replace</code> - This replaces the current URL on the history stack, so the back button won't take you to it. For example:</span></li>
</ul>
<h3 id="what-you-learned-1">What you learned</h3>
<p>In this article, you learned how to:</p>
<ul>
<li><span id="169b">Create navigation links for your route paths; and</span></li>
<li><span id="d108">Redirect users through using the <code>&lt;Redirect&gt;</code> component; and</span></li>
<li><span id="d090">Update a browser's URL programmatically by using React Router's <code>history</code> prop.</span></li>
</ul>
<hr />
<h3 id="react-router-nested-routes">React Router Nested Routes</h3>
<p>Now you know how to create front-end routes and add navigation with React Router. When initializing Express projects, you declare static routes. Static routes are routes that are declared when an application is initialized. When using React Router in your application's initialization, you can declare dynamic routes. React Router introduces dynamic routing, where your routes are created as your application is rendering. This allows you to create nested routes within components!</p>
<p>In this article, let's dive into <a href="https://reacttraining.com/react-router/core/guides/philosophy/nested-routes" class="markup--anchor markup--p-anchor">nested routes</a>! When you finish the article, you should:</p>
<ul>
<li><span id="38ee">Describe what nested routes are; and</span></li>
<li><span id="0559">Be able to use React Router to create and navigate nested routes; and</span></li>
<li><span id="ce4a">Know how to use the React Router <code>match</code> prop to generate links and routes.</span></li>
</ul>
<h3 id="why-nested-routes">Why nested routes?</h3>
<p>Let's begin with why you might need nested routes. As you remember, you are using React to create a single-page application. This means that you'll be organizing your application into different components and sub-components.</p>
<p>For example, imagine creating a simple front-end application with three main pages: a home welcome page (path of <code>/</code>), a users index page (path of <code>/users</code>), and user profile pages (path of <code>/users/:userId</code>). Now imagine if every user had links to separate <code>posts</code> and <code>photos</code> pages.</p>
<p>You can create those routes and links within the user profile component, instead of creating the routes and links where the main routes are defined.</p>
<h3 id="what-are-nested-routes">What are nested routes?</h3>
<p>Now let's dive into a user profile component to understand what are nested routes! Imagine you have a route in your application's entry file to each user's profile like so:</p>
<pre><code>&lt;Route path=&quot;/users/:userId&quot; component={Profile} /&gt;</code></pre>
<p>This means that upon navigating to <code>http://localhost:3000/users/1</code>, you would render the following <code>Profile</code> component and the <code>userId</code> parameter within <code>props.match.params</code> would have the value of <code>"1"</code>.</p>
<pre><code>const Profile = (props) =&gt; {
  // Custom call to database to fetch a user by a user ID.
  const user = fetchUser(props.match.params.userId);
  const { name, id } = user;

return (
&lt;div&gt;
&lt;h1&gt;Welcome to the profile of {name}!&lt;/h1&gt;

      {/* Links to a specific user&#39;s posts and photos */}
      &lt;Link to={`/users/${id}/posts`}&gt;{name}&#39;s Posts&lt;/Link&gt;
      &lt;Link to={`/users/${id}/photos`}&gt;{name}&#39;s Photos&lt;/Link&gt;

      {/* Routes to a specific user&#39;s posts and photos */}
      &lt;Route path=&#39;/users/:userId/posts&#39; component={UserPosts} /&gt;
      &lt;Route path=&#39;/users/:userId/photos&#39; component={UserPhotos} /&gt;
    &lt;/div&gt;

);
};</code></pre>

<p>Since this route is not created until the <code>Profile</code> component is rendered, you are dynamically creating your nested <code>/users/:userId/posts</code> and <code>/users/:userId/photos</code> routes. Remember that your <code>match</code> prop also has other helpful properties. You can use <code>match.url</code> instead of <code>/users/${id}</code> in your profile links. You can also use <code>match.path</code> instead of <code>/users/:userId</code> in your profile routes. Remember that you can destructure <code>url</code>, <code>path</code>, and <code>params</code> from your <code>match</code> prop!</p>
<pre><code>// Destructure `match` prop
const Profile = ({ match: { url, path, params }) =&gt; {

// Custom call to database to fetch a user by a user ID.
const user = fetchUser(params.userId);
const { name, id } = user;

return (
&lt;div&gt;
&lt;h1&gt;Welcome to the profile of {name}!&lt;/h1&gt;

      {/* Replaced `/users/${id}` URL with `props.match.url` */}
      &lt;Link to={`${url}/posts`}&gt;{name}&#39;s Posts&lt;/Link&gt;
      &lt;Link to={`${url}/photos`}&gt;{name}&#39;s Photos&lt;/Link&gt;

      {/* Replaced `/users/:userId` path with `props.match.path` */}
      &lt;Route path={`${path}/posts`} component={UserPosts} /&gt;
      &lt;Route path={`${path}/photos`} component={UserPhotos} /&gt;
    &lt;/div&gt;}

);
};</code></pre>

<p>In tomorrow's project, you'll build a rainbow of routes as well as define nested routes. In the future, you may choose to implement nested routes to keep your application's routes organized within related components.</p>
<h3 id="what-you-learned-2">What you learned</h3>
<p>In this article, you learned:</p>
<ul>
<li><span id="2378">What nested routes are; and</span></li>
<li><span id="e072">About creating and navigating nested routes with React Router; and</span></li>
<li><span id="c8b8">How to use the React Router props to generate nested links and routes.</span></li>
</ul>
<hr />
<h3 id="react-builds-1">React Builds</h3>
<p>A "build" is the process of converting code into something that can actually execute or run on the target platform. A "front-end build" is a process of preparing a front-end or client-side application for the browser.</p>
<p>With React applications, that means (at a minimum) converting JSX to something that browsers can actually understand. When using Create React App, the build process is automatically configured to do that and a lot more.</p>
<p>When you finish this article, you should be able to:</p>
<ul>
<li><span id="2448">Describe what front-end builds are and why they're needed;</span></li>
<li><span id="efab">Describe at a high level what happens in a Create React App when you run <code>npm start</code>; and</span></li>
<li><span id="502f">Prepare to deploy a React application into a production environment.</span></li>
</ul>
<h3 id="understanding-front-end-builds">Understanding front-end builds</h3>
<p>The need for front-end builds predates React. Over the years, developers have found it helpful to extend the lowest common denominator version of JavaScript and CSS that they could use.</p>
<p>Sometimes developers extend JavaScript and CSS with something like <a href="https://www.typescriptlang.org/" class="markup--anchor markup--p-anchor">TypeScript</a> or <a href="https://sass-lang.com/" class="markup--anchor markup--p-anchor">Sass</a>. Using these non-standard languages and syntaxes require you to use a build process to convert your code into standard JavaScript and CSS that can actually run in the browser.</p>
<p>Browser-based applications also require a fair amount of optimization to deliver the best, or at least acceptable, experience to end users. Front-end build processes could be configured to lint code, run unit tests, optimize images, minify and bundle code, and more — all automatically at the press of a button (i.e. running a command at the terminal).</p>
<h3 id="javascript-versions-and-the-growth-of-front-end-builds">JavaScript versions and the growth of front-end builds</h3>
<p>Developers are generally an impatient lot. When new features are added to JavaScript, we don't like to wait for browsers to widely support those features before we start to use them in our code. And we <em>really</em> don't like when we have to support older, legacy versions of browsers.</p>
<p>In recent years, JavaScript has been updated on a yearly basis and browser vendors do a decent job of updating their browsers to support the new features as they're added to the language. Years ago though, there was an infamous delay between versions 5 and 6 of JavaScript. It took <em>years</em> before ES6 (or ES2015 as it eventually was renamed to) to officially be completed and even longer before browsers supported all of its features.</p>
<p>In the period of time before ES2015 was broadly supported by browsers, developers used front-end builds to convert or <em>transpile</em> ES2015 features and syntax to an older version of the language that was more broadly supported by browsers (typically ES5). The transpilation from ES2015/ES6 down to ES5 was one of the major drivers for developers to add front-end builds to their client-side projects.</p>
<h3 id="reviewing-common-terminology">Reviewing common terminology</h3>
<p>When learning about front-end or React builds, you'll encounter a lot of terminology that you may or may not be familiar with. Here's some of the terminology that you'll likely encounter:</p>
<p>Linting is process of using a tool to analyze your code to catch common programming errors, bugs, stylistic inconsistencies, and suspicious coding patterns. <a href="https://eslint.org/" class="markup--anchor markup--p-anchor">ESLint</a> is a popular JavaScript linting tool.</p>
<p>Transpilation is the process of converting source code, like JavaScript, from one version to another version. Usually this means converting newer versions of JavaScript, <a href="https://www.ecma-international.org/ecma-262/10.0/index.html" class="markup--anchor markup--p-anchor">ES2019</a> or <a href="https://tc39.es/ecma262/" class="markup--anchor markup--p-anchor">ES2021</a>, to a version that's more widely supported by browsers, like <a href="http://www.ecma-international.org/ecma-262/6.0/" class="markup--anchor markup--p-anchor">ES2015</a>, or even <a href="https://www.ecma-international.org/ecma-262/5.1/" class="markup--anchor markup--p-anchor">ES5</a> or <a href="https://www.ecma-international.org/publications/files/ECMA-ST-ARCH/ECMA-262,%203rd%20edition,%20December%201999.pdf" class="markup--anchor markup--p-anchor">ES3</a> (if you need to support the browser that your parents or grandparents use).</p>
<p>Minification is the process of removing all unnecessary characters in your code (e.g. white space characters, new line characters, comments) to produce an overall smaller file. Minification tools will often also rename identifers in your code (i.e. parameter and variable names) in the quest for smaller and smaller file sizes. Source maps can also be generated to allow debugging tools to cross reference between minified code and the original source code.</p>
<p>Bundling is the process of combining multiple code files into a single file. Creating a bundle (or a handful of bundles) reduces the number of requests that a client needs to make to the server.</p>
<p>Tree shaking is the process of removing unused (or dead) code from your application before it's bundled. Tree shaking external dependencies can sometimes have a dramatic positive impact on overall bundled file sizes.</p>
<h3 id="configuration-or-code">Configuration or code?</h3>
<p>Front-end build tools have come and gone over the years; sometimes very quickly, which helped bring about the phenomenon known as <a href="https://sdtimes.com/softwaredev/is-the-javascript-fatigue-real/" class="markup--anchor markup--p-anchor">JavaScript fatigue</a>.</p>
<p>Configuration based tools allow you to create your build tasks by declaring (usually using JSON, XML, or YAML) what you want to be done, without explicitly writing every step in the process. In contrast, coding or scripting based tools allow you to, well, write code to create your build tasks. Configuration based tools <em>can</em> sometimes feel simpler to use while giving up some control (at least initially) while coding based tools <em>can</em> feel more familiar and predictable (since you're describing tasks procedurally). Every generalization is false though (including this one), so there are plenty of exceptions.</p>
<p><a href="https://gruntjs.com/" class="markup--anchor markup--p-anchor">Grunt</a> is a JSON configuration based task runner that can be used to orchestrate the various tasks that make up your front-end build. Grunt was very quickly supplanted by <a href="https://gulpjs.com/" class="markup--anchor markup--p-anchor">Gulp</a>, which allowed developers to write JavaScript to define front-end build tasks. After Gulp, the front-end tooling landscape became a bit more muddled. Some developers preferred the simplicity of using <a href="https://docs.npmjs.com/misc/scripts" class="markup--anchor markup--p-anchor">npm scripts</a> to define build tasks while others preferred the power of configuration based bundlers like <a href="https://webpack.js.org/" class="markup--anchor markup--p-anchor">webpack</a>.</p>
<h3 id="babel-and-webpack-yes-thats-intentionally-a-lowercase-w">Babel and webpack (yes, that's intentionally a lowercase 'w')</h3>
<p>As front-end or client-side applications grew in complexity, developers found themselves wanting to leverage more advanced JavaScript features and newer syntax like classes, arrow functions, destructuring, async/await, etc. Using a code transpiler, like <a href="https://babeljs.io/" class="markup--anchor markup--p-anchor">Babel</a>, allows you to use all of the latest and greatest features and syntax without worrying about what browsers support what.</p>
<p>Module loaders and bundlers, like <a href="https://webpack.js.org/" class="markup--anchor markup--p-anchor">webpack</a>, also allowed developers to use JavaScript modules without requiring users to use a browser that natively supports ES modules. Also, module bundling (along with minification and tree-shaking) helps to reduce the bandwidth that's required to deliver the assets for your application to the client.</p>
<p>[Create React App][cra] uses webpack (along with Babel) under the covers to build your React applications. Even if you're not using Create React App, webpack and Babel are still very popular choices for building React applications.</p>
<h3 id="pulling-back-the-covers-a-bit-on-the-create-react-app-build-process">Pulling back the covers (a bit) on the Create React App build process</h3>
<p>Running an application created by Create React App using <code>npm start</code> can feel magical. Some stuff happens in the terminal and your application opens into your default browser. Even better, when you make changes to your application, your changes will (usually) automatically appear in the browser!</p>
<h3 id="the-create-react-app-build-process">The Create React App build process</h3>
<p>At a high level, here's what happens when you run <code>npm start</code>:</p>
<ul>
<li><span id="2808">Environment variables are loaded (more about this in a bit);</span></li>
<li><span id="f272">The list of browsers to support are checked (more about this too in a bit);</span></li>
<li><span id="71b2">The configured HTTP port is checked to ensure that it's available;</span></li>
<li><span id="f826">The application compiler is configured and created;</span></li>
<li><span id="c605"><code>webpack-dev-server</code> is started;</span></li>
<li><span id="a696"><code>webpack-dev-server</code> compiles your application;</span></li>
<li><span id="c66e">The <code>index.html</code> file is loaded into the browser; and</span></li>
<li><span id="6add">A file watcher is started to watch your files, waiting for changes.</span></li>
</ul>
<h3 id="ejecting">Ejecting</h3>
<p>Create React App provides a script that you can run to "eject" your application from the Create React App tooling. When you eject your application, all of the hidden stuff is exposed so that you can review and customize it.</p>
<blockquote>
<p><em>The need to customize Create React App rarely happens. Also, don't eject an actual project as it's a one-way trip! Once a Create React App project has been ejected, there's no going back (though you could always undo the ejection process by reverting to an earlier commit if you're using source control).</em></p>
</blockquote>
<p>To eject your application from Create React App, run the command <code>npm run eject</code>. You'll be prompted if you want to continue; type "y" to continue with the ejection process. Once the ejection process has completed, you can review the files that were previously hidden from you.</p>
<p>In the <code>package.json</code> file, you'll see the following npm scripts:</p>
<pre><code>{
  &quot;scripts&quot;: {
    &quot;start&quot;: &quot;node scripts/start.js&quot;,
    &quot;build&quot;: &quot;node scripts/build.js&quot;,
    &quot;test&quot;: &quot;node scripts/test.js&quot;
  }
}</code></pre>
<p>You can open the <code>./scripts/start.js</code> file to see the code that's executed when you run <code>npm start</code>.</p>
<p>If you're curious about the webpack configuration, you can open and review the <code>./config/webpack.config.js</code>.</p>
<h3 id="preparing-to-deploy-a-react-application-for-production">Preparing to deploy a React application for production</h3>
<p>Before you deploy your application to production, you'll want to make sure that you've replaced static values in your code with environment variables and considered what browsers you need to support.</p>
<h3 id="defining-environment-variables">Defining environment variables</h3>
<p>Create React App supports defining environment variables in an <code>.env</code> file. To define an environment variable, add an <code>.env</code> file to your project and define one or more variables that start with the prefix <code>REACT_APP_</code>:</p>
<pre><code>REACT_APP_FOO: some value
REACT_APP_BAR: another value</code></pre>
<p>Environment variables can be used in code like this:</p>
<pre><code>console.log(process.env.REACT_APP_FOO);</code></pre>
<p>You can also reference environment variables in your <code>index.html</code> like this:</p>
<pre><code>&lt;title&gt;%REACT_APP_BAR%&lt;/title&gt;</code></pre>
<blockquote>
<p><em>Important: Environment variables are embedded into your HTML, CSS, and JavaScript bundles during the build process. Because of this, it's</em> very important <em>to not store any secrets, like API keys, in your environment variables as anyone can view your bundled code in the browser by inspecting your files.</em></p>
</blockquote>
<h3 id="configuring-the-supported-browsers">Configuring the supported browsers</h3>
<p>In your project's <code>package.json</code> file, you can see the list of targeted browsers:</p>
<pre><code>{
  &quot;browserslist&quot;: {
    &quot;production&quot;: [
      &quot;&gt;0.2%&quot;,
      &quot;not dead&quot;,
      &quot;not op_mini all&quot;
    ],
    &quot;development&quot;: [
      &quot;last 1 chrome version&quot;,
      &quot;last 1 firefox version&quot;,
      &quot;last 1 safari version&quot;
    ]
  }
}</code></pre>
<p>Adjusting these targets affect how your code will be transpiled. Specifying older browser versions will result in your code being transpiled to older versions of JavaScript in order to be compatible with the specified browser versions. The <code>production</code> list specifies the browsers to target when creating a production build and the <code>development</code> list specifics the browsers to target when running the application using <code>npm start</code>.</p>
<p>The <a href="https://browserl.ist/" class="markup--anchor markup--p-anchor">browserl.ist</a> website can be used to see the browsers supported by your configured <code>browserslist</code>.</p>
<h3 id="creating-a-production-build">Creating a production build</h3>
<p>To create a production build, run the command <code>npm run build</code>. The production build process bundles React in production mode and optimizes the build for the best performance. When the command completes, you'll find your production ready files in the <code>build</code> folder.</p>
<p>Now your application is ready to be deployed!</p>
<blockquote>
<p><em>For more information about how to deploy a Create React App project into production, see</em> <a href="https://facebook.github.io/create-react-app/docs/deployment" class="markup--anchor markup--blockquote-anchor"><em>this page</em></a> <em>in the official documentation.</em></p>
</blockquote>
<h3 id="what-you-learned-3">What you learned</h3>
<p>In this article, you learned how to:</p>
<ul>
<li><span id="1ff3">Describe what front-end builds are and why they're needed;</span></li>
<li><span id="1fc3">Describe at a high level what happens in a Create React App when you run <code>npm start</code>; and</span></li>
<li><span id="6adc">Prepare to deploy a React application into a production environment.</span></li>
</ul>
<hr />
<h3 id="react-router-documentation">React Router Documentation</h3>
<p>Now that you've had an introduction to React Router, feel free to explore the official documentation to learn more! As you become a full-fledged software engineer, remember that documentation is your friend. You can take a brief overview for now, as the documentation might include a lot of information at first. The more you learn about React, the more you should revisit the official documentation and learn!</p>
<h3 id="setting-up-react-router">Setting up React Router</h3>
<ul>
<li><span id="bfa4"><a href="https://reacttraining.com/react-router/web/guides/quick-start" class="markup--anchor markup--li-anchor">React Router Quick Start</a></span></li>
<li><span id="b0cb"><a href="https://reacttraining.com/react-router/web/api/HashRouter" class="markup--anchor markup--li-anchor">HashRouter</a></span></li>
<li><span id="f48b"><a href="https://reacttraining.com/react-router/web/api/BrowserRouter" class="markup--anchor markup--li-anchor">BrowserRouter</a></span></li>
</ul>
<h3 id="routes-and-links">Routes and Links</h3>
<ul>
<li><span id="72bd"><a href="https://reacttraining.com/react-router/web/api/Route" class="markup--anchor markup--li-anchor">Route</a></span></li>
<li><span id="e256"><a href="https://reacttraining.com/react-router/web/api/Link" class="markup--anchor markup--li-anchor">Link</a></span></li>
<li><span id="1d9d"><a href="https://reacttraining.com/react-router/web/api/NavLink" class="markup--anchor markup--li-anchor">NavLink</a></span></li>
</ul>
<h3 id="switch-and-redirect">Switch and Redirect</h3>
<ul>
<li><span id="5240"><a href="https://reacttraining.com/react-router/web/api/Switch" class="markup--anchor markup--li-anchor">Switch</a></span></li>
<li><span id="b405"><a href="https://reacttraining.com/react-router/web/api/Redirect" class="markup--anchor markup--li-anchor">Redirect</a></span></li>
</ul>
<h3 id="react-router-params-ownprops">React Router Params (ownProps)</h3>
<ul>
<li><span id="e0d6"><a href="https://reacttraining.com/react-router/web/api/history" class="markup--anchor markup--li-anchor">props.history</a></span></li>
<li><span id="5f4a"><a href="https://reacttraining.com/react-router/web/api/location" class="markup--anchor markup--li-anchor">props.location</a></span></li>
<li><span id="bd15"><a href="https://reacttraining.com/react-router/web/api/match" class="markup--anchor markup--li-anchor">props.match</a></span></li>
</ul>
<hr />
<h3 id="rainbow-routes-project">Rainbow Routes Project</h3>
<p>Today you're going to get our first experience using React Router. The goal is to create a basic app that displays the colors of the rainbow. This rainbow, however, has something special about it — some of the colors are nested within others.</p>
<h3 id="phase-0-setup">Phase 0: Setup</h3>
<p>Begin by creating a new React project:</p>
<pre><code>npx create-react-app rainbow-routes --template @appacademy/simple</code></pre>
<p>Now you'll remove all the contents of your <code>src</code> and all the contents from your <code>public</code> directory to build the application architecture from scratch! After you have deleted all your files within the directories, create a new <code>index.html</code> file in your <code>public</code> folder. Use the <code>html:5</code> emmet shortcut to generate an HTML template. Title your page "Rainbow Routes" and create a <code>div</code> with an <code>id</code> of <code>root</code> in your DOM's <code>&lt;body&gt;</code> element. Create an <code>index.css</code> file in your <code>src</code> directory with the following code. Now let's create your entry file!</p>
<pre><code>h4 {
  color: darkblue;
  cursor: pointer;
}

h4:hover {
text-decoration: underline;
}

#rainbow {
position: absolute;
top: 0;
left: 300px;
}

h3 {
position: absolute;
top: 1px;
}

.red {
background-color: red;
width: 100px;
height: 100px;
}

.orange {
background-color: orange;
width: 100px;
height: 50px;
}

.yellow {
background-color: yellow;
width: 100px;
height: 50px;
}

.green {
background-color: green;
width: 100px;
height: 100px;
}

.blue {
background-color: blue;
width: 100px;
height: 100px;
}

.indigo {
background-color: mediumslateblue;
width: 100px;
height: 50px;
}

.violet {
background-color: darkviolet;
width: 100px;
height: 100px;
}

a {
display: block;
margin-bottom: 10px;
}</code></pre>

<p>Create an <code>index.js</code> entry file in the <code>src</code> directory. At the top of the file, make sure to import <code>React</code> from the <code>react</code> package and <code>ReactDOM</code> from the <code>react-dom</code> package. Make sure to also import your the <code>index.css</code> file you just created! This will take care of styling your <em>rainbow routes</em>.</p>
<p>Now you can use the <code>ReactDOM.render()</code> method to render a <code>&lt;Root /&gt;</code> component instead of the DOM element with an <code>id</code> of <code>root</code>. Lastly, wrap your render function with a <code>DOMContentLoaded</code> event listener, like so:</p>
<pre><code>document.addEventListener(&#39;DOMContentLoaded&#39;, () =&gt; {
  ReactDOM.render(
    &lt;Root /&gt;,
    document.getElementById(&#39;root&#39;),
  );
});</code></pre>
<p>Let's create your <code>Root</code> component right in your entry file! Your <code>Root</code> component will take care of applying your <code>BrowserRouter</code> to the application. Applying the <code>BrowserRouter</code> to your <code>Root</code> component allows all the child components rendering within <code>&lt;BrowserRouter&gt;</code> tags to use and access the <code>Route</code>, <code>Link</code>, and <code>NavLink</code> components within the <code>react-router-dom</code> package.</p>
<pre><code>const Root = () =&gt; (
  // TODO: Apply BrowserRouter
  // TODO: Render rainbow
);</code></pre>
<p>Install the <code>react-router-dom</code> package:</p>
<pre><code>npm install react-router-dom@^5.0.0</code></pre>
<p>Now import <code>BrowserRouter</code> from the <code>react-router-dom</code> package, like so:</p>
<pre><code>import { BrowserRouter } from &#39;react-router-dom&#39;;</code></pre>
<p>You're going to be rendering a lot of components, so let's keep your <code>src</code> directory organized by creating a <code>components</code> directory within. Within your new <code>./src/components</code> directory, create a <code>Rainbow.js</code> file for your <code>Rainbow</code> component with the following code:</p>
<pre><code>// ./src/components/Rainbow.js
import React from &#39;react&#39;;
import { Route, Link, NavLink } from &#39;react-router-dom&#39;;

const Rainbow = () =&gt; (
&lt;div&gt;
&lt;h1&gt;Rainbow Router!&lt;/h1&gt;
{/_ Your links should go here _/}

    &lt;div id=&quot;rainbow&quot;&gt;
      {/* Your routes should go here */}
    &lt;/div&gt;

&lt;/div&gt;
);

export default Rainbow;</code></pre>

<p>Your <code>Rainbow</code> component will act as the home page or default path (<code>/</code>) of your application. Import the <code>Rainbow</code> component into your entry file and have your <code>Root</code> component render <code>&lt;Rainbow /&gt;</code> wrapped within <code>&lt;BrowserRouter&gt;</code> tags, like so:</p>
<pre><code>const Root = () =&gt; (
  &lt;BrowserRouter&gt;
    &lt;Rainbow /&gt;
  &lt;/BrowserRouter&gt;
);</code></pre>
<p>Within your <code>Rainbow</code> component, you'll be rendering <code>&lt;NavLink&gt;</code> and <code>&lt;Route&gt;</code> components to add different navigation paths to different components. Let's create all the components you will render!</p>
<p>Create files for the following components in your <code>./src/components</code> directory:</p>
<ul>
<li><span id="1c8e"><code>Red</code></span></li>
<li><span id="a8dd"><code>Blue</code></span></li>
<li><span id="6ca3"><code>Green</code></span></li>
<li><span id="8e44"><code>Indigo</code></span></li>
<li><span id="f8f2"><code>Orange</code></span></li>
<li><span id="0f47"><code>Violet</code></span></li>
<li><span id="8a89"><code>Yellow</code></span></li>
</ul>
<p>Your <code>Red</code> and <code>Blue</code> components will look something like this:</p>
<pre><code>import React from &#39;react&#39;;
import { Route, Link, NavLink } from &#39;react-router-dom&#39;;

const Color = () =&gt; (
&lt;div&gt;
&lt;h2 className=&quot;color&quot;&gt;Color&lt;/h2&gt;
{/_ Links here _/}

    {/* Routes here */}

&lt;/div&gt;
);

export default Color;</code></pre>

<p>Your <code>Green</code>, <code>Indigo</code>, <code>Orange</code>, <code>Violet</code>, and <code>Yellow</code> components will look something like this:</p>
<pre><code>import React from &#39;react&#39;;

const Color = () =&gt; (
&lt;div&gt;
&lt;h3 className=&quot;color&quot;&gt;Color&lt;/h3&gt;
&lt;/div&gt;
);

export default Color;</code></pre>

<p>Now start your server and verify you can see the "Rainbow Router!" header from your <code>Rainbow</code> component. Currently there is no functionality. Let's fix that!</p>
<h3 id="phase-1-routes">Phase 1: Routes</h3>
<p>As a reminder, wrapping the <code>Rainbow</code> component in <code>&lt;BrowserRouter&gt;</code> tags makes the router available to all descendent React Router components. Now open the <code>Rainbow.js</code> file. You're going to render some of your color components from here. Ultimately you want your routes to look like this.</p>
<p>URLComponents<code>/Rainbow/redRainbow -&gt; Red/red/orangeRainbow -&gt; Red -&gt; Orange/red/yellowRainbow -&gt; Red -&gt; Yellow/greenRainbow -&gt; Green/blueRainbow -&gt; Blue/blue/indigoRainbow -&gt; Blue -&gt; Indigo/violetRainbow -&gt; Violet</code></p>
<p>This means that the <code>Red</code>, <code>Green</code>, <code>Blue</code>, and <code>Violet</code> components need to render in the <code>Rainbow</code> component, but only when you are at the corresponding URL. You'll do this with <code>Route</code> components. Begin by importing the <code>Red</code>, <code>Green</code>, <code>Blue</code>, and <code>Violet</code> components into your <code>Rainbow.js</code> file. Then add the necessary <code>Route</code> components inside the <code>div</code> with <code>id="rainbow"</code> in the <code>Rainbow</code> component. For example to render the <code>Red</code> component with the <code>/red</code> path, you would use the following <code>Route</code> component:</p>
<pre><code>&lt;Route path=&quot;/red&quot; component={Red} /&gt;</code></pre>
<p>Test that your code works! Manually type in each URL you just created, and you should see the color component pop up. Remember, these are React Routes, so the paths you created will come after the <code>/</code>. For example, your default rainbow route will look like <code>http://localhost:3000/</code> while your red route will look like <code>http://localhost:3000/red</code><a href="http://localhost:3000/red." class="markup--anchor markup--p-anchor">.</a></p>
<p>You want to nest the <code>Orange</code> and <code>Yellow</code> components inside the <code>Red</code> component, and the <code>Indigo</code> component inside the <code>Blue</code> component. Remember to import your components to use them in a <code>Route</code> tag. You'll have to go add the corresponding <code>Route</code> tags to the <code>Red.js</code> and <code>Blue.js</code> files. Make sure to use the correct nested paths, such as <code>"/red/orange"</code> for the orange <code>Route</code>.</p>
<h3 id="phase-2-links">Phase 2: Links</h3>
<p>Manually navigating to our newly created routes is tiresome, so let's add functionality to take care of this process for us. React Router provides the <code>Link</code> and <code>NavLink</code> components for this purpose.</p>
<p>Add <code>Link</code>s to the paths <code>/red</code>, <code>/green</code>, <code>/blue</code>, and <code>/violet</code> in the <code>Rainbow</code> component. For example, your red link should look like</p>
<pre><code>&lt;Link to=&quot;/red&quot;&gt;Red&lt;/NavLink&gt;</code></pre>
<p>When you are at <code>blue</code> you want to be able to get to <code>/blue/indigo</code>, and then back to <code>/blue</code>. Add the corresponding <code>Link</code>s to the <code>Blue</code> component like this:</p>
<pre><code>&lt;Link to=&#39;/blue&#39; &gt;Blue only&lt;/Link&gt;
&lt;Link to=&#39;/blue/indigo&#39; &gt;Add indigo&lt;/Link&gt;</code></pre>
<p>Similarly, add <code>Link</code>s to <code>/red</code>, <code>/red/orange</code> and <code>/red/yellow</code> to the <code>Red</code> component. Test all your links. Navigation is so much easier now!</p>
<h3 id="phase-3-navlinks">Phase 3: NavLinks</h3>
<p>It would be nice if our links gave us some indication of which route you were at. Fortunately, React Router has a special component for that very purpose: <code>NavLink</code>. NavLinks get an extra CSS class when their <code>to</code> prop matches the current URL. By default this class is called <code>active</code>.</p>
<p>Go ahead and switch all your <code>Link</code>s to <code>NavLink</code>s. If you open the app you won't see any change yet. That's because you haven't added any special styling to the <code>active</code> class. Go ahead and open the <code>index.css</code> file. Create an <code>.active</code> class and add the line <code>font-weight: 700</code>. Now your active links will be bold. Isn't that nice!</p>
<p>The only problem is that now the <code>Blue only</code> link is active even when the path is <code>/blue/indigo</code>. That doesn't make a lot of sense. Let's add the <code>exact</code> flag to that link so it will only be active when its <code>to</code> exactly matches the current path. Now it should look like:</p>
<pre><code>&lt;NavLink exact to=&quot;/blue&quot;&gt;
  Blue only
&lt;/NavLink&gt;</code></pre>
<p>Do the same for the <code>Red only</code> link. Everything should be working now.</p>
<h3 id="phase-4-changing-navlinks-active-class">Phase 4 — Changing NavLink's Active Class</h3>
<p>You've already set up <code>NavLink</code> to bold the link text using the <code>.active</code> class in <code>src/index.css</code>. But what if you wanted this class to be something else? For instance, what if you want your main color links (Red, Green, Blue, Violet) to be styled differently when active than your sub-route links (Red Only, Add Orange, Add Yellow, etc.).</p>
<p>You can set the class that React Router sets to an active <code>NavLink</code> by adding the <code>activeClassName</code> prop.</p>
<p>For instance, when we are at a route matching the below <code>NavLink</code>'s <code>to</code> prop, the component will have a class of <code>.parent-active</code> applied:</p>
<pre><code>&lt;NavLink to=&quot;/blue&quot; activeClassName=&quot;parent-active&quot; &gt;
  Blue
&lt;/NavLink&gt;</code></pre>
<p>This allows much more flexibility to style an active <code>NavLink</code>!</p>
<p>Using the example above, add an <code>activeClassName</code> prop to each of your <code>NavLink</code>s in <code>src/components/Rainbow.js</code>. Now, add some CSS styling for that class in your <code>src/index.css</code> to distinguish your main and your sub-route links.</p>
<p>Compare your work to the solution and make sure the behavior is the same. Time to celebrate! ✨ 🌈 ✨</p>
<p>You can also learn more about using the React Router at <a href="https://reacttraining.com/react-router/web/guides/quick-start" class="markup--anchor markup--p-anchor">reacttraining.com</a>!</p>
<hr />
<h3 id="exploring-react-builds-project">Exploring React Builds Project</h3>
<p>In this project, you'll use Create React App to create a simple React application. You'll experiment with some of the features that Create React App provides and deploy a production build of your application to a standalone Express application.</p>
<h3 id="phase-0-setup-1">Phase 0: Setup</h3>
<p>Begin by using the <a href="https://github.com/facebook/create-react-app" class="markup--anchor markup--p-anchor">create-react-app</a> package to create a React application:</p>
<pre><code>npx create-react-app exploring-react-builds --template @appacademy/simple</code></pre>
<blockquote>
<p><em>Remember that using the</em> <code>create-react-app</code> <em>command initializes your project as a Git repository. If you use the</em> <code>ls -a</code> <em>to view the hidden files in your project, you'll see the </em><code>.git</code> <em>file.</em></p>
</blockquote>
<p>Update the <code>App</code> component:</p>
<ul>
<li><span id="9186">Wrap the <code>&lt;h1&gt;</code> element with a <code>&lt;div&gt;</code> element; and</span></li>
<li><span id="5e97">Change the <code>&lt;h1&gt;</code> element content to something like "Exploring React Builds".</span></li>
</ul>
<!-- -->
<pre><code>// ./src/App.js

import React from &#39;react&#39;;

function App() {
return (
&lt;div&gt;
&lt;h1&gt;Exploring React Builds&lt;/h1&gt;
&lt;/div&gt;
);
}

export default App;</code></pre>

<h3 id="phase-1-using-css-modules">Phase 1: Using CSS modules</h3>
<p>You've already seen an example of using the <code>import</code> keyword to import a stylesheet into a module so that it'll be included in your application build. That's the technique being used to include the global <code>index.css</code> stylesheet:</p>
<pre><code>// ./src/index.js

import React from &#39;react&#39;;
import ReactDOM from &#39;react-dom&#39;;
import &#39;./index.css&#39;;
import App from &#39;./App&#39;;

ReactDOM.render(
&lt;React.StrictMode&gt;
&lt;App /&gt;
&lt;/React.StrictMode&gt;,
document.getElementById(&#39;root&#39;)
);</code></pre>

<p>You can also leverage <a href="https://github.com/css-modules/css-modules" class="markup--anchor markup--p-anchor">CSS modules</a> in your Create React App projects. CSS Modules scope stylesheet class names so that they are unique to a specific React component. This allows you to create class names without having to worry if they might collide with class names used in another component.</p>
<p>Add a new <code>css-modules</code> folder to the <code>src</code> folder. Within that folder, add the following files:</p>
<ul>
<li><span id="2912"><code>HeadingA.js</code></span></li>
<li><span id="3aa3"><code>HeadingA.module.css</code></span></li>
<li><span id="2ea3"><code>HeadingB.js</code></span></li>
<li><span id="ca2b"><code>HeadingB.module.css</code></span></li>
</ul>
<p>Then update the contents of each file to the following:</p>
<pre><code>// ./src/css-modules/HeadingA.js

import React from &#39;react&#39;;
import styles from &#39;./HeadingA.module.css&#39;;

function HeadingA() {
return (
&lt;h1 className={styles.heading}&gt;Heading A&lt;/h1&gt;
);
}

export default HeadingA;

/_ ./src/css-modules/HeadingA.module.css _/

.heading {
color: green;
}

// ./src/css-modules/HeadingB.js

import React from &#39;react&#39;;
import styles from &#39;./HeadingB.module.css&#39;;

function HeadingB() {
return (
&lt;h1 className={styles.heading}&gt;Heading B&lt;/h1&gt;
);
}

export default HeadingB;

/_ ./src/css-modules/HeadingB.module.css _/

.heading {
color: red;
}</code></pre>

<p>Notice how the <code>.heading</code> CSS class name is being used within each component to set the color of the <code>&lt;h1&gt;</code> element. For the <code>HeadingA</code> component, the color is <code>green</code>, and for the <code>HeadingB</code> component, the color is <code>red</code>. Using the file naming convention <code>[name].module.css</code> let's Create React App know that we want these stylesheets to be processed as CSS Modules. Using CSS Modules allows the <code>.heading</code> class name to be reused across components without any issue.</p>
<p>To see this feature in action, update your <code>App</code> component to render both of your new components:</p>
<pre><code>import React from &#39;react&#39;;
import HeadingA from &#39;./css-modules/HeadingA&#39;;
import HeadingB from &#39;./css-modules/HeadingB&#39;;

function App() {
return (
&lt;div&gt;
&lt;h1&gt;Exploring React Builds&lt;/h1&gt;
&lt;HeadingA /&gt;
&lt;HeadingB /&gt;
&lt;/div&gt;
);
}

export default App;</code></pre>

<p>Then run your application (<code>npm start</code>) to see "Heading A" and "Heading B" displayed respectively in green and red. If you use the browser's developer tools to inspect "Heading A", you'll see that the <code>.heading</code> class name has been modified so that it's unique to the <code>HeadingA</code> component:</p>
<p>CSS Modules is an example of how a front-end build process can be used to modify code to enable a feature that's not natively supported by browsers.</p>
<h3 id="phase-2-using-an-image-in-a-component">Phase 2: Using an image in a component</h3>
<p>Create React App configures webpack with support for loading images (as well as CSS, fonts, and other file types). What this means, for you as the developer, is that you can add an image file to your project, import it directly into a module, and render it in a React component.</p>
<p>Download any image of off the Web or <a href="https://appacademy-open-assets.s3-us-west-1.amazonaws.com/Modular-Curriculum/content/react-redux/topics/react-builds/assets/react-builds-cat.png" class="markup--anchor markup--p-anchor">click here</a> to download the below image.</p>
<figure>
<img src="https://cdn-images-1.medium.com/max/800/0*233dNJ6vfgAmEVCD" class="graf-image" />
</figure>
<p>Then within the <code>src</code> folder add a new folder named <code>image</code>. Within that folder add a new component file named <code>Image.js</code>. Also add your downloaded image file to the <code>image</code> folder (so it's a sibling to the <code>Image.js</code> file).</p>
<p>Update the contents of the <code>Image.js</code> file to this:</p>
<pre><code>// ./src/image/Image.js

import React from &#39;react&#39;;
import cat from &#39;./react-builds-cat.png&#39;;

console.log(cat); // /static/media/react-builds-cat.45f7f4d2.png

function Image() {
// Import result is the URL of your image.
return &lt;img src={cat} alt=&quot;images/images/Cat&quot; /&gt;;
}

export default Image;</code></pre>

<p>You can import an image into a component using the <code>import</code> keyword. This tells webpack to include the image in the build. Notice that when you import an image into a module, you'll get a path to the image's location within the build. You can use this path to set the <code>src</code> attribute on an <code>&lt;img&gt;</code> element.</p>
<blockquote>
<p><em>Be sure to update the image</em> <code>import</code> <em>statement to the correct file name if you're using your own image!</em></p>
</blockquote>
<p>Now update the <code>App</code> component to import and render the <code>Image</code> component:</p>
<pre><code>// ./src/App.js

import React from &#39;react&#39;;
import HeadingA from &#39;./css-modules/HeadingA&#39;;
import HeadingB from &#39;./css-modules/HeadingB&#39;;
import Image from &#39;./image/Image&#39;;

function App() {
return (
&lt;div&gt;
&lt;h1&gt;Exploring React Builds&lt;/h1&gt;
&lt;HeadingA /&gt;
&lt;HeadingB /&gt;
&lt;Image /&gt;
&lt;/div&gt;
);
}

export default App;</code></pre>

<p>If you run your application (<code>npm start</code>) you'll see your image displayed on the page! You can also open your browser's developer tools and view the "Sources" for the current page. If you can expand the <code>localhost:3000</code> &gt; <code>static</code> &gt; <code>media</code> node on the left, you can see the image file that webpack copied to your build.</p>
<h3 id="images-in-stylesheets">Images in stylesheets</h3>
<p>You can also reference images in your CSS files too. Add a CSS file named <code>Image.css</code> to the <code>./src/image</code> folder and update its contents to this:</p>
<pre><code>/* ./src/image/Image.css */

.cat {
background-image: url(./react-builds-cat.png);
width: 400px;
height: 400px;
}</code></pre>

<p>Then update the <code>Image</code> component to this:</p>
<pre><code>// ./src/image/Image.js

import React from &#39;react&#39;;
import &#39;./Image.css&#39;;
import cat from &#39;./react-builds-cat.png&#39;;

console.log(cat); // /static/media/react-builds-cat.45f7f4d2.png

function Image() {
return (
&lt;div&gt;
{/_ Import result is the URL of your image. _/}
&lt;img src={cat} alt=&quot;Cat&quot; /&gt;
&lt;div className=&#39;cat&#39;&gt;&lt;/div&gt;
&lt;/div&gt;
);
}

export default Image;</code></pre>

<p>Now you'll see the image displayed twice on the page!</p>
<h3 id="phase-3-updating-the-supported-browsers-and-its-affect-on-code-transpilation">Phase 3: Updating the supported browsers (and its affect on code transpilation)</h3>
<p>Earlier you learned about the <code>browerslist</code> setting in the <code>package.json</code> file and now adjusting these targets affect how your code will be transpiled:</p>
<pre><code>{
  &quot;browserslist&quot;: {
    &quot;production&quot;: [
      &quot;&gt;0.2%&quot;,
      &quot;not dead&quot;,
      &quot;not op_mini all&quot;
    ],
    &quot;development&quot;: [
      &quot;last 1 chrome version&quot;,
      &quot;last 1 firefox version&quot;,
      &quot;last 1 safari version&quot;
    ]
  }
}</code></pre>
<p>The <code>production</code> list specifies the browsers to target when creating a production build and the <code>development</code> list specifics the browsers to target when running the application using <code>npm start</code>. Currently, you're targeting relatively recent versions of the major browsers when creating a development build. Targeting older browser versions results in your code being transpiled to an older version of JavaScript.</p>
<p>To experiment with this configuration option, let's add a class component to the project. Add a new folder named <code>class-component</code> to the <code>src</code> folder. Within that folder, add a file named <code>ClassComponent.js</code> containing the following code:</p>
<pre><code>// ./src/class-component/ClassComponent.js

import React from &#39;react&#39;;

class ClassComponent extends React.Component {
render() {
return (
&lt;h1&gt;Class Component&lt;/h1&gt;
);
}
}

export default ClassComponent;</code></pre>

<p>Don't forget to update your <code>App</code> component to render the new component:</p>
<pre><code>// ./src/App.js

import React from &#39;react&#39;;
import HeadingA from &#39;./css-modules/HeadingA&#39;;
import HeadingB from &#39;./css-modules/HeadingB&#39;;
import Image from &#39;./image/Image&#39;;
import ClassComponent from &#39;./class-component/ClassComponent&#39;;

function App() {
return (
&lt;div&gt;
&lt;h1&gt;Exploring React Builds&lt;/h1&gt;
&lt;HeadingA /&gt;
&lt;HeadingB /&gt;
&lt;Image /&gt;
&lt;ClassComponent /&gt;
&lt;/div&gt;
);
}

export default App;</code></pre>

<p>Now run your application using <code>npm start</code>. Open your browser's developer tools and view the "Sources" for the current page. Expand the <code>localhost:3000</code> &gt; <code>static</code> &gt; <code>js</code> node on the left and select the <code>main.chunk.js</code> file. Press <code>CMD+F</code> on macOS or <code>CTRL+F</code> on Windows to search the file for "Class Component". Here's what the transpiled code looks like for the <code>ClassComponent</code> class:</p>
<pre><code>class ClassComponent extends react__WEBPACK_IMPORTED_MODULE_0___default.a.Component {
  render() {
    return /*#__PURE__*/react__WEBPACK_IMPORTED_MODULE_0___default.a.createElement(&quot;h1&quot;, {
      __self: this,
      __source: {
        fileName: _jsxFileName,
        lineNumber: 7,
        columnNumber: 7
      }
    }, &quot;Class Component&quot;);
  }
}</code></pre>
<blockquote>
<p><em>Have you wondered yet why you need to use the developer tools to view the bundles generated by Create React App? Remember that when you run</em> <code>npm start</code><em>, Create React App builds your application using</em> <code>webpack-dev-server</code><em>. To keep things as performant as possible, the bundles generated by</em> <code>webpack-dev-server</code> <em>are stored in memory instead of writing them to the file system.</em></p>
</blockquote>
<p>The JSX in the component's <code>render</code> method has been converted to JavaScript but the <code>ClassComponent</code> ES2015 class is left alone. This makes sense though as JSX isn't natively supported by any browser while ES2015 classes have been natively supported by browsers for awhile now.</p>
<p>But what if you need to target a version of a browser that doesn't support ES2015 classes? You can use the <a href="https://caniuse.com/#feat=es6-class" class="markup--anchor markup--p-anchor">"Can I use…"</a> website to see when browsers started supporting ES2105 (or ES6) classes. Starting with version 49, Chrome natively supported classes. But imagine that you need to support Chrome going back to version 30, a version of Chrome that doesn't support classes.</p>
<p>Change the <code>browserslist.development</code> property in the <code>package.json</code> file to this:</p>
<pre><code>{
  &quot;browserslist&quot;: {
    &quot;production&quot;: [
      &quot;&gt;0.2%&quot;,
      &quot;not dead&quot;,
      &quot;not op_mini all&quot;
    ],
    &quot;development&quot;: [
      &quot;chrome &gt;= 30&quot;,
      &quot;last 1 firefox version&quot;,
      &quot;last 1 safari version&quot;
    ]
  }
}</code></pre>
<p>The query <code>chrome &gt;= 30</code> specifies that you want to target Chrome version 30 or newer.</p>
<blockquote>
<p><em>The</em> <a href="https://browserl.ist/" class="markup--anchor markup--blockquote-anchor"><em>browserl.ist</em></a> <em>website can be used to see the browsers supported by your configured</em> <code>browserslist</code><em>.</em></p>
</blockquote>
<p>Stop your application if it's currently running. Delete the <code>./node_modules/.cache</code> folder and run <code>npm start</code> again. Then view the <code>main.chunk.js</code> bundle again in the developer tools:</p>
<figure>
<img src="https://cdn-images-1.medium.com/max/800/0*TKBUkpbL5aSm5PTQ" class="graf-image" />
</figure>
<p>Now your ES2015 class component is being converted to a constructor function! Here's the transpiled code for reference:</p>
<pre><code>var ClassComponent = /*#__PURE__*/function (_React$Component) {
  Object(_Users_bryanguner_Documents_GitHub_Modular_Curriculum_content_react_redux_topics_react_builds_projects_exploring_react_builds_solution_node_modules_babel_preset_react_app_node_modules_babel_runtime_helpers_esm_inherits__WEBPACK_IMPORTED_MODULE_2__[&quot;default&quot;])(ClassComponent, _React$Component);

var \_super = Object(\_Users_bryanguner_Documents_GitHub_Modular_Curriculum_content_react_redux_topics_react_builds_projects_exploring_react_builds_solution_node_modules_babel_preset_react_app_node_modules_babel_runtime_helpers_esm_createSuper**WEBPACK_IMPORTED_MODULE_3**[&quot;default&quot;])(ClassComponent);

function ClassComponent() {
Object(\_Users_bryanguner_Documents_GitHub_Modular_Curriculum_content_react_redux_topics_react_builds_projects_exploring_react_builds_solution_node_modules_babel_preset_react_app_node_modules_babel_runtime_helpers_esm_classCallCheck**WEBPACK_IMPORTED_MODULE_0**[&quot;default&quot;])(this, ClassComponent);

    return _super.apply(this, arguments);

}

Object(\_Users_bryanguner_Documents_GitHub_Modular_Curriculum_content_react_redux_topics_react_builds_projects_exploring_react_builds_solution_node_modules_babel_preset_react_app_node_modules_babel_runtime_helpers_esm_createClass**WEBPACK_IMPORTED_MODULE_1**[&quot;default&quot;])(ClassComponent, [{
key: &quot;render&quot;,
value: function render() {
return /*#__PURE__*/react__WEBPACK_IMPORTED_MODULE_4___default.a.createElement(&quot;h1&quot;, {
__self: this,
__source: {
fileName: _jsxFileName,
lineNumber: 7,
columnNumber: 7
}
}, &quot;Class Component&quot;);
}
}]);

return ClassComponent;
}(react**WEBPACK*IMPORTED_MODULE_4***default.a.Component);</code></pre>

<p>Luckily it's very rare that you'll need to read the code in your generated bundles. webpack, by default, is configured to generate sourcemaps. Sourcemaps are a mapping of the code in a generated file, like a bundle file, to the original source code. This gives you access to your original source code in the browser's developer tools:</p>
<p>You can even set a breakpoint in your source within the developer tools to stop execution on a specific line of code!</p>
<h3 id="phase-4-adding-environment-variables">Phase 4: Adding environment variables</h3>
<p>Earlier you learned that Create React App supports defining environment variables in an <code>.env</code> file. This gives you a convenient way to avoid hard coding values that vary across environments.</p>
<p>Let's experiment with this feature so that you can see how the Create React App build process embeds environment variables into your HTML, CSS, and JavaScript bundles.</p>
<p>Add an <code>.env</code> file to the root of your Create React App project. Define an environment variable named <code>REACT_APP_TITLE</code>:</p>
<pre><code>REACT_APP_TITLE=Exploring React Builds</code></pre>
<p>Remember that environment variables need to be prefixed with <code>REACT_APP_</code> for Create React App to process them. After defining your environment variable, you can refer to it within JSX using an expression and <code>process.env</code>:</p>
<pre><code>// ./src/App.js

import React from &#39;react&#39;;
import HeadingA from &#39;./css-modules/HeadingA&#39;;
import HeadingB from &#39;./css-modules/HeadingB&#39;;
import Image from &#39;./image/Image&#39;;
import ClassComponent from &#39;./class-component/ClassComponent&#39;;

function App() {
return (
&lt;div&gt;
&lt;h1&gt;{process.env.REACT_APP_TITLE}&lt;/h1&gt;
&lt;HeadingA /&gt;
&lt;HeadingB /&gt;
&lt;Image /&gt;
&lt;ClassComponent /&gt;
&lt;/div&gt;
);
}

export default App;</code></pre>

<p>Environment variables can also be referred to in regular JavaScript code:</p>
<pre><code>console.log(process.env.REACT_APP_TITLE);</code></pre>
<p>You can also reference environment variables in your <code>./public/index.html</code> file like this:</p>
<pre><code>&lt;!DOCTYPE html&gt;
&lt;html lang=&quot;en&quot;&gt;
  &lt;head&gt;
    &lt;meta charset=&quot;utf-8&quot; /&gt;
    &lt;title&gt;%REACT_APP_TITLE%&lt;/title&gt;
  &lt;/head&gt;
  &lt;body&gt;
    &lt;div id=&quot;root&quot;&gt;&lt;/div&gt;
  &lt;/body&gt;
&lt;/html&gt;</code></pre>
<p>Run your application again using <code>npm start</code>. Open your browser's developer tools and view the "Sources" for the current page. Expand the <code>localhost:3000</code> node on the left and select <code>(index)</code>. Notice that the text <code>%REACT_APP_TITLE%</code> within the <code>&lt;title&gt;</code> element has been converted to the text literal <code>Exploring React Builds</code>:</p>
<p>If you expand the <code>localhost:3000</code> &gt; <code>static</code> &gt; <code>js</code> node on the left and select the <code>main.chunk.js</code> file, you can see how the <code>App</code> component's JSX has been converted to JavaScript:</p>
<p>Here's a closer look at the relevant <code>React.createElement</code> method call:</p>
<pre><code>/*#__PURE__*/react__WEBPACK_IMPORTED_MODULE_0___default.a.createElement(&quot;h1&quot;, {
    __self: this,
    __source: {
      fileName: _jsxFileName,
      lineNumber: 10,
      columnNumber: 7
    }
  }, &quot;Exploring React Builds&quot;)</code></pre>
<p>Again, notice how the environment variable has been replaced with a text literal. This has important security implications for you to consider. Because environment variables are embedded into your HTML, CSS, and JavaScript bundles during the build process, it's <em>very important</em> to not store any secrets, like API keys, in your environment variables. Remember, anyone can view your bundled code in the browser by inspecting your files!</p>
<h3 id="phase-5-deploying-a-production-build">Phase 5: Deploying a production build</h3>
<p>In the last phase of this project, let's add routing to the React application, create a production build, and deploy the build to an Express application!</p>
<h3 id="adding-routing">Adding routing</h3>
<p>To add React Router to the application, start by installing the <code>react-router-dom</code> npm package:</p>
<pre><code>npm install react-router-dom@^5.0.0</code></pre>
<p>Then update the <code>App</code> component to this code:</p>
<pre><code>// ./src/App.js

import React from &#39;react&#39;;
import {
BrowserRouter,
Switch,
Route,
Link
} from &#39;react-router-dom&#39;;
import HeadingA from &#39;./css-modules/HeadingA&#39;;
import HeadingB from &#39;./css-modules/HeadingB&#39;;
import Image from &#39;./image/Image&#39;;
import ClassComponent from &#39;./class-component/ClassComponent&#39;;

function App() {
return (
&lt;BrowserRouter&gt;
&lt;div&gt;
&lt;h1&gt;{process.env.REACT_APP_TITLE}&lt;/h1&gt;
&lt;nav&gt;
&lt;ul&gt;
&lt;li&gt;
&lt;Link to=&quot;/&quot;&gt;Home&lt;/Link&gt;
&lt;/li&gt;
&lt;li&gt;
&lt;Link to=&quot;/image&quot;&gt;Image&lt;/Link&gt;
&lt;/li&gt;
&lt;li&gt;
&lt;Link to=&quot;/class-component&quot;&gt;Class Component&lt;/Link&gt;
&lt;/li&gt;
&lt;/ul&gt;
&lt;/nav&gt;
&lt;Switch&gt;
&lt;Route path=&quot;/image&quot;&gt;
&lt;Image /&gt;
&lt;/Route&gt;
&lt;Route path=&quot;/class-component&quot;&gt;
&lt;ClassComponent /&gt;
&lt;/Route&gt;
&lt;Route path=&quot;/&quot;&gt;
&lt;HeadingA /&gt;
&lt;HeadingB /&gt;
&lt;/Route&gt;
&lt;/Switch&gt;
&lt;/div&gt;
&lt;/BrowserRouter&gt;
);
}

export default App;</code></pre>

<p>Be sure to run and test your application to ensure that the defined routes work as expected:</p>
<ul>
<li><span id="151a"><code>/</code> - Should display the <code>HeadingA</code> and <code>HeadingB</code> components;</span></li>
<li><span id="1e2b"><code>/image</code> - Should display the <code>Image</code> component; and</span></li>
<li><span id="7f3a"><code>/class-component</code> - Should display the <code>ClassComponent</code> component.</span></li>
</ul>
<h3 id="creating-a-production-build-1">Creating a production build</h3>
<p>To create a production build, run the command <code>npm run build</code> from the root of your project. The output in the terminal should look something like this:</p>
<pre><code>&gt; solution@0.1.0 build [absolute path to your project]
&gt; react-scripts build

Creating an optimized production build...
Compiled successfully.

File sizes after gzip:

47.83 KB build/static/js/2.722c16c4.chunk.js
773 B build/static/js/runtime-main.b7d1e5ee.js
745 B build/static/js/main.12299197.chunk.js
197 B build/static/css/main.e9a0d1f8.chunk.css

The project was built assuming it is hosted at /.
You can control this with the homepage field in your package.json.

The build folder is ready to be deployed.
You may serve it with a static server:

npm install -g serve
serve -s build

Find out more about deployment here:

bit.ly/CRA-deploy</code></pre>

<p>Ignore the comments about using <code>serve</code> to deploy your application (i.e. <code>npm install -g serve</code> and <code>serve -s build</code>). In the next step, you'll create a simple Express application to server your React application.</p>
<h3 id="serving-a-react-application-using-express">Serving a React application using Express</h3>
<p>Create a new folder for your Express application outside of the Create React App project folder.</p>
<blockquote>
<p><em>For example, from the root of your project, use</em> <code>cd ..</code> <em>to go up a level and then create a new folder named</em> <code>express-server</code> <em>by running the command</em> <code>mkdir express-server</code><em>. This makes the</em> <code>express-server</code> <em>folder a sibling to your Create React App project folder.</em></p>
</blockquote>
<p>Browse into the <code>express-server</code> folder and initialize it to use npm (i.e. <code>npm init -y</code>). Then install Express by running the command <code>npm install express@^4.0.0</code>.</p>
<p>App a file named <code>app.js</code> with the following contents:</p>
<pre><code>// ./app.js

const express = require(&#39;express&#39;);
const path = require(&#39;path&#39;);

const app = express();

app.use(express.static(path.join(\_\_dirname, &#39;public&#39;)));

app.get(&#39;\*&#39;, function(req, res) {
res.sendFile(path.join(\_\_dirname, &#39;public&#39;, &#39;index.html&#39;));
});

const port = 9000;

app.listen(port, () =&gt; console.log(`Listening on port ${port}...`));</code></pre>

<p>This simple Express application will:</p>
<ul>
<li><span id="31ba">Attempt to match incoming requests to static files located in the <code>public</code> folder; and</span></li>
<li><span id="16e6">If a matching static file isn't found, then the <code>./public/index.html</code> file will be served for all other requests.</span></li>
</ul>
<p>Now add a folder named <code>public</code> to the root of your Express project. Copy the files from the <code>build</code> folder in your Create React App project to the <code>public</code> folder in the Express application project. Then run your application using the command <code>node app.js</code>.</p>
<p>Open a browser and browse to the URL <code>http://localhost:9000/</code>. You should see your React application served from your Express application! Be sure to click the navigation links to verify that all of your configured routes work as expected.</p>
<p>Also, because you configured Express to serve the <code>./public/index.html</code> file for any request that doesn't match a static file, you can "deep link" to any of your React application's routes:</p>
<ul>
<li><span id="58e7"><a href="http://localhost:9000/image" class="markup--anchor markup--li-anchor">http://localhost:9000/image</a></span></li>
<li><span id="3fa9"><a href="http://localhost:9000/class-component" class="markup--anchor markup--li-anchor">http://localhost:9000/class-component</a></span></li>
</ul>
<p><em>More content at</em> <a href="http://plainenglish.io/" class="markup--anchor markup--p-anchor"><strong><em>plainenglish.io</em></strong></a></p>
<p>By <a href="https://medium.com/@bryanguner" class="p-author h-card">Bryan Guner</a> on <a href="https://medium.com/p/1965dcde8d4f">July 15, 2021</a>.</p>
<p><a href="https://medium.com/@bryanguner/react-in-depth-1965dcde8d4f" class="p-canonical">Canonical link</a></p>
<p>Exported from <a href="https://medium.com">Medium</a> on August 31, 2021.</p>
<h1 id="a-quick-guide-to-big-o-notation-memoization-tabulation-and-sorting-algorithms-by-example">A Quick Guide to Big-O Notation, Memoization, Tabulation, and Sorting Algorithms by Example</h1>
<p>Curating Complexity: A Guide to Big-O Notation</p>
<hr />
<h3 id="a-quick-guide-to-big-o-notation-memoization-tabulation-and-sorting-algorithms-by-example-1">A Quick Guide to Big-O Notation, Memoization, Tabulation, and Sorting Algorithms by Example</h3>
<figure>
<img src="https://cdn-images-1.medium.com/max/800/0*yjlSk3T9c2_14in1.png" class="graf-image" />
</figure>
<p><strong><em>Curating Complexity: A Guide to Big-O Notation</em></strong></p>
<p><a href="https://replit.com/@bgoonz/Medium-article-comp-complex" class="markup--anchor markup--mixtapeEmbed-anchor" title="https://replit.com/@bgoonz/Medium-article-comp-complex"><strong>Medium-article-comp-complex</strong>
<br/>

<em>A Node.js repl by bgoonz</em>replit.com</a><a href="https://replit.com/@bgoonz/Medium-article-comp-complex" class="js-mixtapeImage mixtapeImage u-ignoreBlock"></a></p>

<ul>
<li><span id="b70f">Why is looking at runtime not a reliable method of calculating time complexity?</span></li>
<li><span id="2b21">Not all computers are made equal( some may be stronger and therefore boost our runtime speed )</span></li>
<li><span id="1e1a">How many background processes ran concurrently with our program that was being tested?</span></li>
<li><span id="1cad">We also need to ask if our code remains performant if we increase the size of the input.</span></li>
<li><span id="3cb7">The real question we need to answering is: <code>How does our performance scale?</code>.</span></li>
</ul>
<h3 id="big-o-notation">big 'O' notation</h3>
<ul>
<li><span id="9b21">Big O Notation is a tool for describing the efficiency of algorithms with respect to the size of the input arguments.</span></li>
<li><span id="c0e6">Since we use mathematical functions in Big-O, there are a few big picture ideas that we'll want to keep in mind:</span></li>
<li><span id="2e86">The function should be defined by the size of the input.</span></li>
<li><span id="07b0"><code>Smaller</code> Big O is better (lower time complexity)</span></li>
<li><span id="f1b0">Big O is used to describe the worst case scenario.</span></li>
<li><span id="e11f">Big O is simplified to show only its most dominant mathematical term.</span></li>
</ul>
<h3 id="simplifying-math-terms">Simplifying Math Terms</h3>
<ul>
<li><span id="64a4">We can use the following rules to simplify the our Big O functions:</span></li>
<li><span id="a2c2"><code>Simplify Products</code> : If the function is a product of many terms, we drop the terms that don't depend on n.</span></li>
<li><span id="b058"><code>Simplify Sums</code> : If the function is a sum of many terms, we drop the non-dominant terms.</span></li>
<li><span id="eb32"><code>n</code> : size of the input</span></li>
<li><span id="c042"><code>T(f)</code> : unsimplified math function</span></li>
<li><span id="7b41"><code>O(f)</code> : simplified math function.</span></li>
</ul>
<p><code>Putting it all together</code></p>
<figure>
<img src="https://cdn-images-1.medium.com/max/800/1*TT8uuv1x3nmGUw5rvtoZ8A.png" class="graf-image" />
</figure>
<ul>
<li><span id="d18b">First we apply the product rule to drop all constants.</span></li>
<li><span id="4335">Then we apply the sum rule to select the single most dominant term.</span></li>
</ul>
<hr />
<h3 id="complexity-classes">Complexity Classes</h3>
<p>Common Complexity Classes</p>
<h4 id="there-are-7-major-classes-in-time-complexity">There are 7 major classes in Time Complexity</h4>
<figure>
<img src="https://cdn-images-1.medium.com/max/800/1*6zKhmJoHkvDbrd8jfUDf3A.png" class="graf-image" />
</figure>
<h4 id="o1-constant"><code>O(1) Constant</code></h4>
<blockquote>
<p><strong>The algorithm takes roughly the same number of steps for any input size.</strong></p>
</blockquote>
<h4 id="ologn-logarithmic"><code>O(log(n)) Logarithmic</code></h4>
<blockquote>
<p><strong>In most cases our hidden base of Logarithmic time is 2, log complexity algorithm's will typically display 'halving' the size of the input (like binary search!)</strong></p>
</blockquote>
<h4 id="on-linear"><code>O(n) Linear</code></h4>
<blockquote>
<p><strong>Linear algorithm's will access each item of the input "once".</strong></p>
</blockquote>
<h3 id="onlogn-log-linear-time"><code>O(nlog(n)) Log Linear Time</code></h3>
<blockquote>
<p><strong>Combination of linear and logarithmic behavior, we will see features from both classes.</strong></p>
</blockquote>
<blockquote>
<p>Algorithm's that are log-linear will use <strong>both recursion AND iteration.</strong></p>
</blockquote>
<h3 id="onc-polynomial"><code>O(nc) Polynomial</code></h3>
<blockquote>
<p><strong>C is a fixed constant.</strong></p>
</blockquote>
<h3 id="ocn-exponential"><code>O(c^n) Exponential</code></h3>
<blockquote>
<p><strong>C is now the number of recursive calls made in each stack frame.</strong></p>
</blockquote>
<blockquote>
<p><strong>Algorithm's with exponential time are VERY SLOW.</strong></p>
</blockquote>
<hr />
<h3 id="memoization">Memoization</h3>
<ul>
<li><span id="b3b0">Memoization : a design pattern used to reduce the overall number of calculations that can occur in algorithms that use recursive strategies to solve.</span></li>
<li><span id="2583">MZ stores the results of the sub-problems in some other data structure, so that we can avoid duplicate calculations and only 'solve' each problem once.</span></li>
<li><span id="65c9">Two features that comprise memoization:</span></li>
</ul>
<ol type="1">
<li><span id="b2d2">FUNCTION MUST BE RECURSIVE.</span></li>
<li><span id="91a3">Our additional Data Structure is usually an object (we refer to it as our memo… or sometimes cache!)</span></li>
</ol>
<figure>
<img src="https://cdn-images-1.medium.com/max/800/1*4U79jBMjU2wKE_tyYcD_3A.png" class="graf-image" />
</figure>
<figure>
<img src="https://cdn-images-1.medium.com/max/800/1*Qh42KZgcCxmVt6WrTasCVw.png" class="graf-image" />
</figure>
<h3 id="memoizing-factorial">Memoizing Factorial</h3>
<p>Our memo object is <em>mapping</em> out our arguments of factorial to it's return value.</p>
<ul>
<li><span id="854a">Keep in mind we didn't improve the speed of our algorithm.</span></li>
</ul>
<h3 id="memoizing-fibonacci">Memoizing Fibonacci</h3>
<figure>
<img src="https://cdn-images-1.medium.com/max/800/0*2XaPj7UGKZYFjYhb" class="graf-image" />
</figure>
<ul>
<li><span id="5be6">Our time complexity for Fibonacci goes from O(2^n) to O(n) after applying memoization.</span></li>
</ul>
<h3 id="the-memoization-formula">The Memoization Formula</h3>
<blockquote>
<p><em>Rules:</em></p>
</blockquote>
<ol type="1">
<li><span id="b3f0"><em>Write the unoptimized brute force recursion (make sure it works);</em></span></li>
<li><span id="b36e"><em>Add memo object as an additional argument .</em></span></li>
<li><span id="f81f"><em>Add a base case condition that returns the stored value if the function's argument is in the memo.</em></span></li>
<li><span id="1b0f"><em>Before returning the result of the recursive case, store it in the memo as a value and make the function's argument it's key.</em></span></li>
</ol>
<h4 id="things-to-remember">Things to remember</h4>
<ol type="1">
<li><span id="bc4a"><em>When solving DP problems with Memoization, it is helpful to draw out the visual tree first.</em></span></li>
<li><span id="7bb1"><em>When you notice duplicate sub-tree's that means we can memoize.</em></span></li>
</ol>
<hr />
<h3 id="tabulation">Tabulation</h3>
<h4 id="tabulation-strategy">Tabulation Strategy</h4>
<blockquote>
<p>Use When:</p>
</blockquote>
<ul>
<li><span id="f5b0"><strong>The function is iterative and not recursive.</strong></span></li>
<li><span id="015c"><em>The accompanying DS is usually an array.</em></span></li>
</ul>
<h4 id="steps-for-tabulation">Steps for tabulation</h4>
<ul>
<li><span id="8918"><em>Create a table array based off the size of the input.</em></span></li>
<li><span id="b4e7"><em>Initialize some values in the table to 'answer' the trivially small subproblem.</em></span></li>
<li><span id="072e"><em>Iterate through the array and fill in the remaining entries.</em></span></li>
<li><span id="192e"><em>Your final answer is usually the last entry in the table.</em></span></li>
</ul>
<hr />
<h3 id="memo-and-tab-demo-with-fibonacci">Memo and Tab Demo with Fibonacci</h3>
<blockquote>
<p><em>Normal Recursive Fibonacci</em></p>
</blockquote>
<pre><code>function fibonacci(n) {
  if (n &lt;= 2) return 1;
  return fibonacci(n - 1) + fibonacci(n - 2);
}</code></pre>
<blockquote>
<p><em>Memoization Fibonacci 1</em></p>
</blockquote>
<blockquote>
<p><em>Memoization Fibonacci 2</em></p>
</blockquote>
<blockquote>
<p><em>Tabulated Fibonacci</em></p>
</blockquote>
<h3 id="example-of-linear-search">Example of Linear Search</h3>
<ul>
<li><span id="84b2"><em>Worst Case Scenario: The term does not even exist in the array.</em></span></li>
<li><span id="30dc"><em>Meaning: If it doesn't exist then our for loop would run until the end therefore making our time complexity O(n).</em></span></li>
</ul>
<hr />
<h3 id="sorting-algorithms">Sorting Algorithms</h3>
<h3 id="bubble-sort">Bubble Sort</h3>
<p><code>Time Complexity</code>: Quadratic O(n^2)</p>
<ul>
<li><span id="ce1e">The inner for-loop contributes to O(n), however in a worst case scenario the while loop will need to run n times before bringing all n elements to their final resting spot.</span></li>
</ul>
<p><code>Space Complexity</code>: O(1)</p>
<ul>
<li><span id="664f">Bubble Sort will always use the same amount of memory regardless of n.</span></li>
</ul>
<figure>
<img src="https://cdn-images-1.medium.com/max/800/0*Ck9aeGY-d5tbz7dT" class="graf-image" />
</figure>
<ul>
<li><span id="4115">The first major sorting algorithm one learns in introductory programming courses.</span></li>
<li><span id="ecd4">Gives an intro on how to convert unsorted data into sorted data.</span></li>
</ul>
<blockquote>
<p>It's almost never used in production code because:</p>
</blockquote>
<ul>
<li><span id="3cb1"><em>It's not efficient</em></span></li>
<li><span id="4eac"><em>It's not commonly used</em></span></li>
<li><span id="d730"><em>There is stigma attached to it</em></span></li>
<li><span id="8da7"><code>Bubbling Up</code><em> : Term that infers that an item is in motion, moving in some direction, and has some final resting destination.</em></span></li>
<li><span id="8447"><em>Bubble sort, sorts an array of integers by bubbling the largest integer to the top.</em></span></li>
</ul>
<!-- -->
<ul>
<li><span id="dcd2"><em>Worst Case &amp; Best Case are always the same because it makes nested loops.</em></span></li>
<li><span id="9a6a"><em>Double for loops are polynomial time complexity or more specifically in this case Quadratic (Big O) of: O(n²)</em></span></li>
</ul>
<h3 id="selection-sort">Selection Sort</h3>
<p><code>Time Complexity</code>: Quadratic O(n^2)</p>
<ul>
<li><span id="646d">Our outer loop will contribute O(n) while the inner loop will contribute O(n / 2) on average. Because our loops are nested we will get O(n²);</span></li>
</ul>
<p><code>Space Complexity</code>: O(1)</p>
<ul>
<li><span id="45ae">Selection Sort will always use the same amount of memory regardless of n.</span></li>
</ul>
<figure>
<img src="https://cdn-images-1.medium.com/max/800/0*AByxtBjFrPVVYmyu" class="graf-image" />
</figure>
<ul>
<li><span id="c618">Selection sort organizes the smallest elements to the start of the array.</span></li>
</ul>
<figure>
<img src="https://cdn-images-1.medium.com/max/800/0*GeYNxlRcbt2cf0rY" class="graf-image" />
</figure>
<p>Summary of how Selection Sort should work:</p>
<ol type="1">
<li><span id="2277"><em>Set MIN to location 0</em></span></li>
<li><span id="c76c"><em>Search the minimum element in the list.</em></span></li>
<li><span id="79d3"><em>Swap with value at location Min</em></span></li>
<li><span id="4ede"><em>Increment Min to point to next element.</em></span></li>
<li><span id="a649"><em>Repeat until list is sorted.</em></span></li>
</ol>
<h3 id="insertion-sort">Insertion Sort</h3>
<p><code>Time Complexity</code>: Quadratic O(n^2)</p>
<ul>
<li><span id="95ea">Our outer loop will contribute O(n) while the inner loop will contribute O(n / 2) on average. Because our loops are nested we will get O(n²);</span></li>
</ul>
<p><code>Space Complexity</code>: O(n)</p>
<ul>
<li><span id="f6fa">Because we are creating a subArray for each element in the original input, our Space Comlexity becomes linear.</span></li>
</ul>
<figure>
<img src="https://cdn-images-1.medium.com/max/800/0*gbNU6wrszGPrfAZG" class="graf-image" />
</figure>
<h3 id="merge-sort">Merge Sort</h3>
<p><code>Time Complexity</code>: Log Linear O(nlog(n))</p>
<ul>
<li><span id="44b2">Since our array gets split in half every single time we contribute O(log(n)). The while loop contained in our helper merge function contributes O(n) therefore our time complexity is O(nlog(n)); <code>Space Complexity</code>: O(n)</span></li>
<li><span id="9a83">We are linear O(n) time because we are creating subArrays.</span></li>
</ul>
<figure>
<img src="https://cdn-images-1.medium.com/max/800/0*GeU8YwwCoK8GiSTD" class="graf-image" />
</figure>
<figure>
<img src="https://cdn-images-1.medium.com/max/800/0*IxqGb72XDVDeeiMl" class="graf-image" />
</figure>
<h3 id="example-of-merge-sort">Example of Merge Sort</h3>
<figure>
<img src="https://cdn-images-1.medium.com/max/800/0*HMCR--9niDt5zY6M" class="graf-image" />
</figure>
<ul>
<li><span id="48b4"><strong>Merge sort is O(nlog(n)) time.</strong></span></li>
<li><span id="c598"><em>We need a function for merging and a function for sorting.</em></span></li>
</ul>
<blockquote>
<p>Steps:</p>
</blockquote>
<ol type="1">
<li><span id="213f"><em>If there is only one element in the list, it is already sorted; return the array.</em></span></li>
<li><span id="6214"><em>Otherwise, divide the list recursively into two halves until it can no longer be divided.</em></span></li>
<li><span id="3cc8"><em>Merge the smallest lists into new list in a sorted order.</em></span></li>
</ol>
<h3 id="quick-sort">Quick Sort</h3>
<p><code>Time Complexity</code>: Quadratic O(n^2)</p>
<ul>
<li><span id="8e34">Even though the average time complexity O(nLog(n)), the worst case scenario is always quadratic.</span></li>
</ul>
<p><code>Space Complexity</code>: O(n)</p>
<ul>
<li><span id="626b">Our space complexity is linear O(n) because of the partition arrays we create.</span></li>
<li><span id="7e3a">QS is another Divide and Conquer strategy.</span></li>
<li><span id="233d">Some key ideas to keep in mind:</span></li>
<li><span id="1173">It is easy to sort elements of an array relative to a particular target value.</span></li>
<li><span id="8634">An array of 0 or 1 elements is already trivially sorted.</span></li>
</ul>
<figure>
<img src="https://cdn-images-1.medium.com/max/800/0*WLl_HpdBGXYx284T" class="graf-image" />
</figure>
<figure>
<img src="https://cdn-images-1.medium.com/max/800/0*-LyHJXGPTYsWLDZf" class="graf-image" />
</figure>
<h3 id="binary-search">Binary Search</h3>
<p><code>Time Complexity</code>: Log Time O(log(n))</p>
<p><code>Space Complexity</code>: O(1)</p>
<figure>
<img src="https://cdn-images-1.medium.com/max/800/0*-naVYGTXzE2Yoali" class="graf-image" />
</figure>
<p><em>Recursive Solution</em></p>
<blockquote>
<p><em>Min Max Solution</em></p>
</blockquote>
<ul>
<li><span id="6fb1"><em>Must be conducted on a sorted array.</em></span></li>
<li><span id="383b"><em>Binary search is logarithmic time, not exponential b/c n is cut down by two, not growing.</em></span></li>
<li><span id="c940"><em>Binary Search is part of Divide and Conquer.</em></span></li>
</ul>
<h3 id="insertion-sort-1">Insertion Sort</h3>
<ul>
<li><span id="26b7"><strong>Works by building a larger and larger sorted region at the left-most end of the array.</strong></span></li>
</ul>
<blockquote>
<p>Steps:</p>
</blockquote>
<ol type="1">
<li><span id="8c1f"><em>If it is the first element, and it is already sorted; return 1.</em></span></li>
<li><span id="1451"><em>Pick next element.</em></span></li>
<li><span id="0f8b"><em>Compare with all elements in the sorted sub list</em></span></li>
<li><span id="4d78"><em>Shift all the elements in the sorted sub list that is greater than the value to be sorted.</em></span></li>
<li><span id="9131"><em>Insert the value</em></span></li>
<li><span id="6c8a"><em>Repeat until list is sorted.</em></span></li>
</ol>
<h3 id="if-you-found-this-guide-helpful-feel-free-to-checkout-my-githubgists-where-i-host-similar-content-1">If you found this guide helpful feel free to checkout my GitHub/gists where I host similar content:</h3>
<p><a href="https://gist.github.com/bgoonz" class="markup--anchor markup--mixtapeEmbed-anchor" title="https://gist.github.com/bgoonz"><strong>bgoonz's gists</strong>
<br/>

<em>Instantly share code, notes, and snippets. Web Developer, Electrical Engineer JavaScript | CSS | Bootstrap | Python |…</em>gist.github.com</a><a href="https://gist.github.com/bgoonz" class="js-mixtapeImage mixtapeImage u-ignoreBlock"></a></p>

<p><a href="https://github.com/bgoonz" class="markup--anchor markup--mixtapeEmbed-anchor" title="https://github.com/bgoonz"><strong>bgoonz — Overview</strong>
<br/>

<em>Web Developer, Electrical Engineer JavaScript | CSS | Bootstrap | Python | React | Node.js | Express | Sequelize…</em>github.com</a><a href="https://github.com/bgoonz" class="js-mixtapeImage mixtapeImage u-ignoreBlock"></a></p>

<h3 id="or-checkout-my-personal-resource-site">Or Checkout my personal Resource Site:</h3>
<p><a href="https://blog2-backup.netlify.app/" class="markup--anchor markup--mixtapeEmbed-anchor" title="https://blog2-backup.netlify.app/"><strong>Web-Dev-Hub</strong>
<br/>

<em>Memoization, Tabulation, and Sorting Algorithms by Example Why is looking at runtime not a reliable method of…</em>bgoonz-blog.netlify.app</a><a href="https://blog2-backup.netlify.app/" class="js-mixtapeImage mixtapeImage u-ignoreBlock"></a></p>

<figure>
<img src="https://cdn-images-1.medium.com/max/800/1*VCmj_H9AHs41oC9Yx1hZFQ.png" class="graf-image" />
</figure>
<h3 id="discover-more">Discover More:</h3>
<p><a href="https://blog2-backup.netlify.app/" class="markup--anchor markup--mixtapeEmbed-anchor" title="https://blog2-backup.netlify.app/"><strong>Web-Dev-Hub</strong>
<br/>

<em>Memoization, Tabulation, and Sorting Algorithms by Example Why is looking at runtime not a reliable method of…</em>bgoonz-blog.netlify.app</a><a href="https://blog2-backup.netlify.app/" class="js-mixtapeImage mixtapeImage u-ignoreBlock"></a></p>

<p>By <a href="https://medium.com/@bryanguner" class="p-author h-card">Bryan Guner</a> on <a href="https://medium.com/p/803ff193c522">February 27, 2021</a>.</p>
<p><a href="https://medium.com/@bryanguner/a-quick-guide-to-big-o-notation-memoization-tabulation-and-sorting-algorithms-by-example-803ff193c522" class="p-canonical">Canonical link</a></p>
<p>Exported from <a href="https://medium.com">Medium</a> on August 31, 2021.</p>
<h1 id="a-very-quick-guide-to-calculating-big-o-computational-complexity">A Very Quick Guide To Calculating Big O Computational Complexity</h1>
<p>Big O: big picture, broad strokes, not details</p>
<hr />
<h3 id="a-very-quick-guide-to-calculating-big-o-computational-complexity-1">A Very Quick Guide To Calculating Big O Computational Complexity</h3>
<p><strong>Big O</strong>: big picture, broad strokes, not details</p>
<p>For a more complete guide… checkout :</p>
<p><a href="https://medium.com/star-gazers/a-quick-guide-to-big-o-notation-memoization-tabulation-and-sorting-algorithms-by-example-803ff193c522" class="markup--anchor markup--mixtapeEmbed-anchor" title="https://medium.com/star-gazers/a-quick-guide-to-big-o-notation-memoization-tabulation-and-sorting-algorithms-by-example-803ff193c522"><strong>A Quick Guide to Big-O Notation, Memoization, Tabulation, and Sorting Algorithms by Example</strong>
<br/>

<em>Curating Complexity: A Guide to Big-O Notation</em>medium.com</a><a href="https://medium.com/star-gazers/a-quick-guide-to-big-o-notation-memoization-tabulation-and-sorting-algorithms-by-example-803ff193c522" class="js-mixtapeImage mixtapeImage u-ignoreBlock"></a></p>

<figure>
<img src="https://cdn-images-1.medium.com/max/800/0*lte81mEvgEPYXodB.png" class="graf-image" />
</figure>
<ul>
<li><span id="28b6">way we analyze how efficient algorithms are without getting too mired in details</span></li>
<li><span id="4141">can model how much time any function will take given <code>n</code> inputs</span></li>
<li><span id="9479">interested in order of magnitude of number of the exact figure</span></li>
<li><span id="8fe1">O absorbs all fluff and n = biggest term</span></li>
<li><span id="a9c8">Big O of <code>3x^2 +x + 1</code> = <code>O(n^2)</code></span></li>
</ul>
<h3 id="time-complexity">Time Complexity</h3>
<p>no loops or exit &amp; return = O(1)</p>
<p>0 nested loops = <code>O(n)</code>
<br/>

1 nested loops = <code>O(n^2)</code>
<br/>

2 nested loops = <code>O(n^3)</code>
<br/>

3 nested loops = <code>O(n^4)</code></p>

<p><strong>recursive</strong>: as you add more terms, increase in time as you add input diminishes
<br/>

<strong>recursion</strong>: when you define something in terms of itself, a function that calls itself</p>

<ul>
<li><span id="f455">used because of ability to maintain state at diffferent levels of recursion</span></li>
<li><span id="f168">inherently carries large footprint</span></li>
<li><span id="5510">every time function called, you add call to stack</span></li>
</ul>
<p><strong>iterative</strong>: use loops instead of recursion (preferred)
<br/>

-   favor readability over performance</p>
<p><code>O(n log(n))</code> &amp; <code>O(log(n))</code>: dividing/halving</p>
<ul>
<li><span id="4f7e">if code employs recursion/divide-and-conquer strategy</span></li>
<li><span id="d1cc">what power do i need to power my base to get n</span></li>
</ul>
<h3 id="time-definitions">Time Definitions</h3>
<ul>
<li><span id="9aad"><strong>constant</strong>: does not scale with input, will take same amount of time</span></li>
<li><span id="3a19">for any input size n, constant time performs same number of operations every time</span></li>
<li><span id="bf51"><strong>logarithmic</strong>: increases number of operations it performs as logarithmic function of input size n</span></li>
<li><span id="93d5">function log n grows very slowly, so as n gets longer, number of operations the algorithm needs to perform doesn't increase very much</span></li>
<li><span id="a2cf">halving</span></li>
<li><span id="46c0"><strong>linear</strong>: increases number of operations it performs as linear function of input size n</span></li>
<li><span id="5f16">number of additional operations needed to perform grows in direct proportion to increase in input size n</span></li>
<li><span id="ab93"><strong>log-linear</strong>: increases number of operations it performs as log-linear function of input size n</span></li>
<li><span id="0459">looking over every element and doing work on each one</span></li>
<li><span id="bd8a"><strong>quadratic</strong>: increases number of operations it performs as quadratic function of input size n</span></li>
<li><span id="dc41"><strong>exponential</strong>: increases number of operations it performs as exponential function of input size n</span></li>
<li><span id="71fc">number of nested loops increases as function of n</span></li>
<li><span id="8253"><strong>polynomial</strong>: as size of input increases, runtime/space used will grow at a faster rate</span></li>
<li><span id="8827"><strong>factorial</strong>: as size of input increases, runtime/space used will grow astronomically even with relatively small inputs</span></li>
<li><span id="040c"><strong>rate of growth</strong>: how fast a function grows with input size</span></li>
</ul>
<figure>
<img src="https://cdn-images-1.medium.com/max/800/1*5t2u8n1uKhioIzZIXX2zbg.png" class="graf-image" />
</figure>
<h3 id="space-complexity">Space Complexity</h3>
<ul>
<li><span id="403b">How does the space usage scale/change as input gets very large?</span></li>
<li><span id="5f20">What auxiliary space does your algorithm use or is it in place (constant)?</span></li>
<li><span id="b207">Runtime stack space counts as part of space complexity unless told otherwise.</span></li>
</ul>
<h3 id="sorting-algorithms-1">Sorting Algorithms</h3>
<figure>
<img src="https://cdn-images-1.medium.com/max/800/1*HhXmG2cNdg8y4ZCCQGTyuQ.png" class="graf-image" />
</figure>
<figure>
<img src="https://cdn-images-1.medium.com/max/800/1*ULeXxVCDkF73GwhsxyM_2g.png" class="graf-image" />
</figure>
<h3 id="data-structures">Data Structures</h3>
<figure>
<img src="https://cdn-images-1.medium.com/max/1200/1*hkZWlUgFyOSaLD5Uskv0tQ.png" class="graf-image" />
</figure>
<figure>
<img src="https://cdn-images-1.medium.com/max/2560/1*COjzunj0-FsMJ0d7v7Z-6g.png" class="graf-image" />
</figure>
<p>For similar content check out my GitHub:</p>
<p><a href="https://github.com/bgoonz" class="markup--anchor markup--mixtapeEmbed-anchor" title="https://github.com/bgoonz"><strong>bgoonz - Overview</strong>
<br/>

<em>Web Developer, Electrical Engineer https://bryanguner.medium.com/ https://portfolio42.netlify.app/…</em>github.com</a><a href="https://github.com/bgoonz" class="js-mixtapeImage mixtapeImage u-ignoreBlock"></a></p>

<p>By <a href="https://medium.com/@bryanguner" class="p-author h-card">Bryan Guner</a> on <a href="https://medium.com/p/eb1557e85fa3">May 19, 2021</a>.</p>
<p><a href="https://medium.com/@bryanguner/a-very-quick-guide-to-calculating-big-o-computational-complexity-eb1557e85fa3" class="p-canonical">Canonical link</a></p>
<p>Exported from <a href="https://medium.com">Medium</a> on August 31, 2021.</p>
<h1 id="a-list-of-all-of-my-articles-to-link-to-future-posts">A list of all of my articles to link to future posts</h1>
<p>You should probably skip this one… seriously it's just for internal use!</p>
<hr />
<h3 id="all-of-my-medium-stories">All Of My Medium Stories</h3>
<figure>
<img src="https://cdn-images-1.medium.com/max/800/1*yZ41P3YdMYMiyFPAPrzyGw.gif" class="graf-image" />
</figure>
<hr />
<h3 id="this-is-another-backup-of-all-of-them">This is another backup of all of them!</h3>
<p><a href="https://golden-lobe-519.notion.site/Medium-7b5b9bd642344d60afe3f03fe6431952" class="markup--anchor markup--mixtapeEmbed-anchor" title="https://golden-lobe-519.notion.site/Medium-7b5b9bd642344d60afe3f03fe6431952"><strong>All OF MEDIUM ARTICLES</strong>
<br/>

<em>2021-02-27_A-Quick-Guide-to-Big-O-Notation-Memoization-Tabulation-and-Sorting-Algorithms-by-Example-803ff193c522…</em>golden-lobe-519.notion.site</a><a href="https://golden-lobe-519.notion.site/Medium-7b5b9bd642344d60afe3f03fe6431952" class="js-mixtapeImage mixtapeImage u-ignoreBlock"></a></p>

<hr />
<p><a href="https://medium.com/webdevhub/notes-i-wish-i-had-when-i-started-learning-python-16ce4244be12" class="markup--anchor markup--mixtapeEmbed-anchor" title="https://medium.com/webdevhub/notes-i-wish-i-had-when-i-started-learning-python-16ce4244be12"><strong>Notes I Wish I Had When I Started Learning Python</strong>
<br/>

<em>Plus resources for learning data structures and algorithms in python at the bottom of this article!</em>medium.com</a><a href="https://medium.com/webdevhub/notes-i-wish-i-had-when-i-started-learning-python-16ce4244be12" class="js-mixtapeImage mixtapeImage u-ignoreBlock"></a></p>

<p><a href="https://bryanguner.medium.com/awesome-list-of-github-repositories-f1c433e32b17" class="markup--anchor markup--mixtapeEmbed-anchor" title="https://bryanguner.medium.com/awesome-list-of-github-repositories-f1c433e32b17"><strong>Awesome List Of Github Repositories</strong>
<br/>

<em>Platforms</em><a href="https://bryanguner.medium.com/awesome-list-of-github-repositories-f1c433e32b17" class="js-mixtapeImage mixtapeImage u-ignoreBlock"></a></p>

<p><a href="https://bryanguner.medium.com/my-personal-arsenal-of-convenience-scripts-3c7869fdae53" class="markup--anchor markup--mixtapeEmbed-anchor" title="https://bryanguner.medium.com/my-personal-arsenal-of-convenience-scripts-3c7869fdae53"><strong>My Personal Arsenal Of Convenience Scripts</strong>
<br/>

<em>At the bottom the following commands are listed as a markdown file and embed in this article as a github gist.</em><a href="https://bryanguner.medium.com/my-personal-arsenal-of-convenience-scripts-3c7869fdae53" class="js-mixtapeImage mixtapeImage mixtapeImage--empty u-ignoreBlock"></a></p>

<p><a href="https://bryanguner.medium.com/adding-css-to-your-html-3a17ba25ba82" class="markup--anchor markup--mixtapeEmbed-anchor" title="https://bryanguner.medium.com/adding-css-to-your-html-3a17ba25ba82"><strong>Adding CSS To Your HTML</strong>
<br/>

<em>For beginners … very picture heavy since CSS is such a visual discipline!</em><a href="https://bryanguner.medium.com/adding-css-to-your-html-3a17ba25ba82" class="js-mixtapeImage mixtapeImage u-ignoreBlock"></a></p>

<p><a href="https://bryanguner.medium.com/most-common-javascript-errors-311ea1356a3d" class="markup--anchor markup--mixtapeEmbed-anchor" title="https://bryanguner.medium.com/most-common-javascript-errors-311ea1356a3d"><strong>Most Common Javascript Errors</strong>
<br/>

<em>Written in quiz format</em><a href="https://bryanguner.medium.com/most-common-javascript-errors-311ea1356a3d" class="js-mixtapeImage mixtapeImage u-ignoreBlock"></a></p>

<p><a href="https://bryanguner.medium.com/super-simple-intro-to-react-5c78e4207b7f" class="markup--anchor markup--mixtapeEmbed-anchor" title="https://bryanguner.medium.com/super-simple-intro-to-react-5c78e4207b7f"><strong>Super Simple Intro To React</strong>
<br/>

<em>This is a basic introduction for those who feel overwhelmed by the vast microcosm that is the React ecosystem!</em><a href="https://bryanguner.medium.com/super-simple-intro-to-react-5c78e4207b7f" class="js-mixtapeImage mixtapeImage u-ignoreBlock"></a></p>

<p><a href="https://medium.com/codex/react-state-d8e0fc340714" class="markup--anchor markup--mixtapeEmbed-anchor" title="https://medium.com/codex/react-state-d8e0fc340714"><strong>React State</strong>
<br/>

<em>Demystified</em>medium.com</a><a href="https://medium.com/codex/react-state-d8e0fc340714" class="js-mixtapeImage mixtapeImage u-ignoreBlock"></a></p>

<p><a href="https://bryanguner.medium.com/awesome-web-development-youtube-video-archive-792a25839143" class="markup--anchor markup--mixtapeEmbed-anchor" title="https://bryanguner.medium.com/awesome-web-development-youtube-video-archive-792a25839143"><strong>Awesome Web Development Youtube Video Archive</strong>
<br/>

<em>This is going to be a running list of youtube videos and channels that I discover as I learn web development. It will…</em><a href="https://bryanguner.medium.com/awesome-web-development-youtube-video-archive-792a25839143" class="js-mixtapeImage mixtapeImage u-ignoreBlock"></a></p>

<p><a href="https://levelup.gitconnected.com/beginner-python-problems-solutions-dd631e9c3a9f" class="markup--anchor markup--mixtapeEmbed-anchor" title="https://levelup.gitconnected.com/beginner-python-problems-solutions-dd631e9c3a9f"><strong>Python Problems &amp; Solutions For Beginners</strong>
<br/>

<em>Introduction to python taught through example problems. Solutions are included in embedded repl.it at the bottom of…</em>levelup.gitconnected.com</a><a href="https://levelup.gitconnected.com/beginner-python-problems-solutions-dd631e9c3a9f" class="js-mixtapeImage mixtapeImage u-ignoreBlock"></a></p>

<p><a href="https://medium.com/codex/fundamental-concepts-in-javascript-8e093a665b04" class="markup--anchor markup--mixtapeEmbed-anchor" title="https://medium.com/codex/fundamental-concepts-in-javascript-8e093a665b04"><strong>Fundamental Concepts In Javascript</strong>
<br/>

<em>This is the stuff that comes up on interviews…</em>medium.com</a><a href="https://medium.com/codex/fundamental-concepts-in-javascript-8e093a665b04" class="js-mixtapeImage mixtapeImage u-ignoreBlock"></a></p>

<p><a href="https://bryanguner.medium.com/bash-proficiency-in-under-15-minutes-3ec9d4e2e65" class="markup--anchor markup--mixtapeEmbed-anchor" title="https://bryanguner.medium.com/bash-proficiency-in-under-15-minutes-3ec9d4e2e65"><strong>Bash Proficiency In Under 15 Minutes</strong>
<br/>

<em>Cheat sheet and in-depth explanations located below main article contents… The UNIX shell program interprets user…</em><a href="https://bryanguner.medium.com/bash-proficiency-in-under-15-minutes-3ec9d4e2e65" class="js-mixtapeImage mixtapeImage u-ignoreBlock"></a></p>

<p><a href="https://medium.com/analytics-vidhya/mini-review-of-sql-for-postgresql-w-node-express-f34676f3802b" class="markup--anchor markup--mixtapeEmbed-anchor" title="https://medium.com/analytics-vidhya/mini-review-of-sql-for-postgresql-w-node-express-f34676f3802b"><strong>Mini Review Of SQL For PostgreSQL W Node &amp; Express</strong>
<br/>

<em>What is a Query?</em>medium.com</a><a href="https://medium.com/analytics-vidhya/mini-review-of-sql-for-postgresql-w-node-express-f34676f3802b" class="js-mixtapeImage mixtapeImage u-ignoreBlock"></a></p>

<p><a href="https://bryanguner.medium.com/all-the-things-you-can-embed-in-a-medium-article-b03a85c65d86" class="markup--anchor markup--mixtapeEmbed-anchor" title="https://bryanguner.medium.com/all-the-things-you-can-embed-in-a-medium-article-b03a85c65d86"><strong>All The Things You Can Embed In A Medium Article</strong>
<br/>

<em>I have this innate desire to make everything available all in one place and it's usually an unnecessary waste of time……</em><a href="https://bryanguner.medium.com/all-the-things-you-can-embed-in-a-medium-article-b03a85c65d86" class="js-mixtapeImage mixtapeImage u-ignoreBlock"></a></p>

<p><a href="https://bryanguner.medium.com/front-end-behavioral-interview-bf5c079f7461" class="markup--anchor markup--mixtapeEmbed-anchor" title="https://bryanguner.medium.com/front-end-behavioral-interview-bf5c079f7461"><strong>Front End Behavioral Interview</strong>
<br/>

<em>Web Developer Job Interview Questions</em><a href="https://bryanguner.medium.com/front-end-behavioral-interview-bf5c079f7461" class="js-mixtapeImage mixtapeImage u-ignoreBlock"></a></p>

<p><a href="https://medium.com/codex/prerequisites-to-writing-express-apis-75e3267b284a" class="markup--anchor markup--mixtapeEmbed-anchor" title="https://medium.com/codex/prerequisites-to-writing-express-apis-75e3267b284a"><strong>The ExpressJS Way To Write APIs</strong>
<br/>

<em>This article will cover the basics of express from the perspective of a beginner without concerning its self with the…</em>medium.com</a><a href="https://medium.com/codex/prerequisites-to-writing-express-apis-75e3267b284a" class="js-mixtapeImage mixtapeImage u-ignoreBlock"></a></p>

<p><a href="https://medium.com/analytics-vidhya/heroku-deploy-guides-cheatsheet-compilation-b2897b69ce02" class="markup--anchor markup--mixtapeEmbed-anchor" title="https://medium.com/analytics-vidhya/heroku-deploy-guides-cheatsheet-compilation-b2897b69ce02"><strong>Heroku Deploy Guides &amp; Cheatsheet Compilation</strong>
<br/>

<em>Heroku lets you deploy, run and manage applications written in Ruby, Node.js, Java, Python, Clojure, Scala, Go and PHP…</em>medium.com</a><a href="https://medium.com/analytics-vidhya/heroku-deploy-guides-cheatsheet-compilation-b2897b69ce02" class="js-mixtapeImage mixtapeImage u-ignoreBlock"></a></p>

<p><a href="https://javascript.plainenglish.io/react-in-depth-1965dcde8d4f" class="markup--anchor markup--mixtapeEmbed-anchor" title="https://javascript.plainenglish.io/react-in-depth-1965dcde8d4f"><strong>A Comprehensive Deep Dive into React</strong>
<br/>

<em>An in-depth look into the world of React.</em>javascript.plainenglish.io</a><a href="https://javascript.plainenglish.io/react-in-depth-1965dcde8d4f" class="js-mixtapeImage mixtapeImage u-ignoreBlock"></a></p>

<p><a href="https://bryanguner.medium.com/take-a-look-at-the-big-picture-b69e0999a380" class="markup--anchor markup--mixtapeEmbed-anchor" title="https://bryanguner.medium.com/take-a-look-at-the-big-picture-b69e0999a380"><strong>Web Development Resource List #4</strong>
<br/>

<em>Update:</em><a href="https://bryanguner.medium.com/take-a-look-at-the-big-picture-b69e0999a380" class="js-mixtapeImage mixtapeImage u-ignoreBlock"></a></p>

<p><a href="https://bryanguner.medium.com/bash-d3077114aea7" class="markup--anchor markup--mixtapeEmbed-anchor" title="https://bryanguner.medium.com/bash-d3077114aea7"><strong>BASH CHEAT SHEET</strong>
<br/>

<em>My Bash Cheatsheet Index:</em><a href="https://bryanguner.medium.com/bash-d3077114aea7" class="js-mixtapeImage mixtapeImage mixtapeImage--empty u-ignoreBlock"></a></p>

<p><a href="https://bryanguner.medium.com/heroku-cheat-sheet-6107ce6ba52b" class="markup--anchor markup--mixtapeEmbed-anchor" title="https://bryanguner.medium.com/heroku-cheat-sheet-6107ce6ba52b"><strong>Heroku Cheat Sheet</strong>
<br/>

<em>a cheatsheet for using heroku-cli</em><a href="https://bryanguner.medium.com/heroku-cheat-sheet-6107ce6ba52b" class="js-mixtapeImage mixtapeImage u-ignoreBlock"></a></p>

<p><a href="https://bryanguner.medium.com/prerequisites-to-writing-express-apis-75e3267b284a" class="markup--anchor markup--mixtapeEmbed-anchor" title="https://bryanguner.medium.com/prerequisites-to-writing-express-apis-75e3267b284a"><strong>The ExpressJS Way To Write APIs</strong>
<br/>

<em>This article will cover the basics of express from the perspective of a beginner without concerning it's self with the…</em><a href="https://bryanguner.medium.com/prerequisites-to-writing-express-apis-75e3267b284a" class="js-mixtapeImage mixtapeImage u-ignoreBlock"></a></p>

<p><a href="https://bryanguner.medium.com/heroku-deploy-guides-cheatsheet-compilation-b2897b69ce02" class="markup--anchor markup--mixtapeEmbed-anchor" title="https://bryanguner.medium.com/heroku-deploy-guides-cheatsheet-compilation-b2897b69ce02"><strong>Heroku Deploy Guides &amp; Cheatsheet Compilation</strong>
<br/>

<em>Heroku lets you deploy, run and manage applications written in Ruby, Node.js, Java, Python, Clojure, Scala, Go and PHP…</em><a href="https://bryanguner.medium.com/heroku-deploy-guides-cheatsheet-compilation-b2897b69ce02" class="js-mixtapeImage mixtapeImage u-ignoreBlock"></a></p>

<p><a href="https://javascript.plainenglish.io/react-in-depth-1965dcde8d4f" class="markup--anchor markup--mixtapeEmbed-anchor" title="https://javascript.plainenglish.io/react-in-depth-1965dcde8d4f"><strong>A Comprehensive Deep Dive into React</strong>
<br/>

<em>An in-depth look into the world of React.</em>javascript.plainenglish.io</a><a href="https://javascript.plainenglish.io/react-in-depth-1965dcde8d4f" class="js-mixtapeImage mixtapeImage u-ignoreBlock"></a></p>

<p><a href="https://bryanguner.medium.com/take-a-look-at-the-big-picture-b69e0999a380" class="markup--anchor markup--mixtapeEmbed-anchor" title="https://bryanguner.medium.com/take-a-look-at-the-big-picture-b69e0999a380"><strong>Web Development Resource List #4</strong>
<br/>

<em>Update:</em><a href="https://bryanguner.medium.com/take-a-look-at-the-big-picture-b69e0999a380" class="js-mixtapeImage mixtapeImage u-ignoreBlock"></a></p>

<p><a href="https://bryanguner.medium.com/bash-d3077114aea7" class="markup--anchor markup--mixtapeEmbed-anchor" title="https://bryanguner.medium.com/bash-d3077114aea7"><strong>BASH CHEAT SHEET</strong>
<br/>

<em>My Bash Cheatsheet Index:</em><a href="https://bryanguner.medium.com/bash-d3077114aea7" class="js-mixtapeImage mixtapeImage mixtapeImage--empty u-ignoreBlock"></a></p>

<p><a href="https://bryanguner.medium.com/heroku-cheat-sheet-6107ce6ba52b" class="markup--anchor markup--mixtapeEmbed-anchor" title="https://bryanguner.medium.com/heroku-cheat-sheet-6107ce6ba52b"><strong>Heroku Cheat Sheet</strong>
<br/>

<em>a cheatsheet for using heroku-cli</em><a href="https://bryanguner.medium.com/heroku-cheat-sheet-6107ce6ba52b" class="js-mixtapeImage mixtapeImage u-ignoreBlock"></a></p>

<p><a href="https://bryanguner.medium.com/web-developers-technical-glossary-2066beae5e96" class="markup--anchor markup--mixtapeEmbed-anchor" title="https://bryanguner.medium.com/web-developers-technical-glossary-2066beae5e96"><strong>Web Developer's Technical Glossary</strong>
<br/>

<em>This will be a running list as I make updates!</em><a href="https://bryanguner.medium.com/web-developers-technical-glossary-2066beae5e96" class="js-mixtapeImage mixtapeImage mixtapeImage--empty u-ignoreBlock"></a></p>

<p><a href="https://medium.com/codex/postgresql-in-43-commands-or-less-19fba3e37110" class="markup--anchor markup--mixtapeEmbed-anchor" title="https://medium.com/codex/postgresql-in-43-commands-or-less-19fba3e37110"><strong>PostgreSQL In 43 Commands Or Less</strong>
<br/>

<em>In database jargon, PostgreSQL uses a client/server model. A PostgreSQL session consists of the following cooperating…</em>medium.com</a><a href="https://medium.com/codex/postgresql-in-43-commands-or-less-19fba3e37110" class="js-mixtapeImage mixtapeImage u-ignoreBlock"></a></p>

<p><a href="https://medium.com/geekculture/why-jamstack-rocks-666114722f35" class="markup--anchor markup--mixtapeEmbed-anchor" title="https://medium.com/geekculture/why-jamstack-rocks-666114722f35"><strong>Why Jamstack Rocks🤘😎🤙</strong>
<br/>

<em>JAMstack websites don't use the microservices architecture, but they go for the micro frontends architecture. Each…</em>medium.com</a><a href="https://medium.com/geekculture/why-jamstack-rocks-666114722f35" class="js-mixtapeImage mixtapeImage u-ignoreBlock"></a></p>

<p><a href="https://bryanguner.medium.com/what-are-bash-aliases-and-why-should-you-be-using-them-30a6cfafdfeb" class="markup--anchor markup--mixtapeEmbed-anchor" title="https://bryanguner.medium.com/what-are-bash-aliases-and-why-should-you-be-using-them-30a6cfafdfeb"><strong>What Are Bash Aliases And Why Should You Be Using Them!</strong>
<br/>

<em>A Bash alias is a method of supplementing or overriding Bash commands with new ones. Bash aliases make it easy for…</em><a href="https://bryanguner.medium.com/what-are-bash-aliases-and-why-should-you-be-using-them-30a6cfafdfeb" class="js-mixtapeImage mixtapeImage mixtapeImage--empty u-ignoreBlock"></a></p>

<p><a href="https://medium.com/geekculture/life-saving-bash-scripts-part-2-b40c8ee22682" class="markup--anchor markup--mixtapeEmbed-anchor" title="https://medium.com/geekculture/life-saving-bash-scripts-part-2-b40c8ee22682"><strong>Life Saving Bash Scripts Part 2</strong>
<br/>

<em>I am not saying they're in any way special compared with other bash scripts… but when I consider that you can never…</em>medium.com</a><a href="https://medium.com/geekculture/life-saving-bash-scripts-part-2-b40c8ee22682" class="js-mixtapeImage mixtapeImage u-ignoreBlock"></a></p>

<p><a href="https://medium.com/analytics-vidhya/job-boards-and-the-hunt-8cbfefefbb33" class="markup--anchor markup--mixtapeEmbed-anchor" title="https://medium.com/analytics-vidhya/job-boards-and-the-hunt-8cbfefefbb33"><strong>Job Boards and The Hunt</strong>
<br/>

<em>I can't imagine the kind of masochism it would take to enjoy the act of posting and daily maintenance on a job…</em>medium.com</a><a href="https://medium.com/analytics-vidhya/job-boards-and-the-hunt-8cbfefefbb33" class="js-mixtapeImage mixtapeImage u-ignoreBlock"></a></p>

<p><a href="https://bryanguner.medium.com/absolutely-everything-you-could-need-to-know-about-how-javascript-works-633549469528" class="markup--anchor markup--mixtapeEmbed-anchor" title="https://bryanguner.medium.com/absolutely-everything-you-could-need-to-know-about-how-javascript-works-633549469528"><strong>Absolutely Everything You Could Need To Know About How JavaScript Works.</strong>
<br/>

<em>Seriously… this list is utterly exhaustive it covers more core concepts than I can hold the names of in working memory…</em><a href="https://bryanguner.medium.com/absolutely-everything-you-could-need-to-know-about-how-javascript-works-633549469528" class="js-mixtapeImage mixtapeImage u-ignoreBlock"></a></p>

<p><a href="https://bryanguner.medium.com/react-tutorial-from-basics-647ba595e607" class="markup--anchor markup--mixtapeEmbed-anchor" title="https://bryanguner.medium.com/react-tutorial-from-basics-647ba595e607"><strong>Basic React Tutorial</strong>
<br/>

<em>Random Things to Remember</em><a href="https://bryanguner.medium.com/react-tutorial-from-basics-647ba595e607" class="js-mixtapeImage mixtapeImage u-ignoreBlock"></a></p>

<p><a href="https://bryanguner.medium.com/fundamental-concepts-in-react-that-will-probably-come-up-on-an-interview-5495b6421287" class="markup--anchor markup--mixtapeEmbed-anchor" title="https://bryanguner.medium.com/fundamental-concepts-in-react-that-will-probably-come-up-on-an-interview-5495b6421287"><strong>Fundamental Concepts In React That Will Probably Come Up On An Interview</strong>
<br/>

<em>Incomplete Article</em><a href="https://bryanguner.medium.com/fundamental-concepts-in-react-that-will-probably-come-up-on-an-interview-5495b6421287" class="js-mixtapeImage mixtapeImage u-ignoreBlock"></a></p>

<p><a href="https://medium.com/geekculture/the-penultimate-web-developers-cheat-sheet-a02a423139a4" class="markup--anchor markup--mixtapeEmbed-anchor" title="https://medium.com/geekculture/the-penultimate-web-developers-cheat-sheet-a02a423139a4"><strong>The Penultimate Web Developer's Cheat Sheet</strong>
<br/>

<em>I am literally just going to combine a fair number of my Cheat Sheets in no particular order.</em>medium.com</a><a href="https://medium.com/geekculture/the-penultimate-web-developers-cheat-sheet-a02a423139a4" class="js-mixtapeImage mixtapeImage u-ignoreBlock"></a></p>

<p><a href="https://medium.com/geekculture/bash-commands-that-save-time-920fb6ab9d0a" class="markup--anchor markup--mixtapeEmbed-anchor" title="https://medium.com/geekculture/bash-commands-that-save-time-920fb6ab9d0a"><strong>Bash Commands That Save Me Time and Frustration</strong>
<br/>

<em>Here's a list of bash commands that stand between me and insanity.</em>medium.com</a><a href="https://medium.com/geekculture/bash-commands-that-save-time-920fb6ab9d0a" class="js-mixtapeImage mixtapeImage u-ignoreBlock"></a></p>

<p><a href="https://bryanguner.medium.com/quick-web-developers-website-checklist-a-list-of-tools-for-improvement-9a52e11c8ee1" class="markup--anchor markup--mixtapeEmbed-anchor" title="https://bryanguner.medium.com/quick-web-developers-website-checklist-a-list-of-tools-for-improvement-9a52e11c8ee1"><strong>Quick Web Developers Website Checklist &amp; A List Of Tools For Improvement</strong>
<br/>

<em>A set of questions you should use before handing off your application to the client.</em><a href="https://bryanguner.medium.com/quick-web-developers-website-checklist-a-list-of-tools-for-improvement-9a52e11c8ee1" class="js-mixtapeImage mixtapeImage u-ignoreBlock"></a></p>

<p><a href="https://javascript.plainenglish.io/react-md-cbaafb31765d" class="markup--anchor markup--mixtapeEmbed-anchor" title="https://javascript.plainenglish.io/react-md-cbaafb31765d"><strong>10 Essential React Interview Questions For Aspiring Frontend Developers</strong>
<br/>

<em>Comprehensive React Cheatsheet included at the bottom of this article!</em>javascript.plainenglish.io</a><a href="https://javascript.plainenglish.io/react-md-cbaafb31765d" class="js-mixtapeImage mixtapeImage u-ignoreBlock"></a></p>

<p><a href="https://levelup.gitconnected.com/long-list-of-invaluable-nodejs-resources-6a793ae1ce6" class="markup--anchor markup--mixtapeEmbed-anchor" title="https://levelup.gitconnected.com/long-list-of-invaluable-nodejs-resources-6a793ae1ce6"><strong>Long List Of Invaluable NodeJS Resources</strong>
<br/>

<em>Disclaimer: I know that I did not create this list all on my own… I can't recall or track down the original list if you…</em>levelup.gitconnected.com</a><a href="https://levelup.gitconnected.com/long-list-of-invaluable-nodejs-resources-6a793ae1ce6" class="js-mixtapeImage mixtapeImage u-ignoreBlock"></a></p>

<p><a href="https://bryanguner.medium.com/open-ended-frontend-interview-questions-you-should-answer-before-your-next-interview-7c9722712521" class="markup--anchor markup--mixtapeEmbed-anchor" title="https://bryanguner.medium.com/open-ended-frontend-interview-questions-you-should-answer-before-your-next-interview-7c9722712521"><strong>Open Ended Frontend Interview Questions You Should Answer Before Your Next Interview</strong>
<br/>

<em>Explain event delegation.</em><a href="https://bryanguner.medium.com/open-ended-frontend-interview-questions-you-should-answer-before-your-next-interview-7c9722712521" class="js-mixtapeImage mixtapeImage mixtapeImage--empty u-ignoreBlock"></a></p>

<p><a href="https://bryanguner.medium.com/data-structures-under-the-hood-660256c2e4e3" class="markup--anchor markup--mixtapeEmbed-anchor" title="https://bryanguner.medium.com/data-structures-under-the-hood-660256c2e4e3"><strong>Data Structures… Under The Hood</strong>
<br/>

<em>Data Structures Reference</em><a href="https://bryanguner.medium.com/data-structures-under-the-hood-660256c2e4e3" class="js-mixtapeImage mixtapeImage u-ignoreBlock"></a></p>

<p><a href="https://medium.com/geekculture/web-development-interview-resource-list-88fce9876261" class="markup--anchor markup--mixtapeEmbed-anchor" title="https://medium.com/geekculture/web-development-interview-resource-list-88fce9876261"><strong>Web Development Interview Resource List</strong>
<br/>

<em>Most good programmers do programming not because they expect to get paid or get adulation by the public, but because it…</em>medium.com</a><a href="https://medium.com/geekculture/web-development-interview-resource-list-88fce9876261" class="js-mixtapeImage mixtapeImage u-ignoreBlock"></a></p>

<p><a href="https://medium.com/geekculture/beginners-guide-to-python-e5a59b5bb64d" class="markup--anchor markup--mixtapeEmbed-anchor" title="https://medium.com/geekculture/beginners-guide-to-python-e5a59b5bb64d"><strong>Beginners Guide To Python</strong>
<br/>

<em>My favorite language for maintainability is Python. It has simple, clean syntax, object encapsulation, good library…</em>medium.com</a><a href="https://medium.com/geekculture/beginners-guide-to-python-e5a59b5bb64d" class="js-mixtapeImage mixtapeImage u-ignoreBlock"></a></p>

<p><a href="https://bryanguner.medium.com/data-structures-algorithms-resource-list-part-1-8bad647a8ad8" class="markup--anchor markup--mixtapeEmbed-anchor" title="https://bryanguner.medium.com/data-structures-algorithms-resource-list-part-1-8bad647a8ad8"><strong>Data Structures &amp; Algorithms Resource List Part 1</strong>
<br/>

<em>Guess the author of the following quotes:</em><a href="https://bryanguner.medium.com/data-structures-algorithms-resource-list-part-1-8bad647a8ad8" class="js-mixtapeImage mixtapeImage u-ignoreBlock"></a></p>

<p><a href="https://javascript.plainenglish.io/memoization-86685d811182" class="markup--anchor markup--mixtapeEmbed-anchor" title="https://javascript.plainenglish.io/memoization-86685d811182"><strong>What is Memoization?</strong>
<br/>

<em>And why this programming paradigm shouldn't make you cringe.</em>javascript.plainenglish.io</a><a href="https://javascript.plainenglish.io/memoization-86685d811182" class="js-mixtapeImage mixtapeImage u-ignoreBlock"></a></p>

<p><a href="https://bryanguner.medium.com/css-interview-prep-quiz-6e3e4de7ca53" class="markup--anchor markup--mixtapeEmbed-anchor" title="https://bryanguner.medium.com/css-interview-prep-quiz-6e3e4de7ca53"><strong>CSS Interview Prep Quiz</strong>
<br/>

<em>Plus Css Cheat Sheet (82 questions total)</em><a href="https://bryanguner.medium.com/css-interview-prep-quiz-6e3e4de7ca53" class="js-mixtapeImage mixtapeImage u-ignoreBlock"></a></p>

<p><a href="https://medium.com/geekculture/verbal-technical-interview-questions-about-graph-data-structures-fc6b1afbd8be" class="markup--anchor markup--mixtapeEmbed-anchor" title="https://medium.com/geekculture/verbal-technical-interview-questions-about-graph-data-structures-fc6b1afbd8be"><strong>Graph Data Structure Interview Questions At A Glance</strong>
<br/>

<em>Because they're just about the most important data structure there is.</em>medium.com</a><a href="https://medium.com/geekculture/verbal-technical-interview-questions-about-graph-data-structures-fc6b1afbd8be" class="js-mixtapeImage mixtapeImage u-ignoreBlock"></a></p>

<p><a href="https://medium.com/geekculture/object-methods-4066ed24b214" class="markup--anchor markup--mixtapeEmbed-anchor" title="https://medium.com/geekculture/object-methods-4066ed24b214"><strong>Object Methods</strong>
<br/>

<em>Iterating Through Objects</em>medium.com</a><a href="https://medium.com/geekculture/object-methods-4066ed24b214" class="js-mixtapeImage mixtapeImage mixtapeImage--empty u-ignoreBlock"></a></p>

<p><a href="https://levelup.gitconnected.com/github-repositories-that-will-teach-you-how-to-code-for-free-ad0ecf59d89e" class="markup--anchor markup--mixtapeEmbed-anchor" title="https://levelup.gitconnected.com/github-repositories-that-will-teach-you-how-to-code-for-free-ad0ecf59d89e"><strong>Github Repositories That Will Teach You How To Code For Free!</strong>
<br/>

<em>30-seconds/30-seconds-of-code</em>levelup.gitconnected.com</a><a href="https://levelup.gitconnected.com/github-repositories-that-will-teach-you-how-to-code-for-free-ad0ecf59d89e" class="js-mixtapeImage mixtapeImage u-ignoreBlock"></a></p>

<p><a href="https://bryanguner.medium.com/resources-by-programming-language-399d9f9ef520" class="markup--anchor markup--mixtapeEmbed-anchor" title="https://bryanguner.medium.com/resources-by-programming-language-399d9f9ef520"><strong>Resources By Programming Language</strong>
<br/>

<em>Here's a list of programming resources sorted by programming language.</em><a href="https://bryanguner.medium.com/resources-by-programming-language-399d9f9ef520" class="js-mixtapeImage mixtapeImage mixtapeImage--empty u-ignoreBlock"></a></p>

<p><a href="https://medium.com/codex/scope-closures-context-in-javascript-f126f1523104" class="markup--anchor markup--mixtapeEmbed-anchor" title="https://medium.com/codex/scope-closures-context-in-javascript-f126f1523104"><strong>Breaking Down Scope, Context, And Closure In JavaScript In Simple Terms.</strong>
<br/>

<em>"JavaScript's global scope is like a public toilet. You can't avoid going in there, but try to limit your contact with…</em>medium.com</a><a href="https://medium.com/codex/scope-closures-context-in-javascript-f126f1523104" class="js-mixtapeImage mixtapeImage u-ignoreBlock"></a></p>

<p><a href="https://medium.com/codex/these-are-a-few-of-my-favorite-things-82e8b6e61879" class="markup--anchor markup--mixtapeEmbed-anchor" title="https://medium.com/codex/these-are-a-few-of-my-favorite-things-82e8b6e61879"><strong>These Are A Few Of My Favorite Things</strong>
<br/>

<em>A web development student's declassified school survival guide.</em>medium.com</a><a href="https://medium.com/codex/these-are-a-few-of-my-favorite-things-82e8b6e61879" class="js-mixtapeImage mixtapeImage u-ignoreBlock"></a></p>

<p><a href="https://medium.com/codex/objects-in-javascript-b212486dade6" class="markup--anchor markup--mixtapeEmbed-anchor" title="https://medium.com/codex/objects-in-javascript-b212486dade6"><strong>Objects In JavaScript</strong>
<br/>

<em>The object is a data structure that stores other data, similar to how an array stores elements.</em>medium.com</a><a href="https://medium.com/codex/objects-in-javascript-b212486dade6" class="js-mixtapeImage mixtapeImage u-ignoreBlock"></a></p>

<p><a href="https://bryanguner.medium.com/fundamental-javascript-concepts-you-should-understand-81c4d839b827" class="markup--anchor markup--mixtapeEmbed-anchor" title="https://bryanguner.medium.com/fundamental-javascript-concepts-you-should-understand-81c4d839b827"><strong>Fundamental Javascript Concepts You Should Understand</strong>
<br/>

<em>Plain Old JS Object Lesson Concepts</em><a href="https://bryanguner.medium.com/fundamental-javascript-concepts-you-should-understand-81c4d839b827" class="js-mixtapeImage mixtapeImage u-ignoreBlock"></a></p>

<p><a href="https://bryanguner.medium.com/mutability-and-reference-vs-privative-types-in-javascript-5294422db4b0" class="markup--anchor markup--mixtapeEmbed-anchor" title="https://bryanguner.medium.com/mutability-and-reference-vs-privative-types-in-javascript-5294422db4b0"><strong>Mutability And Reference VS Privative Types in JavaScript</strong>
<br/>

<em>Mutability &amp;&amp; Primitive &amp;&amp; Reference Examples</em><a href="https://bryanguner.medium.com/mutability-and-reference-vs-privative-types-in-javascript-5294422db4b0" class="js-mixtapeImage mixtapeImage u-ignoreBlock"></a></p>

<p><a href="https://javascript.plainenglish.io/array-callback-methods-implemented-with-for-loops-d08875df6777" class="markup--anchor markup--mixtapeEmbed-anchor" title="https://javascript.plainenglish.io/array-callback-methods-implemented-with-for-loops-d08875df6777"><strong>Array Callback Methods Implemented With For Loops</strong>
<br/>

<em>How to implement array callback methods in JavaScript</em>javascript.plainenglish.io</a><a href="https://javascript.plainenglish.io/array-callback-methods-implemented-with-for-loops-d08875df6777" class="js-mixtapeImage mixtapeImage u-ignoreBlock"></a></p>

<p><a href="https://blog2-backup.netlify.app/docs/react/react2/" class="markup--anchor markup--mixtapeEmbed-anchor" title="https://blog2-backup.netlify.app/docs/react/react2/"><strong>Beginner's Guide To React Part 2</strong>
<br/>

<em>As I learn to build web applications in React I will blog about it in this series in an attempt to capture the…</em><a href="https://blog2-backup.netlify.app/docs/react/react2/" class="js-mixtapeImage mixtapeImage u-ignoreBlock"></a></p>

<p><a href="https://bryanguner.medium.com/a-very-quick-guide-to-calculating-big-o-computational-complexity-eb1557e85fa3" class="markup--anchor markup--mixtapeEmbed-anchor" title="https://bryanguner.medium.com/a-very-quick-guide-to-calculating-big-o-computational-complexity-eb1557e85fa3"><strong>A Very Quick Guide To Calculating Big O Computational Complexity</strong>
<br/>

<em>Big O: big picture, broad strokes, not details</em><a href="https://bryanguner.medium.com/a-very-quick-guide-to-calculating-big-o-computational-complexity-eb1557e85fa3" class="js-mixtapeImage mixtapeImage u-ignoreBlock"></a></p>

<p><a href="https://javascript.plainenglish.io/introduction-to-react-for-complete-beginners-8021738aa1ad" class="markup--anchor markup--mixtapeEmbed-anchor" title="https://javascript.plainenglish.io/introduction-to-react-for-complete-beginners-8021738aa1ad"><strong>Introduction to React for Complete Beginners</strong>
<br/>

<em>All of the code examples below will be included a second time at the bottom of this article as an embedded gist.</em>javascript.plainenglish.io</a><a href="https://javascript.plainenglish.io/introduction-to-react-for-complete-beginners-8021738aa1ad" class="js-mixtapeImage mixtapeImage u-ignoreBlock"></a></p>

<p><a href="https://javascript.plainenglish.io/scheduling-settimeout-and-setinterval-fcb2f40d16f7" class="markup--anchor markup--mixtapeEmbed-anchor" title="https://javascript.plainenglish.io/scheduling-settimeout-and-setinterval-fcb2f40d16f7"><strong>Scheduling: setTimeout and setInterval</strong>
<br/>

<em>We may decide to execute a function not right now, but at a later time. That's called "scheduling a call".</em>javascript.plainenglish.io</a><a href="https://javascript.plainenglish.io/scheduling-settimeout-and-setinterval-fcb2f40d16f7" class="js-mixtapeImage mixtapeImage u-ignoreBlock"></a></p>

<p><a href="https://bryanguner.medium.com/css-animations-d196a20099a5" class="markup--anchor markup--mixtapeEmbed-anchor" title="https://bryanguner.medium.com/css-animations-d196a20099a5"><strong>LocalStorage VS SessionStorage</strong>
<br/>

<em>Web storage objects localStorage and sessionStorage allow to save key/value pairs in the browser.</em><a href="https://bryanguner.medium.com/css-animations-d196a20099a5" class="js-mixtapeImage mixtapeImage u-ignoreBlock"></a></p>

<p><a href="https://levelup.gitconnected.com/these-are-the-bash-shell-commands-that-stand-between-me-and-insanity-984865ba5d1b" class="markup--anchor markup--mixtapeEmbed-anchor" title="https://levelup.gitconnected.com/these-are-the-bash-shell-commands-that-stand-between-me-and-insanity-984865ba5d1b"><strong>These Are The Bash Shell Commands That Stand Between Me And Insanity</strong>
<br/>

<em>I will not profess to be a bash shell wizard… but I have managed to scour some pretty helpful little scripts from Stack…</em>levelup.gitconnected.com</a><a href="https://levelup.gitconnected.com/these-are-the-bash-shell-commands-that-stand-between-me-and-insanity-984865ba5d1b" class="js-mixtapeImage mixtapeImage u-ignoreBlock"></a></p>

<p><a href="https://bryanguner.medium.com/how-to-implement-native-es6-data-structures-using-arrays-objects-ce953b9f6a07" class="markup--anchor markup--mixtapeEmbed-anchor" title="https://bryanguner.medium.com/how-to-implement-native-es6-data-structures-using-arrays-objects-ce953b9f6a07"><strong>How To Implement Native(ES6) Data Structures Using Arrays &amp; Objects</strong>
<br/>

<em>Smart data structures and dumb code works better than the other way around -"Eric S. Raymond"</em><a href="https://bryanguner.medium.com/how-to-implement-native-es6-data-structures-using-arrays-objects-ce953b9f6a07" class="js-mixtapeImage mixtapeImage u-ignoreBlock"></a></p>

<p><a href="https://medium.com/codex/objects-in-javascript-cc578a781e1d" class="markup--anchor markup--mixtapeEmbed-anchor" title="https://medium.com/codex/objects-in-javascript-cc578a781e1d"><strong>Objects in Javascript</strong>
<br/>

<em>Codepen with examples for you to practice with below!</em>medium.com</a><a href="https://medium.com/codex/objects-in-javascript-cc578a781e1d" class="js-mixtapeImage mixtapeImage u-ignoreBlock"></a></p>

<p><a href="https://javascript.plainenglish.io/absolute-beginners-guide-to-javascript-part-1-e222d166b6e1" class="markup--anchor markup--mixtapeEmbed-anchor" title="https://javascript.plainenglish.io/absolute-beginners-guide-to-javascript-part-1-e222d166b6e1"><strong>The Beginner's Guide To JavaScript</strong>
<br/>

<em>Part 1</em>javascript.plainenglish.io</a><a href="https://javascript.plainenglish.io/absolute-beginners-guide-to-javascript-part-1-e222d166b6e1" class="js-mixtapeImage mixtapeImage u-ignoreBlock"></a></p>

<p><a href="https://medium.com/star-gazers/web-developer-resource-list-part-4-fd686892b9eb" class="markup--anchor markup--mixtapeEmbed-anchor" title="https://medium.com/star-gazers/web-developer-resource-list-part-4-fd686892b9eb"><strong>Web Developer Resource List Part 4</strong>
<br/>

<em>A all encompassing list of tools and resources for web developers</em>medium.com</a><a href="https://medium.com/star-gazers/web-developer-resource-list-part-4-fd686892b9eb" class="js-mixtapeImage mixtapeImage u-ignoreBlock"></a></p>

<p><a href="https://medium.com/codex/vscode-extensions-specifically-for-javascript-development-ea91305cbd4a" class="markup--anchor markup--mixtapeEmbed-anchor" title="https://medium.com/codex/vscode-extensions-specifically-for-javascript-development-ea91305cbd4a"><strong>VSCode Extensions Specifically for JavaScript Development</strong>
<br/>

<em>VSCode Extensions that are indispensable in JavaScript development</em>medium.com</a><a href="https://medium.com/codex/vscode-extensions-specifically-for-javascript-development-ea91305cbd4a" class="js-mixtapeImage mixtapeImage u-ignoreBlock"></a></p>

<p><strong>A list of all of my articles to link to future posts</strong>
<br/>

<em>You should probably skip this one… seriously it's just for internal use!</em></p>

<p><a href="https://javascript.plainenglish.io/lists-stacks-and-queues-in-javascript-88466fae0fbb" class="markup--anchor markup--mixtapeEmbed-anchor" title="https://javascript.plainenglish.io/lists-stacks-and-queues-in-javascript-88466fae0fbb"><strong>Fundamental Data Structures in JavaScript</strong>
<br/>

<em>A simple to follow guide to Lists Stacks and Queues, with animated gifs, diagrams, and code examples!</em>javascript.plainenglish.io</a><a href="https://javascript.plainenglish.io/lists-stacks-and-queues-in-javascript-88466fae0fbb" class="js-mixtapeImage mixtapeImage u-ignoreBlock"></a></p>

<p><a href="https://bryanguner.medium.com/web-development-resources-part-3-f862ceb2b82a" class="markup--anchor markup--mixtapeEmbed-anchor" title="https://bryanguner.medium.com/web-development-resources-part-3-f862ceb2b82a"><strong>Web Development Resources Part 3</strong>
<br/>

<em>I'm the psychological equivalent of a physical hoarder only instead of empty soda cans and dead racoons it's lists of…</em><a href="https://bryanguner.medium.com/web-development-resources-part-3-f862ceb2b82a" class="js-mixtapeImage mixtapeImage u-ignoreBlock"></a></p>

<p><a href="https://medium.com/codex/web-development-interview-part-3-826ae81a9107" class="markup--anchor markup--mixtapeEmbed-anchor" title="https://medium.com/codex/web-development-interview-part-3-826ae81a9107"><strong>Web Development Interview Part 3💻</strong>
<br/>

<em>This installment is going to be the least technically demanding thus far however these questions are a more realistic…</em>medium.com</a><a href="https://medium.com/codex/web-development-interview-part-3-826ae81a9107" class="js-mixtapeImage mixtapeImage u-ignoreBlock"></a></p>

<p><a href="https://bryanguner.medium.com/the-best-cloud-based-code-playgrounds-of-2021-part-1-cdae9448db24" class="markup--anchor markup--mixtapeEmbed-anchor" title="https://bryanguner.medium.com/the-best-cloud-based-code-playgrounds-of-2021-part-1-cdae9448db24"><strong>The Best Cloud-Based Code Playgrounds of 2021 (Part 1)</strong>
<br/>

<em>A plethora of front-end code playgrounds have appeared over the years. They offer a convenient way to experiment with…</em><a href="https://bryanguner.medium.com/the-best-cloud-based-code-playgrounds-of-2021-part-1-cdae9448db24" class="js-mixtapeImage mixtapeImage u-ignoreBlock"></a></p>

<p><a href="https://medium.com/codex/front-end-interview-questions-part-2-86ddc0e91443" class="markup--anchor markup--mixtapeEmbed-anchor" title="https://medium.com/codex/front-end-interview-questions-part-2-86ddc0e91443"><strong>Front End Interview Questions Part 2</strong>
<br/>

<em>These will focus more on vocabulary and concepts than the application driven approach in my last post!</em>medium.com</a><a href="https://medium.com/codex/front-end-interview-questions-part-2-86ddc0e91443" class="js-mixtapeImage mixtapeImage u-ignoreBlock"></a></p>

<p><a href="https://medium.com/star-gazers/web-developer-resource-list-part-2-9c5cb56ab263" class="markup--anchor markup--mixtapeEmbed-anchor" title="https://medium.com/star-gazers/web-developer-resource-list-part-2-9c5cb56ab263"><strong>Web Developer Resource List Part 2</strong>
<br/>

<em>Because I compile these things compulsively anyway…</em>medium.com</a><a href="https://medium.com/star-gazers/web-developer-resource-list-part-2-9c5cb56ab263" class="js-mixtapeImage mixtapeImage u-ignoreBlock"></a></p>

<p><a href="https://levelup.gitconnected.com/http-basics-8f02a96a834a" class="markup--anchor markup--mixtapeEmbed-anchor" title="https://levelup.gitconnected.com/http-basics-8f02a96a834a"><strong>HTTP Basics</strong>
<br/>

<em>"If you want to build a ship, don't drum up the men and women to gather wood, divide the work, and give orders…</em>levelup.gitconnected.com</a><a href="https://levelup.gitconnected.com/http-basics-8f02a96a834a" class="js-mixtapeImage mixtapeImage u-ignoreBlock"></a></p>

<p><a href="https://javascript.plainenglish.io/javascript-frameworks-libraries-35931e187a35" class="markup--anchor markup--mixtapeEmbed-anchor" title="https://javascript.plainenglish.io/javascript-frameworks-libraries-35931e187a35"><strong>JavaScript Frameworks &amp; Libraries</strong>
<br/>

<em>My Awesome JavaScript List Part 2</em>javascript.plainenglish.io</a><a href="https://javascript.plainenglish.io/javascript-frameworks-libraries-35931e187a35" class="js-mixtapeImage mixtapeImage u-ignoreBlock"></a></p>

<p><a href="https://javascript.plainenglish.io/my-take-on-awesome-javascript-243255451e74" class="markup--anchor markup--mixtapeEmbed-anchor" title="https://javascript.plainenglish.io/my-take-on-awesome-javascript-243255451e74"><strong>My 'awesome' list of JavaScript resources</strong>
<br/>

<em>Everyone's seen the 'Awesome' lists on GitHub… and they are indeed awesome… so today I am going to attempt to curate my…</em>javascript.plainenglish.io</a><a href="https://javascript.plainenglish.io/my-take-on-awesome-javascript-243255451e74" class="js-mixtapeImage mixtapeImage u-ignoreBlock"></a></p>

<p><a href="https://levelup.gitconnected.com/everything-you-need-to-get-started-with-vscode-extensions-resources-b9f4c8d91931" class="markup--anchor markup--mixtapeEmbed-anchor" title="https://levelup.gitconnected.com/everything-you-need-to-get-started-with-vscode-extensions-resources-b9f4c8d91931"><strong>Everything You Need to Get Started With VSCode + Extensions &amp; Resources</strong>
<br/>

<em>Commands:</em>levelup.gitconnected.com</a><a href="https://levelup.gitconnected.com/everything-you-need-to-get-started-with-vscode-extensions-resources-b9f4c8d91931" class="js-mixtapeImage mixtapeImage u-ignoreBlock"></a></p>

<p><a href="https://levelup.gitconnected.com/my-favorite-vscode-themes-9bab65af3f0f" class="markup--anchor markup--mixtapeEmbed-anchor" title="https://levelup.gitconnected.com/my-favorite-vscode-themes-9bab65af3f0f"><strong>My Favorite VSCode <em>Themes</em></strong>
<br/>

Themeslevelup.gitconnected.com</a><a href="https://levelup.gitconnected.com/my-favorite-vscode-themes-9bab65af3f0f" class="js-mixtapeImage mixtapeImage u-ignoreBlock"></a></p>

<p><a href="https://levelup.gitconnected.com/object-oriented-programming-in-javascript-d45007d06333" class="markup--anchor markup--mixtapeEmbed-anchor" title="https://levelup.gitconnected.com/object-oriented-programming-in-javascript-d45007d06333"><strong>Object Oriented Programming in JavaScript</strong>
<br/>

<em>Object-Oriented Programming</em>levelup.gitconnected.com</a><a href="https://levelup.gitconnected.com/object-oriented-programming-in-javascript-d45007d06333" class="js-mixtapeImage mixtapeImage u-ignoreBlock"></a></p>

<p><a href="https://medium.com/codex/javascript-rotate-array-problemwalkthrough-31deb19ebba1" class="markup--anchor markup--mixtapeEmbed-anchor" title="https://medium.com/codex/javascript-rotate-array-problemwalkthrough-31deb19ebba1"><strong>JavaScript Rotate (Array) ProblemWalkthrough</strong>
<br/>

<em>Explanation for Rotate Right</em>medium.com</a><a href="https://medium.com/codex/javascript-rotate-array-problemwalkthrough-31deb19ebba1" class="js-mixtapeImage mixtapeImage u-ignoreBlock"></a></p>

<p><a href="https://levelup.gitconnected.com/super-simple-intro-to-html-651d695f9bc" class="markup--anchor markup--mixtapeEmbed-anchor" title="https://levelup.gitconnected.com/super-simple-intro-to-html-651d695f9bc"><strong>Super Simple Intro To HTML</strong>
<br/>

<em>What is HTML, CSS &amp; JS and why do we need all three?</em>levelup.gitconnected.com</a><a href="https://levelup.gitconnected.com/super-simple-intro-to-html-651d695f9bc" class="js-mixtapeImage mixtapeImage u-ignoreBlock"></a></p>

<p><a href="https://medium.com/codex/everything-you-need-to-know-about-relational-databases-sql-postgresql-and-sequelize-to-build-8acb68284a98" class="markup--anchor markup--mixtapeEmbed-anchor" title="https://medium.com/codex/everything-you-need-to-know-about-relational-databases-sql-postgresql-and-sequelize-to-build-8acb68284a98"><strong>Everything You Need To Know About Relational Databases, SQL, PostgreSQL and Sequelize To Build…</strong>
<br/>

<em>For Front end developers who like myself struggle with making the jump to fullstack.</em>medium.com</a><a href="https://medium.com/codex/everything-you-need-to-know-about-relational-databases-sql-postgresql-and-sequelize-to-build-8acb68284a98" class="js-mixtapeImage mixtapeImage u-ignoreBlock"></a></p>

<p><a href="https://levelup.gitconnected.com/understanding-git-a-beginners-guide-containing-cheat-sheets-resources-b50c9c01a107" class="markup--anchor markup--mixtapeEmbed-anchor" title="https://levelup.gitconnected.com/understanding-git-a-beginners-guide-containing-cheat-sheets-resources-b50c9c01a107"><strong>Understanding Git (A Beginners Guide Containing Cheat Sheets &amp; Resources)</strong>
<br/>

<em>Basic Git Work Flow.</em>levelup.gitconnected.com</a><a href="https://levelup.gitconnected.com/understanding-git-a-beginners-guide-containing-cheat-sheets-resources-b50c9c01a107" class="js-mixtapeImage mixtapeImage u-ignoreBlock"></a></p>

<p><a href="https://javascript.plainenglish.io/complete-javascript-reference-guide-64306cd6b0db" class="markup--anchor markup--mixtapeEmbed-anchor" title="https://javascript.plainenglish.io/complete-javascript-reference-guide-64306cd6b0db"><strong>The Complete JavaScript Reference Guide</strong>
<br/>

<em>You will want to bookmark this</em>javascript.plainenglish.io</a><a href="https://javascript.plainenglish.io/complete-javascript-reference-guide-64306cd6b0db" class="js-mixtapeImage mixtapeImage u-ignoreBlock"></a></p>

<p><a href="https://medium.com/geekculture/modules-in-javascript-a55333e35978" class="markup--anchor markup--mixtapeEmbed-anchor" title="https://medium.com/geekculture/modules-in-javascript-a55333e35978"><strong>Modules in Javascript</strong>
<br/>

<em>Differences between Node.js and browsers</em>medium.com</a><a href="https://medium.com/geekculture/modules-in-javascript-a55333e35978" class="js-mixtapeImage mixtapeImage mixtapeImage--empty u-ignoreBlock"></a></p>

<p><a href="https://levelup.gitconnected.com/an-introduction-to-markdown-bonus-markdown-templates-included-3497ce56de3" class="markup--anchor markup--mixtapeEmbed-anchor" title="https://levelup.gitconnected.com/an-introduction-to-markdown-bonus-markdown-templates-included-3497ce56de3"><strong>An Introduction to Markdown (Bonus Markdown Templates Included)</strong>
<br/>

<em>Basic Syntax Guide</em>levelup.gitconnected.com</a><a href="https://levelup.gitconnected.com/an-introduction-to-markdown-bonus-markdown-templates-included-3497ce56de3" class="js-mixtapeImage mixtapeImage u-ignoreBlock"></a></p>

<p><a href="https://levelup.gitconnected.com/web-dev-resources-ec1975773d7d" class="markup--anchor markup--mixtapeEmbed-anchor" title="https://levelup.gitconnected.com/web-dev-resources-ec1975773d7d"><strong>Web Dev Resources</strong>
<br/>

<em>Web Development</em>levelup.gitconnected.com</a><a href="https://levelup.gitconnected.com/web-dev-resources-ec1975773d7d" class="js-mixtapeImage mixtapeImage u-ignoreBlock"></a></p>

<p><a href="https://medium.com/codex/regular-expressions-4d8fb3eb146b" class="markup--anchor markup--mixtapeEmbed-anchor" title="https://medium.com/codex/regular-expressions-4d8fb3eb146b"><strong>Regular Expressions</strong>
<br/>

<em>description:</em>medium.com</a><a href="https://medium.com/codex/regular-expressions-4d8fb3eb146b" class="js-mixtapeImage mixtapeImage u-ignoreBlock"></a></p>

<p><a href="https://medium.com/geekculture/writing-files-using-python-d46b4851366f" class="markup--anchor markup--mixtapeEmbed-anchor" title="https://medium.com/geekculture/writing-files-using-python-d46b4851366f"><strong>Writing Files Using Python</strong>
<br/>

<em>Basics of Writing Files in Python
<br/>

The common methods to operate with files are open() to open a file,</em>medium.com</a><a href="https://medium.com/geekculture/writing-files-using-python-d46b4851366f" class="js-mixtapeImage mixtapeImage mixtapeImage--empty u-ignoreBlock"></a></p>

<p><a href="https://bryanguner.medium.com/a-collection-of-my-most-useful-gist-entries-f4314f3ba3ab" class="markup--anchor markup--mixtapeEmbed-anchor" title="https://bryanguner.medium.com/a-collection-of-my-most-useful-gist-entries-f4314f3ba3ab"><strong>A Collection of my most useful Gist Entries</strong>
<br/>

<em>This list is in no particular order!</em><a href="https://bryanguner.medium.com/a-collection-of-my-most-useful-gist-entries-f4314f3ba3ab" class="js-mixtapeImage mixtapeImage mixtapeImage--empty u-ignoreBlock"></a></p>

<p><a href="https://javascript.plainenglish.io/learn-css-so-that-your-site-doesnt-look-like-garbage-938871b4521a" class="markup--anchor markup--mixtapeEmbed-anchor" title="https://javascript.plainenglish.io/learn-css-so-that-your-site-doesnt-look-like-garbage-938871b4521a"><strong>Learn CSS So That Your Site Doesn't Look Like Garbage</strong>
<br/>

<em>CSS Selectors</em>javascript.plainenglish.io</a><a href="https://javascript.plainenglish.io/learn-css-so-that-your-site-doesnt-look-like-garbage-938871b4521a" class="js-mixtapeImage mixtapeImage u-ignoreBlock"></a></p>

<p><a href="https://bryanguner.medium.com/postgresql-setup-for-windows-wsl-ubuntu-801672ab7089" class="markup--anchor markup--mixtapeEmbed-anchor" title="https://bryanguner.medium.com/postgresql-setup-for-windows-wsl-ubuntu-801672ab7089"><strong>PostgreSQL Setup For Windows &amp; WSL/Ubuntu</strong>
<br/>

<em>If you follow this guide to a tee… you will install PostgreSQL itself on your Windows installation. Then, you will…</em><a href="https://bryanguner.medium.com/postgresql-setup-for-windows-wsl-ubuntu-801672ab7089" class="js-mixtapeImage mixtapeImage u-ignoreBlock"></a></p>

<p><a href="https://bryanguner.medium.com/emmet-cheat-sheet-24758e628d37" class="markup--anchor markup--mixtapeEmbed-anchor" title="https://bryanguner.medium.com/emmet-cheat-sheet-24758e628d37"><strong>Emmet Cheat Sheet</strong>
<br/>

<em>EMMET</em><a href="https://bryanguner.medium.com/emmet-cheat-sheet-24758e628d37" class="js-mixtapeImage mixtapeImage u-ignoreBlock"></a></p>

<p><a href="https://bryanguner.medium.com/git-tricks-57e8d0292285" class="markup--anchor markup--mixtapeEmbed-anchor" title="https://bryanguner.medium.com/git-tricks-57e8d0292285"><strong>Git-Tricks</strong>
<br/>

<em>Refs</em><a href="https://bryanguner.medium.com/git-tricks-57e8d0292285" class="js-mixtapeImage mixtapeImage u-ignoreBlock"></a></p>

<p><a href="https://levelup.gitconnected.com/python-study-guide-for-a-native-javascript-developer-5cfdf3d2bdfb" class="markup--anchor markup--mixtapeEmbed-anchor" title="https://levelup.gitconnected.com/python-study-guide-for-a-native-javascript-developer-5cfdf3d2bdfb"><strong>Python Study Guide for a JavaScript Programmer</strong>
<br/>

<em>A guide to commands in Python from what you know in JavaScript</em>levelup.gitconnected.com</a><a href="https://levelup.gitconnected.com/python-study-guide-for-a-native-javascript-developer-5cfdf3d2bdfb" class="js-mixtapeImage mixtapeImage u-ignoreBlock"></a></p>

<p><a href="https://bryanguner.medium.com/fetch-quick-sheet-8872650742b4" class="markup--anchor markup--mixtapeEmbed-anchor" title="https://bryanguner.medium.com/fetch-quick-sheet-8872650742b4"><strong><em>Fetch</em> Quick Sheet</strong>
<br/>

Fetch<a href="https://bryanguner.medium.com/fetch-quick-sheet-8872650742b4" class="js-mixtapeImage mixtapeImage mixtapeImage--empty u-ignoreBlock"></a></p>

<p><a href="https://bryanguner.medium.com/express-quick-sheet-8f93762c59ca" class="markup--anchor markup--mixtapeEmbed-anchor" title="https://bryanguner.medium.com/express-quick-sheet-8f93762c59ca"><strong>Express Quick Sheet</strong>
<br/>

<em>Settings</em><a href="https://bryanguner.medium.com/express-quick-sheet-8f93762c59ca" class="js-mixtapeImage mixtapeImage mixtapeImage--empty u-ignoreBlock"></a></p>

<p><a href="https://medium.com/codex/fundamental-data-structures-in-javascript-8f9f709c15b4" class="markup--anchor markup--mixtapeEmbed-anchor" title="https://medium.com/codex/fundamental-data-structures-in-javascript-8f9f709c15b4"><strong>Fundamental Data Structures In JavaScript</strong>
<br/>

<em>Data structures in JavaScript</em>medium.com</a><a href="https://medium.com/codex/fundamental-data-structures-in-javascript-8f9f709c15b4" class="js-mixtapeImage mixtapeImage u-ignoreBlock"></a></p>

<p><a href="https://bryanguner.medium.com/deploy-react-app-to-heroku-using-postgres-express-70b7ea807986" class="markup--anchor markup--mixtapeEmbed-anchor" title="https://bryanguner.medium.com/deploy-react-app-to-heroku-using-postgres-express-70b7ea807986"><strong>Deploy React App To Heroku Using Postgres &amp; Express</strong>
<br/>

<em>Heroku is an web application that makes deploying applications easy for a beginner.</em><a href="https://bryanguner.medium.com/deploy-react-app-to-heroku-using-postgres-express-70b7ea807986" class="js-mixtapeImage mixtapeImage mixtapeImage--empty u-ignoreBlock"></a></p>

<p><a href="https://medium.com/codex/postgresql-cheat-sheet-718b813d3e31" class="markup--anchor markup--mixtapeEmbed-anchor" title="https://medium.com/codex/postgresql-cheat-sheet-718b813d3e31"><strong>Postgresql Cheat Sheet</strong>
<br/>

<em>PostgreSQL commands</em>medium.com</a><a href="https://medium.com/codex/postgresql-cheat-sheet-718b813d3e31" class="js-mixtapeImage mixtapeImage u-ignoreBlock"></a></p>

<p><a href="https://medium.com/star-gazers/a-quick-guide-to-big-o-notation-memoization-tabulation-and-sorting-algorithms-by-example-803ff193c522" class="markup--anchor markup--mixtapeEmbed-anchor" title="https://medium.com/star-gazers/a-quick-guide-to-big-o-notation-memoization-tabulation-and-sorting-algorithms-by-example-803ff193c522"><strong>A Quick Guide to Big-O Notation, Memoization, Tabulation, and Sorting Algorithms by Example</strong>
<br/>

<em>Curating Complexity: A Guide to Big-O Notation</em>medium.com</a><a href="https://medium.com/star-gazers/a-quick-guide-to-big-o-notation-memoization-tabulation-and-sorting-algorithms-by-example-803ff193c522" class="js-mixtapeImage mixtapeImage u-ignoreBlock"></a></p>

<p><a href="https://levelup.gitconnected.com/basic-web-development-environment-setup-9f36c3f15afe" class="markup--anchor markup--mixtapeEmbed-anchor" title="https://levelup.gitconnected.com/basic-web-development-environment-setup-9f36c3f15afe"><strong>Basic Web Development Environment Setup</strong>
<br/>

<em>Windows Subsystem for Linux (WSL) and Ubuntu</em>levelup.gitconnected.com</a><a href="https://levelup.gitconnected.com/basic-web-development-environment-setup-9f36c3f15afe" class="js-mixtapeImage mixtapeImage u-ignoreBlock"></a></p>

<p>By <a href="https://medium.com/@bryanguner" class="p-author h-card">Bryan Guner</a> on <a href="https://medium.com/p/1f6f88ebdf5b">March 22, 2021</a>.</p>
<p><a href="https://medium.com/@bryanguner/a-list-of-all-of-my-articles-to-link-to-future-posts-1f6f88ebdf5b" class="p-canonical">Canonical link</a></p>
<p>Exported from <a href="https://medium.com">Medium</a> on August 31, 2021.</p>
<h1 id="absolutely-everything-you-could-need-to-know-about-how-javascript-works.">Absolutely Everything You Could Need To Know About How JavaScript Works.</h1>
<p>Seriously… this list is utterly exhaustive it covers more core concepts than I can hold the names of in working memory on a very good day.</p>
<hr />
<h3 id="absolutely-everything-you-could-need-to-know-about-how-javascript-works.-1">Absolutely Everything You Could Need To Know About How JavaScript Works.</h3>
<h4 id="seriously-this-list-is-utterly-exhaustive-it-covers-more-core-concepts-than-i-can-hold-the-names-of-in-working-memory-on-a-very-good-day.">Seriously… this list is utterly exhaustive it covers more core concepts than I can hold the names of in working memory on a very good day.</h4>
<h4 id="but-first-a-little-bit-of-mildly-shameful-self-promotion">But first a little bit of mildly shameful self promotion:</h4>
<blockquote>
<p>(self promotion ends after the line denoted by a bunch of pictures of my dog🐕 )</p>
</blockquote>
<blockquote>
<p>(Followed by a brief introduction to JavaScript for beginners)</p>
</blockquote>
<blockquote>
<p>(Finally the main content / resources / imbedded YouTube links)</p>
</blockquote>
<figure>
<img src="https://cdn-images-1.medium.com/max/800/0*huxNcspoDvOfqxvn.gif" class="graf-image" />
</figure>
<h3 id="my-blog">My Blog:</h3>
<h3 id="discover-more-1">Discover More:</h3>
<p><a href="