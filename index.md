---
layout: default
---

Text can be **bold**, _italic_, ~~strikethrough~~ or `keyword`.

[Link to another page](./another-page.html).

There should be whitespace between paragraphs.

There should be whitespace between paragraphs. We recommend including a README, or a file with information about your project.

# Header 1
# 9t0wl Hacks

  PermX: My First Steps into Web Exploitation and Privilege Escalation

Introduction

My journey into the world of ethical hacking recently led me to tackle the PermX machine on Hack The Box.  Labeled as "Easy," I was eager to test my skills and see what I could learn. Little did I know, this machine would provide a solid foundation in essential web exploitation and privilege escalation techniques.

Reconnaissance and Enumeration

As with any good hack, I started with reconnaissance.  Firing up Nmap, I scanned the machine to identify open ports and services. I also used Gobuster to brute-force directories, hoping to uncover any hidden gems. This phase reminded me of the importance of thoroughness; even seemingly insignificant details can lead to a breakthrough.

Exploitation

The real excitement began when I discovered a vulnerability in a web application running on the machine. Careful analysis revealed a weakness in the file upload functionality.  With a bit of tinkering and the help of Burp Suite, I was able to craft a malicious file and gain initial access to the system. This was a thrilling moment, a tangible reminder of the impact web application vulnerabilities can have.

Privilege Escalation

Gaining a foothold was just the first step.  The next challenge was to elevate my privileges to root. This involved meticulously examining the system for misconfigurations or vulnerable services.  After some digging, I discovered a SUID binary that could be exploited. With a carefully crafted exploit, I was able to gain the coveted root access. This phase taught me the importance of persistence and creative thinking when it comes to privilege escalation.

Lessons Learned

PermX, though considered "Easy," provided a wealth of learning opportunities.  I gained hands-on experience with essential tools like Nmap and Burp Suite, and I honed my skills in web application exploitation and privilege escalation. This machine reinforced the importance of thoroughness, persistence, and creative problem-solving in the world of ethical hacking.

  Jerry: Unveiling the Power of Apache Tomcat Vulnerabilities

Introduction

My encounter with the Jerry machine on Hack The Box marked my first foray into the world of Apache Tomcat vulnerabilities.  This "Easy" rated machine proved to be an excellent introduction to the potential security risks associated with this popular web server.

Web Server Enumeration

The initial phase involved identifying the web server and its version. Using Nmap and some clever banner grabbing techniques, I was able to confirm that Apache Tomcat was running on the target machine.  This step highlighted the importance of gathering information about the target environment before launching an attack.

Exploiting Tomcat Vulnerabilities

Armed with the knowledge of the web server, I delved into researching known vulnerabilities in Apache Tomcat.  I discovered a specific CVE that seemed promising.  With the help of Metasploit, I was able to craft an exploit and gain initial access to the system. This experience underscored the critical need to stay up-to-date on the latest vulnerabilities and their potential impact.

Web Shell Deployment & Privilege Escalation

Once I had a foothold, I deployed a web shell to maintain access and further explore the system.  From there, it was a matter of identifying and exploiting misconfigurations or vulnerable services to escalate my privileges to root. This machine reinforced the importance of post-exploitation techniques and the continuous pursuit of higher privileges.

Lessons Learned

Jerry provided a valuable introduction to the world of Apache Tomcat security. I learned how to identify and exploit vulnerabilities in this widely used web server, and I gained a deeper appreciation for the importance of staying informed about the latest security threats.

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

![Octocat](https://github.githubassets.com/images/icons/emoji/octocat.png)

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
