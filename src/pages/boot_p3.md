

## MODULE 1
In this module we define and plan our application, understanding the problem, the architecture we'll need, the tech choices. We'll introduce and install PocketBase locally, and we'll start doing some initial data modeling for our app, creating collections.

## MODULE 2
We'll introduce Astro, we'll create our Astro-based website, with a Git repository so we can easily track progress. We'll then create our homepage, blog, etc, for the site part. We'll use Tailwind to build a layout that is responsive and handles dark and bright mode. We'll learn how to use Astro components to compose the HTML, server side, using JavaScript imports. We'll also learn how to create dynamic routes and how to use content collections to build the product blog. Finally we'll push the site to GitHub.

## MODULE 3
In module 3 we'll start working on the app part of our SaaS. We'll create a dashboard and we'll start fetching data from PocketBase and we'll show it in the app. We'll add a way to create a new project using a modal window. We'll introduce htmx and Alpine.js and I'll show you how to use them to perform actions and make our app dynamic. We'll let people add a task to the project, and we'll list the projects tasks.

## MODULE 4
In module 4 we'll first add a sidebar that lists all projects, with a hamburger menu to show it on mobile too. We'll use htmx's `hx-boost` feature to make the app feel faster. Then we'll add a way to mark tasks as done, edit the project status, edit the project's name, and edit the task text. We'll also add a way to delete a project and a task. We'll add the ability to star a task, and we'll then show starred tasks coming form all projects in the dashboard.

## MODULE 5
In module 5 we'll introduce authentication to our app. We'll protect all routes that require auth, and we'll start creating user-specific data. All projects, tasks, etc, will be associated with a user. We'll also add forms to sign up and sign in, and reset the password. We'll let people logout too. We'll add form protection using Cloudflare Turnstile.

## MODULE 6
In module 6 we'll make it possible to upload images to a task via drag and drop, and we'll let users delete them too. We'll also take care of security across our app, talk about XSS, introduce a Content Security Policy. We'll then introduce some error handling across our requests.

## MODULE 7
In module 7 we'll handle showing starred tasks before non-starred ones from PocketBase, we'll handle resource not found issues, we'll see how to handle htmx connection errors, we'll add some more security checks by setting htmx to only allow requests to our domain and using the correct headers and origin to prevent possible abuse.

## MODULE 8
In module 8 we'll create teams. We'll create the teams collection in PocketBase, show a form to let people create a team, we'll show teams in the sidebar, we'll allow people to activate a team by paying the subscription on Stripe, we'll add projects to the team, list team projects, list starred team tasks, we'll also list team projects in the sidebar, and do some work on the sidebar to highlight the active project and team.

## MODULE 9
In module 9 we'll keep working on teams. We'll add invites, we'll list team members,s we'll handle accepting/rejecting invites, we'll send emails through PocketBase, we'll handle changing a team name, subscription cancellation, we'll freeze the projects if people stop paying, and we'll add a link to manage the subscription on Stripe to update payment method. We'll also handle team deletion and clearing the data.

## MODULE 10
In module 10 we'll create an activity page where people can see what happened in their projects, and we'll create a team dashboard where people can see what happened in their team projects at a glance. We'll add a way for people to change their username, and in the filters list we will add a way to filter by user, by team, by project. We also show tasks done today in the personal/team dashboard, we'll do some optimizations and we'll add a service worker to show a offline splash screen. We'll also allow the app to be installed as PWA.

## MODULE 11
In module 11 we'll take care of caching and performance. We'll prevent 2 roundtrips with HX-Redirect, we'll optimize creating a project and task, we'll prevent double click of the buttons, we'll cache modals, we'll cache assets, we'll add loading spinners.

## MODULE 12
Module 12 is about deployment. We'll deploy our app to Railway using Docker, and we'll handle all we need to go from local dev mode to production.