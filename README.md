# recordbleach
# Community Impact
The consequences of having convictions on one's record range from informing law enforcement's opinion of you during a traffic stop to being barred from employment/housing. Under the Texas Code of Criminal Procedure, certain arrest records and convictions are eligible to be removed from someone's record. However, the process is complicated, and many people don't have the tools to get it done.

Enter, Record Bleach! Record Bleach is a full stack platform (react on the front end, rails API on the back end) , that generates the Petition for Expunction and the necessary orders. The app also informs users how to proceed once they have the Petition filled out.

# Tech Stack
### Front end: 
- Backbone.js handles the models and controller and React.js renders the data as a single page app. 
- The logic is designed with Flux architecture with a store and actions module that creates uni-directional data flow.  
- Transpiling is handled with Browserify and Node.js handles the HTTP calls to the RESTful API. 
- Google Fonts

### Back end: 
- Ruby on Rails
- PDF generation via WickedPDF
- PostgreSQL database
- Doorkeeper Oauth for authorization
- SMTP mail 

### Deployment: 
- Heroku
- TravisCI for testing and integration 
- include link to deployment

# Innovation

# Team
- Caitlin Flattery, TIY Houston, JS Cohort May 2016
-  Sarah Swift, TIY Houston, Rails Cohort May 2016
-  Connor Clifton, TIY Houston, JS Cohort September 2016
# Screenshots
