# labwc - hackish grid workspaces modification

Disclaimer: I am doing some hackish changes in labwc for my use-cases, mainly
around grid workspace layouts. I am quite sure this stuff will be handled
differently in future when workspaces are covered better by wlroot wayland
protocols:
    https://gitlab.freedesktop.org/wayland/wayland-protocols/-/merge_requests/40

My hackish workaround is tracked in grid-workspace* branches in case someone
is in a similar situation like me, that grid layout for workspaces is actually
indispensable. See commit msgs for details.

I am building RPMs with modified labwc in this temporary Fedora COPR repository:
    https://copr.fedorainfracloud.org/coprs/pstodulk/my-dirty-wl-and-labwc-hacks/

Note that I do not suggest just to consume & depends on my work as it's possible
I will remove it once all functionality I need is implemented in labwc upstream
project. Also it's possible I will update some stuff to be closer to the plans
of upstream. So consider it unstable and temporary. Feel free to copy/clone my
changes.

Note that in the labwc upstream has been merged implementation of cosmis-workspaces
recently.
