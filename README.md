# Overture Maps/OGC Global Entity Reference ID (GER-ID) Draft Community Standard

## The standardization problem

Numerous datasets/resources with geospatial content reference the same real-world entities but use their own conventions, identifiers, and vocabulary, making them difficult to merge and combine.

## What is the GERS framework?

The Global Entity Reference ID (GER-ID) is a framework originally defined by the [Overture Maps Foundation](https://overturemaps.org) to provide a model for generating, cateloguing, and leveraging the use of unique, persistent identifiers (GER IDs) for real-world entities such as buildings, places, and roads in their open map data. These IDs and addociated framework facilitate data interoperability and sharing by enabling different datasets to be easily connected and enriched using a common reference.

### Who supports GERS?

The use of GER IDs and associated support frameworks is supported by a diverse community of over 40 organizations, including Amazon Web Services (AWS), Meta, Microsoft, TomTom, and Esri. These companies have committed to and depend on Overture data. Overture powers the maps used by billions of people across Meta’s, Microsoft’s, TomTom’s, and Esri’s platforms. Many of the Overture Maps supporting organizations are also OGC Member organizations.

## What does a GER ID look like?

GERS IDs use the [UUID - Universally Unique Identifier](https://en.wikipedia.org/wiki/Universally_unique_identifier) format. Every GERS ID follows the standard UUID format (e.g., 12345678-1234-5678-1234-567812345678), making them:

* Globally unique
* System-agnostic
* Easy to implement in any database or application
* Compatible with existing UUID tools and libraries

Why it matters:

* Universal compatibility: UUIDs work in every modern database and programming language
* No collisions: Guaranteed uniqueness across all systems
* Standard tooling: Leverage existing UUID libraries and utilities

## OGC Justification Document

A draft version of the SWG charter document can be viewed here:

* [GERS Community Standard Justification](https://github.com/opengeospatial/Overture-Maps-GERS/blob/main/gers-justification/gers-work-item-justification.adoc)

## General

This repository contains files and documents for the OGC Overture GERS Community Standard activity

* The OGC GERS Community Standard Justification Document
* Issues for discussion and resolution related to the proposed changes.
* Response to comments received during the public comment period.

## Structure

`sources/`::
source of documents, images, and models
