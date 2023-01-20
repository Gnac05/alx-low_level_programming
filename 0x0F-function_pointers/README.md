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


<title>Project: 0x0F. C - Function pointers | ALX Africa Intranet</title>

<link rel="stylesheet" href="https://use.typekit.net/xgz4ilr.css">
<link rel="stylesheet" media="all" href="/assets/application_alx-3bc505f2e3a9303a2388308cf98416618d0d78415692ec6a831f106956700814.css" />
<script src="https://www.gstatic.com/charts/loader.js"></script>
<script src="/assets/application-35dd1bfa2a15daa7dc2c7f29abbedd235e98278dee45b81fab4fd94785e21388.js"></script>
<link rel="shortcut icon" type="image/x-icon" href="/favicon_alx.ico" />
<meta name="csrf-param" content="authenticity_token" />
<meta name="csrf-token" content="XpbJHjjZKHoteNVN7BDs0QSLQ5kJ8vZ5rJf6DFn_cLy2RYzIchGhRRxiJIKFswwjCbSA6UBt5-YcXdKnK3vB6A" />

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
<div class="inner" style="background-image: url('https://s3.amazonaws.com/alx-intranet.hbtn.io/users/photos/000/197/885/thumb/joker.jpg?X-Amz-Algorithm=AWS4-HMAC-SHA256&amp;X-Amz-Credential=AKIARDDGGGOUSBVO6H7D%2F20230120%2Fus-east-1%2Fs3%2Faws4_request&amp;X-Amz-Date=20230120T132052Z&amp;X-Amz-Expires=600&amp;X-Amz-SignedHeaders=host&amp;X-Amz-Signature=45af958e2f523cdd05f0164cfe957e1214cafc7e50bcf2f67674b27cb251e99c')"></div>
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
<div class="inner" style="background-image: url('https://s3.amazonaws.com/alx-intranet.hbtn.io/users/photos/000/197/885/thumb/joker.jpg?X-Amz-Algorithm=AWS4-HMAC-SHA256&amp;X-Amz-Credential=AKIARDDGGGOUSBVO6H7D%2F20230120%2Fus-east-1%2Fs3%2Faws4_request&amp;X-Amz-Date=20230120T132052Z&amp;X-Amz-Expires=600&amp;X-Amz-SignedHeaders=host&amp;X-Amz-Signature=45af958e2f523cdd05f0164cfe957e1214cafc7e50bcf2f67674b27cb251e99c')"></div>
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
You have a captain's log due before 2023-01-22 (in 2 days)! Log it now!
</div>
</a>    </div>

</div>

<article class="pending_logs">


<div class="project row">
<div class="col-xs-12 col-md-10 col-lg-8 contains-images">

<h1 class="gap">0x0F. C - Function pointers</h1>

<div data-react-class="tags/Tags" data-react-props="{&quot;tags&quot;:[{&quot;id&quot;:7,&quot;value&quot;:&quot;C&quot;,&quot;author_id&quot;:null,&quot;created_at&quot;:&quot;2022-06-16T01:59:38.000Z&quot;,&quot;updated_at&quot;:&quot;2022-06-16T01:59:38.000Z&quot;}]}" data-react-cache-id="tags/Tags-0"></div>

<div data-react-class="projects/ProjectMetadata" data-react-props="{&quot;metadata&quot;:{&quot;author&quot;:&quot;Alexandre Gautier&quot;,&quot;weight&quot;:1,&quot;correction&quot;:{&quot;released&quot;:true,&quot;auto_correction_available_at&quot;:&quot;2023-01-18T07:12:00.000+03:00&quot;,&quot;requires_auto_correction&quot;:true,&quot;requires_manual_correction&quot;:false},&quot;bpi&quot;:{&quot;current&quot;:true,&quot;started&quot;:false,&quot;in_second_deadline&quot;:false,&quot;starts_at&quot;:&quot;2023-01-18T06:00:00.000+03:00&quot;,&quot;ends_at&quot;:&quot;2023-01-23T06:00:00.000+03:00&quot;,&quot;second_deadline_at&quot;:&quot;2023-01-26T06:00:00.000+03:00&quot;}}}" data-react-cache-id="projects/ProjectMetadata-0"></div>







<div id="project_id" style="display: none" data-project-id="226"></div>







<div class="panel panel-default" id="project-description">
<div class="panel-body">
<h2>Resources</h2>

<p><strong>Read or watch</strong>:</p>

<ul>
<li><a href="/rltoken/yt8Q9jxzT_gyRAvnNkAgkw" title="Function Pointer in C" target="_blank">Function Pointer in C</a> </li>
<li><a href="/rltoken/wP-yWvo9IqbcQsywMmh_iQ" title="Pointers to functions" target="_blank">Pointers to functions</a> </li>
<li><a href="/rltoken/dAN27S1yyBPeBa8RGfvPNA" title="Function Pointers in C / C++" target="_blank">Function Pointers in C / C++</a> </li>
<li><a href="/rltoken/1vvWpH9Ux8axOLc9jPWcMw" title="why pointers to functions?" target="_blank">why pointers to functions?</a> </li>
<li><a href="/rltoken/G_0lQzs4LAd1e5tKhNMPiw" title="Everything you need to know about pointers in C" target="_blank">Everything you need to know about pointers in C</a> </li>
</ul>

<h2>Learning Objectives</h2>

<p>At the end of this project, you are expected to be able to <a href="/rltoken/ITYG4BLMI4_5Unpdwue2tw" title="explain to anyone" target="_blank">explain to anyone</a>, <strong>without the help of Google</strong>:</p>

<h3>General</h3>

<ul>
<li>What are function pointers and how to use them</li>
<li>What does a function pointer exactly hold</li>
<li>Where does a function pointer point to in the virtual memory</li>
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
<li>The prototypes of all your functions and the prototype of the function <code>_putchar</code> should be included in your header file called <code>function_pointers.h</code></li>
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


<section class="quiz_questions_show_container">
<div class="quiz_question_item_container" data-role="quiz_question513" data-position="3">
<div class=" clearfix" id="quiz_question-513">

<h4 class="quiz_question">

Question #0
</h4>

<!-- Quiz question Body -->
<p>If <code>f</code> is a pointer to a function that takes no parameter and returns an <code>int</code>, you can call the function pointed by <code>f</code> this way (check all correct answers if there is more than one):</p>


<!-- Quiz question Answers -->
<ul class="quiz_question_answers" data-question-id="513">
<li class="">

<input type="checkbox" name="513" id="513-1508305363160" value="1508305363160" data-quiz-answer-id="1508305363160" data-quiz-question-id="513" />
<label for="513-1508305363160"><p>f();</p>
</label>
</li>

<li class="">

<input type="checkbox" name="513" id="513-1508305404563" value="1508305404563" data-quiz-answer-id="1508305404563" data-quiz-question-id="513" />
<label for="513-1508305404563"><p>f;</p>
</label>
</li>

<li class="">

<input type="checkbox" name="513" id="513-1508305374287" value="1508305374287" data-quiz-answer-id="1508305374287" data-quiz-question-id="513" />
<label for="513-1508305374287"><p>(*f)();</p>
</label>
</li>

</ul>

<!-- Quiz question Tips -->

</div>

</div>
<div class="quiz_question_item_container" data-role="quiz_question514" data-position="4">
<div class=" clearfix" id="quiz_question-514">

<h4 class="quiz_question">

Question #1
</h4>

<!-- Quiz question Body -->
<p>This <code>void (*anjula[])(int, float)</code> is:</p>


<!-- Quiz question Answers -->
<ul class="quiz_question_answers" data-question-id="514">
<li class="">

<input type="radio" name="514" id="514-1508305593000" value="1508305593000" data-quiz-answer-id="1508305593000" data-quiz-question-id="514" />
<label for="514-1508305593000"><p>A pointer to an array of functions that take an <code>int</code> and a <code>float</code> as parameters and returns nothing</p>
</label>
</li>

<li class="">

<input type="radio" name="514" id="514-1508305469598" value="1508305469598" data-quiz-answer-id="1508305469598" data-quiz-question-id="514" />
<label for="514-1508305469598"><p>A pointer to a function that takes an <code>int</code> and a <code>float</code> as parameters and returns nothing</p>
</label>
</li>

<li class="">

<input type="radio" name="514" id="514-1508305512032" value="1508305512032" data-quiz-answer-id="1508305512032" data-quiz-question-id="514" />
<label for="514-1508305512032"><p>A pointer to a function that takes an array of <code>int</code> and <code>float</code> as a parameter and returns nothing</p>
</label>
</li>

<li class="">

<input type="radio" name="514" id="514-1508305566314" value="1508305566314" data-quiz-answer-id="1508305566314" data-quiz-question-id="514" />
<label for="514-1508305566314"><p>An array of pointers to functions that take an <code>int</code> and a <code>float</code> as parameters and returns nothing</p>
</label>
</li>

<li class="">

<input type="radio" name="514" id="514-1508305543720" value="1508305543720" data-quiz-answer-id="1508305543720" data-quiz-question-id="514" />
<label for="514-1508305543720"><p>A pointer to a function that takes an <code>int</code> and a <code>float</code> as parameters and returns an empty array</p>
</label>
</li>

</ul>

<!-- Quiz question Tips -->

</div>

</div>
<div class="quiz_question_item_container" data-role="quiz_question511" data-position="1">
<div class=" clearfix" id="quiz_question-511">

<h4 class="quiz_question">

Question #2
</h4>

<!-- Quiz question Body -->
<p>Which one is a pointer to a function?</p>


<!-- Quiz question Answers -->
<ul class="quiz_question_answers" data-question-id="511">
<li class="">

<input type="radio" name="511" id="511-1508304715133" value="1508304715133" data-quiz-answer-id="1508304715133" data-quiz-question-id="511" />
<label for="511-1508304715133"><p>int (*func)(int a, float b);</p>
</label>
</li>

<li class="">

<input type="radio" name="511" id="511-1508304692616" value="1508304692616" data-quiz-answer-id="1508304692616" data-quiz-question-id="511" />
<label for="511-1508304692616"><p>int func(int a, float b);</p>
</label>
</li>

<li class="">

<input type="radio" name="511" id="511-1508304722369" value="1508304722369" data-quiz-answer-id="1508304722369" data-quiz-question-id="511" />
<label for="511-1508304722369"><p>(int *)func(int a, float b);</p>
</label>
</li>

<li class="">

<input type="radio" name="511" id="511-1508304707385" value="1508304707385" data-quiz-answer-id="1508304707385" data-quiz-question-id="511" />
<label for="511-1508304707385"><p>int *func(int a, float b);</p>
</label>
</li>

</ul>

<!-- Quiz question Tips -->

</div>

</div>
<div class="quiz_question_item_container" data-role="quiz_question515" data-position="5">
<div class=" clearfix" id="quiz_question-515">

<h4 class="quiz_question">

Question #3
</h4>

<!-- Quiz question Body -->
<p>What does a pointer to a function point to (check all correct answers if there is more than one)?</p>


<!-- Quiz question Answers -->
<ul class="quiz_question_answers" data-question-id="515">
<li class="">

<input type="checkbox" name="515" id="515-1508305771886" value="1508305771886" data-quiz-answer-id="1508305771886" data-quiz-question-id="515" />
<label for="515-1508305771886"><p>The first character of the name of the function</p>
</label>
</li>

<li class="">

<input type="checkbox" name="515" id="515-1508305748476" value="1508305748476" data-quiz-answer-id="1508305748476" data-quiz-question-id="515" />
<label for="515-1508305748476"><p>data</p>
</label>
</li>

<li class="">

<input type="checkbox" name="515" id="515-1508305784505" value="1508305784505" data-quiz-answer-id="1508305784505" data-quiz-question-id="515" />
<label for="515-1508305784505"><p>The first byte of code of the function</p>
</label>
</li>

<li class="">

<input type="checkbox" name="515" id="515-1508305764393" value="1508305764393" data-quiz-answer-id="1508305764393" data-quiz-question-id="515" />
<label for="515-1508305764393"><p>code</p>
</label>
</li>

</ul>

<!-- Quiz question Tips -->

</div>

</div>
<div class="quiz_question_item_container" data-role="quiz_question512" data-position="2">
<div class=" clearfix" id="quiz_question-512">

<h4 class="quiz_question">

Question #4
</h4>

<!-- Quiz question Body -->
<p>To store the address of this function:</p>

<pre><code>void neyo(void);
</code></pre>

<p>to the variable <code>f</code> of type pointer to a function that does not take any argument and does not return anything, you would do (check all correct answers if there is more than one):</p>


<!-- Quiz question Answers -->
<ul class="quiz_question_answers" data-question-id="512">
<li class="">

<input type="checkbox" name="512" id="512-1508304939621" value="1508304939621" data-quiz-answer-id="1508304939621" data-quiz-question-id="512" />
<label for="512-1508304939621"><p>*f = neyo;</p>
</label>
</li>

<li class="">

<input type="checkbox" name="512" id="512-1508304924789" value="1508304924789" data-quiz-answer-id="1508304924789" data-quiz-question-id="512" />
<label for="512-1508304924789"><p>f = neyo;</p>
</label>
</li>

<li class="">

<input type="checkbox" name="512" id="512-1508304945125" value="1508304945125" data-quiz-answer-id="1508304945125" data-quiz-question-id="512" />
<label for="512-1508304945125"><p>*f = &neyo;</p>
</label>
</li>

<li class="">

<input type="checkbox" name="512" id="512-1508304932510" value="1508304932510" data-quiz-answer-id="1508304932510" data-quiz-question-id="512" />
<label for="512-1508304932510"><p>f = &neyo;</p>
</label>
</li>

</ul>

<!-- Quiz question Tips -->

</div>

</div>

<div class="quiz_questions_results">
<div class="spinner">
<div class="bounce1"></div>
<div class="bounce2"></div>
<div class="bounce3"></div>
</div>
<button class="btn btn-primary" data-project-id="226">Submit answers</button>
<div class="error"></div>
</div>
</section>
</div>
</div>


<h2 class="gap warning">Please make sure to validate all quiz questions before moving on to project tasks </h2>

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
