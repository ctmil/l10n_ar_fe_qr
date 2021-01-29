# Localización Argentina - FE QR

QR Code for AFIP FE on Odoo 11 Invoice - Localización Argentina

Due to the different methods of invoices generation, for version 11 the report must be modified using the QR image generated in the field `image_qr`

## For Aeroo Report

In the ODT file, create a Frame object (Insert > Frame > Frame). Go to tab "Options" and fill the "Name" field with the following code: `image: asimage(o.image_qr, size_x=90,size_y=90,hold_ratio=True)` 

You can adapt `size_x` and `size_y` to make QR Image more or less bigger.
