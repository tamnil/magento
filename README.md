# magento block snippet

\{{block type="catalog/product" template="catalog/product/xyz.phtml"}}

 \<block type="page/html" name="root" output="toHtml" template="example/view.phtml">
 
 
\<?php echo $this->getLayout()->createBlock('cms/block')->setBlockId('block_identifier')->toHtml(); 
?> 
