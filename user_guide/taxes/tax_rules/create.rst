Create a Tax Rule
~~~~~~~~~~~~~~~~~

To create tax rules for a particular tax jurisdiction:

1. `Create a tax jurisdiction </user_guide/taxes/tax_jurisdictions/create>`_ (country, state and a range of zip codes) where a special taxation rules apply.

2. Create customer tax codes for every group of buyers that have fixed tax rates in this tax jurisdiction. `Link the customer groups to their respective tax codes </user_guide/taxes/link_tax_code_to_a_customer>`_.

3. Create product tax codes for every group of products that have fixed tax rates in this tax jurisdiction. Ensure that these tax codes are `assigned to the products </user_guide/taxes/link_a_tax_code_to_a_product>`_.

4. Create all `the tax rates </user_guide/taxes/taxes/create>`_ defined by the tax jurisdiction for the customers you are serving and products you are selling.

5. Finally, for every the valid combination of the tax rates, product types and customer types, create a tax rule:

     a) Navigate to **Taxes > Tax Rules** and click **Create Tax Rule**.

        .. image:: /user_guide/img/taxes/tax_rules/CreateTaxRule_TaxRules_Taxes_drop.png

     b) In the lists select te Account Tax Code (customer tax code), product tax code, tax jurisdiction, and tax (tax rate). Optionally, add description of the tax rate applied.

     c) Click **Save** or **Save and Close**.

.. stop