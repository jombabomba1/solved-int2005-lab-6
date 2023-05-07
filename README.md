Download Link: https://assignmentchef.com/product/solved-int2005-lab-6
<br>
<strong>ER Modeling </strong>

<strong>Topic: </strong>

<ol>

 <li>Know the symbols and vocabulary of UML notation for ERD</li>

 <li>Use the symbols to represent the Cardinality Classifications: Mandatory, Optional, 1-M, M-N, 1-1</li>

 <li>Understand important relationship patterns: 1-M, M-N, 1-1.</li>

</ol>




<table width="679">

 <tbody>

  <tr>

   <td width="0"> </td>

   <td colspan="2" width="362"><strong>UML Notation </strong></td>

   <td colspan="2" width="317"><strong>Crown’s Foot Notation </strong></td>

  </tr>

  <tr>

   <td width="0"> </td>

   <td colspan="2" width="362">       0..1                   Zero or one1..1                   Exactly one0..*                    Zero or many1..*                    One or many        Staff                  Entity name        staffNo              Primary Key</td>

   <td colspan="2" width="317">         |                      Mandatory o                    Optional |                     One Many CourseNo         Primary KeyCrsDesc            Required/Not NullCrsUnit              Optional/Nullable</td>

  </tr>

  <tr>

   <td width="0"> </td>

   <td colspan="2" width="362">Each <strong>entity1</strong> { must be | may be}  Relationship</td>

   <td colspan="2" width="317">_name  {one or more | exactly one} <strong>entity2</strong></td>

  </tr>

  <tr>

   <td width="0"> </td>

   <td colspan="2" width="362">A staff must be assigned to exactly one branch,</td>

   <td colspan="2" width="317">  A branch must have one or many staffs</td>

  </tr>

  <tr>

   <td width="0"> </td>

   <td colspan="2" width="362"> </td>

   <td colspan="2" width="317"> </td>

  </tr>

  <tr>

   <td width="0"> </td>

   <td colspan="2" width="362">A staff may be assigned to one branch, A branc</td>

   <td colspan="2" width="317">h may have one or many staffs</td>

  </tr>

  <tr>

   <td width="0"> </td>

   <td colspan="2" width="362"> </td>

   <td colspan="2" width="317"> </td>

  </tr>

  <tr>

   <td width="0"> </td>

   <td colspan="4" width="679">A staff may be assigned to exactly one branch, A branch must have one or many staffs</td>

  </tr>

  <tr>

   <td colspan="2" width="362"> </td>

   <td colspan="2" width="317"> </td>

   <td width="0"> </td>

  </tr>

  <tr>

   <td colspan="2" width="362">A staff must be assigned to exactly one branch,</td>

   <td colspan="2" width="317"> A branch may have one or many staffs</td>

   <td width="0"> </td>

  </tr>

  <tr>

   <td colspan="2" width="362"> </td>

   <td colspan="2" width="317"> </td>

   <td width="0"> </td>

  </tr>

  <tr>

   <td colspan="2" width="362">A staff must be assigned to one or more branch staffs</td>

   <td colspan="2" width="317">es, A branch must have one or many</td>

   <td width="0"> </td>

  </tr>

  <tr>

   <td colspan="2" width="362"> </td>

   <td colspan="2" width="317"> </td>

   <td width="0"> </td>

  </tr>

  <tr>

   <td width="0"></td>

   <td width="361"></td>

   <td width="0"></td>

   <td width="316"></td>

   <td width="0"></td>

  </tr>

 </tbody>

</table>







<strong>For more information about MySQL Workbench Data Modeling </strong><a href="https://dev.mysql.com/doc/workbench/en/wb-data-modeling.html">https://dev.mysql.com/doc/workbench/en/wb</a><a href="https://dev.mysql.com/doc/workbench/en/wb-data-modeling.html">–</a><a href="https://dev.mysql.com/doc/workbench/en/wb-data-modeling.html">data</a><a href="https://dev.mysql.com/doc/workbench/en/wb-data-modeling.html">–</a><a href="https://dev.mysql.com/doc/workbench/en/wb-data-modeling.html">modeling.html</a>




<strong><u>Question:</u> According to the given requirements of ABC company, please identify entities and its attributes (your design) and draw a Entity-Relationship Diagram (ERD) using MySQL Workbench. </strong>




<u>Requirements:</u>




ABC company, a world-wide company, plan to develop a Sales system to keep and manage sales information of the company. To do this, the company assign some IT staffs to design Sales database. The important data are products, customers, orders, employees and offices. The business constraints are in the following.

<ul>

 <li>Each CUSTOMER must buy one or more ORDERS. Each ORDER must be belonged to exactly one CUSTOMER.</li>

 <li>Each EMPLOYEE must be assigned to exactly one OFFICE. Each OFFICE may has one or more EMPLOYEES.</li>

 <li>Each PRODUCT may be bought by one or more ORDERS. Each ORDER must have one or more PRODUCTS.</li>

 <li>Each EMPLOYEE may be responsible for one or more CUSTOMERS. Each CUSTOMER must be assigned to exactly one EMPLOYEE.</li>

</ul>

<strong>          </strong>

<strong><u>Instructions:</u></strong>




<ul>

 <li>Save your diagram as a “sales_erd_<em>xxxxx</em>.mwb” file stored in your computer.</li>

 <li>Save your diagram [Using the menu: Export &gt; Export as PNG…] as an image file with file named “sales_erd_<em>xxxxx</em>.png” and submit the diagram into LEB2 system – Note:  <em>xxxxx = your student id</em></li>

</ul>




<strong> </strong>


