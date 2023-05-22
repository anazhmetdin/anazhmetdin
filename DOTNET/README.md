# .NET Projects

- [.NET Projects](#net-projects)
  - [ASP.NET Core MVC](#aspnet-core-mvc)
  - [ASP.NET Core Web API](#aspnet-core-web-api)
  - [WPF .NET](#wpf-net)

## ASP.NET Core MVC

[Food Delivery Web Application](https://github.com/anazhmetdin/FoodDeliveryWebApp)

In this application, my primary responsibility was to develop the seller interface. As part of this role, I successfully integrated ASP.NET Core SignalR to enable real-time push notifications for live orders.

![Live Notifications](./Images/SignalR_Notifications.gif)

[HQ Video with audio](https://drive.google.com/file/d/1hUC08H2q4nuRkJKIiHdhKiZCkoNtXHI8/view)

Order items could be expanded:

![Order Items](./Images/order_items.png)

Additionally, I utilized Chart.js to create visually appealing and informative graphs, providing sellers with valuable insights into their performance over time.

![Seller Stats 1](./Images/seller_stats1.png)

![Seller Stats 1](./Images/seller_stats2.png)

Moreover, I designed and implemented a user-friendly interface for efficient management of a seller's items, incorporating quick and intuitive controls like filters, sales application, and availability modification. These controls are used alongside a fixed header at the top with anchor links to all available categories.

![Menu Control](./Images/Menu_controls.gif)

[HQ Video](https://drive.google.com/file/d/1mk3kSelXGrkSJf0CIvZm77aySx6UHy0q/view)

Finally, I added a section in the customer homepage to display trending sellers (those with the highest order rates in the last few days). This section is updated regularly using a timed hosted service that runs in the background.

![Trending Sellers](./Images/trending_sellers.png)

## ASP.NET Core Web API

[Seetour API](https://github.com/anazhmetdin/SeetourAPI)
[Seetour UI](https://github.com/eman120/SeetourUI)

In the "Seetour" project, I was the scrum master who managed our sprints and contributed to various aspects, including:

- Designed the database schema for the project and utilized a Python script to populate it with realistic mock data.
- Managed the integration of external services, such as the Google Maps API and Azure Storage account, ensuring the secure handling of associated secrets.
- Implemented policy-based authorization throughout the ASP.NET Core Web API, ensuring access control and security measures were enforced consistently across the application.
- Developed an interceptor in Angular to seamlessly handle the login JWT token, facilitating secure authentication and authorization processes.
- Designed and developed the login page in Angular, providing an intuitive and user-friendly interface for users to authenticate and access the system.

![Login Page](./Images/seetour_login.png)

- Implemented the trending section, which displays the top liked, wishlisted, and booked tours based on user activity within the past few days. This feature enhances the user experience by showcasing popular and trending tours. This list is updated daily on the api server using a timed hosted service that I created also.

![Trending Section](./Images/seetour_trending.png)

- Created a comprehensive tours browser that allows users to search for specific tours using a query, as well as apply filters based on various criteria such as price, tour guide rating, category, date, location, and more. This functionality enables users to easily find tours that match their preferences.

![Tours Search](./Images/seetour_search.png)
![Tours Filter](./Images/seetour_filter.png)

- Integrated the ability to sort tours within the browser based on different properties, such as price, rating, or any other relevant attribute. Moreover, I implemented a customizable sorting feature that allows users to change the priority of sorting criteria, such as prioritizing price or rating first, based on their individual preferences.

![Tours Sorter](./Images/seetour_sort.png)

- All the previously mentioned browser features are reflected in the query parameters, so that the user can search the link with other people to sea the same exact result he got.
- Developed a favorites functionality that allows customers to add tour guides to their favorites list. This feature enables users to follow the upcoming tours of their preferred tour guides in a separate section, providing a personalized experience.

![Customer favorite tour guide](./Images/seetour_customer_TG_profile.png)
![Tours from favorite tour guides](./Images/seetour_customer_favorites.png)

- Created a centralized page where customers can manage their cart and booked tours. This page allows users to conveniently book tours from their cart, remove tours, cancel bookings, review completed tours, and view a list of their cancelled tours. This comprehensive tour management page simplifies the process for users to handle their tour reservations efficiently.

![Customer cart](./Images/seetour_customer_cart.png)
![Customer completed tours](./Images/seetour_customer_completed_tours.png)

- Customers can review their completed tours in the same page using a simple form where they can upload multiple photos from their trip. the can see the uploaded photos and add to them or remove some of them easily.

![Customer review completed tours](./Images/seetour_customer_review.png)

- Tour Guides can visit their own profiles to view their own upcoming and past tours plus all of the reviews they got from their customers.

![Tour Guide Profile](./Images/seetour_TG_profile.png)
![Tour Guide Profile Overview](./Images/seetour_TG_overview.png)

- Finally, I developed a part of the admin controls that enables controlling posting requests and tour guides' applicantions to be a partner with Seetour.

![Admin Posting Requests](./Images/seetour_admin_posts.png)
![Admin Form Posting Requests](./Images/seetour_admin_accept_posts.png)
![Admin Applicants](./Images/seetour_admin_applicants.png)

## WPF .NET

[Hotel Management](https://github.com/anazhmetdin/hotelmanagement)

This project was developed using EF Core with code-first approach. I designed a well-structured and normalized database that effectively stored guest information, room details, payment records, and more. To enhance the user experience, I developed a user interface using WPF, ensuring seamless navigation through the data. To achieve a cohesive and professional aesthetic, I implemented customized control styling consistently across the application.

- Login window
![Login](./Image/../Images/hotel/login.gif)

- Returning customers' data is loaded automatically using their SSN
![Customer Search](./Images/hotel/customer_search.gif)

- Available rooms are loaded dynamically using new reservation info and the existing reservations
![Select Reservation Room](./Images/hotel/select_rooms_dinamically.gif)

- Returning Customers' payment information is loaded when they pay for a new reservation
![Payment](./Images/hotel/payment.gif)

- All data could be searched using a single query
![Universal Search](./Images/hotel/search.gif)

- Reserved rooms and occupied rooms (checked in) could be viewed in one place.
![Rooms Availability](./Images/hotel/rooms.png)

- Active reservations are loaded dynamically in the main tab
![Active Reservations](./Images/hotel/old_reservations.gif)

- All reservations could be viewed in a doubly-bound grid view
![Grid View](./Images/hotel/grid.gif)

- Room service could also login to the application and view their to-do list
![Room service login](./Images/hotel/kitchen.gif)
