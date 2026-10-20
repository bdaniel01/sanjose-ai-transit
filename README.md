# Transit Translation: AI for Reliable Transit Information

Client: City of San José, public transit accessibility and rider support  
Team: Sumit Chhabra, Brandon Daniel, Santos Sandoval, Andrew Rivas, Aug–Oct 2026  
My part: I helped develop the AI opportunity, test the prototype, and improve how it uses VTA and 511 data to provide more reliable transit information.

## The problem
San José residents who rely on public transportation, especially riders with limited English proficiency, can have difficulty understanding route changes, delays, and other service information. The experience breaks down when riders cannot tell whether the information they are receiving is current, reliable, or understandable in their preferred language.

## What we built
- A multilingual VTA rider-support prototype that accepts written or spoken reports in English, Spanish, Vietnamese, and Punjabi.
- The prototype uses AI-generated responses along with VTA Open Data and the 511 API to give riders current transit information and save reports for later viewing.
- A human still needs to verify reports, decide whether an issue requires action or escalation, and determine how City or VTA staff should respond.

## What I would do next
One gap we found is that the system can still struggle to understand simple rider requests when the user does not provide an exact route, stop, or station identifier. Next, I would improve the natural-language transit lookup so the system can understand requests like “I missed the train at Winchester, when is the next one?” and safely connect them to the correct live transit data.
