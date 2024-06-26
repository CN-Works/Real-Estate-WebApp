<div align='center'><h1>Real Estate Web App</h1>
</div>

This a public preview of my projet for a reak estate website using JavaScript and Symfony 6.
<br/>
For legal reasons I can't publish the whole project, but here are a few pieces of code to give you an idea about how I completed the tasks.
<br/>
Below are images of the site and code snippets and others details about the application's main functions.

<div align='left'><h1>Home page</h1>
</div>
<img src="https://github.com/CN-Works/Real-Estate-Website/assets/92865037/c20dacf2-e2bb-4a38-a35a-2789e4445f4e"/>

<div align='left'><h1>Loading animation</h1>
</div>
<img src="https://github.com/CN-Works/Real-Estate-WebApp/assets/92865037/97d5ccb5-fd2a-4374-9177-c434790586c9"/>

<div align='left'><h1>Properties</h1>
</div>

<img src="https://github.com/CN-Works/Real-Estate-Website/assets/92865037/c7e2c5da-c379-46bf-9675-e1d2b1050fb3"/>

<img src="https://github.com/CN-Works/Real-Estate-Website/assets/92865037/c8dd10e8-ea06-476d-8ec3-80b7d08b4293"/>


<h3>Related features</h3>
<br/>
- Creating properties with images import (Banners, images)
<br/>
- Editing, Deleting (if Admin)
<br/>
- Show informations (rooms, bathrooms, description...)
<br/>
- Like button
<br/>
- A nice and smooth caroussel

<div align='left'><h1>Profile</h1>
</div>

<img src="https://github.com/CN-Works/Real-Estate-Website/assets/92865037/43a8c70a-a49e-4d96-b267-229fa05b80fe"/>

<img src="https://github.com/CN-Works/Real-Estate-WebApp/assets/92865037/85679177-6fc1-46e1-ad81-a4293a8a6597"/>


<h3>Related features</h3>
<br/>
- Creating an account
<br/>
- Editing it, changing the profile picture
<br/>
- Access to liked properties
<br/>
- Meetings overview

<div align='left'><h1>Meetings</h1>
</div>

<h3>User side</h3>
<img src="https://github.com/CN-Works/Real-Estate-Website/assets/92865037/5c0ecba3-c26f-4705-bc0c-484bb620220d"/>
<h3>Real Estate side</h3>
<img src="https://github.com/CN-Works/Real-Estate-Website/assets/92865037/301b98bd-997c-4a87-8682-ed11375b032f"/>
<img src="https://github.com/CN-Works/Real-Estate-Website/assets/92865037/37cf683f-87b6-48d9-8070-8e9aae7088df"/>

<div align='left'><h1>Code snippets</h1>

<h3>Uploader Service and File management</h3>
<img src="https://github.com/CN-Works/Real-Estate-WebApp/assets/92865037/0145022d-507b-48fc-846d-efca13f8969f"/>
<img src="https://github.com/CN-Works/Real-Estate-WebApp/assets/92865037/00490b93-902d-4239-af20-ee5f280b517d"/>

<br/>
- Uploading images from a form view.
<br/>
- Saving them into objects.
<br/>
- Deleting them when they're no longer used.
<br/>

<h3>Meetings management</h3>

<img src="https://github.com/CN-Works/Real-Estate-WebApp/assets/92865037/a3f12128-035a-476d-b663-1fbe5e9e8206"/>

<img src="https://github.com/CN-Works/Real-Estate-WebApp/assets/92865037/f8920d3a-22f5-428f-b33d-dc58ab9e4b83"/>

<br/>
- Verifying user's date input, cancel meeting unwhitelisted dates (sunday for exemple) or previous days.
<br/>
- Storing meetings demands in database, then accepting them and choosing the time (datetime) after a phone call with the client.
<br/>
- Then, displaying all the meetings in the calendar using JSON to convert data from php table to javascript (for FullCalendar JS).
<br/>

