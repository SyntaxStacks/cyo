Rackspace CYO Project
=====================

Welcome to the Rackspace "Choose Your Own Adventure" Game.

Introduction
------------
This project uses the AngularJS CYO HTML engine.
CYO uses Angular directives to create rich storytelling experiences with an extremely easy-to-remember syntax.
For samples and instructions on how the AngularJS CYO HTML engine works <a target="_new" href="http://danielstern.github.io/cyo/">check out the project page</a>.

How to contribute to the game
-----------------------------
- Clone this repository in a project directory:

    ```
    $ mkdir projectdir
    $ cd projectdir
    $ git clone git@github.com:rackerlabs/cyo.git .
    ```

- Take a look at the instructions and samples in the <a target="_new" href="http://danielstern.github.io/cyo/">CYO engine project page</a> for ideas on how to code your story pages / chapters
- Make a git branch by entering in your project directory:

    ```
    $ git checkout -b branchname
    ```

- Put HTML files with your story chapters / pages to the `racker_cyo/story` folder.  Adding cool media stuff, animation, etc. is HIGHLY DESIRED!
- Put cool media stuff (video, images, audio, whatever) in the `racker_cyo/assets` folder
- Put any javascript libraries you need for your cool stuff in the `racker_cyo/lib` folder
- Put any cool AngularJS code you want to make your story chapters / pages awesome in `racker_cyo/scripts`
- Add a `<script src="yourJSfile.js type="text/javascript"></script>` reference tag to any new javascript files you add
- Add any css libraries or app files in `racker_cyo/assets/styles`
- Add a `<link href="yourcss.css" rel="stylesheet" type="text/css">` reference tag to any new css files you add
- After your finished, add the changes,  commit the changes and push to your branch:

    ```
    $ git add --all
    $ git commit -m"a short message about the changes"
    $ git push origin branchname
    ```

- Create a <a target="_new" href="https://help.github.com/articles/creating-a-pull-request">Pull Request</a>
- Email <a href="mailto:rackspace-cyo@lists.rackspace.com?Subject=Pull Request Submitted" target="_top">rackspace-cyo@lists.rackspace.com</a> and ask the group to review the PR (Pull Request)
- Once two members have approved the PR, it can be merged into the master branch

Running the game
----------------
Just open the `racker_cyo/index.html` file in a browser!

Game
----
TBD - figuring out the best place to host this

Suggestions
-----------
This game is an open collaboration!  Please email any suggestions on how to make it better to the <a href="mailto:rackspace-cyo@lists.rackspace.com?Subject=Game Suggestion(s)" target="_top">rackspace-cyo@lists.rackspace.com</a>

Questions?  Help?
----------------
For any questions or help email <a href="mailto:rackspace-cyo@lists.rackspace.com?Subject=Question" target="_top">rackspace-cyo@lists.rackspace.com</a>

Learning Resources
------------------
- AngularJS: https://github.com/jmcunningham/AngularJS-Learning
- CSS: http://webdesign.tutsplus.com/tutorials/the-best-way-to-learn-css--webdesign-11906
- HTML5: http://www.html5rocks.com/en/resources

*CYO was created by Daniel Stern*