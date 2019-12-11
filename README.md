<!DOCTYPE html>

<html>
  <head>
    <title> PBA Tests</title>
    <!-- AppsFlyer web SDK -->
    <script>
    !function(t,e,n,s,a,c,i,o,p){t.AppsFlyerSdkObject=a,t.AF=t.AF||function(){
    (t.AF.q=t.AF.q||[]).push([Date.now()].concat(Array.prototype.slice.call(arguments)))},
    t.AF.id=t.AF.id||i,t.AF.plugins={},o=e.createElement(n),p=e.getElementsByTagName(n)[0],o.async=1,
    o.src="https://websdk.appsflyer.com?"+(c.length>0?"st="+c.split(",").sort().join(",")+"&":"")+(i.length>0?"af_id="+i:""),
    p.parentNode.insertBefore(o,p)}(window,document,"script",0,"AF","pba","65738378-bd4e-4d5f-b6b2-a7dc38240cfe")
    </script>
  </head>
  
  <body>
    <h3>DevilishBoi Test of AF's PBA PRoduct</h3>
  
    <form>
        <fieldset>
          <label for="rev">Revenue</label>
          <input type="number" id="rev" step="1.00" min="1.0" max="49.99" value="4.99">
          
          <label for="submit">Submit</label>
          <input type="submit" id="submit">
        </fieldset>
    </form>
  </body>

</html>
