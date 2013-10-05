.. NWPPA Alaska 2013 Presentation
   Created by Keith Gray keith.gray at powereng dot com

IEC 61850 GOOSE Project - Start to Finish
=========================================

Outline
=======

.. contents::
   :depth: 1

Introduction
============

Who am I?
---------

* Keith Gray (keith.gray@powereng.com)
* SCADA and Protection Engineer for 8+ years
* 4+ years of experience with IEC 61850
* On initial team for company IEC 61850 Lab

What am I going to talk about today?
------------------------------------

* IEC 61850 GOOSE Review
* IEC 61850 GOOSE Implementation
* Description of the Project
* Description of the Communications Aided Schemes

  * Team Structure
  * Documentation
  * Implementation
  * Testing
  * Lessons Learned

* Questions

IEC 61850 Review
=================

The Standard
------------

* International Standard

  * Carries IEC name but is derived from work done in the US
    by IEEE/EPRI called UCA 2.0
  * 12+ Sections
  * Some sections are at Edition 1 and some are at Edition 2
  
The Standard (con't)
--------------------

* Covers wide range of topics

  * System and Project Management
  * Engineering Tools
  * Data Modeling
  * Hardware Requirements
  * Product Lifecycle
  * Conformance Testing
  * Communication Structure

* Related standards cover

  * Security
  * Switchgear
  * and more

Promise of IEC 61850
--------------------

* **Interoperability**
* **NOT** *Interchangeability*
* Copper Removal
* Design Time Reduction

Communication Structure
-----------------------

* Station Bus

  * SCADA Protocol (MMS)

    * Client-Server Model

  * Protection Protocol (GOOSE)

    * Peer-Peer Model

 * Process Bus

   * Sampled Values (SMV)

Object Orientation
------------------

* Models substation apparatus as software models
* Standard naming convention

.. image:: _static/breaker-model.png
