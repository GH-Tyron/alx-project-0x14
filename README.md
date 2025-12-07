# 🎬 MoviesDatabase API Documentation Summary

## 📘 API Overview
The **MoviesDatabase API** provides access to a large collection of movie- and TV-related data. It allows developers to retrieve details such as movie titles, cast information, genres, ratings, release dates, trailers, and images. The API is designed for building applications related to film discovery, entertainment dashboards, streaming guides, and more.  
It supports flexible search filters, pagination, and multiple query parameters for customizing results.

## 🧩 API Version
**Version:** v1  
(Refer to the MoviesDatabase API documentation for the most current version details.)

---

## 📡 Available Endpoints

### **1. `/titles`**
Retrieves a list of movies or TV shows with options for filtering by year, genre, rating, runtime, etc.

### **2. `/titles/{id}`**
Fetches full details for a specific movie or TV show using its unique ID.

### **3. `/titles/search`**
Searches for titles based on keywords (e.g., movie name, actor, director).

### **4. `/titles/{id}/cast`**
Returns cast and crew information for a specific movie or show.

### **5. `/titles/{id}/images`**
Provides images related to the title, such as posters, backdrops, and still images.

### **6. `/titles/genres`**
Lists all available movie and TV genres in the database.

---

## 🔄 Request and Response Format

### **📥 Request Format**
Most requests are made using standard HTTPS GET requests.  
Example request:

