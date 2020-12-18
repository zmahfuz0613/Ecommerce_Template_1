#  <h1 align="center">Ecommerce_Template_1</h1>


# Overview
We will create an ecommerce template a homepage including 3 different screens: <br/>
Home <br/> 
Products <br/>
Login/signup form <br/>
Checkout form <br/>

The features include full CRUD capabilities for the Signup form which will be sent to our backend server and will become accessible in the "Customer info page" that we will be adding.

# Team Expectations

[Team Expectations] (https://docs.google.com/document/d/1EN9KC4IYI6Q3u1mnXHW-r_XyYMNbEh3gODD6IgHRGz4/edit?usp=sharing)

# Schema

```
const Customer = new Schema(
  {
    firstName: { type: String, required: true },
    lastName: { type: String, required: true },
    email: { type: String, required: true },
    phone: { type: String, required: true },
    address: { type: String, required: true },
    secondAddress: { type: String, required: true },
    city: { type: String, required: true },
    state: { type: String, required: true },
    zip: { type: String, required: true }
  },
  { timestamps: true }
)
```
