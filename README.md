Nonprofit Starter Pack Unmanaged
================================

The Nonprofit Starter Pack (NPSP) is available as 5 managed packages.
This is a compilation of all the code in unmanaged form.

For more information go to http://nonprofitstarterpack.org

Installation
---

This code can be deployed into a Salesforce organization using Eclipse or Ant.

Alternately, you can use the following procedures if you have Eclipse and eGit installed:
- Get a new DE Org from developer.force.com
- Fork the NPSP-UM repository on Github
- Create a local blank project in Eclipse
- Add a git repository to the project
- Configure the local repository to point to your NPSP-UM repository on Github
- Fetch from your forked copy of the NPSP-UM Repository
- Do a hard reset of your local repo to your fetched repo so your commits are lined up
- Add the force.com nature, do not overwrite!
- Save objects and labels to your DE org
- Save all other items to your DE org
- Hack.


Other Important Information
---

There are some minor differences between NPSP-UM and the base packages.  
Primarily these relate to elements that only appear in managed environments such as Package.Version.Request.
There should be no effect from these differences on the functionality of your NPSP instance.


Meta
----

Released under the [BSD license](http://www.opensource.org/licenses/BSD-3-Clause).