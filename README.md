# luma_child
Starter Theme for Luma w/ custom css

Keep in dev mode 
bin/magento deploy:mode:set developer
bin/magento deploy:mode:set production

Useful CMDs
php bin/magento cache:flush && php bin/magento cache:clean && bin/magento indexer:reindex
bin/magento setup:static-content:deploy


Install in /app/design/frontend/Magento/luma_child


Name Custom assets in Magento_Theme/layout/default_head_blocks.xml
path to custom assets begins at web/upperrm.css



!TODO: Add Bootstrap 4
https://magento.stackexchange.com/questions/107763/how-to-add-bootstrap-js-in-magento2

View CDN option https://magento.stackexchange.com/questions/228063/how-to-add-bootstrap-4-in-a-magento-2-theme
