# migrate
compartmentalize my migrations


install organic groups
install c11n_migrate 
make Chapter type a group
install blog [group_content]

I added blogmig1.yml and personmig.yml into the Config Sync box:
/admin/config/development/configuration/single/import


install person
ADD A CHAPTER entity-REFERENCE field_chapter to the PERSON

drush migrate-reset-status -y the-name-of-the-id-in-yml
drush migrate-import -y the-name-of-the-id-in-yml

drush migrate-import -y blogmig1
drush migrate-import -y personmig
drush migrate-import -y chapters