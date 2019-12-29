---
layout: post
title: "Design Sprint: Drone Flight Registry"
date: 2017-03-23
---

In 2016 over 670,000 drones were registered with the federal government, and in early 2017 our household joined them. After paying a $5 registration fee and making three phone calls, our drone was ready for its maiden flight at a park.

But the process of getting to that first flight for new drone owners isn't easy: you have to identify the location you want to fly in and whether or not it is within an airport, helipad or restricted zone, notify the correct authorities in the correct order, and get everyone to approve the flight before it happens. The FAA encourages you register flights 90 days in advance ([source](https://www.faa.gov/uas/request_waiver/media/instructions.pdfhttps://www.faa.gov/uas/request_waiver/media/instructions.pdf)), which really limits the spontaneous Saturday afternoons out flying your drone.

Additionally, the recipients of these flight registrations -- the air traffic control towers, air authorities, helipad managers and others -- need to respond to flight requests in a timely manner, and have access to approved flights that might affect them.

Both of these processes could be made simpler by designing an online flight registration tool that allows registration and viewing of upcoming flights.

The operator starts by identifying the location they want to fly in. The base map lets operators search by location or address, and shows nearby airport exclusion zones.

<img style="max-width:90%;height:auto;border:1px solid black;"
 src="/assets/sprints/drone/operator-start.png"
 title="Search by address">

When an address is entered, the map displays the location as well as any zones that location falls within.

<img style="max-width:90%;height:auto;border:1px solid black;"
 src="/assets/sprints/drone/operator-search-results.png"
 title="Search results">

To correctly identify the flight location, the operator is prompted to outline the area they are intending to fly in.

<img style="max-width:90%;height:auto;border:1px solid black;"
 src="/assets/sprints/drone/operator-select-area.png"
 title="Select flight area on map">

Once they have enclosed an area, they are prompted to register their flight in that area if necessary.

The registration process requires operator contact information and flight details. The flight location is pre-filled and the operator enters their information. This is the information that remains in the FAA database of unmanned aircraft registration, and could be linked to an account allowing operators to add, edit and remove drones from their profile.

<img style="max-width:90%;height:auto;border:1px solid black;"
 src="/assets/sprints/drone/operator-contact.png"
 title="Operator contact information form">

The operator enters flight information next, including a description of the drone they intend to operate.

<img style="max-width:90%;height:auto;border:1px solid black;"
 src="/assets/sprints/drone/flight-information.png"
 title="Flight information form">

The operator then approves a summary of the registration request, and receives a confirmation screen.

<img style="max-width:90%;height:auto;border:1px solid black;"
src="/assets/sprints/drone/flight-summary.png"
title="Flight registration summary">

<img style="max-width:90%;height:auto;border:1px solid black;"
src="/assets/sprints/drone/confirmation.png"
title="Confirmation screen">


At this point, the relevant local authorities are notifed, in this case the Minneapolis-Saint Paul International Airport ATC and the Metro Air Authority. Ideally these agencies would have a set of automatic approval criteria, based on distance, date, time and known special restrictions on flight. This tool would relieve pressure on employees to approve standard flight requests, and create special notifications for unusual requests. It would also create a system where flight requests are handled immediately and operators are notified of approval quickly.

An open registry of flights would allow operators, ATC and other interested parties to view all upcoming flights.

<img style="max-width:90%;height:auto;border:1px solid black;"
src="/assets/sprints/drone/flight-registry.png"
title="Search results">

Flights could be filtered by location to provide relevant information to authorities. ATC and helipad managers would be notified of new flights, and be able to edit the approval status of any flight, adjust their auto-approval settings, and create special restriction events.

By putting this request system online and making the registry open, operators need to perform fewer steps to comply with flight registration regulations. Authorities can respond quickly to flight requests and provide a satisfying and responsive experience to operators while maintaining a high level of compliance.
