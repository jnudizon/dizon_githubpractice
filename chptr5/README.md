Chapter 5 discusses distributed workflows on Git; these workflows are some ways for
multiple developers to collaborate on a single project. Having multiple developers on
a project allows for a great amount of flexibility in managing and operating the development
process, so in order to make use of this flexibility, there are three different workflows:

Centralized workflow - multiple developers make use of a single shared repository; everyone has
push access and each developer has the ability to make changes and overwrite each 
other's changes.

Integration-Manager workflow - each dev has his/her own public repository and read access to 
everyone else's; there is one 'canonical' repository that represents the main line or the 
official project; changes are pushed in the dev's own repository, and pull requests are made
to the maintainer of the main projects in order for the maintainer to add the repo as a
remote, test the changes locally, merge them into the maintainer's branch and push the merge
changes into the main repository.

Dictator and lieutenants workflow - Regular developers work on their individual
 branch and rebase their work on top of the master (dictator's) branch. Lieutenants then
merge the developers' branches into their master branches, which are then merged into
the dictator's master branch. This is then pushed to the reference repo so other devs can
rebase on it. Generally used for larger projects.

The bulk of Chapter 5 discusses how to contribute, and maintain a Git project
with multiple developers.
Private small teams, forked public projects and other types of organizational 
workflows are discusssed in the chapter.
