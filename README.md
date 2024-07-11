# Connected Insurance Software Engineer Interview Task

## Overview

This task is designed to test your skills primarily with AWS while also giving us a good idea of how well-versed you are with full-stack development.

## Task Description

Create a Notes application that allows you to take simple, text-based notes. The app must show a form for submitting a note. The app must show all notes, either all at once or paginated. The app must allow for notes to be edited and deleted. Every note should show its title, text content, time created and time updated. Sort all notes by last updated or allow the user to choose the note sorting.

## Requirements

- Your own AWS Account - can be created for free and is free for the first 12 months;
- Your app's front-end must be accessible online (either on S3 or Amplify, custom domain not needed);
- _API Gateway_ deployment with at least 3 lambdas attached to it;
- _DynamoDB_ database for storing the notes;
- Each _Lambda_ must have it's own permissions, specific to the needs of the function;
- AWS CDK or Terraform to be used as your infrastructure-as-code;
- _Node, Python, Golang or Java_ for your backend Lambda code;
- _React_ as your frontend;

## Other things to note

- The task must be completed in about 5-6 hours;
- You can use a boilerplate to get started;
- Automatic deployment is encouraged;
- React metaframeworks allowed - e.g. _NextJS, Astro_;
- State management/fetching/caching/routing libraries allowed (and encouraged) - e.g. _TanStack Router, React Router Dom, TanStack Query, Jotai_;
- Server-Side Rending not required;
- Authentication not required (but encouraged)
