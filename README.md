# Code to interact between Github and Local Machine

## clone repository. 
git clone git@github.com:debajyoti-ghosh/interaction-b-w-local-Machine-and-Github.git

## trach changes made in local machine.
git status

## add changes
git add .

## Save changes in local git
'here you will face some difficulty at the begining. As you are going to use ["git commit -m "Instruction   Codes" -m "Codes to be used are added from local machine""] it will give - 
    Author identity unknown

    *** Please tell me who you are.

    Run

      git config --global user.email "you@example.com"
      git config --global user.name "Your Name"

    to set your account's default identity.
    Omit --global to set the identity only in this repository.

    fatal: unable to auto-detect email address (got 'Papai@DESKTOP-FJL2QT9.(none)')
so you need to set the author of your local machine
### Set Author
    git config --global user.email "debxxxxxxxxxxx7@xxx.com"
    git config --global user.name "dxxxxxxxx-xxxxh"
    to set your account's default identity.
    Omit --global to set the identity only in this repository.

Now use - git commit -m "Instruction   Codes" -m "Codes to be used are added from local machine"

## Upload to Github
git push origin master [all time]
    git push -u origin master [1st time]
    git push [next time onwards]

Happy coding...