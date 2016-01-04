Releasing Amidst
=================

To release Amidst, follow these steps:

* update information in `src/main/resources/amidst/metadata.properties`
* commit the change on the master branch
* checkout the branch releases
* fast-forward merge the branch master into the branch releases
* push the branch releases
* create and push the tag
* wait for travis ci to build Amidst, it will attach the executable jar, zip and exe files to the release on github
* update the information about the release
  * add a meaningful title and text
  * make the release a pre-release, if necessary
* update the document that is used by Amidst to inform the user about the new version, if it is not a pre-release