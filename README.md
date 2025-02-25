<table>
  <tr>
    <td align="center">
      <img src="https://raw.githubusercontent.com/GeoNode/documentation/master/about/img/geonode-logo_for_readme.gif" alt="GeoNode" width="150">
    </td>
    <td align="center">
      <img src="https://www.osgeo.cn/qgis/_static/images/osgeoproject.png" alt="OSGeo Project" width="150">
    </td>
  </tr>
  <tr>
    <td align="center">
      <img src="https://www.minambiente.gov.co/wp-content/uploads/2023/05/LOGO_AMBIENTE_2023_01.png" alt="ColLogoMADS1" width="150">
    </td>
    <td align="center">
      <img src="https://www.minambiente.gov.co/wp-content/uploads/2023/05/LOGO_AMBIENTE_2023_02-1.png" alt="ColLogoMADS2" width="150">
    </td>
  </tr>
</table>

Table of Contents
=================

- [Table of Contents](#table-of-contents)
  - [What is GeoNode?](#what-is-geonode)
  - [Try out GeoNode](#try-out-geonode)
  - [Install](#install)
  - [Learn GeoNode](#learn-geonode)
  - [Development](#development)
  - [Contributing](#contributing)
  - [Roadmap](#roadmap)
  - [Showcase](#showcase)
  - [Most useful links](#most-useful-links)
  - [Licensing](#licensing)

SIAC GeoNode?
----------------
![LogoSIAC](https://www.arcgis.com/sharing/rest/content/items/7d3fd32eda7d4c07970c69b9564456c5/resources/MADS-SIAC2022.png?v=1685689481075)

GeoNode is a geospatial content management system, a platform for the
management and publication of geospatial data. It brings together mature
and stable open-source software projects under a consistent and
easy-to-use interface allowing non-specialized users to share data and
create interactive maps.

Data management tools built into GeoNode allow for integrated creation
of data, metadata, and map visualization. Each dataset in the system can
be shared publicly or restricted to allow access to only specific users.
Social features like user profiles and commenting and rating systems
allow for the development of communities around each platform to
facilitate the use, management, and quality control of the data the
GeoNode instance contains.

It is also designed to be a flexible platform that software developers
can extend, modify or integrate against to meet requirements in their
own applications.

Try out GeoNode
---------------

If you just want to try out GeoNode visit our official Demo online at:
http://master.demo.geonode.org. After your registration you will be able
to test all basic functionalities like uploading layers, creation of
maps, editing metadata, styles and much more. To get an overview what
GeoNode can do we recommend to have a look at the [Users
Workshop](https://docs.geonode.org/en/master/usage/index.html).

Install
-------

    The latest official release is 4.0.2!

GeoNode can be setup in different ways, flavors and plattforms. If
you´re planning to do development or install for production please visit
the offical GeoNode installation documentation:

- [Docker](https://docs.geonode.org/en/master/install/advanced/core/index.html#docker)
- [Ubuntu 20.04 LTS](https://docs.geonode.org/en/master/install/advanced/core/index.html#ubuntu-20-04lts)

Learn GeoNode
-------------

After you´ve finished the setup process make yourself familiar with the
general usage and settings of your GeoNodes instance. - the [User
Training](https://docs.geonode.org/en/master/usage/index.html)
is going in depth into what we can do. - the [Administrators
Workshop](https://docs.geonode.org/en/master/admin/index.html)
will guide you to the most important parts regarding management commands
and configuration settings.

Development
-----------

GeoNode is a web based GIS tool, and as such, in order to do development
on GeoNode itself or to integrate it into your own application, you
should be familiar with basic web development concepts as well as with
general GIS concepts.

For development GeoNode can be run in a 'development environment'. In
contrast to a 'production environment' development differs as it uses
lightweight components to speed up things.

To get you started have a look at the [Install
instructions](#install) which cover all what is needed to run GeoNode
for development. Further visit the the [Developer
workshop](https://docs.geonode.org/en/master/devel/index.html)
for a basic overview.

If you're planning of customizing your GeoNode instance, or to extend
it's functionalities it's not advisable to change core files in any
case. In this case it's common to use setup a [GeoNode Project
Template](https://github.com/GeoNode/geonode-project).

Contributing
------------

GeoNode is an open source project and contributors are needed to keep
this project moving forward. Learn more on how to contribute on our
[Community
Bylaws](https://github.com/GeoNode/geonode/wiki/Community-Bylaws).

Roadmap
-------

GeoNode's development roadmap is documented in a series of GeoNode
Improvement Projects (GNIPS). They are documented at [GeoNode Wiki](https://github.com/GeoNode/geonode/wiki/GeoNode-Improvement-Proposals).

GNIPS are considered to be large undertakings which will add a large
amount of features to the project. As such they are the topic of
community dicussion and guidance. The community discusses these on the
developer mailing list: http://lists.osgeo.org/pipermail/geonode-devel/

Showcase
--------

A handful of other Open Source projects extend GeoNode’s functionality
by tapping into the re-usability of Django applications. Visit our
gallery to see how the community uses GeoNode: [GeoNode
Showcase](https://geonode.org/gallery/).

The development community is very supportive of new projects and
contributes ideas and guidance for newcomers.

Most useful links
-----------------


**General**

- Project homepage: https://geonode.org
- Repository: https://github.com/GeoNode/geonode
- Offical Demo: http://master.demo.geonode.org
- GeoNode Wiki: https://github.com/GeoNode/geonode/wiki
- Issue tracker: https://github.com/GeoNode/geonode-project/issues

    In case of sensitive bugs like security vulnerabilities, please
    contact a GeoNode Core Developer directly instead of using issue
    tracker. We value your effort to improve the security and privacy of
    this project!

**Related projects**

- GeoNode Project: https://github.com/GeoNode/geonode-project
- GeoNode at Docker: https://hub.docker.com/u/geonode
- GeoNode OSGeo-Live: https://live.osgeo.org/en/


**Support**

- User Mailing List: https://lists.osgeo.org/cgi-bin/mailman/listinfo/geonode-users
- Developer Mailing List: https://lists.osgeo.org/cgi-bin/mailman/listinfo/geonode-devel
- Gitter Chat: https://gitter.im/GeoNode/general


Licensing
---------

GeoNode is Copyright 2018 Open Source Geospatial Foundation (OSGeo).

GeoNode is free software: you can redistribute it and/or modify it under
the terms of the GNU General Public License as published by the Free
Software Foundation, either version 3 of the License, or (at your
option) any later version. GeoNode is distributed in the hope that it
will be useful, but WITHOUT ANY WARRANTY; without even the implied
warranty of MERCHANTABILITY or FITNESS FOR A PARTICULAR PURPOSE. See the
GNU General Public License for more details.

You should have received a copy of the GNU General Public License along
with GeoNode. If not, see http://www.gnu.org/licenses.
