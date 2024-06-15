# Steps to create a minimal Github website:

This instruction module helps to build a minimal academic website hosted at Github. The instructions are written in a way so that one can install Git in a local machine, make the necessary changes locally, and then push everything to the Github from Command Prompt/ Terminal. 

0. **(Optional) Register:** Register a Github account at <https://github.com/signup>.

1.  **Create the website:** Create a new repository at <https://github.com/new>. Name it as \<yourGithubUsername\>.github.io

2.  **Clone:** Clone (download) it locally:

    0.  Ensure Git is installed, or see <https://github.com/git-guides/install-git>.

    1.  In the local machine, at the intended project location, open a terminal/command prompt.

    2.  Clone it using:

    ``` console
    git clone <https://github.com>/<yourGithubUsername>/<yourGithubUsername>.github.io
    ```

3.  **Create main.html file** In the minimal setup, Github hosts the "main.html" file at the root directory. A minimal file example can be found at [minexamplelink](https://github.com/dawranadeep/dawranadeep.github.io/blob/main/miscalleneous/minexample.html). Many other academic website templates can be found [here](<https://github.com/topics/academic-template>).

4.  **Push (upload) to Github:** Use the following code:

``` console
git add .
git commit -m "<some message>"
git push
```

5.  See updated website at \<yourGithubUsername\>.github.io



Note that, the push-pull job becomes significantly easier by using a GUI (such as Github Desktop <https://desktop.github.com>) or a multi-functional Git-enabled interface (such as Visual Studio code <https://code.visualstudio.com>).