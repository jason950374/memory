sram_dualWL

.subckt sram_dualWL WWL WL BL BL_b Vgnd nVdd
***************6T***************************
Mp_inv1 	nData	nData_b	nVdd	nVdd
Mp_inv2 	nData_b	nData	nVdd	nVdd
Mn_inv1 	nData	nData_b	gnd		gnd
Mn_inv2 	nData_b	nData	gnd		gnd
Mn_W_PG		nData	WWL		nTemp	gnd
Mn_W_PG_b	nData_b	WWL		nTemp_b	gnd
***************6T***************************

*PullDown n mos for Data to inverse Data
Mn_PD		nInvD	nData	gnd		gnd 
*PullDown n mos for Data bar inverse Data bar
Mn_PD_b		nInvD_b	nData_b	gnd		gnd 

*Pass gate n mos for inverse Data
Mn_PG		BL		WL		nTemp	gnd 
*Pass gate n mos for inverse Data bar
Mn_PG_b		BL_b	WL		nTemp_b	gnd 
.ends










