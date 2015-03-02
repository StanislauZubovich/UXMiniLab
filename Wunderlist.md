##Version 0.1 (Draft)

This document is intended to describe core specification of “TeamBoard” project.

TeamList is an application for team collaboration via lists of ToDo-alike extended items.

###Glossary:

- Applicaton user (User)
- List item (Item) 
- List of items (List)
- Item parts

###Use cases (UC):

1. User can register themself using unique e-mail address
2. User can perform:
  - CRUD operations for Lists
  - CRUD operations for Items
  - Modify Item parts
  - Enlist Items from any List or all Lists available to the User
  - (TBD) Enlist Items which met predefined criterias (Filter)

###Functional requirements (FR):
1. List can contain zero or more Items, each Item is a part of one List
2. Item contains the following info (Item parts):
  - Header (required, non-whitespace plain text, up to 100 symbols)
  - Description (plain text, up to 10 000 symbols)
  - Attachments (file, up to 100 Mb each)
  - Preview is available for images and plain text files;
  - A list of sub-tasks, each item has
  - ”complete” checkbox
  - text of the sub-task (plain text, up to 50 symbols)

Structural requirements (SR):
- Layers:
  1. Client side:
    - BL - Angular JS 1.2
    - UI - jQuery 2.1+jQueryUI 1.11
  2. Server side:
    - Backend - ASP.Net MVC 5
    - BL - .Net 4.5
    - DAL - Entity Framework 6.1.0
- Solution:
  1.  MS Visual Studio 2013

###Non-functional requirements (NR):
  - MS .Net 4.5
  - Supported Browsers: TBD

###References:
1. https://www.wunderlist.com

Screenshots/Mockups: see in folders
