# OBIS-GBIF Technical Implementation Plan


# Introduction

This plan outlines the key technical objectives to be achieved through the collaboration between GBIF and OBIS. The primary purpose of this document is to propose a high-level milestone roadmap that will assist both organizations in aligning their respective initiatives and activities with a coordinated release schedule for products and services. 

The outcomes of this plan may include prototypes, production-ready services, standards, and training 

materials.

The general activities detailed were initially outlined in  the [Action Plan on Marine Biodiversity Data](https://docs.gbif.org/obis-gbif-action-plan-2024/en/).


# Milestones plan

The proposed plan is organized under quarterly milestones, at the end of each quarter a set of deliverables. The plan has been designed to develop fundamental services and activities first and then later in the process deliver artifacts based on developed services. Additionally, this plan takes an opportunistic approach of the the already existing plans of both organizations with the intention of maximizing available resources.


## Milestone 1 Initial taxonomy, traits and data publication alignment  

Timeline: Q4 2024

This milestone aims to achieve an initial alignment of GBIF’s core data services with the use of WoRMS Checklists. To support this integration and stay aligned with new developments from CoL+ and checklistbank.org, GBIF has initiated efforts to enable the organization of occurrence records across multiple taxonomies (see [https://github.com/gbif/occurrence/issues/342](https://github.com/gbif/occurrence/issues/342)). 

The main activities identified for this milestone are:



* **Proof of concept** in the GBIF UAT environment to demonstrate how occurrence records can be ingested and processed using multiple taxonomies: the GBIF Backbone and WoRMS Checklists.
* **Provide a clear specification** on how species traits from WoRMS can be integrated into the Catalogue of Life (CoL).
* **Initiate discussions** on how a vocabulary of traits can be promoted through TDWG, and explore the feasibility of using the GBIF Vocabulary Server to integrate it into the GBIF Data Pipeline.
* **Evaluate and present** the existing capacities of the GBIF IPT to handle and publish frictionless data.
* **Scope** the options for a shared infrastructure OBIS-GBIF.


## Milestone 2 WoRMS-Occurrence integration

Timeline: Q1 2025

The main objective of this milestone is to implement the indexing of multiple taxonomies/checklists, including WoRMS, in the GBIF production systems. Additionally, AphiaIDs will be made available in the GBIF data portal and data services for search and download.


## Milestone 3 Improve Marine Data Interpretation

Timeline: Q2 2025

The objective of this milestone is to improve the interpretation of marine records in GBIF and evaluate the integration of marine data discovery through [Marine Regions](https://www.marineregions.org/).


## Milestone 4 New Data Model - Event Core - PoF

Timeline: Q3 2025

This milestone aims to assess the benefits of using a more expressive data model for publishing marine data. Additionally, the representation of records published as Event Core should be improved in the GBIF Data Platform.


## Milestone 5 DOI tracking - EBVs - Environment Flags

Timeline: Q4 2025

The objective of this milestone is to initiate the implementation of DOI tracking for OBIS data, introduce environment flags and filtering capabilities, and propose a method for implementing essential variables.
