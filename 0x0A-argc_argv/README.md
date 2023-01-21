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


<title>Project: 0x0A. C - argc, argv | ALX Africa Intranet</title>

<link rel="stylesheet" href="https://use.typekit.net/xgz4ilr.css">
<link rel="stylesheet" media="all" href="/assets/application_alx-bd8f82c7d5afa064449a69a1a91b6daef7bdb1c71c00f2646d99a16e5040963a.css" />
<script src="https://www.gstatic.com/charts/loader.js"></script>
<script src="/assets/application-fb2ab0247cdaae2347e87bac130aa052747dadacfa429138002d69271946027f.js"></script>
<link rel="shortcut icon" type="image/x-icon" href="/favicon_alx.ico" />
<meta name="csrf-param" content="authenticity_token" />
<meta name="csrf-token" content="4-L5xVdMLMqWShu6h8EbmtNXJGBmIxh3oYA_fwjcGvgLMbwTHYSl9adQ6nXuYvto3mjnEC-8CegRShfUelirrA" />

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
<div class="inner" style="background-image: url('https://s3.amazonaws.com/alx-intranet.hbtn.io/users/photos/000/197/885/thumb/joker.jpg?X-Amz-Algorithm=AWS4-HMAC-SHA256&amp;X-Amz-Credential=AKIARDDGGGOUSBVO6H7D%2F20230121%2Fus-east-1%2Fs3%2Faws4_request&amp;X-Amz-Date=20230121T060951Z&amp;X-Amz-Expires=600&amp;X-Amz-SignedHeaders=host&amp;X-Amz-Signature=5a51aef829bbc3e78fa300cb6a437a2850476157bb8486411abb7d97e6a13f29')"></div>
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
<div class="inner" style="background-image: url('https://s3.amazonaws.com/alx-intranet.hbtn.io/users/photos/000/197/885/thumb/joker.jpg?X-Amz-Algorithm=AWS4-HMAC-SHA256&amp;X-Amz-Credential=AKIARDDGGGOUSBVO6H7D%2F20230121%2Fus-east-1%2Fs3%2Faws4_request&amp;X-Amz-Date=20230121T060951Z&amp;X-Amz-Expires=600&amp;X-Amz-SignedHeaders=host&amp;X-Amz-Signature=5a51aef829bbc3e78fa300cb6a437a2850476157bb8486411abb7d97e6a13f29')"></div>
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

<h1 class="gap">0x0A. C - argc, argv</h1>

<div data-react-class="tags/Tags" data-react-props="{&quot;tags&quot;:[{&quot;id&quot;:7,&quot;value&quot;:&quot;C&quot;,&quot;author_id&quot;:null,&quot;created_at&quot;:&quot;2022-06-16T01:59:38.000Z&quot;,&quot;updated_at&quot;:&quot;2022-06-16T01:59:38.000Z&quot;}]}" data-react-cache-id="tags/Tags-0"></div>

<div data-react-class="projects/ProjectMetadata" data-react-props="{&quot;metadata&quot;:{&quot;author&quot;:&quot;Julien Barbier&quot;,&quot;weight&quot;:1,&quot;correction&quot;:{&quot;released&quot;:true,&quot;requires_auto_correction&quot;:true,&quot;requires_manual_correction&quot;:false},&quot;bpi&quot;:{&quot;current&quot;:false,&quot;in_second_deadline&quot;:false,&quot;starts_at&quot;:&quot;2023-01-06T06:00:00.000+03:00&quot;,&quot;ends_at&quot;:&quot;2023-01-07T06:00:00.000+03:00&quot;,&quot;second_deadline_at&quot;:&quot;2023-01-12T06:00:00.000+03:00&quot;}}}" data-react-cache-id="projects/ProjectMetadata-0"></div>

<div class="sm-gap clean well">
<h4>In a nutshell&hellip;</h4>
<ul>


<li>
<strong>Auto QA review:</strong>
0.0/37 mandatory
&
0.0/9 optional
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







<div id="project_id" style="display: none" data-project-id="221"></div>







<div class="panel panel-default" id="project-description">
<div class="panel-body">
<h2>Resources</h2>

<p><strong>Read or watch</strong>:</p>

<ul>
<li><a href="/rltoken/Jip_nI4tv2ybQZ-jV3fqJg" title="Arguments to main" target="_blank">Arguments to main</a> </li>
<li><a href="/rltoken/31aLwv8qsXuiUZrOk9Djqg" title="argc and argv" target="_blank">argc and argv</a> </li>
<li><a href="/rltoken/A0pzqslB6Z3Y3OV3hJQ6Tw" title="What does argc and argv mean?" target="_blank">What does argc and argv mean?</a> </li>
<li><a href="/rltoken/MkOUE1ndq1UAx9Erk-AVbg" title="how to compile with unused variables" target="_blank">how to compile with unused variables</a> </li>
</ul>

<h2>Learning Objectives</h2>

<p>At the end of this project, you are expected to be able to <a href="/rltoken/DBgGt1BaQ75AkikI88WbEw" title="explain to anyone" target="_blank">explain to anyone</a>, <strong>without the help of Google</strong>:</p>

<h3>General</h3>

<ul>
<li>How to use arguments passed to your program</li>
<li>What are two prototypes of <code>main</code> that you know of, and in which case do you use one or the other</li>
<li>How to use <code>__attribute__((unused))</code> or <code>(void)</code> to compile functions with unused variables or parameters</li>
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
<li>The prototypes of all your functions and the prototype of the function <code>_putchar</code> should be included in your header file called <code>main.h</code></li>
<li>Don&rsquo;t forget to push your header file</li>
<li>You are allowed to use the standard library</li>
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
<div class="quiz_question_item_container" data-role="quiz_question470" data-position="3">
<div class=" clearfix" id="quiz_question-470">

<h4 class="quiz_question">

Question #0
</h4>

<!-- Quiz question Body -->
<p>What is <code>argv[0]</code></p>


<!-- Quiz question Answers -->
<ul class="quiz_question_answers" data-question-id="470">
<li class="">

<input type="radio" name="470" id="470-1507175561038" value="1507175561038" data-quiz-answer-id="1507175561038" data-quiz-question-id="470" disabled="disabled" />
<label for="470-1507175561038"><p>The first command line argument</p>
</label>
</li>

<li class="">

<input type="radio" name="470" id="470-1507175524018" value="1507175524018" data-quiz-answer-id="1507175524018" data-quiz-question-id="470" disabled="disabled" />
<label for="470-1507175524018"><p>NULL</p>
</label>
</li>

<li class="">

<input type="radio" name="470" id="470-1507175574047" value="1507175574047" data-quiz-answer-id="1507175574047" data-quiz-question-id="470" disabled="disabled" checked="checked" />
<label for="470-1507175574047"><p>The program name</p>
</label>
</li>

<li class="">

<input type="radio" name="470" id="470-1507175528719" value="1507175528719" data-quiz-answer-id="1507175528719" data-quiz-question-id="470" disabled="disabled" />
<label for="470-1507175528719"><p>It does not always exist</p>
</label>
</li>

</ul>

<!-- Quiz question Tips -->

</div>

</div>
<div class="quiz_question_item_container" data-role="quiz_question471" data-position="4">
<div class=" clearfix" id="quiz_question-471">

<h4 class="quiz_question">

Question #1
</h4>

<!-- Quiz question Body -->
<p>What is <code>argv[argc]</code>?</p>


<!-- Quiz question Answers -->
<ul class="quiz_question_answers" data-question-id="471">
<li class="">

<input type="radio" name="471" id="471-1507175625478" value="1507175625478" data-quiz-answer-id="1507175625478" data-quiz-question-id="471" disabled="disabled" />
<label for="471-1507175625478"><p>The last command line argument</p>
</label>
</li>

<li class="">

<input type="radio" name="471" id="471-1507175589777" value="1507175589777" data-quiz-answer-id="1507175589777" data-quiz-question-id="471" disabled="disabled" checked="checked" />
<label for="471-1507175589777"><p>NULL</p>
</label>
</li>

<li class="">

<input type="radio" name="471" id="471-1507175593303" value="1507175593303" data-quiz-answer-id="1507175593303" data-quiz-question-id="471" disabled="disabled" />
<label for="471-1507175593303"><p>It does not always exist</p>
</label>
</li>

<li class="">

<input type="radio" name="471" id="471-1507175615614" value="1507175615614" data-quiz-answer-id="1507175615614" data-quiz-question-id="471" disabled="disabled" />
<label for="471-1507175615614"><p>The program name</p>
</label>
</li>

<li class="">

<input type="radio" name="471" id="471-1507175603761" value="1507175603761" data-quiz-answer-id="1507175603761" data-quiz-question-id="471" disabled="disabled" />
<label for="471-1507175603761"><p>The first command line argument</p>
</label>
</li>

</ul>

<!-- Quiz question Tips -->

</div>

</div>
<div class="quiz_question_item_container" data-role="quiz_question474" data-position="7">
<div class=" clearfix" id="quiz_question-474">

<h4 class="quiz_question">

Question #2
</h4>

<!-- Quiz question Body -->
<p>In the following command, what is <code>argv[2]</code>?</p>

<pre><code>$ ./argv &quot;My School is fun&quot;
</code></pre>


<!-- Quiz question Answers -->
<ul class="quiz_question_answers" data-question-id="474">
<li class="">

<input type="radio" name="474" id="474-1507175920647" value="1507175920647" data-quiz-answer-id="1507175920647" data-quiz-question-id="474" disabled="disabled" />
<label for="474-1507175920647"><p>My School is fun</p>
</label>
</li>

<li class="">

<input type="radio" name="474" id="474-1507175893870" value="1507175893870" data-quiz-answer-id="1507175893870" data-quiz-question-id="474" disabled="disabled" />
<label for="474-1507175893870"><p>./argv</p>
</label>
</li>

<li class="">

<input type="radio" name="474" id="474-1507175916441" value="1507175916441" data-quiz-answer-id="1507175916441" data-quiz-question-id="474" disabled="disabled" />
<label for="474-1507175916441"><p>is fun</p>
</label>
</li>

<li class="">

<input type="radio" name="474" id="474-1507175890959" value="1507175890959" data-quiz-answer-id="1507175890959" data-quiz-question-id="474" disabled="disabled" checked="checked" />
<label for="474-1507175890959"><p>NULL</p>
</label>
</li>

<li class="">

<input type="radio" name="474" id="474-1507175905639" value="1507175905639" data-quiz-answer-id="1507175905639" data-quiz-question-id="474" disabled="disabled" />
<label for="474-1507175905639"><p>My School</p>
</label>
</li>

<li class="">

<input type="radio" name="474" id="474-1507175902812" value="1507175902812" data-quiz-answer-id="1507175902812" data-quiz-question-id="474" disabled="disabled" />
<label for="474-1507175902812"><p>School</p>
</label>
</li>

<li class="">

<input type="radio" name="474" id="474-1507175898114" value="1507175898114" data-quiz-answer-id="1507175898114" data-quiz-question-id="474" disabled="disabled" />
<label for="474-1507175898114"><p>My</p>
</label>
</li>

<li class="">

<input type="radio" name="474" id="474-1507175912802" value="1507175912802" data-quiz-answer-id="1507175912802" data-quiz-question-id="474" disabled="disabled" />
<label for="474-1507175912802"><p>fun</p>
</label>
</li>

<li class="">

<input type="radio" name="474" id="474-1507175910212" value="1507175910212" data-quiz-answer-id="1507175910212" data-quiz-question-id="474" disabled="disabled" />
<label for="474-1507175910212"><p>is</p>
</label>
</li>

</ul>

<!-- Quiz question Tips -->

</div>

</div>
<div class="quiz_question_item_container" data-role="quiz_question468" data-position="1">
<div class=" clearfix" id="quiz_question-468">

<h4 class="quiz_question">

Question #3
</h4>

<!-- Quiz question Body -->
<p>What is <code>argc</code>?</p>


<!-- Quiz question Answers -->
<ul class="quiz_question_answers" data-question-id="468">
<li class="">

<input type="checkbox" name="468" id="468-1507175378020" value="1507175378020" data-quiz-answer-id="1507175378020" data-quiz-question-id="468" disabled="disabled" checked="checked" />
<label for="468-1507175378020"><p>The size of the <code>argv</code> array</p>
</label>
</li>

<li class="">

<input type="checkbox" name="468" id="468-1507175286306" value="1507175286306" data-quiz-answer-id="1507175286306" data-quiz-question-id="468" disabled="disabled" checked="checked" />
<label for="468-1507175286306"><p>The number of command line arguments</p>
</label>
</li>

<li class="">

<input type="checkbox" name="468" id="468-1507175423200" value="1507175423200" data-quiz-answer-id="1507175423200" data-quiz-question-id="468" disabled="disabled" />
<label for="468-1507175423200"><p>The length of the first command line argument</p>
</label>
</li>

<li class="">

<input type="checkbox" name="468" id="468-1507175317154" value="1507175317154" data-quiz-answer-id="1507175317154" data-quiz-question-id="468" disabled="disabled" />
<label for="468-1507175317154"><p>A flag set to 1 when command line arguments are present</p>
</label>
</li>

</ul>

<!-- Quiz question Tips -->

</div>

</div>
<div class="quiz_question_item_container" data-role="quiz_question472" data-position="5">
<div class=" clearfix" id="quiz_question-472">

<h4 class="quiz_question">

Question #4
</h4>

<!-- Quiz question Body -->
<p>In the following command, what is <code>argv[2]</code>?</p>

<pre><code>$ ./argv My School is fun
</code></pre>


<!-- Quiz question Answers -->
<ul class="quiz_question_answers" data-question-id="472">
<li class="">

<input type="radio" name="472" id="472-1507175884982" value="1507175884982" data-quiz-answer-id="1507175884982" data-quiz-question-id="472" disabled="disabled" />
<label for="472-1507175884982"><p>My School is fun</p>
</label>
</li>

<li class="">

<input type="radio" name="472" id="472-1507175789006" value="1507175789006" data-quiz-answer-id="1507175789006" data-quiz-question-id="472" disabled="disabled" />
<label for="472-1507175789006"><p>./argv</p>
</label>
</li>

<li class="">

<input type="radio" name="472" id="472-1507175814767" value="1507175814767" data-quiz-answer-id="1507175814767" data-quiz-question-id="472" disabled="disabled" />
<label for="472-1507175814767"><p>is fun</p>
</label>
</li>

<li class="">

<input type="radio" name="472" id="472-1507175785696" value="1507175785696" data-quiz-answer-id="1507175785696" data-quiz-question-id="472" disabled="disabled" />
<label for="472-1507175785696"><p>NULL</p>
</label>
</li>

<li class="">

<input type="radio" name="472" id="472-1507175802976" value="1507175802976" data-quiz-answer-id="1507175802976" data-quiz-question-id="472" disabled="disabled" />
<label for="472-1507175802976"><p>My School</p>
</label>
</li>

<li class="">

<input type="radio" name="472" id="472-1507175800225" value="1507175800225" data-quiz-answer-id="1507175800225" data-quiz-question-id="472" disabled="disabled" checked="checked" />
<label for="472-1507175800225"><p>School</p>
</label>
</li>

<li class="">

<input type="radio" name="472" id="472-1507175794545" value="1507175794545" data-quiz-answer-id="1507175794545" data-quiz-question-id="472" disabled="disabled" />
<label for="472-1507175794545"><p>My</p>
</label>
</li>

<li class="">

<input type="radio" name="472" id="472-1507175811296" value="1507175811296" data-quiz-answer-id="1507175811296" data-quiz-question-id="472" disabled="disabled" />
<label for="472-1507175811296"><p>fun</p>
</label>
</li>

<li class="">

<input type="radio" name="472" id="472-1507175807832" value="1507175807832" data-quiz-answer-id="1507175807832" data-quiz-question-id="472" disabled="disabled" />
<label for="472-1507175807832"><p>is</p>
</label>
</li>

</ul>

<!-- Quiz question Tips -->

</div>

</div>
<div class="quiz_question_item_container" data-role="quiz_question473" data-position="6">
<div class=" clearfix" id="quiz_question-473">

<h4 class="quiz_question">

Question #5
</h4>

<!-- Quiz question Body -->
<p>In the following command, what is <code>argv[2]</code>?</p>

<pre><code>$ ./argv &quot;My School&quot; &quot;is fun&quot;
</code></pre>


<!-- Quiz question Answers -->
<ul class="quiz_question_answers" data-question-id="473">
<li class="">

<input type="radio" name="473" id="473-1507175874059" value="1507175874059" data-quiz-answer-id="1507175874059" data-quiz-question-id="473" disabled="disabled" />
<label for="473-1507175874059"><p>My School is fun</p>
</label>
</li>

<li class="">

<input type="radio" name="473" id="473-1507175833714" value="1507175833714" data-quiz-answer-id="1507175833714" data-quiz-question-id="473" disabled="disabled" />
<label for="473-1507175833714"><p>./argv</p>
</label>
</li>

<li class="">

<input type="radio" name="473" id="473-1507175856280" value="1507175856280" data-quiz-answer-id="1507175856280" data-quiz-question-id="473" disabled="disabled" checked="checked" />
<label for="473-1507175856280"><p>is fun</p>
</label>
</li>

<li class="">

<input type="radio" name="473" id="473-1507175830478" value="1507175830478" data-quiz-answer-id="1507175830478" data-quiz-question-id="473" disabled="disabled" />
<label for="473-1507175830478"><p>NULL</p>
</label>
</li>

<li class="">

<input type="radio" name="473" id="473-1507175846567" value="1507175846567" data-quiz-answer-id="1507175846567" data-quiz-question-id="473" disabled="disabled" />
<label for="473-1507175846567"><p>My School</p>
</label>
</li>

<li class="">

<input type="radio" name="473" id="473-1507175843633" value="1507175843633" data-quiz-answer-id="1507175843633" data-quiz-question-id="473" disabled="disabled" />
<label for="473-1507175843633"><p>School</p>
</label>
</li>

<li class="">

<input type="radio" name="473" id="473-1507175838392" value="1507175838392" data-quiz-answer-id="1507175838392" data-quiz-question-id="473" disabled="disabled" />
<label for="473-1507175838392"><p>My</p>
</label>
</li>

<li class="">

<input type="radio" name="473" id="473-1507175853291" value="1507175853291" data-quiz-answer-id="1507175853291" data-quiz-question-id="473" disabled="disabled" />
<label for="473-1507175853291"><p>fun</p>
</label>
</li>

<li class="">

<input type="radio" name="473" id="473-1507175850976" value="1507175850976" data-quiz-answer-id="1507175850976" data-quiz-question-id="473" disabled="disabled" />
<label for="473-1507175850976"><p>is</p>
</label>
</li>

</ul>

<!-- Quiz question Tips -->

</div>

</div>
<div class="quiz_question_item_container" data-role="quiz_question469" data-position="2">
<div class=" clearfix" id="quiz_question-469">

<h4 class="quiz_question">

Question #6
</h4>

<!-- Quiz question Body -->
<p>What is <code>argv</code>?</p>


<!-- Quiz question Answers -->
<ul class="quiz_question_answers" data-question-id="469">
<li class="">

<input type="checkbox" name="469" id="469-1507175446133" value="1507175446133" data-quiz-answer-id="1507175446133" data-quiz-question-id="469" disabled="disabled" />
<label for="469-1507175446133"><p>An array containing the program compilation flags</p>
</label>
</li>

<li class="">

<input type="checkbox" name="469" id="469-1507175498456" value="1507175498456" data-quiz-answer-id="1507175498456" data-quiz-question-id="469" disabled="disabled" checked="checked" />
<label for="469-1507175498456"><p>An array of size <code>argc</code></p>
</label>
</li>

<li class="">

<input type="checkbox" name="469" id="469-1507175483471" value="1507175483471" data-quiz-answer-id="1507175483471" data-quiz-question-id="469" disabled="disabled" checked="checked" />
<label for="469-1507175483471"><p>An array containing the program command line arguments</p>
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

<div data-role="task926" data-position="1" id="task-num-0">
<div class="panel panel-default task-card " id="task-926">
<span id="user_id" data-id="197885"></span>

<div class="panel-heading panel-heading-actions">
<h3 class="panel-title">
0. It ain&#39;t what they call you, it&#39;s what you answer to
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
<div class="task_progress_score_bar" data-task-id="926" data-correction-id="7871676">
<div class="task_progress_bar" style="width: 0.0%">
<div class="task_score_bar" style="width: NaN%">
</div>
</div>
<div class="task_progress_score_text">
Score: <span class="task_score_value">0.0%</span> (<span class="task_progress_value">Checks completed: 0.0%</span>)
</div>
</div>

<!-- Task Body -->
<p>Write a program that prints its name, followed by a new line.</p>

<ul>
<li>If you rename the program, it will print the new name, without having to compile it again</li>
<li>You should not remove the path before the name of the program</li>
</ul>

<pre><code>julien@ubuntu:~/0x0A. argc, argv$ gcc -Wall -pedantic -Werror -Wextra -std=gnu89 0-whatsmyname.c -o mynameis
julien@ubuntu:~/0x0A. argc, argv$ ./mynameis 
./mynameis
julien@ubuntu:~/0x0A. argc, argv$ mv mynameis mynewnameis
julien@ubuntu:~/0x0A. argc, argv$ ./mynewnameis 
./mynewnameis
julien@ubuntu:~/0x0A. argc, argv$ 
</code></pre>

</div>

<div class="list-group">
<!-- Task URLs -->

<!-- Github information -->
<div class="list-group-item">
<p><strong>Repo:</strong></p>
<ul>
<li>GitHub repository: <code>alx-low_level_programming</code></li>
<li>Directory: <code>0x0A-argc_argv</code></li>
<li>File: <code>0-whatsmyname.c</code></li>
</ul>
</div>

<!-- Self-paced manual review -->
</div>

<!-- Panel footer - Controls -->
<div class="panel-footer">
<div class="align-items-center d-flex justify-content-between">

<div>
<button class="student_task_done btn btn-default btn-sm no" data-task-id="926">
<span class="no"><i aria-hidden="true" class="fa fa-square-o "></i></span>
<span class="yes"><i aria-hidden="true" class="fa fa-check-square-o "></i></span>
<span class="pending"><i aria-hidden="true" class="fa fa-spinner  fa-pulse"></i></span>
Done<span class="no pending">?</span><span class="yes">!</span>
</button>

<button class="student-task-done-by btn btn-default btn-sm" data-task-id="926" data-batch-id="26" data-toggle="modal" data-target="#task-926-users-done-modal">
Help
</button>
<div class="modal fade users-done-modal" id="task-926-users-done-modal" data-task-id="926" data-batch-id="26">
<div class="modal-dialog">
<div class="modal-content">
<div class="modal-header">
<button type="button" class="close" data-dismiss="modal" aria-label="Close"><span aria-hidden="true">&times;</span></button>
<h4 class="modal-title">Students who are done with "0. It ain&#39;t what they call you, it&#39;s what you answer to"</h4>
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


<button class="btn btn-default btn-sm check-your-task-926-modal-button" data-task-id="926" data-toggle="modal" data-target="#task-test-correction-926-correction-modal" id="task-num-0-check-code-btn" data-gtm-custom-event-name="task_checker_modal" data-gtm-custom-event-options='{&quot;taskId&quot;:926}'>
Check your code
</button>
<div class="modal fade task_correction_modal student_modal" id="task-test-correction-926-correction-modal">
<div class="modal-dialog">
<div class="modal-content">
<div class="modal-header">
<button type="button" class="close" data-dismiss="modal" aria-label="Close"><span aria-hidden="true">&times;</span></button>
<h4 class="modal-title">Correction of "0. It ain&#39;t what they call you, it&#39;s what you answer to"</h4>
</div>
<div class="modal-body">
<div class="actions">
<center>
<div class="alert alert-info hidden"></div>

<button name="button" type="submit" class="btn btn-primary correction_request_test_send" data-task-id="926">Start a new test</button>
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
<button data-task-id="926">
<i aria-hidden="true" class="fa fa-info-circle "></i>
</button>
<div class="help-container" data-task-id="926">
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


<button class="btn btn-primary btn-sm task_ask_new_correction " data-task-id="926" data-correction-id="7871676">
Ask for a new correction
<span class="in_progress_info">: in progress...</span>
<span class="error_occurred_info">: an error occurred</span>
</button>

<button class="btn btn-default btn-sm" data-toggle="modal" data-target="#container-specs-modal" data-gtm-custom-event-name="task_sandbox_modal" data-gtm-custom-event-options="{&quot;taskId&quot;:926}"><i aria-hidden="true" class="fa fa-terminal "></i><span>Get a sandbox</span></button>

<button class="btn btn-default btn-sm" data-task-id="926" data-toggle="modal" data-target="#task-qa-review-926-modal" data-gtm-custom-event-name="task_qa_review_modal" data-gtm-custom-event-options='{&quot;taskId&quot;:926}'>
QA Review
</button>
<div class="modal fade task_get_qa_review" id="task-qa-review-926-modal" data-correction-id="7871676" data-task-id="926">
<div class="modal-dialog modal-lg">
<div class="modal-content">
<div class="modal-header">
<button type="button" class="close" data-dismiss="modal" aria-label="Close"><span aria-hidden="true">&times;</span></button>
<h4 class="modal-title">0. It ain&#39;t what they call you, it&#39;s what you answer to</h4>
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
<div data-role="task927" data-position="2" id="task-num-1">
<div class="panel panel-default task-card " id="task-927">
<span id="user_id" data-id="197885"></span>

<div class="panel-heading panel-heading-actions">
<h3 class="panel-title">
1. Silence is argument carried out by other means
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
<div class="task_progress_score_bar" data-task-id="927" data-correction-id="7871676">
<div class="task_progress_bar" style="width: 0.0%">
<div class="task_score_bar" style="width: NaN%">
</div>
</div>
<div class="task_progress_score_text">
Score: <span class="task_score_value">0.0%</span> (<span class="task_progress_value">Checks completed: 0.0%</span>)
</div>
</div>

<!-- Task Body -->
<p>Write a program that prints the number of arguments passed into it.</p>

<ul>
<li>Your program should print a number, followed by a new line</li>
</ul>

<pre><code>julien@ubuntu:~/0x0A. argc, argv$ gcc -Wall -pedantic -Werror -Wextra -std=gnu89 1-args.c -o nargs
julien@ubuntu:~/0x0A. argc, argv$ ./nargs 
0
julien@ubuntu:~/0x0A. argc, argv$ ./nargs hello
1
julien@ubuntu:~/0x0A. argc, argv$ ./nargs &quot;hello, world&quot;
1
julien@ubuntu:~/0x0A. argc, argv$ ./nargs hello, world
2
julien@ubuntu:~/0x0A. argc, argv$ 
</code></pre>

</div>

<div class="list-group">
<!-- Task URLs -->

<!-- Github information -->
<div class="list-group-item">
<p><strong>Repo:</strong></p>
<ul>
<li>GitHub repository: <code>alx-low_level_programming</code></li>
<li>Directory: <code>0x0A-argc_argv</code></li>
<li>File: <code>1-args.c</code></li>
</ul>
</div>

<!-- Self-paced manual review -->
</div>

<!-- Panel footer - Controls -->
<div class="panel-footer">
<div class="align-items-center d-flex justify-content-between">

<div>
<button class="student_task_done btn btn-default btn-sm no" data-task-id="927">
<span class="no"><i aria-hidden="true" class="fa fa-square-o "></i></span>
<span class="yes"><i aria-hidden="true" class="fa fa-check-square-o "></i></span>
<span class="pending"><i aria-hidden="true" class="fa fa-spinner  fa-pulse"></i></span>
Done<span class="no pending">?</span><span class="yes">!</span>
</button>

<button class="student-task-done-by btn btn-default btn-sm" data-task-id="927" data-batch-id="26" data-toggle="modal" data-target="#task-927-users-done-modal">
Help
</button>
<div class="modal fade users-done-modal" id="task-927-users-done-modal" data-task-id="927" data-batch-id="26">
<div class="modal-dialog">
<div class="modal-content">
<div class="modal-header">
<button type="button" class="close" data-dismiss="modal" aria-label="Close"><span aria-hidden="true">&times;</span></button>
<h4 class="modal-title">Students who are done with "1. Silence is argument carried out by other means"</h4>
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


<button class="btn btn-default btn-sm check-your-task-927-modal-button" data-task-id="927" data-toggle="modal" data-target="#task-test-correction-927-correction-modal" id="task-num-1-check-code-btn" data-gtm-custom-event-name="task_checker_modal" data-gtm-custom-event-options='{&quot;taskId&quot;:927}'>
Check your code
</button>
<div class="modal fade task_correction_modal student_modal" id="task-test-correction-927-correction-modal">
<div class="modal-dialog">
<div class="modal-content">
<div class="modal-header">
<button type="button" class="close" data-dismiss="modal" aria-label="Close"><span aria-hidden="true">&times;</span></button>
<h4 class="modal-title">Correction of "1. Silence is argument carried out by other means"</h4>
</div>
<div class="modal-body">
<div class="actions">
<center>
<div class="alert alert-info hidden"></div>

<button name="button" type="submit" class="btn btn-primary correction_request_test_send" data-task-id="927">Start a new test</button>
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
<button data-task-id="927">
<i aria-hidden="true" class="fa fa-info-circle "></i>
</button>
<div class="help-container" data-task-id="927">
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


<button class="btn btn-primary btn-sm task_ask_new_correction " data-task-id="927" data-correction-id="7871676">
Ask for a new correction
<span class="in_progress_info">: in progress...</span>
<span class="error_occurred_info">: an error occurred</span>
</button>

<button class="btn btn-default btn-sm" data-toggle="modal" data-target="#container-specs-modal" data-gtm-custom-event-name="task_sandbox_modal" data-gtm-custom-event-options="{&quot;taskId&quot;:927}"><i aria-hidden="true" class="fa fa-terminal "></i><span>Get a sandbox</span></button>

<button class="btn btn-default btn-sm" data-task-id="927" data-toggle="modal" data-target="#task-qa-review-927-modal" data-gtm-custom-event-name="task_qa_review_modal" data-gtm-custom-event-options='{&quot;taskId&quot;:927}'>
QA Review
</button>
<div class="modal fade task_get_qa_review" id="task-qa-review-927-modal" data-correction-id="7871676" data-task-id="927">
<div class="modal-dialog modal-lg">
<div class="modal-content">
<div class="modal-header">
<button type="button" class="close" data-dismiss="modal" aria-label="Close"><span aria-hidden="true">&times;</span></button>
<h4 class="modal-title">1. Silence is argument carried out by other means</h4>
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
<div data-role="task928" data-position="3" id="task-num-2">
<div class="panel panel-default task-card " id="task-928">
<span id="user_id" data-id="197885"></span>

<div class="panel-heading panel-heading-actions">
<h3 class="panel-title">
2. The best argument against democracy is a five-minute conversation with the average voter
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
<div class="task_progress_score_bar" data-task-id="928" data-correction-id="7871676">
<div class="task_progress_bar" style="width: 0.0%">
<div class="task_score_bar" style="width: NaN%">
</div>
</div>
<div class="task_progress_score_text">
Score: <span class="task_score_value">0.0%</span> (<span class="task_progress_value">Checks completed: 0.0%</span>)
</div>
</div>

<!-- Task Body -->
<p>Write a program that prints all arguments it receives.</p>

<ul>
<li>All arguments should be printed, including the first one</li>
<li>Only print one argument per line, ending with a new line</li>
</ul>

<pre><code>julien@ubuntu:~/0x0A. argc, argv$ gcc -Wall -pedantic -Werror -Wextra -std=gnu89 2-args.c -o args
julien@ubuntu:~/0x0A. argc, argv$ ./args 
./args
julien@ubuntu:~/0x0A. argc, argv$ ./args You can do anything, but not everything.
./args
You
can
do
anything,
but
not
everything.
julien@ubuntu:~/0x0A. argc, argv$ 
</code></pre>

</div>

<div class="list-group">
<!-- Task URLs -->

<!-- Github information -->
<div class="list-group-item">
<p><strong>Repo:</strong></p>
<ul>
<li>GitHub repository: <code>alx-low_level_programming</code></li>
<li>Directory: <code>0x0A-argc_argv</code></li>
<li>File: <code>2-args.c</code></li>
</ul>
</div>

<!-- Self-paced manual review -->
</div>

<!-- Panel footer - Controls -->
<div class="panel-footer">
<div class="align-items-center d-flex justify-content-between">

<div>
<button class="student_task_done btn btn-default btn-sm no" data-task-id="928">
<span class="no"><i aria-hidden="true" class="fa fa-square-o "></i></span>
<span class="yes"><i aria-hidden="true" class="fa fa-check-square-o "></i></span>
<span class="pending"><i aria-hidden="true" class="fa fa-spinner  fa-pulse"></i></span>
Done<span class="no pending">?</span><span class="yes">!</span>
</button>

<button class="student-task-done-by btn btn-default btn-sm" data-task-id="928" data-batch-id="26" data-toggle="modal" data-target="#task-928-users-done-modal">
Help
</button>
<div class="modal fade users-done-modal" id="task-928-users-done-modal" data-task-id="928" data-batch-id="26">
<div class="modal-dialog">
<div class="modal-content">
<div class="modal-header">
<button type="button" class="close" data-dismiss="modal" aria-label="Close"><span aria-hidden="true">&times;</span></button>
<h4 class="modal-title">Students who are done with "2. The best argument against democracy is a five-minute conversation with the average voter"</h4>
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


<button class="btn btn-default btn-sm check-your-task-928-modal-button" data-task-id="928" data-toggle="modal" data-target="#task-test-correction-928-correction-modal" id="task-num-2-check-code-btn" data-gtm-custom-event-name="task_checker_modal" data-gtm-custom-event-options='{&quot;taskId&quot;:928}'>
Check your code
</button>
<div class="modal fade task_correction_modal student_modal" id="task-test-correction-928-correction-modal">
<div class="modal-dialog">
<div class="modal-content">
<div class="modal-header">
<button type="button" class="close" data-dismiss="modal" aria-label="Close"><span aria-hidden="true">&times;</span></button>
<h4 class="modal-title">Correction of "2. The best argument against democracy is a five-minute conversation with the average voter"</h4>
</div>
<div class="modal-body">
<div class="actions">
<center>
<div class="alert alert-info hidden"></div>

<button name="button" type="submit" class="btn btn-primary correction_request_test_send" data-task-id="928">Start a new test</button>
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
<button data-task-id="928">
<i aria-hidden="true" class="fa fa-info-circle "></i>
</button>
<div class="help-container" data-task-id="928">
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


<button class="btn btn-primary btn-sm task_ask_new_correction " data-task-id="928" data-correction-id="7871676">
Ask for a new correction
<span class="in_progress_info">: in progress...</span>
<span class="error_occurred_info">: an error occurred</span>
</button>

<button class="btn btn-default btn-sm" data-toggle="modal" data-target="#container-specs-modal" data-gtm-custom-event-name="task_sandbox_modal" data-gtm-custom-event-options="{&quot;taskId&quot;:928}"><i aria-hidden="true" class="fa fa-terminal "></i><span>Get a sandbox</span></button>

<button class="btn btn-default btn-sm" data-task-id="928" data-toggle="modal" data-target="#task-qa-review-928-modal" data-gtm-custom-event-name="task_qa_review_modal" data-gtm-custom-event-options='{&quot;taskId&quot;:928}'>
QA Review
</button>
<div class="modal fade task_get_qa_review" id="task-qa-review-928-modal" data-correction-id="7871676" data-task-id="928">
<div class="modal-dialog modal-lg">
<div class="modal-content">
<div class="modal-header">
<button type="button" class="close" data-dismiss="modal" aria-label="Close"><span aria-hidden="true">&times;</span></button>
<h4 class="modal-title">2. The best argument against democracy is a five-minute conversation with the average voter</h4>
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
<div data-role="task929" data-position="4" id="task-num-3">
<div class="panel panel-default task-card " id="task-929">
<span id="user_id" data-id="197885"></span>

<div class="panel-heading panel-heading-actions">
<h3 class="panel-title">
3. Neither irony nor sarcasm is argument
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
<div class="task_progress_score_bar" data-task-id="929" data-correction-id="7871676">
<div class="task_progress_bar" style="width: 0.0%">
<div class="task_score_bar" style="width: NaN%">
</div>
</div>
<div class="task_progress_score_text">
Score: <span class="task_score_value">0.0%</span> (<span class="task_progress_value">Checks completed: 0.0%</span>)
</div>
</div>

<!-- Task Body -->
<p>Write a program that multiplies two numbers.</p>

<ul>
<li>Your program should print the result of the multiplication, followed by a new line</li>
<li>You can assume that the two numbers and result of the multiplication can be stored in an integer</li>
<li>If the program does not receive two arguments, your program should print <code>Error</code>, followed by a new line, and return <code>1</code></li>
</ul>

<pre><code>julien@ubuntu:~/0x0A. argc, argv$ gcc -Wall -pedantic -Werror -Wextra -std=gnu89 3-mul.c -o mul
julien@ubuntu:~/0x0A. argc, argv$ ./mul 2 3
6
julien@ubuntu:~/0x0A. argc, argv$ ./mul 2 -3
-6
julien@ubuntu:~/0x0A. argc, argv$ ./mul 2 0
0
julien@ubuntu:~/0x0A. argc, argv$ ./mul 245 3245342
795108790
julien@ubuntu:~/0x0A. argc, argv$ ./mul
Error
julien@ubuntu:~/0x0A. argc, argv$ 
</code></pre>

</div>

<div class="list-group">
<!-- Task URLs -->

<!-- Github information -->
<div class="list-group-item">
<p><strong>Repo:</strong></p>
<ul>
<li>GitHub repository: <code>alx-low_level_programming</code></li>
<li>Directory: <code>0x0A-argc_argv</code></li>
<li>File: <code>3-mul.c</code></li>
</ul>
</div>

<!-- Self-paced manual review -->
</div>

<!-- Panel footer - Controls -->
<div class="panel-footer">
<div class="align-items-center d-flex justify-content-between">

<div>
<button class="student_task_done btn btn-default btn-sm no" data-task-id="929">
<span class="no"><i aria-hidden="true" class="fa fa-square-o "></i></span>
<span class="yes"><i aria-hidden="true" class="fa fa-check-square-o "></i></span>
<span class="pending"><i aria-hidden="true" class="fa fa-spinner  fa-pulse"></i></span>
Done<span class="no pending">?</span><span class="yes">!</span>
</button>

<button class="student-task-done-by btn btn-default btn-sm" data-task-id="929" data-batch-id="26" data-toggle="modal" data-target="#task-929-users-done-modal">
Help
</button>
<div class="modal fade users-done-modal" id="task-929-users-done-modal" data-task-id="929" data-batch-id="26">
<div class="modal-dialog">
<div class="modal-content">
<div class="modal-header">
<button type="button" class="close" data-dismiss="modal" aria-label="Close"><span aria-hidden="true">&times;</span></button>
<h4 class="modal-title">Students who are done with "3. Neither irony nor sarcasm is argument"</h4>
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


<button class="btn btn-default btn-sm check-your-task-929-modal-button" data-task-id="929" data-toggle="modal" data-target="#task-test-correction-929-correction-modal" id="task-num-3-check-code-btn" data-gtm-custom-event-name="task_checker_modal" data-gtm-custom-event-options='{&quot;taskId&quot;:929}'>
Check your code
</button>
<div class="modal fade task_correction_modal student_modal" id="task-test-correction-929-correction-modal">
<div class="modal-dialog">
<div class="modal-content">
<div class="modal-header">
<button type="button" class="close" data-dismiss="modal" aria-label="Close"><span aria-hidden="true">&times;</span></button>
<h4 class="modal-title">Correction of "3. Neither irony nor sarcasm is argument"</h4>
</div>
<div class="modal-body">
<div class="actions">
<center>
<div class="alert alert-info hidden"></div>

<button name="button" type="submit" class="btn btn-primary correction_request_test_send" data-task-id="929">Start a new test</button>
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
<button data-task-id="929">
<i aria-hidden="true" class="fa fa-info-circle "></i>
</button>
<div class="help-container" data-task-id="929">
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


<button class="btn btn-primary btn-sm task_ask_new_correction " data-task-id="929" data-correction-id="7871676">
Ask for a new correction
<span class="in_progress_info">: in progress...</span>
<span class="error_occurred_info">: an error occurred</span>
</button>

<button class="btn btn-default btn-sm" data-toggle="modal" data-target="#container-specs-modal" data-gtm-custom-event-name="task_sandbox_modal" data-gtm-custom-event-options="{&quot;taskId&quot;:929}"><i aria-hidden="true" class="fa fa-terminal "></i><span>Get a sandbox</span></button>

<button class="btn btn-default btn-sm" data-task-id="929" data-toggle="modal" data-target="#task-qa-review-929-modal" data-gtm-custom-event-name="task_qa_review_modal" data-gtm-custom-event-options='{&quot;taskId&quot;:929}'>
QA Review
</button>
<div class="modal fade task_get_qa_review" id="task-qa-review-929-modal" data-correction-id="7871676" data-task-id="929">
<div class="modal-dialog modal-lg">
<div class="modal-content">
<div class="modal-header">
<button type="button" class="close" data-dismiss="modal" aria-label="Close"><span aria-hidden="true">&times;</span></button>
<h4 class="modal-title">3. Neither irony nor sarcasm is argument</h4>
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
<div data-role="task930" data-position="5" id="task-num-4">
<div class="panel panel-default task-card " id="task-930">
<span id="user_id" data-id="197885"></span>

<div class="panel-heading panel-heading-actions">
<h3 class="panel-title">
4. To infinity and beyond
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
<div class="task_progress_score_bar" data-task-id="930" data-correction-id="7871676">
<div class="task_progress_bar" style="width: 0.0%">
<div class="task_score_bar" style="width: NaN%">
</div>
</div>
<div class="task_progress_score_text">
Score: <span class="task_score_value">0.0%</span> (<span class="task_progress_value">Checks completed: 0.0%</span>)
</div>
</div>

<!-- Task Body -->
<p>Write a program that adds positive numbers.</p>

<ul>
<li>Print the result, followed by a new line</li>
<li>If no number is passed to the program, print <code>0</code>, followed by a new line</li>
<li>If one of the number contains symbols that are not digits, print <code>Error</code>, followed by a new line, and return <code>1</code></li>
<li>You can assume that numbers and the addition of all the numbers can be stored in an <code>int</code></li>
</ul>

<pre><code>julien@ubuntu:~/0x0A. argc, argv$ gcc -Wall -pedantic -Werror -Wextra -std=gnu89 4-add.c -o add
julien@ubuntu:~/0x0A. argc, argv$ ./add 1 1
2
julien@ubuntu:~/0x0A. argc, argv$ ./add 1 10 100 1000
1111
julien@ubuntu:~/0x0A. argc, argv$ ./add 1 2 3 e 4 5
Error
julien@ubuntu:~/0x0A. argc, argv$ ./add
0
julien@ubuntu:~/0x0A. argc, argv$ 
</code></pre>

</div>

<div class="list-group">
<!-- Task URLs -->

<!-- Github information -->
<div class="list-group-item">
<p><strong>Repo:</strong></p>
<ul>
<li>GitHub repository: <code>alx-low_level_programming</code></li>
<li>Directory: <code>0x0A-argc_argv</code></li>
<li>File: <code>4-add.c</code></li>
</ul>
</div>

<!-- Self-paced manual review -->
</div>

<!-- Panel footer - Controls -->
<div class="panel-footer">
<div class="align-items-center d-flex justify-content-between">

<div>
<button class="student_task_done btn btn-default btn-sm no" data-task-id="930">
<span class="no"><i aria-hidden="true" class="fa fa-square-o "></i></span>
<span class="yes"><i aria-hidden="true" class="fa fa-check-square-o "></i></span>
<span class="pending"><i aria-hidden="true" class="fa fa-spinner  fa-pulse"></i></span>
Done<span class="no pending">?</span><span class="yes">!</span>
</button>

<button class="student-task-done-by btn btn-default btn-sm" data-task-id="930" data-batch-id="26" data-toggle="modal" data-target="#task-930-users-done-modal">
Help
</button>
<div class="modal fade users-done-modal" id="task-930-users-done-modal" data-task-id="930" data-batch-id="26">
<div class="modal-dialog">
<div class="modal-content">
<div class="modal-header">
<button type="button" class="close" data-dismiss="modal" aria-label="Close"><span aria-hidden="true">&times;</span></button>
<h4 class="modal-title">Students who are done with "4. To infinity and beyond"</h4>
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


<button class="btn btn-default btn-sm check-your-task-930-modal-button" data-task-id="930" data-toggle="modal" data-target="#task-test-correction-930-correction-modal" id="task-num-4-check-code-btn" data-gtm-custom-event-name="task_checker_modal" data-gtm-custom-event-options='{&quot;taskId&quot;:930}'>
Check your code
</button>
<div class="modal fade task_correction_modal student_modal" id="task-test-correction-930-correction-modal">
<div class="modal-dialog">
<div class="modal-content">
<div class="modal-header">
<button type="button" class="close" data-dismiss="modal" aria-label="Close"><span aria-hidden="true">&times;</span></button>
<h4 class="modal-title">Correction of "4. To infinity and beyond"</h4>
</div>
<div class="modal-body">
<div class="actions">
<center>
<div class="alert alert-info hidden"></div>

<button name="button" type="submit" class="btn btn-primary correction_request_test_send" data-task-id="930">Start a new test</button>
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
<button data-task-id="930">
<i aria-hidden="true" class="fa fa-info-circle "></i>
</button>
<div class="help-container" data-task-id="930">
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


<button class="btn btn-primary btn-sm task_ask_new_correction " data-task-id="930" data-correction-id="7871676">
Ask for a new correction
<span class="in_progress_info">: in progress...</span>
<span class="error_occurred_info">: an error occurred</span>
</button>

<button class="btn btn-default btn-sm" data-toggle="modal" data-target="#container-specs-modal" data-gtm-custom-event-name="task_sandbox_modal" data-gtm-custom-event-options="{&quot;taskId&quot;:930}"><i aria-hidden="true" class="fa fa-terminal "></i><span>Get a sandbox</span></button>

<button class="btn btn-default btn-sm" data-task-id="930" data-toggle="modal" data-target="#task-qa-review-930-modal" data-gtm-custom-event-name="task_qa_review_modal" data-gtm-custom-event-options='{&quot;taskId&quot;:930}'>
QA Review
</button>
<div class="modal fade task_get_qa_review" id="task-qa-review-930-modal" data-correction-id="7871676" data-task-id="930">
<div class="modal-dialog modal-lg">
<div class="modal-content">
<div class="modal-header">
<button type="button" class="close" data-dismiss="modal" aria-label="Close"><span aria-hidden="true">&times;</span></button>
<h4 class="modal-title">4. To infinity and beyond</h4>
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
<form class="button_to" method="post" action="/projects/221/unlock_optionals"><input id="unlock_optional_btn" class="btn btn-primary btn-block" data-confirm="Are you sure? Make sure you focused on the mandatory tasks first" data-disable-with="Unlocking 1 advanced task..." data-gtm-custom-event-name="project_unlock_advanced_tasks" type="submit" value="Done with the mandatory tasks? Unlock 1 advanced task now!" /><input type="hidden" name="authenticity_token" value="kjvmq5IW3zNwBWH-GTJO-vDJ5lX7ENIRFwZKCKBZiOIwnhZ29Z4TbP_VQvYLuTqndA-Ivxj67YBOfCz6XJy6JA" autocomplete="off" /></form>
</p>




<div class="modal fade" id="container-specs-modal"><div class="modal-dialog modal-lg"><div class="modal-content"><div class="modal-header"><button type="button" class="close" data-dismiss="modal" aria-label="Close"><span aria-hidden="true">&times;</span></button><h4 class="modal-title">Recommended Sandbox</h4></div><div class="modal-body"><div data-react-class="user_containers/ContainerSpecs" data-react-props="{&quot;containerModelName&quot;:&quot;Sandbox&quot;,&quot;containerSpecs&quot;:[{&quot;description&quot;:&quot;\u003cp\u003eBasic Ubuntu 20.04, with vim, emacs, curl, wget and all needed for Foundations\u003c/p\u003e\n&quot;,&quot;id&quot;:39,&quot;name&quot;:&quot;Ubuntu 20.04&quot;,&quot;online&quot;:true,&quot;container&quot;:{&quot;container_id&quot;:null,&quot;id&quot;:239271,&quot;restart_uri&quot;:&quot;/user_containers/239271/restart.json&quot;,&quot;status&quot;:&quot;asleep&quot;,&quot;uri&quot;:&quot;/user_containers/239271.json&quot;,&quot;wake_uri&quot;:&quot;/user_containers/239271/wake.json&quot;,&quot;webterm_uri&quot;:&quot;/user_containers/239271/webterm&quot;,&quot;host&quot;:null,&quot;password&quot;:&quot;2deaf74c415af9350d02&quot;,&quot;ports&quot;:{&quot;8080&quot;:56917,&quot;3306&quot;:56922,&quot;443&quot;:56924,&quot;5000&quot;:56920,&quot;5001&quot;:56919,&quot;8000&quot;:56918,&quot;22&quot;:56926,&quot;3000&quot;:56923,&quot;4000&quot;:56921,&quot;80&quot;:56925}}}],&quot;containersLimit&quot;:2,&quot;csrfToken&quot;:&quot;qInTeKeisaCZeVtLODPu0lDRTj21MSbAvKEwVJg9NBFAWpau7Wo4n6hjqoRRkA4gXe6NTfyuN18Maxj_6rmFRQ&quot;,&quot;startStatusURI&quot;:&quot;/user_containers/start_status.json&quot;,&quot;startURI&quot;:&quot;/user_containers/start.json&quot;}" data-react-cache-id="user_containers/ContainerSpecs-0"></div></div></div></div></div>

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
