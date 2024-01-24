# Bestselling Books App

Welcome to the Bestselling Books App! 📚 This application utilizes the New York Times Books API to showcase the latest bestselling books. Explore both the latest releases and delve into an extensive all-time database.

## Screenshots
<p align="center">
  <img src="https://github.com/YassineRaboudi007/MobileBookApp/assets/93160741/feaa08ec-ead8-42fc-844b-680c6ded63e9" alt="Welcome Fragment" width="300">
  <img src="https://github.com/YassineRaboudi007/MobileBookApp/assets/93160741/c0da3ffe-d518-4167-9604-836cfa197bc6" alt="Book List Fragment" width="300">
</p>

## Welcome Section
Begin your journey with a warm welcome and easily navigate to the BookListFragment. Fetch category data via API and pass it to the fragment using a ViewModel LiveData. When the LiveData updates, execute another API query for the bestselling books, displayed in a RecyclerView.
<p align="center">
  <img src="https://github.com/YassineRaboudi007/MobileBookApp/assets/93160741/43b9012a-a03c-4197-a6ce-8336d713af52" alt="Welcome Fragment" width="300">
</p>

Click on any book to view details and make a purchase through the provided link.

<p align="center">
  <img src="https://github.com/YassineRaboudi007/MobileBookApp/assets/93160741/e87fa9db-c16b-4f4d-afea-b82b360c5d21" alt="Welcome Fragment" width="300">
</p>

## Search Section
Use the DatePicker to select date values and retrieve data from the API. Explore books categorized by date in a nested RecyclerView. Click on a book to view details.

<p align="center">
  <img src="https://github.com/YassineRaboudi007/MobileBookApp/assets/93160741/db859fcd-842d-41c3-a197-4a41d9ed9430" alt="Welcome Fragment" width="300">
</p>
## Error Handling
Experience seamless error handling. If the connection is lost, the app switches to an error fragment, returning to the previous state when the connection is restored.

<p align="center">
  <img src="https://github.com/YassineRaboudi007/MobileBookApp/assets/93160741/2a33b909-6be6-4dc6-8af2-da03dc198c05" alt="Welcome Fragment" width="300">
</p>
## Technology Highlights

### ViewModel
Implementing the Android Architecture Components ViewModel ensures efficient management and persistence of UI-related data. Handle data lifecycle changes and ensure data consistency between UI components.

### Adapters
Employing Adapters enhances the RecyclerView implementation, efficiently binding data to the user interface for smooth scrolling and optimized performance.

Feel free to explore the app, discover new books, and dive into the world of literature with our Bestselling Books App! 📖
