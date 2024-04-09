# Project Live Link : https://mdmamunwebdev.github.io/custom-js-form-api/?tenant_id=pt_tenant_3376520&property_id=pt_property_2119651



# Project Description

Write a JavaScript script that created this form in s given DIV. The created form should be responsive for desktop/tablet/mobile. The form function, logic should replicate the following form:

https://tools.fluidbyte.io/app/test-lease-renewal-form/main-661298e81046c52060fee6b0?tenant_id=cHRfdGVuYW50XzMzNjEwMjA%3D&property_id=cHRfcHJvcGVydHlfMjExOTY1MQ%3D%3D

Additionally detail:

1) the script should extract the tenant_id and property_id from url params to do a GET request for the info that goes into the form. If no tenant_id or property_id, show an error. 

2) when Form is submitted, perform a POST request with the collected data.  For now, you can post to a webhook testing site: https://webhook.site/#!/view/6d0b1ca9-3fa5-47b7-9d5b-c08b16c6717a
