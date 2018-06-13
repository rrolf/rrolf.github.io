---
title: About Opencast Software
description: Opencast is an open source solution for automated video capture and distribution at scale. Build custom capture, processing, scheduling and distribution solutions for your organization with one flexible platform.
---

{% include community_menu.html 
title="Try it"
description="This is an official Opencast test server. The server is reset on a daily basis. The credentials are admin / opencast. [Here you can try it](https://develop.opencast.org)"
%}

{% include community_menu.html 
title="Install it"
description="Here you can install it [Installation](https://docs.opencast.org/r/5.x/admin/installation/)"
%}

{% include community_menu.html 
title="Use it"
description="Here you learn how to use it [Usage](https://docs.opencast.org/)"
%}

# Features

{% include fullsizebox.html 
title="Schedule"
description="Opencast Schedule lets you schedule an event to be automatically recorded on specific days and times of the week, and the distribution channel to which the recordings will be published.

- Based on open standard iCal format
- Manual or automated capture based on schedule
- Configurable capture encoding specifications
- iCalendar import from external scheduling source
- Integrates with open source and proprietary capture hardware
- Tools for disaster recovery"
image="/assets/img/large-schedule.jpg"
align="left"
imagewidth="40%"
%}

{% include fullsizebox.html 
title="Process"
description="Opencast Process is a workflow-based system that provides a scalable infrastructure for encoding and enriching video with metadata, preview images, brands, captioning and text analysis to make the media more discoverable and accessible.

- Customizable workflow for processing throughout the distribution life cycle
- Default encoding engine based on FFmpeg; other engines can be integrated
- Advanced media analysis, including video OCR that extracts time-synched metadata from slides
- Powerful search capabilities for static, dynamic, and user-generated metadata
- Administrative dashboard for monitoring and management of media life cycle"
image="/assets/img/large-process.jpg"
align="right"
backgroundcolor=site.data.colors.box
imagewidth="40%"
%}

{% include fullsizebox.html 
title="Distribute"
description="With Opencast Distribute enables you to publish recordings for on-demand viewing or download. Learning tools interoperability (LTI) and RSS/Atom feeds are available for integration with other systems, and publishing to iTunes U and YouTube can be automated.

- Integration with many platforms, including Learning Management Systems via LTI
- Publish as downloadable and/or streamed content
- Local search index using solr available
- Distribution via RSS/Atom to learning management systems
- Automated publishing to iTunes U and YouTube
- Custom workflows to enable distribution and archiving to local or distribution servers"
image="/assets/img/large-distribute.jpg"
align="left"
imagewidth="40%"
%}

{% include fullsizebox.html 
title="Playback"
description="The Opencast player can be used as a standalone application, or embedded inside other applications like blogs, wikis or content management systems. Opencast Playback enables slide segmentation and in-video text search. All player functionality is fully accessible, supporting assistive technology across multiple platforms.

- Split-screen player for viewing video and slide content simultaneously
- Heat maps indicate sections of content most often watched
- REST APIs make it easy to extend to or integrate players
- Easy customization and localization of the player interface
- Customizable permissions settings
- User directory integration (LDAP, CAS etc.)
- Adaptive Streaming support with HTTP Live Streaming (HLS)"
image="/assets/img/large-playback.jpg"
align="right"
backgroundcolor=site.data.colors.box
imagewidth="40%"
%}

{% include fullsizebox.html 
title="Manage"
description="Opencast Manage provides a dashboard for administrators to configure the system, make bulk edits to content and metadata, track the status and performance of content and configure distribution of video content.

- Metadata entry and editing for related recordings
- Distribution to supported channels (i.e. iTunes, YouTube, RSS, Opencast Playback)
- Manual media upload (e.g. user-generated or production video)
- Bulk editing; media trimming and recording search/filtering
- Monitoring dashboard; status, performance statistics and technical details"
image="/assets/img/large-manage.jpg"
align="left"
imagewidth="40%"
%}

---

# Getting Started with Opencast

Here are some frequently asked questions regarding Opencast. This will help you determine if it’s the right solution for your organization.

{% include simplebox.html backgroundcolor=site.data.colors.box 
content="## How much does it cost?

Opencast is a free, open source software. There is no direct cost associated with downloading and deploying the software. As an open source software, there is free support from the community on the Opencast mailing lists and the Opencast IRC channel. If you require enterprise-level support, there are commercial vendors that provide that service. Keep in mind, for production use you will need several servers and staff to maintain your system." %}

{% include simplebox.html backgroundcolor=site.data.colors.box 
content="## How long does it take to setup an Opencast system?

Setting up a basic Opencast server can be done in a few hours. But Opencast is typically a building block within a larger video capture ecosystem and it is highly customizable. Generally it’s best to plan for a 1-3 month deployment depending on the complexity of your project. For Universities, there is often a small pilot rolled-out and tested before a campus-wide solution is developed."%}


{% include simplebox.html backgroundcolor=site.data.colors.box 
content="## How well will it integrate with what we already have?

Opencast was developed as an open source solution so that it could work well in any environment. The Opencast Marketplace is full of technology providers with active integrations, but the open API lets you develop any integration that’s needed. Opencast adheres to; iCalendar, RSS, ATOM, OAI-PMH, MPEG-7, Dublin Core, LTI, REST standards." %}

{% include simplebox.html backgroundcolor=site.data.colors.box 
content="## How does Opencast compare to proprietary solutions?

The feedback from the community is primarily around the flexibility and scalability of the Opencast platform. It has all the common features built-in with the ability to add any features you require without the development cycles of proprietary solution providers." %}

{% include simplebox.html backgroundcolor=site.data.colors.box 
content="## How well will it integrate with what we already have?

Opencast was developed as an open source solution so that it could work well in any environment. The Opencast Marketplace is full of technology providers with active integrations, but the open API lets you develop any integration that’s needed. Opencast adheres to; iCalendar, RSS, ATOM, OAI-PMH, MPEG-7, Dublin Core, LTI, REST standards." %}

{% include simplebox.html backgroundcolor=site.data.colors.box 
content="## Will students and professors like it?

Educators love Opencast because once it’s set up, they don’t have to worry about much. Lectures are automatically queued to record, so there is little day-to-day management. Students benefit from the easy access to videos on CMS, iTunes, YouTube or RSS subscriptions. Advanced search features also help end-users find the content they are looking for quickly and easily." %}

{% include simplebox.html backgroundcolor=site.data.colors.box 
content="## Why is open source the best option?

Open source is a great way to highlight your organization’s drive for innovation by contributing back to the community. Because Opencast is a community-based solution, you have the benefit of learning directly from and collaborating with like-minded organizations. Open source solutions also have a longer ‘shelf-life’ because the active community is continuing to develop and you don’t have to worry about a software provider discontinuing elements of their software or hardware – which can become extremely costly to replace. You can also continue to change and develop software to address your needs, so it allows for much more flexibility, and more seamless integration with your other IT-systems." %}

{% include simplebox.html backgroundcolor=site.data.colors.box 
content="## How often are new features rolled out by the community?

Every year there are two major releases to Opencast. Throughout the year, maintenance releases, bug fixes and new features are deployed on an on-going basis." %}
