
# Test Driven Development


<br>convert_to_int() returns None for the following:

<br>Arguments with missing thousands comma e.g. "178100,301". If you split the string at the comma using "178100,301".split(","), then the resulting list ["178100", "301"] will have at least one entry with length greater than 3 e.g. "178100".

<br>Arguments with incorrectly placed comma e.g. "12,72,891". If you split this at the comma, then the resulting list is ["12", "72", "891"]. Note that the first entry is allowed to have any length between 1 and 3. But if any other entry has a length other than 3, like "72", then there's an incorrectly placed comma.

<br>Float valued strings e.g. "23,816.92". If you remove the commas and call int() on this string i.e. int("23816.92"), you will get a ValueError
