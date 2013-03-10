# dot symerc

User-level configuration for collaborating on [Syme](https://syme.herokuapp.com).

To create your own, simply make a `.symerc` repo under your GitHub
username that includes an executable `bootstrap` script which copies
your dotfiles into place. This script will be run from the home
directory with two arguments: the user-qualified GitHub project being
worked on (eg. "technomancy/syme") and the primary language GitHub has
detected for that project.
