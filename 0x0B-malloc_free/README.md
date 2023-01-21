# Alx Software Engineer


<!DOCTYPE html>
<html lang="en">
<head>
<meta charset="utf-8">
<meta http-equiv="X-UA-Compatible" content="IE=edge">
<meta name="viewport" content="width=device-width, initial-scale=1">
<!-- The above 3 meta tags *must* come first in the head; any other head content must come *after* these tags -->
<meta name="description" content="">
<meta name="google" content="notranslate">

<script>
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


<title>Project: 0x0B. C - malloc, free | ALX Africa Intranet</title>

<link rel="stylesheet" href="https://use.typekit.net/xgz4ilr.css">
<link rel="stylesheet" media="all" href="/assets/application_alx-bd8f82c7d5afa064449a69a1a91b6daef7bdb1c71c00f2646d99a16e5040963a.css" />
<script src="https://www.gstatic.com/charts/loader.js"></script>
<script src="/assets/application-fb2ab0247cdaae2347e87bac130aa052747dadacfa429138002d69271946027f.js"></script>
<link rel="shortcut icon" type="image/x-icon" href="/favicon_alx.ico" />
<meta name="csrf-param" content="authenticity_token" />
<meta name="csrf-token" content="tuvhzkmXROEH10VmROXGNzRhEFKyk8GxdJXp_FJxgVNeOKQYA1_N3jbNtKktRibFOV7TIvsM0C7EX8FXIPUwBw" />

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
<script src="/packs/js/application-3888a42eeda4c8b53b02.js"></script>
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
<div class="inner" style="background-image: url('https://s3.amazonaws.com/alx-intranet.hbtn.io/users/photos/000/197/885/thumb/joker.jpg?X-Amz-Algorithm=AWS4-HMAC-SHA256&amp;X-Amz-Credential=AKIARDDGGGOUSBVO6H7D%2F20230121%2Fus-east-1%2Fs3%2Faws4_request&amp;X-Amz-Date=20230121T072424Z&amp;X-Amz-Expires=600&amp;X-Amz-SignedHeaders=host&amp;X-Amz-Signature=c744e6212d4942eceaec33bd15342b7087e0a7fc80d45260841444774fe4465d')"></div>
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
<div class="inner" style="background-image: url('https://s3.amazonaws.com/alx-intranet.hbtn.io/users/photos/000/197/885/thumb/joker.jpg?X-Amz-Algorithm=AWS4-HMAC-SHA256&amp;X-Amz-Credential=AKIARDDGGGOUSBVO6H7D%2F20230121%2Fus-east-1%2Fs3%2Faws4_request&amp;X-Amz-Date=20230121T072424Z&amp;X-Amz-Expires=600&amp;X-Amz-SignedHeaders=host&amp;X-Amz-Signature=c744e6212d4942eceaec33bd15342b7087e0a7fc80d45260841444774fe4465d')"></div>
</div>

<div class="visible-xs">My Profile</div>
</a>  </div>
</li>


</ul>
</div>


<main>
<div id="layout-bars">




<div id="captains_log_alert">
<a href="/captain_logs/1687913/edit">
<div>
You have a captain's log due before 2023-01-22 (in 1 day)! Log it now!
</div>
</a>    </div>

</div>

<article class="pending_logs">


<div class="project row">
<div class="col-xs-12 col-md-10 col-lg-8 contains-images">

<h1 class="gap">0x0B. C - malloc, free</h1>

<div data-react-class="tags/Tags" data-react-props="{&quot;tags&quot;:[{&quot;id&quot;:7,&quot;value&quot;:&quot;C&quot;,&quot;author_id&quot;:null,&quot;created_at&quot;:&quot;2022-06-16T01:59:38.000Z&quot;,&quot;updated_at&quot;:&quot;2022-06-16T01:59:38.000Z&quot;},{&quot;id&quot;:15,&quot;value&quot;:&quot;Memory allocation&quot;,&quot;author_id&quot;:null,&quot;created_at&quot;:&quot;2022-06-16T01:59:38.000Z&quot;,&quot;updated_at&quot;:&quot;2022-06-16T01:59:38.000Z&quot;}]}" data-react-cache-id="tags/Tags-0"></div>

<div data-react-class="projects/ProjectMetadata" data-react-props="{&quot;metadata&quot;:{&quot;author&quot;:&quot;Julien Barbier&quot;,&quot;weight&quot;:1,&quot;correction&quot;:{&quot;released&quot;:true,&quot;requires_auto_correction&quot;:true,&quot;requires_manual_correction&quot;:false},&quot;bpi&quot;:{&quot;current&quot;:false,&quot;in_second_deadline&quot;:false,&quot;starts_at&quot;:&quot;2023-01-09T06:00:00.000+03:00&quot;,&quot;ends_at&quot;:&quot;2023-01-11T06:00:00.000+03:00&quot;,&quot;second_deadline_at&quot;:&quot;2023-01-12T06:00:00.000+03:00&quot;}}}" data-react-cache-id="projects/ProjectMetadata-0"></div>

<div class="sm-gap clean well">
<h4>In a nutshell&hellip;</h4>
<ul>


<li>
<strong>Auto QA review:</strong>
0.0/47 mandatory
&
0.0/18 optional
</li>
<li>
<strong>Altogether:</strong>
&nbsp;<strong>0.0%</strong>
<ul>
<li>Mandatory: 0.0%</li>
<li>Optional: 0.0%</li>
<li>
Calculation:&nbsp;
0.0%
+ (0.0% * 0.0%)
&nbsp;==&nbsp;<strong>0.0%</strong>
</li>
</ul>
</li>
</ul>
</div>







<div id="project_id" style="display: none" data-project-id="222"></div>





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
<a href="/concepts/62">Automatic and dynamic allocation, malloc and free</a>
</li>
</ul>
</div>
</div>


<div class="panel panel-default" id="project-description">
<div class="panel-body">
<h2>Resources</h2>

<p><strong>Read or watch</strong>:</p>

<ul>
<li><a href="/rltoken/7q6RmWq86XkUhvmlhrg9bg" title="0x0a - malloc &amp; free - quick overview.pdf" target="_blank">0x0a - malloc &amp; free - quick overview.pdf</a></li>
<li><a href="/rltoken/pfGb2oVIYLO_1a8jtFGQYw" title="Dynamic memory allocation in C - malloc calloc realloc free" target="_blank">Dynamic memory allocation in C - malloc calloc realloc free</a> (<em>stop at 6:50</em>)</li>
</ul>

<p><strong>man or help</strong>:</p>

<ul>
<li><code>malloc</code></li>
<li><code>free</code></li>
</ul>

<h2>Learning Objectives</h2>

<p>At the end of this project, you are expected to be able to <a href="/rltoken/f-MGO-Fu4KSrem3R6GkEyw" title="explain to anyone" target="_blank">explain to anyone</a>, <strong>without the help of Google</strong>:</p>

<h3>General</h3>

<ul>
<li>What is the difference between automatic and dynamic allocation</li>
<li>What is <code>malloc</code> and <code>free</code> and how to use them</li>
<li>Why and when use <code>malloc</code></li>
<li>How to use <code>valgrind</code> to check for memory leak</li>
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
<li>The only C standard library functions allowed are <code>malloc</code> and <code>free</code>. Any use of functions like <code>printf</code>, <code>puts</code>, <code>calloc</code>, <code>realloc</code> etc&hellip; is forbidden</li>
<li>You are allowed to use <a href="https://github.com/holbertonschool/_putchar.c/blob/master/_putchar.c" title="_putchar" target="_blank">_putchar</a></li>
<li>You don&rsquo;t have to push <code>_putchar.c</code>, we will use our file. If you do it won&rsquo;t be taken into account</li>
<li>In the following examples, the <code>main.c</code> files are shown as examples. You can use them to test your functions, but you don&rsquo;t have to push them to your repo (if you do we won&rsquo;t take them into account). We will use our own <code>main.c</code> files at compilation. Our <code>main.c</code> files might be different from the one shown in the examples</li>
<li>The prototypes of all your functions and the prototype of the function <code>_putchar</code> should be included in your header file called <code>main.h</code></li>
<li>Don&rsquo;t forget to push your header file</li>
</ul>

<h2>More Info</h2>

<p>You do not have to learn about <code>calloc</code> and <code>realloc</code>.</p>

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
<div class="quiz_question_item_container" data-role="quiz_question477" data-position="3">
<div class=" clearfix" id="quiz_question-477">

<h4 class="quiz_question">

Question #0
</h4>

<!-- Quiz question Body -->
<p>How many bytes will this statement allocate?</p>

<p><code>malloc(sizeof(int) * 10)</code></p>


<!-- Quiz question Answers -->
<ul class="quiz_question_answers" data-question-id="477">
<li class="">

<input type="radio" name="477" id="477-1507596688742" value="1507596688742" data-quiz-answer-id="1507596688742" data-quiz-question-id="477" disabled="disabled" checked="checked" />
<label for="477-1507596688742"><p>40</p>
</label>
</li>

<li class="">

<input type="radio" name="477" id="477-1507596697706" value="1507596697706" data-quiz-answer-id="1507596697706" data-quiz-question-id="477" disabled="disabled" />
<label for="477-1507596697706"><p>10</p>
</label>
</li>

<li class="">

<input type="radio" name="477" id="477-1507596694559" value="1507596694559" data-quiz-answer-id="1507596694559" data-quiz-question-id="477" disabled="disabled" />
<label for="477-1507596694559"><p>32</p>
</label>
</li>

</ul>

<!-- Quiz question Tips -->

</div>

</div>
<div class="quiz_question_item_container" data-role="quiz_question478" data-position="4">
<div class=" clearfix" id="quiz_question-478">

<h4 class="quiz_question">

Question #1
</h4>

<!-- Quiz question Body -->
<p>How many bytes will this statement allocate?</p>

<p><code>malloc(sizeof(unsigned int) * 2)</code></p>


<!-- Quiz question Answers -->
<ul class="quiz_question_answers" data-question-id="478">
<li class="">

<input type="radio" name="478" id="478-1507596702169" value="1507596702169" data-quiz-answer-id="1507596702169" data-quiz-question-id="478" disabled="disabled" />
<label for="478-1507596702169"><p>2</p>
</label>
</li>

<li class="">

<input type="radio" name="478" id="478-1507596724065" value="1507596724065" data-quiz-answer-id="1507596724065" data-quiz-question-id="478" disabled="disabled" checked="checked" />
<label for="478-1507596724065"><p>8</p>
</label>
</li>

<li class="">

<input type="radio" name="478" id="478-1507596721541" value="1507596721541" data-quiz-answer-id="1507596721541" data-quiz-question-id="478" disabled="disabled" />
<label for="478-1507596721541"><p>4</p>
</label>
</li>

</ul>

<!-- Quiz question Tips -->

</div>

</div>
<div class="quiz_question_item_container" data-role="quiz_question481" data-position="7">
<div class=" clearfix" id="quiz_question-481">

<h4 class="quiz_question">

Question #2
</h4>

<!-- Quiz question Body -->
<p>How many bytes will this statement allocate?</p>

<p><code>malloc((sizeof(char) * 10) + 1)</code></p>


<!-- Quiz question Answers -->
<ul class="quiz_question_answers" data-question-id="481">
<li class="">

<input type="radio" name="481" id="481-1507596791404" value="1507596791404" data-quiz-answer-id="1507596791404" data-quiz-question-id="481" disabled="disabled" checked="checked" />
<label for="481-1507596791404"><p>11</p>
</label>
</li>

<li class="">

<input type="radio" name="481" id="481-1507596777679" value="1507596777679" data-quiz-answer-id="1507596777679" data-quiz-question-id="481" disabled="disabled" />
<label for="481-1507596777679"><p>1</p>
</label>
</li>

<li class="">

<input type="radio" name="481" id="481-1507596781426" value="1507596781426" data-quiz-answer-id="1507596781426" data-quiz-question-id="481" disabled="disabled" />
<label for="481-1507596781426"><p>10</p>
</label>
</li>

<li class="">

<input type="radio" name="481" id="481-1507596788808" value="1507596788808" data-quiz-answer-id="1507596788808" data-quiz-question-id="481" disabled="disabled" />
<label for="481-1507596788808"><p>20</p>
</label>
</li>

<li class="">

<input type="radio" name="481" id="481-1507596784086" value="1507596784086" data-quiz-answer-id="1507596784086" data-quiz-question-id="481" disabled="disabled" />
<label for="481-1507596784086"><p>21</p>
</label>
</li>

</ul>

<!-- Quiz question Tips -->

</div>

</div>
<div class="quiz_question_item_container" data-role="quiz_question475" data-position="1">
<div class=" clearfix" id="quiz_question-475">

<h4 class="quiz_question">

Question #3
</h4>

<!-- Quiz question Body -->
<p>What is Valgrind?</p>


<!-- Quiz question Answers -->
<ul class="quiz_question_answers" data-question-id="475">
<li class="">

<input type="radio" name="475" id="475-1507596544532" value="1507596544532" data-quiz-answer-id="1507596544532" data-quiz-question-id="475" disabled="disabled" />
<label for="475-1507596544532"><p>It&rsquo;s a new step when I compile with <code>gcc</code></p>
</label>
</li>

<li class="">

<input type="radio" name="475" id="475-1507596507109" value="1507596507109" data-quiz-answer-id="1507596507109" data-quiz-question-id="475" disabled="disabled" />
<label for="475-1507596507109"><p>A container service</p>
</label>
</li>

<li class="">

<input type="radio" name="475" id="475-1507596562396" value="1507596562396" data-quiz-answer-id="1507596562396" data-quiz-question-id="475" disabled="disabled" />
<label for="475-1507596562396"><p>It&rsquo;s a program to test a C program in a specific environment</p>
</label>
</li>

<li class="">

<input type="radio" name="475" id="475-1507596517727" value="1507596517727" data-quiz-answer-id="1507596517727" data-quiz-question-id="475" disabled="disabled" checked="checked" />
<label for="475-1507596517727"><p>It&rsquo;s a program to validate memory allocation</p>
</label>
</li>

</ul>

<!-- Quiz question Tips -->

</div>

</div>
<div class="quiz_question_item_container" data-role="quiz_question479" data-position="5">
<div class=" clearfix" id="quiz_question-479">

<h4 class="quiz_question">

Question #4
</h4>

<!-- Quiz question Body -->
<p>How many bytes will this statement allocate?</p>

<p><code>malloc(sizeof(char) * 10)</code></p>


<!-- Quiz question Answers -->
<ul class="quiz_question_answers" data-question-id="479">
<li class="">

<input type="radio" name="479" id="479-1507596731787" value="1507596731787" data-quiz-answer-id="1507596731787" data-quiz-question-id="479" disabled="disabled" checked="checked" />
<label for="479-1507596731787"><p>10</p>
</label>
</li>

<li class="">

<input type="radio" name="479" id="479-1507596755026" value="1507596755026" data-quiz-answer-id="1507596755026" data-quiz-question-id="479" disabled="disabled" />
<label for="479-1507596755026"><p>40</p>
</label>
</li>

<li class="">

<input type="radio" name="479" id="479-1507596752495" value="1507596752495" data-quiz-answer-id="1507596752495" data-quiz-question-id="479" disabled="disabled" />
<label for="479-1507596752495"><p>20</p>
</label>
</li>

</ul>

<!-- Quiz question Tips -->

</div>

</div>
<div class="quiz_question_item_container" data-role="quiz_question480" data-position="6">
<div class=" clearfix" id="quiz_question-480">

<h4 class="quiz_question">

Question #5
</h4>

<!-- Quiz question Body -->
<p>How many bytes will this statement allocate?</p>

<p><code>malloc(10)</code></p>


<!-- Quiz question Answers -->
<ul class="quiz_question_answers" data-question-id="480">
<li class="">

<input type="radio" name="480" id="480-1507596766618" value="1507596766618" data-quiz-answer-id="1507596766618" data-quiz-question-id="480" disabled="disabled" />
<label for="480-1507596766618"><p>4</p>
</label>
</li>

<li class="">

<input type="radio" name="480" id="480-1507596760063" value="1507596760063" data-quiz-answer-id="1507596760063" data-quiz-question-id="480" disabled="disabled" />
<label for="480-1507596760063"><p>2</p>
</label>
</li>

<li class="">

<input type="radio" name="480" id="480-1507596771757" value="1507596771757" data-quiz-answer-id="1507596771757" data-quiz-question-id="480" disabled="disabled" />
<label for="480-1507596771757"><p>40</p>
</label>
</li>

<li class="">

<input type="radio" name="480" id="480-1507596763389" value="1507596763389" data-quiz-answer-id="1507596763389" data-quiz-question-id="480" disabled="disabled" checked="checked" />
<label for="480-1507596763389"><p>10</p>
</label>
</li>

</ul>

<!-- Quiz question Tips -->

</div>

</div>
<div class="quiz_question_item_container" data-role="quiz_question476" data-position="2">
<div class=" clearfix" id="quiz_question-476">

<h4 class="quiz_question">

Question #6
</h4>

<!-- Quiz question Body -->
<p>How many bytes will this statement allocate?</p>

<p><code>malloc(sizeof(int) * 4)</code></p>


<!-- Quiz question Answers -->
<ul class="quiz_question_answers" data-question-id="476">
<li class="">

<input type="radio" name="476" id="476-1507596676791" value="1507596676791" data-quiz-answer-id="1507596676791" data-quiz-question-id="476" disabled="disabled" checked="checked" />
<label for="476-1507596676791"><p>16</p>
</label>
</li>

<li class="">

<input type="radio" name="476" id="476-1507596590794" value="1507596590794" data-quiz-answer-id="1507596590794" data-quiz-question-id="476" disabled="disabled" />
<label for="476-1507596590794"><p>4</p>
</label>
</li>

<li class="">

<input type="radio" name="476" id="476-1507596680131" value="1507596680131" data-quiz-answer-id="1507596680131" data-quiz-question-id="476" disabled="disabled" />
<label for="476-1507596680131"><p>32</p>
</label>
</li>

<li class="">

<input type="radio" name="476" id="476-1507596674034" value="1507596674034" data-quiz-answer-id="1507596674034" data-quiz-question-id="476" disabled="disabled" />
<label for="476-1507596674034"><p>8</p>
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

<div data-role="task932" data-position="1" id="task-num-0">
<div class="panel panel-default task-card " id="task-932">
<span id="user_id" data-id="197885"></span>

<div class="panel-heading panel-heading-actions">
<h3 class="panel-title">
0. Float like a butterfly, sting like a bee
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
<div class="task_progress_score_bar" data-task-id="932" data-correction-id="7879454">
<div class="task_progress_bar" style="width: 0.0%">
<div class="task_score_bar" style="width: NaN%">
</div>
</div>
<div class="task_progress_score_text">
Score: <span class="task_score_value">0.0%</span> (<span class="task_progress_value">Checks completed: 0.0%</span>)
</div>
</div>

<!-- Task Body -->
<p>Write a function that creates an array of chars, and initializes it with a specific char.</p>

<ul>
<li>Prototype: <code>char *create_array(unsigned int size, char c);</code></li>
<li>Returns <code>NULL</code> if size = <code>0</code></li>
<li>Returns a pointer to the array, or <code>NULL</code> if it fails</li>
</ul>

<pre><code>julien@ubuntu:~/0x0a. malloc, free$ cat 0-main.c 
#include &quot;main.h&quot;
#include &lt;stdio.h&gt;
#include &lt;stdlib.h&gt;

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
* main - check the code for ALX School students.
*
* Return: Always 0.
*/
int main(void)
{
char *buffer;

buffer = create_array(98, &#39;H&#39;);
if  (buffer == NULL)
{
printf(&quot;failed to allocate memory\n&quot;);
return (1);
}
simple_print_buffer(buffer, 98);
free(buffer);
return (0);
}
julien@ubuntu:~/0x0a. malloc, free$ gcc -Wall -pedantic -Werror -Wextra -std=gnu89 0-main.c 0-create_array.c -o a
julien@ubuntu:~/0x0a. malloc, free$ ./a 
0x48 0x48 0x48 0x48 0x48 0x48 0x48 0x48 0x48 0x48
0x48 0x48 0x48 0x48 0x48 0x48 0x48 0x48 0x48 0x48
0x48 0x48 0x48 0x48 0x48 0x48 0x48 0x48 0x48 0x48
0x48 0x48 0x48 0x48 0x48 0x48 0x48 0x48 0x48 0x48
0x48 0x48 0x48 0x48 0x48 0x48 0x48 0x48 0x48 0x48
0x48 0x48 0x48 0x48 0x48 0x48 0x48 0x48 0x48 0x48
0x48 0x48 0x48 0x48 0x48 0x48 0x48 0x48 0x48 0x48
0x48 0x48 0x48 0x48 0x48 0x48 0x48 0x48 0x48 0x48
0x48 0x48 0x48 0x48 0x48 0x48 0x48 0x48 0x48 0x48
0x48 0x48 0x48 0x48 0x48 0x48 0x48 0x48
julien@ubuntu:~/0x0a. malloc, free$ 
</code></pre>

</div>

<div class="list-group">
<!-- Task URLs -->

<!-- Github information -->
<div class="list-group-item">
<p><strong>Repo:</strong></p>
<ul>
<li>GitHub repository: <code>alx-low_level_programming</code></li>
<li>Directory: <code>0x0B-malloc_free</code></li>
<li>File: <code>0-create_array.c</code></li>
</ul>
</div>

<!-- Self-paced manual review -->
</div>

<!-- Panel footer - Controls -->
<div class="panel-footer">
<div class="align-items-center d-flex justify-content-between">

<div>
<button class="student_task_done btn btn-default btn-sm no" data-task-id="932">
<span class="no"><i aria-hidden="true" class="fa fa-square-o "></i></span>
<span class="yes"><i aria-hidden="true" class="fa fa-check-square-o "></i></span>
<span class="pending"><i aria-hidden="true" class="fa fa-spinner  fa-pulse"></i></span>
Done<span class="no pending">?</span><span class="yes">!</span>
</button>

<button class="student-task-done-by btn btn-default btn-sm" data-task-id="932" data-batch-id="26" data-toggle="modal" data-target="#task-932-users-done-modal">
Help
</button>
<div class="modal fade users-done-modal" id="task-932-users-done-modal" data-task-id="932" data-batch-id="26">
<div class="modal-dialog">
<div class="modal-content">
<div class="modal-header">
<button type="button" class="close" data-dismiss="modal" aria-label="Close"><span aria-hidden="true">&times;</span></button>
<h4 class="modal-title">Students who are done with "0. Float like a butterfly, sting like a bee"</h4>
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


<button class="btn btn-default btn-sm check-your-task-932-modal-button" data-task-id="932" data-toggle="modal" data-target="#task-test-correction-932-correction-modal" id="task-num-0-check-code-btn" data-gtm-custom-event-name="task_checker_modal" data-gtm-custom-event-options='{&quot;taskId&quot;:932}'>
Check your code
</button>
<div class="modal fade task_correction_modal student_modal" id="task-test-correction-932-correction-modal">
<div class="modal-dialog">
<div class="modal-content">
<div class="modal-header">
<button type="button" class="close" data-dismiss="modal" aria-label="Close"><span aria-hidden="true">&times;</span></button>
<h4 class="modal-title">Correction of "0. Float like a butterfly, sting like a bee"</h4>
</div>
<div class="modal-body">
<div class="actions">
<center>
<div class="alert alert-info hidden"></div>

<button name="button" type="submit" class="btn btn-primary correction_request_test_send" data-task-id="932">Start a new test</button>
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
<button data-task-id="932">
<i aria-hidden="true" class="fa fa-info-circle "></i>
</button>
<div class="help-container" data-task-id="932">
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


<button class="btn btn-primary btn-sm task_ask_new_correction " data-task-id="932" data-correction-id="7879454">
Ask for a new correction
<span class="in_progress_info">: in progress...</span>
<span class="error_occurred_info">: an error occurred</span>
</button>

<button class="btn btn-default btn-sm" data-toggle="modal" data-target="#container-specs-modal" data-gtm-custom-event-name="task_sandbox_modal" data-gtm-custom-event-options="{&quot;taskId&quot;:932}"><i aria-hidden="true" class="fa fa-terminal "></i><span>Get a sandbox</span></button>

<button class="btn btn-default btn-sm" data-task-id="932" data-toggle="modal" data-target="#task-qa-review-932-modal" data-gtm-custom-event-name="task_qa_review_modal" data-gtm-custom-event-options='{&quot;taskId&quot;:932}'>
QA Review
</button>
<div class="modal fade task_get_qa_review" id="task-qa-review-932-modal" data-correction-id="7879454" data-task-id="932">
<div class="modal-dialog modal-lg">
<div class="modal-content">
<div class="modal-header">
<button type="button" class="close" data-dismiss="modal" aria-label="Close"><span aria-hidden="true">&times;</span></button>
<h4 class="modal-title">0. Float like a butterfly, sting like a bee</h4>
</div>
<div class="modal-body">
<div class="spinner gap">
<div class="bounce1"></div>
<div class="bounce2"></div>
<div class="bounce3"></div>
</div>
<div class="review-container">
<div class="review-corrector"></div>
<div class="review-github well" style="display:none">
<h5>Commit used:</h5>
<ul>
<li style="display:none"><strong>User:</strong> <code class="review-github-id"></code> <span class="review-github-name">---</span></li>
<li style="display:none"><strong>URL:</strong> <a class="review-github-url" target="_blank">Click here</a></li>
<li style="display:none"><strong>ID:</strong> <code class="review-github-commit_id">---</code></li>
<li style="display:none"><strong>Author:</strong> <span class="review-github-committer_username">---</span></li>
<li style="display:none"><strong>Subject:</strong> <em class="review-github-subject">---</em></li>
<li style="display:none"><strong>Date:</strong> <span class="review-github-datetime">---</span></li>
</ul>
</div>
<div class="review-percentage_down"></div>
<ul class="review-checks list-group sm-gap"></ul>
<div class="review-comment"></div>
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
<div data-role="task933" data-position="2" id="task-num-1">
<div class="panel panel-default task-card " id="task-933">
<span id="user_id" data-id="197885"></span>

<div class="panel-heading panel-heading-actions">
<h3 class="panel-title">
1. The woman who has no imagination has no wings
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
<div class="task_progress_score_bar" data-task-id="933" data-correction-id="7879454">
<div class="task_progress_bar" style="width: 0.0%">
<div class="task_score_bar" style="width: NaN%">
</div>
</div>
<div class="task_progress_score_text">
Score: <span class="task_score_value">0.0%</span> (<span class="task_progress_value">Checks completed: 0.0%</span>)
</div>
</div>

<!-- Task Body -->
<p>Write a function that returns a pointer to a newly allocated space in memory, which contains a copy of the string given as a parameter.</p>

<ul>
<li>Prototype: <code>char *_strdup(char *str);</code></li>
<li>The <code>_strdup()</code> function returns a pointer to a new string which is a duplicate of the string <code>str</code>.  Memory for the new string is obtained with <code>malloc</code>, and can be freed with <code>free</code>.</li>
<li>Returns <code>NULL</code> if str = NULL</li>
<li>On success, the <code>_strdup</code> function returns a pointer to the duplicated string.  It returns <code>NULL</code> if insufficient memory was available</li>
</ul>

<p>FYI: The standard library provides a similar function: <code>strdup</code>. Run <code>man strdup</code> to learn more.</p>

<pre><code>julien@ubuntu:~/0x0a. malloc, free$ cat 1-main.c
#include &quot;main.h&quot;
#include &lt;stdio.h&gt;
#include &lt;stdlib.h&gt;

/**
* main - check the code for ALX School students.
*
* Return: Always 0.
*/
int main(void)
{
char *s;

s = _strdup(&quot;ALX SE&quot;);
if (s == NULL)
{
printf(&quot;failed to allocate memory\n&quot;);
return (1);
}
printf(&quot;%s\n&quot;, s);
free(s);
return (0);
}
julien@ubuntu:~/0x0a. malloc, free$ gcc -Wall -pedantic -Werror -Wextra -std=gnu89 1-main.c 1-strdup.c -o s
julien@ubuntu:~/0x0a. malloc, free$ ./s 
ALX SE
julien@ubuntu:~/0x0a. malloc, free$ 
</code></pre>

</div>

<div class="list-group">
<!-- Task URLs -->

<!-- Github information -->
<div class="list-group-item">
<p><strong>Repo:</strong></p>
<ul>
<li>GitHub repository: <code>alx-low_level_programming</code></li>
<li>Directory: <code>0x0B-malloc_free</code></li>
<li>File: <code>1-strdup.c</code></li>
</ul>
</div>

<!-- Self-paced manual review -->
</div>

<!-- Panel footer - Controls -->
<div class="panel-footer">
<div class="align-items-center d-flex justify-content-between">

<div>
<button class="student_task_done btn btn-default btn-sm no" data-task-id="933">
<span class="no"><i aria-hidden="true" class="fa fa-square-o "></i></span>
<span class="yes"><i aria-hidden="true" class="fa fa-check-square-o "></i></span>
<span class="pending"><i aria-hidden="true" class="fa fa-spinner  fa-pulse"></i></span>
Done<span class="no pending">?</span><span class="yes">!</span>
</button>

<button class="student-task-done-by btn btn-default btn-sm" data-task-id="933" data-batch-id="26" data-toggle="modal" data-target="#task-933-users-done-modal">
Help
</button>
<div class="modal fade users-done-modal" id="task-933-users-done-modal" data-task-id="933" data-batch-id="26">
<div class="modal-dialog">
<div class="modal-content">
<div class="modal-header">
<button type="button" class="close" data-dismiss="modal" aria-label="Close"><span aria-hidden="true">&times;</span></button>
<h4 class="modal-title">Students who are done with "1. The woman who has no imagination has no wings"</h4>
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


<button class="btn btn-default btn-sm check-your-task-933-modal-button" data-task-id="933" data-toggle="modal" data-target="#task-test-correction-933-correction-modal" id="task-num-1-check-code-btn" data-gtm-custom-event-name="task_checker_modal" data-gtm-custom-event-options='{&quot;taskId&quot;:933}'>
Check your code
</button>
<div class="modal fade task_correction_modal student_modal" id="task-test-correction-933-correction-modal">
<div class="modal-dialog">
<div class="modal-content">
<div class="modal-header">
<button type="button" class="close" data-dismiss="modal" aria-label="Close"><span aria-hidden="true">&times;</span></button>
<h4 class="modal-title">Correction of "1. The woman who has no imagination has no wings"</h4>
</div>
<div class="modal-body">
<div class="actions">
<center>
<div class="alert alert-info hidden"></div>

<button name="button" type="submit" class="btn btn-primary correction_request_test_send" data-task-id="933">Start a new test</button>
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
<button data-task-id="933">
<i aria-hidden="true" class="fa fa-info-circle "></i>
</button>
<div class="help-container" data-task-id="933">
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


<button class="btn btn-primary btn-sm task_ask_new_correction " data-task-id="933" data-correction-id="7879454">
Ask for a new correction
<span class="in_progress_info">: in progress...</span>
<span class="error_occurred_info">: an error occurred</span>
</button>

<button class="btn btn-default btn-sm" data-toggle="modal" data-target="#container-specs-modal" data-gtm-custom-event-name="task_sandbox_modal" data-gtm-custom-event-options="{&quot;taskId&quot;:933}"><i aria-hidden="true" class="fa fa-terminal "></i><span>Get a sandbox</span></button>

<button class="btn btn-default btn-sm" data-task-id="933" data-toggle="modal" data-target="#task-qa-review-933-modal" data-gtm-custom-event-name="task_qa_review_modal" data-gtm-custom-event-options='{&quot;taskId&quot;:933}'>
QA Review
</button>
<div class="modal fade task_get_qa_review" id="task-qa-review-933-modal" data-correction-id="7879454" data-task-id="933">
<div class="modal-dialog modal-lg">
<div class="modal-content">
<div class="modal-header">
<button type="button" class="close" data-dismiss="modal" aria-label="Close"><span aria-hidden="true">&times;</span></button>
<h4 class="modal-title">1. The woman who has no imagination has no wings</h4>
</div>
<div class="modal-body">
<div class="spinner gap">
<div class="bounce1"></div>
<div class="bounce2"></div>
<div class="bounce3"></div>
</div>
<div class="review-container">
<div class="review-corrector"></div>
<div class="review-github well" style="display:none">
<h5>Commit used:</h5>
<ul>
<li style="display:none"><strong>User:</strong> <code class="review-github-id"></code> <span class="review-github-name">---</span></li>
<li style="display:none"><strong>URL:</strong> <a class="review-github-url" target="_blank">Click here</a></li>
<li style="display:none"><strong>ID:</strong> <code class="review-github-commit_id">---</code></li>
<li style="display:none"><strong>Author:</strong> <span class="review-github-committer_username">---</span></li>
<li style="display:none"><strong>Subject:</strong> <em class="review-github-subject">---</em></li>
<li style="display:none"><strong>Date:</strong> <span class="review-github-datetime">---</span></li>
</ul>
</div>
<div class="review-percentage_down"></div>
<ul class="review-checks list-group sm-gap"></ul>
<div class="review-comment"></div>
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
<div data-role="task934" data-position="3" id="task-num-2">
<div class="panel panel-default task-card " id="task-934">
<span id="user_id" data-id="197885"></span>

<div class="panel-heading panel-heading-actions">
<h3 class="panel-title">
2. He who is not courageous enough to take risks will accomplish nothing in life
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
<div class="task_progress_score_bar" data-task-id="934" data-correction-id="7879454">
<div class="task_progress_bar" style="width: 0.0%">
<div class="task_score_bar" style="width: NaN%">
</div>
</div>
<div class="task_progress_score_text">
Score: <span class="task_score_value">0.0%</span> (<span class="task_progress_value">Checks completed: 0.0%</span>)
</div>
</div>

<!-- Task Body -->
<p>Write a function that concatenates two strings.</p>

<ul>
<li>Prototype: <code>char *str_concat(char *s1, char *s2);</code></li>
<li>The returned pointer should point to a newly allocated space in memory which contains the contents of <code>s1</code>, followed by the contents of <code>s2</code>, and null terminated</li>
<li>if <code>NULL</code> is passed, treat it as an empty string</li>
<li>The function should return <code>NULL</code> on failure</li>
</ul>

<pre><code>julien@ubuntu:~/0x0a. malloc, free$ cat 2-main.c
#include &quot;main.h&quot;
#include &lt;stdio.h&gt;
#include &lt;stdlib.h&gt;

/**
* main - check the code for ALX School students.
*
* Return: Always 0.
*/
int main(void)
{
char *s;

s = str_concat(&quot;Betty &quot;, &quot;Holberton&quot;);
if (s == NULL)
{
printf(&quot;failed\n&quot;);
return (1);
}
printf(&quot;%s\n&quot;, s);
free(s);
return (0);
}
julien@ubuntu:~/0x0a. malloc, free$ gcc -Wall -pedantic -Werror -Wextra -std=gnu89 2-main.c 2-str_concat.c -o c
julien@ubuntu:~/c/curriculum_by_julien/holbertonschool-low_level_programming/0x0a. malloc, free$ ./c | cat -e
Betty Holberton$
julien@ubuntu:~/c/curriculum_by_julien/holbertonschool-low_level_programming/0x0a. malloc, free$ 
</code></pre>

</div>

<div class="list-group">
<!-- Task URLs -->

<!-- Github information -->
<div class="list-group-item">
<p><strong>Repo:</strong></p>
<ul>
<li>GitHub repository: <code>alx-low_level_programming</code></li>
<li>Directory: <code>0x0B-malloc_free</code></li>
<li>File: <code>2-str_concat.c</code></li>
</ul>
</div>

<!-- Self-paced manual review -->
</div>

<!-- Panel footer - Controls -->
<div class="panel-footer">
<div class="align-items-center d-flex justify-content-between">

<div>
<button class="student_task_done btn btn-default btn-sm no" data-task-id="934">
<span class="no"><i aria-hidden="true" class="fa fa-square-o "></i></span>
<span class="yes"><i aria-hidden="true" class="fa fa-check-square-o "></i></span>
<span class="pending"><i aria-hidden="true" class="fa fa-spinner  fa-pulse"></i></span>
Done<span class="no pending">?</span><span class="yes">!</span>
</button>

<button class="student-task-done-by btn btn-default btn-sm" data-task-id="934" data-batch-id="26" data-toggle="modal" data-target="#task-934-users-done-modal">
Help
</button>
<div class="modal fade users-done-modal" id="task-934-users-done-modal" data-task-id="934" data-batch-id="26">
<div class="modal-dialog">
<div class="modal-content">
<div class="modal-header">
<button type="button" class="close" data-dismiss="modal" aria-label="Close"><span aria-hidden="true">&times;</span></button>
<h4 class="modal-title">Students who are done with "2. He who is not courageous enough to take risks will accomplish nothing in life"</h4>
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


<button class="btn btn-default btn-sm check-your-task-934-modal-button" data-task-id="934" data-toggle="modal" data-target="#task-test-correction-934-correction-modal" id="task-num-2-check-code-btn" data-gtm-custom-event-name="task_checker_modal" data-gtm-custom-event-options='{&quot;taskId&quot;:934}'>
Check your code
</button>
<div class="modal fade task_correction_modal student_modal" id="task-test-correction-934-correction-modal">
<div class="modal-dialog">
<div class="modal-content">
<div class="modal-header">
<button type="button" class="close" data-dismiss="modal" aria-label="Close"><span aria-hidden="true">&times;</span></button>
<h4 class="modal-title">Correction of "2. He who is not courageous enough to take risks will accomplish nothing in life"</h4>
</div>
<div class="modal-body">
<div class="actions">
<center>
<div class="alert alert-info hidden"></div>

<button name="button" type="submit" class="btn btn-primary correction_request_test_send" data-task-id="934">Start a new test</button>
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
<button data-task-id="934">
<i aria-hidden="true" class="fa fa-info-circle "></i>
</button>
<div class="help-container" data-task-id="934">
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


<button class="btn btn-primary btn-sm task_ask_new_correction " data-task-id="934" data-correction-id="7879454">
Ask for a new correction
<span class="in_progress_info">: in progress...</span>
<span class="error_occurred_info">: an error occurred</span>
</button>

<button class="btn btn-default btn-sm" data-toggle="modal" data-target="#container-specs-modal" data-gtm-custom-event-name="task_sandbox_modal" data-gtm-custom-event-options="{&quot;taskId&quot;:934}"><i aria-hidden="true" class="fa fa-terminal "></i><span>Get a sandbox</span></button>

<button class="btn btn-default btn-sm" data-task-id="934" data-toggle="modal" data-target="#task-qa-review-934-modal" data-gtm-custom-event-name="task_qa_review_modal" data-gtm-custom-event-options='{&quot;taskId&quot;:934}'>
QA Review
</button>
<div class="modal fade task_get_qa_review" id="task-qa-review-934-modal" data-correction-id="7879454" data-task-id="934">
<div class="modal-dialog modal-lg">
<div class="modal-content">
<div class="modal-header">
<button type="button" class="close" data-dismiss="modal" aria-label="Close"><span aria-hidden="true">&times;</span></button>
<h4 class="modal-title">2. He who is not courageous enough to take risks will accomplish nothing in life</h4>
</div>
<div class="modal-body">
<div class="spinner gap">
<div class="bounce1"></div>
<div class="bounce2"></div>
<div class="bounce3"></div>
</div>
<div class="review-container">
<div class="review-corrector"></div>
<div class="review-github well" style="display:none">
<h5>Commit used:</h5>
<ul>
<li style="display:none"><strong>User:</strong> <code class="review-github-id"></code> <span class="review-github-name">---</span></li>
<li style="display:none"><strong>URL:</strong> <a class="review-github-url" target="_blank">Click here</a></li>
<li style="display:none"><strong>ID:</strong> <code class="review-github-commit_id">---</code></li>
<li style="display:none"><strong>Author:</strong> <span class="review-github-committer_username">---</span></li>
<li style="display:none"><strong>Subject:</strong> <em class="review-github-subject">---</em></li>
<li style="display:none"><strong>Date:</strong> <span class="review-github-datetime">---</span></li>
</ul>
</div>
<div class="review-percentage_down"></div>
<ul class="review-checks list-group sm-gap"></ul>
<div class="review-comment"></div>
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
<div data-role="task935" data-position="4" id="task-num-3">
<div class="panel panel-default task-card " id="task-935">
<span id="user_id" data-id="197885"></span>

<div class="panel-heading panel-heading-actions">
<h3 class="panel-title">
3. If you even dream of beating me you&#39;d better wake up and apologize
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
<div class="task_progress_score_bar" data-task-id="935" data-correction-id="7879454">
<div class="task_progress_bar" style="width: 0.0%">
<div class="task_score_bar" style="width: NaN%">
</div>
</div>
<div class="task_progress_score_text">
Score: <span class="task_score_value">0.0%</span> (<span class="task_progress_value">Checks completed: 0.0%</span>)
</div>
</div>

<!-- Task Body -->
<p>Write a function that returns a pointer to a 2 dimensional array of integers.</p>

<ul>
<li>Prototype: <code>int **alloc_grid(int width, int height);</code></li>
<li>Each element of the grid should be initialized to <code>0</code></li>
<li>The function should return <code>NULL</code> on failure</li>
<li>If <code>width</code> or <code>height</code> is <code>0</code> or negative, return <code>NULL</code></li>
</ul>

<pre><code>julien@ubuntu:~/0x0a. malloc, free$ cat 3-main.c
#include &quot;main.h&quot;
#include &lt;stdio.h&gt;
#include &lt;stdlib.h&gt;

/**
* print_grid - prints a grid of integers
* @grid: the address of the two dimensional grid
* @width: width of the grid
* @height: height of the grid
*
* Return: Nothing.
*/
void print_grid(int **grid, int width, int height)
{
int w;
int h;

h = 0;
while (h &lt; height)
{
w = 0;
while (w &lt; width)
{
printf(&quot;%d &quot;, grid[h][w]);
w++;
}
printf(&quot;\n&quot;);
h++;
}   
}

/**
* main - check the code for ALX School students.
*
* Return: Always 0.
*/
int main(void)
{
int **grid;

grid = alloc_grid(6, 4);
if (grid == NULL)
{
return (1);
}
print_grid(grid, 6, 4);
printf(&quot;\n&quot;);
grid[0][3] = 98;
grid[3][4] = 402;
print_grid(grid, 6, 4);
return (0);
}
julien@ubuntu:~/0x0a. malloc, free$ gcc -Wall -pedantic -Werror -Wextra -std=gnu89 3-main.c 3-alloc_grid.c -o g
julien@ubuntu:~/0x0a. malloc, free$ ./g
0 0 0 0 0 0 
0 0 0 0 0 0 
0 0 0 0 0 0 
0 0 0 0 0 0 

0 0 0 98 0 0 
0 0 0 0 0 0 
0 0 0 0 0 0 
0 0 0 0 402 0 
julien@ubuntu:~/0x0a. malloc, free$
</code></pre>

</div>

<div class="list-group">
<!-- Task URLs -->

<!-- Github information -->
<div class="list-group-item">
<p><strong>Repo:</strong></p>
<ul>
<li>GitHub repository: <code>alx-low_level_programming</code></li>
<li>Directory: <code>0x0B-malloc_free</code></li>
<li>File: <code>3-alloc_grid.c</code></li>
</ul>
</div>

<!-- Self-paced manual review -->
</div>

<!-- Panel footer - Controls -->
<div class="panel-footer">
<div class="align-items-center d-flex justify-content-between">

<div>
<button class="student_task_done btn btn-default btn-sm no" data-task-id="935">
<span class="no"><i aria-hidden="true" class="fa fa-square-o "></i></span>
<span class="yes"><i aria-hidden="true" class="fa fa-check-square-o "></i></span>
<span class="pending"><i aria-hidden="true" class="fa fa-spinner  fa-pulse"></i></span>
Done<span class="no pending">?</span><span class="yes">!</span>
</button>

<button class="student-task-done-by btn btn-default btn-sm" data-task-id="935" data-batch-id="26" data-toggle="modal" data-target="#task-935-users-done-modal">
Help
</button>
<div class="modal fade users-done-modal" id="task-935-users-done-modal" data-task-id="935" data-batch-id="26">
<div class="modal-dialog">
<div class="modal-content">
<div class="modal-header">
<button type="button" class="close" data-dismiss="modal" aria-label="Close"><span aria-hidden="true">&times;</span></button>
<h4 class="modal-title">Students who are done with "3. If you even dream of beating me you&#39;d better wake up and apologize"</h4>
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


<button class="btn btn-default btn-sm check-your-task-935-modal-button" data-task-id="935" data-toggle="modal" data-target="#task-test-correction-935-correction-modal" id="task-num-3-check-code-btn" data-gtm-custom-event-name="task_checker_modal" data-gtm-custom-event-options='{&quot;taskId&quot;:935}'>
Check your code
</button>
<div class="modal fade task_correction_modal student_modal" id="task-test-correction-935-correction-modal">
<div class="modal-dialog">
<div class="modal-content">
<div class="modal-header">
<button type="button" class="close" data-dismiss="modal" aria-label="Close"><span aria-hidden="true">&times;</span></button>
<h4 class="modal-title">Correction of "3. If you even dream of beating me you&#39;d better wake up and apologize"</h4>
</div>
<div class="modal-body">
<div class="actions">
<center>
<div class="alert alert-info hidden"></div>

<button name="button" type="submit" class="btn btn-primary correction_request_test_send" data-task-id="935">Start a new test</button>
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
<button data-task-id="935">
<i aria-hidden="true" class="fa fa-info-circle "></i>
</button>
<div class="help-container" data-task-id="935">
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


<button class="btn btn-primary btn-sm task_ask_new_correction " data-task-id="935" data-correction-id="7879454">
Ask for a new correction
<span class="in_progress_info">: in progress...</span>
<span class="error_occurred_info">: an error occurred</span>
</button>

<button class="btn btn-default btn-sm" data-toggle="modal" data-target="#container-specs-modal" data-gtm-custom-event-name="task_sandbox_modal" data-gtm-custom-event-options="{&quot;taskId&quot;:935}"><i aria-hidden="true" class="fa fa-terminal "></i><span>Get a sandbox</span></button>

<button class="btn btn-default btn-sm" data-task-id="935" data-toggle="modal" data-target="#task-qa-review-935-modal" data-gtm-custom-event-name="task_qa_review_modal" data-gtm-custom-event-options='{&quot;taskId&quot;:935}'>
QA Review
</button>
<div class="modal fade task_get_qa_review" id="task-qa-review-935-modal" data-correction-id="7879454" data-task-id="935">
<div class="modal-dialog modal-lg">
<div class="modal-content">
<div class="modal-header">
<button type="button" class="close" data-dismiss="modal" aria-label="Close"><span aria-hidden="true">&times;</span></button>
<h4 class="modal-title">3. If you even dream of beating me you&#39;d better wake up and apologize</h4>
</div>
<div class="modal-body">
<div class="spinner gap">
<div class="bounce1"></div>
<div class="bounce2"></div>
<div class="bounce3"></div>
</div>
<div class="review-container">
<div class="review-corrector"></div>
<div class="review-github well" style="display:none">
<h5>Commit used:</h5>
<ul>
<li style="display:none"><strong>User:</strong> <code class="review-github-id"></code> <span class="review-github-name">---</span></li>
<li style="display:none"><strong>URL:</strong> <a class="review-github-url" target="_blank">Click here</a></li>
<li style="display:none"><strong>ID:</strong> <code class="review-github-commit_id">---</code></li>
<li style="display:none"><strong>Author:</strong> <span class="review-github-committer_username">---</span></li>
<li style="display:none"><strong>Subject:</strong> <em class="review-github-subject">---</em></li>
<li style="display:none"><strong>Date:</strong> <span class="review-github-datetime">---</span></li>
</ul>
</div>
<div class="review-percentage_down"></div>
<ul class="review-checks list-group sm-gap"></ul>
<div class="review-comment"></div>
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
<div data-role="task936" data-position="5" id="task-num-4">
<div class="panel panel-default task-card " id="task-936">
<span id="user_id" data-id="197885"></span>

<div class="panel-heading panel-heading-actions">
<h3 class="panel-title">
4. It&#39;s not bragging if you can back it up
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
<div class="task_progress_score_bar" data-task-id="936" data-correction-id="7879454">
<div class="task_progress_bar" style="width: 0.0%">
<div class="task_score_bar" style="width: NaN%">
</div>
</div>
<div class="task_progress_score_text">
Score: <span class="task_score_value">0.0%</span> (<span class="task_progress_value">Checks completed: 0.0%</span>)
</div>
</div>

<!-- Task Body -->
<p>Write a function that frees a 2 dimensional grid previously created by your <code>alloc_grid</code> function.</p>

<ul>
<li>Prototype: <code>void free_grid(int **grid, int height);</code></li>
<li>Note that we will compile with your <code>alloc_grid.c</code> file. Make sure it compiles.</li>
</ul>

<pre><code>julien@ubuntu:~/0x0a. malloc, free$ cat 4-main.c
#include &quot;main.h&quot;
#include &lt;stdio.h&gt;
#include &lt;stdlib.h&gt;

/**
* print_grid - prints a grid of integers
* @grid: the address of the two dimensional grid
* @width: width of the grid
* @height: height of the grid
*
* Return: Nothing.
*/
void print_grid(int **grid, int width, int height)
{
int w;
int h;

h = 0;
while (h &lt; height)
{
w = 0;
while (w &lt; width)
{
printf(&quot;%d &quot;, grid[h][w]);
w++;
}
printf(&quot;\n&quot;);
h++;
}   
}

/**
* main - check the code for ALX School students.
*
* Return: Always 0.
*/
int main(void)
{
int **grid;

grid = alloc_grid(6, 4);
if (grid == NULL)
{
return (1);
}
print_grid(grid, 6, 4);
printf(&quot;\n&quot;);
grid[0][3] = 98;
grid[3][4] = 402;
print_grid(grid, 6, 4);
free_grid(grid, 4);
return (0);
}
julien@ubuntu:~/0x0a. malloc, free$ gcc -Wall -pedantic -Werror -Wextra -std=gnu89 4-main.c 3-alloc_grid.c 4-free_grid.c -o f
julien@ubuntu:~/0x0a. malloc, free$ valgrind ./f
==5013== Memcheck, a memory error detector
==5013== Copyright (C) 2002-2015, and GNU GPL&#39;d, by Julian Seward et al.
==5013== Using Valgrind-3.11.0 and LibVEX; rerun with -h for copyright info
==5013== Command: ./f
==5013== 
0 0 0 0 0 0 
0 0 0 0 0 0 
0 0 0 0 0 0 
0 0 0 0 0 0 

0 0 0 98 0 0 
0 0 0 0 0 0 
0 0 0 0 0 0 
0 0 0 0 402 0 
==5013== 
==5013== HEAP SUMMARY:
==5013==     in use at exit: 0 bytes in 0 blocks
==5013==   total heap usage: 6 allocs, 6 frees, 1,248 bytes allocated
==5013== 
==5013== All heap blocks were freed -- no leaks are possible
==5013== 
==5013== For counts of detected and suppressed errors, rerun with: -v
==5013== ERROR SUMMARY: 0 errors from 0 contexts (suppressed: 0 from 0)
julien@ubuntu:~/0x0a. malloc, free$ 
</code></pre>

</div>

<div class="list-group">
<!-- Task URLs -->

<!-- Github information -->
<div class="list-group-item">
<p><strong>Repo:</strong></p>
<ul>
<li>GitHub repository: <code>alx-low_level_programming</code></li>
<li>Directory: <code>0x0B-malloc_free</code></li>
<li>File: <code>4-free_grid.c</code></li>
</ul>
</div>

<!-- Self-paced manual review -->
</div>

<!-- Panel footer - Controls -->
<div class="panel-footer">
<div class="align-items-center d-flex justify-content-between">

<div>
<button class="student_task_done btn btn-default btn-sm no" data-task-id="936">
<span class="no"><i aria-hidden="true" class="fa fa-square-o "></i></span>
<span class="yes"><i aria-hidden="true" class="fa fa-check-square-o "></i></span>
<span class="pending"><i aria-hidden="true" class="fa fa-spinner  fa-pulse"></i></span>
Done<span class="no pending">?</span><span class="yes">!</span>
</button>

<button class="student-task-done-by btn btn-default btn-sm" data-task-id="936" data-batch-id="26" data-toggle="modal" data-target="#task-936-users-done-modal">
Help
</button>
<div class="modal fade users-done-modal" id="task-936-users-done-modal" data-task-id="936" data-batch-id="26">
<div class="modal-dialog">
<div class="modal-content">
<div class="modal-header">
<button type="button" class="close" data-dismiss="modal" aria-label="Close"><span aria-hidden="true">&times;</span></button>
<h4 class="modal-title">Students who are done with "4. It&#39;s not bragging if you can back it up"</h4>
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


<button class="btn btn-default btn-sm check-your-task-936-modal-button" data-task-id="936" data-toggle="modal" data-target="#task-test-correction-936-correction-modal" id="task-num-4-check-code-btn" data-gtm-custom-event-name="task_checker_modal" data-gtm-custom-event-options='{&quot;taskId&quot;:936}'>
Check your code
</button>
<div class="modal fade task_correction_modal student_modal" id="task-test-correction-936-correction-modal">
<div class="modal-dialog">
<div class="modal-content">
<div class="modal-header">
<button type="button" class="close" data-dismiss="modal" aria-label="Close"><span aria-hidden="true">&times;</span></button>
<h4 class="modal-title">Correction of "4. It&#39;s not bragging if you can back it up"</h4>
</div>
<div class="modal-body">
<div class="actions">
<center>
<div class="alert alert-info hidden"></div>

<button name="button" type="submit" class="btn btn-primary correction_request_test_send" data-task-id="936">Start a new test</button>
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
<button data-task-id="936">
<i aria-hidden="true" class="fa fa-info-circle "></i>
</button>
<div class="help-container" data-task-id="936">
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


<button class="btn btn-primary btn-sm task_ask_new_correction " data-task-id="936" data-correction-id="7879454">
Ask for a new correction
<span class="in_progress_info">: in progress...</span>
<span class="error_occurred_info">: an error occurred</span>
</button>

<button class="btn btn-default btn-sm" data-toggle="modal" data-target="#container-specs-modal" data-gtm-custom-event-name="task_sandbox_modal" data-gtm-custom-event-options="{&quot;taskId&quot;:936}"><i aria-hidden="true" class="fa fa-terminal "></i><span>Get a sandbox</span></button>

<button class="btn btn-default btn-sm" data-task-id="936" data-toggle="modal" data-target="#task-qa-review-936-modal" data-gtm-custom-event-name="task_qa_review_modal" data-gtm-custom-event-options='{&quot;taskId&quot;:936}'>
QA Review
</button>
<div class="modal fade task_get_qa_review" id="task-qa-review-936-modal" data-correction-id="7879454" data-task-id="936">
<div class="modal-dialog modal-lg">
<div class="modal-content">
<div class="modal-header">
<button type="button" class="close" data-dismiss="modal" aria-label="Close"><span aria-hidden="true">&times;</span></button>
<h4 class="modal-title">4. It&#39;s not bragging if you can back it up</h4>
</div>
<div class="modal-body">
<div class="spinner gap">
<div class="bounce1"></div>
<div class="bounce2"></div>
<div class="bounce3"></div>
</div>
<div class="review-container">
<div class="review-corrector"></div>
<div class="review-github well" style="display:none">
<h5>Commit used:</h5>
<ul>
<li style="display:none"><strong>User:</strong> <code class="review-github-id"></code> <span class="review-github-name">---</span></li>
<li style="display:none"><strong>URL:</strong> <a class="review-github-url" target="_blank">Click here</a></li>
<li style="display:none"><strong>ID:</strong> <code class="review-github-commit_id">---</code></li>
<li style="display:none"><strong>Author:</strong> <span class="review-github-committer_username">---</span></li>
<li style="display:none"><strong>Subject:</strong> <em class="review-github-subject">---</em></li>
<li style="display:none"><strong>Date:</strong> <span class="review-github-datetime">---</span></li>
</ul>
</div>
<div class="review-percentage_down"></div>
<ul class="review-checks list-group sm-gap"></ul>
<div class="review-comment"></div>
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
<form class="button_to" method="post" action="/projects/222/unlock_optionals"><input id="unlock_optional_btn" class="btn btn-primary btn-block" data-confirm="Are you sure? Make sure you focused on the mandatory tasks first" data-disable-with="Unlocking 2 advanced tasks..." data-gtm-custom-event-name="project_unlock_advanced_tasks" type="submit" value="Done with the mandatory tasks? Unlock 2 advanced tasks now!" /><input type="hidden" name="authenticity_token" value="IMHtShefOaa0asDHc13xAQ2EM3792L0znspMgN7W5SrAbErDzwUqtgf5mBWQIjhXuVCHmI6uUWdv21_zgSQwGA" autocomplete="off" /></form>
</p>




<div class="modal fade" id="container-specs-modal"><div class="modal-dialog modal-lg"><div class="modal-content"><div class="modal-header"><button type="button" class="close" data-dismiss="modal" aria-label="Close"><span aria-hidden="true">&times;</span></button><h4 class="modal-title">Recommended Sandbox</h4></div><div class="modal-body"><div data-react-class="user_containers/ContainerSpecs" data-react-props="{&quot;containerModelName&quot;:&quot;Sandbox&quot;,&quot;containerSpecs&quot;:[{&quot;description&quot;:&quot;\u003cp\u003eBasic Ubuntu 20.04, with vim, emacs, curl, wget and all needed for Foundations\u003c/p\u003e\n&quot;,&quot;id&quot;:39,&quot;name&quot;:&quot;Ubuntu 20.04&quot;,&quot;online&quot;:true,&quot;container&quot;:{&quot;container_id&quot;:null,&quot;id&quot;:239271,&quot;restart_uri&quot;:&quot;/user_containers/239271/restart.json&quot;,&quot;status&quot;:&quot;asleep&quot;,&quot;uri&quot;:&quot;/user_containers/239271.json&quot;,&quot;wake_uri&quot;:&quot;/user_containers/239271/wake.json&quot;,&quot;webterm_uri&quot;:&quot;/user_containers/239271/webterm&quot;,&quot;host&quot;:null,&quot;password&quot;:&quot;2deaf74c415af9350d02&quot;,&quot;ports&quot;:{&quot;8080&quot;:56917,&quot;3306&quot;:56922,&quot;443&quot;:56924,&quot;5000&quot;:56920,&quot;5001&quot;:56919,&quot;8000&quot;:56918,&quot;22&quot;:56926,&quot;3000&quot;:56923,&quot;4000&quot;:56921,&quot;80&quot;:56925}}}],&quot;containersLimit&quot;:2,&quot;csrfToken&quot;:&quot;Y4cc_mOV0YB_i8oiOv8b9rW0WJSfyX0SUqkhInKW4HOLVFkoKV1Yv06RO-1TXPsEuIub5NZWbI3iYwmJABJRJw&quot;,&quot;startStatusURI&quot;:&quot;/user_containers/start_status.json&quot;,&quot;startURI&quot;:&quot;/user_containers/start.json&quot;}" data-react-cache-id="user_containers/ContainerSpecs-0"></div></div></div></div></div>

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
