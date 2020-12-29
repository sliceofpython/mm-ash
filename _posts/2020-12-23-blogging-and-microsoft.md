---
title: "Post: Blogging using Microsoft toolkit"
last_modified_at: 2020-10-09T16:20:02-05:00
tags:
  - PowerShell
  - Git
  - standard
---
Git and GitHub, PowerShell, VS Code. 
Adding to this mix Jekyll with Minimal Mistakes theme. 

## sources:
1. [Start using Git for PowerShell scripts](https://4bes.nl/2019/06/02/step-by-step-start-using-git-for-powershell/)

The path travelled, and support on this way. 
Prerequisites on Windows: 
Ruby (option with Ruby Installer or with WSL), Ruby gems
Git, GitHub account, 
VS code and PowerShell. 



2. Then followed the guide from Holistic Security: 
[holistic security](https://holisticsecurity.io/2020/03/30/github-pages-and-jekyll-on-windows-10)

`bundle exec jekyll -v`

`bundle exec jekyll serve `


3. [Blogging with Jekyll using Minimal Mistakes Theme](https://purple.telstra.com.au/blog/opensource-blogging-with-jekyll-github-vscode-part-2)

Got an error doing $bundle exec jekyll serve while executing Remote Theme (Minimal-Mistakes): Could not find gem 'github-pages x64-mingw32' in any of the gem sources listed in your Gemfile.
Run `bundle install` to install missing gems.
`bundle install jekyll` ~!



other refereces: 
Sean Killeen - uilding my Jekyll blog with Ubuntu on WSL2; 