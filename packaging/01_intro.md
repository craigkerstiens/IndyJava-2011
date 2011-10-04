<!SLIDE incremental>
# Releasing a Package #

<br/>
<br/>

## Distutils

<!SLIDE incremental>
# Releasing a Package #

- Write a setup script
- Create a source distribution
- Release it

.notes Disutils seems to have gotten pretty good adoption, people use it and there's far less complaints about it that other issues with dependency management. Essentially you're writing a setup script, creating your distribution and releasing it. That third item is perhaps the biggest issue users encounter.

<!SLIDE>
# *BUT WHERE?* #

.notes First a quick note, this applies only to packages that are going out in the community to be used by others. If its an internal package then these issues become slightly different. So where to release it, there's a few options...
