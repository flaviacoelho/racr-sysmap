<h2> <span style="color:red"> Refactoring-Aware and Code Review: A Systematic Mapping Study </span></h2>

<p>Details on our <b>systematic literature mapping</b> study!</p>

*This work has been supervisioned by Prof. Tiago Massoni and Prof. Everton Alves<br>*
*Federal University of Campina Grande, Brazil</font><br>*
<img src="/images/splab.png" alt="SPLab Logo" width="15%" height="15%">
<hr>


<h3> Research Questions </h3>
<ul style="list-style-type:square;">
    <li><b>RQ1</b>. What are the most common research topics in those papers?</li>
    <li><b>RQ2</b>. What are the methods/techniques/tools proposed in those papers?</li>
    <li><b>RQ3</b>. What are the validation methods applied in those papers?</li>
</ul>
<br>

<h3> Primary Studies </h3>
<p>Details at <b>/primaryStudies</b>.</p>

<table>	    
  <tr>
    <td align="center" valign="center">("code review" OR "code inspection") AND ("refactoring detection" OR "refactoring" OR "tool" OR "method" OR "process" OR "approach")
</th>
  </tr>
	<caption><i>Search search</i></caption>  
</table>
	
<table>	    
  <tr>
    <th>Database</th>
    <th>Collected Studies</th>    
  </tr>
  <tr>
    <td align="center" valign="center">ACM Digital Library</td>
    <td align="center" valign="center">248</td>    
  </tr>
  <tr>
    <td align="center" valign="center">IEEEXplore Digital Library</td>
    <td align="center" valign="center">214</td>    
  </tr>
  <tr>
    <td align="center" valign="center">Inspec & Compendex Guide</td>
    <td align="center" valign="center">578</td>
  </tr>
  <tr>
    <td align="center" valign="center">Science Direct</td>
    <td align="center" valign="center">1597</td>
  </tr>
  <tr>
    <td align="center" valign="center">Springer Link</td>
    <td align="center" valign="center">1090</td>
  </tr>
	<caption><i>Search results by database</i></caption>  
</table>
<br>

<h4> Inclusion and Exclusion Criteria </h4>
<table>	    
  <tr>
    <th>Criteria</th>
    <th>Description</th>    
  </tr>
  <tr>
    <td rowspan="3" align="center" valign="center">Inclusion</td>
    <td align="left" valign="center">Peer-reviewed papers describing empirical works</td>    
  </tr>
  <tr>
    <td align="left" valign="center">Studies published in Journals or Conferences, Workshops and Symposium proceedings</td>       </tr>
  <tr>
    <td align="left" valign="center">Written in English</td>
  </tr>
  <tr>
    <td rowspan="3" align="center" valign="center">Exclusion</td>
    <td align="left" valign="center">Lack of empirical results</td>    
  </tr>
  <tr>
    <td align="left" valign="center">Only available in the form of abstract or summary</td>     
  </tr>
  <tr>
    <td align="left" valign="center">Similarity to already selected research (the most recent paper was considered)</td>
  </tr>  
</table>
<br>

<h4> Data Extraction </h4>
We collected 7 conference proceedings papers and 3 journal articles. These eleven manuscripts were used as a starting set for a backward snowballing procedure, that led to three 3 new conference papers. Details at <b>/dataExtraction</b>.
<br>
<br>

<h4> Analysis and Classification </h4>
<p>In order to categorize the 13 collected papers, we created the following two-phase classification scheme.</p>

<img src="/images/TwoPhaseClassificationSqueme.png" alt="Two Phase Classification Scheme" width="70%" height="70%"> 

In the first phase, we were supported by Shaw's work [1], which specifies classifications for research questions, results, and validation in Software Engineering, as follows. 
<br>
<table>	    
  <tr>
    <th>Categories</th>
    <th>Classification</th>    
  </tr>
  <tr>
    <td rowspan="5" align="center" valign="center">Research Question</td>
    <td align="left" valign="center">Method or means of development</td>    
  </tr>
  <tr>
    <td align="left" valign="center">Method for analysis or evaluation</td>
  </tr>
  <tr>
	  <td align="left" valign="center">Design, evaluation, or analysis of a particular instance</td>
  </tr>
  <tr>
	  <td align="left" valign="center">Generalization and characterization</td>
  </tr>
  <tr>
	  <td align="left" valign="center">Feasibility study or exploration</td>
  </tr>
  <tr>
    <td rowspan="7" align="center" valign="center">Research Results</td>
    <td align="left" valign="center">Procedure or technique</td>    
  </tr>
  <tr>
    <td align="left" valign="center">Qualitative or descriptive model</td>     
  </tr>
  <tr>
    <td align="left" valign="center">Empirical model</td>
  </tr>
  <tr>
    <td align="left" valign="center">Analytic model</td>     
  </tr>
  <tr>
    <td align="left" valign="center">Tool or notation</td>     
  </tr>
  <tr>
    <td align="left" valign="center">Specific solution, prototype, answer or judgment</td>     
  </tr>
  <tr>
    <td align="left" valign="center">Report</td>     
  </tr>	
  <tr>
    <td rowspan="6" align="center" valign="center">Research Validation</td>
    <td align="left" valign="center">Analysis</td>    
  </tr>
  <tr>
    <td align="left" valign="center">Evaluation</td>     
  </tr>
  <tr>
    <td align="left" valign="center">Experience</td>
  </tr>
  <tr>
    <td align="left" valign="center">Example</td>     
  </tr>
  <tr>
    <td align="left" valign="center">Persuasion</td>     
  </tr>
  <tr>
    <td align="left" valign="center">Blatant assertion</td>     
  </tr> 
	<caption><i>Research questions, results, and validation categories in Software Engineering</i></caption>
</table>
<br>

<h4> Results </h4>
<table style="width:100%">
  <tr>
    <th rowspan="2">Selected Paper</th>       	
    <th rowspan="2">Venue</th>
   	<th rowspan="2">Year</th>
   	<th rowspan="2">Summary</th>
   	<th colspan="3" align="center" valign="center">Type of Research</th>
  </tr>
  <tr>    
  	<td>Question</td>
    <td>Result</td>
    <td>Validation</td>
  </tr>
  <tr>
    <td>Robbes and Lanza [2]</td>
    <td>ICPC (C)</td>
    <td>2007</td>
    <td>Development sessions understanding</td>
    <td align="center" valign="center">Ch</td>
    <td align="center" valign="center">D</td>
    <td align="center" valign="center">Ev</td>
  </tr>
  <tr>
    <td>Kim and Notkin [3]</td>
    <td>ICSE (C)</td>
    <td>2009</td>
    <td>Systematic change inspection</td>
    <td align="center" valign="center">M</td>
    <td align="center" valign="center">T</td>
    <td align="center" valign="center">Exp</td>
  </tr>
  <tr>
    <td>Bavota and colleagues [4]</td>
    <td>SCAM (C)</td>
    <td>2012</td>
    <td>Refactoring and software defects</td>
    <td align="center" valign="center">Ch</td>
    <td align="center" valign="center">A</td>
    <td align="center" valign="center">An</td>
  </tr>
  <tr>
    <td>Tao and colleagues [5]</td>
    <td>FSE (C)</td>
    <td>2012</td>
    <td>Change understanding</td>
    <td align="center" valign="center">Ch</td>
    <td align="center" valign="center">A</td>
    <td align="center" valign="center">Ev</td>
  </tr>
  <tr>
    <td>Kim and colleagues [6]</td>
    <td>IEEE TRANS SOFTW ENG (J)</td>
    <td>2014</td>
    <td>Refactoring challenges and benefits</td>
    <td align="center" valign="center">Ch</td>
    <td align="center" valign="center">A</td>
    <td align="center" valign="center">Ev</td>
  </tr>
  <tr>
    <td>Zhang and colleagues [7]</td>
    <td>ICSE (C)</td>
    <td>2015</td>
    <td>Systematic change inspection</td>
    <td align="center" valign="center">M</td>
    <td align="center" valign="center">T</td>
    <td align="center" valign="center">Exp</td>
  </tr>
  <tr>
    <td>Matsuda and colleagues [8]</td>
    <td>IWPSE (C)</td>
    <td>2015</td>
    <td>Refactoring-aware change reorganizing</td>
    <td align="center" valign="center">M</td>
    <td align="center" valign="center">T</td>
    <td align="center" valign="center">Exa</td>
  </tr>
  <tr>
    <td>Tao and Kim [9]</td>
    <td>MSR (C)</td>
    <td>2015</td>
    <td>Decomposition of composite change</td>
    <td align="center" valign="center">M</td>
    <td align="center" valign="center">Te</td>
    <td align="center" valign="center">Exp</td>
  </tr>
  <tr>
    <td>Barnett and colleagues [10]</td>
    <td>ICSE (C)</td>
    <td>2015</td>
    <td>Decomposition of composite change</td>
    <td align="center" valign="center">M</td>
    <td align="center" valign="center">T</td>
    <td align="center" valign="center">Exp</td>
  </tr>
  <tr>
    <td>Ge and colleagues [11]</td>
    <td>VL/HCC (C)</td>
    <td>2017</td>
    <td>Refactoring-aware code review</td>
    <td align="center" valign="center">M</td>
    <td align="center" valign="center">T</td>
    <td align="center" valign="center">Exp</td>
  </tr>
  <tr>
    <td>Guo and Song [12]</td>
    <td>COMPSAC (C)</td>
    <td>2017</td>
    <td>Decomposition of composite change</td>
    <td align="center" valign="center">M</td>
    <td align="center" valign="center">T</td>
    <td align="center" valign="center">Exp</td>
  </tr>
  <tr>
    <td>Alves and colleagues [13]</td>
    <td>IEEE TRANS SOFTW ENG (J)</td>
    <td>2018</td>
    <td>Refactoring-aware code review</td>
    <td align="center" valign="center">M</td>
    <td align="center" valign="center">T</td>
    <td align="center" valign="center">Exp</td>
  </tr>
  <tr>
    <td>Chen and colleagues [14]</td>
    <td>J SOFTW-EVOL PROC (J)</td>
    <td>2018</td>
    <td>Clone refactoring inspection</td>
    <td align="center" valign="center">M</td>
    <td align="center" valign="center">T</td>
    <td align="center" valign="center">Exp</td>
  </tr>
</table>
<i>
Venue: C (Conference proceedings), J (Journal article)<br>
Question: Ch (Characterization), M (Method of development)<br>
Result: A (Answer), D (Descriptive model), Te (Technique), T (Tool)<br>
Validation: An (Analysis), Ev (Evaluation), Exa (Example), Exp (Experience)</i>
<br>

<h4> References </h4>
[1] M. Shaw, ''Writing good software engineering research papers: minitutorial,'' in 25th International Conference on Software Engineering (ICSE'03), USA, 2003, pp. 726–36. <br>
[2] R. Robbes and M. Lanza, ''Characterizing and Understanding Development Sessions,'' in 15th IEEE International Conference on Program Comprehension (ICPC'07), Canada, 2007, pp. 155–66. <br>   
[3] M. Kim and D. Notkin, ''Discovering and Representing Systematic Code Changes,'' in 31st International Conference on Software Engineering (ICSE'09), USA, 2009, pp. 309–19. <br>
[4] G. Bavota, B. De Carluccio, A. De Lucia, M. Di Penta, R. Oliveto and O. Strollo, ''When Does a Refactoring Induce Bugs? An Empirical Study,'' in IEEE 12th International Working Conference on Source Code Analysis and Manipulation (SCAM'12), Italy, 2012, pp. 104–13. <br>
[5] Y. Tao, Y. Dang, T. Xie, D. Zhang and S. Kim, ''How Do Software Engineers Understand Code Changes? An Exploratory Study in Industry,'' in ACM SIGSOFT 20th International Symposium on the Foundations of Software Engineering (FSE'12), USA, 2012, pp. 1–11. <br>
[6] M. Kim, T. Zimmermann and N. Nagappan, ''An Empirical Study of Refactoring Challenges and Benefits at Microsoft,'' IEEE Trans. Softw. Eng., vol. 40, issue 7, 2014, pp. 633–49. <br>
[7] T. Zhang, M. Song, J. Pinedo and M. Kim, ''Interactive Code Review for Systematic Changes,'' in 37th International Conference on Software Engineering - Volume 1 (ICSE'15), USA, 2015, pp. 111–22. <br>
[8] J. Matsuda, S. Hayashi and M. Saeki, ''Hierarchical Categorization of Edit Operations for Separately Committing Large Refactoring Results,'' in 14th International Workshop on Principles of Software Evolution (IWPSE'15), USA, 2015, pp. 19–27. <br>
[9] Y. Tao and S. Kim, ''Partitioning Composite Code Changes to Facilitate Code Review,'' in 12th Working Conference on Mining Software Repositories (MSR'15), USA, 2015, pp. 180–90. <br>
[10] M. Barnett, C. Bird, J. Brunet and S. K. Lahiri, ''Helping Developers Help Themselves: Automatic Decomposition of Code Review Changesets, '' in 37th International Conference on Software Engineering (ICSE'15), USA, 2015, pp. 134–44. <br>
[11] X. Ge, S. Sarkar, J. Witschey and E. Murphy-Hill, ''Refactoring-aware code review,'' in IEEE Symposium on Visual Languages and Human-Centric Computing (VL/HCC'17), USA, 2017, pp. 71–9. <br>
[12] B. Guo and M. Song, ''Interactively Decomposing Composite Changes to Support Code Review and Regression Testing,'' in IEEE 41st Annual Computer Software and Applications Conference (COMPSAC'17), Italy, 2017, pp. 118–27. <br>
[13] E. L. G. Alves, M. Song, T. Massoni, P.D.L. Machado, and M. Kim, ''Refactoring Inspection Support for Manual Refactoring Edits,'' IEEE Trans. Softw. Eng., vol. 44, issue 4, 2018, pp. 365–83. <br>
[14] Z. Chen, Y. Kwon and M. Song, ''Clone refactoring inspection by summarizing clone refactorings and detecting inconsistent changes during software evolution,'' J. Softw.-Evol. Proc., vol. 30, issue 10, 2018, pp.e1951–n/a. <br>
