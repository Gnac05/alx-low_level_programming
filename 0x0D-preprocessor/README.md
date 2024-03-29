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


<title>Project: 0x0D. C - Preprocessor | ALX Africa Intranet</title>

<link rel="stylesheet" href="https://use.typekit.net/xgz4ilr.css">
<link rel="stylesheet" media="all" href="/assets/application_alx-bd8f82c7d5afa064449a69a1a91b6daef7bdb1c71c00f2646d99a16e5040963a.css" />
<script src="https://www.gstatic.com/charts/loader.js"></script>
<script src="/assets/application-fb2ab0247cdaae2347e87bac130aa052747dadacfa429138002d69271946027f.js"></script>
<link rel="shortcut icon" type="image/x-icon" href="/favicon_alx.ico" />
<meta name="csrf-param" content="authenticity_token" />
<meta name="csrf-token" content="lxzqfk1nceUqi3J4ulG-fiaubsgz90u7Q9UkexFQOUF_z6-oB6_42huRg7fT8l6MK5GtuHpoWiTzHwzQY9SIFQ" />

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
<div class="inner" style="background-image: url('https://s3.amazonaws.com/alx-intranet.hbtn.io/users/photos/000/197/885/thumb/joker.jpg?X-Amz-Algorithm=AWS4-HMAC-SHA256&amp;X-Amz-Credential=AKIARDDGGGOUSBVO6H7D%2F20230121%2Fus-east-1%2Fs3%2Faws4_request&amp;X-Amz-Date=20230121T091921Z&amp;X-Amz-Expires=600&amp;X-Amz-SignedHeaders=host&amp;X-Amz-Signature=11adbb1f490c6342836a722bb1e61906f4c9c170c3e6defd2698e05aae6e799f')"></div>
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
<div class="inner" style="background-image: url('https://s3.amazonaws.com/alx-intranet.hbtn.io/users/photos/000/197/885/thumb/joker.jpg?X-Amz-Algorithm=AWS4-HMAC-SHA256&amp;X-Amz-Credential=AKIARDDGGGOUSBVO6H7D%2F20230121%2Fus-east-1%2Fs3%2Faws4_request&amp;X-Amz-Date=20230121T091921Z&amp;X-Amz-Expires=600&amp;X-Amz-SignedHeaders=host&amp;X-Amz-Signature=11adbb1f490c6342836a722bb1e61906f4c9c170c3e6defd2698e05aae6e799f')"></div>
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

<h1 class="gap">0x0D. C - Preprocessor</h1>

<div data-react-class="tags/Tags" data-react-props="{&quot;tags&quot;:[{&quot;id&quot;:7,&quot;value&quot;:&quot;C&quot;,&quot;author_id&quot;:null,&quot;created_at&quot;:&quot;2022-06-16T01:59:38.000Z&quot;,&quot;updated_at&quot;:&quot;2022-06-16T01:59:38.000Z&quot;}]}" data-react-cache-id="tags/Tags-0"></div>

<div data-react-class="projects/ProjectMetadata" data-react-props="{&quot;metadata&quot;:{&quot;author&quot;:&quot;Julien Barbier \u0026 Johan Euphrosine, Software Engineer at Google&quot;,&quot;weight&quot;:1,&quot;correction&quot;:{&quot;released&quot;:true,&quot;requires_auto_correction&quot;:true,&quot;requires_manual_correction&quot;:false},&quot;bpi&quot;:{&quot;current&quot;:false,&quot;in_second_deadline&quot;:false,&quot;starts_at&quot;:&quot;2023-01-16T06:00:00.000+03:00&quot;,&quot;ends_at&quot;:&quot;2023-01-17T06:00:00.000+03:00&quot;,&quot;second_deadline_at&quot;:&quot;2023-01-18T06:00:00.000+03:00&quot;}}}" data-react-cache-id="projects/ProjectMetadata-0"></div>

<div class="sm-gap clean well">
<h4>In a nutshell&hellip;</h4>
<ul>


<li>
<strong>Auto QA review:</strong>
0.0/38 mandatory
</li>
<li>
<strong>Altogether:</strong>
&nbsp;<strong>0.0%</strong>
<ul>
<li>Mandatory: 0.0%</li>
<li>Optional: no optional tasks</li>
</ul>
</li>
</ul>
</div>







<div id="project_id" style="display: none" data-project-id="224"></div>







<div class="panel panel-default" id="project-description">
<div class="panel-body">
<h2>Resources</h2>

<p><strong>Read or watch</strong>:</p>

<ul>
<li><a href="/rltoken/X0ithSsqlz_D0c8V8uA1HQ" title="Understanding C program Compilation Process" target="_blank">Understanding C program Compilation Process</a> </li>
<li><a href="/rltoken/kaqIw352MSJ8xoi1xU09ZA" title="Object-like Macros" target="_blank">Object-like Macros</a> </li>
<li><a href="/rltoken/wcQZzunlgjepxExZFc2ORQ" title="Macro Arguments" target="_blank">Macro Arguments</a> </li>
<li><a href="/rltoken/S4zfCHzg82fUAxdt8_SaZQ" title="Pre Processor Directives in C" target="_blank">Pre Processor Directives in C</a> </li>
<li><a href="/rltoken/G33GiOIZofiIN4Tx9_acbQ" title="The C Preprocessor" target="_blank">The C Preprocessor</a> </li>
<li><a href="/rltoken/0OYhpL2cJfsIMBWhTuZsAA" title="Standard Predefined Macros" target="_blank">Standard Predefined Macros</a> </li>
<li><a href="/rltoken/oF2vgIZNePdU965jCEZLHA" title="include guard" target="_blank">include guard</a> </li>
<li><a href="/rltoken/ROl5xAMKX-JpenEqmf7FnQ" title="Common Predefined Macros" target="_blank">Common Predefined Macros</a> </li>
</ul>

<h2>Learning Objectives</h2>

<p>At the end of this project, you are expected to be able to <a href="/rltoken/ipbpW8pLm91jdr3YD-AENg" title="explain to anyone" target="_blank">explain to anyone</a>, <strong>without the help of Google</strong>:</p>

<h3>General</h3>

<ul>
<li>What are macros and how to use them</li>
<li>What are the most common predefined macros</li>
<li>How to include guard your header files</li>
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
<li>Don&rsquo;t forget to push your header file</li>
<li>All your header files should be include guarded</li>
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
<div class="quiz_question_item_container" data-role="quiz_question504" data-position="13">
<div class=" clearfix" id="quiz_question-504">

<h4 class="quiz_question">

Question #0
</h4>

<!-- Quiz question Body -->
<p>Why should we use include guards in our header files?</p>


<!-- Quiz question Answers -->
<ul class="quiz_question_answers" data-question-id="504">
<li class="">

<input type="radio" name="504" id="504-1508130019194" value="1508130019194" data-quiz-answer-id="1508130019194" data-quiz-question-id="504" disabled="disabled" />
<label for="504-1508130019194"><p>Because we said so, and we should never ask why.</p>
</label>
</li>

<li class="">

<input type="radio" name="504" id="504-1508130056514" value="1508130056514" data-quiz-answer-id="1508130056514" data-quiz-question-id="504" disabled="disabled" checked="checked" />
<label for="504-1508130056514"><p>To avoid the problem of double inclusion when dealing with the include directive.</p>
</label>
</li>

</ul>

<!-- Quiz question Tips -->

</div>

</div>
<div class="quiz_question_item_container" data-role="quiz_question494" data-position="3">
<div class=" clearfix" id="quiz_question-494">

<h4 class="quiz_question">

Question #1
</h4>

<!-- Quiz question Body -->
<p>The preprocessor generates object code</p>


<!-- Quiz question Answers -->
<ul class="quiz_question_answers" data-question-id="494">
<li class="">

<input type="radio" name="494" id="494-1508128511647" value="1508128511647" data-quiz-answer-id="1508128511647" data-quiz-question-id="494" disabled="disabled" />
<label for="494-1508128511647"><p>True</p>
</label>
</li>

<li class="">

<input type="radio" name="494" id="494-1508128514711" value="1508128514711" data-quiz-answer-id="1508128514711" data-quiz-question-id="494" disabled="disabled" checked="checked" />
<label for="494-1508128514711"><p>False</p>
</label>
</li>

</ul>

<!-- Quiz question Tips -->

</div>

</div>
<div class="quiz_question_item_container" data-role="quiz_question501" data-position="10">
<div class=" clearfix" id="quiz_question-501">

<h4 class="quiz_question">

Question #2
</h4>

<!-- Quiz question Body -->
<p>This code will try to allocate 1024 bytes in the heap:</p>

<pre><code>#define BUFFER_SIZE 1024
malloc(BUFFER_SIZE)
</code></pre>


<!-- Quiz question Answers -->
<ul class="quiz_question_answers" data-question-id="501">
<li class="">

<input type="radio" name="501" id="501-1508129449078" value="1508129449078" data-quiz-answer-id="1508129449078" data-quiz-question-id="501" disabled="disabled" checked="checked" />
<label for="501-1508129449078"><p>True</p>
</label>
</li>

<li class="">

<input type="radio" name="501" id="501-1508129451992" value="1508129451992" data-quiz-answer-id="1508129451992" data-quiz-question-id="501" disabled="disabled" />
<label for="501-1508129451992"><p>False</p>
</label>
</li>

</ul>

<!-- Quiz question Tips -->

</div>

</div>
<div class="quiz_question_item_container" data-role="quiz_question495" data-position="4">
<div class=" clearfix" id="quiz_question-495">

<h4 class="quiz_question">

Question #3
</h4>

<!-- Quiz question Body -->
<p>The preprocessor links our code with libraries.</p>


<!-- Quiz question Answers -->
<ul class="quiz_question_answers" data-question-id="495">
<li class="">

<input type="radio" name="495" id="495-1508128582791" value="1508128582791" data-quiz-answer-id="1508128582791" data-quiz-question-id="495" disabled="disabled" />
<label for="495-1508128582791"><p>True</p>
</label>
</li>

<li class="">

<input type="radio" name="495" id="495-1508128586198" value="1508128586198" data-quiz-answer-id="1508128586198" data-quiz-question-id="495" disabled="disabled" checked="checked" />
<label for="495-1508128586198"><p>False</p>
</label>
</li>

</ul>

<!-- Quiz question Tips -->

</div>

</div>
<div class="quiz_question_item_container" data-role="quiz_question500" data-position="9">
<div class=" clearfix" id="quiz_question-500">

<h4 class="quiz_question">

Question #4
</h4>

<!-- Quiz question Body -->
<p>What will be the last 5 lines of the output of the command <code>gcc -E</code> on this code?</p>

<pre><code>#include &lt;stdlib.h&gt;

int main(void)
{
NULL;
return (EXIT_SUCCESS);
}
</code></pre>


<!-- Quiz question Answers -->
<ul class="quiz_question_answers" data-question-id="500">
<li class="">

<input type="radio" name="500" id="500-1508129309792" value="1508129309792" data-quiz-answer-id="1508129309792" data-quiz-question-id="500" disabled="disabled" checked="checked" />
<label for="500-1508129309792"><pre><code>int main(void)
{
((void *)0);
return (0);
}
</code></pre>
</label>
</li>

<li class="">

<input type="radio" name="500" id="500-1508129245032" value="1508129245032" data-quiz-answer-id="1508129245032" data-quiz-question-id="500" disabled="disabled" />
<label for="500-1508129245032"><pre><code>int main(void)
{
0;
return (0);
}
</code></pre>
</label>
</li>

<li class="">

<input type="radio" name="500" id="500-1508129316671" value="1508129316671" data-quiz-answer-id="1508129316671" data-quiz-question-id="500" disabled="disabled" />
<label for="500-1508129316671"><pre><code>int main(void)
{
&#39;\0&#39;;
return (0);
}
</code></pre>
</label>
</li>

<li class="">

<input type="radio" name="500" id="500-1508129274994" value="1508129274994" data-quiz-answer-id="1508129274994" data-quiz-question-id="500" disabled="disabled" />
<label for="500-1508129274994"><pre><code>int main()
{
0;
return (0);
}
</code></pre>
</label>
</li>

</ul>

<!-- Quiz question Tips -->

</div>

</div>
<div class="quiz_question_item_container" data-role="quiz_question498" data-position="7">
<div class=" clearfix" id="quiz_question-498">

<h4 class="quiz_question">

Question #5
</h4>

<!-- Quiz question Body -->
<p>What is the <code>gcc</code> option that runs only the preprocessor?</p>


<!-- Quiz question Answers -->
<ul class="quiz_question_answers" data-question-id="498">
<li class="">

<input type="radio" name="498" id="498-1508128950206" value="1508128950206" data-quiz-answer-id="1508128950206" data-quiz-question-id="498" disabled="disabled" checked="checked" />
<label for="498-1508128950206"><p>-E</p>
</label>
</li>

<li class="">

<input type="radio" name="498" id="498-1508128924350" value="1508128924350" data-quiz-answer-id="1508128924350" data-quiz-question-id="498" disabled="disabled" />
<label for="498-1508128924350"><p>-a</p>
</label>
</li>

<li class="">

<input type="radio" name="498" id="498-1508128931055" value="1508128931055" data-quiz-answer-id="1508128931055" data-quiz-question-id="498" disabled="disabled" />
<label for="498-1508128931055"><p>-P</p>
</label>
</li>

<li class="">

<input type="radio" name="498" id="498-1508128938727" value="1508128938727" data-quiz-answer-id="1508128938727" data-quiz-question-id="498" disabled="disabled" />
<label for="498-1508128938727"><p>-pedantic</p>
</label>
</li>

<li class="">

<input type="radio" name="498" id="498-1508128935175" value="1508128935175" data-quiz-answer-id="1508128935175" data-quiz-question-id="498" disabled="disabled" />
<label for="498-1508128935175"><p>-p</p>
</label>
</li>

<li class="">

<input type="radio" name="498" id="498-1508128961438" value="1508128961438" data-quiz-answer-id="1508128961438" data-quiz-question-id="498" disabled="disabled" />
<label for="498-1508128961438"><p>-preprocessor</p>
</label>
</li>

<li class="">

<input type="radio" name="498" id="498-1508128954254" value="1508128954254" data-quiz-answer-id="1508128954254" data-quiz-question-id="498" disabled="disabled" />
<label for="498-1508128954254"><p>-cisfun</p>
</label>
</li>

</ul>

<!-- Quiz question Tips -->

</div>

</div>
<div class="quiz_question_item_container" data-role="quiz_question492" data-position="1">
<div class=" clearfix" id="quiz_question-492">

<h4 class="quiz_question">

Question #6
</h4>

<!-- Quiz question Body -->
<p>What are the steps of compilation?</p>


<!-- Quiz question Answers -->
<ul class="quiz_question_answers" data-question-id="492">
<li class="">

<input type="radio" name="492" id="492-1508128296687" value="1508128296687" data-quiz-answer-id="1508128296687" data-quiz-question-id="492" disabled="disabled" />
<label for="492-1508128296687"><ol>
<li>compiler 2. preprocessor 3. assembler 4. linker</li>
</ol>
</label>
</li>

<li class="">

<input type="radio" name="492" id="492-1508128363902" value="1508128363902" data-quiz-answer-id="1508128363902" data-quiz-question-id="492" disabled="disabled" />
<label for="492-1508128363902"><ol>
<li>preprocessor 2.compiler 3. linker 4. assembler</li>
</ol>
</label>
</li>

<li class="">

<input type="radio" name="492" id="492-1508128328086" value="1508128328086" data-quiz-answer-id="1508128328086" data-quiz-question-id="492" disabled="disabled" checked="checked" />
<label for="492-1508128328086"><ol>
<li>preprocessor 2.compiler 3. assembler 4. linker</li>
</ol>
</label>
</li>

</ul>

<!-- Quiz question Tips -->

</div>

</div>
<div class="quiz_question_item_container" data-role="quiz_question502" data-position="11">
<div class=" clearfix" id="quiz_question-502">

<h4 class="quiz_question">

Question #7
</h4>

<!-- Quiz question Body -->
<p>What does the macro <code>TABLESIZE</code> expand to?</p>

<pre><code>#define BUFSIZE 1020
#define TABLESIZE BUFSIZE
#undef BUFSIZE
#define BUFSIZE 37
</code></pre>


<!-- Quiz question Answers -->
<ul class="quiz_question_answers" data-question-id="502">
<li class="">

<input type="radio" name="502" id="502-1508129515536" value="1508129515536" data-quiz-answer-id="1508129515536" data-quiz-question-id="502" disabled="disabled" />
<label for="502-1508129515536"><p>1020</p>
</label>
</li>

<li class="">

<input type="radio" name="502" id="502-1508129525328" value="1508129525328" data-quiz-answer-id="1508129525328" data-quiz-question-id="502" disabled="disabled" />
<label for="502-1508129525328"><p>nothing</p>
</label>
</li>

<li class="">

<input type="radio" name="502" id="502-1508129520464" value="1508129520464" data-quiz-answer-id="1508129520464" data-quiz-question-id="502" disabled="disabled" checked="checked" />
<label for="502-1508129520464"><p>37</p>
</label>
</li>

</ul>

<!-- Quiz question Tips -->

</div>

</div>
<div class="quiz_question_item_container" data-role="quiz_question496" data-position="5">
<div class=" clearfix" id="quiz_question-496">

<h4 class="quiz_question">

Question #8
</h4>

<!-- Quiz question Body -->
<p>This portion of code is actually using the library stdlib.</p>

<pre><code>#include &lt;stdlib.h&gt;
</code></pre>


<!-- Quiz question Answers -->
<ul class="quiz_question_answers" data-question-id="496">
<li class="">

<input type="radio" name="496" id="496-1508128673527" value="1508128673527" data-quiz-answer-id="1508128673527" data-quiz-question-id="496" disabled="disabled" />
<label for="496-1508128673527"><p>True</p>
</label>
</li>

<li class="">

<input type="radio" name="496" id="496-1508128676270" value="1508128676270" data-quiz-answer-id="1508128676270" data-quiz-question-id="496" disabled="disabled" checked="checked" />
<label for="496-1508128676270"><p>False</p>
</label>
</li>

</ul>

<!-- Quiz question Tips -->

</div>

</div>
<div class="quiz_question_item_container" data-role="quiz_question497" data-position="6">
<div class=" clearfix" id="quiz_question-497">

<h4 class="quiz_question">

Question #9
</h4>

<!-- Quiz question Body -->
<p>The preprocessor removes all comments</p>


<!-- Quiz question Answers -->
<ul class="quiz_question_answers" data-question-id="497">
<li class="">

<input type="radio" name="497" id="497-1508128730238" value="1508128730238" data-quiz-answer-id="1508128730238" data-quiz-question-id="497" disabled="disabled" checked="checked" />
<label for="497-1508128730238"><p>True</p>
</label>
</li>

<li class="">

<input type="radio" name="497" id="497-1508128734511" value="1508128734511" data-quiz-answer-id="1508128734511" data-quiz-question-id="497" disabled="disabled" />
<label for="497-1508128734511"><p>False</p>
</label>
</li>

</ul>

<!-- Quiz question Tips -->

</div>

</div>
<div class="quiz_question_item_container" data-role="quiz_question506" data-position="15">
<div class=" clearfix" id="quiz_question-506">

<h4 class="quiz_question">

Question #10
</h4>

<!-- Quiz question Body -->
<p>What will be the output of this program? (on a standard 64 bits, Linux machine)</p>

<pre><code>#include &lt;stdio.h&gt;
#include &lt;stdlib.h&gt;

#define int char

int main(void)
{
int i;

i = 5;
printf (&quot;sizeof(i) = %lu&quot;, sizeof(i));
return (EXIT_SUCCESS);
}
</code></pre>


<!-- Quiz question Answers -->
<ul class="quiz_question_answers" data-question-id="506">
<li class="">

<input type="radio" name="506" id="506-1508130330856" value="1508130330856" data-quiz-answer-id="1508130330856" data-quiz-question-id="506" disabled="disabled" />
<label for="506-1508130330856"><p>sizeof(i) = 4</p>
</label>
</li>

<li class="">

<input type="radio" name="506" id="506-1508130226938" value="1508130226938" data-quiz-answer-id="1508130226938" data-quiz-question-id="506" disabled="disabled" />
<label for="506-1508130226938"><p>Segmentation Fault</p>
</label>
</li>

<li class="">

<input type="radio" name="506" id="506-1508130312433" value="1508130312433" data-quiz-answer-id="1508130312433" data-quiz-question-id="506" disabled="disabled" />
<label for="506-1508130312433"><p>It does not compile</p>
</label>
</li>

<li class="">

<input type="radio" name="506" id="506-1508130327730" value="1508130327730" data-quiz-answer-id="1508130327730" data-quiz-question-id="506" disabled="disabled" />
<label for="506-1508130327730"><p>sizeof(i) = 5</p>
</label>
</li>

<li class="">

<input type="radio" name="506" id="506-1508130318147" value="1508130318147" data-quiz-answer-id="1508130318147" data-quiz-question-id="506" disabled="disabled" />
<label for="506-1508130318147"><p>sizeof(i) = 8</p>
</label>
</li>

<li class="">

<input type="radio" name="506" id="506-1508130539733" value="1508130539733" data-quiz-answer-id="1508130539733" data-quiz-question-id="506" disabled="disabled" checked="checked" />
<label for="506-1508130539733"><p>sizeof(i) = 1</p>
</label>
</li>

</ul>

<!-- Quiz question Tips -->

</div>

</div>
<div class="quiz_question_item_container" data-role="quiz_question505" data-position="14">
<div class=" clearfix" id="quiz_question-505">

<h4 class="quiz_question">

Question #11
</h4>

<!-- Quiz question Body -->
<p>The macro <code>__FILE__</code> expands to the name of the current input file, in the form of a C string constant.</p>


<!-- Quiz question Answers -->
<ul class="quiz_question_answers" data-question-id="505">
<li class="">

<input type="radio" name="505" id="505-1508130174050" value="1508130174050" data-quiz-answer-id="1508130174050" data-quiz-question-id="505" disabled="disabled" checked="checked" />
<label for="505-1508130174050"><p>True</p>
</label>
</li>

<li class="">

<input type="radio" name="505" id="505-1508130178577" value="1508130178577" data-quiz-answer-id="1508130178577" data-quiz-question-id="505" disabled="disabled" />
<label for="505-1508130178577"><p>False</p>
</label>
</li>

</ul>

<!-- Quiz question Tips -->

</div>

</div>
<div class="quiz_question_item_container" data-role="quiz_question503" data-position="12">
<div class=" clearfix" id="quiz_question-503">

<h4 class="quiz_question">

Question #12
</h4>

<!-- Quiz question Body -->
<p>This is the correct way to define the macro <code>SUB</code>:</p>

<pre><code>#define SUB(a, b) a - b
</code></pre>


<!-- Quiz question Answers -->
<ul class="quiz_question_answers" data-question-id="503">
<li class="">

<input type="radio" name="503" id="503-1508129861297" value="1508129861297" data-quiz-answer-id="1508129861297" data-quiz-question-id="503" disabled="disabled" />
<label for="503-1508129861297"><p>No, it should be written this way:</p>

<pre><code>#define SUB(a, b) (a) - (b)
</code></pre>
</label>
</li>

<li class="">

<input type="radio" name="503" id="503-1508129788858" value="1508129788858" data-quiz-answer-id="1508129788858" data-quiz-question-id="503" disabled="disabled" />
<label for="503-1508129788858"><p>Yes</p>
</label>
</li>

<li class="">

<input type="radio" name="503" id="503-1508129872961" value="1508129872961" data-quiz-answer-id="1508129872961" data-quiz-question-id="503" disabled="disabled" checked="checked" />
<label for="503-1508129872961"><p>No, it should be written this way:</p>

<pre><code>#define SUB(a, b) ((a) - (b))
</code></pre>
</label>
</li>

<li class="">

<input type="radio" name="503" id="503-1508129793088" value="1508129793088" data-quiz-answer-id="1508129793088" data-quiz-question-id="503" disabled="disabled" />
<label for="503-1508129793088"><p>No, it should be written this way:</p>

<pre><code>#define SUB(a, b) (a - b)
</code></pre>
</label>
</li>

</ul>

<!-- Quiz question Tips -->

</div>

</div>
<div class="quiz_question_item_container" data-role="quiz_question493" data-position="2">
<div class=" clearfix" id="quiz_question-493">

<h4 class="quiz_question">

Question #13
</h4>

<!-- Quiz question Body -->
<p>The preprocessor generates assembly code</p>


<!-- Quiz question Answers -->
<ul class="quiz_question_answers" data-question-id="493">
<li class="">

<input type="radio" name="493" id="493-1508128460630" value="1508128460630" data-quiz-answer-id="1508128460630" data-quiz-question-id="493" disabled="disabled" />
<label for="493-1508128460630"><p>True</p>
</label>
</li>

<li class="">

<input type="radio" name="493" id="493-1508128464854" value="1508128464854" data-quiz-answer-id="1508128464854" data-quiz-question-id="493" disabled="disabled" checked="checked" />
<label for="493-1508128464854"><p>False</p>
</label>
</li>

</ul>

<!-- Quiz question Tips -->

</div>

</div>
<div class="quiz_question_item_container" data-role="quiz_question499" data-position="8">
<div class=" clearfix" id="quiz_question-499">

<h4 class="quiz_question">

Question #14
</h4>

<!-- Quiz question Body -->
<p><code>NULL</code> is a macro</p>


<!-- Quiz question Answers -->
<ul class="quiz_question_answers" data-question-id="499">
<li class="">

<input type="radio" name="499" id="499-1508129032846" value="1508129032846" data-quiz-answer-id="1508129032846" data-quiz-question-id="499" disabled="disabled" checked="checked" />
<label for="499-1508129032846"><p>True</p>
</label>
</li>

<li class="">

<input type="radio" name="499" id="499-1508129036190" value="1508129036190" data-quiz-answer-id="1508129036190" data-quiz-question-id="499" disabled="disabled" />
<label for="499-1508129036190"><p>False</p>
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

<div data-role="task945" data-position="1" id="task-num-0">
<div class="panel panel-default task-card " id="task-945">
<span id="user_id" data-id="197885"></span>

<div class="panel-heading panel-heading-actions">
<h3 class="panel-title">
0. Object-like Macro
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
<div class="task_progress_score_bar" data-task-id="945" data-correction-id="7890381">
<div class="task_progress_bar" style="width: 0.0%">
<div class="task_score_bar" style="width: NaN%">
</div>
</div>
<div class="task_progress_score_text">
Score: <span class="task_score_value">0.0%</span> (<span class="task_progress_value">Checks completed: 0.0%</span>)
</div>
</div>

<!-- Task Body -->
<p>Create a header file that defines a macro named <code>SIZE</code> as an abbreviation for the token <code>1024</code>.</p>

<pre><code>julien@ubuntu:~/0x0c. macro, structures$ cat 0-main.c
#include &quot;0-object_like_macro.h&quot;
#include &quot;0-object_like_macro.h&quot;
#include &lt;stdio.h&gt;

/**
* main - check the code
*
* Return: Always 0.
*/
int main(void)
{
int s;

s = 98 + SIZE;
printf(&quot;%d\n&quot;, s);
return (0);
}
julien@ubuntu:~/0x0c. macro, structures$ gcc -Wall -pedantic -Werror -Wextra -std=gnu89 0-main.c -o a
julien@ubuntu:~/0x0c. macro, structures$ ./a 
1122
julien@ubuntu:~/0x0c. macro, structures$ 
</code></pre>

</div>

<div class="list-group">
<!-- Task URLs -->

<!-- Github information -->
<div class="list-group-item">
<p><strong>Repo:</strong></p>
<ul>
<li>GitHub repository: <code>alx-low_level_programming</code></li>
<li>Directory: <code>0x0D-preprocessor</code></li>
<li>File: <code>0-object_like_macro.h</code></li>
</ul>
</div>

<!-- Self-paced manual review -->
</div>

<!-- Panel footer - Controls -->
<div class="panel-footer">
<div class="align-items-center d-flex justify-content-between">

<div>
<button class="student_task_done btn btn-default btn-sm no" data-task-id="945">
<span class="no"><i aria-hidden="true" class="fa fa-square-o "></i></span>
<span class="yes"><i aria-hidden="true" class="fa fa-check-square-o "></i></span>
<span class="pending"><i aria-hidden="true" class="fa fa-spinner  fa-pulse"></i></span>
Done<span class="no pending">?</span><span class="yes">!</span>
</button>

<button class="student-task-done-by btn btn-default btn-sm" data-task-id="945" data-batch-id="26" data-toggle="modal" data-target="#task-945-users-done-modal">
Help
</button>
<div class="modal fade users-done-modal" id="task-945-users-done-modal" data-task-id="945" data-batch-id="26">
<div class="modal-dialog">
<div class="modal-content">
<div class="modal-header">
<button type="button" class="close" data-dismiss="modal" aria-label="Close"><span aria-hidden="true">&times;</span></button>
<h4 class="modal-title">Students who are done with "0. Object-like Macro"</h4>
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


<button class="btn btn-default btn-sm check-your-task-945-modal-button" data-task-id="945" data-toggle="modal" data-target="#task-test-correction-945-correction-modal" id="task-num-0-check-code-btn" data-gtm-custom-event-name="task_checker_modal" data-gtm-custom-event-options='{&quot;taskId&quot;:945}'>
Check your code
</button>
<div class="modal fade task_correction_modal student_modal" id="task-test-correction-945-correction-modal">
<div class="modal-dialog">
<div class="modal-content">
<div class="modal-header">
<button type="button" class="close" data-dismiss="modal" aria-label="Close"><span aria-hidden="true">&times;</span></button>
<h4 class="modal-title">Correction of "0. Object-like Macro"</h4>
</div>
<div class="modal-body">
<div class="actions">
<center>
<div class="alert alert-info hidden"></div>

<button name="button" type="submit" class="btn btn-primary correction_request_test_send" data-task-id="945">Start a new test</button>
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
<button data-task-id="945">
<i aria-hidden="true" class="fa fa-info-circle "></i>
</button>
<div class="help-container" data-task-id="945">
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


<button class="btn btn-primary btn-sm task_ask_new_correction " data-task-id="945" data-correction-id="7890381">
Ask for a new correction
<span class="in_progress_info">: in progress...</span>
<span class="error_occurred_info">: an error occurred</span>
</button>



<button class="btn btn-default btn-sm" data-task-id="945" data-toggle="modal" data-target="#task-qa-review-945-modal" data-gtm-custom-event-name="task_qa_review_modal" data-gtm-custom-event-options='{&quot;taskId&quot;:945}'>
QA Review
</button>
<div class="modal fade task_get_qa_review" id="task-qa-review-945-modal" data-correction-id="7890381" data-task-id="945">
<div class="modal-dialog modal-lg">
<div class="modal-content">
<div class="modal-header">
<button type="button" class="close" data-dismiss="modal" aria-label="Close"><span aria-hidden="true">&times;</span></button>
<h4 class="modal-title">0. Object-like Macro</h4>
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
<div data-role="task946" data-position="2" id="task-num-1">
<div class="panel panel-default task-card " id="task-946">
<span id="user_id" data-id="197885"></span>

<div class="panel-heading panel-heading-actions">
<h3 class="panel-title">
1. Pi
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
<div class="task_progress_score_bar" data-task-id="946" data-correction-id="7890381">
<div class="task_progress_bar" style="width: 0.0%">
<div class="task_score_bar" style="width: NaN%">
</div>
</div>
<div class="task_progress_score_text">
Score: <span class="task_score_value">0.0%</span> (<span class="task_progress_value">Checks completed: 0.0%</span>)
</div>
</div>

<!-- Task Body -->
<p>Create a header file that defines a macro named <code>PI</code> as an abbreviation for the token <code>3.14159265359</code>.</p>

<pre><code>julien@ubuntu:~/0x0c. macro, structures$ cat 1-main.c
#include &quot;1-pi.h&quot;
#include &quot;1-pi.h&quot;
#include &lt;stdio.h&gt;

/**
* main - check the code
*
* Return: Always 0.
*/
int main(void)
{
float a;
float r;

r = 98;
a = PI * r * r;
printf(&quot;%.3f\n&quot;, a);
return (0);
}
julien@ubuntu:~/0x0c. macro, structures$ gcc -Wall -pedantic -Werror -Wextra -std=gnu89 1-main.c -o b
julien@ubuntu:~/0x0c. macro, structures$ ./b
30171.855
julien@ubuntu:~/0x0c. macro, structures$ 
</code></pre>

</div>

<div class="list-group">
<!-- Task URLs -->

<!-- Github information -->
<div class="list-group-item">
<p><strong>Repo:</strong></p>
<ul>
<li>GitHub repository: <code>alx-low_level_programming</code></li>
<li>Directory: <code>0x0D-preprocessor</code></li>
<li>File: <code>1-pi.h</code></li>
</ul>
</div>

<!-- Self-paced manual review -->
</div>

<!-- Panel footer - Controls -->
<div class="panel-footer">
<div class="align-items-center d-flex justify-content-between">

<div>
<button class="student_task_done btn btn-default btn-sm no" data-task-id="946">
<span class="no"><i aria-hidden="true" class="fa fa-square-o "></i></span>
<span class="yes"><i aria-hidden="true" class="fa fa-check-square-o "></i></span>
<span class="pending"><i aria-hidden="true" class="fa fa-spinner  fa-pulse"></i></span>
Done<span class="no pending">?</span><span class="yes">!</span>
</button>

<button class="student-task-done-by btn btn-default btn-sm" data-task-id="946" data-batch-id="26" data-toggle="modal" data-target="#task-946-users-done-modal">
Help
</button>
<div class="modal fade users-done-modal" id="task-946-users-done-modal" data-task-id="946" data-batch-id="26">
<div class="modal-dialog">
<div class="modal-content">
<div class="modal-header">
<button type="button" class="close" data-dismiss="modal" aria-label="Close"><span aria-hidden="true">&times;</span></button>
<h4 class="modal-title">Students who are done with "1. Pi"</h4>
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


<button class="btn btn-default btn-sm check-your-task-946-modal-button" data-task-id="946" data-toggle="modal" data-target="#task-test-correction-946-correction-modal" id="task-num-1-check-code-btn" data-gtm-custom-event-name="task_checker_modal" data-gtm-custom-event-options='{&quot;taskId&quot;:946}'>
Check your code
</button>
<div class="modal fade task_correction_modal student_modal" id="task-test-correction-946-correction-modal">
<div class="modal-dialog">
<div class="modal-content">
<div class="modal-header">
<button type="button" class="close" data-dismiss="modal" aria-label="Close"><span aria-hidden="true">&times;</span></button>
<h4 class="modal-title">Correction of "1. Pi"</h4>
</div>
<div class="modal-body">
<div class="actions">
<center>
<div class="alert alert-info hidden"></div>

<button name="button" type="submit" class="btn btn-primary correction_request_test_send" data-task-id="946">Start a new test</button>
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
<button data-task-id="946">
<i aria-hidden="true" class="fa fa-info-circle "></i>
</button>
<div class="help-container" data-task-id="946">
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


<button class="btn btn-primary btn-sm task_ask_new_correction " data-task-id="946" data-correction-id="7890381">
Ask for a new correction
<span class="in_progress_info">: in progress...</span>
<span class="error_occurred_info">: an error occurred</span>
</button>



<button class="btn btn-default btn-sm" data-task-id="946" data-toggle="modal" data-target="#task-qa-review-946-modal" data-gtm-custom-event-name="task_qa_review_modal" data-gtm-custom-event-options='{&quot;taskId&quot;:946}'>
QA Review
</button>
<div class="modal fade task_get_qa_review" id="task-qa-review-946-modal" data-correction-id="7890381" data-task-id="946">
<div class="modal-dialog modal-lg">
<div class="modal-content">
<div class="modal-header">
<button type="button" class="close" data-dismiss="modal" aria-label="Close"><span aria-hidden="true">&times;</span></button>
<h4 class="modal-title">1. Pi</h4>
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
<div data-role="task947" data-position="3" id="task-num-2">
<div class="panel panel-default task-card " id="task-947">
<span id="user_id" data-id="197885"></span>

<div class="panel-heading panel-heading-actions">
<h3 class="panel-title">
2. File name
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
<div class="task_progress_score_bar" data-task-id="947" data-correction-id="7890381">
<div class="task_progress_bar" style="width: 0.0%">
<div class="task_score_bar" style="width: NaN%">
</div>
</div>
<div class="task_progress_score_text">
Score: <span class="task_score_value">0.0%</span> (<span class="task_progress_value">Checks completed: 0.0%</span>)
</div>
</div>

<!-- Task Body -->
<p>Write a program that prints the name of the file it was compiled from, followed by a new line.</p>

<ul>
<li>You are allowed to use the standard library</li>
</ul>

<pre><code>julien@ubuntu:~/0x0c. macro, structures$ gcc -Wall -pedantic -Werror -Wextra -std=gnu89 2-main.c -o c
julien@ubuntu:~/0x0c. macro, structures$ ./c 
2-main.c
julien@ubuntu:~/0x0c. macro, structures$ cp 2-main.c 02-main.c
julien@ubuntu:~/0x0c. macro, structures$ gcc -Wall -pedantic -Werror -Wextra -std=gnu89 02-main.c -o cc
julien@ubuntu:~/0x0c. macro, structures$ ./cc
02-main.c
julien@ubuntu:~/0x0c. macro, structures$ 
</code></pre>

</div>

<div class="list-group">
<!-- Task URLs -->

<!-- Github information -->
<div class="list-group-item">
<p><strong>Repo:</strong></p>
<ul>
<li>GitHub repository: <code>alx-low_level_programming</code></li>
<li>Directory: <code>0x0D-preprocessor</code></li>
<li>File: <code>2-main.c</code></li>
</ul>
</div>

<!-- Self-paced manual review -->
</div>

<!-- Panel footer - Controls -->
<div class="panel-footer">
<div class="align-items-center d-flex justify-content-between">

<div>
<button class="student_task_done btn btn-default btn-sm no" data-task-id="947">
<span class="no"><i aria-hidden="true" class="fa fa-square-o "></i></span>
<span class="yes"><i aria-hidden="true" class="fa fa-check-square-o "></i></span>
<span class="pending"><i aria-hidden="true" class="fa fa-spinner  fa-pulse"></i></span>
Done<span class="no pending">?</span><span class="yes">!</span>
</button>

<button class="student-task-done-by btn btn-default btn-sm" data-task-id="947" data-batch-id="26" data-toggle="modal" data-target="#task-947-users-done-modal">
Help
</button>
<div class="modal fade users-done-modal" id="task-947-users-done-modal" data-task-id="947" data-batch-id="26">
<div class="modal-dialog">
<div class="modal-content">
<div class="modal-header">
<button type="button" class="close" data-dismiss="modal" aria-label="Close"><span aria-hidden="true">&times;</span></button>
<h4 class="modal-title">Students who are done with "2. File name"</h4>
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


<button class="btn btn-default btn-sm check-your-task-947-modal-button" data-task-id="947" data-toggle="modal" data-target="#task-test-correction-947-correction-modal" id="task-num-2-check-code-btn" data-gtm-custom-event-name="task_checker_modal" data-gtm-custom-event-options='{&quot;taskId&quot;:947}'>
Check your code
</button>
<div class="modal fade task_correction_modal student_modal" id="task-test-correction-947-correction-modal">
<div class="modal-dialog">
<div class="modal-content">
<div class="modal-header">
<button type="button" class="close" data-dismiss="modal" aria-label="Close"><span aria-hidden="true">&times;</span></button>
<h4 class="modal-title">Correction of "2. File name"</h4>
</div>
<div class="modal-body">
<div class="actions">
<center>
<div class="alert alert-info hidden"></div>

<button name="button" type="submit" class="btn btn-primary correction_request_test_send" data-task-id="947">Start a new test</button>
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
<button data-task-id="947">
<i aria-hidden="true" class="fa fa-info-circle "></i>
</button>
<div class="help-container" data-task-id="947">
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


<button class="btn btn-primary btn-sm task_ask_new_correction " data-task-id="947" data-correction-id="7890381">
Ask for a new correction
<span class="in_progress_info">: in progress...</span>
<span class="error_occurred_info">: an error occurred</span>
</button>

<button class="btn btn-default btn-sm" data-toggle="modal" data-target="#container-specs-modal" data-gtm-custom-event-name="task_sandbox_modal" data-gtm-custom-event-options="{&quot;taskId&quot;:947}"><i aria-hidden="true" class="fa fa-terminal "></i><span>Get a sandbox</span></button>

<button class="btn btn-default btn-sm" data-task-id="947" data-toggle="modal" data-target="#task-qa-review-947-modal" data-gtm-custom-event-name="task_qa_review_modal" data-gtm-custom-event-options='{&quot;taskId&quot;:947}'>
QA Review
</button>
<div class="modal fade task_get_qa_review" id="task-qa-review-947-modal" data-correction-id="7890381" data-task-id="947">
<div class="modal-dialog modal-lg">
<div class="modal-content">
<div class="modal-header">
<button type="button" class="close" data-dismiss="modal" aria-label="Close"><span aria-hidden="true">&times;</span></button>
<h4 class="modal-title">2. File name</h4>
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
<div data-role="task948" data-position="4" id="task-num-3">
<div class="panel panel-default task-card " id="task-948">
<span id="user_id" data-id="197885"></span>

<div class="panel-heading panel-heading-actions">
<h3 class="panel-title">
3. Function-like macro
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
<div class="task_progress_score_bar" data-task-id="948" data-correction-id="7890381">
<div class="task_progress_bar" style="width: 0.0%">
<div class="task_score_bar" style="width: NaN%">
</div>
</div>
<div class="task_progress_score_text">
Score: <span class="task_score_value">0.0%</span> (<span class="task_progress_value">Checks completed: 0.0%</span>)
</div>
</div>

<!-- Task Body -->
<p>Write a function-like macro <code>ABS(x)</code> that computes the absolute value of a number <code>x</code>.</p>

<pre><code>julien@ubuntu:~/0x0c. macro, structures$ cat 3-main.c
#include &lt;stdio.h&gt;
#include &quot;3-function_like_macro.h&quot;
#include &quot;3-function_like_macro.h&quot;

/**
* main - check the code
*
* Return: Always 0.
*/
int main(void)
{
int i;
int j;

i = ABS(-98) * 10;
j = ABS(98) * 10;
printf(&quot;%d, %d\n&quot;, i, j);
return (0);
}
julien@ubuntu:~/0x0c. macro, structures$ gcc -Wall -pedantic -Werror -Wextra -std=gnu89 3-main.c -o d
julien@ubuntu:~/0x0c. macro, structures$ ./d 
980, 980
julien@ubuntu:~/0x0c. macro, structures$ 
</code></pre>

</div>

<div class="list-group">
<!-- Task URLs -->

<!-- Github information -->
<div class="list-group-item">
<p><strong>Repo:</strong></p>
<ul>
<li>GitHub repository: <code>alx-low_level_programming</code></li>
<li>Directory: <code>0x0D-preprocessor</code></li>
<li>File: <code>3-function_like_macro.h</code></li>
</ul>
</div>

<!-- Self-paced manual review -->
</div>

<!-- Panel footer - Controls -->
<div class="panel-footer">
<div class="align-items-center d-flex justify-content-between">

<div>
<button class="student_task_done btn btn-default btn-sm no" data-task-id="948">
<span class="no"><i aria-hidden="true" class="fa fa-square-o "></i></span>
<span class="yes"><i aria-hidden="true" class="fa fa-check-square-o "></i></span>
<span class="pending"><i aria-hidden="true" class="fa fa-spinner  fa-pulse"></i></span>
Done<span class="no pending">?</span><span class="yes">!</span>
</button>

<button class="student-task-done-by btn btn-default btn-sm" data-task-id="948" data-batch-id="26" data-toggle="modal" data-target="#task-948-users-done-modal">
Help
</button>
<div class="modal fade users-done-modal" id="task-948-users-done-modal" data-task-id="948" data-batch-id="26">
<div class="modal-dialog">
<div class="modal-content">
<div class="modal-header">
<button type="button" class="close" data-dismiss="modal" aria-label="Close"><span aria-hidden="true">&times;</span></button>
<h4 class="modal-title">Students who are done with "3. Function-like macro"</h4>
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


<button class="btn btn-default btn-sm check-your-task-948-modal-button" data-task-id="948" data-toggle="modal" data-target="#task-test-correction-948-correction-modal" id="task-num-3-check-code-btn" data-gtm-custom-event-name="task_checker_modal" data-gtm-custom-event-options='{&quot;taskId&quot;:948}'>
Check your code
</button>
<div class="modal fade task_correction_modal student_modal" id="task-test-correction-948-correction-modal">
<div class="modal-dialog">
<div class="modal-content">
<div class="modal-header">
<button type="button" class="close" data-dismiss="modal" aria-label="Close"><span aria-hidden="true">&times;</span></button>
<h4 class="modal-title">Correction of "3. Function-like macro"</h4>
</div>
<div class="modal-body">
<div class="actions">
<center>
<div class="alert alert-info hidden"></div>

<button name="button" type="submit" class="btn btn-primary correction_request_test_send" data-task-id="948">Start a new test</button>
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
<button data-task-id="948">
<i aria-hidden="true" class="fa fa-info-circle "></i>
</button>
<div class="help-container" data-task-id="948">
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


<button class="btn btn-primary btn-sm task_ask_new_correction " data-task-id="948" data-correction-id="7890381">
Ask for a new correction
<span class="in_progress_info">: in progress...</span>
<span class="error_occurred_info">: an error occurred</span>
</button>



<button class="btn btn-default btn-sm" data-task-id="948" data-toggle="modal" data-target="#task-qa-review-948-modal" data-gtm-custom-event-name="task_qa_review_modal" data-gtm-custom-event-options='{&quot;taskId&quot;:948}'>
QA Review
</button>
<div class="modal fade task_get_qa_review" id="task-qa-review-948-modal" data-correction-id="7890381" data-task-id="948">
<div class="modal-dialog modal-lg">
<div class="modal-content">
<div class="modal-header">
<button type="button" class="close" data-dismiss="modal" aria-label="Close"><span aria-hidden="true">&times;</span></button>
<h4 class="modal-title">3. Function-like macro</h4>
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
<div data-role="task949" data-position="5" id="task-num-4">
<div class="panel panel-default task-card " id="task-949">
<span id="user_id" data-id="197885"></span>

<div class="panel-heading panel-heading-actions">
<h3 class="panel-title">
4. SUM
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
<div class="task_progress_score_bar" data-task-id="949" data-correction-id="7890381">
<div class="task_progress_bar" style="width: 0.0%">
<div class="task_score_bar" style="width: NaN%">
</div>
</div>
<div class="task_progress_score_text">
Score: <span class="task_score_value">0.0%</span> (<span class="task_progress_value">Checks completed: 0.0%</span>)
</div>
</div>

<!-- Task Body -->
<p>Write a function-like macro <code>SUM(x, y)</code> that computes the sum of the numbers <code>x</code> and <code>y</code>.</p>

<pre><code>julien@ubuntu:~/0x0c. macro, structures$ cat 4-main.c
#include &lt;stdio.h&gt;
#include &quot;4-sum.h&quot;
#include &quot;4-sum.h&quot;

/**
* main - check the code
*
* Return: Always 0.
*/
int main(void)
{
int s;

s = SUM(98, 1024);
printf(&quot;%d\n&quot;, s);
return (0);
}
julien@ubuntu:~/0x0c. macro, structures$ gcc -Wall -pedantic -Werror -Wextra -std=gnu89 4-main.c -o e
julien@ubuntu:~/0x0c. macro, structures$ ./e 
1122
julien@ubuntu:~/0x0c. macro, structures$ 
</code></pre>

</div>

<div class="list-group">
<!-- Task URLs -->

<!-- Github information -->
<div class="list-group-item">
<p><strong>Repo:</strong></p>
<ul>
<li>GitHub repository: <code>alx-low_level_programming</code></li>
<li>Directory: <code>0x0D-preprocessor</code></li>
<li>File: <code>4-sum.h</code></li>
</ul>
</div>

<!-- Self-paced manual review -->
</div>

<!-- Panel footer - Controls -->
<div class="panel-footer">
<div class="align-items-center d-flex justify-content-between">

<div>
<button class="student_task_done btn btn-default btn-sm no" data-task-id="949">
<span class="no"><i aria-hidden="true" class="fa fa-square-o "></i></span>
<span class="yes"><i aria-hidden="true" class="fa fa-check-square-o "></i></span>
<span class="pending"><i aria-hidden="true" class="fa fa-spinner  fa-pulse"></i></span>
Done<span class="no pending">?</span><span class="yes">!</span>
</button>

<button class="student-task-done-by btn btn-default btn-sm" data-task-id="949" data-batch-id="26" data-toggle="modal" data-target="#task-949-users-done-modal">
Help
</button>
<div class="modal fade users-done-modal" id="task-949-users-done-modal" data-task-id="949" data-batch-id="26">
<div class="modal-dialog">
<div class="modal-content">
<div class="modal-header">
<button type="button" class="close" data-dismiss="modal" aria-label="Close"><span aria-hidden="true">&times;</span></button>
<h4 class="modal-title">Students who are done with "4. SUM"</h4>
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


<button class="btn btn-default btn-sm check-your-task-949-modal-button" data-task-id="949" data-toggle="modal" data-target="#task-test-correction-949-correction-modal" id="task-num-4-check-code-btn" data-gtm-custom-event-name="task_checker_modal" data-gtm-custom-event-options='{&quot;taskId&quot;:949}'>
Check your code
</button>
<div class="modal fade task_correction_modal student_modal" id="task-test-correction-949-correction-modal">
<div class="modal-dialog">
<div class="modal-content">
<div class="modal-header">
<button type="button" class="close" data-dismiss="modal" aria-label="Close"><span aria-hidden="true">&times;</span></button>
<h4 class="modal-title">Correction of "4. SUM"</h4>
</div>
<div class="modal-body">
<div class="actions">
<center>
<div class="alert alert-info hidden"></div>

<button name="button" type="submit" class="btn btn-primary correction_request_test_send" data-task-id="949">Start a new test</button>
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
<button data-task-id="949">
<i aria-hidden="true" class="fa fa-info-circle "></i>
</button>
<div class="help-container" data-task-id="949">
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


<button class="btn btn-primary btn-sm task_ask_new_correction " data-task-id="949" data-correction-id="7890381">
Ask for a new correction
<span class="in_progress_info">: in progress...</span>
<span class="error_occurred_info">: an error occurred</span>
</button>



<button class="btn btn-default btn-sm" data-task-id="949" data-toggle="modal" data-target="#task-qa-review-949-modal" data-gtm-custom-event-name="task_qa_review_modal" data-gtm-custom-event-options='{&quot;taskId&quot;:949}'>
QA Review
</button>
<div class="modal fade task_get_qa_review" id="task-qa-review-949-modal" data-correction-id="7890381" data-task-id="949">
<div class="modal-dialog modal-lg">
<div class="modal-content">
<div class="modal-header">
<button type="button" class="close" data-dismiss="modal" aria-label="Close"><span aria-hidden="true">&times;</span></button>
<h4 class="modal-title">4. SUM</h4>
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





<div class="modal fade" id="container-specs-modal"><div class="modal-dialog modal-lg"><div class="modal-content"><div class="modal-header"><button type="button" class="close" data-dismiss="modal" aria-label="Close"><span aria-hidden="true">&times;</span></button><h4 class="modal-title">Recommended Sandbox</h4></div><div class="modal-body"><div data-react-class="user_containers/ContainerSpecs" data-react-props="{&quot;containerModelName&quot;:&quot;Sandbox&quot;,&quot;containerSpecs&quot;:[{&quot;description&quot;:&quot;\u003cp\u003eBasic Ubuntu 20.04, with vim, emacs, curl, wget and all needed for Foundations\u003c/p\u003e\n&quot;,&quot;id&quot;:39,&quot;name&quot;:&quot;Ubuntu 20.04&quot;,&quot;online&quot;:true,&quot;container&quot;:{&quot;container_id&quot;:null,&quot;id&quot;:239271,&quot;restart_uri&quot;:&quot;/user_containers/239271/restart.json&quot;,&quot;status&quot;:&quot;asleep&quot;,&quot;uri&quot;:&quot;/user_containers/239271.json&quot;,&quot;wake_uri&quot;:&quot;/user_containers/239271/wake.json&quot;,&quot;webterm_uri&quot;:&quot;/user_containers/239271/webterm&quot;,&quot;host&quot;:null,&quot;password&quot;:&quot;2deaf74c415af9350d02&quot;,&quot;ports&quot;:{&quot;8080&quot;:56917,&quot;3306&quot;:56922,&quot;443&quot;:56924,&quot;5000&quot;:56920,&quot;5001&quot;:56919,&quot;8000&quot;:56918,&quot;22&quot;:56926,&quot;3000&quot;:56923,&quot;4000&quot;:56921,&quot;80&quot;:56925}}}],&quot;containersLimit&quot;:2,&quot;csrfToken&quot;:&quot;B0P02AgEgUc-I6KIqaeOvZCpmHOpW3EEsKUKd_VVdqbvkLEOQswIeA85U0fABG5PnZZbA-DEYJsAbyLch9HH8g&quot;,&quot;startStatusURI&quot;:&quot;/user_containers/start_status.json&quot;,&quot;startURI&quot;:&quot;/user_containers/start.json&quot;}" data-react-cache-id="user_containers/ContainerSpecs-0"></div></div></div></div></div>

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
