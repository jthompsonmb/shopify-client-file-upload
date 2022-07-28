# shopify-client-file-upload
Add the ability for clients to upload files with a product when added to cart

Some simple javascript and jquery to add to Shopify's Dawn theme to allow users to upload files when a product is added to the cart. Insert this inside the form tag ({%- form 'product', product, id: product_form_id, class: 'form', novalidate: 'novalidate', data-type: 'add-to-cart-form' -%}) in the main-product.liquid file. 
