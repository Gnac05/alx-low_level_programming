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

<script type="text/javascript" src="https://gc.kis.v2.scr.kaspersky-labs.com/FD126C42-EBFA-4E12-B309-BB3FDD723AC1/main.js?attr=aZ-FOETZCrMD6VoI3TnZx__Ds1syS5MK7jF-e6ea48kzQr_Psx2pushCRW7a2Zay6Szuk8yp59Bvbge_gFxTig" charset="UTF-8"></script><script>
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


<title>Project: 0x08. C - Recursion | ALX Africa Intranet</title>

<link rel="stylesheet" href="https://use.typekit.net/xgz4ilr.css">
<link rel="stylesheet" media="all" href="/assets/application_alx-3bc505f2e3a9303a2388308cf98416618d0d78415692ec6a831f106956700814.css" />
<script src="https://www.gstatic.com/charts/loader.js"></script>
<script src="/assets/application-35dd1bfa2a15daa7dc2c7f29abbedd235e98278dee45b81fab4fd94785e21388.js"></script>
<link rel="shortcut icon" type="image/x-icon" href="/favicon_alx.ico" />
<meta name="csrf-param" content="authenticity_token" />
<meta name="csrf-token" content="XlfbKUGk-W8wF9j_ZbjY5ZJmqbQW5SRjUzvXJhZY8t0rdJu5v0_C-awFx7bjUpMkNRO7GKxbkScWqmdA1nNJRw" />

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
<div class="inner" style="background-image: url('https://s3.amazonaws.com/alx-intranet.hbtn.io/users/photos/000/197/885/thumb/joker.jpg?X-Amz-Algorithm=AWS4-HMAC-SHA256&amp;X-Amz-Credential=AKIARDDGGGOUSBVO6H7D%2F20230104%2Fus-east-1%2Fs3%2Faws4_request&amp;X-Amz-Date=20230104T210842Z&amp;X-Amz-Expires=600&amp;X-Amz-SignedHeaders=host&amp;X-Amz-Signature=3bc09364cba25c8de9455c4b0bbeb3220eab071d1968281c2ba138e9cd9aa78a')"></div>
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
<div class="inner" style="background-image: url('https://s3.amazonaws.com/alx-intranet.hbtn.io/users/photos/000/197/885/thumb/joker.jpg?X-Amz-Algorithm=AWS4-HMAC-SHA256&amp;X-Amz-Credential=AKIARDDGGGOUSBVO6H7D%2F20230104%2Fus-east-1%2Fs3%2Faws4_request&amp;X-Amz-Date=20230104T210842Z&amp;X-Amz-Expires=600&amp;X-Amz-SignedHeaders=host&amp;X-Amz-Signature=3bc09364cba25c8de9455c4b0bbeb3220eab071d1968281c2ba138e9cd9aa78a')"></div>
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

<h1 class="gap">0x08. C - Recursion</h1>

<div data-react-class="tags/Tags" data-react-props="{&quot;tags&quot;:[{&quot;id&quot;:7,&quot;value&quot;:&quot;C&quot;,&quot;author_id&quot;:null,&quot;created_at&quot;:&quot;2022-06-16T01:59:38.000Z&quot;,&quot;updated_at&quot;:&quot;2022-06-16T01:59:38.000Z&quot;},{&quot;id&quot;:14,&quot;value&quot;:&quot;Recursion&quot;,&quot;author_id&quot;:null,&quot;created_at&quot;:&quot;2022-06-16T01:59:38.000Z&quot;,&quot;updated_at&quot;:&quot;2022-06-16T01:59:38.000Z&quot;}]}" data-react-cache-id="tags/Tags-0"></div>

<div data-react-class="projects/ProjectMetadata" data-react-props="{&quot;metadata&quot;:{&quot;author&quot;:&quot;Julien Barbier&quot;,&quot;weight&quot;:1,&quot;correction&quot;:{&quot;released&quot;:true,&quot;auto_correction_available_at&quot;:&quot;2023-01-04T06:00:00.000+03:00&quot;,&quot;requires_auto_correction&quot;:true,&quot;requires_manual_correction&quot;:false},&quot;bpi&quot;:{&quot;current&quot;:true,&quot;started&quot;:false,&quot;in_second_deadline&quot;:false,&quot;starts_at&quot;:&quot;2023-01-04T06:00:00.000+03:00&quot;,&quot;ends_at&quot;:&quot;2023-01-05T06:00:00.000+03:00&quot;,&quot;second_deadline_at&quot;:&quot;2023-01-06T06:00:00.000+03:00&quot;}}}" data-react-cache-id="projects/ProjectMetadata-0"></div>







<div id="project_id" style="display: none" data-project-id="219"></div>







<div class="panel panel-default" id="project-description">
<div class="panel-body">
<p><img src="https://s3.amazonaws.com/intranet-projects-files/holbertonschool-low_level_programming/219/a88.jpg" /></p>

<h2>Resources</h2>

<p><strong>Read or watch</strong>:</p>

<ul>
<li><a href="/rltoken/dzZB83Hm3lO7dScjhebAxw" title="0x08. Recursion, introduction" target="_blank">0x08. Recursion, introduction</a></li>
<li><a href="/rltoken/xYjKl3024oN58Bi_621_vQ" title="What on Earth is Recursion?" target="_blank">What on Earth is Recursion?</a> </li>
<li><a href="/rltoken/u4ojc5CZpf4qiuQvmXCiOA" title="C - Recursion" target="_blank">C - Recursion</a> </li>
<li><a href="/rltoken/Wv-wffgpXelN9ZTrbmiOyA" title="C Programming Tutorial 85, Recursion pt.1" target="_blank">C Programming Tutorial 85, Recursion pt.1</a> </li>
<li><a href="/rltoken/7GVdI-KT-M1vOIzwEjSahQ" title="C Programming Tutorial 86, Recursion pt.2" target="_blank">C Programming Tutorial 86, Recursion pt.2</a> </li>
</ul>

<h2>Learning Objectives</h2>

<p>At the end of this project, you are expected to be able to <a href="/rltoken/Uip4OgfLQdGP921TAMtCHQ" title="explain to anyone" target="_blank">explain to anyone</a>, <strong>without the help of Google</strong>:</p>

<h3>General</h3>

<ul>
<li>What is recursion</li>
<li>How to implement recursion</li>
<li>In what situations you should implement recursion</li>
<li>In what situations you shouldn&rsquo;t implement recursion</li>
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
<li><strong>You are not allowed to use any kind of loops</strong></li>
<li>You are not allowed to use <code>static</code> variables</li>
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
<div class="quiz_question_item_container" data-role="quiz_question461" data-position="3">
<div class=" clearfix" id="quiz_question-461">

<h4 class="quiz_question">

Question #0
</h4>

<!-- Quiz question Body -->
<p>What does this code print?</p>

<pre><code>void print(int nb)
{
printf(&quot;%d&quot;, nb);
nb ++;
if (nb &lt; 10) 
{
print(nb);
}
}

int main(void)
{
print(4);
return (0);
}
</code></pre>


<!-- Quiz question Answers -->
<ul class="quiz_question_answers" data-question-id="461">
<li class="">

<input type="radio" name="461" id="461-1507075542179" value="1507075542179" data-quiz-answer-id="1507075542179" data-quiz-question-id="461" disabled="disabled" />
<label for="461-1507075542179"><p>345678910</p>
</label>
</li>

<li class="">

<input type="radio" name="461" id="461-1507075515088" value="1507075515088" data-quiz-answer-id="1507075515088" data-quiz-question-id="461" disabled="disabled" />
<label for="461-1507075515088"><p>987654</p>
</label>
</li>

<li class="">

<input type="radio" name="461" id="461-1507075551017" value="1507075551017" data-quiz-answer-id="1507075551017" data-quiz-question-id="461" disabled="disabled" checked="checked" />
<label for="461-1507075551017"><p>456789</p>
</label>
</li>

<li class="">

<input type="radio" name="461" id="461-1507075535010" value="1507075535010" data-quiz-answer-id="1507075535010" data-quiz-question-id="461" disabled="disabled" />
<label for="461-1507075535010"><p>109876543</p>
</label>
</li>

</ul>

<!-- Quiz question Tips -->

</div>

</div>
<div class="quiz_question_item_container" data-role="quiz_question462" data-position="4">
<div class=" clearfix" id="quiz_question-462">

<h4 class="quiz_question">

Question #1
</h4>

<!-- Quiz question Body -->
<p>What does this code print?</p>

<pre><code>void print(int nb)
{
if (nb &lt; 0) 
{
return;
}
printf(&quot;%d&quot;, nb);
nb --;
print(nb);
}

int main(void)
{
print(4);
return (0);
}
</code></pre>


<!-- Quiz question Answers -->
<ul class="quiz_question_answers" data-question-id="462">
<li class="">

<input type="radio" name="462" id="462-1507075573296" value="1507075573296" data-quiz-answer-id="1507075573296" data-quiz-question-id="462" disabled="disabled" />
<label for="462-1507075573296"><p>1234</p>
</label>
</li>

<li class="">

<input type="radio" name="462" id="462-1507075556311" value="1507075556311" data-quiz-answer-id="1507075556311" data-quiz-question-id="462" disabled="disabled" />
<label for="462-1507075556311"><p>01234</p>
</label>
</li>

<li class="">

<input type="radio" name="462" id="462-1507075576670" value="1507075576670" data-quiz-answer-id="1507075576670" data-quiz-question-id="462" disabled="disabled" />
<label for="462-1507075576670"><p>4321</p>
</label>
</li>

<li class="">

<input type="radio" name="462" id="462-1507075570695" value="1507075570695" data-quiz-answer-id="1507075570695" data-quiz-question-id="462" disabled="disabled" checked="checked" />
<label for="462-1507075570695"><p>43210</p>
</label>
</li>

</ul>

<!-- Quiz question Tips -->

</div>

</div>
<div class="quiz_question_item_container" data-role="quiz_question459" data-position="1">
<div class=" clearfix" id="quiz_question-459">

<h4 class="quiz_question">

Question #2
</h4>

<!-- Quiz question Body -->
<p>What does this code print?</p>

<pre><code>void print(int nb)
{
printf(&quot;%d&quot;, nb);
nb --;
if (nb &gt; 0) 
{
print(nb);
}
}

int main(void)
{
print(2);
return (0);
}
</code></pre>


<!-- Quiz question Answers -->
<ul class="quiz_question_answers" data-question-id="459">
<li class="">

<input type="radio" name="459" id="459-1507075485534" value="1507075485534" data-quiz-answer-id="1507075485534" data-quiz-question-id="459" disabled="disabled" checked="checked" />
<label for="459-1507075485534"><p>21</p>
</label>
</li>

<li class="">

<input type="radio" name="459" id="459-1507075469878" value="1507075469878" data-quiz-answer-id="1507075469878" data-quiz-question-id="459" disabled="disabled" />
<label for="459-1507075469878"><p>012</p>
</label>
</li>

<li class="">

<input type="radio" name="459" id="459-1507075488107" value="1507075488107" data-quiz-answer-id="1507075488107" data-quiz-question-id="459" disabled="disabled" />
<label for="459-1507075488107"><p>210</p>
</label>
</li>

<li class="">

<input type="radio" name="459" id="459-1507075483594" value="1507075483594" data-quiz-answer-id="1507075483594" data-quiz-question-id="459" disabled="disabled" />
<label for="459-1507075483594"><p>12</p>
</label>
</li>

</ul>

<!-- Quiz question Tips -->

</div>

</div>
<div class="quiz_question_item_container" data-role="quiz_question463" data-position="5">
<div class=" clearfix" id="quiz_question-463">

<h4 class="quiz_question">

Question #3
</h4>

<!-- Quiz question Body -->
<p>What does this code print?</p>

<pre><code>int print(int nb)
{
if (nb &lt; 0) 
{
return (0);
}
printf(&quot;%d&quot;, nb + print(nb - 1));
nb --;
return (nb);
}

int main(void)
{
print(4);
return (0);
}
</code></pre>


<!-- Quiz question Answers -->
<ul class="quiz_question_answers" data-question-id="463">
<li class="">

<input type="radio" name="463" id="463-1507075585822" value="1507075585822" data-quiz-answer-id="1507075585822" data-quiz-question-id="463" disabled="disabled" />
<label for="463-1507075585822"><p>64200</p>
</label>
</li>

<li class="">

<input type="radio" name="463" id="463-1507075641911" value="1507075641911" data-quiz-answer-id="1507075641911" data-quiz-question-id="463" disabled="disabled" />
<label for="463-1507075641911"><p>01234568</p>
</label>
</li>

<li class="">

<input type="radio" name="463" id="463-1507075638802" value="1507075638802" data-quiz-answer-id="1507075638802" data-quiz-question-id="463" disabled="disabled" checked="checked" />
<label for="463-1507075638802"><p>00246</p>
</label>
</li>

</ul>

<!-- Quiz question Tips -->

</div>

</div>
<div class="quiz_question_item_container" data-role="quiz_question460" data-position="2">
<div class=" clearfix" id="quiz_question-460">

<h4 class="quiz_question">

Question #4
</h4>

<!-- Quiz question Body -->
<p>What does this code print?</p>

<pre><code>void print(int nb)
{
printf(&quot;%d&quot;, nb);
-- nb;
if (nb &gt; 0) 
{
print(nb);
}
}

int main(void)
{
print(4);
return (0);
}
</code></pre>


<!-- Quiz question Answers -->
<ul class="quiz_question_answers" data-question-id="460">
<li class="">

<input type="radio" name="460" id="460-1507075505532" value="1507075505532" data-quiz-answer-id="1507075505532" data-quiz-question-id="460" disabled="disabled" />
<label for="460-1507075505532"><p>321</p>
</label>
</li>

<li class="">

<input type="radio" name="460" id="460-1507075492615" value="1507075492615" data-quiz-answer-id="1507075492615" data-quiz-question-id="460" disabled="disabled" checked="checked" />
<label for="460-1507075492615"><p>4321</p>
</label>
</li>

<li class="">

<input type="radio" name="460" id="460-1507075509145" value="1507075509145" data-quiz-answer-id="1507075509145" data-quiz-question-id="460" disabled="disabled" />
<label for="460-1507075509145"><p>3210</p>
</label>
</li>

<li class="">

<input type="radio" name="460" id="460-1507075503331" value="1507075503331" data-quiz-answer-id="1507075503331" data-quiz-question-id="460" disabled="disabled" />
<label for="460-1507075503331"><p>43210</p>
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

<div data-role="task914" data-position="1" id="task-num-0">
<div class="panel panel-default task-card " id="task-914">
<span id="user_id" data-id="197885"></span>

<div class="panel-heading panel-heading-actions">
<h3 class="panel-title">
0. She locked away a secret, deep inside herself, something she once knew to be true... but chose to forget
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
<p>Write a function that prints a string, followed by a new line.</p>

<ul>
<li>Prototype: <code>void _puts_recursion(char *s);</code></li>
</ul>

<p>FYI: The standard library provides a similar function: <code>puts</code>. Run <code>man puts</code> to learn more.</p>

<pre><code>julien@ubuntu:~/0x08. Recursion$ cat 0-main.c
#include &quot;main.h&quot;

/**
* main - check the code
*
* Return: Always 0.
*/
int main(void)
{
_puts_recursion(&quot;Puts with recursion&quot;);
return (0);
}
julien@ubuntu:~/0x08. Recursion$ gcc -Wall -pedantic -Werror -Wextra -std=gnu89 _putchar.c 0-main.c 0-puts_recursion.c -o 0-puts_recursion
julien@ubuntu:~/0x08. Recursion$ ./0-puts_recursion 
Puts with recursion
julien@ubuntu:~/0x08. Recursion$ 
</code></pre>

</div>

<div class="list-group">
<!-- Task URLs -->

<!-- Github information -->
<div class="list-group-item">
<p><strong>Repo:</strong></p>
<ul>
<li>GitHub repository: <code>alx-low_level_programming</code></li>
<li>Directory: <code>0x08-recursion</code></li>
<li>File: <code>0-puts_recursion.c</code></li>
</ul>
</div>

<!-- Self-paced manual review -->
</div>

<!-- Panel footer - Controls -->
<div class="panel-footer">
<div class="align-items-center d-flex justify-content-between">

<div>
<button class="student_task_done btn btn-default btn-sm no" data-task-id="914">
<span class="no"><i aria-hidden="true" class="fa fa-square-o "></i></span>
<span class="yes"><i aria-hidden="true" class="fa fa-check-square-o "></i></span>
<span class="pending"><i aria-hidden="true" class="fa fa-spinner  fa-pulse"></i></span>
Done<span class="no pending">?</span><span class="yes">!</span>
</button>

<button class="student-task-done-by btn btn-default btn-sm" data-task-id="914" data-batch-id="26" data-toggle="modal" data-target="#task-914-users-done-modal">
Help
</button>
<div class="modal fade users-done-modal" id="task-914-users-done-modal" data-task-id="914" data-batch-id="26">
<div class="modal-dialog">
<div class="modal-content">
<div class="modal-header">
<button type="button" class="close" data-dismiss="modal" aria-label="Close"><span aria-hidden="true">&times;</span></button>
<h4 class="modal-title">Students who are done with "0. She locked away a secret, deep inside herself, something she once knew to be true... but chose to forget"</h4>
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


<button class="btn btn-default btn-sm check-your-task-914-modal-button" data-task-id="914" data-toggle="modal" data-target="#task-test-correction-914-correction-modal" id="task-num-0-check-code-btn" data-gtm-custom-event-name="task_checker_modal" data-gtm-custom-event-options='{&quot;taskId&quot;:914}'>
Check your code
</button>
<div class="modal fade task_correction_modal student_modal" id="task-test-correction-914-correction-modal">
<div class="modal-dialog">
<div class="modal-content">
<div class="modal-header">
<button type="button" class="close" data-dismiss="modal" aria-label="Close"><span aria-hidden="true">&times;</span></button>
<h4 class="modal-title">Correction of "0. She locked away a secret, deep inside herself, something she once knew to be true... but chose to forget"</h4>
</div>
<div class="modal-body">
<div class="actions">
<center>
<div class="alert alert-info hidden"></div>

<button name="button" type="submit" class="btn btn-primary correction_request_test_send" data-task-id="914">Start a new test</button>
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
<button data-task-id="914">
<i aria-hidden="true" class="fa fa-info-circle "></i>
</button>
<div class="help-container" data-task-id="914">
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



<button class="btn btn-default btn-sm" data-toggle="modal" data-target="#container-specs-modal" data-gtm-custom-event-name="task_sandbox_modal" data-gtm-custom-event-options="{&quot;taskId&quot;:914}"><i aria-hidden="true" class="fa fa-terminal "></i><span>Get a sandbox</span></button>

</div>


<div class="fs-4">
</div>
</div>


</div>
</div>

</div>
<div data-role="task915" data-position="2" id="task-num-1">
<div class="panel panel-default task-card " id="task-915">
<span id="user_id" data-id="197885"></span>

<div class="panel-heading panel-heading-actions">
<h3 class="panel-title">
1. Why is it so important to dream? Because, in my dreams we are together
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
<p>Write a function that prints a string in reverse.</p>

<ul>
<li>Prototype: <code>void _print_rev_recursion(char *s);</code></li>
</ul>

<pre><code>julien@ubuntu:~/0x08. Recursion$ cat 1-main.c
#include &quot;main.h&quot;

/**
* main - check the code
*
* Return: Always 0.
*/
int main(void)
{
_print_rev_recursion(&quot;\nColton Walker&quot;);
return (0);
}
julien@ubuntu:~/0x08. Recursion$ gcc -Wall -pedantic -Werror -Wextra -std=gnu89 _putchar.c 1-main.c 1-print_rev_recursion.c -o 1-print_rev_recursion
julien@ubuntu:~/0x08. Recursion$ ./1-print_rev_recursion 
reklaW notloC
julien@ubuntu:~/0x08. Recursion$ 
</code></pre>

</div>

<div class="list-group">
<!-- Task URLs -->

<!-- Github information -->
<div class="list-group-item">
<p><strong>Repo:</strong></p>
<ul>
<li>GitHub repository: <code>alx-low_level_programming</code></li>
<li>Directory: <code>0x08-recursion</code></li>
<li>File: <code>1-print_rev_recursion.c</code></li>
</ul>
</div>

<!-- Self-paced manual review -->
</div>

<!-- Panel footer - Controls -->
<div class="panel-footer">
<div class="align-items-center d-flex justify-content-between">

<div>
<button class="student_task_done btn btn-default btn-sm no" data-task-id="915">
<span class="no"><i aria-hidden="true" class="fa fa-square-o "></i></span>
<span class="yes"><i aria-hidden="true" class="fa fa-check-square-o "></i></span>
<span class="pending"><i aria-hidden="true" class="fa fa-spinner  fa-pulse"></i></span>
Done<span class="no pending">?</span><span class="yes">!</span>
</button>

<button class="student-task-done-by btn btn-default btn-sm" data-task-id="915" data-batch-id="26" data-toggle="modal" data-target="#task-915-users-done-modal">
Help
</button>
<div class="modal fade users-done-modal" id="task-915-users-done-modal" data-task-id="915" data-batch-id="26">
<div class="modal-dialog">
<div class="modal-content">
<div class="modal-header">
<button type="button" class="close" data-dismiss="modal" aria-label="Close"><span aria-hidden="true">&times;</span></button>
<h4 class="modal-title">Students who are done with "1. Why is it so important to dream? Because, in my dreams we are together"</h4>
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


<button class="btn btn-default btn-sm check-your-task-915-modal-button" data-task-id="915" data-toggle="modal" data-target="#task-test-correction-915-correction-modal" id="task-num-1-check-code-btn" data-gtm-custom-event-name="task_checker_modal" data-gtm-custom-event-options='{&quot;taskId&quot;:915}'>
Check your code
</button>
<div class="modal fade task_correction_modal student_modal" id="task-test-correction-915-correction-modal">
<div class="modal-dialog">
<div class="modal-content">
<div class="modal-header">
<button type="button" class="close" data-dismiss="modal" aria-label="Close"><span aria-hidden="true">&times;</span></button>
<h4 class="modal-title">Correction of "1. Why is it so important to dream? Because, in my dreams we are together"</h4>
</div>
<div class="modal-body">
<div class="actions">
<center>
<div class="alert alert-info hidden"></div>

<button name="button" type="submit" class="btn btn-primary correction_request_test_send" data-task-id="915">Start a new test</button>
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
<button data-task-id="915">
<i aria-hidden="true" class="fa fa-info-circle "></i>
</button>
<div class="help-container" data-task-id="915">
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



<button class="btn btn-default btn-sm" data-toggle="modal" data-target="#container-specs-modal" data-gtm-custom-event-name="task_sandbox_modal" data-gtm-custom-event-options="{&quot;taskId&quot;:915}"><i aria-hidden="true" class="fa fa-terminal "></i><span>Get a sandbox</span></button>

</div>


<div class="fs-4">
</div>
</div>


</div>
</div>

</div>
<div data-role="task916" data-position="3" id="task-num-2">
<div class="panel panel-default task-card " id="task-916">
<span id="user_id" data-id="197885"></span>

<div class="panel-heading panel-heading-actions">
<h3 class="panel-title">
2. Dreams feel real while we&#39;re in them. It&#39;s only when we wake up that we realize something was actually strange
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
<li>Prototype: <code>int _strlen_recursion(char *s);</code></li>
</ul>

<p>FYI: The standard library provides a similar function: <code>strlen</code>. Run <code>man strlen</code> to learn more.</p>

<pre><code>julien@ubuntu:~/0x08. Recursion$ cat 2-main.c 
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

n = _strlen_recursion(&quot;Corbin Coleman&quot;);
printf(&quot;%d\n&quot;, n);
return (0);
}
julien@ubuntu:~/0x08. Recursion$ gcc -Wall -pedantic -Werror -Wextra -std=gnu89  2-main.c 2-strlen_recursion.c -o 2-strlen_recursion
julien@ubuntu:~/0x08. Recursion$ ./2-strlen_recursion 
14
julien@ubuntu:~/0x08. Recursion$ 
</code></pre>

</div>

<div class="list-group">
<!-- Task URLs -->

<!-- Github information -->
<div class="list-group-item">
<p><strong>Repo:</strong></p>
<ul>
<li>GitHub repository: <code>alx-low_level_programming</code></li>
<li>Directory: <code>0x08-recursion</code></li>
<li>File: <code>2-strlen_recursion.c</code></li>
</ul>
</div>

<!-- Self-paced manual review -->
</div>

<!-- Panel footer - Controls -->
<div class="panel-footer">
<div class="align-items-center d-flex justify-content-between">

<div>
<button class="student_task_done btn btn-default btn-sm no" data-task-id="916">
<span class="no"><i aria-hidden="true" class="fa fa-square-o "></i></span>
<span class="yes"><i aria-hidden="true" class="fa fa-check-square-o "></i></span>
<span class="pending"><i aria-hidden="true" class="fa fa-spinner  fa-pulse"></i></span>
Done<span class="no pending">?</span><span class="yes">!</span>
</button>

<button class="student-task-done-by btn btn-default btn-sm" data-task-id="916" data-batch-id="26" data-toggle="modal" data-target="#task-916-users-done-modal">
Help
</button>
<div class="modal fade users-done-modal" id="task-916-users-done-modal" data-task-id="916" data-batch-id="26">
<div class="modal-dialog">
<div class="modal-content">
<div class="modal-header">
<button type="button" class="close" data-dismiss="modal" aria-label="Close"><span aria-hidden="true">&times;</span></button>
<h4 class="modal-title">Students who are done with "2. Dreams feel real while we&#39;re in them. It&#39;s only when we wake up that we realize something was actually strange"</h4>
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


<button class="btn btn-default btn-sm check-your-task-916-modal-button" data-task-id="916" data-toggle="modal" data-target="#task-test-correction-916-correction-modal" id="task-num-2-check-code-btn" data-gtm-custom-event-name="task_checker_modal" data-gtm-custom-event-options='{&quot;taskId&quot;:916}'>
Check your code
</button>
<div class="modal fade task_correction_modal student_modal" id="task-test-correction-916-correction-modal">
<div class="modal-dialog">
<div class="modal-content">
<div class="modal-header">
<button type="button" class="close" data-dismiss="modal" aria-label="Close"><span aria-hidden="true">&times;</span></button>
<h4 class="modal-title">Correction of "2. Dreams feel real while we&#39;re in them. It&#39;s only when we wake up that we realize something was actually strange"</h4>
</div>
<div class="modal-body">
<div class="actions">
<center>
<div class="alert alert-info hidden"></div>

<button name="button" type="submit" class="btn btn-primary correction_request_test_send" data-task-id="916">Start a new test</button>
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
<button data-task-id="916">
<i aria-hidden="true" class="fa fa-info-circle "></i>
</button>
<div class="help-container" data-task-id="916">
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



<button class="btn btn-default btn-sm" data-toggle="modal" data-target="#container-specs-modal" data-gtm-custom-event-name="task_sandbox_modal" data-gtm-custom-event-options="{&quot;taskId&quot;:916}"><i aria-hidden="true" class="fa fa-terminal "></i><span>Get a sandbox</span></button>

</div>


<div class="fs-4">
</div>
</div>


</div>
</div>

</div>
<div data-role="task917" data-position="4" id="task-num-3">
<div class="panel panel-default task-card " id="task-917">
<span id="user_id" data-id="197885"></span>

<div class="panel-heading panel-heading-actions">
<h3 class="panel-title">
3. You mustn&#39;t be afraid to dream a little bigger, darling
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
<p>Write a function that returns the factorial of a given number.</p>

<ul>
<li>Prototype: <code>int factorial(int n);</code><br></li>
<li>If <code>n</code> is lower than <code>0</code>, the function should return <code>-1</code> to indicate an error<br></li>
<li>Factorial of <code>0</code> is <code>1</code></li>
</ul>

<pre><code>julien@ubuntu:~/0x08. Recursion$ cat 3-main.c
#include &quot;main.h&quot;
#include &lt;stdio.h&gt;

/**
* main - check the code
*
* Return: Always 0.
*/
int main(void)
{
int r;

r = factorial(1);
printf(&quot;%d\n&quot;, r);
r = factorial(5);
printf(&quot;%d\n&quot;, r);
r = factorial(10);
printf(&quot;%d\n&quot;, r);
r = factorial(-1024);
printf(&quot;%d\n&quot;, r);
return (0);
}
julien@ubuntu:~/0x08. Recursion$ gcc -Wall -pedantic -Werror -Wextra -std=gnu89 3-main.c 3-factorial.c -o 3-factorial
julien@ubuntu:~/0x08. Recursion$ ./3-factorial 
1
120
3628800
-1
julien@ubuntu:~/0x08. Recursion$
</code></pre>

</div>

<div class="list-group">
<!-- Task URLs -->

<!-- Github information -->
<div class="list-group-item">
<p><strong>Repo:</strong></p>
<ul>
<li>GitHub repository: <code>alx-low_level_programming</code></li>
<li>Directory: <code>0x08-recursion</code></li>
<li>File: <code>3-factorial.c</code></li>
</ul>
</div>

<!-- Self-paced manual review -->
</div>

<!-- Panel footer - Controls -->
<div class="panel-footer">
<div class="align-items-center d-flex justify-content-between">

<div>
<button class="student_task_done btn btn-default btn-sm no" data-task-id="917">
<span class="no"><i aria-hidden="true" class="fa fa-square-o "></i></span>
<span class="yes"><i aria-hidden="true" class="fa fa-check-square-o "></i></span>
<span class="pending"><i aria-hidden="true" class="fa fa-spinner  fa-pulse"></i></span>
Done<span class="no pending">?</span><span class="yes">!</span>
</button>

<button class="student-task-done-by btn btn-default btn-sm" data-task-id="917" data-batch-id="26" data-toggle="modal" data-target="#task-917-users-done-modal">
Help
</button>
<div class="modal fade users-done-modal" id="task-917-users-done-modal" data-task-id="917" data-batch-id="26">
<div class="modal-dialog">
<div class="modal-content">
<div class="modal-header">
<button type="button" class="close" data-dismiss="modal" aria-label="Close"><span aria-hidden="true">&times;</span></button>
<h4 class="modal-title">Students who are done with "3. You mustn&#39;t be afraid to dream a little bigger, darling"</h4>
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


<button class="btn btn-default btn-sm check-your-task-917-modal-button" data-task-id="917" data-toggle="modal" data-target="#task-test-correction-917-correction-modal" id="task-num-3-check-code-btn" data-gtm-custom-event-name="task_checker_modal" data-gtm-custom-event-options='{&quot;taskId&quot;:917}'>
Check your code
</button>
<div class="modal fade task_correction_modal student_modal" id="task-test-correction-917-correction-modal">
<div class="modal-dialog">
<div class="modal-content">
<div class="modal-header">
<button type="button" class="close" data-dismiss="modal" aria-label="Close"><span aria-hidden="true">&times;</span></button>
<h4 class="modal-title">Correction of "3. You mustn&#39;t be afraid to dream a little bigger, darling"</h4>
</div>
<div class="modal-body">
<div class="actions">
<center>
<div class="alert alert-info hidden"></div>

<button name="button" type="submit" class="btn btn-primary correction_request_test_send" data-task-id="917">Start a new test</button>
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
<button data-task-id="917">
<i aria-hidden="true" class="fa fa-info-circle "></i>
</button>
<div class="help-container" data-task-id="917">
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



<button class="btn btn-default btn-sm" data-toggle="modal" data-target="#container-specs-modal" data-gtm-custom-event-name="task_sandbox_modal" data-gtm-custom-event-options="{&quot;taskId&quot;:917}"><i aria-hidden="true" class="fa fa-terminal "></i><span>Get a sandbox</span></button>

</div>


<div class="fs-4">
</div>
</div>


</div>
</div>

</div>
<div data-role="task918" data-position="5" id="task-num-4">
<div class="panel panel-default task-card " id="task-918">
<span id="user_id" data-id="197885"></span>

<div class="panel-heading panel-heading-actions">
<h3 class="panel-title">
4. Once an idea has taken hold of the brain it&#39;s almost impossible to eradicate
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
<p>Write a function that returns the value of <code>x</code> raised to the power of <code>y</code>.</p>

<ul>
<li>Prototype: <code>int _pow_recursion(int x, int y);</code><br></li>
<li>If <code>y</code> is lower than <code>0</code>, the function should return <code>-1</code></li>
</ul>

<p>FYI: The standard library provides a different function: <code>pow</code>. Run <code>man pow</code> to learn more.</p>

<pre><code>julien@ubuntu:~/0x08. Recursion$ cat 4-main.c
#include &quot;main.h&quot;
#include &lt;stdio.h&gt;

/**
* main - check the code
*
* Return: Always 0.
*/
int main(void)
{
int r;

r = _pow_recursion(1, 10);
printf(&quot;%d\n&quot;, r);
r = _pow_recursion(1024, 0);
printf(&quot;%d\n&quot;, r);
r = _pow_recursion(2, 16);
printf(&quot;%d\n&quot;, r);
r = _pow_recursion(5, 2);
printf(&quot;%d\n&quot;, r);
r = _pow_recursion(5, -2);
printf(&quot;%d\n&quot;, r);
r = _pow_recursion(-5, 3);
printf(&quot;%d\n&quot;, r);
return (0);
}
julien@ubuntu:~/0x08. Recursion$ gcc -Wall -pedantic -Werror -Wextra -std=gnu89 4-main.c 4-pow_recursion.c -o 4-pow
julien@ubuntu:~/0x08. Recursion$ ./4-pow 
1
1
65536
25
-1
-125
julien@ubuntu:~/0x08. Recursion$ 
</code></pre>

</div>

<div class="list-group">
<!-- Task URLs -->

<!-- Github information -->
<div class="list-group-item">
<p><strong>Repo:</strong></p>
<ul>
<li>GitHub repository: <code>alx-low_level_programming</code></li>
<li>Directory: <code>0x08-recursion</code></li>
<li>File: <code>4-pow_recursion.c</code></li>
</ul>
</div>

<!-- Self-paced manual review -->
</div>

<!-- Panel footer - Controls -->
<div class="panel-footer">
<div class="align-items-center d-flex justify-content-between">

<div>
<button class="student_task_done btn btn-default btn-sm no" data-task-id="918">
<span class="no"><i aria-hidden="true" class="fa fa-square-o "></i></span>
<span class="yes"><i aria-hidden="true" class="fa fa-check-square-o "></i></span>
<span class="pending"><i aria-hidden="true" class="fa fa-spinner  fa-pulse"></i></span>
Done<span class="no pending">?</span><span class="yes">!</span>
</button>

<button class="student-task-done-by btn btn-default btn-sm" data-task-id="918" data-batch-id="26" data-toggle="modal" data-target="#task-918-users-done-modal">
Help
</button>
<div class="modal fade users-done-modal" id="task-918-users-done-modal" data-task-id="918" data-batch-id="26">
<div class="modal-dialog">
<div class="modal-content">
<div class="modal-header">
<button type="button" class="close" data-dismiss="modal" aria-label="Close"><span aria-hidden="true">&times;</span></button>
<h4 class="modal-title">Students who are done with "4. Once an idea has taken hold of the brain it&#39;s almost impossible to eradicate"</h4>
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


<button class="btn btn-default btn-sm check-your-task-918-modal-button" data-task-id="918" data-toggle="modal" data-target="#task-test-correction-918-correction-modal" id="task-num-4-check-code-btn" data-gtm-custom-event-name="task_checker_modal" data-gtm-custom-event-options='{&quot;taskId&quot;:918}'>
Check your code
</button>
<div class="modal fade task_correction_modal student_modal" id="task-test-correction-918-correction-modal">
<div class="modal-dialog">
<div class="modal-content">
<div class="modal-header">
<button type="button" class="close" data-dismiss="modal" aria-label="Close"><span aria-hidden="true">&times;</span></button>
<h4 class="modal-title">Correction of "4. Once an idea has taken hold of the brain it&#39;s almost impossible to eradicate"</h4>
</div>
<div class="modal-body">
<div class="actions">
<center>
<div class="alert alert-info hidden"></div>

<button name="button" type="submit" class="btn btn-primary correction_request_test_send" data-task-id="918">Start a new test</button>
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
<button data-task-id="918">
<i aria-hidden="true" class="fa fa-info-circle "></i>
</button>
<div class="help-container" data-task-id="918">
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



<button class="btn btn-default btn-sm" data-toggle="modal" data-target="#container-specs-modal" data-gtm-custom-event-name="task_sandbox_modal" data-gtm-custom-event-options="{&quot;taskId&quot;:918}"><i aria-hidden="true" class="fa fa-terminal "></i><span>Get a sandbox</span></button>

</div>


<div class="fs-4">
</div>
</div>


</div>
</div>

</div>
<div data-role="task919" data-position="6" id="task-num-5">
<div class="panel panel-default task-card " id="task-919">
<span id="user_id" data-id="197885"></span>

<div class="panel-heading panel-heading-actions">
<h3 class="panel-title">
5. Your subconscious is looking for the dreamer
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
<p>Write a function that returns the natural square root of a number.</p>

<ul>
<li>Prototype: <code>int _sqrt_recursion(int n);</code><br></li>
<li>If <code>n</code> does not have a natural square root, the function should return <code>-1</code></li>
</ul>

<p>FYI: The standard library provides a different function: <code>sqrt</code>. Run <code>man sqrt</code> to learn more.</p>

<pre><code>julien@ubuntu:~/0x08. Recursion$ cat 5-main.c 
#include &quot;main.h&quot;
#include &lt;stdio.h&gt;

/**
* main - check the code
*
* Return: Always 0.
*/
int main(void)
{
int r;

r = _sqrt_recursion(1);
printf(&quot;%d\n&quot;, r);
r = _sqrt_recursion(1024);
printf(&quot;%d\n&quot;, r);
r = _sqrt_recursion(16);
printf(&quot;%d\n&quot;, r);
r = _sqrt_recursion(17);
printf(&quot;%d\n&quot;, r);
r = _sqrt_recursion(25);
printf(&quot;%d\n&quot;, r);
r = _sqrt_recursion(-1);
printf(&quot;%d\n&quot;, r);
return (0);
}
julien@ubuntu:~/0x08. gcc -Wall -pedantic -Werror -Wextra -std=gnu89 5-main.c 5-sqrt_recursion.c -o 5-sqrt
julien@ubuntu:~/0x08. Recursion$ ./5-sqrt 
1
32
4
-1
5
-1
julien@ubuntu:~/0x08. Recursion$ 
</code></pre>

</div>

<div class="list-group">
<!-- Task URLs -->

<!-- Github information -->
<div class="list-group-item">
<p><strong>Repo:</strong></p>
<ul>
<li>GitHub repository: <code>alx-low_level_programming</code></li>
<li>Directory: <code>0x08-recursion</code></li>
<li>File: <code>5-sqrt_recursion.c</code></li>
</ul>
</div>

<!-- Self-paced manual review -->
</div>

<!-- Panel footer - Controls -->
<div class="panel-footer">
<div class="align-items-center d-flex justify-content-between">

<div>
<button class="student_task_done btn btn-default btn-sm no" data-task-id="919">
<span class="no"><i aria-hidden="true" class="fa fa-square-o "></i></span>
<span class="yes"><i aria-hidden="true" class="fa fa-check-square-o "></i></span>
<span class="pending"><i aria-hidden="true" class="fa fa-spinner  fa-pulse"></i></span>
Done<span class="no pending">?</span><span class="yes">!</span>
</button>

<button class="student-task-done-by btn btn-default btn-sm" data-task-id="919" data-batch-id="26" data-toggle="modal" data-target="#task-919-users-done-modal">
Help
</button>
<div class="modal fade users-done-modal" id="task-919-users-done-modal" data-task-id="919" data-batch-id="26">
<div class="modal-dialog">
<div class="modal-content">
<div class="modal-header">
<button type="button" class="close" data-dismiss="modal" aria-label="Close"><span aria-hidden="true">&times;</span></button>
<h4 class="modal-title">Students who are done with "5. Your subconscious is looking for the dreamer"</h4>
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


<button class="btn btn-default btn-sm check-your-task-919-modal-button" data-task-id="919" data-toggle="modal" data-target="#task-test-correction-919-correction-modal" id="task-num-5-check-code-btn" data-gtm-custom-event-name="task_checker_modal" data-gtm-custom-event-options='{&quot;taskId&quot;:919}'>
Check your code
</button>
<div class="modal fade task_correction_modal student_modal" id="task-test-correction-919-correction-modal">
<div class="modal-dialog">
<div class="modal-content">
<div class="modal-header">
<button type="button" class="close" data-dismiss="modal" aria-label="Close"><span aria-hidden="true">&times;</span></button>
<h4 class="modal-title">Correction of "5. Your subconscious is looking for the dreamer"</h4>
</div>
<div class="modal-body">
<div class="actions">
<center>
<div class="alert alert-info hidden"></div>

<button name="button" type="submit" class="btn btn-primary correction_request_test_send" data-task-id="919">Start a new test</button>
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
<button data-task-id="919">
<i aria-hidden="true" class="fa fa-info-circle "></i>
</button>
<div class="help-container" data-task-id="919">
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



<button class="btn btn-default btn-sm" data-toggle="modal" data-target="#container-specs-modal" data-gtm-custom-event-name="task_sandbox_modal" data-gtm-custom-event-options="{&quot;taskId&quot;:919}"><i aria-hidden="true" class="fa fa-terminal "></i><span>Get a sandbox</span></button>

</div>


<div class="fs-4">
</div>
</div>


</div>
</div>

</div>
<div data-role="task920" data-position="7" id="task-num-6">
<div class="panel panel-default task-card " id="task-920">
<span id="user_id" data-id="197885"></span>

<div class="panel-heading panel-heading-actions">
<h3 class="panel-title">
6. Inception. Is it possible?
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
<p>Write a function that returns <code>1</code> if the input integer is a <a href="/rltoken/bjG_8Gu-_0rwbYA_tAv2Yw" title="prime number" target="_blank">prime number</a>, otherwise return <code>0</code>.</p>

<ul>
<li>Prototype: <code>int is_prime_number(int n);</code></li>
</ul>

<pre><code>julien@ubuntu:~/0x08. Recursion$ cat 6-main.c
#include &quot;main.h&quot;
#include &lt;stdio.h&gt;

/**
* main - check the code
*
* Return: Always 0.
*/
int main(void)
{
int r;

r = is_prime_number(1);
printf(&quot;%d\n&quot;, r);
r = is_prime_number(1024);
printf(&quot;%d\n&quot;, r);
r = is_prime_number(16);
printf(&quot;%d\n&quot;, r);
r = is_prime_number(17);
printf(&quot;%d\n&quot;, r);
r = is_prime_number(25);
printf(&quot;%d\n&quot;, r);
r = is_prime_number(-1);
printf(&quot;%d\n&quot;, r);
r = is_prime_number(113);
printf(&quot;%d\n&quot;, r);
r = is_prime_number(7919);
printf(&quot;%d\n&quot;, r);
return (0);
}
julien@ubuntu:~/0x08. Recursion$ gcc -Wall -pedantic -Werror -Wextra -std=gnu89 6-main.c 6-is_prime_number.c -o 6-prime
julien@ubuntu:~/0x08. Recursion$ ./6-prime 
0
0
0
1
0
0
1
1
julien@ubuntu:~/0x08. Recursion$ 
</code></pre>

</div>

<div class="list-group">
<!-- Task URLs -->

<!-- Github information -->
<div class="list-group-item">
<p><strong>Repo:</strong></p>
<ul>
<li>GitHub repository: <code>alx-low_level_programming</code></li>
<li>Directory: <code>0x08-recursion</code></li>
<li>File: <code>6-is_prime_number.c</code></li>
</ul>
</div>

<!-- Self-paced manual review -->
</div>

<!-- Panel footer - Controls -->
<div class="panel-footer">
<div class="align-items-center d-flex justify-content-between">

<div>
<button class="student_task_done btn btn-default btn-sm no" data-task-id="920">
<span class="no"><i aria-hidden="true" class="fa fa-square-o "></i></span>
<span class="yes"><i aria-hidden="true" class="fa fa-check-square-o "></i></span>
<span class="pending"><i aria-hidden="true" class="fa fa-spinner  fa-pulse"></i></span>
Done<span class="no pending">?</span><span class="yes">!</span>
</button>

<button class="student-task-done-by btn btn-default btn-sm" data-task-id="920" data-batch-id="26" data-toggle="modal" data-target="#task-920-users-done-modal">
Help
</button>
<div class="modal fade users-done-modal" id="task-920-users-done-modal" data-task-id="920" data-batch-id="26">
<div class="modal-dialog">
<div class="modal-content">
<div class="modal-header">
<button type="button" class="close" data-dismiss="modal" aria-label="Close"><span aria-hidden="true">&times;</span></button>
<h4 class="modal-title">Students who are done with "6. Inception. Is it possible?"</h4>
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


<button class="btn btn-default btn-sm check-your-task-920-modal-button" data-task-id="920" data-toggle="modal" data-target="#task-test-correction-920-correction-modal" id="task-num-6-check-code-btn" data-gtm-custom-event-name="task_checker_modal" data-gtm-custom-event-options='{&quot;taskId&quot;:920}'>
Check your code
</button>
<div class="modal fade task_correction_modal student_modal" id="task-test-correction-920-correction-modal">
<div class="modal-dialog">
<div class="modal-content">
<div class="modal-header">
<button type="button" class="close" data-dismiss="modal" aria-label="Close"><span aria-hidden="true">&times;</span></button>
<h4 class="modal-title">Correction of "6. Inception. Is it possible?"</h4>
</div>
<div class="modal-body">
<div class="actions">
<center>
<div class="alert alert-info hidden"></div>

<button name="button" type="submit" class="btn btn-primary correction_request_test_send" data-task-id="920">Start a new test</button>
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
<button data-task-id="920">
<i aria-hidden="true" class="fa fa-info-circle "></i>
</button>
<div class="help-container" data-task-id="920">
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



<button class="btn btn-default btn-sm" data-toggle="modal" data-target="#container-specs-modal" data-gtm-custom-event-name="task_sandbox_modal" data-gtm-custom-event-options="{&quot;taskId&quot;:920}"><i aria-hidden="true" class="fa fa-terminal "></i><span>Get a sandbox</span></button>

</div>


<div class="fs-4">
</div>
</div>


</div>
</div>

</div>

<p class="lg-gap">
<form class="button_to" method="post" action="/projects/219/unlock_optionals"><input id="unlock_optional_btn" class="btn btn-primary btn-block" data-confirm="Are you sure? Make sure you focused on the mandatory tasks first" data-disable-with="Unlocking 2 advanced tasks..." data-gtm-custom-event-name="project_unlock_advanced_tasks" type="submit" value="Done with the mandatory tasks? Unlock 2 advanced tasks now!" /><input type="hidden" name="authenticity_token" value="f7TrvDmNPo_20-meQa8s1acMHokf2QhhRQpnoBzZiqlUplkgZhUnKa7KrcWG4TeGJulUAsr5JEo3kHHAgoRgCQ" autocomplete="off" /></form>
</p>




<div class="modal fade" id="container-specs-modal"><div class="modal-dialog modal-lg"><div class="modal-content"><div class="modal-header"><button type="button" class="close" data-dismiss="modal" aria-label="Close"><span aria-hidden="true">&times;</span></button><h4 class="modal-title">Recommended Sandbox</h4></div><div class="modal-body"><div data-react-class="user_containers/ContainerSpecs" data-react-props="{&quot;containerModelName&quot;:&quot;Sandbox&quot;,&quot;containerSpecs&quot;:[{&quot;description&quot;:&quot;\u003cp\u003eBasic Ubuntu 20.04, with vim, emacs, curl, wget and all needed for Foundations\u003c/p\u003e\n&quot;,&quot;id&quot;:39,&quot;name&quot;:&quot;Ubuntu 20.04&quot;,&quot;online&quot;:true,&quot;container&quot;:{&quot;container_id&quot;:null,&quot;id&quot;:239271,&quot;restart_uri&quot;:&quot;/user_containers/239271/restart.json&quot;,&quot;status&quot;:&quot;asleep&quot;,&quot;uri&quot;:&quot;/user_containers/239271.json&quot;,&quot;wake_uri&quot;:&quot;/user_containers/239271/wake.json&quot;,&quot;webterm_uri&quot;:&quot;/user_containers/239271/webterm&quot;,&quot;host&quot;:null,&quot;password&quot;:&quot;2deaf74c415af9350d02&quot;,&quot;ports&quot;:{&quot;4000&quot;:49897,&quot;443&quot;:49900,&quot;8000&quot;:49894,&quot;8080&quot;:49893,&quot;3000&quot;:49899,&quot;3306&quot;:49898,&quot;5001&quot;:49895,&quot;80&quot;:49901,&quot;22&quot;:49902,&quot;5000&quot;:49896}}}],&quot;containersLimit&quot;:2,&quot;csrfToken&quot;:&quot;w4_KaUEtMUYnb2hfYANv6-gU6jDVTaKD2hzr7K8eEde2rIr5v8YK0Lt9dxbm6SQqT2H4nG_zF8efjVuKbzWqTQ&quot;,&quot;startStatusURI&quot;:&quot;/user_containers/start_status.json&quot;,&quot;startURI&quot;:&quot;/user_containers/start.json&quot;}" data-react-cache-id="user_containers/ContainerSpecs-0"></div></div></div></div></div>

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
