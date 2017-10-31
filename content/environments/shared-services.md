+++
title = "Shared Services"
description = "What service to share?"
+++

Where possible share services with colleagues. Simply put, that could be some 'down stack' thing that the application relies on, that are made by other teams or from a vendors (where you only really want to license one install). 

A class example is the database. There is only a need for a single database 
prior to production and all staff should use it for whatever purpose they wish.  Developers working on features 
that are forthcoming should seek to have the DBAs make their table-shape changes there. The same developers 
should configure their workstations to use that same shared database just in case they are able to bring up the 
application on their workstation (more typical towards the end of a release cycle, of course).