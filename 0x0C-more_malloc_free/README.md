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


<title>Project: 0x0C. C - More malloc, free | ALX Africa Intranet</title>

<link rel="stylesheet" href="https://use.typekit.net/xgz4ilr.css">
<link rel="stylesheet" media="all" href="/assets/application_alx-bd8f82c7d5afa064449a69a1a91b6daef7bdb1c71c00f2646d99a16e5040963a.css" />
<script src="https://www.gstatic.com/charts/loader.js"></script>
<script src="/assets/application-fb2ab0247cdaae2347e87bac130aa052747dadacfa429138002d69271946027f.js"></script>
<link rel="shortcut icon" type="image/x-icon" href="/favicon_alx.ico" />
<meta name="csrf-param" content="authenticity_token" />
<meta name="csrf-token" content="EhhbpCowR6gO9UTmu_hZdwaoCscd8_iwvEltYXK7Iv36yx5yYPjOlz_vtSnSW7mFC5fJt1Rs6S8Mg0XKAD-TqQ" />

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
<div class="inner" style="background-image: url('https://s3.amazonaws.com/alx-intranet.hbtn.io/users/photos/000/197/885/thumb/joker.jpg?X-Amz-Algorithm=AWS4-HMAC-SHA256&amp;X-Amz-Credential=AKIARDDGGGOUSBVO6H7D%2F20230121%2Fus-east-1%2Fs3%2Faws4_request&amp;X-Amz-Date=20230121T082919Z&amp;X-Amz-Expires=600&amp;X-Amz-SignedHeaders=host&amp;X-Amz-Signature=d97701509f6ef4b6bd8431c32341a9259907a2c96341cb4153fff86604af61de')"></div>
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
<div class="inner" style="background-image: url('https://s3.amazonaws.com/alx-intranet.hbtn.io/users/photos/000/197/885/thumb/joker.jpg?X-Amz-Algorithm=AWS4-HMAC-SHA256&amp;X-Amz-Credential=AKIARDDGGGOUSBVO6H7D%2F20230121%2Fus-east-1%2Fs3%2Faws4_request&amp;X-Amz-Date=20230121T082919Z&amp;X-Amz-Expires=600&amp;X-Amz-SignedHeaders=host&amp;X-Amz-Signature=d97701509f6ef4b6bd8431c32341a9259907a2c96341cb4153fff86604af61de')"></div>
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

<h1 class="gap">0x0C. C - More malloc, free</h1>

<div data-react-class="tags/Tags" data-react-props="{&quot;tags&quot;:[{&quot;id&quot;:7,&quot;value&quot;:&quot;C&quot;,&quot;author_id&quot;:null,&quot;created_at&quot;:&quot;2022-06-16T01:59:38.000Z&quot;,&quot;updated_at&quot;:&quot;2022-06-16T01:59:38.000Z&quot;},{&quot;id&quot;:15,&quot;value&quot;:&quot;Memory allocation&quot;,&quot;author_id&quot;:null,&quot;created_at&quot;:&quot;2022-06-16T01:59:38.000Z&quot;,&quot;updated_at&quot;:&quot;2022-06-16T01:59:38.000Z&quot;}]}" data-react-cache-id="tags/Tags-0"></div>

<div data-react-class="projects/ProjectMetadata" data-react-props="{&quot;metadata&quot;:{&quot;author&quot;:&quot;Julien Barbier&quot;,&quot;weight&quot;:1,&quot;correction&quot;:{&quot;released&quot;:true,&quot;requires_auto_correction&quot;:true,&quot;requires_manual_correction&quot;:false},&quot;bpi&quot;:{&quot;current&quot;:false,&quot;in_second_deadline&quot;:false,&quot;starts_at&quot;:&quot;2023-01-12T06:00:00.000+03:00&quot;,&quot;ends_at&quot;:&quot;2023-01-13T06:00:00.000+03:00&quot;,&quot;second_deadline_at&quot;:&quot;2023-01-14T06:00:00.000+03:00&quot;}}}" data-react-cache-id="projects/ProjectMetadata-0"></div>

<div class="sm-gap clean well">
<h4>In a nutshell&hellip;</h4>
<ul>


<li>
<strong>Auto QA review:</strong>
0.0/36 mandatory
&
0.0/21 optional
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







<div id="project_id" style="display: none" data-project-id="223"></div>





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
<li><a href="/rltoken/uKhvfzpF3v8Be10NCZlQtA" title="Do I cast the result of malloc?" target="_blank">Do I cast the result of malloc?</a> </li>
</ul>

<p><strong>man or help</strong>:</p>

<ul>
<li><code>exit (3)</code></li>
<li><code>calloc</code></li>
<li><code>realloc</code></li>
</ul>

<h2>Learning Objectives</h2>

<p>At the end of this project, you are expected to be able to <a href="/rltoken/XQ_E28qyePVdJn1Irb_Dfg" title="explain to anyone" target="_blank">explain to anyone</a>, <strong>without the help of Google</strong>:</p>

<h3>General</h3>

<ul>
<li>How to use the <code>exit</code> function</li>
<li>What are the functions <code>calloc</code> and <code>realloc</code> from the standard library and how to use them</li>
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
<li>The only C standard library functions allowed are <code>malloc</code>, <code>free</code> and <code>exit</code>. Any use of functions like <code>printf</code>, <code>puts</code>, <code>calloc</code>, <code>realloc</code> etc&hellip; is forbidden</li>
<li>You are allowed to use <a href="https://github.com/holbertonschool/_putchar.c/blob/master/_putchar.c" title="_putchar" target="_blank">_putchar</a></li>
<li>You don&rsquo;t have to push <code>_putchar.c</code>, we will use our file. If you do it won&rsquo;t be taken into account</li>
<li>In the following examples, the <code>main.c</code> files are shown as examples. You can use them to test your functions, but you don&rsquo;t have to push them to your repo (if you do we won&rsquo;t take them into account). We will use our own <code>main.c</code> files at compilation. Our <code>main.c</code> files might be different from the one shown in the examples</li>
<li>The prototypes of all your functions and the prototype of the function <code>_putchar</code> should be included in your header file called <code>main.h</code></li>
<li>Don&rsquo;t forget to push your header file</li>
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
<div class="quiz_question_item_container" data-role="quiz_question484" data-position="3">
<div class=" clearfix" id="quiz_question-484">

<h4 class="quiz_question">

Question #0
</h4>

<!-- Quiz question Body -->
<p>malloc returns a pointer</p>


<!-- Quiz question Answers -->
<ul class="quiz_question_answers" data-question-id="484">
<li class="">

<input type="radio" name="484" id="484-1507762300499" value="1507762300499" data-quiz-answer-id="1507762300499" data-quiz-question-id="484" disabled="disabled" checked="checked" />
<label for="484-1507762300499"><p>True</p>
</label>
</li>

<li class="">

<input type="radio" name="484" id="484-1507762306290" value="1507762306290" data-quiz-answer-id="1507762306290" data-quiz-question-id="484" disabled="disabled" />
<label for="484-1507762306290"><p>False</p>
</label>
</li>

</ul>

<!-- Quiz question Tips -->

</div>

</div>
<div class="quiz_question_item_container" data-role="quiz_question491" data-position="10">
<div class=" clearfix" id="quiz_question-491">

<h4 class="quiz_question">

Question #1
</h4>

<!-- Quiz question Body -->
<p>What will you see on the terminal?</p>

<pre><code>int main(void)
{
int *ptr;

*ptr = 98;
printf(&quot;%d\n&quot;, *ptr);
return (0);
}
</code></pre>


<!-- Quiz question Answers -->
<ul class="quiz_question_answers" data-question-id="491">
<li class="">

<input type="radio" name="491" id="491-1507763089079" value="1507763089079" data-quiz-answer-id="1507763089079" data-quiz-question-id="491" disabled="disabled" />
<label for="491-1507763089079"><p>It doesn&rsquo;t compile</p>
</label>
</li>

<li class="">

<input type="radio" name="491" id="491-1507763075377" value="1507763075377" data-quiz-answer-id="1507763075377" data-quiz-question-id="491" disabled="disabled" />
<label for="491-1507763075377"><p>0</p>
</label>
</li>

<li class="">

<input type="radio" name="491" id="491-1507763095935" value="1507763095935" data-quiz-answer-id="1507763095935" data-quiz-question-id="491" disabled="disabled" checked="checked" />
<label for="491-1507763095935"><p>Segmentation Fault</p>
</label>
</li>

<li class="">

<input type="radio" name="491" id="491-1507763079995" value="1507763079995" data-quiz-answer-id="1507763079995" data-quiz-question-id="491" disabled="disabled" />
<label for="491-1507763079995"><p>98</p>
</label>
</li>

</ul>

<!-- Quiz question Tips -->

</div>

</div>
<div class="quiz_question_item_container" data-role="quiz_question485" data-position="4">
<div class=" clearfix" id="quiz_question-485">

<h4 class="quiz_question">

Question #2
</h4>

<!-- Quiz question Body -->
<p>malloc returns an address</p>


<!-- Quiz question Answers -->
<ul class="quiz_question_answers" data-question-id="485">
<li class="">

<input type="radio" name="485" id="485-1507762349946" value="1507762349946" data-quiz-answer-id="1507762349946" data-quiz-question-id="485" disabled="disabled" checked="checked" />
<label for="485-1507762349946"><p>True</p>
</label>
</li>

<li class="">

<input type="radio" name="485" id="485-1507762361697" value="1507762361697" data-quiz-answer-id="1507762361697" data-quiz-question-id="485" disabled="disabled" />
<label for="485-1507762361697"><p>False</p>
</label>
</li>

</ul>

<!-- Quiz question Tips -->

</div>

</div>
<div class="quiz_question_item_container" data-role="quiz_question490" data-position="9">
<div class=" clearfix" id="quiz_question-490">

<h4 class="quiz_question">

Question #3
</h4>

<!-- Quiz question Body -->
<p>The memory space reserved when calling <code>malloc</code> is on:</p>


<!-- Quiz question Answers -->
<ul class="quiz_question_answers" data-question-id="490">
<li class="">

<input type="radio" name="490" id="490-1507762865772" value="1507762865772" data-quiz-answer-id="1507762865772" data-quiz-question-id="490" disabled="disabled" />
<label for="490-1507762865772"><p>The stack</p>
</label>
</li>

<li class="">

<input type="radio" name="490" id="490-1507762870010" value="1507762870010" data-quiz-answer-id="1507762870010" data-quiz-question-id="490" disabled="disabled" checked="checked" />
<label for="490-1507762870010"><p>The heap</p>
</label>
</li>

</ul>

<!-- Quiz question Tips -->

</div>

</div>
<div class="quiz_question_item_container" data-role="quiz_question488" data-position="7">
<div class=" clearfix" id="quiz_question-488">

<h4 class="quiz_question">

Question #4
</h4>

<!-- Quiz question Body -->
<p>You can do this:</p>

<pre><code>char str[] = &quot;Best School&quot;;

free (str);
</code></pre>


<!-- Quiz question Answers -->
<ul class="quiz_question_answers" data-question-id="488">
<li class="">

<input type="radio" name="488" id="488-1507762781732" value="1507762781732" data-quiz-answer-id="1507762781732" data-quiz-question-id="488" disabled="disabled" />
<label for="488-1507762781732"><p>Yes</p>
</label>
</li>

<li class="">

<input type="radio" name="488" id="488-1507762786387" value="1507762786387" data-quiz-answer-id="1507762786387" data-quiz-question-id="488" disabled="disabled" checked="checked" />
<label for="488-1507762786387"><p>No</p>
</label>
</li>

</ul>

<!-- Quiz question Tips -->

</div>

</div>
<div class="quiz_question_item_container" data-role="quiz_question482" data-position="1">
<div class=" clearfix" id="quiz_question-482">

<h4 class="quiz_question">

Question #5
</h4>

<!-- Quiz question Body -->
<p>To allocate enough space for an array of 10 integers (on a 64bit, Linux machine), I can use:</p>


<!-- Quiz question Answers -->
<ul class="quiz_question_answers" data-question-id="482">
<li class="">

<input type="radio" name="482" id="482-1507761952940" value="1507761952940" data-quiz-answer-id="1507761952940" data-quiz-question-id="482" disabled="disabled" />
<label for="482-1507761952940"><p>malloc(64 * 10)</p>
</label>
</li>

<li class="">

<input type="radio" name="482" id="482-1507762002312" value="1507762002312" data-quiz-answer-id="1507762002312" data-quiz-question-id="482" disabled="disabled" checked="checked" />
<label for="482-1507762002312"><p>malloc(10 * sizeof(int))</p>
</label>
</li>

<li class="">

<input type="radio" name="482" id="482-1507761993867" value="1507761993867" data-quiz-answer-id="1507761993867" data-quiz-question-id="482" disabled="disabled" />
<label for="482-1507761993867"><p>malloc(10 * int)</p>
</label>
</li>

</ul>

<!-- Quiz question Tips -->

</div>

</div>
<div class="quiz_question_item_container" data-role="quiz_question486" data-position="5">
<div class=" clearfix" id="quiz_question-486">

<h4 class="quiz_question">

Question #6
</h4>

<!-- Quiz question Body -->
<p>What is wrong with this code:</p>

<pre><code>

int cp(void)
{
char *s;

s = malloc(12);
strcpy(s, &quot;Best School&quot;);
return (0);
}
</code></pre>


<!-- Quiz question Answers -->
<ul class="quiz_question_answers" data-question-id="486">
<li class="">

<input type="checkbox" name="486" id="486-1507762406718" value="1507762406718" data-quiz-answer-id="1507762406718" data-quiz-question-id="486" disabled="disabled" />
<label for="486-1507762406718"><p>You can&rsquo;t call <code>strcpy</code> with a string literal</p>
</label>
</li>

<li class="">

<input type="checkbox" name="486" id="486-1507762369065" value="1507762369065" data-quiz-answer-id="1507762369065" data-quiz-question-id="486" disabled="disabled" />
<label for="486-1507762369065"><p>You don&rsquo;t have enough space to store the copy of the string &ldquo;Best School&rdquo;</p>
</label>
</li>

<li class="">

<input type="checkbox" name="486" id="486-1507762570877" value="1507762570877" data-quiz-answer-id="1507762570877" data-quiz-question-id="486" disabled="disabled" checked="checked" />
<label for="486-1507762570877"><p>malloc can fail so we should check its return value all the time before using the pointers returned by the function.</p>
</label>
</li>

<li class="">

<input type="checkbox" name="486" id="486-1507762393504" value="1507762393504" data-quiz-answer-id="1507762393504" data-quiz-question-id="486" disabled="disabled" checked="checked" />
<label for="486-1507762393504"><p>There is no comment</p>
</label>
</li>

</ul>

<!-- Quiz question Tips -->

</div>

</div>
<div class="quiz_question_item_container" data-role="quiz_question487" data-position="6">
<div class=" clearfix" id="quiz_question-487">

<h4 class="quiz_question">

Question #7
</h4>

<!-- Quiz question Body -->
<p>You can do this:</p>

<pre><code>free(&quot;Best School&quot;);
</code></pre>


<!-- Quiz question Answers -->
<ul class="quiz_question_answers" data-question-id="487">
<li class="">

<input type="radio" name="487" id="487-1507762771112" value="1507762771112" data-quiz-answer-id="1507762771112" data-quiz-question-id="487" disabled="disabled" />
<label for="487-1507762771112"><p>Yes</p>
</label>
</li>

<li class="">

<input type="radio" name="487" id="487-1507762774886" value="1507762774886" data-quiz-answer-id="1507762774886" data-quiz-question-id="487" disabled="disabled" checked="checked" />
<label for="487-1507762774886"><p>No</p>
</label>
</li>

</ul>

<!-- Quiz question Tips -->

</div>

</div>
<div class="quiz_question_item_container" data-role="quiz_question483" data-position="2">
<div class=" clearfix" id="quiz_question-483">

<h4 class="quiz_question">

Question #8
</h4>

<!-- Quiz question Body -->
<p>If I want to copy the string &ldquo;Best School&rdquo; into a new space in memory, I can use this statement to reserve enough space for it (select all valid answers):</p>


<!-- Quiz question Answers -->
<ul class="quiz_question_answers" data-question-id="483">
<li class="">

<input type="checkbox" name="483" id="483-1507762225841" value="1507762225841" data-quiz-answer-id="1507762225841" data-quiz-question-id="483" disabled="disabled" />
<label for="483-1507762225841"><p>malloc(sizeof(&ldquo;Best School&rdquo;) + 1)</p>
</label>
</li>

<li class="">

<input type="checkbox" name="483" id="483-1507762140035" value="1507762140035" data-quiz-answer-id="1507762140035" data-quiz-question-id="483" disabled="disabled" checked="checked" />
<label for="483-1507762140035"><p>malloc(sizeof(&ldquo;Best School&rdquo;))</p>
</label>
</li>

<li class="">

<input type="checkbox" name="483" id="483-1507762153953" value="1507762153953" data-quiz-answer-id="1507762153953" data-quiz-question-id="483" disabled="disabled" />
<label for="483-1507762153953"><p>malloc(strlen(&ldquo;Best School&rdquo;))</p>
</label>
</li>

<li class="">

<input type="checkbox" name="483" id="483-1507762216251" value="1507762216251" data-quiz-answer-id="1507762216251" data-quiz-question-id="483" disabled="disabled" checked="checked" />
<label for="483-1507762216251"><p>malloc(12)</p>
</label>
</li>

<li class="">

<input type="checkbox" name="483" id="483-1507762214029" value="1507762214029" data-quiz-answer-id="1507762214029" data-quiz-question-id="483" disabled="disabled" />
<label for="483-1507762214029"><p>malloc(11)</p>
</label>
</li>

<li class="">

<input type="checkbox" name="483" id="483-1507762239753" value="1507762239753" data-quiz-answer-id="1507762239753" data-quiz-question-id="483" disabled="disabled" checked="checked" />
<label for="483-1507762239753"><p>malloc(strlen(&ldquo;Best School&rdquo;) + 1)</p>
</label>
</li>

</ul>

<!-- Quiz question Tips -->

</div>

</div>
<div class="quiz_question_item_container" data-role="quiz_question489" data-position="8">
<div class=" clearfix" id="quiz_question-489">

<h4 class="quiz_question">

Question #9
</h4>

<!-- Quiz question Body -->
<p>You can do this:</p>

<pre><code>char *s;

s = strdup(&quot;Best School&quot;);
if (s != NULL)
{
free(s);
}
</code></pre>


<!-- Quiz question Answers -->
<ul class="quiz_question_answers" data-question-id="489">
<li class="">

<input type="radio" name="489" id="489-1507762794419" value="1507762794419" data-quiz-answer-id="1507762794419" data-quiz-question-id="489" disabled="disabled" checked="checked" />
<label for="489-1507762794419"><p>Yes</p>
</label>
</li>

<li class="">

<input type="radio" name="489" id="489-1507762798621" value="1507762798621" data-quiz-answer-id="1507762798621" data-quiz-question-id="489" disabled="disabled" />
<label for="489-1507762798621"><p>No</p>
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

<div data-role="task939" data-position="1" id="task-num-0">
<div class="panel panel-default task-card " id="task-939">
<span id="user_id" data-id="197885"></span>

<div class="panel-heading panel-heading-actions">
<h3 class="panel-title">
0. Trust no one
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
<div class="task_progress_score_bar" data-task-id="939" data-correction-id="7951649">
<div class="task_progress_bar" style="width: 0.0%">
<div class="task_score_bar" style="width: NaN%">
</div>
</div>
<div class="task_progress_score_text">
Score: <span class="task_score_value">0.0%</span> (<span class="task_progress_value">Checks completed: 0.0%</span>)
</div>
</div>

<!-- Task Body -->
<p>Write a function that allocates memory using <code>malloc</code>.</p>

<ul>
<li>Prototype: <code>void *malloc_checked(unsigned int b);</code></li>
<li>Returns a pointer to the allocated memory</li>
<li>if <code>malloc</code> fails, the <code>malloc_checked</code> function should cause normal process termination with a status value of <code>98</code></li>
</ul>

<pre><code>julien@ubuntu:~/0x0b. more malloc, free$ cat 0-main.c
#include &quot;main.h&quot;
#include &lt;stdio.h&gt;
#include &lt;stdlib.h&gt;
#include &lt;limits.h&gt;

/**
* main - check the code
*
* Return: Always 0.
*/
int main(void)
{
char *c;
int *i;
float *f;
double *d;

c = malloc_checked(sizeof(char) * 1024);
printf(&quot;%p\n&quot;, (void *)c);
i = malloc_checked(sizeof(int) * 402);
printf(&quot;%p\n&quot;, (void *)i);
f = malloc_checked(sizeof(float) * 100000000);
printf(&quot;%p\n&quot;, (void *)f);
d = malloc_checked(INT_MAX);
printf(&quot;%p\n&quot;, (void *)d);
free(c);
free(i);
free(f);
free(d);
return (0);
}
julien@ubuntu:~/0x0b. more malloc, free$ gcc -Wall -pedantic -Werror -Wextra -std=gnu89 0-main.c 0-malloc_checked.c -o a
julien@ubuntu:~/0x0b. more malloc, free$ ./a 
0x1e39010
0x1e39830
0x7f31f6c19010
julien@ubuntu:~/0x0b. more malloc, free$ echo $?
98
julien@ubuntu:~/0x0b. more malloc, free$ 
</code></pre>

</div>

<div class="list-group">
<!-- Task URLs -->

<!-- Github information -->
<div class="list-group-item">
<p><strong>Repo:</strong></p>
<ul>
<li>GitHub repository: <code>alx-low_level_programming</code></li>
<li>Directory: <code>0x0C-more_malloc_free</code></li>
<li>File: <code>0-malloc_checked.c</code></li>
</ul>
</div>

<!-- Self-paced manual review -->
</div>

<!-- Panel footer - Controls -->
<div class="panel-footer">
<div class="align-items-center d-flex justify-content-between">

<div>
<button class="student_task_done btn btn-default btn-sm no" data-task-id="939">
<span class="no"><i aria-hidden="true" class="fa fa-square-o "></i></span>
<span class="yes"><i aria-hidden="true" class="fa fa-check-square-o "></i></span>
<span class="pending"><i aria-hidden="true" class="fa fa-spinner  fa-pulse"></i></span>
Done<span class="no pending">?</span><span class="yes">!</span>
</button>

<button class="student-task-done-by btn btn-default btn-sm" data-task-id="939" data-batch-id="26" data-toggle="modal" data-target="#task-939-users-done-modal">
Help
</button>
<div class="modal fade users-done-modal" id="task-939-users-done-modal" data-task-id="939" data-batch-id="26">
<div class="modal-dialog">
<div class="modal-content">
<div class="modal-header">
<button type="button" class="close" data-dismiss="modal" aria-label="Close"><span aria-hidden="true">&times;</span></button>
<h4 class="modal-title">Students who are done with "0. Trust no one"</h4>
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


<button class="btn btn-default btn-sm check-your-task-939-modal-button" data-task-id="939" data-toggle="modal" data-target="#task-test-correction-939-correction-modal" id="task-num-0-check-code-btn" data-gtm-custom-event-name="task_checker_modal" data-gtm-custom-event-options='{&quot;taskId&quot;:939}'>
Check your code
</button>
<div class="modal fade task_correction_modal student_modal" id="task-test-correction-939-correction-modal">
<div class="modal-dialog">
<div class="modal-content">
<div class="modal-header">
<button type="button" class="close" data-dismiss="modal" aria-label="Close"><span aria-hidden="true">&times;</span></button>
<h4 class="modal-title">Correction of "0. Trust no one"</h4>
</div>
<div class="modal-body">
<div class="actions">
<center>
<div class="alert alert-info hidden"></div>

<button name="button" type="submit" class="btn btn-primary correction_request_test_send" data-task-id="939">Start a new test</button>
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
<button data-task-id="939">
<i aria-hidden="true" class="fa fa-info-circle "></i>
</button>
<div class="help-container" data-task-id="939">
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


<button class="btn btn-primary btn-sm task_ask_new_correction " data-task-id="939" data-correction-id="7951649">
Ask for a new correction
<span class="in_progress_info">: in progress...</span>
<span class="error_occurred_info">: an error occurred</span>
</button>



<button class="btn btn-default btn-sm" data-task-id="939" data-toggle="modal" data-target="#task-qa-review-939-modal" data-gtm-custom-event-name="task_qa_review_modal" data-gtm-custom-event-options='{&quot;taskId&quot;:939}'>
QA Review
</button>
<div class="modal fade task_get_qa_review" id="task-qa-review-939-modal" data-correction-id="7951649" data-task-id="939">
<div class="modal-dialog modal-lg">
<div class="modal-content">
<div class="modal-header">
<button type="button" class="close" data-dismiss="modal" aria-label="Close"><span aria-hidden="true">&times;</span></button>
<h4 class="modal-title">0. Trust no one</h4>
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
<div data-role="task940" data-position="2" id="task-num-1">
<div class="panel panel-default task-card " id="task-940">
<span id="user_id" data-id="197885"></span>

<div class="panel-heading panel-heading-actions">
<h3 class="panel-title">
1. string_nconcat
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
<div class="task_progress_score_bar" data-task-id="940" data-correction-id="7951649">
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
<li>Prototype: <code>char *string_nconcat(char *s1, char *s2, unsigned int n);</code></li>
<li>The returned pointer shall point to a newly allocated space in memory, which contains <code>s1</code>, followed by the first <code>n</code> bytes of <code>s2</code>, and null terminated</li>
<li>If the function fails, it should return <code>NULL</code></li>
<li>If <code>n</code> is greater or equal to the length of <code>s2</code> then use the entire string <code>s2</code></li>
<li>if <code>NULL</code> is passed, treat it as an empty string</li>
</ul>

<pre><code>julien@ubuntu:~/0x0b. more malloc, free$ cat 1-main.c
#include &quot;main.h&quot;
#include &lt;stdio.h&gt;
#include &lt;stdlib.h&gt;

/**
* main - check the code
*
* Return: Always 0.
*/
int main(void)
{
char *concat;

concat = string_nconcat(&quot;Best &quot;, &quot;School !!!&quot;, 6);
printf(&quot;%s\n&quot;, concat);
free(concat);
return (0);
}
julien@ubuntu:~/0x0b. more malloc, free$ gcc -Wall -pedantic -Werror -Wextra -std=gnu89 1-main.c 1-string_nconcat.c -o 1-string_nconcat
julien@ubuntu:~/0x0b. more malloc, free$ ./1-string_nconcat
Best School
julien@ubuntu:~/0x0b. more malloc, free$ 
</code></pre>

</div>

<div class="list-group">
<!-- Task URLs -->

<!-- Github information -->
<div class="list-group-item">
<p><strong>Repo:</strong></p>
<ul>
<li>GitHub repository: <code>alx-low_level_programming</code></li>
<li>Directory: <code>0x0C-more_malloc_free</code></li>
<li>File: <code>1-string_nconcat.c</code></li>
</ul>
</div>

<!-- Self-paced manual review -->
</div>

<!-- Panel footer - Controls -->
<div class="panel-footer">
<div class="align-items-center d-flex justify-content-between">

<div>
<button class="student_task_done btn btn-default btn-sm no" data-task-id="940">
<span class="no"><i aria-hidden="true" class="fa fa-square-o "></i></span>
<span class="yes"><i aria-hidden="true" class="fa fa-check-square-o "></i></span>
<span class="pending"><i aria-hidden="true" class="fa fa-spinner  fa-pulse"></i></span>
Done<span class="no pending">?</span><span class="yes">!</span>
</button>

<button class="student-task-done-by btn btn-default btn-sm" data-task-id="940" data-batch-id="26" data-toggle="modal" data-target="#task-940-users-done-modal">
Help
</button>
<div class="modal fade users-done-modal" id="task-940-users-done-modal" data-task-id="940" data-batch-id="26">
<div class="modal-dialog">
<div class="modal-content">
<div class="modal-header">
<button type="button" class="close" data-dismiss="modal" aria-label="Close"><span aria-hidden="true">&times;</span></button>
<h4 class="modal-title">Students who are done with "1. string_nconcat"</h4>
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


<button class="btn btn-default btn-sm check-your-task-940-modal-button" data-task-id="940" data-toggle="modal" data-target="#task-test-correction-940-correction-modal" id="task-num-1-check-code-btn" data-gtm-custom-event-name="task_checker_modal" data-gtm-custom-event-options='{&quot;taskId&quot;:940}'>
Check your code
</button>
<div class="modal fade task_correction_modal student_modal" id="task-test-correction-940-correction-modal">
<div class="modal-dialog">
<div class="modal-content">
<div class="modal-header">
<button type="button" class="close" data-dismiss="modal" aria-label="Close"><span aria-hidden="true">&times;</span></button>
<h4 class="modal-title">Correction of "1. string_nconcat"</h4>
</div>
<div class="modal-body">
<div class="actions">
<center>
<div class="alert alert-info hidden"></div>

<button name="button" type="submit" class="btn btn-primary correction_request_test_send" data-task-id="940">Start a new test</button>
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
<button data-task-id="940">
<i aria-hidden="true" class="fa fa-info-circle "></i>
</button>
<div class="help-container" data-task-id="940">
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


<button class="btn btn-primary btn-sm task_ask_new_correction " data-task-id="940" data-correction-id="7951649">
Ask for a new correction
<span class="in_progress_info">: in progress...</span>
<span class="error_occurred_info">: an error occurred</span>
</button>



<button class="btn btn-default btn-sm" data-task-id="940" data-toggle="modal" data-target="#task-qa-review-940-modal" data-gtm-custom-event-name="task_qa_review_modal" data-gtm-custom-event-options='{&quot;taskId&quot;:940}'>
QA Review
</button>
<div class="modal fade task_get_qa_review" id="task-qa-review-940-modal" data-correction-id="7951649" data-task-id="940">
<div class="modal-dialog modal-lg">
<div class="modal-content">
<div class="modal-header">
<button type="button" class="close" data-dismiss="modal" aria-label="Close"><span aria-hidden="true">&times;</span></button>
<h4 class="modal-title">1. string_nconcat</h4>
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
<div data-role="task941" data-position="3" id="task-num-2">
<div class="panel panel-default task-card " id="task-941">
<span id="user_id" data-id="197885"></span>

<div class="panel-heading panel-heading-actions">
<h3 class="panel-title">
2. _calloc
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
<div class="task_progress_score_bar" data-task-id="941" data-correction-id="7951649">
<div class="task_progress_bar" style="width: 0.0%">
<div class="task_score_bar" style="width: NaN%">
</div>
</div>
<div class="task_progress_score_text">
Score: <span class="task_score_value">0.0%</span> (<span class="task_progress_value">Checks completed: 0.0%</span>)
</div>
</div>

<!-- Task Body -->
<p>Write a function that allocates memory for an array, using <code>malloc</code>.</p>

<ul>
<li>Prototype: <code>void *_calloc(unsigned int nmemb, unsigned int size);</code></li>
<li>The <code>_calloc</code> function allocates memory for an array of <code>nmemb</code> elements of <code>size</code> bytes each and returns a pointer to the allocated memory.</li>
<li>The memory is set to zero</li>
<li>If <code>nmemb</code> or <code>size</code> is <code>0</code>, then <code>_calloc</code> returns <code>NULL</code></li>
<li>If <code>malloc</code> fails, then <code>_calloc</code> returns <code>NULL</code></li>
</ul>

<p>FYI: The standard library provides a different function: <code>calloc</code>. Run <code>man calloc</code> to learn more.</p>

<pre><code>julien@ubuntu:~/0x0b. more malloc, free$ cat 2-main.c
#include &quot;main.h&quot;
#include &lt;stdio.h&gt;
#include &lt;stdlib.h&gt;
#include &lt;string.h&gt;

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
char *a;

a = _calloc(98, sizeof(char));
strcpy(a, &quot;Best&quot;);
strcpy(a + 4, &quot; School! :)\n&quot;);
a[97] = &#39;!&#39;;
simple_print_buffer(a, 98);
free(a);
return (0);
}
julien@ubuntu:~/0x0b. more malloc, free$ gcc -Wall -pedantic -Werror -Wextra -std=gnu89 2-main.c 2-calloc.c -o 2-calloc
julien@ubuntu:~/0x0b. more malloc, free$ ./2-calloc
0x42 0x65 0x73 0x74 0x20 0x53 0x63 0x68 0x6f 0x6f
0x6c 0x21 0x20 0x3a 0x29 0x0a 0x00 0x00 0x00 0x00
0x00 0x00 0x00 0x00 0x00 0x00 0x00 0x00 0x00 0x00
0x00 0x00 0x00 0x00 0x00 0x00 0x00 0x00 0x00 0x00
0x00 0x00 0x00 0x00 0x00 0x00 0x00 0x00 0x00 0x00
0x00 0x00 0x00 0x00 0x00 0x00 0x00 0x00 0x00 0x00
0x00 0x00 0x00 0x00 0x00 0x00 0x00 0x00 0x00 0x00
0x00 0x00 0x00 0x00 0x00 0x00 0x00 0x00 0x00 0x00
0x00 0x00 0x00 0x00 0x00 0x00 0x00 0x00 0x00 0x00
0x00 0x00 0x00 0x00 0x00 0x00 0x00 0x21
julien@ubuntu:~/0x0b. more malloc, free$ 
</code></pre>

</div>

<div class="list-group">
<!-- Task URLs -->

<!-- Github information -->
<div class="list-group-item">
<p><strong>Repo:</strong></p>
<ul>
<li>GitHub repository: <code>alx-low_level_programming</code></li>
<li>Directory: <code>0x0C-more_malloc_free</code></li>
<li>File: <code>2-calloc.c</code></li>
</ul>
</div>

<!-- Self-paced manual review -->
</div>

<!-- Panel footer - Controls -->
<div class="panel-footer">
<div class="align-items-center d-flex justify-content-between">

<div>
<button class="student_task_done btn btn-default btn-sm no" data-task-id="941">
<span class="no"><i aria-hidden="true" class="fa fa-square-o "></i></span>
<span class="yes"><i aria-hidden="true" class="fa fa-check-square-o "></i></span>
<span class="pending"><i aria-hidden="true" class="fa fa-spinner  fa-pulse"></i></span>
Done<span class="no pending">?</span><span class="yes">!</span>
</button>

<button class="student-task-done-by btn btn-default btn-sm" data-task-id="941" data-batch-id="26" data-toggle="modal" data-target="#task-941-users-done-modal">
Help
</button>
<div class="modal fade users-done-modal" id="task-941-users-done-modal" data-task-id="941" data-batch-id="26">
<div class="modal-dialog">
<div class="modal-content">
<div class="modal-header">
<button type="button" class="close" data-dismiss="modal" aria-label="Close"><span aria-hidden="true">&times;</span></button>
<h4 class="modal-title">Students who are done with "2. _calloc"</h4>
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


<button class="btn btn-default btn-sm check-your-task-941-modal-button" data-task-id="941" data-toggle="modal" data-target="#task-test-correction-941-correction-modal" id="task-num-2-check-code-btn" data-gtm-custom-event-name="task_checker_modal" data-gtm-custom-event-options='{&quot;taskId&quot;:941}'>
Check your code
</button>
<div class="modal fade task_correction_modal student_modal" id="task-test-correction-941-correction-modal">
<div class="modal-dialog">
<div class="modal-content">
<div class="modal-header">
<button type="button" class="close" data-dismiss="modal" aria-label="Close"><span aria-hidden="true">&times;</span></button>
<h4 class="modal-title">Correction of "2. _calloc"</h4>
</div>
<div class="modal-body">
<div class="actions">
<center>
<div class="alert alert-info hidden"></div>

<button name="button" type="submit" class="btn btn-primary correction_request_test_send" data-task-id="941">Start a new test</button>
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
<button data-task-id="941">
<i aria-hidden="true" class="fa fa-info-circle "></i>
</button>
<div class="help-container" data-task-id="941">
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


<button class="btn btn-primary btn-sm task_ask_new_correction " data-task-id="941" data-correction-id="7951649">
Ask for a new correction
<span class="in_progress_info">: in progress...</span>
<span class="error_occurred_info">: an error occurred</span>
</button>



<button class="btn btn-default btn-sm" data-task-id="941" data-toggle="modal" data-target="#task-qa-review-941-modal" data-gtm-custom-event-name="task_qa_review_modal" data-gtm-custom-event-options='{&quot;taskId&quot;:941}'>
QA Review
</button>
<div class="modal fade task_get_qa_review" id="task-qa-review-941-modal" data-correction-id="7951649" data-task-id="941">
<div class="modal-dialog modal-lg">
<div class="modal-content">
<div class="modal-header">
<button type="button" class="close" data-dismiss="modal" aria-label="Close"><span aria-hidden="true">&times;</span></button>
<h4 class="modal-title">2. _calloc</h4>
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
<div data-role="task942" data-position="4" id="task-num-3">
<div class="panel panel-default task-card " id="task-942">
<span id="user_id" data-id="197885"></span>

<div class="panel-heading panel-heading-actions">
<h3 class="panel-title">
3. array_range
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
<div class="task_progress_score_bar" data-task-id="942" data-correction-id="7951649">
<div class="task_progress_bar" style="width: 0.0%">
<div class="task_score_bar" style="width: NaN%">
</div>
</div>
<div class="task_progress_score_text">
Score: <span class="task_score_value">0.0%</span> (<span class="task_progress_value">Checks completed: 0.0%</span>)
</div>
</div>

<!-- Task Body -->
<p>Write a function that creates an array of integers.</p>

<ul>
<li>Prototype: <code>int *array_range(int min, int max);</code></li>
<li>The array created should contain all the values from <code>min</code> (included) to <code>max</code> (included), ordered from <code>min</code> to <code>max</code></li>
<li>Return: the pointer to the newly created array</li>
<li>If <code>min</code> &gt; <code>max</code>, return <code>NULL</code></li>
<li>If <code>malloc</code> fails, return <code>NULL</code></li>
</ul>

<pre><code>julien@ubuntu:~/0x0b. more malloc, free$ cat 3-main.c
#include &quot;main.h&quot;
#include &lt;stdio.h&gt;
#include &lt;stdlib.h&gt;
#include &lt;string.h&gt;

/**
* simple_print_buffer - prints buffer in hexa
* @buffer: the address of memory to print
* @size: the size of the memory to print
*
* Return: Nothing.
*/
void simple_print_buffer(int *buffer, unsigned int size)
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
int *a;

a = array_range(0, 10);
simple_print_buffer(a, 11);
free(a);
return (0);
}
julien@ubuntu:~/0x0b. more malloc, free$ gcc -Wall -pedantic -Werror -Wextra -std=gnu89 3-main.c 3-array_range.c -o 3-array_range
julien@ubuntu:~/0x0b. more malloc, free$ ./3-array_range
0x00 0x01 0x02 0x03 0x04 0x05 0x06 0x07 0x08 0x09
0x0a
julien@ubuntu:~/0x0b. more malloc, free$ 
</code></pre>

</div>

<div class="list-group">
<!-- Task URLs -->

<!-- Github information -->
<div class="list-group-item">
<p><strong>Repo:</strong></p>
<ul>
<li>GitHub repository: <code>alx-low_level_programming</code></li>
<li>Directory: <code>0x0C-more_malloc_free</code></li>
<li>File: <code>3-array_range.c</code></li>
</ul>
</div>

<!-- Self-paced manual review -->
</div>

<!-- Panel footer - Controls -->
<div class="panel-footer">
<div class="align-items-center d-flex justify-content-between">

<div>
<button class="student_task_done btn btn-default btn-sm no" data-task-id="942">
<span class="no"><i aria-hidden="true" class="fa fa-square-o "></i></span>
<span class="yes"><i aria-hidden="true" class="fa fa-check-square-o "></i></span>
<span class="pending"><i aria-hidden="true" class="fa fa-spinner  fa-pulse"></i></span>
Done<span class="no pending">?</span><span class="yes">!</span>
</button>

<button class="student-task-done-by btn btn-default btn-sm" data-task-id="942" data-batch-id="26" data-toggle="modal" data-target="#task-942-users-done-modal">
Help
</button>
<div class="modal fade users-done-modal" id="task-942-users-done-modal" data-task-id="942" data-batch-id="26">
<div class="modal-dialog">
<div class="modal-content">
<div class="modal-header">
<button type="button" class="close" data-dismiss="modal" aria-label="Close"><span aria-hidden="true">&times;</span></button>
<h4 class="modal-title">Students who are done with "3. array_range"</h4>
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


<button class="btn btn-default btn-sm check-your-task-942-modal-button" data-task-id="942" data-toggle="modal" data-target="#task-test-correction-942-correction-modal" id="task-num-3-check-code-btn" data-gtm-custom-event-name="task_checker_modal" data-gtm-custom-event-options='{&quot;taskId&quot;:942}'>
Check your code
</button>
<div class="modal fade task_correction_modal student_modal" id="task-test-correction-942-correction-modal">
<div class="modal-dialog">
<div class="modal-content">
<div class="modal-header">
<button type="button" class="close" data-dismiss="modal" aria-label="Close"><span aria-hidden="true">&times;</span></button>
<h4 class="modal-title">Correction of "3. array_range"</h4>
</div>
<div class="modal-body">
<div class="actions">
<center>
<div class="alert alert-info hidden"></div>

<button name="button" type="submit" class="btn btn-primary correction_request_test_send" data-task-id="942">Start a new test</button>
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
<button data-task-id="942">
<i aria-hidden="true" class="fa fa-info-circle "></i>
</button>
<div class="help-container" data-task-id="942">
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


<button class="btn btn-primary btn-sm task_ask_new_correction " data-task-id="942" data-correction-id="7951649">
Ask for a new correction
<span class="in_progress_info">: in progress...</span>
<span class="error_occurred_info">: an error occurred</span>
</button>



<button class="btn btn-default btn-sm" data-task-id="942" data-toggle="modal" data-target="#task-qa-review-942-modal" data-gtm-custom-event-name="task_qa_review_modal" data-gtm-custom-event-options='{&quot;taskId&quot;:942}'>
QA Review
</button>
<div class="modal fade task_get_qa_review" id="task-qa-review-942-modal" data-correction-id="7951649" data-task-id="942">
<div class="modal-dialog modal-lg">
<div class="modal-content">
<div class="modal-header">
<button type="button" class="close" data-dismiss="modal" aria-label="Close"><span aria-hidden="true">&times;</span></button>
<h4 class="modal-title">3. array_range</h4>
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
<form class="button_to" method="post" action="/projects/223/unlock_optionals"><input id="unlock_optional_btn" class="btn btn-primary btn-block" data-confirm="Are you sure? Make sure you focused on the mandatory tasks first" data-disable-with="Unlocking 2 advanced tasks..." data-gtm-custom-event-name="project_unlock_advanced_tasks" type="submit" value="Done with the mandatory tasks? Unlock 2 advanced tasks now!" /><input type="hidden" name="authenticity_token" value="AyRSI_Dglm--BIFx_RmNwZF7ggnddWD9VNiSyQWCw9sT7nul5dlT8i-n4NCndQKjAUZOQARwv0WUCWFmwIvxDA" autocomplete="off" /></form>
</p>





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
