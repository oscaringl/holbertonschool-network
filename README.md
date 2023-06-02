<h1>Networking basics #0</h1>
<h2>Resources</h2>
<p><strong>Read or watch</strong>:</p>
<ul>
<li><a title="OSI model" href="https://intranet.hbtn.io/rltoken/0gZBJLBZ0DVlkVIsZek1Cg" target="_blank" rel="noopener">OSI model</a></li>
<li><a title="Different types of network" href="https://intranet.hbtn.io/rltoken/uhwKSwkglP91KoNRsqj33g" target="_blank" rel="noopener">Different types of network</a></li>
<li><a title="LAN network" href="https://intranet.hbtn.io/rltoken/AY_BwkDbIntiUUEzzAOYpw" target="_blank" rel="noopener">LAN network</a></li>
<li><a title="WAN network" href="https://intranet.hbtn.io/rltoken/UlbohQRQTWFbcOKGN36D3g" target="_blank" rel="noopener">WAN network</a></li>
<li><a title="Internet" href="https://intranet.hbtn.io/rltoken/vV8mtIuKF8oMktJeS7o06w" target="_blank" rel="noopener">Internet</a></li>
<li><a title="MAC address" href="https://intranet.hbtn.io/rltoken/uCjZlyba4pa0vjcFOc_HWg" target="_blank" rel="noopener">MAC address</a></li>
<li><a title="What is an IP address" href="https://intranet.hbtn.io/rltoken/SBU_OXL5nGyhkiPWDqBL8Q" target="_blank" rel="noopener">What is an IP address</a></li>
<li><a title="Private and public address" href="https://intranet.hbtn.io/rltoken/Si0prYb_5y_cCLCqf395TQ" target="_blank" rel="noopener">Private and public address</a></li>
<li><a title="IPv4 and IPv6" href="https://intranet.hbtn.io/rltoken/-CJ08KJ1fgGd5TaBVtxvjw" target="_blank" rel="noopener">IPv4 and IPv6</a></li>
<li><a title="Localhost" href="https://intranet.hbtn.io/rltoken/IA3wOeXxbQFuwhWutfH3Cw" target="_blank" rel="noopener">Localhost</a></li>
<li><a title="TCP and UDP" href="https://intranet.hbtn.io/rltoken/M4UIOFvUfdzrggyY9rwliw" target="_blank" rel="noopener">TCP and UDP</a></li>
<li><a title="TCP/UDP ports List" href="https://intranet.hbtn.io/rltoken/cS-GlmuJlLCth1uWA6VeKA" target="_blank" rel="noopener">TCP/UDP ports List</a></li>
<li><a title="What is ping /ICMP" href="https://intranet.hbtn.io/rltoken/tjQjQ3agyLJeWc4XLYYXVA" target="_blank" rel="noopener">What is ping /ICMP</a></li>
<li><a title="Positional parameters" href="https://intranet.hbtn.io/rltoken/PH7-8E2E1Jv3SYKDXCCGYA" target="_blank" rel="noopener">Positional parameters</a></li>
</ul>
<p><strong>man or help</strong>:</p>
<ul>
<li><code>netstat</code></li>
<li><code>ping</code></li>
</ul>
<h2>Learning Objectives</h2>
<p>At the end of this project, you are expected to be able to <a title="explain to anyone" href="https://intranet.hbtn.io/rltoken/3QHjilRqD4KcEdijsg9aaw" target="_blank" rel="noopener">explain to anyone</a>, <strong>without the help of Google</strong>:</p>
<h3>OSI Model</h3>
<ul>
<li>What it is</li>
<li>How many layers it has</li>
<li>How it is organized</li>
</ul>
<h3>What is a LAN</h3>
<ul>
<li>Typical usage</li>
<li>Typical geographical size</li>
</ul>
<h3>What is a WAN</h3>
<ul>
<li>Typical usage</li>
<li>Typical geographical size</li>
</ul>
<h3>What is the Internet</h3>
<ul>
<li>What is an IP address</li>
<li>What are the 2 types of IP address</li>
<li>What is <code>localhost</code></li>
<li>What is a subnet</li>
<li>Why IPv6 was created</li>
</ul>
<h3>TCP/UDP</h3>
<ul>
<li>What are the 2 mainly used data transfer protocols for IP (transfer level on the OSI schema)</li>
<li>What is the main difference between TCP and UDP</li>
<li>What is a port</li>
<li>Memorize SSH, HTTP and HTTPS port numbers</li>
<li>What tool/protocol is often used to check if a device is connected to a network</li>
</ul>
<h2>Requirements</h2>
<h3>General</h3>
<ul>
<li>Allowed editors: <code>vi</code>, <code>vim</code>, <code>emacs</code></li>
<li>All your Bash script files will be interpreted on Ubuntu 20.04 LTS</li>
<li>All your files should end with a new line</li>
<li>A <code>README.md</code> file, at the root of the folder of the project, is mandatory</li>
<li>All your Bash script files must be executable</li>
<li>Your Bash script must pass <code>shellcheck</code> without any error</li>
<li>The first line of all your Bash scripts should be exactly <code>#!/usr/bin/env bash</code></li>
<li>The second line of all your Bash scripts should be a comment explaining what is the script doing</li>
</ul>
<h2>More Info</h2>
<p>The second line of all your Bash scripts should be a comment explaining what is the script doing</p>
<p>For multiple choice question type tasks, just type the number of the correct answer in your answer file, add a new line for every new answer, example:</p>
<p>What is the most important position in a software company?</p>
<ol>
<li>Project manager</li>
<li>Backend developer</li>
<li>System administrator</li>
</ol>
<pre><code>sylvain@ubuntu$ cat foo_answer_file
3
sylvain@ubuntu$
</code></pre>
<p>Source for question 1 <a title="here" href="https://intranet.hbtn.io/rltoken/XOGXwmI_Zu5N6v-23GO_vA" target="_blank" rel="noopener">here</a></p>