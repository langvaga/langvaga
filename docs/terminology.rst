***********
Terminology
***********

This document holds definitions for terms used throughout the långväga software
suite.

.. glossary::

   AC
   Access Customer
      Access Customer. An access customer is a company that is a customer of an
      access provider's network, such that they can deliver their
      inter-connection (long distance) services to an end user of that network.
      Access customer companies are commonly referred to as an IXC
      (Inter-Exchange Carrier).

   AP
   Access Provider
      Access Provider. An access provider is a company that offers local
      telephone services to end-user customers. Access provider companies are
      commonly referred to as a LEC (Local-Exchange Carrier).

   Långväga
      A Swedish word standing for long-range. Used within this software suite as
      an allusion to long-distance, which is the primary concern of the PIC/CARE
      system; the sending and receiving or orders that subscribe a customer to
      an IXC's long distance service.

   PIC/CARE
      PIC/CARE; where PIC stands for pre-subscribed inter-exchange carrier and
      CARE stands for customer access record exchange, is a standard concerned
      with defining inter-company processes involved with exchanging customer
      subscription information between ACs and APs.

   TCSI
      TCSI stands for transaction code status indicator. A TCSI is composed of 2
      parts, a 2 digit TC (Transaction Code) followed by a 2 digit SI (Status
      Indicator). Combined, they define a type of transaction, followed by a
      sub-type describing the particular circumstances being identified by the
      transaction.

      A TC code starting with the digit *0* defines transactions initiated by an
      AC towards an AP. A TC code starting with the digit *2*, *3* or *7*
      defines transactions initiated by an AP towards an AC.
