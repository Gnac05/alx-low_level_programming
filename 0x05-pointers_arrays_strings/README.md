# Alx Software Engineer

'''


<!DOCTYPE html>
<html lang="en">
<head>
<meta charset="utf-8">
<meta http-equiv="X-UA-Compatible" content="IE=edge">
<meta name="viewport" content="width=device-width, initial-scale=1">
<!-- The above 3 meta tags *must* come first in the head; any other head content must come *after* these tags -->
<meta name="description" content="">
<meta name="google" content="notranslate">

<script type="text/javascript" src="https://gc.kis.v2.scr.kaspersky-labs.com/FD126C42-EBFA-4E12-B309-BB3FDD723AC1/main.js?attr=r7PZLQYmp8nwn0Zw4BWtkCWUMgmbOMRtCFibgrEN53SoLW7UFK9Zq6VmivEcCeHr9AkqjigwNGTEn6QQBCe2DQ" charset="UTF-8"></script><script>
window.dataLayer = window.dataLayer || [];
dataLayer.push({"userId":197885,"visitorType":"student","batch":{"id":26,"fullNameWithC":"AFR-1122 (C#11)","schoolLocation":{"id":1,"name":"ALX Africa"}},"curriculum":{"id":1,"name":"Foundations"}});

window.gtm_user_custom_event = function (name, options) {
if (typeof name === 'undefined') {
return;
}

window.dataLayer.push({
customEventOptions: typeof options !== 'undefined' ? options : {},
event: name,
});
}
</script>

<!-- Google Tag Manager -->
<script>(function(w,d,s,l,i){w[l]=w[l]||[];w[l].push({'gtm.start':
new Date().getTime(),event:'gtm.js'});var f=d.getElementsByTagName(s)[0],
j=d.createElement(s),dl=l!='dataLayer'?'&l='+l:'';j.async=true;j.src=
'https://www.googletagmanager.com/gtm.js?id='+i+dl;f.parentNode.insertBefore(j,f);
})(window,document,'script','dataLayer','GTM-N4C8MF2');</script>
<!-- End Google Tag Manager -->


<title>Project: 0x05. C - Pointers, arrays and strings | ALX Africa Intranet</title>

<link rel="stylesheet" href="https://use.typekit.net/xgz4ilr.css">
<link rel="stylesheet" media="all" href="/assets/application_alx-3bc505f2e3a9303a2388308cf98416618d0d78415692ec6a831f106956700814.css" />
<script src="https://www.gstatic.com/charts/loader.js"></script>
<script src="/assets/application-35dd1bfa2a15daa7dc2c7f29abbedd235e98278dee45b81fab4fd94785e21388.js"></script>
<link rel="shortcut icon" type="image/x-icon" href="/favicon_alx.ico" />
<meta name="csrf-param" content="authenticity_token" />
<meta name="csrf-token" content="ihlZFftC7z1lXjf7MGo0GGlbyjgbvus48gQitektb_439z70dYnFoyuejvXb2RKSIDhbz43ZlAOqE8n5gk6Gmg" />

<link rel="apple-touch-icon" href="/apple-touch-icon_alx.png">

<!-- HTML5 shim and Respond.js for IE8 support of HTML5 elements and media queries -->
<!--[if lt IE 9]>
<script src="https://oss.maxcdn.com/html5shiv/3.7.2/html5shiv.min.js"></script>
<script src="https://oss.maxcdn.com/respond/1.4.2/respond.min.js"></script>
<![endif]-->

<!-- Store user timezone -->
<script>
Cookies.set('timezone', (new Date()).getTimezoneOffset() / -60.0);
</script>

<!-- intro.js for interactive onboarding -->

<!-- React -->
<script src="/packs/js/application-33d3f3be8be3102c1a22.js"></script>
<link rel="stylesheet" media="screen" href="/packs/css/application-87456da7.css" />
</head>

<body class="signed_in env_production notranslate"
translate="no"
class="notranslate"
data-theme-suffix="_alx">
<!-- Google Tag Manager (noscript) -->
<noscript><iframe src="https://www.googletagmanager.com/ns.html?id=GTM-N4C8MF2"
height="0" width="0" style="display:none;visibility:hidden"></iframe></noscript>
<!-- End Google Tag Manager (noscript) -->


<input type="hidden" id="hbtn-slack-url" value="https://alx-students.slack.com">
<nav class="navbar navbar-default navbar-fixed-top topbar visible-xs">
<div class="navbar-header">
<button type="button" class="navbar-toggle collapsed" data-toggle="collapse" data-target="#navbar-mobile" aria-expanded="false">
<span class="sr-only">Toggle navigation</span>
<span class="icon-bar"></span>
<span class="icon-bar"></span>
<span class="icon-bar"></span>
</button>

<a class="navbar-brand" href="/">
<div class="logo"></div>
</a>  </div>

<div class="collapse navbar-collapse navigation" id="navbar-mobile">
<ul class="nav navbar-nav">



<li data-container="body" data-placement="right" data-toggle="tooltip" title="My Planning"><a href="/planning/me"><div class="icon "><i aria-hidden="true" class="fa fa-calendar "></i></div><div class="visible-xs">My Planning</div></a></li>
<li data-container="body" data-placement="right" data-toggle="tooltip" id="sidebar-current-projects-item" title="Projects"><a href="/projects/current"><div class="icon "><i aria-hidden="true" class="fa fa-code-fork "></i></div><div class="visible-xs">Projects</div></a></li>

<li data-container="body" data-placement="right" data-toggle="tooltip" title="QA Reviews I can make"><a href="/corrections/to_review"><div class="icon "><i aria-hidden="true" class="fa fa-check "></i></div><div class="visible-xs">QA Reviews I can make</div></a></li>

<li data-container="body" data-placement="right" data-toggle="tooltip" title="Evaluation quizzes"><a href="/dashboards/my_current_evaluation_quizzes"><div class="icon "><i aria-hidden="true" class="fa fa-question "></i></div><div class="visible-xs">Evaluation quizzes</div></a></li>

<hr title="My resources">

<li data-container="body" data-placement="right" data-toggle="tooltip" title="Curriculums"><a href="/dashboards/my_curriculums"><div class="icon "><i aria-hidden="true" class="fa fa-graduation-cap "></i></div><div class="visible-xs">Curriculums</div></a></li>
<li data-container="body" data-placement="right" data-toggle="tooltip" id="sidebar-concepts-item" title="Concepts"><a href="/concepts"><div class="icon "><i aria-hidden="true" class="fa fa-file-text "></i></div><div class="visible-xs">Concepts</div></a></li>
<li data-container="body" data-placement="right" data-toggle="tooltip" id="sidebar-dashboards-video-rooms" title="Conference rooms"><a href="/dashboards/video_rooms"><div class="icon "><i aria-hidden="true" class="fa fa-comments "></i></div><div class="visible-xs">Conference rooms</div></a></li>
<li data-container="body" data-placement="right" data-toggle="tooltip" title="Servers"><a href="/servers"><div class="icon "><i aria-hidden="true" class="fa fa-server "></i></div><div class="visible-xs">Servers</div></a></li>
<li data-container="body" data-placement="right" data-toggle="tooltip" id="sidebar-dashboards-my-containers" title="Sandboxes"><a href="/user_containers/current"><div class="icon "><i aria-hidden="true" class="fa fa-terminal "></i></div><div class="visible-xs">Sandboxes</div></a></li>



<hr title="My campus">


<li data-container="body" data-placement="right" data-toggle="tooltip" title="Peers"><a href="/users/peers"><div class="icon "><i aria-hidden="true" class="fa fa-users "></i></div><div class="visible-xs">Peers</div></a></li>
<li data-container="body" data-placement="right" data-toggle="tooltip" title="Captain&#39;s Logs"><a href="/dashboards/my_captain_log"><div class="icon "><i aria-hidden="true" class="fa fa-book "></i></div><div class="visible-xs">Captain&#39;s Logs</div></a></li>


<hr class="visible-xs">

<li>
<div
data-container="body"
data-placement="right"
data-toggle="tooltip"
title="Slack">
<a target="_blank" href="https://alx-students.slack.com">
<div class="image slack">
<div class="inner"></div>
</div>
<div class="visible-xs">Slack</div>
</a>    </div>

<div
data-container="body"
data-placement="right"
data-toggle="tooltip"
title="My Profile">
<a href="/users/my_profile">
<div class="image ">
<div class="inner" style="background-image: url('https://s3.amazonaws.com/alx-intranet.hbtn.io/users/photos/000/197/885/thumb/joker.jpg?X-Amz-Algorithm=AWS4-HMAC-SHA256&amp;X-Amz-Credential=AKIARDDGGGOUSBVO6H7D%2F20221219%2Fus-east-1%2Fs3%2Faws4_request&amp;X-Amz-Date=20221219T210638Z&amp;X-Amz-Expires=600&amp;X-Amz-SignedHeaders=host&amp;X-Amz-Signature=92ce625e61387a3c063bc7a57db6967ce946eb64d04d0e26675adb1b05222637')"></div>
</div>

<div class="visible-xs">My Profile</div>
</a>  </div>
</li>


</ul>
</div>
</nav>

<div class="hidden-xs navigation sidebar">
<a class="logo-container" href="/">
<div class="logo"></div>
</a>
<ul>



<li data-container="body" data-placement="right" data-toggle="tooltip" title="My Planning"><a href="/planning/me"><div class="icon "><i aria-hidden="true" class="fa fa-calendar "></i></div><div class="visible-xs">My Planning</div></a></li>
<li data-container="body" data-placement="right" data-toggle="tooltip" id="sidebar-current-projects-item" title="Projects"><a href="/projects/current"><div class="icon "><i aria-hidden="true" class="fa fa-code-fork "></i></div><div class="visible-xs">Projects</div></a></li>

<li data-container="body" data-placement="right" data-toggle="tooltip" title="QA Reviews I can make"><a href="/corrections/to_review"><div class="icon "><i aria-hidden="true" class="fa fa-check "></i></div><div class="visible-xs">QA Reviews I can make</div></a></li>

<li data-container="body" data-placement="right" data-toggle="tooltip" title="Evaluation quizzes"><a href="/dashboards/my_current_evaluation_quizzes"><div class="icon "><i aria-hidden="true" class="fa fa-question "></i></div><div class="visible-xs">Evaluation quizzes</div></a></li>

<hr title="My resources">

<li data-container="body" data-placement="right" data-toggle="tooltip" title="Curriculums"><a href="/dashboards/my_curriculums"><div class="icon "><i aria-hidden="true" class="fa fa-graduation-cap "></i></div><div class="visible-xs">Curriculums</div></a></li>
<li data-container="body" data-placement="right" data-toggle="tooltip" id="sidebar-concepts-item" title="Concepts"><a href="/concepts"><div class="icon "><i aria-hidden="true" class="fa fa-file-text "></i></div><div class="visible-xs">Concepts</div></a></li>
<li data-container="body" data-placement="right" data-toggle="tooltip" id="sidebar-dashboards-video-rooms" title="Conference rooms"><a href="/dashboards/video_rooms"><div class="icon "><i aria-hidden="true" class="fa fa-comments "></i></div><div class="visible-xs">Conference rooms</div></a></li>
<li data-container="body" data-placement="right" data-toggle="tooltip" title="Servers"><a href="/servers"><div class="icon "><i aria-hidden="true" class="fa fa-server "></i></div><div class="visible-xs">Servers</div></a></li>
<li data-container="body" data-placement="right" data-toggle="tooltip" id="sidebar-dashboards-my-containers" title="Sandboxes"><a href="/user_containers/current"><div class="icon "><i aria-hidden="true" class="fa fa-terminal "></i></div><div class="visible-xs">Sandboxes</div></a></li>



<hr title="My campus">


<li data-container="body" data-placement="right" data-toggle="tooltip" title="Peers"><a href="/users/peers"><div class="icon "><i aria-hidden="true" class="fa fa-users "></i></div><div class="visible-xs">Peers</div></a></li>
<li data-container="body" data-placement="right" data-toggle="tooltip" title="Captain&#39;s Logs"><a href="/dashboards/my_captain_log"><div class="icon "><i aria-hidden="true" class="fa fa-book "></i></div><div class="visible-xs">Captain&#39;s Logs</div></a></li>


<hr class="visible-xs">

<li>
<div
data-container="body"
data-placement="right"
data-toggle="tooltip"
title="Slack">
<a target="_blank" href="https://alx-students.slack.com">
<div class="image slack">
<div class="inner"></div>
</div>
<div class="visible-xs">Slack</div>
</a>    </div>

<div
data-container="body"
data-placement="right"
data-toggle="tooltip"
title="My Profile">
<a href="/users/my_profile">
<div class="image ">
<div class="inner" style="background-image: url('https://s3.amazonaws.com/alx-intranet.hbtn.io/users/photos/000/197/885/thumb/joker.jpg?X-Amz-Algorithm=AWS4-HMAC-SHA256&amp;X-Amz-Credential=AKIARDDGGGOUSBVO6H7D%2F20221219%2Fus-east-1%2Fs3%2Faws4_request&amp;X-Amz-Date=20221219T210638Z&amp;X-Amz-Expires=600&amp;X-Amz-SignedHeaders=host&amp;X-Amz-Signature=92ce625e61387a3c063bc7a57db6967ce946eb64d04d0e26675adb1b05222637')"></div>
</div>

<div class="visible-xs">My Profile</div>
</a>  </div>
</li>


</ul>
</div>


<main>
<div id="layout-bars">





</div>

<article class="">


<div class="project row">
<div class="col-xs-12 col-md-10 col-lg-8 contains-images">

<h1 class="gap">0x05. C - Pointers, arrays and strings</h1>

<div data-react-class="tags/Tags" data-react-props="{&quot;tags&quot;:[{&quot;id&quot;:7,&quot;value&quot;:&quot;C&quot;,&quot;author_id&quot;:null,&quot;created_at&quot;:&quot;2022-06-16T01:59:38.000Z&quot;,&quot;updated_at&quot;:&quot;2022-06-16T01:59:38.000Z&quot;}]}" data-react-cache-id="tags/Tags-0"></div>

<div data-react-class="projects/ProjectMetadata" data-react-props="{&quot;metadata&quot;:{&quot;author&quot;:&quot;Julien Barbier&quot;,&quot;weight&quot;:1,&quot;correction&quot;:{&quot;released&quot;:true,&quot;auto_correction_available_at&quot;:&quot;2022-12-19T06:00:00.000+03:00&quot;,&quot;requires_auto_correction&quot;:true,&quot;requires_manual_correction&quot;:false},&quot;bpi&quot;:{&quot;current&quot;:true,&quot;started&quot;:false,&quot;in_second_deadline&quot;:false,&quot;starts_at&quot;:&quot;2022-12-19T06:00:00.000+03:00&quot;,&quot;ends_at&quot;:&quot;2022-12-20T06:00:00.000+03:00&quot;,&quot;second_deadline_at&quot;:&quot;2022-12-21T06:00:00.000+03:00&quot;}}}" data-react-cache-id="projects/ProjectMetadata-0"></div>







<div id="project_id" style="display: none" data-project-id="216"></div>





<div class="panel panel-default">
<div class="panel-heading">
<h3 class="panel-title">Concepts</h3>
</div>
<div class="panel-body">
<p>
<em>For this project, we expect you to look at these concepts:</em>
</p>

<ul>
<li>
<a href="/concepts/60">Pointers and arrays</a>
</li>
<li>
<a href="/concepts/120">Data Structures</a>
</li>
</ul>
</div>
</div>


<div class="panel panel-default" id="project-description">
<div class="panel-body">
<p><img src="https://s3.amazonaws.com/intranet-projects-files/holbertonschool-low_level_programming/216/IMG_2410.JPG" /></p>

<h2>Resources</h2>

<p><strong>Read or watch</strong>:</p>

<ul>
<li><a href="/rltoken/PVi2XMuApOK3jfhsoqsyXw" title="C - Arrays" target="_blank">C - Arrays</a> </li>
<li><a href="/rltoken/oyHybzYBeFiLUMALpb_usA" title="C - Pointers" target="_blank">C - Pointers</a> </li>
<li><a href="/rltoken/sUeh9qDyW9pePOfJIpx_Bw" title="C - Strings" target="_blank">C - Strings</a> </li>
<li><a href="/rltoken/0k6CD2ZMzSFOMUxMOBiAlQ" title="Memory Layout" target="_blank">Memory Layout</a></li>
</ul>

<h2>Learning Objectives</h2>

<p>At the end of this project, you are expected to be able to <a href="/rltoken/OLGzIaD19ia5NZ-WCMckeg" title="explain to anyone" target="_blank">explain to anyone</a>, <strong>without the help of Google</strong>:</p>

<h3>General</h3>

<ul>
<li>What are pointers and how to use them</li>
<li>What are arrays and how to use them</li>
<li>What are the differences between pointers and arrays</li>
<li>How to use strings and how to manipulate them</li>
<li>Scope of variables</li>
</ul>

<h3>Copyright - Plagiarism</h3>

<ul>
<li>You are tasked to come up with solutions for the tasks below yourself to meet with the above learning objectives.</li>
<li>You will not be able to meet the objectives of this or any following project by copying and pasting someone else&rsquo;s work. </li>
<li>You are not allowed to publish any content of this project.</li>
<li>Any form of plagiarism is strictly forbidden and will result in removal from the program.</li>
</ul>

<h2>Requirements</h2>

<h3>General</h3>

<ul>
<li>Allowed editors: <code>vi</code>, <code>vim</code>, <code>emacs</code></li>
<li>All your files will be compiled on Ubuntu 20.04 LTS using <code>gcc</code>, using the options <code>-Wall -Werror -Wextra -pedantic -std=gnu89</code></li>
<li>All your files should end with a new line</li>
<li>A <code>README.md</code> file, at the root of the folder of the project is mandatory</li>
<li>Your code should use the <code>Betty</code> style. It will be checked using <a href="https://github.com/holbertonschool/Betty/blob/master/betty-style.pl" title="betty-style.pl" target="_blank">betty-style.pl</a> and <a href="https://github.com/holbertonschool/Betty/blob/master/betty-doc.pl" title="betty-doc.pl" target="_blank">betty-doc.pl</a></li>
<li>You are not allowed to use global variables</li>
<li>No more than 5 functions per file</li>
<li>You are not allowed to use the standard library. Any use of functions like <code>printf</code>, <code>puts</code>, etc&hellip; is forbidden</li>
<li>You are allowed to use <a href="https://github.com/holbertonschool/_putchar.c/blob/master/_putchar.c" title="_putchar" target="_blank">_putchar</a></li>
<li>You don&rsquo;t have to push <code>_putchar.c</code>, we will use our file. If you do it won&rsquo;t be taken into account</li>
<li>In the following examples, the <code>main.c</code> files are shown as examples. You can use them to test your functions, but you don&rsquo;t have to push them to your repo (if you do we won&rsquo;t take them into account). We will use our own <code>main.c</code> files at compilation. Our <code>main.c</code> files might be different from the one shown in the examples</li>
<li>The prototypes of all your functions and the prototype of the function <code>_putchar</code> should be included in your header file called <code>main.h</code></li>
<li>Don&rsquo;t forget to push your header file</li>
</ul>

<h2>More Info</h2>

<p>You do not need to learn about pointers to functions, pointers to pointers, multidimensional arrays, arrays of structures, <code>malloc</code> and <code>free</code> - yet.</p>

</div>
</div>




<div class="panel panel-default" id="project-quiz-questions-title">
<div class="panel-heading">
<h3 class="panel-title">
Quiz questions
</h3>
</div>

<div class="panel-body">

<div class="alert alert-info">
<strong>Great!</strong>
You've completed the quiz successfully! Keep going!
<span id="quiz_questions_collapse_toggle"></span>
</div>

<section class="quiz_questions_show_container">
<div class="quiz_question_item_container" data-role="quiz_question427" data-position="13">
<div class=" clearfix" id="quiz_question-427">

<h4 class="quiz_question">

Question #0
</h4>

<!-- Quiz question Body -->
<p>We declare the following variable</p>

<pre><code>int arr[5];
</code></pre>

<p>What is the equivalent of typing <code>arr[2]</code>?</p>


<!-- Quiz question Answers -->
<ul class="quiz_question_answers" data-question-id="427">
<li class="">

<input type="radio" name="427" id="427-1506302266007" value="1506302266007" data-quiz-answer-id="1506302266007" data-quiz-question-id="427" disabled="disabled" />
<label for="427-1506302266007"><p>arr + 2</p>
</label>
</li>

<li class="">

<input type="radio" name="427" id="427-1506302298456" value="1506302298456" data-quiz-answer-id="1506302298456" data-quiz-question-id="427" disabled="disabled" checked="checked" />
<label for="427-1506302298456"><p>*(arr + 2)</p>
</label>
</li>

<li class="">

<input type="radio" name="427" id="427-1506302274650" value="1506302274650" data-quiz-answer-id="1506302274650" data-quiz-question-id="427" disabled="disabled" />
<label for="427-1506302274650"><p>*arr + 2</p>
</label>
</li>

</ul>

<!-- Quiz question Tips -->

</div>

</div>
<div class="quiz_question_item_container" data-role="quiz_question417" data-position="3">
<div class=" clearfix" id="quiz_question-417">

<h4 class="quiz_question">

Question #1
</h4>

<!-- Quiz question Body -->
<p>If we have a variable called <code>var</code> of type <code>int</code>, how can we get its address in memory?</p>


<!-- Quiz question Answers -->
<ul class="quiz_question_answers" data-question-id="417">
<li class="">

<input type="radio" name="417" id="417-1506300104106" value="1506300104106" data-quiz-answer-id="1506300104106" data-quiz-question-id="417" disabled="disabled" />
<label for="417-1506300104106"><p>*var</p>
</label>
</li>

<li class="">

<input type="radio" name="417" id="417-1506300123036" value="1506300123036" data-quiz-answer-id="1506300123036" data-quiz-question-id="417" disabled="disabled" checked="checked" />
<label for="417-1506300123036"><p>&amp;var</p>
</label>
</li>

<li class="">

<input type="radio" name="417" id="417-1506300111392" value="1506300111392" data-quiz-answer-id="1506300111392" data-quiz-question-id="417" disabled="disabled" />
<label for="417-1506300111392"><p>*(var)</p>
</label>
</li>

</ul>

<!-- Quiz question Tips -->

</div>

</div>
<div class="quiz_question_item_container" data-role="quiz_question424" data-position="10">
<div class=" clearfix" id="quiz_question-424">

<h4 class="quiz_question">

Question #2
</h4>

<!-- Quiz question Body -->
<p>What is the value of <code>n</code> after the following code is executed?</p>

<pre><code>int n = 98;
int *p = &amp;n;

*p = 402;
</code></pre>


<!-- Quiz question Answers -->
<ul class="quiz_question_answers" data-question-id="424">
<li class="">

<input type="radio" name="424" id="424-1506301550503" value="1506301550503" data-quiz-answer-id="1506301550503" data-quiz-question-id="424" disabled="disabled" />
<label for="424-1506301550503"><p>99</p>
</label>
</li>

<li class="">

<input type="radio" name="424" id="424-1506301542129" value="1506301542129" data-quiz-answer-id="1506301542129" data-quiz-question-id="424" disabled="disabled" />
<label for="424-1506301542129"><p>0</p>
</label>
</li>

<li class="">

<input type="radio" name="424" id="424-1506301553224" value="1506301553224" data-quiz-answer-id="1506301553224" data-quiz-question-id="424" disabled="disabled" checked="checked" />
<label for="424-1506301553224"><p>402</p>
</label>
</li>

<li class="">

<input type="radio" name="424" id="424-1506301545063" value="1506301545063" data-quiz-answer-id="1506301545063" data-quiz-question-id="424" disabled="disabled" />
<label for="424-1506301545063"><p>98</p>
</label>
</li>

</ul>

<!-- Quiz question Tips -->

</div>

</div>
<div class="quiz_question_item_container" data-role="quiz_question418" data-position="4">
<div class=" clearfix" id="quiz_question-418">

<h4 class="quiz_question">

Question #3
</h4>

<!-- Quiz question Body -->
<p>What is the identifier to print an address with <code>printf</code>?</p>


<!-- Quiz question Answers -->
<ul class="quiz_question_answers" data-question-id="418">
<li class="">

<input type="radio" name="418" id="418-1506300152071" value="1506300152071" data-quiz-answer-id="1506300152071" data-quiz-question-id="418" disabled="disabled" checked="checked" />
<label for="418-1506300152071"><p>%p</p>
</label>
</li>

<li class="">

<input type="radio" name="418" id="418-1506300141777" value="1506300141777" data-quiz-answer-id="1506300141777" data-quiz-question-id="418" disabled="disabled" />
<label for="418-1506300141777"><p>%a</p>
</label>
</li>

<li class="">

<input type="radio" name="418" id="418-1506300157631" value="1506300157631" data-quiz-answer-id="1506300157631" data-quiz-question-id="418" disabled="disabled" />
<label for="418-1506300157631"><p>%x</p>
</label>
</li>

<li class="">

<input type="radio" name="418" id="418-1506300148546" value="1506300148546" data-quiz-answer-id="1506300148546" data-quiz-question-id="418" disabled="disabled" />
<label for="418-1506300148546"><p>%d</p>
</label>
</li>

</ul>

<!-- Quiz question Tips -->

</div>

</div>
<div class="quiz_question_item_container" data-role="quiz_question423" data-position="9">
<div class=" clearfix" id="quiz_question-423">

<h4 class="quiz_question">

Question #4
</h4>

<!-- Quiz question Body -->
<p>What is the value of <code>n</code> after the following code is executed?</p>

<pre><code>int n = 98;
int *p = &amp;n;

p = 402;
</code></pre>


<!-- Quiz question Answers -->
<ul class="quiz_question_answers" data-question-id="423">
<li class="">

<input type="radio" name="423" id="423-1506301532768" value="1506301532768" data-quiz-answer-id="1506301532768" data-quiz-question-id="423" disabled="disabled" />
<label for="423-1506301532768"><p>99</p>
</label>
</li>

<li class="">

<input type="radio" name="423" id="423-1506301521562" value="1506301521562" data-quiz-answer-id="1506301521562" data-quiz-question-id="423" disabled="disabled" />
<label for="423-1506301521562"><p>0</p>
</label>
</li>

<li class="">

<input type="radio" name="423" id="423-1506301535285" value="1506301535285" data-quiz-answer-id="1506301535285" data-quiz-question-id="423" disabled="disabled" />
<label for="423-1506301535285"><p>402</p>
</label>
</li>

<li class="">

<input type="radio" name="423" id="423-1506301526784" value="1506301526784" data-quiz-answer-id="1506301526784" data-quiz-question-id="423" disabled="disabled" checked="checked" />
<label for="423-1506301526784"><p>98</p>
</label>
</li>

</ul>

<!-- Quiz question Tips -->

</div>

</div>
<div class="quiz_question_item_container" data-role="quiz_question421" data-position="7">
<div class=" clearfix" id="quiz_question-421">

<h4 class="quiz_question">

Question #5
</h4>

<!-- Quiz question Body -->
<p>What happens when one tries to access an illegal memory location?</p>


<!-- Quiz question Answers -->
<ul class="quiz_question_answers" data-question-id="421">
<li class="">

<input type="radio" name="421" id="421-1506300944852" value="1506300944852" data-quiz-answer-id="1506300944852" data-quiz-question-id="421" disabled="disabled" />
<label for="421-1506300944852"><p>The computer shuts down</p>
</label>
</li>

<li class="">

<input type="radio" name="421" id="421-1506300898779" value="1506300898779" data-quiz-answer-id="1506300898779" data-quiz-question-id="421" disabled="disabled" />
<label for="421-1506300898779"><p>The operation is ignored</p>
</label>
</li>

<li class="">

<input type="radio" name="421" id="421-1506300967027" value="1506300967027" data-quiz-answer-id="1506300967027" data-quiz-question-id="421" disabled="disabled" />
<label for="421-1506300967027"><p>There&rsquo;s a chance for the computer to catch fire, and sometimes even explode</p>
</label>
</li>

<li class="">

<input type="radio" name="421" id="421-1506300922591" value="1506300922591" data-quiz-answer-id="1506300922591" data-quiz-question-id="421" disabled="disabled" checked="checked" />
<label for="421-1506300922591"><p>Segmentation fault</p>
</label>
</li>

</ul>

<!-- Quiz question Tips -->

</div>

</div>
<div class="quiz_question_item_container" data-role="quiz_question415" data-position="1">
<div class=" clearfix" id="quiz_question-415">

<h4 class="quiz_question">

Question #6
</h4>

<!-- Quiz question Body -->
<p>What is the size of a pointer to a <code>char</code> (on a 64-bit architecture)</p>


<!-- Quiz question Answers -->
<ul class="quiz_question_answers" data-question-id="415">
<li class="">

<input type="radio" name="415" id="415-1506300064217" value="1506300064217" data-quiz-answer-id="1506300064217" data-quiz-question-id="415" disabled="disabled" />
<label for="415-1506300064217"><p>4 bytes</p>
</label>
</li>

<li class="">

<input type="radio" name="415" id="415-1506300053315" value="1506300053315" data-quiz-answer-id="1506300053315" data-quiz-question-id="415" disabled="disabled" />
<label for="415-1506300053315"><p>1 byte</p>
</label>
</li>

<li class="">

<input type="radio" name="415" id="415-1506300067346" value="1506300067346" data-quiz-answer-id="1506300067346" data-quiz-question-id="415" disabled="disabled" checked="checked" />
<label for="415-1506300067346"><p>8 bytes</p>
</label>
</li>

<li class="">

<input type="radio" name="415" id="415-1506300059183" value="1506300059183" data-quiz-answer-id="1506300059183" data-quiz-question-id="415" disabled="disabled" />
<label for="415-1506300059183"><p>2 bytes</p>
</label>
</li>

</ul>

<!-- Quiz question Tips -->

</div>

</div>
<div class="quiz_question_item_container" data-role="quiz_question425" data-position="11">
<div class=" clearfix" id="quiz_question-425">

<h4 class="quiz_question">

Question #7
</h4>

<!-- Quiz question Body -->
<p>What is the value of <code>n</code> after the following code is executed?</p>

<pre><code>int n = 98;
int *p = &amp;n;

*p++;
</code></pre>


<!-- Quiz question Answers -->
<ul class="quiz_question_answers" data-question-id="425">
<li class="">

<input type="radio" name="425" id="425-1506301566280" value="1506301566280" data-quiz-answer-id="1506301566280" data-quiz-question-id="425" disabled="disabled" />
<label for="425-1506301566280"><p>99</p>
</label>
</li>

<li class="">

<input type="radio" name="425" id="425-1506301558553" value="1506301558553" data-quiz-answer-id="1506301558553" data-quiz-question-id="425" disabled="disabled" />
<label for="425-1506301558553"><p>0</p>
</label>
</li>

<li class="">

<input type="radio" name="425" id="425-1506301568790" value="1506301568790" data-quiz-answer-id="1506301568790" data-quiz-question-id="425" disabled="disabled" />
<label for="425-1506301568790"><p>402</p>
</label>
</li>

<li class="">

<input type="radio" name="425" id="425-1506301562343" value="1506301562343" data-quiz-answer-id="1506301562343" data-quiz-question-id="425" disabled="disabled" checked="checked" />
<label for="425-1506301562343"><p>98</p>
</label>
</li>

</ul>

<!-- Quiz question Tips -->

</div>

</div>
<div class="quiz_question_item_container" data-role="quiz_question419" data-position="5">
<div class=" clearfix" id="quiz_question-419">

<h4 class="quiz_question">

Question #8
</h4>

<!-- Quiz question Body -->
<p>The process of getting the value that is stored in the memory location pointed to by a pointer is called:</p>


<!-- Quiz question Answers -->
<ul class="quiz_question_answers" data-question-id="419">
<li class="">

<input type="radio" name="419" id="419-1506300332905" value="1506300332905" data-quiz-answer-id="1506300332905" data-quiz-question-id="419" disabled="disabled" checked="checked" />
<label for="419-1506300332905"><p>Dereferencing</p>
</label>
</li>

<li class="">

<input type="radio" name="419" id="419-1506300310549" value="1506300310549" data-quiz-answer-id="1506300310549" data-quiz-question-id="419" disabled="disabled" />
<label for="419-1506300310549"><p>Pointing</p>
</label>
</li>

<li class="">

<input type="radio" name="419" id="419-1506300369305" value="1506300369305" data-quiz-answer-id="1506300369305" data-quiz-question-id="419" disabled="disabled" />
<label for="419-1506300369305"><p>Casting</p>
</label>
</li>

<li class="">

<input type="radio" name="419" id="419-1506300316946" value="1506300316946" data-quiz-answer-id="1506300316946" data-quiz-question-id="419" disabled="disabled" />
<label for="419-1506300316946"><p>Accessing</p>
</label>
</li>

</ul>

<!-- Quiz question Tips -->

</div>

</div>
<div class="quiz_question_item_container" data-role="quiz_question420" data-position="6">
<div class=" clearfix" id="quiz_question-420">

<h4 class="quiz_question">

Question #9
</h4>

<!-- Quiz question Body -->
<p>Is it possible to declare a pointer to a pointer?</p>


<!-- Quiz question Answers -->
<ul class="quiz_question_answers" data-question-id="420">
<li class="">

<input type="radio" name="420" id="420-1506300812990" value="1506300812990" data-quiz-answer-id="1506300812990" data-quiz-question-id="420" disabled="disabled" checked="checked" />
<label for="420-1506300812990"><p>Yes</p>
</label>
</li>

<li class="">

<input type="radio" name="420" id="420-1506300823219" value="1506300823219" data-quiz-answer-id="1506300823219" data-quiz-question-id="420" disabled="disabled" />
<label for="420-1506300823219"><p>It depends on the type the pointer is pointing to</p>
</label>
</li>

<li class="">

<input type="radio" name="420" id="420-1506300818433" value="1506300818433" data-quiz-answer-id="1506300818433" data-quiz-question-id="420" disabled="disabled" />
<label for="420-1506300818433"><p>No</p>
</label>
</li>

</ul>

<!-- Quiz question Tips -->

</div>

</div>
<div class="quiz_question_item_container" data-role="quiz_question426" data-position="12">
<div class=" clearfix" id="quiz_question-426">

<h4 class="quiz_question">

Question #10
</h4>

<!-- Quiz question Body -->
<p>We declare the following variable</p>

<pre><code>int arr[5];
</code></pre>

<p>What is the size in memory of the variable <code>arr</code>?</p>


<!-- Quiz question Answers -->
<ul class="quiz_question_answers" data-question-id="426">
<li class="">

<input type="radio" name="426" id="426-1506302254544" value="1506302254544" data-quiz-answer-id="1506302254544" data-quiz-question-id="426" disabled="disabled" />
<label for="426-1506302254544"><p>32 bytes</p>
</label>
</li>

<li class="">

<input type="radio" name="426" id="426-1506302185672" value="1506302185672" data-quiz-answer-id="1506302185672" data-quiz-question-id="426" disabled="disabled" />
<label for="426-1506302185672"><p>4 bytes</p>
</label>
</li>

<li class="">

<input type="radio" name="426" id="426-1506302194383" value="1506302194383" data-quiz-answer-id="1506302194383" data-quiz-question-id="426" disabled="disabled" />
<label for="426-1506302194383"><p>5 bytes</p>
</label>
</li>

<li class="">

<input type="radio" name="426" id="426-1506302213039" value="1506302213039" data-quiz-answer-id="1506302213039" data-quiz-question-id="426" disabled="disabled" />
<label for="426-1506302213039"><p>10 bytes</p>
</label>
</li>

<li class="">

<input type="radio" name="426" id="426-1506302201999" value="1506302201999" data-quiz-answer-id="1506302201999" data-quiz-question-id="426" disabled="disabled" />
<label for="426-1506302201999"><p>8 bytes</p>
</label>
</li>

<li class="">

<input type="radio" name="426" id="426-1506302229920" value="1506302229920" data-quiz-answer-id="1506302229920" data-quiz-question-id="426" disabled="disabled" checked="checked" />
<label for="426-1506302229920"><p>20 bytes</p>
</label>
</li>

</ul>

<!-- Quiz question Tips -->

</div>

</div>
<div class="quiz_question_item_container" data-role="quiz_question416" data-position="2">
<div class=" clearfix" id="quiz_question-416">

<h4 class="quiz_question">

Question #11
</h4>

<!-- Quiz question Body -->
<p>What is the size of a pointer to an <code>int</code> (on a 64-bit architecture)</p>


<!-- Quiz question Answers -->
<ul class="quiz_question_answers" data-question-id="416">
<li class="">

<input type="radio" name="416" id="416-1506300081076" value="1506300081076" data-quiz-answer-id="1506300081076" data-quiz-question-id="416" disabled="disabled" />
<label for="416-1506300081076"><p>4 bytes</p>
</label>
</li>

<li class="">

<input type="radio" name="416" id="416-1506300074070" value="1506300074070" data-quiz-answer-id="1506300074070" data-quiz-question-id="416" disabled="disabled" />
<label for="416-1506300074070"><p>1 byte</p>
</label>
</li>

<li class="">

<input type="radio" name="416" id="416-1506300084530" value="1506300084530" data-quiz-answer-id="1506300084530" data-quiz-question-id="416" disabled="disabled" checked="checked" />
<label for="416-1506300084530"><p>8 bytes</p>
</label>
</li>

<li class="">

<input type="radio" name="416" id="416-1506300077420" value="1506300077420" data-quiz-answer-id="1506300077420" data-quiz-question-id="416" disabled="disabled" />
<label for="416-1506300077420"><p>2 bytes</p>
</label>
</li>

</ul>

<!-- Quiz question Tips -->

</div>

</div>
<div class="quiz_question_item_container" data-role="quiz_question422" data-position="8">
<div class=" clearfix" id="quiz_question-422">

<h4 class="quiz_question">

Question #12
</h4>

<!-- Quiz question Body -->
<p>What is the value of <code>n</code> after the following code is executed?</p>

<pre><code>int n = 98;
int *p = &amp;n;
</code></pre>


<!-- Quiz question Answers -->
<ul class="quiz_question_answers" data-question-id="422">
<li class="">

<input type="radio" name="422" id="422-1506301503271" value="1506301503271" data-quiz-answer-id="1506301503271" data-quiz-question-id="422" disabled="disabled" />
<label for="422-1506301503271"><p>99</p>
</label>
</li>

<li class="">

<input type="radio" name="422" id="422-1506301490528" value="1506301490528" data-quiz-answer-id="1506301490528" data-quiz-question-id="422" disabled="disabled" />
<label for="422-1506301490528"><p>0</p>
</label>
</li>

<li class="">

<input type="radio" name="422" id="422-1506301509830" value="1506301509830" data-quiz-answer-id="1506301509830" data-quiz-question-id="422" disabled="disabled" />
<label for="422-1506301509830"><p>402</p>
</label>
</li>

<li class="">

<input type="radio" name="422" id="422-1506301498267" value="1506301498267" data-quiz-answer-id="1506301498267" data-quiz-question-id="422" disabled="disabled" checked="checked" />
<label for="422-1506301498267"><p>98</p>
</label>
</li>

</ul>

<!-- Quiz question Tips -->

</div>

</div>

</section>
</div>
</div>



<h2 class="gap">Tasks</h2>

<div data-role="task877" data-position="1" id="task-num-0">
<div class="panel panel-default task-card " id="task-877">
<span id="user_id" data-id="197885"></span>

<div class="panel-heading panel-heading-actions">
<h3 class="panel-title">
0. 98 Battery st.
</h3>

<div>
<span class="label label-info">
mandatory
</span>
</div>
</div>

<div class="panel-body">
<span id="user_id" data-id="197885"></span>

<!-- Progress vs Score -->

<!-- Task Body -->
<p>Write a function that takes a pointer to an <code>int</code> as parameter and updates the value it points to to <code>98</code>.</p>

<ul>
<li>Prototype: <code>void reset_to_98(int *n);</code> </li>
</ul>

<pre><code>julien@ubuntu:~/0x05$ cat 0-main.c
#include &quot;main.h&quot;
#include &lt;stdio.h&gt;

/**
* main - check the code 
*
* Return: Always 0.
*/
int main(void)
{
int n;

n = 402;
printf(&quot;n=%d\n&quot;, n);
reset_to_98(&amp;n);
printf(&quot;n=%d\n&quot;, n);
return (0);
}
julien@ubuntu:~/0x05$ gcc -Wall -pedantic -Werror -Wextra -std=gnu89 0-main.c 0-reset_to_98.c -o 0-98
julien@ubuntu:~/0x05$ ./0-98 
n=402
n=98
julien@ubuntu:~/0x05$ 
</code></pre>

</div>

<div class="list-group">
<!-- Task URLs -->

<!-- Github information -->
<div class="list-group-item">
<p><strong>Repo:</strong></p>
<ul>
<li>GitHub repository: <code>alx-low_level_programming</code></li>
<li>Directory: <code>0x05-pointers_arrays_strings</code></li>
<li>File: <code>0-reset_to_98.c</code></li>
</ul>
</div>

<!-- Self-paced manual review -->
</div>

<!-- Panel footer - Controls -->
<div class="panel-footer">
<div class="align-items-center d-flex justify-content-between">

<div>
<button class="student_task_done btn btn-default btn-sm no" data-task-id="877">
<span class="no"><i aria-hidden="true" class="fa fa-square-o "></i></span>
<span class="yes"><i aria-hidden="true" class="fa fa-check-square-o "></i></span>
<span class="pending"><i aria-hidden="true" class="fa fa-spinner  fa-pulse"></i></span>
Done<span class="no pending">?</span><span class="yes">!</span>
</button>

<button class="student-task-done-by btn btn-default btn-sm" data-task-id="877" data-batch-id="26" data-toggle="modal" data-target="#task-877-users-done-modal">
Help
</button>
<div class="modal fade users-done-modal" id="task-877-users-done-modal" data-task-id="877" data-batch-id="26">
<div class="modal-dialog">
<div class="modal-content">
<div class="modal-header">
<button type="button" class="close" data-dismiss="modal" aria-label="Close"><span aria-hidden="true">&times;</span></button>
<h4 class="modal-title">Students who are done with "0. 98 Battery st."</h4>
</div>
<div class="modal-body">
<div class="list-group">
</div>
<div class="spinner">
<div class="bounce1"></div>
<div class="bounce2"></div>
<div class="bounce3"></div>
</div>
<div class="error"></div>
</div>
</div>
</div>
</div>


<button class="btn btn-default btn-sm check-your-task-877-modal-button" data-task-id="877" data-toggle="modal" data-target="#task-test-correction-877-correction-modal" id="task-num-0-check-code-btn" data-gtm-custom-event-name="task_checker_modal" data-gtm-custom-event-options='{&quot;taskId&quot;:877}'>
Check your code
</button>
<div class="modal fade task_correction_modal student_modal" id="task-test-correction-877-correction-modal">
<div class="modal-dialog">
<div class="modal-content">
<div class="modal-header">
<button type="button" class="close" data-dismiss="modal" aria-label="Close"><span aria-hidden="true">&times;</span></button>
<h4 class="modal-title">Correction of "0. 98 Battery st."</h4>
</div>
<div class="modal-body">
<div class="actions">
<center>
<div class="alert alert-info hidden"></div>

<button name="button" type="submit" class="btn btn-primary correction_request_test_send" data-task-id="877">Start a new test</button>
<button class="btn btn-default close-modal hidden" data-dismiss="modal" type="button">Close</button>

<div class="spinner" style="display: none;">
    <div class="bounce1"></div>
    <div class="bounce2"></div>
    <div class="bounce3"></div>
</div>
<div class="error"></div>
<div class="info"></div>
</center>
</div>
<div class="result"></div>

<div class="help">
<button data-task-id="877">
<i aria-hidden="true" class="fa fa-info-circle "></i>
</button>
<div class="help-container" data-task-id="877">
<div class="check-line">
<div class="check-inline requirement success">
<i aria-hidden="true" class="fa fa-check-circle "></i>
Requirement success
</div>
<div class="check-inline requirement fail">
<i aria-hidden="true" class="fa fa-times-circle "></i>
Requirement fail
</div>
</div>
<div class="check-line">
<div class="check-inline code success">
<i aria-hidden="true" class="fa fa-check-circle "></i>
Code success
</div>
<div class="check-inline code fail">
<i aria-hidden="true" class="fa fa-times-circle "></i>
Code fail
</div>
</div>
<div class="check-line">
<div class="check-inline efficiency success">
<i aria-hidden="true" class="fa fa-check-circle "></i>
Efficiency success
</div>
<div class="check-inline efficiency fail">
<i aria-hidden="true" class="fa fa-times-circle "></i>
Efficiency fail
</div>
</div>
<div class="check-line">
<div class="check-inline answer success">
<i aria-hidden="true" class="fa fa-check-circle "></i>
Text answer success
</div>
<div class="check-inline answer fail">
<i aria-hidden="true" class="fa fa-times-circle "></i>
Text answer fail
</div>
</div>
<div class="check-line">
<div class="check-inline requirement fail offline">
<i aria-hidden="true" class="fa fa-times-circle "></i>
Skipped - Previous check failed
</div>
</div>
</div>
</div>

</div>
</div>
</div>
</div>



<button class="btn btn-default btn-sm" data-toggle="modal" data-target="#container-specs-modal" data-gtm-custom-event-name="task_sandbox_modal" data-gtm-custom-event-options="{&quot;taskId&quot;:877}"><i aria-hidden="true" class="fa fa-terminal "></i><span>Get a sandbox</span></button>

</div>


<div class="fs-4">
</div>
</div>


</div>
</div>

</div>
<div data-role="task878" data-position="2" id="task-num-1">
<div class="panel panel-default task-card " id="task-878">
<span id="user_id" data-id="197885"></span>

<div class="panel-heading panel-heading-actions">
<h3 class="panel-title">
1. Don&#39;t swap horses in crossing a stream
</h3>

<div>
<span class="label label-info">
mandatory
</span>
</div>
</div>

<div class="panel-body">
<span id="user_id" data-id="197885"></span>

<!-- Progress vs Score -->

<!-- Task Body -->
<p>Write a function that swaps the values of two integers.</p>

<ul>
<li>Prototype: <code>void swap_int(int *a, int *b);</code><br></li>
</ul>

<pre><code>julien@ubuntu:~/0x05$ cat 1-main.c
#include &quot;main.h&quot;
#include &lt;stdio.h&gt;

/**
* main - check the code
*
* Return: Always 0.
*/
int main(void)
{
int a;
int b;

a = 98;
b = 42;
printf(&quot;a=%d, b=%d\n&quot;, a, b);
swap_int(&amp;a, &amp;b);
printf(&quot;a=%d, b=%d\n&quot;, a, b);
return (0);
}
julien@ubuntu:~/0x05$ gcc -Wall -pedantic -Werror -Wextra -std=gnu89 1-main.c 1-swap.c -o 1-swap
julien@ubuntu:~/0x05$ ./1-swap 
a=98, b=42
a=42, b=98
julien@ubuntu:~/0x05$
</code></pre>

</div>

<div class="list-group">
<!-- Task URLs -->

<!-- Github information -->
<div class="list-group-item">
<p><strong>Repo:</strong></p>
<ul>
<li>GitHub repository: <code>alx-low_level_programming</code></li>
<li>Directory: <code>0x05-pointers_arrays_strings</code></li>
<li>File: <code>1-swap.c</code></li>
</ul>
</div>

<!-- Self-paced manual review -->
</div>

<!-- Panel footer - Controls -->
<div class="panel-footer">
<div class="align-items-center d-flex justify-content-between">

<div>
<button class="student_task_done btn btn-default btn-sm no" data-task-id="878">
<span class="no"><i aria-hidden="true" class="fa fa-square-o "></i></span>
<span class="yes"><i aria-hidden="true" class="fa fa-check-square-o "></i></span>
<span class="pending"><i aria-hidden="true" class="fa fa-spinner  fa-pulse"></i></span>
Done<span class="no pending">?</span><span class="yes">!</span>
</button>

<button class="student-task-done-by btn btn-default btn-sm" data-task-id="878" data-batch-id="26" data-toggle="modal" data-target="#task-878-users-done-modal">
Help
</button>
<div class="modal fade users-done-modal" id="task-878-users-done-modal" data-task-id="878" data-batch-id="26">
<div class="modal-dialog">
<div class="modal-content">
<div class="modal-header">
<button type="button" class="close" data-dismiss="modal" aria-label="Close"><span aria-hidden="true">&times;</span></button>
<h4 class="modal-title">Students who are done with "1. Don&#39;t swap horses in crossing a stream"</h4>
</div>
<div class="modal-body">
<div class="list-group">
</div>
<div class="spinner">
<div class="bounce1"></div>
<div class="bounce2"></div>
<div class="bounce3"></div>
</div>
<div class="error"></div>
</div>
</div>
</div>
</div>


<button class="btn btn-default btn-sm check-your-task-878-modal-button" data-task-id="878" data-toggle="modal" data-target="#task-test-correction-878-correction-modal" id="task-num-1-check-code-btn" data-gtm-custom-event-name="task_checker_modal" data-gtm-custom-event-options='{&quot;taskId&quot;:878}'>
Check your code
</button>
<div class="modal fade task_correction_modal student_modal" id="task-test-correction-878-correction-modal">
<div class="modal-dialog">
<div class="modal-content">
<div class="modal-header">
<button type="button" class="close" data-dismiss="modal" aria-label="Close"><span aria-hidden="true">&times;</span></button>
<h4 class="modal-title">Correction of "1. Don&#39;t swap horses in crossing a stream"</h4>
</div>
<div class="modal-body">
<div class="actions">
<center>
<div class="alert alert-info hidden"></div>

<button name="button" type="submit" class="btn btn-primary correction_request_test_send" data-task-id="878">Start a new test</button>
<button class="btn btn-default close-modal hidden" data-dismiss="modal" type="button">Close</button>

<div class="spinner" style="display: none;">
    <div class="bounce1"></div>
    <div class="bounce2"></div>
    <div class="bounce3"></div>
</div>
<div class="error"></div>
<div class="info"></div>
</center>
</div>
<div class="result"></div>

<div class="help">
<button data-task-id="878">
<i aria-hidden="true" class="fa fa-info-circle "></i>
</button>
<div class="help-container" data-task-id="878">
<div class="check-line">
<div class="check-inline requirement success">
<i aria-hidden="true" class="fa fa-check-circle "></i>
Requirement success
</div>
<div class="check-inline requirement fail">
<i aria-hidden="true" class="fa fa-times-circle "></i>
Requirement fail
</div>
</div>
<div class="check-line">
<div class="check-inline code success">
<i aria-hidden="true" class="fa fa-check-circle "></i>
Code success
</div>
<div class="check-inline code fail">
<i aria-hidden="true" class="fa fa-times-circle "></i>
Code fail
</div>
</div>
<div class="check-line">
<div class="check-inline efficiency success">
<i aria-hidden="true" class="fa fa-check-circle "></i>
Efficiency success
</div>
<div class="check-inline efficiency fail">
<i aria-hidden="true" class="fa fa-times-circle "></i>
Efficiency fail
</div>
</div>
<div class="check-line">
<div class="check-inline answer success">
<i aria-hidden="true" class="fa fa-check-circle "></i>
Text answer success
</div>
<div class="check-inline answer fail">
<i aria-hidden="true" class="fa fa-times-circle "></i>
Text answer fail
</div>
</div>
<div class="check-line">
<div class="check-inline requirement fail offline">
<i aria-hidden="true" class="fa fa-times-circle "></i>
Skipped - Previous check failed
</div>
</div>
</div>
</div>

</div>
</div>
</div>
</div>





</div>


<div class="fs-4">
</div>
</div>


</div>
</div>

</div>
<div data-role="task879" data-position="3" id="task-num-2">
<div class="panel panel-default task-card " id="task-879">
<span id="user_id" data-id="197885"></span>

<div class="panel-heading panel-heading-actions">
<h3 class="panel-title">
2. This report, by its very length, defends itself against the risk of being read
</h3>

<div>
<span class="label label-info">
mandatory
</span>
</div>
</div>

<div class="panel-body">
<span id="user_id" data-id="197885"></span>

<!-- Progress vs Score -->

<!-- Task Body -->
<p>Write a function that returns the length of a string.</p>

<ul>
<li>Prototype: <code>int _strlen(char *s);</code></li>
</ul>

<p>FYI: The standard library provides a similar function: <code>strlen</code>. Run <code>man strlen</code> to learn more.</p>

<pre><code>julien@ubuntu:~/0x05$ cat 2-main.c
#include &quot;main.h&quot;
#include &lt;stdio.h&gt;

/**
* main - check the code
*
* Return: Always 0.
*/
int main(void)
{
char *str;
int len;

str = &quot;My first strlen!&quot;;
len = _strlen(str);
printf(&quot;%d\n&quot;, len);
return (0);
}
julien@ubuntu:~/0x05$ gcc -Wall -pedantic -Werror -Wextra -std=gnu89 2-main.c 2-strlen.c -o 2-strlen
julien@ubuntu:~/0x05$ ./2-strlen 
16
julien@ubuntu:~/0x05$ 
</code></pre>

</div>

<div class="list-group">
<!-- Task URLs -->

<!-- Github information -->
<div class="list-group-item">
<p><strong>Repo:</strong></p>
<ul>
<li>GitHub repository: <code>alx-low_level_programming</code></li>
<li>Directory: <code>0x05-pointers_arrays_strings</code></li>
<li>File: <code>2-strlen.c</code></li>
</ul>
</div>

<!-- Self-paced manual review -->
</div>

<!-- Panel footer - Controls -->
<div class="panel-footer">
<div class="align-items-center d-flex justify-content-between">

<div>
<button class="student_task_done btn btn-default btn-sm no" data-task-id="879">
<span class="no"><i aria-hidden="true" class="fa fa-square-o "></i></span>
<span class="yes"><i aria-hidden="true" class="fa fa-check-square-o "></i></span>
<span class="pending"><i aria-hidden="true" class="fa fa-spinner  fa-pulse"></i></span>
Done<span class="no pending">?</span><span class="yes">!</span>
</button>

<button class="student-task-done-by btn btn-default btn-sm" data-task-id="879" data-batch-id="26" data-toggle="modal" data-target="#task-879-users-done-modal">
Help
</button>
<div class="modal fade users-done-modal" id="task-879-users-done-modal" data-task-id="879" data-batch-id="26">
<div class="modal-dialog">
<div class="modal-content">
<div class="modal-header">
<button type="button" class="close" data-dismiss="modal" aria-label="Close"><span aria-hidden="true">&times;</span></button>
<h4 class="modal-title">Students who are done with "2. This report, by its very length, defends itself against the risk of being read"</h4>
</div>
<div class="modal-body">
<div class="list-group">
</div>
<div class="spinner">
<div class="bounce1"></div>
<div class="bounce2"></div>
<div class="bounce3"></div>
</div>
<div class="error"></div>
</div>
</div>
</div>
</div>


<button class="btn btn-default btn-sm check-your-task-879-modal-button" data-task-id="879" data-toggle="modal" data-target="#task-test-correction-879-correction-modal" id="task-num-2-check-code-btn" data-gtm-custom-event-name="task_checker_modal" data-gtm-custom-event-options='{&quot;taskId&quot;:879}'>
Check your code
</button>
<div class="modal fade task_correction_modal student_modal" id="task-test-correction-879-correction-modal">
<div class="modal-dialog">
<div class="modal-content">
<div class="modal-header">
<button type="button" class="close" data-dismiss="modal" aria-label="Close"><span aria-hidden="true">&times;</span></button>
<h4 class="modal-title">Correction of "2. This report, by its very length, defends itself against the risk of being read"</h4>
</div>
<div class="modal-body">
<div class="actions">
<center>
<div class="alert alert-info hidden"></div>

<button name="button" type="submit" class="btn btn-primary correction_request_test_send" data-task-id="879">Start a new test</button>
<button class="btn btn-default close-modal hidden" data-dismiss="modal" type="button">Close</button>

<div class="spinner" style="display: none;">
    <div class="bounce1"></div>
    <div class="bounce2"></div>
    <div class="bounce3"></div>
</div>
<div class="error"></div>
<div class="info"></div>
</center>
</div>
<div class="result"></div>

<div class="help">
<button data-task-id="879">
<i aria-hidden="true" class="fa fa-info-circle "></i>
</button>
<div class="help-container" data-task-id="879">
<div class="check-line">
<div class="check-inline requirement success">
<i aria-hidden="true" class="fa fa-check-circle "></i>
Requirement success
</div>
<div class="check-inline requirement fail">
<i aria-hidden="true" class="fa fa-times-circle "></i>
Requirement fail
</div>
</div>
<div class="check-line">
<div class="check-inline code success">
<i aria-hidden="true" class="fa fa-check-circle "></i>
Code success
</div>
<div class="check-inline code fail">
<i aria-hidden="true" class="fa fa-times-circle "></i>
Code fail
</div>
</div>
<div class="check-line">
<div class="check-inline efficiency success">
<i aria-hidden="true" class="fa fa-check-circle "></i>
Efficiency success
</div>
<div class="check-inline efficiency fail">
<i aria-hidden="true" class="fa fa-times-circle "></i>
Efficiency fail
</div>
</div>
<div class="check-line">
<div class="check-inline answer success">
<i aria-hidden="true" class="fa fa-check-circle "></i>
Text answer success
</div>
<div class="check-inline answer fail">
<i aria-hidden="true" class="fa fa-times-circle "></i>
Text answer fail
</div>
</div>
<div class="check-line">
<div class="check-inline requirement fail offline">
<i aria-hidden="true" class="fa fa-times-circle "></i>
Skipped - Previous check failed
</div>
</div>
</div>
</div>

</div>
</div>
</div>
</div>





</div>


<div class="fs-4">
</div>
</div>


</div>
</div>

</div>
<div data-role="task880" data-position="4" id="task-num-3">
<div class="panel panel-default task-card " id="task-880">
<span id="user_id" data-id="197885"></span>

<div class="panel-heading panel-heading-actions">
<h3 class="panel-title">
3. I do not fear computers. I fear the lack of them
</h3>

<div>
<span class="label label-info">
mandatory
</span>
</div>
</div>

<div class="panel-body">
<span id="user_id" data-id="197885"></span>

<!-- Progress vs Score -->

<!-- Task Body -->
<p>Write a function that prints a string, followed by a new line, to <code>stdout</code>.</p>

<ul>
<li>Prototype: <code>void _puts(char *str);</code></li>
</ul>

<p>FYI: The standard library provides a similar function: <code>puts</code>. Run <code>man puts</code> to learn more.</p>

<pre><code>julien@ubuntu:~/0x05$ cat 3-main.c
#include &quot;main.h&quot;

/**
* main - check the code
*
* Return: Always 0.
*/
int main(void)
{
char *str;

str = &quot;I do not fear computers. I fear the lack of them - Isaac Asimov&quot;;
_puts(str);
return (0);
}
julien@ubuntu:~/0x05$ gcc -Wall -pedantic -Werror -Wextra -std=gnu89 _putchar.c 3-main.c 3-puts.c -o 3-puts
julien@ubuntu:~/0x05$ ./3-puts 
I do not fear computers. I fear the lack of them - Isaac Asimov
julien@ubuntu:~/0x05$ 

</code></pre>

</div>

<div class="list-group">
<!-- Task URLs -->

<!-- Github information -->
<div class="list-group-item">
<p><strong>Repo:</strong></p>
<ul>
<li>GitHub repository: <code>alx-low_level_programming</code></li>
<li>Directory: <code>0x05-pointers_arrays_strings</code></li>
<li>File: <code>3-puts.c</code></li>
</ul>
</div>

<!-- Self-paced manual review -->
</div>

<!-- Panel footer - Controls -->
<div class="panel-footer">
<div class="align-items-center d-flex justify-content-between">

<div>
<button class="student_task_done btn btn-default btn-sm no" data-task-id="880">
<span class="no"><i aria-hidden="true" class="fa fa-square-o "></i></span>
<span class="yes"><i aria-hidden="true" class="fa fa-check-square-o "></i></span>
<span class="pending"><i aria-hidden="true" class="fa fa-spinner  fa-pulse"></i></span>
Done<span class="no pending">?</span><span class="yes">!</span>
</button>

<button class="student-task-done-by btn btn-default btn-sm" data-task-id="880" data-batch-id="26" data-toggle="modal" data-target="#task-880-users-done-modal">
Help
</button>
<div class="modal fade users-done-modal" id="task-880-users-done-modal" data-task-id="880" data-batch-id="26">
<div class="modal-dialog">
<div class="modal-content">
<div class="modal-header">
<button type="button" class="close" data-dismiss="modal" aria-label="Close"><span aria-hidden="true">&times;</span></button>
<h4 class="modal-title">Students who are done with "3. I do not fear computers. I fear the lack of them"</h4>
</div>
<div class="modal-body">
<div class="list-group">
</div>
<div class="spinner">
<div class="bounce1"></div>
<div class="bounce2"></div>
<div class="bounce3"></div>
</div>
<div class="error"></div>
</div>
</div>
</div>
</div>


<button class="btn btn-default btn-sm check-your-task-880-modal-button" data-task-id="880" data-toggle="modal" data-target="#task-test-correction-880-correction-modal" id="task-num-3-check-code-btn" data-gtm-custom-event-name="task_checker_modal" data-gtm-custom-event-options='{&quot;taskId&quot;:880}'>
Check your code
</button>
<div class="modal fade task_correction_modal student_modal" id="task-test-correction-880-correction-modal">
<div class="modal-dialog">
<div class="modal-content">
<div class="modal-header">
<button type="button" class="close" data-dismiss="modal" aria-label="Close"><span aria-hidden="true">&times;</span></button>
<h4 class="modal-title">Correction of "3. I do not fear computers. I fear the lack of them"</h4>
</div>
<div class="modal-body">
<div class="actions">
<center>
<div class="alert alert-info hidden"></div>

<button name="button" type="submit" class="btn btn-primary correction_request_test_send" data-task-id="880">Start a new test</button>
<button class="btn btn-default close-modal hidden" data-dismiss="modal" type="button">Close</button>

<div class="spinner" style="display: none;">
    <div class="bounce1"></div>
    <div class="bounce2"></div>
    <div class="bounce3"></div>
</div>
<div class="error"></div>
<div class="info"></div>
</center>
</div>
<div class="result"></div>

<div class="help">
<button data-task-id="880">
<i aria-hidden="true" class="fa fa-info-circle "></i>
</button>
<div class="help-container" data-task-id="880">
<div class="check-line">
<div class="check-inline requirement success">
<i aria-hidden="true" class="fa fa-check-circle "></i>
Requirement success
</div>
<div class="check-inline requirement fail">
<i aria-hidden="true" class="fa fa-times-circle "></i>
Requirement fail
</div>
</div>
<div class="check-line">
<div class="check-inline code success">
<i aria-hidden="true" class="fa fa-check-circle "></i>
Code success
</div>
<div class="check-inline code fail">
<i aria-hidden="true" class="fa fa-times-circle "></i>
Code fail
</div>
</div>
<div class="check-line">
<div class="check-inline efficiency success">
<i aria-hidden="true" class="fa fa-check-circle "></i>
Efficiency success
</div>
<div class="check-inline efficiency fail">
<i aria-hidden="true" class="fa fa-times-circle "></i>
Efficiency fail
</div>
</div>
<div class="check-line">
<div class="check-inline answer success">
<i aria-hidden="true" class="fa fa-check-circle "></i>
Text answer success
</div>
<div class="check-inline answer fail">
<i aria-hidden="true" class="fa fa-times-circle "></i>
Text answer fail
</div>
</div>
<div class="check-line">
<div class="check-inline requirement fail offline">
<i aria-hidden="true" class="fa fa-times-circle "></i>
Skipped - Previous check failed
</div>
</div>
</div>
</div>

</div>
</div>
</div>
</div>





</div>


<div class="fs-4">
</div>
</div>


</div>
</div>

</div>
<div data-role="task881" data-position="5" id="task-num-4">
<div class="panel panel-default task-card " id="task-881">
<span id="user_id" data-id="197885"></span>

<div class="panel-heading panel-heading-actions">
<h3 class="panel-title">
4. I can only go one way. I&#39;ve not got a reverse gear
</h3>

<div>
<span class="label label-info">
mandatory
</span>
</div>
</div>

<div class="panel-body">
<span id="user_id" data-id="197885"></span>

<!-- Progress vs Score -->

<!-- Task Body -->
<p>Write a function that prints a string, in reverse, followed by a new line.</p>

<ul>
<li>Prototype: <code>void print_rev(char *s);</code></li>
</ul>

<pre><code>julien@ubuntu:~/0x05$ cat 4-main.c
#include &quot;main.h&quot;

/**
* main - check the code
*
* Return: Always 0.
*/
int main(void)
{
char *str;

str = &quot;I do not fear computers. I fear the lack of them - Isaac Asimov&quot;;
print_rev(str);
return (0);
}
julien@ubuntu:~/0x05$ gcc -Wall -pedantic -Werror -Wextra -std=gnu89 _putchar.c 4-main.c 4-print_rev.c -o 4-print_rev
julien@ubuntu:~/0x05$ ./4-print_rev 
vomisA caasI - meht fo kcal eht raef I .sretupmoc raef ton od I
julien@ubuntu:~/0x05$ 
</code></pre>

</div>

<div class="list-group">
<!-- Task URLs -->

<!-- Github information -->
<div class="list-group-item">
<p><strong>Repo:</strong></p>
<ul>
<li>GitHub repository: <code>alx-low_level_programming</code></li>
<li>Directory: <code>0x05-pointers_arrays_strings</code></li>
<li>File: <code>4-print_rev.c</code></li>
</ul>
</div>

<!-- Self-paced manual review -->
</div>

<!-- Panel footer - Controls -->
<div class="panel-footer">
<div class="align-items-center d-flex justify-content-between">

<div>
<button class="student_task_done btn btn-default btn-sm no" data-task-id="881">
<span class="no"><i aria-hidden="true" class="fa fa-square-o "></i></span>
<span class="yes"><i aria-hidden="true" class="fa fa-check-square-o "></i></span>
<span class="pending"><i aria-hidden="true" class="fa fa-spinner  fa-pulse"></i></span>
Done<span class="no pending">?</span><span class="yes">!</span>
</button>

<button class="student-task-done-by btn btn-default btn-sm" data-task-id="881" data-batch-id="26" data-toggle="modal" data-target="#task-881-users-done-modal">
Help
</button>
<div class="modal fade users-done-modal" id="task-881-users-done-modal" data-task-id="881" data-batch-id="26">
<div class="modal-dialog">
<div class="modal-content">
<div class="modal-header">
<button type="button" class="close" data-dismiss="modal" aria-label="Close"><span aria-hidden="true">&times;</span></button>
<h4 class="modal-title">Students who are done with "4. I can only go one way. I&#39;ve not got a reverse gear"</h4>
</div>
<div class="modal-body">
<div class="list-group">
</div>
<div class="spinner">
<div class="bounce1"></div>
<div class="bounce2"></div>
<div class="bounce3"></div>
</div>
<div class="error"></div>
</div>
</div>
</div>
</div>


<button class="btn btn-default btn-sm check-your-task-881-modal-button" data-task-id="881" data-toggle="modal" data-target="#task-test-correction-881-correction-modal" id="task-num-4-check-code-btn" data-gtm-custom-event-name="task_checker_modal" data-gtm-custom-event-options='{&quot;taskId&quot;:881}'>
Check your code
</button>
<div class="modal fade task_correction_modal student_modal" id="task-test-correction-881-correction-modal">
<div class="modal-dialog">
<div class="modal-content">
<div class="modal-header">
<button type="button" class="close" data-dismiss="modal" aria-label="Close"><span aria-hidden="true">&times;</span></button>
<h4 class="modal-title">Correction of "4. I can only go one way. I&#39;ve not got a reverse gear"</h4>
</div>
<div class="modal-body">
<div class="actions">
<center>
<div class="alert alert-info hidden"></div>

<button name="button" type="submit" class="btn btn-primary correction_request_test_send" data-task-id="881">Start a new test</button>
<button class="btn btn-default close-modal hidden" data-dismiss="modal" type="button">Close</button>

<div class="spinner" style="display: none;">
    <div class="bounce1"></div>
    <div class="bounce2"></div>
    <div class="bounce3"></div>
</div>
<div class="error"></div>
<div class="info"></div>
</center>
</div>
<div class="result"></div>

<div class="help">
<button data-task-id="881">
<i aria-hidden="true" class="fa fa-info-circle "></i>
</button>
<div class="help-container" data-task-id="881">
<div class="check-line">
<div class="check-inline requirement success">
<i aria-hidden="true" class="fa fa-check-circle "></i>
Requirement success
</div>
<div class="check-inline requirement fail">
<i aria-hidden="true" class="fa fa-times-circle "></i>
Requirement fail
</div>
</div>
<div class="check-line">
<div class="check-inline code success">
<i aria-hidden="true" class="fa fa-check-circle "></i>
Code success
</div>
<div class="check-inline code fail">
<i aria-hidden="true" class="fa fa-times-circle "></i>
Code fail
</div>
</div>
<div class="check-line">
<div class="check-inline efficiency success">
<i aria-hidden="true" class="fa fa-check-circle "></i>
Efficiency success
</div>
<div class="check-inline efficiency fail">
<i aria-hidden="true" class="fa fa-times-circle "></i>
Efficiency fail
</div>
</div>
<div class="check-line">
<div class="check-inline answer success">
<i aria-hidden="true" class="fa fa-check-circle "></i>
Text answer success
</div>
<div class="check-inline answer fail">
<i aria-hidden="true" class="fa fa-times-circle "></i>
Text answer fail
</div>
</div>
<div class="check-line">
<div class="check-inline requirement fail offline">
<i aria-hidden="true" class="fa fa-times-circle "></i>
Skipped - Previous check failed
</div>
</div>
</div>
</div>

</div>
</div>
</div>
</div>





</div>


<div class="fs-4">
</div>
</div>


</div>
</div>

</div>
<div data-role="task882" data-position="6" id="task-num-5">
<div class="panel panel-default task-card " id="task-882">
<span id="user_id" data-id="197885"></span>

<div class="panel-heading panel-heading-actions">
<h3 class="panel-title">
5. A good engineer thinks in reverse and asks himself about the stylistic consequences of the components and systems he proposes
</h3>

<div>
<span class="label label-info">
mandatory
</span>
</div>
</div>

<div class="panel-body">
<span id="user_id" data-id="197885"></span>

<!-- Progress vs Score -->

<!-- Task Body -->
<p>Write a function that reverses a string.  </p>

<ul>
<li>Prototype: <code>void rev_string(char *s);</code><br></li>
</ul>

<pre><code>julien@ubuntu:~/0x05$ cat 5-main.c
#include &quot;main.h&quot;
#include &lt;stdio.h&gt;

/**
* main - check the code
*
* Return: Always 0.
*/
int main(void)
{
char s[10] = &quot;My School&quot;;

printf(&quot;%s\n&quot;, s);
rev_string(s);
printf(&quot;%s\n&quot;, s);
return (0);
}
julien@ubuntu:~/0x05$ gcc -Wall -pedantic -Werror -Wextra -std=gnu89 5-main.c 5-rev_string.c -o 5-rev_string
julien@ubuntu:~/0x05$ ./5-rev_string 
My School
loohcS yM
julien@ubuntu:~/0x05$ 
</code></pre>

</div>

<div class="list-group">
<!-- Task URLs -->

<!-- Github information -->
<div class="list-group-item">
<p><strong>Repo:</strong></p>
<ul>
<li>GitHub repository: <code>alx-low_level_programming</code></li>
<li>Directory: <code>0x05-pointers_arrays_strings</code></li>
<li>File: <code>5-rev_string.c</code></li>
</ul>
</div>

<!-- Self-paced manual review -->
</div>

<!-- Panel footer - Controls -->
<div class="panel-footer">
<div class="align-items-center d-flex justify-content-between">

<div>
<button class="student_task_done btn btn-default btn-sm no" data-task-id="882">
<span class="no"><i aria-hidden="true" class="fa fa-square-o "></i></span>
<span class="yes"><i aria-hidden="true" class="fa fa-check-square-o "></i></span>
<span class="pending"><i aria-hidden="true" class="fa fa-spinner  fa-pulse"></i></span>
Done<span class="no pending">?</span><span class="yes">!</span>
</button>

<button class="student-task-done-by btn btn-default btn-sm" data-task-id="882" data-batch-id="26" data-toggle="modal" data-target="#task-882-users-done-modal">
Help
</button>
<div class="modal fade users-done-modal" id="task-882-users-done-modal" data-task-id="882" data-batch-id="26">
<div class="modal-dialog">
<div class="modal-content">
<div class="modal-header">
<button type="button" class="close" data-dismiss="modal" aria-label="Close"><span aria-hidden="true">&times;</span></button>
<h4 class="modal-title">Students who are done with "5. A good engineer thinks in reverse and asks himself about the stylistic consequences of the components and systems he proposes"</h4>
</div>
<div class="modal-body">
<div class="list-group">
</div>
<div class="spinner">
<div class="bounce1"></div>
<div class="bounce2"></div>
<div class="bounce3"></div>
</div>
<div class="error"></div>
</div>
</div>
</div>
</div>


<button class="btn btn-default btn-sm check-your-task-882-modal-button" data-task-id="882" data-toggle="modal" data-target="#task-test-correction-882-correction-modal" id="task-num-5-check-code-btn" data-gtm-custom-event-name="task_checker_modal" data-gtm-custom-event-options='{&quot;taskId&quot;:882}'>
Check your code
</button>
<div class="modal fade task_correction_modal student_modal" id="task-test-correction-882-correction-modal">
<div class="modal-dialog">
<div class="modal-content">
<div class="modal-header">
<button type="button" class="close" data-dismiss="modal" aria-label="Close"><span aria-hidden="true">&times;</span></button>
<h4 class="modal-title">Correction of "5. A good engineer thinks in reverse and asks himself about the stylistic consequences of the components and systems he proposes"</h4>
</div>
<div class="modal-body">
<div class="actions">
<center>
<div class="alert alert-info hidden"></div>

<button name="button" type="submit" class="btn btn-primary correction_request_test_send" data-task-id="882">Start a new test</button>
<button class="btn btn-default close-modal hidden" data-dismiss="modal" type="button">Close</button>

<div class="spinner" style="display: none;">
    <div class="bounce1"></div>
    <div class="bounce2"></div>
    <div class="bounce3"></div>
</div>
<div class="error"></div>
<div class="info"></div>
</center>
</div>
<div class="result"></div>

<div class="help">
<button data-task-id="882">
<i aria-hidden="true" class="fa fa-info-circle "></i>
</button>
<div class="help-container" data-task-id="882">
<div class="check-line">
<div class="check-inline requirement success">
<i aria-hidden="true" class="fa fa-check-circle "></i>
Requirement success
</div>
<div class="check-inline requirement fail">
<i aria-hidden="true" class="fa fa-times-circle "></i>
Requirement fail
</div>
</div>
<div class="check-line">
<div class="check-inline code success">
<i aria-hidden="true" class="fa fa-check-circle "></i>
Code success
</div>
<div class="check-inline code fail">
<i aria-hidden="true" class="fa fa-times-circle "></i>
Code fail
</div>
</div>
<div class="check-line">
<div class="check-inline efficiency success">
<i aria-hidden="true" class="fa fa-check-circle "></i>
Efficiency success
</div>
<div class="check-inline efficiency fail">
<i aria-hidden="true" class="fa fa-times-circle "></i>
Efficiency fail
</div>
</div>
<div class="check-line">
<div class="check-inline answer success">
<i aria-hidden="true" class="fa fa-check-circle "></i>
Text answer success
</div>
<div class="check-inline answer fail">
<i aria-hidden="true" class="fa fa-times-circle "></i>
Text answer fail
</div>
</div>
<div class="check-line">
<div class="check-inline requirement fail offline">
<i aria-hidden="true" class="fa fa-times-circle "></i>
Skipped - Previous check failed
</div>
</div>
</div>
</div>

</div>
</div>
</div>
</div>





</div>


<div class="fs-4">
</div>
</div>


</div>
</div>

</div>
<div data-role="task883" data-position="7" id="task-num-6">
<div class="panel panel-default task-card " id="task-883">
<span id="user_id" data-id="197885"></span>

<div class="panel-heading panel-heading-actions">
<h3 class="panel-title">
6. Half the lies they tell about me aren&#39;t true
</h3>

<div>
<span class="label label-info">
mandatory
</span>
</div>
</div>

<div class="panel-body">
<span id="user_id" data-id="197885"></span>

<!-- Progress vs Score -->

<!-- Task Body -->
<p>Write a function that prints every other character of a string, starting with the first character, followed by a new line.</p>

<ul>
<li>Prototype: <code>void puts2(char *str);</code></li>
</ul>

<pre><code>julien@ubuntu:~/0x05$ cat 6-main.c
#include &quot;main.h&quot;

/**
* main - check the code
*
* Return: Always 0.
*/
int main(void)
{
char *str;

str = &quot;0123456789&quot;;
puts2(str);
return (0);
}
julien@ubuntu:~/0x05$ gcc -Wall -pedantic -Werror -Wextra -std=gnu89 _putchar.c 6-main.c 6-puts2.c -o 6-puts2
julien@ubuntu:~/0x05$ ./6-puts2 
02468
julien@ubuntu:~/0x05$ 
</code></pre>

</div>

<div class="list-group">
<!-- Task URLs -->

<!-- Github information -->
<div class="list-group-item">
<p><strong>Repo:</strong></p>
<ul>
<li>GitHub repository: <code>alx-low_level_programming</code></li>
<li>Directory: <code>0x05-pointers_arrays_strings</code></li>
<li>File: <code>6-puts2.c</code></li>
</ul>
</div>

<!-- Self-paced manual review -->
</div>

<!-- Panel footer - Controls -->
<div class="panel-footer">
<div class="align-items-center d-flex justify-content-between">

<div>
<button class="student_task_done btn btn-default btn-sm no" data-task-id="883">
<span class="no"><i aria-hidden="true" class="fa fa-square-o "></i></span>
<span class="yes"><i aria-hidden="true" class="fa fa-check-square-o "></i></span>
<span class="pending"><i aria-hidden="true" class="fa fa-spinner  fa-pulse"></i></span>
Done<span class="no pending">?</span><span class="yes">!</span>
</button>

<button class="student-task-done-by btn btn-default btn-sm" data-task-id="883" data-batch-id="26" data-toggle="modal" data-target="#task-883-users-done-modal">
Help
</button>
<div class="modal fade users-done-modal" id="task-883-users-done-modal" data-task-id="883" data-batch-id="26">
<div class="modal-dialog">
<div class="modal-content">
<div class="modal-header">
<button type="button" class="close" data-dismiss="modal" aria-label="Close"><span aria-hidden="true">&times;</span></button>
<h4 class="modal-title">Students who are done with "6. Half the lies they tell about me aren&#39;t true"</h4>
</div>
<div class="modal-body">
<div class="list-group">
</div>
<div class="spinner">
<div class="bounce1"></div>
<div class="bounce2"></div>
<div class="bounce3"></div>
</div>
<div class="error"></div>
</div>
</div>
</div>
</div>


<button class="btn btn-default btn-sm check-your-task-883-modal-button" data-task-id="883" data-toggle="modal" data-target="#task-test-correction-883-correction-modal" id="task-num-6-check-code-btn" data-gtm-custom-event-name="task_checker_modal" data-gtm-custom-event-options='{&quot;taskId&quot;:883}'>
Check your code
</button>
<div class="modal fade task_correction_modal student_modal" id="task-test-correction-883-correction-modal">
<div class="modal-dialog">
<div class="modal-content">
<div class="modal-header">
<button type="button" class="close" data-dismiss="modal" aria-label="Close"><span aria-hidden="true">&times;</span></button>
<h4 class="modal-title">Correction of "6. Half the lies they tell about me aren&#39;t true"</h4>
</div>
<div class="modal-body">
<div class="actions">
<center>
<div class="alert alert-info hidden"></div>

<button name="button" type="submit" class="btn btn-primary correction_request_test_send" data-task-id="883">Start a new test</button>
<button class="btn btn-default close-modal hidden" data-dismiss="modal" type="button">Close</button>

<div class="spinner" style="display: none;">
    <div class="bounce1"></div>
    <div class="bounce2"></div>
    <div class="bounce3"></div>
</div>
<div class="error"></div>
<div class="info"></div>
</center>
</div>
<div class="result"></div>

<div class="help">
<button data-task-id="883">
<i aria-hidden="true" class="fa fa-info-circle "></i>
</button>
<div class="help-container" data-task-id="883">
<div class="check-line">
<div class="check-inline requirement success">
<i aria-hidden="true" class="fa fa-check-circle "></i>
Requirement success
</div>
<div class="check-inline requirement fail">
<i aria-hidden="true" class="fa fa-times-circle "></i>
Requirement fail
</div>
</div>
<div class="check-line">
<div class="check-inline code success">
<i aria-hidden="true" class="fa fa-check-circle "></i>
Code success
</div>
<div class="check-inline code fail">
<i aria-hidden="true" class="fa fa-times-circle "></i>
Code fail
</div>
</div>
<div class="check-line">
<div class="check-inline efficiency success">
<i aria-hidden="true" class="fa fa-check-circle "></i>
Efficiency success
</div>
<div class="check-inline efficiency fail">
<i aria-hidden="true" class="fa fa-times-circle "></i>
Efficiency fail
</div>
</div>
<div class="check-line">
<div class="check-inline answer success">
<i aria-hidden="true" class="fa fa-check-circle "></i>
Text answer success
</div>
<div class="check-inline answer fail">
<i aria-hidden="true" class="fa fa-times-circle "></i>
Text answer fail
</div>
</div>
<div class="check-line">
<div class="check-inline requirement fail offline">
<i aria-hidden="true" class="fa fa-times-circle "></i>
Skipped - Previous check failed
</div>
</div>
</div>
</div>

</div>
</div>
</div>
</div>





</div>


<div class="fs-4">
</div>
</div>


</div>
</div>

</div>
<div data-role="task884" data-position="8" id="task-num-7">
<div class="panel panel-default task-card " id="task-884">
<span id="user_id" data-id="197885"></span>

<div class="panel-heading panel-heading-actions">
<h3 class="panel-title">
7. Winning is only half of it. Having fun is the other half
</h3>

<div>
<span class="label label-info">
mandatory
</span>
</div>
</div>

<div class="panel-body">
<span id="user_id" data-id="197885"></span>

<!-- Progress vs Score -->

<!-- Task Body -->
<p>Write a function that prints half of a string, followed by a new line.</p>

<ul>
<li>Prototype: <code>void puts_half(char *str);</code></li>
<li>The function should print the second half of the string</li>
<li>If the number of characters is odd, the function should print the last <code>n</code> characters of the string, where <code>n = (length_of_the_string - 1) / 2</code></li>
</ul>

<pre><code>julien@ubuntu:~/0x05$ cat 7-main.c
#include &quot;main.h&quot;

/**
* main - check the code
*
* Return: Always 0.
*/
int main(void)
{
char *str;

str = &quot;0123456789&quot;;
puts_half(str);
return (0);
}
julien@ubuntu:~/0x05$ gcc -Wall -pedantic -Werror -Wextra -std=gnu89 _putchar.c 7-main.c 7-puts_half.c -o 7-puts_half
julien@ubuntu:~/0x05$ ./7-puts_half 
56789
julien@ubuntu:~/0x05$ 
</code></pre>

</div>

<div class="list-group">
<!-- Task URLs -->

<!-- Github information -->
<div class="list-group-item">
<p><strong>Repo:</strong></p>
<ul>
<li>GitHub repository: <code>alx-low_level_programming</code></li>
<li>Directory: <code>0x05-pointers_arrays_strings</code></li>
<li>File: <code>7-puts_half.c</code></li>
</ul>
</div>

<!-- Self-paced manual review -->
</div>

<!-- Panel footer - Controls -->
<div class="panel-footer">
<div class="align-items-center d-flex justify-content-between">

<div>
<button class="student_task_done btn btn-default btn-sm no" data-task-id="884">
<span class="no"><i aria-hidden="true" class="fa fa-square-o "></i></span>
<span class="yes"><i aria-hidden="true" class="fa fa-check-square-o "></i></span>
<span class="pending"><i aria-hidden="true" class="fa fa-spinner  fa-pulse"></i></span>
Done<span class="no pending">?</span><span class="yes">!</span>
</button>

<button class="student-task-done-by btn btn-default btn-sm" data-task-id="884" data-batch-id="26" data-toggle="modal" data-target="#task-884-users-done-modal">
Help
</button>
<div class="modal fade users-done-modal" id="task-884-users-done-modal" data-task-id="884" data-batch-id="26">
<div class="modal-dialog">
<div class="modal-content">
<div class="modal-header">
<button type="button" class="close" data-dismiss="modal" aria-label="Close"><span aria-hidden="true">&times;</span></button>
<h4 class="modal-title">Students who are done with "7. Winning is only half of it. Having fun is the other half"</h4>
</div>
<div class="modal-body">
<div class="list-group">
</div>
<div class="spinner">
<div class="bounce1"></div>
<div class="bounce2"></div>
<div class="bounce3"></div>
</div>
<div class="error"></div>
</div>
</div>
</div>
</div>


<button class="btn btn-default btn-sm check-your-task-884-modal-button" data-task-id="884" data-toggle="modal" data-target="#task-test-correction-884-correction-modal" id="task-num-7-check-code-btn" data-gtm-custom-event-name="task_checker_modal" data-gtm-custom-event-options='{&quot;taskId&quot;:884}'>
Check your code
</button>
<div class="modal fade task_correction_modal student_modal" id="task-test-correction-884-correction-modal">
<div class="modal-dialog">
<div class="modal-content">
<div class="modal-header">
<button type="button" class="close" data-dismiss="modal" aria-label="Close"><span aria-hidden="true">&times;</span></button>
<h4 class="modal-title">Correction of "7. Winning is only half of it. Having fun is the other half"</h4>
</div>
<div class="modal-body">
<div class="actions">
<center>
<div class="alert alert-info hidden"></div>

<button name="button" type="submit" class="btn btn-primary correction_request_test_send" data-task-id="884">Start a new test</button>
<button class="btn btn-default close-modal hidden" data-dismiss="modal" type="button">Close</button>

<div class="spinner" style="display: none;">
    <div class="bounce1"></div>
    <div class="bounce2"></div>
    <div class="bounce3"></div>
</div>
<div class="error"></div>
<div class="info"></div>
</center>
</div>
<div class="result"></div>

<div class="help">
<button data-task-id="884">
<i aria-hidden="true" class="fa fa-info-circle "></i>
</button>
<div class="help-container" data-task-id="884">
<div class="check-line">
<div class="check-inline requirement success">
<i aria-hidden="true" class="fa fa-check-circle "></i>
Requirement success
</div>
<div class="check-inline requirement fail">
<i aria-hidden="true" class="fa fa-times-circle "></i>
Requirement fail
</div>
</div>
<div class="check-line">
<div class="check-inline code success">
<i aria-hidden="true" class="fa fa-check-circle "></i>
Code success
</div>
<div class="check-inline code fail">
<i aria-hidden="true" class="fa fa-times-circle "></i>
Code fail
</div>
</div>
<div class="check-line">
<div class="check-inline efficiency success">
<i aria-hidden="true" class="fa fa-check-circle "></i>
Efficiency success
</div>
<div class="check-inline efficiency fail">
<i aria-hidden="true" class="fa fa-times-circle "></i>
Efficiency fail
</div>
</div>
<div class="check-line">
<div class="check-inline answer success">
<i aria-hidden="true" class="fa fa-check-circle "></i>
Text answer success
</div>
<div class="check-inline answer fail">
<i aria-hidden="true" class="fa fa-times-circle "></i>
Text answer fail
</div>
</div>
<div class="check-line">
<div class="check-inline requirement fail offline">
<i aria-hidden="true" class="fa fa-times-circle "></i>
Skipped - Previous check failed
</div>
</div>
</div>
</div>

</div>
</div>
</div>
</div>





</div>


<div class="fs-4">
</div>
</div>


</div>
</div>

</div>
<div data-role="task885" data-position="9" id="task-num-8">
<div class="panel panel-default task-card " id="task-885">
<span id="user_id" data-id="197885"></span>

<div class="panel-heading panel-heading-actions">
<h3 class="panel-title">
8. Arrays are not pointers
</h3>

<div>
<span class="label label-info">
mandatory
</span>
</div>
</div>

<div class="panel-body">
<span id="user_id" data-id="197885"></span>

<!-- Progress vs Score -->

<!-- Task Body -->
<p>Write a function that prints <code>n</code> elements of an array of integers, followed by a new line.</p>

<ul>
<li>Prototype: <code>void print_array(int *a, int n);</code><br></li>
<li>where <code>n</code> is the number of elements of the array to be printed</li>
<li>Numbers must be separated by comma, followed by a space</li>
<li>The numbers should be displayed in the same order as they are stored in the array</li>
<li>You are allowed to use <code>printf</code></li>
</ul>

<pre><code>julien@ubuntu:~/0x05$ cat 8-main.c
#include &quot;main.h&quot;

/**
* main - check the code for
*
* Return: Always 0.
*/
int main(void)
{
int array[5];

array[0] = 98;
array[1] = 402;
array[2] = -198;
array[3] = 298;
array[4] = -1024;
print_array(array, 5);
return (0);
}
julien@ubuntu:~/0x05$ gcc -Wall -pedantic -Werror -Wextra -std=gnu89 8-main.c 8-print_array.c -o 8-print_array
julien@ubuntu:~/0x05$ ./8-print_array 
98, 402, -198, 298, -1024
julien@ubuntu:~/0x05$
</code></pre>

</div>

<div class="list-group">
<!-- Task URLs -->

<!-- Github information -->
<div class="list-group-item">
<p><strong>Repo:</strong></p>
<ul>
<li>GitHub repository: <code>alx-low_level_programming</code></li>
<li>Directory: <code>0x05-pointers_arrays_strings</code></li>
<li>File: <code> 8-print_array.c</code></li>
</ul>
</div>

<!-- Self-paced manual review -->
</div>

<!-- Panel footer - Controls -->
<div class="panel-footer">
<div class="align-items-center d-flex justify-content-between">

<div>
<button class="student_task_done btn btn-default btn-sm no" data-task-id="885">
<span class="no"><i aria-hidden="true" class="fa fa-square-o "></i></span>
<span class="yes"><i aria-hidden="true" class="fa fa-check-square-o "></i></span>
<span class="pending"><i aria-hidden="true" class="fa fa-spinner  fa-pulse"></i></span>
Done<span class="no pending">?</span><span class="yes">!</span>
</button>

<button class="student-task-done-by btn btn-default btn-sm" data-task-id="885" data-batch-id="26" data-toggle="modal" data-target="#task-885-users-done-modal">
Help
</button>
<div class="modal fade users-done-modal" id="task-885-users-done-modal" data-task-id="885" data-batch-id="26">
<div class="modal-dialog">
<div class="modal-content">
<div class="modal-header">
<button type="button" class="close" data-dismiss="modal" aria-label="Close"><span aria-hidden="true">&times;</span></button>
<h4 class="modal-title">Students who are done with "8. Arrays are not pointers"</h4>
</div>
<div class="modal-body">
<div class="list-group">
</div>
<div class="spinner">
<div class="bounce1"></div>
<div class="bounce2"></div>
<div class="bounce3"></div>
</div>
<div class="error"></div>
</div>
</div>
</div>
</div>


<button class="btn btn-default btn-sm check-your-task-885-modal-button" data-task-id="885" data-toggle="modal" data-target="#task-test-correction-885-correction-modal" id="task-num-8-check-code-btn" data-gtm-custom-event-name="task_checker_modal" data-gtm-custom-event-options='{&quot;taskId&quot;:885}'>
Check your code
</button>
<div class="modal fade task_correction_modal student_modal" id="task-test-correction-885-correction-modal">
<div class="modal-dialog">
<div class="modal-content">
<div class="modal-header">
<button type="button" class="close" data-dismiss="modal" aria-label="Close"><span aria-hidden="true">&times;</span></button>
<h4 class="modal-title">Correction of "8. Arrays are not pointers"</h4>
</div>
<div class="modal-body">
<div class="actions">
<center>
<div class="alert alert-info hidden"></div>

<button name="button" type="submit" class="btn btn-primary correction_request_test_send" data-task-id="885">Start a new test</button>
<button class="btn btn-default close-modal hidden" data-dismiss="modal" type="button">Close</button>

<div class="spinner" style="display: none;">
    <div class="bounce1"></div>
    <div class="bounce2"></div>
    <div class="bounce3"></div>
</div>
<div class="error"></div>
<div class="info"></div>
</center>
</div>
<div class="result"></div>

<div class="help">
<button data-task-id="885">
<i aria-hidden="true" class="fa fa-info-circle "></i>
</button>
<div class="help-container" data-task-id="885">
<div class="check-line">
<div class="check-inline requirement success">
<i aria-hidden="true" class="fa fa-check-circle "></i>
Requirement success
</div>
<div class="check-inline requirement fail">
<i aria-hidden="true" class="fa fa-times-circle "></i>
Requirement fail
</div>
</div>
<div class="check-line">
<div class="check-inline code success">
<i aria-hidden="true" class="fa fa-check-circle "></i>
Code success
</div>
<div class="check-inline code fail">
<i aria-hidden="true" class="fa fa-times-circle "></i>
Code fail
</div>
</div>
<div class="check-line">
<div class="check-inline efficiency success">
<i aria-hidden="true" class="fa fa-check-circle "></i>
Efficiency success
</div>
<div class="check-inline efficiency fail">
<i aria-hidden="true" class="fa fa-times-circle "></i>
Efficiency fail
</div>
</div>
<div class="check-line">
<div class="check-inline answer success">
<i aria-hidden="true" class="fa fa-check-circle "></i>
Text answer success
</div>
<div class="check-inline answer fail">
<i aria-hidden="true" class="fa fa-times-circle "></i>
Text answer fail
</div>
</div>
<div class="check-line">
<div class="check-inline requirement fail offline">
<i aria-hidden="true" class="fa fa-times-circle "></i>
Skipped - Previous check failed
</div>
</div>
</div>
</div>

</div>
</div>
</div>
</div>





</div>


<div class="fs-4">
</div>
</div>


</div>
</div>

</div>
<div data-role="task886" data-position="10" id="task-num-9">
<div class="panel panel-default task-card " id="task-886">
<span id="user_id" data-id="197885"></span>

<div class="panel-heading panel-heading-actions">
<h3 class="panel-title">
9. strcpy
</h3>

<div>
<span class="label label-info">
mandatory
</span>
</div>
</div>

<div class="panel-body">
<span id="user_id" data-id="197885"></span>

<!-- Progress vs Score -->

<!-- Task Body -->
<ul>
<li>Prototype: <code>char *_strcpy(char *dest, char *src);</code> </li>
</ul>

<p>Write a function that copies the string pointed to by <code>src</code>, including the terminating null byte (<code>\0</code>), to the buffer pointed to by <code>dest</code>.</p>

<ul>
<li>Return value: the pointer to <code>dest</code></li>
</ul>

<p>FYI: The standard library provides a similar function: <code>strcpy</code>. Run <code>man strcpy</code> to learn more.</p>

<pre><code>julien@ubuntu:~/0x05$ cat 9-main.c
#include &quot;main.h&quot;
#include &lt;stdio.h&gt;

/**
* main - check the code
*
* Return: Always 0.
*/
int main(void)
{
char s1[98];
char *ptr;

ptr = _strcpy(s1, &quot;First, solve the problem. Then, write the code\n&quot;);
printf(&quot;%s&quot;, s1);
printf(&quot;%s&quot;, ptr);
return (0);
}
julien@ubuntu:~/0x05$ gcc -Wall -pedantic -Werror -Wextra -std=gnu89 9-main.c 9-strcpy.c -o 9-strcpy
julien@ubuntu:~/0x05$ ./9-strcpy 
First, solve the problem. Then, write the code
First, solve the problem. Then, write the code
julien@ubuntu:~/0x05$ 
</code></pre>

</div>

<div class="list-group">
<!-- Task URLs -->

<!-- Github information -->
<div class="list-group-item">
<p><strong>Repo:</strong></p>
<ul>
<li>GitHub repository: <code>alx-low_level_programming</code></li>
<li>Directory: <code>0x05-pointers_arrays_strings</code></li>
<li>File: <code>9-strcpy.c</code></li>
</ul>
</div>

<!-- Self-paced manual review -->
</div>

<!-- Panel footer - Controls -->
<div class="panel-footer">
<div class="align-items-center d-flex justify-content-between">

<div>
<button class="student_task_done btn btn-default btn-sm no" data-task-id="886">
<span class="no"><i aria-hidden="true" class="fa fa-square-o "></i></span>
<span class="yes"><i aria-hidden="true" class="fa fa-check-square-o "></i></span>
<span class="pending"><i aria-hidden="true" class="fa fa-spinner  fa-pulse"></i></span>
Done<span class="no pending">?</span><span class="yes">!</span>
</button>

<button class="student-task-done-by btn btn-default btn-sm" data-task-id="886" data-batch-id="26" data-toggle="modal" data-target="#task-886-users-done-modal">
Help
</button>
<div class="modal fade users-done-modal" id="task-886-users-done-modal" data-task-id="886" data-batch-id="26">
<div class="modal-dialog">
<div class="modal-content">
<div class="modal-header">
<button type="button" class="close" data-dismiss="modal" aria-label="Close"><span aria-hidden="true">&times;</span></button>
<h4 class="modal-title">Students who are done with "9. strcpy"</h4>
</div>
<div class="modal-body">
<div class="list-group">
</div>
<div class="spinner">
<div class="bounce1"></div>
<div class="bounce2"></div>
<div class="bounce3"></div>
</div>
<div class="error"></div>
</div>
</div>
</div>
</div>


<button class="btn btn-default btn-sm check-your-task-886-modal-button" data-task-id="886" data-toggle="modal" data-target="#task-test-correction-886-correction-modal" id="task-num-9-check-code-btn" data-gtm-custom-event-name="task_checker_modal" data-gtm-custom-event-options='{&quot;taskId&quot;:886}'>
Check your code
</button>
<div class="modal fade task_correction_modal student_modal" id="task-test-correction-886-correction-modal">
<div class="modal-dialog">
<div class="modal-content">
<div class="modal-header">
<button type="button" class="close" data-dismiss="modal" aria-label="Close"><span aria-hidden="true">&times;</span></button>
<h4 class="modal-title">Correction of "9. strcpy"</h4>
</div>
<div class="modal-body">
<div class="actions">
<center>
<div class="alert alert-info hidden"></div>

<button name="button" type="submit" class="btn btn-primary correction_request_test_send" data-task-id="886">Start a new test</button>
<button class="btn btn-default close-modal hidden" data-dismiss="modal" type="button">Close</button>

<div class="spinner" style="display: none;">
    <div class="bounce1"></div>
    <div class="bounce2"></div>
    <div class="bounce3"></div>
</div>
<div class="error"></div>
<div class="info"></div>
</center>
</div>
<div class="result"></div>

<div class="help">
<button data-task-id="886">
<i aria-hidden="true" class="fa fa-info-circle "></i>
</button>
<div class="help-container" data-task-id="886">
<div class="check-line">
<div class="check-inline requirement success">
<i aria-hidden="true" class="fa fa-check-circle "></i>
Requirement success
</div>
<div class="check-inline requirement fail">
<i aria-hidden="true" class="fa fa-times-circle "></i>
Requirement fail
</div>
</div>
<div class="check-line">
<div class="check-inline code success">
<i aria-hidden="true" class="fa fa-check-circle "></i>
Code success
</div>
<div class="check-inline code fail">
<i aria-hidden="true" class="fa fa-times-circle "></i>
Code fail
</div>
</div>
<div class="check-line">
<div class="check-inline efficiency success">
<i aria-hidden="true" class="fa fa-check-circle "></i>
Efficiency success
</div>
<div class="check-inline efficiency fail">
<i aria-hidden="true" class="fa fa-times-circle "></i>
Efficiency fail
</div>
</div>
<div class="check-line">
<div class="check-inline answer success">
<i aria-hidden="true" class="fa fa-check-circle "></i>
Text answer success
</div>
<div class="check-inline answer fail">
<i aria-hidden="true" class="fa fa-times-circle "></i>
Text answer fail
</div>
</div>
<div class="check-line">
<div class="check-inline requirement fail offline">
<i aria-hidden="true" class="fa fa-times-circle "></i>
Skipped - Previous check failed
</div>
</div>
</div>
</div>

</div>
</div>
</div>
</div>





</div>


<div class="fs-4">
</div>
</div>


</div>
</div>

</div>

<p class="lg-gap">
<form class="button_to" method="post" action="/projects/216/unlock_optionals"><input id="unlock_optional_btn" class="btn btn-primary btn-block" data-confirm="Are you sure? Make sure you focused on the mandatory tasks first" data-disable-with="Unlocking 2 advanced tasks..." data-gtm-custom-event-name="project_unlock_advanced_tasks" type="submit" value="Done with the mandatory tasks? Unlock 2 advanced tasks now!" /><input type="hidden" name="authenticity_token" value="ujm_BmbYN1urYyT6tgaB1Pr1YzVEMTD27Y1-YAY6e_GJh3KvQ1RZ4-9__s9HLPQT7028fkTScUhCGbfbdDlmtA" autocomplete="off" /></form>
</p>




<div class="modal fade" id="container-specs-modal"><div class="modal-dialog modal-lg"><div class="modal-content"><div class="modal-header"><button type="button" class="close" data-dismiss="modal" aria-label="Close"><span aria-hidden="true">&times;</span></button><h4 class="modal-title">Recommended Sandbox</h4></div><div class="modal-body"><div data-react-class="user_containers/ContainerSpecs" data-react-props="{&quot;containerModelName&quot;:&quot;Sandbox&quot;,&quot;containerSpecs&quot;:[{&quot;description&quot;:&quot;\u003cp\u003eBasic Ubuntu 20.04, with vim, emacs, curl, wget and all needed for Foundations\u003c/p\u003e\n&quot;,&quot;id&quot;:39,&quot;name&quot;:&quot;Ubuntu 20.04&quot;,&quot;online&quot;:true,&quot;container&quot;:{&quot;container_id&quot;:null,&quot;id&quot;:239271,&quot;restart_uri&quot;:&quot;/user_containers/239271/restart.json&quot;,&quot;status&quot;:&quot;asleep&quot;,&quot;uri&quot;:&quot;/user_containers/239271.json&quot;,&quot;wake_uri&quot;:&quot;/user_containers/239271/wake.json&quot;,&quot;webterm_uri&quot;:&quot;/user_containers/239271/webterm&quot;,&quot;host&quot;:null,&quot;password&quot;:&quot;2deaf74c415af9350d02&quot;,&quot;ports&quot;:{&quot;4000&quot;:49897,&quot;443&quot;:49900,&quot;8000&quot;:49894,&quot;8080&quot;:49893,&quot;3000&quot;:49899,&quot;3306&quot;:49898,&quot;5001&quot;:49895,&quot;80&quot;:49901,&quot;22&quot;:49902,&quot;5000&quot;:49896}}}],&quot;containersLimit&quot;:2,&quot;csrfToken&quot;:&quot;NbxlYJ-QG2eNWDkoEYqQrvWYMYFBKvTBSr_DWAXEyd-IUgKBEVsx-cOYgCb6ObYkvPugdtdNi_oSqCgUbqcguw&quot;,&quot;startStatusURI&quot;:&quot;/user_containers/start_status.json&quot;,&quot;startURI&quot;:&quot;/user_containers/start.json&quot;}" data-react-cache-id="user_containers/ContainerSpecs-0"></div></div></div></div></div>

</div>
</div>


</article>

<div class="copyright">Copyright © 2022 ALX, All rights reserved.</div>

</main>

<button class="btn btn-primary" id="search-button" data-search-active="false" data-toggle="modal" data-target="#search-modal">
<i aria-hidden="true" class="fa fa-search "></i>
<i aria-hidden="true" class="fa fa-window-minimize "></i>
</button>

<div class="modal fade" id="search-modal" tabindex="-1" role="dialog" aria-labelledby="search-modal-label">
<div class="modal-dialog modal-md">
<div class="modal-content">
<div class="modal-header">
<div id="search-bar-container">
<input id="search-bar"
type="text"
name="hbtn-search-bar"
placeholder="✨Start search by typing in this field✨">
</div>

</div>
<div class="modal-body">
<div id="modal-spinner" class="spinner gap">
<div class="bounce1"></div>
<div class="bounce2"></div>
<div class="bounce3"></div>
</div>
<div id="search-results-container">
</div>

</div>
</div>
</div>
</div>



<div class="modal fade" id="markdownGuideModal" tabindex="-1" role="dialog" aria-labelledby="markdownGuideModalLabel" aria-hidden="true">
<div class="modal-dialog modal-md">
<div class="modal-content">
<div class="modal-header">
<button type="button" class="close" data-dismiss="modal" aria-label="Close"><span aria-hidden="true">&times;</span></button>
<h4 class="modal-title">Markdown Guide</h4>
</div>
<div class="modal-body">
<h4>Emphasis</h4>
<pre>**<strong>bold</strong>**
*<em>italics</em>*
~~<strike>strikethrough</strike>~~</pre>
<h4>Headers</h4>
<pre># Big header
## Medium header
### Small header
#### Tiny header</pre>
<h4>Lists</h4>
<pre>* Generic list item
* Generic list item
* Generic list item

1. Numbered list item
2. Numbered list item
3. Numbered list item</pre>
<h4>Links</h4>
<pre>[Text to display](http://www.example.com)</pre>
<h4>Quotes</h4>
<pre>> This is a quote.
> It can span multiple lines!</pre>
<h4>Images</h4>
<p>CSS style available: <code>width, height, opacity</code></p>
<pre>![](http://www.example.com/image.jpg)
![](http://www.example.com/image.jpg | width: 200px)
![](http://www.example.com/image.jpg | height: 124px | width: 80px | opacity: 0.6)
</pre>
<h4>Tables</h4>
<pre>| Column 1 | Column 2 | Column 3 |
| -------- | -------- | -------- |
| John     | Doe      | Male     |
| Mary     | Smith    | Female   |

<em>Or without aligning the columns...</em>

| Column 1 | Column 2 | Column 3 |
| -------- | -------- | -------- |
| John | Doe | Male |
| Mary | Smith | Female |
</pre>
<h4>Displaying code</h4>
<pre>`var example = "hello!";`

<em>Or spanning multiple lines...</em>

```
var example = "hello!";
alert(example);
```</pre>
</div>
</div>
</div>
</div>


</body>
</html>


'''