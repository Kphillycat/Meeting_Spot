 # Meeting Spot!

![Meeting Spot]("public/img/SocialRadius_screenshot.png")

Meeting Spot is a web application that allows you and your friends to input their locations and find a common meeting place based on transit time. You can also input other parameters like type of place, time of meeting and price point.

## Demo

Visit http://socialradius.herokuapp.com/

## Command Line

Bundle the Gemfile

```ruby
bundle install
```

Migrate your database
```ruby
rake db:migrate
```

Run the server

```ruby
rails s
```

Application will be running on http://localhost:3000/

## How to use Meeting Spot

Input the a name for the map and the city you want the Meeting Spot to appear at.

![Meeting Spot]("public/img/SocialRadius_screenshot.png")

Input the addresses where each of the attendees will be traveling from.

![Meeting Spot]("public/img/SocialRadius_addresses.png")

Once you identify your preferences for type of location (Bar, Cafe, Restaurant), Time and Date of Meeting and Maximum Price point click the "Find Meeting Place" button. 

The suggested meeting places will populate to the right of the map.

![Meeting Spot]("public/img/SocialRadius_found_places.png")

Happy Meeting!