# squad-tutorials

You may be able to compile this without `stack`, but this README assumes you are
using it.

To build the executable run `stack build`.

To update the site run `stack exec squad-tutorials -- build`, commit the changes
from the `docs` folder and push the commit to the GitHub remote if you are using
GitHub pages.

If you want to observe the changes you are making while working on a post or
styling changes use the command `stack exec squad-tutorials -- watch`.
