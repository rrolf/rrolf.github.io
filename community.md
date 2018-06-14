---
title: Opencast Community
description: "The Opencast Project thrives off of community engagement, sharing and contributions. It’s a community of institutions, individuals, and corporate organizations interested in open media for learning. Opencast was created to solve the need identified with academic institutions to run an affordable, flexible and enterprise-ready video management systems, and has grown into a robust community of innovators worldwide."
---
{% include community-menu.html %}

# Institutions that use Opencast
As an open-source project, it is hard to tell how many institutions are using Opencast. The software does not have to be licensed and the users do not need to register.But from registrations to the repositories we can say that at over 300 different institutions worldwide have downloaded Opencast. In this area we want to highlight some of the institutions that use Opencast in production.
Some adopters of Opencast were able to provide some feedback on how they use Opencast and what they have contributed back to the project.

{% include box-start.html backgroundcolor="#dfe6ed" %}

{% for post in site.posts %}
{% if post.categories contains "user" %}
{% include imagebox.html 
title=post.title
description=post.description
image=post.logo
linkurl=post.url
linktext="Learn More"
%}
{% endif %}
{% endfor %}

{% include box-end.html %}

> Opencast was the only solution that was fully automated and flexible enough to work with our existing audiovisual technology.

Stuart Phillipson, University of Manchester

> Opencast drastically reduces the time it takes to get educational resources online so end users can interact with content in real-time.

Rüdiger Rolf, University of Osnabrück

## Get Started Now

# Communication

## Communication details/ impress
Olaf Schulte

## Communications

# Upcoming Events
Here are the conferences and workshops organized by the Opencast community and/or with participation by / relevance for the Opencast community.

{% include simplebox.html backgroundcolor=site.data.colors.box 
content="## Opencast D/A/CH Meeting 2018

*The Friedrich-Alexander-Universität Erlangen-Nürnberg ist hosting this years german-speaking conference in Erlangen.*

**September 27.-28., 2018**

The [website](https://www.opencast.fau.de/) has all the information for planning your itinerary, with registration.

As usually the event has more an un-conference style and the participants can contribute to the agenda in the [Opencast Wiki](https://opencast.jira.com/wiki/spaces/MHDE/pages/368607233/Themen+f+r+das+Treffen+der+DACH+Community+2018).
[Contact us](http://www.opencast.org/events) for more information or questions." %}

{% include fullsizebox.html 
title="2018 Opencast summit"
description="The website has recording of most of the sessions of this years conference.
*Thanks to Austria’s Academic Moodle Cooperation for hosting the 2018 Opencast Summit at the University of Vienna.*"
image="/assets/img/opencast2018wien.jpg"
align="left"
backgroundcolor=site.data.colors.box
imagewidth="40%"
%}

{% include fullsizebox.html 
title="Conferences and Workshops"
description="There is one major annual meeting, the Opencast Summit. While this used to be an unconference with an open agenda, we are trying to mix planned sessions with open slots these days, based on feedback we got from the community. Usually, there will be a call for participation to the community with a selection of presentations submitted (if necessary) so that a programme is set a couple of weeks before the event. To maintain the \"unconference style\" there will be empty slots for ad hoc sessions or open discussions. Besides the presentation slot(s) we usually organize a vendor showcase for the latest capture agent technology and service provider offerings.

Plus, there are regional Opencast meetings. The German-speaking community for example meets once or twice a year for a workshop.

Last but not least, there is the annual Open Apereo Conference, with members of the Opencast Community joining and – ideally – presenting or organizing seminars and workshops to inform the larger Apereo community about Opencast."
image="http://www.opencast.org/wp-content/uploads/2017/03/opencast-summit-2017.jpg"
align="left"
imagewidth="40%"
%}

{% include fullsizebox.html 
title="Frequent Webmeetings"
description="Best entry point to the community probably is our **Adopters’ meeting** on the last Wednesday of each month. The meeting is at 3pm UTC at [http://opencast.blindsidenetworks.net](http://opencast2018.univie.ac.at/programme-and-recordings)(password: welcome). An agenda for this meeting is usually announced a few days before the meeting on the mailing-lists.

There is also a german-speaking **Adopters’ meeting** on the last Wednesday of every even month (February, April, June, August, October). The meeting is at 15:00 CEST at [http://opencast.blindsidenetworks.net](http://opencast2018.univie.ac.at/programme-and-recordings)(password: welcome). An agenda for this meeting is usually announced a few days before the meeting on the german-speaking mailing-lists.

There is also a weekly **technical meeting** for developers and sysops on Tuesdays at 3pm UTC on [http://opencast.blindsidenetworks.net](http://opencast2018.univie.ac.at/programme-and-recordings)(password: welcome). An agenda is also announced before the meeting on the developers’ mailing-lists.

The Sakai Teaching and Learning group has opened up for other Apereo projects as an open forum. They meet [http://opencast.blindsidenetworks.net](https://confluence.sakaiproject.org/display/PED/Sakai+Teaching+and+Learning+Conference+Calls)(password: welcome)."
image="http://www.opencast.org/wp-content/uploads/2015/02/bbb-conf.png"
align="left"
backgroundcolor=site.data.colors.box
imagewidth="40%"
%}
# Stay Informed
These are the official mailing lists of the Opencast Community. If you are seeking support for running Opencast, we would recommend to subscribe to the Opencast users list. If you are interested in general announcements, the community list is probably the list that you would like to join.

{% include simplebox.html backgroundcolor=site.data.colors.box 
content="## Opencast Announcements

[announcements@opencast.org](announcements@opencast.org)
- For all matters related to academic video (technical, didactical) in general and Opencast in particular; announcements
- More a newsletter, as users cannot post to this list
- Highly recommended for everybody interested in the Opencast software and community
- Archieve" %}
 
{% include simplebox.html backgroundcolor=site.data.colors.box 
content="## Opencast Users

[users@opencast.org](users@opencast.org)
- For anyone who is testing or using Opencast and need support around installation, configuration and implementation

- For anyone who wants to support others who are using Opencast
- Before posting, cf. archive

**NOTE: As a community support group, all subscribers are encouraged to help out with any support needs that come across the list.**" %}


{% include simplebox.html backgroundcolor=site.data.colors.box 
content="## Opencast Development List

[dev@opencast.org](dev@opencast.org)
- For anyone interested in detailed day-to-day progress of Opencast
- For anyone interested in contributing to the Opencast development effort
- For all Opencast Development Team members
- Before posting, cf. [https://groups.google.com/a/opencast.org/forum/#!forum/dev](https://groups.google.com/a/opencast.org/forum/#!forum/dev)

**NOTE: You should also be subscribed to the Community list, as some important announcements about Opencast will only be sent to the Community list. We assume everyone on the dev@ list is also on the announcements@ list**"
 %}


{% include simplebox.html backgroundcolor=site.data.colors.box 
content="## Opencast Security Notices

[security-notices@opencast.org](security-notices@opencast.org)
- For notices relating to security issues in Opencast
- Recommended for all Opencast development team members, anyone running a Opencast instance" %}

{% include simplebox.html backgroundcolor=site.data.colors.box 
content="## Opencast Security

[security@opencast.org](security@opencast.org)
- A security reporting list, allows anonymous posting but is not publicly visible
- Use this list to report security issues to the team" %}

{% include simplebox.html backgroundcolor=site.data.colors.box 
content="## Spanish-speaking community

[opencast-es@opencastproject.es](opencast-es@opencastproject.es)
- For issues unique to Spanish-speaking adopters (cooperation, meetings etc.)
- For anyone feeling more comfortable discussing Opencast-related issues in Spanish

**NOTE: You should also be subscribed to the Community list, as some important announcements about Opencast will only be sent to the Community list. We assume everyone on this list is also on the announcements@ list**"%}

{% include simplebox.html backgroundcolor=site.data.colors.box 
content="## German-speaking community

[anwender@opencast.org](anwender@opencast.orgs)
- For issues unique to German, Austrian, and Swiss institutions (cooperation, meetings etc.)
- For anyone feeling more comfortable discussing Opencast-related issues in German

**NOTE: You should also be subscribed to the Community list, as some important announcements about Opencast will only be sent to the Community list. We assume everyone on the anwender@ list is also on the announcements@ list**"%}

{% include simplebox.html backgroundcolor=site.data.colors.box 
content="## IRC Channel #opencast

-On irc.freenode.net, the chat group #opencast is used around the clock for real-time assistance by both users and develoeprs.
Feel free to use the [webchat webinterface](http://webchat.freenode.net/?channels=opencast) to access this chat directly or [find a client](https://en.wikipedia.org/wiki/Comparison_of_Internet_Relay_Chat_clientst); in addition, this [IRC primer](http://www.irchelp.org/irchelp/ircprimer.html) should help get you started.
"%}

# People and Institutions
## Opencast Committers

<img  src="https://opencast.jira.com/wiki/images/icons/user_bw_16.gif">
[Christian Greweling](https://opencast.jira.com/wiki/display/~cgreweling)

<img src="https://opencast.jira.com/wiki/images/icons/user_bw_16.gif">
[Greg Logan](https://opencast.jira.com/wiki/display/~greg_logan)

<img src="https://opencast.jira.com/wiki/images/icons/user_bw_16.gif">
[James Perrin](https://opencast.jira.com/wiki/display/~james.perrin)

<img src="https://opencast.jira.com/wiki/images/icons/user_bw_16.gif">
[Karen Dolan](https://opencast.jira.com/wiki/display/~karen)

<img src="https://opencast.jira.com/wiki/images/icons/user_bw_16.gif">
[Lars Kiesow](https://opencast.jira.com/wiki/display/~lkiesow)

<img src="https://opencast.jira.com/wiki/images/icons/user_bw_16.gif">
[Matjaz Rihtar](https://opencast.jira.com/wiki/display/~matjaz)

<img src="https://opencast.jira.com/wiki/images/icons/user_bw_16.gif">
[Michael Stypa](https://opencast.jira.com/wiki/display/~mstypa)

<img src="https://opencast.jira.com/wiki/images/icons/user_bw_16.gif">
[Rubén Pérez](https://opencast.jira.com/wiki/display/~ruben.perez)

<img src="https://opencast.jira.com/wiki/images/icons/user_bw_16.gif">
[Rute Santos](https://opencast.jira.com/wiki/display/~rsantos)

<img src="https://opencast.jira.com/wiki/images/icons/user_bw_16.gif">
[Rüdiger Rolf](https://opencast.jira.com/wiki/display/~rrolf)

<img src="https://opencast.jira.com/wiki/images/icons/user_bw_16.gif">
[Stephen Marquard](https://opencast.jira.com/wiki/display/~smarquard)

<img src="https://opencast.jira.com/wiki/images/icons/user_bw_16.gif">
[Sven Stauber](https://opencast.jira.com/wiki/display/~staubesv)

<img src="https://opencast.jira.com/wiki/images/icons/user_bw_16.gif">
[Tobias Schiebeck](https://opencast.jira.com/wiki/display/~ts23)

<img src="https://opencast.jira.com/wiki/images/icons/user_bw_16.gif">
[Waldmar Smirnow](https://opencast.jira.com/wiki/display/~waldemarsmirnow)

## Committers Emeritus
The following people were committers at one time and have contributed to the project, but are no longer active committers.

- Chris Brooks, University of Saskatchewan
- David Horwitz, University of Cape Town
- Edmore Moyo, University of Cape Town
- Eduardo Alonso, University of Vigo
- Jaime Gago, Entwine
- Markus Ketterl, University of Osnabrueck
- Markus Moorman, University of Osnabrueck
- Michelle Ziegmann, University of California Berkeley
- Stefan Altevogt, University of Osnabrueck
- Kristofor Amundson, University of Saskatchewan
- Johannes Emden, University of Osnabrueck
- Adam Hochman, University of California Berkeley
- Jamie Hodge, University of Copenhagen
- Josh Holtzman, University of California Berkeley
- Andre Klassen, University of Osnabrueck
- Kenneth Lui
- Susana Ozores, University of Vigo
- Bostjan Pajntar, Jozef Stefan Institute
- Nejc Škofič, Jozef Stefan Institute
- Micah Sutton, University of Nebraska-Lincoln
- Aaron Zeckoski, Cambridge University
- Benjamin Wulff, University of Osnabrück
- Adam McKenzie, Entwine/Extron
- Tobias Wunden, Entwine/Extron
- Xavier Butty, Entwine/Extron
- Lukas Rohner, Entwine/Extron
- Christoph Driessen, Entwine/Extron
- Basil Brunner, Entwine/Extron

## Opencast Sponsors
Thank you to the following sponsor(s) for their support to advance the Opencast project. More details can be found [here](http://www.opencast.org/sponsors).

## Our Supporters
These institutions have provided financial, technical, or personnel suppport to advance the Opencast project. Thank you!

{% include fullsizebox.html 
image="/assets/img/eth-logo1.png"
align="left"
imagewidth="40%"
%}

{% include fullsizebox.html 
image="http://www.opencast.org/wp-content/uploads/2015/03/osnabruk.png"
align="left"
imagewidth="40%"
%}

{% include fullsizebox.html 
image="/assets/img/Switch600x400.jpg"
align="left"
imagewidth="40%"
%}

{% include fullsizebox.html 
image="/assets/img/logo-university-of-manchester.png"
align="left"
imagewidth="40%"
%}

{% include fullsizebox.html 
image="http://www.opencast.org/wp-content/uploads/2015/03/blindside.png"
align="left"
imagewidth="40%"
%}

{% include fullsizebox.html 
image="/assets/img/Valencia600x400.jpg"
align="left"
imagewidth="40%"
%}

{% include fullsizebox.html 
image="/assets/img/UCT-round-logo.png"
align="left"
imagewidth="40%"
%}

{% include fullsizebox.html 
image="http://www.opencast.org/wp-content/uploads/2015/03/jira.png"
align="left"
imagewidth="40%"
%}


{% include fullsizebox.html 
image="http://www.opencast.org/wp-content/uploads/2018/01/Harvard600x400.jpg"
align="left"
imagewidth="40%"
%}

# Governance

Opencast as a community and the related software development project have their rules and regulations.
The community elects a board that should care about the health and status of the project and the community. The board organizes events like the Opencast conference or cares for the marketing. It also manages to funds of the projects.
[More information on the current board can be found here.](http://www.opencast.org/community/opencast-board)
The software development project is lead by a groups of committers. Committers can decide on which new features will be merged into an upcoming version or decide on proposals regarding the future development of software. They also have obligations. Developers for example have to review patches for the software.
A contributor to Opencast (that may be an developer, but other contributions like testing and improving documentation or processes can also qualify) can be proposed as a new committer to the project by an existing committer. After this proposal the other committers can vote for the applicant.
[More information on the current board can be found here.](http://www.opencast.org/community/governance)
