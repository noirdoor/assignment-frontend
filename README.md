# assignment-frontend

> Interview assignment for frontend engineers

This will provide you with a better understanding of [Noirdoor](https://noirdoor.com) and affords us some common ground to discuss candidates.

The assignment itself is open-ended, with few actual requirements. We want you to use this occasion to showcase your passions, skills, and experience.

## Goal

You will create an artist profile that plays music from the cloud.

## Tools

These are just a few of the things you will use during the project:

**Tool** | **Purpose**
-------- | -----------
[GitHub](https://github.com/) | Source code storage and version control
[React](https://reactjs.org/) | Framework for user interface components
[Wavesurfer](https://wavesurfer-js.org/) or similar | Music player in the browser
[hapi](https://hapijs.com/) | Node.js framework for creating web servers
[Inert](https://github.com/hapijs/inert) and/or [Vision](https://github.com/hapijs/vision) | Render pages on the server
[Amazon S3](https://aws.amazon.com/s3/) or similar | File storage for music and photos

## Implementation

You will create a hapi server with at least one route, as shown below.

### GET /jane

Returns an HTML profile page for a fictional artist, [Jane Doe](https://en.wikipedia.org/wiki/John_Doe), where we can play her tracks and see any other content she has.

Jane should have multiple tracks. Each track should have a title and at least 60 seconds of audio. Her profile should display at least her username in addition to her tracks.

## Optional / Bonus Points

If you want to show off, here are a few extra things you could do.

 - Beautiful, intuitive, responsive UI / UX design
 - Enforce high-quality code style by using [XO](https://github.com/sindresorhus/xo) and [Tidy](https://github.com/sholladay/eslint-config-tidy)
 - Fetch profile data from an API
 - Use other tools from the React ecosystem, such as [Redux](https://redux.js.org)
 - Write tests with [AVA](https://github.com/avajs/ava), [Intern](https://theintern.io), or similar test frameworks
 - Add routes for other artists (e.g. GET /john)
 - Host the server on [now.sh](https://zeit.co/now) or [Heroku](https://heroku.com) (otherwise use [Localtunnel](https://localtunnel.me) to demo it)

## Checklist

1. [Create a new repository](https://help.github.com/articles/create-a-repo/).
3. Do the assignment work.
4. Commit your work: `git commit -am 'Add some things'`
5. Push commits to GitHub: `git push origin master`
6. Send us the link to your repository.

## Help & Support

We highly encourage you to reach out to us with questions. We do not expect everyone to be familiar with every facet of the assignment. This is a collaborative effort and discussing it may lead you to new, innovative approaches that we have not considered.

## Feedback

We would love to hear your thoughts about this assignment, both before and after completing it. We embrace change and aim to continually improve.

## License

Copyright © [Noirdoor](https://noirdoor.com "Owner of assignment-frontend"). All rights reserved.
