# Labweek24

LabWeek is a decentralized conference convened by network teams in Protocol Las. Taking place in emerging tech hubs around the world, it’s a chance for PL network teams to connect, collaborate and innovate across their fields of expertise. Events span topics such as zk proofs, AI x blockchain, decentralized storage, gaming in Web3, public goods funding, consensus, DePIN, cryptoeconomics, DeSci, and many more.

This year, there are 3 LabWeeks focused on Public Goods Funding, AI and Web3. Join us for a week of summits, research-focused seminars, engineering workshops, unconferences, and happy hours that are open to anyone interested in learning more.

We are using this github repository [this github repository](https://github.com/memser-spaceport/labweek24-events) to coordinate event listings.

## LabWeek24-Web3 - Location & Date

LabWeek Web3 is taking place from Nov 7th, Thursday to Nov 13th, Wednesday at Bangkok, Thailand.

## Past Events
### LabWeek - Public Goods

LabWeek Pulic Goods took place from April 11th, Thursday to April 16th, Tuesday at San Francisco Bay Area, United States.

## Decentralized Conference

A decentralized conference is a series of related events happening around the same place and time, put on by a community. The goal is to enable people and groups to host their own events, loosely coordinating with the rest of the community.

Events can be run in many formats: roundtables, talks with slides, hack sessions, whiteboard sessions, or more. Anyone can submit subevents, just follow the instructions below!

## Events Listing Service

This repo contains all the events being planned and hosted at labweek24 including Public Goods and Web3. But in the future it can hold any events created on behalf of any such decentralized conferences

## Submitting Events using GitHub Pull Requests (PRs)

We encourage you to submit your events via a pull request on github, to do so..

1\. Please download a copy of the template from the path: events_template/sample_event.json

2\. Using the template please fill details related to your event and rename the file as &lt;your-event-name&gt;.json. Make sure you provide a valid filename, because sometimes event names can contain special characters that are not valid for a filename, in that case provide an alternate filename that will be valid, readable and resembles your event name.

3\. Create a branch like event-&lt;your-event-filename&gt;, for eg. 'event-Funding-the-Commons', 'event-Opening-Party'

4\. Place the finished file in the path as mentioned:
    * For Web3 - /events/labweek-24/web3/&lt;your-event-file-name&gt;.json
    * For Public Goods - /events/labweek-24/pg/&lt;your-event-file-name&gt;.json   (Public Goods event is completed and no more accepts new events. Hence this folder is not active)

5\. Create a PR from this branch to 'main' branch

6\. The Labweek team will review and merge your event into the website

## Important points before raising Pull Request

In the events template json file, fields commented as #mandatory are required fields for your event to be approved.

After the pull request is approved, please allow a maximum of 10 minutes for your events to be reflected in labweek schedule.

If you don't have details for the non-mandatory fields, you may not not include those field in your json instead of providing empty values.

For fields like event logo and host logo, make sure you host your images are in 1:1 ratio with maximum of 4MB

Host the images in a publicly accessible place and provide the url for the same. We recommend checking out IPFS-based solutions like web3.storage.

## Editing Events

1\. You've already created your event but want to add or change details, make appropriate changes and raise another pull request to the 'main' branch preferably using the same branch name used when it was created.

2\. The LabWeek event planning team will review and merge your changes.
