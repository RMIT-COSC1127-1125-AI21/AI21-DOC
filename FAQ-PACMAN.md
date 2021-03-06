# FAQ - Pacman Projects - RMIT AI 2021

This is a FAQ for the project assessments only (i.e., Pacman assessment projects).

For general questions about the course, refer to the other FAQs available under [Resources](https://edstem.org/courses/6081/resources).

As any FAQ page, this page is always "under construction". As we realize that some questions become common, we add them here. So, bookmark it and check it regularly, particularly when you have a doubt and you suspect it may have been answered before!

- [FAQ - Pacman Projects - RMIT AI 2021](#faq---pacman-projects---rmit-ai-2021)
- [GENERAL](#general)
  - [In a code assignment/project, how do I make sure I do not go against academic integrity?](#in-a-code-assignmentproject-how-do-i-make-sure-i-do-not-go-against-academic-integrity)
  - [Cannot access the Google Form, says I need permission](#cannot-access-the-google-form-says-i-need-permission)
  - [I submitted wrongly (e.g., didn't tag correctly) and is now after the due date, can you consider my submission?](#i-submitted-wrongly-eg-didnt-tag-correctly-and-is-now-after-the-due-date-can-you-consider-my-submission)
  - [Project specification says "You should code your implantation only at the locations ...." . Does this mean that we can't create our custom classes outside the provided functions?](#project-specification-says-you-should-code-your-implantation-only-at-the-locations---does-this-mean-that-we-cant-create-our-custom-classes-outside-the-provided-functions)
  - [How do I zip files in folder X without including the folder X itself?](#how-do-i-zip-files-in-folder-x-without-including-the-folder-x-itself)
  - [The autograder says _"Your grades are NOT yet registered."_ What should I do to register?](#the-autograder-says-your-grades-are-not-yet-registered-what-should-i-do-to-register)
  - [Should I pass all the autograder tests?](#should-i-pass-all-the-autograder-tests)
- [GIT & GITHUB](#git--github)
  - [Git, GitHub, what is that?](#git-github-what-is-that)
  - [How do I submit my project solution in my GIT repository?](#how-do-i-submit-my-project-solution-in-my-git-repository)
  - [How do I change the submission tag if I have already tagged one commit for submission?](#how-do-i-change-the-submission-tag-if-i-have-already-tagged-one-commit-for-submission)
  - [Cannot clone or push to GitHub with my password credentials?](#cannot-clone-or-push-to-github-with-my-password-credentials)
  - [I have committed to the remote repo but I am not listed as a "contributor", why?](#i-have-committed-to-the-remote-repo-but-i-am-not-listed-as-a-contributor-why)
  - [Commits not correctly associated to my GitHub account, why?](#commits-not-correctly-associated-to-my-github-account-why)
- [PYTHON](#python)
  - [What version of Python should I use?](#what-version-of-python-should-i-use)
  - [How do I run Python 3.6 in `coreteachingXX.csit.rmit.edu.au`??](#how-do-i-run-python-36-in-coreteachingxxcsitrmiteduau)
  - [How do I know the type of a variable in Python?](#how-do-i-know-the-type-of-a-variable-in-python)
  - [AttributeError: module 'importlib' has no attribute 'util'](#attributeerror-module-importlib-has-no-attribute-util)
- [GENERAL PACMAN](#general-pacman)
  - [What is the best way to develop my solutions for the Pacman project?](#what-is-the-best-way-to-develop-my-solutions-for-the-pacman-project)
  - [How to run Pacman remotely from `coreteaching`?](#how-to-run-pacman-remotely-from-coreteaching)
  - [Coreteaching? What is that?](#coreteaching-what-is-that)
  - [How do I setup a system in Windows with Python 3.6?](#how-do-i-setup-a-system-in-windows-with-python-36)
  - [Can I use `problem._visited`?](#can-i-use-problem_visited)
  - [I get "`_tkinter.TclError: no display name and no $DISPLAY environment variable`" error when running in WSL or ssh](#i-get-_tkintertclerror-no-display-name-and-no-display-environment-variable-error-when-running-in-wsl-or-ssh)
  - [Cannot run Pacman due to problems with Tkinter: "`ImportError: No module named Tkinter`"](#cannot-run-pacman-due-to-problems-with-tkinter-importerror-no-module-named-tkinter)
  - [Error module 'cgi' has no attribute 'escape' when running autograder.pt](#error-module-cgi-has-no-attribute-escape-when-running-autograderpt)
  - [Can't fit the Pacman window in my screen, can I resize it?](#cant-fit-the-pacman-window-in-my-screen-can-i-resize-it)
  - [Cannot compile Metric-FF in MacOS](#cannot-compile-metric-ff-in-macos)
  - [One of the many tests is failing, how can I just run one question or even one particular test only?](#one-of-the-many-tests-is-failing-how-can-i-just-run-one-question-or-even-one-particular-test-only)
  - [My X algorithm (e.g. A* search) works but it takes too long, what's the best way to work out why it's taking so long/work out how to optimise it?](#my-x-algorithm-eg-a-search-works-but-it-takes-too-long-whats-the-best-way-to-work-out-why-its-taking-so-longwork-out-how-to-optimise-it)
  - [How can I debug my system?](#how-can-i-debug-my-system)
- [Project 1](#project-1)
  - [What actions should I return in the search algorithms?](#what-actions-should-i-return-in-the-search-algorithms)
  - [What counts as an expansion? I am getting too many expansions....](#what-counts-as-an-expansion-i-am-getting-too-many-expansions)
  - [My solution works manually for `tinaMaze` but the authograder fails. The state format used in the autogarders tests are different from the Pacman game's in `tinaMaze`. What happens here?](#my-solution-works-manually-for-tinamaze-but-the-authograder-fails-the-state-format-used-in-the-autogarders-tests-are-different-from-the-pacman-games-in-tinamaze-what-happens-here)
  - [What is a good timeout for Q7 (Eating All The Dots)?](#what-is-a-good-timeout-for-q7-eating-all-the-dots)
  - [In Q7, can I take a heuristic from elsewhere (e.g., Google) and implement it?](#in-q7-can-i-take-a-heuristic-from-elsewhere-eg-google-and-implement-it)
  - [In Q7, what timeout will be used? How do I know what timeout should I use?](#in-q7-what-timeout-will-be-used-how-do-i-know-what-timeout-should-i-use)
- [Project 2](#project-2)
  - [Inconsistent depth in minimax project 2, Q2 and careful use of `__init__`](#inconsistent-depth-in-minimax-project-2-q2-and-careful-use-of-__init__)
  - [Can we apply a "magic number" such as -9999 in our evaluation functions, as part of our logic not simply an arbitrary "return -9999"?](#can-we-apply-a-magic-number-such-as--9999-in-our-evaluation-functions-as-part-of-our-logic-not-simply-an-arbitrary-return--9999)
  - [In Q4, what does it mean an adversary which chooses amongst their `getLegalActions` uniformly at random?](#in-q4-what-does-it-mean-an-adversary-which-chooses-amongst-their-getlegalactions-uniformly-at-random)
- [Capture the Flag](#capture-the-flag)
  - [How to import/load my additional files beyond myTeam.py?](#how-to-importload-my-additional-files-beyond-myteampy)
  - [How do I know what version of my team has played?](#how-do-i-know-what-version-of-my-team-has-played)
  - [Can I assume a certain size of the map?](#can-i-assume-a-certain-size-of-the-map)
  - [Games go too fast! What should I do?](#games-go-too-fast-what-should-i-do)
  - [How do I replay a game?](#how-do-i-replay-a-game)
  - [How does one check if a given agent is currently scared? Is the only option to check the number of capsules in previous states?](#how-does-one-check-if-a-given-agent-is-currently-scared-is-the-only-option-to-check-the-number-of-capsules-in-previous-states)
  - [It looks like the distance calculator is performing calculations in the background of our turns, can we replace it with our own version that does more?](#it-looks-like-the-distance-calculator-is-performing-calculations-in-the-background-of-our-turns-can-we-replace-it-with-our-own-version-that-does-more)
  - [Can we re-use code from Project 2?](#can-we-re-use-code-from-project-2)
  - [Ugly rendering of graphics under MacOs?](#ugly-rendering-of-graphics-under-macos)
  - [How to call a planner like (like `ff`) or any another external tool?](#how-to-call-a-planner-like-like-ff-or-any-another-external-tool)
  - [What does it mean that we must use 2/3 AI techniques? Do they all need to be part of the final submission?](#what-does-it-mean-that-we-must-use-23-ai-techniques-do-they-all-need-to-be-part-of-the-final-submission)
  - [Can I use library or program X (e.g., tensorflow, FF planner, etc.)?](#can-i-use-library-or-program-x-eg-tensorflow-ff-planner-etc)
  - [I have performance problem with `generateSuccessor` in my search implementation, why?](#i-have-performance-problem-with-generatesuccessor-in-my-search-implementation-why)
  - [I want to update an enemy position that's not in my sight range. I need to assign the position information in a copy of `gameState`. But I could only get an Agent Position not set.](#i-want-to-update-an-enemy-position-thats-not-in-my-sight-range-i-need-to-assign-the-position-information-in-a-copy-of-gamestate-but-i-could-only-get-an-agent-position-not-set)
  - [The Berkeley site claims that observations are noisy unless the other agent is nearby, but when I call `getAgentPosition` it gives the exact location of any agent, including opponents.](#the-berkeley-site-claims-that-observations-are-noisy-unless-the-other-agent-is-nearby-but-when-i-call-getagentposition-it-gives-the-exact-location-of-any-agent-including-opponents)
  - [What does the "Score Balance" mean?](#what-does-the-score-balance-mean)
  - [Is there any way to determine how long is left in a game? The Berkley spec it says 'games are limited to 1200 agent moves'. Will this limit also be the same for our tournament?](#is-there-any-way-to-determine-how-long-is-left-in-a-game-the-berkley-spec-it-says-games-are-limited-to-1200-agent-moves-will-this-limit-also-be-the-same-for-our-tournament)
  - [Can I override the `X` (e.g., `makeObservation()`) method of `CaptureAgent`?](#can-i-override-the-x-eg-makeobservation-method-of-captureagent)
  - [How to simulate opponent in MCTS?](#how-to-simulate-opponent-in-mcts)
  - [The option `--numTraining` (or `-x`) option does not work, why?](#the-option---numtraining-or--x-option-does-not-work-why)
  - [Can I perform training during the contest (in `agent.final(gameState)`)?](#can-i-perform-training-during-the-contest-in-agentfinalgamestate)

-------------------------

# GENERAL

## In a code assignment/project, how do I make sure I do not go against academic integrity?

Check the [answer to this key question here](https://docs.google.com/document/d/1AQAU7cH9zgsneTAfig-afBoVfPCi6t1k2nBzFfhdBfc/edit?usp=sharing)

## Cannot access the Google Form, says I need permission

If you see something like this:

![google-form](img/permission-google.png)

then chances are you are not correctly logged into your uni account or you are logged with your private Google account and your browser cannot distinguish. Either open it on an incognito browser window or make sure you are logged into your uni account. There is nothing I can do from my side if you don't access the form with the right authentication credentials.


## I submitted wrongly (e.g., didn't tag correctly) and is now after the due date, can you consider my submission?

We will not fix any submission and it is your responsibility to do it correctly.

However, the nice thing about git-based projects/assessments is that we can rely on commits. If you have submitted your tag incorrectly (did not tag it at all, tagged with different name or different capital letters), then please fix your submission by tagging the specific commit you want me to mark. I will use the timestamp of the commit itself, not of when it was tagged. This means that if the commit was done before the deadline, then all good!! Isn't this cool?

## Project specification says "You should code your implantation only at the locations ...." . Does this mean that we can't create our custom classes outside the provided functions?

Yes, you can create some help functions or classes, but **always** in the allowed files. Any other change in any other file will be totally ignored.

If you want to create custom classes and functions, you can also nest them inside the location where you read `***YOUR CODE HERE***`. See [this link](https://www.datacamp.com/community/tutorials/inner-classes-python) and [this link](https://www.programiz.com/python-programming/closure#:~:text=A%20function%20defined%20inside%20another,in%20order%20to%20modify%20them) for more info.

## How do I zip files in folder X without including the folder X itself?

Use the `-j` option, for example:

```bash
$ zip -r -j myAgent.zip project-2/MySolution/ 
```

However, this is OK if you don&rsquo;t need ANY folder at all in the zip, everything in the root. If you just don&rsquo;t want the root folder included but you do want all the folders after that to be included:

```bash
$ rm -f myAgent.zip ; cd project-2/MySolution; zip -r -j ../../myAgent.zip * ; cd ..
```

## The autograder says _"Your grades are NOT yet registered."_ What should I do to register?

The autograder is some immediate **feedback** for you, but it is not the final grading we do as teaching staff.  

So, while the automarker is a useful indication of your performance, it may not represent the ultimate mark. We reserve the right to run more tests, inspect your code and repo manually, run similarity software for integrity checks (this year via [Codequiry](https://codequiry.com/)), and arrange for a face-to-face meeting for a discussion and demo of your solution if needed.

After submission deadline we will mark them all and provide you with the results.


## Should I pass all the autograder tests?

Well, if you want to have a chance to get full marks _yes_. 

So, the short answer is that you should try to pass the test cases provided, yes.

If your solution does not meet those test cases, it is *not* exactly what we are looking for (that is the bare minimum). Some test cases in the autograder may still give some partial marks. In fact, even if your solution does meet every test case given, it still does not necessarily mean it is perfect, and we may run additional tests when we actually grade the submission.

We are aware that it can be a bit unforgiving to work with the automated test harness, but often your understanding of the underlying algorithms are greatly improved when you need to dig into particular corner cases, so it's time well spent. 

As recognised by students, the autograder is indeed a fantatic feedback before submission for you. It is the minimum expected and you have it right from the start, so use it!

------------------------------
# GIT & GITHUB

## Git, GitHub, what is that?

We will use proper (git) version control in all our programming projects. This is totally standard practice in the industry and you would have seen that in previous courses (SEF and SEPT at least). Said so, if you want to refresh or have a quick intro to it, here are two resources I found useful:

- [30' video on Git & GitHub](https://youtu.be/jG4Vs81kMlc).
- [GitHub Guides](https://guides.github.com/).
- [Git \& GitHub Tutorial & Reference @ Javatpoint](https://www.javatpoint.com/git).

There are lots more good resources on the web of course!
## How do I submit my project solution in my GIT repository?

You submit by **tagging the _exact_ commit that you want to submit and be marked**, using the exact name given in the assignment specification. We will ONLY marked tagged submissions and will ONLY mark the tagged commit. Students can have many commits, and branches, even commits after the deadline. We will mark ONLY what you submit.

Of course we do not have access to your local machine, so the tag has to be done or pushed into GitHub server repo (see below for several guides). Your tag has to show under `tags`, for example:

![google-form](img/tags-github-gui.png)

Observe that a tag is:

- NOT the same as a branch called "`submission`";
- NOT the same as a commit message "`submission`"; and
- NOT the same as a release called "`submission`".

A tag is a specific point in the repository history, the point you want to be used for marking. A branch, a comment, and a release are different things. 

Note that a tag is a unique name and is case-sensitive, you cannot have commits tagged with the same name and `Submission` is not the same as `submission`. So if you have submitted a version by tagging it and you want to change the commit submission, you first need to delete the existing tag and then re-tag the good commit; see next question for that.

- For basic information on tagging, check [here](https://git-scm.com/book/en/v2/Git-Basics-Tagging). 
- To create, push, and view tags in GitHub Desktop, check [here](https://docs.github.com/en/desktop/contributing-to-projects/managing-tags). 
- To tag via command line or via GitHub web interface, check [here](https://stackoverflow.com/questions/18216991/create-a-tag-in-a-github-repository). 

Note that the timestamp of the commit is the submission date.

See next questions to change the submission tag you have already done (i.e., you want to update your submission to another point in the repo history, usually a more recent one).

## How do I change the submission tag if I have already tagged one commit for submission?

This will happen when you realize you have a better version to submit than the one you submitted/tagged before. To do that, you need to delete the tag (from your local repo and from the server):

- First delete it from the GIT server by running: `git push --delete origin <tagname>`
- Second, delete the local tag in your repo by running: `git tag --delete tagname`

More information on how to delete git tags [here](https://devconnected.com/how-to-delete-local-and-remote-tags-on-git/).

See this as well:

![google-form](img/how-to-rename-tag.png)

It used to be the case that GitHub web interface did not allow deleting tags (though you could create new tags); but it was [@120](https://piazza.com/class/kbsmlzxg3k7418?cid=120) suggests that it is now possible to change a tag from the GitHub web interface!

## Cannot clone or push to GitHub with my password credentials?

As [per August 12th, 2021 GitHub post](https://github.blog/changelog/2021-08-12-git-password-authentication-is-shutting-down/), GitHub is not no longer accepting account passwords when authenticating Git operations, like clonning private repos or pushing changes. You should use **token-based authentication**, such as  personal access, OAuth, SSH Key, or GitHub App installation token.

So, if you were still using a password to authenticate your GitHub.com operations (something never recommended anyways if you are doing development), you must start using a [personal access token](https://docs.github.com/en/github/authenticating-to-github/keeping-your-account-and-data-secure/creating-a-personal-access-token) by August 13, 2021 via HTTPS (recommended) or [SSH key](https://docs.github.com/en/github/authenticating-to-github/connecting-to-github-with-ssh) to start using a personal access token to avoid disruption. 

For example, you can set-up your remote as follows (after you generated your token in GitHub):

```shell
$ git remote set-url origin https://<token>@github.com/<username>/<repo>
```

As explained [here](https://www.sobyte.net/post/2021-08/github-deprecates-passwords-for-git-operations/), tokens offer many advantages over password-based authentication: 

* **Unique:** tokens are specific to GitHub and can be generated on a per-use or per-device basis.
* **Revocable:** tokens can be individually revoked at any time without the need to update unaffected credentials.
* **Limited:** tokens can be narrowed to allow only the access required by the use case.
* **Random:** tokens are not subject to dictionary types or brute force attempts that might be made with simpler passwords that users need to remember or enter periodically.

## I have committed to the remote repo but I am not listed as a "contributor", why?

The two main reasons may be:

1. Your commit is in a branch and has not yet made it to the default (master/main) branch, therefore you did not technically contribute (yet).
2. Your local Git commit email isn't connected to your account; [connect it](https://docs.github.com/en/github/setting-up-and-managing-your-github-user-account/managing-email-preferences/setting-your-commit-email-address)!

Read [this GitHub page](https://docs.github.com/en/github/setting-up-and-managing-your-github-profile/managing-contribution-graphs-on-your-profile/why-are-my-contributions-not-showing-up-on-my-profile#common-reasons-that-contributions-are-not-counted) to understand more about why your commit is not yet counting as contributions.


## Commits not correctly associated to my GitHub account, why?

Please [check this](https://docs.github.com/en/github/committing-changes-to-your-project/troubleshooting-commits/why-are-my-commits-linked-to-the-wrong-user) and fix it so we can know the commit was *yous*. Otherwise we may get your contributions wrong and risk getting lower marks or delaying your marking.

------------------------------
# PYTHON

## What version of Python should I use?

All projects run on **Python 3.6**, so your code must be written for such a version. Please note the original project from UC runs in Python 2.7. 

**Note**: Some Linux distributions come with both python2 and python3 installed but default to python2 for the python command. In this case, you should use the python3 command in place of python to explicitly use version 3.x.

Additionally, in order to render the game, the homework projects require the Python module tkinter to be installed. You can follow the [official docs](https://tkdocs.com/tutorial/install.html) to get tkinter on your platform if it is not installed already. If you are using Linux, many distributions have packaged tkinter for easy install and you should use the package manager to install it. The package name is `python3-tk` for Debian/Ubuntu, python3-tkinter for RHEL/Fedora and tk for Manjaro/Arch.

There is no problem **having more than one Python version installed in your machine**, you just need to be careful your code is using the right one. You need to use Python Package and Environment Managers.

One good option is to use **Miniconda**, a minimalist version of Anaconda virtual environment variable to have both installations coexist in your machine (here are others these days, like pipenv)

The download page is [here](https://conda.io/miniconda.html) (install either the version for Python 2 or 3, it only affects the default environment, you can still install others).

After you install Miniconda, you can create new environments via 

```bash
$ conda create --name <env-name> python=3.6
```

For example, you can do:

```bash
$ conda create --name ai20 python=3.6
```

At that point, to active your ai20 environment:

```bash
$ source activate ai20
```

(on Windows; instructions for other OSs [here](https://conda.io/docs/using/envs.html#change-environments-activate-deactivate))

These commands will make your calls to `python` or `pip` run the correct version.

Example run (on Debian Linux, so the activation command is slightly different):

```bash
marco@w8103259:~$ source activate py27
discarding /home/marco/miniconda3/bin from PATH
prepending /home/marco/miniconda3/envs/py27/bin to PATH

(py27)marco@w8103259:~$ python --version
Python 2.7.12 :: Continuum Analytics, Inc.

(py27)marco@w8103259:~$ source activate py36
discarding /home/marco/miniconda3/envs/py27/bin from PATH
prepending /home/marco/miniconda3/envs/py36/bin to PATH

(py36)marco@w8103259:~$ python --version
Python 3.6.0 :: Anaconda 4.3.0 (64-bit)
```

As you can see, I have python 2.7 and 3.6 coexisting peacefully in my OS."

## How do I run Python 3.6 in `coreteachingXX.csit.rmit.edu.au`??

You need to activate it first using `scl`:

```bash
[e62439@csitprdap01 ~]$ scl enable rh-python36 bash
[e62439@csitprdap01 ~]$ python --version
Python 3.6.9
[e62439@csitprdap01 ~]$ python
Python 3.6.9 (default, Sep 11 2019, 16:40:19) 
[GCC 4.8.5 20150623 (Red Hat 4.8.5-16)] on linux
Type "help", "copyright", "credits" or "license" for more information.
```

## How do I know the type of a variable in Python?

Check this video to know how to print the type of a variable in Python:

[![Alt text](https://img.youtube.com/vi/iROZLaQGy4s/0.jpg)](https://www.youtube.com/watch?v=iROZLaQGy4s)

## AttributeError: module 'importlib' has no attribute 'util'

Some students reported that running `python capture.py` gives them the following errors:

```shell
Traceback (most recent call last):
  File "capture.py", line 1127, in <module>
    options = readCommand( sys.argv[1:] ) # Get game components based on input
  File "capture.py", line 902, in readCommand
    redAgents = loadAgents(True, options.red, nokeyboard, redArgs)
  File "capture.py", line 978, in loadAgents
    spec = importlib.util.spec_from_loader(moduleName, loader)
AttributeError: module 'importlib' has no attribute 'util'
```

Changing `import importlib` with `import importlib.util` seems to fix the problem.

We are still investigating this issue as it seems to work well in our set-up. This seems to be related to the fact that ["importing a package does not automatically load its submodules"](https://stackoverflow.com/questions/65028261/attributeerror-module-importlib-has-no-attribute-util-ii) but we are unclear why sometimes it does work! A quick search also brings [this post](https://stackoverflow.com/questions/39660934/error-when-using-importlib-util-to-check-for-library) which may be

------------------------------
# GENERAL PACMAN

## What is the best way to develop my solutions for the Pacman project?

We highly recommend developing your solutions in your local machine (e.g., your laptop). Even more, if you are running Linux locally, 99.99% sure your code will ran in another Linux install. If you are using Windows, you may want to consider installing a Linux virtual machine with Virtualbox.

Running it locally will make the development much faster. I also strongly suggest using a version control system, like git or mercurial. This is best practice and should be something normal at this stage of the program. Remember though NOT to make your solutions public and this will violate the course plagiarism code AND also break the will of the creators of this wonderful project. SO if you use bitbucket for example, make sure your repository is private.


## How to run Pacman remotely from `coreteaching`?

If you do not care about the graphics (e.g., for grading), then try using `--textGraphics` or even `--quietTextGraphics`. In most cases you will use `coreteaching` machines just to test that the autograder works well. The autograder does not need any graphical interface so it should work properly.

If you do want the display, then you need to do X forwarding when you connect via ssh. If you are in Linux/Unix this is easy, just do `-X` and `-Y` when you ssh; for example:

```shell
$ ssh -X -Y username@coreteaching01.csit.rmit.edu.au
```

If you use Windows, then you need an X server running and set your ssh client (e.g., Putty) with X forwarding. For example, check [this page](https://superuser.com/questions/119792/how-to-use-x11-forwarding-with-putty) or this video:

[![Alt text](https://img.youtube.com/vi/vwZXhTykSis/0.jpg)](https://www.youtube.com/watch?v=vwZXhTykSis)

Said so, for development, we strongly suggest to clone your repo locally on your machine and work there (e.g., using PyCharm, Visual Code Studio, or even ECLIPSE).

## Coreteaching? What is that?

Check [this FAQ](https://docs.google.com/document/d/12CS_7OdEmpQZiwuxDTc9PHfHan4mGRwceT0t-kstKNc/edit) on RMIT coreteaching facilities.

## How do I setup a system in Windows with Python 3.6?

Although we will assume you are able to install and get Python running in your machine, there are plenty of videos on that on the web. For example: 

[![Alt text](https://img.youtube.com/vi/oHOiqFs_x8Y/0.jpg)](https://www.youtube.com/watch?v=oHOiqFs_x8Y)

## Can I use `problem._visited`?

Under Python convention, single underscore before a name (e.g., `_visited`) denotes private data, and hence it is good practice not to rely on such data. Check [this post](https://shahriar.svbtle.com/underscores-in-python) for example. Note that such private data can change without notice, it may not be available anymore, it may not be available under other interfaces, etc. So.... 

## I get "`_tkinter.TclError: no display name and no $DISPLAY environment variable`" error when running in WSL or ssh

If you do not care about the graphics, then try using `-t` (or `--textGraphics`) or even `-q` (or `--quietTextGraphics`).

If you do want the display, then you need to do X forwarding when you connect via ssh. If you are in Linux/Unix this is easy, just do `-X` and `-Y` when you ssh (e.g., `ssh -X -Y server`).

If you use Windows, then you need an X server running and set your ssh client (e.g., Putty) with X forwarding. For example, check [this page](https://superuser.com/questions/119792/how-to-use-x11-forwarding-with-putty) and [this video](https://www.youtube.com/watch?v=vwZXhTykSis).

Also, if you are using Windows hooked up into Linux (WSL or WSL2), you need to properly resolve the IP Address seen by Linux. For example, under Ubuntu bash, add this to your `~/.bashrc`:

```shell
export DISPLAY=$(cat /etc/resolv.conf | grep nameserver | awk '{print $2}'):0
```

Then install the [VCXSRV](https://sourceforge.net/projects/vcxsrv/files/vcxsrv/) X-server. Run xLaunch and "Disable access control". And add a new inbound rule in Windows Firewall for TCP Port 6000.  Use the ssh command as above.

As you can see, all this can be too complicated for no benefit. For development, **we strongly suggest** to clone your repo locally on your machine and work there (e.g., using PyCharm, Visual Code Studio).

## Cannot run Pacman due to problems with Tkinter: "`ImportError: No module named Tkinter`"

Install Tkinter in your system. If you are running `conda`:

```bash
$ conda install tk
```

Now it should be installed, so you should not get this error. But please try the code below, it should not trigger any error:

```bash
[e62439@foo~]$ scl enable rh-python36 bash
[e62439@foo~]$ python
Python 3.6.9 (default, Sep 11 2019, 16:40:19) 
[GCC 4.8.5 20150623 (Red Hat 4.8.5-16)] on linux
Type "help", "copyright", "credits" or "license" for more information.
>>> import tkinter
>>> 
>>> 
[e62439@foo~]$ 
```

## Error module 'cgi' has no attribute 'escape' when running autograder.pt

You are probably not using Python 3.6 but a higher version. Check [this post](https://piazza.com/class/kbsmlzxg3k7418?cid=28).

## Can't fit the Pacman window in my screen, can I resize it?

The Pacman windows cannot be resized once open. However, you can use the option `-z <float>` (or `--zoom <float>`) to scale the window. For example, using `-z 0.5` will scale down the window by half. Using this option you should be able to fit the entire window in the screen.

## Cannot compile Metric-FF in MacOS

Some Mac users have reported this error when compiling [Metric-FF](https://fai.cs.uni-saarland.de/hoffmann/metric-ff.html) planner:

![bad-graphics](img/ff-compile-mac.png)

The problem seems to be that the default `gcc` in Mac is set to be `clang`. So, you first neeed to install standard `gcc` on using command `brew install gcc@7`  (must use version 7, newest version 10 won't work) and instead of just `make`, you need to run:

```bash
make CC=/usr/local/bin/gcc-7
```

Thanks Banhao from AI'20!

## One of the many tests is failing, how can I just run one question or even one particular test only?

Use the `-q n` option for running just one question (e.g., `-q q3` to run Question 3 only) or `-t` to run only a specific test (e.g., `-t test_cases/q1/graph_bfs_vs_dfs`).

## My X algorithm (e.g. A* search) works but it takes too long, what's the best way to work out why it's taking so long/work out how to optimise it?

Fundamentally there are two ways of approaching this, empirically or theoretically.

Empirically you can profile your code and see which sections are taking the longest. If you have a particular section that you suspect might be the issue, you can use the time module to check manually. However probably the better way is to use pythons inbuilt `cprofile` tool. This works well, especially when paired with [Snakeviz](https://stackoverflow.com/a/49173782). There is also 
[line_profiler](https://github.com/pyutils/line_profiler) which profiles line by line showing line time, total line time and number of calls.

Theoretically, you can use your algorithms and analysis skills to try to figure out the time complexity of your algorithm. If your code matches the book, it should have a similar time complexity, but you may want to dig a bit deeper into each individual line of code. What is the time complexity of popping from a priority queue in python? What about a list? What about adding a node to the frontier, or visited data structure?

In general, before spending a lot of time doing experimental analysis, look at your implementation conceptually in a very, I repeat, _very_, critical way and perform the (theoretical) analysis of it. Think where the problem could be and whether you can suspect of something that is not well done. It's like being a detective, and good detectives are critical and meticulous!

## How can I debug my system?

While you may want to do some print outs here and there, eventually using a debugger is the way to go. Check [this video](https://www.youtube.com/watch?v=w8QHoVam1-I) for a quick guide to debugging python in VSCode (you can do similar things in PyCharm or other editors as well). This is far more flexible and reliable than print messages. :-)

-----------------
# Project 1

## What actions should I return in the search algorithms?

Check the actions in this class in games.py

```python
class Directions:
NORTH = 'North'
SOUTH = 'South'
EAST = 'East'
WEST = 'West'
STOP = 'Stop'
```

## What counts as an expansion? I am getting too many expansions....

Basically, every time you call `problem.getSuccessors(.)`. 

(It is not popping out from the queue, as we don't have access to that part of your code!)

So be careful not using that function for more than what is needed. :-)

One can implement the various search algorithms (e.g., DFS) doing one call to `getSuccessor()` per loop/node, as in the pseudo-code (e.g., book or slides).

## My solution works manually for `tinaMaze` but the authograder fails. The state format used in the autogarders tests are different from the Pacman game's in `tinaMaze`. What happens here?

Indeed, the test cases often have atomic states instead of `(x,y)` coordinates, but this should not affect your code at all. From the algorithms perspective, a state is (just) a "state", regardless of the representation. The autograder often checks corner cases which are not tested by the standard 
mazes, which may be why you see it failing (despite your manual cases working).

## What is a good timeout for Q7 (Eating All The Dots)? 

In this question you have to consider two question:

1. How good is your A* implementation?
2. How good is your heuristic?

Basically you are after a good enough A* implementation and a heursitic that improves A* when used without heuristic. Remember taht a heuristic is useful, only if gives benefit over not using it; otherwise what is the point of it? If your heuristic expands very few nodes, BUT it takes alot of time to compute, then the heuristic will not be beneficial after all. Consider, what would be the very best heuristic you can use (but not useful)? ;-)

Now, to test your A* without the heuristic, just `return 0` as heuristic and see how it runs. In my laptop:

```shell
$ python pacman.py -l trickySearch -p AStarFoodSearchAgent -q

Path found with total cost of 60 in 1.6 seconds
Search nodes expanded: 16688
Pacman emerges victorious! Score: 570
Average Score: 570.0
Scores:        570.0
Win Rate:      1/1 (1.00)
Record:        Win
```

So, it took 1.6seconds and expanded 16k+  nodes. However, when I ran it with the heuristic:

```shell
$ python pacman.py -l trickySearch -p AStarFoodSearchAgent -q

Path found with total cost of 60 in 0.1 seconds
Search nodes expanded: 255
Pacman emerges victorious! Score: 570
Average Score: 570.0
Scores:        570.0
Win Rate:      1/1 (1.00)
Record:        Win
```

Note this is a really good heuristic (expanded only 255!) and we are not expecting this to get full marks. There are very fast implementations taking 0.5secs and expanding 1500 nodes, way below the 7000 mark!


Finally, take note of the comment in the source code:

```
If you want to *store* information to be reused in other calls to the
    heuristic, there is a dictionary called problem.heuristicInfo that you can
    use. For example, if you only want to count the walls once and store that
    value, try: problem.heuristicInfo['wallCount'] = problem.walls.count()
    Subsequent calls to this heuristic can access
    problem.heuristicInfo['wallCount']
```

This could be a deal breaker and could move your heuristic performance from 30secs to 1sec.

## In Q7, can I take a heuristic from elsewhere (e.g., Google) and implement it?

The objective of the exercise is NOT to program in Python a solution that somebody else has invented/created. The fact is that we are not testing Python here or even coding skills per se alone. We are learning how to come up/create good heuristics ourselves, by thinking about the domain at hand and the way search works.

What we are interested in assessing for this question is your ability to understand what heuristics are and design them yourself. As a result, while searching online for heuristics **in general** would be fine (but we doubt useful here if you read the book), searching for a heuristic, even at a conceptual level, for this particular problem is definitively **not** OK.

Think about what some relaxations of the problem are, and how you might design a heuristic from those. There are a number of quite simple heuristics that do quite well, as well as some more sophisticated ones.

## In Q7, what timeout will be used? How do I know what timeout should I use?

The key point to understand here is *why do we use heuristics after all?* We use heuristics to guide the search---informed search---so that it runs _faster_. 

OK, but _faster thank what?_ Well, at least faster than if we do not use a heuristic, right? So, we can set the heuristic to just be `0` (by just doing `return 0` at the top of function `foodHeuristic`) and see how much it would take by running:

```shell
$ python pacman.py -l trickySearch -p AStarFoodSearchAgent -q 

Path found with total cost of 60 in 1.9 seconds
Search nodes expanded: 16688
Pacman emerges victorious! Score: 570
Average Score: 570.0
Scores:        570.0
Win Rate:      1/1 (1.00)
Record:        Win
```

So it takes 1.9 seconds when running the agent with an "empty" heuristic. What happens when we plugged our heuristic? 


```shell
$ python pacman.py -l trickySearch -p AStarFoodSearchAgent -q 

Path found with total cost of 60 in 0.2 seconds
Search nodes expanded: 255
Pacman emerges victorious! Score: 570
Average Score: 570.0
Scores:        570.0
Win Rate:      1/1 (1.00)
Record:        Win
```

As one can see the time was cut down to just 0.2 seconds (10% of the time when no heuristic is used!) and the number of nodes expanded to just 255. Note this is a very powerful heuristic, you can reduce the time to 50% while expanding 1500 nodes.

So, the question is not just whether the heuristic reduces the number of expansions, but also, ultimately, the search time.


-----------------
# Project 2

## Inconsistent depth in minimax project 2, Q2 and careful use of `__init__`

Taken from Andrew's and other student fantastic answer in post @140 

So it looks like this issue is due to issues in calling constructors of parent classes (i.e. `__init__`). This can be a bit tricky, so here is the takeaway that is needed for this project:

If you want to add an `__init__` method into any (or all) of `MinimaxAgent`, `AlphaBetaAgent`, or `ExpectimaxAgent`, it should look like this:

```python
class MinimaxAgent(MultiAgentSearchAgent):
def __init__(self, **kwargs):
"*** YOUR CODE HERE ***"
super().__init__(**kwargs)
```

This ensures that you aren't interfering with the arguments being passed through to the `MultiAgentSearchAgent` subclass. For anyone who wants to know why you need to do this and what that means, keep reading.

Let's imagine you want to add something to the constructor (i.e. the `__init__` method) of `MinimaxAgent`, for whatever reason. Your first attempt might look like: 

```python
class MinimaxAgent(MultiAgentSearchAgent):
def __init__(self):
self.foo = 0 # initialise foo
```

This should fail with the following `error: TypeError: __init__()` got an unexpected keyword argument 'depth'.

Why is that? Well, the test harness is trying to call `__init__()` on `MultiAgentSearchAgent` to pass in the depth (and potentially evalFn) argument. Your new constructor now overwrites the original constructor of `MultiAgentSearchAgent`, and it isn't expecting any arguments, hence the error. What you want to do is call the parent constructor from within your constructor, to make sure that you aren't interfering with the original code. You can try to do so with the `super()` keyword like so:

```python
class MinimaxAgent(MultiAgentSearchAgent):
def __init__(self):
self.foo = 0 # initialise foo
super().__init__()
```

But this still gives the same error, as you haven't passed through the arguments. You can pass them through manually like so:

```python
class MinimaxAgent(MultiAgentSearchAgent):
def __init__(self, evalFn = 'scoreEvaluationFunction', depth = '2'):
self.foo = 0 # initialise foo
super().__init__(evalFn, depth)
```

However this runs into a number of problems:

If you have multiple parent classes (either directly or indirectly), you don't know which arguments to pass.
It duplicates code (including default arguments), now a change to one class needs to be made in many places.
It requires you to know exactly what the parent class is doing, which is not ideal. 

This is where `**kwargs` comes in. For our purposes we can think of `**kwargs` as a dictionary that store an unlimited number of keyword arguments to a function, where we don't have to know what they are. This allows you to pass then on to other functions from parent classes, but you can also access them like any other dictionary:

```python
class MinimaxAgent(MultiAgentSearchAgent):
def __init__(self, **kwargs):
self.foo = 0 # initialise foo
print("Minimax depth: ", kwargs['depth'])
super().__init__(**kwargs)
```


More details about super can be found [here](https://stackoverflow.com/questions/2399307/how-to-invoke-the-super-constructor-in-python) (although it lacks discussion of arguments), and details about kwargs [here](https://stackoverflow.com/questions/3394835/use-of-args-and-kwargs)

## Can we apply a "magic number" such as -9999 in our evaluation functions, as part of our logic not simply an arbitrary "return -9999"?

You would not be marked down for using a number like that - however if you really want a very large number, you might consider using `math.inf` instead, or even `float('inf')`.

## In Q4, what does it mean an adversary which chooses amongst their `getLegalActions` uniformly at random?

All it means is that the other players in the game are acting randomly, with no bias towards any action: all legal actions have the same chance of being executed. For example, if player 2 has three legal moves: left, down and up, then it will choose left with 33% chances, down with 33% chances and up with 33% chances.

-----------------
# Capture the Flag

## How to import/load my additional files beyond myTeam.py?

You may have coded supported files that you will import in your `myTeam.py`, for example a module  `abc.py`. In order for the contest script to find it you need to do it this way:

```python
import os
import sys

cd = os.path.dirname(os.path.abspath(__file__))
sys.path.append(cd)

import abc 
```

The `cd` variable will contain the absolute path to the folder where your agent is located.

This will add the folder where your system is to Python [`sys.path`](https://docs.python.org/3/library/sys.html#sys.path) that contains the directories where Python will look for modules when importing. By doing so, you are telling Python to also look at the folder where your agent is located; otherwise it will not find it and your agent will just crash when importing.

Also, make sure the module you import has a very unique name. Do not call it `qlearning.py` as it may clash with other files. If anything, use your team name as suffix, e.g., `qlearning_myteam.py`.

You should be able to also use variable `cd` to access other auxiliarly files you may bundle with your agent system. For example:

```python
with open(os.path.join(cd, data_agent.json)) as f:
  ....
```


## How do I know what version of my team has played?

One way is that you print the version number of your system right at the start of your agent and then you just check the log:

```python
VERSION = 1.0   # set the version number of your current system

...

print("Team XYZ: ", VERSION)
```

Make sure you change constant `VERSION` when you update your agent.

## Can I assume a certain size of the map?

The short answer is _yes_, you can assume that all of the boards in the competition have the same dimensions.

Said so, note the general ovearching idea of the project is to make an AI system that is NOT tailored to special cases, but general to tackle different situations, even ones not ever seen.

Of course, in the context of map size, we can think of a continuum of agents, from most specific to most general, as follows:

1. Can play pacman capture the flag (hereafter referred to simply as pacman) on one specific map, with one specific starting condition.
2. Can play pacman on one specific map, as either team.
3. Can play pacman on a range of maps all of the same size.
4. Can play pacman on a range of maps with differing sizes.
5. Can play pacman on a range of maps and with varying configurations (e.g. changing numbers of agents, or splitting map top/bottom instead of left/right).
6. Can play a range of different games involving moving around on a square grid.
7. Can play any game ever made.
8. Can perform any task requiring intelligence.

When we say "a good AI is general", we re not talking about cases 7 or 8 (although if your system can do that, then you will likely get both good marks and a Turing award)! For this project, we are really aiming for the **range of 3-4**. For some AI techniques, like planning, it is likely that if your agent can do 3 well, it can probably also do 4 reasonably well. For others, like deep RL, having an agent that is capable of handling 4 instead of 3 may be substantially more challenging.

There is a delicate balance to walk in terms of how specific vs how general your agent should be. Our advice is that _whenever reasonable_, you should aim to handle arbitrary sized boards (e.g. to figure out where the boundary is, divide the width of the board by 2, don't hard code in a particular number). **Certainly hard coding in strategies for a specific board is not appropriate**. However if your agent can play on any sized board but is just not as good at arbitrary boards as it is on the competition sized ones, then I wouldn't worry too much.

If in doubt whether the assumption you are considered is reasonable or not, please attend the drop-in lab sessions to discuss, they are exactly for that!

## Games go too fast! What should I do?

Use the `--delay-step` option. Note that option is NOT available in the standard UC-Berkeley distribution; I have added it.

## How do I replay a game?

You can play a game and use the `--record` option, you will be left with the game history to a file named by the time the game was played. You can replay these files using the `--replay` option and specifying the file to replay. You can use the `--replay-delay` to change the speed of the replay (see this is a feature in our distribution, not in the UC-Berkeley distribution). For example:

```bash
$ python capture.py --replay BBC_vs_It_depends_contest18Capture.replay --delay-step=0.1
```

All matches played in the preliminary contests are automatically recorded and the most recent ones can be viewed on the contest site. You are also able to download the history associated with each replay.

A new script [replay.py](https://drive.google.com/drive/folders/1LaqFVayH4cLp3_QW3ar3RVQ4-KuMm9xb?usp=sharing) is provided as well that can be used to select which replay to run from a collection of replays (obtained from the contest site). This is an extended version of the one developed by student Thomas and hosted [here](https://github.com/itsjfx/pacman-contest-replay-player). This makes running replays much easier!



## How does one check if a given agent is currently scared? Is the only option to check the number of capsules in previous states?

```python
GetAgentState(self.index).scaredTimer
```

##  It looks like the distance calculator is performing calculations in the background of our turns, can we replace it with our own version that does more?

The short answer is **no**, you cannot replace or change that code, but you can create your own version that you use instead. For the long answer, keep reading.

The premise to this question is a little off, the distancer is not doing any calculations on "your turns", it only calculates things _during the initialisation phase_. To be precise, that work is done during the `self.distancer.getMazeDistances()` call on line `105` of `captureAgents.py`, in the `registerInitialState` method of `CaptureAgent`. This will be called by all of your agents as you are subclassing `CaptureAgent`.
 
This shouldn't be an issue, as it will only take less than 1 second of your 15 second initialisation time (and even then only 1 second for the first agent). 
 After that, all the distances are cached, so you can get distances essentially for free in your code by calling `self.distancer.getDistance(p1, p2)`.

## Can we re-use code from Project 2?

If you were part of the team for Project 2, then yes, but you need to be careful how.

What you need to ask yourself is: _Was any of the team members for the contest an author of the code you want to re-use for the contest?_ 

* If _yes_, and this was clearly stated in the previous project Certification form, then you can re-use it as is, no problem! 
* _Otherwise_, if it was done by someone else outside the current contest team, then you should be careful as none of the current members can claim ownership of that solution. You may re-use the idea but you would need to re-implement and very clearly acknowledge that the technique came from someone else. Hopefully your system will not just be that, and you will add value to it.

## Ugly rendering of graphics under MacOs?

Some students have reported some stranger rendering of the graphics:

![bad-graphics](img/bad-pacman-rendering-macos.png)


Some have reported that by clicking and slightly moving the window stops the game from repainting poorly. Also by using Python 3.8, though the game speed seems slower and one has to then make sure everything runs under 3.6 as expected.



## How to call a planner like (like `ff`) or any another external tool?

We will provide some AI tools out-of-the-shelf for you to use if you want. These binaries will be available in the `PATH` so you can assume they will just run.

For example, we will provide the [FF](https://fai.cs.uni-saarland.de/hoffmann/ff.html) and [Metric-FF](https://fai.cs.uni-saarland.de/hoffmann/metric-ff.html) planners. You can call them directly via `ff` and  `mff`. 

Basically, if you have `problem.pddl` and want to write the plan into `solution.txt` you can do:

Note that the same technique would apply for any other binary that is provided system wide by the contest organizers.

So, for the rest of this question, suppose you have [`ff` planner](https://fai.cs.uni-saarland.de/hoffmann/ff.html) up and running in your machine. How do I call it from my Python code and extract the plan from its solution?

First, whatever external call is used, it **cannot be done** in another concurrent thread: your agent must _block and wait_ for the external code to finish. Remember that it is against the rules of the game to spawn concurrent threads. You can ran external commands (and wait for them to return) using [`os.system(command)`](https://docs.python.org/3/library/os.html#os.system) or the more preferred one [`subprocess.run(command)`](https://docs.python.org/3/library/subprocess.html#subprocess.run). We will explain the latter here, as it is now a more preferred approach as per Python doc.

**NOTE:** Please do not use `popen`. This is a non-blocking command which might leave things running on the server after your turn has finished, which will lead to your disqualification!

Suppose your code generates the specific `domain.pddl` and `problem.pddl` files that you want to use the planner on.  We are assuming these files, and the `ff` executable, are all in the same folder as `myTeam.py`.

Here is a template using `subprocess.run()`:

```python
import os
import subprocess

def call_ff(domain, problem):
    cd = os.path.dirname(os.path.abspath(__file__))
    cmd = [f"ff", "-o", f"{cd}/{domain}", "-f", f"{cd}/{problem}"]

    result = subprocess.run(cmd, stdout=subprocess.PIPE, stderr=subprocess.PIPE, universal_newlines=True)

    return result.stdout.splitlines() if result.returncode == 0 else None
```

**Note**: Before calling FF you will probably produce the corresponding PDDL problem file. Make sure that all that file has been generated in full and not partially. When you do a print on a file, it may not be printed right away due to buffers in the input-output system. So make sure you close the PDDL file so that you are guaranteed to have a complete file, that you can the use as the input to FF. Otherwise, you ran the risk that the PDDL file is incomplete (some lines have not yet made it to the file) and FF will give error.

The above code will return a list of lines representing the output of `ff,` which can in turn be processed to extract the plan. For example:

```python
output = call_ff('domain.pddl', `problem.pddl')
plan = parse_ff_output(output)

if plan is not None:
    print(plan)
    if plan:
        print(extract_loc(plan[0]))
else:
    print('No plan!')
```


This is the function I use to extract the plan from `ff`'s output:

```python
def parse_ff_output(lines):
    plan = []
    for line in lines:
        search_action = re.search(r'\d: (.*)$', line)
        if search_action:
            plan.append(search_action.group(1))

        # Empty Plan
        if line.find("ff: goal can be simplified to TRUE.") != -1:
            return []
        # No Plan
        if line.find("ff: goal can be simplified to FALSE.") != -1:
            return None

    if len(plan) > 0:
        return plan
    else:
        print('should never have ocurred!')
        return None
```

If there is no plan, a null object will be returned. If a plan was found, a list of actions will be given; for example:

```
['GO P_1_9 P_1_10', 'GO P_1_10 P_1_11', 'GO P_1_11 P_1_12', 'GO P_1_12 P_1_13', 'GO P_1_13 P_1_14', 'GO P_1_14 P_2_14', 'GO P_2_14 P_3_14', 'GO P_3_14 P_3_13', 'GO P_3_13 P_3_12', 'GO P_3_12 P_3_11', 'GO P_3_11 P_3_10', 'GO P_3_10 P_4_10', 'GO P_4_10 P_4_9', 'GO P_4_9 P_4_8', 'GO P_4_8 P_4_7', 'GO P_4_7 P_5_7', 'GO P_5_7 P_5_6', 'GO P_5_6 P_5_5', 'GO P_5_5 P_6_5', 'GO P_6_5 P_7_5', 'GO P_7_5 P_7_6', 'GO P_7_6 P_8_6', 'GO P_8_6 P_9_6', 'GO P_9_6 P_10_6', 'GO P_10_6 P_11_6', 'GO P_11_6 P_12_6', 'GO P_12_6 P_13_6', 'GO P_13_6 P_13_7', 'GO P_13_7 P_14_7', 'GO P_14_7 P_15_7', 'GO P_15_7 P_16_7', 'GO P_16_7 P_17_7', 'GO P_17_7 P_17_6', 'GO P_17_6 P_17_7', 'GO P_17_7 P_18_7', 'GO P_18_7 P_19_7', 'GO P_19_7 P_19_8', 'GO P_19_8 P_19_9', 'GO P_19_9 P_20_9', 'GO P_20_9 P_21_9', 'GO P_21_9 P_22_9', 'GO P_22_9 P_23_9', 'GO P_23_9 P_24_9', 'GO P_24_9 P_24_10', 'GO P_24_10 P_25_10']
``` 

This corresponds to an output containing these lines:

```
ff: found legal plan as follows

step    0: GO P_1_9 P_1_10
        1: GO P_1_10 P_1_11
        2: GO P_1_11 P_1_12
        3: GO P_1_12 P_1_13
        4: GO P_1_13 P_1_14
        5: GO P_1_14 P_2_14
        6: GO P_2_14 P_3_14
        7: GO P_3_14 P_3_13
        8: GO P_3_13 P_3_12
        9: GO P_3_12 P_3_11
       10: GO P_3_11 P_3_10
...
```

Of course, all the above can be adapted to run other planners or even other external tools.

## What does it mean that we must use 2/3 AI techniques? Do they all need to be part of the final submission?

Your final submission should have >= 1 techniques, and your repo & experiments should have the code & analysis of all the techniques you tried. Which should be at least 2 or 3 depending on the size of the team.

It's expected that some techniques that you try will not work well, so you can just report about them in your analysis. In terms of final submission, if you want to perform well, most likely you'll end up mixing a few techniques. 

If you have made a good attempt to use a technique and decided against it and this is documented well on the Wiki, then that _will count_. What wouldn't count is you saying: _"Well, we tried planning but it didn't work"_. But if you say: 

> "We tried planning and implemented it with X, Y and Z details. We submitted it to these contests, but the results were underwhelming as it timed out frequently. After trying to fix it with q and r, we decided to remove it from our final submission because of p. You can see the code in branch x and here are some experimental result that convinced us it was not worth it..." 

then that is a good submission that will count as an AI technique. 


## Can I use library or program X (e.g., tensorflow, FF planner, etc.)?

If it is a "standard" or very "common" library, most probably yes. Otherwise you can check with me and we can work out to make sure it is available in the cluster.

For example, some tools I have installed system-wide are:

- `TensorFlow`, `keras`, `sklearn`, `numpy`, `scipy` and `neat-python` libraries.
- The [FF planner](https://fai.cs.uni-saarland.de/hoffmann/ff.html) version 2.3 with the corresponding variations: `ff2.3` (the original one), and `ff2.3-suda` and `ff2.3-goldman`. 
    - The binary `ff` will point to the original `ff2.3` version.
- The [Metric-FF planner](https://fai.cs.uni-saarland.de/hoffmann/metric-ff.html). Here there are a few versions, depending which one you have used in your local machine from the Metric-FF web site. The binaries in the cluster are: `mff1`, `mff2`, and `mff2.1` for versions 1.0 (the original used in the competition), 2.0 and 2.1, respectively.
    - The binary `mff` will point to the original `mff1` version.

Again, please let me know if you want to use any other AI tool and we'll try to make it available!

The FF and Metric-FF planners with the adapted sources as per cluster install can all be found [here](https://github.com/ssardina-planning/ff-planners). You can also found here pre-compiled versions for Linux, so you can use them off-the-shelf without needing to compile them.
 

## I have performance problem with `generateSuccessor` in my search implementation, why?

A student post a very interesting question:

> I have a little performance issue regarding our A-star heuristic search agent performing on OfficeCapture. The behaviour is it stops 3-4 seconds to complete A-star search.

> As investigated, most of the time was executed on the generateSuccessor method, which belongs to `capture.py` which is out of our control.

> ![](img/getSuccessor-performance.png)

First that is a great work on using profiling to look into this issue!

If you look at what `generateSuccessor` is doing, you will see there is a fair amount of work going on. If you compare this to the search code used to generate maze distances in `distanceCalculator.py` (`computeDistances()`, line 110), you will see they aren't generating successors at all, but are still doing a search though the maze. You might want to consider whether that is an appropriate method to follow for your case. 

One thing that one would like to see is how many calls are being made to `generateSuccessor` in each search. If you are seeing about 100 then that is plausible given the map size. If you are seeing thousands then it's likely you are double checking some cells and might need to tweak your algorithm.

This shows that the transition function is not free :) and that there is a tradeoff between a good (informed) heuristic that reduces the number of generated nodes and the actual cost of that heuristic!


## I want to update an enemy position that's not in my sight range. I need to assign the position information in a copy of `gameState`. But I could only get an Agent Position not set.

You can do anything you want with the `gameState` you receive - it's only a copy of the real one. 



## The Berkeley site claims that observations are noisy unless the other agent is nearby, but when I call `getAgentPosition` it gives the exact location of any agent, including opponents. 

This is true only during `registerInitialState`, but then returns `None` as expected during `chooseAction`, thus aligned with what the Berkeley site says.

## What does the "Score Balance" mean?

It mans the sum of your winning (or losing) margins. 

E.g. You win one game by 20 points, then lose two by 4 points each. Your score balance is +12

## Is there any way to determine how long is left in a game? The Berkley spec it says 'games are limited to 1200 agent moves'. Will this limit also be the same for our tournament? 

Yes, our tournaments will be all of 1200 moves. But you can get the time left as follows:
You can access `state.data.timeleft` if you want,

```
timeRemaining = gameState.data.timeleft  
```


## Can I override the `X` (e.g., `makeObservation()`) method of `CaptureAgent`?

No in general unless you get the explicit written permission from the teaching staff. 

For example, if you override `makeObservation()` you would get to see beyond the rules of the game and have an unfair advantage, thus breaching the code of honor.

As a rule of thumb, anything that makes you think twice whether it's permitted, most likely it isn't.  I'll check for cases of overriding the inherited functions. 

If you want to do so nonetheless, you must get the written permission of the teaching staff to avoid breaching the code of honor.

## How to simulate opponent in MCTS?

There has been a few different conversations about how the enemy can be simulated in MCTS, so I thought I would collect a few different things in one place.

A common problem is that if the opponent is out of sight, then `gameState.getLegalActions(opponentIndex)` will return an error.

_Why is this?_

Following the stack trace below, we can see that in order to get the legal actions, the function needs to know the position of the enemy agent, so it can figure out which walls are adjacent. Since the enemy's position has been set to None in your version of the gameState, this fails.

 ```python
 File "capture.py", line 107, in getLegalActions
    return AgentRules.getLegalActions( self, agentIndex )
  File "capture.py", line 461, in getLegalActions
    possibleActions = Actions.getPossibleActions( conf, state.data.layout.walls )
  File "game.py", line 334, in getPossibleActions
    x, y = config.pos
AttributeError: 'NoneType' object has no attribute 'pos'
```

I just want it to make a random move, can't it do that without telling me the position?

* Unfortunately no, because if you can call a function that at some stage looks up the position, you would be able to access that data directly if you tried. Also consider the following: you want to know where the opponent is so you ask for it to generate 100 random possible actions for that opponent. You can then conclude that whichever directions don't appear in that list are blocked by walls, giving you information about the position.

**_Ok, so how do I make MCTS work then?_**

There are a number of options, but first we must take a step back and understand how the game simulation is running. The simulator itself has access to the true game state, with all agents positions. When it is time for your turn, it makes a copy, removes information about the true positions for any opponents out of range, and then passes it to you in the `chooseAction` call (or more precisely the `getAction` call but that can be ignored). So your `gameState` object is a copy, which is not then used for anything else in terms of the simulator. What this means is that you can do anything you want to it!

The standard MCTS algorithm assumes that the game is fully observable, so perhaps the most obvious this to do would be to pretend our game is fully observable. _How can we do that?_ Well, if you guess where the opponent is, you can 'place' the enemy there in your copy of gameState (the underlying data is hidden away in `gameState.data.agentStates[index].configuration.pos`). Having said this, it might not be the best idea to mess around with these deep internal variables. You might want to think about how you can 'pretend' the enemy is in that position without changing the actual gameState. This will depend on what exactly you are doing, because you might need a more or less accurate 'pretend scenario'.

Another option is to run a variant of MCTS which is designed for use in partially observable settings. There is at least one algorithm which has been tried in the literature which you can research.

Hope this helps, here are some links to other related posts: [@193](https://piazza.com/class/kbsmlzxg3k7418?cid=193) and [@199](https://piazza.com/class/kbsmlzxg3k7418?cid=199).

## The option `--numTraining` (or `-x`) option does not work, why?

We also wondered... here is the answer:

The simplest way to run multiple games for training purposes is with the following command: 

```shell
$ python3 capture.py --numGames 100 --quiet --delay-step 0
```

When using the  `--numTraining` argument, a new parameter is passed to your `createTeam()` method in `myTeam.py`, that is, unexpected and so can cause an error. 

To fix this, simply add a numTraining argument with a suitable default value:

```python
def createTeam(firstIndex, secondIndex, isRed,
               first = 'DummyAgent', second = 'DummyAgent', numTraining = 0):
```

The option `--numTraining` does not actually run multiple games, it just suppresses output for those number of games. 

So, the option is supposed to be used in conjunction with the `--numGames` argument which does specify the number of games to run. So, you would do something like:

```shell
$ python3 capture.py --numGames 1010 --numTraining 1000
```

to run 1010 games, of which the first 1000 will not be displayed graphically as they are counted as "training games". 

If you don't want to see any results, you can avoid `--numTraining` entirely and run:

```shell
$ python capture.py --numGames 1010 --quiet --delay-step 0
```

If you set `--numTraining` to be greater or equal to `--numGames`, your code will _fail_ at the very end with the error:

```python
    Traceback (most recent call last):
      File "capture.py", line 1117, in <module>
        save_score(games[0])
    IndexError: list index out of range
```

This is not a big problem, as it is after all your games have run and training has already occurred. However, if it bothers you (and it should bother you! ;-) ), you can comment out line 1116 in `capture.py` to fix it: `(save_score(games[0]))`.


## Can I perform training during the contest (in `agent.final(gameState)`)?

I will break this down into two parts:

Can we put some code in `agent.final(gameState)` to implement learning or logging or something else? Technically yes, that is allowed, but see point 2 for some serious limitations. Also be very careful that it does not take excessively long. Anything **beyond 10 seconds is definitely too long** - if you think this is going to be a problem feel free to discuss your particular use case with me directly in a private post or in a python lab/consultation time.

Is learning after a game going to help my agents in the competition? Here unfortunately the answer is no. In order to handle the large volume of games that are being played, the contest infrastructure generates all the jobs (i.e. pacman games such as team1 vs team2 on map 3) and then distributes them independently to a range of servers in a cluster. This means that each of your games is running in parallel, with no knowledge of the games that have come before it. Any learning that you perform during the contest is therefore constrained to that game alone.



