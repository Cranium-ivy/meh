# Prototype Feedback README

This write-up answers the task brief using my project, **Greenfield Local Hub**.

## What the prototype is

My prototype is a Django marketplace website for local food sellers and customers.

It has two main types of users:

- customers, who can browse products and add items to a cart
- farmers, who can log in and manage their own product listings

At the moment, the working parts of the prototype are:

- signup, login and logout
- customer and farmer dashboards
- product browsing with search
- add to cart
- farmer product create, edit and delete
- accessibility controls like text size and text colour

The navigation also still includes **Track Orders** and **Loyalty Rewards**, but those are only there as future development pages for now.

## Why I need feedback

The reason I need feedback is to see how effective the prototype actually is before improving it further.

I want to know things like:

- do people understand what the website is for?
- is it easy for a customer to browse products and use the cart?
- is it easy for a farmer to manage products?
- does the layout make sense?
- does the project feel technically well structured?
- what should I improve next?

## Materials I would prepare to gather feedback

To gather feedback properly, I would prepare different materials for technical people and non-technical people.

### For a technical audience

For example:

- tutor
- teacher
- developer
- another student who understands programming

The materials I would use are:

1. **The live prototype**
   - I would run the project locally using:

   ```powershell
   python manage.py runserver
   ```

2. **The main README**
   - this explains what the project is, what it does, and how to run it

3. **The implementation documentation**
   - this explains the main changes I made to the system

4. **The project explanation guide**
   - this helps me explain the code structure and design decisions clearly

5. **A short technical demo plan**
   - show login and role-based dashboards
   - show farmer product management
   - show customer browsing and cart use
   - explain that tracking and rewards are future features
   - show that the project passes tests

### For a non-technical audience

For example:

- users
- classmates
- client
- family members

The materials I would use are:

1. **A simple walkthrough**
   - home page
   - products page
   - cart page
   - farmer dashboard

2. **A plain explanation**
   - what the site is for
   - who it is for
   - what customers can do
   - what farmers can do
   - what features are planned later

3. **A short feedback form**
   - quick ratings
   - simple written comments
   - suggestions

4. **Observation notes**
   - I can write down where people get stuck or confused

## How I would demonstrate the prototype

## Demonstration for a technical audience

If I was showing the project to a technical audience, I would focus more on how it was built.

I would talk about:

- the Django project structure
- the custom user model
- customer and farmer roles
- the session cart
- reusable templates with `base.html`
- product CRUD
- tests, migrations and maintainability
- why some features were left as future development

### Technical demo steps

1. Start the server.
2. Explain the project folders like `accounts`, `marketplace`, `templates`, and `static`.
3. Show how different users see different dashboards.
4. Show how a farmer can add, edit and delete products.
5. Show how a customer can browse products and add them to the cart.
6. Explain why Track Orders and Loyalty Rewards are only placeholder pages at the moment.
7. Run:

```powershell
python manage.py test
```

### Questions I would ask the technical audience

- Is the project structure clear?
- Does the role-based approach make sense?
- Is using a session cart acceptable for this kind of prototype?
- Are the views and templates easy to follow?
- Does the simplified scope make sense for a student project?
- What should I improve first in the next version?

## Demonstration for a non-technical audience

If I was showing it to a non-technical audience, I would explain it more simply and focus on whether it is easy to use.

I would focus on:

- whether the purpose of the site is clear
- whether the navigation makes sense
- whether browsing products feels easy
- whether the farmer pages are understandable
- whether the layout is simple and readable

### Non-technical demo steps

1. Show the home page and explain what the website does.
2. Show the products page and how search works.
3. Add a product to the cart.
4. Open the cart page.
5. Show the farmer dashboard and explain product management.
6. Open Track Orders and Loyalty Rewards and explain that they are planned for future development.

### Questions I would ask the non-technical audience

- Was the website easy to understand?
- Was it clear what customers can do?
- Was it clear what farmers can do?
- Was it easy to browse products?
- Was it easy to use the cart?
- Did anything confuse you?
- What would you want me to add next?

## My plan for gathering feedback

My plan would be to gather feedback from both technical and non-technical people so I get a balanced view.

### Audience groups

- technical audience: about 2 to 3 people
- non-technical audience: about 3 to 5 people

### Methods I would use

- live demonstration
- short questionnaire
- short verbal questions
- observation notes

### Tools I would use

- the running prototype in a browser
- Microsoft Forms or Google Forms
- a notebook, document or spreadsheet for recording feedback
- a simple checklist of tasks for users to try

### Session structure

Each session would be done in this order:

1. briefly explain the project
2. show the main features
3. let the person watch or try the prototype
4. ask them questions
5. record their answers clearly

## How I would use the materials to gather feedback

I would use the materials in a practical way:

- the live website would be the main thing being tested
- the demo script would help me stay organised
- the plain explanation would help non-technical users understand what they are looking at
- the form would collect ratings and written comments
- the notes sheet would let me record things like hesitation, confusion, or positive reactions

This would make the feedback more useful because it would be planned and structured instead of random.

## How I would record the feedback

To make the feedback suitable for analysis, I would record it in a simple table like this:

| Participant ID | Audience Type | Area Reviewed | Feedback | Issue Type | Priority | Next Step |
|---|---|---|---|---|---|---|
| T1 | Technical | Dashboard structure | Clear overall, but repeated logic could be cleaned up | Technical structure | Medium | Refactor repeated context code |
| N1 | Non-technical | Products page | Easy to browse | Positive | Low | Keep as it is |
| N2 | Non-technical | Cart page | I was not sure where to go after adding an item | Navigation | High | Add clearer links |

### Issue types I would use

- usability
- navigation
- layout
- technical structure
- missing feature
- accessibility
- clarity of content

### Priority levels I would use

- High
- Medium
- Low

## Example feedback questions

### Technical audience

I could ask them to rate:

- code structure
- readability
- maintainability
- use of Django features
- future development readiness

Then I would ask:

- What is the strongest technical part of the prototype?
- What is the weakest part?
- What should I improve next?

### Non-technical audience

I could ask them to rate:

- ease of navigation
- page clarity
- readability
- ease of browsing products
- overall usefulness

Then I would ask:

- What did you like most?
- What confused you?
- What would you want added next?

## How I would analyse the feedback

After collecting feedback, I would:

1. group similar comments together
2. separate technical feedback from non-technical feedback
3. look for issues that came up more than once
4. decide which problems are high, medium, or low priority
5. use that to plan the next version of the project

For example:

- if several users say the cart flow is confusing, that becomes a priority usability fix
- if technical reviewers say some code is repeated, that becomes a refactoring task
- if multiple people ask for real order tracking, that supports building that feature in the future

## What this feedback would help me improve

Based on the current version of the prototype, the feedback would help me decide whether to improve:

- navigation
- cart flow
- dashboard clarity
- product presentation
- future features like real order tracking
- future features like real loyalty rewards
- general usability

## Final answer to the brief

For this Greenfield Local Hub prototype, I would gather feedback by preparing suitable materials for both technical and non-technical audiences, demonstrating the prototype in different ways depending on the audience, collecting feedback using forms, questions and observation notes, and recording the results in a table so I can analyse them properly.

This would help me judge how effective the prototype is now and what should be improved in the next iteration.
