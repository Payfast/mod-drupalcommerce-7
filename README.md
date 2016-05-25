Drupal Commerce Payfast payment module 1.0.1
=============================================

Copyright © 2011 - 2016 PayFast (Pty) Ltd

LICENSE:

This payment module is free software; you can redistribute it and/or modify
it under the terms of the GNU Lesser General Public License as published
by the Free Software Foundation; either version 3 of the License, or (at
your option) any later version.

This payment module is distributed in the hope that it will be useful, but
WITHOUT ANY WARRANTY; without even the implied warranty of MERCHANTABILITY
or FITNESS FOR A PARTICULAR PURPOSE. See the GNU Lesser General Public
License for more details.

Please see http://www.opensource.org/licenses/ for a copy of the GNU Lesser
General Public License.

INTEGRATION:
Requirements:-
Drupal-7.17 ( http://drupal.org/drupal-7.17-release-notes ) or commerce_kickstart 7.x-2.0-rc4 (http://drupal.org/node/1836498 )
Commerce 7.x-1.4 ( http://drupal.org/node/1819278 )

Installation:-
1. Download the module from https://github.com/PayFast/mod-drupalcommerce-7/archive/master.zip and extract the contents into a new folder
2. Move or copy this new folder to your “sites/all/modules” directory
3. Log in as a privileged user on your Drupal7 site
4. Navigate to “modules” via the admin menu and enable the module
5. Navigate to “Payment methods” via the admin menu and:
- click on “PayFast” under the “Enabled payment method rules”,
- then, under “Actions” in the “Elements” block, click on “Enable payment method Payfast”
- The sandbox credentials will be filled in automatically
- Click save to make test transactions with the sandbox (using the account details under “User account:” on https://www.payfast.co.za/c/std/integration-guide#system)
- To make real transactions select “live” and replace the sandbox credentials with your Payfast merchant id and key

******************************************************************************
*                                                                            *
*    Please see the URL below for all information concerning this module:    *
*                                                                            *
*          https://www.payfast.co.za/shopping-carts/drupal-commerce/         *
*                                                                            *
******************************************************************************
