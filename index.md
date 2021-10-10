<!DOCTYPE HTML>
<html lang="en">
  <head>
<link rel="stylesheet" href="style.css">
    <meta charset="UTF-8">
<style>
 img{
border: 5px solid rgb(145, 13, 35);
}
</style>
  </head>
  <body>
    <h3>ClassReviews.com</h3> 
    <br><br>
    <p>This website's primary function is to collect class reviews.*<br><br>
      See below to get started<br>
    </p>
    <br><br>
    <form action="submission.html" method="post">
      <label for="class" style="color: white;font-size:25px;font-family: Helvetica, sans-serif;">Select Class:</label>
      <select name="class" id="classes">
        <option value="tech">Tech</option>
        <option value="math">Math</option>
        <option value="science">Science</option>
        <option value="other">Other</option>
      </select>
      <br><br>
      <input type="submit" value="Next">
<h3> Statistics </h3>
	<ul>
	<li> Tech: <p id="tstats" style="text-align:left;"></p>
	<li> Math: <p id="mstats" style="text-align:left;"></p>
	<li> Science: <p id="sstats" style="text-align:left;"></p>
	<li> Other: <p id="ostats" style="text-align:left;"></p>
	</ul>
	<p> (average % of users who left a positive review)</p>
	<script>
	document.getElementById("tstats").innerHTML =
	Math.floor(Math.random() * 100);
	</script>

	<script>
	document.getElementById("mstats").innerHTML =
	Math.floor(Math.random() * 100);
	</script>

	<script>
	document.getElementById("sstats").innerHTML =
	Math.floor(Math.random() * 100);
	</script>
	<script>
	document.getElementById("ostats").innerHTML =
	Math.floor(Math.random() * 100);
	</script>
	<br>
	<br>
	<p style="color: rgb(29, 23, 52)"> WDYM IT'S FAKE?!?!?! </p>
	<br>
	<img src="disclaimer.jpg" alt="disclaimer" width="100px" height="100px">
	<p> *DISCLAIMER! This is just a mockup of a review website! (i.e., due to unavoidable technical errors,
	the website does not actually collect user reviews. Instead, it uses randomly generated numbers in place of review
	statistics.)
	I apologize for any offense created by this randomly generated number system.
  </body>
</html>
