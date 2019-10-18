This repository showcases [project Vintage](https://github.com/github/vintage/), which adds support to the [Dependency graph](https://help.github.com/en/articles/listing-the-packages-that-a-repository-depends-on) for dependencies vendored directly into the repository, as opposed to defined with a package management manifest like a `package.json`, `requirements.txt`, or `pom.xml`.

Now, Vintage is focused on single-file Javascript dependencies, like `jQuery`.

There are three `jQuery` javascript files in the [`lib`](/lib) directory, each of which are identified as a dependency on `jQuery`, and reflected in the [Dependency graph](https://github.com/github/vintage-demo/network/dependencies).
