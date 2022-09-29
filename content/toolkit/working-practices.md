---
title: "Working Practices"
date: 2022-09-29
draft: false
weight: 8
slug: working-practices
---


# Working Practices

... this is the Decision trees content - please edit ...

While data management plans focus strongly on the data produced or reused by research projects, the whole research process itself represents a long path of decision-making that involves the assessment of the project’s environmental footprint. This chapter is work-in-progress toward a set of decision trees, to help you make informed decisions in the research process.

{{<hint info>}}
**Read:** Bibliography and raw ideas can be found in the [Frameapad here](https://semestriel.framapad.org/p/toolkit_decisiontree-9tho?lang=en).
{{</hint>}}


## Using digital devices in general

It is best to use **devices** as long as possible e.g., to repair them when possible. If you purchase a device through your institution, it is advisable to require the longest possible warranty for all newly purchased devices (this is of course also true if you purchase the device for individual use). There has been a growing awareness of the importance of repairability, which is now used as a selling point by companies. Sometimes it is more a greenwashing argument than an actual indicator of repairability (see as an example [this Greenpeace assessment of the repairability of some smartphones, laptops and tablets](https://www.greenpeace.org/static/planet4-eastasia-stateless/2019/11/47a8cd27-47a8cd27-howrepairableisyourmobiledevice.pdf)). Some companies rely on repairability of device components like [Fairphone](https://www.fairphone.com/en/) and [Framework](https://frame.work/gb/en) but there are still few of them. Therefore, think about buying a second-hand-device. Often they are sold updated with partly new hardware. 

For your old devices that are broken beyond repair, you can inquire into the forms of recycling that are possible. Check online for WEEE (Waste Electrical and Electronic Equipment, [DEEE](https://ecoinfo.cnrs.fr/thematiques/ressources-et-e-dechets/deee-ou-e-dechets/) in French, application in Germany and Europe explained in German [here](https://deutsche-recycling.de/weee-eu-richtlinie/#)). 

In order to have a precise idea of the environmental footprint of a device, you can consult the corresponding Life-Cycle Assessment ([LCA](https://en.wikipedia.org/wiki/Life-cycle_assessment), [here](https://ecoinfo.cnrs.fr/thematiques/analyse-de-cycle-de-vie/) for an explanation in French) that hardware companies usually provide. LCAs are never fully accurate - some of the information they contain are rough estimates, and the criteria that are communicated are only a handful from a long list. But they remain the best way of assessing the digital footprint of a device or hardware.

All in all, the less devices you purchase and use, the better. You should consider this for instance when you want to plug an additional monitor to your laptop: the monitor itself not only has a considerable carbon weight but it also requires much more energy than your laptop (further information see below).

More generally, the choice of the device you want to use plays an important role when it comes to the amount of electricity that is used. For example, by streaming 1 hour via good wifi in HD quality, a laptop needs 9g CO2, a tablet 1.2 g and a smartphone 0.5g (and a television 48g). Source: https://www.iea.org/commentaries/the-carbon-footprint-of-streaming-video-fact-checking-the-headlines 

You might think that you can sometimes work faster with a laptop than with a smartphone or faster with two monitors than with one. But, on the other hand, sometimes, the screen size does not influence what you do or how much time you need to do it. Therefore, you don’t have to switch devices or the amount of monitors in general, but before starting a new task, you could step back and reflect on the kind of device you really need. For example: Maybe you can unplug your second monitor and only plug it in when it helps you work more efficiently. 

Concerning peripheral hardware like mouses and keyboards, their energy supply can also make a difference. While the type of connection (cable vs. bluetooth) is marginal (see this [thread on Stackoverflow](https://hardwarerecs.stackexchange.com/questions/14045/usb-mouse-vs-bluetooth-mouse-less-battery-drain)), devices also require batteries that need to be replaced or recharged regularly.

Note that every digital device uses electricity. The amount of CO2 that is used by producing the electricity depends on the way of production. Every country uses different ways to produce electricity (f.e. Fossil fuels [bad for the climate], nuclear power [bad for the environment, bad for climate and dangerous], renewables [best to stop climate crisis], Therefore, the amount of CO2 used depends on the country you live in. If you would like to think about moving into another country, you can find information about the ways of electricity-production per country here: https://ourworldindata.org/electricity-mix . 



## Using an operating system

You cannot say that one operating system (like Windows, Linux, MacOS) is better from a carbon footprint point of view than another. There are too many different versions of the systems to compare them in general. But you can check if there are a lot of elements running in the back end of your operating system, and if there are a lot of programs that run automatically by starting the system even if you don’t need them at that moment. 

### Towards minimal operating systems {#mini-kernels}

Unikernels provide a light-weight alternative to traditional VMs or containers. Technologies such as [MirageOS](https://mirage.io/) offer a declarative way to build statically compiled binaries that can run directly over a hypervisor or even over bare metal. This approach allows minimal systems to be built which contain the exact functionality required for the task, even down to being able to specify what parts of a network stack are required. This not only provides opportunity for improving the security of the running system but also can result in energy savings compared to traditional operating systems such as Linux.

{{< hint info >}}
**Watch:** [Leaving legacy behind. Reducing carbon footprint of network services with MirageOS unikernels](https://media.ccc.de/v/36c3-11172-leaving_legacy_behind), Hannes Mehnert.
{{< /hint >}}
{{< video "https://media.ccc.de/v/36c3-11172-leaving_legacy_behind/oembed" >}}



## Data traffic

**Data traffic** on the internet is all the more problematic as the tendency to facilitate data traffic with new technologies like 5G comes with a massive growth of data consumption. In terms of impact, the rule of thumb would be: Wired connection>Wifi>3G>4G>5G. A poor internet connection has a better carbon footprint than a strong one. 

For example, let’s imagine you use a smartphone for one hour and you stream something in HD quality. With a “low” Wifi connection you might need 4g CO2 in total, with a “high” Wifi connection you might need 10g CO2 in total. Source: https://www.iea.org/commentaries/the-carbon-footprint-of-streaming-video-fact-checking-the-headlines 











*[start of zoom measurement/estimate info - need more samples and how to factor in multiple participants]*



**Day-to-day working**



**E-mailing** is resource-intensive, but you can minimise the impact by following a few simple rules. First, avoid integrating an image footer as a signature in your emails. (Consider communicating to your teammates the environmental cost of including images, such an institutional logo, in email signatures). Second, avoid emailing large groups of people unless it is definitely necessary.

Emails are stored as long as they are in your inbox or in subfolders of your inbox, it matters that you clean your inbox by deleting emails regularly (see mini case study: “Email Storage”). This is particularly important for emails with attached files (a regular email weighs 4g CO2, and an email with a photo 50g CO2). 

**Sharing files**. You might think about using a download link (e.g. provided by a cloud storage) to share documents instead of sending them via e-mail. It is advisable to use online documents especially when: 1) the shared document has a large file size, 2) you have a high number of recipients. 

**Documents stored in cloud or network drives** require traffic for saving files and synchronisation. Network drives usually synchronise »file by file«, that means each change will result in uploading the document completely again. Especially in case you edit large files, you might consider copying them once to your local drive, edit them there and copy the edited version back when you are finished. Instead, most cloud solutions only require traffic for the modified parts of a file. On the backend, cloud storages usually synchronise automatically on every modification. You can disable the client temporarily or turn on cloud synchronisation only when you need it in order to save energy from additional, superfluous traffic. Generally, saving the document less often will reduce energy consumption if you edit remotely stored documents.

**Editing documents online together** is a good solution to avoid frequent email traffic, besides the advantage of synchronous editing or synchronisation. However, each time you open an online document, the application needs to be loaded into your browser memory, which creates a lot of traffic. Additionally, it creates traffic by permanently synchronising your edits, which you cannot turn off in an online environment (consider also traffic by tracking, see above: Browsing). It also relies on a permanent internet connection (see above: Data Traffic). Depending on the type of information you need to communicate, it is advisable to opt for a light-weight tool (e.g. EtherPad) for taking collaborative notes.

**Browsing** on the Internet causes data traffic. As a general rule, more data privacy also means less data traffic. You can track your browsing footprint with the »[Carbonalyser](https://theshiftproject.org/en/carbonalyser-browser-extension/)« tool developed by the Shift Project to identify traffic-intense websites. A lot of traffic remains invisible to the user: ads, tracking and social media functions (cf. https://whotracks.me/) are being processed in the background. It is possible to avoid some of this invisible traffic with browser extensions (AdBlockPlus, Ghostery, uBlockOrigin; for general advice see [WikiHow](https://www.wikihow.com/Prevent-People-from-Tracking-You-on-the-Internet)). 

**Editing documents locally** on your machine sometimes consumes unnecessary energy when additional features are running in the background of your program. For example, you can save energy by turning off automatic grammar/spell check (and activate it e.g. only for finalising a document). If your document is very large and you use cloud storage or a network drive, consider turning off the autosave function, or adjust it to a larger interval in order to reduce synchronisation traffic. Also check for further features in your text editor that may not be required to run all the time – essentially everything that checks the text permanently in the background and needs to go through large vocabularies.





## How to communicate within your team

Communicating within your project team might include sending messages, sharing documents, or videoconferences. While the carbon footprint of the applications and software you will choose is a key element in making this decision, we have included a few additional criteria to help you balance pros and cons of the most frequently used software.



**Choosing a videoconference system**

| Software | Carbon footprint | Accessibility | GDPR compliance |
| --- | --- | --- | --- |
| Google Meet |     | Proprietary | Very nontransparent |
| Zoom |    | Proprietary | Very nontransparent |
| BBB |    | General Public Licence; needs to be installed and maintained on an institutional server | Transparent |
| Jitsi |    | Apache Licence | Mostly transparent     |
| Webex |    | Proprietary | Relatively transparent |
| MS Teams |    | Proprietary | Very nontransparent    |


**Choosing a Team-Chat Program**

| Software | Carbon footprint | Accessibility | Functions | Data privacy | Costs |
| --- | --- | --- | --- | --- | --- |
| Discord  |   | Runs on all major systems | Messaging, Audio and Video | Bad (Data is transmitted unencrypted and the company is allowed to read and resell the data. Data can be transmitted to US-Server) | No fees |
| Element  |   | Runs on all major systems; open-source (GitHub-repo); available in 25 languages | Messaging, Audio and Video (can be unstable) | End-to-end encryption; can be hosted on own server | No fees |
| Slack |   | Runs on all major systems; Available in 8 languages | Messaging, Audio and Video | Cloud-based (can be hacked); end-to-end encryption | Basic version without fees is normally sufficient |



If the online platform you are using declares its carbon or electricity efficiencies (and it’s likely that it does not) it will help you understand which factors use electricity when using the web service. The company’s data centre and where in the world it is located, how much data the service transmists to and from your network, how efficiently their (often proprietary) software is conceived, and the energy ratings of the computing device you use are all critical factors – and extremely difficult to find! 



**Decisions regarding the way you present your results**

In this area, the key is to take advantage of infrastructure that is used by as many people as possible in order to reduce the carbon footprint per capita. Ad-hoc, tailored solutions are basically the most resource-intensive and should be avoided as much as possible. 



**Making (primary) data available**

Humanities projects with a strong digital component usually include the production of primary data in their expected output (for instance in their Data Management Plan), but research in general, even classical Humanities research without a strong digital component, combines and/or creates primary resources such as texts, images, videos, audios. The simple fact that your research project deals with a specific combination of sources, connected by the research question you work on, could make it worth for you to present this data as a publication per se (in the framework of the rights associated with this data). This type of publication can be included in your publication list or integrated to a data paper publication (on data papers, see [Schöpfel et al., 2019](https://halshs.archives-ouvertes.fr/halshs-02284548/document)). 

Primary data should be hosted in a stable, sustainable environment that will provide access and reuse (reuse is key here in terms of environmental footprint). Research, Teaching and Cultural Heritage Institutions usually provide in-house, state-of-the art solutions (such as nextcloud) on dedicated servers. In some countries (like in France), national infrastructures offer this type for services as well. You can also decide to use trusted repositories like github or zenodo. The key here is to avoid one-shot solutions and maximise mutualisations. This is also in general the best way to ensure multiple site archiving and hence making sure your data will not disappear in a server crash. For more in-depth information on Sustainability and Archiving Strategies, see above (Sustainable preservation and archiving).



**Publishing your results**

Following up on the idea that mutualized infrastructure reduces the carbon footprint, the publication on massive preprint servers like [ArXiv ](https://arxiv.org/)or [HAL](https://hal.archives-ouvertes.fr/) presents an excellent ratio in terms of visibility/resource consumptions. Green Open Access is actually green (see [here](https://en.wikipedia.org/wiki/Open_access#Definitions) the difference between Green and Gold OA).

Gold Open Access, comes with a few caveats. First, like for any other website, the fancier the hosting, the more resource-intensive. Pop-ups, banners, pictures, videos on the publisher’s website are loaded every time the paper is accessed and generating a substantial CO2 footprint. What is more, a wide array of well-established publishers harvests researchers’ data ([data tracking](https://www.dfg.de/download/pdf/foerderung/programme/lis/datentracking_papier_en.pdf)), which is not only problematic in terms of data privacy, but also in terms of environmental impact that comes from harvesting, storing, and using the tracked data. 



**Communicating on social media**

| Software  | Environmental footprint (scrolling 1 minute in gEqCO”) | Energy consumption (1 minute, in mAh) | Data exchange (scrolling 1 minute in MB) |
| --- | --- | --- | --- |
| Twitter   | 0.60 | 10.28 | 6.28 |
| Instagram | 1.05 | 8.9 | 32.46 |
| Facebook  | 0.79 | 12.36 | 11.15 |
| TikTok    | 2.63 | 15.81 | 96.23 |


–> The footprint is smaller with less videos that start being played automatically.  

Src: https://greenspector.com/en/social-media-2021/
 


*Perspectives that we should keep in mind*:

* How much electricity is needed to run a software?
* Is any special hardware needed that needs resources?
* How sustainable is the workflow-process (concerning women/man-power)
* Data privacy (Who hosts my data? On which conditions / legal restrictions? Who has access?)
* Open source software (Who can use the software, accessibility)
* Maybe: Do I need a lot of time to learn something new? Are there communities that can help me?
* Is the tool accessible for people with disabilities or people that speak different languages? 