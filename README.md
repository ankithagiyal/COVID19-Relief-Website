# COVID-19 Relief Website

A multi-page front-end website built during the COVID-19 pandemic. It brings
together an essentials shop, a donation page, state-wise case data,
government orders and basic safety guidance in one place.

## Overview
I built this during the pandemic to strengthen my front-end skills. I wanted
a project that felt relevant to what was happening at the time, so I designed
a relief site and used it to practise page layout, responsive design and
interactive features like a shopping cart.

It is a static front-end project, so there is no backend or real payment
processing.

## Features
- **Essentials shop:** AngularJS shopping cart with add/remove, quantity
  controls capped by available stock, and a running total in ₹
- **Checkout:** billing, shipping and payment form (UI only)
- **Donations:** one-time or monthly donation options, plus sections for
  donating supplies, food or money
- **State-wise data:** table of total and discharged cases by state/UT
  (static snapshot from 2020)
- **Government orders:** list of official COVID-19 orders and advisories
  with links
- **Updates:** news-style page on the situation in Delhi
- **Basic precautions:** prevention guidance for protecting yourself and others
- Responsive layout built with Bootstrap and CSS grid

## Tech Stack
- **Languages:** HTML5, CSS3, JavaScript
- **Frameworks/Libraries:** Bootstrap 4, AngularJS, jQuery, Font Awesome
- **Tools:** Git, GitHub

## Getting Started
1. Clone the repository
   `git clone https://github.com/ankithagiyal/COVID.git`
2. Open `index.html` in your browser

No installation or build step is needed. An internet connection is required
for the Bootstrap, Font Awesome, AngularJS and Google Fonts CDNs.

## Pages
| Page | Purpose |
|------|---------|
| `index.html` | Landing page |
| `shoppingindex.html` | Essentials shop and cart |
| `checkout.html` | Checkout form |
| `donationindex.html` | Donations |
| `state.html` | State-wise case data |
| `orders.html` | Government orders and advisories |
| `emrg.html` | Situation updates |
| `basicprec.html` | Basic precautions |

## Limitations
- Product data and case numbers are hard-coded, not pulled from an API
- The checkout and donation forms are front-end only; no payments are processed

## What I Learned
- Building an interactive shopping cart with AngularJS data binding,
  including stock limits and live total calculation
- Structuring and linking a multi-page site with consistent navigation
- Creating responsive layouts with Bootstrap and CSS grid
- Designing forms for a checkout and donation flow

## Future Improvements
- Connect the shop and donation forms to a backend and a payment gateway
- Pull live case data from a public API instead of a static table
- Add form validation
