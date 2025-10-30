LIFX LAN protocol description
=============================

``protocol.yml`` - A YAML representation of the public LAN API

More information can be found at https://lan.developer.lifx.com/

Changelog
---------

0.9 - 31 October 2025
    * Defined duration field of ``TileCopyFrameBuffer`` message. 

0.8 - 30 October 2025
    * Added ``TileCopyFrameBuffer`` message.
    * Added ``FbIndex`` field to ``TileBufferRect``
    * Added a number of new button target types.

0.7 - 13 June 2024
    * Added Sky to Tile firmware effects.

0.6 - 27 July 2022
    * Added Button messages for configuring buttons on v3.90 firmware switches.

0.5 - 15 March 2021
    * Added some HEV specific messages relevant to the LIFX Clean.

0.4 - 6 November 2020
    * There is now a ``reserved`` type to indicate a reserved field
    * Added the ``StateUnhandled`` message
      (see https://lan.developer.lifx.com/v2.0/docs/the-lifx-switch#section-light-messages)
    * Added messages for changing the power state of a relay on a switch

0.3 - 20 Mar 2019
    Firmware versions now consist of separate minor/major properties and Tile messages have been renamed to reflect naming conventions.

0.2 - 20 Feb 2019
    Added Extended multizone and firmware effects messages

0.1 - 3 Jan 2019
    Initial release of protocol.yml

Terms and Conditions
--------------------

LAN Protocol. LiFi Labs, Inc. All rights reserved. Usage of this documentation
is bound by the `LIFX Developer Terms <http://www.lifx.com/pages/developer-terms-of-use>`_
