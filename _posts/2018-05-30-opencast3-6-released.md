---
title: Opencast 3.6 has been released
date: 2018-05-30
description: This new release includes the popular Paella Player, a new Animate service to create exciting trailers, a Live Streaming Scheduler and many more improvements.
category: release
tags: [release, paella, player, animate, live, scheduler, OAI-PMH, moodle]
---

The new features for this release are:


  - **Streamlined Video Editor** - The video editor has been streamlined to better support the Adopters' processes,
    significantly enhancing the efficiency when it comes to publishing content. Metadata and comments can now be edited
    directly in the video editor - saving the time to navigate within the UI to perform this almost always required
    steps. Keyboard shortcuts can be used to gain further efficiency.

  - **Streamlined Keyboard Accessibility** - The introduction of keyboard shortcuts and vastly improved support for
    tab navigation across the administrative UI allow users to more efficiently interact with Opencast.

  - **Improved User Experience** - The user experience has been approved and streamlined at many other locations. For
    example, the user is presented configurable defaults for the input masks used to schedule recordings. The capture
    agent status is now additional indicated colors. The event counter filters have been reordered to match the life
    cycly of recordings. Series dropdowns are now sorted alphabetically and can be searched. The access policy page now
    supports search and filtering.

  - **Piwik Integration** - The Opencast video player now comes with out-of-the-box Piwik support so that user
    statistics for the player can be easily gathered and visualized

  - **Caption Support** - The Opencast video player now supports captions

  - **Users and roles** - The management of users and roles has been significantly improved to better support
    intergration of third-party user providers (e.g. LDAP, Sakai). The administrative user interface has been
    extended to better support externally provided roles. A new custom role provider allows Adopters to integrate
    their custom roles in a seamless way.

  - **OAI-PMH** - The OAI-PMH implementation has been completely revised. Now implemented as independent communication
    channels, an arbitrary number of OAI-PMH repositories can be handled by the Opencast OAI-PMH server.
    A new OAI-PMH metadata prefix provides direct access to Dublincore metadata catalogs, promoting a strong decoupling
    from external OAI-PMH harverster

  - **Fixed basic LDAP Integration** - Updated format of the configuration files and fixed basic authentication and
    authorization via LDAP. Opencast groups are still not supported.

  - **AAI Support** - Opencast now provides out-of-the-box support for the Authentication and Authorization
    Infrastructre (AAI). This enables adopters to use their existing single sign-on log-in for Opencast.

  - **Sakai User Provider** - Opencast now out-of-the-box provides an Sakai user provider.

  - **AWS S3 and Cloudfront Support** - Opencast now supports distribution to Amazon S3 and Cloudfront.  This support is
    built into the workflow engine by default and requires only minor configuration.  Details on how to set up S3 and
    Cloudfront distribution can be found [here](modules/awss3distribution.md)

  - **Extended Themes** - The themes facility that allows producers to let Opencast brand their produced video content
    using intro and outro videos has been extended to support title slides (metadata within video content) and
    watermarks.

  - **New Workflow Operation Handlers**
    - **WOH tag-by-dcterm** allows media package element tagging based on Dublincore metadata values
    - **WOH configure-by-dcterm** can be used to set workflow instance variables based on Dublincore metadata which in
      turn can be used to conditionally execute workflow operations
    - **WOH probe-resolution** allows workflow operations to be executed based on specific properties ...
    - **WOH publish-oaipmh, retract-oaipmh and republish-oaipmh** support publication management for OAI-PMH
      repositories
    - **WOH publish-aws** enables the publication of distribution artefacts to Amazon S3
    - **WOH send-mail** is a powerful E-mail notification facility that allows workflows to send E-mail containing
      detailed data about media packages and processing incidents
  - **Improved Workflow Operation Handlers**
    - **WOH analyze-tracks** now allows workflow operations to be conditionally executed based on video resolution
      and aspect ratio critera
    - **WOH composite** can now be configured to take the input resolution as output resolution which makes it
      fully capable of generating Picture-in-Picture (PiP) outputs
    - **And Even More** A lot of minor improvements have been added to other worfklow operation handlers.

  - **New Waveform Service** - Waveform generation has been completely rewritten and implemented as an independet
     service. It is now faster and more flexible.

  - **REST Documentation** - The REST endpoint documentation interface comes with a new look & feel and search
    capabilities

  - **Capture Agent API** - The capture agent API supports a new error state that can be set by capture agents
    to indicate errors. Note that the API is, of course, backwards compatible.

  - **Migration Aid** - The Ingest REST endpoint has been extended to offer functionality required when migrating
    data from older Opencast versions. A workflow specifically designed for data migration has been added.

  - **Library Update** - Many libraries have been updated to more recent versions. Most noteworthy, Karaf has
    been updated to version 4.0.8


The Opencast codebase is now located on [GitHub](https://github.com/opencast/opencast).

A full list of changes can be found in the [official release notes](https://docs.opencast.org/r/3.x/admin/releasenotes/).

Visit the [download section](http://www.opencast.org/software/download) for more information on how to get Opencast 3.0.
