#resolving issues with github behind a proxy

http://stackoverflow.com/questions/20370294/could-not-resolve-host-github-com-error-while-cloning-remote-repository-in-git
set HTTPS_PROXY=http://<login_internet>:<password_internet>@aproxy:aport
set HTTP_PROXY=http://<login_internet>:<password_internet>@aproxy:aport
set NO_PROXY=localhost,my.company
