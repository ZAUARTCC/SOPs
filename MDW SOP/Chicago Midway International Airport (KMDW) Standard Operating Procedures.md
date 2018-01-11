Chicago Midway International Airport (KMDW) Standard Operating Procedures
===
##### Disclaimer
The follow are the standard operating procedures for use by Air Traffic Control Specialists at Chicago Midway International Airport on the VATSIM Network. Controllers are required to be familiar with the provisions of these procedures that pertain to their operational responsibilities and to exercise their best judgement if they encounter situations not covered by in this document. 
These procedures and the information within this document are designed for and specifically for use in a virtual controlling environment and **should not be used nor referenced for live operations in the National Airspace System**. The procedures in this document outline how the positions are to be operated and will be the basis for performance evaluations, training, and certification.

### Revisions
Change | Description | Effective Date
:---: | :---: | :---:
2015.1 | Document is first published for public evaluation | 1/1/2015
2015.2 | Document published second time for public evaluation | 3/1/2015
2015.3 | Document is reviewed by senior staff | 4/1/2015
2015.4 | 5-3 -- LRAC procedures removed | 1/1/2016
2015.5 | 6-1 -- Added Chapter to define abbreviations | 1/1/2016
2015.6 | Changed MDW1 and CICRO to MIDWAY2 and CISRO8 where used | 1/1/2016
2015.7 | 5-6.1 -- Added BACEN and renamed Petty to PETTY | 1/1/2016
2015.8 | Deleted any strikeouts from previous edits | 1/1/2016
2016.1 | Chapter Pages Updated | 7/1/2016
2016.2 | 1-3 -- vERAM included in supported clients | 7/1/2016
2016.3 | 4-9 -- Taxiway use Diagrams removed | 7/1/2016
2016.4 | 5-9 -- Initial Headings Updated | 7/1/2016
2017.1 | 5-6.1 -- Update of SID fixes | 1/1/2017
2017.2 | Update of any spelling errors or notes | 1/1/2017
2017.3 | 4-5 -- Flows Updated | 4/16/2017
2017.4 | 5-9 -- Flows Updated | 4/16/2017
2018.1 | Change to markdown format | XX/XX/2018

### Chapter 1. General Information
1. General Information
    1. **Purpose of This Document**: This document establishes standard operating procedures for the vZAU Chicago ARTCC of the VATSIM Network, specifically the operations at Chicago Midway International Airport.
    2. **Audience**: All vZAU Chicago ARTCC members and visiting controllers certified or working towards certification to provide ATC services at Chicago Midway International Airport.
    3. **Software Utilization**: vZAU has standardized on the Virtual Radar Client (VRC), vSTARS, and the vERAM software as its operating software of choice. Any references to software in this and other facility documents are written with this software in mind.
    4. **Global Ratings**: All positions of operation outlined within this document shall be staffed in compliance with [VATSIM Global Ratings Policy (GRP)](https://www.vatsim.net/documents/global-ratings-policy). Chicago Midway International Airport is designated by the GRP as a MINOR facility, and all controllers staffing Chicago Midway positions are only required to possess the appropriate VATSIM rating necessary to work a Ground or Tower position. Special endorsements are not required.
    5. **Emergencies**: Controllers shall reference the [VATSIM Code of Conduct](https://www.vatsim.net/documents/code-of-conduct) and the [VATSIM Code of Regulations](https://www.vatsim.net/documents/code-of-regulations) policies regarding emergencies at all times, and have the right to request the termination of an emergency should it interfere with operations. Non-compliant pilots should be referred to a VATSIM Supervisor by utilizing the .WALLOP command on the radar client software. 
    6. **Updates**: This SOP is to be reviewed and, if necessary, updated every six months to remain as current as possible. Senior Staff will convene during the months of June and December to release any necessary updates effective each July and January. 
    7. **Chicago Midway Tower Airspace**: Chicago Midway Tower Airspace is depicted below and includes the airspace from the surface up to and including 3,100 feet south and east of the Chicago O’Hare Class Bravo shelf that extends from the northeast to southeast, as indicated by the blue line, within the 5NM ring of the Chicago Midway Class Charlie Airspace. North and west of that line, the Midway Tower Airspace includes the airspace from the surface up to but not including 3,000 feet within the 5NM ring of the Midway Class Charlie Airspace.
![KMDW Sectional](https://i.gyazo.com/66cba13e5ea421ebd5e7b4f26898e91c.png)  
    8. **Transfer-of-control point for MDW arrivals**: Transfer of control to Chicago Midway Local Control for arrivals takes place for ILS Approaches at the Final Approach Fix and for visual approaches at the point the aircraft on final crosses the Tower airspace lateral boundary.  

### Chapter 2. MDW Positions Universial Standard Operating Procedures
2. MDW Positions Universial Standard Operating Procedures
    1. **General**: Chicago Midway International Airport is vZAU’s primary Class Charlie airport, but it is not a GRP-designated Major facility within the ARTCC. However, the TRACON airspace above and surrounding the MDW airport IS GRP-designated Major TRACON airspace as it primarily serves operations into and out of KORD, which is a GRP Major Facility.
        1. Controllers staffing Chicago Midway Clearance Delivery or Ground Control positions shall hold at least a
Ground Controller (S1) rating.  
        2. Controllers staffing the Chicago Midway Local Control position shall hold at least a Tower Controller (S2)
rating or shall be in training for such having been cleared to be monitored on the position.

    2. **Communications**: Controllers operating positions at Chicago Midway International Airport shall utilize the following radar client frequencies and voice channels. **The * indicates the primary position for each level primary position for each level**. The default voice server shall be: rw.liveatc.net. In order to streamline coordination with other vZAU controllers, voice channels shall be configured exactly as follows: 
        1. Every controller shall utilize a primary frequency in their ATC client program for communications with aircraft. Every controller is encouraged to use voice as the primary method of communication with aircraft per VATSIM regulations. However, aircraft utilizing non-voice communications (text or receive only) will never be denied ATC services, nor will controllers executing text or receive only commands be denied the ability to control. Controllers shall use text as they are able to clarify instructions and/or when instructed by an aircraft.   
        2. Every MDW position will maintain a standard and common position ATIS. VRC’s Controller Info dialog automates many of these elements of a standard position ATIS. The position ATIS will include the following elements at minimum:
            ```
            Position
            Current ATIS Letter ID
            Active Runways
            ```

            Position Name | Frequency | Callsign | Voice Channel
            :---: | :---: | :---: | :---:
            Midway ATIS | 132.750 | KMDW_ATIS | none
            Clearance Delivery* | 124.620 | MDW_DEL / MDW_1_DEL | mdw_1_del
            Ground Control* | 121.650 | MDW_GND / MDW_1_GND | mdw_1_gnd
            Local Control* | 118.700 | MDW_TWR / MDW_1_TWR | mdw_1_twr
  
        3. Voice ATIS. Local Control shall be responsible for keeping an updated voice ATIS with all necessary information pertaining to operations at MDW. The ATIS should also be recorded with the voice server as rw.liveatc.net with a frequency of 132.750. Sample MDW voice ATIS templates can be found below.
            1. Midway Airport Information (code), (time of wx observation) Zulu, (weather sequence – wind,
            vis, precip/phenomena, clouds, temp, dewpoint, altimeter)
            2. Arrivals expect vectors (choose one: ILS, Visual) Runway (#) approach
            3. Departures expect runways (#, #, #)
            4. Notices to Airmen: PIREP; Closures; Birds; Noise abatement, MU readings; Wind shear;
            SIGMET; HIWAS; Braking action; SWAP (as necessary)
            5. For Clearance Delivery contact (position name) on frequency (frequency)
            6. VFR aircraft say direction of flight, aircraft type and requested altitude
            7. Pilots readback all runway hold short and taxi instructions
            8. Advise on initial contact you have information (code)

                NOTE 1 -- When MDW is landing converging runways, place a message in the voice ATIS advising of converging operations to converging runways in use.
                NOTE 2 -- Prior to broadcasting, review the pending ATIS to ensure accuracy and inform pilots via voice and text of the updated information code being broadcast.

### Chapter 3. MDW Clearance Delivery
3. MDW Clearance Delivery
    1. **Positions**: Midway Clearance Delivery (MDW_DEL -- 124.620).
    2. **IFR Operations**: Every aircraft departing MDW airport under an IFR flight plan shall be issued a Standard Instrument Departure (SID). 
        1. Clearance Delivery shall ensure that flight plans are amended to include an assigned SID in the filed flight plan if it does not originally include one. Should a pilot not have SID procedures available to them, coordination with higher controllers must take place as to agree on the best possible route.  
NOTE -- Clearance Delivery is not authorized to grant “direct-to” clearances. Should a pilot request a direct-to clearance, the clearance may include verbiage to `"expect"` clearance direct-to a clearance limit. Coordination with C90 TRACON and Chicago Center, if online, prior to issuing a direct-to clearance.  
EXAMPLE -- `“Southwest 501, Midway Delivery, cleared to LaGuardia airport via the Midway # departure, expect
vectors direct to LaGuardia…” `  
        2. The MDWAY# and CISRO# Departures are the only departure procedure at Midway and are both radar vectored departures. This type of SID allows controllers to vector aircraft toward virtually every primary airway navaid in the regional vicinity of KMDW to initiate an IFR routing.  
        3. Clearance Delivery shall ensure that appropriate altitudes for direction of flight are filed in the flight plan, as well as given in the clearance. Direction of flight shall be based upon the on-course heading of the flight. Initial departure headings after takeoff shall not be considered direction of flight for purposes of altitude clearance assignment. Clearance Delivery shall ensure that appropriate altitude restrictions listed in LOAs with adjacent ARTCCs are complied with.  
        4. Clearance Delivery shall issue initial altitudes of 3,000ft for all aircraft filed at or above 3,000ft. For aircraft filed less than 3,000ft, an initial altitude of the filed cruising altitude shall be used.  
NOTE -- If no Departure or Center controller is online, aircraft may be cleared directly to their cruise altitude with no initial altitude required in their clearance.  
        5. When clearing an aircraft to their altitude, your transmission shall consist of `“MAINTAIN 3,000”`.  
        6. If C90 needs to change the initial altitude for some reason due to traffic or weather, your transmission can be modified to: `“MAINTAIN XX,XXX”`.  
    3. **VFR Operations**: Midway is not within the Chicago O’Hare Class Bravo Airspace, and therefore Midway Clearance Delivery cannot authorize requests to operate within the Chicago O’Hare Class Bravo Airspace. In lieu of this, Clearance Delivery must coordinate with the appropriate controller working C90 to prepare them for such request from the pilot.  
        1. Aircraft requesting VFR clearance to depart MDW, without additional flight following, shall be issued an altitude at or below 1,800ft and pointed out to the appropriate C90 controller prior to giving the aircraft clearance. Aircraft should be assigned a transponder code from `5101-5177` block. The aircraft will be relieved of this code as they leave the Class Charlie airspace.  
        2. VFR aircraft requesting flight following within C90 airspace shall be issued an initial altitude at or below 1,800 and coordinated with the appropriate C90 position prior to departure to determine effect on C90’s workload. Aircraft should be assigned a transponder code from `5101-5177` block.  
        3. Local Control shall assign the initial direction of flight prior to takeoff, the same as IFR aircraft, that follows the NEODD SWEVEN rule when cruise altitude is at or above 3,000ft.  
    4. **Universal  Duties**: Issue ATC Clearances for IFR and VFR aircraft and perform the appropriate flight data strip marking (VRC users only).  
        1. When a clearance is issued, only then is a squawk code to be assigned. Controllers monitoring their departure list will know an aircraft has received clearance when an assigned squawk code appears next to their callsign.  
3-4.2 If necessary, question each non-US carrier heavy departure to verify their ability to comply with the climb restriction in the current DP.  
    5. **Landing at Airports Within C90**: Aircraft filed to an airport within C90 airspace shall be assigned no higher than 5,000 feet as their final cruise altitude. NEODD SWEVEN rule applies to all flights above 3,000 feet.  
    6. **Runway Assignment**: Clearance Delivery is not responsible for assigning runways to outbound aircraft. If an aircraft requests a runway assignment, the controller is required to transfer the aircraft to Ground Control or the next highest controller for such assignment. If there is no other controller online, Clearance Delivery may suggest a runway based on current weather conditions.  
EXAMPLE -- `“Citrus 923, no other ATC is available at this time, winds are 270 at 10, suggested departure runways
are 22L or 31c, monitor UNICOM on 122.80.”`

### Chapter 4. MDW Ground Control
4. MDW Ground Control
    1. **Positions**: Midway Ground Control (MDW_GND -- 121.650).  
    2. **ASDE-X Surveillance System**: Chicago Midway International Airport is equipped with ASDE-X Surveillance Equipment to aid in the monitoring of ground movements. In accordance with ASDE-X operations, MDW controllers shall place a message in the voice ATIS advising all aircraft to taxi with their transponder and altitude encoding on. If a voice ATIS is not operational, Ground Control should request the pilot turn their transponder to Mode C upon initial contact.  
NOTE -- Pilot participation in the simulation of ASDE-X Surveillance equipment is encouraged to enhance realism, but not required. In accordance with [VATSIM Code of Regulations](https://www.vatsim.net/documents/code-of-regulations), controllers shall not deny services to aircraft unable or unwilling to operate with Mode C on during ground movement operations.
    3. **Airport Movement Area**: The Airport Movement Area of Chicago Midway Airport is all runways, taxiways, and other areas which are utilized for taxiing/hover-taxiing, air taxiing, takeoff, and landing of aircraft, exclusive of loading ramps and parking areas.  
    4. **Ground Movement Operations**: Ground Controllers should reference the taxi diagrams below to determine the route necessary for inbound and outbound aircraft.  
        1. Maintain awareness of aircraft exiting a runway as their vacated position may interfere with an aircraft already taxiing.  
    5. **Runway Assignment**: Runways should be assigned to aircraft based on their vectored waypoint on the MDWAY# or CISRO# Departure or direction of flight if VFR.  

        Flow | Wind | Departure Runway
        --- | --- | ---
        West | Winds 140-170 < 5kts | 22L, 31C
        West | Winds 180-360 | 22L, 31C
        West | Winds 010-040 < 5kts | 22L, 31C
        |||
        East | Winds 010-040 between 5-19kts | 4R, 13C
        East | Winds 050-130 | 4R, 13C
        East | Winds 140-170 between 5-19kts | 4R, 13C
        
    6.  **Runway Assignment Restrictions**: 31C/13C and 22L/4R are the primary runways for their triples/pairs. Unless an aircraft specifically requests 22R/4L, 31L/13R, 31R/13L or unless taxi to the primary runway would involve crossing the primary runway, all aircraft should expect departure on the primary runways. VFR closed traffic is preferred to operate on a secondary runway but can operate on a primary runway with Tower approval.  
    7.  **Taxiway Restrictions**: For the purposes of flight simulation, any aircraft can operate on any taxiway on the airfield unless the pilot requests use of or diversion from a specific taxiway. The taxi charts shown at the end of this chapter highlight the preferred taxi routing from gate to runway and vice versa.  
    8. **Runway Crossing Procedures**: Unless a runway is coordinated between Local and Ground control to be inactive or closed, Ground Control is required to have aircraft hold short of any runway to be crossed along its path to runway or gate until Local clears that aircraft to cross the runway. In some situations, Local control may require communications be transferred to them for this clearance. However, in most cases, Ground and Local Control cab work out runway crossings via text or TeamSpeak coordination.  
        1. No aircraft should receive more than one runway crossing clearance at a time. The only exception to this rule follows: Runways 31L/C/R may be included in one crossing instruction provided the aircraft remain on the same taxiway for both crossings and 31L/13R is closed. Runways 22L/22R may be included in one crossing instruction provided the aircraft remain on the same taxiway for both crossings. 

### Chapter 5. MDW Local Control
5. MDW Local Control
    1. **Positions**: Midway Local Control (MDW_TWR -- 118.700).  
    2. **ASDE-X Surveillance System**: Midway International Airport is equipped with ASDE-X Surveillance Equipment to aid in the monitoring of ground movements. In accordance with ASDE-X operations, MDW controllers shall place a message in the voice ATIS advising all aircraft to taxi with their transponder and altitude encoding on. If a voice ATIS is not operational, Local Control should request the pilot turn their transponder to Mode C upon initial contact.  
NOTE -- Pilot participation in the simulation of ASDE-X Surveillance equipment is encouraged in order to enhance realism, but not required. In accordance with [VATSIM Code of Regulations](https://www.vatsim.net/documents/code-of-regulations), controllers shall not deny services to aircraft unable or unwilling to operate with Mode C on during ground movement operations. 
    3. **Active Runways**: All runways are to be considered active unless Local Control specifically indicates that they are inactive or closed.  
    4. **Braking Action Reports**: All reports of *poor* to *nil* braking can be immediately recorded in an updated voice or text ATIS so that future operations can be coordinated. Local Control can issue braking reports as received from pilots when braking action advisories are in effect.  
    5. **Midway Tower Airspace**: In accordance with Chicago Approach Control (C90), C90 delegates to MDW ATCT the airspace within the Chicago Midway Class Charlie surface area.  
        1. Chicago Midway Tower Airspace is depicted below and includes the airspace from the surface up to and including 3,100 feet south and east of the Chicago O’Hare Class Bravo shelf that extends from the northeast to southeast, as indicated by the blue line, within the 5NM ring of the Chicago Midway Class Charlie Airspace. North and west of that line, the Chicago Midway Tower Airspace includes the airspace from the surface up to but not including 3,000 feet within the 5NM ring of the Chicago Midway Class Charlie Airspace.  
        2. C90 can turn departures/missed approaches in Tower airspace at or above 1,500ft AGL with respect to other arrivals and/or missed approaches. C90 can climb missed approaches on the localizer to 3,000ft MSL, and transfer communications to the tower, if necessary, once coordination is confirmed.  
        3. MDW ATCT is authorized to provide visual separation between arrivals, departures and arrivals/departures under the control of MDW ATCT as well as C90. Ensure weather conditions to not obscure visibility prior to the application of visual separation.  
    6. **Departure Procedures**: All IFR aircraft that are filed at 3,000 or above are expected to maintain 3,000 feet as their initial altitude. For IFR aircraft with final altitudes lower than 3,000, verbal coordination is required. VFR Aircraft are to climb to an initial altitude 1,800 MSL but are not permitted higher than 4,500 MSL if further climb instructions are given prior to leaving the boundaries of the Local airspace.  
        1. IFR aircraft departing on the MIDWAY# or CISRO# departure should be assigned the following scratchpad entries prior to departure based on their initial waypoint:
        2. VRC Users should provide C90 with a flight progress strip at the time of departure and prior to the aircraft leaving MDW ATCT airspace. 
        
            Fix Name | Scratchpad Entry
            :---: | :---:
            ACITO | ACI
            BACEN | BAC
            Badger VOR | BAE
            CMSKY | CMS
            DENNT | DEN
            EARND | EAR
            Gipper VOR | GIJ
            Iowa City VOR | IOW
            LEWKE | LEW
            PEKUE | PEK
            Peotone VOR | EON
            PETTY | PET
            PMPKN | PMP
            Polo VOR | PLL
            RAYNR | RAY
            Roberts VOR | RBS
            SIMMN | SIM
    7. **Arrival Procedures**: Unless otherwise coordinated, arrival aircraft shall be transferred to the appropriate Local Control frequency no later than the Outer Marker/fix of the ILS final approach course of the FAF on a non-precision approach.  
        1. All missed approaches, if not using published procedures, should be assigned 3,000 feet and issued headings according to the arrival area in use.  
        2. Simultaneous approaches on parallel runways are not authorized at Midway.  
        3. In lieu of verbal coordination, during ILS approaches, C90 will use scratchpad entries beginning with “V” to indicate a visual approach.  
        4. MDW Local shall be responsible for longitudinal separation of aircraft inside the outer marker/fix. If this is not possible, alert C90 as soon as possible. This separation is required for all runways or no runways. C90 will not further anticipate this separation for individual runways.  
        5. C90 will initiate a radar handoff of aircraft approximately 10nm from the airport when established on a final approach course and no closer than 1nm from the tower airspace boundary. C90 will not issue a communication handoff until Local control accepts the radar handoff.  
    8. **Special Operations**: Radar separation of helicopters must be established to provide radar services. No helicopter may hover within the Class Charlie airspace without specific approval from MDW ATCT.  
    9. **Runway Configurations and Initial Headings**:

        Flow | Wind | Departures | Headings
        --- | --- | ---| ---
        West | Winds 140-170 < 5kts | 22L | 220, 250
        ||| 31C | 220, 250, Right turn 090 if MDW not landing 22L
        || Winds 180-260 | 22L | 220, 250
        ||| 31C | 220, 250, Right turn 090 if MDW not landing 22L
        || Winds 010-040 < 5kts | 22L | 220, 250
        ||| 31C| 220, 250, Right turn 090 if MDW not landing 22L
        ||||
        East | Winds 010-040 between 5-19kts | 4R | 090, 130
        ||| 13C | 090, 170, 200
        || Winds 050-130 | 4R | 090, 130
        ||| 13C | 090, 170, 200
        || Winds 140-170 between 5-19 kts | 4R | 090, 130
        ||| 13C | 090, 170, 200
        
        Flow | Wind | Arrivals
        --- | --- | ---
        West | Winds 140-170 < 5kts | 22L, 31C
        || Winds 180-360 | 22L, 31C
        || Winds 010-040 < 5kts | 22L, 31C
        ||||
        East | Winds 010-040 between 5-19kts | 4R, 13C
        || Winds 050-130 | 4R, 13C
        || Winds 140-170 between 5-19kts | 4R, 13C

### Chapter 6. Glossary of Terms
6. Glossary of Terms
    Term | Definition
    --- | ---
    AGL | Above Ground Level. This measurement changes as the topography of the earth changes.
    ARTCC | Air Route Traffic Control Center
    ASDE-X | Airport Surface Detection Equipment, model X, a runway safety tool that enables controllers to detect potential runway conflicts by providing coverage of movement of aircraft on runways and taxiways. 
    ATCT | Air Traffic Control Tower. Another name for the cab.
    ATIS | Automatic Terminal Information System, provided by airports with towers utilized on a frequency that gives weather and airport information to pilots. 
    DEL | The VATSIM designation of a Clearance Delivery position.
    ES | Euroscope, one of the radar clients supported by our facility.
    FAF | Final Approach Fix.
    GND | The VATSIM designation of a Ground position.
    GRP | The [VATSIM Global Ratings Policy](https://www.vatsim.net/documents/global-ratings-policy), a document governing the training and promotion of controllers to be used throughout the Network.
    IFR | Instrument Flight Rules.
    ILS | Instrument Landing System, a primary method of instrument approaches. A precision approach providing both lateral and vertical guidance to the runway
    LAHSO | Land and Hold Short of, for when an aircraft lands and must stop prior to a certain runway or taxiway intersection.
    LOCAL | Another name for a Tower controller.
    MSL | Mean Sea Level. Serves as a reference point for elevations; calculated based on observations of tides and seasonal variations over a 19 year period.
    NEODD SWEVEN | North, East: Odd; South, West: Even. A method of determine the cruising altitude of an aircraft based on direction of flight. 
    SID | Standard Instrument Departure.
    SOP | Standard Operating Procedure(s).
    TRACON | Terminal Radar Approach Control.
    TWR | The VATSIM designation of a Tower Position
    VFR | Visual Flight Rules
    VRC | Virtual Radar Client, one of the radar clients supported by our facility. The most popular client in the U.S.
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
