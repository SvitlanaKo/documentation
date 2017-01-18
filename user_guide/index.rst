User Guide
==========

.. contents:: :local:

OroCommerce as a B2B eCommerce platform provides a number of self-serve capabilities, mature buyer-seller interaction processes (e.g. for placing orders, sharing pricing information, requesting quotes, and submitting proposals), and may be easily used as a B2B Marketplace that connects a wide range of suppliers with multiple buyers. Buyers may get multiple offers and bids across various goods and services.

OroCommerce provides corporate accounts, multiple organizations, websites and stores, high-performance content management system (CMS) with `product </complete-reference/products/products>`_, `inventory </complete-reference/inventory/manage-inventory>`_ and `warehouse </complete-reference/inventory/warehouses>`_ management, personalized `web catalog management </complete-reference/marketing/web-catalog>`_, multiple and customized `price lists </complete-reference/sales/price-lists>`_ for your sales organization and multiple `shopping lists </complete-reference/sales/shopping-lists>`_ for your buyer's organization.

Core Features
-------------

* `Corporate Accounts <../complete_reference/customers/index>`_: Manage complex, hierarchical corporate account structures via the seller admin console. Buyers can also configure their own corporate account structure, add authorized users, and create purchasing rules regardless of whether your account structure has multiple businesses, teams, departments, offices, or branches.
* `Access Controls <../complete_reference/system/access_management>`_, `Roles & Permissions <../complete_reference/system/user_management/roles>`_: Providing the correct user the right access to the right information is a crucial capability. Both sellers and authorized buyers can manage access levels to information, like specific price lists and product catalogs, for both user groups or individual users.
* Multiple `Organizations <../complete_reference/customers/index>`_, `Websites <../complete_reference/system/websites>`_ & `Stores <../complete_reference/marketing/web_catalog>`_: Many businesses manage multinational brands that operate across various countries, currencies, and tax regulations. OroCommerce Enterprise Edition comes out-of-the-box with flexible and robust multi-website management capabilities which allows organizations to easily orchestrate multiple businesses from one central admin console.
* `Content Management System <../complete_reference/marketing/index>`_: Native CMS capabilities allow marketers and merchandise managers to manage robust digital media-enabled catalogs and rich product information pages providing buyers with the information they need to make purchasing decisions. In addition, OroCommerce’s theme is designed with an intuitive, user-friendly front-end which allows buyers to easily find the information and products they need.
* `Personalized Catalog Management <../complete_reference/products/index>`_: Versatile catalog management capabilities allow B2B sellers to customize product catalogs to specific corporations, divisions, business units, and even individual buyers or customers. Each group has access to its own catalog where purchasing managers are able to view its content and purchase products.
* `Multiple & Customized Price Lists <../complete_reference/sales/price_lists/index>`_: Create and manage multiple customized price lists for each customer, company, or business unit based on the negotiated contracts. Each price list can contain an unlimited number of price points, various tiers, and different currencies.
* `Multiple Shopping Lists <../complete_reference/sales/shopping_lists>`_: Corporate buyers working on multiple projects, such as trade show displays, printed materials, or product/equipment for different business units, can manage and save multiple shopping lists in OroCommerce. This allows buyers to save shopping lists for future use and quickly purchase previously saved shopping lists.
* `Streamline Buyer-Seller Interaction <../complete_reference/sales>`_: OroCommerce improves buyer-seller interactions by providing buyers an easy way to create and submit order forms, purchase orders, RFQs, and more. Sellers are then able to easily respond to orders & quote requests on the same platform thus facilitating an efficient negotiation process between the buyer and the seller.
* `Segmentation & Custom Reports <../complete_reference/reports_and_segments>`_: The robust dashboard and reporting engine along with advanced segmentation capabilities allow sellers to gain actionable insight to their data. Leverage OroCommerce’s segmentation and reporting engine to track key business KPIs, understand customer’s purchasing patterns, and send timely, targeted marketing campaigns.
* `Flexible Workflow Engine <../complete_reference/system/websites>`_: Create an unlimited number of custom eCommerce workflows to support both buyer and seller-related processes. The flexible workflow engine allows sellers to customize workflows like the checkout experience or order submission process. Automatic alerts can also be set to trigger when orders reach a certain value but haven’t been purchased.

Community Edition vs Enterprise Edition
---------------------------------------

The key differences between CE and EE is the application’s enhanced performance scalability, extended functional capabilities and customer support.

On top of the features available in OroCommerce CE, OroCommerce EE provides:

* Big data processing with PostgreSQL database.
* Big data search with ElasticSearch.
* Integration with RabbitMQ to handle large amounts of job queues.
* Multiple organizations support.
* Multiple websites support.
* Multiple currencies support.
* Support for inventory management across multiple warehouses.
* OroCRM capabilities integrated into OroCommerce interface.

Orientation in the OroCommerce User Guide
-----------------------------------------

For detailed information on using OroCommerce CE and EE, please see the following topics:

* `Navigation and using OroCommerce UI <../complete_reference/getting_started/index>`_

* `Managing master catalog, product details, and price attributes <../complete_reference/products/index>`_

* `Managing inventory and product availability in the warehouses <../complete_reference/inventory/index>`_

* `Managing product prices <../complete_reference/sales/price_lists/index>`_

* `Managing customers, their subsidiaries and users <../complete_reference/customers/index>`_

* `Handling customer quotes <../complete_reference/sales/quotes/index>`_, `customer requests for quote <../complete_reference/sales/requests_for_quote/index>`_

* Configuring `payment <../complete_reference/sales/payment/index>`_ and `shipping <../complete_reference/sales/shipping/index>`_ options available to the csutomer users during checkout.

* `Using marketing tools: custom web catalog, landing pages, and customer login pages <../complete_reference/marketing/index>`_

* `Controlling tax rates that are included in the customer order <../complete_reference/taxes/index>`_

.. note:: Depending on your role in OroCommerce and custom system permissions, the available information and actions may vary.


Table of Contents
-----------------

.. toctree::
   :maxdepth: 1

   ../complete_reference/getting_started/index

   ../complete_reference/products/index

   ../complete_reference/inventory/index

   ../complete_reference/sales/price_lists/index

   ../complete_reference/customers/index

   ../complete_reference/sales/quotes/index

   ../complete_reference/sales/requests_for_quote/index

   ../complete_reference/sales/payment/index

   ../complete_reference/sales/shipping/index

   ../complete_reference/marketing/index

   ../complete_reference/taxes/index

..   install/index


.. comment
   # Quick Start
   # -----------
   # 
   # * You are :ref:`starting a new B2B Commerce project <   # orocommerce-user-guide-starting>`, and plan to sell products and    # services to multiple business customers.
   # 
   # For the role-based information, please see the following sections on    # using OroCommerce as a...:
   # 
   # * `Business owner </guides-by-role/business-owner-guide>`_
   # * `Buyer </guides-by-role/buyer-guide>`_
   # * `Sales person </guides-by-role/sales-guide>`_
   # * `Organization administrator </guides-by-role/org-admin-guide>`_
   # * `Catalog manager </guides-by-role/catalog-manager-guide>`_
   # * `System administrator </admin-guide>`_
   # * `System comfiguration manager </guides-by-role/config-guide>`_

.. comment
   #Starting a new B2B commerce project
   #-----------------------------------
   #
   #**WORK IN PROGRESS**
   #
   #You need a complete transparency of your services for your customers, easily controlled sales and marketing process for your employees, and access to statistics and retrospective data for leadership and management team. You might start with the following:
   #
   #* Request a demo (more info)
   #* Get a demo instance in Oro Cloud to try using OroCommerce without a hassle of complete configuration and setup. On your request, the demo instance may be installed with the demo data that reveals most of the functionality and provides the best learning experience for the new users.
   #* Make your mind about having an on-premise deployment vs OroCommerce in a Cloud. 
   #* Review a getting started section that explains basic configuration and data you'll need to start your B2B sells online.
   #* Plan your B2B Commerce rollover. Get more information about :ref:`using OroCommerce for Enterprize sales processes <orocommerce-user-guide-as-an-enterprise>` or about :ref:`using OroCommerce as a small and middle-size business owner <orocommerce-user-guide-as-a-business-owner>`).
   #
   #.. _orocommerce-user-guide-as-an-enterprise:
   #
   #Using OroCommerce for Enterprise sales processes
   #------------------------------------------------
   #
   #**WORK IN PROGRESS**
   #
   #* It should scale
   #* More distributed decisions, approval processes, more granular set up (more websites, locales, etc.).


.. COMMENT -------------------------------------- This text is in the User Guide body
    * Installation
      * On Premise deployment
        * Obtain the application
        * System requirements
        * Installation wizard
      * OroCloud
        * Installation wizard / Initial configuration
          
    * Getting started
        * Navigation
        * Roles and permissions
        * Initial configuration
        * Quick start for...
            * Sales manager
            * Commerce manager
            * Oro Commerce administrator
              
    * Manage your product catalog
      * Product information management
      * Product media (images)
      * Product attributes
        * Attribute Sets
        * Price attributes
      * Units of quantity
      * Master catalog
      * Export/import product data
      * Product variants
      * Custom personalized catalogs
      * Web categories
      * Landing pages & embedding product info & add to card
      * Product visibility
        
    * Inventory
      * Overview
      * Configuration options
      * Product-level configuration
      * Working with multiple warehouses
      * Export/import inventory
        
    * Pricing
      * Overview
      * Configure prices for a website, customer group, customer
      * Scheduling
      * Export/import
      * Price attributes
      * Rule-based configuration
      * Assignment rules
      * Calculation rules
      * Working with multiple currencies
      * Price list ownership
      * Internal price lists
        
    * Customers
      * Customer accounts
      * Managing users
      * Roles and permissions
      * Account hierarchy
      * Customer groups
      * Delegate account management to customers
        
    * Quotes & Proposals
      * RFQs
        * RFQs in general + notifications
        * Default RFQ workflows (management console + store frontend)
        * Customize RFQ submission form
        * Processing RFQs, creating quotes (proposals)
          * Working with line items, etc.
        * Quote shipping
        * Quote payment term
        * Quote discounts
          
    * Order Management
      * Editing an order
      * Default order workflow (management console)
      * Default order workflow (store frontend)
      * Create an order
      * Customizing the checkout experience
        * Address books and permissions
        * Checkout workflow
        * Payment “tricks”
        * Shipping “tricks”
      * Export orders
      * Shipping tracking
        
    * Payment
      * Enabling payment methods
      * Configure payment rules
      * Payment terms
      * Payment methods:
        * Payment terms
        * PayPal Payments Pro
        * PayPal PayFlow Gateway
        * Check/Money Order
        * COD
        * Bank wire transfer
          
    * Shipping
      * Enabling shipping methods
      * Configure shipping rules
      * Product shipping attributes
      * Shipping methods:
        * Flat Rate
        * Table Rates
        * UPS
        * FedEx
        * USPS
        * ...
          
    * Marketing
      * Landing pages
      * Content blocks
      * Banners
      * Homepage
      * Promotions
        
    * Taxes
      * USA
      * Canada
      * European Union
      * Great Britain
      * Australia
      * Other counties (“get in touch with us” or refer to the partner listing page)
        
    * Support
      * Online documentation, feature videos
      * On-demand training
      * How to contact us
      * Refer to partners page
      * OroCloud customers ------------------------------------- End of User Guide body
