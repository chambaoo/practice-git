# work log

## set up github cli
- generate new token

  - <https://docs.github.com/en/authentication/keeping-your-account-and-data-secure/managing-your-personal-access-tokens>

  - <https://github.com/settings/tokens?type=beta>


- <https://cli.github.com/manual/>
  - exec gh auth
    ```
    $ gh auth login
    ? What account do you want to log into? GitHub.com
    ? What is your preferred protocol for Git operations? HTTPS
    ? Authenticate Git with your GitHub credentials? Yes
    ? How would you like to authenticate GitHub CLI? Paste an authentication token       
    Tip: you can generate a Personal Access Token here https://github.com/settings/tokens
    The minimum required scopes are 'repo', 'read:org', 'workflow'.
    ? Paste your authentication token: *********************************************************************************************
    - gh config set -h github.com git_protocol https
    ✓ Configured git protocol
    ! Authentication credentials saved in plain text
    ✓ Logged in as chambaoo
    $ gh repo clone chambaoo/practice-git
    Cloning into 'practice-git'...
    remote: Enumerating objects: 3, done.
    remote: Counting objects: 100% (3/3), done.
    remote: Total 3 (delta 0), reused 3 (delta 0), pack-reused 0
    Unpacking objects: 100% (3/3), 201 bytes | 3.00 KiB/s, done.
    $
    ```
