<h2> <span style="color:red"> Refactoring-Aware and Code Review: A Systematic Mapping Study </span></h2>

<p>Details on our <b>systematic literature mapping</b> study!</p>
<img src="/images/splab.png" alt="SPLab Logo" width="100" height="100">
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
    <td align="left" valign="center">Peer-reviewed papers describing empirical works.</td>    
  </tr>
  <tr>
    <td align="left" valign="center">Studies published in Journals or Conferences, Workshops and Symposium proceedings.</td>       </tr>
  <tr>
    <td align="left" valign="center">Written in English.</td>
  </tr>
  <tr>
    <td rowspan="3" align="center" valign="center">Exclusion</td>
    <td align="left" valign="center">Lack of empirical results.</td>    
  </tr>
  <tr>
    <td align="left" valign="center">Only available in the form of abstract or summary.</td>     
  </tr>
  <tr>
    <td align="left" valign="center">Similarity to already selected research (the most recent paper was considered).</td>
  </tr>  
</table>
<br>
	

<h4> Data Extraction </h4>
We collected 7 conference proceedings papers and 3 journal articles. These eleven manuscripts were used as a starting set for a backward snowballing procedure, that led to three 3 new conference papers. Details at <b>/dataExtraction</b>.
<br>


<h4> Analysis and Classification </h4>
<p>In order to categorize the 13 collected papers, we created the following two-phase classification scheme.</p>

<img src="/images/TwoPhaseClassificationSqueme.png" alt="Two Phase Classification Scheme" width="70%" height="70%"> 

In the first phase, we were supported by Shaw's work [1], which specifies classifications for research questions, results, and validation in Software Engineering, as follows. 

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
<br>

<h4> References </h4>
[1] M. Shaw, "Writing good software engineering research papers: minitutorial," in 25th International Conference on Software Engineering (ICSE'03), USA, 2003, pp. 726-36. 
