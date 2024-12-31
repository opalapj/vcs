# Configuration

    gh auth login

# Adding local repo to GitHub

- create a repo interactively:

        gh repo create

- create a private repo with given name and clone to the current directory:

        gh repo create <name> --private --clone

- creata a private repo from the current directory 

        gh repo create --private --source=. --push

    > Important note:
    >
    > Switch to `main` branch before creation.

# Resources

https://docs.github.com/en/github-cli

https://cli.github.com/manual/