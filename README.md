<a href="https://github.com/JaeSeoKim/badge42"><img src="https://badge42.vercel.app/api/v2/cl4qxms4g001609l49j835g66/project/2694515" alt="joslopez's 42 minitalk Score" /></a>
# minitalk
<p>The purpose of this project is to code a small data exchange program using UNIX signals.<p/n>
<b>PROJECT INSTRUCTIONS</b>
<p>• Name your executable files client and server.</p>
<p>• You have to turn in a Makefile which will compile your source files. It must not
relink.</p>
<p>• You can definitely use your libft.</p>
<p>• You have to handle errors thoroughly. In no way your program should quit unexpectedly (segmentation fault, bus error, double free, and so forth).
<p>• Your program mustn’t have memory leaks.</p>
<p>• You can have one global variable per program (one for the client and one for
the server), but you will have to justify their use.</p>
<p>• In order to complete the mandatory part, you are allowed to use the following
functions:</p>
<p>◦ write</p>
<p>◦ ft_printf and any equivalent YOU coded</p>
<p>◦ signal</p>
<p>◦ sigemptyset</p>
<p>◦ sigaddset</p>
<p>◦ sigaction</p>
<p>◦ kill</p>
<p>◦ getpid</p>
<p>◦ malloc</p>
<p>◦ free</p>
<p>◦ pause</p>
<p>◦ sleep</p>
<p>◦ usleep</p>
<p>◦ exit<p/n>
<b>MANDATORY PART</b>
<p>You must create a communication program in the form of a client and a server.</p>
<p>• The server must be started first. After its launch, it has to print its PID.</p>
<p>• The client takes two parameters:</p>
<p>◦ The server PID.</p>
<p>◦ The string to send.</p>
<p>• The client must send the string passed as a parameter to the server.</p>
<p>Once the string has been received, the server must print it.</p>
<p>• The server has to display the string pretty quickly. Quickly means that if you think
it takes too long, then it is probably too long.</p>
<p>• Your server should be able to receive strings from several clients in a row without
needing to restart.</p>
<p>• The communication between your client and your server has to be done only using
UNIX signals.</p>
<p>• You can only use these two signals: SIGUSR1 and SIGUSR2.</p>
