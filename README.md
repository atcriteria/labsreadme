# Human Rights First - Asylum - Front End

### Product Mission and Goals

Human Rights First (HRF) is a non-profit, nonpartisan, 501(c)(3), international human rights organization based in New York, Washington D.C., Houston, and Los Angeles. HRF works to link immigration attorneys and advocates with asylum seekers and provide those attorneys with resources to best represent their clients. Our application leverages historical data to better inform advocates of a judge’s past decisions. The hope is that advocates for asylum seekers can use our tools to tailor their arguments before a particular judge and maximize their client's chances of receiving asylum.

## Codebases

[Front-End](https://github.com/Lambda-School-Labs/human-rights-first-asylum-fe-a)

[Back-End](https://github.com/Lambda-School-Labs/human-rights-first-asylum-be-a)

[Data Science](https://github.com/Lambda-School-Labs/Lambda-School-Labs-human-rights-first-asylum-ds-a)

### About

- The Front End of the application allows Superadministrators to invite users and assign them as either an Administrator role or a Refugee Representative role. All users authenticate themselves to the application through [Okta](https://www.okta.com/).
- Superadministrators are able to oversee user management such as inviting users, editing any user's role, and deleting users. Superadministrators may also perform all other tasks available to Administrators or Refugee Representatives.
- Administrators are able to approve, deny, or edit uploaded asylum case data, as well as perform all other tasks available to Refugee Representatives.
- Refugee Representatives, or standard users, are able to look up information on judges, look up information on previous asylum cases, upload case file information in bulk on asylum case rulings, and see accurate data visualizations.

- Primary Action color: #215589
- Seconday "Disabled" color: #7f9bb3

### To get started:
- Clone the repo locally to your machine.
- Create an .env file on the top level of the repo, with the provided credentials.
- run: `npm install` to download all dependencies.
- run: `npm start` to start your local development server.

### Key Features and Notes to the Next Group on what still needs work

- PDF Export button for Table Data implemented as well as Ant Design collapse for the FAQ page. Find a way to get the export function to also filter according to table checkbox selections and column selections.
- Cases and Judges can be saved to a user profile by checking their row's select box and clicking the save button, this will add them to the saved cases or saved judges page
- PDF viewer pops up a modal, more work is needed to make it functional
- Case outcome pie chart dynamically renders based on searches
- Continue to convert other tables and menus from MUI to Ant
- Download all has been implemented but a modal needs to be added confirming download all if nothing is selected.
- Created accordians that expand when a case is selected, displaying case information to be reviewed. Fix this to only show the relevant case information rather than information from all cases
- Added animated spinner that runs while the scraper is scraping the data from a PDF

## Bugs

- The PDF Export filters according to search queries but not according to the table check boxes.
<!-- ??? -->
- PDF Modal (clicking “View PDF”) doesn’t work and causes errors when clicked
- The adminData and userData functions do not work currently as there are no endpoints for distinguishing between user types and the components do not exist
- Sometimes https://a.humanrightsfirstasylum.dev/ gets stuck on “Fetching user profile” after signing in.  The current workaround is to clear localStorage. Updating Okta may have fixed this problem. 


## Contributors

### Labs33 - Web
| [Juan Ruiz](https://github.com/ruizaj13) | [Niki Dossett](https://github.com/ndossett) | [Senih AYDIN](https://github.com/aydinsenih) |
| --- | --- | --- |
| [<img src="https://avatars.githubusercontent.com/u/61928590?v=4" width="200" align="center"/>](https://github.com/ruizaj13) | [<img src="https://avatars.githubusercontent.com/u/68928202?v=4" width="200" align="center"/>](https://github.com/ndossett) | [<img src="https://avatars.githubusercontent.com/u/35286437?v=4" width="200" align="center"/>](https://github.com/aydinsenih) | 
| |
| [Cameron Mirza](https://github.com/cmirza) | [Matthew Justice](https://github.com/JusticeMatthew) | [Christina Melchor](https://github.com/c-melchor) |                                     | --- | --- | --- }
| [<img src="https://avatars.githubusercontent.com/u/7876859?v=4" width="200" align="center"/>](https://github.com/cmirza) | [<img src="https://avatars.githubusercontent.com/u/72817096?v=4" width="200" align="center"/>](https://github.com/JusticeMatthew) |[<img src="https://avatars.githubusercontent.com/u/71955286?v=4" width="200" align="center"/>](https://github.com/c-melchor) |
| |
| [Crystal Csete](https://github.com/crystal-csete) |
| [<img src="https://avatars.githubusercontent.com/u/68755171?v=4" width="200" align="center"/>](https://github.com/ruizaj13) |

### Labs32 - Web

|                                                                                                                                                                               |                                                                                                                                                                              |                                                                                                                                                                                   |
| :---------------------------------------------------------------------------------------------------------------------------------------------------------------------------: | :--------------------------------------------------------------------------------------------------------------------------------------------------------------------------: | :-------------------------------------------------------------------------------------------------------------------------------------------------------------------------------: |
|                                                                [Matt Bokovitz](https://github.com/MattBokovitz1)                                                                |                                                               [Rees Harper](https://github.com/reesharper)                                                               |                                                                [Nathaniel Patterson](https://github.com/odst0016)                                                                 |
| [<img src="https://avatars.githubusercontent.com/u/70045367?v=4" width = "200" align="center"/>](https://github.com/MattBokovitz1) | [<img src="https://avatars.githubusercontent.com/u/70249966?v=4" width = "200" align="center"/>](https://github.com/reesharper) | [<img src="https://avatars.githubusercontent.com/u/1438371?v=4" width = "200" align="center"/>](https://github.com/odst0016) |              
|                                                                                                                                                                               |                                                                                                                                                                              |                                                                                                                                                                                   |
|                                                                [Dionne Stratton](https://github.com/Dionne-Stratton)                                                                 |                                                              [Krista Verleger](https://github.com/kristapants)                                                               |                                                                                                                                      |
| [<img src="https://avatars.githubusercontent.com/u/68926102?v=4" width = "200" align="center"/>](https://github.com/Dionne-Stratton) | [<img src="https://avatars.githubusercontent.com/u/42698664?v=4" width = "200" align="center"/>](https://github.com/kristapants) |

### labs31 - Team A

[Brian Abeyta-Pratt](https://github.com/babeytapratt),[LinkedIn](https://www.linkedin.com/in/brian-abeyta-pratt-9758991ba/)


### Labs30 - Team A

|                                                                                                                                                                               |                                                                                                                                                                              |                                                                                                                                                                                   |
| :---------------------------------------------------------------------------------------------------------------------------------------------------------------------------: | :--------------------------------------------------------------------------------------------------------------------------------------------------------------------------: | :-------------------------------------------------------------------------------------------------------------------------------------------------------------------------------: |
|                                                                [Tzong-Lian Tsay](https://github.com/tzonglian)                                                                |                                                               [Trevor Beadle](https://github.com/TrevorBeadle)                                                               |                                                                [Reuben Palumbo](https://github.com/reubenPalumbo)                                                                 |
| [<img src="https://avatars.githubusercontent.com/u/68922354?s=460&u=93ce3bbc5de94dd89246239b70828545b5dcac5e&v=4" width = "200" align="center"/>](https://github.com/avawing) | [<img src="https://avatars.githubusercontent.com/u/66217015?s=460&u=bc4a490d18d80167985a032f5ca86b9193124a6c&v=4" width = "200" align="center"/>](https://github.com/TBau23) | [<img src="https://avatars.githubusercontent.com/u/68444266?s=460&u=ff38ccc9dcb83047c2134ce9852e0dfef1fae8fb&v=4" width = "200" align="center"/>](https://github.com/SassyFatCat) |
|                                                                [Linkedin](https://www.linkedin.com/in/tltsay/)                                                                |                                                       [Linkedin](https://www.linkedin.com/in/trevor-beadle-1850481b6/)                                                       |                                                              [Linkedin](https://www.linkedin.com/in/reuben-palumbo/)                                                              |
|                                                                                                                                                                               |                                                                                                                                                                              |                                                                                                                                                                                   |
|                                                                [Anna Brander](https://github.com/aelise17264)                                                                 |                                                              [Maycie Morris](https://github.com/maycie-morris)                                                               |                                                                   [Lynda Santiago](https://github.com/lyntechi)                                                                   |
| [<img src="https://avatars.githubusercontent.com/u/66019108?s=460&u=b98ac38b13155691c2189b10914cff7a092ab5a5&v=4" width = "200" align="center"/>](https://github.com/avawing) | [<img src="https://avatars.githubusercontent.com/u/67204638?s=460&u=57c9c3585fd3326f80ce34c02cbb7939a3ddc0fa&v=4" width = "200" align="center"/>](https://github.com/TBau23) | [<img src="https://avatars.githubusercontent.com/u/64440403?s=460&u=ebd52037cfa31421477942f041a43a6ef88267ca&v=4" width = "200" align="center"/>](https://github.com/SassyFatCat) |
|                                                             [Linkedin](https://www.linkedin.com/in/aelise17264/)                                                              |                                                            [Linkedin](https://www.linkedin.com/in/mayciemorris/)                                                             |                                                         [Linkedin](https://www.linkedin.com/in/lynda-santiago-7b58221b4/)                                                         |


### Labs29 - Team A

|                                                                                                                                          |                                                                                                                                         |                                                                                                                                              |
| :--------------------------------------------------------------------------------------------------------------------------------------: | :-------------------------------------------------------------------------------------------------------------------------------------: | :------------------------------------------------------------------------------------------------------------------------------------------: |
|                                               [Ava Wingfield](https://github.com/avawing)                                                |                                                 [Tom Bauer](https://github.com/TBau23)                                                  |                                                  [Ryan Lee](https://github.com/SassyFatCat)                                                  |
| [<img src="https://ca.slack-edge.com/ESZCHB482-W014G4L7R1P-5e90ae004407-512" width = "200" align="center"/>](https://github.com/avawing) | [<img src="https://ca.slack-edge.com/ESZCHB482-W015P694SUV-84c590ba765c-512" width = "200" align="center"/>](https://github.com/TBau23) | [<img src="https://ca.slack-edge.com/ESZCHB482-W014G4N2FEV-9b9fece7a4af-512" width = "200" align="center"/>](https://github.com/SassyFatCat) |
|                                          [Linkedin](https://www.linkedin.com/in/avawingfield/)                                           |                                           [Linkedin](https://www.linkedin.com/in/tombauer11/)                                           |                                             [Linkedin](https://www.linkedin.com/in/sassyfatcat/)                                             |
<br />

###
