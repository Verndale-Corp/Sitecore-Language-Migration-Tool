Verndale Language Migration Tool for Sitecore

Purpose
Quickly add language versions, copy language version content, remove language versions for the content tree.

Compatibility
The codebase is compatible with Sitecore 6.6.x releases.  It should work with earlier versions though.

How to build code and deploy the solution

1. Download and unzip the Verndale.SharedSource.zip from this repository, it contains a class library
2. The important file in this is LanguageHelper.cs, for the method CreateVersionInEachLanguage

3. Download and install the Language Migration Tool-1.zip Sitecore package
This will add an application to core and add a LanguageTools folder to /sitecore modules/web

Testing
1. Open up the tool by either going directly to the url and opening via the Sitecore start button and choosing in the right menu column
2. Set a path to a content section of sitecore (recommend a small set of items to begin with)
3. Select a Source Language and Target Language
4. Decide if running recursively or on children (recommend neither for first time)
5. Run tool and then check the items, see if the language was added

There will be lengthy documentation in a blog post on Sitecore

Review the blog series about Partial Language Fallback on Sitecore, link TBD
