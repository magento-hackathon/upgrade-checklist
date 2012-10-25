Chesklist For Estimating Magneto Upgrade
=================

- Number of enabled extenstions.
  
  For each extension check.

  - compatibility with Magento version you are upgrading to [CRIT]
  - class rewrites
  - layout updates
  - addition of foreign keys in install scripts

  &nbsp;
- Custom theme
  - if upgrade made from version before 1.4 [CRIT]
  - if layout XMLs are overwritten

  &nbsp;
- app/code/local/Mage [CRIT]
- core modifications [CRIT]