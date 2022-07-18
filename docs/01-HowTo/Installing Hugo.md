# Installing Hugo
ref.: https://cloudcannon.com/community/learn/hugo-tutorial/

Get Hugo set up and installed for the rest of the lessons.

Hugo is one of the simplest static site generators to install, because it’s distributed as a single binary. This means that everything is included in one package, and you don’t have to manage anything. Even though Hugo is built in Go, you don’t need that installed!

````ad-note
There are two versions of Hugo: **standard** and **extended**. If you are a user of SCSS/SASS, the **extended** version is recommended, as this gives you built-in processing capabilities.
````
## How to install Hugo

Hugo can be installed in multiple ways, but a package manager is recommended - either [Homebrew](https://docs.brew.sh/Installation) for Mac/Linux or [Chocolatey](https://chocolatey.org/install) for Windows. Check [Hugo’s installation page](https://gohugo.io/getting-started/installing/) for more options, such as cloning directly from GitHub.

**Mac/Linux (Homebrew):**
```shell
brew install hugo
```
**Windows (Chocolatey):**
```shell
choco install hugo-extended -confirm
```
## Final installation check

To check that the Hugo installation has worked properly, run the following command:
```shell
hugo version
```