VAR_INPUT
	
END_VAR

VAR_OUTPUT

	Blink100ms : BOOL;
	Blink250ms : BOOL;
	Blink500ms : BOOL;
	Blink750ms : BOOL;
	Blink1000ms : BOOL;
	Blink1100ms : BOOL;
	Blink1250ms : BOOL;
	Blink1500ms : BOOL;
	Blink1750ms : BOOL;
	Blink2000ms : BOOL;
	Blink2100ms : BOOL;
	Blink2250ms : BOOL;
	Blink2500ms : BOOL;
	Blink2750ms : BOOL;
	Blink3000ms : BOOL;
	Blink3100ms : BOOL;
	Blink3250ms : BOOL;
	Blink3500ms : BOOL;
	Blink3750ms : BOOL;
	Blink4000ms : BOOL;
	Blink4100ms : BOOL;
	Blink4250ms : BOOL;
	Blink4500ms : BOOL;
	Blink4750ms : BOOL;
	Blink5000ms : BOOL;
  
END_VAR

VAR

	t100ms : ton;
	rTrig100ms : r_trig;
	
	t250ms : ton;
	rTrig250ms : r_trig;
	
	t500ms : ton;
	rTrig500ms : r_trig;
	
	t750ms : ton;
	rTrig750ms : r_trig;
	
	t1000ms : ton;
	rTrig1000ms : r_trig;
	
	t1100ms : ton;
	rTrig1100ms : r_trig;
	
	t1250ms : ton;
	rTrig1250ms : r_trig;
	
	t1500ms : ton;
	rTrig1500ms : r_trig;
	
	t1750ms : ton;
	rTrig1750ms : r_trig;
	
	t2000ms : ton;
	rTrig2000ms : r_trig;
	
	t2100ms : ton;
	rTrig2100ms : r_trig;
	
	t2250ms : ton;
	rTrig2250ms : r_trig;
	
	t2500ms : ton;
	rTrig2500ms : r_trig;
	
	t2750ms : ton;
	rTrig2750ms : r_trig;
	
	t3000ms : ton;
	rTrig3000ms : r_trig;
	
	t3100ms : ton;
	rTrig3100ms : r_trig;
	
	t3250ms : ton;
	rTrig3250ms : r_trig;
	
	t3500ms : ton;
	rTrig3500ms : r_trig;
	
	t3750ms : ton;
	rTrig3750ms : r_trig;
	
	t4000ms : ton;
	rTrig4000ms : r_trig;
	
	t4100ms : ton;
	rTrig4100ms : r_trig;
	
	t4250ms : ton;
	rTrig4250ms : r_trig;
	
	t4500ms : ton;
	rTrig4500ms : r_trig;
	
	t4750ms : ton;
	rTrig4750ms : r_trig;
	
	t5000ms : ton;
	rTrig5000ms : r_trig;
  
END_VAR


(******Blinking at 100ms*****) 

t100ms(IN:= TRUE , PT:= T#100MS);
rTrig100ms(CLK := t100ms.Q);

IF rTrig100ms.Q THEN

	Blink100ms := NOT Blink100ms;
	t100ms(IN := FALSE);
  
END_IF

IF NOT t100ms.IN THEN 

	t100ms(IN := TRUE);
  
END_IF

(******Blinking at 250ms*****) 

t250ms(IN:= TRUE , PT:= T#250MS);
rTrig250ms(CLK := t250ms.Q);

IF rTrig250ms.Q THEN

	Blink250ms := NOT Blink250ms;
	t250ms(IN := FALSE);
  
END_IF

IF NOT t250ms.IN THEN 

	t250ms(IN := TRUE);
  
END_IF

(******Blinking at 500ms*****) 

t500ms(IN:= TRUE , PT:= T#500MS);
rTrig500ms(CLK := t500ms.Q);

IF rTrig500ms.Q THEN

	Blink500ms := NOT Blink500ms;
	t500ms(IN := FALSE);
  
END_IF

IF NOT t500ms.IN THEN 

	t500ms(IN := TRUE);
  
END_IF

(******Blinking at 750ms*****) 

t750ms(IN:= TRUE , PT:= T#750MS);
rTrig750ms(CLK := t750ms.Q);

IF rTrig750ms.Q THEN

	Blink750ms := NOT Blink750ms;
	t750ms(IN := FALSE);
  
END_IF

IF NOT t750ms.IN THEN 

	t750ms(IN := TRUE);
  
END_IF

(******Blinking at 1000ms*****) 

t1000ms(IN:= TRUE , PT:= T#1000MS);
rTrig1000ms(CLK := t1000ms.Q);

IF rTrig1000ms.Q THEN

	Blink1000ms := NOT Blink1000ms;
	t1000ms(IN := FALSE);
  
END_IF

IF NOT t1000ms.IN THEN 

	t1000ms(IN := TRUE);
  
END_IF

(******Blinking at 1100ms*****) 

t1100ms(IN:= TRUE , PT:= T#1100MS);
rTrig1100ms(CLK := t1100ms.Q);

IF rTrig1100ms.Q THEN

	Blink1100ms := NOT Blink1100ms;
	t1100ms(IN := FALSE);
  
END_IF

IF NOT t1100ms.IN THEN 

	t1100ms(IN := TRUE);
  
END_IF

(******Blinking at 1250ms*****) 

t1250ms(IN:= TRUE , PT:= T#1250MS);
rTrig1250ms(CLK := t1250ms.Q);

IF rTrig1250ms.Q THEN

	Blink1250ms := NOT Blink1250ms;
	t1250ms(IN := FALSE);
  
END_IF

IF NOT t1250ms.IN THEN 

	t1250ms(IN := TRUE);
  
END_IF

(******Blinking at 1500ms*****) 

t1500ms(IN:= TRUE , PT:= T#1500MS);
rTrig1500ms(CLK := t1500ms.Q);

IF rTrig1500ms.Q THEN

	Blink1500ms := NOT Blink1500ms;
	t1500ms(IN := FALSE);
  
END_IF

IF NOT t1500ms.IN THEN 

	t1500ms(IN := TRUE);
  
END_IF

(******Blinking at 1750ms*****) 

t1750ms(IN:= TRUE , PT:= T#1750MS);
rTrig1750ms(CLK := t1750ms.Q);

IF rTrig1750ms.Q THEN

	Blink1750ms := NOT Blink1750ms;
	t1750ms(IN := FALSE);
  
END_IF

IF NOT t1750ms.IN THEN 

	t1750ms(IN := TRUE);
  
END_IF


(******Blinking at 2000ms*****) 

t2000ms(IN:= TRUE , PT:= T#2000MS);
rTrig2000ms(CLK := t2000ms.Q);

IF rTrig2000ms.Q THEN

	Blink2000ms := NOT Blink2000ms;
	t2000ms(IN := FALSE);
  
END_IF

IF NOT t2000ms.IN THEN 

	t2000ms(IN := TRUE);
  
END_IF

(******Blinking at 2100ms*****) 

t2100ms(IN:= TRUE , PT:= T#2100MS);
rTrig2100ms(CLK := t2100ms.Q);

IF rTrig2100ms.Q THEN

	Blink2100ms := NOT Blink2100ms;
	t2100ms(IN := FALSE);
  
END_IF

IF NOT t2100ms.IN THEN 

	t2100ms(IN := TRUE);
  
END_IF

(******Blinking at 2250ms*****) 

t2250ms(IN:= TRUE , PT:= T#2250MS);
rTrig2250ms(CLK := t2250ms.Q);

IF rTrig2250ms.Q THEN

	Blink2250ms := NOT Blink2250ms;
	t2250ms(IN := FALSE);
  
END_IF

IF NOT t2250ms.IN THEN 

	t2250ms(IN := TRUE);
  
END_IF

(******Blinking at 2500ms*****) 

t2500ms(IN:= TRUE , PT:= T#2500MS);
rTrig2500ms(CLK := t2500ms.Q);

IF rTrig2500ms.Q THEN

	Blink2500ms := NOT Blink2500ms;
	t2500ms(IN := FALSE);
  
END_IF

IF NOT t2500ms.IN THEN 

	t2500ms(IN := TRUE);
  
END_IF

(******Blinking at 2750ms*****) 

t2750ms(IN:= TRUE , PT:= T#2750MS);
rTrig2750ms(CLK := t2750ms.Q);

IF rTrig2750ms.Q THEN

	Blink2750ms := NOT Blink2750ms;
	t2750ms(IN := FALSE);
  
END_IF

IF NOT t2750ms.IN THEN 

	t2750ms(IN := TRUE);
  
END_IF

(******Blinking at 3000ms*****) 

t3000ms(IN:= TRUE , PT:= T#3000MS);
rTrig3000ms(CLK := t3000ms.Q);

IF rTrig3000ms.Q THEN

	Blink3000ms := NOT Blink3000ms;
	t3000ms(IN := FALSE);
  
END_IF

IF NOT t3000ms.IN THEN 

	t3000ms(IN := TRUE);
  
END_IF

(******Blinking at 3100ms*****) 

t3100ms(IN:= TRUE , PT:= T#3100MS);
rTrig3100ms(CLK := t3100ms.Q);

IF rTrig3100ms.Q THEN

	Blink3100ms := NOT Blink3100ms;
	t3100ms(IN := FALSE);
  
END_IF

IF NOT t3100ms.IN THEN 

	t3100ms(IN := TRUE);
  
END_IF

(******Blinking at 3250ms*****) 

t3250ms(IN:= TRUE , PT:= T#3250MS);
rTrig3250ms(CLK := t3250ms.Q);

IF rTrig3250ms.Q THEN

	Blink3250ms := NOT Blink3250ms;
	t3250ms(IN := FALSE);
  
END_IF

IF NOT t3250ms.IN THEN 

	t3250ms(IN := TRUE);
  
END_IF

(******Blinking at 3500ms*****) 

t3500ms(IN:= TRUE , PT:= T#3500MS);
rTrig3500ms(CLK := t3500ms.Q);

IF rTrig3500ms.Q THEN

	Blink3500ms := NOT Blink3500ms;
	t3500ms(IN := FALSE);
  
END_IF

IF NOT t3500ms.IN THEN 

	t3500ms(IN := TRUE);
  
END_IF

(******Blinking at 3750ms*****) 

t3750ms(IN:= TRUE , PT:= T#3750MS);
rTrig3750ms(CLK := t3750ms.Q);

IF rTrig3750ms.Q THEN

	Blink3750ms := NOT Blink3750ms;
	t3750ms(IN := FALSE);
  
END_IF

IF NOT t3750ms.IN THEN 

	t3750ms(IN := TRUE);
  
END_IF

(******Blinking at 4000ms*****) 

t4000ms(IN:= TRUE , PT:= T#4000MS);
rTrig4000ms(CLK := t4000ms.Q);

IF rTrig4000ms.Q THEN

	Blink4000ms := NOT Blink4000ms;
	t4000ms(IN := FALSE);
  
END_IF

IF NOT t4000ms.IN THEN 

	t4000ms(IN := TRUE);
  
END_IF

(******Blinking at 4100ms*****) 

t4100ms(IN:= TRUE , PT:= T#4100MS);
rTrig4100ms(CLK := t4100ms.Q);

IF rTrig4100ms.Q THEN

	Blink4100ms := NOT Blink4100ms;
	t4100ms(IN := FALSE);
  
END_IF

IF NOT t4100ms.IN THEN 

	t4100ms(IN := TRUE);
  
END_IF

(******Blinking at 4250ms*****) 

t4250ms(IN:= TRUE , PT:= T#4250MS);
rTrig4250ms(CLK := t4250ms.Q);

IF rTrig4250ms.Q THEN

	Blink4250ms := NOT Blink4250ms;
	t4250ms(IN := FALSE);
  
END_IF

IF NOT t4250ms.IN THEN 

	t4250ms(IN := TRUE);
  
END_IF

(******Blinking at 4500ms*****) 

t4500ms(IN:= TRUE , PT:= T#4500MS);
rTrig4500ms(CLK := t4500ms.Q);

IF rTrig4500ms.Q THEN

	Blink4500ms := NOT Blink4500ms;
	t4500ms(IN := FALSE);
  
END_IF

IF NOT t4500ms.IN THEN 

	t4500ms(IN := TRUE);
  
END_IF

(******Blinking at 4750ms*****) 

t4750ms(IN:= TRUE , PT:= T#4750MS);
rTrig4750ms(CLK := t4750ms.Q);

IF rTrig4750ms.Q THEN

	Blink4750ms := NOT Blink4750ms;
	t4750ms(IN := FALSE);
  
END_IF

IF NOT t4750ms.IN THEN 

	t4750ms(IN := TRUE);
  
END_IF

(******Blinking at 5000ms*****) 

t5000ms(IN:= TRUE , PT:= T#5000MS);
rTrig5000ms(CLK := t5000ms.Q);

IF rTrig5000ms.Q THEN

	Blink5000ms := NOT Blink5000ms;
	t5000ms(IN := FALSE);
  
END_IF

IF NOT t5000ms.IN THEN 

	t5000ms(IN := TRUE);
  
END_IF
