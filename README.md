# Radon

A full-stack e-commerce website built using Next.js, Nextauth, Redux, Tailwind CSS, MongoDB

## Features

- Responsive
- Real Time and Dynamic
- Progressive Web App (PWA)
- Payment Gateway integration
- Admin Dashboard with functionalities like adding products, deleting a product, updating products, adding a category, viewing users registered, updating order status, and canceling orders
- State management using Redux
- Google authentication
- Track order status real time
- Cancel orders


## Run Locally

Clone the project

```bash
  git clone https://github.com/54nd339/Radon.git
```

Go to the project directory

```bash
  cd Radon
```

Install dependencies (Node versions: 16)

```bash
  yarn
```

Start the server

```bash
  npm run dev
```

Admin Access 

```
 To gain admin access, you need to add your email ID to the admin collection in MongoDB. 
 After adding it, try logging in with the same email ID, and you should see the dashboard option.  
```

## Stripe Payment Gateway

Test Stripe payment gateway with these card details.

```
  BRAND - VISA
  CARD NUMBER - 4242424242424242
  CVC - Any 3 digits
  DATE - Any future date
```