#Change Product Attribute Set (forked from Ibnab and fixed for Magento2 v2.1.3 )
  - Download / Clone
  - create folder **Ibnab** in **app/code** directory
  - create folder **ChangeAttributeSet** in **app/code/Ibnab** directory
  - paste everything in **ChangeAttributeSet** directory

  * enable extension in **app/etc/config.php** by adding **Ibnab_ChangeAttributeSet => 1**,
  * or via command line: **php bin/magento module:enable Ibnab_ChangeAttributeSet**
  * execute the command **php bin/magento setup:upgrade**