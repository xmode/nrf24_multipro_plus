# nrf24-multipro-plus
nRF24L01 multi-protocol RC transmitter modified to accept new hardware.

## Setup Procedure
- Create a model in OpenTX using external module in PPM mode, 12 channels and TAER sequence order.
- Set the momentary switch to channel 12 (used for reset/rebind)

## Binding Procedure
To setup bind without ising the screen:

- Turn off Taranis.
- Power up quad.
- While holding the appropriate stick pattern listed below, power up Taranis.
- Arm quad based on it's firmware's specification. 

To bind by using the screen:

- Turn on Taranis and allow module to go to the default mode
- Power up the quad
- On the module, cycle to the correct model type.
- Quad should bind automatically when selected.
- If quad doesnt bind, powercycle the quad and pull the reset switch on the taranis to try and bind again. 


#####Protocol is selected with stick position at startup:

- Rudder right + Aileron right + Elevator down = EAchine E010, NiHui NH-010, JJRC H36 mini  
- Rudder right + Aileron right + Elevator up = FQ-777-124 Pocket Drone  
- Rudder right + Aileron left + Elevator up = CX-10 older red PCB/CX11/CX205/CX30, JXD389/391/393, SH6057/6043/6044/6046/6047, FY326Q7, WLToys v252 Pro/v343, XinXun X28/X30/X33/X39/X40   
- Rudder right + Aileron left + Elevator down = WLToys V930/931/939/966/977/988  
- Rudder right + Elevator down = HiSky RXs, HFP80, HCP80/100, FBL70/80/90/100, FF120, HMX120, WLToys v933/944/955  
- Rudder right + Elevator up = Syma X5C (older model), X2 ...  
- Rudder right + Aileron right = MJX X600  
- Rudder right + Aileron left = EAchine H8 mini 3D, JJRC H20/H22   
- Elevator down + Aileron left = Syma X5C-1/X11/X11C/X12  
- Elevator down + Aileron right = Attop YD-822/YD-829/YD-829C ...  
- Elevator up + Aileron right = EAchine H8(C) mini, BayangToys X6/X7/X9, JJRC JJ850, Floureon H101 ...  
- Elevator up + Aileron left = EAchine H7  
- Elevator up = WLToys V202/252/272, JXD 385/388, JJRC H6C, Yizhan Tarantula X6 ...  
- Elevator down = EAchine CG023/CG031/3D X4  
- Aileron left = Cheerson CX-10 green pcb  
- Aileron right = Cheerson CX-10 blue pcb & some newer red pcb, CX-10A, CX-10C, CX11, CX12, Floureon FX10, JJRC DHD D1  

Last used protocol is automatically selected if stick is in neutral position. Also note the model type can be changed with the buttons on the module.

#####Extra features (if available on aircraft):

- Channel 5: led light, 3 pos. rate on CX-10 and FQ777-124, H7, inverted flight on H101  
- Channel 6: flip control  
- Channel 7: still camera  
- Channel 8: video camera, pitch trim (FQ777-124)  
- Channel 9: headless  
- Channel 10: calibrate Y (V2x2), pitch trim (H7), RTH (H8 mini/H20, FQ777-124), 360deg flip mode (H8 mini 3D/H22)  
- Channel 11: calibrate X (V2x2), roll trim (H7,FQ777-124)  
- Channel 12: Reset / Rebind  
