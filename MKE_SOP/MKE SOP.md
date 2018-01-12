MKE TRACON 
===
General Mitchell International Airport (KMKE), MKE TRACON Satellite Airports
===
Standard Operating Procedures
===
##### Disclaimer
The follow are the standard operating procedures for use by Air Traffic Control Specialists at the Milwaukee TRACON, General Mitchell International Airport, and MKE TRACON satellite airports on the VATSIM Network. Controllers are required to be familiar with the provisions of these procedures that pertain to their operational responsibilities and to exercise their best judgement if they encounter situations not covered by in this document. 
These procedures and the information within this document are designed for and specifically for use in a virtual controlling environment and **should not be used nor referenced for live operations in the National Airspace System**. The procedures in this document outline how the positions are to be operated and will be the basis for performance evaluations, training, and certification.

### Revisions
Change | Description | Effective Date
:---: | :---: | :---:
2017.1 | Document is reviewed by Senior Staff | 12/21/2017
2017.2 | Document is approved by Senior Staff | 12/27/2017
2017.3 | Document is posted | 12/27/2017
2018.1 | Document is converted to markdown | XX/XX/2018


### Chapter 1. General Information
1. General Information
    1. **Purpose of this Document**: This document establishes standard operating procedures for the vZAU Chicago ARTCC of the VATSIM Network, specifically the operations at the Milwaukee TRACON, General Mitchell International Airport and MKE TRACON Satellite airports. 
    2. **Audience**: All vZAU Chicago ARTCC members and visiting controllers certified or working toward certification to provide ATC services at the Milwaukee TRACON, General Mitchell International Airport and MKE TRACON Satellite airports. 
    3. **Software Utilization**: vZAU has standardized on the Virtual Radar Client (VRC), vSTARS, and the vERAM software as its operating software of choice. Any references to software in this and other facility documents are written with this software in mind. 
    4. **Global Ratings**: All positions of operation outlined within this document shall be staffed in compliance with [VATSIM Global Ratings Policy (GRP)](https://www.vatsim.net/documents/global-ratings-policy). Milwaukee TRACON, General Mitchell International Airport and MKE TRACON Satellite airports are designated by the GRP as a MINOR facility, and all controllers staffing Milwaukee TRACON, General Mitchell International Airport and MKE TRACON Satellite airports positions are only required to possess the appropriate VATSIM rating necessary to work a Ground, Tower or Approach/Departure position. Special endorsements are not required. 
    5. **Emergencies**: Controllers shall reference the [VATSIM Code of Conduct](https://www.vatsim.net/documents/code-of-conduct) and [Code of Regulations](https://www.vatsim.net/documents/code-of-regulations) policies regarding emergencies at all times, and have the right to request the termination of an emergency should it interfere with operations. Non-compliant pilots should be referred to a VATSIM Supervisor by utilizing the `.WALLOP` command on the radar client software. 
    6. **Updates**: This SOP is to be reviewed and, if necessary, updated every six months to remain as current as possible. Senior Staff will convene during the months of June and December to release any necessary updates effective each July and January. 
    7. **KMKE Tower Airspace**: Milwaukee Tower Airspace includes the airspace from the surface up to and including 3,200 feet within the 5NM ring of the Milwaukee Class Charlie airspace. 
![Milwaukee Class Charlie](https://i.gyazo.com/637b0272aad117acd66f44d2a5f21b97.png)
    8. **Transfer-of-control point for KMKE arrivals**: Transfer of control to Milwaukee Local Control for arrivals takes place for ILS Approaches at the Final Approach Fix and for visual approaches at the point the aircraft on final crosses the Tower airspace lateral boundary. 

### Chapter 2. KMKE Positions Universal Standard Operating Procedures
2. KMKE Position Universal Standard Operating Procedures
    1. **General**: General Mitchell International Airport is vZAU’s second busiest Class Charlie airport and it is not a [GRP](https://www.vatsim.net/documents/global-ratings-policy) designated Major facility within the ARTCC. 
        1. Controllers staffing Milwaukee Clearance Delivery or Ground Control positions shall hold at least a Ground Controller (S1) rating.
        2. Controllers staffing the Milwaukee Local Control position shall hold at least a Tower Controller (S2) rating or shall be in training for such having been cleared to be monitored on the position.
    2. **Communications**: Controllers operating positions at General Mitchell International Airport shall utilize the following radar client frequencies and voice channels. The * indicates the primary position for each level. The default voice server shall be: rw.liveatc.net. In order to streamline coordination with other vZAU controllers, voice channels shall be configured exactly as follows: 

        Position Name | Frequency | Callsign | Voice Channel
        :---: | :---: | :---: | :---:
        Milwaukee Atis | 126.400 | KMKE_ATIS | --
        Clearance Delivery* | 120.800 | MKE_DEL / MKE_1_DEL | mke_1_del
        Ground Control* | 121.800 | MKE_GND / MKE_1_GND | mke_1_gnd
        Local Control* | 124.570 | MKE_TWR / MKE_1_TWR | mke_1_twr
        
        1. Every controller shall utilize a primary frequency in their ATC client program for communications with aircraft. Every controller is encouraged to use voice as the primary method of communication with aircraft per VATSIM regulations. However, aircraft utilizing non-voice communications (text or receive only) will never be denied ATC services, nor will controllers executing text or receive only commands be denied the ability to control. Controllers shall use text as they are able to clarify instructions and/or when instructed by an aircraft. 
        2. Every KMKE position will maintain a standard and common position ATIS. VRC’s Controller Info dialog automates many of these elements of a standard position ATIS. The position ATIS will include the following elements at minimum:

            ```
             Position
             Current ATIS Letter ID
            Active Runways 
             ```
        3. Voice ATIS. Local Control shall be responsible for keeping an updated voice ATIS with all necessary information pertaining to operations at KMKE. The ATIS should also be recorded with the voice server as rw.liveatc.net with a frequency of 126.400. Sample KMKE voice ATIS templates can be found below.
            1. General Mitchell International Airport Information (code), (time of wx observation) Zulu,
(weather sequence – wind, vis, precip/phenomena, clouds, temp, dewpoint, altimeter)
            2. Arrivals expect vectors (choose one: ILS, Visual) Runway (#) approach
            3. Departures expect runways (#, #, #)
            4. Notices to Airmen: PIREP; Closures; Birds; Noise abatement, MU readings; Wind shear;
SIGMET; HIWAS; Braking action; SWAP (as necessary)
            5. For Clearance Delivery contact (position name) on frequency (frequency)
            6. VFR aircraft say direction of flight, aircraft type and requested altitude
            7. Pilots readback all runway hold short and taxi instructions
            8. Advise on initial contact you have information (code)
            >NOTE -- When KMKE is landing converging runways, place a message in the voice ATIS advising of converging operations to converging runways in use.
            
            >NOTE -- Prior to broadcasting, review the pending ATIS to ensure accuracy and inform pilots via voice and text of the updated information code being broadcast. 

### Chapter 3. KMKE Clearance Delivery
3. Clearance Delivery
    1. **Positions**: Milwaukee Clearance Delivery (MKE_DEL -- 120.800).
    2. ***IFR Operations***: Every aircraft departing KMKE airport under an IFR flight plan shall be issued a Standard Instrument Departure (SID).
        1. Clearance Delivery shall ensure that flight plans are amended to include an assigned SID in the filed flight plan if it does not originally include one. Should a pilot not have SID procedures available to them, coordination with higher controllers must take place as to agree on the best possible route.
            >NOTE -- Clearance Delivery is not authorized to grant “direct-to” clearances. Should a pilot request a direct-to clearance, the clearance may include verbiage to “expect” clearance direct-to a clearance limit. Coordination with MKE TRACON, C90 TRACON and Chicago Center, if online, prior to issuing a direct to clearance. 
    
            >EXAMPLE -- `"Southwest 501, Milwaukee Delivery, cleared to LaGuardia airport via the Mitchell# departure, expect
vectors direct to LaGuardia…”`

        2. The ACCRA#, MITCHELL#, and UECKR# Departures are the current procedures.
        3. Clearance Delivery shall ensure that appropriate altitudes for direction of flight are filed in the flight plan, as well as given in the clearance. Direction of flight shall be based upon the on-course heading of the flight. Initial departure headings after takeoff shall not be considered direction of flight for purposes of altitude clearance assignment. Clearance Delivery shall ensure that appropriate altitude restrictions listed in LOAs with adjacent ARTCCs are complied with. 
        4. Clearance Delivery shall issue initial altitudes of 5,000ft for all aircraft filed at or above 5,000ft. For aircraft filed less than 5,000ft, an initial altitude of the filed cruising altitude shall be used.
 NOTE -- If no Departure or Center controller is online, aircraft may be cleared directly to their cruise altitude with no initial altitude required in their clearance. 
        5. When clearing an aircraft to their altitude, your transmission shall consist of `“CLIMB VIA SID, TOP ALTITUDE 5,000.” `
        6. If MKE TRACON needs to change the initial altitude for some reason due to traffic or weather, your transmission can be modified to: `“CLIMB VIA SID, EXCEPT MAINTAIN XX,XXXft.”`
        7. If an aircraft is cleared to a destination that does not include the published departure procedures (if destination is within MKE TRACON, or if pilot is granted a special clearance) the “CLIMB VIA SID” phraseology is not required, and the controller shall simply say `“MAINTAIN XX,XXX, EXPECT FLXXX 10 MINUTES AFTER DEPARTURE”` or cruise altitude. 
    3. **VFR Operations**: The following describe VFR operations at KMKE Airport:
        1. Aircraft requesting VFR clearance to depart KMKE, without additional flight following, shall be issued an altitude at or below 1,800ft and pointed out to the appropriate MKE TRACON controller prior to giving the aircraft clearance. Aircraft should be assigned a transponder code from `5101-5177` block. The aircraft will be relieved of this code as they leave the Class Charlie airspace.
        2. VFR aircraft requesting flight following within MKE TRACON airspace shall be issued an initial altitude at or below 1,800 and coordinated with the appropriate MKE TRACON position prior to departure to determine effect on the TRACON’s workload. Aircraft should be assigned a transponder code from `5101-5177` block. 
        3. Local Control shall assign the initial direction of flight prior to takeoff, the same as IFR aircraft, that follows the NEODD SWEVEN rule when cruise altitude is at or above 5,000ft. 
    4. **Universal Duties**: Issue ATC Clearances for IFR and VFR aircraft and perform appropriate flight data strip markings (VRC users only). 
        1. When a clearance is issued, only then is a squawk code to be assigned. Controllers monitoring their departure list will know an aircraft has received clearance when an assigned squawk code appears next to their callsign.
    5. **Landing at Airports Within MKE TRACON**: Aircraft filed to an airport within MKE TRACON airspace shall be assigned no higher than 5,000 feet as their final cruise altitude. NEODD SWEVEN rule applies to all flights above 3,000 feet. 
    6. **Runway Assignment**: Clearance Delivery is not responsible for assigning runways to outbound aircraft. If an aircraft requests a runway assignment, the controller is required to transfer the aircraft to Ground Control or the next highest controller for such assignment. If there is no other controller online, Clearance Delivery may suggest a runway based on current weather conditions. 
        >EXAMPLE -- `“Citrus 923, no other ATC is available at this time, winds are 270 at 10, suggested departure runways
are 25L or 19R, monitor UNICOM on 122.80.”`

### Chapter 4. KMKE Ground Control
4. KMKE Ground Control
    1. **Positions**: Milwaukee Ground Control (MKE_GND -- 121.800).
    2. **ASDE-X Surveillance System**: General Mitchell International Airport is equipped with ASDE-X Surveillance Equipment to aid in the monitoring of ground movements. In accordance with ASDE-X operations, KMKE controllers shall place a message in the voice ATIS advising all aircraft to taxi with their transponder and altitude encoding on. If a voice ATIS is not operational, Ground Control should request the pilot turn their transponder to Mode C upon initial contact. 
        >NOTE -- Pilot participation in the simulation of ASDE-X Surveillance equipment is encouraged to enhance realism, but not required. In accordance with [VATSIM Code of Regulations](https://www.vatsim.net/documents/code-of-regulations), controllers shall not deny services to aircraft unable or unwilling to operate with Mode C on during ground movement operations. 
    
    3. **Airport Movement Areas**: The Airport Movement Area of General Mitchell International Airport is all runways, taxiways, and other areas which are utilized for taxiing/hover-taxiing, air taxiing, takeoff, and landing of aircraft, exclusive of loading ramps and parking areas.
    4. **Ground Movement Operations**: Ground Controllers should reference the taxi diagrams below to determine the route necessary for inbound and outbound aircraft.
        1. Maintain awareness of aircraft exiting a runway as their vacated position may interfere with an aircraft already taxiing. 
    5. **Runway Assignment**: Runways should be assigned to aircraft based on their direction of flight or SID waypoint.
    
        Flow | Wind | Departure Runways
        :---: | :---: | :---:
        West | <3kts | 25L, 19R
        West | Winds 130-310 | 29L, 19R
        East | Winds 320-120 | 7R, 1L
        >NOTE -- The runways shown for this flow are the maximum number of runways that can be in use. Based on the weather conditions, the local controller may choose any number of the available options to be active.

    6. **Runway Assignment Restrictions**: 1L/19R and 25L/7R are the primary runways. Unless an aircraft specifically requests another all aircraft should expect departure on the primary runways. VFR closed traffic is preferred to operate on a secondary runway but can operate on a primary runway with Tower approval. 
    7. **Taxiway Restrictions**: For the purposes of flight simulation, any aircraft can operate on any taxiway on the airfield unless the pilot requests use of or diversion from a specific taxiway. 
    8. **Runway Crossing Procedures**: Unless a runway is coordinated between Local and Ground control to be inactive or closed, Ground Control is required to have aircraft hold short of any runway to be crossed along its path to runway or gate until Local clears that aircraft to cross the runway. In some situations, Local control may require communications be transferred to them for this clearance. However, in most cases, Ground and Local Control can work out runway crossings via text or TeamSpeak coordination. 
        1.  No aircraft should receive more than one runway crossing clearance at a time. The only exception to this rule follows: Runways 1L/R may be included in one crossing instruction provided the aircraft remain on the same taxiway for both crossings. This occurs only if the aircraft is on taxiway M or K. 

### Chapter 5. KMKE Local Control
5. KMKE Local Control
    1. **Positions**: Milwaukee Local Control (MKE_TWR -- 125.570).
    2. **ASDE-X Surveillance System**: General Mitchell International Airport is equipped with ASDE-X Surveillance Equipment to aid in the monitoring of ground movements. In accordance with ASDE-X operations, KMKE controllers shall place a message in the voice ATIS advising all aircraft to taxi with their transponder and altitude encoding on. If a voice ATIS is not operational, Local Control should request the pilot turn their transponder to Mode C upon initial contact. 
        >NOTE -- Pilot participation in the simulation of ASDE-X Surveillance equipment is encouraged to enhance realism, but not required. In accordance with [VATSIM Code of Regulations](https://www.vatsim.net/documents/code-of-regulations), controllers shall not deny services to aircraft unable or unwilling to operate with Mode C on during ground movement operations. 
    
    3. **Active Runways**: All runways are to be considered active unless Local Control specifically indicates that they are inactive or closed.
    4. **Braking Action Reports**: All reports of poor to nil braking can be immediately recorded in an updated voice or text ATIS so that future operations can be coordinated. Local Control can issue braking reports as received from pilots when braking action advisories are in effect.
    5. **KMKE Tower Airspace**: In accordance with Milwaukee Approach Control, MKE TRACON delegates to KMKE ATCT the airspace within the Milwaukee Class Charlie surface area:
        1. Milwaukee Tower Airspace includes the airspace from the surface up to and including 3,200 feet within the 5NM ring of the Milwaukee Class Charlie Airspace. 
        2. MKE TRACON can turn departures/missed approaches in Tower airspace at or above 1,500ft AGL with respect to other arrivals and/or missed approaches. MKE TRACON can climb missed approaches on the localizer to 5,000ft MSL, and transfer communications to the tower, if necessary, once coordination is confirmed. 
        3. KMKE ATCT is authorized to provide visual separation between arrivals, departures and arrivals/departures under the control of KMKE ATCT as well as MKE TRACON. Ensure weather conditions to not obscure visibility prior to the application of visual separation.
    6. **Departure Procedures**: All IFR aircraft that are filed at 5,000 or above are expected to maintain 5,000 feet as their initial altitude. For IFR aircraft with final altitudes lower than 5,000, verbal coordination is required. VFR Aircraft are to climb to an initial altitude 1,800 MSL. 
        1. IFR Aircraft departing on the MITCHELL# departure should be assigned the following scratchpad entries prior to departure based on their initial waypoint: 
        
            Waypoint | Scratchpad Entry || Waypoint | Scratchpad Entry
            :---: | :---: | :---: | :---: | :---:
            Badger | BAE || Manitowoc | MTW
            Bradford | BDF || Muskegon | MKG
            Dells | DLL || Northbrook | OBK
            Dubuque |DBQ || Oshkosh | OSH
            Gipper | GIJ || Pullman | PMM
            Green Bay | GRB || Rockford | RFD
            Janesville | JVL || SIBER | SIB
            JAYBE | JAY || Timmerman | LJT
            Keeler | ELX || Victory | VIO
            Madison | MSN

        2. VRC Users should provide MKE TRACON with a flight progress strip at the time of departure and prior to the aircraft leaving KMKE ATCT airspace.
    7. **Arrival Procedures**: Unless otherwise coordinated, arrival aircraft shall be transferred to the appropriate Local Control frequency no later than the Outer Marker/fix of the ILS final approach course of the FAF on a non-precision approach. 
        1. All missed approaches, if not using published procedures, should be assigned 5,000 feet and issued headings according to the arrival area in use. 
        2. Simultaneous approaches on parallel runways are not authorized at Milwaukee.
        3. In lieu of verbal coordination, during ILS approaches, MKE TRACON will use scratchpad entries beginning with “V” to indicate a visual approach. 
        4. KMKE Local shall be responsible for longitudinal separation of aircraft inside the outer marker/fix. If this is not possible, alert MKE TRACON as soon as possible. This separation is required for all runways or no runways. MKE TRACON will not further anticipate this separation for individual runways.
        5. MKE TRACON will initiate a radar handoff of aircraft approximately 10nm from the airport when established on a final approach course and no closer than 1nm from the tower airspace boundary. MKE TRACON will not issue a communication handoff until Local control accepts the radar handoff. 
    8. **Special Operations**: Radar separation of helicopters must be established to provide radar services. No helicopter may hover within the Class Charlie airspace without specific approval from KMKE ATCT. 
    9. **Runway Configuration and Initial Headings**: The following runway configurations display only the maximum number of runways to be utilized for arrivals/departures. At any point in time, Local Control may choose to limit the number of runways utilized for a particular configuration as long as one runway remains active. 
    
        Flow | Wind | Departure Runway | Departure Headings
        :---: | :---: | :---: | :---:
        West | Winds 130-310 | 25L | 220, 250, 270
        ||| 19R | 160, 190, 220
        East | Winds 320-120 | 1L | 350, 010, 040
        |||7R | 040, 070, 100

        Flow | Wind | Arrival Runway
        :---: | :---: | :---:
        West | Winds 130-310 | 25L, 19R
        East | Winds 320-120 | 1L, 7R
        
        >NOTE -- The runways shown for this flow are the maximum number of runways that can be in use. Based on the weather conditions, the local controller may choose any number of the available options to be active. 

### Chapte 6. MKE TRACON Positions of Operation
6. MKE TRACON Positions of Operation
    1. **General**: General Mitchell International Airport is vZAU's second busiest Class Charlie airport and it is not a [GRP-designated](https://www.vatsim.net/documents/global-ratings-policy) Major facility within the ARTCC. 
        1. Controllers staffing TRACON positions in MKE TRACON shall hold at least an Approach Controller (S3) rating or shall be in training for such.
    2. **Communications**: The following are the TRACON positions that require duty familiarization and the transfer of position responsibility. The name of the position, the frequency, the online callsign, and the voice channel are as follows:

        Position Name | Frequency | Callsign | Voice Channel
        :---: | :---: | :---: | :---:
        Milwaukee South* | 118.000 | MKE_A_APP / MKE_A1_APP | mke_a_app
        Milwaukee North | 126.500 | MKE_B_APP / MKE_B1_APP | mke_b_app
        North Satellite (App/Dep) | 127.000 | MKE_N_APP / MKE_N1_APP | mke_n_app
        Milwaukee Departure | 125.350 | MKE_A_DEP / MKE_A1_DEP | mke_a_dep
        >NOTE -- * in the above table indicates the primary combined frequency to be connected first.
        
        1. Every controller shall utilize a primary frequency in their ATC client program for communications with aircraft. Every controller is encouraged to use voice as the primary method of communication with aircraft per VATSIM regulations. However, aircraft utilizing non-voice communications (text or receive only) will never be denied ATC services, nor will controllers executing text or receive only commands be denied the ability to control. Controllers shall use text to clarify instructions and/or when instructed by an aircraft. 
        2. Every MKE TRACON position will maintain a standard and common position ATIS. VRC’s Controller Info dialog automates many of these elements of a standard position ATIS. The position ATIS will include the following elements at minimum:
            ```
            Position
            Current ATIS Letter ID
            Active Runways 
            ```
        3. Voice ATIS. At Class D and C airports located within MKE TRACON, Local Control shall be responsible for keeping an updated voice ATIS with all necessary information pertaining to operations its respective airport. The standard VOICE ATIS for MKE TRACON if no other controller is online, is KMKE_ATIS. The ATIS should also be recorded with the voice server as rw.liveatc.net. Sample voice ATIS templates can be found below.
            1. General Mitchell International Airport Information (code), (time of wx observation) Zulu,
(weather sequence – wind, vis, precip/phenomena, clouds, temp, dewpoint, altimeter)
            2. Arrivals expect vectors (choose one: ILS, Visual) Runway (#) approach
            3. Departures expect runways (#, #, #)
            4. Notices to Airmen: PIREP; Closures; Birds; Noise abatement, MU readings Wind shear;
SIGMET; HIWAS; Braking action; SWAP.
            5. For Clearance Delivery contact (position name) on frequency (frequency)
            6. VFR aircraft say direction of flight, aircraft type and requested altitude
            7. Pilots readback all runway hold short and taxi instructions.
            8. Advise on initial contact you have information (code). 
            
            >NOTE -- When KMKE is landing converging runways or simultaneous approaches, place a message in the voice ATIS advising of converging operations to converging runways in use and/or that simultaneous approaches are in use. Also, when LAHSO operations are in effect, place an appropriate message in the voice ATIS. 
            
            >NOTE -- Prior to broadcasting, review the pending ATIS to ensure accuracy and inform pilots via voice and text of the update information code being broadcast.
            
    3. **Hierarchy of Opening Positions**: The following is a suggestion as to the order in which positions will be opened/split in the event more than one controller wishes to control MKE TRACON. All splits will be governed by the event parameters and may not occur as shown below. 

        Position Name | Frequency | Callsign | Airspace Delegation
        :---: | :---: | :---: | :---:
        MKE South | 118.000 | MKE_A_APP | All MKE
        MKE North | 126.500 | MKE_B_APP | S/N and Sat. split
        MKE Departure | 125.350 | MKE_A_DEP | All departures
        MKE N. Satellite | 127.000 | MKE_N_APP | Add N/Sat split


### Chapter 7. MKE TRACON Position Descriptions
7. MKE TRACON Position Descriptions
    1. **MKE TRACON Airspace**: MKE TRACON controllers are delegated that airspace as described below.  
 MKE South (A) – From southern border to 270/090 radial of KMKE Airport up to 13,000.  
 MKE North (B) – From 270/090 radial of KMKE Airport to 270/090 radial of BJB up to 13,000.  
 North Satellite (N) – From 270/090 radial of BJB to northern border up to 13,000. 
![MKE Airspace Delegation](https://i.gyazo.com/3104c9ec791353faebdb08ca05083366.png)
    2. **MKE South (A)**: 
        1. During a West Flow, MKE South will work as a feeder approach to MKE North to prepare aircraft to land on 19R and/or 25L. MKE South may receive handoffs from MKE North, C90, MSN TRACON or Chicago Center. MKE South will also work departures when a dedicated Departure is offline. 
        2. During an East Flow, MKE South will work as a final approach to runways 1L and/or 7R. MKE South may receive handoffs from MKE North, C90, MSN TRACON or Chicago Center. MKE South will also work departures when a dedicated Departure is offline. 
        3. MKE South will also handle satellite operations south of KMKE Airport. If a Departure controller is online, MKE South will handle arrivals only for KMKE and satellites. 
    3. **MKE North (B)**: 
        1. During an East Flow, MKE North will work as a feeder approach to MKE South to prepare aircraft to land on 1L and/or 7R. MKE North may receive handoffs from MKE South, North Satellie, MSN TRACON, and Chicago Center. MKE North may also receive handoffs from GRB TRACON and Minneapolis Center if North Satellite is offline. MKE North will also work departures when a dedicated Departure is offline. 
        2. During a West Flow, MKE North will work as a final approach to runways 19R and/or 25L. MKE North may receive handoffs from MKE South, North Sattellite, MSN TRACON, and Chicago Center. MKE North may also receive handoffs from GRB TRACON and Minneapolis Center if North Satellite is offline. MKE North will also work departures when a dedicated Departure is offline. 
        3. MKE North will also handle satellite operations north of KMKE Airport including the North Satellite airspace if that position is offline. If a Departure controller is online, MKE North will handle arrivals only for KMKE and satellites.
    4. **MKE Departure (A)**: 
        1. MKE Departure will cover A and B airspaces for KMKE departures. If North Satellite is offline, MKE Departure will also cover departures for N airspace. 
        2. MKE Departure operates in the same airspace as MKE North and South Approach and shall give way to any aircraft controlled by the approach controller, making every possible effort to keep departures separated from arrivals handled by another MKE TRACON controller. 
    5. **North Satellite (N)**: 
        1. North Satellite will cover arrivals and departures within the north satellite airspace. 
    6. **Configuration Changes**: When the weather is greater than a ceiling of 4,500 feet and greater than a visibility of 10 miles, traffic shall be no closer than a 10NM final from traffic that is touching down on an opposite direction final. When the weather is less that stated, traffic shall be no closer than a 16NM final from traffic that is touching down on an opposite direction final. 


### Chapter 8. MKE TRACON Satellite Towered Airport Flows
8. MKE TRACON Satellite Towered Airport Flows
    1. **MKE TRACON Satellite airports within MKE South (A) airspace**
        1. KENW -- Kenosha Regional Airport (ENW_TWR -- 118.600)
    
            Flow | Departure Runways | Arrival Runways
            :---: | :---: | :---:
            West | 25L/R, 33 | 25L/R, 33
            East | 7L/R, 15 | 7L/R, 15
            >NOTE -- The runways shown for this flow are the maximum number of runways that can be in use. Based on the weather conditions, the local controller may choose any number of the available options to be active.
    
    2. **MKE TRACON Satellite airports within MKE North (B) airspace**
        1. KEUS -- Waukesha Count Airport (EUS_TWR -- 123.700)
        
            Flow | Departure Runways | Arrival Runways
            :---: | :---: | :---:
            West | 28, 36/18 | 28, 36/18
            East | 10, 26/18 | 10, 36/18
            >NOTE -- The runways shown for this flow are the maximum number of runways that can be in use. Based on the weather conditions, the local controller may choose any number of the available options to be active.
        
        2. KMWC -- Timmerman Airport (MWC_TWR -- 120.500)

            Flow | Departure Runways | Arrival Runways
            :---: | :---: | :---:
            West | 22L/R, 33L/R | 22L/R, 33L/R
            East | 4L/R, 15L/R | 4L/R, 15L/R
            >NOTE -- The runways shown for this flow are the maximum number of runways that can be in use. Based on the weather conditions, the local controller may choose any number of the available options to be active.
    
    3. **MKE TRACON Satellite airports within North Satellite (N) airspace**
        1. KOSH -- Wittman Regional Airport (OSH_TWR -- 118.500)
        
            Flow | Departure Runways | Arrival Runways
            :---: | :---: | :---:
            West | 27, 36/18, 23*, 31* | 27, 36/18, 23*, 31*
            East | 9, 36/18, 13*, 5* | 9, 36/18, 13*, 5*
            >NOTE -- * indicates runways that may be used as necessary.  
            
            >NOTE -- The runways shown for this flow are the maximum number of runways that can be in use. Based on the weather conditions, the local controller may choose any number of the available options to be active.


### Chapter 9. Special Procedures
9. Special Procedures
    1. **Uncontrolled Satellite Airport Instrument Approach Procedures**: The following procedures shall be applied when an approach procedure to an uncontrolled airport originates in one sector’s airspace and the destination airport is in another controller’s airspace. 
        1. The initiating controller shall coordinate with the receiving controller to determine whether a communication handoff is necessary. The receiving controller will be the one to determine whether such handoff is necessary. The initiating controller will commence a point out of the aircraft to the receiving controller. 
        2. If the receiving controller accepts the point out, the initiating controller shall issue as part of the cancellation procedure to report cancellation on the receiving controller’s frequency. Even though no communication transfer has been made it is the responsibility of the receiving controller to ensure the cancellation of IFR by the aircraft. 
    2. **Uncontrolled Satellite Airport Instrument Approach Restrictions**: Whether the aircraft will transfer from one sector to another, it is the responsibility of the initiating controller to ensure the aircraft does not breach the vertical or lateral limits of the satellite airspace while flying the approach procedure. 
        1. If the pilot is unable to abide by the following restrictions, coordination with the affected position
may be made based on controller workload. 


### Chapter 10. Position Relief
10. Position Relief
    1. **Relief Restrictions**: Critically dependent positions must not be simultaneously relieved. In this case, a second position may not be relieved until after the first is complete and transfer of control has been confirmed. 
    2. **Relief Procedures**: These procedures shall apply at all positions utilizing radio capabilities, acting in handoff duties for radio positions or working in the split mode for a radio position. 
        1. The relieving controller shall observe the position for a period of time including the operational situation and listening to voice communications. The relieving controller shall indicate when he/she is ready to be briefed on the position being relieved. The relieving controller may ask any questions necessary to ensure a complete understanding of the operational situation after the verbal briefing is complete. 
        2. The controller being relieved shall commence the verbal briefing at the request of the relieving controller. The relief checklist should be followed by the active controller. Any abnormal traffic should be pointed out to the relieving controller. After the checklist has been completed and all questions have been answered, the active controller may release the position. The now-inactive controller shall remain on the frequency for a period of time to ensure the position has been
successfully transferred. 
        3. At the point in which the transfer is complete, the relieving controller, now-active-controller shall make a statement or otherwise indicate to the now-inactive-controller that position responsibility has been assumed. 
        4. When both parties agree that the relieving controller has assumed responsibility, they must end coordination communication with their operating initials. 
    3. **Relief Checklist Order**: When transferring a position to a relieving controller, the following items shall be communicated verbally as part of this checklist and in the following order: 
        1. Runway configuration at all noteworthy airports
        2. Approach procedures in use at all noteworthy airports
        3. Weather conditions, including PIREPs
        4. Special activities including emergencies, abnormal traffic
        5. Current ZAU, C90, MKE TRACON, and ATCT positions online and splits, if applicable
        6. Current traffic, headings, altitudes, speeds, point-outs, spacing requirements, coordination agreements, status of traffic.


### Chapter 11. Glossary of Terms
11. Glossary of Terms

Term | Definition
:---: | ---
AGL | Above Ground Level. This measurement changes as the topography of the earth changes.
ARTCC | Air Route Traffic Control Center. 
ASDE-X | Airport Surface Detection Equipment, model X, a runway safety tool that enables controllers to detect potential runway conflicts by providing coverage of movement of aircraft on runways and taxiways. 
ATCT | Air Traffic Control Tower. Another name for the cab.
ATIS | Automatic Terminal Information System, provided by airports with towers utilized on a frequency that gives weather and airport information to pilots.
C90 | The FAA designation for the Chicago TRACON. Adjacent the MKE TRACON airspace.
Capture Point | The point on the approach that the aircraft will intercept with and join the glideslope inbound for the runway. 
DEL | The VATSIM designation of a Clearance Delivery position.
Descent Area | Area in which an aircraft is permitted to descend for an approach to a runway given the lateral and vertical boundary changes in the approach airspace. 
GND | The VATSIM designation of a Ground position.
GRP | The [VATSIM Global Ratings Policy](https://www.vatsim.net/documents/global-ratings-policy), a document governing the training and promotion of controllers to be used throughout the Network.
High Side | The runway in use that aircraft will intercept at the higher altitude than aircraft intercepting the parallel runways. 
IFR | Instrument Flight Rules.
ILS | Instrument Landing System, a primary method of instrument approaches. A precision approach providing both lateral and vertical guidance to the runway.
LAHSO | Land and Hold Short of, for when an aircraft lands and must stop prior to a certain runway or taxiway intersection.
LOCAL | Another name for a Tower controller.
Low Side | The runway in use that aircraft will intercept at the lower altitude than aircraft intercepting the parallel runways. 
MSL | Mean Sea Level. Serves as a reference point for elevations; calculated based on observations of tides and seasonal variations over a 19 year period.
NEODD SWEVEN | North, East: Odd; South, West: Even. A method of determine the cruising altitude of an aircraft based on direction of flight. 
PIREP | A pilot report of actual weather conditions encountered by an aircraft in flight.
SID | Standard Instrument Departure.
SOP | Standard Operating Procedure(s).
TRACON | Terminal Radar Approach Control.
TWR | The VATSIM designation of a Tower Position.
VRF | Visual Flight Rules.
VRC | Virtual Radar Client, one of the radar clients supported by our facility. The most popular client in the U.S.
vZAU | ZAU is the designator for the Chicago ARTCC facility. *v* is used to designate a virtual environment, *Z* is assigned to each facility in the United States, and *AU* represents the town of Aurora where the facility is physically located.











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