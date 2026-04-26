# invoke-issue
A set of typings for invoke Python library. Repo is made strictly as material for issue and will be archived after closing it.

Maybe, a month ago, I wrote a set of `.pyi` files of `invoke` library for our project. The reason was that Pyright actively complained about `invoke` providing incomplete types for `invoke.tasks.task` decorator.

@bitprophet, hope it will help you if you consider improving type hints of public interfaces.

`invoke.tasks.task` is not the only thing I've changed types for but I don't remember at this point what type hints were overwritten. If you want, as I stated in the issue, I can, you know, look through types and code, edit type hints in your library properly and create PR for a review, but there are lots of open PRs in your repo, so just tell me if you will look through the PR if I'll make it.
