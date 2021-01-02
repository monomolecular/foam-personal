# Project Zelda

Zelda is the codename for the aqcquition of BuyerQuest.

[[Terry Leeper]] Notes:

- Technology
  - Based on Magento v1. x (PHP-based), MongoDB, PostgreSQL.  Would require significant effort to upgrade to 2.x.
  - Would require strong lift to migrate to modern development platform (non-PHP based)
  - Magento was used for base platform with modules to extend product.  Direction is to lessen dependency.
  - Newer components are React and API based.  Older ones are not.  Unclear yet how we can leverage through API calls for functionality.
  - Platform is rendered as an instance per customer and takes 3-6 months to onboard.
    - (Max) A lot of the delay is on the customer side, it will be interesting to try to figure out how to bring that number down and will likely require proessional services that is highly skilled. The same problem exists on the supplier side. Often the customers/suppliers don't have the skills to support the integration themselves and need to outsource and higher consultants.
  - Customer dash boards and ETL are very good, but don’t know cost/scalability yet.
  - Some work on internationalization but unclear how much work remains.
- Technical Team
  - Credible presentations and architectural discussions
  - Majority of developers are based in Ukraine and are contractors.
    - Risk if we lose Ukraine developers as they have most of the implementation details
  - Chief architect has good product background from Magento and eBay
