---
title: Progressive Web Application or Device-Based Mobile Application
lang: en
ref: pwa-mobile
---
## Context

This document is to identify key considerations when the choice to develop an application is narrowed between:

- A device-based mobile application
- A progressive web application (PWA)

## Definitions

Web application: A software that is accessed and used via a device's web browser.
It requires a constant access to the Internet to be used.

Progressive web application: A software that is accessed and used via a device's web browser.
It may not require constant access to the Internet to be used, in whole or in part.

Device based mobile application: A software that is accessed and used directly on a mobile device, without the use of a web browser.
It may not require constant access to the Internet to be used.

## Assumption

Proper user research has been conducted and the need for a dedicated application to provide a service is clear.

## Comparison

### Development

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

### 

||WA|PWA|Mobile|
|---|---|---|---|
|Requires Constant Internet Access|Y|||