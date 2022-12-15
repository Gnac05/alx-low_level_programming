# ALX Software engineer

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

<script type="text/javascript" src="https://gc.kis.v2.scr.kaspersky-labs.com/FD126C42-EBFA-4E12-B309-BB3FDD723AC1/main.js?attr=LXmhiIRDity8zFU1mmLP-u9-bF-Pg_YSKbaj2Bf63WyWqK3up_r9pvKowuqUSaVox62AOyWQmDPXZ8zIVzcJRA" charset="UTF-8"></script><script>
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


<title>Project: 0x03. C - Debugging | ALX Africa Intranet</title>

<link rel="stylesheet" href="https://use.typekit.net/xgz4ilr.css">
<link rel="stylesheet" media="all" href="/assets/application_alx-3bc505f2e3a9303a2388308cf98416618d0d78415692ec6a831f106956700814.css" />
<script src="https://www.gstatic.com/charts/loader.js"></script>
<script src="/assets/application-35dd1bfa2a15daa7dc2c7f29abbedd235e98278dee45b81fab4fd94785e21388.js"></script>
<link rel="shortcut icon" type="image/x-icon" href="/favicon_alx.ico" />
<meta name="csrf-param" content="authenticity_token" />
<meta name="csrf-token" content="9Nn8PU2zVjsBt0llX8TifGWdfBfAv9A_yx3Km8iRDagBiNY4E49nZ8XAF33mzwcSRHyk6Vbi1HRWtt0oNCvHHQ" />

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
<div class="inner" style="background-image: url('https://s3.amazonaws.com/alx-intranet.hbtn.io/users/photos/000/197/885/thumb/joker.jpg?X-Amz-Algorithm=AWS4-HMAC-SHA256&amp;X-Amz-Credential=AKIARDDGGGOUSBVO6H7D%2F20221215%2Fus-east-1%2Fs3%2Faws4_request&amp;X-Amz-Date=20221215T160111Z&amp;X-Amz-Expires=600&amp;X-Amz-SignedHeaders=host&amp;X-Amz-Signature=51750f2b8bddf7d58c9b8699ff1fd57a4773fc5db691a0e9d4ff4acf145db2a1')"></div>
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
<div class="inner" style="background-image: url('https://s3.amazonaws.com/alx-intranet.hbtn.io/users/photos/000/197/885/thumb/joker.jpg?X-Amz-Algorithm=AWS4-HMAC-SHA256&amp;X-Amz-Credential=AKIARDDGGGOUSBVO6H7D%2F20221215%2Fus-east-1%2Fs3%2Faws4_request&amp;X-Amz-Date=20221215T160111Z&amp;X-Amz-Expires=600&amp;X-Amz-SignedHeaders=host&amp;X-Amz-Signature=51750f2b8bddf7d58c9b8699ff1fd57a4773fc5db691a0e9d4ff4acf145db2a1')"></div>
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

<h1 class="gap">0x03. C - Debugging</h1>

<div data-react-class="tags/Tags" data-react-props="{&quot;tags&quot;:[{&quot;id&quot;:7,&quot;value&quot;:&quot;C&quot;,&quot;author_id&quot;:null,&quot;created_at&quot;:&quot;2022-06-16T01:59:38.000Z&quot;,&quot;updated_at&quot;:&quot;2022-06-16T01:59:38.000Z&quot;},{&quot;id&quot;:31,&quot;value&quot;:&quot;Debugging&quot;,&quot;author_id&quot;:null,&quot;created_at&quot;:&quot;2022-06-16T01:59:38.000Z&quot;,&quot;updated_at&quot;:&quot;2022-06-16T01:59:38.000Z&quot;}]}" data-react-cache-id="tags/Tags-0"></div>

<div data-react-class="projects/ProjectMetadata" data-react-props="{&quot;metadata&quot;:{&quot;author&quot;:&quot;Carrie Ybay&quot;,&quot;weight&quot;:1,&quot;correction&quot;:{&quot;released&quot;:true,&quot;auto_correction_available_at&quot;:&quot;2022-12-14T00:00:00.000+03:00&quot;,&quot;requires_auto_correction&quot;:true,&quot;requires_manual_correction&quot;:false},&quot;bpi&quot;:{&quot;current&quot;:true,&quot;started&quot;:false,&quot;in_second_deadline&quot;:false,&quot;starts_at&quot;:&quot;2022-12-13T06:00:00.000+03:00&quot;,&quot;ends_at&quot;:&quot;2022-12-16T06:00:00.000+03:00&quot;,&quot;second_deadline_at&quot;:&quot;2022-12-17T06:00:00.000+03:00&quot;}}}" data-react-cache-id="projects/ProjectMetadata-0"></div>







<div id="project_id" style="display: none" data-project-id="539"></div>







<div class="panel panel-default" id="project-description">
<div class="panel-body">
<h2>Resources</h2>

<p><strong>Read or watch:</strong></p>

<ul>
<li><a href="/rltoken/faGcpiJiejHH6GhqpmbhUw" title="Debugging" target="_blank">Debugging</a></li>
<li><a href="/rltoken/RaecqJBNkmZ92vLMpNDuGg" title="Rubber Duck Debugging" target="_blank">Rubber Duck Debugging</a></li>
</ul>

<p>Debugging is the process of finding and fixing errors in software that prevents it from running correctly. As you become a more advanced programmer and an industry engineer, you will learn how to use debugging tools such as <code>gdb</code> or built-in tools that IDEs have. However, it&rsquo;s important to understand the concepts and processes of debugging manually.</p>

<p><img src="https://s3.amazonaws.com/alx-intranet.hbtn.io/uploads/medias/2019/5/af682f2cbb6d73fd4e42.jpg?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Credential=AKIARDDGGGOUSBVO6H7D%2F20221215%2Fus-east-1%2Fs3%2Faws4_request&X-Amz-Date=20221215T160111Z&X-Amz-Expires=86400&X-Amz-SignedHeaders=host&X-Amz-Signature=026b35041afddd694533658cf935865197d5be57b01eaa86fa6e433f9d705560" alt="" loading='lazy' style="" /></p>

<h2>Learning Objectives</h2>

<p>At the end of this project, you are expected to be able to <a href="/rltoken/b8uX1nIy0A55tWVlIRTaHQ" title="explain to anyone" target="_blank">explain to anyone</a>, without the help of Google:</p>

<h3>General</h3>

<ul>
<li>What is debugging</li>
<li>What are some methods of debugging manually</li>
<li>How to read the error messages</li>
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
<li>Your code should use the <code>Betty</code> style. It will be checked using <code>betty-style.pl</code> and <code>betty-doc.pl</code></li>
<li>A README.md file at the root of the repo, containing a description of the repository</li>
<li>A README.md file, at the root of the folder of this project (i.e. <code>0x03-debugging</code>), describing what this project is about</li>
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
<div class="quiz_question_item_container" data-role="quiz_question865" data-position="3">
<div class=" clearfix" id="quiz_question-865">

<h4 class="quiz_question">

Question #0
</h4>

<!-- Quiz question Body -->
<p>The following code gives this output. What is the error?</p>

<pre><code>carrie@ubuntu:/debugging$ cat main.c                                
#include &lt;stdio.h&gt;                                                                                  

/**                                                                                                 
* main - debugging example                                                                         
* Return: 0                                                                                        
*/                                                                                                 
int main(void)                                                                                      
{                                                                                                   
int i;                                                                                      
int j;                                                                                      
int k;                                                                                      

i = 0;                                                                                      
j = 1000;                                                                                   
while (i &lt; j)                                                                               
{                                                                                           
k = j / 98;                                                                         
i = i + k;                                                                          
printf(&quot;%d\n&quot;, i);                                                                  
j == j - 1;                                                                         
}                                                                                           

return (0);                                                                                 
}                                                                                                   
carrie@ubuntu:/debugging$
</code></pre>

<pre><code>carrie@ubuntu:/debugging$ gcc -Wall -Werror -Wextra -pedantic main.
c                                                                                                   
main.c: In function ‘main’:                                                                         
main.c:20:3: error: statement with no effect [-Werror=unused-value]                                 
j == j - 1;                                                                                      
^                                                                                                
cc1: all warnings being treated as errors                                                           
carrie@ubuntu:/debugging$
</code></pre>


<!-- Quiz question Answers -->
<ul class="quiz_question_answers" data-question-id="865">
<li class="">

<input type="radio" name="865" id="865-1557782391227" value="1557782391227" data-quiz-answer-id="1557782391227" data-quiz-question-id="865" disabled="disabled" />
<label for="865-1557782391227"><p>We don&rsquo;t need to assign a new value to <code>j</code> because it doesn&rsquo;t do anything</p>
</label>
</li>

<li class="">

<input type="radio" name="865" id="865-1557782394286" value="1557782394286" data-quiz-answer-id="1557782394286" data-quiz-question-id="865" disabled="disabled" />
<label for="865-1557782394286"><p>We want to compare <code>j</code> so we need an <code>if</code> statement before <code>j == j - 1</code></p>
</label>
</li>

<li class="">

<input type="radio" name="865" id="865-1557782393037" value="1557782393037" data-quiz-answer-id="1557782393037" data-quiz-question-id="865" disabled="disabled" checked="checked" />
<label for="865-1557782393037"><p>We want to assign <code>j</code> a new value, not compare it, so it should be <code>j = j - 1</code> instead of <code>j == j - 1</code></p>
</label>
</li>

</ul>

<!-- Quiz question Tips -->

</div>

</div>
<div class="quiz_question_item_container" data-role="quiz_question866" data-position="4">
<div class=" clearfix" id="quiz_question-866">

<h4 class="quiz_question">

Question #1
</h4>

<!-- Quiz question Body -->
<p>This code doesn&rsquo;t work as intended. </p>

<pre><code>#include &quot;main.h&quot;

/**
* main - prints even numbers from 0 to 100
* Return: 0
*/

int main(void)
{
int i;

for (i = 0; i &lt; 100; i++)
{
if (i % 2 != 0)
{
continue;
}
else
{
break;
}

printf(&quot;%d\n&quot;, i);
}

return(0);
}
</code></pre>

<p>Let&rsquo;s add <code>printf</code> statements to the code. What information do the <code>printf</code> statements tell us about how our code is executed?</p>

<pre><code>#include &quot;main.h&quot;

/**
* main - prints even numbers from 0 to 100
* Return: 0
*/

int main(void)
{
int i;

printf(&quot;Before loop\n&quot;);

for (i = 0; i &lt; 100; i++)
{
if (i % 2 != 0)
{
printf(&quot;i is not even so don&#39;t print\n&quot;);
continue;
}
else
{
printf(&quot;i is even, break to print\n&quot;);
break;
}

printf(&quot;Outside of if/else, still inside for loop\n&quot;);

printf(&quot;%d\n&quot;, i);
}

printf(&quot;For loop exited\n&quot;);

return(0);
}
</code></pre>


<!-- Quiz question Answers -->
<ul class="quiz_question_answers" data-question-id="866">
<li class="">

<input type="checkbox" name="866" id="866-1557858506856" value="1557858506856" data-quiz-answer-id="1557858506856" data-quiz-question-id="866" disabled="disabled" checked="checked" />
<label for="866-1557858506856"><p><code>printf</code> statements shows that <code>break</code> will cause &ldquo;For loop exited&rdquo; to print, indicating that the even number is never printed</p>
</label>
</li>

<li class="">

<input type="checkbox" name="866" id="866-1557858397111" value="1557858397111" data-quiz-answer-id="1557858397111" data-quiz-question-id="866" disabled="disabled" checked="checked" />
<label for="866-1557858397111"><p>A <code>printf</code> statement shows when the <code>for</code> loop is finished</p>
</label>
</li>

<li class="">

<input type="checkbox" name="866" id="866-1557858575741" value="1557858575741" data-quiz-answer-id="1557858575741" data-quiz-question-id="866" disabled="disabled" />
<label for="866-1557858575741"><p>A <code>printf</code> statement shows that there is an infinite loop in the code</p>
</label>
</li>

<li class="">

<input type="checkbox" name="866" id="866-1557858429748" value="1557858429748" data-quiz-answer-id="1557858429748" data-quiz-question-id="866" disabled="disabled" />
<label for="866-1557858429748"><p>A <code>printf</code> statement shows exactly how many times the loop executes</p>
</label>
</li>

</ul>

<!-- Quiz question Tips -->

</div>

</div>
<div class="quiz_question_item_container" data-role="quiz_question863" data-position="1">
<div class=" clearfix" id="quiz_question-863">

<h4 class="quiz_question">

Question #2
</h4>

<!-- Quiz question Body -->
<p>Look at the following code.</p>

<pre><code>carrie@ubuntu:/debugging$ cat main.c                                
#include &lt;stdio.h&gt;                                                                                  

/**                                                                                                 
* main - debugging example                                                                         
* Return: 0                                                                                        
*/                                                                                                 
int main(void)                                                                                      
{                                                                                                   
char *hello = &quot;Hello, World!&quot;;                                                              

for (i = 0; hello[i] != &#39;\0&#39;; i++)                                                          
{                                                                                           
printf(&quot;%c&quot;, hello[i]);                                                             
}                                                                                           

printf(&quot;\n&quot;);                                                                               

return (0);                                                                                 
}                                                                                                   
carrie@ubuntu:/debugging$
</code></pre>

<pre><code>carrie@ubuntu:/debugging$ gcc -Wall -Werror -Wextra -pedantic main.
c                                                                                                   
main.c: In function ‘main’:                                                                         
main.c:11:7: error: ‘i’ undeclared (first use in this function)                                     
for (i = 0; hello[i] != &#39;\0&#39;; i++)                                                                
^                                                                                            
main.c:11:7: note: each undeclared identifier is reported only once for each function it appears in
main.c:9:8: error: variable ‘hello’ set but not used [-Werror=unused-but-set-variable]              
char *hello = &quot;Hello, World!&quot;;                                                                    
^                                                                                           
cc1: all warnings being treated as errors                                                           
carrie@ubuntu:/debugging$                         
</code></pre>

<p>In the <code>main.c</code> file, on what line is the first error that the compiler returns?</p>


<!-- Quiz question Answers -->
<ul class="quiz_question_answers" data-question-id="863">
<li class="">

<input type="radio" name="863" id="863-1557782064790" value="1557782064790" data-quiz-answer-id="1557782064790" data-quiz-question-id="863" disabled="disabled" />
<label for="863-1557782064790"><p>9</p>
</label>
</li>

<li class="">

<input type="radio" name="863" id="863-1557782070360" value="1557782070360" data-quiz-answer-id="1557782070360" data-quiz-question-id="863" disabled="disabled" />
<label for="863-1557782070360"><p>7</p>
</label>
</li>

<li class="">

<input type="radio" name="863" id="863-1557782067998" value="1557782067998" data-quiz-answer-id="1557782067998" data-quiz-question-id="863" disabled="disabled" checked="checked" />
<label for="863-1557782067998"><p>11</p>
</label>
</li>

</ul>

<!-- Quiz question Tips -->
<div class="alert alert-info">
<h4>Tips:</h4>
<p>You do not have to know exactly what this code does yet (but you will soon!).</p>

</div>

</div>

</div>
<div class="quiz_question_item_container" data-role="quiz_question864" data-position="2">
<div class=" clearfix" id="quiz_question-864">

<h4 class="quiz_question">

Question #3
</h4>

<!-- Quiz question Body -->
<p>The following code gives this incorrect output. Which of the following statements about what is causing the error is true?</p>

<pre><code>carrie@ubuntu:/debugging$ cat main.c                               
#include &lt;stdio.h&gt;                                                                                 

/**                                                                                                
* main - debugging example                                                                        
* Return: 0                                                                                       
*/                                                                                                
int main(void)                                                                                     
{                                                                                                  
int i;                                                                                     
int j;                                                                                     

for (i = 0; i &lt; 10; i++)                                                                   
{                                                                                          
j = 0;                                                                             
while (j &lt; 10)                                                                     
{                                                                                  
printf(&quot;%d&quot;, j);                                                           
}                                                                                  
printf(&quot;\n&quot;);                                                                      
}                                                                                          

return (0);                                                                                
}                                                                                                  
carrie@ubuntu:/debugging$
</code></pre>

<pre><code>carrie@ubuntu:/debugging$ gcc -Wall -Werror -Wextra -pedantic main.c                                                                                                  
carrie@ubuntu:/debugging$ ./a.out
0000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000 &lt;...&gt;
^Ccarrie@ubuntu:/debugging$
</code></pre>


<!-- Quiz question Answers -->
<ul class="quiz_question_answers" data-question-id="864">
<li class="">

<input type="checkbox" name="864" id="864-1557782211325" value="1557782211325" data-quiz-answer-id="1557782211325" data-quiz-question-id="864" disabled="disabled" checked="checked" />
<label for="864-1557782211325"><p><code>j</code> never increments so it will always be less than <code>10</code></p>
</label>
</li>

<li class="">

<input type="checkbox" name="864" id="864-1557782214161" value="1557782214161" data-quiz-answer-id="1557782214161" data-quiz-question-id="864" disabled="disabled" checked="checked" />
<label for="864-1557782214161"><p><code>j</code> never increments so it is always going to print <code>0</code></p>
</label>
</li>

<li class="">

<input type="checkbox" name="864" id="864-1557782212596" value="1557782212596" data-quiz-answer-id="1557782212596" data-quiz-question-id="864" disabled="disabled" />
<label for="864-1557782212596"><p><code>j</code> is always equal to <code>i</code> so the loop will never end</p>
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

<div data-role="task3904" data-position="1" id="task-num-0">
<div class="panel panel-default task-card " id="task-3904">
<span id="user_id" data-id="197885"></span>

<div class="panel-heading panel-heading-actions">
<h3 class="panel-title">
0. Multiple mains
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
<p>In most projects, we often give you only one main file to test with. For example, this main file is a test for a <code>postitive_or_negative()</code> function similar to the one you worked with in <a href="/rltoken/lKcOFkG-GCivSDXgWgld2g" title="an earlier C project" target="_blank">an earlier C project</a>:</p>

<pre><code>carrie@ubuntu:/debugging$ cat main.c
#include &quot;main.h&quot;

/**
* main - tests function that prints if integer is positive or negative
* Return: 0
*/

int main(void)
{
int i;

i = 98;
positive_or_negative(i);

return (0);
}
carrie@ubuntu:/debugging$
</code></pre>

<pre><code>carrie@ubuntu:/debugging$ cat main.h
#ifndef MAIN_H
#define MAIN_H

#include &lt;stdio.h&gt;

void positive_or_negative(int i);

#endif /* MAIN_H */
carrie@ubuntu:/debugging$ 
</code></pre>

<pre><code>carrie@ubuntu:/debugging$ gcc -Wall -pedantic -Werror -Wextra -std=gnu89 positive_or_negative.c main.c
carrie@ubuntu:/debugging$ ./a.out
98 is positive
carrie@ubuntu:/debugging$
</code></pre>

<p>Based on the <code>main.c</code> file above, create a file named <code>0-main.c</code>. This file must test that the function <code>positive_or_negative()</code> gives the correct output when given a case of <code>0</code>.</p>

<p>You are not coding the solution / function, you&rsquo;re just testing it! However, you can adapt your function from <a href="/rltoken/lKcOFkG-GCivSDXgWgld2g" title="0x01. C - Variables, if, else, while - Task #0" target="_blank">0x01. C - Variables, if, else, while - Task #0</a> to compile with this main file to test locally.</p>

<ul>
<li>You only need to upload <code>0-main.c</code> and <code>main.h</code> for this task. We will provide our own <code>positive_or_negative()</code> function.</li>
<li>You are not allowed to add or remove lines of code, you may change only <strong>one</strong> line in this task.</li>
</ul>

<pre><code>carrie@ubuntu:/debugging$ gcc -Wall -pedantic -Werror -Wextra -std=gnu89 positive_or_negative.c 0-main.c -o 0-main
carrie@ubuntu:/debugging$ ./0-main
0 is zero
carrie@ubuntu:/debugging$ wc -l 0-main.c
16 1-main.c
carrie@ubuntu:/debugging$ 
</code></pre>

</div>

<div class="list-group">
<!-- Task URLs -->

<!-- Github information -->
<div class="list-group-item">
<p><strong>Repo:</strong></p>
<ul>
<li>GitHub repository: <code>alx-low_level_programming</code></li>
<li>Directory: <code>0x03-debugging</code></li>
<li>File: <code>0-main.c, main.h</code></li>
</ul>
</div>

<!-- Self-paced manual review -->
</div>

<!-- Panel footer - Controls -->
<div class="panel-footer">
<div class="align-items-center d-flex justify-content-between">

<div>
<button class="student_task_done btn btn-default btn-sm no" data-task-id="3904">
<span class="no"><i aria-hidden="true" class="fa fa-square-o "></i></span>
<span class="yes"><i aria-hidden="true" class="fa fa-check-square-o "></i></span>
<span class="pending"><i aria-hidden="true" class="fa fa-spinner  fa-pulse"></i></span>
Done<span class="no pending">?</span><span class="yes">!</span>
</button>

<button class="student-task-done-by btn btn-default btn-sm" data-task-id="3904" data-batch-id="26" data-toggle="modal" data-target="#task-3904-users-done-modal">
Help
</button>
<div class="modal fade users-done-modal" id="task-3904-users-done-modal" data-task-id="3904" data-batch-id="26">
<div class="modal-dialog">
<div class="modal-content">
<div class="modal-header">
<button type="button" class="close" data-dismiss="modal" aria-label="Close"><span aria-hidden="true">&times;</span></button>
<h4 class="modal-title">Students who are done with "0. Multiple mains"</h4>
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


<button class="btn btn-default btn-sm check-your-task-3904-modal-button" data-task-id="3904" data-toggle="modal" data-target="#task-test-correction-3904-correction-modal" id="task-num-0-check-code-btn" data-gtm-custom-event-name="task_checker_modal" data-gtm-custom-event-options='{&quot;taskId&quot;:3904}'>
Check your code
</button>
<div class="modal fade task_correction_modal student_modal" id="task-test-correction-3904-correction-modal">
<div class="modal-dialog">
<div class="modal-content">
<div class="modal-header">
<button type="button" class="close" data-dismiss="modal" aria-label="Close"><span aria-hidden="true">&times;</span></button>
<h4 class="modal-title">Correction of "0. Multiple mains"</h4>
</div>
<div class="modal-body">
<div class="actions">
<center>
<div class="alert alert-info hidden"></div>

<button name="button" type="submit" class="btn btn-primary correction_request_test_send" data-task-id="3904">Start a new test</button>
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
<button data-task-id="3904">
<i aria-hidden="true" class="fa fa-info-circle "></i>
</button>
<div class="help-container" data-task-id="3904">
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
<div data-role="task3905" data-position="2" id="task-num-1">
<div class="panel panel-default task-card " id="task-3905">
<span id="user_id" data-id="197885"></span>

<div class="panel-heading panel-heading-actions">
<h3 class="panel-title">
1. Like, comment, subscribe
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
<p>Copy this main file. Comment out (don&rsquo;t delete it!) the part of the code that is causing the output to go into an infinite loop.</p>

<ul>
<li>Don&rsquo;t add or remove any lines of code, as we will be checking your line count. You are only allowed to comment out existing code.</li>
<li>You do not have to compile with <code>-Wall -Werror -Wextra -pedantic</code> for this task.</li>
</ul>

<pre><code>carrie@ubuntu:/debugging$ cat 1-main.c
#include &lt;stdio.h&gt;

/**
* main - causes an infinite loop
* Return: 0
*/

int main(void)
{
int i;

printf(&quot;Infinite loop incoming :(\n&quot;);

i = 0;

while (i &lt; 10)
{
putchar(i);
}

printf(&quot;Infinite loop avoided! \\o/\n&quot;);

return (0);
}
carrie@ubuntu:/debugging$
</code></pre>

<p>Your output should look like this:</p>

<pre><code>carrie@ubuntu:/debugging$ gcc -std=gnu89 1-main.c -o 1-main
carrie@ubuntu:/debugging$ ./1-main
Infinite loop incoming :(
Infinite loop avoided! \o/
carrie@ubuntu:/debugging$ wc -l 1-main.c
24 1-main.c
carrie@ubuntu:/debugging$
</code></pre>

</div>

<div class="list-group">
<!-- Task URLs -->

<!-- Github information -->
<div class="list-group-item">
<p><strong>Repo:</strong></p>
<ul>
<li>GitHub repository: <code>alx-low_level_programming</code></li>
<li>Directory: <code>0x03-debugging</code></li>
<li>File: <code>1-main.c</code></li>
</ul>
</div>

<!-- Self-paced manual review -->
</div>

<!-- Panel footer - Controls -->
<div class="panel-footer">
<div class="align-items-center d-flex justify-content-between">

<div>
<button class="student_task_done btn btn-default btn-sm no" data-task-id="3905">
<span class="no"><i aria-hidden="true" class="fa fa-square-o "></i></span>
<span class="yes"><i aria-hidden="true" class="fa fa-check-square-o "></i></span>
<span class="pending"><i aria-hidden="true" class="fa fa-spinner  fa-pulse"></i></span>
Done<span class="no pending">?</span><span class="yes">!</span>
</button>

<button class="student-task-done-by btn btn-default btn-sm" data-task-id="3905" data-batch-id="26" data-toggle="modal" data-target="#task-3905-users-done-modal">
Help
</button>
<div class="modal fade users-done-modal" id="task-3905-users-done-modal" data-task-id="3905" data-batch-id="26">
<div class="modal-dialog">
<div class="modal-content">
<div class="modal-header">
<button type="button" class="close" data-dismiss="modal" aria-label="Close"><span aria-hidden="true">&times;</span></button>
<h4 class="modal-title">Students who are done with "1. Like, comment, subscribe"</h4>
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


<button class="btn btn-default btn-sm check-your-task-3905-modal-button" data-task-id="3905" data-toggle="modal" data-target="#task-test-correction-3905-correction-modal" id="task-num-1-check-code-btn" data-gtm-custom-event-name="task_checker_modal" data-gtm-custom-event-options='{&quot;taskId&quot;:3905}'>
Check your code
</button>
<div class="modal fade task_correction_modal student_modal" id="task-test-correction-3905-correction-modal">
<div class="modal-dialog">
<div class="modal-content">
<div class="modal-header">
<button type="button" class="close" data-dismiss="modal" aria-label="Close"><span aria-hidden="true">&times;</span></button>
<h4 class="modal-title">Correction of "1. Like, comment, subscribe"</h4>
</div>
<div class="modal-body">
<div class="actions">
<center>
<div class="alert alert-info hidden"></div>

<button name="button" type="submit" class="btn btn-primary correction_request_test_send" data-task-id="3905">Start a new test</button>
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
<button data-task-id="3905">
<i aria-hidden="true" class="fa fa-info-circle "></i>
</button>
<div class="help-container" data-task-id="3905">
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



<button class="btn btn-default btn-sm" data-toggle="modal" data-target="#container-specs-modal" data-gtm-custom-event-name="task_sandbox_modal" data-gtm-custom-event-options="{&quot;taskId&quot;:3905}"><i aria-hidden="true" class="fa fa-terminal "></i><span>Get a sandbox</span></button>

</div>


<div class="fs-4">
</div>
</div>


</div>
</div>

</div>
<div data-role="task3935" data-position="3" id="task-num-2">
<div class="panel panel-default task-card " id="task-3935">
<span id="user_id" data-id="197885"></span>

<div class="panel-heading panel-heading-actions">
<h3 class="panel-title">
2. 0 &gt; 972?
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
<p>This program prints the largest of three integers.</p>

<pre><code>carrie@ubuntu:/debugging$ cat 2-main.c
#include &lt;stdio.h&gt;
#include &quot;main.h&quot;

/**
* main - prints the largest of 3 integers
* Return: 0
*/

int main(void)
{
int a, b, c;
int largest;

a = 972;
b = -98;
c = 0;

largest = largest_number(a, b, c);

printf(&quot;%d is the largest number\n&quot;, largest);

return (0);
}
carrie@ubuntu:/debugging$
</code></pre>

<pre><code>carrie@ubuntu:/debugging$ cat 2-largest_number.c
#include &quot;main.h&quot;

/**
* largest_number - returns the largest of 3 numbers
* @a: first integer
* @b: second integer
* @c: third integer
* Return: largest number
*/

int largest_number(int a, int b, int c)
{
int largest;

if (a &gt; b &amp;&amp; b &gt; c)
{
largest = a;
}
else if (b &gt; a &amp;&amp; a &gt; c)
{
largest = b;
}
else
{
largest = c;
}

return (largest);
}

carrie@ubuntu:/debugging$
</code></pre>

<pre><code>carrie@ubuntu:/debugging$ gcc -Wall -Werror -Wextra -pedantic -std=gnu89 2-largest_number.c 2-main.c -o 2-main
carrie@ubuntu:/debugging$ ./2-main
0 is the largest number
carrie@ubuntu:/debugging$
</code></pre>

<p>? That&rsquo;s definitely not right.</p>

<p>Fix the code in <code>2-largest_number.c</code> so that it correctly prints out the largest of three numbers, no matter the case.</p>

<ul>
<li>Line count will not be checked for this task.</li>
</ul>

</div>

<div class="list-group">
<!-- Task URLs -->

<!-- Github information -->
<div class="list-group-item">
<p><strong>Repo:</strong></p>
<ul>
<li>GitHub repository: <code>alx-low_level_programming</code></li>
<li>Directory: <code>0x03-debugging</code></li>
<li>File: <code>2-largest_number.c, main.h</code></li>
</ul>
</div>

<!-- Self-paced manual review -->
</div>

<!-- Panel footer - Controls -->
<div class="panel-footer">
<div class="align-items-center d-flex justify-content-between">

<div>
<button class="student_task_done btn btn-default btn-sm no" data-task-id="3935">
<span class="no"><i aria-hidden="true" class="fa fa-square-o "></i></span>
<span class="yes"><i aria-hidden="true" class="fa fa-check-square-o "></i></span>
<span class="pending"><i aria-hidden="true" class="fa fa-spinner  fa-pulse"></i></span>
Done<span class="no pending">?</span><span class="yes">!</span>
</button>

<button class="student-task-done-by btn btn-default btn-sm" data-task-id="3935" data-batch-id="26" data-toggle="modal" data-target="#task-3935-users-done-modal">
Help
</button>
<div class="modal fade users-done-modal" id="task-3935-users-done-modal" data-task-id="3935" data-batch-id="26">
<div class="modal-dialog">
<div class="modal-content">
<div class="modal-header">
<button type="button" class="close" data-dismiss="modal" aria-label="Close"><span aria-hidden="true">&times;</span></button>
<h4 class="modal-title">Students who are done with "2. 0 &gt; 972?"</h4>
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


<button class="btn btn-default btn-sm check-your-task-3935-modal-button" data-task-id="3935" data-toggle="modal" data-target="#task-test-correction-3935-correction-modal" id="task-num-2-check-code-btn" data-gtm-custom-event-name="task_checker_modal" data-gtm-custom-event-options='{&quot;taskId&quot;:3935}'>
Check your code
</button>
<div class="modal fade task_correction_modal student_modal" id="task-test-correction-3935-correction-modal">
<div class="modal-dialog">
<div class="modal-content">
<div class="modal-header">
<button type="button" class="close" data-dismiss="modal" aria-label="Close"><span aria-hidden="true">&times;</span></button>
<h4 class="modal-title">Correction of "2. 0 &gt; 972?"</h4>
</div>
<div class="modal-body">
<div class="actions">
<center>
<div class="alert alert-info hidden"></div>

<button name="button" type="submit" class="btn btn-primary correction_request_test_send" data-task-id="3935">Start a new test</button>
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
<button data-task-id="3935">
<i aria-hidden="true" class="fa fa-info-circle "></i>
</button>
<div class="help-container" data-task-id="3935">
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



<button class="btn btn-default btn-sm" data-toggle="modal" data-target="#container-specs-modal" data-gtm-custom-event-name="task_sandbox_modal" data-gtm-custom-event-options="{&quot;taskId&quot;:3935}"><i aria-hidden="true" class="fa fa-terminal "></i><span>Get a sandbox</span></button>

</div>


<div class="fs-4">
</div>
</div>


</div>
</div>

</div>
<div data-role="task3906" data-position="4" id="task-num-3">
<div class="panel panel-default task-card " id="task-3906">
<span id="user_id" data-id="197885"></span>

<div class="panel-heading panel-heading-actions">
<h3 class="panel-title">
3. Leap year
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
<p>This program converts a date to the day of year and determines how many days are left in the year, taking leap year into consideration.</p>

<pre><code>carrie@ubuntu:/debugging$ cat 3-main_a.c
#include &lt;stdio.h&gt;
#include &quot;main.h&quot;

/**
* main - takes a date and prints how many days are left in the year, taking
* leap years into account
* Return: 0
*/

int main(void)
{
int month;
int day;
int year;

month = 4;
day = 01;
year = 1997;

printf(&quot;Date: %02d/%02d/%04d\n&quot;, month, day, year);

day = convert_day(month, day);

print_remaining_days(month, day, year);

return (0);
}

carrie@ubuntu:/debugging$
</code></pre>

<pre><code>carrie@ubuntu:/debugging$ cat 3-convert_day.c
#include &quot;main.h&quot;

/**
* convert_day - converts day of month to day of year, without accounting
* for leap year
* @month: month in number format
* @day: day of month
* Return: day of year
*/

int convert_day(int month, int day)
{
switch (month)
{
case 2:
day = 31 + day;
break;
case 3:
day = 59 + day;
break;
case 4:
day = 90 + day;
break;
case 5:
day = 120 + day;
break;
case 6:
day = 151 + day;
break;
case 7:
day = 181 + day;
break;
case 8:
day = 212 + day;
break;
case 9:
day = 243 + day;
break;
case 10:
day = 273 + day;
break;
case 11:
day = 304 + day;
break;
case 12:
day = 334 + day;
break;
default:
break;
}
return (day);
}

carrie@ubuntu:/debugging$
</code></pre>

<pre><code>carrie@ubuntu:/debugging$ cat 3-print_remaining_days.c
#include &lt;stdio.h&gt;
#include &quot;main.h&quot;

/**
* print_remaining_days - takes a date and prints how many days are
* left in the year, taking leap years into account
* @month: month in number format
* @day: day of month
* @year: year
* Return: void
*/

void print_remaining_days(int month, int day, int year)
{
if ((year % 4 == 0 || year % 400 == 0) &amp;&amp; !(year % 100 == 0))
{
if (month &gt;= 2 &amp;&amp; day &gt;= 60)
{
day++;
}

printf(&quot;Day of the year: %d\n&quot;, day);
printf(&quot;Remaining days: %d\n&quot;, 366 - day);
}
else
{
if (month == 2 &amp;&amp; day == 60)
{
printf(&quot;Invalid date: %02d/%02d/%04d\n&quot;, month, day - 31, year);
}
else
{
printf(&quot;Day of the year: %d\n&quot;, day);
printf(&quot;Remaining days: %d\n&quot;, 365 - day);
}
}
}

carrie@ubuntu:/debugging$ 
</code></pre>

<pre><code>carrie@ubuntu:/debugging$ gcc -Wall -Werror -Wextra -pedantic -std=gnu89 3-convert_day.c 3-print_remaining_days.c 3-main_a.c -o 3-main_a 
carrie@ubuntu:/debugging$ ./3-main_a
Date: 04/01/1997
Day of the year: 91
Remaining days: 274
carrie@ubuntu:/debugging$
</code></pre>

<p>Output looks good for <code>04/01/1997</code>! Let&rsquo;s make a new main file <code>3-main_b.c</code> to try a case that is a leap year: <code>02/29/2000</code>.</p>

<pre><code>carrie@ubuntu:/debugging$ gcc -Wall -Werror -Wextra -pedantic -std=gnu89 3-convert_day.c 3-print_remaining_days.c 3-main_b.c -o 3-main_b 
carrie@ubuntu:/debugging$ ./3-main_b
Date: 02/29/2000
Invalid date: 02/29/2000
carrie@ubuntu:/debugging$
</code></pre>

<p>? That doesn&rsquo;t seem right.</p>

<p>Fix the <code>print_remaining_days()</code> function so that the output works correctly for <em>all</em> dates and <em>all</em> leap years.</p>

<ul>
<li>Line count will not be checked for this task.</li>
<li>You can assume that all test cases have valid months (i.e. the value of <code>month</code> will never be less than <code>1</code> or greater than <code>12</code>) and valid days (i.e. the value of <code>day</code> will never be less than <code>1</code> or greater than <code>31</code>). </li>
<li>You can assume that all test cases have valid month/day combinations (i.e. there will never be a June 31st or November 31st, etc.), but not all month/day/year combinations are valid (i.e. February 29, 1991 or February 29, 2427).</li>
</ul>

</div>

<div class="list-group">
<!-- Task URLs -->

<!-- Github information -->
<div class="list-group-item">
<p><strong>Repo:</strong></p>
<ul>
<li>GitHub repository: <code>alx-low_level_programming</code></li>
<li>Directory: <code>0x03-debugging</code></li>
<li>File: <code>3-print_remaining_days.c, main.h</code></li>
</ul>
</div>

<!-- Self-paced manual review -->
</div>

<!-- Panel footer - Controls -->
<div class="panel-footer">
<div class="align-items-center d-flex justify-content-between">

<div>
<button class="student_task_done btn btn-default btn-sm no" data-task-id="3906">
<span class="no"><i aria-hidden="true" class="fa fa-square-o "></i></span>
<span class="yes"><i aria-hidden="true" class="fa fa-check-square-o "></i></span>
<span class="pending"><i aria-hidden="true" class="fa fa-spinner  fa-pulse"></i></span>
Done<span class="no pending">?</span><span class="yes">!</span>
</button>

<button class="student-task-done-by btn btn-default btn-sm" data-task-id="3906" data-batch-id="26" data-toggle="modal" data-target="#task-3906-users-done-modal">
Help
</button>
<div class="modal fade users-done-modal" id="task-3906-users-done-modal" data-task-id="3906" data-batch-id="26">
<div class="modal-dialog">
<div class="modal-content">
<div class="modal-header">
<button type="button" class="close" data-dismiss="modal" aria-label="Close"><span aria-hidden="true">&times;</span></button>
<h4 class="modal-title">Students who are done with "3. Leap year"</h4>
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


<button class="btn btn-default btn-sm check-your-task-3906-modal-button" data-task-id="3906" data-toggle="modal" data-target="#task-test-correction-3906-correction-modal" id="task-num-3-check-code-btn" data-gtm-custom-event-name="task_checker_modal" data-gtm-custom-event-options='{&quot;taskId&quot;:3906}'>
Check your code
</button>
<div class="modal fade task_correction_modal student_modal" id="task-test-correction-3906-correction-modal">
<div class="modal-dialog">
<div class="modal-content">
<div class="modal-header">
<button type="button" class="close" data-dismiss="modal" aria-label="Close"><span aria-hidden="true">&times;</span></button>
<h4 class="modal-title">Correction of "3. Leap year"</h4>
</div>
<div class="modal-body">
<div class="actions">
<center>
<div class="alert alert-info hidden"></div>

<button name="button" type="submit" class="btn btn-primary correction_request_test_send" data-task-id="3906">Start a new test</button>
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
<button data-task-id="3906">
<i aria-hidden="true" class="fa fa-info-circle "></i>
</button>
<div class="help-container" data-task-id="3906">
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





<div class="modal fade" id="container-specs-modal"><div class="modal-dialog modal-lg"><div class="modal-content"><div class="modal-header"><button type="button" class="close" data-dismiss="modal" aria-label="Close"><span aria-hidden="true">&times;</span></button><h4 class="modal-title">Recommended Sandbox</h4></div><div class="modal-body"><div data-react-class="user_containers/ContainerSpecs" data-react-props="{&quot;containerModelName&quot;:&quot;Sandbox&quot;,&quot;containerSpecs&quot;:[{&quot;description&quot;:&quot;\u003cp\u003eBasic Ubuntu 20.04, with vim, emacs, curl, wget and all needed for Foundations\u003c/p\u003e\n&quot;,&quot;id&quot;:39,&quot;name&quot;:&quot;Ubuntu 20.04&quot;,&quot;online&quot;:true,&quot;container&quot;:{&quot;container_id&quot;:&quot;c4e7755b271894d6b87d359c2ee6cf3e671d80d61d2080878d7d18ac32959bfc&quot;,&quot;id&quot;:239271,&quot;restart_uri&quot;:&quot;/user_containers/239271/restart.json&quot;,&quot;status&quot;:&quot;running&quot;,&quot;uri&quot;:&quot;/user_containers/239271.json&quot;,&quot;wake_uri&quot;:&quot;/user_containers/239271/wake.json&quot;,&quot;webterm_uri&quot;:&quot;/user_containers/239271/webterm&quot;,&quot;host&quot;:&quot;c4e7755b2718.3f09d370.alx-cod.online&quot;,&quot;password&quot;:&quot;2deaf74c415af9350d02&quot;,&quot;ports&quot;:{&quot;4000&quot;:49897,&quot;443&quot;:49900,&quot;8000&quot;:49894,&quot;8080&quot;:49893,&quot;3000&quot;:49899,&quot;3306&quot;:49898,&quot;5001&quot;:49895,&quot;80&quot;:49901,&quot;22&quot;:49902,&quot;5000&quot;:49896}}}],&quot;containersLimit&quot;:2,&quot;csrfToken&quot;:&quot;gd11daGoh1S_oD0LrtpQTPVpIVnY4wiYTn_itpqta7t0jF9w_5S2CHvXYxMX0bUi1Ij5p06-DNPT1PUFZhehDg&quot;,&quot;startStatusURI&quot;:&quot;/user_containers/start_status.json&quot;,&quot;startURI&quot;:&quot;/user_containers/start.json&quot;}" data-react-cache-id="user_containers/ContainerSpecs-0"></div></div></div></div></div>

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