Hi %(name)s!
~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~

You are receiving this e-mail because you are taking the course
%(course)s and have submitted the fourth mandatory assignement.
You are now asked to join a collaboration with two of your fellow
students. Together you are asked to performed peer-review on three
other students. (Likewise, another group of three will be
reviewing your assignment.)

You have been assigned to work with %(group_names)s as part of
%(team_name)s. Start by contacting your collaborators to organize
yourself. Email addresses to your collaborators:

%(team_emails)s

Together, the three of you will be correcting the work of the
following repositories:

%(correcting_names)s

You now have access to push and pull to these repositories. You
should make a temporary directory and execute

.. code-block:: bash

%(get_repos)s

Rules
~~~~~

Deadline for review is today.

A template for the feedback file is attached and have to be used!

A review is completed by pushing a file to each of the reviewed
repositories. The name of the file should either be: `PASSED3_YES`
or `PASSED3_NO`.  The names represent a pass and a fail
respectively. The name has to be exact, since they will be read
automagically.
