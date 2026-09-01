# SGAWPS-SGAIEM
Framework that runs the weather system for the fictional island Marrow Bay created by TechKraziest/



# About TechKraziest (Main Developer and Creator Profile)

TechKraziest is a YouTube creator and Python programmer who develops custom weather simulation frameworks. He is independent and not a member of the traditional EAS Hobbyist community. He specializes in programming mocks of official Advanced Weather Interactive Processing System (AWIPS) programs, including HazServices, Broadcast Message Handler, WarnGen, and HazCollect. He is looking to major in Computer Science, and is hoping to be an IT specialist and software engineer for the National Weather Service and their local offices. Despite his young age of 16, he has created phenomenal expert-like weather systems in the span of 3 years. He used AI in the beginning to better learn python and general programming, and later began taking the knowledge
ChatGPT taught him and used it to create his own significant weather applications that run is weather infrastructure Today.

## Software Frameworks that run the core weather processing system of Marrow Bay.
* **SGAWPS:** Stands for the SGA Weather Processing System. Originally rooted in Suwanee, Georgia, the system framework is currently transitioning its operational jurisdiction to the fictional region of Marrow Bay. Future system upgrades plan to transition the hardcoded station identifier from SGA to MRB. This framework is responsible for providing quick and fast weather models to the forecaster and is the "sender" of the entire database. This framework contains applications such as,
sgawps_tw.exe which is the text workstation that forecasters use to create, edit, and distribute forecast messages such as Warnings, Watches, Advisories, statements, non weather emergency messages, etc. This software is also responsible of hosting
the Broadcast Message Handler client which controls all stations across Marrow Bay. Keep in mind that the station servers are located on each individual computer per station...sgawps_awips.exe which is the client that
forecasters use which loads the geographical data of Marrow Bay, and loads CONUS radar data and storm rotation information, and provides them with the ability to create storm-based polygons and send them to WarnGen, which creates the short term
convective warnings.
* **SGAIEM:** Currently stands for "Suwanee Georgia Iowa Environmental Mesonet." It is slated to be renamed to "Suwanee Georgia Integrated Emergency Manager" in future software builds. This framework is the 'receiving' end of the database. This
software receives messages sent from SGAWPS, and distributes them out to the BMH system, the WwA system, and local officials and the general public. 

## Simulated NOAA Weather Radio Stations (Marrow Bay Jurisdiction)
* **WXK39 (South Atlanta, Marrow Bay):** A simulated NWR transmitter serving the western half of Marrow Bay and adjacent coastal waters. It operates on a frequency of 162.475 MHz using a wireless audio feed.
* **KBB56 (North Miami, Marrow Bay):** A simulated NWR transmitter serving the eastern side of Marrow Bay and adjacent waters. It operates on a frequency of 162.425 MHz using a wireless audio feed.


## BayFrontWX application in development
I am also in development of a significant weather app specifically designed for Marrow Bay, in which you can monitor when there is active weather ongoing in the west central Atlantic...
where Marrow Bay is located. This app will be named BayFrontWX, and will have the capabaility of notifying you whenever I issue critical messages for specific counties of the state,
as if the real NWS was issuing a warning for your area. It will also show you live radar data, and polygon data. It is a really neat software, and I cannot wait to get a public domain out
so you guys can access the app via the web, and hopefully design an app for iPhones and Androids which uses the frame network of this application.


Stay tuned
