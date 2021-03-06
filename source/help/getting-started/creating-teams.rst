Creating Teams
==============

New teams can be created if the System Admin has **Enable Team Creation** set to true from the System Console.

Methods to Create a Team
------------------------

Teams can be created from the Team Selection page or Main Menu. The person who creates a team will automatically be given the Team Admin role for that team.

Team Selection Page
~~~~~~~~~~~~~~~~~~~~
Navigate to the web address of your system, ``https://domain.com/``. Sign in using your credentials. Click **Create a new team** to be guided through the rest of the set up steps. If this option is not visible on the web page, then the System Admin has disabled team creation. 

Main Menu
~~~~~~~~~~
From your current Mattermost team, click on the **Main Menu** > **Create a New Team**. If this option is not visible in the menu, then the System Admin has disabled team creation.

Team Name and URL Selection
---------------------------

There are a few details and restrictions to consider when selecting a team name and team URL.

Team Name
~~~~~~~~~~~~~

This is the display name of your team that appears in menus and
headings.

-  It can contain any letters, numbers or symbols.
-  It is case sensitive.
-  It must be 2 - 15 characters in length.

Team URL
~~~~~~~~~~~

The team URL is part of the web address that navigates to your team on
the system domain, ``https://domain.com/teamurl/``.

-  It may contain only lowercase letters, numbers and dashes.
-  It must start with a letter and cannot end in a dash.
-  It must be 2 - 15 characters in length.
-  It cannot start with the following restricted words: ``signup``,
   ``login``, ``admin``, ``channel``, ``post``, ``api``, ``oauth``
