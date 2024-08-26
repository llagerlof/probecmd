# probecmd

Extract useful information from an EndeavourOS command or package.

"I" wrote this program using an LLM called Claude 3.5 Sonnet. I didn't even have to read the code.

I had to make a dozen interactions with Claude to fix some problems, but this experiment is working.

```
[user@pc ~/repos/probecmd]$ ./probecmd bottom
probecmd 1.6
* Package name: bottom
* Executable location: /usr/bin/btm
* Alias: No
* Function: No
* Shell built-in command: No
* Binary: Yes
* Interpreted: No
* AUR: No
* Pacman: Yes
* Pip: No
* Npm: No


[user@pc ~/repos/probecmd]$ ./probecmd btm
probecmd 1.6
* Package name: bottom
* Executable location: /usr/bin/btm
* Alias: No
* Function: No
* Shell built-in command: No
* Binary: Yes
* Interpreted: No
* AUR: No
* Pacman: Yes
* Pip: No
* Npm: No
```
