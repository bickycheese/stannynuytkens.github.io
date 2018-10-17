---
title: "Use cmder as integrated console in vscode"
date: 2018-04-09T15:18:39+02:00
draft: false
tags: ["vscode", "cmder"]
comments: true
---
First, if you're not using [vscode](https://code.visualstudio.com/) or [cmder](http://cmder.net/) yet, start using them. Thank me later..

[vscode](https://code.visualstudio.com/) is Microsofts next-gen lightweight code-editor. I'm not going to be a fanboy here but it's simply awesome! Just watch this demo if you don't believe me.
{{< youtube anvYeA1pWlk >}}

[cmder](http://cmder.net/) is a shell replacement tool for Windows.
It's basically the only shell you'll ever need in terms of customization.
It offers things like built-in colors, aliases, commands, transparency, ... You can use this shell in place for DOS, powershell, git bash, Ubuntu bash, ...

Now if you have worked with both you probably want to know how you can use [cmder](http://cmder.net/) as _Integrated Terminal_ in [vscode](https://code.visualstudio.com/).

1. Create a file named vscode.bat in your cmder root directory and set its contents to:
{{< gist stannynuytkens 076c70a824dd0a5524de88d11bd4c653 "vscode.bat" >}}
Be sure to change CMDER_ROOT appropriately!

2. In [vscode](https://code.visualstudio.com/) change your _User Preferences_ to have these 2 lines:
{{< gist stannynuytkens 076c70a824dd0a5524de88d11bd4c653 "settings.json" >}} Again make sure the target file path is set correctly.

3. Magic! :unicorn::rainbow:
<img src="/img/snippets/snippet.0001.PNG" alt="snippet.0001" />