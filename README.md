# Embedded-payment-demo

<a href="https://www.frontstream.com/?itc=2" id="hs-link-module_1550769146607472_hs_logo_widget" style="border-width:0px;border:0px;">
<img src="https://www.frontstream.com/hubfs/Logos/fs-logo.svg" width="400">
</a>

This repository contains a full stack example of how to integrate Frontstream's Embedded Payment Form into an application using separate frontend and backend services.
It includes:

 **Frontend: SampleEpfApp** 
 An Angular 19 application
 - Select payment line items
 - Initiate the EPF form in a modal
 - Show results of the transaction
 
 **Backend: SamplePaymentApi**: 
 A .NET web API using C#
 - Securely start a payment session

## Frontend - Angular

### Quick Start

To get started with the Angular frontend:

```bash
# Clone the repository
git clone https://github.com/FS-Panorama/Embedded-payment-demo.git
cd Embedded-payment-demo/SampleEpfApp

# Install dependencies and start the development server
npm install
npm start
```

Visit [http://localhost:4200](http://localhost:4200) in your browser.

---

## Backend - .NET Web API

### Quick Start

To get started with the backend you can use eiter _Visual Studio_ or _VS Code_.

**Visual Studio** - the project was built with Visual Studio 2022 and contains a solution file
```bash
# Open the solution project from visual studio
Embedded-payment-demo/SamplePaymentApi

# Run the web API in IIS Express
F5 
```

**VS Code** - the project can also be run using VS Code
```bash
# Start Visual Code

# Its recommended to load these extensions:
```

[.NET Install Tool — Visual Studio Marketplace](https://marketplace.visualstudio.com/items?itemName=ms-dotnettools.vscode-dotnet-runtime)

[C# — Visual Studio Marketplace](https://marketplace.visualstudio.com/items?itemName=ms-dotnettools.csharp)

[C# Dev Kit — Visual Studio Marketplace](https://marketplace.visualstudio.com/items?itemName=ms-dotnettools.csdevkit)

```bash
# Open the project folder
Embedded-payment-demo/SamplePaymentApi

# open ‘Program.cs’. Make sure that file is open. 
Open Program.cs

# At the top menu start the API
Run > Start Debugging.

```
<img src="https://github.com/user-attachments/assets/3c351cfb-795b-45b0-a6c1-87c994bc3e96" width="800">

## To use the application


```sh
# Place the URL of the running Sample API in the appropriate textbox
-for IIS Express this will probabably be https://localhost:44316
-for VS Code it might be https://localhost:5069
```
<img src="https://github.com/user-attachments/assets/241550d2-0cd3-4618-aeac-1dbd4973ff17" width="400">


```bash
# Create your line items and select Checkout
```
<img src="https://github.com/user-attachments/assets/8ba1c064-37ee-4c66-8ac8-9ad95a117a81" width="800">

```bash
# The modal should pop up with your form
```
<img src="https://github.com/user-attachments/assets/2c6293cd-a36a-41f0-93f0-4410bd08be08" width="400">


```sh
# You may enter a test card number for demo purposes:
Card: 5454545454545454 CVV: 999
Exp Date can be anything
```
<img src="https://github.com/user-attachments/assets/a3b6e1f7-e426-4703-a4bb-ce6ac916d6ec" width="400">

```bash
# View the results on success
```
<img src="https://github.com/user-attachments/assets/91203f94-0245-40fe-9faa-f5f43de42bf1" width="800">


## Documentation

For step-by-step tutorials and more information:

- [https://developers.frontstream.com/introducing-our-embedded-form/how-to-implement](https://developers.frontstream.com/introducing-our-embedded-form/how-to-implement)
