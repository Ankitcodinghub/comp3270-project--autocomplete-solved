# comp3270-project--autocomplete-solved
**TO GET THIS SOLUTION VISIT:** [COMP3270  Project- Autocomplete Solved](https://www.ankitcodinghub.com/product/comp3270-project-autocomplete-solved/)


---

📩 **If you need this solution or have special requests:** **Email:** ankitcoding@gmail.com  
📱 **WhatsApp:** +1 419 877 7882  
📄 **Get a quote instantly using this form:** [Ask Homework Questions](https://www.ankitcodinghub.com/services/ask-homework-questions/)

*We deliver fast, professional, and affordable academic help.*

---

<h2>Description</h2>



<div class="kk-star-ratings kksr-auto kksr-align-center kksr-valign-top" data-payload="{&quot;align&quot;:&quot;center&quot;,&quot;id&quot;:&quot;95502&quot;,&quot;slug&quot;:&quot;default&quot;,&quot;valign&quot;:&quot;top&quot;,&quot;ignore&quot;:&quot;&quot;,&quot;reference&quot;:&quot;auto&quot;,&quot;class&quot;:&quot;&quot;,&quot;count&quot;:&quot;1&quot;,&quot;legendonly&quot;:&quot;&quot;,&quot;readonly&quot;:&quot;&quot;,&quot;score&quot;:&quot;5&quot;,&quot;starsonly&quot;:&quot;&quot;,&quot;best&quot;:&quot;5&quot;,&quot;gap&quot;:&quot;4&quot;,&quot;greet&quot;:&quot;Rate this product&quot;,&quot;legend&quot;:&quot;5\/5 - (1 vote)&quot;,&quot;size&quot;:&quot;24&quot;,&quot;title&quot;:&quot;COMP3270&nbsp; Project- Autocomplete\u2028 Solved&quot;,&quot;width&quot;:&quot;138&quot;,&quot;_legend&quot;:&quot;{score}\/{best} - ({count} {votes})&quot;,&quot;font_factor&quot;:&quot;1.25&quot;}">

<div class="kksr-stars">

<div class="kksr-stars-inactive">
            <div class="kksr-star" data-star="1" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" data-star="2" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" data-star="3" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" data-star="4" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" data-star="5" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
    </div>

<div class="kksr-stars-active" style="width: 138px;">
            <div class="kksr-star" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
    </div>
</div>


<div class="kksr-legend" style="font-size: 19.2px;">
            5/5 - (1 vote)    </div>
    </div>
&nbsp;

<ol>
<li><strong>Pseudocode</strong>: Understand the strategy provided for <em>TrieAutoComplete</em>. State the algorithm for the functions <u>precisely using numbered steps that follow the pseudocode conventions</u> that we use. Provide an approximate efficiency analysis by filling the table given below, for your algorithm.</li>
</ol>
&nbsp;

<em>Add</em>

<ul>
<li>Pseudocode:</li>
</ul>
&nbsp;

<ol>
<li><strong>if word is null</strong></li>
<li><strong>throw an exception</strong></li>
<li><strong>if weight &lt; 0</strong></li>
<li><strong>throw an exception</strong></li>
<li><strong>char character = “”</strong></li>
<li><strong>Node temp = root node of the tree</strong></li>
<li><strong>For a to word.length</strong></li>
<li><strong>Character = the character at index a</strong></li>
<li><strong>Node next = the child node of temp with the</strong></li>
</ol>
<strong>character character</strong>

<ol start="10">
<li><strong>If next is null</strong></li>
<li><strong>Initialize next with the index of the character, parent temp, and given weight</strong></li>
<li><strong>Add the new child to tree</strong></li>
<li><strong>If the weight &gt; temp subtree max weight</strong></li>
<li><strong>temp subtree max weight = weight</strong></li>
<li><strong>Point temp to next</strong></li>
</ol>
<ol start="16">
<li><strong>Set temp node word value</strong></li>
<li><strong>Set temp node weight</strong></li>
<li><strong>Set temp node to that of a word</strong></li>
</ol>
<ul>
<li>Complexity analysis:</li>
</ul>
<table>
<tbody>
<tr>
<td width="130">Step #</td>
<td width="328">Complexity stated as O(_)</td>
</tr>
<tr>
<td width="130"><strong>1</strong></td>
<td width="328"><strong>O(1)</strong></td>
</tr>
<tr>
<td width="130"><strong>2</strong></td>
<td width="328"><strong>O(1)</strong></td>
</tr>
<tr>
<td width="130"><strong>3</strong></td>
<td width="328"><strong>O(1)</strong></td>
</tr>
<tr>
<td width="130"><strong>4</strong></td>
<td width="328"><strong>O(1)</strong></td>
</tr>
<tr>
<td width="130"><strong>5</strong></td>
<td width="328"><strong>O(1)</strong></td>
</tr>
<tr>
<td width="130"><strong>6</strong></td>
<td width="328"><strong>O(1)</strong></td>
</tr>
<tr>
<td width="130"><strong>7</strong></td>
<td width="328"><strong>O(n)</strong></td>
</tr>
<tr>
<td width="130"><strong>8</strong></td>
<td width="328"><strong>O(n)</strong></td>
</tr>
<tr>
<td width="130"><strong>9</strong></td>
<td width="328"><strong>O(n)</strong></td>
</tr>
<tr>
<td width="130"><strong>10</strong></td>
<td width="328"><strong>O(n)</strong></td>
</tr>
<tr>
<td width="130"><strong>11</strong></td>
<td width="328"><strong>O(n)</strong></td>
</tr>
<tr>
<td width="130"><strong>12</strong></td>
<td width="328"><strong>O(n)</strong></td>
</tr>
<tr>
<td width="130"><strong>13</strong></td>
<td width="328"><strong>O(n)</strong></td>
</tr>
<tr>
<td width="130"><strong>14</strong></td>
<td width="328"><strong>O(n)</strong></td>
</tr>
<tr>
<td width="130"><strong>15</strong></td>
<td width="328"><strong>O(n)</strong></td>
</tr>
<tr>
<td width="130"><strong>16</strong></td>
<td width="328"><strong>O(1)</strong></td>
</tr>
<tr>
<td width="130"><strong>17</strong></td>
<td width="328"><strong>O(1)</strong></td>
</tr>
<tr>
<td width="130"><strong>18</strong></td>
<td width="328"><strong>O(1)</strong></td>
</tr>
</tbody>
</table>
Complexity of the algorithm = <strong>O(n)</strong>

&nbsp;

<em>topMatch</em>

<ul>
<li>Pseudocode:</li>
</ul>
&nbsp;

<ol>
<li><strong> if prefix is null</strong></li>
<li><strong> throw an exception</strong></li>
<li><strong> Boolean matchFound = true</strong></li>
<li><strong> char character = “”</strong></li>
<li><strong> Node temp = root node of the tree</strong></li>
<li><strong> string emptyString = “”</strong></li>
<li><strong> string bestMatchFound = “”</strong></li>
<li><strong> priorityQueue = new priority queue of nodes using </strong></li>
</ol>
<strong>a reverse weight comparator</strong>

<ol start="9">
<li><strong> for a to prefix.length</strong></li>
<li><strong> character = the character in the word at index a</strong></li>
<li><strong> if a child of temp contains the value of character</strong></li>
<li><strong> temp points to that child</strong></li>
<li><strong> else</strong></li>
<li><strong> matchFound = false</strong></li>
<li><strong> break</strong></li>
</ol>
<strong>16&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; if matchFound is false</strong>

<ol start="17">
<li><strong> return emptyString</strong></li>
<li><strong> while temp’s subtree max weight &gt; temp’s weight and </strong></li>
</ol>
<strong>temp is a word</strong>

<ol start="19">
<li><strong> for every node within temp’s children </strong></li>
<li><strong> add that node into priorityQueue</strong></li>
<li><strong> point temp to the head of the queue and then remove the element from the queue</strong></li>
<li><strong> bestMatchFound = word value of temp node</strong></li>
<li><strong> return bestMatchFound</strong></li>
</ol>
<ul>
<li>Complexity analysis:</li>
</ul>
&nbsp;

<table>
<tbody>
<tr>
<td width="130">Step #</td>
<td width="328">Complexity stated as O(_)</td>
</tr>
<tr>
<td width="130"><strong>1</strong></td>
<td width="328"><strong>O(1)</strong></td>
</tr>
<tr>
<td width="130"><strong>2</strong></td>
<td width="328"><strong>O(1)</strong></td>
</tr>
<tr>
<td width="130"><strong>3</strong></td>
<td width="328"><strong>O(1)</strong></td>
</tr>
<tr>
<td width="130"><strong>4</strong></td>
<td width="328"><strong>O(1)</strong></td>
</tr>
<tr>
<td width="130"><strong>5</strong></td>
<td width="328"><strong>O(1)</strong></td>
</tr>
<tr>
<td width="130"><strong>6</strong></td>
<td width="328"><strong>O(1)</strong></td>
</tr>
<tr>
<td width="130"><strong>7</strong></td>
<td width="328"><strong>O(1)</strong></td>
</tr>
<tr>
<td width="130"><strong>8</strong></td>
<td width="328"><strong>O(1)</strong></td>
</tr>
<tr>
<td width="130"><strong>9</strong></td>
<td width="328"><strong>O(n)</strong></td>
</tr>
<tr>
<td width="130"><strong>10</strong></td>
<td width="328"><strong>O(n)</strong></td>
</tr>
<tr>
<td width="130"><strong>11</strong></td>
<td width="328"><strong>O(n)</strong></td>
</tr>
<tr>
<td width="130"><strong>12</strong></td>
<td width="328"><strong>O(n)</strong></td>
</tr>
<tr>
<td width="130"><strong>13</strong></td>
<td width="328"><strong>O(n)</strong></td>
</tr>
<tr>
<td width="130"><strong>14</strong></td>
<td width="328"><strong>O(n)</strong></td>
</tr>
<tr>
<td width="130"><strong>15</strong></td>
<td width="328"><strong>O(n)</strong></td>
</tr>
<tr>
<td width="130"><strong>16</strong></td>
<td width="328"><strong>O(1)</strong></td>
</tr>
<tr>
<td width="130"><strong>17</strong></td>
<td width="328"><strong>O(1)</strong></td>
</tr>
<tr>
<td width="130"><strong>18</strong></td>
<td width="328"><strong>O(n)</strong></td>
</tr>
<tr>
<td width="130"><strong>19</strong></td>
<td width="328"><strong>O(n²)</strong></td>
</tr>
<tr>
<td width="130"><strong>20</strong></td>
<td width="328"><strong>O(n²)</strong></td>
</tr>
<tr>
<td width="130"><strong>21</strong></td>
<td width="328"><strong>O(n)</strong></td>
</tr>
<tr>
<td width="130"><strong>22</strong></td>
<td width="328"><strong>O(1)</strong></td>
</tr>
<tr>
<td width="130"><strong>23</strong></td>
<td width="328"><strong>O(1)</strong></td>
</tr>
</tbody>
</table>
Complexity of the algorithm = <strong>O(n²)</strong>

&nbsp;

<em>topMatches</em>

<ul>
<li>Pseudocode:</li>
</ul>
&nbsp;

<ol>
<li><strong> if prefix is null</strong></li>
<li><strong> throw an exception</strong></li>
<li><strong> char character = “”</strong></li>
<li><strong> Node temp = root of the tree</strong></li>
<li><strong> wordList = new ArrayList of Nodes</strong></li>
<li><strong> output = new ArrayList of Strings</strong></li>
<li><strong> noWordsList = new ArrayList of Strings</strong></li>
<li><strong> priorityQueue = new PriorityQueue of Nodes</strong></li>
<li><strong> for a to prefix.length</strong></li>
<li><strong> character = the character in the word at the index a</strong></li>
<li><strong> temp points to the child with the value of i</strong></li>
<li><strong> if temp is null</strong></li>
<li><strong> return noWordsList</strong></li>
<li><strong> if priorityQueue is not null</strong></li>
<li><strong> add temp to priorityQueue</strong></li>
<li><strong> while priorityQueue is not empty</strong></li>
<li><strong> if the size of wordList &gt;= k</strong></li>
<li><strong> sort wordList in descending order of the values</strong></li>
<li><strong> break</strong></li>
<li><strong> set temp to point to the head of the queue and then remove the element from the queue</strong></li>
<li><strong> if temp is a word</strong></li>
<li><strong> add temp to wordList</strong></li>
<li><strong> for each node within temp nodes children</strong></li>
<li><strong> add the node into priorityQueue</strong></li>
<li><strong> for b to the smallest value between k and wordList’s size</strong></li>
<li><strong> add the word that is located at b to output</strong></li>
<li><strong> return output</strong></li>
</ol>
&nbsp;

&nbsp;

&nbsp;

&nbsp;

<ul>
<li>Complexity analysis:</li>
</ul>
<table>
<tbody>
<tr>
<td width="130">Step #</td>
<td width="328">Complexity stated as O(_)</td>
</tr>
<tr>
<td width="130"><strong>1</strong></td>
<td width="328"><strong>O(1)</strong></td>
</tr>
<tr>
<td width="130"><strong>2</strong></td>
<td width="328"><strong>O(1)</strong></td>
</tr>
<tr>
<td width="130"><strong>3</strong></td>
<td width="328"><strong>O(1)</strong></td>
</tr>
<tr>
<td width="130"><strong>4</strong></td>
<td width="328"><strong>O(1)</strong></td>
</tr>
<tr>
<td width="130"><strong>5</strong></td>
<td width="328"><strong>O(1)</strong></td>
</tr>
<tr>
<td width="130"><strong>6</strong></td>
<td width="328"><strong>O(1)</strong></td>
</tr>
<tr>
<td width="130"><strong>7</strong></td>
<td width="328"><strong>O(1)</strong></td>
</tr>
<tr>
<td width="130"><strong>8</strong></td>
<td width="328"><strong>O(1)</strong></td>
</tr>
<tr>
<td width="130"><strong>9</strong></td>
<td width="328"><strong>O(n)</strong></td>
</tr>
<tr>
<td width="130"><strong>10</strong></td>
<td width="328"><strong>O(n)</strong></td>
</tr>
<tr>
<td width="130"><strong>11</strong></td>
<td width="328"><strong>O(n)</strong></td>
</tr>
<tr>
<td width="130"><strong>12</strong></td>
<td width="328"><strong>O(n)</strong></td>
</tr>
<tr>
<td width="130"><strong>13</strong></td>
<td width="328"><strong>O(n)</strong></td>
</tr>
<tr>
<td width="130"><strong>14</strong></td>
<td width="328"><strong>O(1)</strong></td>
</tr>
<tr>
<td width="130"><strong>15</strong></td>
<td width="328"><strong>O(1)</strong></td>
</tr>
<tr>
<td width="130"><strong>16</strong></td>
<td width="328"><strong>O(n)</strong></td>
</tr>
<tr>
<td width="130"><strong>17</strong></td>
<td width="328"><strong>O(n)</strong></td>
</tr>
<tr>
<td width="130"><strong>18</strong></td>
<td width="328"><strong>O(nlogn)</strong></td>
</tr>
<tr>
<td width="130"><strong>19</strong></td>
<td width="328"><strong>O(1)</strong></td>
</tr>
<tr>
<td width="130"><strong>20</strong></td>
<td width="328"><strong>O(n)</strong></td>
</tr>
<tr>
<td width="130"><strong>21</strong></td>
<td width="328"><strong>O(n)</strong></td>
</tr>
<tr>
<td width="130"><strong>22</strong></td>
<td width="328"><strong>O(n)</strong></td>
</tr>
<tr>
<td width="130"><strong>23</strong></td>
<td width="328"><strong>O(n²)</strong></td>
</tr>
<tr>
<td width="130"><strong>24</strong></td>
<td width="328"><strong>O(n²)</strong></td>
</tr>
<tr>
<td width="130"><strong>25</strong></td>
<td width="328"><strong>O(n)</strong></td>
</tr>
<tr>
<td width="130"><strong>26</strong></td>
<td width="328"><strong>O(n)</strong></td>
</tr>
<tr>
<td width="130"><strong>27</strong></td>
<td width="328"><strong>O(1)</strong></td>
</tr>
</tbody>
</table>
Complexity of the algorithm = <strong>O(n²)</strong>

&nbsp;

&nbsp;

2.<strong>Testing</strong>: Complete your test cases to test the <em>TrieAutoComplete</em> functions based upon the criteria mentioned below.

&nbsp;

<strong>Test of correctness:</strong>

Assuming the trie already contains the terms {”ape, 6”, ”app, 4”, ”ban, 2”, ”bat, 3”, ”bee, 5”, ”car, 7”, ”cat, 1”}, you would expect results based on the following table:

<table width="396">
<tbody>
<tr>
<td width="59">Query</td>
<td width="42">k</td>
<td width="294">Result</td>
</tr>
<tr>
<td width="59">””</td>
<td width="42">8</td>
<td width="294">{”car”, ”ape”, ”bee”, ”app”, ”bat”, ”ban”, ”cat”}</td>
</tr>
<tr>
<td width="59">””</td>
<td width="42">1</td>
<td width="294">{”car”}</td>
</tr>
<tr>
<td width="59">””</td>
<td width="42">2</td>
<td width="294">{”car”, ”ape”}</td>
</tr>
<tr>
<td width="59">””</td>
<td width="42">3</td>
<td width="294">{”car”, ”ape”, ”bee”}</td>
</tr>
<tr>
<td width="59">”a”</td>
<td width="42">1</td>
<td width="294">{”ape”}</td>
</tr>
<tr>
<td width="59">”ap”</td>
<td width="42">1</td>
<td width="294">{”ape”}</td>
</tr>
<tr>
<td width="59">”b”</td>
<td width="42">2</td>
<td width="294">{”bee”, ”bat”}</td>
</tr>
<tr>
<td width="59">”ba”</td>
<td width="42">2</td>
<td width="294">{”bee”, ”bat”}</td>
</tr>
<tr>
<td width="59">”d”</td>
<td width="42">100</td>
<td width="294">{}</td>
</tr>
</tbody>
</table>
<strong><u>&nbsp;</u></strong>

<strong><u>&nbsp;</u></strong>

<strong>**passed all test cases**</strong>

3.<strong>Analysis</strong>: Answer the following questions. Use data wherever possible to justify your answers, and keep explanations brief but accurate:

<ol>
<li>What is the order of growth (big-Oh) of the number of compares (in the worst case) that each of the operations in the&nbsp;<em>Autocompletor </em>data type make?</li>
<li><strong>Add: O(n)</strong></li>
<li><strong>topMatch: O(</strong><strong>n²)</strong></li>
<li><strong>topMatches: O(</strong><strong>n²)</strong></li>
<li>How does the runtime of <em>topMatches()</em> vary with k, assuming a fixed prefix and set of terms? Provide answers for <em>BruteAutocomplete </em>and <em>TrieAutocomplete</em>. Justify your answer, with both data and algorithmic analysis.</li>
</ol>
&nbsp;

<ul>
<li>How does increasing the size of the source and increasing the size of the prefix argument affect the runtime of <em>topMatch</em> and <em>topMatches</em>? (Tip: Benchmark each implementation using fourletterwords.txt, which has all four-letter combinations from aaaa to zzzz, and fourletterwordshalf.txt, which has all four-letter word combinations from aaaa to mzzz. These datasets provide a very clean distribution of words and an exact 1-to-2 ratio of words in source files.)</li>
</ul>
<ol start="4">
<li>Graphical Analysis: Provide a graphical analysis by comparing the following:</li>
</ol>
&nbsp;

<ol>
<li>The big-Oh for <em>TrieAutoComplete</em> after analyzing the pseudocode and big-Oh for <em>TrieAutoComplete</em> after the implementation.</li>
</ol>
&nbsp;

<ol>
<li>Compare the <em>TrieAutoComplete</em> with <em>BruteAutoComplete </em>and <em>BinarySearchAutoComplete</em>.</li>
</ol>
&nbsp;

<ul>
<li><strong>According to the data shown above, it is apparent that </strong><strong>Trie is far more efficient than that of Brute and Binary. </strong></li>
</ul>
