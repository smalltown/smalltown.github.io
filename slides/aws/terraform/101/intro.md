name: Mastering Infrastructure as Code Workshop
class: center
![:scale 60%](images/intro/tf_aws.png)
<br><br>
# Mastering Infrastructure as Code Workshop
### Build AWS Resources with Infrastructure as Code
???
<!---
Mastering Infrastructure as Code Workshop
Build AWS Resources with Infrastructure as Code

This slide presentation is stored as Markdown code, specifically using the RemarkJS engine to render it. All standard markdown tags are supported, and you can also use some HTML within this document.

If you need to change the look and feel of the slide deck just use the style.css and remark_settings.js files to suit your needs. The content in this file is picked up by index.html when the page is loaded.

HTML comments like this one will show up in the source code, but not in the slides or speaker notes.
--->

Welcome to the beginner's guide to Terraform on AWS. This slide deck is written entirely in Markdown language, which means you can make edits or additions, then submit a pull request to add your changes to the master copy. To make edits to the slide deck simply fork this repository, edit the Markdown files, and submit a pull request with your changes.

The Markdown content is contained in the docs/ subdirectories.

Here are some helpful keyboard shortcuts for the instructor or participant:

⬆ ⬇ ⬅ ➡ - Navigate back and forth
P         - Toggle presenter view
C         - Pop an external window for presentation

Instructor notes are included in plain text, narrative parts are in **bold**. You can use the narrative quotes or change them to suit your own presentation style.

---
name: Link-to-Slide-Deck
# The Slide Deck
<br><br><br>
Follow along on your own computer at this link:

### <https://git.io/>

---
name: Introduction
class: img-right-full

![](images/intro/profile.png)

# Hello!
## I am smalltown
  - MaiCoin Lead Site Reliability Engineering
  - Taipei HashiCorp User Group Organizer
  - AWS User Group Taiwan Staff
<br><br><br>
![:scale 100%](images/intro/profile-org.png)


???
Use this slide to introduce yourself, give a little bit of your background story, then go around the room and have all your participants introduce themselves.

The favorite text editor question is a good ice breaker, but perhaps more importantly it gives you an immediate gauge of how technical your users are.

**There are no wrong answers to this question. Unless you say Notepad. Friends don't let friends write code in Notepad.**

**If you don't have a favorite text editor, that's okay! Our cloud lab has Visual Studio Code preinstalled. VSC is a free programmer's text editor for Microsoft, and it has great Terraform support. Most of this workshop will be simply copying and pasting code, so if you're not a developer don't fret. Terraform is easy to learn and fun to work with.**

---
name: IaC Day 1
# IaC Day 1

1. Intro to Terraform<br>
2. Terraform Basics<br>
👩‍🔬 **Lab - Setup and Basic Usage**<br>
3. Terraform In Action<br>
🧪 **Lab - Terraform in Action**<br>
4. Provision and Configure AWS Instances<br>
🔬 **Lab - Provisioning with Terraform**<br>
5. Manage and Change Infrastructure State<br>

???
This workshop should take roughly three hours to complete.

**Here is our agenda for today's training. The format is simple, you'll hear a lecture and view slides on each topic, then participate in a hands-on lab about that topic. We'll alternate between lecture and lab, with a couple of breaks thrown in.**

---
name: IaC Day 2
class: col-2
# IaC Day 2

<div>
1. OSS to Cloud/Enterprise<br>
🌥️ Terraform Cloud Overview<br>
👨🏽‍🏫 Review the Basics<br>
🔗 Configure Remote State<br>
<hr>
2. Security and RBACs<br>
🔐 Protect Sensitive Variables<br>
🛡️ Work With Access Controls<br>
<hr>
3. VCS & Policy Enforcement<br>
🕸️ Connect to VCS<br>
👬 Collaboration with VCS<br>
👮 Sentinel Policy Enforcement<br>
<hr>
4. Terraform Modules & API<br>
⚙️ Private Module Registry<br>
🏗️ API Driven Workflows<br>
<hr>
5. Extra Resources<br>
⚗️ Bonus Lab<br>
🌐 Useful Links
</div>

???
**This is our table of contents. We have a lot of ground to cover today. The workshop will alternate between lecture and lab exercise so we don't get bored and fall asleep. We'll be taking breaks roughly every 90 minutes, with a 45 minute break for lunch.**

Make sure your EAM or sponsor have arranged for lunch if presenting this as a full-day workshop.