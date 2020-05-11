Workshop for Creating a Pull Request

This repo is to show how to cooperate in a team with pull requests. Follow these steps:

1. Find the <code>Fork</code> button, and click it to folk this repo under your usernam, Github will guide you to your clone repo, remember the URL of your repo, this would be required in step 3.
2. Open <code>git bash</code>, **DON'T** change the folder this time, just stay at your home directory which is displayed as a <code>~</code> in the prompt.
3. In <code>git bash</code>, execute
    ```
    git clone $URL
    ```
    and replace <code>$URL</code> with the URL of your clone repo in step 1.
4. Execute these commands one by one in <code>git bash</code> to create a commit and push to your repo. Git will ask for your username and password when pushing.
    ```bash
    cd demo-fork-and-pr
    echo 'helloworld' > 1.txt
    git add 1.txt
    git commit -m 'commit log for 1.txt'
    git push
    ```
5. Now back to the browser, on your clone repo, you'll find a <code>Pull requests</code> tab. Click on it and create a new pull request. Try to fill the form by your own and submit.

Then a pull request is sent to me, and that's it.