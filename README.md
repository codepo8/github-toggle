# github-toggle
A bookmarklet to toggle between Repo and GitHub pages

Drag the following link to your bookmarks bar: [GitHub Toggle](javascript:dl=document.location.href;str=dl.indexOf('github.io')!==-1 ? dl.replace(/\/(.*)\.github.io/,'//github.com$1'):dl.replace(/github.com\/([^\/]+)\//,'$1.github.io/');document.location.href=str)
