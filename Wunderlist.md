Version 0.1 (Draft)

This document is intended to describe core specification of “TeamBoard” project.

TeamList is an application for team collaboration via lists of ToDo-alike extended items.

Glossary:
●	Applicaton user (User)
●	List item (Item) 
●	List of items (List)
●	Item parts

Use cases (UC):
1.	User can register themself using unique e-mail address
2.	User can perform:
a.	CRUD operations for Lists
b.	CRUD operations for Items
c.	Modify Item parts
d.	Enlist Items from any List or all Lists available to the User
e.	(TBD) Enlist Items which met predefined criterias (Filter)

Functional requirements (FR):
1.	List can contain zero or more Items, each Item is a part of one List
2.	Item contains the following info (Item parts):
a.	Header (required, non-whitespace plain text, up to 100 symbols)
b.	Description (plain text, up to 10 000 symbols)
c.	Attachments (file, up to 100 Mb each)
i.	preview is available for images and plain text files;
d.	A list of sub-tasks, each item has
i.	”complete” checkbox
ii.	text of the sub-task (plain text, up to 50 symbols)

Structural requirements (SR):
1.	Layers:
a.	Client side:
■	BL - Angular JS 1.2
■	UI - jQuery 2.1+jQueryUI 1.11
b.	Server side:
■	Backend - ASP.Net MVC 5
■	BL - .Net 4.5
■	DAL - Entity Framework 6.1.0
2.	Solution:
a.	MS Visual Studio 2013
Non-functional requirements (NR):
1.	MS .Net 4.5
2.	Supported Browsers: TBD
3.	

References:
1.	https://www.wunderlist.com

Screenshots/Mockups: see in folders
