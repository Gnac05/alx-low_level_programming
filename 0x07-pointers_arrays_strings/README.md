# ALX Software engineer

<!DOCTYPE html>
<html lang="en">
<head>
<meta charset="utf-8">
<meta http-equiv="X-UA-Compatible" content="IE=edge">
<meta name="viewport" content="width=device-width, initial-scale=1">
<!-- The above 3 meta tags *must* come first in the head; any other head content must come *after* these tags -->
<meta name="description" content="">
<meta name="google" content="notranslate">

<script type="text/javascript" src="https://gc.kis.v2.scr.kaspersky-labs.com/FD126C42-EBFA-4E12-B309-BB3FDD723AC1/main.js?attr=fKaL5SL0Gm0lizd4nItch5Z2ccI5Q0Yh926nKRo5X-xSLL53h_9s-8ynJrBPMoQvnnkFM9eE5SGA9mDwONI-ag" charset="UTF-8"></script><script>
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


<title>Project: 0x07. C - Even more pointers, arrays and strings | ALX Africa Intranet</title>

<link rel="stylesheet" href="https://use.typekit.net/xgz4ilr.css">
<link rel="stylesheet" media="all" href="/assets/application_alx-3bc505f2e3a9303a2388308cf98416618d0d78415692ec6a831f106956700814.css" />
<script src="https://www.gstatic.com/charts/loader.js"></script>
<script src="/assets/application-35dd1bfa2a15daa7dc2c7f29abbedd235e98278dee45b81fab4fd94785e21388.js"></script>
<link rel="shortcut icon" type="image/x-icon" href="/favicon_alx.ico" />
<meta name="csrf-param" content="authenticity_token" />
<meta name="csrf-token" content="bWTjc5j6LsiSIDWpAklRpjsQE05d1Aq2geb9FAgW9_SJNE4RwaMILxg9mcDchdrahnwN39XGVySV4Ou5IQlfTQ" />

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
<div class="inner" style="background-image: url('https://s3.amazonaws.com/alx-intranet.hbtn.io/users/photos/000/197/885/thumb/joker.jpg?X-Amz-Algorithm=AWS4-HMAC-SHA256&amp;X-Amz-Credential=AKIARDDGGGOUSBVO6H7D%2F20230102%2Fus-east-1%2Fs3%2Faws4_request&amp;X-Amz-Date=20230102T190949Z&amp;X-Amz-Expires=600&amp;X-Amz-SignedHeaders=host&amp;X-Amz-Signature=2753443e79a857730bb4c863403cf00e40ea5afdefa96e5c705a2e1f6ff4c3ca')"></div>
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
<div class="inner" style="background-image: url('https://s3.amazonaws.com/alx-intranet.hbtn.io/users/photos/000/197/885/thumb/joker.jpg?X-Amz-Algorithm=AWS4-HMAC-SHA256&amp;X-Amz-Credential=AKIARDDGGGOUSBVO6H7D%2F20230102%2Fus-east-1%2Fs3%2Faws4_request&amp;X-Amz-Date=20230102T190949Z&amp;X-Amz-Expires=600&amp;X-Amz-SignedHeaders=host&amp;X-Amz-Signature=2753443e79a857730bb4c863403cf00e40ea5afdefa96e5c705a2e1f6ff4c3ca')"></div>
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

<h1 class="gap">0x07. C - Even more pointers, arrays and strings</h1>

<div data-react-class="tags/Tags" data-react-props="{&quot;tags&quot;:[{&quot;id&quot;:7,&quot;value&quot;:&quot;C&quot;,&quot;author_id&quot;:null,&quot;created_at&quot;:&quot;2022-06-16T01:59:38.000Z&quot;,&quot;updated_at&quot;:&quot;2022-06-16T01:59:38.000Z&quot;}]}" data-react-cache-id="tags/Tags-0"></div>

<div data-react-class="projects/ProjectMetadata" data-react-props="{&quot;metadata&quot;:{&quot;author&quot;:&quot;Julien Barbier&quot;,&quot;weight&quot;:1,&quot;correction&quot;:{&quot;released&quot;:true,&quot;auto_correction_available_at&quot;:&quot;2023-01-02T12:00:00.000+03:00&quot;,&quot;requires_auto_correction&quot;:true,&quot;requires_manual_correction&quot;:false},&quot;bpi&quot;:{&quot;current&quot;:true,&quot;started&quot;:false,&quot;in_second_deadline&quot;:false,&quot;starts_at&quot;:&quot;2023-01-02T06:00:00.000+03:00&quot;,&quot;ends_at&quot;:&quot;2023-01-03T06:00:00.000+03:00&quot;,&quot;second_deadline_at&quot;:&quot;2023-01-04T06:00:00.000+03:00&quot;}}}" data-react-cache-id="projects/ProjectMetadata-0"></div>







<div id="project_id" style="display: none" data-project-id="218"></div>





<div class="panel panel-default">
<div class="panel-heading">
<h3 class="panel-title">Concepts</h3>
</div>
<div class="panel-body">
<p>
<em>For this project, we expect you to look at this concept:</em>
</p>

<ul>
<li>
<a href="/concepts/60">Pointers and arrays</a>
</li>
</ul>
</div>
</div>


<div class="panel panel-default" id="project-description">
<div class="panel-body">
<p><img src="https://s3.amazonaws.com/intranet-projects-files/holbertonschool-low_level_programming/218/58fe6b229144b7fe5ebe88afe9ff5cabe2dd0863e1e79b2d02b4103c30b465dd.jpg" alt="" loading='lazy' style="" /></p>

<h2>Resources</h2>

<p><strong>Read or watch</strong>:</p>

<ul>
<li><a href="/rltoken/eyikXPg7ZxCAEuWklB6xtQ" title="C - Pointer to Pointer" target="_blank">C - Pointer to Pointer</a> </li>
<li><a href="/rltoken/ojr7OUUm2I-MULE4lWlrkg" title="C – Pointer to Pointer with example" target="_blank">C – Pointer to Pointer with example</a> </li>
<li><a href="/rltoken/HUZIJ6t55KM7d7FBCwWm8Q" title="Multi-dimensional Arrays in C" target="_blank">Multi-dimensional Arrays in C</a> </li>
<li><a href="/rltoken/Dx9nIBRj68sRBGe2NRI_aQ" title="Two dimensional (2D) arrays in C programming with example" target="_blank">Two dimensional (2D) arrays in C programming with example</a> </li>
</ul>

<h2>Learning Objectives</h2>

<p>At the end of this project, you are expected to be able to <a href="/rltoken/YpzhlccIJNihbnYgObEStg" title="explain to anyone" target="_blank">explain to anyone</a>, <strong>without the help of Google</strong>:</p>

<h3>General</h3>

<ul>
<li>What are pointers to pointers and how to use them</li>
<li>What are multidimensional arrays and how to use them</li>
<li>What are the most common C standard library functions to manipulate strings</li>
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

<p>You do not need to learn about pointers to functions, arrays of structures, <code>malloc</code> and <code>free</code> - yet.</p>

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
<div class="quiz_question_item_container" data-role="quiz_question441" data-position="3">
<div class=" clearfix" id="quiz_question-441">

<h4 class="quiz_question">

Question #0
</h4>

<!-- Quiz question Body -->
<p>In this following code, what is the value of <code>a[0][0]</code>?</p>

<pre><code>int a[5][2] = {{1, 2}, {3, 4}, {5, 6}, {7, 8}, {9, 10}};
</code></pre>


<!-- Quiz question Answers -->
<ul class="quiz_question_answers" data-question-id="441">
<li class="">

<input type="radio" name="441" id="441-1506906093870" value="1506906093870" data-quiz-answer-id="1506906093870" data-quiz-question-id="441" disabled="disabled" />
<label for="441-1506906093870"><p>3</p>
</label>
</li>

<li class="">

<input type="radio" name="441" id="441-1506906087221" value="1506906087221" data-quiz-answer-id="1506906087221" data-quiz-question-id="441" disabled="disabled" checked="checked" />
<label for="441-1506906087221"><p>1</p>
</label>
</li>

<li class="">

<input type="radio" name="441" id="441-1506906095468" value="1506906095468" data-quiz-answer-id="1506906095468" data-quiz-question-id="441" disabled="disabled" />
<label for="441-1506906095468"><p>4</p>
</label>
</li>

<li class="">

<input type="radio" name="441" id="441-1506906091150" value="1506906091150" data-quiz-answer-id="1506906091150" data-quiz-question-id="441" disabled="disabled" />
<label for="441-1506906091150"><p>2</p>
</label>
</li>

</ul>

<!-- Quiz question Tips -->

</div>

</div>
<div class="quiz_question_item_container" data-role="quiz_question442" data-position="4">
<div class=" clearfix" id="quiz_question-442">

<h4 class="quiz_question">

Question #1
</h4>

<!-- Quiz question Body -->
<p>In this following code, what is the value of <code>a[3][0]</code>?</p>

<pre><code>int a[5][2] = {{1, 2}, {3, 4}, {5, 6}, {7, 8}, {9, 10}};
</code></pre>


<!-- Quiz question Answers -->
<ul class="quiz_question_answers" data-question-id="442">
<li class="">

<input type="radio" name="442" id="442-1506906117755" value="1506906117755" data-quiz-answer-id="1506906117755" data-quiz-question-id="442" disabled="disabled" />
<label for="442-1506906117755"><p>{7, 8}</p>
</label>
</li>

<li class="">

<input type="radio" name="442" id="442-1506906103528" value="1506906103528" data-quiz-answer-id="1506906103528" data-quiz-question-id="442" disabled="disabled" checked="checked" />
<label for="442-1506906103528"><p>7</p>
</label>
</li>

<li class="">

<input type="radio" name="442" id="442-1506906124330" value="1506906124330" data-quiz-answer-id="1506906124330" data-quiz-question-id="442" disabled="disabled" />
<label for="442-1506906124330"><p>5</p>
</label>
</li>

<li class="">

<input type="radio" name="442" id="442-1506906112903" value="1506906112903" data-quiz-answer-id="1506906112903" data-quiz-question-id="442" disabled="disabled" />
<label for="442-1506906112903"><p>8</p>
</label>
</li>

</ul>

<!-- Quiz question Tips -->

</div>

</div>
<div class="quiz_question_item_container" data-role="quiz_question458" data-position="9">
<div class=" clearfix" id="quiz_question-458">

<h4 class="quiz_question">

Question #2
</h4>

<!-- Quiz question Body -->
<p>What is stored inside a pointer to a pointer to an int?</p>


<!-- Quiz question Answers -->
<ul class="quiz_question_answers" data-question-id="458">
<li class="">

<input type="radio" name="458" id="458-1506908663220" value="1506908663220" data-quiz-answer-id="1506908663220" data-quiz-question-id="458" disabled="disabled" />
<label for="458-1506908663220"><p>An address where an int is stored</p>
</label>
</li>

<li class="">

<input type="radio" name="458" id="458-1506908732098" value="1506908732098" data-quiz-answer-id="1506908732098" data-quiz-question-id="458" disabled="disabled" checked="checked" />
<label for="458-1506908732098"><p>An address where an address is stored</p>
</label>
</li>

<li class="">

<input type="radio" name="458" id="458-1506908729513" value="1506908729513" data-quiz-answer-id="1506908729513" data-quiz-question-id="458" disabled="disabled" />
<label for="458-1506908729513"><p>An int</p>
</label>
</li>

</ul>

<!-- Quiz question Tips -->

</div>

</div>
<div class="quiz_question_item_container" data-role="quiz_question456" data-position="7">
<div class=" clearfix" id="quiz_question-456">

<h4 class="quiz_question">

Question #3
</h4>

<!-- Quiz question Body -->
<p>What is the size of <code>*p</code> in this code?</p>

<pre><code>int **p;
</code></pre>


<!-- Quiz question Answers -->
<ul class="quiz_question_answers" data-question-id="456">
<li class="">

<input type="radio" name="456" id="456-1506908631679" value="1506908631679" data-quiz-answer-id="1506908631679" data-quiz-question-id="456" disabled="disabled" />
<label for="456-1506908631679"><p>4 bytes</p>
</label>
</li>

<li class="">

<input type="radio" name="456" id="456-1506908640351" value="1506908640351" data-quiz-answer-id="1506908640351" data-quiz-question-id="456" disabled="disabled" />
<label for="456-1506908640351"><p>16 bytes</p>
</label>
</li>

<li class="">

<input type="radio" name="456" id="456-1506908635336" value="1506908635336" data-quiz-answer-id="1506908635336" data-quiz-question-id="456" disabled="disabled" checked="checked" />
<label for="456-1506908635336"><p>8 bytes</p>
</label>
</li>

</ul>

<!-- Quiz question Tips -->

</div>

</div>
<div class="quiz_question_item_container" data-role="quiz_question439" data-position="1">
<div class=" clearfix" id="quiz_question-439">

<h4 class="quiz_question">

Question #4
</h4>

<!-- Quiz question Body -->
<p>What is the size of <code>p</code> in this code?</p>

<pre><code>int *p;
</code></pre>


<!-- Quiz question Answers -->
<ul class="quiz_question_answers" data-question-id="439">
<li class="">

<input type="radio" name="439" id="439-1506906040304" value="1506906040304" data-quiz-answer-id="1506906040304" data-quiz-question-id="439" disabled="disabled" />
<label for="439-1506906040304"><p>4 bytes</p>
</label>
</li>

<li class="">

<input type="radio" name="439" id="439-1506906053536" value="1506906053536" data-quiz-answer-id="1506906053536" data-quiz-question-id="439" disabled="disabled" />
<label for="439-1506906053536"><p>16 bytes</p>
</label>
</li>

<li class="">

<input type="radio" name="439" id="439-1506906046166" value="1506906046166" data-quiz-answer-id="1506906046166" data-quiz-question-id="439" disabled="disabled" checked="checked" />
<label for="439-1506906046166"><p>8 bytes</p>
</label>
</li>

</ul>

<!-- Quiz question Tips -->

</div>

</div>
<div class="quiz_question_item_container" data-role="quiz_question443" data-position="5">
<div class=" clearfix" id="quiz_question-443">

<h4 class="quiz_question">

Question #5
</h4>

<!-- Quiz question Body -->
<p>In this following code, what is the value of <code>a[3][1]</code>?</p>

<pre><code>int a[5][2] = {{1, 2}, {3, 4}, {5, 6}, {7, 8}, {9, 10}};
</code></pre>


<!-- Quiz question Answers -->
<ul class="quiz_question_answers" data-question-id="443">
<li class="">

<input type="radio" name="443" id="443-1506906141920" value="1506906141920" data-quiz-answer-id="1506906141920" data-quiz-question-id="443" disabled="disabled" />
<label for="443-1506906141920"><p>{7, 8}</p>
</label>
</li>

<li class="">

<input type="radio" name="443" id="443-1506906131459" value="1506906131459" data-quiz-answer-id="1506906131459" data-quiz-question-id="443" disabled="disabled" />
<label for="443-1506906131459"><p>7</p>
</label>
</li>

<li class="">

<input type="radio" name="443" id="443-1506906153329" value="1506906153329" data-quiz-answer-id="1506906153329" data-quiz-question-id="443" disabled="disabled" checked="checked" />
<label for="443-1506906153329"><p>8</p>
</label>
</li>

<li class="">

<input type="radio" name="443" id="443-1506906134046" value="1506906134046" data-quiz-answer-id="1506906134046" data-quiz-question-id="443" disabled="disabled" />
<label for="443-1506906134046"><p>9</p>
</label>
</li>

</ul>

<!-- Quiz question Tips -->

</div>

</div>
<div class="quiz_question_item_container" data-role="quiz_question444" data-position="6">
<div class=" clearfix" id="quiz_question-444">

<h4 class="quiz_question">

Question #6
</h4>

<!-- Quiz question Body -->
<p>In this following code, what is the value of <code>a[1][1]</code>?</p>

<pre><code>int a[5][2] = {{1, 2}, {3, 4}, {5, 6}, {7, 8}, {9, 10}};
</code></pre>


<!-- Quiz question Answers -->
<ul class="quiz_question_answers" data-question-id="444">
<li class="">

<input type="radio" name="444" id="444-1506906170844" value="1506906170844" data-quiz-answer-id="1506906170844" data-quiz-question-id="444" disabled="disabled" />
<label for="444-1506906170844"><p>3</p>
</label>
</li>

<li class="">

<input type="radio" name="444" id="444-1506906161320" value="1506906161320" data-quiz-answer-id="1506906161320" data-quiz-question-id="444" disabled="disabled" />
<label for="444-1506906161320"><p>1</p>
</label>
</li>

<li class="">

<input type="radio" name="444" id="444-1506906172981" value="1506906172981" data-quiz-answer-id="1506906172981" data-quiz-question-id="444" disabled="disabled" checked="checked" />
<label for="444-1506906172981"><p>4</p>
</label>
</li>

<li class="">

<input type="radio" name="444" id="444-1506906163778" value="1506906163778" data-quiz-answer-id="1506906163778" data-quiz-question-id="444" disabled="disabled" />
<label for="444-1506906163778"><p>2</p>
</label>
</li>

</ul>

<!-- Quiz question Tips -->

</div>

</div>
<div class="quiz_question_item_container" data-role="quiz_question440" data-position="2">
<div class=" clearfix" id="quiz_question-440">

<h4 class="quiz_question">

Question #7
</h4>

<!-- Quiz question Body -->
<p>What is the size of <code>p</code> in this code?</p>

<pre><code>int **p;
</code></pre>


<!-- Quiz question Answers -->
<ul class="quiz_question_answers" data-question-id="440">
<li class="">

<input type="radio" name="440" id="440-1506906065751" value="1506906065751" data-quiz-answer-id="1506906065751" data-quiz-question-id="440" disabled="disabled" />
<label for="440-1506906065751"><p>4 bytes</p>
</label>
</li>

<li class="">

<input type="radio" name="440" id="440-1506906081562" value="1506906081562" data-quiz-answer-id="1506906081562" data-quiz-question-id="440" disabled="disabled" />
<label for="440-1506906081562"><p>16 bytes</p>
</label>
</li>

<li class="">

<input type="radio" name="440" id="440-1506906071304" value="1506906071304" data-quiz-answer-id="1506906071304" data-quiz-question-id="440" disabled="disabled" checked="checked" />
<label for="440-1506906071304"><p>8 bytes</p>
</label>
</li>

</ul>

<!-- Quiz question Tips -->

</div>

</div>
<div class="quiz_question_item_container" data-role="quiz_question457" data-position="8">
<div class=" clearfix" id="quiz_question-457">

<h4 class="quiz_question">

Question #8
</h4>

<!-- Quiz question Body -->
<p>What is the size of <code>*p</code> in this code?</p>

<pre><code>int *p;
</code></pre>


<!-- Quiz question Answers -->
<ul class="quiz_question_answers" data-question-id="457">
<li class="">

<input type="radio" name="457" id="457-1506908645410" value="1506908645410" data-quiz-answer-id="1506908645410" data-quiz-question-id="457" disabled="disabled" checked="checked" />
<label for="457-1506908645410"><p>4 bytes</p>
</label>
</li>

<li class="">

<input type="radio" name="457" id="457-1506908657387" value="1506908657387" data-quiz-answer-id="1506908657387" data-quiz-question-id="457" disabled="disabled" />
<label for="457-1506908657387"><p>16 bytes</p>
</label>
</li>

<li class="">

<input type="radio" name="457" id="457-1506908652592" value="1506908652592" data-quiz-answer-id="1506908652592" data-quiz-question-id="457" disabled="disabled" />
<label for="457-1506908652592"><p>8 bytes</p>
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

<div data-role="task903" data-position="1" id="task-num-0">
<div class="panel panel-default task-card " id="task-903">
<span id="user_id" data-id="197885"></span>

<div class="panel-heading panel-heading-actions">
<h3 class="panel-title">
0. memset
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
<p>Write a function that fills memory with a constant byte.</p>

<ul>
<li>Prototype: <code>char *_memset(char *s, char b, unsigned int n);</code></li>
<li>The <code>_memset()</code> function fills the first <code>n</code> bytes of the memory area pointed to by <code>s</code> with the constant byte <code>b</code></li>
<li>Returns a pointer to the memory area <code>s</code></li>
</ul>

<p>FYI: The standard library provides a similar function: <code>memset</code>. Run <code>man memset</code> to learn more.</p>

<pre><code>julien@ubuntu:~/0x07$ cat 0-main.c
#include &quot;main.h&quot;
#include &lt;stdio.h&gt;

/**
* simple_print_buffer - prints buffer in hexa
* @buffer: the address of memory to print
* @size: the size of the memory to print
*
* Return: Nothing.
*/
void simple_print_buffer(char *buffer, unsigned int size)
{
unsigned int i;

i = 0;
while (i &lt; size)
{
if (i % 10)
{
printf(&quot; &quot;);
}
if (!(i % 10) &amp;&amp; i)
{
printf(&quot;\n&quot;);
}
printf(&quot;0x%02x&quot;, buffer[i]);
i++;
}
printf(&quot;\n&quot;);
}

/**
* main - check the code
*
* Return: Always 0.
*/
int main(void)
{
char buffer[98] = {0x00};

simple_print_buffer(buffer, 98);
_memset(buffer, 0x01, 95);
printf(&quot;-------------------------------------------------\n&quot;);
simple_print_buffer(buffer, 98);    
return (0);
}
julien@ubuntu:~/0x07$ gcc -Wall -pedantic -Werror -Wextra -std=gnu89 0-main.c 0-memset.c -o 0-memset
julien@ubuntu:~/0x07$ ./0-memset 
0x00 0x00 0x00 0x00 0x00 0x00 0x00 0x00 0x00 0x00
0x00 0x00 0x00 0x00 0x00 0x00 0x00 0x00 0x00 0x00
0x00 0x00 0x00 0x00 0x00 0x00 0x00 0x00 0x00 0x00
0x00 0x00 0x00 0x00 0x00 0x00 0x00 0x00 0x00 0x00
0x00 0x00 0x00 0x00 0x00 0x00 0x00 0x00 0x00 0x00
0x00 0x00 0x00 0x00 0x00 0x00 0x00 0x00 0x00 0x00
0x00 0x00 0x00 0x00 0x00 0x00 0x00 0x00 0x00 0x00
0x00 0x00 0x00 0x00 0x00 0x00 0x00 0x00 0x00 0x00
0x00 0x00 0x00 0x00 0x00 0x00 0x00 0x00 0x00 0x00
0x00 0x00 0x00 0x00 0x00 0x00 0x00 0x00
-------------------------------------------------
0x01 0x01 0x01 0x01 0x01 0x01 0x01 0x01 0x01 0x01
0x01 0x01 0x01 0x01 0x01 0x01 0x01 0x01 0x01 0x01
0x01 0x01 0x01 0x01 0x01 0x01 0x01 0x01 0x01 0x01
0x01 0x01 0x01 0x01 0x01 0x01 0x01 0x01 0x01 0x01
0x01 0x01 0x01 0x01 0x01 0x01 0x01 0x01 0x01 0x01
0x01 0x01 0x01 0x01 0x01 0x01 0x01 0x01 0x01 0x01
0x01 0x01 0x01 0x01 0x01 0x01 0x01 0x01 0x01 0x01
0x01 0x01 0x01 0x01 0x01 0x01 0x01 0x01 0x01 0x01
0x01 0x01 0x01 0x01 0x01 0x01 0x01 0x01 0x01 0x01
0x01 0x01 0x01 0x01 0x01 0x00 0x00 0x00
julien@ubuntu:~/0x07$ 
</code></pre>

</div>

<div class="list-group">
<!-- Task URLs -->

<!-- Github information -->
<div class="list-group-item">
<p><strong>Repo:</strong></p>
<ul>
<li>GitHub repository: <code>alx-low_level_programming</code></li>
<li>Directory: <code>0x07-pointers_arrays_strings</code></li>
<li>File: <code>0-memset.c</code></li>
</ul>
</div>

<!-- Self-paced manual review -->
</div>

<!-- Panel footer - Controls -->
<div class="panel-footer">
<div class="align-items-center d-flex justify-content-between">

<div>
<button class="student_task_done btn btn-default btn-sm no" data-task-id="903">
<span class="no"><i aria-hidden="true" class="fa fa-square-o "></i></span>
<span class="yes"><i aria-hidden="true" class="fa fa-check-square-o "></i></span>
<span class="pending"><i aria-hidden="true" class="fa fa-spinner  fa-pulse"></i></span>
Done<span class="no pending">?</span><span class="yes">!</span>
</button>

<button class="student-task-done-by btn btn-default btn-sm" data-task-id="903" data-batch-id="26" data-toggle="modal" data-target="#task-903-users-done-modal">
Help
</button>
<div class="modal fade users-done-modal" id="task-903-users-done-modal" data-task-id="903" data-batch-id="26">
<div class="modal-dialog">
<div class="modal-content">
<div class="modal-header">
<button type="button" class="close" data-dismiss="modal" aria-label="Close"><span aria-hidden="true">&times;</span></button>
<h4 class="modal-title">Students who are done with "0. memset"</h4>
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


<button class="btn btn-default btn-sm check-your-task-903-modal-button" data-task-id="903" data-toggle="modal" data-target="#task-test-correction-903-correction-modal" id="task-num-0-check-code-btn" data-gtm-custom-event-name="task_checker_modal" data-gtm-custom-event-options='{&quot;taskId&quot;:903}'>
Check your code
</button>
<div class="modal fade task_correction_modal student_modal" id="task-test-correction-903-correction-modal">
<div class="modal-dialog">
<div class="modal-content">
<div class="modal-header">
<button type="button" class="close" data-dismiss="modal" aria-label="Close"><span aria-hidden="true">&times;</span></button>
<h4 class="modal-title">Correction of "0. memset"</h4>
</div>
<div class="modal-body">
<div class="actions">
<center>
<div class="alert alert-info hidden"></div>

<button name="button" type="submit" class="btn btn-primary correction_request_test_send" data-task-id="903">Start a new test</button>
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
<button data-task-id="903">
<i aria-hidden="true" class="fa fa-info-circle "></i>
</button>
<div class="help-container" data-task-id="903">
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



<button class="btn btn-default btn-sm" data-toggle="modal" data-target="#container-specs-modal" data-gtm-custom-event-name="task_sandbox_modal" data-gtm-custom-event-options="{&quot;taskId&quot;:903}"><i aria-hidden="true" class="fa fa-terminal "></i><span>Get a sandbox</span></button>

</div>


<div class="fs-4">
</div>
</div>


</div>
</div>

</div>
<div data-role="task904" data-position="2" id="task-num-1">
<div class="panel panel-default task-card " id="task-904">
<span id="user_id" data-id="197885"></span>

<div class="panel-heading panel-heading-actions">
<h3 class="panel-title">
1. memcpy
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
<p>Write a function that copies memory area.</p>

<ul>
<li>Prototype: <code>char *_memcpy(char *dest, char *src, unsigned int n);</code></li>
<li>The <code>_memcpy()</code>  function  copies <code>n</code> bytes from memory area <code>src</code> to memory area <code>dest</code></li>
<li>Returns a pointer to <code>dest</code></li>
</ul>

<p>FYI: The standard library provides a similar function: <code>memcpy</code>. Run <code>man memcpy</code> to learn more.</p>

<pre><code>julien@ubuntu:~/0x07$ cat 1-main.c
#include &quot;main.h&quot;
#include &lt;stdio.h&gt;

/**
* simple_print_buffer - prints buffer in hexa
* @buffer: the address of memory to print
* @size: the size of the memory to print
*
* Return: Nothing.
*/
void simple_print_buffer(char *buffer, unsigned int size)
{
unsigned int i;

i = 0;
while (i &lt; size)
{
if (i % 10)
{
printf(&quot; &quot;);
}
if (!(i % 10) &amp;&amp; i)
{
printf(&quot;\n&quot;);
}
printf(&quot;0x%02x&quot;, buffer[i]);
i++;
}
printf(&quot;\n&quot;);
}

/**
* main - check the code
*
* Return: Always 0.
*/
int main(void)
{
char buffer[98] = {0};
char buffer2[98] = {1, 2, 3, 4, 5, 6, 7, 8, 9, 10, 11, 12, 13, 14};

simple_print_buffer(buffer, 98);
_memcpy(buffer + 50, buffer2, 10);
printf(&quot;-------------------------------------------------\n&quot;);
simple_print_buffer(buffer, 98);    
return (0);
}
julien@ubuntu:~/0x07$ gcc -Wall -pedantic -Werror -Wextra -std=gnu89 1-main.c 1-memcpy.c -o 1-memcpy
julien@ubuntu:~/0x07$ ./1-memcpy 
0x00 0x00 0x00 0x00 0x00 0x00 0x00 0x00 0x00 0x00
0x00 0x00 0x00 0x00 0x00 0x00 0x00 0x00 0x00 0x00
0x00 0x00 0x00 0x00 0x00 0x00 0x00 0x00 0x00 0x00
0x00 0x00 0x00 0x00 0x00 0x00 0x00 0x00 0x00 0x00
0x00 0x00 0x00 0x00 0x00 0x00 0x00 0x00 0x00 0x00
0x00 0x00 0x00 0x00 0x00 0x00 0x00 0x00 0x00 0x00
0x00 0x00 0x00 0x00 0x00 0x00 0x00 0x00 0x00 0x00
0x00 0x00 0x00 0x00 0x00 0x00 0x00 0x00 0x00 0x00
0x00 0x00 0x00 0x00 0x00 0x00 0x00 0x00 0x00 0x00
0x00 0x00 0x00 0x00 0x00 0x00 0x00 0x00
-------------------------------------------------
0x00 0x00 0x00 0x00 0x00 0x00 0x00 0x00 0x00 0x00
0x00 0x00 0x00 0x00 0x00 0x00 0x00 0x00 0x00 0x00
0x00 0x00 0x00 0x00 0x00 0x00 0x00 0x00 0x00 0x00
0x00 0x00 0x00 0x00 0x00 0x00 0x00 0x00 0x00 0x00
0x00 0x00 0x00 0x00 0x00 0x00 0x00 0x00 0x00 0x00
0x01 0x02 0x03 0x04 0x05 0x07 0x07 0x08 0x09 0x0a
0x00 0x00 0x00 0x00 0x00 0x00 0x00 0x00 0x00 0x00
0x00 0x00 0x00 0x00 0x00 0x00 0x00 0x00 0x00 0x00
0x00 0x00 0x00 0x00 0x00 0x00 0x00 0x00 0x00 0x00
0x00 0x00 0x00 0x00 0x00 0x00 0x00 0x00
julien@ubuntu:~/0x07$ 
</code></pre>

</div>

<div class="list-group">
<!-- Task URLs -->

<!-- Github information -->
<div class="list-group-item">
<p><strong>Repo:</strong></p>
<ul>
<li>GitHub repository: <code>alx-low_level_programming</code></li>
<li>Directory: <code>0x07-pointers_arrays_strings</code></li>
<li>File: <code>1-memcpy.c</code></li>
</ul>
</div>

<!-- Self-paced manual review -->
</div>

<!-- Panel footer - Controls -->
<div class="panel-footer">
<div class="align-items-center d-flex justify-content-between">

<div>
<button class="student_task_done btn btn-default btn-sm no" data-task-id="904">
<span class="no"><i aria-hidden="true" class="fa fa-square-o "></i></span>
<span class="yes"><i aria-hidden="true" class="fa fa-check-square-o "></i></span>
<span class="pending"><i aria-hidden="true" class="fa fa-spinner  fa-pulse"></i></span>
Done<span class="no pending">?</span><span class="yes">!</span>
</button>

<button class="student-task-done-by btn btn-default btn-sm" data-task-id="904" data-batch-id="26" data-toggle="modal" data-target="#task-904-users-done-modal">
Help
</button>
<div class="modal fade users-done-modal" id="task-904-users-done-modal" data-task-id="904" data-batch-id="26">
<div class="modal-dialog">
<div class="modal-content">
<div class="modal-header">
<button type="button" class="close" data-dismiss="modal" aria-label="Close"><span aria-hidden="true">&times;</span></button>
<h4 class="modal-title">Students who are done with "1. memcpy"</h4>
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


<button class="btn btn-default btn-sm check-your-task-904-modal-button" data-task-id="904" data-toggle="modal" data-target="#task-test-correction-904-correction-modal" id="task-num-1-check-code-btn" data-gtm-custom-event-name="task_checker_modal" data-gtm-custom-event-options='{&quot;taskId&quot;:904}'>
Check your code
</button>
<div class="modal fade task_correction_modal student_modal" id="task-test-correction-904-correction-modal">
<div class="modal-dialog">
<div class="modal-content">
<div class="modal-header">
<button type="button" class="close" data-dismiss="modal" aria-label="Close"><span aria-hidden="true">&times;</span></button>
<h4 class="modal-title">Correction of "1. memcpy"</h4>
</div>
<div class="modal-body">
<div class="actions">
<center>
<div class="alert alert-info hidden"></div>

<button name="button" type="submit" class="btn btn-primary correction_request_test_send" data-task-id="904">Start a new test</button>
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
<button data-task-id="904">
<i aria-hidden="true" class="fa fa-info-circle "></i>
</button>
<div class="help-container" data-task-id="904">
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



<button class="btn btn-default btn-sm" data-toggle="modal" data-target="#container-specs-modal" data-gtm-custom-event-name="task_sandbox_modal" data-gtm-custom-event-options="{&quot;taskId&quot;:904}"><i aria-hidden="true" class="fa fa-terminal "></i><span>Get a sandbox</span></button>

</div>


<div class="fs-4">
</div>
</div>


</div>
</div>

</div>
<div data-role="task905" data-position="98" id="task-num-2">
<div class="panel panel-default task-card " id="task-905">
<span id="user_id" data-id="197885"></span>

<div class="panel-heading panel-heading-actions">
<h3 class="panel-title">
2. strchr
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
<p>Write a function that locates a character in a string.</p>

<ul>
<li>Prototype: <code>char *_strchr(char *s, char c);</code></li>
<li>Returns a pointer to the first occurrence of the character <code>c</code> in the string <code>s</code>, or <code>NULL</code> if the character is not  found</li>
</ul>

<p>FYI: The standard library provides a similar function: <code>strchr</code>. Run <code>man strchr</code> to learn more.</p>

<pre><code>julien@ubuntu:~/0x07$ cat 2-main.c
#include &quot;main.h&quot;
#include &lt;stdio.h&gt;

/**
* main - check the code
*
* Return: Always 0.
*/
int main(void)
{
char *s = &quot;hello&quot;;
char *f;

f = _strchr(s, &#39;l&#39;);

if (f != NULL)
{
printf(&quot;%s\n&quot;, f);
}
return (0);
}
julien@ubuntu:~/0x07$ gcc -Wall -pedantic -Werror -Wextra -std=gnu89 2-main.c 2-strchr.c -o 2-strchr
julien@ubuntu:~/0x07$ ./2-strchr 
llo
julien@ubuntu:~/0x07$ 
</code></pre>

</div>

<div class="list-group">
<!-- Task URLs -->

<!-- Github information -->
<div class="list-group-item">
<p><strong>Repo:</strong></p>
<ul>
<li>GitHub repository: <code>alx-low_level_programming</code></li>
<li>Directory: <code>0x07-pointers_arrays_strings</code></li>
<li>File: <code>2-strchr.c</code></li>
</ul>
</div>

<!-- Self-paced manual review -->
</div>

<!-- Panel footer - Controls -->
<div class="panel-footer">
<div class="align-items-center d-flex justify-content-between">

<div>
<button class="student_task_done btn btn-default btn-sm no" data-task-id="905">
<span class="no"><i aria-hidden="true" class="fa fa-square-o "></i></span>
<span class="yes"><i aria-hidden="true" class="fa fa-check-square-o "></i></span>
<span class="pending"><i aria-hidden="true" class="fa fa-spinner  fa-pulse"></i></span>
Done<span class="no pending">?</span><span class="yes">!</span>
</button>

<button class="student-task-done-by btn btn-default btn-sm" data-task-id="905" data-batch-id="26" data-toggle="modal" data-target="#task-905-users-done-modal">
Help
</button>
<div class="modal fade users-done-modal" id="task-905-users-done-modal" data-task-id="905" data-batch-id="26">
<div class="modal-dialog">
<div class="modal-content">
<div class="modal-header">
<button type="button" class="close" data-dismiss="modal" aria-label="Close"><span aria-hidden="true">&times;</span></button>
<h4 class="modal-title">Students who are done with "2. strchr"</h4>
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


<button class="btn btn-default btn-sm check-your-task-905-modal-button" data-task-id="905" data-toggle="modal" data-target="#task-test-correction-905-correction-modal" id="task-num-2-check-code-btn" data-gtm-custom-event-name="task_checker_modal" data-gtm-custom-event-options='{&quot;taskId&quot;:905}'>
Check your code
</button>
<div class="modal fade task_correction_modal student_modal" id="task-test-correction-905-correction-modal">
<div class="modal-dialog">
<div class="modal-content">
<div class="modal-header">
<button type="button" class="close" data-dismiss="modal" aria-label="Close"><span aria-hidden="true">&times;</span></button>
<h4 class="modal-title">Correction of "2. strchr"</h4>
</div>
<div class="modal-body">
<div class="actions">
<center>
<div class="alert alert-info hidden"></div>

<button name="button" type="submit" class="btn btn-primary correction_request_test_send" data-task-id="905">Start a new test</button>
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
<button data-task-id="905">
<i aria-hidden="true" class="fa fa-info-circle "></i>
</button>
<div class="help-container" data-task-id="905">
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



<button class="btn btn-default btn-sm" data-toggle="modal" data-target="#container-specs-modal" data-gtm-custom-event-name="task_sandbox_modal" data-gtm-custom-event-options="{&quot;taskId&quot;:905}"><i aria-hidden="true" class="fa fa-terminal "></i><span>Get a sandbox</span></button>

</div>


<div class="fs-4">
</div>
</div>


</div>
</div>

</div>
<div data-role="task906" data-position="99" id="task-num-3">
<div class="panel panel-default task-card " id="task-906">
<span id="user_id" data-id="197885"></span>

<div class="panel-heading panel-heading-actions">
<h3 class="panel-title">
3. strspn
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
<p>Write a function that gets the length of a prefix substring.</p>

<ul>
<li>Prototype: <code>unsigned int _strspn(char *s, char *accept);</code></li>
<li>Returns the number of bytes in the initial segment of <code>s</code> which consist only of bytes from <code>accept</code></li>
</ul>

<p>FYI: The standard library provides a similar function: <code>strspn</code>. Run <code>man strspn</code> to learn more.</p>

<pre><code>julien@ubuntu:~/0x07$ cat 3-main.c
#include &quot;main.h&quot;
#include &lt;stdio.h&gt;

/**
* main - check the code
*
* Return: Always 0.
*/
int main(void)
{
char *s = &quot;hello, world&quot;;
char *f = &quot;oleh&quot;;
unsigned int n;

n = _strspn(s, f);
printf(&quot;%u\n&quot;, n);
return (0);
}
julien@ubuntu:~/0x07$ gcc -Wall -pedantic -Werror -Wextra -std=gnu89 3-main.c 3-strspn.c -o 3-strspn
julien@ubuntu:~/0x07$ ./3-strspn 
5
julien@ubuntu:~/0x07$ 
</code></pre>

</div>

<div class="list-group">
<!-- Task URLs -->

<!-- Github information -->
<div class="list-group-item">
<p><strong>Repo:</strong></p>
<ul>
<li>GitHub repository: <code>alx-low_level_programming</code></li>
<li>Directory: <code>0x07-pointers_arrays_strings</code></li>
<li>File: <code>3-strspn.c</code></li>
</ul>
</div>

<!-- Self-paced manual review -->
</div>

<!-- Panel footer - Controls -->
<div class="panel-footer">
<div class="align-items-center d-flex justify-content-between">

<div>
<button class="student_task_done btn btn-default btn-sm no" data-task-id="906">
<span class="no"><i aria-hidden="true" class="fa fa-square-o "></i></span>
<span class="yes"><i aria-hidden="true" class="fa fa-check-square-o "></i></span>
<span class="pending"><i aria-hidden="true" class="fa fa-spinner  fa-pulse"></i></span>
Done<span class="no pending">?</span><span class="yes">!</span>
</button>

<button class="student-task-done-by btn btn-default btn-sm" data-task-id="906" data-batch-id="26" data-toggle="modal" data-target="#task-906-users-done-modal">
Help
</button>
<div class="modal fade users-done-modal" id="task-906-users-done-modal" data-task-id="906" data-batch-id="26">
<div class="modal-dialog">
<div class="modal-content">
<div class="modal-header">
<button type="button" class="close" data-dismiss="modal" aria-label="Close"><span aria-hidden="true">&times;</span></button>
<h4 class="modal-title">Students who are done with "3. strspn"</h4>
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


<button class="btn btn-default btn-sm check-your-task-906-modal-button" data-task-id="906" data-toggle="modal" data-target="#task-test-correction-906-correction-modal" id="task-num-3-check-code-btn" data-gtm-custom-event-name="task_checker_modal" data-gtm-custom-event-options='{&quot;taskId&quot;:906}'>
Check your code
</button>
<div class="modal fade task_correction_modal student_modal" id="task-test-correction-906-correction-modal">
<div class="modal-dialog">
<div class="modal-content">
<div class="modal-header">
<button type="button" class="close" data-dismiss="modal" aria-label="Close"><span aria-hidden="true">&times;</span></button>
<h4 class="modal-title">Correction of "3. strspn"</h4>
</div>
<div class="modal-body">
<div class="actions">
<center>
<div class="alert alert-info hidden"></div>

<button name="button" type="submit" class="btn btn-primary correction_request_test_send" data-task-id="906">Start a new test</button>
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
<button data-task-id="906">
<i aria-hidden="true" class="fa fa-info-circle "></i>
</button>
<div class="help-container" data-task-id="906">
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



<button class="btn btn-default btn-sm" data-toggle="modal" data-target="#container-specs-modal" data-gtm-custom-event-name="task_sandbox_modal" data-gtm-custom-event-options="{&quot;taskId&quot;:906}"><i aria-hidden="true" class="fa fa-terminal "></i><span>Get a sandbox</span></button>

</div>


<div class="fs-4">
</div>
</div>


</div>
</div>

</div>
<div data-role="task907" data-position="100" id="task-num-4">
<div class="panel panel-default task-card " id="task-907">
<span id="user_id" data-id="197885"></span>

<div class="panel-heading panel-heading-actions">
<h3 class="panel-title">
4. strpbrk
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
<p>Write a function that searches a string for any of a set of bytes.</p>

<ul>
<li>Prototype: <code>char *_strpbrk(char *s, char *accept);</code></li>
<li>The <code>_strpbrk()</code>  function locates the first occurrence in the string <code>s</code> of any of the bytes in the string <code>accept</code></li>
<li>Returns a pointer to the byte in <code>s</code> that matches one of the bytes in <code>accept</code>,  or <code>NULL</code> if no such byte is found</li>
</ul>

<p>FYI: The standard library provides a similar function: <code>strpbrk</code>. Run <code>man strpbrk</code> to learn more.</p>

<pre><code>julien@ubuntu:~/0x07$ cat 4-main.c
#include &quot;main.h&quot;
#include &lt;stdio.h&gt;

/**
* main - check the code
*
* Return: Always 0.
*/
int main(void)
{
char *s = &quot;hello, world&quot;;
char *f = &quot;world&quot;;
char *t;

t = _strpbrk(s, f);
printf(&quot;%s\n&quot;, t);
return (0);
}
julien@ubuntu:~/0x07$ gcc -Wall -pedantic -Werror -Wextra -std=gnu89 4-main.c 4-strpbrk.c -o 4-strpbrk
julien@ubuntu:~/0x07$ ./4-strpbrk 
llo, world
julien@ubuntu:~/0x07$ 
</code></pre>

</div>

<div class="list-group">
<!-- Task URLs -->

<!-- Github information -->
<div class="list-group-item">
<p><strong>Repo:</strong></p>
<ul>
<li>GitHub repository: <code>alx-low_level_programming</code></li>
<li>Directory: <code>0x07-pointers_arrays_strings</code></li>
<li>File: <code>4-strpbrk.c</code></li>
</ul>
</div>

<!-- Self-paced manual review -->
</div>

<!-- Panel footer - Controls -->
<div class="panel-footer">
<div class="align-items-center d-flex justify-content-between">

<div>
<button class="student_task_done btn btn-default btn-sm no" data-task-id="907">
<span class="no"><i aria-hidden="true" class="fa fa-square-o "></i></span>
<span class="yes"><i aria-hidden="true" class="fa fa-check-square-o "></i></span>
<span class="pending"><i aria-hidden="true" class="fa fa-spinner  fa-pulse"></i></span>
Done<span class="no pending">?</span><span class="yes">!</span>
</button>

<button class="student-task-done-by btn btn-default btn-sm" data-task-id="907" data-batch-id="26" data-toggle="modal" data-target="#task-907-users-done-modal">
Help
</button>
<div class="modal fade users-done-modal" id="task-907-users-done-modal" data-task-id="907" data-batch-id="26">
<div class="modal-dialog">
<div class="modal-content">
<div class="modal-header">
<button type="button" class="close" data-dismiss="modal" aria-label="Close"><span aria-hidden="true">&times;</span></button>
<h4 class="modal-title">Students who are done with "4. strpbrk"</h4>
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


<button class="btn btn-default btn-sm check-your-task-907-modal-button" data-task-id="907" data-toggle="modal" data-target="#task-test-correction-907-correction-modal" id="task-num-4-check-code-btn" data-gtm-custom-event-name="task_checker_modal" data-gtm-custom-event-options='{&quot;taskId&quot;:907}'>
Check your code
</button>
<div class="modal fade task_correction_modal student_modal" id="task-test-correction-907-correction-modal">
<div class="modal-dialog">
<div class="modal-content">
<div class="modal-header">
<button type="button" class="close" data-dismiss="modal" aria-label="Close"><span aria-hidden="true">&times;</span></button>
<h4 class="modal-title">Correction of "4. strpbrk"</h4>
</div>
<div class="modal-body">
<div class="actions">
<center>
<div class="alert alert-info hidden"></div>

<button name="button" type="submit" class="btn btn-primary correction_request_test_send" data-task-id="907">Start a new test</button>
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
<button data-task-id="907">
<i aria-hidden="true" class="fa fa-info-circle "></i>
</button>
<div class="help-container" data-task-id="907">
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



<button class="btn btn-default btn-sm" data-toggle="modal" data-target="#container-specs-modal" data-gtm-custom-event-name="task_sandbox_modal" data-gtm-custom-event-options="{&quot;taskId&quot;:907}"><i aria-hidden="true" class="fa fa-terminal "></i><span>Get a sandbox</span></button>

</div>


<div class="fs-4">
</div>
</div>


</div>
</div>

</div>
<div data-role="task908" data-position="101" id="task-num-5">
<div class="panel panel-default task-card " id="task-908">
<span id="user_id" data-id="197885"></span>

<div class="panel-heading panel-heading-actions">
<h3 class="panel-title">
5. strstr
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
<p>Write a function that locates a substring.</p>

<ul>
<li>Prototype: <code>char *_strstr(char *haystack, char *needle);</code></li>
<li>The <code>_strstr()</code> function finds the first occurrence of the substring <code>needle</code> in the string <code>haystack</code>.  The terminating null bytes (<code>\0</code>) are not compared</li>
<li>Returns a pointer to the beginning of the located substring, or <code>NULL</code> if the substring is not found.</li>
</ul>

<p>FYI: The standard library provides a similar function: <code>strstr</code>. Run <code>man strstr</code> to learn more.</p>

<pre><code>julien@ubuntu:~/0x07$ cat 5-main.c
#include &quot;main.h&quot;
#include &lt;stdio.h&gt;

/**
* main - check the code
*
* Return: Always 0.
*/
int main(void)
{
char *s = &quot;hello, world&quot;;
char *f = &quot;world&quot;;
char *t;

t = _strstr(s, f);
printf(&quot;%s\n&quot;, t);
return (0);
}
julien@ubuntu:~/0x07$ gcc -Wall -pedantic -Werror -Wextra -std=gnu89 5-main.c 5-strstr.c -o 5-strstr
julien@ubuntu:~/0x07$ ./5-strstr 
world
julien@ubuntu:~/0x07$ 

</code></pre>

</div>

<div class="list-group">
<!-- Task URLs -->

<!-- Github information -->
<div class="list-group-item">
<p><strong>Repo:</strong></p>
<ul>
<li>GitHub repository: <code>alx-low_level_programming</code></li>
<li>Directory: <code>0x07-pointers_arrays_strings</code></li>
<li>File: <code>5-strstr.c</code></li>
</ul>
</div>

<!-- Self-paced manual review -->
</div>

<!-- Panel footer - Controls -->
<div class="panel-footer">
<div class="align-items-center d-flex justify-content-between">

<div>
<button class="student_task_done btn btn-default btn-sm no" data-task-id="908">
<span class="no"><i aria-hidden="true" class="fa fa-square-o "></i></span>
<span class="yes"><i aria-hidden="true" class="fa fa-check-square-o "></i></span>
<span class="pending"><i aria-hidden="true" class="fa fa-spinner  fa-pulse"></i></span>
Done<span class="no pending">?</span><span class="yes">!</span>
</button>

<button class="student-task-done-by btn btn-default btn-sm" data-task-id="908" data-batch-id="26" data-toggle="modal" data-target="#task-908-users-done-modal">
Help
</button>
<div class="modal fade users-done-modal" id="task-908-users-done-modal" data-task-id="908" data-batch-id="26">
<div class="modal-dialog">
<div class="modal-content">
<div class="modal-header">
<button type="button" class="close" data-dismiss="modal" aria-label="Close"><span aria-hidden="true">&times;</span></button>
<h4 class="modal-title">Students who are done with "5. strstr"</h4>
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


<button class="btn btn-default btn-sm check-your-task-908-modal-button" data-task-id="908" data-toggle="modal" data-target="#task-test-correction-908-correction-modal" id="task-num-5-check-code-btn" data-gtm-custom-event-name="task_checker_modal" data-gtm-custom-event-options='{&quot;taskId&quot;:908}'>
Check your code
</button>
<div class="modal fade task_correction_modal student_modal" id="task-test-correction-908-correction-modal">
<div class="modal-dialog">
<div class="modal-content">
<div class="modal-header">
<button type="button" class="close" data-dismiss="modal" aria-label="Close"><span aria-hidden="true">&times;</span></button>
<h4 class="modal-title">Correction of "5. strstr"</h4>
</div>
<div class="modal-body">
<div class="actions">
<center>
<div class="alert alert-info hidden"></div>

<button name="button" type="submit" class="btn btn-primary correction_request_test_send" data-task-id="908">Start a new test</button>
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
<button data-task-id="908">
<i aria-hidden="true" class="fa fa-info-circle "></i>
</button>
<div class="help-container" data-task-id="908">
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



<button class="btn btn-default btn-sm" data-toggle="modal" data-target="#container-specs-modal" data-gtm-custom-event-name="task_sandbox_modal" data-gtm-custom-event-options="{&quot;taskId&quot;:908}"><i aria-hidden="true" class="fa fa-terminal "></i><span>Get a sandbox</span></button>

</div>


<div class="fs-4">
</div>
</div>


</div>
</div>

</div>
<div data-role="task911" data-position="103" id="task-num-6">
<div class="panel panel-default task-card " id="task-911">
<span id="user_id" data-id="197885"></span>

<div class="panel-heading panel-heading-actions">
<h3 class="panel-title">
6. Chess is mental torture
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
<p>Write a function that prints the chessboard.</p>

<ul>
<li>Prototype: <code>void print_chessboard(char (*a)[8]);</code></li>
</ul>

<pre><code>julien@ubuntu:~/0x07$ cat 7-main.c 
#include &quot;main.h&quot;
#include &lt;stdio.h&gt;

/**
* main - check the code
*
* Return: Always 0.
*/
int main(void)
{
char board[8][8] = {
{&#39;r&#39;, &#39;k&#39;, &#39;b&#39;, &#39;q&#39;, &#39;k&#39;, &#39;b&#39;, &#39;k&#39;, &#39;r&#39;},
{&#39;p&#39;, &#39;p&#39;, &#39;p&#39;, &#39;p&#39;, &#39;p&#39;, &#39;p&#39;, &#39;p&#39;, &#39;p&#39;},
{&#39; &#39;, &#39; &#39;, &#39; &#39;, &#39; &#39;, &#39; &#39;, &#39; &#39;, &#39; &#39;, &#39; &#39;},
{&#39; &#39;, &#39; &#39;, &#39; &#39;, &#39; &#39;, &#39; &#39;, &#39; &#39;, &#39; &#39;, &#39; &#39;},
{&#39; &#39;, &#39; &#39;, &#39; &#39;, &#39; &#39;, &#39; &#39;, &#39; &#39;, &#39; &#39;, &#39; &#39;},
{&#39; &#39;, &#39; &#39;, &#39; &#39;, &#39; &#39;, &#39; &#39;, &#39; &#39;, &#39; &#39;, &#39; &#39;},
{&#39;P&#39;, &#39;P&#39;, &#39;P&#39;, &#39;P&#39;, &#39;P&#39;, &#39;P&#39;, &#39;P&#39;, &#39;P&#39;},
{&#39;R&#39;, &#39;K&#39;, &#39;B&#39;, &#39;Q&#39;, &#39;K&#39;, &#39;B&#39;, &#39;K&#39;, &#39;R&#39;},
};
print_chessboard(board);
return (0);
}
julien@ubuntu:~/0x07$ gcc -Wall -pedantic -Werror -Wextra -std=gnu89 _putchar.c 7-main.c 7-print_chessboard.c -o 7-print_chessboard
julien@ubuntu:~/0x07$ ./7-print_chessboard 
rkbqkbkr
pppppppp




PPPPPPPP
RKBQKBKR
julien@ubuntu:~/0x07$ 
</code></pre>

</div>

<div class="list-group">
<!-- Task URLs -->

<!-- Github information -->
<div class="list-group-item">
<p><strong>Repo:</strong></p>
<ul>
<li>GitHub repository: <code>alx-low_level_programming</code></li>
<li>Directory: <code>0x07-pointers_arrays_strings</code></li>
<li>File: <code>7-print_chessboard.c</code></li>
</ul>
</div>

<!-- Self-paced manual review -->
</div>

<!-- Panel footer - Controls -->
<div class="panel-footer">
<div class="align-items-center d-flex justify-content-between">

<div>
<button class="student_task_done btn btn-default btn-sm no" data-task-id="911">
<span class="no"><i aria-hidden="true" class="fa fa-square-o "></i></span>
<span class="yes"><i aria-hidden="true" class="fa fa-check-square-o "></i></span>
<span class="pending"><i aria-hidden="true" class="fa fa-spinner  fa-pulse"></i></span>
Done<span class="no pending">?</span><span class="yes">!</span>
</button>

<button class="student-task-done-by btn btn-default btn-sm" data-task-id="911" data-batch-id="26" data-toggle="modal" data-target="#task-911-users-done-modal">
Help
</button>
<div class="modal fade users-done-modal" id="task-911-users-done-modal" data-task-id="911" data-batch-id="26">
<div class="modal-dialog">
<div class="modal-content">
<div class="modal-header">
<button type="button" class="close" data-dismiss="modal" aria-label="Close"><span aria-hidden="true">&times;</span></button>
<h4 class="modal-title">Students who are done with "6. Chess is mental torture"</h4>
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


<button class="btn btn-default btn-sm check-your-task-911-modal-button" data-task-id="911" data-toggle="modal" data-target="#task-test-correction-911-correction-modal" id="task-num-6-check-code-btn" data-gtm-custom-event-name="task_checker_modal" data-gtm-custom-event-options='{&quot;taskId&quot;:911}'>
Check your code
</button>
<div class="modal fade task_correction_modal student_modal" id="task-test-correction-911-correction-modal">
<div class="modal-dialog">
<div class="modal-content">
<div class="modal-header">
<button type="button" class="close" data-dismiss="modal" aria-label="Close"><span aria-hidden="true">&times;</span></button>
<h4 class="modal-title">Correction of "6. Chess is mental torture"</h4>
</div>
<div class="modal-body">
<div class="actions">
<center>
<div class="alert alert-info hidden"></div>

<button name="button" type="submit" class="btn btn-primary correction_request_test_send" data-task-id="911">Start a new test</button>
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
<button data-task-id="911">
<i aria-hidden="true" class="fa fa-info-circle "></i>
</button>
<div class="help-container" data-task-id="911">
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



<button class="btn btn-default btn-sm" data-toggle="modal" data-target="#container-specs-modal" data-gtm-custom-event-name="task_sandbox_modal" data-gtm-custom-event-options="{&quot;taskId&quot;:911}"><i aria-hidden="true" class="fa fa-terminal "></i><span>Get a sandbox</span></button>

</div>


<div class="fs-4">
</div>
</div>


</div>
</div>

</div>
<div data-role="task912" data-position="104" id="task-num-7">
<div class="panel panel-default task-card " id="task-912">
<span id="user_id" data-id="197885"></span>

<div class="panel-heading panel-heading-actions">
<h3 class="panel-title">
7. The line of life is a ragged diagonal between duty and desire
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
<p>Write a function that prints the sum of the two diagonals of a square matrix of integers.</p>

<ul>
<li>Prototype: <code>void print_diagsums(int *a, int size);</code></li>
<li>Format: see example</li>
<li>You are allowed to use the standard library</li>
</ul>

<p>Note that in the following example we are casting an <code>int[][]</code> into an <code>int*</code>. This is not something you should do. The goal here is to make sure you understand how an array of array is stored in memory.</p>

<pre><code>julien@ubuntu:~/0x07$ cat 8-main.c
#include &quot;main.h&quot;
#include &lt;stdio.h&gt;

/**
* main - check the code
*
* Return: Always 0.
*/
int main(void)
{
int c3[3][3] = {
{0, 1, 5},
{10, 11, 12},
{1000, 101, 102},
};
int c5[5][5] = {
{0, 1, 5, 12124, 1234},
{10, 11, 12, 123521, 12512},
{1000, 101, 102, 12545, 214543435},
{100, 1012451, 11102, 12545, 214543435},
{10, 12401, 10452, 11542545, 1214543435},
};
print_diagsums((int *)c3, 3);
print_diagsums((int *)c5, 5);
return (0);
}
julien@ubuntu:~/0x07$ gcc -Wall -pedantic -Werror -Wextra -std=gnu89 8-main.c 8-print_diagsums.c -o 8-print_diagsums
julien@ubuntu:~/0x07$ ./8-print_diagsums 
113, 1016
1214556093, 1137318
julien@ubuntu:~/0x07$ 
</code></pre>

</div>

<div class="list-group">
<!-- Task URLs -->

<!-- Github information -->
<div class="list-group-item">
<p><strong>Repo:</strong></p>
<ul>
<li>GitHub repository: <code>alx-low_level_programming</code></li>
<li>Directory: <code>0x07-pointers_arrays_strings</code></li>
<li>File: <code>8-print_diagsums.c</code></li>
</ul>
</div>

<!-- Self-paced manual review -->
</div>

<!-- Panel footer - Controls -->
<div class="panel-footer">
<div class="align-items-center d-flex justify-content-between">

<div>
<button class="student_task_done btn btn-default btn-sm no" data-task-id="912">
<span class="no"><i aria-hidden="true" class="fa fa-square-o "></i></span>
<span class="yes"><i aria-hidden="true" class="fa fa-check-square-o "></i></span>
<span class="pending"><i aria-hidden="true" class="fa fa-spinner  fa-pulse"></i></span>
Done<span class="no pending">?</span><span class="yes">!</span>
</button>

<button class="student-task-done-by btn btn-default btn-sm" data-task-id="912" data-batch-id="26" data-toggle="modal" data-target="#task-912-users-done-modal">
Help
</button>
<div class="modal fade users-done-modal" id="task-912-users-done-modal" data-task-id="912" data-batch-id="26">
<div class="modal-dialog">
<div class="modal-content">
<div class="modal-header">
<button type="button" class="close" data-dismiss="modal" aria-label="Close"><span aria-hidden="true">&times;</span></button>
<h4 class="modal-title">Students who are done with "7. The line of life is a ragged diagonal between duty and desire"</h4>
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


<button class="btn btn-default btn-sm check-your-task-912-modal-button" data-task-id="912" data-toggle="modal" data-target="#task-test-correction-912-correction-modal" id="task-num-7-check-code-btn" data-gtm-custom-event-name="task_checker_modal" data-gtm-custom-event-options='{&quot;taskId&quot;:912}'>
Check your code
</button>
<div class="modal fade task_correction_modal student_modal" id="task-test-correction-912-correction-modal">
<div class="modal-dialog">
<div class="modal-content">
<div class="modal-header">
<button type="button" class="close" data-dismiss="modal" aria-label="Close"><span aria-hidden="true">&times;</span></button>
<h4 class="modal-title">Correction of "7. The line of life is a ragged diagonal between duty and desire"</h4>
</div>
<div class="modal-body">
<div class="actions">
<center>
<div class="alert alert-info hidden"></div>

<button name="button" type="submit" class="btn btn-primary correction_request_test_send" data-task-id="912">Start a new test</button>
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
<button data-task-id="912">
<i aria-hidden="true" class="fa fa-info-circle "></i>
</button>
<div class="help-container" data-task-id="912">
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



<button class="btn btn-default btn-sm" data-toggle="modal" data-target="#container-specs-modal" data-gtm-custom-event-name="task_sandbox_modal" data-gtm-custom-event-options="{&quot;taskId&quot;:912}"><i aria-hidden="true" class="fa fa-terminal "></i><span>Get a sandbox</span></button>

</div>


<div class="fs-4">
</div>
</div>


</div>
</div>

</div>

<p class="lg-gap">
<form class="button_to" method="post" action="/projects/218/unlock_optionals"><input id="unlock_optional_btn" class="btn btn-primary btn-block" data-confirm="Are you sure? Make sure you focused on the mandatory tasks first" data-disable-with="Unlocking 2 advanced tasks..." data-gtm-custom-event-name="project_unlock_advanced_tasks" type="submit" value="Done with the mandatory tasks? Unlock 2 advanced tasks now!" /><input type="hidden" name="authenticity_token" value="CLp_ZsK2Qwb3BPqObKAK-rh-kDeCoiwWL7vGWQJyDxcxyEvx6vWhtfSZR9xxKp3eb-ZFDaGByruAjPlHQuNLTw" autocomplete="off" /></form>
</p>




<div class="modal fade" id="container-specs-modal"><div class="modal-dialog modal-lg"><div class="modal-content"><div class="modal-header"><button type="button" class="close" data-dismiss="modal" aria-label="Close"><span aria-hidden="true">&times;</span></button><h4 class="modal-title">Recommended Sandbox</h4></div><div class="modal-body"><div data-react-class="user_containers/ContainerSpecs" data-react-props="{&quot;containerModelName&quot;:&quot;Sandbox&quot;,&quot;containerSpecs&quot;:[{&quot;description&quot;:&quot;\u003cp\u003eBasic Ubuntu 20.04, with vim, emacs, curl, wget and all needed for Foundations\u003c/p\u003e\n&quot;,&quot;id&quot;:39,&quot;name&quot;:&quot;Ubuntu 20.04&quot;,&quot;online&quot;:true,&quot;container&quot;:{&quot;container_id&quot;:null,&quot;id&quot;:239271,&quot;restart_uri&quot;:&quot;/user_containers/239271/restart.json&quot;,&quot;status&quot;:&quot;asleep&quot;,&quot;uri&quot;:&quot;/user_containers/239271.json&quot;,&quot;wake_uri&quot;:&quot;/user_containers/239271/wake.json&quot;,&quot;webterm_uri&quot;:&quot;/user_containers/239271/webterm&quot;,&quot;host&quot;:null,&quot;password&quot;:&quot;2deaf74c415af9350d02&quot;,&quot;ports&quot;:{&quot;4000&quot;:49897,&quot;443&quot;:49900,&quot;8000&quot;:49894,&quot;8080&quot;:49893,&quot;3000&quot;:49899,&quot;3306&quot;:49898,&quot;5001&quot;:49895,&quot;80&quot;:49901,&quot;22&quot;:49902,&quot;5000&quot;:49896}}}],&quot;containersLimit&quot;:2,&quot;csrfToken&quot;:&quot;Noz2GU3Qy4fp_NLk63p5ADPF7DGYkU4zYZyh1WfmTNTS3Ft7FIntYGPhfo01tvJ8jqnyoBCDE6F1mrd4TvnkbQ&quot;,&quot;startStatusURI&quot;:&quot;/user_containers/start_status.json&quot;,&quot;startURI&quot;:&quot;/user_containers/start.json&quot;}" data-react-cache-id="user_containers/ContainerSpecs-0"></div></div></div></div></div>

</div>
</div>


</article>

<div class="copyright">Copyright © 2023 ALX, All rights reserved.</div>

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
