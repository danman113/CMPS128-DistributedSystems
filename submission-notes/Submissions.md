0. Preconditions - You have a project folder on your local machine.  

1. Create a file members.txt. It will contain one member per line, member being the ucsc id. e.g.
    ```shell
    $ cat members.txt
    nkini
    palvaro
    ```  

2. Create a contribution-notes.txt file. This can be empty until the moment of final submission.
    ```shell
    $ cat contribution-notes.txt
    palvaro
    created all the docker related files
    
    nkini
    wrote the web server app in python  
    ```

3. Create a local git repo (git init, add, commit)  

4. Create a bitbucket account https://bitbucket.org/account/signup/  

5. Create a team (NOTE: Do NOT create a repo before creating a team, it will be 'wasted')
    a. Team ID needs to be unique at bitbucket, but prefix it with cmps128 e.g. cmps128team1 or cmps128nkini
    b. Add team members nkini and palvaro  

6. Create a repository for the team. Ensure that it is private.  

7. Commit files to the repository
    ```shell
    cd /path/to/my/repo
    git remote add origin https://nikhilkini@bitbucket.org/cmps128TAtest/hw1.git
    git push -u origin --all # pushes up the repo and its refs for the first time
    git push -u origin --tags # pushes up any tags  
    ```

8. Create your Dockerfile, create your source folder for the server that will run in the docker image. Test output. Commit early, commit often.  

9. When you are satisfied with your solution (or when you nearly run out of time :/ ), 
submit the commit URL (see figure 4 to see how to obtain this) in this form : http://goo.gl/forms/WMHBIwVuud
