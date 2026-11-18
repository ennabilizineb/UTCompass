# UTCompass Transportation App

> Campus transportation, wayfinding and parking management system for the UTM Johor Bahru community.
> SCSE2243 Application Development Project 1 · Section 01 · Semester 1 2026/2027

**Tech stack:** HTML5 · CSS3 · Bootstrap 5 · JavaScript (AJAX / Fetch API) · PHP 8.5 (Apache / XAMPP) · MySQL · PHPMailer · Postman · GitHub · Trello

---

## TINKER CO. MEMBERS

| Name | Matric Number | Subsystem |
|------|---------------|-----------|
| Zeng Liting | A24CS4073 | 1 – Shuttle Schedule & Route Management |
| Ennabili Zineb | A24CS4057 | 2 – Real-Time GPS & Fleet Tracking |
| Rawan MohamedSalih Magzob | A24CS4066 | 3 – Ride Reservation & Alert Notification |
| Abu Saleh Md Tahsin | A24CS4060 | 4 – Parking Availability & Reservation |

## SPRINT PLAN

| Sprint | Focus |
|--------|-------|
| 1 | Module 1 of each subsystem, sprint report |
| 2 | Module 2 of each subsystem, sprint report |
| 3 | Module 3 of each subsystem, sprint report |
| 4 | Cross-subsystem integration, SIT, UAT, bug fixing, final report |

---

## SUBSYSTEM 1 : ZENG LITING

| Sprint | Module | FrontEnd | BackEnd | Database |
|--------|--------|----------|---------|----------|
| 1 | Route-level Detail Management | <ul><li>[Route Management Page](frontend/route_management.html)</li><li>[Bus Stop List Page](frontend/bus_stops.html)</li><li>[Route Details Page](frontend/route_details.html)</li></ul> | <ul><li>[Route CRUD API](backend/api/routes.php)</li><li>[Bus Stop Management API](backend/api/bus_stops.php)</li></ul> | <ul><li>[Routes Table](database/routes.sql)</li><li>[Bus Stops Table](database/bus_stops.sql)</li><li>[Route Stops Table](database/route_stops.sql)</li></ul> |
| 2 | Vehicle and Driver Route Assignment | <ul><li>[Vehicle Assignment Page](frontend/vehicle_assignment.html)</li><li>[Driver Assignment Page](frontend/driver_assignment.html)</li><li>[Assignment Overview Page](frontend/assignment_overview.html)</li></ul> | <ul><li>[Vehicle Assignment API](backend/api/vehicle_assignment.php)</li><li>[Driver Assignment API](backend/api/driver_assignment.php)</li><li>[Assignment Validation](backend/helpers/assignment_validation.php)</li></ul> | <ul><li>[Vehicles Table](database/vehicles.sql)</li><li>[Drivers Table](database/drivers.sql)</li><li>[Route Assignments Table](database/route_assignments.sql)</li></ul> |
| 3 | Shuttle Bus Timetable Management | <ul><li>[Shuttle Timetable Page](frontend/shuttle_timetable.html)</li><li>[Timetable Management Page](frontend/timetable_management.html)</li><li>[Schedule Search & Filter](frontend/schedule_filter.js)</li></ul> | <ul><li>[Timetable CRUD API](backend/api/timetables.php)</li><li>[Schedule Retrieval API](backend/api/schedules.php)</li><li>[Timetable Conflict Validation](backend/helpers/timetable_validation.php)</li></ul> | <ul><li>[Timetables Table](database/timetables.sql)</li><li>[Routes Table](database/routes.sql)</li><li>[Route Stops Table](database/route_stops.sql)</li></ul> |
| 4 | Integration | <ul><li>[Integrated Route & Schedule View](frontend/route_schedule.html)</li><li>[UI Testing & Refinement](frontend/)</li></ul> | <ul><li>[API Integration](backend/api/)</li><li>[Integration Testing & Bug Fixing](tests/)</li></ul> | <ul><li>[Database Integration](database/)</li><li>[Data Consistency Validation](tests/)</li></ul> |

---

## SUBSYSTEM 2 : ENNABILI ZINEB

| Sprint | Module | FrontEnd | BackEnd | Database |
|--------|--------|----------|---------|----------|
| 1 | Telemetry Ingestion & Data Smoothing | <ul><li>[GPS Simulator Page](frontend/gps_simulator.html)</li><li>[Telemetry Monitor Page (Admin)](frontend/telemetry_monitor.html)</li></ul> | <ul><li>[Telemetry Controller](backend/api/telemetry.php)</li><li>[Data Smoothing Helper](backend/helpers/smoothing.php)</li></ul> | <ul><li>[GPS Records Table](database/gps_records.sql)</li><li>[Vehicles Table](database/vehicles.sql)</li></ul> |
| 2 | Live Streaming & Client Broadcast | <ul><li>[Live Map Page](frontend/live_map.html)</li><li>[Bus Detail Panel](frontend/bus_detail.html)</li><li>[Route Overlay Component](frontend/js/route_overlay.js)</li></ul> | <ul><li>[Live Location Controller](backend/api/live_location.php)</li><li>[Broadcast Controller](backend/api/broadcast.php)</li></ul> | <ul><li>[GPS Records Table](database/gps_records.sql)</li><li>[Vehicles Table](database/vehicles.sql)</li></ul> |
| 3 | Dynamic ETA & Route Progress Engine | <ul><li>[ETA Board Page](frontend/eta_board.html)</li><li>[Route Progress Page](frontend/route_progress.html)</li></ul> | <ul><li>[ETA Controller](backend/api/eta.php)</li><li>[Route Progress Engine](backend/helpers/route_progress.php)</li></ul> | <ul><li>[Stops Table](database/stops.sql)</li><li>[Routes Table](database/routes.sql)</li><li>[Timetables Table](database/timetables.sql)</li></ul> |
| 4 | Integration | <ul><li>[Integrated Dashboard Page](frontend/dashboard.html)</li><li>[Live Map and ETA Linking](frontend/live_map.html)</li></ul> | <ul><li>[API Integration Layer](backend/api/index.php)</li><li>[Postman Test Collection](tests/postman_collection.json)</li></ul> | <ul><li>[Unified Database Schema](database/utcompass.sql)</li></ul> |

---

## SUBSYSTEM 3 : RAWAN MOHAMEDSALIH MAGZOB

| Sprint | Module | FrontEnd | BackEnd | Database |
|--------|--------|----------|---------|----------|
| 1 | Passenger Check-in & Pass Verification | - TBD | - TBD | - TBD |
| 2 | Service Disruption & Delay Alerts | - TBD | - TBD | - TBD |
| 3 | Passenger Demand & Usage Analytics | - TBD | - TBD | - TBD |
| 4 | Integration | - TBD | - TBD | - TBD |

---

## SUBSYSTEM 4 : ABU SALEH MD TAHSIN

| Sprint | Module | FrontEnd | BackEnd | Database |
|--------|--------|----------|---------|----------|
| 1 | Parking Lot Monitoring | - TBD | - TBD | - TBD |
| 2 | Space Allocation | - TBD | - TBD | - TBD |
| 3 | Customer Support | - TBD | - TBD | - TBD |
| 4 | Integration | - TBD | - TBD | - TBD |