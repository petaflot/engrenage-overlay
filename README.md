# engrenage-overlay

## Setting up

`/etc/portage/repos.conf/engrenage`
    [engrenage-overlay]
    name = engrenage-overlay
    location = /var/db/repos/engrenage-overlay
    sync-type = git
    sync-uri = https://github.com/petaflot/engrenage-overlay.git
    priority = 50
    auto-sync = yes
    clone-depth = 1
    sync-depth = 1
    
