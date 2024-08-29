---
layout: default
---

Text can be **bold**, _italic_, ~~strikethrough~~ or `keyword`.

[Link to another page](./another-page.html).

There should be whitespace between paragraphs.

There should be whitespace between paragraphs. We recommend including a README, or a file with information about your project.

![Spidertocat](inspectocat.resized.jpg)
# 9t0wl Hack's;


#   PermX: My First Steps into Web Exploitation and Privilege Escalation

**Introduction**

My journey into the world of ethical hacking recently led me to tackle the PermX machine on Hack The Box.  Labeled as "Easy," I was eager to test my skills and see what I could learn. Little did I know, this machine would provide a solid foundation in essential web exploitation and privilege escalation techniques.

**Reconnaissance and Enumeration**

As with any good hack, I started with reconnaissance.  Firing up Nmap, I scanned the machine to identify open ports and services. I also used Gobuster to brute-force directories, hoping to uncover any hidden gems. This phase reminded me of the importance of thoroughness; even seemingly insignificant details can lead to a breakthrough.

**Exploitation**

The real excitement began when I discovered a vulnerability in a web application running on the machine. Careful analysis revealed a weakness in the file upload functionality.  With a bit of tinkering and the help of Burp Suite, I was able to craft a malicious file and gain initial access to the system. This was a thrilling moment, a tangible reminder of the impact web application vulnerabilities can have.

**Privilege Escalation**

Gaining a foothold was just the first step.  The next challenge was to elevate my privileges to root. This involved meticulously examining the system for misconfigurations or vulnerable services.  After some digging, I discovered a SUID binary that could be exploited. With a carefully crafted exploit, I was able to gain the coveted root access. This phase taught me the importance of persistence and creative thinking when it comes to privilege escalation.

**Lessons Learned**

PermX, though considered "Easy," provided a wealth of learning opportunities.  I gained hands-on experience with essential tools like Nmap and Burp Suite, and I honed my skills in web application exploitation and privilege escalation. This machine reinforced the importance of thoroughness, persistence, and creative problem-solving in the world of ethical hacking.

#   Jerry: Unveiling the Power of Apache Tomcat Vulnerabilities

**Introduction**

My encounter with the Jerry machine on Hack The Box marked my first foray into the world of Apache Tomcat vulnerabilities.  This "Easy" rated machine proved to be an excellent introduction to the potential security risks associated with this popular web server.

**Web Server Enumeration**

The initial phase involved identifying the web server and its version. Using Nmap and some clever banner grabbing techniques, I was able to confirm that Apache Tomcat was running on the target machine.  This step highlighted the importance of gathering information about the target environment before launching an attack.

**Exploiting Tomcat Vulnerabilities**

Armed with the knowledge of the web server, I delved into researching known vulnerabilities in Apache Tomcat.  I discovered a specific CVE that seemed promising.  With the help of Metasploit, I was able to craft an exploit and gain initial access to the system. This experience underscored the critical need to stay up-to-date on the latest vulnerabilities and their potential impact.

**Web Shell Deployment & Privilege Escalation**

Once I had a foothold, I deployed a web shell to maintain access and further explore the system.  From there, it was a matter of identifying and exploiting misconfigurations or vulnerable services to escalate my privileges to root. This machine reinforced the importance of post-exploitation techniques and the continuous pursuit of higher privileges.

**Lessons Learned**

Jerry provided a valuable introduction to the world of Apache Tomcat security. I learned how to identify and exploit vulnerabilities in this widely used web server, and I gained a deeper appreciation for the importance of staying informed about the latest security threats.

#   Greenhorn: My Initiation into the World of Linux Privilege Escalation

**Introduction**

As I continued my journey through Hack The Box, I encountered the Greenhorn machine. Aptly named, this "Easy" rated machine served as my initiation into the fascinating world of Linux privilege escalation.

**Enumeration and Foothold**

The initial phase involved the usual reconnaissance. With Nmap as my trusty companion, I mapped out the machine's open ports and services. I also meticulously analyzed the web server, looking for any clues or potential vulnerabilities.  This careful probing, aided by tools like Dirb or Nikto, led me to a weakness in the server configuration, allowing me to gain an initial foothold on the system.

**Privilege Escalation: The Real Challenge**

Gaining initial access was merely the first step. The real challenge lay in escalating my privileges to root. This involved carefully examining the system for any misconfigurations, vulnerable services, or exploitable SUID binaries. I utilized LinEnum to enumerate potential privilege escalation vectors. Greenhorn truly put my Linux knowledge to the test, forcing me to dig deep into file permissions, system configurations, and potential privilege escalation paths.

After some persistence and careful analysis, I discovered a subtle misconfiguration that allowed me to elevate my privileges and seize control of the system. This breakthrough highlighted the importance of attention to detail and understanding the nuances of the Linux operating system.

**Lessons Learned**

Greenhorn, while relatively straightforward, provided an invaluable learning experience. I gained a deeper understanding of Linux privilege escalation techniques and the importance of thorough system enumeration. This machine also reinforced the value of persistence and the satisfaction of overcoming challenges. It solidified my understanding of essential tools like Nmap, and introduced me to powerful enumeration tools like LinEnum.

#   Pickle Rick: Wubba Lubba Dub Dub into Windows Privilege Escalation

**Introduction**

My latest adventure on TryHackMe took me into the quirky world of Pickle Rick, a machine designed to teach us the art of Windows privilege escalation.  With its "Easy" rating, I was ready to dive in and see what challenges awaited.

**Enumeration and Initial Access**

As always, I started with thorough enumeration using trusty tools like Nmap.  Port scanning revealed several open ports, including the ever-present Remote Desktop Protocol (RDP). A bit of further probing led me to discover weak credentials for a user account, granting me my initial access to the machine.

**Privilege Escalation: Getting Schwifty**

Gaining a foothold was just the beginning. The true test lay in escalating my privileges to the coveted SYSTEM level.  Pickle Rick threw some interesting curveballs my way, forcing me to explore various privilege escalation techniques specific to Windows environments.

I carefully examined the system for misconfigurations, vulnerable services, and potential exploit opportunities. Using tools like WinPEAS and PowerUp, I meticulously searched for any weaknesses that I could leverage. Eventually, I stumbled upon a juicy kernel exploit that allowed me to elevate my privileges and achieve SYSTEM access.

**Lessons Learned**

Pickle Rick was more than just a fun pop-culture reference; it provided a valuable learning experience in the world of Windows privilege escalation. I gained hands-on experience with essential tools like WinPEAS and PowerUp, and I learned how to identify and exploit common misconfigurations in Windows environments.  This machine reminded me that even seemingly secure systems can have hidden vulnerabilities, waiting to be discovered by a persistent and resourceful attacker.

## Header 2

> This is a blockquote following a header.
>
> When something is important enough, you do it even if the odds are not in your favor.

### Header 3

```js
// Javascript code with syntax highlighting.
var fun = function lang(l) {
  dateformat.i18n = require('./lang/' + l)
  return true;
}
```

```ruby
# Ruby code with syntax highlighting
GitHubPages::Dependencies.gems.each do |gem, version|
  s.add_dependency(gem, "= #{version}")
end
```

#### Header 4

*   This is an unordered list following a header.
*   This is an unordered list following a header.
*   This is an unordered list following a header.

##### Header 5

1.  This is an ordered list following a header.
2.  This is an ordered list following a header.
3.  This is an ordered list following a header.

###### Header 6

| head1        | head two          | three |
|:-------------|:------------------|:------|
| ok           | good swedish fish | nice  |
| out of stock | good and plenty   | nice  |
| ok           | good `oreos`      | hmm   |
| ok           | good `zoute` drop | yumm  |

### There's a horizontal rule below this.

* * *

### Here is an unordered list:

*   Item foo
*   Item bar
*   Item baz
*   Item zip

### And an ordered list:

1.  Item one
1.  Item two
1.  Item three
1.  Item four

### And a nested list:

- level 1 item
  - level 2 item
  - level 2 item
    - level 3 item
    - level 3 item
- level 1 item
  - level 2 item
  - level 2 item
  - level 2 item
- level 1 item
  - level 2 item
  - level 2 item
- level 1 item

### Small image

![Octocat](hBt_L6.gif)

### Large image

![Branching](DALL·E 2024-08-28 11.36.40 bugbounty.jpg)


### Definition lists can be used with HTML syntax.

<dl>
<dt>Name</dt>
<dd>Herry Hernandez</dd>
<dt>Birthplace</dt>
<dd>California</dd>
<dt>Color</dt>
<dd>Green</dd>
</dl>

```
Long, single-line code blocks should not wrap. They should horizontally scroll if they are too long. This line should be long enough to demonstrate this.
```

```
The final element.
```
