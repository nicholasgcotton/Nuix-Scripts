# Nuix Scripts Index
An index of useful Nuix Workstation Scripts, including mine and others.

## Nuix Export To Evidence & Reports III (E&R III)
https://github.com/nicholasgcotton/Nuix-Export-To-Evidence-Reports

Nuix API Script to support exporting data from Nuix Workstation to Evidence & Reports 3 (E&R III)


## Scripted Metadata for DOCID
https://github.com/nicholasgcotton/Nuix-Scripted-Metadata-DOCID

Find the DOCID of the current item using scripted metadata. Intended for reviewing EDRM/Relativity/Concordance formatted data in Nuix Workstation.

e.g. when you are reviewing data such as "\Natives\VOL00001\DOCID12345.msg\Re: Contract Dispute" Nuix Workstation will return the email item as the name, that is "Re: Contract Dispute" but it may also be helpful to keep track of the EDRM style DOCID, e.g. DOCID12345.msg.

Script must be updated with the current DOCID basename (e.g. "DOC") to work.

## Nuix Intake Scripts
https://github.com/nicholasgcotton/Nuix-Intake-Scripts

Standard intake scripts for RCMP Nuix Workstation Intake, including "Default Quality Assurance and Tags v3" and "Email Chain Cluster Analysis v 1.1".

The purpose of these scripts is to automate parts of the Nuix Workstation intake that I always do the same way.

# Other Useful Nuix Scripts
Scripts created by Nuix, see https://github.com/Nuix for a full list. 

## Nukers
https://github.com/Nuix/Nukers

Sometimes you just need to completely remove work product from a case. In many instances, the API require that you first remove work product from all items before removing it entirely from the case. This repository contains a series of scripts to assist in removing:

* Custom Metadata
* Tags
* Exclusions
* Production Sets
* Item Sets
* Item Comments
* Custodians

Note that the scripts remove the above work product as best they can based on available API methods. Records of these things will still exist in the case's history

## Scripted Metadata Profile Fields
https://github.com/Nuix/Scripted-Metadata-Profile-Fields

This repository contains a collection of scripted metadata profile fields. Allows you to display scripted metadata within the Nuix Workstation interface, showing metadata for various types/sources of data including:

* Date
* Duplicates
* Emails
* Folder Size
* Misc Items
* Pathing
* QC

## Create Tag Batches
https://github.com/Nuix/Create-Tag-Batches

This script allows you to tag items in batches based on number of items or number of batches.

## Bitcoin Extractor
https://github.com/Nuix/Bitcoin-Extractor

This repository contains 2 scripts to assist with extraction and verification of Bitcoin addresses.
