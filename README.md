# Specialized Redux Bootcamp - Capstone Project

<p align="center">
    <a href="https://academy.wizeline.com/">
    <img src="academylogo.png"
         alt="Academy" style="height: 18px; border-radius: 4px">
</p>

<p align="center">
  <a href="#overview">Overview</a> •
  <a href="#project">Project</a> •
  <a href="#instructions">Instructions</a> •
  <a href="#deliverables">Deliverables</a> 
</p>

---

## Overview

<table>
<tr>
<td>

The purpose of this project is for you to demonstrate your knowledge acquired in the **Specialized Redux Bootcamp**.

With this E-commerce project, you will have the opportunity to show your **React** skills by adding functionality and applying **Redux Toolkit**, the toolset for global state management that you have learned in this Bootcamp.

Here you will find all the instructions to complete and deliver your **Redux Capstone Project**.

</td>
</tr>
</table>

## Project

<table>
<tr>
<td>

This repository contains the minimum structure of an E-commerce called **WizeStore** with three modules:

1. Login
1. Products
1. Cart

Here is the [link](https://redux-shopping-cart-gules.vercel.app/login) to the demo application.
<img width="960" alt="WizeStore" src="https://user-images.githubusercontent.com/88999796/175117974-122bcd92-21a8-4b08-8eab-6f536c1cd7c0.png">

</td>
</tr>
</table>

## Instructions

<table>
<tr>
<td>
Before starting:

1. Fork this repository to your **GitHub** account and make it a public repository.
1. Invite your mentor as a contributor to your **GitHub** project.
1. You can message your mentor to have 1:1 sessions, or you can use the [**Slack channel**](https://wizelineacademy.slack.com/archives/C03KCQ0CPDM) if you feel stuck, want to share your progress, or need some feedback.
1. Get started with the requirements specified below.

</td>
</tr>
</table>

## Deliverables

All deliverables are cumulative, and for each delivery:

- Use **React Hooks** in your components.
- Use **styled-components** for component styles or any other _CSS_ library or framework like **Material UI** or **Bootstrap**.
- Ensure that your application does not log warnings and errors in the browser console.
- Create a _pull request_ (_PR_) for each _deliverable_ to merge into your _main_ **GitHub** branch.
- Add your mentor as a reviewer of your _PRs._ Your mentor will review and leave feedback on your progress.

### Dates

You must submit three deliverables on the following dates:

1. The **first delivery** is before 10 AM (CST) on Monday, July 4th, 2022.
1. The **second delivery** is before 10 AM (CST) on Monday, July 11th, 2022.
1. The **third delivery** is before midnight (CST) on Friday, July 15th, 2022.

### First delivery

In this assignment, you will create the **Products** module.

#### Requirements

1. Create a new branch with the name "_feat/deliverable1_" derived from "_main_" on your forked repository.
1. Create the **Products** module** and fill it with data obtained from this [mock file](http://public/data/products.json)**.\*\*

Design your user interface (_UI_). You can base it on the layout proposed in this [demo](https://redux-shopping-cart-gules.vercel.app/products), or if you want, implement any other design, but include the following elements:

1. A grid of products, and for each element on the grid, show the following elements:

- One _image_ of the product.
- The product _name_.
- The first _category_.
- The product _price_.
- A _button_ without functionality with the text "**Add to cart"**.

1. Deploy your app on **Netlify**, **Firebase**, **Heroku**, **GitHub Pages**, or any other hosting service you prefer.
1. When you meet all _Acceptance Criteria_ (_AC)_ of this first deliverable, fill out this [form](https://docs.google.com/forms/d/e/1FAIpQLSeXxiqrN2BjLTVF79xI6OdCedGgaw_6pxWOrNEoxDkEaExEWA/viewform) and add the _URL_ of your _PR_ and the _URL_ of your deployment.

#### Acceptance Criteria

The following is the list of _evaluation criteria_ for your first deliverable:

| **Acceptance criteria** | **Description**                                                                                                                                                                                                                                                 | **Points for completed** |
| :---------------------- | :-------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- | :----------------------- |
| 1                       | Your **Products** module reads data products correctly from this [mock](http://public/data/products.json)[ file](http://public/data/products.json).                                                                                                             | 30                       |
| 2                       | Your **Products** module displays your _CSS styles_ correctly.                                                                                                                                                                                                  | 20                       |
| 3                       | <p>For each product, the following elements render correctly:</p><p>A. One _image_ of the product.</p><p>B. The product _name_.</p><p>C. The first _category_.</p><p>D. The product _price_.</p><p>E. The "**Add to cart**" _button_ without functionality.</p> | 50                       |

### Second delivery

In this assignment, you will create both the **Cart** and **Login** module.

#### Requirements

1. Create a new branch with the name "_feat/deliverable2_" derived from "_main_" on your forked repository.
1. Create the **Cart** module and fill it with data obtained from the same [mock file](http://public/data/products.json)\*\* used in the first delivery. Just take a few products and add the quantity of one to each.

Design your _UI_. You can base it on the layout proposed in this [demo](https://redux-shopping-cart-gules.vercel.app/cart), or if you want, implement any other design, but include the following elements:

1. A _heading_ with the text "**Shopping Cart"**.
1. A grid with the products of the cart, and for each product on the grid, show the following elements:

- A _label_ with the text "**Product details"**.
- At least one _image_ of the product.
- The product _name_.
- An _input_ field with a numeric _type_ for the _quantity_ of the product and its label "**Quantity"**.
- The product _price_ and its label "**Price"**.
- The _total_ by multiplying the _quantity_ by the product _price._ And its label "**Total"**.
- A _button_ without functionality with the text "**Remove"**.
  1. The summary section with the following elements:
     1. A _heading_ with the text "**Summary"**.
     1. The _total items_ in the cart and its label "**Items**".
     1. The _total cost_ of the items in the cart and its label "**Total cost**".
     1. A _button_ without functionality with the text "**Checkout"**.

1. Create the **Login** module and design your _UI_. You can base it on the layout proposed in this [demo](https://redux-shopping-cart-gules.vercel.app/login), or if you want, implement any other design, but include the following elements:
   1. A _heading_ with the text "**Welcome to the WizeStore!**".
   1. An _input_ field with a text _type_ for the username and its label "**Username**".
   1. An _input_ field with a password _type_ and its label "**Password**".
   1. A _button_ with the text "**Login".**
1. On the **Login** module, authenticate your user using the **loginApi** function located on _src/utils/api.js_. If the users are not authenticated, redirect them to the **Login** module.
1. Deploy your app on **Netlify**, **Firebase**, **Heroku**, **GitHub Pages**, or any other hosting service you prefer.
1. When you meet all _AC_ of this second deliverable, fill out this [form](https://docs.google.com/forms/d/e/1FAIpQLSeXxiqrN2BjLTVF79xI6OdCedGgaw_6pxWOrNEoxDkEaExEWA/viewform) and add the _URL_ of your _PR_ and the _URL_ of your deployment.

#### Acceptance Criteria

The following is the list of _evaluation criteria_ for your second deliverable:

| **Acceptance criteria** | **Description**                                                                                                                                                                                                                                                                                                                                                                                                    | **Points for completed** |
| :---------------------- | :----------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- | :----------------------- |
| 1                       | Your **Cart** module reads products correctly from this [mock](http://public/data/products.json) file.                                                                                                                                                                                                                                                                                                             | 10                       |
| 2                       | Your **Cart** module displays your _CSS styles_ correctly.                                                                                                                                                                                                                                                                                                                                                         | 10                       |
| 3                       | <p>For each product, the following elements render correctly:</p><p>A. One _image_ of the product.</p><p>B. The product _name_ and its _label_ "**Product details"**.</p><p>C. The _quantity input_ and its label "**Quantity"**.</p><p>D. The product _price_ and its _label_ "**Price"**.</p><p>E. The _total_ amount and its _label_ "**Total"**.</p><p>F. The "**Remove**" _button_ without functionality.</p> | 15                       |
| 4                       | The "**Quantity"** _input_ only allows positive numbers and affects the \*total*** cost of the product, the total *items\***,** and the _total cost_ in the "**Summary"\*\* section.                                                                                                                                                                                                                               | 10                       |
| 5                       | <p>For the "**Summary"** section, the following elements render correctly:</p><p>A. The _heading_ with the text "**Summary".**</p><p>B. The _total items_ in the cart and its label "**Items"**.</p><p>C. The _total cost_ of the items in the cart and its label "**Total cost"**.</p><p>D. The "**Checkout"** _button_ without functionality.</p>                                                                | 15                       |
| 6                       | Your **Login** module displays your _CSS styles_ correctly.                                                                                                                                                                                                                                                                                                                                                        | 10                       |
| 7                       | <p>Your **Login** module render correctly the following elements:</p><p>A. The _heading_ with the text "**Welcome to the WizeStore!**".</p><p>B. The _username input_ and its label "**Username**".</p><p>C. The _user password input_ and its label "**Password**"..</p><p>D. The "**Login"** _button_.</p>                                                                                                       | 15                       |
| 8                       | Your **Products** and **Cart** modules redirect to the **Login** module if the user is not authenticated.                                                                                                                                                                                                                                                                                                          | 15                       |

### Third and last delivery

In this final assignment, you will fetch the **API** and add **Redux Toolkit** to manage the state of your application.

Stay tuned on [**Slack**](https://wizelineacademy.slack.com/archives/C03KCQ0CPDM) because we will send you your **API key** on Friday, July 8th, 2022, so you will be allowed access to the [API](https://wizeline-academy-react-redux-api.netlify.app/).

#### Requirements

1. Create a new branch with the name "_feat/deliverable3_" derived from "_main_" on your forked repository.
1. Add **Redux Toolkit** to your project to simplify your _store_ setup, your _reducers_, and your _update logic_.
1. On the **Products** module, instead of reading from the **mock file**, now use createAsyncThunk and your _API Key to_ fetch data asynchronously* from the */products* endpoint of this [*API\*](https://62ace26a720b29256841ed36--cheery-quokka-c3476d.netlify.app/#/).
1. Save products and quantities in the **Redux** _store_ when the user clicks on the "**Add to cart**" buttons in the **Products** module.
1. Read those products and quantities from the **Redux** _store_ and allow updates and deletes when the user interacts with the "**Quantity"** _input_ and the "**Remove"** _button_ in the **Cart** module.
1. Allow the user to click the "**Checkout**" button only if there are items in the cart, and when that happens, use createAsyncThunk and your _API Key_ to post an order using the _/orders_ endpoint of this [API](https://62ace26a720b29256841ed36--cheery-quokka-c3476d.netlify.app/#/default/post_orders). Show the API response, the error if something goes wrong, or the "**order**"\* and "**message"** if the post is successful.
1. Deploy your app on **Netlify**, **Firebase**, **Heroku**, **GitHub Pages**, or any other hosting service you prefer.
1. When you meet all _AC_ of this third deliverable, fill out this [form](https://docs.google.com/forms/d/e/1FAIpQLSeXxiqrN2BjLTVF79xI6OdCedGgaw_6pxWOrNEoxDkEaExEWA/viewform) and add the _URL_ of your _PR_ and the _URL_ of your deployment.

#### Acceptance Criteria

The following is the list of _evaluation criteria_ for your third deliverable:

| **Acceptance criteria** | **Description**                                                                                                                                       | **Points for completed** |
| :---------------------- | :---------------------------------------------------------------------------------------------------------------------------------------------------- | :----------------------- |
| 1                       | Your **Products** module fetches the [API](https://62ace26a720b29256841ed36--cheery-quokka-c3476d.netlify.app/#/)                                     | 15                       |
| 2                       | Your project uses **Redux Toolkit** for its global state management.                                                                                  | 25                       |
| 3                       | On the **Products** module, the **"Add to cart"** _buttons_ allow adding products to the **Cart** module.                                             | 15                       |
| 4                       | On the **Cart** module, the "**Quantity"** _input_ updates the **Redux** _store_ and affects the totals of that product and the "**Summary**" totals. | 15                       |
| 5                       | On the **Cart** module, the "**Remove"** _buttons_ allow removing products from the **Cart** module and affect the "**Summary"** totals.              | 15                       |
| 6                       | On the **Cart** module, the "**Checkout"** _button_ displays the _API_ response on another page if there are items in the cart.                       | 15                       |

### Bonus

The bonus is a plus that helps us know you better and increments your final score. Consider the following:

| **Bonus** | **Description**                                                                                                         | **Points for completed** |
| :-------- | :---------------------------------------------------------------------------------------------------------------------- | :----------------------- |
| 1         | Use unit testing to validate your components using **Jest**, **React Testing Library**, and/or **Mock Service Worker**. | 10                       |
| 2         | Utilize third-party authentication providers for your **Login** module like **Auth0**.                                  | 10                       |
| 3         | Add a search bar functionality to the **Products** module.                                                              | 10                       |
| 4         | Add products to the **Favorites** module.                                                                               | 10                       |
