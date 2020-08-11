On paper, WSL fulfills a dire need in the development community. It allows you to have the *NIX environment on any device that can run windows. Whereas previously you had to either buy Apple hardware or go through the intimidating Linux installation.

In this article I will give you some ideas about the setup process and runtime of WSL2 vs Native Ubuntu to let you decide if it’s worth the switch.

Let’s begin with a little setup for WSL2.
Note: WSL and WSL2 will be used interchangeably from here on out, but they are meant to mean the same thing.

1. Install WSL

This article does a great job in getting your Windows OS setup and ensuring you’re using WSL2 and not WSL1.

2. Download and install Ubuntu from the Windows Store
3. Start Ubuntu in WSL
You’ll be asked to create a user and password, then you should drop straight into the Ubuntu shell
What’s Working Well?
Zshell / Oh-My-Zsh / Git
VSCode
Being able to run code . from within a directory in WSL and have it open up the windows application is real nice, and gives a more native feel to the sub system.

This may in fact be the standout feature of WSL so far.
Python / Golang / Nodejs.

If you’re comfortable with pairing VSCode and these languages you’re good to go now with WSL. All the relevant package managers, npm, pip, etc, also work without any hacks and create a nice separation from the host OS.
Some limitations (What’s not working)
Jetbrains IDEs

This path unfortunately is fraught with issues at present. I had issues setting up just about every language/toolkit I tried. And even after getting is to run the Linux version of the SDK/JDK, Intellij still had many issues. I understand there is significant pressure on Jetbrains to create better integration with WSL, so we will see this improve in the future.

Conclusion

I really enjoyed using WSL2 on windows and think many people will be able to make use of the current features. However, it doesn’t seem to be feature rich enough, or at least have the support of feature rich software, to be a viable total option for me.
