User Access Management in OroCommerce
=====================================

.. contents:: :local:
    :depth: 3

A user's ability to access data and perform actions in the system depends on the following:

*  User role: E.g., sales manager and system administrators need access to different data and system capabilities.

   - Actions a user can perform with particular data depend on access levels set for these actions in the user's role.
   
   - Roles also control access to certain parts of the system. 
   
   Therefore, for some users interface may not always look like on the images in this guide. 

   Users can check their role on the **My User** page. 

*  Organizations and units which the user has access to or has membership in, e.g., users who work in different divisions have access to the data within their division. This information is available on the **My User** page.  

|   
	   
.. image:: /complete_reference/img/system/user_management/access_roles_management/user_access.png 

|

*  Ownership for particular data: some information may be a part of a business unit, division, or organization level. Data ownership creates this relation and help isolate the information based in the ownership (e.g. customer's A owner is a business unit B, whose user B created the customer A record and set onwership to their business unit). Some data may be bound to the particular ownership type (for example, company address book may belong only to the whole company and the ownership may not be limited to the individual user, business unit or division.
  
   Users who create or edit a record can specify a record owner. The range from which they can pick up a record owner depends on the user role(s) and the ownership type of an entity the record they create / edit.  


Related Information
-------------------

* `Role Management </complete_reference/system/user_management/roles.html>`_. 

* `Access Level </complete_reference/system/access_management/access_configuration.html>`_.

* User Access to `Business Units </complete_reference/system/user_management/business-units.html>`_ and Organizations </complete_reference/system/user_management/organizations.html>`_.

* Altering available access levels for the entity by setting `Ownership Type </complete_reference/system/access_management/ownership.html>`_.

* `Sample access configuration </complete_reference/system/access_management/example.html>`_.


.. toctree::
    :hidden:

    ../user_management/roles

    ownership

    access_configuration

    example

    user_access_settings