Title: PublicPacletServer
Authors: 
Categories: misc
Description: A beta version of a paclet for interfacing with the public paclet serverCurrent supports:  forking the server, submitting paclets, sending PRs,  cloning the server, and building the server
DisplayName: PublicPacletServer
Extensions: <|"Kernel" -> <|"Root" -> ".", "Context" -> {"PublicPacletServer`"}|>, "PacletServer" -> <|"Description" -> "A beta version of a paclet for interfacing with the public paclet server\nCurrent supports:\n  forking the server, submitting paclets, sending PRs,\n  cloning the server, and building the server"|>, "Resource" -> <|"Root" -> "Resources", "Resources" -> {"Templates", {"ExtraPacletInfo", "Templates/ExtraPacletInfo.wl"}, {"IncludedPaclets", "Templates/IncludedPaclets.wl"}}|>|>
Modified: 2019-01-16 10:49:45
Name: PublicPacletServer
Slug: publicpacletserver
Tags: 
Thumbnail: PacletIcon.png
Version: 0.0.11

<a id="publicpacletserver" class="Section" style="width:0;height:0;margin:0;padding:0;">&zwnj;</a>

# PublicPacletServer

![PublicPacletServer]({filename}/img/PublicPacletServer/PacletIcon.png)

A beta version of a paclet for interfacing with the public paclet server
Current supports:
  forking the server, submitting paclets, sending PRs,
  cloning the server, and building the server

---

<a id="install" class="Subsection" style="width:0;height:0;margin:0;padding:0;">&zwnj;</a>

## Install

**Before installing, be sure to check out the ** **[Change Log](https://paclets.github.io/PacletServer/pages/log.html)** ** to make sure that you trust the developer.**

To install this paclet, run:

    << https://paclets.github.io/PacletServer/Install.wl
    PublicPacletInstall["PublicPacletServer"]

*  To update it, replace  `PublicPacletInstall` with  `PublicPacletUpdate` . 

---

<a id="basicinformation" class="Subsection" style="width:0;height:0;margin:0;padding:0;">&zwnj;</a>

## Basic Information

<a id="name" class="Subsubsection" style="width:0;height:0;margin:0;padding:0;">&zwnj;</a>

###Name

PublicPacletServer

<a id="version" class="Subsubsection" style="width:0;height:0;margin:0;padding:0;">&zwnj;</a>

###Version

0.0.11

---

<a id="extrainformation" class="Subsection" style="width:0;height:0;margin:0;padding:0;">&zwnj;</a>

## Extra Information

This package provides no extra information

---

<a id="extensions" class="Subsection" style="width:0;height:0;margin:0;padding:0;">&zwnj;</a>

## Extensions

<a id="kernel" class="Subsubsection" style="width:0;height:0;margin:0;padding:0;">&zwnj;</a>

###Kernel

*  Root: .

*  Context: PublicPacletServer`

<a id="resource" class="Subsubsection" style="width:0;height:0;margin:0;padding:0;">&zwnj;</a>

###Resource

*  Root: Resources

*  Resources

  *  `Templates`

  *  `{ExtraPacletInfo, Templates/ExtraPacletInfo.wl}`

  *  `{IncludedPaclets, Templates/IncludedPaclets.wl}`