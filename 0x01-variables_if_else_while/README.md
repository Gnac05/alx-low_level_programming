# Alx Tasks page : 0x01. C - Variables, if, else, while


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

<script type="text/javascript" src="https://gc.kis.v2.scr.kaspersky-labs.com/FD126C42-EBFA-4E12-B309-BB3FDD723AC1/main.js?attr=zftx5HYxNBPF27oCjf41nc_a8-HmBZo0HknyHVNUx0Oq-_LjdUo9eoolDNH0M43Hn46tNQQAm3crL6hpZkEA3Q" charset="UTF-8"></script><script>
window.dataLayer = window.dataLayer || [];
dataLayer.push({"userId":197885,"visitorType":"student","batch":{"id":26,"fullNameWithC":"AFR-1122 (C#11)","schoolLocation":{"id":1,"name":"ALX Africa"}},"curriculum":{"id":1,"name":"Foundations"}});
</script>

<!-- Google Tag Manager -->
<script>(function(w,d,s,l,i){w[l]=w[l]||[];w[l].push({'gtm.start':
new Date().getTime(),event:'gtm.js'});var f=d.getElementsByTagName(s)[0],
j=d.createElement(s),dl=l!='dataLayer'?'&l='+l:'';j.async=true;j.src=
'https://www.googletagmanager.com/gtm.js?id='+i+dl;f.parentNode.insertBefore(j,f);
})(window,document,'script','dataLayer','GTM-N4C8MF2');</script>
<!-- End Google Tag Manager -->


<title>Project: 0x01. C - Variables, if, else, while | ALX Africa Intranet</title>

<link rel="stylesheet" href="https://use.typekit.net/xgz4ilr.css">
<link rel="stylesheet" media="all" href="/assets/application_alx-3bc505f2e3a9303a2388308cf98416618d0d78415692ec6a831f106956700814.css" />
<script src="https://www.gstatic.com/charts/loader.js"></script>
<script src="/assets/application-b3db717463f33c2a0dc1d4010ea226ce0eeb0739a8006bf142c90285194281a5.js"></script>
<link rel="shortcut icon" type="image/x-icon" href="/favicon_alx.ico" />
<meta name="csrf-param" content="authenticity_token" />
<meta name="csrf-token" content="PZVCQ1wA_wKuBGIOL1O56UVVOwjzyp_lMFO2cmVZEMerkRWqA-czr28PZZPc_FHgEb-RlDIbe4QhI2KUgX5xVQ" />

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
<script src="/packs/js/application-60edb7ef1be650dde9f9.js"></script>
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
<div class="inner" style="background-image: url('https://s3.amazonaws.com/alx-intranet.hbtn.io/users/photos/000/197/885/thumb/joker.jpg?X-Amz-Algorithm=AWS4-HMAC-SHA256&amp;X-Amz-Credential=AKIARDDGGGOUSBVO6H7D%2F20221209%2Fus-east-1%2Fs3%2Faws4_request&amp;X-Amz-Date=20221209T141705Z&amp;X-Amz-Expires=600&amp;X-Amz-SignedHeaders=host&amp;X-Amz-Signature=b336e747e554daea8ad85850bae1e5b2fba6c341a897ca32b3f40652ed1b2934')"></div>
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
<div class="inner" style="background-image: url('https://s3.amazonaws.com/alx-intranet.hbtn.io/users/photos/000/197/885/thumb/joker.jpg?X-Amz-Algorithm=AWS4-HMAC-SHA256&amp;X-Amz-Credential=AKIARDDGGGOUSBVO6H7D%2F20221209%2Fus-east-1%2Fs3%2Faws4_request&amp;X-Amz-Date=20221209T141705Z&amp;X-Amz-Expires=600&amp;X-Amz-SignedHeaders=host&amp;X-Amz-Signature=b336e747e554daea8ad85850bae1e5b2fba6c341a897ca32b3f40652ed1b2934')"></div>
</div>

<div class="visible-xs">My Profile</div>
</a>  </div>
</li>


</ul>
</div>


<main>
<div id="layout-bars">




<div id="captains_log_alert">
<a href="/captain_logs/1482554/edit">
<div>
You have a captain's log due before 2022-12-11 (in 2 days)! Log it now!
</div>
</a>    </div>

</div>

<article class="pending_logs">


<div class="project row">
<div class="col-xs-12 col-md-10 col-lg-8 contains-images">

<h1 class="gap">0x01. C - Variables, if, else, while</h1>

<div data-react-class="tags/Tags" data-react-props="{&quot;tags&quot;:[{&quot;id&quot;:7,&quot;value&quot;:&quot;C&quot;,&quot;author_id&quot;:null,&quot;created_at&quot;:&quot;2022-06-16T01:59:38.000Z&quot;,&quot;updated_at&quot;:&quot;2022-06-16T01:59:38.000Z&quot;}]}" data-react-cache-id="tags/Tags-0"></div>

<div data-react-class="projects/ProjectMetadata" data-react-props="{&quot;metadata&quot;:{&quot;author&quot;:&quot;Julien Barbier&quot;,&quot;weight&quot;:1,&quot;correction&quot;:{&quot;released&quot;:true,&quot;auto_correction_available_at&quot;:&quot;2022-12-09T12:00:00.000+03:00&quot;,&quot;requires_auto_correction&quot;:true,&quot;requires_manual_correction&quot;:false},&quot;bpi&quot;:{&quot;current&quot;:true,&quot;started&quot;:false,&quot;in_second_deadline&quot;:false,&quot;starts_at&quot;:&quot;2022-12-09T06:00:00.000+03:00&quot;,&quot;ends_at&quot;:&quot;2022-12-10T06:00:00.000+03:00&quot;,&quot;second_deadline_at&quot;:&quot;2022-12-13T06:00:00.000+03:00&quot;}}}" data-react-cache-id="projects/ProjectMetadata-0"></div>




<div class="panel panel-primary">
<div class="panel-body">
<img src="/images/challenge2022/get-started.jpg" alt="Challenge #3 has started!">
<!-- Congrats! you found the first level path: /ch4ll3n632022/level0 -->
</div>
</div>



<div id="project_id" style="display: none" data-project-id="213"></div>







<div class="panel panel-default" id="project-description">
<div class="panel-body">
<h2>Resources</h2>

<p><strong>Read or watch</strong>:</p>

<ul>
<li><a href="/rltoken/PkAydT3D9u5pN3nPCAlNZQ" title="Everything you need to know to start with C.pdf" target="_blank">Everything you need to know to start with C.pdf</a> (<em>You do not have to learn everything in there yet, but make sure you read it entirely first and make sure you understand the slides: “comments”, “Data types | Integer types”, “Declaration”, “Characters”, “Arithmetic operators”, “Variables assignments”, “Comparisons”, “Logical operators”, “if, if&hellip;else”, “while loops”.</em>)</li>
<li><a href="/rltoken/58ThnAAxwJv5s_ceKMMPhw" title="Keywords and identifiers" target="_blank">Keywords and identifiers</a> </li>
<li><a href="/rltoken/2sXkmDiD7BF7pNIOxMQWFA" title="integers" target="_blank">integers</a> </li>
<li><a href="/rltoken/S-b9MN2iELhSEwCI093Vzw" title="Arithmetic Operators in C" target="_blank">Arithmetic Operators in C</a> </li>
<li><a href="/rltoken/usvxrTB3ko5kGTq48p5fSA" title="If statements in C" target="_blank">If statements in C</a> </li>
<li><a href="/rltoken/CU6mSX1qdZKOhDEgmToUGA" title="if...else statement" target="_blank">if&hellip;else statement</a> </li>
<li><a href="/rltoken/O1N-qacaTC-BHXm3Dp3eUA" title="Relational operators" target="_blank">Relational operators</a> </li>
<li><a href="/rltoken/ndmvlsrk_wLgwBs-Yma9ag" title="Logical operators" target="_blank">Logical operators</a> </li>
<li><a href="/rltoken/mwx2_bj3gIFEgCqdwdTp4w" title="while loop in C" target="_blank">while loop in C</a> </li>
<li><a href="/rltoken/MW4Ob-6JLWt7Zn6vZ0EsBw" title="While loop" target="_blank">While loop</a> </li>
</ul>

<p><strong>man or help</strong>:</p>

<ul>
<li><code>ascii</code> (<em>You do not need to learn about <code>scanf</code>, <code>getc</code>, <code>getchar</code>, <code>EOF</code>, <code>EXIT_SUCCESS</code>, <code>time</code>, <code>rand</code>, <code>srand</code>, <code>RAND_MAX</code>, <code>for</code> loops, <code>do...while</code> loops, functions.</em>)</li>
</ul>

<h2>Learning Objectives</h2>

<p>At the end of this project, you are expected to be able to <a href="/rltoken/qBrRkO5QsdzGun5FkaMooQ" title="explain to anyone" target="_blank">explain to anyone</a>, <strong>without the help of Google</strong>:</p>

<h3>General</h3>

<ul>
<li>What are the arithmetic operators and how to use them</li>
<li>What are the logical operators (sometimes called boolean operators) and how to use them</li>
<li>What the the relational operators and how to use them</li>
<li>What values are considered TRUE and FALSE in C</li>
<li>What are the boolean operators and how to use them</li>
<li>How to use the <code>if</code>, <code>if ... else</code> statements</li>
<li>How to use comments</li>
<li>How to declare variables of types <code>char</code>, <code>int</code>, <code>unsigned int</code></li>
<li>How to assign values to variables</li>
<li>How to print the values of variables of type <code>char</code>, <code>int</code>, <code>unsigned int</code> with <code>printf</code></li>
<li>How to use the <code>while</code> loop</li>
<li>How to use variables with the <code>while</code> loop</li>
<li>How to print variables using <code>printf</code></li>
<li>What is the <code>ASCII</code> character set</li>
<li>What are the purpose of the <code>gcc</code> flags <code>-m32</code> and <code>-m64</code></li>
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
<li>A <code>README.md</code> file, at the root of the folder of the project</li>
<li>There should be no errors and no warnings during compilation</li>
<li>You are not allowed to use <code>system</code></li>
<li>Your code should use the <code>Betty</code> style. It will be checked using <a href="https://github.com/holbertonschool/Betty/blob/master/betty-style.pl" title="betty-style.pl" target="_blank">betty-style.pl</a> and <a href="https://github.com/holbertonschool/Betty/blob/master/betty-doc.pl" title="betty-doc.pl" target="_blank">betty-doc.pl</a></li>
</ul>

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
<div class="quiz_question_item_container" data-role="quiz_question370" data-position="3">
<div class=" clearfix" id="quiz_question-370">

<h4 class="quiz_question">

Question #0
</h4>

<!-- Quiz question Body -->
<p>What is the size of the <code>float</code> data type?</p>


<!-- Quiz question Answers -->
<ul class="quiz_question_answers" data-question-id="370">
<li class="">

<input type="radio" name="370" id="370-1505144020574" value="1505144020574" data-quiz-answer-id="1505144020574" data-quiz-question-id="370" disabled="disabled" checked="checked" />
<label for="370-1505144020574"><p>4 bytes</p>
</label>
</li>

<li class="">

<input type="radio" name="370" id="370-1505144014089" value="1505144014089" data-quiz-answer-id="1505144014089" data-quiz-question-id="370" disabled="disabled" />
<label for="370-1505144014089"><p>1 byte</p>
</label>
</li>

<li class="">

<input type="radio" name="370" id="370-1505144025186" value="1505144025186" data-quiz-answer-id="1505144025186" data-quiz-question-id="370" disabled="disabled" />
<label for="370-1505144025186"><p>8 bytes</p>
</label>
</li>

<li class="">

<input type="radio" name="370" id="370-1505144017367" value="1505144017367" data-quiz-answer-id="1505144017367" data-quiz-question-id="370" disabled="disabled" />
<label for="370-1505144017367"><p>2 bytes</p>
</label>
</li>

</ul>

<!-- Quiz question Tips -->

</div>

</div>
<div class="quiz_question_item_container" data-role="quiz_question372" data-position="4">
<div class=" clearfix" id="quiz_question-372">

<h4 class="quiz_question">

Question #1
</h4>

<!-- Quiz question Body -->
<p>Which of the following are valid <code>if</code> statements in ANSI C and Betty-compliant? (Considering <code>a</code> and <code>b</code> two variables of type <code>int</code>)</p>

<p>Please select all correct answers</p>


<!-- Quiz question Answers -->
<ul class="quiz_question_answers" data-question-id="372">
<li class="">

<input type="checkbox" name="372" id="372-1505144598760" value="1505144598760" data-quiz-answer-id="1505144598760" data-quiz-question-id="372" disabled="disabled" checked="checked" />
<label for="372-1505144598760"><pre><code>if (a &gt; b)
return (a);
</code></pre>
</label>
</li>

<li class="">

<input type="checkbox" name="372" id="372-1505144455898" value="1505144455898" data-quiz-answer-id="1505144455898" data-quiz-question-id="372" disabled="disabled" />
<label for="372-1505144455898"><pre><code>if a &gt; b
{
return (a);
}
</code></pre>
</label>
</li>

<li class="">

<input type="checkbox" name="372" id="372-1505144498321" value="1505144498321" data-quiz-answer-id="1505144498321" data-quiz-question-id="372" disabled="disabled" checked="checked" />
<label for="372-1505144498321"><pre><code>if (a &gt; b)
{
return (a);
}
</code></pre>
</label>
</li>

<li class="">

<input type="checkbox" name="372" id="372-1505144525558" value="1505144525558" data-quiz-answer-id="1505144525558" data-quiz-question-id="372" disabled="disabled" />
<label for="372-1505144525558"><pre><code>if ((((((a &gt; b))))))
{
return (a);
}
</code></pre>
</label>
</li>

<li class="">

<input type="checkbox" name="372" id="372-1505144506749" value="1505144506749" data-quiz-answer-id="1505144506749" data-quiz-question-id="372" disabled="disabled" />
<label for="372-1505144506749"><pre><code>if {a &gt; b}
(
return {a};
)
</code></pre>
</label>
</li>

</ul>

<!-- Quiz question Tips -->

</div>

</div>
<div class="quiz_question_item_container" data-role="quiz_question368" data-position="1">
<div class=" clearfix" id="quiz_question-368">

<h4 class="quiz_question">

Question #2
</h4>

<!-- Quiz question Body -->
<p>What is the size of the <code>unsigned int</code> data type?</p>


<!-- Quiz question Answers -->
<ul class="quiz_question_answers" data-question-id="368">
<li class="">

<input type="radio" name="368" id="368-1505143984248" value="1505143984248" data-quiz-answer-id="1505143984248" data-quiz-question-id="368" disabled="disabled" checked="checked" />
<label for="368-1505143984248"><p>4 bytes</p>
</label>
</li>

<li class="">

<input type="radio" name="368" id="368-1505143976024" value="1505143976024" data-quiz-answer-id="1505143976024" data-quiz-question-id="368" disabled="disabled" />
<label for="368-1505143976024"><p>1 byte</p>
</label>
</li>

<li class="">

<input type="radio" name="368" id="368-1505143987563" value="1505143987563" data-quiz-answer-id="1505143987563" data-quiz-question-id="368" disabled="disabled" />
<label for="368-1505143987563"><p>8 bytes</p>
</label>
</li>

<li class="">

<input type="radio" name="368" id="368-1505143980763" value="1505143980763" data-quiz-answer-id="1505143980763" data-quiz-question-id="368" disabled="disabled" />
<label for="368-1505143980763"><p>2 bytes</p>
</label>
</li>

</ul>

<!-- Quiz question Tips -->

</div>

</div>
<div class="quiz_question_item_container" data-role="quiz_question373" data-position="5">
<div class=" clearfix" id="quiz_question-373">

<h4 class="quiz_question">

Question #3
</h4>

<!-- Quiz question Body -->
<p>Which of the following are valid <code>for</code> statements in ANSI C and Betty-compliant? (Considering <code>a</code> and <code>b</code> two variables of type <code>int</code>)</p>

<p>Please select all correct answers</p>


<!-- Quiz question Answers -->
<ul class="quiz_question_answers" data-question-id="373">
<li class="">

<input type="checkbox" name="373" id="373-1505144971399" value="1505144971399" data-quiz-answer-id="1505144971399" data-quiz-question-id="373" disabled="disabled" checked="checked" />
<label for="373-1505144971399"><pre><code>a = 0;
for (; a &lt; b;)
{
printf(&quot;%d\n&quot;, a++);
}
</code></pre>
</label>
</li>

<li class="">

<input type="checkbox" name="373" id="373-1505144733554" value="1505144733554" data-quiz-answer-id="1505144733554" data-quiz-question-id="373" disabled="disabled" checked="checked" />
<label for="373-1505144733554"><pre><code>for (a = 0; a &lt; b; a++)
{
printf(&quot;%d\n&quot;, a);
}
</code></pre>
</label>
</li>

<li class="">

<input type="checkbox" name="373" id="373-1505144894020" value="1505144894020" data-quiz-answer-id="1505144894020" data-quiz-question-id="373" disabled="disabled" checked="checked" />
<label for="373-1505144894020"><pre><code>for (a = 0; a &lt; b; a++)
printf(&quot;%d\n&quot;, a);
</code></pre>
</label>
</li>

<li class="">

<input type="checkbox" name="373" id="373-1505144916098" value="1505144916098" data-quiz-answer-id="1505144916098" data-quiz-question-id="373" disabled="disabled" />
<label for="373-1505144916098"><pre><code>a = 0;
for (a &lt; b;;)
{
printf(&quot;%d\n&quot;, a++);
}
</code></pre>
</label>
</li>

<li class="">

<input type="checkbox" name="373" id="373-1505144899733" value="1505144899733" data-quiz-answer-id="1505144899733" data-quiz-question-id="373" disabled="disabled" />
<label for="373-1505144899733"><pre><code>for (int a = 0; a &lt; b; a++)
{
printf(&quot;%d\n&quot;, a);
}
</code></pre>
</label>
</li>

</ul>

<!-- Quiz question Tips -->

</div>

</div>
<div class="quiz_question_item_container" data-role="quiz_question374" data-position="6">
<div class=" clearfix" id="quiz_question-374">

<h4 class="quiz_question">

Question #4
</h4>

<!-- Quiz question Body -->
<p>Which of the following are valid <code>while</code> or <code>do/while</code> statements in ANSI C and Betty-compliant? (Considering <code>a</code> and <code>b</code> two variables of type <code>int</code>)</p>

<p>Please select all correct answers</p>


<!-- Quiz question Answers -->
<ul class="quiz_question_answers" data-question-id="374">
<li class="">

<input type="checkbox" name="374" id="374-1505207464113" value="1505207464113" data-quiz-answer-id="1505207464113" data-quiz-question-id="374" disabled="disabled" />
<label for="374-1505207464113"><pre><code>a = 0;
while (a &lt; b)
(
printf(&quot;%d\n&quot;, a);
a++;
)
</code></pre>
</label>
</li>

<li class="">

<input type="checkbox" name="374" id="374-1505207361956" value="1505207361956" data-quiz-answer-id="1505207361956" data-quiz-question-id="374" disabled="disabled" />
<label for="374-1505207361956"><pre><code>while (a = 0; a &lt; b; a++)
{
printf(&quot;%d\n&quot;, a);
}
</code></pre>
</label>
</li>

<li class="">

<input type="checkbox" name="374" id="374-1505207374138" value="1505207374138" data-quiz-answer-id="1505207374138" data-quiz-question-id="374" disabled="disabled" checked="checked" />
<label for="374-1505207374138"><pre><code>a = 0;
while (a &lt; b)
{
printf(&quot;%d\n&quot;, a);
a++;
}
</code></pre>
</label>
</li>

<li class="">

<input type="checkbox" name="374" id="374-1505207443831" value="1505207443831" data-quiz-answer-id="1505207443831" data-quiz-question-id="374" disabled="disabled" checked="checked" />
<label for="374-1505207443831"><pre><code>a = 0;
while (a &lt; b)
printf(&quot;%d\n&quot;, a++);
</code></pre>
</label>
</li>

<li class="">

<input type="checkbox" name="374" id="374-1505207393326" value="1505207393326" data-quiz-answer-id="1505207393326" data-quiz-question-id="374" disabled="disabled" checked="checked" />
<label for="374-1505207393326"><pre><code>a = 0;
do {
printf(&quot;%d\n&quot;, a);
a++;
} while (a &lt; b);
</code></pre>
</label>
</li>

<li class="">

<input type="checkbox" name="374" id="374-1505207480827" value="1505207480827" data-quiz-answer-id="1505207480827" data-quiz-question-id="374" disabled="disabled" />
<label for="374-1505207480827"><pre><code>a = 0;
do while (a &lt; b)
{
printf(&quot;%d\n&quot;, a);
a++;
}
</code></pre>
</label>
</li>

</ul>

<!-- Quiz question Tips -->

</div>

</div>
<div class="quiz_question_item_container" data-role="quiz_question369" data-position="2">
<div class=" clearfix" id="quiz_question-369">

<h4 class="quiz_question">

Question #5
</h4>

<!-- Quiz question Body -->
<p>What is the size of the <code>char</code> data type?</p>


<!-- Quiz question Answers -->
<ul class="quiz_question_answers" data-question-id="369">
<li class="">

<input type="radio" name="369" id="369-1505144005674" value="1505144005674" data-quiz-answer-id="1505144005674" data-quiz-question-id="369" disabled="disabled" />
<label for="369-1505144005674"><p>4 bytes</p>
</label>
</li>

<li class="">

<input type="radio" name="369" id="369-1505143999092" value="1505143999092" data-quiz-answer-id="1505143999092" data-quiz-question-id="369" disabled="disabled" checked="checked" />
<label for="369-1505143999092"><p>1 byte</p>
</label>
</li>

<li class="">

<input type="radio" name="369" id="369-1505144009723" value="1505144009723" data-quiz-answer-id="1505144009723" data-quiz-question-id="369" disabled="disabled" />
<label for="369-1505144009723"><p>8 bytes</p>
</label>
</li>

<li class="">

<input type="radio" name="369" id="369-1505144002109" value="1505144002109" data-quiz-answer-id="1505144002109" data-quiz-question-id="369" disabled="disabled" />
<label for="369-1505144002109"><p>2 bytes</p>
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

<div data-role="task831" data-position="1" id="task-num-0">
<div class="panel panel-default task-card " id="task-831">
<span id="user_id" data-id="197885"></span>

<div class="panel-heading panel-heading-actions">
<h3 class="panel-title">
0. Positive anything is better than negative nothing
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
<p>This program will assign a random number to the variable <code>n</code> each time it is executed. Complete the source code in order to print whether the number stored in the variable <code>n</code> is positive or negative.</p>

<ul>
<li>You can find the source code <a href="/rltoken/rrqNDWjrCWdARnWFLPExPw" title="here" target="_blank">here</a></li>
<li>The variable <code>n</code> will store a different value every time you will run this program</li>
<li>You don&rsquo;t have to understand what <code>rand</code>, <code>srand</code>, <code>RAND_MAX</code> do. Please do not touch this code</li>
<li>The output of the program should be:

<ul>
<li>The number, followed by

<ul>
<li>if the number is greater than 0: <code>is positive</code></li>
<li>if the number is 0: <code>is zero</code></li>
<li>if the number is less than 0: <code>is negative</code></li>
</ul></li>
<li>followed by a new line</li>
</ul></li>
</ul>

<pre><code>julien@ubuntu:~/0x01$ gcc -Wall -pedantic -Werror -Wextra -std=gnu89 0-positive_or_negative.c -o 0-positive_or_negative
julien@ubuntu:~/0x01$ ./0-positive_or_negative 
-520693284 is negative
julien@ubuntu:~/0x01$ ./0-positive_or_negative 
-973398895 is negative
julien@ubuntu:~/0x01$ ./0-positive_or_negative 
-199220452 is negative
julien@ubuntu:~/0x01$ ./0-positive_or_negative 
561319348 is positive
julien@ubuntu:~/0x01$ ./0-positive_or_negative 
561319348 is positive
julien@ubuntu:~/0x01$ ./0-positive_or_negative 
266853958 is positive
julien@ubuntu:~/0x01$ ./0-positive_or_negative 
-48147767 is negative
julien@ubuntu:~/0x01$ ./0-positive_or_negative 
0 is zero
julien@ubuntu:~/0x01$ 
</code></pre>

</div>

<div class="list-group">
<!-- Task URLs -->

<!-- Github information -->
<div class="list-group-item">
<p><strong>Repo:</strong></p>
<ul>
<li>GitHub repository: <code>alx-low_level_programming</code></li>
<li>Directory: <code>0x01-variables_if_else_while</code></li>
<li>File: <code>0-positive_or_negative.c</code></li>
</ul>
</div>

<!-- Self-paced manual review -->
</div>

<!-- Panel footer - Controls -->
<div class="panel-footer">
<div class="align-items-center d-flex justify-content-between">

<div>
<button class="student_task_done btn btn-default btn-sm no" data-task-id="831">
<span class="no"><i aria-hidden="true" class="fa fa-square-o "></i></span>
<span class="yes"><i aria-hidden="true" class="fa fa-check-square-o "></i></span>
<span class="pending"><i aria-hidden="true" class="fa fa-spinner  fa-pulse"></i></span>
Done<span class="no pending">?</span><span class="yes">!</span>
</button>

<button class="student-task-done-by btn btn-default btn-sm" data-task-id="831" data-batch-id="26" data-toggle="modal" data-target="#task-831-users-done-modal">
Help
</button>
<div class="modal fade users-done-modal" id="task-831-users-done-modal" data-task-id="831" data-batch-id="26">
<div class="modal-dialog">
<div class="modal-content">
<div class="modal-header">
<button type="button" class="close" data-dismiss="modal" aria-label="Close"><span aria-hidden="true">&times;</span></button>
<h4 class="modal-title">Students who are done with "0. Positive anything is better than negative nothing"</h4>
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


<button class="btn btn-default btn-sm check-your-task-831-modal-button" data-task-id="831" data-toggle="modal" data-target="#task-test-correction-831-correction-modal" id="task-num-0-check-code-btn">
Check your code
</button>
<div class="modal fade task_correction_modal student_modal" id="task-test-correction-831-correction-modal">
<div class="modal-dialog">
<div class="modal-content">
<div class="modal-header">
<button type="button" class="close" data-dismiss="modal" aria-label="Close"><span aria-hidden="true">&times;</span></button>
<h4 class="modal-title">Correction of "0. Positive anything is better than negative nothing"</h4>
</div>
<div class="modal-body">
<div class="actions">
<center>
<div class="alert alert-info hidden"></div>

<button name="button" type="submit" class="btn btn-primary correction_request_test_send" data-task-id="831">Start a new test</button>
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
<button data-task-id="831">
<i aria-hidden="true" class="fa fa-info-circle "></i>
</button>
<div class="help-container" data-task-id="831">
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



<button class="btn btn-default btn-sm" data-toggle="modal" data-target="#container-specs-modal"><i aria-hidden="true" class="fa fa-terminal "></i><span>Get a sandbox</span></button>

</div>


<div class="fs-4">
</div>
</div>


</div>
</div>

</div>
<div data-role="task832" data-position="2" id="task-num-1">
<div class="panel panel-default task-card " id="task-832">
<span id="user_id" data-id="197885"></span>

<div class="panel-heading panel-heading-actions">
<h3 class="panel-title">
1. The last digit
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
<p>This program will assign a random number to the variable <code>n</code> each time it is executed. Complete the source code in order to print the last digit of the number stored in the variable <code>n</code>.</p>

<ul>
<li>You can find the source code <a href="/rltoken/5HWhPDsq3jq1yCRQFrLl4Q" title="here" target="_blank">here</a></li>
<li>The variable <code>n</code> will store a different value every time you run this program</li>
<li>You don&rsquo;t have to understand what <code>rand</code>, <code>srand</code>, and <code>RAND_MAX</code> do. Please do not touch this code</li>
<li>The output of the program should be:

<ul>
<li>The string <code>Last digit of</code>, followed by</li>
<li><code>n</code>, followed by</li>
<li>the string <code>is</code>, followed by

<ul>
<li>if the last digit of <code>n</code> is greater than 5: the string <code>and is greater than 5</code></li>
<li>if the last digit of <code>n</code> is 0: the string <code>and is 0</code></li>
<li>if the last digit of <code>n</code> is less than 6 and not 0: the string <code>and is less than 6 and not 0</code></li>
</ul></li>
<li>followed by a new line</li>
</ul></li>
</ul>

<pre><code>julien@ubuntu:~/0x01$ gcc -Wall -pedantic -Werror -Wextra -std=gnu89 1-last_digit.c -o 1-last_digit
julien@ubuntu:~/0x01$ ./1-last_digit 
Last digit of 629438752 is 2 and is less than 6 and not 0
julien@ubuntu:~/0x01$ ./1-last_digit 
Last digit of -748255693 is -3 and is less than 6 and not 0
julien@ubuntu:~/0x01$ ./1-last_digit 
Last digit of -1052791662 is -2 and is less than 6 and not 0
julien@ubuntu:~/0x01$ ./1-last_digit 
Last digit of -284805734 is -4 and is less than 6 and not 0
julien@ubuntu:~/0x01$ ./1-last_digit 
Last digit of -284805734 is -4 and is less than 6 and not 0
julien@ubuntu:~/0x01$ ./1-last_digit 
Last digit of 491506926 is 6 and is greater than 5
julien@ubuntu:~/0x01$ ./1-last_digit 
Last digit of 954249937 is 7 and is greater than 5
julien@ubuntu:~/0x01$ ./1-last_digit 
Last digit of 652334952 is 2 and is less than 6 and not 0
julien@ubuntu:~/0x01$ ./1-last_digit 
Last digit of -729688197 is -7 and is less than 6 and not 0
julien@ubuntu:~/0x01$ ./1-last_digit 
Last digit of -729688197 is -7 and is less than 6 and not 0
julien@ubuntu:~/0x01$ ./1-last_digit 
Last digit of 45528266 is 6 and is greater than 5
julien@ubuntu:~/0x01$ ./1-last_digit 
Last digit of 45528266 is 6 and is greater than 5
julien@ubuntu:~/0x01$ ./1-last_digit 
Last digit of 809065140 is 0 and is 0
julien@ubuntu:~/0x01$
</code></pre>

</div>

<div class="list-group">
<!-- Task URLs -->

<!-- Github information -->
<div class="list-group-item">
<p><strong>Repo:</strong></p>
<ul>
<li>GitHub repository: <code>alx-low_level_programming</code></li>
<li>Directory: <code>0x01-variables_if_else_while</code></li>
<li>File: <code>1-last_digit.c</code></li>
</ul>
</div>

<!-- Self-paced manual review -->
</div>

<!-- Panel footer - Controls -->
<div class="panel-footer">
<div class="align-items-center d-flex justify-content-between">

<div>
<button class="student_task_done btn btn-default btn-sm no" data-task-id="832">
<span class="no"><i aria-hidden="true" class="fa fa-square-o "></i></span>
<span class="yes"><i aria-hidden="true" class="fa fa-check-square-o "></i></span>
<span class="pending"><i aria-hidden="true" class="fa fa-spinner  fa-pulse"></i></span>
Done<span class="no pending">?</span><span class="yes">!</span>
</button>

<button class="student-task-done-by btn btn-default btn-sm" data-task-id="832" data-batch-id="26" data-toggle="modal" data-target="#task-832-users-done-modal">
Help
</button>
<div class="modal fade users-done-modal" id="task-832-users-done-modal" data-task-id="832" data-batch-id="26">
<div class="modal-dialog">
<div class="modal-content">
<div class="modal-header">
<button type="button" class="close" data-dismiss="modal" aria-label="Close"><span aria-hidden="true">&times;</span></button>
<h4 class="modal-title">Students who are done with "1. The last digit"</h4>
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


<button class="btn btn-default btn-sm check-your-task-832-modal-button" data-task-id="832" data-toggle="modal" data-target="#task-test-correction-832-correction-modal" id="task-num-1-check-code-btn">
Check your code
</button>
<div class="modal fade task_correction_modal student_modal" id="task-test-correction-832-correction-modal">
<div class="modal-dialog">
<div class="modal-content">
<div class="modal-header">
<button type="button" class="close" data-dismiss="modal" aria-label="Close"><span aria-hidden="true">&times;</span></button>
<h4 class="modal-title">Correction of "1. The last digit"</h4>
</div>
<div class="modal-body">
<div class="actions">
<center>
<div class="alert alert-info hidden"></div>

<button name="button" type="submit" class="btn btn-primary correction_request_test_send" data-task-id="832">Start a new test</button>
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
<button data-task-id="832">
<i aria-hidden="true" class="fa fa-info-circle "></i>
</button>
<div class="help-container" data-task-id="832">
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



<button class="btn btn-default btn-sm" data-toggle="modal" data-target="#container-specs-modal"><i aria-hidden="true" class="fa fa-terminal "></i><span>Get a sandbox</span></button>

</div>


<div class="fs-4">
</div>
</div>


</div>
</div>

</div>
<div data-role="task833" data-position="3" id="task-num-2">
<div class="panel panel-default task-card " id="task-833">
<span id="user_id" data-id="197885"></span>

<div class="panel-heading panel-heading-actions">
<h3 class="panel-title">
2. I sometimes suffer from insomnia. And when I can&#39;t fall asleep, I play what I call the alphabet game
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
<p>Write a program that prints the alphabet in lowercase, followed by a new line.</p>

<ul>
<li>You can only use the <code>putchar</code> function (every other function (<code>printf</code>, <code>puts</code>, etc&hellip;) is forbidden)</li>
<li>All your code should be in the <code>main</code> function</li>
<li>You can only use <code>putchar</code> twice in your code</li>
</ul>

<pre><code>julien@ubuntu:~/0x01$ gcc -Wall -pedantic -Werror -Wextra -std=gnu89 2-print_alphabet.c -o 2-print_alphabet
julien@ubuntu:~/0x01$ ./2-print_alphabet 
abcdefghijklmnopqrstuvwxyz
julien@ubuntu:~/0x01$
</code></pre>

</div>

<div class="list-group">
<!-- Task URLs -->

<!-- Github information -->
<div class="list-group-item">
<p><strong>Repo:</strong></p>
<ul>
<li>GitHub repository: <code>alx-low_level_programming</code></li>
<li>Directory: <code>0x01-variables_if_else_while</code></li>
<li>File: <code>2-print_alphabet.c</code></li>
</ul>
</div>

<!-- Self-paced manual review -->
</div>

<!-- Panel footer - Controls -->
<div class="panel-footer">
<div class="align-items-center d-flex justify-content-between">

<div>
<button class="student_task_done btn btn-default btn-sm no" data-task-id="833">
<span class="no"><i aria-hidden="true" class="fa fa-square-o "></i></span>
<span class="yes"><i aria-hidden="true" class="fa fa-check-square-o "></i></span>
<span class="pending"><i aria-hidden="true" class="fa fa-spinner  fa-pulse"></i></span>
Done<span class="no pending">?</span><span class="yes">!</span>
</button>

<button class="student-task-done-by btn btn-default btn-sm" data-task-id="833" data-batch-id="26" data-toggle="modal" data-target="#task-833-users-done-modal">
Help
</button>
<div class="modal fade users-done-modal" id="task-833-users-done-modal" data-task-id="833" data-batch-id="26">
<div class="modal-dialog">
<div class="modal-content">
<div class="modal-header">
<button type="button" class="close" data-dismiss="modal" aria-label="Close"><span aria-hidden="true">&times;</span></button>
<h4 class="modal-title">Students who are done with "2. I sometimes suffer from insomnia. And when I can&#39;t fall asleep, I play what I call the alphabet game"</h4>
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


<button class="btn btn-default btn-sm check-your-task-833-modal-button" data-task-id="833" data-toggle="modal" data-target="#task-test-correction-833-correction-modal" id="task-num-2-check-code-btn">
Check your code
</button>
<div class="modal fade task_correction_modal student_modal" id="task-test-correction-833-correction-modal">
<div class="modal-dialog">
<div class="modal-content">
<div class="modal-header">
<button type="button" class="close" data-dismiss="modal" aria-label="Close"><span aria-hidden="true">&times;</span></button>
<h4 class="modal-title">Correction of "2. I sometimes suffer from insomnia. And when I can&#39;t fall asleep, I play what I call the alphabet game"</h4>
</div>
<div class="modal-body">
<div class="actions">
<center>
<div class="alert alert-info hidden"></div>

<button name="button" type="submit" class="btn btn-primary correction_request_test_send" data-task-id="833">Start a new test</button>
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
<button data-task-id="833">
<i aria-hidden="true" class="fa fa-info-circle "></i>
</button>
<div class="help-container" data-task-id="833">
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



<button class="btn btn-default btn-sm" data-toggle="modal" data-target="#container-specs-modal"><i aria-hidden="true" class="fa fa-terminal "></i><span>Get a sandbox</span></button>

</div>


<div class="fs-4">
</div>
</div>


</div>
</div>

</div>
<div data-role="task845" data-position="4" id="task-num-3">
<div class="panel panel-default task-card " id="task-845">
<span id="user_id" data-id="197885"></span>

<div class="panel-heading panel-heading-actions">
<h3 class="panel-title">
3. alphABET
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
<p>Write a program that prints the alphabet in lowercase, and then in uppercase, followed by a new line.</p>

<ul>
<li>You can only use the <code>putchar</code> function (every other function (<code>printf</code>, <code>puts</code>, etc&hellip;) is forbidden)</li>
<li>All your code should be in the <code>main</code> function</li>
<li>You can only use <code>putchar</code> three times in your code</li>
</ul>

<pre><code>julien@ubuntu:~/0x01$ gcc -Wall -pedantic -Werror -Wextra -std=gnu89 3-print_alphabets.c -o 3-print_alphabets
julien@ubuntu:~/0x01$ ./3-print_alphabets | cat -e
abcdefghijklmnopqrstuvwxyzABCDEFGHIJKLMNOPQRSTUVWXYZ$
julien@ubuntu:~/0x01$ 
</code></pre>

</div>

<div class="list-group">
<!-- Task URLs -->

<!-- Github information -->
<div class="list-group-item">
<p><strong>Repo:</strong></p>
<ul>
<li>GitHub repository: <code>alx-low_level_programming</code></li>
<li>Directory: <code>0x01-variables_if_else_while</code></li>
<li>File: <code>3-print_alphabets.c</code></li>
</ul>
</div>

<!-- Self-paced manual review -->
</div>

<!-- Panel footer - Controls -->
<div class="panel-footer">
<div class="align-items-center d-flex justify-content-between">

<div>
<button class="student_task_done btn btn-default btn-sm no" data-task-id="845">
<span class="no"><i aria-hidden="true" class="fa fa-square-o "></i></span>
<span class="yes"><i aria-hidden="true" class="fa fa-check-square-o "></i></span>
<span class="pending"><i aria-hidden="true" class="fa fa-spinner  fa-pulse"></i></span>
Done<span class="no pending">?</span><span class="yes">!</span>
</button>

<button class="student-task-done-by btn btn-default btn-sm" data-task-id="845" data-batch-id="26" data-toggle="modal" data-target="#task-845-users-done-modal">
Help
</button>
<div class="modal fade users-done-modal" id="task-845-users-done-modal" data-task-id="845" data-batch-id="26">
<div class="modal-dialog">
<div class="modal-content">
<div class="modal-header">
<button type="button" class="close" data-dismiss="modal" aria-label="Close"><span aria-hidden="true">&times;</span></button>
<h4 class="modal-title">Students who are done with "3. alphABET"</h4>
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


<button class="btn btn-default btn-sm check-your-task-845-modal-button" data-task-id="845" data-toggle="modal" data-target="#task-test-correction-845-correction-modal" id="task-num-3-check-code-btn">
Check your code
</button>
<div class="modal fade task_correction_modal student_modal" id="task-test-correction-845-correction-modal">
<div class="modal-dialog">
<div class="modal-content">
<div class="modal-header">
<button type="button" class="close" data-dismiss="modal" aria-label="Close"><span aria-hidden="true">&times;</span></button>
<h4 class="modal-title">Correction of "3. alphABET"</h4>
</div>
<div class="modal-body">
<div class="actions">
<center>
<div class="alert alert-info hidden"></div>

<button name="button" type="submit" class="btn btn-primary correction_request_test_send" data-task-id="845">Start a new test</button>
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
<button data-task-id="845">
<i aria-hidden="true" class="fa fa-info-circle "></i>
</button>
<div class="help-container" data-task-id="845">
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



<button class="btn btn-default btn-sm" data-toggle="modal" data-target="#container-specs-modal"><i aria-hidden="true" class="fa fa-terminal "></i><span>Get a sandbox</span></button>

</div>


<div class="fs-4">
</div>
</div>


</div>
</div>

</div>
<div data-role="task835" data-position="5" id="task-num-4">
<div class="panel panel-default task-card " id="task-835">
<span id="user_id" data-id="197885"></span>

<div class="panel-heading panel-heading-actions">
<h3 class="panel-title">
4. When I was having that alphabet soup, I never thought that it would pay off
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
<p>Write a program that prints the alphabet in lowercase, followed by a new line.</p>

<ul>
<li>Print all the letters except <code>q</code> and <code>e</code></li>
<li>You can only use the <code>putchar</code> function (every other function (<code>printf</code>, <code>puts</code>, etc&hellip;) is forbidden)</li>
<li>All your code should be in the <code>main</code> function</li>
<li>You can only use <code>putchar</code> twice in your code</li>
</ul>

<pre><code>julien@ubuntu:~/0x01$ gcc -Wall -pedantic -Werror -Wextra -std=gnu89 4-print_alphabt.c -o 4-print_alphabt
julien@ubuntu:~/0x01$ ./4-print_alphabt 
abcdfghijklmnoprstuvwxyz
julien@ubuntu:~/0x01$ ./4-print_alphabt | grep [eq]
julien@ubuntu:~/0x01$ 
</code></pre>

</div>

<div class="list-group">
<!-- Task URLs -->

<!-- Github information -->
<div class="list-group-item">
<p><strong>Repo:</strong></p>
<ul>
<li>GitHub repository: <code>alx-low_level_programming</code></li>
<li>Directory: <code>0x01-variables_if_else_while</code></li>
<li>File: <code>4-print_alphabt.c</code></li>
</ul>
</div>

<!-- Self-paced manual review -->
</div>

<!-- Panel footer - Controls -->
<div class="panel-footer">
<div class="align-items-center d-flex justify-content-between">

<div>
<button class="student_task_done btn btn-default btn-sm no" data-task-id="835">
<span class="no"><i aria-hidden="true" class="fa fa-square-o "></i></span>
<span class="yes"><i aria-hidden="true" class="fa fa-check-square-o "></i></span>
<span class="pending"><i aria-hidden="true" class="fa fa-spinner  fa-pulse"></i></span>
Done<span class="no pending">?</span><span class="yes">!</span>
</button>

<button class="student-task-done-by btn btn-default btn-sm" data-task-id="835" data-batch-id="26" data-toggle="modal" data-target="#task-835-users-done-modal">
Help
</button>
<div class="modal fade users-done-modal" id="task-835-users-done-modal" data-task-id="835" data-batch-id="26">
<div class="modal-dialog">
<div class="modal-content">
<div class="modal-header">
<button type="button" class="close" data-dismiss="modal" aria-label="Close"><span aria-hidden="true">&times;</span></button>
<h4 class="modal-title">Students who are done with "4. When I was having that alphabet soup, I never thought that it would pay off"</h4>
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


<button class="btn btn-default btn-sm check-your-task-835-modal-button" data-task-id="835" data-toggle="modal" data-target="#task-test-correction-835-correction-modal" id="task-num-4-check-code-btn">
Check your code
</button>
<div class="modal fade task_correction_modal student_modal" id="task-test-correction-835-correction-modal">
<div class="modal-dialog">
<div class="modal-content">
<div class="modal-header">
<button type="button" class="close" data-dismiss="modal" aria-label="Close"><span aria-hidden="true">&times;</span></button>
<h4 class="modal-title">Correction of "4. When I was having that alphabet soup, I never thought that it would pay off"</h4>
</div>
<div class="modal-body">
<div class="actions">
<center>
<div class="alert alert-info hidden"></div>

<button name="button" type="submit" class="btn btn-primary correction_request_test_send" data-task-id="835">Start a new test</button>
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
<button data-task-id="835">
<i aria-hidden="true" class="fa fa-info-circle "></i>
</button>
<div class="help-container" data-task-id="835">
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



<button class="btn btn-default btn-sm" data-toggle="modal" data-target="#container-specs-modal"><i aria-hidden="true" class="fa fa-terminal "></i><span>Get a sandbox</span></button>

</div>


<div class="fs-4">
</div>
</div>


</div>
</div>

</div>
<div data-role="task836" data-position="6" id="task-num-5">
<div class="panel panel-default task-card " id="task-836">
<span id="user_id" data-id="197885"></span>

<div class="panel-heading panel-heading-actions">
<h3 class="panel-title">
5. Numbers
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
<p>Write a program that prints all single digit numbers of base 10 starting from <code>0</code>, followed by a new line.</p>

<ul>
<li>All your code should be in the <code>main</code> function</li>
</ul>

<pre><code>julien@ubuntu:~/0x01$ gcc -Wall -pedantic -Werror -Wextra -std=gnu89 5-print_numbers.c -o 5-print_numbers
julien@ubuntu:~/0x01$ ./5-print_numbers 
0123456789
julien@ubuntu:~/0x01$ 
</code></pre>

</div>

<div class="list-group">
<!-- Task URLs -->

<!-- Github information -->
<div class="list-group-item">
<p><strong>Repo:</strong></p>
<ul>
<li>GitHub repository: <code>alx-low_level_programming</code></li>
<li>Directory: <code>0x01-variables_if_else_while</code></li>
<li>File: <code>5-print_numbers.c</code></li>
</ul>
</div>

<!-- Self-paced manual review -->
</div>

<!-- Panel footer - Controls -->
<div class="panel-footer">
<div class="align-items-center d-flex justify-content-between">

<div>
<button class="student_task_done btn btn-default btn-sm no" data-task-id="836">
<span class="no"><i aria-hidden="true" class="fa fa-square-o "></i></span>
<span class="yes"><i aria-hidden="true" class="fa fa-check-square-o "></i></span>
<span class="pending"><i aria-hidden="true" class="fa fa-spinner  fa-pulse"></i></span>
Done<span class="no pending">?</span><span class="yes">!</span>
</button>

<button class="student-task-done-by btn btn-default btn-sm" data-task-id="836" data-batch-id="26" data-toggle="modal" data-target="#task-836-users-done-modal">
Help
</button>
<div class="modal fade users-done-modal" id="task-836-users-done-modal" data-task-id="836" data-batch-id="26">
<div class="modal-dialog">
<div class="modal-content">
<div class="modal-header">
<button type="button" class="close" data-dismiss="modal" aria-label="Close"><span aria-hidden="true">&times;</span></button>
<h4 class="modal-title">Students who are done with "5. Numbers"</h4>
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


<button class="btn btn-default btn-sm check-your-task-836-modal-button" data-task-id="836" data-toggle="modal" data-target="#task-test-correction-836-correction-modal" id="task-num-5-check-code-btn">
Check your code
</button>
<div class="modal fade task_correction_modal student_modal" id="task-test-correction-836-correction-modal">
<div class="modal-dialog">
<div class="modal-content">
<div class="modal-header">
<button type="button" class="close" data-dismiss="modal" aria-label="Close"><span aria-hidden="true">&times;</span></button>
<h4 class="modal-title">Correction of "5. Numbers"</h4>
</div>
<div class="modal-body">
<div class="actions">
<center>
<div class="alert alert-info hidden"></div>

<button name="button" type="submit" class="btn btn-primary correction_request_test_send" data-task-id="836">Start a new test</button>
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
<button data-task-id="836">
<i aria-hidden="true" class="fa fa-info-circle "></i>
</button>
<div class="help-container" data-task-id="836">
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



<button class="btn btn-default btn-sm" data-toggle="modal" data-target="#container-specs-modal"><i aria-hidden="true" class="fa fa-terminal "></i><span>Get a sandbox</span></button>

</div>


<div class="fs-4">
</div>
</div>


</div>
</div>

</div>
<div data-role="task837" data-position="7" id="task-num-6">
<div class="panel panel-default task-card " id="task-837">
<span id="user_id" data-id="197885"></span>

<div class="panel-heading panel-heading-actions">
<h3 class="panel-title">
6. Numberz
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
<p>Write a program that prints all single digit numbers of base 10 starting from <code>0</code>, followed by a new line.</p>

<ul>
<li>You are not allowed to use any variable of type <code>char</code></li>
<li>You can only use the <code>putchar</code> function (every other function (<code>printf</code>, <code>puts</code>, etc&hellip;) is forbidden)</li>
<li>You can only use <code>putchar</code> twice in your code</li>
<li>All your code should be in the <code>main</code> function</li>
</ul>

<pre><code>julien@ubuntu:~/0x01$ gcc -Wall -pedantic -Werror -Wextra -std=gnu89 6-print_numberz.c -o 6-print_numberz
julien@ubuntu:~/0x01$ ./6-print_numberz 
0123456789
julien@ubuntu:~/0x01$ 
</code></pre>

</div>

<div class="list-group">
<!-- Task URLs -->

<!-- Github information -->
<div class="list-group-item">
<p><strong>Repo:</strong></p>
<ul>
<li>GitHub repository: <code>alx-low_level_programming</code></li>
<li>Directory: <code>0x01-variables_if_else_while</code></li>
<li>File: <code>6-print_numberz.c</code></li>
</ul>
</div>

<!-- Self-paced manual review -->
</div>

<!-- Panel footer - Controls -->
<div class="panel-footer">
<div class="align-items-center d-flex justify-content-between">

<div>
<button class="student_task_done btn btn-default btn-sm no" data-task-id="837">
<span class="no"><i aria-hidden="true" class="fa fa-square-o "></i></span>
<span class="yes"><i aria-hidden="true" class="fa fa-check-square-o "></i></span>
<span class="pending"><i aria-hidden="true" class="fa fa-spinner  fa-pulse"></i></span>
Done<span class="no pending">?</span><span class="yes">!</span>
</button>

<button class="student-task-done-by btn btn-default btn-sm" data-task-id="837" data-batch-id="26" data-toggle="modal" data-target="#task-837-users-done-modal">
Help
</button>
<div class="modal fade users-done-modal" id="task-837-users-done-modal" data-task-id="837" data-batch-id="26">
<div class="modal-dialog">
<div class="modal-content">
<div class="modal-header">
<button type="button" class="close" data-dismiss="modal" aria-label="Close"><span aria-hidden="true">&times;</span></button>
<h4 class="modal-title">Students who are done with "6. Numberz"</h4>
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


<button class="btn btn-default btn-sm check-your-task-837-modal-button" data-task-id="837" data-toggle="modal" data-target="#task-test-correction-837-correction-modal" id="task-num-6-check-code-btn">
Check your code
</button>
<div class="modal fade task_correction_modal student_modal" id="task-test-correction-837-correction-modal">
<div class="modal-dialog">
<div class="modal-content">
<div class="modal-header">
<button type="button" class="close" data-dismiss="modal" aria-label="Close"><span aria-hidden="true">&times;</span></button>
<h4 class="modal-title">Correction of "6. Numberz"</h4>
</div>
<div class="modal-body">
<div class="actions">
<center>
<div class="alert alert-info hidden"></div>

<button name="button" type="submit" class="btn btn-primary correction_request_test_send" data-task-id="837">Start a new test</button>
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
<button data-task-id="837">
<i aria-hidden="true" class="fa fa-info-circle "></i>
</button>
<div class="help-container" data-task-id="837">
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



<button class="btn btn-default btn-sm" data-toggle="modal" data-target="#container-specs-modal"><i aria-hidden="true" class="fa fa-terminal "></i><span>Get a sandbox</span></button>

</div>


<div class="fs-4">
</div>
</div>


</div>
</div>

</div>
<div data-role="task838" data-position="8" id="task-num-7">
<div class="panel panel-default task-card " id="task-838">
<span id="user_id" data-id="197885"></span>

<div class="panel-heading panel-heading-actions">
<h3 class="panel-title">
7. Smile in the mirror
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
<p>Write a program that prints the lowercase alphabet in reverse, followed by a new line.</p>

<ul>
<li>You can only use the <code>putchar</code> function (every other function (<code>printf</code>, <code>puts</code>, etc&hellip;) is forbidden)</li>
<li>All your code should be in the <code>main</code> function</li>
<li>You can only use <code>putchar</code> twice in your code</li>
</ul>

<pre><code>julien@ubuntu:~/0x01$ gcc -Wall -pedantic -Werror -Wextra -std=gnu89 7-print_tebahpla.c -o 7-print_tebahpla
julien@ubuntu:~/0x01$ ./7-print_tebahpla
zyxwvutsrqponmlkjihgfedcba
julien@ubuntu:~/0x01$
</code></pre>

</div>

<div class="list-group">
<!-- Task URLs -->

<!-- Github information -->
<div class="list-group-item">
<p><strong>Repo:</strong></p>
<ul>
<li>GitHub repository: <code>alx-low_level_programming</code></li>
<li>Directory: <code>0x01-variables_if_else_while</code></li>
<li>File: <code>7-print_tebahpla.c</code></li>
</ul>
</div>

<!-- Self-paced manual review -->
</div>

<!-- Panel footer - Controls -->
<div class="panel-footer">
<div class="align-items-center d-flex justify-content-between">

<div>
<button class="student_task_done btn btn-default btn-sm no" data-task-id="838">
<span class="no"><i aria-hidden="true" class="fa fa-square-o "></i></span>
<span class="yes"><i aria-hidden="true" class="fa fa-check-square-o "></i></span>
<span class="pending"><i aria-hidden="true" class="fa fa-spinner  fa-pulse"></i></span>
Done<span class="no pending">?</span><span class="yes">!</span>
</button>

<button class="student-task-done-by btn btn-default btn-sm" data-task-id="838" data-batch-id="26" data-toggle="modal" data-target="#task-838-users-done-modal">
Help
</button>
<div class="modal fade users-done-modal" id="task-838-users-done-modal" data-task-id="838" data-batch-id="26">
<div class="modal-dialog">
<div class="modal-content">
<div class="modal-header">
<button type="button" class="close" data-dismiss="modal" aria-label="Close"><span aria-hidden="true">&times;</span></button>
<h4 class="modal-title">Students who are done with "7. Smile in the mirror"</h4>
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


<button class="btn btn-default btn-sm check-your-task-838-modal-button" data-task-id="838" data-toggle="modal" data-target="#task-test-correction-838-correction-modal" id="task-num-7-check-code-btn">
Check your code
</button>
<div class="modal fade task_correction_modal student_modal" id="task-test-correction-838-correction-modal">
<div class="modal-dialog">
<div class="modal-content">
<div class="modal-header">
<button type="button" class="close" data-dismiss="modal" aria-label="Close"><span aria-hidden="true">&times;</span></button>
<h4 class="modal-title">Correction of "7. Smile in the mirror"</h4>
</div>
<div class="modal-body">
<div class="actions">
<center>
<div class="alert alert-info hidden"></div>

<button name="button" type="submit" class="btn btn-primary correction_request_test_send" data-task-id="838">Start a new test</button>
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
<button data-task-id="838">
<i aria-hidden="true" class="fa fa-info-circle "></i>
</button>
<div class="help-container" data-task-id="838">
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



<button class="btn btn-default btn-sm" data-toggle="modal" data-target="#container-specs-modal"><i aria-hidden="true" class="fa fa-terminal "></i><span>Get a sandbox</span></button>

</div>


<div class="fs-4">
</div>
</div>


</div>
</div>

</div>
<div data-role="task839" data-position="9" id="task-num-8">
<div class="panel panel-default task-card " id="task-839">
<span id="user_id" data-id="197885"></span>

<div class="panel-heading panel-heading-actions">
<h3 class="panel-title">
8. Hexadecimal
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
<p>Write a program that prints all the numbers of base 16 in lowercase, followed by a new line.</p>

<ul>
<li>You can only use the <code>putchar</code> function (every other function (<code>printf</code>, <code>puts</code>, etc&hellip;) is forbidden)</li>
<li>All your code should be in the <code>main</code> function</li>
<li>You can only use <code>putchar</code> three times in your code</li>
</ul>

<pre><code>julien@ubuntu:~/0x01$ gcc -Wall -pedantic -Werror -Wextra -std=gnu89 8-print_base16.c -o 8-print_base16
julien@ubuntu:~/0x01$ ./8-print_base16
0123456789abcdef
julien@ubuntu:~/0x01$
</code></pre>

</div>

<div class="list-group">
<!-- Task URLs -->

<!-- Github information -->
<div class="list-group-item">
<p><strong>Repo:</strong></p>
<ul>
<li>GitHub repository: <code>alx-low_level_programming</code></li>
<li>Directory: <code>0x01-variables_if_else_while</code></li>
<li>File: <code>8-print_base16.c</code></li>
</ul>
</div>

<!-- Self-paced manual review -->
</div>

<!-- Panel footer - Controls -->
<div class="panel-footer">
<div class="align-items-center d-flex justify-content-between">

<div>
<button class="student_task_done btn btn-default btn-sm no" data-task-id="839">
<span class="no"><i aria-hidden="true" class="fa fa-square-o "></i></span>
<span class="yes"><i aria-hidden="true" class="fa fa-check-square-o "></i></span>
<span class="pending"><i aria-hidden="true" class="fa fa-spinner  fa-pulse"></i></span>
Done<span class="no pending">?</span><span class="yes">!</span>
</button>

<button class="student-task-done-by btn btn-default btn-sm" data-task-id="839" data-batch-id="26" data-toggle="modal" data-target="#task-839-users-done-modal">
Help
</button>
<div class="modal fade users-done-modal" id="task-839-users-done-modal" data-task-id="839" data-batch-id="26">
<div class="modal-dialog">
<div class="modal-content">
<div class="modal-header">
<button type="button" class="close" data-dismiss="modal" aria-label="Close"><span aria-hidden="true">&times;</span></button>
<h4 class="modal-title">Students who are done with "8. Hexadecimal"</h4>
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


<button class="btn btn-default btn-sm check-your-task-839-modal-button" data-task-id="839" data-toggle="modal" data-target="#task-test-correction-839-correction-modal" id="task-num-8-check-code-btn">
Check your code
</button>
<div class="modal fade task_correction_modal student_modal" id="task-test-correction-839-correction-modal">
<div class="modal-dialog">
<div class="modal-content">
<div class="modal-header">
<button type="button" class="close" data-dismiss="modal" aria-label="Close"><span aria-hidden="true">&times;</span></button>
<h4 class="modal-title">Correction of "8. Hexadecimal"</h4>
</div>
<div class="modal-body">
<div class="actions">
<center>
<div class="alert alert-info hidden"></div>

<button name="button" type="submit" class="btn btn-primary correction_request_test_send" data-task-id="839">Start a new test</button>
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
<button data-task-id="839">
<i aria-hidden="true" class="fa fa-info-circle "></i>
</button>
<div class="help-container" data-task-id="839">
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



<button class="btn btn-default btn-sm" data-toggle="modal" data-target="#container-specs-modal"><i aria-hidden="true" class="fa fa-terminal "></i><span>Get a sandbox</span></button>

</div>


<div class="fs-4">
</div>
</div>


</div>
</div>

</div>
<div data-role="task840" data-position="10" id="task-num-9">
<div class="panel panel-default task-card " id="task-840">
<span id="user_id" data-id="197885"></span>

<div class="panel-heading panel-heading-actions">
<h3 class="panel-title">
9. Patience, persistence and perspiration make an unbeatable combination for success
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
<p>Write a program that prints all possible combinations of single-digit numbers.</p>

<ul>
<li>Numbers must be separated by <code>,</code>, followed by a space</li>
<li>Numbers should be printed in ascending order</li>
<li>You can only use the <code>putchar</code> function (every other function (<code>printf</code>, <code>puts</code>, etc&hellip;) is forbidden)</li>
<li>All your code should be in the <code>main</code> function</li>
<li>You can only use <code>putchar</code> four times maximum in your code</li>
<li>You are not allowed to use any variable of type <code>char</code></li>
</ul>

<pre><code>julien@ubuntu:~/0x01$ gcc -Wall -pedantic -Werror -Wextra -std=gnu89 9-print_comb.c -o 9-print_comb
julien@ubuntu:~/0x01$ ./9-print_comb | cat -e
0, 1, 2, 3, 4, 5, 6, 7, 8, 9$
julien@ubuntu:~/0x01$ 
</code></pre>

</div>

<div class="list-group">
<!-- Task URLs -->

<!-- Github information -->
<div class="list-group-item">
<p><strong>Repo:</strong></p>
<ul>
<li>GitHub repository: <code>alx-low_level_programming</code></li>
<li>Directory: <code>0x01-variables_if_else_while</code></li>
<li>File: <code>9-print_comb.c</code></li>
</ul>
</div>

<!-- Self-paced manual review -->
</div>

<!-- Panel footer - Controls -->
<div class="panel-footer">
<div class="align-items-center d-flex justify-content-between">

<div>
<button class="student_task_done btn btn-default btn-sm no" data-task-id="840">
<span class="no"><i aria-hidden="true" class="fa fa-square-o "></i></span>
<span class="yes"><i aria-hidden="true" class="fa fa-check-square-o "></i></span>
<span class="pending"><i aria-hidden="true" class="fa fa-spinner  fa-pulse"></i></span>
Done<span class="no pending">?</span><span class="yes">!</span>
</button>

<button class="student-task-done-by btn btn-default btn-sm" data-task-id="840" data-batch-id="26" data-toggle="modal" data-target="#task-840-users-done-modal">
Help
</button>
<div class="modal fade users-done-modal" id="task-840-users-done-modal" data-task-id="840" data-batch-id="26">
<div class="modal-dialog">
<div class="modal-content">
<div class="modal-header">
<button type="button" class="close" data-dismiss="modal" aria-label="Close"><span aria-hidden="true">&times;</span></button>
<h4 class="modal-title">Students who are done with "9. Patience, persistence and perspiration make an unbeatable combination for success"</h4>
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


<button class="btn btn-default btn-sm check-your-task-840-modal-button" data-task-id="840" data-toggle="modal" data-target="#task-test-correction-840-correction-modal" id="task-num-9-check-code-btn">
Check your code
</button>
<div class="modal fade task_correction_modal student_modal" id="task-test-correction-840-correction-modal">
<div class="modal-dialog">
<div class="modal-content">
<div class="modal-header">
<button type="button" class="close" data-dismiss="modal" aria-label="Close"><span aria-hidden="true">&times;</span></button>
<h4 class="modal-title">Correction of "9. Patience, persistence and perspiration make an unbeatable combination for success"</h4>
</div>
<div class="modal-body">
<div class="actions">
<center>
<div class="alert alert-info hidden"></div>

<button name="button" type="submit" class="btn btn-primary correction_request_test_send" data-task-id="840">Start a new test</button>
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
<button data-task-id="840">
<i aria-hidden="true" class="fa fa-info-circle "></i>
</button>
<div class="help-container" data-task-id="840">
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



<button class="btn btn-default btn-sm" data-toggle="modal" data-target="#container-specs-modal"><i aria-hidden="true" class="fa fa-terminal "></i><span>Get a sandbox</span></button>

</div>


<div class="fs-4">
</div>
</div>


</div>
</div>

</div>

<p class="lg-gap">
<form class="button_to" method="post" action="/projects/213/unlock_optionals"><input id="unlock_optional_btn" class="btn btn-primary btn-block" data-confirm="Are you sure? Make sure you focused on the mandatory tasks first" data-disable-with="Unlocking 3 advanced tasks..." type="submit" value="Done with the mandatory tasks? Unlock 3 advanced tasks now!" /><input type="hidden" name="authenticity_token" value="faO6pdNQgx_nUDCooVP8sSL6T0Ix1oVLbUmTY5goYzRywsvI3X9tkDsmI--T58qnk0uMBEW76lzHJFlTGNQQLA" autocomplete="off" /></form>
</p>




<div class="modal fade" id="container-specs-modal"><div class="modal-dialog modal-lg"><div class="modal-content"><div class="modal-header"><button type="button" class="close" data-dismiss="modal" aria-label="Close"><span aria-hidden="true">&times;</span></button><h4 class="modal-title">Recommended Sandbox</h4></div><div class="modal-body"><div data-react-class="user_containers/ContainerSpecs" data-react-props="{&quot;containerModelName&quot;:&quot;Sandbox&quot;,&quot;containerSpecs&quot;:[{&quot;description&quot;:&quot;\u003cp\u003eBasic Ubuntu 20.04, with vim, emacs, curl, wget and all needed for Foundations\u003c/p\u003e\n&quot;,&quot;id&quot;:39,&quot;name&quot;:&quot;Ubuntu 20.04&quot;,&quot;online&quot;:true,&quot;container&quot;:{&quot;container_id&quot;:&quot;c4e7755b271894d6b87d359c2ee6cf3e671d80d61d2080878d7d18ac32959bfc&quot;,&quot;id&quot;:239271,&quot;restart_uri&quot;:&quot;/user_containers/239271/restart.json&quot;,&quot;status&quot;:&quot;running&quot;,&quot;uri&quot;:&quot;/user_containers/239271.json&quot;,&quot;wake_uri&quot;:&quot;/user_containers/239271/wake.json&quot;,&quot;webterm_uri&quot;:&quot;/user_containers/239271/webterm&quot;,&quot;host&quot;:&quot;c4e7755b2718.3f09d370.alx-cod.online&quot;,&quot;password&quot;:&quot;2deaf74c415af9350d02&quot;,&quot;ports&quot;:{&quot;4000&quot;:49897,&quot;443&quot;:49900,&quot;8000&quot;:49894,&quot;8080&quot;:49893,&quot;3000&quot;:49899,&quot;3306&quot;:49898,&quot;5001&quot;:49895,&quot;80&quot;:49901,&quot;22&quot;:49902,&quot;5000&quot;:49896}}}],&quot;containersLimit&quot;:2,&quot;csrfToken&quot;:&quot;DLjU7_Iq1QJL6lgXjI3ZzZKlaQeZJ7VLHM1FMZgk8leavIMGrc0Zr4rhX4p_IjHExk_Dm1j2USoNvZHXfAOTxQ&quot;,&quot;startStatusURI&quot;:&quot;/user_containers/start_status.json&quot;,&quot;startURI&quot;:&quot;/user_containers/start.json&quot;}" data-react-cache-id="user_containers/ContainerSpecs-0"></div></div></div></div></div>

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