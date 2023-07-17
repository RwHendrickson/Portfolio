---
layout: page
title: Contact
---

<!--See here for how to do this
https://github.com/toperkin/staticFormEmails/blob/master/README.md-->

<script src="assets/js/jquery.min.js"></script>
<script type="text/javascript">var submitted=false;</script>
<script type="text/javascript">
$('#gform').on('submit', function(e) {
  $('#gform').fadeOut(2000);
  $('#gform').prepend('Your submission has been processed...');
  });
</script>

<form name="gform" id="gform" enctype="text/plain" action="https://docs.google.com/forms/d/e/1FAIpQLSf34QlZ8Il35mNscQ_fLP7MZwcWGJC1iHpKYU5ADn9pBUc3YA/formResponse?" target="hidden_iframe" onsubmit="submitted=true;">
  Name:<br>
  <input type="text" name="entry.904879265" id="entry.904879265"><br>
  Email or Phone Number:<br>
  <input type="text" name="entry.1340553445" id="entry.1340553445"><br>
  Message:<br>
  <input type="textarea" name="entry.644807198" id="entry.644807198"><br>
  <input type="submit" value="Submit">
</form>
<iframe name="hidden_iframe" id="hidden_iframe" style="display:none;" onload="if(submitted) {}"></iframe>
