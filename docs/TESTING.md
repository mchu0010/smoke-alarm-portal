# TESTING.md

A list of tests to be included in future unit tests:

## User data entry:

- Front page loads
- Can enter valid data in each field
- Errors show up correctly for invalid data
- Focusing and unfocusing in a formfield without inputting data causes
  correct tooltip to come up 
- Submit button sends request:
  - nonexistent zip code gets "Sorry, we didn't recognize..."
  - existent zip without region gets "Sorry" with correct county
  - zip in inactive region gets "Sorry" with correct county
  - zip in active region gets "Thank you" with ID (serial number)
- "Thank you" or "Sorry" page shows up as expected
- Email is sent to correct person/people

## Language:

- language switcher is visible
- changing the language works on the front page
- the language remains consistent from the home page to the sorry and
  thank you pages.
- tooltips and default text show up in the correct language

## Admin report(s):

- all requests show up (nonexistent zip, existent zip, inactive zip,
  active zip)
- sort by all options
- search by name
- search by start date
- search by end date
- search by start and end date
- search by all regions
- search by a region
- change pagination

