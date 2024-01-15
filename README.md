# lab-bash.-New
Lab work
Last login: Sun Jan 14 22:27:25 on ttys000
(base) shaktipandit@SHAKTIs-iMac ~ % ls
Desktop			Pictures		firstlabgit.txt
Documents		Public			import random.py
Downloads		about.txt		lorem
Ironshakti		about.txtt		print("was up").py
Library			anaconda3		print('Hallo').py
Movies			example_firstrap
Music			example_firstrap.txt
(base) shaktipandit@SHAKTIs-iMac ~ % git clone exercises  inputs  lorem  lorem-copy  modules  outputs  README.md
fatal: Too many arguments.

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

(base) shaktipandit@SHAKTIs-iMac ~ % ls
Desktop			Pictures		firstlabgit.txt
Documents		Public			import random.py
Downloads		about.txt		lorem
Ironshakti		about.txtt		print("was up").py
Library			anaconda3		print('Hallo').py
Movies			example_firstrap
Music			example_firstrap.txt
(base) shaktipandit@SHAKTIs-iMac ~ % echo Hello!
Hello!
(base) shaktipandit@SHAKTIs-iMac ~ % git new_dir
git: 'new_dir' is not a git command. See 'git --help'.
(base) shaktipandit@SHAKTIs-iMac ~ % mkdir new_dir
(base) shaktipandit@SHAKTIs-iMac ~ % ls
Desktop			Pictures		firstlabgit.txt
Documents		Public			import random.py
Downloads		about.txt		lorem
Ironshakti		about.txtt		new_dir
Library			anaconda3		print("was up").py
Movies			example_firstrap	print('Hallo').py
Music			example_firstrap.txt
(base) shaktipandit@SHAKTIs-iMac ~ % rmdir new_dir
(base) shaktipandit@SHAKTIs-iMac ~ % ls
Desktop			Pictures		firstlabgit.txt
Documents		Public			import random.py
Downloads		about.txt		lorem
Ironshakti		about.txtt		print("was up").py
Library			anaconda3		print('Hallo').py
Movies			example_firstrap
Music			example_firstrap.txt
(base) shaktipandit@SHAKTIs-iMac ~ % cp sed.txt                          
usage: cp [-R [-H | -L | -P]] [-fi | -n] [-apvXc] source_file target_file
       cp [-R [-H | -L | -P]] [-fi | -n] [-apvXc] source_file ... target_directory
(base) shaktipandit@SHAKTIs-iMac ~ % cp lorem/sed.txt
usage: cp [-R [-H | -L | -P]] [-fi | -n] [-apvXc] source_file target_file
       cp [-R [-H | -L | -P]] [-fi | -n] [-apvXc] source_file ... target_directory
(base) shaktipandit@SHAKTIs-iMac ~ % cp -a lorem sed.txt
(base) shaktipandit@SHAKTIs-iMac ~ % ./ lorem_copy
zsh: permission denied: ./
(base) shaktipandit@SHAKTIs-iMac ~ % ./ lorem_copy.git
zsh: permission denied: ./
(base) shaktipandit@SHAKTIs-iMac ~ % p ./ lorem_copy
zsh: command not found: p
(base) shaktipandit@SHAKTIs-iMac ~ % mv lorem_copy
usage: mv [-f | -i | -n] [-v] source target
       mv [-f | -i | -n] [-v] source ... directory
(base) shaktipandit@SHAKTIs-iMac ~ % git mv lorem/sed.txt lorem_copy/
fatal: not a git repository (or any of the parent directories): .git
(base) shaktipandit@SHAKTIs-iMac ~ % mv lorem/sed.txt lorem_copy/
mv: rename lorem/sed.txt to lorem_copy/: No such file or directory
(base) shaktipandit@SHAKTIs-iMac ~ % ls
Desktop			Pictures		firstlabgit.txt(nr. %............................................. 5 did not find the resuld going to solve with CTA
Documents		Public			import random.py
Downloads		about.txt		lorem
Ironshakti		about.txtt		print("was up").py
Library			anaconda3		print('Hallo').py
Movies			example_firstrap	sed.txt
Music			example_firstrap.txt
(base) shaktipandit@SHAKTIs-iMac ~ % cd lorem
(base) shaktipandit@SHAKTIs-iMac lorem % touch sed.txt
(base) shaktipandit@SHAKTIs-iMac lorem % ls
sed.txt
(base) shaktipandit@SHAKTIs-iMac lorem % cd ../
(base) shaktipandit@SHAKTIs-iMac ~ % mkdir lorem_copy 
(base) shaktipandit@SHAKTIs-iMac ~ % ls
Desktop			Pictures		firstlabgit.txt
Documents		Public			import random.py
Downloads		about.txt		lorem
Ironshakti		about.txtt		lorem_copy
Library			anaconda3		print("was up").py
Movies			example_firstrap	print('Hallo').py
Music			example_firstrap.txt	sed.txt
(base) shaktipandit@SHAKTIs-iMac ~ % mv lorem/sed.txt lorem_copy/
(base) shaktipandit@SHAKTIs-iMac ~ % ls
Desktop			Pictures		firstlabgit.txt
Documents		Public			import random.py
Downloads		about.txt		lorem
Ironshakti		about.txtt		lorem_copy
Library			anaconda3		print("was up").py
Movies			example_firstrap	print('Hallo').py
Music			example_firstrap.txt	sed.txt
(base) shaktipandit@SHAKTIs-iMac ~ % cd lorem_copy
(base) shaktipandit@SHAKTIs-iMac lorem_copy % ls
sed.txt
(base) shaktipandit@SHAKTIs-iMac lorem_copy % #..cp ~/test.txt ~/folder1 && cp ~/test.txt ~/folder2

zsh: command not found: #..cp
(base) shaktipandit@SHAKTIs-iMac lorem_copy % cd lorem
cd: no such file or directory: lorem
(base) shaktipandit@SHAKTIs-iMac lorem_copy % ls
sed.txt
(base) shaktipandit@SHAKTIs-iMac lorem_copy % mkdir sed2.txt
(base) shaktipandit@SHAKTIs-iMac lorem_copy % ls
sed.txt		sed2.txt
(base) shaktipandit@SHAKTIs-iMac lorem_copy % cd../
zsh: no such file or directory: cd../
(base) shaktipandit@SHAKTIs-iMac lorem_copy % cd ../
(base) shaktipandit@SHAKTIs-iMac ~ % cp lorem/sed.txt lorem/sed2.txt lorem_copy/
cp: lorem/sed.txt: No such file or directory
cp: lorem/sed2.txt: No such file or directory
(base) shaktipandit@SHAKTIs-iMac ~ % cd lorem
(base) shaktipandit@SHAKTIs-iMac lorem % ls
(base) shaktipandit@SHAKTIs-iMac lorem % mkdir sed.txt
(base) shaktipandit@SHAKTIs-iMac lorem % mkdir sed2.txt
(base) shaktipandit@SHAKTIs-iMac lorem % ls
sed.txt		sed2.txt
(base) shaktipandit@SHAKTIs-iMac lorem % cd ../
(base) shaktipandit@SHAKTIs-iMac ~ % cp lorem/sed.txt lorem/sed2.txt lorem_copy/ 
cp: lorem/sed.txt is a directory (not copied).
cp: lorem/sed2.txt is a directory (not copied).
(base) shaktipandit@SHAKTIs-iMac ~ % cp lorem/sed.txt;sed2.txt lorem_copy/+    
usage: cp [-R [-H | -L | -P]] [-fi | -n] [-apvXc] source_file target_file
       cp [-R [-H | -L | -P]] [-fi | -n] [-apvXc] source_file ... target_directory
zsh: command not found: sed2.txt
(base) shaktipandit@SHAKTIs-iMac ~ % cp lorem/sed.txt ; cp lorem/sed2.txt lorem_copy/
usage: cp [-R [-H | -L | -P]] [-fi | -n] [-apvXc] source_file target_file
       cp [-R [-H | -L | -P]] [-fi | -n] [-apvXc] source_file ... target_directory
cp: lorem/sed2.txt is a directory (not copied).
(base) shaktipandit@SHAKTIs-iMac ~ % ´cp lorem/sed.txt ; lorem/sed2.txt lorem_copy/
zsh: command not found: ´cp
zsh: permission denied: lorem/sed2.txt
(base) shaktipandit@SHAKTIs-iMac ~ % cp lorem/sed.txt;lorem/sed2.txt lorem_copy/
usage: cp [-R [-H | -L | -P]] [-fi | -n] [-apvXc] source_file target_file
       cp [-R [-H | -L | -P]] [-fi | -n] [-apvXc] source_file ... target_directory
zsh: permission denied: lorem/sed2.txt
(base) shaktipandit@SHAKTIs-iMac ~ % cp -a lorem sed.txt ; sed2.txt lorem_copy/
zsh: command not found: sed2.txt
(base) shaktipandit@SHAKTIs-iMac ~ % cd lorem
(base) shaktipandit@SHAKTIs-iMac lorem % ls
sed.txt		sed2.txt
(base) shaktipandit@SHAKTIs-iMac lorem % rmdir sed2.txt
(base) shaktipandit@SHAKTIs-iMac lorem % mkdir at.txt lorem.txt
(base) shaktipandit@SHAKTIs-iMac lorem % ls
at.txt		lorem.txt	sed.txt
(base) shaktipandit@SHAKTIs-iMac lorem % cd ../
(base) shaktipandit@SHAKTIs-iMac ~ % head -n 3 lorem_copy/sed.txt
(base) shaktipandit@SHAKTIs-iMac ~ % ls
Desktop			Pictures		firstlabgit.txt
Documents		Public			import random.py
Downloads		about.txt		lorem
Ironshakti		about.txtt		lorem_copy
Library			anaconda3		print("was up").py
Movies			example_firstrap	print('Hallo').py
Music			example_firstrap.txt	sed.txt
(base) shaktipandit@SHAKTIs-iMac ~ % head -n 3 lorem_copy/sed.txt
(base) shaktipandit@SHAKTIs-iMac ~ % cd lorem_copy
(base) shaktipandit@SHAKTIs-iMac lorem_copy % ls
sed.txt		sed2.txt
(base) shaktipandit@SHAKTIs-iMac lorem_copy %  cd ../
(base) shaktipandit@SHAKTIs-iMac ~ % tail -n 3 lorem_copy/sed.txt
(base) shaktipandit@SHAKTIs-iMac ~ % echo "Homo homini lupus.">> lorem_copy/sed.txt
(base) shaktipandit@SHAKTIs-iMac ~ % tail -n 3 lorem_copy/sed.txt
Homo homini lupus.
(base) shaktipandit@SHAKTIs-iMac ~ % sed -i 's/et/ET/g lorem/at.txt
quote> '
sed: -i may not be used with stdin....................................................12 , did not get anser need help from CTA
(base) shaktipandit@SHAKTIs-iMac ~ % sed -i 's/et/ET/g' lorem/at.txt
sed: 1: "lorem/at.txt": extra characters at the end of l command
(base) shaktipandit@SHAKTIs-iMac ~ % cat lorem/sed.txt
cat: lorem/sed.txt: Is a directory
(base) shaktipandit@SHAKTIs-iMac ~ % sed -i - r 's/et/ET/g' lorem/at.txt
sed: 1: "r": filename expected
(base) shaktipandit@SHAKTIs-iMac ~ % cat lorem
cat: lorem: Is a directory
(base) shaktipandit@SHAKTIs-iMac ~ % cat sed.txt
cat: sed.txt: Is a directory
(base) shaktipandit@SHAKTIs-iMac ~ % cat lorem/sed.txt
cat: lorem/sed.txt: Is a directory
(base) shaktipandit@SHAKTIs-iMac ~ % id -un
shaktipandit
(base) shaktipandit@SHAKTIs-iMac ~ % pwd
/Users/shaktipandit
(base) shaktipandit@SHAKTIs-iMac ~ % ls 
Desktop			Pictures		firstlabgit.txt
Documents		Public			import random.py
Downloads		about.txt		lorem
Ironshakti		about.txtt		lorem_copy
Library			anaconda3		print("was up").py
Movies			example_firstrap	print('Hallo').py
Music			example_firstrap.txt	sed.txt
(base) shaktipandit@SHAKTIs-iMac ~ % ls > .txt
(base) shaktipandit@SHAKTIs-iMac ~ % ls
Desktop			Pictures		firstlabgit.txt
Documents		Public			import random.py
Downloads		about.txt		lorem
Ironshakti		about.txtt		lorem_copy
Library			anaconda3		print("was up").py
Movies			example_firstrap	print('Hallo').py
Music			example_firstrap.txt	sed.txt
(base) shaktipandit@SHAKTIs-iMac ~ % ls lorem/*.txt
lorem/at.txt:

lorem/lorem.txt:

lorem/sed.txt:
(base) shaktipandit@SHAKTIs-iMac ~ % cat loren/sed.txt | wc -1
cat: loren/sed.txt: No such file or directory
wc: illegal option -- 1
usage: wc [-clmw] [file ...]
(base) shaktipandit@SHAKTIs-iMac ~ % find / -name 'lorem*' -type f wc -1
find: wc: unknown primary or operator
(base) shaktipandit@SHAKTIs-iMac ~ % lorem/
├── at.txt
├── lorem.txt
└── sed.txt......................................................................17 need CTA help
zsh: permission denied: lorem/
zsh: command not found: ├──
zsh: command not found: ├──
zsh: command not found: └──
(base) shaktipandit@SHAKTIs-iMac ~ % read -p "Enter your name: " name
read: -p: no coprocess
(base) shaktipandit@SHAKTIs-iMac ~ % read -p "Enter text: " shakti
read: -p: no coprocess
(base) shaktipandit@SHAKTIs-iMac ~ % 
