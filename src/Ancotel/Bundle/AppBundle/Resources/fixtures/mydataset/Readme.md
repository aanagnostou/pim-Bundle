### ADD OUR OWN DATA

### MANDATORY DATA

Be sure you have included mandatory data in your custom installation fixtures. These are:

user group ```all``` named ```All``` regardless of the translation in your ```user_groups.yml```;
attribute group ```other``` in your ```attribute_groups.yml```.
You should also make sure that: - your product attributes have only one attribute of type ```pim_catalog_identifier``` (SKU by default); - you have at least one ```channel``` in your channels.yml; - you have at least one ```category tree``` (default: master) in your ```categories.csv```.
### 1

Check ```pim-Bundle/src/Ancotel/Bundle/AppBundle/Resources/fixtures/mydataset``` to see what the mandatory format is and which fixtures are absolutely needed, then you can draw heavily on ```pim-Bundle/src/Ancotel/Bundle/AppBundle/Resources/fixtures/mydatasetmydatasetAdvanced``` to add optional objects.
