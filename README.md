# Issues
This repo would be for different errors or bugs I've ever come across froom now in my journey and how I solved them.


# 1. Key is invalid. You must supply a key in OpenSSH public key format
This issue comes when you're trying to add your ssh keys so that github can authenticate, in simple words recognize your laptop when trying to push a code to github from git.
Reason is the code you get immediately on your terminal when you enter ssh-keygen -t ed25519 -C "your email" is actually not your ssh key
SHA256:+tY8rzxU5umpPBbhKu9tSyy4qIJiw - The one in this format is not what you should enter

Your ssh key needed is the one stored in the publisher file - Usually in this format ssh-ed25519 1NTYvmqUo60ZnEnrLMxgTki2CXOtTl

If your publisher can't open the file, simply open with notepad and voila.

Also this is not my real ssh key. Don't stress yourself trying anything fradulent. *inserts laughing emoji*
