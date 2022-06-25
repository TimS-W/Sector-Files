// ##################################################################
//                 VATSSA | FIR ICAO | GroundRadar | Settings
// ##################################################################

// GroundRadar Version 1.5 Beta 5

// Version v0.1
// Update Date 19/05/2022

// Changelog
// v0.1 | ICAO GroundRadar Settings Initial Update

// ##################################################################
//                 SYSTEM SETTINGS v0.1
// ##################################################################

Equip_ModeS=WZLCISG
Equip_ProMode=0
RawVideo=1
RawVideo_MaxHistory=5

System_GroundMode_AltFilter_AAL=5000
System_UseReportedGS=1
System_RwyArea=45.0 
System_RwyBufferArea=90.0 
System_RwyArea_LVP=90.0
System_RwyBufferArea_LVP=140.0

System_State_OnFreq=STBY
System_State_StartUp=XX
System_State_Push=PB
System_State_Taxi=TX
System_State_LineUp=LU
System_State_Depa=TO
System_State_DeIce=SU

System_TagColor=2

// ##################################################################
//                 COLORS v0.3
// ##################################################################

Color_Arrival=253,189,166
//Color_Arrival=253,236,166
Color_Departure=210,236,166
// Color_Departure=0,18,153
Color_Unknown=0,0,0
Color_Background=160,160,160
Color_RawVideo=175,190,200
Color_RawVideoHistory=175,190,200
Color_SelectedLabelFill_App=200,200,200
Color_SelectedLabelFill_Gnd=200,200,200
Color_WBackground=170,170,170
Color_WBorder=250,250,250
Color_WForeground2=170,170,170
Color_WForeground=65,65,65
Color_WTitleBar=250,250,250

AppLabel_Font=EuroScope
AppLabel_Transparency_Bg=255

// ##################################################################
//                 LABELS v0.3
// ##################################################################

GroundLabel=1
GroundLabel_Font=EuroScope
GroundLabel_FontStyle=1000,0,0,0
GroundLabel_FontSize=11
GroundLabel_Transparency_Bg=100
TowerLabel_FontSize=11
AppLabel_FontSize=11

Label=GND:ARR:0:ALRT,0,0:COMM,0,1 
Label=GND:ARR:1:CALLSIGN,0,0:STAND,0,1 
Label=GND:ARR:2:ATYP,0,0:WTC,0,1,0
Label=GND:ARR:3:RMK,0,1 

Label=GND:DEP:0:ALRT,0,0:ASSR_E,0,1:COMM,0,1 
Label=GND:DEP:1:CALLSIGN,0,0:DRWY,0,1,1 
Label=GND:DEP:2:ATYP,0,0:WTC,0,1,0
Label=GND:DEP:3:DEP,0,0:RMK,0,1 

Label=TWR:ARR:0:ALRT,0,0:COMM,0,1 
Label=TWR:ARR:1:CALLSIGN,0,0:ARWY,0,1 
Label=TWR:ARR:2:AFL+VS,0,1,20:GS,0,1
Label=TWR:ARR:3:ATYP,0,0:RMK,0,1 

Label=TWR:DEP:0:ALRT,0,0:COMM,0,1 
Label=TWR:DEP:1:CALLSIGN,0,0:ATYP,0,1
Label=TWR:DEP:2:AFL+VS,0,1,20:GS,0,1
Label=TWR:DEP:3:DEP,0,0:RMK,0,1

Label_AFL+VS=0,0,1
Label_ARWY=0,0,0
Label_ATYP=0,0,0
Label_DEP=0,0,0
Label_DRWY=0,1,0
Label_RMK=0,1,1
Label_STAND=0,1,0
Label_GS=0,0,1


// ##################################################################
//                 OTHERS v0.1
// ##################################################################

Track_PredictionLine_TWR=1
Window_APP_Extensions=1

System_GroundMode_AltFilter_AAL=24000
System_UseReportedGS=0
System_RwyArea=45.0 
System_RwyBufferArea=90.0 
System_RwyArea_LVP=90.0
System_RwyBufferArea_LVP=140.0

Track_PredictionLine_APP=2
Track_HistoryDots_APP=5
Track_HistoryDots_GND=0
Track_HistoryDots_TWR_Type=1
Track_Heading_Line=0


// ##################################################################
//                 LISTS | DEPARTURES v0.1
// ##################################################################

List_Departure=0,1100,45
List_Departure_RWY=1
List_Departure_TYPE=1
List_Departure_WTC=1
List_Departure_EOBT=1
List_Departure_STAND=1
List_Departure_Items=10


// ##################################################################
//                 LISTS | DEPARTURE TIMER v0.1
// ##################################################################

List_Outbound_DefPos=1100,150
List_Outbound_TYPE=1
List_Outbound_WTC=1
List_Outbound_WTC_Type=2
List_Outbound_SID=1
List_Outbound_ExpiryTime=600


// ##################################################################
//                 LISTS | ARRIVALS v0.1
// ##################################################################

List_Arrival=0,1390,45
List_Arrival_RWY=1
List_Arrival_TYPE=1
List_Arrival_WTC=1
List_Arrival_ETA=1
List_Arrival_STAND=1
List_Arrival_Items=10
List_Arrival_MaxTime=60

List_Inbound_TYPE=0
List_Inbound_WTC=0
List_Inbound_ETA=1
List_Inbound_STAND=0


// ##################################################################
//                 LISTS | STANDS v0.1
// ##################################################################

List_Stand=0,1680,45
List_Stand_Items=20