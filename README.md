# KeiKei React Native Challenge

At our software development house nestled in the vibrant city of İstanbul, we embody innovation and a passion for crafting top-notch solutions. We wholeheartedly embrace agile methodologies and adhere to industry best practices throughout the software life cycle.

Our commitment to excellence extends beyond just technology, as we strongly value our company culture and invest in our team. We strive to assemble a group of highly skilled developers, each driven by their love for software development.

**We continue to constantly seek talented individuals to join our team. Please direct all questions regarding employment opportunities to us via :**

- E-mail: [developer@keikei.co](mailto:developer@keikei.co)
- Linkedin: [KeiKei](https://www.linkedin.com/company/keikeico/)

# About the challenge

This assessment requires the creation of a Next.js application utilizing the provided screens as a reference. The task involves retrieving content, sorting, searching and add to favorite, and displaying it in the view.

Please note that while this is a basic exercise, it is expected that the submitted code will exhibit simplicity, proper design, and thorough testing. A keen attention to detail and quality is essential.

# Task

Using the provided screens as a reference, you will need to build a set of React components to render the app. You will also need to request a data feed, filter that data, and use the relevant fields.

We have provided mock user data (https://dummyjson.com/docs/products). While requesting data, we also ask you to use React Query for storing incoming data. So this stored data will be used when you build the app and the components.

Use the returned data to display a page of results that matches the given design.

Please include a README with setup instructions, and any tests or other documentation you created as part of your solution.

You can use frameworks or packages as long as you can explain to us why you chose them.

# Design

You can find the design sample in the [_screens_](/screens) folder. You can work independently as a UI on design. We expect you to be committed to designing when it comes to UX.

# Details

You will need to build the following 2 pages:

1. Product Listing
2. Product Detail

   ## Product Listing

   This will be the page where the products are listed.

   - The products should have sorting functionality according to alphabetic name (default), price increase, and decrease.
   - The search feature should be added and relevant products should only be displayed as the input changes, and the search function should start when at least 3 characters are entered.
   - New products should be loaded as the list scrolls down or click load more button.
   - The case of no search results should be handled.
   - Products can be added to favorites.
   - Products image, price, discounted price, name and discount rate should be displayed.

   ## Product Detail

   - Products image, price, discounted price, description (max 50 word.), name and discount rate should be displayed.
   - Product images should be displayed in a slider.
   - Page rendering should be SSR.

### Note

- The discount rate should be calculated manually from the price and discounted price.
- You can use local storage to store the favorites list.

# Nice to have

1. Use of TypeScript
2. Documentation of the development process through Git commit history.
3. Adherence to production-grade coding standards, including clean, maintainable, and reusable code.
4. Implementation of unit tests using Jest, Cypress and React Testing Library.
5. Use of styled-components for styling.
6. Use of React Query.

# Submission Guidelines

- Please submit your code by sending a GitHub repository link.
- App should be deployed.
