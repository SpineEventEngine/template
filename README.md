# template
This repository is a template for new repositories of the Spine framework.

Please see the [config](https://github.com/SpineEventEngine/config) repository
for shared configurations and scripts. `config` is added to this repository as a Git submodule.

## Applying to new sub-project

Search for `template` throughout the Gradle code and replace it with the name of 
your sub-project.

This template has two sub-modules called `template-client` and `template-user`.
Update the [settings.gradle.kts](settings.gradle.kts) file according to the needs
of your sub-project.

## Updating configurations
When you learn that `config` was changed, run `./config/pull` to apply updated configurations
to your repository.
