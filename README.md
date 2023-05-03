Download Link: https://assignmentchef.com/product/solved-cs156-homework-4-uninformed-search
<br>



The objective of this homework assignment is to understand and visualize how different uninformed search algorithms work. Specifically, we will implement and compare the performance of three different uninformed search algorithms:

<ol>

 <li>Depth First Search (DFS)</li>

 <li>Breadth First Search (BFS)</li>

 <li>Uniform Cost Search (UCS)</li>

</ol>




We will explore these algorithms in a gaming environment where the Spartan Sammy will try to collect medals in a maze in the shortest possible time.

These are the following files for this assignment:

<ol>

 <li>data_structures contains all the Class definitions for data structures to be used by the search algorithms</li>

 <li>graphics contains Visualization of the maze and solution for the Spartan’s quest</li>

 <li>noway, questA, questB, questC, questD and SJSU are txt files containing the description of different mazes with walls, starting position of Sammy and the starting positions of the medals that will be collected by Sammy</li>

 <li>Sammy is the Spartan (mascot).</li>

 <li>Spartanquest has the Main program that guides Sammy the Spartan on a quest within a given maze. It is invoked using: spartanquest.py maze_file search_algoritm where</li>

</ol>







The maze_file is a text file such as SJSU.txt

The search_algorithm in homework 4 is:

dfs: for depth first search (coded for you)

bfs: for breadth first search

ucs for uniform cost search

Example:  spartanquest.py SJSU.txt dfs

<ol start="6">

 <li>Uninformed_search_only_dfs has the implementation of the dfs algorithm and place holders for bfs and ucs algorithms that you have to write for this homework assignment.</li>

</ol>




<strong><u>Assignment:</u></strong>

<ol>

 <li>Tabulate the results showing</li>

</ol>

(a) Path length, (b) Path cost, (c) Number of nodes expanded and (d) Processing time from all three searches dfs, bfs and ucs for the following scenarios:

<ol>

 <li>questA</li>

 <li>questB</li>

 <li>questC</li>

 <li>questD</li>

 <li>SJSU</li>

 <li>Noway</li>

</ol>




<table>

 <tbody>

  <tr>

   <td colspan="7" width="613"><strong><em>Depth First Search</em></strong></td>

  </tr>

  <tr>

   <td width="172"><em> </em></td>

   <td width="75"><strong>Quest A </strong></td>

   <td width="74"><strong>Quest B</strong></td>

   <td width="74"><strong>Quest C</strong></td>

   <td width="76"><strong>Quest D</strong></td>

   <td width="66"><strong>SJSU</strong></td>

   <td width="75"><strong>No Way</strong></td>

  </tr>

  <tr>

   <td width="172"><em>Path Length</em></td>

   <td width="75"><em>99</em></td>

   <td width="74"><em>992</em></td>

   <td width="74"><em>70</em></td>

   <td width="76"><em>256</em></td>

   <td width="66"><em>202</em></td>

   <td width="75"><em>0</em></td>

  </tr>

  <tr>

   <td width="172"><em>Path Cost</em></td>

   <td width="75"><em>252</em></td>

   <td width="74"><em>2336</em></td>

   <td width="74"><em>202</em></td>

   <td width="76"><em>499</em></td>

   <td width="66"><em>421</em></td>

   <td width="75"><em>0</em></td>

  </tr>

  <tr>

   <td width="172"><em>No. Nodes Expanded</em></td>

   <td width="75"><em>207</em></td>

   <td width="74"><em>1177</em></td>

   <td width="74"><em>274</em></td>

   <td width="76"><em>256</em></td>

   <td width="66"><em>304</em></td>

   <td width="75"><em>78</em></td>

  </tr>

  <tr>

   <td width="172"><em>Processing Time (secs)</em></td>

   <td width="75"><em>0.0059</em></td>

   <td width="74"><em>0.0143</em></td>

   <td width="74"><em>0.0034</em></td>

   <td width="76"><em>0.0037</em></td>

   <td width="66"><em>0.0036</em></td>

   <td width="75"><em>0.0009</em></td>

  </tr>

 </tbody>

</table>

<em> </em>

<table width="626">

 <tbody>

  <tr>

   <td colspan="7" width="626"><strong><em>Breadth First Search</em></strong></td>

  </tr>

  <tr>

   <td width="172"><em> </em></td>

   <td width="75"><strong><em>Quest A</em></strong></td>

   <td width="88"><strong><em>Quest B</em></strong></td>

   <td width="74"><strong><em>Quest C</em></strong></td>

   <td width="76"><strong><em>Quest D</em></strong></td>

   <td width="66"><strong><em>SJSU</em></strong></td>

   <td width="75"><strong><em>No Way</em></strong></td>

  </tr>

  <tr>

   <td width="172"><em>Path Length</em></td>

   <td width="75"><em>17</em></td>

   <td width="88"><em>100</em></td>

   <td width="74"><em>47</em></td>

   <td width="76"><em>31</em></td>

   <td width="66"><em>45</em></td>

   <td width="75"><em>0</em></td>

  </tr>

  <tr>

   <td width="172"><em>Path Cost</em></td>

   <td width="75"><em>49</em></td>

   <td width="88"><em>301</em></td>

   <td width="74"><em>166</em></td>

   <td width="76"><em>134</em></td>

   <td width="66"><em>157</em></td>

   <td width="75"><em>0</em></td>

  </tr>

  <tr>

   <td width="172"><em>No. Nodes Expanded</em></td>

   <td width="75"><em>97</em></td>

   <td width="88"><em>393981</em></td>

   <td width="74"><em>284</em></td>

   <td width="76"><em>723</em></td>

   <td width="66"><em>533</em></td>

   <td width="75"><em>78</em></td>

  </tr>

  <tr>

   <td width="172"><em>Processing Time (secs)</em></td>

   <td width="75"><em>0.0012</em></td>

   <td width="88"><em>23.5377</em></td>

   <td width="74"><em>0.0034</em></td>

   <td width="76"><em>0.0091</em></td>

   <td width="66"><em>0.0060</em></td>

   <td width="75"><em>0.0009</em></td>

  </tr>

 </tbody>

</table>

<em> </em>

<table width="626">

 <tbody>

  <tr>

   <td colspan="7" width="626"><strong><em>Uniform Cost Search</em></strong></td>

  </tr>

  <tr>

   <td width="172"><em> </em></td>

   <td width="75"><strong><em>Quest A</em></strong></td>

   <td width="88"><strong><em>Quest B</em></strong></td>

   <td width="74"><strong><em>Quest C</em></strong></td>

   <td width="76"><strong><em>Quest D</em></strong></td>

   <td width="66"><strong><em>SJSU</em></strong></td>

   <td width="75"><strong><em>No Way</em></strong></td>

  </tr>

  <tr>

   <td width="172"><em>Path Length</em></td>

   <td width="75"><em>17</em></td>

   <td width="88"><em>113</em></td>

   <td width="74"><em>48</em></td>

   <td width="76"><em>31</em></td>

   <td width="66"><em>52</em></td>

   <td width="75"><em>0</em></td>

  </tr>

  <tr>

   <td width="172"><em>Path Cost</em></td>

   <td width="75"><em>49</em></td>

   <td width="88"><em>281</em></td>

   <td width="74"><em>157</em></td>

   <td width="76"><em>134</em></td>

   <td width="66"><em>144</em></td>

   <td width="75"><em>0</em></td>

  </tr>

  <tr>

   <td width="172"><em>No. Nodes Expanded</em></td>

   <td width="75"><em>85</em></td>

   <td width="88"><em>398525</em></td>

   <td width="74"><em>303</em></td>

   <td width="76"><em>1251</em></td>

   <td width="66"><em>553</em></td>

   <td width="75"><em>78</em></td>

  </tr>

  <tr>

   <td width="172"><em>Processing Time (secs)</em></td>

   <td width="75"><em>0.0024</em></td>

   <td width="88"><em>14.3876</em></td>

   <td width="74"><em>0.0036</em></td>

   <td width="76"><em>0.0191</em></td>

   <td width="66"><em>0.0075</em></td>

   <td width="75"><em>0.0010</em></td>

  </tr>

 </tbody>

</table>




<ol>

 <li>Which search algorithm performed the best? Why do you think so?</li>

</ol>

Overall, Breadth First Search performed the best compared to Depth-First Search and Uniform Cost Search. BFS consistently had the shortest path length, with UCS coming in close behind. Additionally, BFS had the shortest processing time. BFS was a laggard compared to UCS in terms of path cost. UCS consistently had the smallest path cost.




<ol>

 <li>Did the performance of the algorithms vary with the type of the maze file? Why?</li>

</ol>

QuestB seemed to perform the worst among <strong>all</strong> three search algorithms; the goal state most likely was towards the end of the maze. Otherwise, the performance did not vary with the type of maze file(s). Slight discrepancies can be attributed to the size of the maze and the location of the goal state.




<strong><em><u>Additional Quests (Extra Credit)</u></em></strong>

<table>

 <tbody>

  <tr>

   <td colspan="7" width="613"><strong><em>Depth First Search</em></strong></td>

  </tr>

  <tr>

   <td width="172"><em> </em></td>

   <td width="75"><strong>Quest E </strong></td>

   <td width="74"><strong>Quest F</strong></td>

   <td width="74"><strong>Quest G</strong></td>

   <td width="76"><strong>Quest H</strong></td>

   <td width="66"><strong>Quest J</strong></td>

   <td width="75"> </td>

  </tr>

  <tr>

   <td width="172"><em>Path Length</em></td>

   <td width="75"><em>156</em></td>

   <td width="74"><em>1233</em></td>

   <td width="74"><em>1903</em></td>

   <td width="76"><em>100</em></td>

   <td width="66"><em>739</em></td>

   <td width="75"> </td>

  </tr>

  <tr>

   <td width="172"><em>Path Cost</em></td>

   <td width="75"><em>314</em></td>

   <td width="74"><em>2431</em></td>

   <td width="74"><em>3780</em></td>

   <td width="76"><em>243</em></td>

   <td width="66"><em>1407</em></td>

   <td width="75"> </td>

  </tr>

  <tr>

   <td width="172"><em>No. Nodes Expanded</em></td>

   <td width="75"><em>164</em></td>

   <td width="74"><em>1322</em></td>

   <td width="74"><em>2411</em></td>

   <td width="76"><em>175</em></td>

   <td width="66"><em>750</em></td>

   <td width="75"> </td>

  </tr>

  <tr>

   <td width="172"><em>Processing Time (secs)</em></td>

   <td width="75"><em>0.0025</em></td>

   <td width="74"><em>0.0151</em></td>

   <td width="74"><em>0.0275</em></td>

   <td width="76"><em>0.0018</em></td>

   <td width="66"><em>0.0089</em></td>

   <td width="75"> </td>

  </tr>

  <tr>

   <td width="172"><em> </em></td>

   <td colspan="6" width="441"> </td>

  </tr>

  <tr>

   <td colspan="7" width="613"><strong> </strong><strong><em>Breadth First Search</em></strong></td>

  </tr>

  <tr>

   <td width="172"><em> </em></td>

   <td width="75"><strong>Quest E </strong></td>

   <td width="74"><strong>Quest F</strong></td>

   <td width="74"><strong>Quest G</strong></td>

   <td width="76"><strong>Quest H</strong></td>

   <td width="66"><strong>Quest J</strong></td>

   <td width="75"> </td>

  </tr>

  <tr>

   <td width="172"><em>Path Length</em></td>

   <td width="75"><em>12</em></td>

   <td width="74"><em>73</em></td>

   <td width="74"><em>DNC</em></td>

   <td width="76"><em>40</em></td>

   <td width="66"><em>40</em></td>

   <td width="75"> </td>

  </tr>

  <tr>

   <td width="172"><em>Path Cost</em></td>

   <td width="75"><em>30</em></td>

   <td width="74"><em>133</em></td>

   <td width="74"><em>DNC</em></td>

   <td width="76"><em>106</em></td>

   <td width="66"><em>185</em></td>

   <td width="75"> </td>

  </tr>

  <tr>

   <td width="172"><em>No. Nodes Expanded</em></td>

   <td width="75"><em>188</em></td>

   <td width="74"><em>106463</em></td>

   <td width="74"><em>DNC</em></td>

   <td width="76"><em>1422</em></td>

   <td width="66"><em>4193</em></td>

   <td width="75"> </td>

  </tr>

  <tr>

   <td width="172"><em>Processing Time (secs)</em></td>

   <td width="75"><em>0.0021</em></td>

   <td width="74"><em>3.9901</em></td>

   <td width="74"><em>DNC</em></td>

   <td width="76"><em>0.0161</em></td>

   <td width="66"><em>0.0598</em></td>

   <td width="75"> </td>

  </tr>

 </tbody>

</table>




<table>

 <tbody>

  <tr>

   <td colspan="7" width="621"><strong><em>Uniform Cost Search</em></strong></td>

  </tr>

  <tr>

   <td width="172"><em> </em></td>

   <td width="75"><strong>Quest E </strong></td>

   <td width="74"><strong>Quest F</strong></td>

   <td width="82"><strong>Quest G</strong></td>

   <td width="76"><strong>Quest H</strong></td>

   <td width="66"><strong>Quest L</strong></td>

   <td width="75"> </td>

  </tr>

  <tr>

   <td width="172"><em>Path Length</em></td>

   <td width="75"><em>12</em></td>

   <td width="74"><em>73</em></td>

   <td width="82"><em>98</em></td>

   <td width="76"><em>40</em></td>

   <td width="66"><em>47</em></td>

   <td width="75"> </td>

  </tr>

  <tr>

   <td width="172"><em>Path Cost</em></td>

   <td width="75"><em>30</em></td>

   <td width="74"><em>133</em></td>

   <td width="82"><em>2173</em></td>

   <td width="76"><em>106</em></td>

   <td width="66"><em>137</em></td>

   <td width="75"> </td>

  </tr>

  <tr>

   <td width="172"><em>No. Nodes Expanded</em></td>

   <td width="75"><em>310</em></td>

   <td width="74"><em>47621</em></td>

   <td width="82"><em>1941519</em></td>

   <td width="76"><em>1154</em></td>

   <td width="66"><em>3859</em></td>

   <td width="75"> </td>

  </tr>

  <tr>

   <td width="172"><em>Processing Time (secs)</em></td>

   <td width="75"><em>0.0048</em></td>

   <td width="74"><em>1.0241</em></td>

   <td width="82"><em>113.1236</em></td>

   <td width="76"><em>0.0146</em></td>

   <td width="66"><em>0.0604</em></td>

   <td width="75"> </td>

  </tr>

 </tbody>

</table>




<strong><em><u>DNC = Did Not Complete</u></em></strong>