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
    
    
    <script>
        window.onload = function () {
            document.getElementById('login').addEventListener('click', function () {
                AF('pba', 'event', {eventType: 'EVENT',eventCategory: 'conversion', eventName: 'af_login'});
            });
        }
        
        window.onload = function () {
            document.getElementById('register').addEventListener('click', function () {
                AF('pba', 'event', {eventType: 'EVENT',eventCategory: 'conversion', eventName: 'af_register'});
            });
        }
    </script>
  </head>
  
  <body>
    <h3>DevilishBoi Test of AF's PBA PRoduct</h3>
  
    <button type="button" id="register">Sign Up</button>
    <button type="button" id="login">Log in</button>

  </body>

</html>
