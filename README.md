# 🎬 Movie Watchlist APEX App

A web application built to help you discover and keep track of movies you want to watch or have already seen.  
This project leverages the power of **Oracle Cloud Infrastructure (OCI)** and the **Oracle APEX low-code platform** to deliver a seamless user experience, with movie data provided by **The Movie Database (TMDB)**.

---

## 🚀 Live Demo

You can try out the live application here:

🔗 **URL:** [Movie Watchlist APEX App](https://g6ac2036f7cec2d-rvhr0npwczbbct5t.adb.ap-singapore-1.oraclecloudapps.com/ords/r/demo/movies-watchlist/home)  
👤 **Username:** `DEMO`  
🔒 **Password:** `SecretPassw0rd`

---

## 📸 Screenshots

### 🎞️ Movie Discovery Page
<img width="1920" height="947" alt="Image" src="https://github.com/user-attachments/assets/be08f18d-24b2-412f-977f-89d154c1072c" />
Users can search for movies and view popular or upcoming titles fetched directly from the **TMDB API**.

### 🧾 Personal Watchlist
<img width="1920" height="942" alt="Image" src="https://github.com/user-attachments/assets/e77e8c26-ca00-43d1-ad6a-4df6efbd9227" />
Once added, movies appear in a personal, sortable watchlist where users can track what they want to see.

---

## ✨ Key Features

- 🔍 **Browse & Search**: Dynamically search a vast library of movies from *The Movie Database* (TMDB).  
- 🎯 **Personal Watchlist**: Add and remove movies from your personalized list with a single click.  
- 🧠 **Data-Rich Interface**: View key details for each movie, including posters, release year, and ratings.  
- ⚙️ **Advanced Filtering**: Sort and filter your watchlist by title, decade, runtime, and more.

---

## 🛠️ Technology Stack

This application was built using a modern, cloud-based stack:

| Component | Technology |
|------------|-------------|
| ☁️ **Cloud Platform** | Oracle Cloud Infrastructure (OCI) |
| 🧩 **Application Framework** | Oracle APEX (low-code platform) |
| 🗄️ **Database** | Oracle Autonomous Database |
| 🎥 **External Data Source** | The Movie Database (TMDB) API |

---

## ⚙️ How It Works

1. The front-end interface is built and rendered by **Oracle APEX**.  
2. When a user searches for a movie, **APEX makes a REST API call** to the **TMDB API** to retrieve movie data.  
3. When a user adds a movie to their watchlist, its ID and associated data are **stored in the Oracle Database** on OCI.  
4. The **“My Watchlist”** page queries this local database to display the user’s curated list.

---

