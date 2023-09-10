# Family Geneaology Builder
### Proposal Author: Sivan Cooperman (sc7443)

## Description
This proposal entails the creation of a web application that allows users to
create family trees and geneaologies. Users would be able to insert family
members, relationships, and biographical information, as well as view and share
their family tree to other users. Functionality can be expanded to advanced or
dynamic visualizations, collaborative editing of trees, association of a person
or group of people with multimedia, and compatibility with other popular 
geneaology applications, among other features.

## Need Fulfilled
While many aspects of our lives have moved online, documents, photos, and other
materials that serve as records of family geneaology are often lost or
destroyed over time, due to not being preserved digitally. By using a web
application to digitize a user's record of their family tree, they can
guarantee (for the lifetime of the application, at least) that their data not
be lost or destroyed, and that other family members can easily view, visualize, 
and expand the tree with information of their own. Furthermore, uploading
geneaological information to a web application makes it more accessible to
others for the purposes of viewing and editing.

## Intended Users
The intended end-users of this application are people who want to digitize and
safely store data about their family tree, and share it with friends or other
members of their family. One such user is my father, who has collected
biographical information for and photos and videos of dozens of members of our
family. Right now, most of it is either stored locally/in the cloud, or on an
extremely basic website that is missing many features. What data that has been
digitized is not easily accessible, and often fraught with errors that would be
impossible with a dedicated web application.

## System Summary
### General
- Users should be able to create an account for themselves.

### Editing
- Users should be able to create "trees" which contain geneaological data. 
- Users should be able to add members to these trees, and create relationships
  between them, such as sister or husband. 
- Users should be able to associate information such as DOB, name, other
  anecdotal or biographical information, and possibly multimedia such as photos
  or videos. 
- The application should attempt to minimize errors caused by erroneous user
  inputs by maximizing the amount of data that can be filled in automatically.
  For example, if the user says that person A is the child of person B, person
  B's record should automatically update to include that they are the parent of
  person A.

### Sharing
- Users should be able to permit other users to edit family trees that they own.
- Users should be able to export a tree to a downloadable file, and import
  trees into the application from appropriately formatted files. 
- Users should be able to generate a URL that allows other users to view, but
  not edit, the tree.

### Visualizing
- Users should be able to view and visualize the entire tree easily and
  intuitively.

## Scope
Some core features of the application include a login system, a database to
store family member information in, a way to edit trees, and a way to export or
share trees. Beyond that, features such as inviting other users to collaborate,
advanced visualizations, compatibility with other geneaology apps, etc. are not
strictly necessary. In my estimation it is highly likely that some but not all
of the "bonus" features will be able to be included, but keeping a list of them
allows for extra time to be utilized if available.
