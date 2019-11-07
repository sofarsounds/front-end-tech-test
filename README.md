# Sofar Sounds Tech Test

The product manager has asked you to build a production ready listing page. Please read the
instructions carefully and do not spend more than one evening on it. Whatever you can't complete
in time, please write up a quick readme file with what you would have done in addition.

Please make sure you include instructions on how to run your project.

## What you will be building

![design](mockup.jpg)

## Product Requirements
- The application should match the design mockup above
- On initial load, no filters should be active and all events should be displayed
- To filter the events, the user has to click the "search" button
- The user can filter by both city and date at the same time
- The "Reset Filters" button only appears when at least one filter is active
- Clicking on "Reset Filters" removes all currently active filters
- When the user clicks on an event card they are redirected to the sofar sounds event page

## Tech Requirements
- Please use React (create-react-app is a great starting point)
- It should be typed (Typescript or Flow)
- When the events are filtered, no new request is being made to the API
- The application should be tested to a degree you feel is necessary for production
- If you can, dockerise the app

You can use anything for styling, however we use [https://styled-components.com](styled-components)
for the new generation frontend.

## API Documentation

You will be developing against our staging api which has some demo data setup.

**Request**
```
GET https://app.staging.sofarsounds.com/api/v2/events
```

**Example Response:**
```
{
  "id": 1,
  "city": "Oxford",
  "image_url": "url-to-the-image.jpg",
  "start_time": "2019-11-07T20:00:00.000Z",
  "arrival_time": "19:30",
  "event_url": "https://url-to-the-event",
}
```

## Assets
In this repository you will find the assets required to replicated the design attached:

- `./img`: The Sofar Sounds logo and a banner image for the header

## Brand
- Typeface: Open Sans
- Brand Colour: #10ad52
