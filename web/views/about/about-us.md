---
layout: page
title: About
nav_title: About
menu_title: About Us
type: about
weight: 8
permalink: /about/about-us/
---

**QuickFIX/n implements the [FIX protocol][5] on .NET.** 

QuickFIX/n is 100% free and open source with a liberal [license][4].

Comparisons to QuickFIX
-----------------------
QuickFIX/n is a .NET port of [QuickFIX][0], an open source C++ FIX engine.

We love QuickFIX.  We have been contributors nearly since its
conception and use it heavily in our products and consulting.

The goal of QuickFIX/n is to create an open source FIX engine that feels
native to C#.  The (C++) QuickFIX project maintains a C# wrapper 
which has been used successfully in .NET for many years, but it results
in code that is not idiomatic of .NET development.  QuickFIX/n
attempts to keep the same robustness and conformance of QuickFIX
with a similar API while bringing native performance and idiomatic 
usage to .NET.

For Java development, please visit the excellent [QuickFIX/J][1].

QuickFIX/n uses the QuickFIX name with the full backing and support of QuickFIX 
and its creator Oren Miller.

Commercial Backing
------------------
Work on QuickFIX/n is sponsored by Connamara.

[![Connamara][3]][2]

In addition to launching and supporting the QuickFIX/n initiative, Connamara 
has been involved with the QuickFIX project since its inception. Today, 
Connamara is an active maintainer of QuickFIX and a contributor to the 
QuickFIX/J project. Connamara also offers a commercial version of QuickFIX/J 
that exhibits dramatically lower latencies and variance.

About the Name...
-----------------
This project's correct and proper name is "QuickFIX/n".

It is true that the "n" was inspired by ".NET", but the word "net"
is NOT part of the name and should never be written as such.

[0]: http://quickfixengine.org
[1]: http://quickfixj.org
[2]: http://connamara.com
[3]: {{ site.github.url }}/web/public/images/Connamara-Logo.png
[4]: https://github.com/connamara/quickfixn/blob/master/LICENSE
[5]: http://fixprotocol.org
