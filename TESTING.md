# Testing

Return back to the [README.md](README.md) file.

In this section I will be showing that I have conducted enough testing to legitimately believe that the site works well.
Essentially, in this part, I will be going over all of my project's features to ensure that they all work as intended,
with the project providing an easy and straightforward way for the users to achieve their goals.

## Code Validation

I will use this space to discuss code validation for all of my own code files (where applicable).
I will not validate external libraries/frameworks, such as imported Bootstrap, Font Awesome, etc.

### HTML

I have used the recommended [HTML W3C Validator](https://validator.w3.org) to validate all of my HTML files.

I validated the live pages (each of them) using the deployed URL.
This will give me a custom URL as well, which I will use on my testing documentation.
It makes it easier to return back to a page to validate it again in the future.

| Page | W3C URL | Screenshot | Notes |
| --- | --- | --- | --- |
| Home | [W3C](https://validator.w3.org/nu/?doc=https%3A%2F%2FNap199I.github.io%2FMuay-thai-boxing-Cwmbran%2Findex.html) | ![screenshot](documentation/testing/home-html-validation.png) | Pass: No Errors |
| Contact | [W3C](https://validator.w3.org/nu/?doc=https%3A%2F%2FNap199I.github.io%2FMuay-thai-boxing-Cwmbran%2Fcontact.html) | ![screenshot](documentation/testing/contact-html-validation.png) | Pass: No Errors |
| Schedule | [W3C](https://validator.w3.org/nu/?doc=https%3A%2F%2Fnap199i.github.io%2FMuay-thai-boxing-Cwmbran%2Fschedule.html) | ![screenshot](documentation/testing/schedule-html-validation.png) | Pass: No Errors |
| Facilities | [W3C](https://validator.w3.org/nu/?doc=https%3A%2F%2Fnap199i.github.io%2FMuay-thai-boxing-Cwmbran%2Ffacilities.html) | ![screenshot](documentation/testing/facilities-html-validation.png) | Pass: No Errors |
| Gallery | [W3C](https://validator.w3.org/nu/?doc=https%3A%2F%2Fnap199i.github.io%2FMuay-thai-boxing-Cwmbran%2Fgallery.html) | ![screenshot](documentation/testing/gallery-html-validation.png) | Pass: No Errors |
| confirmation | [W3C](https://validator.w3.org/nu/?doc=https%3A%2F%2Fnap199i.github.io%2FMuay-thai-boxing-Cwmbran%2Fconfirmation.html) | ![screenshot](documentation/testing/confirmation-html-validation.png) | Pass: No Errors |

### CSS

I have used the recommended [CSS Jigsaw Validator](https://jigsaw.w3.org/css-validator) to validate my CSS files.

CSS code validation documentation:

| File | Jigsaw URL | Screenshot | Notes |
| --- | --- | --- | --- |
| style.css | [Jigsaw](https://jigsaw.w3.org/css-validator/validator?uri=https%3A%2F%2FNap199I.github.io%2FMuay-thai-boxing-Cwmbran) | ![screenshot](documentation/testing/css-validation.png) | Pass on personal code: No Errors, the shown error is from the font awesome library as seen in the screenshot and the warnings are from the imported bootstrap and font awesome files. |

## Browser Compatibility

This space will be used to discuss testing of the live/deployed site on various browsers.

Browser testing documentation:

I've tested my deployed project on multiple browsers to check for compatibility issues.

| Browser | Screenshot | Notes |
| --- | --- | --- |
| Chrome | ![screenshot](documentation/testing/chrome-compatability-home.png) | Works as expected |
| Firefox | ![screenshot](documentation/testing/firefox-compatability-home.png) | Works as expected |
| Edge | ![screenshot](documentation/testing/microsoft-edge-compatability-home.png) | Works as expected |
| Samsung internet android (samsung galaxy note 20 ultra) | ![screenshot](documentation/testing/mobile-android-compatability-home.jpg) | Works as expected |
| Brave | ![screenshot](documentation/testing/brave-compatibility-home.png) | Works as expected |
| Opera | ![screenshot](documentation/testing/opera-compatability-home.png) | Works as expected |

## Responsiveness

Here i will discuss testing the live/deployed site on various device sizes and screen sizes.

Responsiveness testing documentation:

I've tested my deployed project on devices and DevTools screen sizes to check for responsiveness issues.

| Device | Screenshot | Notes |
| --- | --- | --- |
| Mobile (samsung galaxy note 20 ultra) | ![screenshot](documentation/testing/mobile-android-compatability-home.jpg) | Works as expected |
| Mobile small (DevTools) | ![screenshot](documentation/testing/mobile-responsive-one.png) | Works as expected |
| Mobile medium (DevTools) | ![screenshot](documentation/testing/mobile-responsive-two.png) | Works as expected |
| Mobile large (DevTools) | ![screenshot](documentation/testing/mobile-responsive-three.png) | Works as expected |
| Tablet (DevTools) | ![screenshot](documentation/testing/tablet-responsive.png) | Works as expected |
| laptop (DevTools) | ![screenshot](documentation/testing/laptop-responsive.png) | Works as expected |
| laptop large (DevTools) | ![screenshot](documentation/testing/laptop-large-responsive.png) | Works as expected |
| Desktop | ![screenshot](documentation/testing/chrome-compatability-home.png) | Works as expected |
| 4K Monitor (DevTools) | ![screenshot](documentation/testing/4k-responsive.png) | Works as expected |

## Lighthouse Audit

Here i will discuss testing the live/deployed site's Lighthouse Audit reports.

Lighthouse testing documentation:

I've tested my deployed project using the Lighthouse Audit tool for all of my pages to check for any major issues.

| Page | Size | Screenshot | Notes |
| --- | --- | --- | --- |
| Home | Mobile | ![screenshot](documentation/testing/lighthouse-home-mobile.png) | Few warnings that have been discussed with my mentor (Tim Nelson), I was told that I cannot do anything about them as it is not from my code. |
| Home | Desktop | ![screenshot](documentation/testing/lighthouse-home-desktop.png) | Few warnings that have been discussed with my mentor (Tim Nelson), I was told that I cannot do anything about them as it is not from my code. |
| schedule | Mobile | ![screenshot](documentation/testing/lighthouse-schedule-mobile.png) | Few warnings that have been discussed with my mentor (Tim Nelson), I was told that I cannot do anything about them as it is not from my code. |
| schedule | Desktop | ![screenshot](documentation/testing/lighthouse-schedule-desktop.png) | Few warnings that have been discussed with my mentor (Tim Nelson), I was told that I cannot do anything about them as it is not from my code. |
| Gallery | Mobile | ![screenshot](documentation/testing/lighthouse-gallery-mobile.png) | Few warnings that have been discussed with my mentor (Tim Nelson), I was told that I cannot do anything about them as it is not from my code. |
| Gallery | Desktop | ![screenshot](documentation/testing/lighthouse-gallery-desktop.png) | Few warnings that have been discussed with my mentor (Tim Nelson), I was told that I cannot do anything about them as it is not from my code. |
| facilities | Mobile | ![screenshot](documentation/testing/lighthouse-facilities-mobile.png) | Few warnings that have been discussed with my mentor (Tim Nelson), I was told that I cannot do anything about them as it is not from my code. |
| facilities | Desktop | ![screenshot](documentation/testing/lighthouse-facilities-desktop.png) | Few warnings that have been discussed with my mentor (Tim Nelson), I was told that I cannot do anything about them as it is not from my code. |
| contact | Mobile | ![screenshot](documentation/testing/lighthouse-contact-mobile.png) | Few warnings that have been discussed with my mentor (Tim Nelson), I was told that I cannot do anything about them as it is not from my code. |
| contact | Desktop | ![screenshot](documentation/testing/lighthouse-contact-desktop.png) | Few warnings that have been discussed with my mentor (Tim Nelson), I was told that I cannot do anything about them as it is not from my code. |
| confirmation | Mobile | ![screenshot](documentation/testing/lighthouse-confirmation-mobile.png) | Few warnings that have been discussed with my mentor (Tim Nelson), I was told that I cannot do anything about them as it is not from my code. |
| confirmation | Desktop | ![screenshot](documentation/testing/lighthouse-confirmation-desktop.png) | Few warnings that have been discussed with my mentor (Tim Nelson), I was told that I cannot do anything about them as it is not from my code. |

## User Story Testing

| User Story | Screenshot |
| --- | --- |
| As a new site user, I would like to find out the location, so that I can join the camp. | ![screenshot](documentation/testing/schedule-location.png) |
| As a new site user, I would like to find out the schedule, so that I can join the camp. | ![screenshot](documentation/testing/chrome-compatability-schedule-two.png) |
| As a new site user, I would like to contact the camp administration, so that I can ask any questions I may have. | ![screenshot](documentation/readme/contact-form.png) |
| As a new site user, I would like to find the price of the sessions, so that I can pay the correct amount when I join. | ![screenshot](documentation/testing/price.png) |
| As a new site user, I would like to find information on the sessions, so that I can pick which ones to attend. | ![screenshot](documentation/testing/session-information.png) |
| As a returning site user, I would like to find the schedule, so that I can make sure there has been no changes. | ![screenshot](documentation/testing/chrome-compatability-schedule-two.png) |
| As a returning site user, I would like to look at the gallery, so that I can show people my friends and what I am a part of. | ![screenshot](documentation/readme/gallery-scrn-sht-one.png) |
| As a returning site user, I would like to use the contact section, so that I can inform the instructor that I wont be able to make a session. | ![screenshot](documentation/readme/contact-form.png) |
| As a site administrator, I should be able to have our information displayed, so that I can update new and existing members on times, locations and prices. | ![screenshot](documentation/testing/chrome-compatability-schedule-two.png) |
| As a site administrator, I should be able to have images on the site, so that I can so potential new recruits can see what we do or so existing members can show friends. | ![screenshot](documentation/readme/gallery-scrn-sht-one.png) |
| As a site administrator, I should be able to recieve and answer queries by email, so that I can assist anyone looking to join or any existing members issues. | ![screenshot](documentation/readme/contact-form.png) |

## Bugs

I have not come across any bugs in development.

### GitHub **Issues**

I have not had any issues within GitHub.

**Fixed Bugs**

None as I have not come across any in my testing or development.

**Open Issues**

There are no open issues as i have not had any to open or close.

## Unfixed Bugs

There are no remaining bugs that I am aware of as I did not find any in the first place.
