..
  Technote content.

  See https://developer.lsst.io/restructuredtext/style.html
  for a guide to reStructuredText writing.

  Do not put the title, authors or other metadata in this document;
  those are automatically added.

  Use the following syntax for sections:

  Sections
  ========

  and

  Subsections
  -----------

  and

  Subsubsections
  ^^^^^^^^^^^^^^

  To add images, add the image file (png, svg or jpeg preferred) to the
  _static/ directory. The reST syntax for adding the image is

  .. figure:: /_static/filename.ext
     :name: fig-label

     Caption text.

   Run: ``make html`` and ``open _build/html/index.html`` to preview your work.
   See the README at https://github.com/lsst-sqre/lsst-technote-bootstrap or
   this repo's README for more info.

   Feel free to delete this instructional comment.

:tocdepth: 1

.. Please do not modify tocdepth; will be fixed when a new Sphinx theme is shipped.

.. sectnum::

.. TODO: Delete the note below before merging new content to the master branch.

.. note::

   **This technote is not yet published.**

   Procedure to document activities carried out by IT User Support when working remotely.

============
Introduction
============

Due to the global viral outbreak, Rubin Observatory has shut down its operations both at summit Pachon and La Serena Recinto and has moved on to remote work.

The purpose of this document is to clarify IT User Support activities through the next 3 to 6 months detailing our service desk approach throughout this period of time.

.. Add content here.

IT User Support - Communication channels
========================================
The purpose of IT user support is to capture demand for incident resolution and service requests in a timely and kindly manner throughout our various communication channels listed below.

Jira
-----
.. figure:: /_static/jira.png
    :name: fig-label

    Jira.
The IT support dashboard is the main point of contact with the helpdesk when it comes to reporting incidents and handling requests.

If you are not sure how to file a ticket correctly to IT User Support please visit the following guide to assist you with this process:

How to file a JIRA Ticket for IT User Support

Slack
-----
.. figure:: /_static/slack.jpg
    :name: fig-label

    Slack.
Another way we can report a problem or request is by contacting directly through the slack application.

This can be done by one of the two ways:

    Signing in through your computer device or smartphone with your account credentials.
    Signing in through the slack website located at https://slack.com/signin  using the lsstc workspace name.

.. figure:: /_static/slack1.png
    :name: fig-label

    Sign in.

.. figure:: /_static/slack2.png
    :name: fig-label

    Sign in.


Note: If you don't remember your slack password, you can always use the "Forgot Password" option to reset your account password using your LSST email.

Email
-----
Alternatively, IT User support can be contacted via email at rubinobs-it@lsst.org and rubinobs-it-las@lsst.org.

IT User Support - Work Schedule
========================================

Emergencies
-----------
In case of emergencies or special requests outside normal work hours please contact rubinobs-it@lsst.org or rubinobs-it-las@lsst.org for support.

IT User Support - Communication channels
========================================

Current Situation
=================

Summit Status
-------------
Currently, all work at Cerro Pachon is paralyzed until further notice. There are inspection teams who will be in going up to the summit when requested by the manager in charge.

In case of requiring any IT asset or element from the summit, this needs to be notified to the corresponding manager, either Eduardo Serrano or Jacques Sebag to coordinate with the inspection team to bring down these elements from the summit.

The assets will be stored in LAS Facility and will be recovered by authorized personnel.

La Serena Status
----------------
At this moment there is a strict prohibition to visit the recinto, access will only be granted in case of emergencies with authorization of the manager in charge. Regarding IT, Cristian Silva is the only person authorized to enter the recinto based on the necessity and priority of the request.

In case a user requires any IT equipment be it monitors, docking stations or any other accessory to work from home, it needs to be notified to the manager in charge and IT Helpdesk which can be contacted at rubinobs-it@lsst.org or rubinobs-it-las@lsst.org.

Additionally, a ticket will be created in JIRA to document this activity and to follow up on the return of the assets loaned.

For any incidents regarding hardware failure of their asset: laptops, monitors, and desktops requiring our onsite Helpdesk intervention it is requested from our users to drop of the asset at the recinto at the main hall of the first floor in one of the cubicles were the printer and plotter are located. IT will recover the failing asset for revision and depending on the case a basic spare asset will be assigned to the user in the meantime to continue its normal work that is (Office, Slack, Bluejeans, Email).

The spare assets and repaired assets will be dropped off for use for the user at the same place where it was dropped off for revision.

Note: All physical interventions are limited to the current COVID-19 viral outbreak the country is facing, this being said response time may vary taking hours to days to deliver the assets to the user.

Purchases and Warehouse
=======================
Aura warehouse is working normally with Victor Rojas in charge of receiving all incoming packages and products internationally and nationally.

Due to the national contingency, these activities are being handled a bit slower than usual but it is all working normally based on the most important necessities.

.. Add content here.

.. Do not include the document title (it's automatically added from metadata.yaml).

.. .. rubric:: References

.. Make in-text citations with: :cite:`bibkey`.

.. .. bibliography:: local.bib lsstbib/books.bib lsstbib/lsst.bib lsstbib/lsst-dm.bib lsstbib/refs.bib lsstbib/refs_ads.bib
..    :style: lsst_aa
