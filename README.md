# Pedal Pal 

Project Repo at [PedalPal](https://github.com/Pedal-Pal-CS253)

## Introduction
This application is made as a course project of the course CS253: Software Development and Operations, Winter 2024, under the guidance of [Prof. Indranil Saha](https://www.cse.iitk.ac.in/users/isaha/). 

PedalPal aims to enhance the cycling experience for IITK students through a convenient and efficient bicycle-sharing system on campus. It allows easy bicycle access to the campus residents via strategically placed cycle-hubs install across the campus. The salient features of our application are - 
- Users can choose and ride a cycle instantly by scanning the QR code present on it
- Users can book a cycle to be used in the future, by paying a nominal cost to reserve the cycle. (This feature is only allowed for subscribed members)
- Subscribed users are provided with an in-app wallet to facilitate hassle-free payments
- Users can view the details of all the hubs present in the campus on a map
- Users can view their ride history and analytics like total time used, etc.

Intended audience of the application - IITK campus community and visitors

## Deployment
To download and use our application, please install the `pedal-pal-v1.1.apk` file given [here](https://drive.google.com/drive/folders/1NgxvJv4w105I9mXTnCMT2q3f57FX7lac?usp=sharing). Currently the application is available on the Android platform only. The backend of our application is hosted on the [Vercel platform](vercel.com). The administrator view can be accessed [here](https://pedal-pal-backend.vercel.app/admin/).

The QR codes corresponding to various locks are also provided in the same Google Drive link. Initial database contains around 30 locks which have cycles attached to them and 10 which are free. To see which lock is what, please check it in the admin view. The credentials are given in the user manual. 

To make payments, please use the RazorPay dummy card details as given [here](https://razorpay.com/docs/payments/payments/test-card-details#test-card-for-indian-payments). Please do not use real money as we do not guarantee that it can be returned back.

## Development 
To set up the development environment locally, please follow the instructions given in the individual repositories, [pedal-pal-backend](https://github.com/Pedal-Pal-CS253/pedal-pal-backend/) and [pedal-pal-frontend](https://github.com/Pedal-Pal-CS253/pedal-pal-frontend/).
