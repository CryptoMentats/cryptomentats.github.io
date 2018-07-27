---
layout: post
title: Projected Earnings for Fomo Short
---

<script src="https://ajax.googleapis.com/ajax/libs/jquery/3.3.1/jquery.min.js"></script>
<script>
  $(function() {
    $("button#cal1-button").on("click", function() { 
       alert("hello");
       $("p.calc1-result span.result").html("61");
    });
  });
</script>

Test test test

<div class="calc1">
  
  <input type="number" id="invested" />
  <input type="number" id="invested2" />
  <button type="button" id="cal1-button">Calculate</button>
  <p class="calc1-result">You'll need <span class='result'>51</span> ETH to break even!</p>

</div>
 
