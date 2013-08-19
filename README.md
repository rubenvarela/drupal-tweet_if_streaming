# Description
Drupal module — When a user is streaming via Ustream, it searches a Twitter account and prints a Tweet if it matches a certain criteria.

## Installation
 1. Download and extract the following module into the corresponding *sites/*/module/ folder. 
 2. Afterwards in the website, go to */admin/modules* and Enable the module.
 
## Usage
 1. Block – If you have a defined region, you can go to  */admin/structure/block* and put the block in the region you want.
 2. PHP Snippet - You can open your theme's page.tpl.php and in it you can use the following code:
     `<?php print tweet_if_streaming_print(); ?>` 