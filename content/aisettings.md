---
title: "AI Settings"
draft: false
--- 

# AI Feedback Examples

Context for all examples: 

*A student has submitted program_1.py. The volume() function is correct, but the litres_to_gallons() conversion uses the wrong divisor. The correct value is 4.546 litres per UK gallon.* 

&nbsp; 

## Feedback styles 
Three feedback styles control the tone and framing of the AI response. The teacher selects a style before triggering feedback generation. 

&nbsp; 

### Concise — direct and brief, minimal explanation: 
*Your volume() function is correct. The issue is in litres_to_gallons() — check the conversion factor you are dividing by (should be 4.546).* 

### Supportive — encouraging, acknowledges effort: 
*Well done for getting the volume calculation right — that's the trickiest part! Your litres_to_gallons() function is very close. Have a look at the number you're dividing by. One UK gallon is 4.546 litres, so that's the value you need. You're nearly there!* 

### Structured — organised with clearly labelled sections: 
***What worked:** Your volume() function correctly multiplies the three dimensions and divides by 1000 to convert cm³ to litres.* 

***To improve:** Your litres_to_gallons() function uses the wrong conversion factor. One UK gallon = 4.546 litres, so divide by 4.546.*

***Next step:** Update the divisor on line 5 and re-run — the test panel will confirm whether the output is now correct.* 

&nbsp; 

## Feedback lengths 
Three length settings control how much detail the AI includes. Length is selected alongside style and is independent of it. 

&nbsp; 

**Shorter — one to two sentences:** 

*Good volume calculation. The gallons conversion has an error — check the divisor in litres_to_gallons().* 

**Medium — a short paragraph:** 

*Your volume() function is correct — multiplying the three dimensions and dividing by 1000 gives the right value in litres. The issue is in litres_to_gallons(): the conversion factor you are dividing by needs to match the exact value of one UK gallon in litres. Look up the standard conversion (4.546 litres per gallon) and update that line.* 

**Longer — multiple paragraphs with full explanation:** 

*Your approach to this task is well-structured. You've broken the problem into two clear functions, which makes the code much easier to read and test independently. The volume() function is working correctly — multiplying length × width × height and dividing by 1000 converts cubic centimetres to litres accurately.*
 
*The issue is in litres_to_gallons(). The conversion factor you've used isn't right. One UK gallon is equal to approximately 4.546 litres, which means to convert litres to gallons you should divide by 4.546. Check the value on that line and update it.*
 
*Once you've made the correction, re-run the program. The test panel will show you whether the expected output now matches. This kind of lookup — finding the right conversion factor — is a normal part of real programming work.* 

&nbsp; 

## Feedback Formats
Three formats define the structural shape of the feedback. Format is selected independently of style and length — any combination is valid. 

&nbsp; 

**Standard — prose feedback:** 

*Your volume() function is correct and your code structure is good. The litres_to_gallons() function contains an error — the divisor you are using is not the right value for a UK gallon. The correct figure is 4.546 litres per gallon. Update that value and re-run to check your output.* 

**2 Stars and a Wish — two positives, one area for improvement:** 

⭐ *Your volume() function is correctly structured — well done for separating the two calculations into distinct functions.* 

⭐ *The litres output is accurate — length × width × height ÷ 1000 gives the right result.* 

🌟 *One to improve: Your gallons conversion uses the wrong divisor. One UK gallon is 4.546 litres — update that value in litres_to_gallons().*  

&nbsp; 

**Defaults:** Style = Supportive, Length = Medium, Format = Standard. 





