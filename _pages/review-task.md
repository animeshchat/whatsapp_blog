---
layout: page
title: Earn Rs. 50 Cash in 5 Easy Steps | Indians Only
description: Complete small easy tasks to earn quick cash via Paytm or Google Pay. 
permalink: /review-task

---

<div>
  
  <br /> 
  
  <h4>Step 1. Download App & Login</h4>
  Use this link to download: 
  
  <button class="btn btn-success" type="submit" value="Submit">
    <a style="color:white" href="https://play.app.goo.gl/?link=https%3A%2F%2Fplay.google.com%2Fstore%2Fapps%2Fdetails%3Fid%3Dapp.getboss.messenger%26referrer%3Dutm_source%253Dreview_campaign%2526utm_medium%253Dreview_campaign">Download</a>
  </button>
  
  <br/>
  Enter phone number and OTP and log into app.
  
  <br/><br/><br />

  <h4>Step 2. Take 1st Screenshot after login</h4>
  <img src="https://storage.googleapis.com/bossapp-website-bucket/assets/step-%20%20logged%20in.svg.png"/>

  <br/><br/><br />

  <h4>Step 3. Go to play-store, give 5 stars rating & copy-paste below review</h4>
  
  <div class="flex">
  <textarea style="line-height:110%"  id="review_text" name="review_text" rows="5" >
    please wait...
  </textarea>

  <button class="btn btn-success v-center" style="margin-left:1em" onclick="myFunction()">Copy</button>
  </div>
  <br/><br/>
  Use this link to go to play store:
  <button class="btn btn-success" type="submit" value="Submit">
    <a style="color:white" href="https://play.app.goo.gl/?link=https%3A%2F%2Fplay.google.com%2Fstore%2Fapps%2Fdetails%3Fid%3Dapp.getboss.messenger%26referrer%3Dutm_source%253Dreview_campaign%2526utm_medium%253Dreview_campaign">Click here</a>
  </button>

  <br/><br/><br/>

  <h4>Step 4. Take 2nd Screenshot of review on Play Store</h4>
  <img src="https://storage.googleapis.com/bossapp-website-bucket/assets/step-%20reviews.png"/>

  <br/><br/><br/><br/>

  <h4>Step 5. Submit 1st Screenshot and 2nd Sceenshot with GPay phone number</h4>
  <button class="btn btn-success" type="submit" value="Submit">
    <a style="color:white;padding:1em" href="https://docs.google.com/forms/d/e/1FAIpQLSc9QbDOs0gjph1--fgG1oAyvSVokE0efS-K8iRplSVlknuNYw/viewform">Submit Screenshots</a>
  </button>
  <br/><br/><br/><br/>
</div>


<script>
  function myFunction() {
    var copyText = document.getElementById("review_text");
    copyText.select();
    copyText.setSelectionRange(0, 99999)
    document.execCommand("copy");
    alert("Copied the text: " + copyText.value);
  }
  
  function loadReview() {
  	var xhttp = new XMLHttpRequest();
  	xhttp.onreadystatechange = function() {
  	  if (this.readyState == 4 && this.status == 200) {
  	    document.getElementById("review_text").innerHTML = this.responseText;
  	  }
  	};
    xhttp.open("GET", "https://getboss.app/dashboard/api/get_random_review", true)
		xhttp.send()
  }
  loadReview()
</script>

