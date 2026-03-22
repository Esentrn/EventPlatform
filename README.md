# Event Planning Platform

This project is an **Event Planning Platform** where users can create events, join events, and engage in social interaction around them. Users can receive rule-based personalized event recommendations, chat with others, and track events through map integration.

This project was developed with **ASP.NET Core MVC** and uses the **OpenStreetMap API** for map integration.

---

## Technologies and Tools

- **Backend:** ASP.NET Core MVC
- **Frontend:** HTML, CSS, JavaScript
- **Database:** Microsoft SQL Server
- **Map Integration:** OpenStreetMap API

---

## Main Features

### User Management

- User registration, login, and profile update
- Password reset and verification
- User roles (**Admin / User**)

### Event Management

- Create, edit, and delete events
- List event details
- Prevent event conflicts with a time-overlap detection algorithm

### Rule-Based Event Recommendation System

- Event recommendations based on user interests
- Personalized suggestions based on participation history
- Location-based event recommendations

### Map and Route Planning

- **OpenStreetMap API** integration
- Users can view event locations on the map
- Users can calculate the most suitable route to the event

### Messaging and Notifications

- Users can chat on event pages
- Instant message notifications and message history

### Gamification System

- Users can earn points by participating in events
- User points are displayed on the profile page

### Admin Panel

- Authority to approve, edit, and delete events
- Manage user accounts
- System settings and reporting

## API Usage

The project uses the **OpenStreetMap API** for map and route planning services. The API integration was implemented through libraries such as **Leaflet.js**.

- **Viewing Event Locations:**  
  Users can view the event location on the map from the event details page.
- **Route Planning:**  
  Users can calculate the most suitable route from their current location to the event.

---

## Installation and Setup

### 1. Clone the Repository

Run the following commands in your terminal or command prompt:

```sh
git clone https://github.com/Esentrn/EventPlatform.git
cd EventPlatform
```

### 2. Run the Application

You can start the application by pressing `F5` in Visual Studio or by running the following command in the terminal:

```sh
dotnet run
```

---

## Screenshots

![Image](https://github.com/Esentrn/EventPlatform/blob/1723dd634a927d9d14f78725eb809da478d444f1/EventPlatform/Images2/EventPlatform_1.png)

![Image](https://github.com/Esentrn/EventPlatform/blob/1723dd634a927d9d14f78725eb809da478d444f1/EventPlatform/Images2/EventPlatform_2.png)

![Image](https://github.com/Esentrn/EventPlatform/blob/1723dd634a927d9d14f78725eb809da478d444f1/EventPlatform/Images2/EventPlatform_11.png)

<table>
  <tr>
    <td><img src="https://github.com/Esentrn/EventPlatform/blob/1723dd634a927d9d14f78725eb809da478d444f1/EventPlatform/Images2/EventPlatform_3.png" alt="Event Platform Screenshot 3"/></td>
    <td><img src="https://github.com/Esentrn/EventPlatform/blob/1723dd634a927d9d14f78725eb809da478d444f1/EventPlatform/Images2/EventPlatform_4.png" alt="Event Platform Screenshot 4"/></td>
  </tr>
  <tr>
    <td><img src="https://github.com/Esentrn/EventPlatform/blob/1723dd634a927d9d14f78725eb809da478d444f1/EventPlatform/Images2/EventPlatform_5.png" alt="Event Platform Screenshot 5"/></td>
    <td><img src="https://github.com/Esentrn/EventPlatform/blob/1723dd634a927d9d14f78725eb809da478d444f1/EventPlatform/Images2/EventPlatform_6.png" alt="Event Platform Screenshot 6"/></td>
  </tr>
  <tr>
    <td><img src="https://github.com/Esentrn/EventPlatform/blob/1723dd634a927d9d14f78725eb809da478d444f1/EventPlatform/Images2/EventPlatform_7.png" alt="Event Platform Screenshot 7"/></td>
    <td><img src="https://github.com/Esentrn/EventPlatform/blob/1723dd634a927d9d14f78725eb809da478d444f1/EventPlatform/Images2/EventPlatform_8.png" alt="Event Platform Screenshot 8"/></td>
  </tr>
  <tr>
    <td><img src="https://github.com/Esentrn/EventPlatform/blob/1723dd634a927d9d14f78725eb809da478d444f1/EventPlatform/Images2/EventPlatform_9.png" alt="Event Platform Screenshot 9"/></td>
    <td><img src="https://github.com/Esentrn/EventPlatform/blob/1723dd634a927d9d14f78725eb809da478d444f1/EventPlatform/Images2/EventPlatform_10.png" alt="Event Platform Screenshot 10"/></td>
  </tr>
  <tr>
    <td><img src="https://github.com/Esentrn/EventPlatform/blob/1723dd634a927d9d14f78725eb809da478d444f1/EventPlatform/Images2/EventPlatform_12.png" alt="Event Platform Screenshot 12"/></td>
    <td><img src="https://github.com/Esentrn/EventPlatform/blob/1723dd634a927d9d14f78725eb809da478d444f1/EventPlatform/Images2/EventPlatform_13.png" alt="Event Platform Screenshot 13"/></td>
  </tr>
</table>
