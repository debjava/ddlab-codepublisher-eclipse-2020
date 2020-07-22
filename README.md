![DDLAB](./images/A22.png) 

CodePublisher An Eclipse Plugin to publish code in GitHub, GitLab or Bitbucket
==========================================================================================

Introduction
============
**Code Publisher** is an eclipse plugin which helps in publishing and sharing the complete codebase or code snippet directly to GitHub, GitLab or Bitbucket.  This plugin does not provide any git functionality, it only provides an easy way to keep the code in [GitHub.com](https://github.com/), [GitLab.com](https://gitlab.com/) or [Bitbucket.com](https://bitbucket.org/) for future references. Many times, developers write good code for some POC and code goes into lost world after some time. This plugin will help you to save and share your code in GitHub, GitLab or Bitbucket.


Advantages of Code Publisher
============================

* **A hassle free way to publish code base in [GitHub.com](https://github.com/), [GitLab.com](https://gitlab.com/) or [Bitbucket.com](https://bitbucket.org/).**
* **Easy to create a code snippet and share with your friends.**
* **A non blocking way to publish the code or code snippet.**
* **Easy to work as it has been developed using pure java and it is free and open source.**

Technology Stack
================
The following framework/s and tool/s have been used in this current sample application.

<table border="1">
  <tr>
    <th>Name</th>
    <th>Version</th> 
  </tr>
  <tr>
    <td>Java</td>
    <td>1.8</td> 
  </tr>
  <tr>
    <td>Eclipse framework (SWT & JFace) with Oxygen</td>
    <td>3.0.9</td> 
  </tr>
  <tr>
    <td>Eclipse tycho</td>
    <td>1.2.0</td> 
  </tr>
  <tr>
    <td>Eclipse eGit framework</td>
    <td>5.2</td> 
  </tr>
  <tr>
    <td>Apache Maven</td>
    <td>3.6.3</td> 
  </tr>
</table>

How to use it ?
===============
Install using the below button.

<table style="border: none; width:100%">
  <tbody>
    <tr style="border:none;">
      <td style="vertical-align: middle; padding-top: 10px; border: none;">
        <a href="https://dl.bintray.com/debajava/codepublisher/" title="Drag and drop onto a running Eclipse Main Toolbar to install CodePublisher plugin">
          <img src="./images/installbutton.png">
        </a>
      </td>
      <td style="vertical-align: middle; text-align: left; border: none;">
        ← Drag it to your eclipse workbench to install!</td>
    </tr>
  </tbody>
</table>

or 

use `https://dl.bintray.com/debajava/codepublisher/` in Help -> Install New Software ... Dialog.

or

Please Download [<img src="./images/download32.png">](https://dl.bintray.com/debajava/eclipseplugins/codepublisher/ddlab.codepublisher.updatesite-1.2.0.zip) latest zip file directly or you can also download from the **download** directory of this repository.

Download the zip file and install as in Help -> Install New Software -> Add... -> Archive... Dialog.

See the screenshots give below to know its usage.

* **To create a project in GitHub/GitLab/Bitbucket**

![DDLAB](./images/1.png)

![DDLAB](./images/2.png)

* **To create a Gist in GitHub or Snippet in GitLab or Bitbucket**

![DDLAB](./images/3.png)

![DDLAB](./images/4.png)


How to build this project
=========================
This is an eclipse plugin development project developed using java 1.8. Follow the steps mentioned below.

* Clone the project or simply download the project and unzip it.
* Go to the directory in command prompt.
* Use the command `mvnw clean package`.
* **Download** folder contains the installable plugin as a zip file..
* **latest-2020** contains the installable plugin.


Bugs and Feedback
=================
There may be some bugs or error, please feel free to report to me at deba.java@gmail.com

Contributor
==========
@Author : **Debadatta Mishra (PIKU)** [Know me](https://about.me/debadattamishra)

Conclusion
==========
Hope you have enjoyed my small utility plugin, try to learn and explore more and share with all.

![DDLAB](./images/dd-logo.png)
