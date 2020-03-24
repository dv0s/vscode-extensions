The command used on windows
---
code --list-extensions | % { "code --install-extension $_" }

The command used on Unix
---
code --list-extensions | xargs -L 1 echo code --install-extension

output
---

code --linstall-extension abusaidm.html-snippets  
code --linstall-extension amiralizadeh9480.laravel-extra-intellisense  
code --linstall-extension austenc.laravel-blade-spacer  
code --linstall-extension bmewburn.vscode-intelephense-client  
code --linstall-extension cjhowe7.laravel-blade  
code --linstall-extension Equinusocio.vsc-community-material-theme  
code --linstall-extension Equinusocio.vsc-material-theme  
code --linstall-extension equinusocio.vsc-material-theme-icons  
code --linstall-extension felixfbecker.php-debug  
code --linstall-extension felixfbecker.php-intellisense  
code --linstall-extension felixfbecker.php-pack  
code --linstall-extension firefox-devtools.vscode-firefox-debug   
code --linstall-extension hollowtree.vue-snippets  
code --linstall-extension MehediDracula.php-namespace-resolver  
code --linstall-extension ms-vscode-remote.remote-wsl  
code --linstall-extension ms-vscode.sublime-keybindings  
code --linstall-extension neilbrayfield.php-docblocker  
code --linstall-extension onecentlin.laravel-blade  
code --linstall-extension onecentlin.laravel5-snippets  
code --linstall-extension PKief.material-icon-theme  
code --linstall-extension Tyriar.shell-launcher  
code --linstall-extension xabikos.JavaScriptSnippets  
code --linstall-extension xabikos.ReactSnippets  