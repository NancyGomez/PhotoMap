# Lab 6 - *PhotoMap*

**PhotoMap** is an app that allows the user to search for locations using the [Foursquare API](https://developer.foursquare.com/docs) and create a pin with an image annotation.

Time spent: **9** hours spent in total

## User Stories

The following **required** user stories are complete:

- [x] User can view a map (+2pt)
- [x] User can take a photo (+1pt)
- [x] User can tag a location (+1pt)
- [x] User can drop a pin with image annotation (+1pt)

The following **stretch** user stories are implemented:

- [x] User sees a custom annotation (+1pt)
- [x] User can see Fullscreen Picture (+1pt)
- [ ] User sees a custom image for the "pin" (+1pt)
- [x] List anything else that you can get done to improve the app functionality! (+1-3pts)

Please list two areas of the assignment you'd like to **discuss further with your peers** during the next class (examples include better ways to implement something, how to extend your app in certain ways, etc):

1. It would be cool to allow the user to simply click on a location on the map to add a pin.
2. Being able to toggle between list mode and map mode might also be interesting when it comes to geotagging an image. Perhaps even allow for a custom message rather than coordinates.

## Video Walkthrough

Here's a walkthrough of implemented user stories:

<img src='https://cdn.discordapp.com/attachments/207408290458501120/423588493470728202/photomapDemo.gif' title='Video Walkthrough' width='' alt='Video Walkthrough' />


## Notes

I was missing one very important line of code, the part where once a location is clicked, we call the locationsPickedLocation function to actually add the pin. I was so confused on why it wasn't working for so long!!!

## License

Copyright [2018] [Nancy and Carlos]

Licensed under the Apache License, Version 2.0 (the "License");
you may not use this file except in compliance with the License.
You may obtain a copy of the License at

http://www.apache.org/licenses/LICENSE-2.0

Unless required by applicable law or agreed to in writing, software
distributed under the License is distributed on an "AS IS" BASIS,
WITHOUT WARRANTIES OR CONDITIONS OF ANY KIND, either express or implied.
See the License for the specific language governing permissions and
limitations under the License.
