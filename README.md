#Resilient coders authentication site

Allows the user to create an account and login. The user can also upload a file once in the profile page. The use can also write down a comment, and rate that comment with a thumbs up or down. Lastly, the user can delete the comment.

##How it's made:

 *Tech Used:* HTML, CSS, JavaScript,  Node.js, Express, and is coonected to MLab(mongoDB)

 I created this repository by first creating an mlab account and set up my server. Then i downloaded some node modules such as multer for uploading images, and then downloaded my frameworks like passport and express. Lastly,  set up my template engines like ejs. The server and routing was don later to support my site and connect me to the database.  

 Then i went to testing to make sure everything was working perfectly by running it on node server.js.

### Optimization:

If i had more time, i would design the profile page to have the option for the user to log in a user name instead of using their email's as the username. I would also change the sign up page to have an about us so that the users that are signing up can see what they are signing up into. 

## Installation

1. Clone repo
2. run `npm install`

## Usage

1. run `node server.js`
2. Navigate to `localhost:8080`

## Credit

Modified from Scotch.io's auth tutorial
