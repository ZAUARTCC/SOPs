Chicago O'Hare International Airport (KORD)
===
Standard Operating Procedures
===

##### Disclaimer
The follow are the standard operating procedures for use by Air Traffic Control Specialists at Chicago Midway International Airport on the VATSIM Network. Controllers are required to be familiar with the provisions of these procedures that pertain to their operational responsibilities and to exercise their best judgement if they encounter situations not covered by in this document. 
These procedures and the information within this document are designed for and specifically for use in a virtual controlling environment and **should not be used nor referenced for live operations in the National Airspace System**. The procedures in this document outline how the positions are to be operated and will be the basis for performance evaluations, training, and certification.

### Revisions
Change | Description | Effective Date
:---: | :--- | :---:
2015.1 | Document is first presented for public evaluation | 1/1/2015
2015.2 | Document is presented second time for public evaluation | 3/1/2015
2015.3 | Document is reviewed by Senior Staff | 4/1/2015
2015.4 | 5-5 -- LRAC procedures removed | 1/1/2016
2015.5 | 6-1 --- Added Chapter to define abbreviations | 1/1/2016
2015.6 | Changed ORD8 to ORD9 where used | 1/1/2016
2015.7 | 5-10.1 -- Added BACEN and renamed Petty to PETTY | 1/1/2016
2015.8 | Deleted any strikeouts from previous edits | 1/1/2016
2015.9 | 4-8 and 5-13 -- Added disclaimer of the use of runway 28L/10R | 1/1/2016
2015.10 | 2-2 -- Removed the M from the Metering position to be replaced with R, also in subsequent uses of the position in this document | 1/1/2016
2015.11 | 2-2 -- Added S Ground and Tower and disclaimer of their use, renaming other Ground and Tower positions as needed. Changed N_GND frequency to reflect current | 1/1/2016
2015.12 | Removed any use of runway 32R/14L as the runway is permanently closed. Added departure runway of 32L @ T10 for west flow. Changed 14s A Pair flow to 14R only | 1/1/2016
2016.1 | Chapter pages updated | 7/1/2016
2016.2 | 1-3 -- vERAM included in supported clients | 7/1/2016
2016.3 | Changed ORD9 to ORD1 where used | 7/1/2016
2017.1 | Updated spelling error and nots | 1/1/2017
2017.2 | Updated SID nmbers | 1/1/2017
2017.3 | 2-2 -- South Frequencies Activated for events | 1/1/2017
2017.4 | 4-8 -- Runways updated to reflect 33/15 | 1/1/2017
2017.5 | 4-11 -- Removed, out of date | 1/1/2017
2017.6 | 5-10.1 -- SID Fixes updated | 1/1/2017
2017.7 | Chapter pages updated | 1/1/2017
2017.8 | 5-13 -- Flows updated | 4/16/2017
2017.9 | 4-8 -- Flows updated | 4/16/2017
2018.1 | Change to markdown format | XX/XX/2018


### Chapter 1. General Information
1. General Information
    1. **Purpose of this Document**: This document establishes standard operating procedures for the vZAU Chicago ARTCC of the VATSIM Network, specifically the operations at Chicago O’Hare International Airport. 
    2. **Audience**: All vZAU Chicago ARTCC members and visiting controllers certified or working toward certification to provide ATC services at Chicago O’Hare International Airport. 
    3. **Software Utilization**: vZAU has standardized on the Virtual Radar Client (VRC), vSTARS, and the vERAM software as its operating software of choice. Any references to software in this and other facility documents are written with this software in mind. 
    4. **Global Ratings**: All positions of operation outlined within this document shall be staffed in compliance with [VATSIM Global Ratings Policy (GRP)](https://www.vatsim.net/documents/global-ratings-policy). O’Hare International Airport is designated by the GRP as a MAJOR facility, and all controllers staffing O’Hare positions shall either possess or be in training (certified to be monitored) for the appropriate rating and/or facility endorsements. 
    5. **Emergencies**: Controllers shall reference the [VATSIM Code of Conduct](https://www.vatsim.net/documents/code-of-conduct) and [Code of Regulations](https://www.vatsim.net/documents/code-of-regulations) policies regarding emergencies at all times, and have the right to request the termination of an emergency should it interfere with operations. Non-compliant pilots should be referred to a VATSIM Supervisor by utilizing the `.WALLOP` command on the radar client software. 
    6. **Updates**: This SOP is to be reviewed and, if necessary, updated every six months to remain as current as possible. Senior Staff will convene during the months of June and December to release any necessary updates effective each July and January. 
    7. **Chicago O'Hare Tower Airspace**: O’Hare Tower Airspace is depicted below and generally includes the airspace from the surface up to and including 5,000 feet within the 6NM ring of the Chicago Class Bravo Airspace from the 345 radial from the ORD VOR, counter-clockwise to the 090 radial, and the 5NM ring of the Chicago Class Bravo Airspace from the 090 radial of the ORD VOR, counter-clockwise to the 345 radial. From the 285 radial of the ORD VOR counter-clockwise to the 245 radial, the O’Hare Tower airspace follows I-290, which at its smallest radius is equal to 5.5NM. Specific airspace designations can be found in the Local Control procedures of this document and they will depict airspace altitude restrictions based on arrival and departure areas of the airspace.
![O'Hare Tower Airspace Diagram](https://i.gyazo.com/69a8129a874311eaf44cb732b25a17ae.png)
    8. **Transfer-of-control point for KORD arrivals**: Transfer of control to O’Hare Local Control for arrivals takes place for ILS Approaches at the Final Approach Fix and for visual approaches at the point the aircraft on final crosses the Tower airspace lateral boundary. 


### Chapter 2. ORD Positions Universal Standard Operating Procedures
2. ORD Positions Universal Standard Operating Procedures
    1. **General**: O’Hare International Airport is vZAU’s primary Class Bravo airport, and the only GRP-designated Major
facility within the ARTCC. 
        1. Controllers staffing Clearance Delivery or Ground Control positions at ORD shall hold at least a Ground Controller (S1) rating, along with an ORD Delivery or ORD Ground major endorsement rating, or shall be in training for such having been cleared to be monitored on the position. 
        2. Controllers staffing O’Hare Local Control positions at ORD shall hold at least a Tower Controller (S2) rating, along with an ORD Tower major endorsement rating, or shall be in training for such having been cleared to be monitored on the position. 
    2. **Communications**: Controllers operating positions at O’Hare International Airport shall utilize the following radar client frequencies and voice channels. The default voice server shall be: rw.liveatc.net. To streamline coordination with other vZAU controllers, voice channels shall be configured exactly as follows: 

        Position Name | Frequency | Callsign | Voice Channel
        :---: | :---: | :---: | :---:
        O'Hare ATIS | 135.400 | KORD_ ATIS | -
        **Clearance Delivery** | **121.600** | **ORD_O_DEL / ORD_O1_DEL** | **ord_o_del**
        Ground Metering Control | 121.670 | ORD_R_GND / ORD_R1_GND | ord_r_gnd
        Ground Control North | 124.120 | ORD_N_GND / ORD_N1_GND | ord_n_gnd
        **Ground Control Inbound** | ***121.900** | **ORD_I_GND / ORD_I1_GND** | **ord_i_gnd**
        Ground Control Outbound | 121.750 | ORD_O_GND / ORD_O1_GND | ord_o_gnd
        Ground Control South | 118.050 | ORD_S_GND / ORD_S1_GND | ord_s_gnd
        Local Control North | 128.150 | ORD_N_TWR / ORD_NN_TWR | ord_n_twr
        **Local Control North Central** | **126.900** | **ORD_NC_TWR / ORD_N1_TWR** | **ord_nc_twr**
        Local Control South Centeral | 120.750 | ORD_SC_TWR / ORD_S1_TWR | ord_sc_twr
        Local Control South | 133.000 | ORD_S_TWR / ORD_SS_TWR | ord_s_twr
        >NOTE -- Bolded entries in the table above indicate the primary combined frequency to be connected first
        
        1. Every controller shall utilize a primary frequency in their ATC client program for communications with aircraft. Every controller is encouraged to use voice as the primary method of communication with aircraft per VATSIM regulations. However, aircraft utilizing non-voice communications (text or receive only) will never be denied ATC services, nor will controllers executing text or receive only commands be denied the ability to control. Controllers shall use text as they are able to clarify instructions and/or when instructed by an aircraft. 
        2. Every ORD position will maintain a standard and common position ATIS. VRC’s Controller Info dialog automates many of these elements of a standard position ATIS. The position ATIS will include the following elements at minimum:
            ```
            Position
            Current ATIS Letter ID
            Active Runways 
            ```
        3. Voice ATIS. Local Control shall be responsible for keeping an updated voice ATIS with all necessary information pertaining to operations at KORD. During split operations, voice ATIS shall be the responsibility of the Local Control Central unless otherwise coordinated. The ATIS should also be recorded with the voice server as rw.liveatc.net with a frequency of 135.400. Sample KORD voice ATIS templates can be found below.
            1. O’Hare Airport Information (code), (time of wx observation) Zulu, (weather sequence – wind,
vis, precip/phenomena, clouds, temp, dewpoint, altimeter)
            2. Arrivals expect vectors (choose one: ILS, Visual) Runway (#) approach
            3. Departures expect runways (#, #, #)
            4. Notices to Airmen: PIREP; Closures; Birds; Noise abatement, MU readings; Wind shear;
SIGMET; HIWAS; Braking action; SWAP (as necessary)
            5. For Clearance Delivery contact (position name) on frequency (frequency)
            6. VFR aircraft say direction of flight, aircraft type and requested altitude
            7. Pilots readback all runway hold short and taxi instructions 
            8. Advise on initial contact you have information (code) 
                >NOTE -- When KORD is landing converging runways or simultaneous approaches, place a message in the voice ATIS advising of converging operations to converging runways in use and/or that simultaneous approaches are in use. Also, when LAHSO operations are in effect, place an appropriate message in the voice ATIS. 
            
                >NOTE -- Prior to broadcasting, review the pending ATIS to ensure accuracy and inform pilots via voice and text of the update information code being broadcast. 
            
                >NOTE -- Due to the many runway designation changes at O’Hare and the unavailability of current scenery on the network, please consider using the following transmission in your ATIS to avoid runway designation challenges, `“AIRPORT RUNWAY AND TAXIWAY DESIGNATIONS HAVE CHANGED. PLEASE REVIEW CURRENT CHARTS AND USE THE RUNWAY AND TAXI INSTRUCTIONS YOU ARE ASSIGNED.”`


### Chapter 3. ORD Clearance Delivery
3. ORD Clearance Delivery
    1. **Positions**: O'Hare Clearance Delivery (ORD_O_DEL -- 121.600).
    2. **IFR Operations**: Every aircraft departing ORD airport under an IFR flight plan shall be issued a Standard Instrument Departure (SID). 
        1.  Clearance Delivery shall ensure that flight plans are amended to include an assigned SID in the filed flight plan if it does not originally include one. Should a pilot not have SID procedures available to them, coordination with higher controllers must take place as to agree on the best possible route. 
            > NOTE -- Clearance Delivery is not authorized to grant “direct-to” clearances. Should a pilot request a direct-to clearance, the clearance may include verbiage to “expect” clearance direct-to a clearance limit. Coordination with C90 TRACON and Chicago Center, if online, prior to issuing a direct-to clearance. 

            > EXAMPLE -- `“United 501, O’Hare Delivery, cleared to LaGuardia airport via the O’Hare# departure, expect vectors direct to LaGuardia…”`

        2. The ORD# Departure is the only departure procedure at O’Hare and is a radar vectored departure. This type of SID allows controllers to vector aircraft toward virtually every primary airway navaid in the regional vicinity of ORD to initiate an IFR routing. 
        3. Clearance Delivery shall ensure that appropriate altitudes for direction of flight are filed in the flight plan, as well as given in the clearance. Direction of flight shall be based upon the on-course heading of the flight. Initial departure headings after takeoff shall not be considered direction of flight for purposes of altitude clearance assignment. Clearance Delivery shall ensure that appropriate altitude restrictions listed in LOAs with adjacent ARTCCs are complied with.
        4. Clearance Delivery shall issue initial altitudes of 5,000ft for all aircraft filed at or above 5,000ft. For aircraft filed less than 5,000ft, an initial altitude of the filed cruising altitude shall be used. 
            >NOTE -- If no Departure or Center controller is online, aircraft may be cleared directly to their cruise altitude with no initial altitude required in their clearance. 
        
        5. When clearing an aircraft to their altitude, your transmission shall consist of `“Climb via SID, top altitude 5,000.”`
        6. If C90 needs to change the initial altitude for some reason due to traffic or weather, your transmission can be modified to: `“MAINTAIN XX,XXXft.”` 
        7. If an aircraft is cleared to a destination that does not include the ORD1ORD2 (if destination is within C90, or if pilot is granted a special clearance) the “CLIMB VIA SID” phraseology is not required, and the controller shall simply say `“MAINTAIN XX,XXX, EXPECT FLXXX 10 MINUTES AFTER DEPARTURE”` or cruise altitude. 
    3. **VFR Operations**: Clearance Delivery shall authorize requests to operate within the Chicago Class Bravo Airspace and obtain aircraft identification, type, direction of flight/destination and requested altitude prior to taxi or as soon as practical. 
        1. Aircraft requesting VFR clearance to leave the Class Bravo Airspace, without additional flight following, shall be issued an altitude at or below 1,800ft and pointed out to the appropriate C90 controller prior to giving the aircraft clearance. Aircraft should be assigned a transponder code from `5101-5177` block.
        2. VFR aircraft requesting flight following within C90 airspace shall be issued an initial altitude at or below 1,800 and pointed out to the appropriate C90 position. 
        3. Local Control shall assign the initial direction of flight prior to takeoff, the same as IFR aircraft, that follows the NEODD SWEVEN rule when cruise altitude is above 3,000ft. 
    4. **Universal Duties**: Issue ATC Clearances for IFR and VFR aircraft and perform appropriate flight data strip marking (VRC users only). 
        1. When a clearance is issued, only then is a squawk code to be assigned. Controllers monitoring their departure list will know an aircraft has received clearance when an assigned squawk code appears next to their callsign. 
        2. Question each non-US carrier heavy departure to verify their ability to comply with the climb restriction in the current DP. 
    5. **Landing at Airports Within C90**: Aircraft filed to an airport within C90 airspace shall be assigned no higher than 5,000 feet as their final cruise altitude NEODD SWEVEN applies to all cruise altitudes above 3,000ft.
    6. **Runway Assignement**: Clearance Delivery is not responsible for assigning runways to outbound aircraft. If an aircraft requests a runway assignment, the controller is required to transfer the aircraft to Ground Control or the next highest controller for such assignment. If there is no other controller online, Clearance Delivery may suggest a runway based on current weather conditions. 
        >EXAMPLE -- `“American 923, no other ATC is available at this time, winds are 270 at 10, suggested departure runways are 27L or 28R, monitor UNICOM on 122.80.”`


### Chapter 4. ORD Ground Control
4. ORD Ground Control
    1. **Positions**:  
    O’Hare Ground Metering ORD_R_GND – 121.670)  
    O’Hare Ground Control North (ORD_N_GND –124.120).  
    O’Hare Ground Control Inbound (ORD_I_GND – 121.900).  
    O’Hare Ground Control Outbound (ORD_O_GND – 121.750).  
    O’Hare Ground Control South (ORD_S_GND – 118.050).  
    2. **Order of Positions During Split Operations**: During high traffic times, the ground positions may be split as necessary due to traffic demands and ATC preference. 
    3. **Responsibilities During Split Operations**: 
        1. O’Hare Ground Control North shall be responsible for all taxi operations conducted north of runway 27L/9R. O’Hare Ground Control South shall be responsible for all taxi operations conducted south of runway 28C/10C. 
        2. O’Hare Ground Control Inbound shall be responsible for aircraft taxiing to a parking area either from a runway or another parking area south of runway 27L/9R. Taxi diagrams can be found in Section 4-11. When transitioning aircraft between Alpha and Bravo taxiways surrounding the main terminal. Aircraft transitioning toward the center, or inbound, shall use even numbered Alpha taxiways while aircraft transitioning out from the center or outbound, shall use odd numbered taxiways. Think IE, Inbound Even and OO, Outbound Odd.
        3. O’Hare Ground Control Outbound shall be responsible for aircraft taxiing to a runway for departure from any point on the airport south of runway 27L/9R. Taxi diagrams can be found in Section 4-11. When transitioning aircraft between Alpha and Bravo taxiways surrounding the main terminal. Aircraft transitioning toward the center, or inbound, shall use even numbered Alpha taxiways while aircraft transitioning out from the center or outbound, shall use odd numbered taxiways. Think IE, Inbound Even and OO, Outbound Odd. 
        4. O’Hare Ground Metering shall be responsible for aircraft prior to leaving ramp areas after receiving clearance from Clearance Delivery. Metering will issue take off times, delays, and ground stops to aircraft. Metering will provide push back approval and taxi approval to aircraft located in the main terminal and international terminal only within the non-movement area and will transfer communications of those aircraft directly to Outbound Ground immediately afterward. For aircraft at other ramps, they will provide push back approval and then be sent directly to Outbound or North Ground depending on their location. Metering should only be considered as a position during high traffic departure events where separation between departures will be necessary. Coordination with outbound ground is necessary to determine the delay or take of time assigned to an aircraft. Take off time should be provided to an aircraft prior to pushback approval in the event aircraft wish to remain at the gate in major delays. 
    4. **ASDE-X Surveillance System**: O’Hare International Airport is equipped with ASDE-X Surveillance Equipment to aid in the monitoring of ground movements. In accordance with ASDE-X operations, ORD controllers shall place a message in the voice ATIS advising all aircraft to taxi with their transponder and altitude encoding on. If a voice ATIS is not operational, Ground Control should request the pilot turn their transponder to Mode C upon initial contact. 
        >NOTE -- Pilot participation in the simulation of ASDE-X Surveillance equipment is encouraged to enhance realism, but not required. In accordance with [VATSIM Code of Regulations](https://www.vatsim.net/documents/code-of-regulations), controllers shall not deny services to aircraft unable or unwilling to operate with Mode C on during ground movement operations. 

    5. **Airport Movement Area**: The Airport Movement Area of O’Hare Airport is all runways, taxiways, and other areas which are utilized for taxiing/hover-taxiing, air taxiing, takeoff, and landing of aircraft, exclusive of loading ramps and parking areas. 
    6. **Ground Movement Operations**: Ground Controllers should reference the taxi diagrams in Section 4-11 to determine the route necessary for inbound and outbound aircraft. 
        1. Maintain awareness of aircraft exiting runway 27L/9R as their exiting from the runway may interfere with an aircraft taxiing to that runway. Taxiway Hotel will always be operating as a one-way taxiway in all split operations depending on the runways in use. The direction of Taxiway Hotel can also be found in Section 4-11. In some flows, the direction of Hotel can be coordinated between the ground positions. 
    7. **Controller Coordination**: Ground Control North should be familiar with the direction of Taxiway Hotel in the event an arriving aircraft is taxiing to a gate. The controller should ensure that if Taxiway Hotel is running eastbound and an aircraft is approaching from Mike and going to Concourse C that the aircraft will need to circle the terminal area by turning left on Hotel rather than right. In this situation, west parking aircraft should be taxied via Echo, Golf, or Tango. The same is true when Hotel is running westbound. 
        1. Aircraft on taxiways Alpha and Bravo will always have the right of way over aircraft transitioning or turning onto those taxiways. This includes transition from Bravo to Alpha or Alpha to Bravo utilizing odd Alphas for outbound from the center and Even Alphas for inbound toward the center. 
        2. Ground Control should be familiar with and utilize taxi diagrams appropriate for the runways in use. Using these diagrams is essential in preventing inbound and outbound aircraft from any head-on situations while on their appropriate frequency. 
    8. **Runway Assignment** (Arrival runways are available in 5-13): Runways should be assigned to aircraft based on their vectored waypoint on the ORD# Departure or direction of flight if VFR. Runways should be assigned based on the runway assignment procedures below: 
        1.  
    
        Flow | Wind | Runways
        :---: | :---: | :---:
        West | Winds 140-170 < 5kts | 22L, 28R, 33@T20
        ||Winds 180-360 < 19kts | 22L, 28R, 33@T10
        || Winds 010-040 < 5kts | 22L, 28R, 33@T10
        || Winds 230-340 > 20kts | 22L, 28R, 33@T10
        ||
        East | Winds 010-040 between 5-19kts | 4L, 9R, 10L
        || Winds 050-130 < 19kts | 4L, 9R, 10L
        || Winds 140-170 between 5-19kts | 4L, 9R, 10L
        || Winds 050-150 > 20kts | 4L, 9R, 10L
        ||
        4's A Pair | Winds 340-040 > 20kts | 4L, 9R, 10L
        ||
        22's A Pair | Winds 210-220 > 20kts | 22L, 28R
        ||
        15 Only | Winds 160-200 > 20kts | 10L OR 28R*
        >NOTE -- * Only one runway may be used. Either 10L or 28R, not both.
        
        >NOTE -- Runway 33 is only authorized as a departure runway from the T10 intersection.
        
        >NOTE -- Intersection departures are authorized. Take off distance available must be given to pilots  
            when assigning the runway unless the distance is available in the ATIS.  
            10L at DD - 10,093 ft. available.  
            28R at EE - 10,100 ft. available.  
            33 at T10 - 8,800 ft. available
    
    9. **Taxiway Restrictions**: For the purposes of flight simulation, any aircraft can operate on any taxiway on the airfield unless the pilot requests use of or diversion from a specific taxiway. The taxi charts shown at the end of this chapter highlight the preferred taxi routing from gate to runway and vice versa. The only restrictions placed on taxiways can be found in the main terminal area concerning taxiways Alpha, Bravo and those taxiways that connect the two. 
        1. Alpha and Bravo will always operate in opposing directions. Alpha will always run clockwise and Bravo counterclockwise. Taxiway Hotel between taxiways Bravo and Uniform will operate in the same direction as taxiway Bravo. 
        2. All odd numbered Alpha taxiways will be used for aircraft transition from the center of the terminal area outward toward Bravo. These taxiways include: A1, A5, A7, A9, A11, A13, A15, A19, and A21. Regardless if the aircraft is a departure or arrival, if they need to transition from Alpha to or past Bravo, they must use odd alpha taxiways. 
        3. All even numbered Alpha taxiways will be used for aircraft transition from the outside of the terminal area inward toward the center. These taxiways include: A2, A4, A6, A8, A10, A12, A14, A16, A18, and A20. Regardless if the aircraft is a departure or arrival, if they need to transition from Bravo to or past Alpha, they must use even alpha taxiways. 
        4. Between taxiways Bravo and Alpha, the direction of taxiways Echo and Foxtrot will always be designated as inbound taxiways (toward the center) but can be coordinated between inbound and outbound ground for special circumstances.
    10. **Runway Crossing Procedures**: Unless a runway is coordinated between Local and Ground control to be inactive or closed, Ground Control is required to have aircraft hold short of any runway to be crossed along its path to runway or gate until Local clears that aircraft to cross the runway. In some situations, Local control may require communications be transferred to them for this clearance. However, in most cases, Ground and Local Control can work out runway crossings via text or TeamSpeak coordination.
        >NOTE -- **No aircraft should receive more than one runway crossing clearance at a time.**

    11. **OLD Taxiway Diagrams**: Some pilots may not have updated scenery. The following diagrams can be used to understand what taxiways and runways are visible to them.
    ![Default Flight Simulator Scenery](https://i.gyazo.com/4b78512eb83964b2d853d94f4233c6c2.png)  
    ![FS Dream Team Payware Scenery](https://i.gyazo.com/4e0406f833a77325a62e983b53ba2bfd.png)


### ORD Local Control
5. ORD Local Control
    1. **Positions**:  
    O’Hare Local Control North (ORD_N_TWR – 128.150).  
    O’Hare Local Control North Central (ORD_NC_TWR – 126.900).  
    O’Hare Local Control South Central (ORD_SC_TWR – 120.750).  
    O’Hare Local Control South (ORD_S_TWR – 133.000).  
    2. **Order of Positions During Split Operations**: During high traffic times, the local positions may be split as necessary due to traffic demands and ATC preference. 
    3. **Responsibilities During Split Operations**: 
        1. When two Local Controls are online, NC will be responsible for runways 27L/27R, and 4R and their respective opposites. SC will be responsible for the remaining runways. 
        2. When three Local Controls are online, N will be responsible for 27R/9L only. NC will be responsible for 27L, and 4R and their respective opposites. SC will be responsible for the remaining runways. 
        3. When four Local Controls are online, N will be responsible for 27R/9L only. NC will be responsible for 27L, and 4R and their respective opposites. SC will be responsible for 32L 33, 28R, and 28C and their respective opposites. S will be responsible for 28L/10R only. 
    4. **ASDE-X Surveillance System**: O’Hare International Airport is equipped with ASDE-X Surveillance Equipment to aid in the monitoring of ground movements. In accordance with ASDE-X operations, ORD controllers shall place a message in the voice ATIS advising all aircraft to taxi with their transponder and altitude encoding on. If a voice ATIS is not operational, Local Control should request the pilot turn their transponder to Mode C upon initial contact. 
        >NOTE -- Pilot participation in the simulation of ASDE-X Surveillance equipment is encouraged to enhance realism, but not required. In accordance with [VATSIM Code of Regulations](https://www.vatsim.net/documents/code-of-regulations), controllers shall not deny services to aircraft unable or unwilling to operate with Mode C on during ground movement operations. 

    5. **Active Runways**: All runways are to be considered active unless Local Control specifically indicates that they are inactive or closed. 
    6. **Braking Action Reports**: All reports of poor to nil braking can be immediately recorded in an updated voice or text ATIS so that future operations can be coordinated. Local Control can issue braking reports as received from pilots, until a new ATIS has been broadcast, when a poor to nil braking report has been issued. 
    7. **Taxiway Restrictions**: When conditions warrant the use of 4R for arrivals, aircraft will be expected to roll to the end of the runway, not utilizing taxiways that will require them to cross runways 28C/R. 
    8. **O'Hare Tower Airspace**: In accordance with Chicago Approach Control (C90), C90 delegates to ORD ATCT the airspace within the Chicago Class Bravo surface area:
        1. From the surface up to and including 4,000 feet MSL in the arrival area (shaded areas), and from the surface up to and including 5,000 feet MSL in the departure area (non-shaded areas), according to the arrival configuration in use as depicted in Figures 1-5 below:
        ![West Flow ATCT Airspace Delegation](https://i.gyazo.com/4987a023c3e27b876dc314a09a5c2802.png)
        ![East Flow ATCT Airspace Delegation](https://i.gyazo.com/f7b74e72e2cabb2e6762cb8a2b53a048.png)
        ![Parallel 4's ATCT Airspace Delegation](https://i.gyazo.com/5dfc7ff4df65e41a889cc303f321c05c.png)
        ![Parallel 22's ATCT Airspace Delegation](https://i.gyazo.com/0f8ebd1fe4655d513688427a96bc770d.png)
        ![15 Only ATCT Airspace Delegation](https://i.gyazo.com/913d3de7f23c8bd44ffaabc9632f2da0.png)  
        
        2. C90 can turn departures/missed approaches adjacent to the arrival/descent area at or above 2,500ft MSL with respect to other arrivals and/or missed approaches. C90 can climb missed approaches on the localizer to 4,000 feet, and transfer communications to the tower once coordination is confirmed. 
        3. ORD ATCT is authorized to provide visual separation between arrivals, departures and arrivals/departures under the control of ORD ATCT as well as C90. Ensure weather conditions to not obscure visibility prior to the application of visual separation. 
    10. **Departure Procedures**: All IFR aircraft that are filed at 5,000 or above are expected to maintain 5,000 feet as their initial altitude. For IFR aircraft with final altitudes lower than 5,000, verbal coordination is required. VFR Aircraft are to climb to an initial altitude 1,800 MSL but are not permitted higher than 4,500 MSL if further climb instructions are given prior to leaving the boundaries of the Local airspace.
        1. IFR aircraft departing on the ORD# departure should be assigned one of the follow scratchpad entries prior to departure based on their initial waypoint:
        
            Waypoint | Scratchpad Entry || Waypoint | Scratchpad Entry
            :---: | :---: | :---: | :---: | :---:
            ACITO | ACI || Keeler | ELX
            BACEN | BAC || MOBLE | MOB
            Badger | BAE || MYKIE | MYK
            CMSKY | CMS || NONNY | NOO
            DENNT| DEN || OLINN | OLI
            DUFEE | DUF || PEKUE | PEK
            DPA093 Radial | DPA || PETTY | PET
            EARND | EAR || PMPKN | PMP
            EBAKE | EBA || Polo | PLL
            Gipper | GIJ || RAYNR || RAY
            Iowa City | IOW || SIMMN | SIM
    
        2. VRC Users should provide C90 with a flight progress strip at the time of departure and prior to the aircraft leaving ORD ATCT airspace. 
    11. **Arrival Procedures**: Unless otherwise coordinated, arrival aircraft shall be transferred to the appropriate Local Control frequency no later than the Outer Marker/fix of the ILS final approach course of the FAF on a non-precision approach. 
        1. All missed approaches, if not using published procedures, should be assigned 4,000 feet and issued headings according to the arrival area in use. 
        2. When simultaneous ILS approaches are in progress, arrivals shall be instructed to monitor the appropriate Local Control frequency when they are within 10 miles of the airport. Separation may be reduced to 2.5NM between aircraft established on the final approach course, when within 10NM of the airport unless the leading aircraft is in a higher weight class than the following aircraft. 
        3. In lieu of verbal coordination, during ILS approaches, C90 will use scratchpad entries beginning with “V” to indicate a visual approach. 
        4. ORD shall be responsible for longitudinal separation of aircraft inside the outer marker/fix. If this is not possible, alert C90 as soon as possible. This separation is required for all runways or no runways. C90 will not further anticipate this separation for individual runways. 
        5. C90 will initiate a radar handoff of aircraft approximately 10nm from the airport when established on a final approach course and no closer than 1nm from the tower airspace boundary. C90 will not issue a communication handoff until Local control accepts the radar handoff. 
    12. **Special Operations**: Radar separation of helicopters must be established to provide radar services. Radar service must be terminated upon the aircraft leaving the Class Bravo airspace. Flight along any approved route shall be confined to within 1/4 mile from the centerline of the designated route. No helicopter may hover within the Class Bravo airspace without specific approval from ORD ATCT. The helicopter routing chart is provided below in Figure 7:
        ![Helicoper Routing Chart](https://i.gyazo.com/420a87bd03cb63354ea051d703dd4df1.png)
    13. **Runway Configuration and Initial Headings**: The following runway configurations display only the maximum number of runways to be utilized for arrivals/departures. At any point in time, Local Control may choose to limit the number of runways utilized for a configuration as long as runway 28R/10L always remains active. Runway 28L/10R will not be officially utilized until a confirmed scenery is publicly available and the runway can be used by pilots on the network.
    
        Flow | Winds | Departure Runway | Heading
        :---: | :---: | :---: | :---:
        West | Winds 140-170 < 5kts | 22L | 120
        ||| 28R | RWY, 180, 360
        ||| 33@T10 | 290, 010
        || Winds 180-360 < 19kts | 22L | 120
        ||| 28R | RWY, 180, 360
        ||| 33@T10 | 290, 010
        || Winds 010-040 < 5kts | 22L | 120
        ||| 28R | RWY, 180, 360
        ||| 33@T10 | 290, 010
        ||
        East | Winds 010-040 between 5-19kts | 4L | 010
        ||| 9R | RWY
        ||| 10L | 180
        || Winds 050-130 < 19kts | 4L | 010
        ||| 9R | RWY
        || 10L | 180
        || Winds 140-170 between 5-19kts | 4L | 010
        ||| 9R | RWY
        ||| 10L | 180
        || Winds 050-150 > 20kts | 4L 010
        ||| 9R | RWY
        ||| 10L | 180
        ||
        4's A Pair | Winds 340-040 > 20kts | 4L | 010
        ||| 9R | RWY
        ||| 10L | 180
        ||
        22's A Pair | Winds 210-220 > 20kts | 22L | 120
        ||| 28R | RWY
        ||
        15 Only | Winds 160-200 > 20kts | 10L | RWY
        |||OR*
        ||| 28R | RWY
        >NOTE -- * Only one runway may be used. Either 10L or 28R, not both.
        
        >NOTE -- Runway 33 is only authorized as a departure runway from the T10 intersection.
        
        >NOTE -- Intersection departures are authorized. Take off distance available must be given to pilots when assigning the runway unless the distance is available in the ATIS.
        10L at DD - 10,093 ft. available
        28R at EE - 10,100 ft. available
        33 at T10 - 8,800 ft. available  
          
        Flow | Winds | Arrival Runway
        :---: | :---: | :---:
        West | Winds 140-170 < 5kts | 27R, 27L, 28R, 28C, 28L
        || Winds 180-360 < 19kts | "
        || Winds 010-040 < 5kts | "
        || Winds 230-340 > 20kts | "
        ||
        East | Winds 010-040 between 5-19 kts | 9L, 9R, 10L, 10C, 10R
        || Winds 050-130 < 19kts | "
        || Winds 140-170 between 5-19kts | "
        || Winds 050-150 > 20kts | "
        ||
        4's A Pair | Winds 340-040 > 20kts | 4R, 4L, 10L
        ||
        22's A Pair | Winds 210-220 > 20kts | 22R, 22L, 28R
        || 
        15 Only | Winds 160-200 > 20kts | 15, 10L*, 28R*
        
        >NOTE -- * Runway 10L only authorized when wind is between 140-180 only. 
        >NOTE -- * Runway 28R only authorized when wind is between 190-200 only.


### Chapter 6. Glossary of Terms

Term | Definition
--- | ---
AGL | Above Ground Level. This measurement changes as the topography of the earth changes.
ARTCC | Air Route Traffic Control Center
ASDE-X | Airport Surface Detection Equipment, model X, a runway safety tool that enables controllers to detect potential runway conflicts by providing coverage of movement of aircraft on runways and taxiways. 
ATCT | Air Traffic Control Tower. Another name for the cab.
ATIS | Automatic Terminal Information System, provided by airports with towers utilized on a frequency that gives weather and airport information to pilots.
C90 | The FAA designation for the Chicago TRACON. The TRACON airspace in which KORD operates.
DEL | The VATSIM designation of a Clearance Delivery position.
ES | Euroscope, one of the radar clients supported by our facility.
FAF | Final Approach Fix.
GND | The VATSIM designation of a Ground position.
GRP | The [VATSIM Global Ratings Policy](https://www.vatsim.net/documents/global-ratings-policy), a document governing the training and promotion of controllers to be used throughout the Network.
HIWAS | Hazardous Inflight Weather Advisory Service. A continuous broadcast of inflight weather advisories. 
IFR | Instrument Flight Rules.
ILS | Instrument Landing System, a primary method of instrument approaches. A precision approach providing both lateral and vertical guidance to the runway
LAHSO | Land and Hold Short of, for when an aircraft lands and must stop prior to a certain runway or taxiway intersection.
LOA | Letter(s) of Agreement. A set of Standard Operating procedures to be used by neighboring facilities to speed up the communication process between facilities.
LOCAL | Another name for a Tower controller.
MSL | Mean Sea Level. Serves as a reference point for elevations; calculated based on observations of tides and seasonal variations over a 19-year period.
MU | Greek term meaning the co-efficient of friction. Used for braking action reports.
NEODD SWEVEN | North, East: Odd; South, West: Even. A method of determine the cruising altitude of an aircraft based on direction of flight. 
PIREP | A pilot report of actual weather conditions encountered by an aircraft in flight.
SID | Standard Instrument Departure.
SIGMET | Significant Meteorological Information. A weather advisory that contains meteorological information concerning the safety of all aircraft. 
SOP | Standard Operating Procedure(s).
SWAP | Severe Weather Avoidance Program. A formalized program that is developed for areas susceptible to disruption in air traffic flows, caused by thunderstorms. 
TRACON | Terminal Radar Approach Control.
TWR | The VATSIM designation of a Tower Position
vERAM | [vERAM](http://veram.metacraft.com/) is an air traffic control radar simulation program for use on the VATSIM network. It is a high-fidelity simulation of the real ATC system used in many enroute control facilities in the United States.
VFR | Visual Flight Rules
VRC | [Virtual Radar Client](http://www1.metacraft.com/VRC/), one of the radar clients supported by our facility. The most popular client in the United States.
vSTARS | [vSTARS](http://vstars.metacraft.com/) is an air traffic control radar simulation program for use on the VATSIM network. It is a high-fidelity simulation of the real ATC system used in many approach control facilities in the United States.
vZAU | ZAU is the designator for the Chicago ARTCC facility. *v* is used to designate a virtual environment. *Z* is assigned to each facility in the United States, and *AU* represents the town of Aurora where the facility is physically located.

---
Signed,  
/s/  
Jakob Kruse  
Air Traffic Manager  
vZAU Chicago ARTCC  

Signed,  
/s/  
XX XXX  
Deputy Air Traffic Manager  
vZAU Chicago ARTCC  

Signed,  
/s/  
XXX XXXX  
Training Administrator  
vZAU Chicago ARTCC  