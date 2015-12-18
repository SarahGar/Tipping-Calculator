# Tipping-Calculator
CodePath University PreWork- Sarah Garrow



# Pre-work - Tipping Calculator

Tipping Calculator is a tip calculator application for iOS.

Submitted by: Sarah Garrow

Time spent: 20 hours spent in total

## User Stories

The following **required** functionality is complete:
* [x] User can enter a bill amount, choose a tip percentage, and see the tip and total values.

The following **optional** features are implemented:
* [x] Settings page to change the default tip percentage.
* [ ] UI animations
* [ ] Remembering the bill amount across app restarts (if <10mins)
* [ ] Using locale-specific currency and currency thousands separators.
* [ ] Making sure the keyboard is always visible and the bill amount is always the first responder. This way the user doesn't have to tap anywhere to use this app. Just launch the app and start typing.

The following **additional** features are implemented:

- [x] Added app icon
- [x] Allowed for user to input number of people to split the bill 

## Video Walkthrough 

Here's a walkthrough of implemented user stories:

<blockquote class="imgur-embed-pub" lang="en" data-id="aFAAhMj"><a href="//imgur.com/aFAAhMj">Tipping Calculator Demo</a></blockquote><script async src="//s.imgur.com/min/embed.js" charset="utf-8"></script>

GIF created with [LiceCap](http://www.cockos.com/licecap/).

## Notes

I have very little coding experience. I took a basic programming course a couple years ago and learned some C++. The tutorial was very nice in setting up the basic functionality of the tipping calculator. I spent most of my time working to get the Setting View Control to pass data to the View Controller . I did a lot of googling to help me, but went down the wrong path. I thought I needed to use prepareForSegue to pass information. I emailed Charlie Hielger and he informed me that I needed to use NSUserDefaults. Once I had this information I was able to do more researching and successfully implement this in my code. I added an additional feature that would allow the user to input the number of people to split a bil.

## License

    Copyright [yyyy] [name of copyright owner]

    Licensed under the Apache License, Version 2.0 (the "License");
    you may not use this file except in compliance with the License.
    You may obtain a copy of the License at

        http://www.apache.org/licenses/LICENSE-2.0

    Unless required by applicable law or agreed to in writing, software
    distributed under the License is distributed on an "AS IS" BASIS,
    WITHOUT WARRANTIES OR CONDITIONS OF ANY KIND, either express or implied.
    See the License for the specific language governing permissions and
    limitations under the License.
