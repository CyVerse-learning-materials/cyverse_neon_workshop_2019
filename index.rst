.. include:: cyverse_rst_defined_substitutions.txt

|CyVerse_logo|_

|Home_Icon|_
`Learning Center Home <http://learning.cyverse.org/>`_

**Introduction to CyVerse**
=================

..
    #### Comment: Use short, imperative titles e.g. Upload and share data, uploading and
    sharing data ####

Goals
----

* Introduce NEON scientists and staff to `CyVerse <https://www.cyverse.org>`_ and its resources.

* Demonstrate via hands-on exercises the CyVerse `Data Store <https://www.cyverse.org/data-store>`_, Data Science Workbench (`Discovery Environment <https://www.cyverse.org/discovery-environment>`_), Cloud (`Atmosphere <https://www.cyverse.org/atmosphere>`_), `BisQue <https://www.cyverse.org/bisque>`_ image analysis, `Data Commons <https://www.cyverse.org/data-commons>`_, and `Powered By <https://www.cyverse.org/powered-by-cyverse>`_ features. 

* Open discussion about how NEON staff or academic scientists working with NEON data could begin to utilize CyVerse at scale.

	Suggested topics:
	
	* Identify NEON's computational and data storage|sharing bottlenecks that CyVerse can ameliorate.
	* Identify missing components from the current CyVerse infrastructure that NEON requires.

..
    #### Comment: Avoid covering upstream and downstream steps that are not explicitly and
    necessarily part of the tutorial - write or link to separate quick
    starts/tutorials for those parts ####

----

.. toctree::
	:maxdepth: 2

	Tutorial home <self>
	Morning Workflow <step1.rst>
	Afternoon Workflow <step2.rst>
..
	#### Comment:This tutorial can have multiple pages. The table of contents assumes
	you have an additional page called 'Step One' with content located in 'step1.rst'
	Edit these titles and filenames as needed ####


Prerequisites
-------------

Downloads, access, and services
~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~

*In order to complete this tutorial you will need access to the following services/software*

..
	#### comment: delete any row not needed in this table ####

.. list-table::
    :header-rows: 1

    * - Prerequisite
      - Preparation/Notes
      - Link/Download
    * - CyVerse account
      - You will need a CyVerse account to complete this exercise
      - `Register <https://user.cyverse.org/>`_
    * - Atmosphere access
      - You must have access to Atmosphere
      - `Request Access <https://user.cyverse.org/services/available>`_
    * - CyVerse Data Store allocation increase (Optional)
      - You must be registered for CyVerse
      - `Request Increase (form #2) <https://user.cyverse.org/forms>`_
    * - Jetstream access (Optional)
      - You must have registered with XSEDE
      - `Request Access <https://portal.xsede.org/my-xsede#/guest>`_
    * - Cyberduck (Optional)
      - Standalone program for uploading/downloading data to Data Store
      - `Download <https://cyberduck.io/>`_
    * - Windows 10 Linux Subsystem (Optional)
      - Install Ubuntu Bash on a Windows OS
      - `Installation Instructions <https://docs.microsoft.com/en-us/windows/wsl/install-win10/>`_
    * - iCommands Installation (Optional)
      - Install iCommands for Linux, Windows, or Mac OSX
      - `Installation Instructions <https://learning.cyverse.org/projects/data_store_guide/en/latest/step2.html#command-line-transfer-with-icommands>`_

Platform(s)
~~~~~~~~~~~

*We will use the following CyVerse platform(s):*

 ..
   #### comment: delete any row not needed in this table ####

.. list-table::
    :header-rows: 1

    * - Platform
      - Interface
      - Link
      - Platform Documentation
      - Quick Start
    * - Data Store
      - GUI/Command line
      - |Data Store|
      - |Data Store Manual|
      - |Data Store Guide|
    * - Discovery Environment
      - Web/Point-and-click
      - |Discovery Environment|
      - |DE Manual|
      - |Discovery Environment Guide|
    * - Atmosphere
      - Command line (ssh) and/or Desktop (VNC)
      - |Atmosphere|
      - |Atmosphere Manual|
      - |Atmosphere Guide|
    * - BisQue
      - Web/Point-and-click and/or Command-line (API)
      - |BisQue|
      - |BisQue Manual|
      - (See Manual)
    * - DNA Subway
      - Web/Point-and-click
      - |DNA Subway|
      - (See Guide)
      - |DNA Subway Guide|
    * - SciApps
      - Command-line (API)
      - |SciApps|
      - (See Guide)
      - |SciApps Guide|
    * - Agave API
      - Command-line (API)
      - |Agave API|
      - |Agave Live Docs|
      - |Agave Quickstart|

Application(s) used
~~~~~~~~~~~~~~~~~~~
..
	#### Comment: these tables are examples, delete whatever is unnecessary ####

**Discovery Environment App(s):**

.. list-table::
    :header-rows: 1

    * - App name
      - Version
      - Description
      - App link
      - Notes/other links
    * - Muscle
      - 3.8.31
      - Multiple sequence aligner
      -	|DE Application URL|
      - |Original App Documentation|
    * - Jupyter-Lab
      - 0.0.3
      - Base Jupyter Lab Image
      - |VICE Application 1 URL|
      - |VICE Manual|
    * - RStudio Geospatial
      - 3.5.0
      - Based on Rocker Geospatial RStudio Image
      - |VICE RStudio URL|
      - |Rocker Docker|
    * - Shiny Apps
      - 1.5.9
      - R Shiny with Geospatial dependencies (GDAL, GEOS, etc)
      - |Geospatial Shiny App|
      - |Rocker Shiny|


**Atmosphere Image(s):**

.. list-table::
    :header-rows: 1

    * - Image name
      - Version
      - Description
      - Link
      - Notes/other links
    * - CyVerse CentOS 6.8 GUI Base
      - 1.0
      - base image CentOS 6.8 with GNOME GUI
      - |Atmosphere Image 1|
      -
    * - Ubuntu 18.04 GUI XFCE Base
      - 1.0
      - base Ubuntu 18.04 with GNOME GUI
      - |Atmosphere Image 2|
      -



Input and example data
~~~~~~~~~~~~~~~~~~~~~~

*In order to complete this tutorial you will need to have the following inputs prepared*

..
	#### comment: delete any row not needed in this table ####

.. list-table::
    :header-rows: 1

    * - Input File(s)
      - Format
      - Preparation/Notes
      - Example Data
    * -
      -
      -
      -

----

**Fix or improve this documentation**

- Search for an answer:
  |CyVerse Learning Center|
- Ask us for help:
  click |Intercom| on the lower right-hand side of the page
- Report an issue or submit a change:
  |Github Repo Link|
- Send feedback: `Tutorials@CyVerse.org <Tutorials@CyVerse.org>`_



Post your question to the user forum:
|Ask CyVerse|

----

|Home_Icon|_
`Learning Center Home <http://learning.cyverse.org/>`__


.. Comment: Place Images Below This Line
   use :width: to give a desired width for your image
   use :height: to give a desired height for your image
   replace the image name/location and URL if hyperlinked


 .. |Clickable hyperlinked image| image:: ./img/IMAGENAME.png
    :width: 500
    :height: 100
 .. _CyVerse logo: http://learning.cyverse.org/

 .. |Static image| image:: ./img/IMAGENAME.png
    :width: 25
    :height: 25



.. Comment: Place URLS Below This Line

   # Use this example to ensure that links open in new tabs, avoiding
   # forcing users to leave the document, and making it easy to update links
   # In a single place in this document

   .. |Substitution| raw:: html # Place this anywhere in the text you want a hyperlink

      <a href="REPLACE_THIS_WITH_URL" target="blank">Replace_with_text</a>


.. |Github Repo Link|  raw:: html

   <a href="https://github.com/CyVerse-learning-materials/cyverse_neon_workshop_2019" target="blank">Github Repo Link</a>

.. |Download Cyberduck| raw:: html

   <a href="https://cyberduck.io/" target="blank">Download Cyberduck</a>

.. |DE Application URL|  raw:: html

   <a href="https://de.cyverse.org/de/?type=apps&app-id=9b41c9e4-5031-4a49-b1cb-c471335df16e&system-id=de" target="blank">DE Application URL</a>

.. |Original App Documentation|  raw:: html

   <a href="http://www.drive5.com/muscle/manual/" target="blank">Original App Documentation</a>

.. |VICE Application 1 URL| raw:: html

   <a href="https://de.cyverse.org/de/?type=apps&app-id=34f2c392-9a8a-11e8-9c8e-008cfa5ae621&system-id=de" target="blank">VICE Application URL</a>
   
.. |VICE Manual| raw:: html   
   
   <a href="https://cyverse-visual-interactive-computing-environment.readthedocs-hosted.com/en/latest/index.html" target="blank">VICE Manual</a>

.. |VICE RStudio URL| raw:: html

   <a href="https://de.cyverse.org/de/?type=apps&app-id=a8b22ed8-e2bc-11e8-a839-008cfa5ae621&system-id=de" target="blank">VICE RStudio URL</a>
   
.. |Rocker Docker| raw:: html

   <a href="https://hub.docker.com/r/rocker/geospatial/" target="blank">Rocker Docker</a>

.. |Geospatial Shiny App| raw:: html
   
   <a href="https://de.cyverse.org/de/?type=apps&app-id=203b0bc2-e2a5-11e8-9df7-008cfa5ae621&system-id=de" target="blank">Geospatial Shiny App</a>
   
.. |Rocker Shiny| raw:: html
   
   <a href="https://hub.docker.com/r/rocker/shiny/" target="blank">Rocker Shiny<a/>

.. |Atmosphere Image 1|  raw:: html

   <a href="https://atmo.cyverse.org/application/images/1384" target="blank">Atmosphere Image 1</a>
   
.. |Atmosphere Image 2|  raw:: html

   <a href="https://atmo.cyverse.org/application/images/1556" target="blank">Atmosphere Image 2</a>

