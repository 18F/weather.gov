# Welcome to Weather.gov 2.0

## Background and core problem

**Weather.gov is owned by the National Weather Service (NWS).** Weather.gov and associated applications are frequently in the Top-10 list of most-visited federal websites with 1.5 billion visits per year. They are a major source of life and property-saving weather/water/climate information for the public and partners. Often they are the only source for on-demand, detailed weather/water/climate information from 122 Weather Forecast Offices.

**The fundamental problem that we’ve observed** is that weather.gov reflects its organizational silos (Conway's Law) more than its users’ needs. A lack of overall strategy, feedback/monitoring, and tools have perpetuated this problem.

This has led to a disorganized repository of valuable information that external users struggle to use and internal users struggle to manage.

We will know that we are progressing forward on this problem if people find the information faster, understand it better, continue to see NWS as the authoritative source, and maintain that progress.

## Vision, mission, and strategy for MVP

### Our vision is that anyone can understand the impact of impending weather. When it comes to making decisions to save life and property, every word and every minute matters.

**Our mission** is to rebuild weather.gov to reflect the integrity and care NWS has for the people you serve. 

Weather.gov 2.0 will only succeed if everyone with NWS sees the site reflect their values, much like the agency. Because the mission and culture at NWS is built around serving, preparing, and protecting people, the site must do the same. 

**Our strategy** for our Minimal Viable Product (MVP) is to make it easier to communicate forecasts and conditions for regular and hazardous weather in a way that anyone can find, understand, and use to take action.

**Our primary outcomes** for MVP include:

  - Make it easier to communicate the impact of impending, regular and hazardous weather
  - Anyone can find, understand, and use the information take action
  - A sustainable and compliant system

**Our primary users** for MVP include:
  - Internal - NWS Meteorologists 
  - External - The Public and Emergency Managers

## Roadmap

**Strategy for prioritization**
  - Now - Prototype individual parts to inform key decisions and evaluate risk
  - Next - Start building the simplest thing possible
  - Later - Add complexity, ASAP

| Phase      | Priorities |
| :----------- | :----------- |
| **Now - Prototype** | <ul><li>Partners / gen public view weather basics</li><li>CMS requirements and viable options</li><li>Critical data integrations</li><li>BONUS: Critical third party integrations</li><li>User validation</li></ul> |
| Next - Build MVP | <ul><li>A “happy path” for NWS forecasters and public users</li><li>1 location</li><li>Core architecture - CMS, Admin experience, User experience, data integrations, CI/CD pipeline</li><li>Initial governance</li><li>User validation</li></ul> |
| Later - Expand | <ul><li>“Unhappy paths” for forecasters and public users</li><li>Multiple locations, geographies, or specialized services</li><li>More comprehensive governance</li><li>User validation</li></ul> |
| Beyond | <ul><li>Transition and migration</li><li>Continuous improvement</li></ul> |

![happy path journey map](/docs/img/happy-path.png)

## How will we ultimately succeed or fail

### We will succeed if 
  - all regions and programs work in good faith with the team when the site is ready to expand and cover their needs
  - decisions are made by those closest to the work, backed by data
  - we start small with a small group and bring it to more and more people
  - having the space to test and iteratively improve
  - Continuously get feedback on working code, over memos and proposals

### We will fail if 
  - The site is mandated, instead of organically adopted
  - We do a big splash rollout
  - A single miss is considered a failure of the project instead of a learning experience to inform the next version
  - Decisions are informed by opinions and perceptions, over observations and data
  - Everyone’s explicit commitment is required to begin development
  - Everyone’s feedback has to be factored into the solution
  - The product team works in isolation from the rest of the NWS

## Public domain

This project is in the worldwide [public domain](LICENSE.md). As stated in [CONTRIBUTING](CONTRIBUTING.md):

> This project is in the public domain within the United States, and copyright and related
> rights in the work worldwide are waived through the
> [CC0 1.0 Universal public domain dedication](https://creativecommons.org/publicdomain/zero/1.0/).
>
> All contributions to this project will be released under the CC0 dedication. By submitting a pull
> request, you are agreeing to comply with this waiver of copyright interest.
