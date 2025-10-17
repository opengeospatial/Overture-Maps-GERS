# Overture Maps/OGC Global Entity Reference System (GERS) Draft Standard

## What is GERS

The Global Entity Reference System (GERS) is a framework created by the http://https://overturemaps.org/[Overture Maps Foundation] to provide unique, persistent identifiers (GERS IDs) for real-world entities such as buildings, places, and roads in their open map data. These IDs facilitate data interoperability and sharing by enabling different datasets to be easily connected and enriched using a common reference.

### Who supports GERS?

GERS is supported by a diverse community of over 40 organizations, including Amazon Web Services (AWS), Meta, Microsoft, TomTom, and Esri. These companies have committed to and depend on Overture data. Overture powers the maps used by billions of people across Meta’s, Microsoft’s, TomTom’s, and Esri’s platforms. Many of the Overture Maps supporting organizations are also OGC Member organization.

## What does a GERS ID look like?

GERS IDs use the https://en.wikipedia.org/wiki/Universally_unique_identifier[UUID - Universally Unique Identifier)] format. Every GERS ID follows the standard UUID format (e.g., 12345678-1234-5678-1234-567812345678), making them:

* Globally unique
* System-agnostic
* Easy to implement in any database or application
* Compatible with existing UUID tools and libraries

Why it matters:

* Universal compatibility: UUIDs work in every modern database and programming language
* No collisions: Guaranteed uniqueness across all systems
* Standard tooling: Leverage existing UUID libraries and utilities

## OGC Draft of the Charter

A draft version of the SWG charter document can be viewed here:

* https://github.com/opengeospatial/Overture-Maps-GERS/blob/main/gers-swg-charter.adoc[GERS SWG Charter]

## General

This repository contains files and documents for the OGC Overture GERS Community Standard activity

* The OGC GERS Community Standard Justification Document
* Issues for discussion and resolution related to the proposed changes.

## Structure

`sources/`::
source of documents, images, and models
