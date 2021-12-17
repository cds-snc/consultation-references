---
title: Progressive Web Application or Device-Based Mobile Application
lang: en
ref: pwa-mobile
---
## Context

This document is to identify key considerations when the choice to develop an application for mobile devices is narrowed down between:

- A device-based mobile application
- A progressive web application (PWA)

## Definitions

Progressive web application: A web application accessed and used via a web browser, leveraging modern browsers functionalities to offer the user a similar experience as a device based mobile application.

Device based mobile application: A dedicated software that is accessed and used directly on a mobile device operating system.

## Considerations

Key elements to consider:

- Will the user need to be able to use the application while being offline intermitently?
- Will the user need to be able to use the application while being offline for an extended period?
- Will the user need to be able to exchange information with the service provider when using via the application?
- Will the application require the use of a lot of graphics or storage space?
- Does the current staff has the necessary knowledge to develop the application?
- Does the team have access to the necessary tools and development environment to support the chosen solution (PWA or Mobile)?

Procuring custom code vs. internal development

- While the development of the application by a third party may seem faster, the end-to-end duration of procurement processes and the rigidity of properly framing the requirements ahead of time may lead to extra delays.
  - External development discards an opportunity to build the internal knowledge and capacity to develop and maintain modern web applications and maintain their content in the long term.
  - When contracting with a third party, the foreground intellectual property (IP), in this case the custom code developed, by default resides with the contractor (see references below). This means that future changes to the code or releasing it as open source is not possible unless sufficient rights are acquired in the contracting agreement. Two main options can be looked into to mitigate this situation:
    - An exception is requested to TBS so that the foreground IP is acquired by the Crown. This could work but could introduce unnecessary delays and complications.
    - The custom code is obtained under sufficient terms and conditions to allow the GC to released it as open source, under the licence of its choice. Either the service provider agrees to licence the custom source code under a predetermined licence (MIT, Apache 2.0, etc.) or under terms broad enough to have the code released publicly under a licence of the Crown representative's choice (see Guide on Publishing OSS).

Device-based mobile applications

- Mobile operating systems and devices have independent roadmaps, update schedules and version distribution across the entire market which implies an extensive amount of testing every time there is a change by a third party to remain compliant with the TBS Standard on Optimizing Websites and Applications for Mobile Devices (see References below).
  - For example, there are currently 4 major Android versions and at least 2 major iOS versions with currently more than 5% market share, meaning that a device based mobile application would need to be compatible with all of them to meet the TBS policy mentioned above.
- Mobile applications have to be published on curated application stores which are outside the control of the Government of Canada, adding a layer of uncertainty and possibly introducing unexpected delays.
- On the other hand, a device-based mobile application can use all the hardware features offered by the mobile device operating system which is not the case for a PWA since it is limited to the browser’s features instead. This still allows for a very rich user experience if properly designed.


### User Experience

||PWA|Mobile|
|---|---|---|
|Acquiring the app|Visit the website|Find in application catalogue|
|Installing the app|Add to home screen|Purchase* and download|
|Using the installed app|Click on the icon|Click on the icon|
|Uninstalling|Delete the icon|Delete the applicaton from the menu|

*Purchase: if required

### Government of Canada Obligations

The application, whether PWA or mobile, must be compliant with the Government of Canada regulations and policies:

- Accessibility
- Official languages
- Security
- Privacy (PIPEDA)
- Standard on Optimizing Websites and Applications for Mobile Devices

### Development

Consideration should also be taken with regards to the development specificities.
<!-- markdownlint-disable MD033 -->
||PWA|Mobile|
|---|---|---|
|Programming languages|Mainly HTML, CSS, Javascript<br>Supports other languages and frameworks|Mobile operating system specific:<br><ul><li>iOS: Most popular are Swift, Objective-C but possible to use Javascript and a few other languages</li><li>Android: Java, Kotlin, C#, Python, Dart</li></ul>|
|Development Environment Operating System|Can be developed on all major operating systems<ul><li>Windows</li><li>macOS</li><li>Linux</li></ul>|Mobile operating system specific:<ul><li>iOS: macOS only<li>Android: all major operating systems<ul><li>Windows</li><li>macOS</li><li>Linux</li></ul></ul>|

- Programming languages
  - Web app or PWA can be built with programming languages supported by most modern browsers. A single code base could sufficient to offer the application to all mobile users, in line with the TBS Standard with regards to marketshare of platforms.
  - Mobile apps require device specific compatible programming languages meaning that at least two separate code base would be needed to support the two major operating systems (iOS and Android)
- Development environments
  - iOS mobile applications requires the use of Mac computer with the latest version of Xcode. Mac computers are not currently supported by default on the Government of Canada network and usually are operated independantly.
  - Web apps and PWA can be developed on all major desktop operating systems, including Windows, macOS and most Linux distributions.
- Toolchain
  - Web applications, PWA, and mobile device applications all support the use of various tools to improve development practices such as frameworks, software dependency libraries and package management, 
- Skillset
  - The programming languages, development frameworks and available dependencies being different, it may not be possible to easily transfer the knowledge of software development teams from web to mobile, or at least not do so without a loss in productivity.

### Release and Update

- Both web app and PWA offer more flexibility than mobile app since don't need to deal with curated marketplace for applications.
- Releasing and updating a mobile application requires a developer account with each marketplace, adding overhead compared with a web app or a PWA.

(link to Apple and Play store rules)

### Maintenance

- 

### User

||WA|PWA|Mobile|
|---|---|---|---|
|Requires Constant Internet Access|Y|||