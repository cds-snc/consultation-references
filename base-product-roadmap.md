# High Level Roadmap

- [High Level Roadmap](#high-level-roadmap)
  - [Product Design](#product-design)
    - [Hypothesis Validation](#hypothesis-validation)
    - [Content Structure](#content-structure)
    - [Data Vizualisation](#data-vizualisation)
    - [Advanced Search](#advanced-search)
    - [Interactive Capabilities](#interactive-capabilities)
  - [Product Development](#product-development)
    - [Content Management System (CMS)](#content-management-system-cms)
    - [Presentation Layer](#presentation-layer)
    - [Visualizations](#visualizations)
    - [Search](#search)
    - [Interactive Functionalities](#interactive-functionalities)

```mermaid
%%{init: {'theme': 'base', 'themeVariables': { 'primaryColor': '#F6BE00' }, 'themeCSS': ".taskText { font-size:13px; font-weight: bold} .taskTextOutsideRight { font-size:13px; fill: #F6BE00; text-shadow: 1px 1px 1px black; font-weight: bold;} .taskTextOutsideLeft { font-size:13px; fill: #F6BE00; text-shadow: 0.5px 0.5px 0.5px black; font-weight: bold;} .section {opacity:0.05} "}}%%
gantt
    title High Level Roadmap
    dateFormat  YYYY-MM-DD
    axisFormat  %Y-%m
    excludes    weekends

    section Product Design

    Hypothesis Validation               :  des1, 2022-05-15, 25d
    End Users Recruitment               :2022-05-15, 5d
    User Experience Research            :10d
    UX Report                           :10d

    Content Structure                   : des2, after des1,  30d
    Current Structure Assessment        :des2a, after des1, 5d
    New Structure Design                :15d
    User Testing                        :5d
    Production Release                  :milestone, mil1, after des2, 0d
    
    Data Visualizations             : des3, after mil1, 30d
    UX Research                     :after mil1, 5d
    Options Analysis                :3d
    Prototyping                     :7d
    User Testing                    :4d
    Production Release              :milestone, mil2, after des3, 0d
    
    Advanced Search                 : des4, after des3, 12d
    UX Research                     :after des3, 2d
    Wireframes                      :3d
    Prototype                       :5d
    User Testing                    :2d
    Production Release              :milestone, 0d

    Interactive Capabilities            : des5, after des4, 25d
    UX Research                         :after des4, 5d
    Wireframes                          :5d
    Prototype                           :10d
    User Testing                        :2d
    Production Release                  :milestone, 0d


    section Product Development

    Content Management System : dev1, 2022-05-20, 30d
    Technical Team Sync: milestone, 2022-05-20, 0d
    Technical Options Analysis :2022-05-20, 5d
    Security Assessment          :crit,  5d
    CMS Decision: milestone, 0d
    CMS Deployment      : 20d
    CMS in Production: milestone, 0d
    
    Presentation Layer              : dev2, after dev1, 20d
    CMS Modules Config              :after dev1, 10d
    Source Data Integration         :5d
    Custom Modules                  :5d
    Production Release              :milestone, 0d

    Data Vizualisation              : dev3, after dev2, 30d
    Technical Options Analysis      :after dev2, 5d
    Feature Development             :25d
    Production Release              :milestone, 0d

    Advanced Search                 : dev4, after dev3, 15d
    Production Release              : milestone, 0d

    Interactive Capabilities        : dev5, after dev4, 40d
    Production Release              : milestone, 0d
    
```

## Product Design

Typically, the following actors will be required for the product design:

- Product Manager
- Content Designer
- Service Designer
- User Experience Researcher
- End Users

All the milestones in the Design swimlane align with milestones in the Development one.
The reason is that although they may require different skills and methodologies, they should be conducted simultaneously by a multidisciplinary team.

This means that if the product developers have their substantiary position with an IT branch or a private company, a clear understanding that everyone must work together as a single team is required for a successful Agile delivery of the product.

### Hypothesis Validation

The first milestone would be to validate the hypothesis defined by the product team by conducting a User Experience Research.
This is considered the Discovery stage.

While a lot of information may be gathered at this step, there wouldn't necessarily be any technical deployment visible to the end users yet.
However, the development team would already be heavily involved in analyzing and choosing the best technical tools to support an interactive product development.

### Content Structure

The second milestone would be to design the content structure and validate the changes with end users.

### Data Vizualisation

The third milestone would be to design data vizualisation and validate the proposed changes with end users.

### Advanced Search

The fourth milestone would be to design an advanced search feature and validate it with end users.

### Interactive Capabilities

The last milestone is actually a possible series of additional milestones.
The reason here is that as the product evolves over time and features are added, user feedback will provide valuable and tangible information as to what other capabilities are required to meet their needs.

## Product Development

Typically, the following actors will be required for the product design:

- Developers
- System Administrators

Whoever will be part of the development and operations team must be onboard early on and throughout the entire product development life cyle.
Multiple "short projects" can be used to secure internal IT staff's time if the product team does not have developers embedded with them.

The product roadmap should provide sufficient work level estimates but not consist in a business requirements document since short development cycles will be leveraged to course correct based on end users needs and feedback.

### Content Management System (CMS)

The first milestone on the product development front would be to settle on a content management system that supports flexible configuration out of the box and deploying it for the product team.

Note: This milestone also includes an integration stage with the data source via an API so that the product team can focus on the presentation layer instead of data formatting.

### Presentation Layer

The second milestone would be to configure the CMS to meet the content design needs.

If out of the box configurations are not meeting all the needs, additional modules could be developed.

### Visualizations

The third milestone would be to configure the CMS to meet the Visualizations needs identified by the end users.

If out of the box features are not meeting all the requirements, extensive open source vizualisation libraries can be leveraged to ensure rapid prototyping and ensuring flexibility for future needs.

### Search

The fourth milestone would be to configure the CMS to meet the search functionalities identified in the user experience research.

While most modern CMS offer out of the box search features, the development team might need to look at enhancing those with additional open source libraries or Software as a Service (SaaS) offerings.

### Interactive Functionalities

The fifth milestone would be further fleshed out by the continuous user feedback throughout the entire length of the product development life cycle.

As new needs are surfaced, further technical analysis would be required and features development planned accordingly.
