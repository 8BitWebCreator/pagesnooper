<img src="https://github.com/8BitWebCreator/pagesnooper/blob/master/20170804_193410.png?raw=true" width="300" height="300" alt="logo">
<HR>
<div class="text">
<p>See the source code of any online site. Find out exactly how the website is structured and scripted.</p>
<p> </p>
<table class="border">
<form action="" method="post" name="page_snooper_form" id="page_snooper_form" onsubmit="pageSnooper(); return false;">
  <tr>
    <td class="single"><strong>Website URL</strong></td>
    <td class="doubledouble"><input type="text" name="input_url" id="input_url" value="" /></td>
  </tr>
  <tr>
    <td class="single"><img src="./includes/php/classes/captcha.php?width=80&height=35&characters=5" style="margin-bottom:1px;vertical-align:bottom;" name="img-captcha" id="img-captcha" width="80" height="35" /></td>
    <td class="doubledouble"><input type="text" name="captcha" id="captcha" value="" class="small" /><p>please type in the exact letters as seen in the image on the left handside</p></td>
  </tr>
  <tr>
    <td class="single"> </td>
    <td class="doubledouble"> </td>
  </tr>
  <tr>
    <td class="single">
    <input type="hidden" id="checksum" name="checksum" value="14527" />
    <div name="process" id="process" style="float:right;"></div>
    </td>
    <td class="doubledouble"><input type="submit" name="page_snooper" id="page_snooper" class="submit" value="View Source Code" /></td>
  </tr>
  <tr>
    <td class="single"> </td>
    <td class="doubledouble"><div name="notification" id="notification" style="display:none;"></div></td>
  </tr>
</form>
</table>
<div name="page_snooper_result" id="page_snooper_result" style="display:none;"></div>
<p> </p>
</div>
</div>
</div>
<!-- END   MAIN PAN        -->
<!-- START SIDEBAR          -->
<div class="sidebar" id="sidebar">
