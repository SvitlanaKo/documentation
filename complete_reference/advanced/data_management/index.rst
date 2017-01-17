.. _user-guide-data-management-basics:

Data Management Basics
======================

.. warning:: Reused from OroCRM. Rework. Should go into platform

With OroCommerce, you can record, store, process, and analyze various customer-related data. This information may cover 
different areas, including personal and contact details, records of the customer activity, possible sales and 
arrangements, and many others. This can include any type of information necessary to monitor, manage, and understand 
specific customer-related activities.

In this article, we will review the ways that data is represented and managed in OroCommerce. For each point that requires 
further explanation, you will find links to related documentation.

.. _user-guide-data-management-basics-entities:

How Data Is Organized
---------------------

The customer relationship management process requires us to collect and process huge amounts of information. OroCommerce is
designed to do this in the most efficient and convenient way possible.

The system organizes information according to Entities, Records, and Properties. An **Entity** is a collection 
of similar information. Each instance of this collection is called a **Record**. Details of each record are its 
**Properties**.

So, information about customers of an online store is collected as properties of the records of the Web Customer entity. 
This means that one of the OroCommerce entities is “Web Customer” and the system knows that records of this entity can have a 
number of properties, such as the first name, last name, email, phone number, ID of the shipping address, ID of the 
cart, and ID's of the orders. The system is also aware that some of these properties need to be defined while some are 
optional. When a new customer is added to the system, their record is created and values of the properties are saved 
for it. If something has changed (e.g., the phone number), the properties are updated.

New records can be created and the existing record can be updated both manually and automatically 
(as a result of integration with third-party systems). 

With OroCommerce's comprehensive access settings you can define what users 
will be able to view, update, delete, and create records of specific entities.

As soon as a property has been updated, all the system users who have access permission will see its new updated state.
This ensures that all the stakeholders can obtain actual and up-to-date information at any moment. 


How Entities Can Be Related
^^^^^^^^^^^^^^^^^^^^^^^^^^^

Some pieces of information are complex enough to have their own entity. For example, for each cart in an online store, 
we need to know its unique ID (number), how many items are in the cart, what their total value is, and whether a 
purchase has been made. Therefore, we have an entity called “Cart”, which will contain records that will have all of 
these properties: ID, number of items, total value, and status. 

One customer may have several carts. In OroCommerce, this means that Web Customer records can be related to many different 
Carts records. To show this, we assign one of the Web Customer properties as a “relation” to carts. This field will 
save an identifier of the customer’s carts (such as a field of the cart). Using this identifier, the system can find 
the cart and bind its properties to the customer.

Moreover, each cart may have several 
items in it. This means that each Cart record is related to its Item records as one to many. 

*User-wise, this means that you can easily get a full picture and drill-down into details as much as required for any 
specific task, as well as update the process with the provided data.*  

See All the Records of a Kind on Grids
--------------------------------------

 A grid is an aggregated view of all the records of the same entity. Each row of a grid contains one record, and each 
 column contains one of the grid properties.

For example, you can open a grid of all the Contacts. (The Contact records represent actual people you are dealing with 
and contains properties such as personal information, details of their position in the customer-company, contact 
details, etc. The contacts may be related to a customer, an opportunity, or any other record in the system, if 
applicable.)

So, we have opened the *"All Contacts"* grid. 

.. image:: /complete_reference/img/advanced/data_management/grid/grid_01.png

We immediately see some major details of our contacts, such as their first and last names, email, phone number, etc.

You can adjust and save grid views, updated and delete grid records, get to the Edit and View pages of any grid record, 
and even export all the data in the grid as a .csv file.

The grid details are described in the `Grids <grids.html>`_ section.

View Details of a Specific Record
---------------------------------

To see more details of a specific record, and to work directly with the record (create a task related to a customer, 
appoint a calendar event for a user, turn a cart into an order, share a contact and so on), you need to get to its 
View page.

For example, we have opened the View page of one of our Contacts.

.. image:: /complete_reference/img/advanced/data_management/view/view_01.png

On the View page, you can see all the details of a record and the location of its address on the map. You can click the 
phone number link to call it via Hangouts or log a call, start writing an email by clicking on its address, or initiate 
a Skype session directly from the View page. If there is a related entity, its identifier will be a link to the View 
page of this entity.

Action buttons at the top of each View page reflect the actions that you can do with the record. 

The View Page details are described in the `View Pages <view.html>`_ guide.

Create New Records and Edit Existing Records
--------------------------------------------

To change the details of an existing record or to create a new record, you need to (re)define the record properties on 
its Create/Edit form.

The Create/Edit form details are described in the `Create/Edit Forms <../../../complete_reference/advanced/data_management/form.html>`_ 
guide.

Tag the Records
---------------

In order to give system users additional information about a record, as well as to systematize records and mark them for 
future usage (e.g., to select them for reports or create segments), you can assign them existing or new tags. For 
example, if you tag a customer as "VIP," this will let the other system users know about the customer's importance. You 
can then adjust the report to show only data for your VIPs and make targeted mailings to them. Moreover, you can find a 
record by its tag with the :ref:search <user-guide-getting-started-search> functionality.
 

Use Workflows to Define Processes
---------------------------------

The process of working with customers is ongoing: carts turn into orders, potential opportunities either fizzle or 
turn into successful deals, and so on. OroCommerce reflects these and other processes by changing record properties and 
sometimes creating new relations. (For example, when a new lead appears and then turns successful, it gets bound to some 
contact, some opportunity, and some customer).

In many cases, the success of a business depends on the unity of its procedures and how closely its employees follow 
them throughout the company. For example, most companies won't allow their employees to close a cart without contacting 
the potential customer, but no one wants to annoy customers with duplicate calls. Likewise, each customer complaint has 
to be researched and responded to, and potential big contracts require specific negotiations before they turn into 
either a successful deal or a lost chance.

In order to regulate this, workflows can be created in OroCommerce. Workflow defines what transitions (changes of 
properties) are available to the system users at each step.

You can find more details about workflows in the :ref:`Workflows <user-guide-workflow-management-basics>` guide.

Log Actions in the System
-------------------------

Whether a workflow has been defined for entity records, or users can process it in any order, it is important to know 
what actions have been performed with a record, as well as by whom. Who has turned this cart into an order? Who has 
closed an opportunity? Who has deleted a customer? Who has changed contact details? In order to know the answers, you 
can use OroCommerce's data audit functionality

A detailed description of the data audit functionality is available in the :ref:`Data Audit <user-guide-data-audit>` 
guide.

Integrate with Third-Party Systems
----------------------------------

OroCommerce can easily integrate with third-party systems, letting users transfer their CRM data into another application, 
and vice versa. For example, the users can upload OroCommerce data into a third-party program, edit it, then transfer that 
data back into OroCommerce. Likewise, data can also be transferred into OroCommerce from another application, processed, then 
transferred back.

For example, integrating with ldap lets you load user records to OroCommerce, integrating with Magento lets you load customer 
records from a Magento store into OroCommerce, and integrating with MailChimp lets you load OroCommerce contact details into 
MailChimp, as well as get the results of an email campaign within OroCommerce.

Integrations are created by the system administrator. A list of integrations available by default is available in the 
`integration  <../../system/Integrations>`_.

Import and Export Data
----------------------

Another way to add records to OroCommerce is to export it from a .csv file. These can consist of customer details, 
information about your leads and opportunities, contact information, and other data.

You can also export data from OroCommerce into a .csv file. You can export all the records of one entity, as well as all the 
records available on a specific grid. 

Step-by-step instructions for the import and export actions are provided in the 
:ref:`Import and Export Functionality <user-guide-export-import>` guide.


Conclusion
----------

Changing record properties in OroCommerce reflects the processes that make up customer relationships. Users can add new 
records to OroCommerce one by one, either with .csv files or with integrations. The way in which records are processed can 
be limited using record types (entities) or with workflows, and all the changes can be tracked with the data audit 
tools. Details of the record can be easily viewed and updated in OroCommerce, and as soon as there has been a change, other 
users will see the updated information. Throughout, stakeholders of customer relationships can access record 
details in order to make their work more efficient.
    
Related Documents
----------------- 
 
.. toctree::

    grids

    view

    form

    tags

    workflows

    data_audit

    import_export

    access_permissions_basics

 
.. |IcDelete| image:: /complete_reference/img/common/buttons/IcDelete.png
   :align: middle
   
.. |IcSettings| image:: /complete_reference/img/common/buttons/IcSettings.png
   :align: middle

.. |IcEdit| image:: /complete_reference/img/common/buttons/IcEdit.png
   :align: middle

.. |IcView| image:: /complete_reference/img/common/buttons/IcView.png
   :align: middle
   
.. |IcBulk| image:: /complete_reference/img/common/buttons/IcBulk.png
   :align: middle
   
.. |ScrollPage| image:: /complete_reference/img/common/buttons/scroll_page.png
   :align: middle
   
.. |BRefresh| image:: /complete_reference/img/common/buttons/BRefresh.png
   :align: middle
   
.. |BReset| image:: /complete_reference/img/common/buttons/BReset.png
   :align: middle