# gwdg-cloud-share-packages
DPKG packages for GWDG Cloud Share service of PowerFolder software

gwdg-cloud-share-repo: Builds a small package that registers a gpg key and puts the repository URL into apt; intended for client packages from http://my.powerfolder.com.

gwdg-cloud-share-server-repo: Same as above, for a repository for server software (below).

gwdg-cloud-share-server: Contains files for packaging the server software from http://download.powerfolder.com/server/linux/ into a DPKG package.

gwdg-cloud-share-server-test: Same as above, intended for packaging testing version of the software server.

BEWARE: Package information contains GWDG specific information such as the GPG key, GPG keys id, URLs and descriptions.
