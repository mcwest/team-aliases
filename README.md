# Team aliases for polyglot developers (currently supports groovy/gradle and angular/gulp) 
# Developed by Brian Westrich (bw@mcwest.com) and Rob Danek (rdanek@mcwest.com, rdanek@gmail.com) 

## Key commands
### building with multiple build tools (maven, gradle, grunt, gulp) 
      utest: run unit tests
      run: run application
      go: pre-commit (clean build, run unit and functional tests)
      build: build deployable artifact 
      
### working with git 
      git new-branch: create a branch
      git addall: add all to git
      gsp: git smart pull
      git create-pull-request: create a (bitbucket) pull request
      see gitconfig-aliases for complete list

### other commands (tool specific)
      refresh: run gradle refresh 
      rgo: run gradle refresh, then run 'go'
      j{#} (where # = 6, 7, or 8): set Java version
      gsp: git smart-pull that does a "smarter" pull (handles upstream branching and possibly stashes changes if needed)
      gs: git status -sb, nicer git status display.

### updating aliases (both team and individual)
      ea: edit team aliases (do a git commit and push to share with team)
      eb: edit bash_profile
      
## To install
* add commands in sample-include-in-bash-profile to .bash_profile
* source ~./bash_profile

## To use git-smart (called by the gsp alias), install it with gem as follows:
* sudo gem install git-smart

## More git aliases
* copy the aliases from gitconfig-aliases to your ~/.gitconfig file.  Then these can be used such as "git co" instead of "git checkout".

