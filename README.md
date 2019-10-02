# nearestCarparkInfo API
This repository is the API used for the [Understanding Web Development Course](https://www.cscollege.gov.sg/programmes/pages/display%20programme.aspx?epid=88mh6oplhphm3pdmkhkcpp5smo) created and run by the [Open Government Products](open.gov.sg) team. Course notes available at https://opengovsg.github.io/live-parking-info

In addition to course content, this repository contains the API that participants use during the course (documentation [here](https://opengovsg.github.io/carparks-near-me/)). 

One of the goals of the course was to let participants walk away with a website that they created by the end of the course. This strong sense of empowerment, we believe, would spur them on to find out more about web development beyond the course. However, we realized across multiple runs that our API section would be quite tough for participants and leave them confused instead of enlightened. In order to find out the nearest carpark to you, you'd need to get the X and Y coordinates of your location from OneMap's API and an exhasutive list of carparks and availability from Data.gov.sg's API to calculate which carpark is closest to you.

We have now abstracted both API calls and implementation logic away from the participants and presented them with one simple API call, similar to the [Chuck Norris Joke API](https://api.chucknorris.io/) that is used in other web introductory courses. The code for the API can be viewed in `index.js` file and the API documentation can be edited in the `swagger.yml` file.

For participant and public consumption, we have deployed the following code on Heroku.

# Attribution

This course is distributed under the MIT license. While you are free to use it and create derivative works as you see fit, 
we would love to be duly attributed. This could be done by flashing a slide at the workshop that describes who we are, accompanied with a short verbal statement crediting us as the original authors.

# Get in touch

If you are interested in working with us to improve digital literacy in government and the nation, 
we would love to hear from you! Reach us at https://open.gov.sg/contact-us/
