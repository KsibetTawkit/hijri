# hijri
Description
This is a simple API service that provides the current Hijri date. The Hijri calendar is a lunar calendar used to date events in many predominantly Muslim countries, and it's based on the observation of the Moon's phases.

The API is hosted on GitHub Pages and can be accessed via a simple HTTP request. The API endpoint returns the current Hijri date in JSON format.

Usage
To access the API, make a GET request to the following endpoint:

lua
Copy code
https://KsibetTawkit.github.io/hijri/api/hijri-date


The API will respond with a JSON object containing the current Hijri date:

json
Copy code
{
  "hijriDate": "1443-06-30"
}
The date format is YYYY-MM-DD.

Manual Date Update
The Hijri date is updated manually by the administrator. To update the date, you need to modify the getHijriDate() function in the index.html file. After making the necessary changes, commit and push the changes to GitHub.

Technologies Used
HTML
JavaScript
Credits
This API was created by [FREJ Youssef].

License
This project is licensed under the MIT License.