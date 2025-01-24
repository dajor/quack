Location	Invoice Amount	PO?	Step 1: Who Receives?	Step 2: PO Matching?	Step 3: Validation	Step 3bis: Additional Validation?	Steps 4–5: Booking
Paris	≤ X	No	Person A	N/A (Not used in Paris)	Person A assigns validator (if unclear)	None (Paris does not apply 3bis)	Person C books invoice
Paris	≤ X	Yes	Person A	N/A (Not used in Paris)	Person A assigns validator	None (Paris does not apply 3bis)	Person C books invoice
Paris	> X	No	Person A	N/A (Not used in Paris)	Person A assigns validator	None (Paris does not apply 3bis)	Person C books invoice
Paris	> X	Yes	Person A	N/A (Not used in Paris)	Person A assigns validator	None (Paris does not apply 3bis)	Person C books invoice
Tournon	≤ X	No	Person B	No (no PO)	Person B assigns validator	None (≤ X)	Person C books invoice
Tournon	≤ X	Yes	Person B	Yes (attempt matching)	Person B assigns validator	None (≤ X)	Person C books invoice
Tournon	> X	No	Person B	No (no PO)	Person B assigns validator	Yes (Person C must also approve)	Person C books invoice
Tournon	> X	Yes	Person B	Yes (attempt matching)	Person B assigns validator	Yes (Person C must also approve)	Person C books invoice
