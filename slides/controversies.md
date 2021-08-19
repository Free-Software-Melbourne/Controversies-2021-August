<style>
    .reveal section .small li {
    font-size: 0.7em;
    line-height: 1.3em;
    vertical-align: top;
  }
</style>

<br>

## Elastic Search - History
<hr><br>

* Elasticsearch started in 2010 and was Apache 2.0 licensed
* Based on the Lucene library
* Distributed, scalable and used a common interface
* Elastic NV was founded in 2012
* Litigations with AWS that started in 2015

<br><img src=slides/img/elastic-logo.png height="120px">

Note:
* started in 2010
* it is based on the Lucene search library
* formerly Free and Open Source (Apache 2.0)
* built from the ground up to be distributed, scalable and used a common interface, JSON over HTTP
* Elastic NV was founded in 2012
* issues and litigations with AWS that started in 2015 when the cloud provider introduced a managed version and deepened in 2019 when AWS launched the Open Distro
* currently dual-licensed under the source-available Server Side Public License and the Elastic license
* Elastic license
  *  Provide the products to others as a managed service
  *  Circumvent the license key functionality
  *  Remove or obscure any licensing, copyright, or other notices
* Elastic’s prevalence has led to what could be seen as an over-reliance on their software
* ES: "years of what we believe to be Amazon/AWS misleading and confusing the community"
* ES: "many large businesses don't have contracts with Elastic. Instead, these companies use Amazon Elasticsearch Service"
* ES: "We've tried every avenue available including going through the courts, but with AWS's ongoing behavior, we have decided to change our license"


---

<br>

## Elastic Search - New Licencing Model
<hr><br>

* Elastic Search (and Kibana)
* Adopted the SSPL
* Motivation: AWS
* January 2021 starting with version 7.11
* Legally within their rights

Note:
* Elastic Search (and Kibana)... everything is (& Kibana)
* Recently relicensed to Server Side Public License and the Elastic license
* Motivation: AWS
* SSPL (created by mongodb)
  * any "service" that incorporates it must release the entirety of the code
* MongoDB came up with the SSPL. Its intention was the same as Elastic, it wanted a share of the vast profits that AWS makes selling Mongo/Elastic
* January 2021, Elastic announced that starting with version 7.11 they will be using SSPL
* Elastic is legally within their rights to make the change - "unilateral changes to licenses intended to solve one perceived problem are likely to in turn create unanticipated other problems"

---

<br>

## Elastic Search - SSPL and FLOSS
<hr><br>

* Based on the GPLv3
* Not approved by the OSI
* Not even acknowledged by the FSF

Note:
* based on the GPLv3
* SSPL: If you make the functionality of the Program or a modified version available to third parties as a service, you must make the Service Source Code available via network download to everyone at no charge, under the terms of this License.”
*
* not recognised by the OSI or the FSF
* OSI reached their decision and published the results precisely to make consumers and users aware
* 'restrict cloud service providers from offering our software as a service' in violation of OSD6
* FSF have not listed the SSPL
* components of Elasticsearch or Kibana in subsequent versions (7.11 and onwards) are no longer under an OSI-approved open source license


---

<br>

## Elastic Search - Impact
<hr><br>

* "No impact on the overwhelming majority of our user community"
* A cloud provider would need to agree to open-source your hosting infrastructure

Note:
* "no impact on the overwhelming majority of our user community who use our default distribution for free"
* For AWS or any other cloud provider to offer Elasticsearch services under the SSPL, they'd need to agree to open-source your hosting cloud's infrastructure
* Plenty of FLOSS FUD mixed in
* Almost makes me thing SSPL should be FSF approved


---

<br>

## Elastic Search - Alternatives
<hr><br>

* Amazon previously announced their plan to fork Elasticsearch and feed this into OpenDistro
* Amazon reacted with a plan to fork Elasticsearch and Kibana
* Amazon Rebranded OpenSearch
* Use Lucene library directly
* Would AGPL have been a viable alternative for Amazon

Note:
* just as with MongoDB, AWS launched DocumentDB
* January 21: AWS has just announced their plan to fork Elasticsearch and feed this into OpenDistro
* Open Distro is primarily a distribution with the Apache 2.0-licensed source code, rather than an explicit fork
*
* Amazon reacted with a plan to fork Elasticsearch and Kibana (an Apache v2-licensed fork)
* April 2021: AWS rebranded their fork as "OpenSearch"
*
* Use Lucene library directly
* Would the AGPL have been a better solution
* indicator of SSPLs success... even bigger threat, proven in court


---

<br>

## Elastic Search - References
<hr><br>

<div class=small>

  * FAQ: https://www.elastic.co/pricing/faq/licensing
  * Video: https://archive.org/details/copyleftconf2020-allison
  * Blog: https://www.elastic.co/blog/elastic-license-v2
  * Article: https://www.infoq.com/news/2021/01/elastic-aws-open-source/
  * Article: https://www.leanix.net/en/blog/changes-to-elasticsearch-and-kibana-licenses-what-engineering-managers-need-to-know
  * Article: https://www.instaclustr.com/changes-to-elasticsearch-licensing/#
  * Article: https://www.zdnet.com/article/elastic-changes-open-source-license-to-monetize-cloud-service-use/
  * Article: https://coralogix.com/blog/elasticsearch-sspl-license-threat-to-business/
  * Article: https://www.protocol.com/enterprise/about/aws-targeted-by-elastic

</div>

===

<br>

## Audacity - History
<hr><br>

* Digital audio editor and recording application software
* GPL Version 2 & CC BY 3.0
* In excess of 200 million downloads
* The Muse Group would be acquiring Audacity

<br><img src=slides/img/Audacity-logo.png height="120px">

Note:
* What is it? digital audio editor and recording application software
* started in 2000 with 0.8
* GNU GPL Version 2 (CC BY 3.0 for docs)
* most popular download from FossHub
* in excess of 200 million downloads
* April 2021, it was announced that Muse Group would be acquiring the Audacity trademark


---

<br>

## Audacity - Who are The Muse Group?
<hr><br>

The Muse Group
* Ultimate Guitar community and guitar tab catalog
* music notation software and online catalog MuseScore (2017)
* assignment management platform MuseClass (2020/1)
* song learning and effects app Tonebridge

Note:
* "provides digital tools, resources, and content to musicians at each stage in their personal development"
* Started with "Ultimate Guitar" community and guitar tab catalog
* 2017: "MuseScore" music notation software and online catalog
* ~2020: assignment management platform MuseClass
* 2021?: song learning and effects app Tonebridge
* Interview on podcast, they seem really dedicated and connected to the craft, but new to FLOSS (although not new to digital and alternative money streams)


---

<br>

## Audacity - Contributor License Agreement
<hr><br>

* Introduced a new CLA after acquiring Audacity
* Not well received
* In line with similar CLAs
* Still in place


Note:
* after acquiring Audacity, introduced a CLA
* requires anyone wishing to send a pull request to the original source code to agree on giving them unlimited and unrestricted rights to own the modified lines of code
*
* In line with other projects, but not a great first impression
* e.g. Apache, Django, OpenJS and QT all have CLAs
* Better explained but not reversed


---

<br>

## Audacity - Telemetry, Analytics and Update Checks
<hr><br>

* Early GitHub Pull Request to enable analytics and error reporting
* PR was released before a planned announcement
* Dropped telemetry ideas
* In house analytics and update checking
* GDPR + Analytics + Poor Communications = ...


Note:
* May 4, a GitHub update revealed the app was supposed to include opt-in anonymous analytics data collection... using Google hosted analytics
* May 13 dropping the proposed telemetry features & error reporting and checks for updates would be self-hosted
* update checking (which sends your IP address to them at every usage)
* In conjunction with the GDPR your IP address is personal information
* GDPR + Analytics + Poor Communications = ...


---


<br>

## Audacity - Privacy Policy Updates
<hr><br>

* Audacity updates the privacy policy
* Sharing personal data with 3rd parties
* Sharing data for legal enforcement
* Suggests that people under 13 should not use Audacity
* Reworded privacy policy to remove restrictions and most of the data collection

Note:
* June 2: updated privacy policy
* Data collected: operating system and version, the user's country based on their IP address, non-fatal error codes and messages, crash reports, and the processor in use
*
* occasionally required to share your personal data with our main office in Russia and our external counsel in the USA... and other third parties
* (and "for legal enforcement")
*
* people under 13 years old to "please do not use the app."
* "the processing of the personal data of a child shall be lawful where the child is at least 16 years old"
* a minor using Audacity with default settings is a potential legal nightmare


---


<br>

## Audacity - Reactions
<hr><br>

* Self hosting analytics & anonymized data
* No telemetry
* Revised privacy policy
* Intending to use the CLAs for good

Note:
* "Taking Google and Yandex out of the equation was an easy decision"
* the data are anonymized
* the company deciding to use error/crash reporting and optional update checking instead
*
* published a revised privacy policy on July 22 for the latest version of Audacity 3.0.3
* No sharing with any random 3rd parties
* Muse Group also removed the draft provision that discouraged children under 13 years old from using Audacity
*
* The CLA stays
* We intend to update the license to GPLv3 to enable support for new technologies
* uplicensing, dual licensing (Apple's App Store)

---


<br>

## Audacity - Alternatives and Forks
<hr><br>

* Honorary mention: "Aefkaa"
* Audacium - https://github.com/SartoxOnlyGNU/audacium
* DarkAudacity - https://github.com/JamesCrook/audacity/tree/darkaudacity
* Sneedacity - https://github.com/Sneeds-Feed-and-Seed/sneedacity
* Tenacity - https://github.com/tenacityteam/tenacity

Note:
* "Aefkaa" (Audio editor formally known as Audacity)
* audacium - On Hold (3 contribs)
* darkaudacity (previous contributor - 5 contribs - no commit for a month)
* sneedacity (updated this week - 9+ contribs)
* tenacity (updated this week - 9+ contribs)

---


<br>

## Audacity - References
<hr><br>
<div class=small>

  * Article: https://www.musictech.net/news/industry/audacity-acquired-muse-group-ultimate-guitar-musescore/
  * Article: https://appleinsider.com/articles/21/07/04/open-source-audacity-deemed-spyware-over-data-collection-changes
  * Article: https://librearts.org/2021/07/audacity-privacy/
  * Article: https://fosspost.org/audacity-is-now-a-spyware/
  * Article: https://www.theregister.com/2021/05/27/audacity_cla/
  * Article: https://www.theregister.com/2021/07/05/audacity/
  * Podcast: https://www.scoringnotes.com/news/muse-group-formed-to-support-musescore-ultimate-guitar-acquires-audacity/
  * Video: https://www.youtube.com/watch?v=RMWNvwLiXIQ
  * CLA: https://github.com/audacity/audacity/discussions/932
  * PP: https://github.com/audacity/audacity/discussions/1225
  * PP: https://github.com/audacity/audacity/issues/1213
  * PP retraction: https://github.com/audacity/audacity/discussions/1353
  * New PP: https://www.audacityteam.org/about/desktop-privacy-notice/
  * Telemitry: https://github.com/audacity/audacity/pull/835
  * Telemetry backdown: https://www.theregister.com/2021/05/14/audacity_telemetry/
  * Telemetry retraction: https://github.com/audacity/audacity/discussions/889
  * Audacity mark: https://assignments.uspto.gov/assignments/q?db=tm&sno=78352743
  * 4Chan: https://www.theregister.com/2021/07/07/tenacity_maintainer_quits_4chan_harassment/

</div>