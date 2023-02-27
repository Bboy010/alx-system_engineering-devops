
<!DOCTYPE html>
<html lang="en">
  <head>
    <meta charset="utf-8">
    <meta http-equiv="X-UA-Compatible" content="IE=edge">
    <meta name="viewport" content="width=device-width, initial-scale=1">
    <!-- The above 3 meta tags *must* come first in the head; any other head content must come *after* these tags -->
    <meta name="description" content="">
    <meta name="google" content="notranslate">

  </head>

  <body class="signed_in env_production notranslate"
        translate="no"
        class="notranslate"
        data-theme-suffix="_alx">   
  <div class="collapse navbar-collapse navigation" id="navbar-mobile">
  </div>
</nav>

      <div class="hidden-xs navigation sidebar">
    <div class="logo"></div>
    <h2>Background Context</h2>

<p><a href="https://youtu.be/BC2neyc5GcI" target="_blank"><img src="https://s3.amazonaws.com/alx-intranet.hbtn.io/uploads/medias/2019/6/b07e3333b1edfb9beed5.png?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Credential=AKIARDDGGGOUSBVO6H7D%2F20230224%2Fus-east-1%2Fs3%2Faws4_request&X-Amz-Date=20230224T230813Z&X-Amz-Expires=86400&X-Amz-SignedHeaders=host&X-Amz-Signature=c786640b08f9898a4abfc3e470789610a575260e5aeb75fcfa657b46a19c4d79" alt="" loading='lazy' style="" /></a></p>

<h2>Resources</h2>

<p><strong>Read or watch</strong>:</p>

<ul>
<li><a href="/rltoken/wT98UJfv_E2tk4yP9PcLLw" title="The <code>for</code> loop&quot; target=&ldquo;_blank&rdquo;>The <code>for</code> loop</a> </li>
<li><a href="/rltoken/FSAs6DuzuuIaN6naWyxzTw" title="The <code>while</code> loop&quot; target=&ldquo;_blank&rdquo;>The <code>while</code> loop</a> </li>
<li><a href="/rltoken/nl_7uNvLtjRrH1C62_IF_g" title="The <code>until</code> loop&quot; target=&ldquo;_blank&rdquo;>The <code>until</code> loop</a> </li>
<li><a href="/rltoken/U93Es1esHYob0oDmydSVAg" title="Loops sample" target="_blank">Loops sample</a> </li>
<li><a href="/rltoken/olvOKX699pq50rkHRE5cSA" title="Variable assignment and arithmetic" target="_blank">Variable assignment and arithmetic</a> </li>
<li><a href="/rltoken/HxohzllkOWh0t4dy_HptIQ" title="Comparison operators" target="_blank">Comparison operators</a> </li>
<li><a href="/rltoken/g8of2ABPEJfCNtPrDQaqVw" title="File test operators" target="_blank">File test operators</a> </li>
<li><a href="/rltoken/O0Ay21p7tDhfLMsYbtAKug" title="Make your scripts portable" target="_blank">Make your scripts portable</a> </li>
</ul>

<p><strong>man or help</strong>:</p>

<ul>
<li><code>env</code></li>
<li><code>cut</code></li>
<li><code>for</code></li>
<li><code>while</code></li>
<li><code>until</code></li>
<li><code>if</code></li>
</ul>

<h2>Learning Objectives</h2>

<p>At the end of this project, you are expected to be able to <a href="/rltoken/UnkzDNdH09TFJ0-Y56azyg" title="explain to anyone" target="_blank">explain to anyone</a>, <strong>without the help of Google</strong>:</p>

<h3>General</h3>

<ul>
<li>How to create SSH keys</li>
<li>What is the advantage of using  <code>#!/usr/bin/env bash</code> over <code>#!/bin/bash</code></li>
<li>How to use <code>while</code>, <code>until</code> and <code>for</code> loops</li>
<li>How to use <code>if</code>, <code>else</code>, <code>elif</code> and <code>case</code> condition statements</li>
<li>How to use the <code>cut</code> command</li>
<li>What are files and other comparison operators, and how to use them</li>
</ul>

<h2>Requirements</h2>

<h3>General</h3>

<ul>
<li>Allowed editors: <code>vi</code>, <code>vim</code>, <code>emacs</code></li>
<li>All your files will be interpreted on Ubuntu 20.04 LTS</li>
<li>All your files should end with a new line</li>
<li>A <code>README.md</code> file, at the root of the folder of the project, is mandatory</li>
<li>All your Bash script files must be executable</li>
<li>You are not allowed to use <code>awk</code></li>
<li>Your Bash script must pass <code>Shellcheck</code> (version <code>0.7.0</code>) without any error</li>
<li>The first line of all your Bash scripts should be exactly <code>#!/usr/bin/env bash</code></li>
<li>The second line of all your Bash scripts should be a comment explaining what is the script doing</li>
</ul>

<h3>Copyright - Plagiarism</h3>

<ul>
<li>You are tasked to come up with solutions for the tasks below yourself to meet with the above learning objectives.</li>
<li>You will not be able to meet the objectives of this or any following project by copying and pasting someone else&rsquo;s work. </li>
<li>You are not allowed to publish any content of this project.</li>
<li>Any form of plagiarism is strictly forbidden and will result in removal from the program.</li>
</ul>

<h2>More Info</h2>

<h3>Shellcheck</h3>

<p><a href="/rltoken/joK6l_yEZ9N7T0GQ1RDjLA" title="Shellcheck" target="_blank">Shellcheck</a> is a tool that will help you write proper Bash scripts. It will make recommendations on your syntax and semantics and provide advice on edge cases that you might not have thought about. <code>Shellcheck</code> is your friend! <strong>All your Bash scripts must pass <code>Shellcheck</code> without any error or you will not get any points on the task</strong>.</p>

<p><code>Shellcheck</code> is available on the school&rsquo;s computers. If you want to use it on your own computer, here is how to <a href="/rltoken/jbz0_-i3TV3WpKgxhyrtpA" title="install it" target="_blank">install it</a>.</p>

<p>Examples:</p>

<p>Not passing <code>Shellcheck</code>:<br />
<br />
<img src="https://s3.amazonaws.com/intranet-projects-files/holbertonschool-sysadmin_devops/251/Vxotqyj.png" alt="" loading='lazy' style="" /></p>

<p>Passing <code>Shellcheck</code>:<br />
<br />
<img src="https://s3.amazonaws.com/intranet-projects-files/holbertonschool-sysadmin_devops/251/ubHWxDU.png" alt="" loading='lazy' style="" /></p>

<p>For every feedback, Shellcheck will provide a code that you can use to get more information about the issue, for example for code <code>SC2034</code>, you can browse <a href="/rltoken/dxp49_rfO4_9Yjtcg59exg" title="https://github.com/koalaman/shellcheck/wiki/SC2034" target="_blank">https://github.com/koalaman/shellcheck/wiki/SC2034</a>.</p>

  </div>
</div>


      

      

        
          <h2 class="gap">Tasks</h2>

    <div data-role="task1223" data-position="1" id="task-num-0">
      <div class="panel panel-default task-card " id="task-1223">
  <span id="user_id" data-id="164918"></span>

  <div class="panel-heading panel-heading-actions">
    <h3 class="panel-title">
      0. Create a SSH RSA key pair
    </h3>

    <div>
        <span class="label label-info">
          mandatory
        </span>
    </div>
  </div>

  <div class="panel-body">
    <span id="user_id" data-id="164918"></span>

    <!-- Progress vs Score -->
      <div class="task_progress_score_bar" data-task-id="1223" data-correction-id="11598315">
        <div class="task_progress_bar" style="width: 0.0%">
          <div class="task_score_bar" style="width: NaN%">
          </div>
        </div>
        <div class="task_progress_score_text">
          Score: <span class="task_score_value">0.0%</span> (<span class="task_progress_value">Checks completed: 0.0%</span>)
        </div>
      </div>

    <!-- Task Body -->
    <p>Read for this task:</p>

<ul>
<li><a href="/rltoken/Cy1plV2eR3VphjPqliXB8A" title="Linux and Mac OS users" target="_blank">Linux and Mac OS users</a></li>
<li><a href="/rltoken/PXriGT0IKaSXC7L5l0CVag" title="Windows users" target="_blank">Windows users</a></li>
</ul>

<p>man: <code>ssh-keygen</code></p>

<p>You will soon have to manage your own <strong>servers</strong> concept page hosted on remote <a href="/rltoken/nDPzEm5SYxcdGxP_OpVYXQ" title="data centers" target="_blank">data centers</a>. We need to set them up with your RSA public key so that you can access them via SSH.</p>

<p>Create a RSA key pair.</p>

<p>Requirements:</p>

<ul>
<li>Share your <strong>public key</strong> in your answer file <code>0-RSA_public_key.pub</code></li>
<li>Fill the <code>SSH public key</code> field of your <a href="/rltoken/qsaEQ3ZWrgs-zoueDpXpPA" title="intranet profile" target="_blank">intranet profile</a> with the public key you just generated</li>
<li><strong>Keep the private key to yourself in a secure location</strong>, you will use it later to connect to your servers using SSH. Some storing ideas are Dropbox, Google Drive, password manager, USB key. Failing to do so will prevent you to access your servers, which will prevent you from doing your projects</li>
<li>If you decide to add a passphrase to your key, make sure to save this passphrase in a secure location, you will not be able to use your keys without the passphrase</li>
</ul>

<p>SSH and RSA keys will be covered in depth in a later project.</p>

  </div>

  <div class="list-group">
    <!-- Task URLs -->

    <!-- Github information -->
      <div class="list-group-item">
        <p><strong>Repo:</strong></p>
        <ul>
          <li>GitHub repository: <code>alx-system_engineering-devops</code></li>
            <li>Directory: <code>0x04-loops_conditions_and_parsing</code></li>
            <li>File: <code>0-RSA_public_key.pub</code></li>
        </ul>
      </div>

    <!-- Self-paced manual review -->
  </div>

  <!-- Panel footer - Controls -->
  <div class="panel-footer">
      <div class="align-items-center d-flex justify-content-between">
        
<div>
    <button class="student_task_done btn btn-default btn-sm no" data-task-id="1223">
      <span class="no"><i aria-hidden="true" class="fa fa-square-o "></i></span>
      <span class="yes"><i aria-hidden="true" class="fa fa-check-square-o "></i></span>
      <span class="pending"><i aria-hidden="true" class="fa fa-spinner  fa-pulse"></i></span>
      Done<span class="no pending">?</span><span class="yes">!</span>
    </button>

  <button class="student-task-done-by btn btn-default btn-sm" data-task-id="1223" data-batch-id="56" data-toggle="modal" data-target="#task-1223-users-done-modal">
    Help
  </button>
  <div class="modal fade users-done-modal" id="task-1223-users-done-modal" data-task-id="1223" data-batch-id="56">
    <div class="modal-dialog">
        <div class="modal-content">
        <div class="modal-header">
            <button type="button" class="close" data-dismiss="modal" aria-label="Close"><span aria-hidden="true">&times;</span></button>
            <h4 class="modal-title">Students who are done with "0. Create a SSH RSA key pair"</h4>
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


      <button class="btn btn-default btn-sm check-your-task-1223-modal-button" data-task-id="1223" data-toggle="modal" data-target="#task-test-correction-1223-correction-modal" id="task-num-0-check-code-btn" data-gtm-custom-event-name="task_checker_modal" data-gtm-custom-event-options='{&quot;taskId&quot;:1223}'>
          Check your code
      </button>
      <div class="modal fade task_correction_modal student_modal" id="task-test-correction-1223-correction-modal">
    <div class="modal-dialog">
        <div class="modal-content">
            <div class="modal-header">
                <button type="button" class="close" data-dismiss="modal" aria-label="Close"><span aria-hidden="true">&times;</span></button>
                <h4 class="modal-title">Correction of "0. Create a SSH RSA key pair"</h4>
            </div>
            <div class="modal-body">
                <div class="actions">
                    <center>
                        <div class="alert alert-info hidden"></div>

                        <button name="button" type="submit" class="btn btn-primary correction_request_test_send" data-task-id="1223">Start a new test</button>
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

  <div class="panel-heading panel-heading-actions">
    <h3 class="panel-title">
      1. For Best School loop
    </h3>

  </div>
    <!-- Task Body -->
    <p>Write a Bash script that displays <code>Best School</code> 10 times.</p>

<p>Requirement:</p>

<ul>
<li>You must use the <code>for</code> loop (<code>while</code> and <code>until</code> are forbidden)</li>
</ul>

<pre><code>sylvain@ubuntu$ head -n 2 1-for_best_school 
#!/usr/bin/env bash
# This script is displaying &quot;Best School&quot; 10 times
sylvain@ubuntu$ ./1-for_best_school 
Best School
Best School
Best School
Best School
Best School
Best School
Best School
Best School
Best School
Best School
sylvain@ubuntu$ 
</code></pre>

<p>Note that: </p>

<ul>
<li>The first line of my Bash script starts with <code>#!/usr/bin/env bash</code></li>
<li>The second line of my Bash scripts is a comment explaining what it is doing</li>
</ul>

  </div>

  <div class="list-group">
    <!-- Task URLs -->

    <!-- Github information -->
      <div class="list-group-item">
        <p><strong>Repo:</strong></p>
        <ul>
          <li>GitHub repository: <code>alx-system_engineering-devops</code></li>
            <li>Directory: <code>0x04-loops_conditions_and_parsing</code></li>
            <li>File: <code>1-for_best_school</code></li>
        </ul>
      </div>

  <div class="panel-heading panel-heading-actions">
    <h3 class="panel-title">
      2. While Best School loop
    </h3>

    <div>
        <span class="label label-info">
          mandatory
        </span>
    </div>
  </div>
    <!-- Task Body -->
    <p>Write a Bash script that displays <code>Best School</code> 10 times.</p>

<p>Requirements:</p>

<ul>
<li>You must use the <code>while</code> loop (<code>for</code> and <code>until</code> are forbidden)</li>
</ul>

<pre><code>sylvain@ubuntu$ ./2-while_best_school
Best School
Best School
Best School
Best School
Best School
Best School
Best School
Best School
Best School
Best School
sylvain@ubuntu$ 
</code></pre>

  </div>

  <div class="list-group">
    <!-- Task URLs -->

    <!-- Github information -->
      <div class="list-group-item">
        <p><strong>Repo:</strong></p>
        <ul>
          <li>GitHub repository: <code>alx-system_engineering-devops</code></li>
            <li>Directory: <code>0x04-loops_conditions_and_parsing</code></li>
            <li>File: <code>2-while_best_school</code></li>
        </ul>
      </div>

  <div class="panel-heading panel-heading-actions">
    <h3 class="panel-title">
      3. Until Best School loop
    </h3>

    <!-- Task Body -->
    <p>Write a Bash script that displays <code>Best School</code> 10 times.</p>

<p>Requirements:</p>

<ul>
<li>You must use the <code>until</code> loop (<code>for</code> and <code>while</code> are forbidden)</li>
</ul>

<pre><code>sylvain@ubuntu$ ./3-until_best_school
Best School
Best School
Best School
Best School
Best School
Best School
Best School
Best School
Best School
Best School
sylvain@ubuntu$ 
</code></pre>

  </div>

  <div class="list-group">
    <!-- Task URLs -->

    <!-- Github information -->
      <div class="list-group-item">
        <p><strong>Repo:</strong></p>
        <ul>
          <li>GitHub repository: <code>alx-system_engineering-devops</code></li>
            <li>Directory: <code>0x04-loops_conditions_and_parsing</code></li>
            <li>File: <code>3-until_best_school</code></li>
        </ul>
      </div>

  <div class="panel-heading panel-heading-actions">
    <h3 class="panel-title">
      4. If 9, say Hi!
    </h3>

    <!-- Task Body -->
    <p>Write a Bash script that displays <code>Best School</code> 10 times, but for the 9th iteration, displays <code>Best School</code> <em>and then</em> <code>Hi</code> on a new line.</p>

<p>Requirements:</p>

<ul>
<li>You must use the <code>while</code> loop (<code>for</code> and <code>until</code> are forbidden)</li>
<li>You must use the <code>if</code> statement</li>
</ul>

<pre><code>sylvain@ubuntu$ ./4-if_9_say_hi
Best School
Best School
Best School
Best School
Best School
Best School
Best School
Best School
Best School
Hi
Best School
sylvain@ubuntu$ 
</code></pre>

  </div>

  <div class="list-group">
    <!-- Task URLs -->

    <!-- Github information -->
      <div class="list-group-item">
        <p><strong>Repo:</strong></p>
        <ul>
          <li>GitHub repository: <code>alx-system_engineering-devops</code></li>
            <li>Directory: <code>0x04-loops_conditions_and_parsing</code></li>
            <li>File: <code>4-if_9_say_hi</code></li>
        </ul>
      </div>

   

  <div class="panel-heading panel-heading-actions">
    <h3 class="panel-title">
      5. 4 bad luck, 8 is your chance
    </h3>

    <div>
        <span class="label label-info">
          mandatory
        </span>
    </div>
  </div>

  <div class="panel-body">
    <span id="user_id" data-id="164918"></span>

    <!-- Progress vs Score -->
      <div class="task_progress_score_bar" data-task-id="1228" data-correction-id="11598315">
        <div class="task_progress_bar" style="width: 0.0%">
          <div class="task_score_bar" style="width: NaN%">
          </div>
        </div>
        <div class="task_progress_score_text">
          Score: <span class="task_score_value">0.0%</span> (<span class="task_progress_value">Checks completed: 0.0%</span>)
        </div>
      </div>

    <!-- Task Body -->
    <p>Write a Bash script that loops from 1 to 10 and:</p>

<ul>
<li>displays <code>bad luck</code> for the 4th loop iteration</li>
<li>displays <code>good luck</code> for the 8th loop iteration</li>
<li>displays <code>Best School</code> for the other iterations</li>
</ul>

<p>Requirements:</p>

<ul>
<li>You must use the <code>while</code> loop (<code>for</code> and <code>until</code> are forbidden)</li>
<li>You must use the <code>if</code>, <code>elif</code> and <code>else</code> statements</li>
</ul>

<pre><code>sylvain@ubuntu$ ./5-4_bad_luck_8_is_your_chance
Best School
Best School
Best School
bad luck
Best School
Best School
Best School
good luck
Best School
Best School
sylvain@ubuntu$ 
</code></pre>

<p>For the most curious:</p>

<ul>
<li><a href="/rltoken/uhCfz6ariijQvbvmCyYRMg" title="8 in the Chinese culture" target="_blank">8 in the Chinese culture</a></li>
<li><a href="/rltoken/WwpjD57ABmwWSfdUVcBhNg" title="4 in the Chinese culture" target="_blank">4 in the Chinese culture</a></li>
</ul>

  </div>

  <div class="list-group">
    <!-- Task URLs -->

    <!-- Github information -->
      <div class="list-group-item">
        <p><strong>Repo:</strong></p>
        <ul>
          <li>GitHub repository: <code>alx-system_engineering-devops</code></li>
            <li>Directory: <code>0x04-loops_conditions_and_parsing</code></li>
            <li>File: <code>5-4_bad_luck_8_is_your_chance</code></li>
        </ul>
      </div>

    <!-- Self-paced manual review -->
  </div>

  <!-- Panel footer - Controls -->
  <div class="panel-footer">
      <div class="align-items-center d-flex justify-content-between">
        
<div>
    <button class="student_task_done btn btn-default btn-sm no" data-task-id="1228">
      <span class="no"><i aria-hidden="true" class="fa fa-square-o "></i></span>
      <span class="yes"><i aria-hidden="true" class="fa fa-check-square-o "></i></span>
      <span class="pending"><i aria-hidden="true" class="fa fa-spinner  fa-pulse"></i></span>
      Done<span class="no pending">?</span><span class="yes">!</span>
    </button>

  <button class="student-task-done-by btn btn-default btn-sm" data-task-id="1228" data-batch-id="56" data-toggle="modal" data-target="#task-1228-users-done-modal">
    Help
  </button>
  <div class="modal fade users-done-modal" id="task-1228-users-done-modal" data-task-id="1228" data-batch-id="56">
    <div class="modal-dialog">
        <div class="modal-content">
        <div class="modal-header">
            <button type="button" class="close" data-dismiss="modal" aria-label="Close"><span aria-hidden="true">&times;</span></button>
            <h4 class="modal-title">Students who are done with "5. 4 bad luck, 8 is your chance"</h4>
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


  <div class="panel-heading panel-heading-actions">
    <h3 class="panel-title">
      6. Superstitious numbers
    </h3>

    <div>
        <span class="label label-info">
          mandatory
        </span>
    </div>
  </div>

  <div class="panel-body">
    <span id="user_id" data-id="164918"></span>

    <!-- Progress vs Score -->
      <div class="task_progress_score_bar" data-task-id="1229" data-correction-id="11598315">
        <div class="task_progress_bar" style="width: 0.0%">
          <div class="task_score_bar" style="width: NaN%">
          </div>
        </div>
        <div class="task_progress_score_text">
          Score: <span class="task_score_value">0.0%</span> (<span class="task_progress_value">Checks completed: 0.0%</span>)
        </div>
      </div>

    <!-- Task Body -->
    <p>Write a Bash script that displays numbers from 1 to 20 and:</p>

<ul>
<li>displays <code>4</code> <em>and then</em> <code>bad luck from China</code> for the 4th loop iteration</li>
<li>displays <code>9</code> <em>and then</em> <code>bad luck from Japan</code> for the 9th loop iteration</li>
<li>displays <code>17</code> <em>and then</em> <code>bad luck from Italy</code> for the 17th loop iteration</li>
</ul>

<p>Requirements:</p>

<ul>
<li>You must use the <code>while</code> loop (<code>for</code> and <code>until</code> are forbidden)</li>
<li>You must use the <code>case</code> statement</li>
</ul>

<pre><code>sylvain@ubuntu$ ./6-superstitious_numbers
1
2
3
4
bad luck from China
5
6
7
8
9
bad luck from Japan
10
11
12
13
14
15
16
17
bad luck from Italy
18
19
20
sylvain@ubuntu$ 
</code></pre>

  </div>

  <div class="list-group">
    <!-- Task URLs -->

    <!-- Github information -->
      <div class="list-group-item">
        <p><strong>Repo:</strong></p>
        <ul>
          <li>GitHub repository: <code>alx-system_engineering-devops</code></li>
            <li>Directory: <code>0x04-loops_conditions_and_parsing</code></li>
            <li>File: <code>6-superstitious_numbers</code></li>
        </ul>
      </div>

    <!-- Self-paced manual review -->
  </div>

  <div class="panel-heading panel-heading-actions">
    <h3 class="panel-title">
      7. Clock
    </h3>

    <div>
        <span class="label label-info">
          mandatory
        </span>
    </div>
  </div>

  <div class="panel-body">
    <span id="user_id" data-id="164918"></span>

    <!-- Progress vs Score -->
      <div class="task_progress_score_bar" data-task-id="1230" data-correction-id="11598315">
        <div class="task_progress_bar" style="width: 0.0%">
          <div class="task_score_bar" style="width: NaN%">
          </div>
        </div>
        <div class="task_progress_score_text">
          Score: <span class="task_score_value">0.0%</span> (<span class="task_progress_value">Checks completed: 0.0%</span>)
        </div>
      </div>

    <!-- Task Body -->
    <p>Write a Bash script that displays the time for 12 hours and 59 minutes:</p>

<ul>
<li>display hours from 0 to 12</li>
<li>display minutes from 1 to 59</li>
</ul>

<p>Requirements:</p>

<ul>
<li>You must use the <code>while</code> loop (<code>for</code> and <code>until</code> are forbidden)</li>
</ul>

<p>Note that in this example, we only display the first 70 lines using the <code>head</code> command.</p>

<pre><code>sylvain@ubuntu$ ./7-clock | head -n 70
Hour: 0
1
2
3
4
5
6
7
8
9
10
11
12
13
14
15
16
17
18
19
20
21
22
23
24
25
26
27
28
29
30
31
32
33
34
35
36
37
38
39
40
41
42
43
44
45
46
47
48
49
50
51
52
53
54
55
56
57
58
59
Hour: 1
1
2
3
4
5
6
7
8
9
sylvain@ubuntu$ 
</code></pre>

  </div>

  <div class="list-group">
    <!-- Task URLs -->

    <!-- Github information -->
      <div class="list-group-item">
        <p><strong>Repo:</strong></p>
        <ul>
          <li>GitHub repository: <code>alx-system_engineering-devops</code></li>
            <li>Directory: <code>0x04-loops_conditions_and_parsing</code></li>
            <li>File: <code>7-clock</code></li>
        </ul>
      </div>

    <!-- Self-paced manual review -->
  </div>

  <div class="panel-heading panel-heading-actions">
    <h3 class="panel-title">
      8. For ls
    </h3>

    <div>
        <span class="label label-info">
          mandatory
        </span>
    </div>
  </div>

  <div class="panel-body">
    <span id="user_id" data-id="164918"></span>

    <!-- Progress vs Score -->
      <div class="task_progress_score_bar" data-task-id="1231" data-correction-id="11598315">
        <div class="task_progress_bar" style="width: 0.0%">
          <div class="task_score_bar" style="width: NaN%">
          </div>
        </div>
        <div class="task_progress_score_text">
          Score: <span class="task_score_value">0.0%</span> (<span class="task_progress_value">Checks completed: 0.0%</span>)
        </div>
      </div>

    <!-- Task Body -->
    <p>Write a Bash script that displays:</p>

<ul>
<li>The content of the current directory</li>
<li>In a list format</li>
<li>Where only the part of the name after the first dash is displayed (refer to the example)</li>
</ul>

<p>Requirements:</p>

<ul>
<li>You must use the <code>for</code> loop (<code>while</code> and <code>until</code> are forbidden)</li>
<li>Do not display hidden files</li>
</ul>

<pre><code>sylvain@ubuntu$ ls
100-read_and_cut              1-for_best_school         6-superstitious_numbers
101-tell_the_story_of_passwd  2-while_best_school       7-clock
102-lets_parse_apache_logs    3-until_best_school       8-for_ls
103-dig_the-data              4-if_9_say_hi                  9-to_file_or_not_to_file
10-fizzbuzz                   5-4_bad_luck_8_is_your_chance
sylvain@ubuntu$  ./8-for_ls
read_and_cut
tell_the_story_of_passwd
lets_parse_apache_logs
dig_the-data
fizzbuzz
for_best_school
while_best_school
until_best_school
if_9_say_hi
4_bad_luck_8_is_your_chance
superstitious_numbers
clock
for_ls
to_file_or_not_to_file
sylvain@ubuntu$ 
</code></pre>

  </div>

  <div class="list-group">
    <!-- Task URLs -->

    <!-- Github information -->
      <div class="list-group-item">
        <p><strong>Repo:</strong></p>
        <ul>
          <li>GitHub repository: <code>alx-system_engineering-devops</code></li>
            <li>Directory: <code>0x04-loops_conditions_and_parsing</code></li>
            <li>File: <code>8-for_ls</code></li>
        </ul>
      </div>

    <!-- Self-paced manual review -->
  </div>

  <div class="panel-heading panel-heading-actions">
    <h3 class="panel-title">
      9. To file, or not to file
    </h3>

    <div>
        <span class="label label-info">
          mandatory
        </span>
    </div>
  </div>

  <div class="panel-body">
    <span id="user_id" data-id="164918"></span>

    <!-- Progress vs Score -->
      <div class="task_progress_score_bar" data-task-id="1266" data-correction-id="11598315">
        <div class="task_progress_bar" style="width: 0.0%">
          <div class="task_score_bar" style="width: NaN%">
          </div>
        </div>
        <div class="task_progress_score_text">
          Score: <span class="task_score_value">0.0%</span> (<span class="task_progress_value">Checks completed: 0.0%</span>)
        </div>
      </div>

    <!-- Task Body -->
    <p>Write a Bash script that gives you information about the <code>school</code> file.</p>

<p>Requirements:</p>

<ul>
<li>You must use <code>if</code> and, <code>else</code> (<code>case</code> is forbidden)</li>
<li>Your Bash script should check if the file exists and print:

<ul>
<li>if the file exists: <code>school file exists</code></li>
<li>if the file does not exist: <code>school file does not exist</code></li>
</ul></li>
<li>If the file exists, print:

<ul>
<li>if the file is empty: <code>school file is empty</code></li>
<li>if the file is not empty: <code>school file is not empty</code></li>
<li>if the file is a regular file: <code>school is a regular file</code></li>
<li>if the file is not a regular file: (nothing)</li>
</ul></li>
</ul>

<pre><code>sylvain@ubuntu$ file school
school: cannot open `school&#39; (No such file or directory)
sylvain@ubuntu$ ./9-to_file_or_not_to_file 
school file does not exist
sylvain@ubuntu$ touch school
sylvain@ubuntu$ ./9-to_file_or_not_to_file 
school file exists
school file is empty
school is a regular file
sylvain@ubuntu$ echo &#39;betty&#39; &gt; school 
sylvain@ubuntu$ ./9-to_file_or_not_to_file 
school file exists
school file is not empty
school is a regular file
sylvain@ubuntu$ rm school 
sylvain@ubuntu$ mkdir school
sylvain@ubuntu$ ./9-to_file_or_not_to_file 
school file exists
school file is not empty
sylvain@ubuntu$ 
</code></pre>

  </div>

  <div class="list-group">
    <!-- Task URLs -->

    <!-- Github information -->
      <div class="list-group-item">
        <p><strong>Repo:</strong></p>
        <ul>
          <li>GitHub repository: <code>alx-system_engineering-devops</code></li>
            <li>Directory: <code>0x04-loops_conditions_and_parsing</code></li>
            <li>File: <code>9-to_file_or_not_to_file</code></li>
        </ul>
      </div>

    <!-- Self-paced manual review -->
  </div>

  <div class="panel-heading panel-heading-actions">
    <h3 class="panel-title">
      10. FizzBuzz
    </h3>

    <div>
        <span class="label label-info">
          mandatory
        </span>
    </div>
  </div>

  <div class="panel-body">
    <span id="user_id" data-id="164918"></span>

    <!-- Progress vs Score -->
      <div class="task_progress_score_bar" data-task-id="1279" data-correction-id="11598315">
        <div class="task_progress_bar" style="width: 0.0%">
          <div class="task_score_bar" style="width: NaN%">
          </div>
        </div>
        <div class="task_progress_score_text">
          Score: <span class="task_score_value">0.0%</span> (<span class="task_progress_value">Checks completed: 0.0%</span>)
        </div>
      </div>

    <!-- Task Body -->
    <p>Write a Bash script that displays numbers from 1 to 100.</p>

<p>Requirements:</p>

<ul>
<li>Displays <code>FizzBuzz</code> when the number is a multiple of 3 and 5</li>
<li>Displays <code>Fizz</code> when the number is multiple of 3</li>
<li>Displays <code>Buzz</code> when the number is a multiple of 5</li>
<li>Otherwise, displays the number</li>
<li>In a list format</li>
</ul>

<pre><code>sylvain@ubuntu$ ./10-fizzbuzz | head -20
1
2
Fizz
4
Buzz
Fizz
7
8
Fizz
Buzz
11
Fizz
13
14
FizzBuzz
16
17
Fizz
19
Buzz
sylvain@ubuntu$ 
</code></pre>

<footer>
   </div>

  <div class="list-group">
    <!-- Task URLs -->

    <!-- Github information -->
      <div class="list-group-item">
        <p><strong>Repo:</strong></p>
        <ul>
          <li>GitHub repository: <code>alx-system_engineering-devops</code></li>
            <li>Directory: <code>0x04-loops_conditions_and_parsing</code></li>
            <li>File: <code>10-fizzbuzz</code></li>
        </ul>
      </div>


      </article>

      <div class="copyright">Copyright © 2023 ALX, All rights reserved.</div>
</footer>
     </main>
  </body>
</html>
