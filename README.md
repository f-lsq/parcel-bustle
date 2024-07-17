# Parcel Bustle (Frontend)
[Parcel Bustle](#) is a cutting-edge courier service app designed to streamline your courier and logistic needs. With this app, you can manage parcel deliveries and track shipments in real-time with no hassle.

<p align="center">
  <img src="assets/images/readme/logo.webp#gh-light-mode-only" width="400" margin="auto">
  <img src="assets/images/readme/logo-dark.webp#gh-dark-mode-only" width="400" margin="auto">
</p>

This app is targeted for last-mile delivery services providers, specialising in transporting good from a distribution center to the end customer's doorstep. It allows workers to save parcel details into the system either using an Optical Character Recognition (OCR) tool, or by manual input. Customers will be contactable via WhatsApp with the click of a button, while the host can manage the parcels and workers' permission through the frontend interface.

* [Frontend Repository](https://github.com/f-lsq/parcel-bustle) (React Native with Redux, Expo)
* [Backend Repository](https://github.com/f-lsq/parcel-bustle-backend) (Golang - Gin, GORM, MySQL)

## Table of Contents
1. [UI/UX](#uiux)
2. [Features](#features)
3. [Technologies Used](#technologies-used)
4. [Deployment](#deployment)
5. [Credits](#credits)
6. [References](#references)

## UI/UX
### User Stories
1. As a *worker*, I want to be able to scan the individual parcels' information, so that the parcel details will be recorded in the system
2. As a *worker*, I want to be able to upload images of the delivered parcels, so that they can be marked as delivered and also sent to the customers for confirmation
3. As a *host*, I want to be able to see the list of the parcels, workers and customers, so that I will be able to combine any parcel orders, and perform CRUD operations on the lists 
4. As a *host*, I want to be able to see the list of the undelivered parcels, so that I can contact the affected customers to settle their delivery

### User Flow Diagram
![User Flow Diagram](flowchart.png)


### Wireframes
Below are the wireframes for both the worker, and admin pages. The link to the Figma project can be accessed [here](https://www.figma.com/design/CiTGcBQOT12mRk9EoIGapD/ParcelBustle?node-id=1-4&t=ymUMwcQ5qwJpLO2J-1).

## Features

## Technologies Used
### Frontend
* [React Native](https://reactnative.dev/)
* [Expo](https://expo.dev/)

### Backend
* [Gin](https://gin-gonic.com/docs/) - Server environment. [GORM](https://gorm.io/)
* [MySQL](https://www.mysql.com/)/[PostgresSQL](https://www.postgresql.org/) - Database management

## Deployment
### Live Links
* [React Native Frontend](#)
* [Gin Backend](#)

### Test Accounts
| Account Type | Name | Email | Password | 
|--------------|------|-------|----------|
| Worker       | [Mulan Hua](https://disney.fandom.com/wiki/Fa_Mulan) | mulanhua@parcelbustle.com    | mulanhua123@      |
| Worker       | [Shang Li](https://disney.fandom.com/wiki/Li_Shang)   | shangli@parcelbustle.com    | shangli123@      |
| Worker       | [Chi Fu](https://disney.fandom.com/wiki/Chi-Fu)   | chifu@parcelbustle.com    | shangli123@      |
| Host         | [Yu Shan](https://en.wikipedia.org/wiki/Li_Shang)      | shanyu@parcelbustle.com    | *Not provided* |

## Credits
Links to all assets are listed here.

* Logo - [Fast delivery service logo](https://stock.adobe.com/sg/images/fast-delivery-service-logo/317882616)

Do note that some assets were manipulated with using AI and design tools, such as  [Adobe Background Remover](https://www.adobe.com/express/feature/image/remove-background) and [Krita](https://krita.org/en/).

This project is not intended for commercial use and no profit will be generated from it. 

For any issues with regard to the use of the above assets, please [contact me via GitHub](https://medium.com/@kahkoii/how-to-contact-a-user-on-github-b6b62c3db92f). Thank you!

## References
1. [Tania, R. (n.d.). React Architecture: How to Structure and Organize a React Application.](https://www.taniarascia.com/react-architecture-directory-structure/)