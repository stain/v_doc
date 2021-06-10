# v_doc

This repository is a snapshot of [Netlab's Voyager Documentation](http://trac.netlabs.org/v_doc) and is **no longer maintained**.

You may also need:

* https://github.com/stain/v_nom/
* https://github.com/stain/v_desktop/
* https://github.com/stain/v_triton/
* https://github.com/stain/v_doc/

## License/copyright

License and copyright was not explicit across the original source repository, but where in-line, is indicated as Dual-license CDDL 1.0/LGPL 2.1, e.g.:

```
/* ***** BEGIN LICENSE BLOCK *****
* Version: CDDL 1.0/LGPL 2.1
*
* The contents of this file are subject to the COMMON DEVELOPMENT AND
* DISTRIBUTION LICENSE (CDDL) Version 1.0 (the "License"); you may not use
* this file except in compliance with the License. You may obtain a copy of
* the License at http://www.sun.com/cddl/
*
* Software distributed under the License is distributed on an "AS IS" basis,
* WITHOUT WARRANTY OF ANY KIND, either express or implied. See the License
* for the specific language governing rights and limitations under the
* License.
*
* The Original Code is "NOM" Netlabs Object Model
*
* The Initial Developer of the Original Code is
* netlabs.org: Chris Wohlgemuth <cinc-ml@netlabs.org>.
* Portions created by the Initial Developer are Copyright (C) 2005-2007
* the Initial Developer. All Rights Reserved.
*
* Contributor(s):
*
* Alternatively, the contents of this file may be used under the terms of
* the GNU Lesser General Public License Version 2.1 (the "LGPL"), in which
* case the provisions of the LGPL are applicable instead of those above. If
* you wish to allow use of your version of this file only under the terms of
* the LGPL, and not to allow others to use your version of this file under
* the terms of the CDDL, indicate your decision by deleting the provisions
* above and replace them with the notice and other provisions required by the
* LGPL. If you do not delete the provisions above, a recipient may use your
* version of this file under the terms of any one of the CDDL or the LGPL.
*
* ***** END LICENSE BLOCK ***** */
```

Documentation adapted from <http://trac.netlabs.org/v_doc>:

# Voyager Documentation

This is the entry point for the documentation of Voyager, right now this mainly consists of the [Design of Voyager](http://voyager.netlabs.org). But that will hopefully get much more later.

You can browse the XML files [here](DOV/).

## What is Voyager?

Voyager is the codename for the idea of reimplementing key technologies of OS/2 and its successor eComStation on top of modern technology. It basically reimplements the Workplace Shell and some other parts of the OS/2 platform. Please read the [http://wiki.netlabs.org/index.php/Voyager_FAQ Voyager FAQ] for more.

So far Voyager is nothing you can see or use yet. We invest a lot of time into the design of this project and for various reasons we decided to do the core-parts of the design in private with a rather small group of people. Right now we are working on proof-of-concept code to show that the idea works out like we plan it. Later we will do a prototype that will be released to the public as well as soon as we think it is ready for it.

## Voyager in a few words (for the /. crowd :)

This page got [linked in Slashdot](http://slashdot.org/articles/08/01/22/0258213.shtml), that's not a problem but we are not at a stage where we wanted that much publicity yet :) So we would like to add some more explanation in a few words here: 

* Voyager will not be a full featured operating system. Think of it like a full object oriented workplace that will use the underlying operating system for interaction with what users need.
* Voyager will be portable. A first incarnation will probably appear on normal desktop PCs but the design will permit to use it on new devices as well like mobile phones, PDAs or even game consoles.
* Voyager will work for upcoming input devices as well. Keyboard and mouse were designed in the 80ies, upcoming workplaces need real support for new things like multitouch displays.
* Voyager will use its own object model. Heavily influenced by IBMs SOM (System Object Model) this will allow us to create wrappers to many existing languages and still keep the full flexibility of our design. Our objects will be binary compatible unlike about every other model used nowadays on desktop environments. See the FAQ for more information about that.
* Voyager will be documented. If you ever tried to code something on a free desktop environment you know what we mean...

We know that our pages look rather boring right now but we will try to change that the next months. Once we have prototypes available we will announce that on the well known channels again, with a bit of luck even Slashdot will pick it up as well. So make sure to visit us again later :)

## Design of Voyager

We already started to discuss the design for Voyager, see the [Voyager Wiki](http://wiki.netlabs.org/index.php/Voyager) for details. It contains details on the design and first thoughts on an Implementation and Design Guide.

Unlike many other ideas before we try to implement the absolute minimum necessary to reach our goal. That means we will implement our concept on top of existing and widely used open source technology. This makes sure that we can concentrate on the interesting parts of the concept instead of loosing time with things which were already done by other programmers.

Please note that the public available documentation does not resemble the current state of the project, there is internal documentation as well which will be released to the public with the prototype of the project. 

## Take part

You can take part in the discussion of Voyager Design and other issues. Please join the [Voyager mailing list](http://dir.gmane.org/gmane.org.netlabs.voyager.devel) or #netlabs IRC channel.

Even if the core-team is rather small we appreciate constructive feedback to our project! 
