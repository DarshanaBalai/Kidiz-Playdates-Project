# Kids Play date - Let's play !!

This is Kidz playdate website and targetted audience is family with kids. It will help to create playful society for kids, different age group kids from different location can come together. It will address some real issues in the society like

- Loneliness with the Kids
- Address social awareness

## Responsive Website
Kidiz Playdates website is designed to be responsive website allowing visitors to view on a range of devices. 

![](https://github.com/DarshanaBalai/Kidiz-Playdates-Project/assets/130803590/dd336f77-2102-4980-967d-cad040e289c7)
## Feature

This website provides platform for the end user mainly parents or organizer. User will be able to

- Register/ Login onto the platform

User can signup and provide some basic information, this information will be used to contact in later stage.

![](https://user-images.githubusercontent.com/130803590/236688754-97c26e83-3637-4702-8ffe-652c775b2ce7.png)

- Event Gallery

Gallery will showcase all the events, at the moment it will show from all locations and search will be embedded in the future.

![](https://github.com/DarshanaBalai/Kidiz-Playdates-Project/assets/130803590/8184fd3c-3034-4eac-85e0-c2cbd6d5960e)

- Participate in existing events

On Event gallery, all availabe events will be listed. User can participate and click on `Interested` on listed event as seen in above snapshot.

- Start new event

New event can be started using `Start Event` on Event Gallery page. As part of Event, user need to provide event name, description about event and venue of the event. This will be enhanced to provide targetted age group like 3-6 years and date, time will be added in the event.

![](https://github.com/DarshanaBalai/Kidiz-Playdates-Project/assets/130803590/814c18fa-7c5a-45cd-94de-7e036a8c52a4)

## Other pages

- Landing page

![](https://github.com/DarshanaBalai/Kidiz-Playdates-Project/assets/130803590/f4fbac5d-e282-4f80-bb5c-57905999e1fa)

- Photo Gallery

It shows some snaps from different events and just give the user/ kid positive vibes to join new event as well adding some excitement for new users and encourage the kids to participate in the new event.

![](https://github.com/DarshanaBalai/Kidiz-Playdates-Project/assets/130803590/63668a76-d2b1-45d1-ba9a-0505c7f78e35)

- All Pages on the website have:
- A responsive navigation bar at the top which allows the user to navigate through the site.
- A footer which contains social media icon links to instagram, facebook and twitter. Icons were used to keep the footer clean and because they are universally recognisable.

## Features Left to Implement

- Adding date, time and age on Event details page
- Search, filter based on location or some search query on Event gallery

## Testing

Testing is done to test frontend like html, css.

- Validator Testing

  - HTML - No errors were returned when passing through the official W3C validator
    ![](https://github.com/DarshanaBalai/Kidiz-Playdates-Project/assets/130803590/7177fb3f-a121-4f85-84fa-677dbf84992d)
  - CSS - No errors were found when passing through the official (Jigsaw) validator
    ![](https://github.com/DarshanaBalai/Kidiz-Playdates-Project/assets/130803590/4604b261-8803-452c-b1e1-3525eac621b0)

- Problems

  - When running `python3 -m http.server` on codeanywhere, I got `Address already in use` error.
    Resoultion: When I researched and read about it, I came to know that it's because port issue. We are running the python
    program on 8000 port and somehow old port is still in use. I killed that process using some linux commands 1. ps -fA | grep python - find all processes with python in name and get process id say pid 2. Kill -9 pid (pid collected in step 1) - this will kill old process.

        I referred few sources for the same, one of them was `https://stackoverflow.com/questions/4465959/python-errno-98-address-already-in-use`

  - I updated some of html files but it was not reflecting and then I found I need to hard refresh the website page with (cmd + shift + r) to reload.

## Techstack

- HTML
- CSS
- Github pages for deployment.

## Deployment

Github Pages was used to deploy the live website. The instructions to achieve this are below:

1. Log in (or sign up) to Github.
2. Find the repository for this project, Bully-Book-Club.
3. Click on the Settings link.
4. Click on the Pages link in the left hand side navigation bar.
5. In the Source section, choose main from the drop down select branch menu. Select Root from the drop down select folder menu.
6. Click Save. Your live Github Pages site is now deployed at the URL shown.
