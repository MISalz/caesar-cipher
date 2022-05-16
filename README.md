LAB - Class 18
# Project: caesar_cipher
**Author:** Michelle Salazar
----
## Problem Domain

Feature Tasks and Requirements

<ul><li>
Create an encrypt function that takes in a plain text phrase and a numeric shift.
</li><li>
the phrase will then be shifted that many letters.
E.g. encrypt(‘abc’,1) would return ‘bcd’. = E.g. encrypt(‘abc’, 10) would return ‘klm’.
</li><li>
shifts that exceed 26 should wrap around.
</li><li>
E.g. encrypt(‘abc’,27) would return ‘bcd’.
</li><li>
shifts that push a letter out or range should wrap around.
</li><li>
E.g. encrypt(‘zzz’,1) would return ‘aaa’.
</li><li>
Create a decrypt function that takes in encrypted text and numeric shift which will restore the encrypted text back to its original form when correct key is supplied.
</li><li>
create a crack function that will decode the cipher so that an encrypted message can be transformed into its original state WITHOUT access to the key.
</li><li>
Devise a method for the computer to determine if code was broken with minimal human guidance.
</li></ul>

## Implementation Notes

<ul><li>
In order to accomplish a certain task you’ll need access to a corpus of English words.
</li><li>
A search on something like python list of english words should get you going.
</li></ul>

## Links and Resources

• back-end server url (when applicable)<br>

• front-end application (when applicable)

## Setup

cat requirements.txt
pip install pytest

**PORT -** Port Number

**DATABASE_URL -** URL to the running Postgres instance/db

*How to initialize/run your application (where applicable)*

• e.g. python main.py

## How to use your library (where applicable)
pip freeze > requirements.txt

## User Acceptance Tests
The application must:
<ul><li>
encrypt a string with a given shift
</li><li>
decrypt a previously encrypted string with the same shift.
</li><li>
encryption should handle upper and lower case letters.
</li><li>
encryption should allow non-alpha characters but ignore them, including white space.
</li><li>
decrypt encrypted version of It was the best of times, it was the worst of times. WITHOUT knowing the shift used.
</li><li>
refer to supplied unit tests.
</li></ul>

## Links

---
*Notes:*
