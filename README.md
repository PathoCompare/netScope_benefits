# netScope — Product Overview

![netScope Viewer](https://www.netscope.de/fileadmin/_processed_/6/5/csm_09_Directory_Browsing_1a3381feee.jpg)

## Overview

netScope is a small but fairly complete software ecosystem for working with whole-slide imaging data. Instead of concentrating only on viewing slides, the product range covers local viewing, network sharing, browser access and larger on-premises slide management.

The five main products are **netScope Viewer, Cloud, Desk, Group and Server**. They are related quite closely, but each is aimed at a somewhat different setup.

The main attraction is probably compatibility. netScope was originally developed around ZEISS CZI data, but has expanded into a fairly broad collection of microscopy and pathology formats. This is useful in real laboratories, where data rarely comes from one scanner vendor only.

### Supported file types

netScope currently supports:

- CZI
- ZVI
- MRXS
- QPTIFF
- DICOM
- BigTIFF
- Philips TIFF
- IBL
- NDPI
- SVS
- AFI
- SCN
- BIF
- SVSLIDE
- VMS
- VMU
- TIFF / TIF
- JPEG / JPG
- PNG
- GIF

ZEISS and ImageScope annotation formats are supported as well. The manufacturer also notes that additional formats can be added on request. The IBL implementation is described as basic, so that one is worth treating a little more carefully. NnetScope+1


## Viewer

The **netScope Viewer** is the central desktop application. It is designed for viewing, organizing and working with large microscopy slides rather than simply opening an image and zooming in.

![netScope Viewer export](https://www.netscope.de/fileadmin/_processed_/a/9/csm_export_maus_augenregion_542cd32c5a.jpg)

There are useful features for annotations, measurements, slide linking, fluorescence channels, histograms and Z/T-stack viewing. Export and snapshot functions are also well integrated.

The interface is practical, although it does look a little more traditional than some newer web-based pathology applications. This isn't a serious problem once you know where the tools are, but first-time users may need some time to find everything.

Another small limitation is the strong Windows focus. AlternativeTo lists Windows as the main platform and also mentions Wine and CrossOver, which gives other users some options, but native multi-platform support would obviously be nicer. AAlternativeTo


## Cloud

**netScope Cloud** takes much of the same functionality into the browser. It is probably the easiest version to get started with, especially when slides need to be shared with people who should not have to install the desktop application.

The browser approach is convenient for remote work, collaboration and teaching. It also avoids having to maintain the complete server infrastructure yourself.

The downside is mostly the usual one with cloud storage: large whole-slide datasets can become quite substantial, and organizations with strict internal infrastructure policies may prefer to keep everything on-premises.

## Desk

**netScope Desk** is the simple local-sharing option.

A folder on a workstation can be shared with other netScope Viewer users, avoiding the need to copy large WSI files between computers. It is an uncomplicated idea and probably works well for smaller departments.

The main weakness is quite clear: clients can only access the slides while the local user is logged in. The permissions also correspond to that local user's privileges. NnetScope


So Desk is useful, but it is not really a replacement for a proper central server.

## Group

**netScope Group** improves the Desk concept by adding Windows Active Directory Federation Services.

Users can receive individual permissions, and a Windows service keeps the slides accessible even when nobody is logged into the workstation. This makes Group more suitable for an institutional environment.

The catch is that it still depends on a Windows/domain-oriented setup. That is fine for a Microsoft-heavy organization, but less attractive if the infrastructure is more mixed.

## Server

**netScope Server** is the most complete on-premises product.

![netScope Server](https://www.netscope.de/fileadmin/images/netScopeServer/99mikroTransparentHistogram.png)

It combines slide storage and organization with browser access, user and group management, permissions, annotations, comments, audit trails and collaboration. SAML 2.0 single sign-on is supported, and the system can work with existing folder structures. NnetScope


This makes Server considerably more than a viewer. It is closer to a dedicated WSI management platform.

The price of that flexibility is complexity. IIS, SQL Server and server administration are not something every small laboratory wants to maintain. For larger environments, however, the additional control makes more sense.

## Overall impression

netScope is not the flashiest digital pathology platform, but that is not necessarily its main goal. The software seems to concentrate more on compatibility and practical workflows.

The strongest point is the broad format support combined with several ways of sharing the same underlying slide data. A small team can use Viewer and Desk, a Windows-based organization can move to Group, and larger installations can use Server or Cloud.

There are some rough edges. The interface and parts of the documentation feel a little dated, and some wording is not perfectly polished. But these are relatively minor issues compared with the useful functionality underneath.

Overall, netScope is a fairly solid and somewhat understated solution: not perfect, but more capable than its relatively modest presentation might suggest.
