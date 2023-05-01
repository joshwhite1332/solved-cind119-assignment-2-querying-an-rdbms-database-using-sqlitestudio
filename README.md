Download Link: https://assignmentchef.com/product/solved-cind119-assignment-2-querying-an-rdbms-database-using-sqlitestudio
<br>
<strong>Querying an RDBMS database using SQLiteStudio </strong>

Complete this assignment using SQLiteStudio.

<ol>

 <li>Create a database called “sample”.</li>

 <li></li>

</ol>

<table>

 <tbody>

  <tr>

   <td width="96"></td>

  </tr>

  <tr>

   <td></td>

   <td></td>

  </tr>

 </tbody>

</table>

<ul>

 <li>Create a table called “test_data” and load the following data into the table. (5 points)</li>

</ul>

<table width="687">

 <tbody>

  <tr>

   <td width="46"><strong>class </strong></td>

   <td width="45"><strong>age </strong></td>

   <td width="95"><strong>menopause </strong></td>

   <td width="94"><strong>tumor_size </strong></td>

   <td width="86"><strong>node_caps </strong></td>

   <td width="85"><strong>deg_malig </strong></td>

   <td width="66"><strong>breast </strong></td>

   <td width="104"><strong>breast_quad </strong></td>

   <td width="66"><strong>irradiat </strong></td>

  </tr>

  <tr>

   <td width="46">NO</td>

   <td width="45">35</td>

   <td width="95">premeno</td>

   <td width="94">31</td>

   <td width="86">no</td>

   <td width="85">3</td>

   <td width="66">left</td>

   <td width="104">left_low</td>

   <td width="66">no</td>

  </tr>

  <tr>

   <td width="46">NO</td>

   <td width="45">42</td>

   <td width="95">premeno</td>

   <td width="94">22</td>

   <td width="86">no</td>

   <td width="85">2</td>

   <td width="66">right</td>

   <td width="104">right_up</td>

   <td width="66">no</td>

  </tr>

  <tr>

   <td width="46">NO</td>

   <td width="45">30</td>

   <td width="95">premeno</td>

   <td width="94">23</td>

   <td width="86">no</td>

   <td width="85">2</td>

   <td width="66">left</td>

   <td width="104">left_low</td>

   <td width="66">no</td>

  </tr>

  <tr>

   <td width="46">NO</td>

   <td width="45">61</td>

   <td width="95">ge40</td>

   <td width="94">16</td>

   <td width="86">no</td>

   <td width="85">2</td>

   <td width="66">right</td>

   <td width="104">left_up</td>

   <td width="66">no</td>

  </tr>

  <tr>

   <td width="46">NO</td>

   <td width="45">45</td>

   <td width="95">premeno</td>

   <td width="94">2</td>

   <td width="86">no</td>

   <td width="85">2</td>

   <td width="66">right</td>

   <td width="104">right_low</td>

   <td width="66">no</td>

  </tr>

  <tr>

   <td width="46">NO</td>

   <td width="45">64</td>

   <td width="95">ge40</td>

   <td width="94">17</td>

   <td width="86">no</td>

   <td width="85">2</td>

   <td width="66">left</td>

   <td width="104">left_low</td>

   <td width="66">no</td>

  </tr>

  <tr>

   <td width="46">NO</td>

   <td width="45">52</td>

   <td width="95">premeno</td>

   <td width="94">27</td>

   <td width="86">no</td>

   <td width="85">2</td>

   <td width="66">left</td>

   <td width="104">left_low</td>

   <td width="66">no</td>

  </tr>

  <tr>

   <td width="46">NO</td>

   <td width="45">67</td>

   <td width="95">ge40</td>

   <td width="94">21</td>

   <td width="86">no</td>

   <td width="85">1</td>

   <td width="66">left</td>

   <td width="104">left_low</td>

   <td width="66">no</td>

  </tr>

  <tr>

   <td width="46">YES</td>

   <td width="45">41</td>

   <td width="95">premeno</td>

   <td width="94">52</td>

   <td width="86">no</td>

   <td width="85">2</td>

   <td width="66">left</td>

   <td width="104">left_low</td>

   <td width="66">no</td>

  </tr>

  <tr>

   <td width="46">YES</td>

   <td width="45">43</td>

   <td width="95">premeno</td>

   <td width="94">22</td>

   <td width="86">no</td>

   <td width="85">2</td>

   <td width="66">right</td>

   <td width="104">left_up</td>

   <td width="66">no</td>

  </tr>

  <tr>

   <td width="46">YES</td>

   <td width="45">41</td>

   <td width="95">premeno</td>

   <td width="94">1</td>

   <td width="86">no</td>

   <td width="85">3</td>

   <td width="66">left</td>

   <td width="104">central</td>

   <td width="66">no</td>

  </tr>

  <tr>

   <td width="46">YES</td>

   <td width="45">44</td>

   <td width="95">ge40</td>

   <td width="94">27</td>

   <td width="86">no</td>

   <td width="85">2</td>

   <td width="66">left</td>

   <td width="104">left_low</td>

   <td width="66">no</td>

  </tr>

  <tr>

   <td width="46">YES</td>

   <td width="45">61</td>

   <td width="95">lt40</td>

   <td width="94">14</td>

   <td width="86">no</td>

   <td width="85">1</td>

   <td width="66">left</td>

   <td width="104">right_up</td>

   <td width="66">no</td>

  </tr>

  <tr>

   <td width="46">YES</td>

   <td width="45">55</td>

   <td width="95">ge40</td>

   <td width="94">26</td>

   <td width="86">no</td>

   <td width="85">3</td>

   <td width="66">left</td>

   <td width="104">right_up</td>

   <td width="66">no</td>

  </tr>

  <tr>

   <td width="46">YES</td>

   <td width="45">44</td>

   <td width="95">premeno</td>

   <td width="94">32</td>

   <td width="86">no</td>

   <td width="85">3</td>

   <td width="66">left</td>

   <td width="104">left_up</td>

   <td width="66">no</td>

  </tr>

 </tbody>

</table>

<ol start="3">

 <li>Write SQL queries to select/compute data from the “test_data” table. (2 points each)

  <ol>

   <li>Select all rows where menopause column has the value “ge40”.</li>

   <li>Select all rows where age is less than 41.</li>

   <li>Select all rows where age is less than 41 and menopause column has the value “ge40”.</li>

   <li>Compute the average age across all rows.</li>

   <li>Compute average age across rows where deg_malig value is equal to 3.</li>

  </ol></li>

</ol>

Reference: Full dataset available at <a href="https://grouplens.org/datasets/movielens/">GroupLens</a>