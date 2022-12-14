
<!DOCTYPE html>
<html lang="en-US">

  <head>
    <meta charset='utf-8'>
    <meta http-equiv="X-UA-Compatible" content="IE=edge">
    <meta name="viewport" content="width=device-width,maximum-scale=2">
    <link rel="stylesheet" type="text/css" media="screen" href="/assets/css/style.css?v=bee61cfe411c270f1f8420debc42121cd5759665">

<!-- Begin Jekyll SEO tag v2.8.0 -->
<title>$ WHOAMI | m3n0sd0n4ld (David Utón)</title>
<meta name="generator" content="Jekyll v3.9.2" />
<meta property="og:title" content="$ WHOAMI" />
<meta property="og:locale" content="en_US" />
<meta name="description" content="Writeups HTB, THM, VulnHub and others…" />
<meta property="og:description" content="Writeups HTB, THM, VulnHub and others…" />
<link rel="canonical" href="https://m3n0sd0n4ld.github.io/" />
<meta property="og:url" content="https://m3n0sd0n4ld.github.io/" />
<meta property="og:site_name" content="m3n0sd0n4ld (David Utón)" />
<meta property="og:type" content="website" />
<meta name="twitter:card" content="summary" />
<meta property="twitter:title" content="$ WHOAMI" />
<script type="application/ld+json">
{"@context":"https://schema.org","@type":"WebSite","description":"Writeups HTB, THM, VulnHub and others…","headline":"$ WHOAMI","name":"m3n0sd0n4ld (David Utón)","url":"https://m3n0sd0n4ld.github.io/"}</script>
<!-- End Jekyll SEO tag -->

    <!-- start custom head snippets, customize with your own _includes/head-custom.html file -->

<!-- Setup Google Analytics -->



<!-- You can set your favicon here -->
<!-- link rel="shortcut icon" type="image/x-icon" href="/favicon.ico" -->

<!-- end custom head snippets -->

  </head>

  <body>

    <!-- HEADER -->
    <div id="header_wrap" class="outer">
        <header class="inner">
          

          <h1 id="project_title">m3n0sd0n4ld (David Utón)</h1>
          <h2 id="project_tagline">Writeups HTB, THM, VulnHub and others...</h2>

          
        </header>
    </div>

    <!-- MAIN CONTENT -->
    <div id="main_content_wrap" class="outer">
      <section id="main_content" class="inner">
        <h2 id="-whoami">$ WHOAMI</h2>

<h2 id="tools">Tools</h2>
<ol>
  <li><a href="https://github.com/m3n0sd0n4ld/GooFuzz">GooFuzz</a>: GooFuzz is a tool to perform fuzzing with an OSINT approach, managing to enumerate directories, files, subdomains or parameters without leaving evidence on the target’s server and by means of advanced Google searches (Google Dorking).</li>
  <li><a href="https://github.com/m3n0sd0n4ld/uDork">uDork</a>: uDork is a script written in Bash Scripting that uses advanced Google search techniques to obtain sensitive information in files or directories, find IoT devices, detect versions of web application… (<strong>Currently not working</strong>)</li>
  <li><a href="https://github.com/m3n0sd0n4ld/uNominaCracker">uNominaCracker</a>: It is a script written in Python that performs brute force on workers’ payroll files through the use of their DNI (National Identity Document).</li>
</ol>

<hr />
<h2 id="exploits">Exploits</h2>

<table>
  <thead>
    <tr>
      <th>Software</th>
      <th style="text-align: center">CVE</th>
      <th style="text-align: center">Link</th>
    </tr>
  </thead>
  <tbody>
    <tr>
      <td>WordPress 5.7 - ‘Media Library’ XML External Entity Injection (XXE) (Authenticated)</td>
      <td style="text-align: center">CVE-2021-29447</td>
      <td style="text-align: center"><a href="https://www.exploit-db.com/exploits/50304">Link</a></td>
    </tr>
    <tr>
      <td>SUDO</td>
      <td style="text-align: center">CVE-2021-3156 (Checker)</td>
      <td style="text-align: center"><a href="https://github.com/m3n0sd0n4ld/CVE-Exploits/tree/main/CVE-2021-3156">Link</a></td>
    </tr>
    <tr>
      <td>Strapi &lt; 3.0.0-beta.17.7 (Authenticated)</td>
      <td style="text-align: center">CVE-2019-19609</td>
      <td style="text-align: center"><a href="https://www.exploit-db.com/exploits/50238">Link</a></td>
    </tr>
    <tr>
      <td>Simple Image Gallery System 1.0 - SQL Injection (Time-Based blind)</td>
      <td style="text-align: center">n/a</td>
      <td style="text-align: center"><a href="https://github.com/m3n0sd0n4ld/CVE-Exploits/blob/main/Simple%20Image%20Gallery%20System/index.md">Link</a></td>
    </tr>
    <tr>
      <td>Company’s Recruitment Management System 1.0 - Remote Readable Administrator Credentials (Unauthenticated)</td>
      <td style="text-align: center">n/a</td>
      <td style="text-align: center"><a href="https://m3n0sd0n4ld.github.io/articles/Company-Recruitment-Management-System_1.0_Remote_Readable_Administrator_Credentials%20(Unauthenticated)/">Link</a></td>
    </tr>
  </tbody>
</table>

<hr />

<h2 id="writeups">Writeups</h2>
<p><img src="imgs/hackthebox.png" width="200" align="center" /></p>

<table>
  <thead>
    <tr>
      <th style="text-align: left">Name</th>
      <th style="text-align: center">Level</th>
      <th style="text-align: center">OS</th>
      <th style="text-align: center">Tags</th>
    </tr>
  </thead>
  <tbody>
    <tr>
      <td style="text-align: left"><a href="https://github.com/m3n0sd0n4ld/writeups/blob/master/pdfs/Resolute%20-%20hackthebox.pdf">Resolute</a></td>
      <td style="text-align: center"><code class="language-plaintext highlighter-rouge">Medium</code></td>
      <td style="text-align: center"><code class="language-plaintext highlighter-rouge">Windows</code></td>
      <td style="text-align: center"><code class="language-plaintext highlighter-rouge">#smb #evil-winrm #password-spray</code></td>
    </tr>
    <tr>
      <td style="text-align: left"><a href="https://www.hackingarticles.in/hack-the-box-monteverde-walkthrough">Monteverde</a></td>
      <td style="text-align: center"><code class="language-plaintext highlighter-rouge">Medium</code></td>
      <td style="text-align: center"><code class="language-plaintext highlighter-rouge">Windows</code></td>
      <td style="text-align: center"><code class="language-plaintext highlighter-rouge">#enum4linux #powershell #AzureAD</code></td>
    </tr>
    <tr>
      <td style="text-align: left"><a href="https://www.hackingarticles.in/hackthebox-sauna-walkthrough/">Sauna</a></td>
      <td style="text-align: center"><code class="language-plaintext highlighter-rouge">Easy</code></td>
      <td style="text-align: center"><code class="language-plaintext highlighter-rouge">Windows</code></td>
      <td style="text-align: center"><code class="language-plaintext highlighter-rouge">#GetNPUsers #mimikatz #winPEAS</code></td>
    </tr>
    <tr>
      <td style="text-align: left"><a href="https://www.hackingarticles.in/conceal-hackthebox-walkthrough/">Conceal</a></td>
      <td style="text-align: center"><code class="language-plaintext highlighter-rouge">Hard</code></td>
      <td style="text-align: center"><code class="language-plaintext highlighter-rouge">Windows</code></td>
      <td style="text-align: center"><code class="language-plaintext highlighter-rouge">#snmp #ike-scan #strongswan</code></td>
    </tr>
    <tr>
      <td style="text-align: left"><a href="https://www.hackingarticles.in/omni-hackthebox-walkthrough/">Omni</a></td>
      <td style="text-align: center"><code class="language-plaintext highlighter-rouge">Easy</code></td>
      <td style="text-align: center"><code class="language-plaintext highlighter-rouge">Windows</code></td>
      <td style="text-align: center"><code class="language-plaintext highlighter-rouge">#IoT #SirepRAT.py #WDP</code></td>
    </tr>
    <tr>
      <td style="text-align: left"><a href="https://www.hackingarticles.in/mango-hackthebox-walkthrough/">Mango</a></td>
      <td style="text-align: center"><code class="language-plaintext highlighter-rouge">Medium</code></td>
      <td style="text-align: center"><code class="language-plaintext highlighter-rouge">Linux</code></td>
      <td style="text-align: center"><code class="language-plaintext highlighter-rouge">#NoSQL #script #SUID #jjs #java</code></td>
    </tr>
    <tr>
      <td style="text-align: left"><a href="https://www.hackingarticles.in/bastard-hackthebox-walkthrough/">Bastard</a></td>
      <td style="text-align: center"><code class="language-plaintext highlighter-rouge">Medium</code></td>
      <td style="text-align: center"><code class="language-plaintext highlighter-rouge">Windows</code></td>
      <td style="text-align: center"><code class="language-plaintext highlighter-rouge">#Drupal #RCE</code></td>
    </tr>
    <tr>
      <td style="text-align: left"><a href="https://www.hackingarticles.in/forest-hackthebox-walkthrough/">Forest</a></td>
      <td style="text-align: center"><code class="language-plaintext highlighter-rouge">Easy</code></td>
      <td style="text-align: center"><code class="language-plaintext highlighter-rouge">Windows</code></td>
      <td style="text-align: center"><code class="language-plaintext highlighter-rouge">#Exchange #Secretsdump</code></td>
    </tr>
    <tr>
      <td style="text-align: left"><a href="https://www.hackingarticles.in/doctor-hackthebox-walkthrough/">Doctor</a></td>
      <td style="text-align: center"><code class="language-plaintext highlighter-rouge">Easy</code></td>
      <td style="text-align: center"><code class="language-plaintext highlighter-rouge">Linux</code></td>
      <td style="text-align: center"><code class="language-plaintext highlighter-rouge">#SSTI #RCE #Splunk</code></td>
    </tr>
    <tr>
      <td style="text-align: left"><a href="https://www.hackingarticles.in/chaos-hackthebox-walkthrough/">Chaos</a></td>
      <td style="text-align: center"><code class="language-plaintext highlighter-rouge">Medium</code></td>
      <td style="text-align: center"><code class="language-plaintext highlighter-rouge">Linux</code></td>
      <td style="text-align: center"><code class="language-plaintext highlighter-rouge">#WP #Roundcube #Firefox</code></td>
    </tr>
    <tr>
      <td style="text-align: left"><a href="https://m3n0sd0n4ld.github.io/htb/Armageddon/">Armageddon</a></td>
      <td style="text-align: center"><code class="language-plaintext highlighter-rouge">Easy</code></td>
      <td style="text-align: center"><code class="language-plaintext highlighter-rouge">Linux</code></td>
      <td style="text-align: center"><code class="language-plaintext highlighter-rouge">#Drupal #Snap</code></td>
    </tr>
    <tr>
      <td style="text-align: left"><a href="https://m3n0sd0n4ld.github.io/htb/Knife/">Knife</a></td>
      <td style="text-align: center"><code class="language-plaintext highlighter-rouge">Easy</code></td>
      <td style="text-align: center"><code class="language-plaintext highlighter-rouge">Linux</code></td>
      <td style="text-align: center"><code class="language-plaintext highlighter-rouge">#PHP8 #RCE #Knife</code></td>
    </tr>
    <tr>
      <td style="text-align: left"><a href="https://m3n0sd0n4ld.github.io/htb/BountyHunter/">BountyHunter</a></td>
      <td style="text-align: center"><code class="language-plaintext highlighter-rouge">Easy</code></td>
      <td style="text-align: center"><code class="language-plaintext highlighter-rouge">Linux</code></td>
      <td style="text-align: center"><code class="language-plaintext highlighter-rouge">#XXE #RCE #MDFiles</code></td>
    </tr>
    <tr>
      <td style="text-align: left">Explore (<strong>private</strong>)</td>
      <td style="text-align: center"><code class="language-plaintext highlighter-rouge">Easy</code></td>
      <td style="text-align: center"><code class="language-plaintext highlighter-rouge">Android</code></td>
      <td style="text-align: center">—</td>
    </tr>
    <tr>
      <td style="text-align: left">Previse (<strong>private</strong>)</td>
      <td style="text-align: center"><code class="language-plaintext highlighter-rouge">Easy</code></td>
      <td style="text-align: center"><code class="language-plaintext highlighter-rouge">Linux</code></td>
      <td style="text-align: center">—</td>
    </tr>
    <tr>
      <td style="text-align: left"><a href="https://m3n0sd0n4ld.github.io/htb/Driver/">Driver</a></td>
      <td style="text-align: center"><code class="language-plaintext highlighter-rouge">Easy</code></td>
      <td style="text-align: center"><code class="language-plaintext highlighter-rouge">Windows</code></td>
      <td style="text-align: center"><code class="language-plaintext highlighter-rouge">#Drivers #MFP #RCE</code></td>
    </tr>
    <tr>
      <td style="text-align: left"><a href="https://m3n0sd0n4ld.github.io/htb/Bolt/">Bolt</a></td>
      <td style="text-align: center"><code class="language-plaintext highlighter-rouge">Medium</code></td>
      <td style="text-align: center"><code class="language-plaintext highlighter-rouge">Linux</code></td>
      <td style="text-align: center"><code class="language-plaintext highlighter-rouge">#Passbolt #AdminLTE3 #GPG</code></td>
    </tr>
    <tr>
      <td style="text-align: left"><a href="https://m3n0sd0n4ld.github.io/htb/Secret/">Secret</a></td>
      <td style="text-align: center"><code class="language-plaintext highlighter-rouge">Easy</code></td>
      <td style="text-align: center"><code class="language-plaintext highlighter-rouge">Linux</code></td>
      <td style="text-align: center"><code class="language-plaintext highlighter-rouge">#JWT #Cmd-Injection</code></td>
    </tr>
    <tr>
      <td style="text-align: left"><a href="https://m3n0sd0n4ld.github.io/htb/Shibboleth/">Shibboleth</a></td>
      <td style="text-align: center"><code class="language-plaintext highlighter-rouge">Medium</code></td>
      <td style="text-align: center"><code class="language-plaintext highlighter-rouge">Linux</code></td>
      <td style="text-align: center"><code class="language-plaintext highlighter-rouge">#IPMI #Zabbix #MariaDB </code></td>
    </tr>
    <tr>
      <td style="text-align: left"><a href="https://m3n0sd0n4ld.github.io/htb/Paper/">Paper</a></td>
      <td style="text-align: center"><code class="language-plaintext highlighter-rouge">Easy</code></td>
      <td style="text-align: center"><code class="language-plaintext highlighter-rouge">Linux</code></td>
      <td style="text-align: center"><code class="language-plaintext highlighter-rouge">WordPress</code> <code class="language-plaintext highlighter-rouge">#rocketchat</code> <code class="language-plaintext highlighter-rouge">#Polkit</code></td>
    </tr>
    <tr>
      <td style="text-align: left"><a href="https://m3n0sd0n4ld.github.io/htb/Timelapse/">Timelapse (<strong>private</strong>)</a></td>
      <td style="text-align: center"><code class="language-plaintext highlighter-rouge">Easy</code></td>
      <td style="text-align: center"><code class="language-plaintext highlighter-rouge">Windows</code></td>
      <td style="text-align: center">—</td>
    </tr>
    <tr>
      <td style="text-align: left"><a href="https://m3n0sd0n4ld.github.io/htb/Pandora/">Pandora</a></td>
      <td style="text-align: center"><code class="language-plaintext highlighter-rouge">Easy</code></td>
      <td style="text-align: center"><code class="language-plaintext highlighter-rouge">Linux</code></td>
      <td style="text-align: center"><code class="language-plaintext highlighter-rouge">#SNMP</code> <code class="language-plaintext highlighter-rouge">#PandoraFMS</code> <code class="language-plaintext highlighter-rouge">#PathHijacking</code></td>
    </tr>
    <tr>
      <td style="text-align: left"><a href="https://m3n0sd0n4ld.github.io/htb/Unicode/">Unicode</a></td>
      <td style="text-align: center"><code class="language-plaintext highlighter-rouge">Medium</code></td>
      <td style="text-align: center"><code class="language-plaintext highlighter-rouge">Linux</code></td>
      <td style="text-align: center"><code class="language-plaintext highlighter-rouge">#JWT</code> <code class="language-plaintext highlighter-rouge">#RSA</code> <code class="language-plaintext highlighter-rouge">#ByPass</code> <code class="language-plaintext highlighter-rouge">#cURL</code></td>
    </tr>
    <tr>
      <td style="text-align: left"><a href="https://m3n0sd0n4ld.github.io/htb/RouterSpace/">RouterSpace</a></td>
      <td style="text-align: center"><code class="language-plaintext highlighter-rouge">Easy</code></td>
      <td style="text-align: center"><code class="language-plaintext highlighter-rouge">Linux</code></td>
      <td style="text-align: center"><code class="language-plaintext highlighter-rouge">#apk #anbox #cmdinjection #SUDO</code></td>
    </tr>
    <tr>
      <td style="text-align: left"><a href="https://m3n0sd0n4ld.github.io/htb/Meta/">Meta</a></td>
      <td style="text-align: center"><code class="language-plaintext highlighter-rouge">Medium</code></td>
      <td style="text-align: center"><code class="language-plaintext highlighter-rouge">Linux</code></td>
      <td style="text-align: center"><code class="language-plaintext highlighter-rouge">#Exiftool</code> <code class="language-plaintext highlighter-rouge">#RCE</code> <code class="language-plaintext highlighter-rouge">#Mogrify</code> <code class="language-plaintext highlighter-rouge">#ImageMagick</code> <code class="language-plaintext highlighter-rouge">#Neofetch</code></td>
    </tr>
    <tr>
      <td style="text-align: left"><a href="https://m3n0sd0n4ld.github.io/htb/Undetected/">Undetected</a></td>
      <td style="text-align: center"><code class="language-plaintext highlighter-rouge">Medium</code></td>
      <td style="text-align: center"><code class="language-plaintext highlighter-rouge">Linux</code></td>
      <td style="text-align: center"><code class="language-plaintext highlighter-rouge">#PHPUnit</code> <code class="language-plaintext highlighter-rouge">#RCE</code> <code class="language-plaintext highlighter-rouge">#XOR</code> <code class="language-plaintext highlighter-rouge">#Reversing</code></td>
    </tr>
    <tr>
      <td style="text-align: left"><a href="https://m3n0sd0n4ld.github.io/htb/Timing/">Timing</a></td>
      <td style="text-align: center"><code class="language-plaintext highlighter-rouge">Medium</code></td>
      <td style="text-align: center"><code class="language-plaintext highlighter-rouge">Linux</code></td>
      <td style="text-align: center"><code class="language-plaintext highlighter-rouge">#PHPWrappers #PHPTime #Git</code></td>
    </tr>
    <tr>
      <td style="text-align: left"><a href="https://m3n0sd0n4ld.github.io/htb/AdmirerToo/">AdmirerToo</a></td>
      <td style="text-align: center"><code class="language-plaintext highlighter-rouge">Hard</code></td>
      <td style="text-align: center"><code class="language-plaintext highlighter-rouge">Linux</code></td>
      <td style="text-align: center"><code class="language-plaintext highlighter-rouge">#Adminer</code> <code class="language-plaintext highlighter-rouge">#SSRF</code> <code class="language-plaintext highlighter-rouge">#OpenTSDB</code> <code class="language-plaintext highlighter-rouge">#OpenCATS</code> <code class="language-plaintext highlighter-rouge">#Fail2Ban</code></td>
    </tr>
    <tr>
      <td style="text-align: left"><a href="https://m3n0sd0n4ld.github.io/htb/Catch/">Catch</a></td>
      <td style="text-align: center"><code class="language-plaintext highlighter-rouge">Medium</code></td>
      <td style="text-align: center"><code class="language-plaintext highlighter-rouge">Linux</code></td>
      <td style="text-align: center"><code class="language-plaintext highlighter-rouge">#APK</code> <code class="language-plaintext highlighter-rouge">#Cachet</code> <code class="language-plaintext highlighter-rouge">#SQLi</code> <code class="language-plaintext highlighter-rouge">#jarsigner</code></td>
    </tr>
    <tr>
      <td style="text-align: left"><a href="https://m3n0sd0n4ld.github.io/htb/Noter/">Noter (<strong>private</strong>)</a></td>
      <td style="text-align: center"><code class="language-plaintext highlighter-rouge">Medium</code></td>
      <td style="text-align: center"><code class="language-plaintext highlighter-rouge">Linux</code></td>
      <td style="text-align: center">—</td>
    </tr>
    <tr>
      <td style="text-align: left"><a href="https://m3n0sd0n4ld.github.io/htb/Acute/">Acute</a></td>
      <td style="text-align: center"><code class="language-plaintext highlighter-rouge">Hard</code></td>
      <td style="text-align: center"><code class="language-plaintext highlighter-rouge">Windows</code></td>
      <td style="text-align: center"><code class="language-plaintext highlighter-rouge">#PowershellWeb</code> <code class="language-plaintext highlighter-rouge">#AV</code> <code class="language-plaintext highlighter-rouge">#Invoke-Command</code></td>
    </tr>
    <tr>
      <td style="text-align: left"><a href="https://m3n0sd0n4ld.github.io/htb/Phoenix/">Phoenix</a></td>
      <td style="text-align: center"><code class="language-plaintext highlighter-rouge">Hard</code></td>
      <td style="text-align: center"><code class="language-plaintext highlighter-rouge">Linux</code></td>
      <td style="text-align: center"><code class="language-plaintext highlighter-rouge">#WP</code> <code class="language-plaintext highlighter-rouge">#plugins</code> <code class="language-plaintext highlighter-rouge">#google-authenticator</code> <code class="language-plaintext highlighter-rouge">#rsync</code></td>
    </tr>
    <tr>
      <td style="text-align: left"><a href="https://m3n0sd0n4ld.github.io/htb/OpenSource/">OpenSource (<strong>private</strong>)</a></td>
      <td style="text-align: center"><code class="language-plaintext highlighter-rouge">Easy</code></td>
      <td style="text-align: center"><code class="language-plaintext highlighter-rouge">Linux</code></td>
      <td style="text-align: center">—</td>
    </tr>
    <tr>
      <td style="text-align: left"><a href="https://m3n0sd0n4ld.github.io/htb/Trick/">Trick (<strong>private</strong>)</a></td>
      <td style="text-align: center"><code class="language-plaintext highlighter-rouge">Easy</code></td>
      <td style="text-align: center"><code class="language-plaintext highlighter-rouge">Linux</code></td>
      <td style="text-align: center">—</td>
    </tr>
    <tr>
      <td style="text-align: left"><a href="https://m3n0sd0n4ld.github.io/htb/Faculty/">Faculty (<strong>private</strong>)</a></td>
      <td style="text-align: center"><code class="language-plaintext highlighter-rouge">Medium</code></td>
      <td style="text-align: center"><code class="language-plaintext highlighter-rouge">Linux</code></td>
      <td style="text-align: center">—</td>
    </tr>
    <tr>
      <td style="text-align: left"><a href="https://m3n0sd0n4ld.github.io/htb/Late/">Late</a></td>
      <td style="text-align: center"><code class="language-plaintext highlighter-rouge">Easy</code></td>
      <td style="text-align: center"><code class="language-plaintext highlighter-rouge">Linux</code></td>
      <td style="text-align: center"><code class="language-plaintext highlighter-rouge">#SSTI</code> <code class="language-plaintext highlighter-rouge">#Jinja2</code> <code class="language-plaintext highlighter-rouge">#misconfiguration</code></td>
    </tr>
    <tr>
      <td style="text-align: left"><a href="https://m3n0sd0n4ld.github.io/htb/RedPanda/">RedPanda (<strong>private</strong>)</a></td>
      <td style="text-align: center"><code class="language-plaintext highlighter-rouge">Easy</code></td>
      <td style="text-align: center"><code class="language-plaintext highlighter-rouge">Linux</code></td>
      <td style="text-align: center">—</td>
    </tr>
    <tr>
      <td style="text-align: left"><a href="https://m3n0sd0n4ld.github.io/htb/StreamIO/">StreamIO (<strong>private</strong>)</a></td>
      <td style="text-align: center"><code class="language-plaintext highlighter-rouge">Medium</code></td>
      <td style="text-align: center"><code class="language-plaintext highlighter-rouge">Windows</code></td>
      <td style="text-align: center">—</td>
    </tr>
    <tr>
      <td style="text-align: left"><a href="https://m3n0sd0n4ld.github.io/htb/Talkative/">Talkative</a></td>
      <td style="text-align: center"><code class="language-plaintext highlighter-rouge">Hard</code></td>
      <td style="text-align: center"><code class="language-plaintext highlighter-rouge">Linux</code></td>
      <td style="text-align: center"><code class="language-plaintext highlighter-rouge">#rocketchat</code> <code class="language-plaintext highlighter-rouge">#jamovi</code> <code class="language-plaintext highlighter-rouge">#boltcms</code> <code class="language-plaintext highlighter-rouge">#mongodb</code> <code class="language-plaintext highlighter-rouge">#cap-dac-read-search</code></td>
    </tr>
    <tr>
      <td style="text-align: left"><a href="https://m3n0sd0n4ld.github.io/htb/Support/">Support (<strong>private</strong>)</a></td>
      <td style="text-align: center"><code class="language-plaintext highlighter-rouge">Easy</code></td>
      <td style="text-align: center"><code class="language-plaintext highlighter-rouge">Windows</code></td>
      <td style="text-align: center">—</td>
    </tr>
    <tr>
      <td style="text-align: left"><a href="https://m3n0sd0n4ld.github.io/htb/Shared/">Shared (<strong>private</strong>)</a></td>
      <td style="text-align: center"><code class="language-plaintext highlighter-rouge">Medium</code></td>
      <td style="text-align: center"><code class="language-plaintext highlighter-rouge">Linux</code></td>
      <td style="text-align: center">—</td>
    </tr>
  </tbody>
</table>

<p><img src="imgs/tryhackme.png" width="200" align="center" /></p>

<table>
  <thead>
    <tr>
      <th style="text-align: left">Name</th>
      <th style="text-align: center">Level</th>
      <th style="text-align: center">OS</th>
      <th style="text-align: center">Tags</th>
    </tr>
  </thead>
  <tbody>
    <tr>
      <td style="text-align: left"><a href="https://www.hackingarticles.in/relevant-tryhackme-walkthrough/">Relevant</a></td>
      <td style="text-align: center"><code class="language-plaintext highlighter-rouge">Medium</code></td>
      <td style="text-align: center"><code class="language-plaintext highlighter-rouge">Windows</code></td>
      <td style="text-align: center"><code class="language-plaintext highlighter-rouge">#smb #cmdasp</code></td>
    </tr>
    <tr>
      <td style="text-align: left"><a href="https://www.hackingarticles.in/startup-tryhackme-walkthrough/">Startup</a></td>
      <td style="text-align: center"><code class="language-plaintext highlighter-rouge">Easy</code></td>
      <td style="text-align: center"><code class="language-plaintext highlighter-rouge">Linux</code></td>
      <td style="text-align: center"><code class="language-plaintext highlighter-rouge">#wireshark #cron #gobuster</code></td>
    </tr>
    <tr>
      <td style="text-align: left"><a href="https://www.hackingarticles.in/internal-tryhackme-walkthrough/">Internal</a></td>
      <td style="text-align: center"><code class="language-plaintext highlighter-rouge">Hard</code></td>
      <td style="text-align: center"><code class="language-plaintext highlighter-rouge">Linux</code></td>
      <td style="text-align: center"><code class="language-plaintext highlighter-rouge">#WP #Jenkins</code></td>
    </tr>
    <tr>
      <td style="text-align: left"><a href="https://www.hackingarticles.in/revenge-tryhackme-walkthrough">Revenge</a></td>
      <td style="text-align: center"><code class="language-plaintext highlighter-rouge">Medium</code></td>
      <td style="text-align: center"><code class="language-plaintext highlighter-rouge">Linux</code></td>
      <td style="text-align: center"><code class="language-plaintext highlighter-rouge">#sqlmap #sudo #systemctl</code></td>
    </tr>
    <tr>
      <td style="text-align: left"><a href="https://www.hackingarticles.in/0day-tryhackme-walkthrough">0day</a></td>
      <td style="text-align: center"><code class="language-plaintext highlighter-rouge">Medium</code></td>
      <td style="text-align: center"><code class="language-plaintext highlighter-rouge">Linux</code></td>
      <td style="text-align: center"><code class="language-plaintext highlighter-rouge">#shellshock #overlays</code></td>
    </tr>
    <tr>
      <td style="text-align: left"><a href="https://www.hackingarticles.in/ghizer-tryhackme-walkthrough">Ghizer</a></td>
      <td style="text-align: center"><code class="language-plaintext highlighter-rouge">Medium</code></td>
      <td style="text-align: center"><code class="language-plaintext highlighter-rouge">Linux</code></td>
      <td style="text-align: center"><code class="language-plaintext highlighter-rouge">#debug #RCE #Limesurvey #ghidra</code></td>
    </tr>
    <tr>
      <td style="text-align: left"><a href="https://www.hackingarticles.in/iron-corp-tryhackme-walkthrough">Iron Corp</a></td>
      <td style="text-align: center"><code class="language-plaintext highlighter-rouge">Hard</code></td>
      <td style="text-align: center"><code class="language-plaintext highlighter-rouge">Windows</code></td>
      <td style="text-align: center"><code class="language-plaintext highlighter-rouge">#hydra #dig #SSRF #ACL</code></td>
    </tr>
    <tr>
      <td style="text-align: left"><a href="https://m3n0sd0n4ld.github.io/thm/Bookstore">Bookstore</a></td>
      <td style="text-align: center"><code class="language-plaintext highlighter-rouge">Medium</code></td>
      <td style="text-align: center"><code class="language-plaintext highlighter-rouge">Linux</code></td>
      <td style="text-align: center"><code class="language-plaintext highlighter-rouge">#rest #api #python #SUID</code></td>
    </tr>
    <tr>
      <td style="text-align: left"><a href="https://m3n0sd0n4ld.github.io/thm/USTOUN/">USTOUN</a></td>
      <td style="text-align: center"><code class="language-plaintext highlighter-rouge">Medium</code></td>
      <td style="text-align: center"><code class="language-plaintext highlighter-rouge">Windows</code></td>
      <td style="text-align: center"><code class="language-plaintext highlighter-rouge">#AD #RID #crackmapexec #mssqlclient</code></td>
    </tr>
    <tr>
      <td style="text-align: left"><a href="https://m3n0sd0n4ld.github.io/thm/GoldenEye/">GoldenEye</a></td>
      <td style="text-align: center"><code class="language-plaintext highlighter-rouge">Medium</code></td>
      <td style="text-align: center"><code class="language-plaintext highlighter-rouge">Linux</code></td>
      <td style="text-align: center"><code class="language-plaintext highlighter-rouge">#hydra #telnet #pop3 #aspell #overlays</code></td>
    </tr>
    <tr>
      <td style="text-align: left"><a href="https://m3n0sd0n4ld.github.io/thm/LunizzCTF/">Lunizz CTF (Patched)</a></td>
      <td style="text-align: center"><code class="language-plaintext highlighter-rouge">Medium</code></td>
      <td style="text-align: center"><code class="language-plaintext highlighter-rouge">Linux</code></td>
      <td style="text-align: center"><code class="language-plaintext highlighter-rouge">#Cmd-inject #mysql #bcrypt #cipher</code></td>
    </tr>
    <tr>
      <td style="text-align: left"><a href="https://m3n0sd0n4ld.github.io/thm/CatPictures/">Cat Pictures</a></td>
      <td style="text-align: center"><code class="language-plaintext highlighter-rouge">Easy</code></td>
      <td style="text-align: center"><code class="language-plaintext highlighter-rouge">Linux</code></td>
      <td style="text-align: center"><code class="language-plaintext highlighter-rouge">#phpbb #docker #cron</code></td>
    </tr>
    <tr>
      <td style="text-align: left"><a href="https://m3n0sd0n4ld.github.io/thm/WgelCTF/">Wgel CTF</a></td>
      <td style="text-align: center"><code class="language-plaintext highlighter-rouge">Easy</code></td>
      <td style="text-align: center"><code class="language-plaintext highlighter-rouge">Linux</code></td>
      <td style="text-align: center"><code class="language-plaintext highlighter-rouge">#wget #passwd #SUDO</code></td>
    </tr>
    <tr>
      <td style="text-align: left"><a href="https://m3n0sd0n4ld.github.io/thm/Jack-of-All-Trades/">Jack-of-All-Trades</a></td>
      <td style="text-align: center"><code class="language-plaintext highlighter-rouge">Easy</code></td>
      <td style="text-align: center"><code class="language-plaintext highlighter-rouge">Linux</code></td>
      <td style="text-align: center"><code class="language-plaintext highlighter-rouge">#crypto #stego #strings</code></td>
    </tr>
    <tr>
      <td style="text-align: left"><a href="https://m3n0sd0n4ld.github.io/thm/VulnNet-dotjar/">VulnNet: dotjar</a></td>
      <td style="text-align: center"><code class="language-plaintext highlighter-rouge">Medium</code></td>
      <td style="text-align: center"><code class="language-plaintext highlighter-rouge">Linux</code></td>
      <td style="text-align: center"><code class="language-plaintext highlighter-rouge">#ghostcat #war #tomcat #SUDO #jar</code></td>
    </tr>
    <tr>
      <td style="text-align: left"><a href="https://m3n0sd0n4ld.github.io/thm/KoTH-Food-CTF/">KoTH Food CTF</a></td>
      <td style="text-align: center"><code class="language-plaintext highlighter-rouge">Easy</code></td>
      <td style="text-align: center"><code class="language-plaintext highlighter-rouge">Linux</code></td>
      <td style="text-align: center"><code class="language-plaintext highlighter-rouge">#mysql #SETUID #screen</code></td>
    </tr>
    <tr>
      <td style="text-align: left"><a href="https://m3n0sd0n4ld.github.io/thm/KoTH-Hackers/">KoTH Hackers</a></td>
      <td style="text-align: center"><code class="language-plaintext highlighter-rouge">Medium</code></td>
      <td style="text-align: center"><code class="language-plaintext highlighter-rouge">Linux</code></td>
      <td style="text-align: center"><code class="language-plaintext highlighter-rouge">#ssh #privatekeys #SUDO #nano</code></td>
    </tr>
    <tr>
      <td style="text-align: left"><a href="https://m3n0sd0n4ld.github.io/thm/The-Blob-Blog/">The Blob Blog</a></td>
      <td style="text-align: center"><code class="language-plaintext highlighter-rouge">Medium</code></td>
      <td style="text-align: center"><code class="language-plaintext highlighter-rouge">Linux</code></td>
      <td style="text-align: center"><code class="language-plaintext highlighter-rouge">#brainfuck #steghide #reversing</code></td>
    </tr>
    <tr>
      <td style="text-align: left"><a href="https://m3n0sd0n4ld.github.io/thm/Mustacchio/">Mustacchio</a></td>
      <td style="text-align: center"><code class="language-plaintext highlighter-rouge">Easy</code></td>
      <td style="text-align: center"><code class="language-plaintext highlighter-rouge">Linux</code></td>
      <td style="text-align: center"><code class="language-plaintext highlighter-rouge">#XXE #pathabsolute #tail</code></td>
    </tr>
    <tr>
      <td style="text-align: left"><a href="https://m3n0sd0n4ld.github.io/thm/Harder/">Harder</a></td>
      <td style="text-align: center"><code class="language-plaintext highlighter-rouge">Medium</code></td>
      <td style="text-align: center"><code class="language-plaintext highlighter-rouge">Linux</code></td>
      <td style="text-align: center"><code class="language-plaintext highlighter-rouge">#git #alpine #gpg</code></td>
    </tr>
    <tr>
      <td style="text-align: left"><a href="https://m3n0sd0n4ld.github.io/thm/Fusion-Corp/">Fusion Corp</a></td>
      <td style="text-align: center"><code class="language-plaintext highlighter-rouge">Hard</code></td>
      <td style="text-align: center"><code class="language-plaintext highlighter-rouge">Windows</code></td>
      <td style="text-align: center"><code class="language-plaintext highlighter-rouge">#kerbrute #ASReproast #LDAP #AD</code></td>
    </tr>
    <tr>
      <td style="text-align: left"><a href="https://m3n0sd0n4ld.github.io/thm/EnterPrize/">EnterPrize</a></td>
      <td style="text-align: center"><code class="language-plaintext highlighter-rouge">Hard</code></td>
      <td style="text-align: center"><code class="language-plaintext highlighter-rouge">Linux</code></td>
      <td style="text-align: center"><code class="language-plaintext highlighter-rouge">#typo3 #libcustom.so #norootsquash</code></td>
    </tr>
    <tr>
      <td style="text-align: left"><a href="https://m3n0sd0n4ld.github.io/thm/Mnemonic/">Mnemonic</a></td>
      <td style="text-align: center"><code class="language-plaintext highlighter-rouge">Medium</code></td>
      <td style="text-align: center"><code class="language-plaintext highlighter-rouge">Linux</code></td>
      <td style="text-align: center"><code class="language-plaintext highlighter-rouge">#cracking #python #script</code></td>
    </tr>
    <tr>
      <td style="text-align: left"><a href="https://m3n0sd0n4ld.github.io/thm/Undiscovered/">Undiscovered</a></td>
      <td style="text-align: center"><code class="language-plaintext highlighter-rouge">Medium</code></td>
      <td style="text-align: center"><code class="language-plaintext highlighter-rouge">Linux</code></td>
      <td style="text-align: center"><code class="language-plaintext highlighter-rouge">#riteCMS #RCE #norootsquash</code></td>
    </tr>
    <tr>
      <td style="text-align: left"><a href="https://m3n0sd0n4ld.github.io/thm/Couch/">Couch</a></td>
      <td style="text-align: center"><code class="language-plaintext highlighter-rouge">Easy</code></td>
      <td style="text-align: center"><code class="language-plaintext highlighter-rouge">Linux</code></td>
      <td style="text-align: center"><code class="language-plaintext highlighter-rouge">#CouchDB #docker</code></td>
    </tr>
    <tr>
      <td style="text-align: left"><a href="https://m3n0sd0n4ld.github.io/thm/Empline/">Empline</a></td>
      <td style="text-align: center"><code class="language-plaintext highlighter-rouge">Medium</code></td>
      <td style="text-align: center"><code class="language-plaintext highlighter-rouge">Linux</code></td>
      <td style="text-align: center"><code class="language-plaintext highlighter-rouge">#opencats #XXE #capabilities #ruby</code></td>
    </tr>
    <tr>
      <td style="text-align: left"><a href="https://m3n0sd0n4ld.github.io/thm/IDE/">IDE</a></td>
      <td style="text-align: center"><code class="language-plaintext highlighter-rouge">Easy</code></td>
      <td style="text-align: center"><code class="language-plaintext highlighter-rouge">Linux</code></td>
      <td style="text-align: center"><code class="language-plaintext highlighter-rouge">#Codiad #RCE #services</code></td>
    </tr>
    <tr>
      <td style="text-align: left"><a href="https://m3n0sd0n4ld.github.io/thm/zeno/">Zeno</a></td>
      <td style="text-align: center"><code class="language-plaintext highlighter-rouge">Medium</code></td>
      <td style="text-align: center"><code class="language-plaintext highlighter-rouge">Linux</code></td>
      <td style="text-align: center"><code class="language-plaintext highlighter-rouge">#Restaurant #SQLi #RCE #services #reboot</code></td>
    </tr>
    <tr>
      <td style="text-align: left"><a href="https://m3n0sd0n4ld.github.io/thm/Minotaurs-Labyrinth/">Minotaur’s Labyrinth</a></td>
      <td style="text-align: center"><code class="language-plaintext highlighter-rouge">Medium</code></td>
      <td style="text-align: center"><code class="language-plaintext highlighter-rouge">Linux</code></td>
      <td style="text-align: center"><code class="language-plaintext highlighter-rouge">#API #SQLi #Time-based #Cmd-Injection</code></td>
    </tr>
    <tr>
      <td style="text-align: left"><a href="https://m3n0sd0n4ld.github.io/thm/Lumberjack-Turtle/">Lumberjack Turtle</a></td>
      <td style="text-align: center"><code class="language-plaintext highlighter-rouge">Medium</code></td>
      <td style="text-align: center"><code class="language-plaintext highlighter-rouge">Linux</code></td>
      <td style="text-align: center"><code class="language-plaintext highlighter-rouge">#Log4j #Nagios #NSCA #Escape-Docker</code></td>
    </tr>
    <tr>
      <td style="text-align: left"><a href="https://m3n0sd0n4ld.github.io/thm/Flatline/">Flatline</a></td>
      <td style="text-align: center"><code class="language-plaintext highlighter-rouge">Easy</code></td>
      <td style="text-align: center"><code class="language-plaintext highlighter-rouge">Windows</code></td>
      <td style="text-align: center"><code class="language-plaintext highlighter-rouge">#FreeSWITCH #OpenClinic</code></td>
    </tr>
    <tr>
      <td style="text-align: left"><a href="https://m3n0sd0n4ld.github.io/thm/Oh-My-WebServer/">Oh My WebServer</a></td>
      <td style="text-align: center"><code class="language-plaintext highlighter-rouge">Medium</code></td>
      <td style="text-align: center"><code class="language-plaintext highlighter-rouge">Linux</code></td>
      <td style="text-align: center"><code class="language-plaintext highlighter-rouge">#Apache #CVE-2021-41773 #OMIGOD</code></td>
    </tr>
    <tr>
      <td style="text-align: left"><a href="https://m3n0sd0n4ld.github.io/thm/Aratus/">Aratus</a></td>
      <td style="text-align: center"><code class="language-plaintext highlighter-rouge">Medium</code></td>
      <td style="text-align: center"><code class="language-plaintext highlighter-rouge">Linux</code></td>
      <td style="text-align: center"><code class="language-plaintext highlighter-rouge">#tcpdump #capabilities #ansible</code></td>
    </tr>
    <tr>
      <td style="text-align: left"><a href="https://m3n0sd0n4ld.github.io/thm/Ollie/">Ollie</a></td>
      <td style="text-align: center"><code class="language-plaintext highlighter-rouge">Medium</code></td>
      <td style="text-align: center"><code class="language-plaintext highlighter-rouge">Linux</code></td>
      <td style="text-align: center"><code class="language-plaintext highlighter-rouge">#phpIPAM #sqli</code></td>
    </tr>
    <tr>
      <td style="text-align: left"><a href="https://m3n0sd0n4ld.github.io/thm/Plotted-LMS/">Plotted-LMS</a></td>
      <td style="text-align: center"><code class="language-plaintext highlighter-rouge">Hard</code></td>
      <td style="text-align: center"><code class="language-plaintext highlighter-rouge">Linux</code></td>
      <td style="text-align: center"><code class="language-plaintext highlighter-rouge">#Moodle #RCE #Logrotate</code></td>
    </tr>
  </tbody>
</table>

<p><img src="imgs/vulnhub.png" width="200" align="center" /></p>

<table>
  <thead>
    <tr>
      <th style="text-align: left">Name</th>
      <th style="text-align: center">Level</th>
      <th style="text-align: center">OS</th>
      <th style="text-align: center">Tags</th>
    </tr>
  </thead>
  <tbody>
    <tr>
      <td style="text-align: left"><a href="https://github.com/m3n0sd0n4ld/writeups/blob/master/pdfs/VulnUni%20-%20vulnhub.pdf">VulnUni</a></td>
      <td style="text-align: center"><code class="language-plaintext highlighter-rouge">Medium</code></td>
      <td style="text-align: center"><code class="language-plaintext highlighter-rouge">Linux</code></td>
      <td style="text-align: center"><code class="language-plaintext highlighter-rouge">#eClass #SQLi #DirtyCow</code></td>
    </tr>
    <tr>
      <td style="text-align: left"><a href="https://github.com/m3n0sd0n4ld/writeups/blob/master/pdfs/Recon-1%20-%20vulnhub.pdf">Recon:1</a></td>
      <td style="text-align: center"><code class="language-plaintext highlighter-rouge">Easy</code></td>
      <td style="text-align: center"><code class="language-plaintext highlighter-rouge">Linux</code></td>
      <td style="text-align: center"><code class="language-plaintext highlighter-rouge">#WP #SUDO #gdb</code></td>
    </tr>
    <tr>
      <td style="text-align: left"><a href="https://github.com/m3n0sd0n4ld/writeups/blob/master/pdfs/CK-00%20-%20vulnhub.pdf">CK-00</a></td>
      <td style="text-align: center"><code class="language-plaintext highlighter-rouge">Easy</code></td>
      <td style="text-align: center"><code class="language-plaintext highlighter-rouge">Linux</code></td>
      <td style="text-align: center"><code class="language-plaintext highlighter-rouge">#WP #SUDO #scp</code></td>
    </tr>
    <tr>
      <td style="text-align: left"><a href="https://github.com/m3n0sd0n4ld/writeups/blob/master/pdfs/DevRandom%20CTF%201.1-%20vulnhub.pdf">DevRandom CTF: 1.1</a></td>
      <td style="text-align: center"><code class="language-plaintext highlighter-rouge">Easy</code></td>
      <td style="text-align: center"><code class="language-plaintext highlighter-rouge">Linux</code></td>
      <td style="text-align: center"><code class="language-plaintext highlighter-rouge">#LFI #RCE #apache #poison #SUDO #dpkg</code></td>
    </tr>
    <tr>
      <td style="text-align: left"><a href="https://github.com/m3n0sd0n4ld/writeups/blob/master/pdfs/Victim-1%20-%20vulnhub.pdf">Victim: 1</a></td>
      <td style="text-align: center"><code class="language-plaintext highlighter-rouge">Medium</code></td>
      <td style="text-align: center"><code class="language-plaintext highlighter-rouge">Linux</code></td>
      <td style="text-align: center"><code class="language-plaintext highlighter-rouge">#Bolt #WebFS #wpa #wifi #SUID #nohup</code></td>
    </tr>
    <tr>
      <td style="text-align: left"><a href="https://github.com/m3n0sd0n4ld/writeups/blob/master/pdfs/Zion-1%20-%20vulnhub.pdf">Zion: 1</a></td>
      <td style="text-align: center"><code class="language-plaintext highlighter-rouge">Medium</code></td>
      <td style="text-align: center"><code class="language-plaintext highlighter-rouge">Linux</code></td>
      <td style="text-align: center"><code class="language-plaintext highlighter-rouge">#SSH #SUDO #cp</code></td>
    </tr>
    <tr>
      <td style="text-align: left"><a href="https://github.com/m3n0sd0n4ld/writeups/blob/master/pdfs/Death%20Star-1%20-%20vulnhub.pdf">Death Star: 1</a></td>
      <td style="text-align: center"><code class="language-plaintext highlighter-rouge">Medium</code></td>
      <td style="text-align: center"><code class="language-plaintext highlighter-rouge">Linux</code></td>
      <td style="text-align: center"><code class="language-plaintext highlighter-rouge">#UDP #steghide #knockport #lib.so.6</code></td>
    </tr>
    <tr>
      <td style="text-align: left"><a href="https://github.com/m3n0sd0n4ld/writeups/blob/master/pdfs/Tre-1%20-%20vulnhub.pdf">Tre: 1</a></td>
      <td style="text-align: center"><code class="language-plaintext highlighter-rouge">Medium</code></td>
      <td style="text-align: center"><code class="language-plaintext highlighter-rouge">Linux</code></td>
      <td style="text-align: center"><code class="language-plaintext highlighter-rouge">#adminer #mantisBT #SUDO #shutdown</code></td>
    </tr>
    <tr>
      <td style="text-align: left"><a href="https://github.com/m3n0sd0n4ld/writeups/blob/master/pdfs/Seppuku-1%20-%20vulnhub.pdf">Seppuku: 1</a></td>
      <td style="text-align: center"><code class="language-plaintext highlighter-rouge">Hard</code></td>
      <td style="text-align: center"><code class="language-plaintext highlighter-rouge">Linux</code></td>
      <td style="text-align: center"><code class="language-plaintext highlighter-rouge">#webconsole #smb #SUDO #ln</code></td>
    </tr>
    <tr>
      <td style="text-align: left"><a href="https://github.com/m3n0sd0n4ld/writeups/blob/master/pdfs/CengBox-2%20-%20vulnhub.pdf">CengBox: 2</a></td>
      <td style="text-align: center"><code class="language-plaintext highlighter-rouge">Medium</code></td>
      <td style="text-align: center"><code class="language-plaintext highlighter-rouge">Linux</code></td>
      <td style="text-align: center"><code class="language-plaintext highlighter-rouge">#GilaCMS #SUDO #scripts</code></td>
    </tr>
    <tr>
      <td style="text-align: left"><a href="https://www.hackingarticles.in/ha-natraj-vulnhub-walkthrough/">HA: Natraj</a></td>
      <td style="text-align: center"><code class="language-plaintext highlighter-rouge">Medium</code></td>
      <td style="text-align: center"><code class="language-plaintext highlighter-rouge">Linux</code></td>
      <td style="text-align: center"><code class="language-plaintext highlighter-rouge">#LFI #SSH #RCE #poison #SUDO #nmap</code></td>
    </tr>
    <tr>
      <td style="text-align: left"><a href="https://www.hackingarticles.in/glasgow-smile-1-1-vulnhub-walkthrough/">Glasgow Smile: 1.1</a></td>
      <td style="text-align: center"><code class="language-plaintext highlighter-rouge">Medium</code></td>
      <td style="text-align: center"><code class="language-plaintext highlighter-rouge">Linux</code></td>
      <td style="text-align: center"><code class="language-plaintext highlighter-rouge">#joomla #cron</code></td>
    </tr>
    <tr>
      <td style="text-align: left"><a href="https://www.hackingarticles.in/gitroot-1-vulnhub-walkthrough/">GitRoot: 1</a></td>
      <td style="text-align: center"><code class="language-plaintext highlighter-rouge">Medium</code></td>
      <td style="text-align: center"><code class="language-plaintext highlighter-rouge">Linux</code></td>
      <td style="text-align: center"><code class="language-plaintext highlighter-rouge">#git #SUDO</code></td>
    </tr>
    <tr>
      <td style="text-align: left"><a href="https://www.hackingarticles.in/election-1-vulnhub-walkthorugh/">eLection: 1</a></td>
      <td style="text-align: center"><code class="language-plaintext highlighter-rouge">Medium</code></td>
      <td style="text-align: center"><code class="language-plaintext highlighter-rouge">Linux</code></td>
      <td style="text-align: center"><code class="language-plaintext highlighter-rouge">#eLection #OSINT #SQLi #</code></td>
    </tr>
    <tr>
      <td style="text-align: left"><a href="https://www.hackingarticles.in/sunset-decoy-vulnhub-walkthrough/">Sunset: decoy</a></td>
      <td style="text-align: center"><code class="language-plaintext highlighter-rouge">Easy</code></td>
      <td style="text-align: center"><code class="language-plaintext highlighter-rouge">Linux</code></td>
      <td style="text-align: center"><code class="language-plaintext highlighter-rouge">#zip #john #chkrootkit</code></td>
    </tr>
    <tr>
      <td style="text-align: left"><a href="https://www.hackingarticles.in/cybersploit-1-vulnhub-walkthrough/">CyberSploit: 1</a></td>
      <td style="text-align: center"><code class="language-plaintext highlighter-rouge">Easy</code></td>
      <td style="text-align: center"><code class="language-plaintext highlighter-rouge">Linux</code></td>
      <td style="text-align: center"><code class="language-plaintext highlighter-rouge">#crypto #overlays</code></td>
    </tr>
    <tr>
      <td style="text-align: left"><a href="https://www.hackingarticles.in/pwned-1-vulnhub-walkthorugh/">Pwned: 1</a></td>
      <td style="text-align: center"><code class="language-plaintext highlighter-rouge">Easy</code></td>
      <td style="text-align: center"><code class="language-plaintext highlighter-rouge">Linux</code></td>
      <td style="text-align: center"><code class="language-plaintext highlighter-rouge">#SSH #group #docker</code></td>
    </tr>
    <tr>
      <td style="text-align: left"><a href="https://www.hackingarticles.in/blackrose-1-vulnhub-walkthrough/">BlackRose: 1</a></td>
      <td style="text-align: center"><code class="language-plaintext highlighter-rouge">Hard</code></td>
      <td style="text-align: center"><code class="language-plaintext highlighter-rouge">Linux</code></td>
      <td style="text-align: center"><code class="language-plaintext highlighter-rouge">#byPass #PHP #strcmp #id.so #reversing #ghidra #waf</code></td>
    </tr>
    <tr>
      <td style="text-align: left"><a href="https://www.hackingarticles.in/greenoptic-1-vulnhub-walkthrough/">GreenOptic: 1</a></td>
      <td style="text-align: center"><code class="language-plaintext highlighter-rouge">Hard</code></td>
      <td style="text-align: center"><code class="language-plaintext highlighter-rouge">Linux</code></td>
      <td style="text-align: center"><code class="language-plaintext highlighter-rouge">#LFI #wireshark #group</code></td>
    </tr>
    <tr>
      <td style="text-align: left"><a href="https://www.hackingarticles.in/presidential-1-vulnhub-walkthrough/">Presidential: 1</a></td>
      <td style="text-align: center"><code class="language-plaintext highlighter-rouge">Hard</code></td>
      <td style="text-align: center"><code class="language-plaintext highlighter-rouge">Linux</code></td>
      <td style="text-align: center"><code class="language-plaintext highlighter-rouge">#LFI #RCE #phpmyadmin #capabilities #tar</code></td>
    </tr>
    <tr>
      <td style="text-align: left"><a href="https://www.hackingarticles.in/tomato-1-vulnhub-walkthrough/">Tomato: 1</a></td>
      <td style="text-align: center"><code class="language-plaintext highlighter-rouge">Medium</code></td>
      <td style="text-align: center"><code class="language-plaintext highlighter-rouge">Linux</code></td>
      <td style="text-align: center"><code class="language-plaintext highlighter-rouge">#LFI #poison #RCE #ssh #log #CVE-2017-16995</code></td>
    </tr>
    <tr>
      <td style="text-align: left"><a href="https://www.hackingarticles.in/sunset-midnight-vulnhub-walkthrough/">Sunset: Midninght</a></td>
      <td style="text-align: center"><code class="language-plaintext highlighter-rouge">Medium</code></td>
      <td style="text-align: center"><code class="language-plaintext highlighter-rouge">Linux</code></td>
      <td style="text-align: center"><code class="language-plaintext highlighter-rouge">#WP #SUID #status #path #service</code></td>
    </tr>
    <tr>
      <td style="text-align: left"><a href="https://www.hackingarticles.in/sunset-twilight-vulnhub-walkthrough/">Sunset: Twilight</a></td>
      <td style="text-align: center"><code class="language-plaintext highlighter-rouge">Medium</code></td>
      <td style="text-align: center"><code class="language-plaintext highlighter-rouge">Linux</code></td>
      <td style="text-align: center"><code class="language-plaintext highlighter-rouge">#PHPF1 #shadow #file</code></td>
    </tr>
    <tr>
      <td style="text-align: left"><a href="https://www.hackingarticles.in/chili-1-vulnhub-walkthrough/">Chili: 1</a></td>
      <td style="text-align: center"><code class="language-plaintext highlighter-rouge">Easy</code></td>
      <td style="text-align: center"><code class="language-plaintext highlighter-rouge">Linux</code></td>
      <td style="text-align: center"><code class="language-plaintext highlighter-rouge">#FTP #write #abuse #passwd</code></td>
    </tr>
    <tr>
      <td style="text-align: left"><a href="https://www.hackingarticles.in/cewlkid-1-vulnhub-walkthrough/">Cewlkid: 1</a></td>
      <td style="text-align: center"><code class="language-plaintext highlighter-rouge">Medium</code></td>
      <td style="text-align: center"><code class="language-plaintext highlighter-rouge">Linux</code></td>
      <td style="text-align: center"><code class="language-plaintext highlighter-rouge">#SitemagicCMS #fileupload #cron #SUDO</code></td>
    </tr>
    <tr>
      <td style="text-align: left"><a href="https://www.hackingarticles.in/durian-1-vulnhub-walkthrough/">Durian: 1</a></td>
      <td style="text-align: center"><code class="language-plaintext highlighter-rouge">Hard</code></td>
      <td style="text-align: center"><code class="language-plaintext highlighter-rouge">Linux</code></td>
      <td style="text-align: center"><code class="language-plaintext highlighter-rouge">#LFI #RCE #log #poison #capabilities #gdb</code></td>
    </tr>
    <tr>
      <td style="text-align: left"><a href="https://www.hackingarticles.in/relevant-1-vulnhub-walkthrough/">Relevant: 1</a></td>
      <td style="text-align: center"><code class="language-plaintext highlighter-rouge">Medium</code></td>
      <td style="text-align: center"><code class="language-plaintext highlighter-rouge">Linux</code></td>
      <td style="text-align: center"><code class="language-plaintext highlighter-rouge">#WP #nmap #scripts #plugins #wp-file-manager #RCE #SUDO #node</code></td>
    </tr>
    <tr>
      <td style="text-align: left"><a href="https://www.hackingarticles.in/powergrid-1-0-1-vulnhub-walkthrough/">Powergrid: 1.0.1</a></td>
      <td style="text-align: center"><code class="language-plaintext highlighter-rouge">Hard</code></td>
      <td style="text-align: center"><code class="language-plaintext highlighter-rouge">Linux</code></td>
      <td style="text-align: center"><code class="language-plaintext highlighter-rouge">#Roundcube #RCE #PGP #Rsync #pivoting #SSH</code></td>
    </tr>
    <tr>
      <td style="text-align: left"><a href="https://www.hackingarticles.in/insanity-1-vulnhub-walkthrough/">Insanity: 1</a></td>
      <td style="text-align: center"><code class="language-plaintext highlighter-rouge">Hard</code></td>
      <td style="text-align: center"><code class="language-plaintext highlighter-rouge">Linux</code></td>
      <td style="text-align: center"><code class="language-plaintext highlighter-rouge">#wireshark #SQLi #SquirrelMail #Firefox</code></td>
    </tr>
    <tr>
      <td style="text-align: left"><a href="https://www.hackingarticles.in/tempus-fugit-3-vulnhub-walkthrough/">Tempus Fugit: 3</a></td>
      <td style="text-align: center"><code class="language-plaintext highlighter-rouge">Hard</code></td>
      <td style="text-align: center"><code class="language-plaintext highlighter-rouge">Linux</code></td>
      <td style="text-align: center"><code class="language-plaintext highlighter-rouge">#SSTI #SQLite #Processwire #OPT #Google #reversing #abuse #binary</code></td>
    </tr>
    <tr>
      <td style="text-align: left"><a href="https://www.hackingarticles.in/kb-vuln-3-vulnhub-walkthrough/">KB-Vulns: 3</a></td>
      <td style="text-align: center"><code class="language-plaintext highlighter-rouge">Easy</code></td>
      <td style="text-align: center"><code class="language-plaintext highlighter-rouge">Linux</code></td>
      <td style="text-align: center"><code class="language-plaintext highlighter-rouge">#smb #SiteMagicCMS #SETUID #systemctl</code></td>
    </tr>
    <tr>
      <td style="text-align: left"><a href="https://www.hackingarticles.in/cybox-1-vulnhub-walkthrough/">Cybox: 1</a></td>
      <td style="text-align: center"><code class="language-plaintext highlighter-rouge">Medium</code></td>
      <td style="text-align: center"><code class="language-plaintext highlighter-rouge">Linux</code></td>
      <td style="text-align: center"><code class="language-plaintext highlighter-rouge">#LFI #RCE #Apache #poison #SETUID #uncommon</code></td>
    </tr>
  </tbody>
</table>

<p><img src="imgs/offensivesecurity.png" width="250" align="center" /></p>

<table>
  <thead>
    <tr>
      <th style="text-align: left">Name</th>
      <th style="text-align: center">Level</th>
      <th style="text-align: center">OS</th>
      <th style="text-align: center">Tags</th>
    </tr>
  </thead>
  <tbody>
    <tr>
      <td style="text-align: left"><a href="https://m3n0sd0n4ld.github.io/OSC/DC5/">DC5</a></td>
      <td style="text-align: center"><code class="language-plaintext highlighter-rouge">Easy</code></td>
      <td style="text-align: center"><code class="language-plaintext highlighter-rouge">Linux</code></td>
      <td style="text-align: center"><code class="language-plaintext highlighter-rouge">#LFI #RCE #Nginx #log #poison #SETUID #screen</code></td>
    </tr>
  </tbody>
</table>

<p><img src="imgs/uam.png" width="200" align="center" /></p>

<table>
  <thead>
    <tr>
      <th style="text-align: left">Name</th>
      <th style="text-align: center">Level</th>
      <th style="text-align: center">OS</th>
      <th style="text-align: center">Tags</th>
    </tr>
  </thead>
  <tbody>
    <tr>
      <td style="text-align: left"><a href="https://github.com/m3n0sd0n4ld/writeups/blob/master/pdfs/UAM%20-%20El%20coche%20fant%C3%A1stico%20-%20Episodio%201.pdf">El coche fantástico</a></td>
      <td style="text-align: center"><code class="language-plaintext highlighter-rouge">Easy</code></td>
      <td style="text-align: center"><code class="language-plaintext highlighter-rouge">Linux</code></td>
      <td style="text-align: center"><code class="language-plaintext highlighter-rouge">#web #waf #xor #RCE</code></td>
    </tr>
  </tbody>
</table>

<hr />

<h2 id="articles">Articles</h2>
<ul>
  <li><a href="https://www.sothis.tech/capture-the-flag-aprende-hacking-jugando/">CTF: Aprende «hacking» jugando</a></li>
  <li><a href="https://www.sothis.tech/por-el-router-muere-el-pez/">Por el router muere el pez</a></li>
  <li><a href="https://www.sothis.tech/sistemas-de-control-industrial/">Ciberataques físicos: cuando el peligro está en un USB</a></li>
  <li><a href="https://www.sothis.tech/black-fraude-como-evitar-las-estafas-en-rebajas/">Black Fraude: cómo evitar las estafas en rebajas</a></li>
  <li><a href="https://www.sothis.tech/ciberseguridad-aplicada-al-coronavirus/">El Coronavirus, una excusa más para los ciberdelincuentes</a></li>
  <li><a href="https://www.hackplayers.com/2022/06/goofuzz-tool-enum-pasiva.html">GooFuzz: la herramienta para la enumeración de directorios y ficheros de forma pasiva</a></li>
  <li><a href="https://m3n0sd0n4ld.github.io/articles/Company-Recruitment-Management-System_1.0_Remote_Readable_Administrator_Credentials%20(Unauthenticated)/">Company’s Recruitment Management System 1.0 - Remote Readable Administrator Credentials (Unauthenticated)</a></li>
</ul>

<hr />
<h2 id="events--conferences">Events &amp; Conferences</h2>

<ul>
  <li><a href="https://vimeo.com/431392473">Interview: Digitalización industrial en CCI (Centro de Ciberseguridad Industrial)</a></li>
  <li><a href="https://t.co/dXTbGuI56n?amp=1">Conference: Voz de la industria sobre la integración de Redes IT/OT - Ciberseguridad Industrial</a></li>
  <li><a href="https://t.co/ZlkglPYsvN?amp=1">Conference: uDork - Google Hacking Tool - Hack&amp;Beers Remake vol 5</a></li>
  <li><a href="https://youtu.be/zzcUdmpo6ow">Conference: uDork - Google Hacking Tool v2.0 - BitUP 2020</a></li>
  <li><a href="https://youtu.be/efpL9KAW3Fo?t=33410">Conference: MailDay - Hackterriza como puedas - BitUP 2021</a></li>
  <li><a href="https://youtu.be/K1lTgYDF4lE">Conference: IES Rafael Alberti (Cádiz) - IoT Pentesting - 2022</a></li>
  <li><a href="https://www.twitch.tv/videos/1517579986">Conference: GooFuzz - Securiters Twitch- 2022</a></li>
</ul>

<hr />
<h2 id="about">About</h2>

<p>David Utón is Penetration Tester and security auditor for web and mobiles applications, perimeter networks, internal and industrial corporate infrastructures, and wireless networks.</p>

<h4 id="contacted-on">Contacted on:</h4>

<p><img src="imgs/linkedin.png" width="40" align="center" /> <a href="https://www.linkedin.com/in/david-uton/">David-Uton</a>
<img src="imgs/twitter.png" width="43" align="center" /> <a href="https://twitter.com/David_Uton">@David_Uton</a></p>

      </section>
    </div>

    <!-- FOOTER  -->
    <div id="footer_wrap" class="outer">
      <footer class="inner">
        
        <p>Published with <a href="https://pages.github.com">GitHub Pages</a></p>
      </footer>
    </div>
  </body>
</html>
