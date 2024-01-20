Last login: Sun Jan 14 23:52:57 on ttys000
(base) shaktipandit@SHAKTIs-iMac ~ % git clone git@github.com:shaktipandit001/lab-bash.-New.git
Cloning into 'lab-bash.-New'...
The authenticity of host 'github.com (140.82.121.4)' can't be established.
ECDSA key fingerprint is SHA256:p2QAMXNIC1TJYWeIOttrVc98/R1BUFWu3/LiyKgUfQM.
Are you sure you want to continue connecting (yes/no/[fingerprint])? y
Please type 'yes', 'no' or the fingerprint: 'yes'
Please type 'yes', 'no' or the fingerprint: 
Host key verification failed.
fatal: Could not read from remote repository.

Please make sure you have the correct access rights
and the repository exists.
(base) shaktipandit@SHAKTIs-iMac ~ % git clone git@github.com:shaktipandit001/lab-bash.-New.git
Cloning into 'lab-bash.-New'...
The authenticity of host 'github.com (140.82.121.4)' can't be established.
ECDSA key fingerprint is SHA256:p2QAMXNIC1TJYWeIOttrVc98/R1BUFWu3/LiyKgUfQM.
Are you sure you want to continue connecting (yes/no/[fingerprint])? yes
Warning: Permanently added 'github.com,140.82.121.4' (ECDSA) to the list of known hosts.
git@github.com: Permission denied (publickey).
fatal: Could not read from remote repository.

Please make sure you have the correct access rights
and the repository exists.
(base) shaktipandit@SHAKTIs-iMac ~ % ls
Desktop			Pictures		firstlabgit.txt
Documents		Public			import random.py
Downloads		about.txt		lorem
Ironshakti		about.txtt		lorem_copy
Library			anaconda3		print("was up").py
Movies			example_firstrap	print('Hallo').py
Music			example_firstrap.txt	sed.txt
(base) shaktipandit@SHAKTIs-iMac ~ % touch firstlabgit.txt 
(base) shaktipandit@SHAKTIs-iMac ~ % ls
Desktop			Pictures		firstlabgit.txt
Documents		Public			import random.py
Downloads		about.txt		lorem
Ironshakti		about.txtt		lorem_copy
Library			anaconda3		print("was up").py
Movies			example_firstrap	print('Hallo').py
Music			example_firstrap.txt	sed.txt
(base) shaktipandit@SHAKTIs-iMac ~ % nano about.txt
(base) shaktipandit@SHAKTIs-iMac ~ % git add about.txt
fatal: not a git repository (or any of the parent directories): .git
(base) shaktipandit@SHAKTIs-iMac ~ % git commit -m "a txt file added"
fatal: not a git repository (or any of the parent directories): .git
(base) shaktipandit@SHAKTIs-iMac ~ % cat about.txt
I know its difficlut to learn first time in coding area.
(base) shaktipandit@SHAKTIs-iMac ~ % ls
Desktop			Pictures		firstlabgit.txt
Documents		Public			import random.py
Downloads		about.txt		lorem
Ironshakti		about.txtt		lorem_copy
Library			anaconda3		print("was up").py
Movies			example_firstrap	print('Hallo').py
Music			example_firstrap.txt	sed.txt
(base) shaktipandit@SHAKTIs-iMac ~ % cd Ironshakti
(base) shaktipandit@SHAKTIs-iMac Ironshakti % touch about_me.txt
(base) shaktipandit@SHAKTIs-iMac Ironshakti % ls
README.md	about_me.txt	about_me.txt#m	about_me.txtt
(base) shaktipandit@SHAKTIs-iMac Ironshakti % nano about_me.txt
(base) shaktipandit@SHAKTIs-iMac Ironshakti % cat about_me.txt
I know its hard to code, I am learning and I know it I wil kill it.

(base) shaktipandit@SHAKTIs-iMac Ironshakti % git add about_me.txt
(base) shaktipandit@SHAKTIs-iMac Ironshakti % git commit --m "a txt file added"
On branch main
Your branch is ahead of 'origin/main' by 1 commit.
  (use "git push" to publish your local commits)

Untracked files:
	about_me.txt#m
	about_me.txtt

nothing added to commit but untracked files present
(base) shaktipandit@SHAKTIs-iMac Ironshakti % git push 
Username for 'https://github.com': shakti pandit
Password for 'https://shakti pandit@github.com': 
remote: Invalid username or password.
fatal: Authentication failed for 'https://github.com/shaktipandit001/Ironshakti.git/'
(base) shaktipandit@SHAKTIs-iMac Ironshakti % 
(base) shaktipandit@SHAKTIs-iMac Ironshakti % git push
Username for 'https://github.com': shakti pandit
Password for 'https://shakti pandit@github.com': 
remote: Support for password authentication was removed on August 13, 2021.
remote: Please see https://docs.github.com/en/get-started/getting-started-with-git/about-remote-repositories#cloning-with-https-urls for information on currently recommended modes of authentication.
fatal: Authentication failed for 'https://github.com/shaktipandit001/Ironshakti.git/'
(base) shaktipandit@SHAKTIs-iMac Ironshakti % git status
On branch main
Your branch is ahead of 'origin/main' by 1 commit.
  (use "git push" to publish your local commits)

Untracked files:
  (use "git add <file>..." to include in what will be committed)
	about_me.txt#m
	about_me.txtt

nothing added to commit but untracked files present (use "git add" to track)
(base) shaktipandit@SHAKTIs-iMac Ironshakti % git add
Nothing specified, nothing added.
Maybe you wanted to say 'git add .'?
(base) shaktipandit@SHAKTIs-iMac Ironshakti % git commit -m
error: switch `m' requires a value
(base) shaktipandit@SHAKTIs-iMac Ironshakti % git push
Username for 'https://github.com': shakti
Password for 'https://shakti@github.com': 
remote: Support for password authentication was removed on August 13, 2021.
remote: Please see https://docs.github.com/en/get-started/getting-started-with-git/about-remote-repositories#cloning-with-https-urls for information on currently recommended modes of authentication.
fatal: Authentication failed for 'https://github.com/shaktipandit001/Ironshakti.git/'
(base) shaktipandit@SHAKTIs-iMac Ironshakti % git push
Username for 'https://github.com': shakti pandit
Password for 'https://shakti pandit@github.com': 
remote: Invalid username or password.
fatal: Authentication failed for 'https://github.com/shaktipandit001/Ironshakti.git/'
(base) shaktipandit@SHAKTIs-iMac Ironshakti % git push       
Username for 'https://github.com': shaktipandit001                      
Password for 'https://shaktipandit001@github.com': 
remote: Invalid username or password.
fatal: Authentication failed for 'https://github.com/shaktipandit001/Ironshakti.git/'
(base) shaktipandit@SHAKTIs-iMac Ironshakti % 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
zsh: command not found: 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
(base) shaktipandit@SHAKTIs-iMac Ironshakti % git push
Username for 'https://github.com': shaktipandit001
Password for 'https://shaktipandit001@github.com': 
#remote: Permission to shaktipandit001/Ironshakti.git denied to shaktipandit001.
fatal: unable to access 'https://github.com/shaktipandit001/Ironshakti.git/': The requested URL returned error: 403
(base) shaktipandit@SHAKTIs-iMac Ironshakti % gitpush
zsh: command not found: gitpush
(base) shaktipandit@SHAKTIs-iMac Ironshakti % git push
Username for 'https://github.com': shaktipandit001
Password for 'https://shaktipandit001@github.com': 
remote: Support for password authentication was removed on August 13, 2021.
remote: Please see https://docs.github.com/en/get-started/getting-started-with-git/about-remote-repositories#cloning-with-https-urls for information on currently recommended modes of authentication.
fatal: Authentication failed for 'https://github.com/shaktipandit001/Ironshakti.git/'
(base) shaktipandit@SHAKTIs-iMac Ironshakti % git clone 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
fatal: repository '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' does not exist
(base) shaktipandit@SHAKTIs-iMac Ironshakti % git clone
fatal: You must specify a repository to clone.

usage: git clone [<options>] [--] <repo> [<dir>]

    -v, --verbose         be more verbose
    -q, --quiet           be more quiet
    --progress            force progress reporting
    -n, --no-checkout     don't create a checkout
    --bare                create a bare repository
    --mirror              create a mirror repository (implies bare)
    -l, --local           to clone from a local repository
    --no-hardlinks        don't use local hardlinks, always copy
    -s, --shared          setup as shared repository
    --recursive ...       alias of --recurse-submodules
    --recurse-submodules[=<pathspec>]
                          initialize submodules in the clone
    -j, --jobs <n>        number of submodules cloned in parallel
    --template <template-directory>
                          directory from which templates will be used
    --reference <repo>    reference repository
    --reference-if-able <repo>
                          reference repository
    --dissociate          use --reference only while cloning
    -o, --origin <name>   use <name> instead of 'origin' to track upstream
    -b, --branch <branch>
                          checkout <branch> instead of the remote's HEAD
    -u, --upload-pack <path>
                          path to git-upload-pack on the remote
    --depth <depth>       create a shallow clone of that depth
    --shallow-since <time>
                          create a shallow clone since a specific time
    --shallow-exclude <revision>
                          deepen history of shallow clone, excluding rev
    --single-branch       clone only one branch, HEAD or --branch
    --no-tags             don't clone any tags, and make later fetches not to follow them
    --shallow-submodules  any cloned submodules will be shallow
    --separate-git-dir <gitdir>
                          separate git dir from working tree
    -c, --config <key=value>
                          set config inside the new repository
    --server-option <server-specific>
                          option to transmit
    -4, --ipv4            use IPv4 addresses only
    -6, --ipv6            use IPv6 addresses only
    --filter <args>       object filtering
    --remote-submodules   any cloned submodules will use their remote-tracking branch

(base) shaktipandit@SHAKTIs-iMac Ironshakti % git clone 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
fatal: repository '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' does not exist
(base) shaktipandit@SHAKTIs-iMac Ironshakti % curl --request GET \ --url "https://api.github.com/octocat" \ --header "Authorization: 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" \ --header "X-GitHub-Api-Version: 2022-11-28"
curl: (3) URL rejected: Malformed input to a URL function

               MMM.           .MMM
               MMMMMMMMMMMMMMMMMMM
               MMMMMMMMMMMMMMMMMMM      _______________________________________
              MMMMMMMMMMMMMMMMMMMMM    |                                       |
             MMMMMMMMMMMMMMMMMMMMMMM   | Non-blocking is better than blocking. |
            MMMMMMMMMMMMMMMMMMMMMMMM   |_   ___________________________________|
            MMMM::- -:::::::- -::MMMM    |/
             MM~:~ 00~:::::~ 00~:~MM
        .. MMMMM::.00:::+:::.00::MMMMM ..
              .MM::::: ._. :::::MM.
                 MMMM;:::::;MMMM
          -MM        MMMMMMM
          ^  M+     MMMMMMMMM
              MMMMMMM MM MM MM
                   MM MM MM MM
                   MM MM MM MM
                .~~MM~MM~MM~MM~~.
             ~~~~MM:~MM~~~MM~:MM~~~~
            ~~~~~~==~==~~~==~==~~~~~~
             ~~~~~~==~==~==~==~~~~~~
                 :~==~==~==~==~~
curl: (3) URL rejected: Malformed input to a URL function
curl: (3) URL rejected: Malformed input to a URL function
curl: (3) URL rejected: Malformed input to a URL function
curl: (3) URL rejected: Malformed input to a URL function
(base) shaktipandit@SHAKTIs-iMac Ironshakti % github_pat_11APWE4LI0FpNKzkoHXCQw_5pbAmIDg2NaZ2efMR3WWoyXlMAM3k2yVgbt88haTCoXAU2MKH57IAIQSLC
zsh: command not found: github_pat_11APWE4LI0FpNKzkoHXCQw_5pbAmIDg2NaZ2efMR3WWoyXlMAM3k2yVgbt88haTCoXAU2MKH57IAIQSLC
(base) shaktipandit@SHAKTIs-iMac Ironshakti % echo "https://github.com/ shaktipandit001 " > ~/.git-credentials
(base) shaktipandit@SHAKTIs-iMac Ironshakti % echo "https:// shaktipandit001 :Ironhack@github.com" >> ~/.git-credentials
(base) shaktipandit@SHAKTIs-iMac Ironshakti % git commit --m "a txt file added"
On branch main
On branch main
Your branch is ahead of 'origin/main' by 1 commit.
  (use "git push" to publish your local commits)

Untracked files:
	about_me.txt#m
	about_me.txtt

nothing added to commit but untracked files present
zsh: command not found: On
(base) shaktipandit@SHAKTIs-iMac Ironshakti % git push
Username for 'https://github.com': shaktipandit001
Password for 'https://shaktipandit001@github.com': 
remote: Support for password authentication was removed on August 13, 2021.
remote: Please see https://docs.github.com/en/get-started/getting-started-with-git/about-remote-repositories#cloning-with-https-urls for information on currently recommended modes of authentication.
fatal: Authentication failed for 'https://github.com/shaktipandit001/Ironshakti.git/'
(base) shaktipandit@SHAKTIs-iMac Ironshakti % git clone git@github.com:ironhack-labs/lab-git.git
Cloning into 'lab-git'...
Warning: Permanently added the ECDSA host key for IP address '140.82.121.3' to the list of known hosts.
git@github.com: Permission denied (publickey).
fatal: Could not read from remote repository.

Please make sure you have the correct access rights
and the repository exists.
(base) shaktipandit@SHAKTIs-iMac Ironshakti % git push
Username for 'https://github.com': shaktipandit001
Password for 'https://shaktipandit001@github.com': 
remote: Support for password authentication was removed on August 13, 2021.
remote: Please see https://docs.github.com/en/get-started/getting-started-with-git/about-remote-repositories#cloning-with-https-urls for information on currently recommended modes of authentication.
fatal: Authentication failed for 'https://github.com/shaktipandit001/Ironshakti.git/'
(base) shaktipandit@SHAKTIs-iMac Ironshakti % git push
Username for 'https://github.com': shaktipandit001
Password for 'https://shaktipandit001@github.com': 
remote: Support for password authentication was removed on August 13, 2021.
remote: Please see https://docs.github.com/en/get-started/getting-started-with-git/about-remote-repositories#cloning-with-https-urls for information on currently recommended modes of authentication.
fatal: Authentication failed for 'https://github.com/shaktipandit001/Ironshakti.git/'
(base) shaktipandit@SHAKTIs-iMac Ironshakti % git clone https://github.com/shaktipandit001/lab-bash-1.git
Cloning into 'lab-bash-1'...
remote: Enumerating objects: 43, done.
remote: Counting objects: 100% (2/2), done.
remote: Compressing objects: 100% (2/2), done.
remote: Total 43 (delta 0), reused 0 (delta 0), pack-reused 41
Unpacking objects: 100% (43/43), done.
(base) shaktipandit@SHAKTIs-iMac Ironshakti % git push
Username for 'https://github.com': shaktipandit001                        
Password for 'https://shaktipandit001@github.com': 
remote: Support for password authentication was removed on August 13, 2021.
remote: Please see https://docs.github.com/en/get-started/getting-started-with-git/about-remote-repositories#cloning-with-https-urls for information on currently recommended modes of authentication.
fatal: Authentication failed for 'https://github.com/shaktipandit001/Ironshakti.git/'
(base) shaktipandit@SHAKTIs-iMac Ironshakti % cd clone https://github.com/shaktipandit001/lab-bash-1.git
cd: string not in pwd: clone
(base) shaktipandit@SHAKTIs-iMac Ironshakti % git add.
git: 'add.' is not a git command. See 'git --help'.

The most similar command is
	add
(base) shaktipandit@SHAKTIs-iMac Ironshakti % git add
Nothing specified, nothing added.
Maybe you wanted to say 'git add .'?
(base) shaktipandit@SHAKTIs-iMac Ironshakti % git add .
(base) shaktipandit@SHAKTIs-iMac Ironshakti % Git commit -m 
error: switch `m' requires a value
(base) shaktipandit@SHAKTIs-iMac Ironshakti % 
(base) shaktipandit@SHAKTIs-iMac Ironshakti % 
(base) shaktipandit@SHAKTIs-iMac Ironshakti % 
(base) shaktipandit@SHAKTIs-iMac Ironshakti % 
(base) shaktipandit@SHAKTIs-iMac Ironshakti % 
(base) shaktipandit@SHAKTIs-iMac Ironshakti % 
(base) shaktipandit@SHAKTIs-iMac Ironshakti % 
(base) shaktipandit@SHAKTIs-iMac Ironshakti % 
(base) shaktipandit@SHAKTIs-iMac Ironshakti % 
(base) shaktipandit@SHAKTIs-iMac Ironshakti % Git commit -m «your comment»
error: pathspec 'comment»' did not match any file(s) known to git
(base) shaktipandit@SHAKTIs-iMac Ironshakti % Git commit -m «pushing file«
error: pathspec 'file«' did not match any file(s) known to git
(base) shaktipandit@SHAKTIs-iMac Ironshakti % 

(base) shaktipandit@SHAKTIs-iMac Ironshakti % Git commit -m «pushing file«
error: pathspec 'file«' did not match any file(s) known to git
(base) shaktipandit@SHAKTIs-iMac Ironshakti % git commit -m "pushing file"

[main d9a128b] pushing file
 Committer: SHAKTI PANDIT <shaktipandit@SHAKTIs-iMac.local>
Your name and email address were configured automatically based
on your username and hostname. Please check that they are accurate.
You can suppress this message by setting them explicitly. Run the
following command and follow the instructions in your editor to edit
your configuration file:

    git config --global --edit

After doing this, you may fix the identity used for this commit with:

    git commit --amend --reset-author

 3 files changed, 2 insertions(+)
 create mode 100644 .DS_Store
 create mode 100644 about_me.txt#m
 create mode 100644 about_me.txtt
(base) shaktipandit@SHAKTIs-iMac Ironshakti % cd dekstop
cd: no such file or directory: dekstop
(base) shaktipandit@SHAKTIs-iMac Ironshakti % ls
README.md	about_me.txt	about_me.txt#m	about_me.txtt
(base) shaktipandit@SHAKTIs-iMac Ironshakti % cd../
zsh: no such file or directory: cd../
(base) shaktipandit@SHAKTIs-iMac Ironshakti % git clone git@github.com:shaktipandit001/lab-bash.-New.git
Cloning into 'lab-bash.-New'...
git@github.com: Permission denied (publickey).
fatal: Could not read from remote repository.

Please make sure you have the correct access rights
and the repository exists.
(base) shaktipandit@SHAKTIs-iMac Ironshakti % ls
README.md	about_me.txt	about_me.txt#m	about_me.txtt
(base) shaktipandit@SHAKTIs-iMac Ironshakti % cd ../
(base) shaktipandit@SHAKTIs-iMac ~ % ls
Desktop			Public			import random.py
Documents		Untitled.ipynb		lorem
Downloads		about.txt		lorem_copy
Ironshakti		about.txtt		print("was up").py
Library			anaconda3		print('Hallo').py
Movies			example_firstrap	sed.txt
Music			example_firstrap.txt
Pictures		firstlabgit.txt
(base) shaktipandit@SHAKTIs-iMac ~ % git commit -m "pushing file"
fatal: not a git repository (or any of the parent directories): .git
(base) shaktipandit@SHAKTIs-iMac ~ % git add .
fatal: not a git repository (or any of the parent directories): .git
(base) shaktipandit@SHAKTIs-iMac ~ % cd path/to/your/git/repository

cd: no such file or directory: path/to/your/git/repository
(base) shaktipandit@SHAKTIs-iMac ~ % cd path/to/shaktipandit001/git/repository
cd: no such file or directory: path/to/shaktipandit001/git/repository
(base) shaktipandit@SHAKTIs-iMac ~ % git rev-parse --show-toplevel

fatal: not a git repository (or any of the parent directories): .git
(base) shaktipandit@SHAKTIs-iMac ~ % ls
Desktop			Public			import random.py
Documents		Untitled.ipynb		lorem
Downloads		about.txt		lorem_copy
Ironshakti		about.txtt		print("was up").py
Library			anaconda3		print('Hallo').py
Movies			example_firstrap	sed.txt
Music			example_firstrap.txt
Pictures		firstlabgit.txt
(base) shaktipandit@SHAKTIs-iMac ~ % git clone https://github.com/shaktipandit001/lab-bash-1.git
Cloning into 'lab-bash-1'...
remote: Enumerating objects: 43, done.
remote: Counting objects: 100% (2/2), done.
remote: Compressing objects: 100% (2/2), done.
remote: Total 43 (delta 0), reused 0 (delta 0), pack-reused 41
Unpacking objects: 100% (43/43), done.
(base) shaktipandit@SHAKTIs-iMac ~ % ls
Desktop			Public			import random.py
Documents		Untitled.ipynb		lab-bash-1
Downloads		about.txt		lorem
Ironshakti		about.txtt		lorem_copy
Library			anaconda3		print("was up").py
Movies			example_firstrap	print('Hallo').py
Music			example_firstrap.txt	sed.txt
Pictures		firstlabgit.txt
(base) shaktipandit@SHAKTIs-iMac ~ % cd /path/to/lab-bash-1/git/repository
cd: no such file or directory: /path/to/lab-bash-1/git/repository
(base) shaktipandit@SHAKTIs-iMac ~ % pwd

/Users/shaktipandit
(base) shaktipandit@SHAKTIs-iMac ~ % cd ~/lab-bash-1/git/repository

cd: no such file or directory: /Users/shaktipandit/lab-bash-1/git/repository
(base) shaktipandit@SHAKTIs-iMac ~ % cd ~

(base) shaktipandit@SHAKTIs-iMac ~ % find . -type d -name ".git" 2>/dev/null

./Desktop/lab-bash-1/.git
./Desktop/Z-Not nedded for study/Work /R-Course-HTML-Notes/.git

./example_firstrap/.git
./Ironshakti/.git
./lab-bash-1/.git
(base) shaktipandit@SHAKTIs-iMac ~ % 
(base) shaktipandit@SHAKTIs-iMac ~ % git add .
fatal: not a git repository (or any of the parent directories): .git
(base) shaktipandit@SHAKTIs-iMac ~ % cd /path/to/your/git/repository

cd: no such file or directory: /path/to/your/git/repository
(base) shaktipandit@SHAKTIs-iMac ~ % find ~ -type d -name ".git" 2>/dev/null

/Users/shaktipandit/Desktop/lab-bash-1/.git
/Users/shaktipandit/Desktop/Z-Not nedded for study/Work /R-Course-HTML-Notes/.git
/Users/shaktipandit/example_firstrap/.git
/Users/shaktipandit/Ironshakti/.git
/Users/shaktipandit/lab-bash-1/.git
(base) shaktipandit@SHAKTIs-iMac ~ % cd /path/to/actual/git/repository

cd: no such file or directory: /path/to/actual/git/repository
(base) shaktipandit@SHAKTIs-iMac ~ % Git add  .
fatal: not a git repository (or any of the parent directories): .git
(base) shaktipandit@SHAKTIs-iMac ~ % git add .
fatal: not a git repository (or any of the parent directories): .git
(base) shaktipandit@SHAKTIs-iMac ~ % ls
Desktop			Public			import random.py
Documents		Untitled.ipynb		lab-bash-1
Downloads		about.txt		lorem
Ironshakti		about.txtt		lorem_copy
Library			anaconda3		print("was up").py
Movies			example_firstrap	print('Hallo').py
Music			example_firstrap.txt	sed.txt
Pictures		firstlabgit.txt
(base) shaktipandit@SHAKTIs-iMac ~ % cd lab.bash-1
cd: no such file or directory: lab.bash-1
(base) shaktipandit@SHAKTIs-iMac ~ % cd lab-bash-1
(base) shaktipandit@SHAKTIs-iMac lab-bash-1 % git add .
(base) shaktipandit@SHAKTIs-iMac lab-bash-1 % git commit -m «pushing file»
error: pathspec 'file»' did not match any file(s) known to git
(base) shaktipandit@SHAKTIs-iMac lab-bash-1 % git commit -m «pushing file»
error: pathspec 'file»' did not match any file(s) known to git
(base) shaktipandit@SHAKTIs-iMac lab-bash-1 % Git commit -m «pushing file»
error: pathspec 'file»' did not match any file(s) known to git
(base) shaktipandit@SHAKTIs-iMac lab-bash-1 % ls

exercices	lorem		outputs
inputs		lorem-copy	readme.md
(base) shaktipandit@SHAKTIs-iMac lab-bash-1 % echo "Hello"    
Hello
(base) shaktipandit@SHAKTIs-iMac lab-bash-1 % mkdir new_dir
(base) shaktipandit@SHAKTIs-iMac lab-bash-1 % remdir new_dir
zsh: command not found: remdir
(base) shaktipandit@SHAKTIs-iMac lab-bash-1 % rmdir new_dir
(base) shaktipandit@SHAKTIs-iMac lab-bash-1 % cp lorem/sed.txt lorem-copy/

(base) shaktipandit@SHAKTIs-iMac lab-bash-1 % cp lorem/{at.txt,lorem.txt} lorem-copy/

(base) shaktipandit@SHAKTIs-iMac lab-bash-1 % cat lorem/sed.txt

Sed ut perspiciatis unde omnis iste natus error sit voluptatem accusantium doloremque laudantium, 
totam rem aperiam, eaque ipsa quae ab illo inventore veritatis et quasi architecto beatae vitae dicta sunt explicabo. 
Nemo enim ipsam voluptatem quia voluptas sit aspernatur aut odit aut fugit, 
sed quia consequuntur magni dolores eos qui ratione voluptatem sequi nesciunt. 
Neque porro quisquam est, qui dolorem ipsum quia dolor sit amet, consectetur, adipisci velit, 
sed quia non numquam eius modi tempora incidunt ut labore et dolore magnam aliquam quaerat voluptatem. 
Ut enim ad minima veniam, quis nostrum exercitationem ullam corporis suscipit laboriosam, 
nisi ut aliquid ex ea commodi consequatur? Quis autem vel eum iure reprehenderit qui in ea voluptate velit esse quam nihil molestiae consequatur, 
vel illum qui dolorem eum fugiat quo voluptas nulla pariatur?Homo homini lupus
(base) shaktipandit@SHAKTIs-iMac lab-bash-1 % ls
exercices	lorem		outputs
inputs		lorem-copy	readme.md
(base) shaktipandit@SHAKTIs-iMac lab-bash-1 % cd lorem
(base) shaktipandit@SHAKTIs-iMac lorem % ls
at.txt		at.txte		lorem.txt	sed.txt
(base) shaktipandit@SHAKTIs-iMac lorem % cd../
zsh: no such file or directory: cd../
(base) shaktipandit@SHAKTIs-iMac lorem % cd../
zsh: no such file or directory: cd../
(base) shaktipandit@SHAKTIs-iMac lorem % cd lab-bash-1
cd: no such file or directory: lab-bash-1
(base) shaktipandit@SHAKTIs-iMac lorem % cd /path/to/lab-bash-1

cd: no such file or directory: /path/to/lab-bash-1
(base) shaktipandit@SHAKTIs-iMac lorem % find / -type d -name "lab-bash-1" 2>/dev/null

/System/Volumes/Data/Users/shaktipandit/Desktop/lab-bash-1

/System/Volumes/Data/Users/shaktipandit/lab-bash-1

/Users/shaktipandit/Desktop/lab-bash-1
/Users/shaktipandit/lab-bash-1


(base) shaktipandit@SHAKTIs-iMac lorem % 
(base) shaktipandit@SHAKTIs-iMac lorem % 
(base) shaktipandit@SHAKTIs-iMac lorem % 
(base) shaktipandit@SHAKTIs-iMac lorem % 
(base) shaktipandit@SHAKTIs-iMac lorem % cd /correct/path/to/lab-bash-1

cd: no such file or directory: /correct/path/to/lab-bash-1
(base) shaktipandit@SHAKTIs-iMac lorem % pwd

/Users/shaktipandit/lab-bash-1/lorem
(base) shaktipandit@SHAKTIs-iMac lorem % pwd

/Users/shaktipandit/lab-bash-1/lorem
(base) shaktipandit@SHAKTIs-iMac lorem % cd relative/path/to/lab-bash-1

cd: no such file or directory: relative/path/to/lab-bash-1
(base) shaktipandit@SHAKTIs-iMac lorem % cd lab-bash-1

cd: no such file or directory: lab-bash-1
(base) shaktipandit@SHAKTIs-iMac lorem % ls
at.txt		at.txte		lorem.txt	sed.txt
(base) shaktipandit@SHAKTIs-iMac lorem % pwd
/Users/shaktipandit/lab-bash-1/lorem
(base) shaktipandit@SHAKTIs-iMac lorem % cd../
zsh: no such file or directory: cd../
(base) shaktipandit@SHAKTIs-iMac lorem % cd..
zsh: command not found: cd..
(base) shaktipandit@SHAKTIs-iMac lorem % ls
at.txt		at.txte		lorem.txt	sed.txt
(base) shaktipandit@SHAKTIs-iMac lorem % ´cd lab-bash-1
zsh: command not found: ´cd
(base) shaktipandit@SHAKTIs-iMac lorem % cd ..
(base) shaktipandit@SHAKTIs-iMac lab-bash-1 % cp lorem/{at.txt,lorem.txt} lorem-copy/
(base) shaktipandit@SHAKTIs-iMac lab-bash-1 % cat lorem/sed.txt
Sed ut perspiciatis unde omnis iste natus error sit voluptatem accusantium doloremque laudantium, 
totam rem aperiam, eaque ipsa quae ab illo inventore veritatis et quasi architecto beatae vitae dicta sunt explicabo. 
Nemo enim ipsam voluptatem quia voluptas sit aspernatur aut odit aut fugit, 
sed quia consequuntur magni dolores eos qui ratione voluptatem sequi nesciunt. 
Neque porro quisquam est, qui dolorem ipsum quia dolor sit amet, consectetur, adipisci velit, 
sed quia non numquam eius modi tempora incidunt ut labore et dolore magnam aliquam quaerat voluptatem. 
Ut enim ad minima veniam, quis nostrum exercitationem ullam corporis suscipit laboriosam, 
nisi ut aliquid ex ea commodi consequatur? Quis autem vel eum iure reprehenderit qui in ea voluptate velit esse quam nihil molestiae consequatur, 
vel illum qui dolorem eum fugiat quo voluptas nulla pariatur?Homo homini lupus
(base) shaktipandit@SHAKTIs-iMac lab-bash-1 % cat lorem/at.txt lorem/lorem.txt
At vero eos ET accusamus ET iusto odio dignissimos ducimus qui blanditiis praesentium voluptatum 
deleniti atque corrupti quos dolores ET quas molestias excepturi sint occaecati cupiditate non 
provident, similique sunt in culpa qui officia deserunt mollitia animi, id est laborum ET dolorum fuga. 
Et harum quidem rerum facilis est ET expedita distinctio. 
Nam libero tempore, cum soluta nobis est eligendi optio cumque nihil impedit quo minus id quod 
maxime placeat facere possimus, omnis voluptas assumenda est, omnis dolor repellendus. 
Temporibus autem quibusdam ET aut officiis debitis aut rerum necessitatibus saepe eveniET 
ut ET voluptates repudiandae sint ET molestiae non recusandae. 
Itaque earum rerum hic tenETur a sapiente delectus, ut aut reiciendis voluptatibus maiores 
alias consequatur aut perferendis doloribus asperiores repellat
Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do eiusmod tempor incididunt ut labore et dolore magna aliqua. 
Ut enim ad minim veniam, quis nostrud exercitation ullamco laboris nisi ut aliquip ex ea commodo consequat. 
Duis aute irure dolor in reprehenderit in voluptate velit esse cillum dolore eu fugiat nulla pariatur. 
Excepteur sint occaecat cupidatat non proident, sunt in culpa qui officia deserunt mollit anim id est laborum.%                                                 (base) shaktipandit@SHAKTIs-iMac lab-bash-1 % head -n 3 lorem-copy/sed.txt

Sed ut perspiciatis unde omnis iste natus error sit voluptatem accusantium doloremque laudantium, 
totam rem aperiam, eaque ipsa quae ab illo inventore veritatis et quasi architecto beatae vitae dicta sunt explicabo. 
Nemo enim ipsam voluptatem quia voluptas sit aspernatur aut odit aut fugit, 
(base) shaktipandit@SHAKTIs-iMac lab-bash-1 % tail -n 3 lorem-copy/sed.txt
Ut enim ad minima veniam, quis nostrum exercitationem ullam corporis suscipit laboriosam, 
nisi ut aliquid ex ea commodi consequatur? Quis autem vel eum iure reprehenderit qui in ea voluptate velit esse quam nihil molestiae consequatur, 
vel illum qui dolorem eum fugiat quo voluptas nulla pariatur?Homo homini lupus
(base) shaktipandit@SHAKTIs-iMac lab-bash-1 % head -n 3 lorem-copy/sed.txt

Sed ut perspiciatis unde omnis iste natus error sit voluptatem accusantium doloremque laudantium, 
totam rem aperiam, eaque ipsa quae ab illo inventore veritatis et quasi architecto beatae vitae dicta sunt explicabo. 
Nemo enim ipsam voluptatem quia voluptas sit aspernatur aut odit aut fugit, 
(base) shaktipandit@SHAKTIs-iMac lab-bash-1 % tail -n 3 lorem-copy/sed.txt

Ut enim ad minima veniam, quis nostrum exercitationem ullam corporis suscipit laboriosam, 
nisi ut aliquid ex ea commodi consequatur? Quis autem vel eum iure reprehenderit qui in ea voluptate velit esse quam nihil molestiae consequatur, 
vel illum qui dolorem eum fugiat quo voluptas nulla pariatur?Homo homini lupus
(base) shaktipandit@SHAKTIs-iMac lab-bash-1 % sed -i 's/et/ET/g' lorem/at.txt
cat lorem/at.txt
sed: 1: "lorem/at.txt": extra characters at the end of l command
At vero eos ET accusamus ET iusto odio dignissimos ducimus qui blanditiis praesentium voluptatum 
deleniti atque corrupti quos dolores ET quas molestias excepturi sint occaecati cupiditate non 
provident, similique sunt in culpa qui officia deserunt mollitia animi, id est laborum ET dolorum fuga. 
Et harum quidem rerum facilis est ET expedita distinctio. 
Nam libero tempore, cum soluta nobis est eligendi optio cumque nihil impedit quo minus id quod 
maxime placeat facere possimus, omnis voluptas assumenda est, omnis dolor repellendus. 
Temporibus autem quibusdam ET aut officiis debitis aut rerum necessitatibus saepe eveniET 
ut ET voluptates repudiandae sint ET molestiae non recusandae. 
Itaque earum rerum hic tenETur a sapiente delectus, ut aut reiciendis voluptatibus maiores 
alias consequatur aut perferendis doloribus asperiores repellat
(base) shaktipandit@SHAKTIs-iMac lab-bash-1 % whoami
shaktipandit
(base) shaktipandit@SHAKTIs-iMac lab-bash-1 % pwd
/Users/shaktipandit/lab-bash-1
(base) shaktipandit@SHAKTIs-iMac lab-bash-1 % ls lorem/*.txt
lorem/at.txt	lorem/lorem.txt	lorem/sed.txt
(base) shaktipandit@SHAKTIs-iMac lab-bash-1 % cat lorem/sed.txt | wc -l

       9
(base) shaktipandit@SHAKTIs-iMac lab-bash-1 % find . -name 'lorem*' -type f | wc -l

       2
(base) shaktipandit@SHAKTIs-iMac lab-bash-1 % read -p "Enter your name: " my_name
echo "Your name is: $my_name"
read: -p: no coprocess
Your name is: 
(base) shaktipandit@SHAKTIs-iMac lab-bash-1 % echo "Directory named $my_name will be created"
mkdir "$my_name"
Directory named  will be created
mkdir: .: No such file or directory
(base) shaktipandit@SHAKTIs-iMac lab-bash-1 % rmdir "$my_name"
rmdir: : No such file or directory
(base) shaktipandit@SHAKTIs-iMac lab-bash-1 % git add . 
(base) shaktipandit@SHAKTIs-iMac lab-bash-1 %  Git commit -m «your comment»
error: pathspec 'comment»' did not match any file(s) known to git
(base) shaktipandit@SHAKTIs-iMac lab-bash-1 %  Git commit -m «pushing files»
error: pathspec 'files»' did not match any file(s) known to git
(base) shaktipandit@SHAKTIs-iMac lab-bash-1 % git commit -m "pushing files"

[master 5f8bd6a] pushing files
 Committer: SHAKTI PANDIT <shaktipandit@SHAKTIs-iMac.local>
Your name and email address were configured automatically based
on your username and hostname. Please check that they are accurate.
You can suppress this message by setting them explicitly. Run the
following command and follow the instructions in your editor to edit
your configuration file:

    git config --global --edit

After doing this, you may fix the identity used for this commit with:

    git commit --amend --reset-author

 3 files changed, 23 insertions(+)
 create mode 100755 lorem-copy/at.txt
 create mode 100755 lorem-copy/lorem.txt
 create mode 100755 lorem-copy/sed.txt
(base) shaktipandit@SHAKTIs-iMac lab-bash-1 % git remote set-url origin https://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@github.com/shaktipandit001/NAME_OF_THE_REPO
(base) shaktipandit@SHAKTIs-iMac lab-bash-1 % git push
remote: Repository not found.
fatal: repository 'https://github.com/shaktipandit001/NAME_OF_THE_REPO/' not found
(base) shaktipandit@SHAKTIs-iMac lab-bash-1 % # Set the remote URL
git remote set-url origin https://github.com/shaktipandit001/NAME_OF_THE_REPO.git

# Push changes to the repository
git push -u origin main

zsh: command not found: #
zsh: command not found: #
error: src refspec main does not match any
error: failed to push some refs to 'https://github.com/shaktipandit001/NAME_OF_THE_REPO.git'
(base) shaktipandit@SHAKTIs-iMac lab-bash-1 % git remote set-url origin https://github.com/shaktipandit001/NAME_OF_THE_REPO.git
(base) shaktipandit@SHAKTIs-iMac lab-bash-1 % git push -u origin main
error: src refspec main does not match any
error: failed to push some refs to 'https://github.com/shaktipandit001/NAME_OF_THE_REPO.git'
(base) shaktipandit@SHAKTIs-iMac lab-bash-1 % git branch

* master
(base) shaktipandit@SHAKTIs-iMac lab-bash-1 % git branch main

(base) shaktipandit@SHAKTIs-iMac lab-bash-1 % git checkout main

Switched to branch 'main'
(base) shaktipandit@SHAKTIs-iMac lab-bash-1 % git commit -m "Your commit message"

On branch main
nothing to commit, working tree clean
(base) shaktipandit@SHAKTIs-iMac lab-bash-1 % git push -u origin main

Username for 'https://github.com': ^[[32~
Password for 'https://@github.com': 
remote: Invalid username or password.
fatal: Authentication failed for 'https://github.com/shaktipandit001/NAME_OF_THE_REPO.git/'
(base) shaktipandit@SHAKTIs-iMac lab-bash-1 % git push -u origin main

Username for 'https://github.com': shaktipandit001
Password for 'https://shaktipandit001@github.com': 
remote: Repository not found.
fatal: repository 'https://github.com/shaktipandit001/NAME_OF_THE_REPO.git/' not found
(base) shaktipandit@SHAKTIs-iMac lab-bash-1 % # Set the remote URL
git remote set-url origin https://github.com/shaktipandit001/lab-bash.-New.git 
zsh: command not found: #
(base) shaktipandit@SHAKTIs-iMac lab-bash-1 % git push
fatal: The current branch main has no upstream branch.
To push the current branch and set the remote as upstream, use

    git push --set-upstream origin main

(base) shaktipandit@SHAKTIs-iMac lab-bash-1 % git push --set-upstream origin main

Username for 'https://github.com': shaktipandit001@gmail.com
Password for 'https://shaktipandit001@gmail.com@github.com': 
remote: Support for password authentication was removed on August 13, 2021.
remote: Please see https://docs.github.com/en/get-started/getting-started-with-git/about-remote-repositories#cloning-with-https-urls for information on currently recommended modes of authentication.
fatal: Authentication failed for 'https://github.com/shaktipandit001/lab-bash.-New.git/'
(base) shaktipandit@SHAKTIs-iMac lab-bash-1 % git remote remove origin
(base) shaktipandit@SHAKTIs-iMac lab-bash-1 % git remote add origin https://github.com/shaktipandit001/lab-bash.-New.git
(base) shaktipandit@SHAKTIs-iMac lab-bash-1 % git push -u origin main
Username for 'https://github.com': shakti.pandit001@gmail.com
Password for 'https://shakti.pandit001@gmail.com@github.com': 
remote: Support for password authentication was removed on August 13, 2021.
remote: Please see https://docs.github.com/en/get-started/getting-started-with-git/about-remote-repositories#cloning-with-https-urls for information on currently recommended modes of authentication.
fatal: Authentication failed for 'https://github.com/shaktipandit001/lab-bash.-New.git/'
(base) shaktipandit@SHAKTIs-iMac lab-bash-1 % 
(base) shaktipandit@SHAKTIs-iMac lab-bash-1 % git remote remove origin
(base) shaktipandit@SHAKTIs-iMac lab-bash-1 % git remote add origin https://github.com/shaktipandit001/lab-bash.-New.git
(base) shaktipandit@SHAKTIs-iMac lab-bash-1 % git push -u origin main
Username for 'https://github.com': shaktipandit001
Password for 'https://shaktipandit001@github.com': 
remote: Support for password authentication was removed on August 13, 2021.
remote: Please see https://docs.github.com/en/get-started/getting-started-with-git/about-remote-repositories#cloning-with-https-urls for information on currently recommended modes of authentication.
fatal: Authentication failed for 'https://github.com/shaktipandit001/lab-bash.-New.git/'
(base) shaktipandit@SHAKTIs-iMac lab-bash-1 % git config --global credential.helper cache

(base) shaktipandit@SHAKTIs-iMac lab-bash-1 % git config --global credential.helper 'cache --timeout=3600'  # 1 hour timeout

usage: git config [<options>]

Config file location
    --global              use global config file
    --system              use system config file
    --local               use repository config file
    --worktree            use per-worktree config file
    -f, --file <file>     use given config file
    --blob <blob-id>      read config from given blob object

Action
    --get                 get value: name [value-regex]
    --get-all             get all values: key [value-regex]
    --get-regexp          get values for regexp: name-regex [value-regex]
    --get-urlmatch        get value specific for the URL: section[.var] URL
    --replace-all         replace all matching variables: name value [value_regex]
    --add                 add a new variable: name value
    --unset               remove a variable: name [value-regex]
    --unset-all           remove all matches: name [value-regex]
    --rename-section      rename section: old-name new-name
    --remove-section      remove a section: name
    -l, --list            list all
    -e, --edit            open an editor
    --get-color           find the color configured: slot [default]
    --get-colorbool       find the color setting: slot [stdout-is-tty]

Type
    -t, --type <>         value is given this type
    --bool                value is "true" or "false"
    --int                 value is decimal number
    --bool-or-int         value is --bool or --int
    --path                value is a path (file or directory name)
    --expiry-date         value is an expiry date

Other
    -z, --null            terminate values with NUL byte
    --name-only           show variable names only
    --includes            respect include directives on lookup
    --show-origin         show origin of config (file, standard input, blob, command line)
    --default <value>     with --get, use default value when missing entry

(base) shaktipandit@SHAKTIs-iMac lab-bash-1 % git remote remove origin
(base) shaktipandit@SHAKTIs-iMac lab-bash-1 % git remote add origin https://github.com/shaktipandit001/lab-bash.-New.git
(base) shaktipandit@SHAKTIs-iMac lab-bash-1 % git push -u origin main
Username for 'https://github.com': shaktipandit001
Password for 'https://shaktipandit001@github.com': 
remote: Support for password authentication was removed on August 13, 2021.
remote: Please see https://docs.github.com/en/get-started/getting-started-with-git/about-remote-repositories#cloning-with-https-urls for information on currently recommended modes of authentication.
fatal: Authentication failed for 'https://github.com/shaktipandit001/lab-bash.-New.git/'
(base) shaktipandit@SHAKTIs-iMac lab-bash-1 % https://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github.com/shaktipandit001/lab-bash-1.git
zsh: no such file or directory: https://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github.com/shaktipandit001/lab-bash-1.git
(base) shaktipandit@SHAKTIs-iMac lab-bash-1 % git add .
(base) shaktipandit@SHAKTIs-iMac lab-bash-1 % Git commit -m «your comment»
error: pathspec 'comment»' did not match any file(s) known to git
(base) shaktipandit@SHAKTIs-iMac lab-bash-1 % git commit -m "your comment"

On branch main
nothing to commit, working tree clean
(base) shaktipandit@SHAKTIs-iMac lab-bash-1 % git remote set-url origin https://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github.com/shaktipandit001/lab-bash-1.git
(base) shaktipandit@SHAKTIs-iMac lab-bash-1 % git push
fatal: The current branch main has no upstream branch.
To push the current branch and set the remote as upstream, use

    git push --set-upstream origin main

(base) shaktipandit@SHAKTIs-iMac lab-bash-1 % git push --set-upstream origin main

fatal: unable to access 'https://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github.com/shaktipandit001/lab-bash-1.git/': Could not resolve host: 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github.com
(base) shaktipandit@SHAKTIs-iMac lab-bash-1 % git remote remove origin  
(base) shaktipandit@SHAKTIs-iMac lab-bash-1 % git remote add origin https://github.com/shaktipandit001/lab-bash-1.git
(base) shaktipandit@SHAKTIs-iMac lab-bash-1 % git push -u origin main
Username for 'https://github.com': shaktipandit001
Password for 'https://shaktipandit001@github.com': 
remote: Support for password authentication was removed on August 13, 2021.
remote: Please see https://docs.github.com/en/get-started/getting-started-with-git/about-remote-repositories#cloning-with-https-urls for information on currently recommended modes of authentication.
fatal: Authentication failed for 'https://github.com/shaktipandit001/lab-bash-1.git/'
(base) shaktipandit@SHAKTIs-iMac lab-bash-1 % git push -u origin main
Username for 'https://github.com': shaktipandit001
Password for 'https://shaktipandit001@github.com': 
remote: Permission to shaktipandit001/lab-bash-1.git denied to shaktipandit001.
fatal: unable to access 'https://github.com/shaktipandit001/lab-bash-1.git/': The requested URL returned error: 403
(base) shaktipandit@SHAKTIs-iMac lab-bash-1 % git push -u origin main
Username for 'https://github.com': shaktipandit001
Password for 'https://shaktipandit001@github.com': 
remote: Permission to shaktipandit001/lab-bash-1.git denied to shaktipandit001.
fatal: unable to access 'https://github.com/shaktipandit001/lab-bash-1.git/': The requested URL returned error: 403
(base) shaktipandit@SHAKTIs-iMac lab-bash-1 % git clone git@github.com:ironhack-labs/lab-bash.git
Cloning into 'lab-bash'...
git@github.com: Permission denied (publickey).
fatal: Could not read from remote repository.

Please make sure you have the correct access rights
and the repository exists.
(base) shaktipandit@SHAKTIs-iMac lab-bash-1 % git add .
(base) shaktipandit@SHAKTIs-iMac lab-bash-1 % Git commit -m «your comment»
error: pathspec 'comment»' did not match any file(s) known to git
(base) shaktipandit@SHAKTIs-iMac lab-bash-1 % git commit -m "your comment"

On branch main
nothing to commit, working tree clean
(base) shaktipandit@SHAKTIs-iMac lab-bash-1 %  git remote set-url origin https://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github.com/shaktipandit001/lab-bash-1.git
(base) shaktipandit@SHAKTIs-iMac lab-bash-1 % git push -u origin main
fatal: unable to access 'https://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github.com/shaktipandit001/lab-bash-1.git/': Could not resolve host: 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github.com
(base) shaktipandit@SHAKTIs-iMac lab-bash-1 % git push
fatal: The current branch main has no upstream branch.
To push the current branch and set the remote as upstream, use

    git push --set-upstream origin main

(base) shaktipandit@SHAKTIs-iMac lab-bash-1 % git push --set-upstream origin main
fatal: unable to access 'https://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github.com/shaktipandit001/lab-bash-1.git/': Could not resolve host: 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github.com
(base) shaktipandit@SHAKTIs-iMac lab-bash-1 % git push --set-upstream origin main

fatal: unable to access 'https://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github.com/shaktipandit001/lab-bash-1.git/': Could not resolve host: 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github.com
(base) shaktipandit@SHAKTIs-iMac lab-bash-1 % git remote -v

origin	https://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github.com/shaktipandit001/lab-bash-1.git (fetch)
origin	https://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github.com/shaktipandit001/lab-bash-1.git (push)
(base) shaktipandit@SHAKTIs-iMac lab-bash-1 % git remote set-url origin https://github.com/shaktipandit001/lab-bash-1.git

(base) shaktipandit@SHAKTIs-iMac lab-bash-1 % git push --set-upstream origin main

Username for 'https://github.com': shaktipandit001
Password for 'https://shaktipandit001@github.com': 
remote: Permission to shaktipandit001/lab-bash-1.git denied to shaktipandit001.
fatal: unable to access 'https://github.com/shaktipandit001/lab-bash-1.git/': The requested URL returned error: 403
(base) shaktipandit@SHAKTIs-iMac lab-bash-1 % 
Username for 'https://github.com': shaktipandit001
Password for 'https://shaktipandit001@github.com':
remote: Permission to shaktipandit001/lab-bash-1.git denied to shaktipandit001.
fatal: unable to access 'https://github.com/shaktipandit001/lab-bash-1.git/': The requested URL returned error: 403
zsh: command not found: Username
zsh: command not found: Password
zsh: command not found: remote:
zsh: command not found: fatal:
(base) shaktipandit@SHAKTIs-iMac lab-bash-1 % git push --set-upstream origin main
Username for 'https://github.com': shaktipandit001
Password for 'https://shaktipandit001@github.com': 
remote: Support for password authentication was removed on August 13, 2021.
remote: Please see https://docs.github.com/en/get-started/getting-started-with-git/about-remote-repositories#cloning-with-https-urls for information on currently recommended modes of authentication.
fatal: Authentication failed for 'https://github.com/shaktipandit001/lab-bash-1.git/'
(base) shaktipandit@SHAKTIs-iMac lab-bash-1 % git credential reject

git push -u origin main
warning: invalid credential line: git push -u origin main
fatal: unable to read credential from stdin
(base) shaktipandit@SHAKTIs-iMac lab-bash-1 % git push -u origin main

Username for 'https://github.com': shaktipandit001
Password for 'https://shaktipandit001@github.com': 
remote: Permission to shaktipandit001/lab-bash-1.git denied to shaktipandit001.
fatal: unable to access 'https://github.com/shaktipandit001/lab-bash-1.git/': The requested URL returned error: 403
(base) shaktipandit@SHAKTIs-iMac lab-bash-1 % 
