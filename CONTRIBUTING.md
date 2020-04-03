# Contribution Guidelines
Welcome! We're excited that you're contributing to this project! :tada: 

The following is a set of guidelines for contributing to projects hosted in the [Arcus Data GitHub organization](https://github.com/arcus-data). These are guidelines, not rules. Use your best judgement. Feel free to propose changes or additions to these guidelines in the [.github metadata repo](https://github.com/arcus-data/.github) using a pull request.

## How can I contribute?

### Branching Model
Arcus Data generally tries to follow "[A successful Git branching model](https://nvie.com/posts/a-successful-git-branching-model/)".

Please prefix your branches according to what they are doing. For example, a bug fix branch should be prefixed with `bug/` or `bugfix/`

### Requirements
* Commits must be signed
* Enable MFA for your GitHub account
* Never commit any of the following:
    * Customer confidential information
    * Anything that violates a copyright or license agreement
    * API Access and secret keys
    * Passwords
    * Private keys (SSL, SSH, GPG, etc.)

## Style Guides

### Git Commit Messages

* Use the present tense ("Add feature" not "Added feature")
* Use the imperative mood ("Move cursor to..." not "Moves cursor to...")
* Limit the first line to 72 characters or less
* Reference issues and pull requests liberally after the first line
* Consider starting the commit message with an applicable emoji:
    * :art: `:art:` when improving the format/structure of the code
    * :racehorse: `:racehorse:` when improving performance
    * :memo: `:memo:` when writing docs
    * :bug: `:bug:` when fixing a bug
    * :fire: `:fire:` when removing code or files
    * :green_heart: `:green_heart:` when fixing the CI build
    * :white_check_mark: `:white_check_mark:` when adding tests
    * :lock: `:lock:` when dealing with security
   
### Python

Python code should be written according to the [PEP8 standards](https://www.python.org/dev/peps/pep-0008/). Use [Flake8](https://flake8.pycqa.org/en/latest/) to lint your code. 

### Splunk .conf Files

* One blank line between sections.
* Place spaces between the following:
    * Option name and equals sign
    * Equals sign and option value
* Comments are prefaced by a single hash sign (`#`) and a single space.
* A single blank line before a comment inside a section is acceptable.
* Comments must not occupy a line with any configuration item or section header.
* Limit comment lines to 120 characters or less.
* Place a blank line at the end of the file.

Example:

```ini
# sample.conf.spec

[section]
option = value
option2 = test

# A descriptive comment here is okay
option3 = 

[section2]
# Multi
# Line
# Comments
# are okay
option = value↵

```

### Documentation

For complex documentation that cannot fit neatly into a file, use a separate `README.md` file in the directory. Use [Markdown](https://daringfireball.net/projects/markdown) formatting.
