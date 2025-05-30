# Contributor Guidelines

Thanks for your interest in contributing. This page will give you a quick overview of how things are
organized and, most importantly, how to get involved. Everyone is welcome to contribute, and everybody's 
contribution is valued.


## 1. Before contributing

Welcome to Certificaciones Unir! Before sending your pull requests, make sure that you read the whole guidelines.
If you have any doubt on the contributing guide, please feel free to state it clearly in an issue against the
repository.


## 2. Submitting changes

1. Create an issue.
2. Assign the issue to a developer and create a branch.
3. Create a Pull Request.
4. The admin (first creator) of the repository will review the Pull Request.

### Git branches

- Always perform work in a feature branch.
- It is better to branch out from `develop` branch.
- Delete local and remote feature branches after merging.

### Git commit messages

- Start the subject with an action between brackets. Ex.: `[fix]`.
- Separate the subject from the body with a newline between the two (if the body exists).
- Limit the subject line to 50 characters and Wrap the body at 72 characters.
- Capitalize the subject line.
- Do not end the subject line with a period.
- Use imperative mood in the subject line.

#### Commit actions

| Actions  | Example                                       | Description                                           |
|----------|-----------------------------------------------|-------------------------------------------------------|
| `update` | `[update]` secret added to the config-service | A commit in the code that doesn't change the outcome. |
| `wip`    | `[wip]` added new fetaures to home            | A commit of a develop that is still in progress.      |
| `fix`    | `[fix]` string error                          | A commit pushed to fix a previous bug in the code.    |

Example:

```sh
git commit -m "[Update] get initial documentation"
```

(If applied, this commit will be `[update] get initial documentation`)


## 3. Licensing

When you submit code to my repositories, you implicitly and irrevocably agree to adopt the associated licenses.
You should be able to find this in the file named `LICENSE`.

## 4. Code of conduct

You should be able to find this in the file named `code_of_conduct.md`.  This Code of Conduct is the Contributor
Covenant, version 1.4, available at [Covenant code of conduct](http://contributor-covenant.org/version/1/4)


## Thank you!

If you have any questions, concerns or comments about these guidelines, please get in touch. You can do this by raising
an issue against the template repository.

Happy coding!

-- @charlstown