Contributing guidelines
=======================

## Git Workflow

 - We use _github flow_
    - ``master` is the default branch
    - Create feature branches from ``master`` prefixed with ``feature/``, e.g. ``feature/some-new-thing``
    - All proposed merges to ``master`` must be done via pull request. 
 - Pull requests must contain a succinct, clear sumary of what the request entails and why it is necessary to occur.
 - Ensure your branch contains logical atomic commits before sending a pull request - follow the [alphagov Git styleguide](https://github.com/alphagov/styleguides/blob/master/git.md)
 - You may rebase your branch after feedback if it's to include relevant updates from the develop branch. We prefer a rebase here to a merge commit as we prefer a clean and straight history on develop with discrete merge commits for features