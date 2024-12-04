# SQL_Project_Music_Store_Analysis
SQL project to analyze online music store data

🎵 Music Store Data Analysis Project using SQL

📖 Project Description

The Music Store Data Analysis Project is designed to analyze the data of a music store to gain insights into customer behavior, track sales trends, and optimize inventory. Using SQL, the project dives deep into a well-structured relational database containing information about customers, artists, tracks, invoices, and employees.

This analysis helps stakeholders make data-driven decisions to improve sales, enhance customer satisfaction, and streamline inventory management.

🗃️ Database Schema

The database consists of the following key tables:

Artist: Stores details of music artists.
Columns: ArtistId, Name
Album: Contains albums associated with artists.
Columns: AlbumId, Title, ArtistId
Track: Includes individual tracks with metadata like genre, media type, and pricing.
Columns: TrackId, Name, AlbumId, MediaTypeId, GenreId, Composer, Milliseconds, Bytes, UnitPrice
Genre: Categorizes tracks into genres.
Columns: GenreId, Name
MediaType: Specifies the media type for each track.
Columns: MediaTypeId, Name
Customer: Stores customer details for billing and communication.
Columns: CustomerId, FirstName, LastName, Company, Address, City, State, Country, PostalCode, Phone, Email, SupportRepId
Invoice: Tracks sales transactions.
Columns: InvoiceId, CustomerId, InvoiceDate, BillingAddress, BillingCity, BillingState, BillingCountry, BillingPostalCode, Total
InvoiceLine: Line items for each invoice.
Columns: InvoiceLineId, InvoiceId, TrackId, UnitPrice, Quantity
Employee: Contains details about employees, including support reps for customers.
Columns: EmployeeId, LastName, FirstName, Title, ReportsTo, BirthDate, HireDate, Address, City, State, Country, PostalCode, Phone, Fax, Email
Playlist: Represents playlists created by customers.
Columns: PlaylistId, Name
PlaylistTrack: Links tracks to playlists.
Columns: PlaylistId, TrackId

🎯 Project Objectives

Identify Popular Genres, Artists, and Albums: Analyze sales data to find top-performing music categories.
Understand Customer Behavior: Assess customer purchase trends and preferences.
Track Business Performance: Examine sales trends over time to evaluate the store’s growth.
Optimize Inventory: Identify tracks or albums with low or high demand.
Provide Business Recommendations: Generate actionable insights for decision-making.



## Database and Tools
* Postgre SQL
* PgAdmin4

Schema- Music Store Database  
![MusicDatabaseSchema](https://user-images.githubusercontent.com/112153548/213707717-bfc9f479-52d9-407b-99e1-e94db7ae10a3.png)
