# CatMap v2

CatMap v2 is a campus parking navigation app currently being upgraded to provide **enhanced features** like **user login authentication**. The app helps users find the nearest parking lots, check real-time occupancy, and plan ahead.

## User Interface

![CatMap UI](./src/catmap.svg)  

> Full UI mockup showing map interface, predictive information, and login panel.

## Features

- **Real-time parking lot availability** with color-coded pins  
- **User authentication & login system** for personalized experience  
- **OpenStreetMap powered map** for accurate location tracking  
- **Mobile and desktop friendly interface**
  
## Key Technologies

- **Backend:** Java, Spring Boot (with Thymeleaf for templating)  
- **Frontend:** JavaScript, Thymeleaf templates  
- **Mapping API:** OpenStreetMap  
- **Database:** MySQL / PostgreSQL (for parking history and user accounts)  

## How it Works

1. The **map interface** displays parking lots as pins.  
2. **Pin colors** indicate occupancy:
   - Green → Available  
   - Yellow → Filling Up  
   - Red → Full  
3. Click a pin to see detailed occupancy info.
4. . **User Login:** Access personalized settings, saved preferences, and history.


## Why CatMap v2 Matters

Finding a parking space on campus can be frustrating. CatMap helps:

- Save time for students, staff, and visitors  
- Reduce traffic congestion in parking areas  
- Enable smarter, data-driven parking management (CatMap v3 will leverage AI, predictive analytics)

## Getting Started

```bash
# Clone Repository
git clone https://github.com/yourusername/catmap-v2.git
cd catmap-v2

# Build & Run Backend
./mvnw spring-boot:run

# Open Application
# Navigate to http://localhost:8080 in your browser
```

## Team
> Pratik Chaudhari

> Nathan Wick
