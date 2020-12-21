Tools:

Git/GitHub:  The core tool is git and GitHub.  We will work via repos - as developers work.  This will evolve as we work. Git is the basic technology, open source, originated by Linus Torvalds and used by the open source community and increasingly by everyone else.  Git repos allow very clear collaboration, versioning, divergence (forking), convergence (merging), and modularity (in a number of ways).

Visual Studio Code:  There is a very large choice of editors that work OK for text projects like Prose Objects.  The web interface at GitHub allows easy direct editing of one file at a time.  But for major work, it is very helpful to be able to manage and navigate between multiple files.  VS Code is one widely-used tool.  It lets you edit a bunch of different files, and has built in the git cycle of stage, commit, push-pull.   (BTW, watch out when installing not to confuse with Visual Studio <strike>Code</strike>.  That is something else.

Local Web Install:  It will often be helpful to see your work rendered into full documents. This is more than satisfying, it often identifies errors, and there are a couple of tools built into even the current implementation that can make big authoring jobs quicker and more consistent.  A local install requires a web server and the software languages PHP and perl.  (We expect this will be replaced as we code a new parser.)  These technologies are on many laptops, but I have found it easiest to install a package called MAMP, and configure it.  After getting a webserver running, you can download any of a variety of the basic software for Prose Objects, at Github.com/CommonAccord.

Public Deployment:  We currently use Heroku to present the materials as a website.  Heroku deploys a new version of the website each time the GitHub repo is updated.  We currently have a problem that that perl/PHP code is inefficient and perhaps has a memory leak such that the Heroku platform is overloaded by very large, granular documents.  Things that run fine (though very slowly) locally will crash the public sites.  Finding another hosting solution would be helpful.  Recoding the cmacc-app would be even more helpful.  A group at Brown University did a Python version that was much faster and more efficient, but remains command-line.  https://github.com/adonalsium/common_accord/tree/dev  (It may also not be entirely lazy?) That group also formalized the Record format as a map of Key=Values and an ordered list of Prefix.=[Links]. (The order of the links is important.)

**see comment**

VS Code plug-in:  It would be great to have basic rendering available as a VS Code plug-in.  (In a variant version, we briefly had that experience https://github.com/CommonAccord/cmacc-vscode.)



