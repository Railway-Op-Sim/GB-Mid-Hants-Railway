# Mid Hants Railway

## History

The Mid Hants Railway (more commonly known as the Watercress Line), was a 17 mile line in Hampshire, UK, opened on 2nd October 1865 between Alton and Winchester. Initial stations were constructed at Ropley, Alresford and Itchen Abbas, with an additional station at Medstead & Four Marks opening in 1868. The line was single track, with passing loops at each station, however the infrastructure (bridges, tunnels etc) was generally built to allow for the route to be doubled in the future.

Following electrification from London as far as Alton, the line was downgraded to an hourly diesel shuttle between Alton and Southampton. However, it was heavily used for diversions while the South West Main Line was closed between Woking and Winchester for its own electrification. Additionally, the line was used extensively by goods trains, particularly for the locally grown Watercress (from which it gained its name). However, the freight traffic ceased in 1964, and as the passenger service was becoming increasingly financially unviable, the route south from Alton to Winchester eventually closed in 1973.

Following closure, the stretch between Alton and Alresford was gradually reopened in stages between 1977 and 1985, operating today as the Watercress Line Heritage Railway.

## About the RailOS Project

This project is 2 in 1 - the first is a present day simulation of the heritage railway, operating a two train timetable as in 2023. There is also a fictional simulation set in the future, representing what could happen if the line were to reopen completely.

### Fictional Route Notes

- The fictional version represents the line from Farnham, through Alton and Alresford, before joining the current South West Main Line just north of Winchester (which is also included).
- A new station at Kings Worthy, a relatively recent new housing estate near Winchester, has been proposed.
- Some creative liberties have been taken with the route:
  - "Bridge Road" level crossing just south of Alresford has been included - in reality if the route were to ever reopen it is likely that grade separation would be carried out here to avoid the need for a level crossing.
  - Platform 3 at Alton (currently the heritage line platform) has been connected to the line heading north towards Farnham and London - this allows passing moves to take place at Alton, as currently only platform 2 is connected to both the main network and the heritage line.
  - The line speed has been raised to 60mph - currently as a heritage railway trains are only permitted to operate at 25mph, but it has been assumed that this would be changed were the line to reopen fully.
  - It has been assumed that the line would be electrified with the 750V DC third rail system used by the Alton Main Line and South West Main Line, to allow for through running of services.

## Simulation

### Present Day

A two train timetable for summer 2023 has been included. For ease of operation, the trains start and finish in the stations rather than the sidings and shed. The standard service is:

- 6tpd Alton - Alresford

### Fictional Future

The timetable has been designed loosely to fit in with South Western Railway's (SWR) May 2023 timetable. This has a service from Winchester to Bournemouth, which is an ideal candidate to be extended up towards Alton. At Alton itself, two services from London terminate, and a further two services terminate at Farnham having originated from Guildford. With some minor alterations to the calling pattern at Bentley, these two services can be extended from Farnham to Alton, providing 4tph. Theoretically, these could all continue along the Mid Hants Railway, however there are capacity constraints on the South West Main Line, especially with regards to where to turn the trains around. Consideration has also been given to how any new services would interface with Great Western Railway services at Guildford and Fareham, and Southern services at Fareham, although these are not included in the simulation.

The need to fit around existing services was rather restrictive, so the following service pattern has been decided on:

- 2tph London Waterloo to Weymouth (SW)
- 1tph London Waterloo to Portsmouth Harbour via Fareham (SW)
- 1tph London Waterloo to Alton (SW)
- 1tph London Waterloo to Fareham via Alton (SW)
- 1tph Guildford to Alresford (SW)
- 1tph Guildford to Bournemouth (SW)
- 1tph Manchester Piccadilly to Bournemouth (XC)

The London Waterloo to Fareham via Alton service provides an hourly stopping service along the new route, with the Guildford to Alresford and Guildford to Bournemouth both running "express" - calling only at Alresford. Fareham has been chosen as a southern terminus for one of the extended services as it currently has a spare platform that is only used during disruption or engineering works that could be used to turn the train back, and provides a second service each hour to Botley and Hedge End (although not included in this simulation).

The simulation runs from 10:00 until 13:00, with no additional peak services.

## Operational Tips

### Present Day

- Trains passing alternates between Medstead & Four Marks and Ropley - make sure not to route the train too far ahead to block a route.
- The locomotive will detach at each end to run around the coaches.

### Fictional Future

- The train terminating at Alton alternates between using platform 1 (the bay platform), and platforms 2/3. Check the "next service" instruction - if the train continues into Alton South Loops, it should use platform 2 or 3.
- Generally, northbound trains at Alton should use platform 2, while southbound trains use platform 3.
- Be careful not to set the route for trains too far ahead - keep an eye on the passing times at each station so you know where the trains are going to pass.
- Try to ensure the level crossings at Farnham and Alresford are lowered early enough to not disrupt the service, but not too early to incur a penalty on the score.

## Other Documentation

An Excel spreadsheet has been included in the download. This has three tabs as follows:

- "Times": These are the durations it takes a train to run between each station on the new route, used for timetable creation. The "Stopper" times assume stopping at each station, while the "Express" times assume running fast through Kings Worthy, Itchen Abbas, Ropley and Medstead & Four Marks.
- "Line Diagram": A graphical representation of the timetable in use (extended to Aldershot North Jn and Fareham).
- "Timetable": An easier to read version of the timetable between Farnham and Winchester (so only the section included within the simulation).

The line diagram especially should help with determining where trains pass each other, and which order trains cross the junction at Winchester.