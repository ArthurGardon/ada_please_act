<head>
	<link type="text/css" rel="stylesheet" href="stylesheets/main.css" />
</head>


<h2 align="center" header="H1"> Politicians Lie Everytime About Subjects on the Environment, Acknowledge Climate Transformation ! </h2>

## Abstract
<p style="text-align: justify;">
    Now more than ever, <b>climate change</b> is a very hotly debated topic which often comes up in the news. This year alone, the Intergovernmental Panel on Climate Change and World Meteorological Organization released very <b>alarming reports</b> stating that we are "way behind" on the objectives of the Paris Agreement. While there will be some individual action involved if we are to tackle the climate crisis, laws and regulations passed by governments will be imperative to avoid the worst case scenario. Using the <b>Quotebank dataset</b>, we were interested to see whether climate change is used as a <b>campaign promise by politicians</b> or if it really is a <b>subject that is constantly talked about</b>. Furthermore, which political groups are the most involved in proposing solutions and spreading awareness about the pressing climate crisis that we are facing. More importantly : do they Act?
</p>

## Our Goals 
<p style="text-align: justify;">
    Using Quotebank, WikiData, allong with the Environmental indicators for USA dataset, our study aims at giving an answer to the following interogations :
</p>

<ul>
	<li> Who speaks the most about climate change ? </li>
	<li> What is their position on the subject ? </li>
	<li> Do politicians all have the same words and opinions on the subject ? </li>
	<li> What factors affect this position ? </li>
	<li> What are the periods when the subject is most highlighted, and at the heart of the debates ? </li>
	<li> Do voting periods have an impact ? </li>
	<li> Does speaking about the problem mean taking action ? </li>
</ul>

<p style="text-align: justify;">
    The first part of our study was to retrieve for the Quotebank dataset the quotes related to climate-change from 2015 and 2020. Then, we tackled the problem
</p> 

<div class="grid">
  <div class="col-1-2">
         <img src="usa_word_cloud.png" />
  </div>
<div class="wraper"></div>
  <div class="col-1-2">
     <div class="comment">
          <h2 class="commenttitle">Common Words</h2>
	     Top Words appearing
     </div>
  </div>
</div>



## Section 1
<p style="text-align: justify;">
    
</p>    

{% include time_series.html %}

## Section 2
<p style="text-align: justify;">
    Then, we focused on performing an LDA (Latent Dirichlet Allocation) on the dataset, with the aim of extracting the main topics, but especially in order to be able to distribute each document as belonging to a topic. The goal of this section is to highlight the differences in lexicon used by the speakers, and what these differences imply from the opinions of each speaker on climate change.<br><br>
   After running a cross validation on the numbeer of topics, we stood with the solution having the maximum choerence number : 8 topics (à redire). For each topic, we propose a list of the most significant and meaningful terms, and a title that encompasses and interprets the topic.  
</p>

<h3>Topic 1 : General Climate Change</h3>
<table border = "0">
<tbody>
<tr>
  <td>
    <ul>
      <li>Climate</li>
      <li>Change</li>
    </ul>
  </td>
  <td>
    <ul>
      <li>Crisis</li>
      <li>Challenge</li>
    </ul>
  </td>
  <td>
    <ul>
      <li>Action</li>
      <li>Future</li>
    </ul>
  </td>
  <td>
    <ul>
      <li>Important</li>
    </ul>
  </td>
</tr>
</tbody>
</table>

<h3>Topic 2 : Business and Economy</h3>
<table>
<tbody>
<tr>
  <td>
    <ul>
      <li>New</li>
      <li>Energy</li>
    </ul>
  </td>
  <td>
    <ul>
      <li>Work</li>
      <li>Company</li>
    </ul>
  </td>
  <td>
    <ul>
      <li>Business</li>
      <li>Plan</li>
    </ul>
  </td>
  <td>
    <ul>
      <li>Technology</li>
      <li>Forward</li>
    </ul>
  </td>
</tr>
</tbody>
</table>

<h3>Topic 3 : Scientifical Knowledge and Belief</h3>
<table>
<tbody>
<tr>
  <td>
    <ul>
      <li>Trump</li>
      <li>Would</li>
    </ul>
  </td>
  <td>
    <ul>
      <li>Question</li>
      <li>Science</li>
    </ul>
  </td>
  <td>
    <ul>
      <li>Scientist</li>
      <li>Debate</li>
    </ul>
  </td>
  <td>
    <ul>
      <li>View</li>
      <li>Matter</li>
    </ul>
  </td>
</tr>
</tbody>
</table>

<h3>Topic 4 : Concrete Impact of climate change on the Earth and Biodiversity</h3>
<table>
<tbody>
<tr>
  <td>
    <ul>
      <li>Existential</li>
      <li>Threat</li>
      <li>High</li>
    </ul>
  </td>
  <td>
    <ul>
      <li>Water</li>
      <li>Ocean</li>
      <li>Flood</li>
    </ul>
  </td>
  <td>
    <ul>
      <li>Increasing</li>
      <li>Drought</li>
      <li>Weather</li>
    </ul>
  </td>
  <td>
    <ul>
      <li>Disaster</li>
      <li>Biodiversity</li>
      <li>Vulnerable</li>
    </ul>
  </td>
</tr>
</tbody>
</table>

<h3>Topic 5 : Energy</h3>
<table>
<tbody>
<tr>
  <td>
    <ul>
      <li>Greenhouse Gas</li>
      <li>Reduce</li>
    </ul>
  </td>
  <td>
    <ul>
      <li>CO2 Emission</li>
      <li>Fuel</li>
    </ul>
  </td>
  <td>
    <ul>
      <li>Air</li>
      <li>Pollution</li>
    </ul>
  </td>
  <td>
    <ul>
      <li>Cut</li>
      <li>Waste</li>
    </ul>
  </td>
</tr>
</tbody>
</table>

<h3>Topic 6 : International Concern and Cooperation arround Climate Change</h3>
<table>
<tbody>
<tr>
  <td>
    <ul>
      <li>International</li>
      <li>Agreement</li>
    </ul>
  </td>
  <td>
    <ul>
      <li>COP</li>
      <li>Young People</li>
    </ul>
  </td>
  <td>
    <ul>
      <li>Adaptation</li>
      <li>Agriculture</li>
    </ul>
  </td>
  <td>
    <ul>
      <li>Meeting</li>
      <li>Development</li>
    </ul>
  </td>
</tr>
</tbody>
</table>

<h3>Topic 7 : Catastrophic Records</h3>
<table>
<tbody>
<tr>
  <td>
    <ul>
      <li>Human</li>
      <li>Caused</li>
    </ul>
  </td>
  <td>
    <ul>
      <li>Temperature</li>
      <li>Record</li>
    </ul>
  </td>
  <td>
    <ul>
      <li>Earth</li>
      <li>Destruction</li>
    </ul>
  </td>
  <td>
    <ul>
      <li>Human activity</li>
      <li>Wildfire</li>
    </ul>
  </td>
</tr>
</tbody>
</table>

<h3>Topic 8 : Axis of Hope, Democrat's group</h3>
<table>
<tbody>
<tr>
  <td>
    <ul>
      <li>United</li>
      <li>Health Care</li>
    </ul>
  </td>
  <td>
    <ul>
      <li>Long Term</li>
      <li>Federal</li>
    </ul>
  </td>
  <td>
    <ul>
      <li>Across country</li>
      <li>Combating</li>
    </ul>
  </td>
  <td>
    <ul>
      <li>Greta</li>
      <li>Tax</li>
    </ul>
  </td>
</tr>
</tbody>
</table>


<div class="large_content">
{% include LDAvis.html %}
</div>

## Section 3

{% include pie_chart.html %}

