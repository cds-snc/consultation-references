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
    - [Vizualisations](#vizualisations)
    - [Search](#search)
    - [Interactive Functionalities](#interactive-functionalities)

```mermaid
%%{init: {'theme':'base'}}%%
gantt
    title High Level Roadmap
    dateFormat  YYYY-MM-DD
    axisFormat  %Y-%m
    excludes    weekends

    section Product Design

    Hypothesis Validation               :active,  des1, 2022-05-15, 25d
    End Users Recruitment               :2022-05-15, 5d
    User Experience Research            :10d
    UX Report                           :10d

    Content Structure                   :active, des2, after des1,  30d
    Current Structure Assessment        :des2a, after des1, 5d
    New Structure Design                :15d
    User Testing                        :5d
    Production Release                  :milestone, mil1, after des2, 0d
    
    Data Vizualisations             :active, des3, after mil1, 30d
    UX Research                     :after mil1, 5d
    Options Analysis                :3d
    Prototyping                     :7d
    User Testing                    :4d
    Production Release              :milestone, mil2, after des3, 0d
    
    Advanced Search                 :active, des4, after des3, 12d
    UX Research                     :after des3, 2d
    Wireframes                      :3d
    Prototype                       :5d
    User Testing                    :2d
    Production Release              :milestone, 0d

    Interactive Capabilities            :active, des5, after des4, 25d
    UX Research                         :after des4, 5d
    Wireframes                          :5d
    Prototype                           :10d
    User Testing                        :2d
    Production Release                  :milestone, 0d


    section Product Development

    Content Management System (CMS) :active, dev1, 2022-05-15, 31d
    Technical Options Analysis :2022-05-15, 5d
    Security Assessment          :crit,  5d
    CMS Decision: milestone, 0d
    CMS Deployment      : 20d
    CMS in Production: milestone, 0d
    
    Presentation Layer              :active, dev2, after dev1, 20d
    CMS Modules Config              :after dev1, 10d
    Source Data Integration         :5d
    Custom Modules                  :5d
    Production Release              :milestone, 0d

    Data Vizualisation              :active, dev3, after dev2, 30d
    Technical Options Analysis      :after dev2, 5d
    Feature Development             :25d
    Production Release              :milestone, 0d

    Advanced Search                 :active, dev4, after dev3, 15d
    Production Release              : milestone, 0d

    Interactive Capabilities        :active, dev5, after dev4, 40d
    Production Release              : milestone, 0d
    
```

## Product Design

Typically, the following actors will be required for the product design:

- Product Manager
- Content Designer
- Service Designer
- User Experience Researcher
- End Users

### Hypothesis Validation

### Content Structure

### Data Vizualisation

### Advanced Search

### Interactive Capabilities

## Product Development

Typically, the following actors will be required for the product design:

- Developers
- System Administrators

### Content Management System (CMS)

### Presentation Layer

### Vizualisations

### Search

### Interactive Functionalities

