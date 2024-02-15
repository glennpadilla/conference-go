This is Conference-go.
The Django project is in the conference_go directory. The Django apps are installed in the settings.py file.

There are four Django apps:
1. accounts contains a custom User model
2. attendees contains the Attendee and Badge models. It has two URL configurations: one to list the attendees for a conference, and one to get the details for a specific attendee
3. events contains the Conference, Location, and State models. It has four URL configurations:
- one to list the conferences
- one to get the details of a conference
- one to list the locations
- one to show the detaisl of a location
4. presentations contain the Presentation and Status models:
- one to get a list of presentations for a conference
- one to get the details for a presentation

api_urls.py and api_views.py are used to specify the URLs and build the views that return HTML responses. These files are creating path entries and include the correct module from settings.py


