# fast-forward-action

Adds a fast-forward label to PRs and fast-forwards them on `/fast-forward` comment.

## Inputs

| Input      | Description |
| ----------- | ----------- |
| GITHUB_TOKEN      | Automatically provided token, that can be used to authenticate on behalf of the GitHub action, with permissions limited to the repository that contains your workflow       |
| SSH_PRIVATE_KEY   | Deploy key for push. Must be  set in the repository settings. This is used by the action to push the fast-forwarded branch/commit/PR.        |


## Examples

For working examples checkout the `fast-forward` tagged PRs. 
They have been merged via the `/fast-forward` command.

* https://github.com/APN-Pucky/smpl/pulls?q=is%3Apr+is%3Aclosed
* https://github.com/APN-Pucky/HEPi/pulls
