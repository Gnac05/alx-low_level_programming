# ALX Software Engeneer 

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

<script type="text/javascript" src="https://gc.kis.v2.scr.kaspersky-labs.com/FD126C42-EBFA-4E12-B309-BB3FDD723AC1/main.js?attr=96GsaOjXGODLpKneLXgeaxLKooGd1-TepaxSrTL0pRRhM5CrgbjclF59-JsGeTiTE6Dh9_LiZPbiVmBr-KmJWQ" charset="UTF-8"></script><script>
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


<title>Project: 0x02. C - Functions, nested loops | ALX Africa Intranet</title>

<link rel="stylesheet" href="https://use.typekit.net/xgz4ilr.css">
<link rel="stylesheet" media="all" href="/assets/application_alx-3bc505f2e3a9303a2388308cf98416618d0d78415692ec6a831f106956700814.css" />
<script src="https://www.gstatic.com/charts/loader.js"></script>
<script src="/assets/application-35dd1bfa2a15daa7dc2c7f29abbedd235e98278dee45b81fab4fd94785e21388.js"></script>
<link rel="shortcut icon" type="image/x-icon" href="/favicon_alx.ico" />
<meta name="csrf-param" content="authenticity_token" />
<meta name="csrf-token" content="t7zDZL5PR0Ug_oVRKD3x2KQWxrIH3yNcQ_r9yDl-IZRC7elh4HN2GeSJ20mRNhS2hfceTJGCJxfeUep7xcTrIQ" />

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
<script src="/packs/js/application-491cc5291ca9391a78e1.js"></script>
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
<div class="inner" style="background-image: url('https://s3.amazonaws.com/alx-intranet.hbtn.io/users/photos/000/197/885/thumb/joker.jpg?X-Amz-Algorithm=AWS4-HMAC-SHA256&amp;X-Amz-Credential=AKIARDDGGGOUSBVO6H7D%2F20221213%2Fus-east-1%2Fs3%2Faws4_request&amp;X-Amz-Date=20221213T124312Z&amp;X-Amz-Expires=600&amp;X-Amz-SignedHeaders=host&amp;X-Amz-Signature=8b1bbf8042bb25d83e51d106853b15bc7a20d27c9e2fd1292e7a5a041f492b70')"></div>
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
<div class="inner" style="background-image: url('https://s3.amazonaws.com/alx-intranet.hbtn.io/users/photos/000/197/885/thumb/joker.jpg?X-Amz-Algorithm=AWS4-HMAC-SHA256&amp;X-Amz-Credential=AKIARDDGGGOUSBVO6H7D%2F20221213%2Fus-east-1%2Fs3%2Faws4_request&amp;X-Amz-Date=20221213T124312Z&amp;X-Amz-Expires=600&amp;X-Amz-SignedHeaders=host&amp;X-Amz-Signature=8b1bbf8042bb25d83e51d106853b15bc7a20d27c9e2fd1292e7a5a041f492b70')"></div>
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

<h1 class="gap">0x02. C - Functions, nested loops</h1>

<div data-react-class="tags/Tags" data-react-props="{&quot;tags&quot;:[{&quot;id&quot;:7,&quot;value&quot;:&quot;C&quot;,&quot;author_id&quot;:null,&quot;created_at&quot;:&quot;2022-06-16T01:59:38.000Z&quot;,&quot;updated_at&quot;:&quot;2022-06-16T01:59:38.000Z&quot;}]}" data-react-cache-id="tags/Tags-0"></div>

<div data-react-class="projects/ProjectMetadata" data-react-props="{&quot;metadata&quot;:{&quot;author&quot;:&quot;Julien Barbier&quot;,&quot;weight&quot;:1,&quot;correction&quot;:{&quot;released&quot;:true,&quot;auto_correction_available_at&quot;:&quot;2022-12-13T12:00:00.000+03:00&quot;,&quot;requires_auto_correction&quot;:true,&quot;requires_manual_correction&quot;:false},&quot;bpi&quot;:{&quot;current&quot;:true,&quot;started&quot;:false,&quot;in_second_deadline&quot;:false,&quot;starts_at&quot;:&quot;2022-12-13T06:00:00.000+03:00&quot;,&quot;ends_at&quot;:&quot;2022-12-14T06:00:00.000+03:00&quot;,&quot;second_deadline_at&quot;:&quot;2022-12-15T06:00:00.000+03:00&quot;}}}" data-react-cache-id="projects/ProjectMetadata-0"></div>




<div class="panel panel-primary">
<div class="panel-body">
<img src="/images/challenge2022/get-started.jpg" alt="Challenge #3 has started!">
<!-- Congrats! you found the first level path: /ch4ll3n632022/level0 -->
</div>
</div>



<div id="project_id" style="display: none" data-project-id="214"></div>







<div class="panel panel-default" id="project-description">
<div class="panel-body">
<h2>Resources</h2>

<p><strong>Read or watch</strong>:</p>

<ul>
<li><a href="/rltoken/_4aLZ5nW24njUT2VbSZdQQ" title="Nested while loops" target="_blank">Nested while loops</a> </li>
<li><a href="/rltoken/Vg1zzzrxLhPh71405uggSg" title="C - Functions" target="_blank">C - Functions</a> </li>
<li><a href="/rltoken/jveXtnJII2S0z7a06c7-JA" title="Learning to Program in C (Part 06)" target="_blank">Learning to Program in C (Part 06)</a> (<em>stop at 14:00</em>)</li>
<li><a href="/rltoken/XZ--UJZO76ZoUWNA9bTmbg" title="What is the purpose of a function prototype?" target="_blank">What is the purpose of a function prototype?</a> </li>
<li><a href="/rltoken/AS8JW4ObD5gmyX2mgtqV0A" title="C - Header Files" target="_blank">C - Header Files</a> (<em>stop before the &ldquo;Once-Only Headers&rdquo; paragraph</em>)</li>
</ul>

<h2>Learning Objectives</h2>

<p>At the end of this project, you are expected to be able to <a href="/rltoken/-ERX2Jh115GIdTUsSixnnA" title="explain to anyone" target="_blank">explain to anyone</a>, <strong>without the help of Google</strong>:</p>

<h3>General</h3>

<ul>
<li>What are nested loops and how to use them</li>
<li>What is a function and how do you use functions</li>
<li>What is the difference between a declaration and a definition of a function</li>
<li>What is a prototype</li>
<li>Scope of variables</li>
<li>What are the <code>gcc</code> flags <code>-Wall -Werror -pedantic -Wextra -std=gnu89</code></li>
<li>What are header files and how to to use them with <code>#include</code></li>
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

<h3>Copyright - Plagiarism</h3>

<ul>
<li>You are tasked to come up with solutions for the tasks below yourself to meet with the above learning objectives.</li>
<li>You will not be able to meet the objectives of this or any following project by copying and pasting someone else&rsquo;s work. </li>
<li>You are not allowed to publish any content of this project.</li>
<li>Any form of plagiarism is strictly forbidden and will result in removal from the program.</li>
</ul>

<h2>More Info</h2>

<p>You do not have to understand the call by reference (address), stack, static variables, recursions or arrays, yet.</p>

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
<div class="quiz_question_item_container" data-role="quiz_question377" data-position="3">
<div class=" clearfix" id="quiz_question-377">

<h4 class="quiz_question">

Question #0
</h4>

<!-- Quiz question Body -->
<p>What is the ASCII value of <code>a</code>?</p>


<!-- Quiz question Answers -->
<ul class="quiz_question_answers" data-question-id="377">
<li class="">

<input type="radio" name="377" id="377-1505520542808" value="1505520542808" data-quiz-answer-id="1505520542808" data-quiz-question-id="377" disabled="disabled" />
<label for="377-1505520542808"><p>12</p>
</label>
</li>

<li class="">

<input type="radio" name="377" id="377-1505520535141" value="1505520535141" data-quiz-answer-id="1505520535141" data-quiz-question-id="377" disabled="disabled" checked="checked" />
<label for="377-1505520535141"><p>97</p>
</label>
</li>

<li class="">

<input type="radio" name="377" id="377-1505520548061" value="1505520548061" data-quiz-answer-id="1505520548061" data-quiz-question-id="377" disabled="disabled" />
<label for="377-1505520548061"><p>1</p>
</label>
</li>

<li class="">

<input type="radio" name="377" id="377-1505520540319" value="1505520540319" data-quiz-answer-id="1505520540319" data-quiz-question-id="377" disabled="disabled" />
<label for="377-1505520540319"><p>65</p>
</label>
</li>

</ul>

<!-- Quiz question Tips -->

</div>

</div>
<div class="quiz_question_item_container" data-role="quiz_question384" data-position="10">
<div class=" clearfix" id="quiz_question-384">

<h4 class="quiz_question">

Question #1
</h4>

<!-- Quiz question Body -->
<p>What is the result of <code>12 % 10</code>?</p>


<!-- Quiz question Answers -->
<ul class="quiz_question_answers" data-question-id="384">
<li class="">

<input type="radio" name="384" id="384-1505520698322" value="1505520698322" data-quiz-answer-id="1505520698322" data-quiz-question-id="384" disabled="disabled" checked="checked" />
<label for="384-1505520698322"><p>2</p>
</label>
</li>

<li class="">

<input type="radio" name="384" id="384-1505520694532" value="1505520694532" data-quiz-answer-id="1505520694532" data-quiz-question-id="384" disabled="disabled" />
<label for="384-1505520694532"><p>0</p>
</label>
</li>

<li class="">

<input type="radio" name="384" id="384-1505520700383" value="1505520700383" data-quiz-answer-id="1505520700383" data-quiz-question-id="384" disabled="disabled" />
<label for="384-1505520700383"><p>3</p>
</label>
</li>

<li class="">

<input type="radio" name="384" id="384-1505520696975" value="1505520696975" data-quiz-answer-id="1505520696975" data-quiz-question-id="384" disabled="disabled" />
<label for="384-1505520696975"><p>1</p>
</label>
</li>

</ul>

<!-- Quiz question Tips -->

</div>

</div>
<div class="quiz_question_item_container" data-role="quiz_question378" data-position="4">
<div class=" clearfix" id="quiz_question-378">

<h4 class="quiz_question">

Question #2
</h4>

<!-- Quiz question Body -->
<p>What is the ASCII value of <code>J</code>?</p>


<!-- Quiz question Answers -->
<ul class="quiz_question_answers" data-question-id="378">
<li class="">

<input type="radio" name="378" id="378-1505520560343" value="1505520560343" data-quiz-answer-id="1505520560343" data-quiz-question-id="378" disabled="disabled" checked="checked" />
<label for="378-1505520560343"><p>74</p>
</label>
</li>

<li class="">

<input type="radio" name="378" id="378-1505520551476" value="1505520551476" data-quiz-answer-id="1505520551476" data-quiz-question-id="378" disabled="disabled" />
<label for="378-1505520551476"><p>70</p>
</label>
</li>

<li class="">

<input type="radio" name="378" id="378-1505520563226" value="1505520563226" data-quiz-answer-id="1505520563226" data-quiz-question-id="378" disabled="disabled" />
<label for="378-1505520563226"><p>76</p>
</label>
</li>

<li class="">

<input type="radio" name="378" id="378-1505520557207" value="1505520557207" data-quiz-answer-id="1505520557207" data-quiz-question-id="378" disabled="disabled" />
<label for="378-1505520557207"><p>72</p>
</label>
</li>

</ul>

<!-- Quiz question Tips -->

</div>

</div>
<div class="quiz_question_item_container" data-role="quiz_question383" data-position="9">
<div class=" clearfix" id="quiz_question-383">

<h4 class="quiz_question">

Question #3
</h4>

<!-- Quiz question Body -->
<p>What is the result of <code>12 % 3</code>?</p>


<!-- Quiz question Answers -->
<ul class="quiz_question_answers" data-question-id="383">
<li class="">

<input type="radio" name="383" id="383-1505520673874" value="1505520673874" data-quiz-answer-id="1505520673874" data-quiz-question-id="383" disabled="disabled" />
<label for="383-1505520673874"><p>2</p>
</label>
</li>

<li class="">

<input type="radio" name="383" id="383-1505520669153" value="1505520669153" data-quiz-answer-id="1505520669153" data-quiz-question-id="383" disabled="disabled" checked="checked" />
<label for="383-1505520669153"><p>0</p>
</label>
</li>

<li class="">

<input type="radio" name="383" id="383-1505520675325" value="1505520675325" data-quiz-answer-id="1505520675325" data-quiz-question-id="383" disabled="disabled" />
<label for="383-1505520675325"><p>3</p>
</label>
</li>

<li class="">

<input type="radio" name="383" id="383-1505520672275" value="1505520672275" data-quiz-answer-id="1505520672275" data-quiz-question-id="383" disabled="disabled" />
<label for="383-1505520672275"><p>1</p>
</label>
</li>

</ul>

<!-- Quiz question Tips -->

</div>

</div>
<div class="quiz_question_item_container" data-role="quiz_question381" data-position="7">
<div class=" clearfix" id="quiz_question-381">

<h4 class="quiz_question">

Question #4
</h4>

<!-- Quiz question Body -->
<p>What is the ASCII value of <code>5</code>?</p>


<!-- Quiz question Answers -->
<ul class="quiz_question_answers" data-question-id="381">
<li class="">

<input type="radio" name="381" id="381-1505520612483" value="1505520612483" data-quiz-answer-id="1505520612483" data-quiz-question-id="381" disabled="disabled" />
<label for="381-1505520612483"><p>50</p>
</label>
</li>

<li class="">

<input type="radio" name="381" id="381-1505520628708" value="1505520628708" data-quiz-answer-id="1505520628708" data-quiz-question-id="381" disabled="disabled" />
<label for="381-1505520628708"><p>5</p>
</label>
</li>

<li class="">

<input type="radio" name="381" id="381-1505520626031" value="1505520626031" data-quiz-answer-id="1505520626031" data-quiz-question-id="381" disabled="disabled" checked="checked" />
<label for="381-1505520626031"><p>53</p>
</label>
</li>

</ul>

<!-- Quiz question Tips -->

</div>

</div>
<div class="quiz_question_item_container" data-role="quiz_question375" data-position="1">
<div class=" clearfix" id="quiz_question-375">

<h4 class="quiz_question">

Question #5
</h4>

<!-- Quiz question Body -->
<p>Which of these loop statements don&rsquo;t exist?</p>


<!-- Quiz question Answers -->
<ul class="quiz_question_answers" data-question-id="375">
<li class="">

<input type="checkbox" name="375" id="375-1505520461236" value="1505520461236" data-quiz-answer-id="1505520461236" data-quiz-question-id="375" disabled="disabled" checked="checked" />
<label for="375-1505520461236"><p><code>loop_to</code></p>
</label>
</li>

<li class="">

<input type="checkbox" name="375" id="375-1505520434993" value="1505520434993" data-quiz-answer-id="1505520434993" data-quiz-question-id="375" disabled="disabled" />
<label for="375-1505520434993"><p><code>for</code></p>
</label>
</li>

<li class="">

<input type="checkbox" name="375" id="375-1505520439710" value="1505520439710" data-quiz-answer-id="1505520439710" data-quiz-question-id="375" disabled="disabled" />
<label for="375-1505520439710"><p><code>while</code></p>
</label>
</li>

<li class="">

<input type="checkbox" name="375" id="375-1505520451761" value="1505520451761" data-quiz-answer-id="1505520451761" data-quiz-question-id="375" disabled="disabled" />
<label for="375-1505520451761"><p><code>do... while</code></p>
</label>
</li>

<li class="">

<input type="checkbox" name="375" id="375-1505520445250" value="1505520445250" data-quiz-answer-id="1505520445250" data-quiz-question-id="375" disabled="disabled" checked="checked" />
<label for="375-1505520445250"><p><code>foreach</code></p>
</label>
</li>

<li class="">

<input type="checkbox" name="375" id="375-1505520473454" value="1505520473454" data-quiz-answer-id="1505520473454" data-quiz-question-id="375" disabled="disabled" checked="checked" />
<label for="375-1505520473454"><p><code>each</code></p>
</label>
</li>

</ul>

<!-- Quiz question Tips -->

</div>

</div>
<div class="quiz_question_item_container" data-role="quiz_question385" data-position="11">
<div class=" clearfix" id="quiz_question-385">

<h4 class="quiz_question">

Question #6
</h4>

<!-- Quiz question Body -->
<p>What is the result of <code>89 % 7</code>?</p>


<!-- Quiz question Answers -->
<ul class="quiz_question_answers" data-question-id="385">
<li class="">

<input type="radio" name="385" id="385-1505520711130" value="1505520711130" data-quiz-answer-id="1505520711130" data-quiz-question-id="385" disabled="disabled" />
<label for="385-1505520711130"><p>3</p>
</label>
</li>

<li class="">

<input type="radio" name="385" id="385-1505520707724" value="1505520707724" data-quiz-answer-id="1505520707724" data-quiz-question-id="385" disabled="disabled" />
<label for="385-1505520707724"><p>0</p>
</label>
</li>

<li class="">

<input type="radio" name="385" id="385-1505520712796" value="1505520712796" data-quiz-answer-id="1505520712796" data-quiz-question-id="385" disabled="disabled" checked="checked" />
<label for="385-1505520712796"><p>5</p>
</label>
</li>

<li class="">

<input type="radio" name="385" id="385-1505520709611" value="1505520709611" data-quiz-answer-id="1505520709611" data-quiz-question-id="385" disabled="disabled" />
<label for="385-1505520709611"><p>2</p>
</label>
</li>

</ul>

<!-- Quiz question Tips -->

</div>

</div>
<div class="quiz_question_item_container" data-role="quiz_question379" data-position="5">
<div class=" clearfix" id="quiz_question-379">

<h4 class="quiz_question">

Question #7
</h4>

<!-- Quiz question Body -->
<p>What is the ASCII value of <code>0</code>?</p>


<!-- Quiz question Answers -->
<ul class="quiz_question_answers" data-question-id="379">
<li class="">

<input type="radio" name="379" id="379-1505520568283" value="1505520568283" data-quiz-answer-id="1505520568283" data-quiz-question-id="379" disabled="disabled" />
<label for="379-1505520568283"><p>79</p>
</label>
</li>

<li class="">

<input type="radio" name="379" id="379-1505520579610" value="1505520579610" data-quiz-answer-id="1505520579610" data-quiz-question-id="379" disabled="disabled" checked="checked" />
<label for="379-1505520579610"><p>48</p>
</label>
</li>

<li class="">

<input type="radio" name="379" id="379-1505520572694" value="1505520572694" data-quiz-answer-id="1505520572694" data-quiz-question-id="379" disabled="disabled" />
<label for="379-1505520572694"><p>0</p>
</label>
</li>

</ul>

<!-- Quiz question Tips -->

</div>

</div>
<div class="quiz_question_item_container" data-role="quiz_question380" data-position="6">
<div class=" clearfix" id="quiz_question-380">

<h4 class="quiz_question">

Question #8
</h4>

<!-- Quiz question Body -->
<p>What is the ASCII value of <code>-</code>?</p>


<!-- Quiz question Answers -->
<ul class="quiz_question_answers" data-question-id="380">
<li class="">

<input type="radio" name="380" id="380-1505520588547" value="1505520588547" data-quiz-answer-id="1505520588547" data-quiz-question-id="380" disabled="disabled" checked="checked" />
<label for="380-1505520588547"><p>45</p>
</label>
</li>

<li class="">

<input type="radio" name="380" id="380-1505520607246" value="1505520607246" data-quiz-answer-id="1505520607246" data-quiz-question-id="380" disabled="disabled" />
<label for="380-1505520607246"><p>47</p>
</label>
</li>

<li class="">

<input type="radio" name="380" id="380-1505520602298" value="1505520602298" data-quiz-answer-id="1505520602298" data-quiz-question-id="380" disabled="disabled" />
<label for="380-1505520602298"><p>3</p>
</label>
</li>

</ul>

<!-- Quiz question Tips -->

</div>

</div>
<div class="quiz_question_item_container" data-role="quiz_question376" data-position="2">
<div class=" clearfix" id="quiz_question-376">

<h4 class="quiz_question">

Question #9
</h4>

<!-- Quiz question Body -->
<p>What is the ASCII value of <code>A</code>?</p>


<!-- Quiz question Answers -->
<ul class="quiz_question_answers" data-question-id="376">
<li class="">

<input type="radio" name="376" id="376-1505520527661" value="1505520527661" data-quiz-answer-id="1505520527661" data-quiz-question-id="376" disabled="disabled" />
<label for="376-1505520527661"><p>12</p>
</label>
</li>

<li class="">

<input type="radio" name="376" id="376-1505520496569" value="1505520496569" data-quiz-answer-id="1505520496569" data-quiz-question-id="376" disabled="disabled" />
<label for="376-1505520496569"><p>97</p>
</label>
</li>

<li class="">

<input type="radio" name="376" id="376-1505520530933" value="1505520530933" data-quiz-answer-id="1505520530933" data-quiz-question-id="376" disabled="disabled" />
<label for="376-1505520530933"><p>1</p>
</label>
</li>

<li class="">

<input type="radio" name="376" id="376-1505520524374" value="1505520524374" data-quiz-answer-id="1505520524374" data-quiz-question-id="376" disabled="disabled" checked="checked" />
<label for="376-1505520524374"><p>65</p>
</label>
</li>

</ul>

<!-- Quiz question Tips -->

</div>

</div>
<div class="quiz_question_item_container" data-role="quiz_question382" data-position="8">
<div class=" clearfix" id="quiz_question-382">

<h4 class="quiz_question">

Question #10
</h4>

<!-- Quiz question Body -->
<p>What is the result of <code>12 % 2</code>?</p>


<!-- Quiz question Answers -->
<ul class="quiz_question_answers" data-question-id="382">
<li class="">

<input type="radio" name="382" id="382-1505520633337" value="1505520633337" data-quiz-answer-id="1505520633337" data-quiz-question-id="382" disabled="disabled" checked="checked" />
<label for="382-1505520633337"><p>0</p>
</label>
</li>

<li class="">

<input type="radio" name="382" id="382-1505520656948" value="1505520656948" data-quiz-answer-id="1505520656948" data-quiz-question-id="382" disabled="disabled" />
<label for="382-1505520656948"><p>2</p>
</label>
</li>

<li class="">

<input type="radio" name="382" id="382-1505520654315" value="1505520654315" data-quiz-answer-id="1505520654315" data-quiz-question-id="382" disabled="disabled" />
<label for="382-1505520654315"><p>1</p>
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

<div data-role="task846" data-position="1" id="task-num-0">
<div class="panel panel-default task-card " id="task-846">
<span id="user_id" data-id="197885"></span>

<div class="panel-heading panel-heading-actions">
<h3 class="panel-title">
0. _putchar
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
<p>Write a program that prints <code>_putchar</code>, followed by a new line.</p>

<ul>
<li>The program should return <code>0</code></li>
</ul>

<pre><code>julien@ubuntu:~/0x02$  gcc -Wall -pedantic -Werror -Wextra -std=gnu89 _putchar.c 0-putchar.c -o 0-putchar
julien@ubuntu:~/0x02$ ./0-putchar 
_putchar
julien@ubuntu:~/0x02$ 
</code></pre>

</div>

<div class="list-group">
<!-- Task URLs -->

<!-- Github information -->
<div class="list-group-item">
<p><strong>Repo:</strong></p>
<ul>
<li>GitHub repository: <code>alx-low_level_programming</code></li>
<li>Directory: <code>0x02-functions_nested_loops</code></li>
<li>File: <code>0-putchar.c</code></li>
</ul>
</div>

<!-- Self-paced manual review -->
</div>

<!-- Panel footer - Controls -->
<div class="panel-footer">
<div class="align-items-center d-flex justify-content-between">

<div>
<button class="student_task_done btn btn-default btn-sm no" data-task-id="846">
<span class="no"><i aria-hidden="true" class="fa fa-square-o "></i></span>
<span class="yes"><i aria-hidden="true" class="fa fa-check-square-o "></i></span>
<span class="pending"><i aria-hidden="true" class="fa fa-spinner  fa-pulse"></i></span>
Done<span class="no pending">?</span><span class="yes">!</span>
</button>

<button class="student-task-done-by btn btn-default btn-sm" data-task-id="846" data-batch-id="26" data-toggle="modal" data-target="#task-846-users-done-modal">
Help
</button>
<div class="modal fade users-done-modal" id="task-846-users-done-modal" data-task-id="846" data-batch-id="26">
<div class="modal-dialog">
<div class="modal-content">
<div class="modal-header">
<button type="button" class="close" data-dismiss="modal" aria-label="Close"><span aria-hidden="true">&times;</span></button>
<h4 class="modal-title">Students who are done with "0. _putchar"</h4>
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


<button class="btn btn-default btn-sm check-your-task-846-modal-button" data-task-id="846" data-toggle="modal" data-target="#task-test-correction-846-correction-modal" id="task-num-0-check-code-btn" data-gtm-custom-event-name="task_checker_modal" data-gtm-custom-event-options='{&quot;taskId&quot;:846}'>
Check your code
</button>
<div class="modal fade task_correction_modal student_modal" id="task-test-correction-846-correction-modal">
<div class="modal-dialog">
<div class="modal-content">
<div class="modal-header">
<button type="button" class="close" data-dismiss="modal" aria-label="Close"><span aria-hidden="true">&times;</span></button>
<h4 class="modal-title">Correction of "0. _putchar"</h4>
</div>
<div class="modal-body">
<div class="actions">
<center>
    <div class="alert alert-info hidden"></div>

    <button name="button" type="submit" class="btn btn-primary correction_request_test_send" data-task-id="846">Start a new test</button>
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
<button data-task-id="846">
<i aria-hidden="true" class="fa fa-info-circle "></i>
</button>
<div class="help-container" data-task-id="846">
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



<button class="btn btn-default btn-sm" data-toggle="modal" data-target="#container-specs-modal" data-gtm-custom-event-name="task_sandbox_modal" data-gtm-custom-event-options="{&quot;taskId&quot;:846}"><i aria-hidden="true" class="fa fa-terminal "></i><span>Get a sandbox</span></button>

</div>


<div class="fs-4">
</div>
</div>


</div>
</div>

</div>
<div data-role="task847" data-position="2" id="task-num-1">
<div class="panel panel-default task-card " id="task-847">
<span id="user_id" data-id="197885"></span>

<div class="panel-heading panel-heading-actions">
<h3 class="panel-title">
1. I sometimes suffer from insomnia. And when I can&#39;t fall asleep, I play what I call the alphabet game
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
<p>Write a function that prints the alphabet, in lowercase, followed by a new line.</p>

<ul>
<li>Prototype: <code>void print_alphabet(void);</code></li>
<li>You can only use <code>_putchar</code> twice in your code</li>
</ul>

<pre><code>julien@ubuntu:~/0x02$ cat 1-main.c
#include &quot;main.h&quot;

/**
* main - check the code
*
* Return: Always 0.
*/
int main(void)
{
print_alphabet();
return (0);
}
julien@ubuntu:~/0x02$ gcc -Wall -pedantic -Werror -Wextra -std=gnu89 _putchar.c 1-main.c 1-alphabet.c -o 1-alphabet
julien@ubuntu:~/0x02$ ./1-alphabet 
abcdefghijklmnopqrstuvwxyz
julien@ubuntu:~/0x02$
</code></pre>

</div>

<div class="list-group">
<!-- Task URLs -->

<!-- Github information -->
<div class="list-group-item">
<p><strong>Repo:</strong></p>
<ul>
<li>GitHub repository: <code>alx-low_level_programming</code></li>
<li>Directory: <code>0x02-functions_nested_loops</code></li>
<li>File: <code>1-alphabet.c</code></li>
</ul>
</div>

<!-- Self-paced manual review -->
</div>

<!-- Panel footer - Controls -->
<div class="panel-footer">
<div class="align-items-center d-flex justify-content-between">

<div>
<button class="student_task_done btn btn-default btn-sm no" data-task-id="847">
<span class="no"><i aria-hidden="true" class="fa fa-square-o "></i></span>
<span class="yes"><i aria-hidden="true" class="fa fa-check-square-o "></i></span>
<span class="pending"><i aria-hidden="true" class="fa fa-spinner  fa-pulse"></i></span>
Done<span class="no pending">?</span><span class="yes">!</span>
</button>

<button class="student-task-done-by btn btn-default btn-sm" data-task-id="847" data-batch-id="26" data-toggle="modal" data-target="#task-847-users-done-modal">
Help
</button>
<div class="modal fade users-done-modal" id="task-847-users-done-modal" data-task-id="847" data-batch-id="26">
<div class="modal-dialog">
<div class="modal-content">
<div class="modal-header">
<button type="button" class="close" data-dismiss="modal" aria-label="Close"><span aria-hidden="true">&times;</span></button>
<h4 class="modal-title">Students who are done with "1. I sometimes suffer from insomnia. And when I can&#39;t fall asleep, I play what I call the alphabet game"</h4>
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


<button class="btn btn-default btn-sm check-your-task-847-modal-button" data-task-id="847" data-toggle="modal" data-target="#task-test-correction-847-correction-modal" id="task-num-1-check-code-btn" data-gtm-custom-event-name="task_checker_modal" data-gtm-custom-event-options='{&quot;taskId&quot;:847}'>
Check your code
</button>
<div class="modal fade task_correction_modal student_modal" id="task-test-correction-847-correction-modal">
<div class="modal-dialog">
<div class="modal-content">
<div class="modal-header">
<button type="button" class="close" data-dismiss="modal" aria-label="Close"><span aria-hidden="true">&times;</span></button>
<h4 class="modal-title">Correction of "1. I sometimes suffer from insomnia. And when I can&#39;t fall asleep, I play what I call the alphabet game"</h4>
</div>
<div class="modal-body">
<div class="actions">
<center>
    <div class="alert alert-info hidden"></div>

    <button name="button" type="submit" class="btn btn-primary correction_request_test_send" data-task-id="847">Start a new test</button>
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
<button data-task-id="847">
<i aria-hidden="true" class="fa fa-info-circle "></i>
</button>
<div class="help-container" data-task-id="847">
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



<button class="btn btn-default btn-sm" data-toggle="modal" data-target="#container-specs-modal" data-gtm-custom-event-name="task_sandbox_modal" data-gtm-custom-event-options="{&quot;taskId&quot;:847}"><i aria-hidden="true" class="fa fa-terminal "></i><span>Get a sandbox</span></button>

</div>


<div class="fs-4">
</div>
</div>


</div>
</div>

</div>
<div data-role="task848" data-position="3" id="task-num-2">
<div class="panel panel-default task-card " id="task-848">
<span id="user_id" data-id="197885"></span>

<div class="panel-heading panel-heading-actions">
<h3 class="panel-title">
2. 10 x alphabet
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
<p>Write a function that prints 10 times the alphabet, in lowercase, followed by a new line.</p>

<ul>
<li>Prototype: <code>void print_alphabet_x10(void);</code></li>
<li>You can only use <code>_putchar</code> twice in your code</li>
</ul>

<pre><code>julien@ubuntu:~/0x02$ cat 2-main.c
#include &quot;main.h&quot;

/**
* main - check the code.
*
* Return: Always 0.
*/
int main(void)
{
print_alphabet_x10();
return (0);
}
julien@ubuntu:~/0x02$ gcc -Wall -pedantic -Werror -Wextra -std=gnu89 _putchar.c 2-main.c 2-print_alphabet_x10.c -o 2-alphabet_x10
julien@ubuntu:~/0x02$ ./2-alphabet_x10 
abcdefghijklmnopqrstuvwxyz
abcdefghijklmnopqrstuvwxyz
abcdefghijklmnopqrstuvwxyz
abcdefghijklmnopqrstuvwxyz
abcdefghijklmnopqrstuvwxyz
abcdefghijklmnopqrstuvwxyz
abcdefghijklmnopqrstuvwxyz
abcdefghijklmnopqrstuvwxyz
abcdefghijklmnopqrstuvwxyz
abcdefghijklmnopqrstuvwxyz
julien@ubuntu:~/0x02$ 
</code></pre>

</div>

<div class="list-group">
<!-- Task URLs -->

<!-- Github information -->
<div class="list-group-item">
<p><strong>Repo:</strong></p>
<ul>
<li>GitHub repository: <code>alx-low_level_programming</code></li>
<li>Directory: <code>0x02-functions_nested_loops</code></li>
<li>File: <code>2-print_alphabet_x10.c</code></li>
</ul>
</div>

<!-- Self-paced manual review -->
</div>

<!-- Panel footer - Controls -->
<div class="panel-footer">
<div class="align-items-center d-flex justify-content-between">

<div>
<button class="student_task_done btn btn-default btn-sm no" data-task-id="848">
<span class="no"><i aria-hidden="true" class="fa fa-square-o "></i></span>
<span class="yes"><i aria-hidden="true" class="fa fa-check-square-o "></i></span>
<span class="pending"><i aria-hidden="true" class="fa fa-spinner  fa-pulse"></i></span>
Done<span class="no pending">?</span><span class="yes">!</span>
</button>

<button class="student-task-done-by btn btn-default btn-sm" data-task-id="848" data-batch-id="26" data-toggle="modal" data-target="#task-848-users-done-modal">
Help
</button>
<div class="modal fade users-done-modal" id="task-848-users-done-modal" data-task-id="848" data-batch-id="26">
<div class="modal-dialog">
<div class="modal-content">
<div class="modal-header">
<button type="button" class="close" data-dismiss="modal" aria-label="Close"><span aria-hidden="true">&times;</span></button>
<h4 class="modal-title">Students who are done with "2. 10 x alphabet"</h4>
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


<button class="btn btn-default btn-sm check-your-task-848-modal-button" data-task-id="848" data-toggle="modal" data-target="#task-test-correction-848-correction-modal" id="task-num-2-check-code-btn" data-gtm-custom-event-name="task_checker_modal" data-gtm-custom-event-options='{&quot;taskId&quot;:848}'>
Check your code
</button>
<div class="modal fade task_correction_modal student_modal" id="task-test-correction-848-correction-modal">
<div class="modal-dialog">
<div class="modal-content">
<div class="modal-header">
<button type="button" class="close" data-dismiss="modal" aria-label="Close"><span aria-hidden="true">&times;</span></button>
<h4 class="modal-title">Correction of "2. 10 x alphabet"</h4>
</div>
<div class="modal-body">
<div class="actions">
<center>
    <div class="alert alert-info hidden"></div>

    <button name="button" type="submit" class="btn btn-primary correction_request_test_send" data-task-id="848">Start a new test</button>
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
<button data-task-id="848">
<i aria-hidden="true" class="fa fa-info-circle "></i>
</button>
<div class="help-container" data-task-id="848">
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



<button class="btn btn-default btn-sm" data-toggle="modal" data-target="#container-specs-modal" data-gtm-custom-event-name="task_sandbox_modal" data-gtm-custom-event-options="{&quot;taskId&quot;:848}"><i aria-hidden="true" class="fa fa-terminal "></i><span>Get a sandbox</span></button>

</div>


<div class="fs-4">
</div>
</div>


</div>
</div>

</div>
<div data-role="task849" data-position="4" id="task-num-3">
<div class="panel panel-default task-card " id="task-849">
<span id="user_id" data-id="197885"></span>

<div class="panel-heading panel-heading-actions">
<h3 class="panel-title">
3. islower
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
<p>Write a function that checks for lowercase character. </p>

<ul>
<li>Prototype: <code>int _islower(int c);</code></li>
<li>Returns <code>1</code> if <code>c</code> is lowercase</li>
<li>Returns <code>0</code> otherwise</li>
</ul>

<p>FYI: The standard library provides a similar function: <code>islower</code>. Run <code>man islower</code> to learn more.</p>

<pre><code>julien@ubuntu:~/0x02$ cat 3-main.c 
#include &quot;main.h&quot;

/**
* main - check the code.
*
* Return: Always 0.
*/
int main(void)
{
int r;

r = _islower(&#39;H&#39;);
_putchar(r + &#39;0&#39;);
r = _islower(&#39;o&#39;);
_putchar(r + &#39;0&#39;);
r = _islower(108);
_putchar(r + &#39;0&#39;);
_putchar(&#39;\n&#39;);
return (0);
}
julien@ubuntu:~/0x02$ gcc -Wall -pedantic -Werror -Wextra -std=gnu89 _putchar.c 3-main.c 3-islower.c -o 3-islower
julien@ubuntu:~/0x02$ ./3-islower 
011
julien@ubuntu:~/0x02$ 
</code></pre>

</div>

<div class="list-group">
<!-- Task URLs -->

<!-- Github information -->
<div class="list-group-item">
<p><strong>Repo:</strong></p>
<ul>
<li>GitHub repository: <code>alx-low_level_programming</code></li>
<li>Directory: <code>0x02-functions_nested_loops</code></li>
<li>File: <code>3-islower.c</code></li>
</ul>
</div>

<!-- Self-paced manual review -->
</div>

<!-- Panel footer - Controls -->
<div class="panel-footer">
<div class="align-items-center d-flex justify-content-between">

<div>
<button class="student_task_done btn btn-default btn-sm no" data-task-id="849">
<span class="no"><i aria-hidden="true" class="fa fa-square-o "></i></span>
<span class="yes"><i aria-hidden="true" class="fa fa-check-square-o "></i></span>
<span class="pending"><i aria-hidden="true" class="fa fa-spinner  fa-pulse"></i></span>
Done<span class="no pending">?</span><span class="yes">!</span>
</button>

<button class="student-task-done-by btn btn-default btn-sm" data-task-id="849" data-batch-id="26" data-toggle="modal" data-target="#task-849-users-done-modal">
Help
</button>
<div class="modal fade users-done-modal" id="task-849-users-done-modal" data-task-id="849" data-batch-id="26">
<div class="modal-dialog">
<div class="modal-content">
<div class="modal-header">
<button type="button" class="close" data-dismiss="modal" aria-label="Close"><span aria-hidden="true">&times;</span></button>
<h4 class="modal-title">Students who are done with "3. islower"</h4>
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


<button class="btn btn-default btn-sm check-your-task-849-modal-button" data-task-id="849" data-toggle="modal" data-target="#task-test-correction-849-correction-modal" id="task-num-3-check-code-btn" data-gtm-custom-event-name="task_checker_modal" data-gtm-custom-event-options='{&quot;taskId&quot;:849}'>
Check your code
</button>
<div class="modal fade task_correction_modal student_modal" id="task-test-correction-849-correction-modal">
<div class="modal-dialog">
<div class="modal-content">
<div class="modal-header">
<button type="button" class="close" data-dismiss="modal" aria-label="Close"><span aria-hidden="true">&times;</span></button>
<h4 class="modal-title">Correction of "3. islower"</h4>
</div>
<div class="modal-body">
<div class="actions">
<center>
    <div class="alert alert-info hidden"></div>

    <button name="button" type="submit" class="btn btn-primary correction_request_test_send" data-task-id="849">Start a new test</button>
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
<button data-task-id="849">
<i aria-hidden="true" class="fa fa-info-circle "></i>
</button>
<div class="help-container" data-task-id="849">
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



<button class="btn btn-default btn-sm" data-toggle="modal" data-target="#container-specs-modal" data-gtm-custom-event-name="task_sandbox_modal" data-gtm-custom-event-options="{&quot;taskId&quot;:849}"><i aria-hidden="true" class="fa fa-terminal "></i><span>Get a sandbox</span></button>

</div>


<div class="fs-4">
</div>
</div>


</div>
</div>

</div>
<div data-role="task850" data-position="5" id="task-num-4">
<div class="panel panel-default task-card " id="task-850">
<span id="user_id" data-id="197885"></span>

<div class="panel-heading panel-heading-actions">
<h3 class="panel-title">
4. isalpha
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
<p>Write a function that checks for alphabetic character. </p>

<ul>
<li>Prototype: <code>int _isalpha(int c);</code></li>
<li>Returns <code>1</code> if <code>c</code> is a letter, lowercase or uppercase</li>
<li>Returns <code>0</code> otherwise</li>
</ul>

<p>FYI: The standard library provides a similar function: <code>isalpha</code>. Run <code>man isalpha</code> to learn more.</p>

<pre><code>julien@ubuntu:~/0x02$ cat 4-main.c 
#include &quot;main.h&quot;

/**
* main - check the code.
*
* Return: Always 0.
*/
int main(void)
{
int r;

r = _isalpha(&#39;H&#39;);
_putchar(r + &#39;0&#39;);
r = _isalpha(&#39;o&#39;);
_putchar(r + &#39;0&#39;);
r = _isalpha(108);
_putchar(r + &#39;0&#39;);
r = _isalpha(&#39;;&#39;);
_putchar(r + &#39;0&#39;);
_putchar(&#39;\n&#39;);
return (0);
}
julien@ubuntu:~/0x02$ gcc -Wall -pedantic -Werror -Wextra -std=gnu89 _putchar.c 4-main.c 4-isalpha.c -o 4-isalpha
julien@ubuntu:~/0x02$ ./4-isalpha 
1110
julien@ubuntu:~/0x02$ 
</code></pre>

</div>

<div class="list-group">
<!-- Task URLs -->

<!-- Github information -->
<div class="list-group-item">
<p><strong>Repo:</strong></p>
<ul>
<li>GitHub repository: <code>alx-low_level_programming</code></li>
<li>Directory: <code>0x02-functions_nested_loops</code></li>
<li>File: <code>4-isalpha.c</code></li>
</ul>
</div>

<!-- Self-paced manual review -->
</div>

<!-- Panel footer - Controls -->
<div class="panel-footer">
<div class="align-items-center d-flex justify-content-between">

<div>
<button class="student_task_done btn btn-default btn-sm no" data-task-id="850">
<span class="no"><i aria-hidden="true" class="fa fa-square-o "></i></span>
<span class="yes"><i aria-hidden="true" class="fa fa-check-square-o "></i></span>
<span class="pending"><i aria-hidden="true" class="fa fa-spinner  fa-pulse"></i></span>
Done<span class="no pending">?</span><span class="yes">!</span>
</button>

<button class="student-task-done-by btn btn-default btn-sm" data-task-id="850" data-batch-id="26" data-toggle="modal" data-target="#task-850-users-done-modal">
Help
</button>
<div class="modal fade users-done-modal" id="task-850-users-done-modal" data-task-id="850" data-batch-id="26">
<div class="modal-dialog">
<div class="modal-content">
<div class="modal-header">
<button type="button" class="close" data-dismiss="modal" aria-label="Close"><span aria-hidden="true">&times;</span></button>
<h4 class="modal-title">Students who are done with "4. isalpha"</h4>
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


<button class="btn btn-default btn-sm check-your-task-850-modal-button" data-task-id="850" data-toggle="modal" data-target="#task-test-correction-850-correction-modal" id="task-num-4-check-code-btn" data-gtm-custom-event-name="task_checker_modal" data-gtm-custom-event-options='{&quot;taskId&quot;:850}'>
Check your code
</button>
<div class="modal fade task_correction_modal student_modal" id="task-test-correction-850-correction-modal">
<div class="modal-dialog">
<div class="modal-content">
<div class="modal-header">
<button type="button" class="close" data-dismiss="modal" aria-label="Close"><span aria-hidden="true">&times;</span></button>
<h4 class="modal-title">Correction of "4. isalpha"</h4>
</div>
<div class="modal-body">
<div class="actions">
<center>
    <div class="alert alert-info hidden"></div>

    <button name="button" type="submit" class="btn btn-primary correction_request_test_send" data-task-id="850">Start a new test</button>
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
<button data-task-id="850">
<i aria-hidden="true" class="fa fa-info-circle "></i>
</button>
<div class="help-container" data-task-id="850">
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



<button class="btn btn-default btn-sm" data-toggle="modal" data-target="#container-specs-modal" data-gtm-custom-event-name="task_sandbox_modal" data-gtm-custom-event-options="{&quot;taskId&quot;:850}"><i aria-hidden="true" class="fa fa-terminal "></i><span>Get a sandbox</span></button>

</div>


<div class="fs-4">
</div>
</div>


</div>
</div>

</div>
<div data-role="task851" data-position="6" id="task-num-5">
<div class="panel panel-default task-card " id="task-851">
<span id="user_id" data-id="197885"></span>

<div class="panel-heading panel-heading-actions">
<h3 class="panel-title">
5. Sign
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
<p>Write a function that prints the sign of a number.</p>

<ul>
<li>Prototype: <code>int print_sign(int n);</code></li>
<li>Returns <code>1</code> and prints <code>+</code> if <code>n</code> is greater than zero</li>
<li>Returns <code>0</code> and prints <code>0</code> if <code>n</code> is zero</li>
<li>Returns <code>-1</code> and prints <code>-</code> if <code>n</code> is less than zero</li>
</ul>

<pre><code>julien@ubuntu:~/0x02$ cat 5-main.c
#include &quot;main.h&quot;

/**
* main - check the code.
*
* Return: Always 0.
*/
int main(void)
{
int r;

r = print_sign(98);
_putchar(&#39;,&#39;);
_putchar(&#39; &#39;);
_putchar(r + &#39;0&#39;);
_putchar(&#39;\n&#39;);
r = print_sign(0);
_putchar(&#39;,&#39;);
_putchar(&#39; &#39;);
_putchar(r + &#39;0&#39;);
_putchar(&#39;\n&#39;);
r = print_sign(0xff);
_putchar(&#39;,&#39;);
_putchar(&#39; &#39;);
_putchar(r + &#39;0&#39;);
_putchar(&#39;\n&#39;);
r = print_sign(-1);
_putchar(&#39;,&#39;);
_putchar(&#39; &#39;);
_putchar(r + &#39;0&#39;);
_putchar(&#39;\n&#39;);
return (0);
}
julien@ubuntu:~/0x02$ gcc -Wall -pedantic -Werror -Wextra -std=gnu89 _putchar.c 5-main.c 5-sign.c -o 5-sign
julien@ubuntu:~/0x02$ ./5-sign 
+, 1
0, 0
+, 1
-, /
julien@ubuntu:~/0x02$ 
</code></pre>

</div>

<div class="list-group">
<!-- Task URLs -->

<!-- Github information -->
<div class="list-group-item">
<p><strong>Repo:</strong></p>
<ul>
<li>GitHub repository: <code>alx-low_level_programming</code></li>
<li>Directory: <code>0x02-functions_nested_loops</code></li>
<li>File: <code>5-sign.c</code></li>
</ul>
</div>

<!-- Self-paced manual review -->
</div>

<!-- Panel footer - Controls -->
<div class="panel-footer">
<div class="align-items-center d-flex justify-content-between">

<div>
<button class="student_task_done btn btn-default btn-sm no" data-task-id="851">
<span class="no"><i aria-hidden="true" class="fa fa-square-o "></i></span>
<span class="yes"><i aria-hidden="true" class="fa fa-check-square-o "></i></span>
<span class="pending"><i aria-hidden="true" class="fa fa-spinner  fa-pulse"></i></span>
Done<span class="no pending">?</span><span class="yes">!</span>
</button>

<button class="student-task-done-by btn btn-default btn-sm" data-task-id="851" data-batch-id="26" data-toggle="modal" data-target="#task-851-users-done-modal">
Help
</button>
<div class="modal fade users-done-modal" id="task-851-users-done-modal" data-task-id="851" data-batch-id="26">
<div class="modal-dialog">
<div class="modal-content">
<div class="modal-header">
<button type="button" class="close" data-dismiss="modal" aria-label="Close"><span aria-hidden="true">&times;</span></button>
<h4 class="modal-title">Students who are done with "5. Sign"</h4>
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


<button class="btn btn-default btn-sm check-your-task-851-modal-button" data-task-id="851" data-toggle="modal" data-target="#task-test-correction-851-correction-modal" id="task-num-5-check-code-btn" data-gtm-custom-event-name="task_checker_modal" data-gtm-custom-event-options='{&quot;taskId&quot;:851}'>
Check your code
</button>
<div class="modal fade task_correction_modal student_modal" id="task-test-correction-851-correction-modal">
<div class="modal-dialog">
<div class="modal-content">
<div class="modal-header">
<button type="button" class="close" data-dismiss="modal" aria-label="Close"><span aria-hidden="true">&times;</span></button>
<h4 class="modal-title">Correction of "5. Sign"</h4>
</div>
<div class="modal-body">
<div class="actions">
<center>
    <div class="alert alert-info hidden"></div>

    <button name="button" type="submit" class="btn btn-primary correction_request_test_send" data-task-id="851">Start a new test</button>
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
<button data-task-id="851">
<i aria-hidden="true" class="fa fa-info-circle "></i>
</button>
<div class="help-container" data-task-id="851">
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



<button class="btn btn-default btn-sm" data-toggle="modal" data-target="#container-specs-modal" data-gtm-custom-event-name="task_sandbox_modal" data-gtm-custom-event-options="{&quot;taskId&quot;:851}"><i aria-hidden="true" class="fa fa-terminal "></i><span>Get a sandbox</span></button>

</div>


<div class="fs-4">
</div>
</div>


</div>
</div>

</div>
<div data-role="task852" data-position="7" id="task-num-6">
<div class="panel panel-default task-card " id="task-852">
<span id="user_id" data-id="197885"></span>

<div class="panel-heading panel-heading-actions">
<h3 class="panel-title">
6. There is no such thing as absolute value in this world. You can only estimate what a thing is worth to you
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
<p>Write a function that computes the absolute value of an integer.</p>

<ul>
<li>Prototype: <code>int _abs(int);</code></li>
</ul>

<p>FYI: The standard library provides a similar function: <code>abs</code>. Run <code>man abs</code> to learn more.</p>

<pre><code>julien@ubuntu:~/0x02$ cat 6-main.c
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

r = _abs(-1);
printf(&quot;%d\n&quot;, r);
r = _abs(0);
printf(&quot;%d\n&quot;, r);
r = _abs(1);
printf(&quot;%d\n&quot;, r);
r = _abs(-98);
printf(&quot;%d\n&quot;, r);
return (0);
}
julien@ubuntu:~/0x02$ gcc -Wall -pedantic -Werror -Wextra -std=gnu89 _putchar.c 6-main.c 6-abs.c -o 6-abs
julien@ubuntu:~/0x02$ ./6-abs 
1
0
1
98
julien@ubuntu:~/0x02$ 
</code></pre>

</div>

<div class="list-group">
<!-- Task URLs -->

<!-- Github information -->
<div class="list-group-item">
<p><strong>Repo:</strong></p>
<ul>
<li>GitHub repository: <code>alx-low_level_programming</code></li>
<li>Directory: <code>0x02-functions_nested_loops</code></li>
<li>File: <code>6-abs.c</code></li>
</ul>
</div>

<!-- Self-paced manual review -->
</div>

<!-- Panel footer - Controls -->
<div class="panel-footer">
<div class="align-items-center d-flex justify-content-between">

<div>
<button class="student_task_done btn btn-default btn-sm no" data-task-id="852">
<span class="no"><i aria-hidden="true" class="fa fa-square-o "></i></span>
<span class="yes"><i aria-hidden="true" class="fa fa-check-square-o "></i></span>
<span class="pending"><i aria-hidden="true" class="fa fa-spinner  fa-pulse"></i></span>
Done<span class="no pending">?</span><span class="yes">!</span>
</button>

<button class="student-task-done-by btn btn-default btn-sm" data-task-id="852" data-batch-id="26" data-toggle="modal" data-target="#task-852-users-done-modal">
Help
</button>
<div class="modal fade users-done-modal" id="task-852-users-done-modal" data-task-id="852" data-batch-id="26">
<div class="modal-dialog">
<div class="modal-content">
<div class="modal-header">
<button type="button" class="close" data-dismiss="modal" aria-label="Close"><span aria-hidden="true">&times;</span></button>
<h4 class="modal-title">Students who are done with "6. There is no such thing as absolute value in this world. You can only estimate what a thing is worth to you"</h4>
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


<button class="btn btn-default btn-sm check-your-task-852-modal-button" data-task-id="852" data-toggle="modal" data-target="#task-test-correction-852-correction-modal" id="task-num-6-check-code-btn" data-gtm-custom-event-name="task_checker_modal" data-gtm-custom-event-options='{&quot;taskId&quot;:852}'>
Check your code
</button>
<div class="modal fade task_correction_modal student_modal" id="task-test-correction-852-correction-modal">
<div class="modal-dialog">
<div class="modal-content">
<div class="modal-header">
<button type="button" class="close" data-dismiss="modal" aria-label="Close"><span aria-hidden="true">&times;</span></button>
<h4 class="modal-title">Correction of "6. There is no such thing as absolute value in this world. You can only estimate what a thing is worth to you"</h4>
</div>
<div class="modal-body">
<div class="actions">
<center>
    <div class="alert alert-info hidden"></div>

    <button name="button" type="submit" class="btn btn-primary correction_request_test_send" data-task-id="852">Start a new test</button>
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
<button data-task-id="852">
<i aria-hidden="true" class="fa fa-info-circle "></i>
</button>
<div class="help-container" data-task-id="852">
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



<button class="btn btn-default btn-sm" data-toggle="modal" data-target="#container-specs-modal" data-gtm-custom-event-name="task_sandbox_modal" data-gtm-custom-event-options="{&quot;taskId&quot;:852}"><i aria-hidden="true" class="fa fa-terminal "></i><span>Get a sandbox</span></button>

</div>


<div class="fs-4">
</div>
</div>


</div>
</div>

</div>
<div data-role="task853" data-position="8" id="task-num-7">
<div class="panel panel-default task-card " id="task-853">
<span id="user_id" data-id="197885"></span>

<div class="panel-heading panel-heading-actions">
<h3 class="panel-title">
7. There are only 3 colors, 10 digits, and 7 notes; it&#39;s what we do with them that&#39;s important
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
<p>Write a function that prints the last digit of a number.</p>

<ul>
<li>Prototype: <code>int print_last_digit(int);</code></li>
<li>Returns the value of the last digit</li>
</ul>

<pre><code>julien@ubuntu:~/0x02$ cat 7-main.c
#include &quot;main.h&quot;

/**
* main - check the code
*
* Return: Always 0.
*/
int main(void)
{
int r;

print_last_digit(98);
print_last_digit(0);
r = print_last_digit(-1024);
_putchar(&#39;0&#39; + r);
_putchar(&#39;\n&#39;);
return (0);
}
julien@ubuntu:~/0x02$ gcc -Wall -pedantic -Werror -Wextra -std=gnu89 _putchar.c 7-main.c 7-print_last_digit.c -o 7-last_digit
julien@ubuntu:~/0x02$ ./7-last_digit 
8044
julien@ubuntu:~/0x02$ 
</code></pre>

</div>

<div class="list-group">
<!-- Task URLs -->

<!-- Github information -->
<div class="list-group-item">
<p><strong>Repo:</strong></p>
<ul>
<li>GitHub repository: <code>alx-low_level_programming</code></li>
<li>Directory: <code>0x02-functions_nested_loops</code></li>
<li>File: <code>7-print_last_digit.c</code></li>
</ul>
</div>

<!-- Self-paced manual review -->
</div>

<!-- Panel footer - Controls -->
<div class="panel-footer">
<div class="align-items-center d-flex justify-content-between">

<div>
<button class="student_task_done btn btn-default btn-sm no" data-task-id="853">
<span class="no"><i aria-hidden="true" class="fa fa-square-o "></i></span>
<span class="yes"><i aria-hidden="true" class="fa fa-check-square-o "></i></span>
<span class="pending"><i aria-hidden="true" class="fa fa-spinner  fa-pulse"></i></span>
Done<span class="no pending">?</span><span class="yes">!</span>
</button>

<button class="student-task-done-by btn btn-default btn-sm" data-task-id="853" data-batch-id="26" data-toggle="modal" data-target="#task-853-users-done-modal">
Help
</button>
<div class="modal fade users-done-modal" id="task-853-users-done-modal" data-task-id="853" data-batch-id="26">
<div class="modal-dialog">
<div class="modal-content">
<div class="modal-header">
<button type="button" class="close" data-dismiss="modal" aria-label="Close"><span aria-hidden="true">&times;</span></button>
<h4 class="modal-title">Students who are done with "7. There are only 3 colors, 10 digits, and 7 notes; it&#39;s what we do with them that&#39;s important"</h4>
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


<button class="btn btn-default btn-sm check-your-task-853-modal-button" data-task-id="853" data-toggle="modal" data-target="#task-test-correction-853-correction-modal" id="task-num-7-check-code-btn" data-gtm-custom-event-name="task_checker_modal" data-gtm-custom-event-options='{&quot;taskId&quot;:853}'>
Check your code
</button>
<div class="modal fade task_correction_modal student_modal" id="task-test-correction-853-correction-modal">
<div class="modal-dialog">
<div class="modal-content">
<div class="modal-header">
<button type="button" class="close" data-dismiss="modal" aria-label="Close"><span aria-hidden="true">&times;</span></button>
<h4 class="modal-title">Correction of "7. There are only 3 colors, 10 digits, and 7 notes; it&#39;s what we do with them that&#39;s important"</h4>
</div>
<div class="modal-body">
<div class="actions">
<center>
    <div class="alert alert-info hidden"></div>

    <button name="button" type="submit" class="btn btn-primary correction_request_test_send" data-task-id="853">Start a new test</button>
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
<button data-task-id="853">
<i aria-hidden="true" class="fa fa-info-circle "></i>
</button>
<div class="help-container" data-task-id="853">
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



<button class="btn btn-default btn-sm" data-toggle="modal" data-target="#container-specs-modal" data-gtm-custom-event-name="task_sandbox_modal" data-gtm-custom-event-options="{&quot;taskId&quot;:853}"><i aria-hidden="true" class="fa fa-terminal "></i><span>Get a sandbox</span></button>

</div>


<div class="fs-4">
</div>
</div>


</div>
</div>

</div>
<div data-role="task854" data-position="9" id="task-num-8">
<div class="panel panel-default task-card " id="task-854">
<span id="user_id" data-id="197885"></span>

<div class="panel-heading panel-heading-actions">
<h3 class="panel-title">
8. I&#39;m federal agent Jack Bauer, and today is the longest day of my life
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
<p>Write a function that prints every minute of the day of Jack Bauer, starting from 00:00 to 23:59.</p>

<ul>
<li>Prototype: <code>void jack_bauer(void);</code></li>
<li>You can listen to <a href="/rltoken/aNwRcWg7MPM1J2lYuuuBjA" title="this soundtrack" target="_blank">this soundtrack</a> while coding :)</li>
</ul>

<pre><code>julien@ubuntu:~/0x02$ cat 8-main.c
#include &quot;main.h&quot;

/**
* main - check the code
*
* Return: Always 0.
*/
int main(void)
{
jack_bauer();
return (0);
}
julien@ubuntu:~/0x02$ gcc -Wall -pedantic -Werror -Wextra -std=gnu89 _putchar.c 8-main.c 8-24_hours.c -o 8-24
julien@ubuntu:~/0x02$ ./8-24 | head
00:00
00:01
00:02
00:03
00:04
00:05
00:06
00:07
00:08
00:09
julien@ubuntu:~/0x02$ ./8-24 | tail
23:50
23:51
23:52
23:53
23:54
23:55
23:56
23:57
23:58
23:59
julien@ubuntu:~/0x02$ ./8-24 | wc -l
1440
julien@ubuntu:~/0x02$ 
</code></pre>

</div>

<div class="list-group">
<!-- Task URLs -->

<!-- Github information -->
<div class="list-group-item">
<p><strong>Repo:</strong></p>
<ul>
<li>GitHub repository: <code>alx-low_level_programming</code></li>
<li>Directory: <code>0x02-functions_nested_loops</code></li>
<li>File: <code>8-24_hours.c</code></li>
</ul>
</div>

<!-- Self-paced manual review -->
</div>

<!-- Panel footer - Controls -->
<div class="panel-footer">
<div class="align-items-center d-flex justify-content-between">

<div>
<button class="student_task_done btn btn-default btn-sm no" data-task-id="854">
<span class="no"><i aria-hidden="true" class="fa fa-square-o "></i></span>
<span class="yes"><i aria-hidden="true" class="fa fa-check-square-o "></i></span>
<span class="pending"><i aria-hidden="true" class="fa fa-spinner  fa-pulse"></i></span>
Done<span class="no pending">?</span><span class="yes">!</span>
</button>

<button class="student-task-done-by btn btn-default btn-sm" data-task-id="854" data-batch-id="26" data-toggle="modal" data-target="#task-854-users-done-modal">
Help
</button>
<div class="modal fade users-done-modal" id="task-854-users-done-modal" data-task-id="854" data-batch-id="26">
<div class="modal-dialog">
<div class="modal-content">
<div class="modal-header">
<button type="button" class="close" data-dismiss="modal" aria-label="Close"><span aria-hidden="true">&times;</span></button>
<h4 class="modal-title">Students who are done with "8. I&#39;m federal agent Jack Bauer, and today is the longest day of my life"</h4>
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


<button class="btn btn-default btn-sm check-your-task-854-modal-button" data-task-id="854" data-toggle="modal" data-target="#task-test-correction-854-correction-modal" id="task-num-8-check-code-btn" data-gtm-custom-event-name="task_checker_modal" data-gtm-custom-event-options='{&quot;taskId&quot;:854}'>
Check your code
</button>
<div class="modal fade task_correction_modal student_modal" id="task-test-correction-854-correction-modal">
<div class="modal-dialog">
<div class="modal-content">
<div class="modal-header">
<button type="button" class="close" data-dismiss="modal" aria-label="Close"><span aria-hidden="true">&times;</span></button>
<h4 class="modal-title">Correction of "8. I&#39;m federal agent Jack Bauer, and today is the longest day of my life"</h4>
</div>
<div class="modal-body">
<div class="actions">
<center>
    <div class="alert alert-info hidden"></div>

    <button name="button" type="submit" class="btn btn-primary correction_request_test_send" data-task-id="854">Start a new test</button>
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
<button data-task-id="854">
<i aria-hidden="true" class="fa fa-info-circle "></i>
</button>
<div class="help-container" data-task-id="854">
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



<button class="btn btn-default btn-sm" data-toggle="modal" data-target="#container-specs-modal" data-gtm-custom-event-name="task_sandbox_modal" data-gtm-custom-event-options="{&quot;taskId&quot;:854}"><i aria-hidden="true" class="fa fa-terminal "></i><span>Get a sandbox</span></button>

</div>


<div class="fs-4">
</div>
</div>


</div>
</div>

</div>
<div data-role="task855" data-position="10" id="task-num-9">
<div class="panel panel-default task-card " id="task-855">
<span id="user_id" data-id="197885"></span>

<div class="panel-heading panel-heading-actions">
<h3 class="panel-title">
9. Learn your times table
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
<p>Write a function that prints the 9 times table, starting with 0.</p>

<ul>
<li>Prototype: <code>void times_table(void);</code></li>
<li>Format: see example</li>
</ul>

<pre><code>julien@ubuntu:~/0x02$ cat 9-main.c
#include &quot;main.h&quot;

/**
* main - check the code
*
* Return: Always 0.
*/
int main(void)
{
times_table();
return (0);
}
julien@ubuntu:~/0x02$ gcc -Wall -pedantic -Werror -Wextra -std=gnu89 _putchar.c 9-main.c 9-times_table.c -o 9-times_table
ulien@ubuntu:~/0x02$ ./9-times_table | cat -e
0,  0,  0,  0,  0,  0,  0,  0,  0,  0$
0,  1,  2,  3,  4,  5,  6,  7,  8,  9$
0,  2,  4,  6,  8, 10, 12, 14, 16, 18$
0,  3,  6,  9, 12, 15, 18, 21, 24, 27$
0,  4,  8, 12, 16, 20, 24, 28, 32, 36$
0,  5, 10, 15, 20, 25, 30, 35, 40, 45$
0,  6, 12, 18, 24, 30, 36, 42, 48, 54$
0,  7, 14, 21, 28, 35, 42, 49, 56, 63$
0,  8, 16, 24, 32, 40, 48, 56, 64, 72$
0,  9, 18, 27, 36, 45, 54, 63, 72, 81$
julien@ubuntu:~/0x02$ ./9-times_table | tr &#39; &#39; . | cat -e
0,..0,..0,..0,..0,..0,..0,..0,..0,..0$
0,..1,..2,..3,..4,..5,..6,..7,..8,..9$
0,..2,..4,..6,..8,.10,.12,.14,.16,.18$
0,..3,..6,..9,.12,.15,.18,.21,.24,.27$
0,..4,..8,.12,.16,.20,.24,.28,.32,.36$
0,..5,.10,.15,.20,.25,.30,.35,.40,.45$
0,..6,.12,.18,.24,.30,.36,.42,.48,.54$
0,..7,.14,.21,.28,.35,.42,.49,.56,.63$
0,..8,.16,.24,.32,.40,.48,.56,.64,.72$
0,..9,.18,.27,.36,.45,.54,.63,.72,.81$
julien@ubuntu:~/0x02$ 
</code></pre>

</div>

<div class="list-group">
<!-- Task URLs -->

<!-- Github information -->
<div class="list-group-item">
<p><strong>Repo:</strong></p>
<ul>
<li>GitHub repository: <code>alx-low_level_programming</code></li>
<li>Directory: <code>0x02-functions_nested_loops</code></li>
<li>File: <code>9-times_table.c</code></li>
</ul>
</div>

<!-- Self-paced manual review -->
</div>

<!-- Panel footer - Controls -->
<div class="panel-footer">
<div class="align-items-center d-flex justify-content-between">

<div>
<button class="student_task_done btn btn-default btn-sm no" data-task-id="855">
<span class="no"><i aria-hidden="true" class="fa fa-square-o "></i></span>
<span class="yes"><i aria-hidden="true" class="fa fa-check-square-o "></i></span>
<span class="pending"><i aria-hidden="true" class="fa fa-spinner  fa-pulse"></i></span>
Done<span class="no pending">?</span><span class="yes">!</span>
</button>

<button class="student-task-done-by btn btn-default btn-sm" data-task-id="855" data-batch-id="26" data-toggle="modal" data-target="#task-855-users-done-modal">
Help
</button>
<div class="modal fade users-done-modal" id="task-855-users-done-modal" data-task-id="855" data-batch-id="26">
<div class="modal-dialog">
<div class="modal-content">
<div class="modal-header">
<button type="button" class="close" data-dismiss="modal" aria-label="Close"><span aria-hidden="true">&times;</span></button>
<h4 class="modal-title">Students who are done with "9. Learn your times table"</h4>
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


<button class="btn btn-default btn-sm check-your-task-855-modal-button" data-task-id="855" data-toggle="modal" data-target="#task-test-correction-855-correction-modal" id="task-num-9-check-code-btn" data-gtm-custom-event-name="task_checker_modal" data-gtm-custom-event-options='{&quot;taskId&quot;:855}'>
Check your code
</button>
<div class="modal fade task_correction_modal student_modal" id="task-test-correction-855-correction-modal">
<div class="modal-dialog">
<div class="modal-content">
<div class="modal-header">
<button type="button" class="close" data-dismiss="modal" aria-label="Close"><span aria-hidden="true">&times;</span></button>
<h4 class="modal-title">Correction of "9. Learn your times table"</h4>
</div>
<div class="modal-body">
<div class="actions">
<center>
    <div class="alert alert-info hidden"></div>

    <button name="button" type="submit" class="btn btn-primary correction_request_test_send" data-task-id="855">Start a new test</button>
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
<button data-task-id="855">
<i aria-hidden="true" class="fa fa-info-circle "></i>
</button>
<div class="help-container" data-task-id="855">
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



<button class="btn btn-default btn-sm" data-toggle="modal" data-target="#container-specs-modal" data-gtm-custom-event-name="task_sandbox_modal" data-gtm-custom-event-options="{&quot;taskId&quot;:855}"><i aria-hidden="true" class="fa fa-terminal "></i><span>Get a sandbox</span></button>

</div>


<div class="fs-4">
</div>
</div>


</div>
</div>

</div>
<div data-role="task856" data-position="11" id="task-num-10">
<div class="panel panel-default task-card " id="task-856">
<span id="user_id" data-id="197885"></span>

<div class="panel-heading panel-heading-actions">
<h3 class="panel-title">
10. a + b
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
<p>Write a function that adds two integers and returns the result.</p>

<ul>
<li>Prototype: <code>int add(int, int);</code></li>
</ul>

<pre><code>julien@ubuntu:~/$ cat 10-main.c
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

n = add(89, 9);
printf(&quot;%d\n&quot;, n);
return (0);
}
julien@ubuntu:~/0x02$ gcc -Wall -pedantic -Werror -Wextra -std=gnu89 _putchar.c 10-main.c 10-add.c -o 10-add
julien@ubuntu:~/0x02$ ./10-add 
98
julien@ubuntu:~/0x02$ 
</code></pre>

</div>

<div class="list-group">
<!-- Task URLs -->

<!-- Github information -->
<div class="list-group-item">
<p><strong>Repo:</strong></p>
<ul>
<li>GitHub repository: <code>alx-low_level_programming</code></li>
<li>Directory: <code>0x02-functions_nested_loops</code></li>
<li>File: <code>10-add.c</code></li>
</ul>
</div>

<!-- Self-paced manual review -->
</div>

<!-- Panel footer - Controls -->
<div class="panel-footer">
<div class="align-items-center d-flex justify-content-between">

<div>
<button class="student_task_done btn btn-default btn-sm no" data-task-id="856">
<span class="no"><i aria-hidden="true" class="fa fa-square-o "></i></span>
<span class="yes"><i aria-hidden="true" class="fa fa-check-square-o "></i></span>
<span class="pending"><i aria-hidden="true" class="fa fa-spinner  fa-pulse"></i></span>
Done<span class="no pending">?</span><span class="yes">!</span>
</button>

<button class="student-task-done-by btn btn-default btn-sm" data-task-id="856" data-batch-id="26" data-toggle="modal" data-target="#task-856-users-done-modal">
Help
</button>
<div class="modal fade users-done-modal" id="task-856-users-done-modal" data-task-id="856" data-batch-id="26">
<div class="modal-dialog">
<div class="modal-content">
<div class="modal-header">
<button type="button" class="close" data-dismiss="modal" aria-label="Close"><span aria-hidden="true">&times;</span></button>
<h4 class="modal-title">Students who are done with "10. a + b"</h4>
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


<button class="btn btn-default btn-sm check-your-task-856-modal-button" data-task-id="856" data-toggle="modal" data-target="#task-test-correction-856-correction-modal" id="task-num-10-check-code-btn" data-gtm-custom-event-name="task_checker_modal" data-gtm-custom-event-options='{&quot;taskId&quot;:856}'>
Check your code
</button>
<div class="modal fade task_correction_modal student_modal" id="task-test-correction-856-correction-modal">
<div class="modal-dialog">
<div class="modal-content">
<div class="modal-header">
<button type="button" class="close" data-dismiss="modal" aria-label="Close"><span aria-hidden="true">&times;</span></button>
<h4 class="modal-title">Correction of "10. a + b"</h4>
</div>
<div class="modal-body">
<div class="actions">
<center>
    <div class="alert alert-info hidden"></div>

    <button name="button" type="submit" class="btn btn-primary correction_request_test_send" data-task-id="856">Start a new test</button>
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
<button data-task-id="856">
<i aria-hidden="true" class="fa fa-info-circle "></i>
</button>
<div class="help-container" data-task-id="856">
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



<button class="btn btn-default btn-sm" data-toggle="modal" data-target="#container-specs-modal" data-gtm-custom-event-name="task_sandbox_modal" data-gtm-custom-event-options="{&quot;taskId&quot;:856}"><i aria-hidden="true" class="fa fa-terminal "></i><span>Get a sandbox</span></button>

</div>


<div class="fs-4">
</div>
</div>


</div>
</div>

</div>
<div data-role="task857" data-position="12" id="task-num-11">
<div class="panel panel-default task-card " id="task-857">
<span id="user_id" data-id="197885"></span>

<div class="panel-heading panel-heading-actions">
<h3 class="panel-title">
11. 98 Battery Street, the OG
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
<p>Write a function that prints all natural numbers from <code>n</code> to <code>98</code>, followed by a new line.</p>

<ul>
<li>Prototype: <code>void print_to_98(int n);</code></li>
<li>Numbers must be separated by a comma, followed by a space</li>
<li>Numbers should be printed in order</li>
<li>The first printed number should be the number passed to your function</li>
<li>The last printed number should be <code>98</code></li>
<li>You are allowed to use the standard library</li>
</ul>

<pre><code>julien@ubuntu:~/0x02$ cat 11-main.c
#include &quot;main.h&quot;

/**
* main - check the code
*
* Return: Always 0.
*/
int main(void)
{
print_to_98(0);
print_to_98(98);
print_to_98(111);
print_to_98(81);
print_to_98(-10);
return (0);
}
julien@ubuntu:~/0x02$ gcc -Wall -pedantic -Werror -Wextra -std=gnu89 _putchar.c 11-main.c 11-print_to_98.c -o 11-98
julien@ubuntu:~/0x02$ ./11-98 
0, 1, 2, 3, 4, 5, 6, 7, 8, 9, 10, 11, 12, 13, 14, 15, 16, 17, 18, 19, 20, 21, 22, 23, 24, 25, 26, 27, 28, 29, 30, 31, 32, 33, 34, 35, 36, 37, 38, 39, 40, 41, 42, 43, 44, 45, 46, 47, 48, 49, 50, 51, 52, 53, 54, 55, 56, 57, 58, 59, 60, 61, 62, 63, 64, 65, 66, 67, 68, 69, 70, 71, 72, 73, 74, 75, 76, 77, 78, 79, 80, 81, 82, 83, 84, 85, 86, 87, 88, 89, 90, 91, 92, 93, 94, 95, 96, 97, 98
98
111, 110, 109, 108, 107, 106, 105, 104, 103, 102, 101, 100, 99, 98
81, 82, 83, 84, 85, 86, 87, 88, 89, 90, 91, 92, 93, 94, 95, 96, 97, 98
-10, -9, -8, -7, -6, -5, -4, -3, -2, -1, 0, 1, 2, 3, 4, 5, 6, 7, 8, 9, 10, 11, 12, 13, 14, 15, 16, 17, 18, 19, 20, 21, 22, 23, 24, 25, 26, 27, 28, 29, 30, 31, 32, 33, 34, 35, 36, 37, 38, 39, 40, 41, 42, 43, 44, 45, 46, 47, 48, 49, 50, 51, 52, 53, 54, 55, 56, 57, 58, 59, 60, 61, 62, 63, 64, 65, 66, 67, 68, 69, 70, 71, 72, 73, 74, 75, 76, 77, 78, 79, 80, 81, 82, 83, 84, 85, 86, 87, 88, 89, 90, 91, 92, 93, 94, 95, 96, 97, 98
julien@ubuntu:~/0x02$ 
</code></pre>

</div>

<div class="list-group">
<!-- Task URLs -->

<!-- Github information -->
<div class="list-group-item">
<p><strong>Repo:</strong></p>
<ul>
<li>GitHub repository: <code>alx-low_level_programming</code></li>
<li>Directory: <code>0x02-functions_nested_loops</code></li>
<li>File: <code>11-print_to_98.c</code></li>
</ul>
</div>

<!-- Self-paced manual review -->
</div>

<!-- Panel footer - Controls -->
<div class="panel-footer">
<div class="align-items-center d-flex justify-content-between">

<div>
<button class="student_task_done btn btn-default btn-sm no" data-task-id="857">
<span class="no"><i aria-hidden="true" class="fa fa-square-o "></i></span>
<span class="yes"><i aria-hidden="true" class="fa fa-check-square-o "></i></span>
<span class="pending"><i aria-hidden="true" class="fa fa-spinner  fa-pulse"></i></span>
Done<span class="no pending">?</span><span class="yes">!</span>
</button>

<button class="student-task-done-by btn btn-default btn-sm" data-task-id="857" data-batch-id="26" data-toggle="modal" data-target="#task-857-users-done-modal">
Help
</button>
<div class="modal fade users-done-modal" id="task-857-users-done-modal" data-task-id="857" data-batch-id="26">
<div class="modal-dialog">
<div class="modal-content">
<div class="modal-header">
<button type="button" class="close" data-dismiss="modal" aria-label="Close"><span aria-hidden="true">&times;</span></button>
<h4 class="modal-title">Students who are done with "11. 98 Battery Street, the OG"</h4>
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


<button class="btn btn-default btn-sm check-your-task-857-modal-button" data-task-id="857" data-toggle="modal" data-target="#task-test-correction-857-correction-modal" id="task-num-11-check-code-btn" data-gtm-custom-event-name="task_checker_modal" data-gtm-custom-event-options='{&quot;taskId&quot;:857}'>
Check your code
</button>
<div class="modal fade task_correction_modal student_modal" id="task-test-correction-857-correction-modal">
<div class="modal-dialog">
<div class="modal-content">
<div class="modal-header">
<button type="button" class="close" data-dismiss="modal" aria-label="Close"><span aria-hidden="true">&times;</span></button>
<h4 class="modal-title">Correction of "11. 98 Battery Street, the OG"</h4>
</div>
<div class="modal-body">
<div class="actions">
<center>
    <div class="alert alert-info hidden"></div>

    <button name="button" type="submit" class="btn btn-primary correction_request_test_send" data-task-id="857">Start a new test</button>
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
<button data-task-id="857">
<i aria-hidden="true" class="fa fa-info-circle "></i>
</button>
<div class="help-container" data-task-id="857">
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



<button class="btn btn-default btn-sm" data-toggle="modal" data-target="#container-specs-modal" data-gtm-custom-event-name="task_sandbox_modal" data-gtm-custom-event-options="{&quot;taskId&quot;:857}"><i aria-hidden="true" class="fa fa-terminal "></i><span>Get a sandbox</span></button>

</div>


<div class="fs-4">
</div>
</div>


</div>
</div>

</div>

<p class="lg-gap">
<form class="button_to" method="post" action="/projects/214/unlock_optionals"><input id="unlock_optional_btn" class="btn btn-primary btn-block" data-confirm="Are you sure? Make sure you focused on the mandatory tasks first" data-disable-with="Unlocking 5 advanced tasks..." data-gtm-custom-event-name="project_unlock_advanced_tasks" type="submit" value="Done with the mandatory tasks? Unlock 5 advanced tasks now!" /><input type="hidden" name="authenticity_token" value="xqX3Ffq6VS-M-v5IQcJCpG6YjI7rQ3yUbMF_a5tUpS__IQmWgoTywgzfT-VElQqT-eqCsAZ_QR0xdTktfz3UVQ" autocomplete="off" /></form>
</p>




<div class="modal fade" id="container-specs-modal"><div class="modal-dialog modal-lg"><div class="modal-content"><div class="modal-header"><button type="button" class="close" data-dismiss="modal" aria-label="Close"><span aria-hidden="true">&times;</span></button><h4 class="modal-title">Recommended Sandbox</h4></div><div class="modal-body"><div data-react-class="user_containers/ContainerSpecs" data-react-props="{&quot;containerModelName&quot;:&quot;Sandbox&quot;,&quot;containerSpecs&quot;:[{&quot;description&quot;:&quot;\u003cp\u003eBasic Ubuntu 20.04, with vim, emacs, curl, wget and all needed for Foundations\u003c/p\u003e\n&quot;,&quot;id&quot;:39,&quot;name&quot;:&quot;Ubuntu 20.04&quot;,&quot;online&quot;:true,&quot;container&quot;:{&quot;container_id&quot;:&quot;c4e7755b271894d6b87d359c2ee6cf3e671d80d61d2080878d7d18ac32959bfc&quot;,&quot;id&quot;:239271,&quot;restart_uri&quot;:&quot;/user_containers/239271/restart.json&quot;,&quot;status&quot;:&quot;running&quot;,&quot;uri&quot;:&quot;/user_containers/239271.json&quot;,&quot;wake_uri&quot;:&quot;/user_containers/239271/wake.json&quot;,&quot;webterm_uri&quot;:&quot;/user_containers/239271/webterm&quot;,&quoquot;host&quot;:&quot;c4e7755b2718.3f09d370.alx-cod.online&quot;,&quot;password&quot;:&quot;2deaf74c415af9350d02&quot;,&quot;ports&quot;:{&quot;4000&quot;:49897,&quot;443&quot;:49900,&quot;8000&quot;:49894,&quot;8080&quot;:49893,&quot;3000&quot;:49899,&quot;3306&quot;:49898,&quot;5001&quot;:49895,&quot;80&quot;:49901,&quot;22&quot;:49902,&quot;5000&quot;:49896}}}],&quot;containersLimit&quot;:2,&quot;csrfToken&quot;:&quot;VsGAdQcmi7W0KvEh57PfIo1Z33v8e7uvf9_T816tvUajkKpwWRq66XBdrzleuDpMrLgHhWomv-TidMRAohd38w&quot;,&quot;startStatusURI&quot;:&quot;/user_containers/start_status.json&quot;,&quot;startURI&quot;:&quot;/user_containers/start.json&quot;}" data-react-cache-id="user_containers/ContainerSpecs-0"></div></div></div></div></div>

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