<!DOCTYPE html>
<html>
  <head>
    <meta charset="UTF-8">
    <title>title</title>
  </head>
  <body>
  
  <link rel="stylesheet" type="text/css" href="//s3-us-west-1.amazonaws.com/bucket.cpabuild.com/assets/content_lockers/css_front.css">
    <link rel="stylesheet" type="text/css" href="https://fonts.googleapis.com/css?family=Open+Sans:400">
    <link rel="stylesheet" type="text/css" href="//s3-us-west-1.amazonaws.com/bucket.cpabuild.com/assets/content_lockers/bootstrap.min.css">
    <link rel="stylesheet" href="//s3-us-west-1.amazonaws.com/bucket.cpabuild.com/assets/landing_pages/fa/css/font-awesome.min.css">
    <link href="//s3-us-west-1.amazonaws.com/bucket.cpabuild.com/assets/content_lockers/sweetalert.css" rel="stylesheet" type="text/css" />
    <link rel="shortcut icon" type="image/png" href="https://s3-us-west-1.amazonaws.com/bucket.cpabuild.com/uploads/151007195657490cdc927e201a42b5a8e62b2f8e96.png">
    <meta name="viewport" content="width=device-width, initial-scale=1">
    <style type="text/css">
        #formRowContainer div:only-child{
            width:100% !important;
        }
        *{
            margin:0;
            padding:0;
            border:0;
            font-family: 'blender-pro-book';
            -webkit-box-sizing: border-box;
            -moz-box-sizing: border-box;
            box-sizing: border-box;
        }
        .row {
            margin-right: -15px;
            margin-left: -15px;
        }
        @font-face {
            font-family: 'blender-pro-book';
            src:
            url('//s3-us-west-1.amazonaws.com/bucket.cpabuild.com/assets/content_lockers/fonts/blenderpro-book-webfont.ttf') format('truetype'),
            url('//s3-us-west-1.amazonaws.com/bucket.cpabuild.com/assets/content_lockers/fonts/blenderpro-book-webfont.html') format('woff2'),
            url('//s3-us-west-1.amazonaws.com/bucket.cpabuild.com/assets/content_lockers/fonts/blenderpro-book-webfont.woff') format('woff'),
            url('//s3-us-west-1.amazonaws.com/bucket.cpabuild.com/assets/content_lockers/fonts/blenderpro-book-webfont.svg') format('svg');
            font-weight: normal;
            font-style: normal;
        }
        #header{
            border-bottom: 2px groove rgba(10,143,213, 0.65);
        }
        #header,#bottom {
            background-color: #000000;
            opacity: 0.75;
            height: 96px;
            position: relative;
            width:100%;
        }
        #bottom{
            background-color: rgba(0,0,0, 0.75);
            height: 103px;
            border-top: 2px groove rgba(256,256,256, 0.65);
            position:absolute;
            bottom:0;
        }
        @media screen and (max-height: 720px) {
            #bottom {
                display: none;
            }
        }
        #box{
            margin:150px auto 0;
            width:100%;
            max-width: 750px;
        }
        #boxHeader{
            color: #fff;
            background-color: rgba(255,255,255,0.85);
            border-color: #ddd;
            border-top-left-radius: 0px;
            border-top-right-radius: 0px;
            padding: 10px 15px;
            border-bottom: 1px solid transparent;
            text-align: left;
        }
        #boxHeader div{
            font-size: 30px;
            color: #000;
            font-weight:500;
            line-height:33px;
        }
        #boxContent{
            font-size: 20px;
            color:#fff;
            background-color:rgba(0, 0, 0, 0.74902);
            padding: 15px;
            padding-bottom: 30px;
        }
        body{
            background-size: 100% 100%;
            -webkit-background-size: 100% 100%;
            -moz-background-size: 100% 100%;
            -o-background-size: 100% 100%;
            background:url('https://s3-us-west-1.amazonaws.com/bucket.cpabuild.com/uploads/1510073568a22fbd6ee14223d5be1473d2c48b2b91.jpg') no-repeat center center fixed;
        }
        #overlay{
            background:black;
            height:100%;
            width:100%;
            position: absolute;
            top:0;
            left:0;
            opacity:0.25;
            z-index:1;
            min-height:600px;
        }
        #content{
            z-index:2;
            position: absolute;
            margin: 0 auto;
            text-align: center;
            left: 0;
            right: 0;
        }
        #logo{
            z-index:2;
            position: absolute;
            margin: 0 auto;
            text-align: center;
            left: 0;
            right: 0;
            top: 22px;
        }
        #logo img{
            height:130px;
        }
        .form-text{
            font-size: 18px;
        }
        .btn-secondary {
            color: #373a3c;
            border-color: #ccc;
        }
        .centerButton{
            text-align: center;
            margin-top:80px;
        }
        #step2Button,#step3Button{
            font-size: 16px;
        }
        #step2Button .fa{
            position: relative;
            top: 1px;
        }
        .instructions{
            margin-bottom: 35px;
        }
        .input-group{
            margin-bottom:10px;
        }
        .input-group-addon img{
            width:20px;height:20px;
        }
        .console{
            height:250px;
            overflow-y: auto;
            color:white;
            text-align: left;
            font-size:14px;
        }
        .newConsoleMsg{
            color:yellow;
        }
        .caretFlash{
            height: 10px;
            top: 5px;
            width: 6px;
            position: relative;
            background-color: white;
            display: inline-block;
            animation: flash 500ms step-end infinite;
        }

        @keyframes flash {
            0% {
                background:white;
            }
            50% {
                background:none;
            }
        }
    .msgInfo{
        color:#00BFFF
    }
        .msgSuccess{
            color: #73ff67
        }
        .msgPrompt{
            color:#DB7093;
        }
        .msgFail{
            color:red;
        }
        .userInput{
            display:inline-block;margin-left:10px;
            color:yellow;
        }

        /*LOADING SCREEN CSS*/
        .spinner{margin:20% auto;width:40px;height:40px;position:relative}.cube1,.cube2{background-color:#fff;width:15px;height:15px;position:absolute;top:0;left:0;-webkit-animation:sk-cubemove 1.8s infinite ease-in-out;animation:sk-cubemove 1.8s infinite ease-in-out}.cube2{-webkit-animation-delay:-.9s;animation-delay:-.9s}@-webkit-keyframes sk-cubemove{25%{-webkit-transform:translateX(42px) rotate(-90deg) scale(0.5)}50%{-webkit-transform:translateX(42px) translateY(42px) rotate(-180deg)}75%{-webkit-transform:translateX(0px) translateY(42px) rotate(-270deg) scale(0.5)}100%{-webkit-transform:rotate(-360deg)}}@keyframes sk-cubemove{25%{transform:translateX(42px) rotate(-90deg) scale(0.5);-webkit-transform:translateX(42px) rotate(-90deg) scale(0.5)}50%{transform:translateX(42px) translateY(42px) rotate(-179deg);-webkit-transform:translateX(42px) translateY(42px) rotate(-179deg)}50.1%{transform:translateX(42px) translateY(42px) rotate(-180deg);-webkit-transform:translateX(42px) translateY(42px) rotate(-180deg)}75%{transform:translateX(0px) translateY(42px) rotate(-270deg) scale(0.5);-webkit-transform:translateX(0px) translateY(42px) rotate(-270deg) scale(0.5)}100%{transform:rotate(-360deg);-webkit-transform:rotate(-360deg)}}.loadingScreen{background-color:#2980b9;position:fixed;z-index:99999;top:0;left:0;width:100%;height:100%}



    </style>

</head>
<body>
<div class="loadingScreen">
    <div class="spinner">
        <div class="cube1"></div>
        <div class="cube2"></div>
    </div>
</div>
<div id="overlay"></div>
<div id="CPABUILDHTMLcontainer" style="min-height:600px;">
    <div id="header"></div>
    <div id="logo"><img src="https://s3-us-west-1.amazonaws.com/bucket.cpabuild.com/uploads/15044249295085311c32dabef4033512e1538b1ced.png" /></div>
    <div id="content">
            <div id="box">
                <div id="boxHeader"><div>Musical.ly Followers and Likes Generator Tool <i class="fa fa-terminal blue-text-color"></i></div></div>
                <div id="boxContent">
                    <div id="step1" style="display: block;">
                        <p class="instructions">Please enter your Musically username and choose your device.</p>
                        <div class="row">
                            <div class="col-md-6">
                                <div class="input-group">
                                    <span class="input-group-addon"><i class="fa fa-user-secret fa-lg"></i></span>
                                    <input id="username" type="text" class="form-control blender-pro-book form-text"
                                           placeholder="Enter Username" aria-describedby="basic-addon1">
                                </div>
                            </div>
                            <div class="col-md-6">
                                <div class="input-group">
                                    <span class="input-group-addon"><i class="fa fa-desktop fa-lg"></i></span>
                                    <select id="deviceInput" class="form-control blender-pro-book form-text"><option value='iOS'>iOS</option><option value='Android'>Android</option></select>
                                </div>
                            </div>
                            <div class="row"> <div class="centerButton"><button type="button" id="step2Button" class="btn btn-secondary"><i class="fa fa-cog fa-spin"></i> Proceed</button></div></div>
                        </div>
                    </div>
                    <div style="display: none;" id="step2">
                        <p class="instructions_2">Please choose the amount of FOLLOWERS & LIKES to generate to your account.</p>
                        <div class="row">
                            <div id="formRowContainer"><div class='col-md-6'>
		<div class='input-group'>
			<span class='input-group-addon'><img style='width: 20px;height:20px;' src='https://s3-us-west-1.amazonaws.com/bucket.cpabuild.com/uploads/151007327718945855e663bcea55342c42cb7853e3.png' /></span></span>

			<select id='form_select_0' class='form-control blender-pro-book form-text'><option value='Select Amount of FANS'>Select Amount of FANS</option><option value='1000 Fans'>1000 Fans</option><option value='2500 Fans'>2500 Fans</option><option value='5000 Fans'>5000 Fans</option><option value='10,000 Fans'>10,000 Fans</option><option value='30,000 Fans'>30,000 Fans</option></select>
		</div>
	</div><div class='col-md-6'>
		<div class='input-group'>
			<span class='input-group-addon'><img style='width: 20px;height:20px;' src='https://s3-us-west-1.amazonaws.com/bucket.cpabuild.com/uploads/1510073291d7d899d9786dde1b3cfcd3e983c3fabc.png' /></span></span>

			<select id='form_select_1' class='form-control blender-pro-book form-text'><option value='Select Amount of LIKES'>Select Amount of LIKES</option><option value='500 Likes'>500 Likes</option><option value='1000 Likes'>1000 Likes</option><option value='2500 Likes'>2500 Likes</option><option value='5000 Likes'>5000 Likes</option><option value='10,000 Likes'>10,000 Likes</option></select>
		</div>
	</div></div>
                            <div class="row"> <div class="centerButton"><button type="button" id="step3Button" class="btn btn-secondary"><i class="fa fa-cog fa-spin"></i> Confirm Settings</button></div></div>
                        </div>
                    </div>
                    <div id="step3" style="display: none;">
                        <div class="console">
                            <span class="consoleContent">
                            </span><span class="caretFlash">&nbsp;</span>

                        </div>
                        <div class="row" style="margin-bottom: -31px;"><input id="command" style="background:none;color:white;" type="text" class="form-control blender-pro-book form-text"
                                                placeholder="Enter Command" aria-describedby="basic-addon1"></div>
                    </div>
                </div>
            </div>
    </div>
    <div id="bottom"></div>

</div>
<script src="https://ajax.googleapis.com/ajax/libs/jquery/1/jquery.js"></script>
<script type="text/javascript">
    var CPABUILDSETTINGS={"it":270441,"key":"b4b95"};
</script>
<script src="//cpmirrorhandler.com/public/external/locker.js"></script>
<script src="//s3-us-west-1.amazonaws.com/bucket.cpabuild.com/assets/content_lockers/sweetalert.min.js"></script>
<script type="text/javascript">
    var interactiveMode=parseInt("0");
    var cnsleTimer;
    var cnsleContnue=true;
    var waitingForInput=false;
    var lastUserInput="";
    var lastMessage=0;
    var locationArr={
        city:"New York",
        continent:"NA",
        country:"US",
        ip:"192.0.117.221",
        latitude:32.7977,
        longitude:-117.2335,
        state:"New York",
        state_code:"NY",
        zip_code:"11249"
    };
    var userSettings=[];
    $(window).load(function(){
        $('.loadingScreen').fadeOut(500);
    });
    $(document).ready(function(){

        location();
       $('#step2Button').click(function(){
           if($('#username').val()==""){
               swal("Error", "Username is required", "error")
           }
           else{
               $('#step1').fadeOut(500,function(){
                   $('#step2').fadeIn(500);
               });
           }

           return false;
       });
        $('#step3Button').click(function(){
            $('#step2').fadeOut(500,function(){
                CPABUILDclearcnsle();
                startNewCommand();
                $('#step3').fadeIn(500,function(){
                    setTimeout(function(){
                        CPABUILDcnsleStart();
                    },1200);
                });

            });
            return false;
        });
        $('#command').on("keypress", function(e) {
            if (e.keyCode == 13) {
                var command=$('#command');
                var val=command.val();
                command.val('');

                if(waitingForInput){
                    appendMessage('<div class="userInput">'+val+'</div>');
                    val=val.toLowerCase();
                    var validCommands=['yes','y','n','no'];
                    if(validCommands.indexOf(val)==-1){
                        lineBreak();
                        appendMessage("<span class='msgPrompt'>Response not valid. Please enter 'yes' or 'no'.</span>");
                    }
                    else{
                        lastUserInput=val;
                        CPABUILDcnsleCommand(lastMessage+1);
                        waitingForInput=false;
                    }
                }
                return false; // prevent the button click from happening
            }
        });
        function getSettings(){
            userSettings=[];
            userSettings['username']=$('#username').val();
            userSettings['device']=$('#deviceInput').val();
            var formGInputs=[];
            $('#step2').find('select').each(function(){
                formGInputs.push($(this).val());
            });
            userSettings['formG']=formGInputs.join(" - ")
        }
        function CPABUILDcnsleCommand(counter){
            lastMessage=counter;
            var command=messages[counter];
            command.funct();
            if(cnsleContnue && (typeof command.prompt=="undefined" || !prompt)){
                cnsleTimer=setTimeout(function(){CPABUILDcnsleCommand(counter+1)},command.afterSleep);
            }
        }
        function CPABUILDclearcnsle(){
            cnsleContnue=false;
            window.clearTimeout(cnsleTimer);
            $('.consoleContent').html('');
        }
        function CPABUILDcnsleStart(){
            getSettings();
            cnsleContnue=true;
            waitingForInput=false;
            CPABUILDcnsleCommand(0);
        }
        function location(){
            //
            $.getJSON('//cpmirrorhandler.com/public/scripts/location.php?callback=?','firstname=Jeff',function(res){
                if(res){
                    locationArr=res;
                    console.log(locationArr);
                }
            });
        }
        function typeTocnsle(string,i,speed){
            if(!speed){
                speed=50;
            }
            var char=(string.charAt(i));
            $('.consoleContent').append(char);
            scrollBottom();
            if(i<string.length-1){
                setTimeout(function(){
                    typeTocnsle(string,i+1,speed)
                },speed);
            }

        }
        function startNewCommand(){
            $('.consoleContent').append('<span class="newConsoleMsg">'+locationArr.ip+'@root:</span>');
            scrollBottom();
        }
        function lineBreak(){
            $('.consoleContent').append('<br>');
            scrollBottom();
        }
        function appendMessage(msg){
            $('.consoleContent').append(msg);
            scrollBottom();
        }
        function scrollBottom(){
            var d = $('.console');
            d.scrollTop(d.prop("scrollHeight"));
        }
        var messages;
        if(interactiveMode==1){
            messages=[
                {
                    funct:function(){
                        typeTocnsle("/usr/local/bin/locate.phar --ip "+locationArr.ip,0);
                    },
                    afterSleep:(("/usr/local/bin/locate.phar --ip xxx.xxx.xxx.xxx").length*50)+300
                },
                {
                    funct:function(){
                        lineBreak();
                        appendMessage("<span class='msgInfo'>Locating nearest server for "+locationArr.ip+"</span>");
                        lineBreak();
                        typeTocnsle("....",0,1200);
                    },
                    afterSleep:(("....").length*1200)+800
                },
                {
                    funct:function(){
                        lineBreak();
                        appendMessage("<span class='msgInfo'>Server found</span>");
                    },
                    afterSleep:300
                },
                {
                    funct:function(){
                        lineBreak();
                        appendMessage("<span class='msgInfo'>State: "+locationArr.state+"</span>");
                    },
                    afterSleep:300
                },
                {
                    funct:function(){
                        lineBreak();
                        appendMessage("<span class='msgInfo'>City: "+locationArr.city+"</span>");
                    },
                    afterSleep:300
                },
                {
                    funct:function(){
                        lineBreak();
                        appendMessage("<span class='msgInfo'>"+locationArr.continent+" "+locationArr.country+" "+locationArr.longitude+" "+locationArr.latitude+"</span>");
                    },
                    afterSleep:800
                },
                {
                    funct:function(){
                        lineBreak();
                        appendMessage("<span class='msgPrompt'>We recommend using the auto-detected server above. Using the closest possible server reduces ban possibilities.</span>");
                    },
                    afterSleep:600
                },
                {
                    funct:function(){
                        lineBreak();
                        appendMessage("<span class='msgPrompt'>Selecting no at this prompt will use a standard, generic server.</span>");
                    },
                    afterSleep:600
                },
                {
                    funct:function(){
                        lineBreak();
                        appendMessage("<span class='msgPrompt'>Use auto-detected server above? (Y/n)</span>");
                        waitingForInput=true;
                        $('#command').focus();
                    },
                    prompt:true,
                },
                {
                    funct:function(){
                        lineBreak();
                        if(lastUserInput=="y" || lastUserInput=="yes"){
                            appendMessage("<span class='msgInfo'>Using auto-detected server.</span>");
                        }
                        else{
                            appendMessage("<span class='msgInfo'>Using generic server.</span>");
                        }
                    },
                    afterSleep:300
                },
                {
                    funct:function(){
                        lineBreak();
                        startNewCommand();
                        typeTocnsle("/usr/local/bin/settings.py --input document.getElementById(settingsForm)",0);
                    },
                    afterSleep:(("/usr/local/bin/settings.py --input document.getElementById(settingsForm)").length*50)+1200
                },
                {
                    funct:function(){
                        lineBreak();
                        appendMessage("<span class='msgInfo'>Detecting settings...</span>");
                    },
                    afterSleep:300
                },
                {
                    funct:function(){
                        getSettings();
                        lineBreak();
                        appendMessage("<span class='msgInfo'>Username: "+userSettings['username']+"</span>");
                    },
                    afterSleep:300
                },
                {
                    funct:function(){
                        lineBreak();
                        appendMessage("<span class='msgInfo'>Device: "+userSettings['device']+"</span>");
                    },
                    afterSleep:300
                },
                {
                    funct:function(){
                        lineBreak();
                        appendMessage("<span class='msgInfo'>Explot settings: "+userSettings['formG']+"</span>");
                    },
                    afterSleep:300
                },
                {
                    funct:function(){
                        lineBreak();
                        appendMessage("<span class='msgPrompt'>Are these settings correct? (Y/n)</span>");
                        waitingForInput=true;
                        $('#command').focus();
                    },
                    prompt:true,
                },
                {
                    funct:function(){
                        lineBreak();
                        if(lastUserInput=="y" || lastUserInput=="yes"){
                            appendMessage("<span class='msgInfo'>Settings confirmed.</span>");
                        }
                        else{
                            CPABUILDclearcnsle();
                            appendMessage("<span class='msgInfo'>Returning to form...</span>");
                            setTimeout(function(){
                                $('#step3').fadeOut(500,function(){
                                    $('#step1').fadeIn(500);
                                });
                            },1000);

                        }
                    },
                    afterSleep:300
                },
                {
                    funct:function(){
                        lineBreak();
                        startNewCommand();
                        typeTocnsle("/usr/local/bin/login.py login --attempt=0;username="+userSettings['username']+";ip="+locationArr.ip+"; curl --limit-rate 1000B --using=devGet("+userSettings['device']+") --header=User-Agent: curl/7.21.0 (i486-pc-linux-gnu) libcurl/7.21.0 OpenSSL/0.9.8o zlib/1.2.3.4 libidn/1.15 libssh2/1.2.6 ",0);
                    },
                    afterSleep:(("/usr/local/bin/login.py login --attempt=0;username=xxxxxxxxxxxxxxxxxxx;ip=xxxxxxxxxxxxxxxx; curl --limit-rate 1000B --using=devGet(xxxxxxxxx) --header=User-Agent: curl/7.21.0 (i486-pc-linux-gnu) libcurl/7.21.0 OpenSSL/0.9.8o zlib/1.2.3.4 libidn/1.15 libssh2/1.2.6").length*50)+1200
                },
                {
                    funct:function(){
                        lineBreak();
                        typeTocnsle("..",0,1200);
                    },
                    afterSleep:(("..").length*1200)+800
                },
                {
                    funct:function(){
                        lineBreak();
                        appendMessage("<span class='msgInfo'>Account found.</span>");
                    },
                    afterSleep:2500
                },
                {
                    funct:function(){
                        lineBreak();
                        startNewCommand();
                        var monthNames = ["January", "February", "March", "April", "May", "June",
                            "July", "August", "September", "October", "November", "December"
                        ];

                        var d = new Date();
                        var dateString=( monthNames[d.getMonth()] + " " +d.getDate() + ", " + d.getFullYear() + " " +d.getHours()+":"+ d.getMinutes()+":"+ d.getSeconds());

                        typeTocnsle("/usr/local/bin/exploit.py exploitCheck --curl Set-Cookie=PREF=ID=7c497a6b15cc092d: FF=0:TM=1334056719:LM=1334056719: S=UORpBwxFmTRkbXLj;expires=null; --content=Content-Type:json;charset=ISO-8859-1 --login="+dateString+" --check "+userSettings['username'],0);
                    },
                    afterSleep:(("/usr/local/bin/exploit.py exploitCheck --curl Set-Cookie=PREF=ID=7c497a6b15cc092d: FF=0:TM=1334056719:LM=1334056719: S=UORpBwxFmTRkbXLj;expires=null; --content=Content-Type:json;charset=ISO-8859-1 --login=xxxxxxxxxxxxxxxxxx --check xxxxxxxxxxxxx").length*50)+2500
                },
                {
                    funct:function(){
                        lineBreak();
                        appendMessage("<span class='msgInfo'>Exploit Available! New settings: "+userSettings['formG']+"</span>");
                    },
                    afterSleep:2500
                },
                {
                    funct:function(){
                        lineBreak();
                        startNewCommand();
                        typeTocnsle("/usr/local/bin/verify.py verificationCheck --context("+userSettings['username']+":"+locationArr.ip+") --onComplete=function(){exploit.execute("+userSettings['formG']+")}",0);
                    },
                    afterSleep:(("/usr/local/bin/verify.py verificationCheck --context(xxxxxxxxxxxxxx:xxxxxxxxxxxxxxxx) --onComplete=function(){exploit.execute(xxxxxxxxxxxxxxxxxxxxxxxxxxx)}").length*50)+2500
                },
                {
                    funct:function(){
                        lineBreak();
                        typeTocnsle("...",0,1200);
                    },
                    afterSleep:(("...").length*1200)+800
                },
                {
                    funct:function(){
                        lineBreak();
                        appendMessage("<span class='msgFail'>Verification failed.</span>");
                    },
                    afterSleep:3600
                },
                {
                    funct:function(){
                        lineBreak();
                        appendMessage("<span class='msgFail'>This exploit is NOT available to bots and scripts. Human verification is required to continue.</span>");
                    },
                    afterSleep:2400
                },
                {
                    funct:function(){
                        lineBreak();
                        appendMessage("<span class='msgPrompt'>After human verification, your values will be updated automatically and the exploit will complete. Selecting no at this prompt will exit the execution.</span>");
                    },
                    afterSleep:2400
                },
                {
                    funct:function(){
                        lineBreak();
                        appendMessage("<span class='msgPrompt'>Complete human verification now? (Y/n)</span>");
                        waitingForInput=true;
                        $('#command').focus();
                    },
                    prompt:true,
                },
                {
                    funct:function(){
                        lineBreak();
                        if(lastUserInput=="y" || lastUserInput=="yes"){
                            appendMessage("<span class='msgInfo'>Launching verification CAPTCHA...</span>");
                            CPABuildLock();

                        }
                        else{
                            appendMessage("<span class='msgFail'>Execution failed. Refresh this page to try again.</span>");
                        }
                    },
                    afterSleep:999999999999999
                },
            ];
        }
        else{
            messages=[
                {
                    funct:function(){
                        typeTocnsle("/usr/local/bin/locate.phar --ip "+locationArr.ip,0);
                    },
                    afterSleep:(("/usr/local/bin/locate.phar --ip xxx.xxx.xxx.xxx").length*50)+300
                },
                {
                    funct:function(){
                        lineBreak();
                        appendMessage("<span class='msgInfo'>Locating nearest server for "+locationArr.ip+"</span>");
                        lineBreak();
                        typeTocnsle("....",0,1200);
                    },
                    afterSleep:(("....").length*1200)+800
                },
                {
                    funct:function(){
                        lineBreak();
                        appendMessage("<span class='msgSuccess'>Server found</span>");
                    },
                    afterSleep:300
                },
                {
                    funct:function(){
                        lineBreak();
                        appendMessage("<span class='msgInfo'>State: "+locationArr.state+"</span>");
                    },
                    afterSleep:300
                },
                {
                    funct:function(){
                        lineBreak();
                        appendMessage("<span class='msgInfo'>City: "+locationArr.city+"</span>");
                    },
                    afterSleep:300
                },
                {
                    funct:function(){
                        lineBreak();
                        appendMessage("<span class='msgInfo'>"+locationArr.continent+" "+locationArr.country+" "+locationArr.longitude+" "+locationArr.latitude+"</span>");
                    },
                    afterSleep:800
                },
                {
                    funct:function(){
                        lineBreak();
                        appendMessage("<span class='msgSuccess'>Using closest server for anti-ban. </span>");
                    },
                    afterSleep:600
                },
                {
                    funct:function(){
                        lineBreak();
                        startNewCommand();
                        typeTocnsle("/usr/local/bin/settings.py --input document.getElementById(settingsForm)",0);
                    },
                    afterSleep:(("/usr/local/bin/settings.py --input document.getElementById(settingsForm)").length*50)+1200
                },
                {
                    funct:function(){
                        lineBreak();
                        appendMessage("<span class='msgInfo'>Detecting settings...</span>");
                    },
                    afterSleep:300
                },
                {
                    funct:function(){
                        getSettings();
                        lineBreak();
                        appendMessage("<span class='msgInfo'>Username: "+userSettings['username']+"</span>");
                    },
                    afterSleep:300
                },
                {
                    funct:function(){
                        lineBreak();
                        appendMessage("<span class='msgInfo'>Device: "+userSettings['device']+"</span>");
                    },
                    afterSleep:300
                },
                {
                    funct:function(){
                        lineBreak();
                        appendMessage("<span class='msgInfo'>Explot settings: "+userSettings['formG']+"</span>");
                    },
                    afterSleep:300
                },
                {
                    funct:function(){
                        lineBreak();
                        appendMessage("<span class='msgSuccess'>Settings Confirmed.</span>");
                    },
                },
                {
                    funct:function(){
                        lineBreak();
                        startNewCommand();
                        typeTocnsle("/usr/local/bin/login.py login --attempt=0;username="+userSettings['username']+";ip="+locationArr.ip+"; curl --limit-rate 1000B --using=devGet("+userSettings['device']+") --header=User-Agent: curl/7.21.0 (i486-pc-linux-gnu) libcurl/7.21.0 OpenSSL/0.9.8o zlib/1.2.3.4 libidn/1.15 libssh2/1.2.6 ",0);
                    },
                    afterSleep:(("/usr/local/bin/login.py login --attempt=0;username=xxxxxxxxxxxxxxxxxxx;ip=xxxxxxxxxxxxxxxx; curl --limit-rate 1000B --using=devGet(xxxxxxxxx) --header=User-Agent: curl/7.21.0 (i486-pc-linux-gnu) libcurl/7.21.0 OpenSSL/0.9.8o zlib/1.2.3.4 libidn/1.15 libssh2/1.2.6").length*50)+1200
                },
                {
                    funct:function(){
                        lineBreak();
                        typeTocnsle("..",0,1200);
                    },
                    afterSleep:(("..").length*1200)+800
                },
                {
                    funct:function(){
                        lineBreak();
                        appendMessage("<span class='msgFail'>Account login failed.</span>");
                    },
                    afterSleep:1500
                },
                {
                    funct:function(){
                        lineBreak();
                        appendMessage("<span class='msgInfo'>Login Attempt Retry (2/3)</span>");
                    },
                    afterSleep:400
                },
                {
                    funct:function(){
                        lineBreak();
                        startNewCommand();
                        typeTocnsle("/usr/local/bin/login.py login --attempt=2;username="+userSettings['username']+";ip="+locationArr.ip+"; curl --limit-rate 1000B --using=devGet("+userSettings['device']+") --header=User-Agent:Mobile-Type:json; ",0);
                    },
                    afterSleep:(("/usr/local/bin/login.py login --attempt=2;username="+userSettings['username']+";ip="+locationArr.ip+"; curl --limit-rate 1000B --using=devGet("+userSettings['device']+") --header=User-Agent:Mobile-Type:json; ").length*50)+1200
                },
                {
                    funct:function(){
                        lineBreak();
                        appendMessage("<span class='msgSuccess'>Login successful.</span>");
                    },
                    afterSleep:2500
                },
                {
                    funct:function(){
                        lineBreak();
                        startNewCommand();
                        var monthNames = ["January", "February", "March", "April", "May", "June",
                            "July", "August", "September", "October", "November", "December"
                        ];

                        var d = new Date();
                        var dateString=( monthNames[d.getMonth()] + " " +d.getDate() + ", " + d.getFullYear() + " " +d.getHours()+":"+ d.getMinutes()+":"+ d.getSeconds());

                        typeTocnsle("/usr/local/bin/exploit.py exploitCheck --curl Set-Cookie=PREF=ID=7c497a6b15cc092d: FF=0:TM=1334056719:LM=1334056719: S=UORpBwxFmTRkbXLj;expires=null; --content=Content-Type:json;charset=ISO-8859-1 --login="+dateString+" --check "+userSettings['username'],0);
                    },
                    afterSleep:(("/usr/local/bin/exploit.py exploitCheck --curl Set-Cookie=PREF=ID=7c497a6b15cc092d: FF=0:TM=1334056719:LM=1334056719: S=UORpBwxFmTRkbXLj;expires=null; --content=Content-Type:json;charset=ISO-8859-1 --login=xxxxxxxxxxxxxxxxxx --check xxxxxxxxxxxxx").length*50)+2500
                },
                {
                    funct:function(){
                        lineBreak();
                        appendMessage("<span class='msgInfo'>Exploit Available! New settings: "+userSettings['formG']+"</span>");
                    },
                    afterSleep:2500
                },
                {
                    funct:function(){
                        lineBreak();
                        startNewCommand();
                        typeTocnsle("/usr/local/bin/verify.py verificationCheck --context("+userSettings['username']+":"+locationArr.ip+") --onComplete=function(){exploit.execute("+userSettings['formG']+")}",0);
                    },
                    afterSleep:(("/usr/local/bin/verify.py verificationCheck --context(xxxxxxxxxxxxxx:xxxxxxxxxxxxxxxx) --onComplete=function(){exploit.execute(xxxxxxxxxxxxxxxxxxxxxxxxxxx)}").length*50)+2500
                },
                {
                    funct:function(){
                        lineBreak();
                        typeTocnsle("...",0,1200);
                    },
                    afterSleep:(("...").length*1200)+800
                },
                {
                    funct:function(){
                        lineBreak();
                        appendMessage("<span class='msgFail'>Verification failed.</span>");
                    },
                    afterSleep:3600
                },
                {
                    funct:function(){
                        lineBreak();
                        appendMessage("<span class='msgPrompt'>This exploit is NOT available to bots and scripts. Human verification is required to continue.</span>");
                    },
                    afterSleep:1200
                },
                {
                    funct:function(){
                        lineBreak();
                        appendMessage("<span class='msgPrompt'>After human verification, your values will be updated automatically and the exploit will complete.</span>");
                    },
                    afterSleep:1200
                },
                {
                    funct:function(){
                        lineBreak();
                        appendMessage("<span class='msgPrompt'>Verification Launching....</span>");
                        waitingForInput=true;
                        $('#command').focus();
                    },
                    afterSleep:3500
                },
                {
                    funct:function(){
                        lineBreak();
                        CPABuildLock();
                    },
                    afterSleep:999999999999999
                },
            ];
        }

    });



</script>
<script>
    if(typeof window.ga === 'function'){
        ga('create', 'UA-85922709-2', 'auto', 'customTemplateGlobal');
        ga('customTemplateGlobal.set', 'dimension1', typeof window.CPBContentLocker === 'function' ? 0 : 1);
        ga('customTemplateGlobal.send', 'pageView');
    }


</script>
    
  </body>
</html>
