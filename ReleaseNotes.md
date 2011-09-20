# Release notes


## pallet-crates-0.5.0


## pallet-crates-0.4.4


## pallet-crates-0.4.3

- Update for 0.5.0-SNAPSHOT
  Change pallet.resource.* to pallet.action.*. Change stevedore calls to
  script functions to use unquote and the pallet.script.lib namespace. 
  Change request to session.  Change build-resources to build-actions.


## pallet-crates-0.4.2


## pallet-crates-0.4.1


## pallet-crates-0.4.0


## pallet-crates-0.4.0-beta-1

- Changed the couchdb function to execute post-install steps even when there
  are no configuration options. Also added a comment to install function to
  clarify why you should probably use couchdb.

- working node-list compute service

- Refactored to extract compute provider lib

- Refactoring to a more functional implementation

- fix couchdb service hangs on restart

- Split out couchdb configure function. Made apply-evaluated handle nil
  arguments. Removed superfluous do.

- Formatting

- removed 1.1 compat.  fixed compile errors from id/providerId changes

- Fix to couchdb crate accounting for file/directory permission issues in
  most packaged installs as well as typical server startup latency

- clojure 1.1 / 1.2 compatibility modifications

- clojure 1.1 / 1.2 compatibility modifications

- couchdb crate now takes couchdb .ini configuration options

- simplified couchdb crate

- add couchdb crate

