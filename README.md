# Showcase
Web GIS mapping for Avocado farmers in Kenya. Leaflet has been used to provide drawing functionalities, Turf Js provides buffering while PostgrSQL + Postgis provides backend support for geospatial data!
Geo Django was then used to develop spatial content and datasets serialization with GeoJSON
[Screenshot from 2022-03-08 21-35-46](https://user-images.githubusercontent.com/42302441/166160429-a3b2fa67-5b13-40d8-91f4-6a0590ff7553.png)

The suitability locations were derived using the Analytical Hierarchial Process (AHP), with four classes computed.

![Screenshot from 2022-03-08 21-35-46](https://user-images.githubusercontent.com/42302441/166160890-11dc29ab-6729-4ea1-91bb-e524f62c79b5.png)


Service area allocation shows the drive times from the center of each polygon ,with 5, 10, and 15 minute drive times.

![SERVICE_Areas](https://user-images.githubusercontent.com/42302441/166160437-1f262367-ccc9-4330-9f75-d43ad132c931.png)

Farmers can also query additional layers from the system, such as temperature data,soils, elevation and slope datasets.
![Screenshot from 2022-03-08 21-34-32](https://user-images.githubusercontent.com/42302441/166160816-271dcbc1-2204-4c77-8275-03ad1b004943.png)

![Screenshot from 2022-03-08 21-35-03](https://user-images.githubusercontent.com/42302441/166160849-54134e08-7d88-4f2c-b2ae-783f7327be1e.png)

![Screenshot from 2022-03-08 21-35-08](https://user-images.githubusercontent.com/42302441/166160853-c5b28906-8c76-4dbd-abcd-3830b652ac27.png)





The system uses OSRM for routing.
![Routing](https://user-images.githubusercontent.com/42302441/166160778-ff7a677f-918e-489d-a247-9db05ec6b2a1.png)

The administrators of the system assist the farmers with the pick-up schedules, farmers can then plan for the pick ups and be available at the right time.
![AddPickUpSchedule](https://user-images.githubusercontent.com/42302441/166160804-a5d5005a-48b5-40e4-ae62-656e251a4c7b.png)

The system also allows farmers to track their harvests in their local accounts, this helps them avoid scamming by brokers.
![TrackHarvest](https://user-images.githubusercontent.com/42302441/166160791-f26f5ce2-71b7-41c9-9432-1cacf7956022.png)

Finally, farmers can also report an incidence, such as malpractice, exploitation by stakeholders, or break out of a disease, this information is used to inform other farmers and notify the stakeholders to take action.

![report_incidence](https://user-images.githubusercontent.com/42302441/166160770-3b548e04-8072-496c-876a-21108e57cc17.png)
